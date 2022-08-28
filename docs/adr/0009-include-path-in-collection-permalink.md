# 9. Include path in collection permalink

Date: 2022-08-27

## Status

Proposed

Supercedes [8. Set guides collection_dir](0008-set-guides-collection-dir.md)

## Context

By setting the collections permalink to `/:collection/:name`, it doesn't follow the full path of the document. Using `/:collection/:name` doesn't give us the correct generated html file. So the following document:
`/guides/_content/our-style/inclusive-language.md`

Should be generated as:
`/content/our-style/inclusive-language/index.html`

With the final URL:
`<domain>/our-style/inclusive-language/`

## Decision

Set the permalink on pages in a subdirectory.

## Consequences

The `_site` file generated and the final URL will be correct. RISK: Users might not know what the correct path is when creating a new page.
