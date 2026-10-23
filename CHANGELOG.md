# 1.0.0
## 2026-10-23

1. [](#new)
    * Initial release: documentation layout for Quark 2
    * Documentation template (`docs.html.twig`) for pages named `docs.md` or using `template: docs`
    * Collapsible, recursive sidebar listing every page under the docs root, including pages hidden from the main navigation
    * "On this page" table of contents generated from `h2`, `h3` and `h4` headings on child pages
    * Sidebar remembers expanded sections for the browser session
    * Responsive layout: sidebar and table of contents stack below 850px
    * Admin options under **Documentation layout**: docs root route, include non-visible pages, table of contents, sidebar memory and sidebar width
    * Sample documentation pages in `_demo/pages`
    * Documentation styles live in `css/docs.css`, leaving `css/custom.css` free for your own CSS
