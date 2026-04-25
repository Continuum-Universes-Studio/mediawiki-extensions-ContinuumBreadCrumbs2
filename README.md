## Continuum Fork Changes

ContinuumBreadCrumbs2 includes the following changes from the original BreadCrumbs2 extension:

- Renamed and namespaced the extension for the broader Continuum Universes ecosystem.
- Updated deprecated MediaWiki code for MediaWiki 1.45 compatibility.
- Updated runtime compatibility for PHP 8.4.
- Preserved the original Creative Commons Attribution 3.0 license.
- Preserved attribution for all original authors and prior contributors.
- Added integration with ContinuumForumEmotes, allowing forum emotes to be parsed inside breadcrumb output.
- Extended the breadcrumb category resolver with a secondary category condition for more specific breadcrumb selection.

When both configured categories match an article, the more specific breadcrumb rule is selected. When only one category matches, or neither category matches, ContinuumBreadCrumbs2 falls back to the original breadcrumb selection behavior.