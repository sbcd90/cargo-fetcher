# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed
- Updated dependencies
- Place all GCS specific code/dependencies behind a `gcs` feature

### Fixed
- Replaced `failure` with `anyhow`

## [0.5.1] - 2019-10-27
### Fixed
- Allow using as `cargo fetcher` instead of only `cargo-fetcher`

## [0.5.0] - 2019-10-26
### Added
- Validate crate checksums after download

### Fixed
- Ensure duplicates are only downloaded once eg. same git source for multiple crates

## [0.4.1] - 2019-10-25
### Added
- Add support for only updating the registry index after it hasn't been updated
for a user specified amount of time, rather than always

## [0.4.0] - 2019-10-25
### Added
- Add support for retrieving and uploading the crates.io index

## [0.4.0] - 2019-10-25
### Added
- Add support for retrieving and uploading the crates.io index

## [0.3.0] - 2019-10-25
### Added
- Add support for unpacking compressed crate tarballs into registry/src

## [0.2.0] - 2019-07-24
### Added
- Add crate retrieval and uploading for `git` sources

## [0.1.1] - 2019-07-23
### Fixed
- Travis config

## [0.1.0] - 2019-07-23
### Added
- Initial add of `cargo-fetcher`

[Unreleased]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.5.1...HEAD
[0.5.1]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.5.0...0.5.1
[0.5.0]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.4.1...0.5.0
[0.4.1]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.4.0...0.4.1
[0.4.0]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.3.0...0.4.0
[0.3.0]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.1.1...0.2.0
[0.1.1]: https://github.com/EmbarkStudios/cargo-fetcher/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/EmbarkStudios/cargo-fetcher/releases/tag/0.1.0
