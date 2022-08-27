# 5. Separate code from content in HTML templates

Date: 2022-08-26

## Status

Accepted

## Context

> "GitHub is very technical and 18F is the most by far GitHub using, it can be intimidating."

> " We should also be investing as an org in making those edits easy, straightforward and streamlined."

## Decision

Markdown content only includes formatted text and images. NO HTML. NO includes.
Use front matter, data yaml, config settings and environment variables.

## Consequences

By stopping the practice of hard coding text in HTML templates, product owners and contributors feel empowered to edit and add content without intimidation of code.
Risk: considerable "upfront work" to ensure templates provide guardrails without hindering content.
