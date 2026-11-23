# Changelog

All notable showcase and product-documentation updates for Kashida Paint Visualizer are recorded here.

## [1.5.0] - 2026-11-23

### Added
- Added the optional **Company Catalog** color source through integration with Kashida Color Library 2.7.0.
- Added selection of published and enabled company color groups.
- Added catalog color search by name, commercial code, and HEX value.
- Added pagination for large color groups.
- Added localized loading, empty, error, and retry states for catalog browsing.

### Improved
- Catalog colors use the visualizer's existing color-application workflow.
- Catalog colors are fetched only after a visitor selects a group; the integration does not download every group and color at once.
- Preserved the built-in visualizer palette as an independent fallback when Kashida Color Library is not installed, inactive, has no available groups, or its API is temporarily unavailable.
- Kept Kashida Paint Visualizer and Kashida Color Library as independent plugins; the visualizer remains usable without the catalog plugin.
- The integration reads only public catalog fields and does not save customer designs or customer-specific color selections.

### Compatibility and validation
- Updated the showcase documentation for version 1.5.0 in English and Arabic.
- The 1.5.0 integration was tested on a live WordPress website; the integration test checklist passed.
- Plugin Check for Kashida Paint Visualizer 1.5.0 reported: `Checks complete. No errors found.`

## [1.4.1]

- Improved the mobile user experience and responsive interface.
- Refined the user interface for clearer interaction across screen sizes.
- Inherited the active WordPress theme's font.
- Updated Before & After comparison to use a draggable divider directly on the image.
