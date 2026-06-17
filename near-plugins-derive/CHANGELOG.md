# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.5.3](https://github.com/near/near-plugins/compare/near-plugins-derive-v0.5.2...near-plugins-derive-v0.5.3) - 2026-06-17

### Fixed

- ship the real README on crates.io ([#199](https://github.com/near/near-plugins/pull/199))

## [0.5.2](https://github.com/near/near-plugins/compare/near-plugins-derive-v0.5.1...near-plugins-derive-v0.5.2) - 2026-06-09

### Fixed

- detect near_bindgen-generated functions on rustc >= 1.87 ([#197](https://github.com/near/near-plugins/pull/197))
- use path+version deps for inter-crate references to fix crates.io publishing ([#187](https://github.com/near/near-plugins/pull/187))

### Other

- fix changelogs for release-plz automation ([#194](https://github.com/near/near-plugins/pull/194))

## [0.5.1](https://github.com/near/near-plugins/releases/tag/near-plugins-derive-v0.5.1) - 2026-04-08

### Added

- Improve Pausable migration guide and add migration tests ([#163](https://github.com/near/near-plugins/pull/163))

### Fixed

- Update `syn` crate to match `near-sdk` crate and to enable parsing of `#[unsafe(no_mangle)]` ([#171](https://github.com/near/near-plugins/pull/171))

### Other

- Downgrade `near-sdk` dep to allow plugins for older versions of SDK ([#183](https://github.com/near/near-plugins/pull/183))
