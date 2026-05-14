# How to Contribute

This wiki is designed to be easy to add to. Every organization is a single
Markdown file; categories are curated list pages that link to those files.

## The model

- **Every organization is one file** in `docs/organizations/`, named with a
  lowercase, hyphenated slug (e.g. `braver-angels.md`).
- **Categories do not nest organizations.** An organization's category
  membership is recorded in the `Categories:` field inside its own file, and
  the relevant category page links to it.
- An organization can belong to **more than one category** — just list
  each one in the `Categories:` field and add a link from each category page.

## Adding an organization

1. Create a new file in `docs/organizations/` named `your-org-slug.md`.
2. Copy the template below and fill it in.
3. Add a link to the organization from each relevant category page in
   `docs/categories/`.
4. Commit your change (or open a pull request — see below).

## Entry template

```markdown
# Organization Name

**Domain:** example.org
**Categories:** [Category One](../categories/category-one.md)
**Date added:** YYYY-MM-DD

## Mission

One or two neutral, present-tense sentences describing what the organization
does.

## Notes

Anything else worth flagging — funding, lineage, caveats, relationships
to other organizations on the list.
```

If an organization belongs to multiple categories, separate the links with a
semicolon:

```markdown
**Categories:** [Category One](../categories/category-one.md); [Category Two](../categories/category-two.md)
```

## Editing through GitHub (no tools required)

If you are not set up with Git locally, you can still contribute entirely
through the GitHub website:

1. Navigate to the file you want to change (or use **Add file → Create new
   file** to add one).
2. Click the **pencil icon** to edit.
3. Make your change.
4. Scroll down, write a short description of the change, and choose
   **"Create a new branch ... and start a pull request."**
5. A maintainer will review and merge it.

## Style notes

- **Missions** are neutral and factual — describe what the organization
  does, not whether it is good or relevant.
- **Notes** is the place for context, caveats, and judgment.
- Keep both concise. The wiki is a quick reference, not a profile database.
- When in doubt about which category something belongs to, add it to the most
  obvious one and leave a note — a maintainer can refine it.
