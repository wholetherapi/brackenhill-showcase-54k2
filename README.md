# Brackenhill Instrument Works - showcase site

This repository holds the public project pages for the Brackenhill
Instrument Works collective. Each project page lives under `projects/`
as a Markdown file with YAML front matter.

## Front matter keys

- `title`, `slug`, `year`, `summary`
- `maintainers`, `license`, `tags`
- `build_kit`: the kit code used in the shared build register
- `package_url`: optional link to the project's design package repository

Site content is rebuilt from the `projects/` directory on every push.
