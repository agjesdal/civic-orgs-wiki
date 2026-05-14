# Civic & Democracy Organizations Wiki

A navigable reference of organizations working in the civic and democracy
space — bridging political divides, deliberative civic technology, open
inquiry, healthy information ecosystems, and related fields.

The wiki is organized **from broad categories down to individual
organizations**. Each organization has its own page with a mission and notes;
each category page lists the organizations that belong to it. Organizations
may appear in more than one category.

## How it is structured

```
docs/
  index.md                  landing page, lists all categories
  organizations/            one file per organization (flat — this is storage)
  categories/               one file per category (curated lists that link to orgs)
  contributing.md           how to add or edit entries
mkdocs.yml                  site configuration and navigation
.github/workflows/          automatic site deployment
```

The key idea: **`organizations/` is just storage — every org is one file there.**
Categories are curated pages that link to those files. An organization's
category membership lives in the `Categories:` field inside its own file. This
keeps a single source of truth per organization while letting it appear in
multiple categories.

## Contributing

See [`docs/contributing.md`](docs/contributing.md) for the entry template and
step-by-step instructions, including how to contribute entirely through the
GitHub website without any local tools.

## Viewing the site

**Locally** (works while the repo is private):

```
pip install mkdocs-material
mkdocs serve
```

Then open the address it prints (usually `http://localhost:8000`).

**Published:** once the repository is made public and GitHub Pages is enabled
(Settings → Pages → Source: GitHub Actions), the site builds and publishes
automatically on every change to the `main` branch.

## Status

- 26 organizations
- 9 categories
- Generated 2026-05-14
