---
title: Troubleshooting
visible: false
---

# Troubleshooting

## Pages do not show the sidebar

Check that the file is named `docs.md` or has `template: docs` in its front matter, then clear the cache:

```bash
bin/grav clearcache
```

## The sidebar is empty

Check that **Documentation root route** matches the route of your docs landing page. The route is the folder name without its number prefix, so `05.docs` becomes `/docs`.

## Some pages are missing from the sidebar

Make sure **Include non-visible pages in sidebar** is enabled, and that the pages are published.

## There is no "On this page" list

The list only appears on child pages, not on the landing page or main topics, and only when the page has `h2`, `h3` or `h4` headings.

## The theme will not install

The theme needs the Quark 2 parent theme. Install it first with `bin/gpm install quark2`.
