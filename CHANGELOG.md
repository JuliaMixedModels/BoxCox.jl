# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.10] - 2026-06-17

### Changed

- Use Distributions.jl instead of a direct dependency on StatsFuns.jl ([#71])

## [0.3.9] - 2026-05-22

### Fixed

- Minor correctness and consistency issues ([#67])

## [0.3.8] - 2026-02-09

### Added

- Zenodo metadata and citation badge ([#52])

## [0.3.7] - 2025-08-27

### Changed

- Compat bumped to allow MixedModels.jl v5 ([#49])

## [0.3.6] - 2025-06-24

### Changed

- Compat bumped to allow Makie.jl 0.24 (weak dependency) ([#46])

## [0.3.5] - 2025-06-17

### Changed

- Compat bumped to allow Makie.jl 0.23 ([#43])

## [0.3.4] - 2025-01-17

### Changed

- Minimum supported Julia version updated ([#32])
- Compat bumped to allow Makie.jl 0.22 (weak dependency) ([#37])

## [0.3.3] - 2024-08-09

### Changed

- Fine-tuning of the Yeo-Johnson transformation ([#31])

## [0.3.2] - 2024-08-09

### Added

- Yeo-Johnson transformation ([#30])

## [0.3.1] - 2024-05-14

### Fixed

- Small test and documentation errors ([#29])

### Changed

- Compat bumped to allow Makie.jl 0.21 ([#28])

## [0.3.0] - 2024-03-23

### Changed

- Reduced dependency on Makie recipes ([#23])

## [0.2.4] - 2023-11-22

### Fixed

- Spelling errors ([#21])

### Changed

- Compat bumped to allow Makie.jl 0.20 ([#22])

## [0.2.3] - 2023-11-03

### Changed

- Added stdlib compat entries and updated Statistics.jl compat ([#19], [#20])

## [0.2.2] - 2023-09-02

### Fixed

- Swapped plot labels ([#17])

## [0.2.1] - 2023-08-31

### Changed

- Documentation tweaks and improvements ([#16])

## [0.2.0] - 2023-08-31

### Added

- Support for MixedModels.jl ([#6])
- MixedModels example in the documentation ([#15])

### Changed

- CI now also runs on `release-*` branches ([#14])

### Fixed

- Broken links in documentation ([#11])

## [0.1.1] - 2023-08-29

### Fixed

- Broken links in documentation ([#11])

## [0.1.0] - 2023-08-28

### Added

- Initial release, including `confint` support ([#4])

[Unreleased]: https://github.com/palday/BoxCox.jl/compare/v0.3.10...HEAD
[0.3.10]: https://github.com/palday/BoxCox.jl/compare/v0.3.9...v0.3.10
[0.3.9]: https://github.com/palday/BoxCox.jl/compare/v0.3.8...v0.3.9
[0.3.8]: https://github.com/palday/BoxCox.jl/compare/v0.3.7...v0.3.8
[0.3.7]: https://github.com/palday/BoxCox.jl/compare/v0.3.6...v0.3.7
[0.3.6]: https://github.com/palday/BoxCox.jl/compare/v0.3.5...v0.3.6
[0.3.5]: https://github.com/palday/BoxCox.jl/compare/v0.3.4...v0.3.5
[0.3.4]: https://github.com/palday/BoxCox.jl/compare/v0.3.3...v0.3.4
[0.3.3]: https://github.com/palday/BoxCox.jl/compare/v0.3.2...v0.3.3
[0.3.2]: https://github.com/palday/BoxCox.jl/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/palday/BoxCox.jl/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/palday/BoxCox.jl/compare/v0.2.4...v0.3.0
[0.2.4]: https://github.com/palday/BoxCox.jl/compare/v0.2.3...v0.2.4
[0.2.3]: https://github.com/palday/BoxCox.jl/compare/v0.2.2...v0.2.3
[0.2.2]: https://github.com/palday/BoxCox.jl/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/palday/BoxCox.jl/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/palday/BoxCox.jl/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/palday/BoxCox.jl/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/palday/BoxCox.jl/releases/tag/v0.1.0

[#71]: https://github.com/palday/BoxCox.jl/pull/71
[#67]: https://github.com/palday/BoxCox.jl/pull/67
[#52]: https://github.com/palday/BoxCox.jl/pull/52
[#49]: https://github.com/palday/BoxCox.jl/pull/49
[#46]: https://github.com/palday/BoxCox.jl/pull/46
[#43]: https://github.com/palday/BoxCox.jl/pull/43
[#37]: https://github.com/palday/BoxCox.jl/pull/37
[#32]: https://github.com/palday/BoxCox.jl/pull/32
[#31]: https://github.com/palday/BoxCox.jl/pull/31
[#30]: https://github.com/palday/BoxCox.jl/pull/30
[#29]: https://github.com/palday/BoxCox.jl/pull/29
[#28]: https://github.com/palday/BoxCox.jl/pull/28
[#23]: https://github.com/palday/BoxCox.jl/pull/23
[#22]: https://github.com/palday/BoxCox.jl/pull/22
[#21]: https://github.com/palday/BoxCox.jl/pull/21
[#20]: https://github.com/palday/BoxCox.jl/pull/20
[#19]: https://github.com/palday/BoxCox.jl/pull/19
[#17]: https://github.com/palday/BoxCox.jl/pull/17
[#16]: https://github.com/palday/BoxCox.jl/pull/16
[#15]: https://github.com/palday/BoxCox.jl/pull/15
[#14]: https://github.com/palday/BoxCox.jl/pull/14
[#11]: https://github.com/palday/BoxCox.jl/pull/11
[#6]: https://github.com/palday/BoxCox.jl/pull/6
[#4]: https://github.com/palday/BoxCox.jl/pull/4
