# 10. Shared components and styles go in a base theme

Date: 2022-08-28

## Status

Proposed

## Context

Product owners need to be assured that their proprietary content can have its own "look". However, to keep costs low, as much code should be shared as possible. In other multisite builders, this concept is called a "base theme".

## Decision

Shared HTML components and styles will be included in a *base theme*. Any components or styles unique to a guide will be in a *child theme*.

## Consequences

It will be easier to maintain shared HTML components and styles. Update once, update everywhere. Product owners will still have options to create their unique style.
