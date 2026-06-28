# Changelog

## [1.2.5] - 2026-06-29

### Fixed

- Fixed an issue where being over a tab limit could close tabs you already had open. Tab Limiter Plus now only stops new tabs from opening past a limit — it never closes tabs that are already open. This was most noticeable with the per-domain limit on single-page sites such as x.com, where everyday browsing could trim open tabs down to the limit.

### Added

- Added WebP screenshots for browser store listings.

### Improved

- Made tab counting more reliable across multiple browser windows.
- Refreshed store assets and screenshots.
- Updated privacy and changelog documentation.
- Tidied project files and asset locations so Chrome and Firefox releases are easier to maintain.

## [1.2.4] - 2026-03-04

### Improved

- Renamed the extension to Tab Limiter Plus across the extension, package, and store materials.
- Updated the extension description to mention per-window, per-domain, and total tab limits.

## [1.2.3] - 2026-03-03

### Improved

- Finalized the 1.2.x domain-limit update and versioned the Chrome and Firefox manifests.

## [1.2.2] - 2026-02-24

### Added

- Added favicons to domain rows to make the domain list easier to scan.
- Added an option to show favicons in color or in a quieter grayscale style.

### Improved

- Refined the domain-limit UI and simplified favicon handling for better reliability across different websites.

## [1.2.0] - 2026-02-24

### Added

- Added per-domain tab limits, so individual sites can have their own limits.
- Added a domain overview that shows which sites are using the most tabs.

### Improved

- Improved the domain tab-count display so busy domains are easier to spot.

## [1.1.2] - 2026-02-24

### Improved

- Improved the live progress cards so tab counts refresh more consistently.

## [1.1.1] - 2026-02-24

### Improved

- Fixed limit controls so changes sync more reliably across browser windows.

### Behind the scenes

- Reworked the extension into a shared Chrome and Firefox source layout.
- Added build scripts for creating browser-specific development folders and store packages.

## [1.1] - 2025-09-09

### Added

- Added a main settings view that shows open tabs and remaining tabs at a glance.
- Added progress bars that change color as limits get closer.
- Added a settings toggle to keep everyday tab counts separate from less-used options.

### Improved

- Redesigned the options page with clearer cards, labels, icons, and spacing.
- Improved progress labels so limits are easier to understand quickly.
- Updated browser store screenshots, promo tiles, and feature descriptions.
- Removed temporary test pages and cleaned up the extension package.

## [1.0.0] - 2025-08-24

### Added

- Modernized the extension for current browsers.
- Added a redesigned options experience.
- Added clearer alerts when tab limits are reached.
- Added store listing information and a privacy policy.

### Improved

- Migrated the extension to Manifest V3.
- Improved badge updates so the remaining-tab count stays more accurate.
- Refreshed icons, screenshots, naming, credits, and documentation.
- Reorganized the project into a cleaner extension folder structure.

## [0.4.0] - 2025-08-18

### Improved

- Updated screenshots and manifest details during the modernization work.
- Prepared the extension for the larger 1.0 redesign and Manifest V3 release.