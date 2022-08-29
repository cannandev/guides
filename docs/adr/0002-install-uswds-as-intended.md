# 2. Install USWDS as intended

Date: 2022-08-26

## Status

Proposed

## Context

USWDS gives specific instructions to developers to install, compile and customize a project as a Node package with Gulp as a taskrunner. https://designsystem.digital.gov/documentation/getting-started-for-developers/

## Decision

Follow USWDS instructions instead of starting with a USWDS Jekyll template.

## Consequences

Since these Jekyll templates are not maintained by USWDS (and some aren't maintained at all), they quickly become outdated. Installing USWDS the way it was intended allows us to change overhead frameworks (Jekyll, Node, Hugo, Gatsby, 11ty, whatever). Thus USWDS styles become easier to maintain and update. It will also set a good standard for partner projects.
