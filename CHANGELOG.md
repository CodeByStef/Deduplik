# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [v1.0.1.1] - 2025-11-05
### Fixed
  - Significant tagging performance improvement.  UI was unresponsive with larger workspaces.

## [v1.0.0.0] - 2025-11-03
### Changed
  - Graph nodes now have default approximate position instead of top left corner.
### Fixed
  - MinDupsToShow kept value from previous Workspace.
  - Fixed issue [GH-4](https://github.com/CodeByStef/Deduplik/issues/4) - While in detection mode the app is unresponsive.

## [v0.9.2.1-Beta2-2] - 2025-10-29
### Added
  - New message at app startup when an update is available.
### Changed
  - Revised tooltips.
### Fixed
  - KeepAndRemoveOthers would not remove others if folder name is a subset of the other folder.
  - When there are no longer any duplicates, graphs would render all Signature nodes.
  - Workspace sorting no longer case sensitive.
  - A few small improvements.

## [v0.9.2.1-Beta2-1] - 2025-10-21
First release of Beta-2.

## [0.9.1.3-beta.1] - 2025-06-25
Last release of Beta-1.

## Release template - version and date goes here
### Added
  - Added for new features.
### Changed
  - Changed for changes in existing functionality.
### Deprecated
  - Deprecated for soon-to-be removed features.
### Removed
  - Removed for now removed features.
### Fixed
  - Fixed for any bug fixes.
### Security
  - Security in case of vulnerabilities.
