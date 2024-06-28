# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Nothing yet!

## [0.3.0] - 2023-05-15

### Added

- Added support for `prettier-plugin-marko` ([#151](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/151))
- Allow sorting of custom attributes, functions, and tagged template literals ([#155](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/155))

### Fixed

- Speed up formatting ([#153](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/153))
- Fix plugin compatibility when loaded with require ([#159](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/159))

## [0.2.8] - 2023-04-28

### Changed

- Remove support for `@prettier/plugin-php` ([#152](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/152))

## [0.2.7] - 2023-04-05

### Fixed

- Don't break liquid tags inside attributes when sorting classes ([#143](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/143))

## [0.2.6] - 2023-03-29

### Added

- Support ESM and TS config files ([#137](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/137))

### Fixed

- Load `tailwindcss` modules from nearest instance only ([#139](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/139))

## [0.2.5] - 2023-03-17

### Fixed

- Fix class sorting in `capture` liquid tag ([#131](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/131))

## [0.2.4] - 2023-03-02

### Fixed

- Sort `class` attribute on components and custom elements in Astro ([#129](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/129))

## [0.2.3] - 2023-02-15

### Fixed

- Don't sort classes in Glimmer `concat` helper ([#119](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/119))
- Add support for `@ianvs/prettier-plugin-sort-imports` ([#122](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/122))

## [0.2.2] - 2023-01-24

### Fixed

- Add prettier plugins to peer dependencies ([#114](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/114))
- Traverse await expression blocks in Svelte ([#118](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/118))

## [0.2.1] - 2022-12-08

### Fixed

- Fix support for latest Shopify Liquid plugin ([#109](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/109))

## [0.2.0] - 2022-11-25

### Changed

- Don't bundle `prettier-plugin-svelte` ([#101](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/101))

### Added

- Improve compatibility with other Prettier plugins ([#101](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/101), [#102](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/102))

## [0.1.13] - 2022-07-25

### Fixed

- Fix error when using Angular pipes ([#86](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/86))

## [0.1.12] - 2022-07-07

### Added

- Add support for Glimmer / Handlebars ([#83](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/83))

## [0.1.11] - 2022-05-16

### Changed

- Update `prettier-plugin-svelte` to `v2.7.0` ([#77](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/77))

### Fixed

- Fix sorting in Svelte `:else` blocks ([#79](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/79))

## [0.1.10] - 2022-04-20

### Removed

- Remove whitespace tidying and duplicate class removal due to [issues](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/issues/71) with whitespace removal ([#72](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/72))

## [0.1.9] - 2022-04-19

### Added

- Add license file ([#64](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/64))
- Add whitespace tidying and duplicate class removal ([#70](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/70))

## [0.1.8] - 2022-02-24

### Changed

- Use Tailwind's `getClassOrder` API when available ([#57](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/57))

### Fixed

- Fix Tailwind config file resolution when Prettier config file is not present ([#62](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/62))

## [0.1.7] - 2022-02-09

### Fixed

- Fix single quotes being converted to double quotes ([#51](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/51))

## [0.1.6] - 2022-02-08

### Fixed

- Fix error when no Prettier options provided ([#46](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/46))

## [0.1.5] - 2022-02-04

### Added

- Add support for MDX ([#30](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/30))

### Fixed

- Fix error when formatting Svelte files that contain `let:class` attributes ([#24](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/24))

## [0.1.4] - 2022-01-25

### Fixed

- Handle empty class attributes ([#17](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/17))
- Handle TypeScript syntax in Vue/Angular class attributes ([#18](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/18))

## [0.1.3] - 2022-01-24

### Fixed

- Ignore `!important` when sorting `@apply` classes ([#4](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/4))

## [0.1.2] - 2022-01-24

### Fixed

- Fix error when using nullish coalescing operator in Vue/Angular ([#2](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/pull/2))

[unreleased]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.8...v0.3.0
[0.2.8]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.7...v0.2.8
[0.2.7]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.6...v0.2.7
[0.2.6]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.5...v0.2.6
[0.2.5]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.4...v0.2.5
[0.2.4]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.3...v0.2.4
[0.2.3]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.2...v0.2.3
[0.2.2]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.13...v0.2.0
[0.1.13]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.12...v0.1.13
[0.1.12]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.11...v0.1.12
[0.1.11]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.10...v0.1.11
[0.1.10]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.9...v0.1.10
[0.1.9]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.8...v0.1.9
[0.1.8]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.7...v0.1.8
[0.1.7]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.6...v0.1.7
[0.1.6]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.5...v0.1.6
[0.1.5]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/tailwindlabs/prettier-plugin-tailwindcss/compare/d9c27f07a69bf9feec7f9d889426ad2ba76e1b09...v0.1.2
