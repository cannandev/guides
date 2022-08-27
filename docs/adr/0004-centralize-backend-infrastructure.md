# 4. Centralize backend infrastructure

Date: 2022-08-26

## Status

Accepted

## Context

Centralizing infrastructure/environment will reduce long-term maintenance costs

## Decision

Have one environment for the guides. One Jekyll framework, gems, local development workflow, CMS, USWDS version that all guides share. Build flexible HTML templates that separate content from code.

## Consequences

* Product owners and contributors can comfortably edit their _content_ without the intimidation of maintaining _code_.
* Eliminating redundant work drastically reduces billability and capability of engineering support.
* Reduces long term maintenance cost of dependency and security bots.
