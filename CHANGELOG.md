# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.9.0]
### Added
- Configured VuePress Plugin Janitor

### Changed
- Google Analytics is now a plugin and configured via plugin and not in the config object directly

### Fixed
- Future blog posts will no longer be output in the build directory
- RSS Feed filter will now compare identical UTC timezone

### Deprecated
- Limited tagging UI functionality (i.e., sort posts by tags) was removed in order to allow for better integration of official blog plugin in the near future