# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
- Added modal frame that can be used to render top level elements like dropdown list.
- Fixed story tree item's texts being too big.
- Sidebar is now fixed size

### Changed
- When a studio test is initiated, HoarceKat will no longer display an update message.
- Changed how loaded scripts location are displayed. Instead of using the script source, it uses the script location within the datamodel.

## [1.1.1] - 2020-05-10
### Fixed
- Fixed permanently breaking if the cleanup function errored.
- Fixed stories being re-required if they were closed out.

## [1.1.0] - 2020-02-05
### Added
- Added a button to select the preview.

## [1.0.1] - 2020-02-05
### Changed
- `_G` is now monkey patched instead of referring to the real `_G`.

## [1.0.0] - 2020-01-22
### Added
- Initial release.
