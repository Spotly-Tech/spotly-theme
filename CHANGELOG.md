# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2024-12-09
**This update addresses and fixed several color inconsistencies.**
### Changed

-	Changed colors of:
	-	Selection of text inside IDE from `#EEFF0064` to `#2859c248`.
	-	Terminal cursor background (text color inside cursor) from `#EDFF00` to `#120F12`.
	-	Terminal cursor foreground (cursor body color) from `#120f12` to `#EDFF00`.
	-	Selection color of text inside terminal from `#FFFFFF10` to `#FFFFFF3c`.
	-	Active selection color inside editor from `#3A3D4140` to `#3F69C220`.
	-	Inactive selection color inside editor from `#3A3D4197` to `#3F69C23A`.

## [1.0.0] - 2024-12-08

**This release focuses on improving accessibility and addressing user feedback related to eye strain caused by overly bright colors.**

### Added

-   Introduced new accent colors:
    -   `#BF56DE` for keywords.
    -   `#98C379` for strings.
	-	`#FFD255` for HTML tags.
	-	`#FFFCF5` for numbers.
	-	`#56B6C2` for logical operators.
	-	`#FFFCF5` for primary button's background and `#161316` for button's text.
	-	`#21499F` for secondary button's background and `#FFFCF5` for button's text.

### Changed

-   Replaced overly bright colors in the palette with less intense options for better readability.
-   Adjusted contrast levels for background and text to reduce visual fatigue.

### Removed

-   Deprecated excessively bright colors that caused discomfort in the previous version.

### Fixed

-   Resolved color contrast issues in the sidebar and activity bar.

---

## [0.0.1] - 2024-12-08

### Added

-   Initial release of the VS Code theme
-   Syntax highlighting for core languages: JavaScript, TypeScript, JSON, HTML, CSS
-   Optimized contrast for readability
-   Integrated styling for non-editor UI elements:
    -   Terminal, sidebar, status bar and activity bar

### Known Issues

-   Eye strain
