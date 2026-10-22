# 1.0.0
## 2026-10-21

1. [](#new)
    * Documentation template (`docs.html.twig`) for pages named `docs.md` or using `template: docs`
    * Collapsible, recursive sidebar listing every page under the docs root
    * "On this page" table of contents generated from `h2`, `h3` and `h4` headings on child pages
    * Sidebar remembers expanded sections for the browser session
    * Admin options under **Documentation layout**: docs root route, include non-visible pages, table of contents, sidebar memory and sidebar width
2. [](#improved)
    * Sidebar can list pages that are hidden from the main navigation
    * Responsive layout: sidebar and table of contents stack below 850px
    * Sidebar width is controlled by the `--docs-sidebar-width` CSS variable
3. [](#bugfix)
    * Fixed HTML-escaped quotes (`&#039;`) in the default theme configuration
