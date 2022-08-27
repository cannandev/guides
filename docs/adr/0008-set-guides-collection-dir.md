# 8. Set guides collection_dir

Date: 2022-08-27

## Status

Accepted

## Context

Need a way to control urls per guide.

## Decision

Change `pages` directory to `guides`. Set as `collections_dir` in config.yml, per <https://jekyllrb.com/docs/collections/>.

Add an underscore to each guide subdirectory, so Jekyll recognizes them as collections. For example, change `accessbility` to `_accessibility`.

Set the permalink on all collections to `/:collection/:name`. This will create the collections as directories.

## Consequences

This will allow us to easily control URL and slug names from one config file instead of each Markdown file. When a user creates a new file, they don't have to worry about adding a permalink, although we can still give users the option of overriding by adding a permalink on the Markdown file.

The resulting path for *checklist.md* will be `/accessibility/checklist/`. Having a consistent path for all pages will allow us to use redirects and custom domains.

We'll keep the old permalink by renaming them as `alias` in front-matter.

The collection to which document belongs will be available in templates as `page.collection`. See <https://jekyllrb.com/docs/variables/#page-variables>.
