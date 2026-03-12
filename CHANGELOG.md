# Changelog

## Unreleased

### Added
- OpenClaw Shortcut Mode for underspecified diagram requests
- multi-theme palette system in `references/color-palette.md`
  - Default / Universal
  - 技术指南针 / Tech Compass
  - 小红书 IP / Warm Creator
- style guidance for whiteboard, handout, and teaching-oriented output
- `examples/` source diagrams for public-facing documentation
- `screenshots/` preview images for README and project sharing
- `CONTRIBUTING.md` and `ATTRIBUTION.md`

### Changed
- expanded trigger description for natural-language chart requests
- improved README for open-source publication
- `.gitignore` updated so screenshots can be tracked while temporary experiment renders remain ignored
- renderer timeout increased to reduce flaky Playwright startup failures

### Fixed
- handout-style diagram text overflow fixes in container footnotes
- render retry issue caused by short module-ready timeout
