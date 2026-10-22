---
title: Markdown features
visible: false
---

# Markdown features

The "On this page" list on the right is built from the `h2`, `h3` and `h4` headings of this page.

## Headings

Use `##` for sections, `###` for subsections and `####` for details. Each level is indented in the table of contents.

### A subsection

Subsections appear under their section.

#### A detail

Details are indented one more step.

## Text formatting

You can write **bold**, *italic*, `inline code` and [links](/docs). A short note works well as a blockquote:

> Documentation is easier to keep up to date when it lives next to the code.

## Lists

- Unordered lists group related points.
- They can be as long as you need.

1. Ordered lists describe steps.
2. The numbers are generated for you.

## Code blocks

```bash
bin/grav clearcache
```

```yaml
docs:
  root: /docs
```

## Tables

| Feature | Where it comes from |
| --- | --- |
| Sidebar | The page tree under the docs root |
| On this page | The headings in the article |
| Light and dark mode | Quark 2 |
