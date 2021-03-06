# Changelog
All notable changes to this project will be documented in this file.

## [Unrelease]

### Changed
- Rename  `ResolverContext::new` by `ResolverContext::for_reference`

### Added 
- `ResolverContext::new` to build a context with a reference, min and max interval.

## [0.19.3]
### Fixed
- Remove Chinese training examples causing issues on raspbian and windows [#205](https://github.com/snipsco/rustling-ontology/pull/205)
- Fix float parsing for all languages [#203](https://github.com/snipsco/rustling-ontology/pull/203)
- Add various improvements in all languages [#203](https://github.com/snipsco/rustling-ontology/pull/203)

## [0.19.2]
### Fixed
- Fix chrono issue and move to rust edition 2018 [#194](https://github.com/snipsco/rustling-ontology/pull/194)
- Bump rustling to `0.9.1` [#195](https://github.com/snipsco/rustling-ontology/pull/195)

## [0.19.1]
### Added
- [Fr] Implement datetime subtypes in French [#191](https://github.com/snipsco/rustling-ontology/pull/191)
- [Fr] Improve grammars [#191](https://github.com/snipsco/rustling-ontology/pull/191)

## [0.19.0]
### Added
- [All] Added new datetime subtypes [#167](https://github.com/snipsco/rustling-ontology/pull/167)

### Fixed
- [All] Include prefix + in numbers [#186](https://github.com/snipsco/rustling-ontology/pull/186)
- [All] Set boundaries for quarters in datetimes [#185](https://github.com/snipsco/rustling-ontology/pull/185)
- [En] En moneys: add "centime" (request from PM team) [#183](https://github.com/snipsco/rustling-ontology/pull/183)
- [Fr] Fix/fr add duration vocab 2 [#182](https://github.com/snipsco/rustling-ontology/pull/182)
- [Fr] Fr "sept" abbreviation (for "september") removed if no following dot [#178](https://github.com/snipsco/rustling-ontology/pull/178)
- [Es] Misc. fixes for Spanish. [#177](https://github.com/snipsco/rustling-ontology/pull/177)
- [Ja] Delete rule that accepts numbers followed by quantifiers for cardinal [#176](https://github.com/snipsco/rustling-ontology/pull/176)
- [Fr] Fix some interval rules in Fr and switched Duration/Datetime priority [#173](https://github.com/snipsco/rustling-ontology/pull/173)
- [En] Typo in English training [#168](https://github.com/snipsco/rustling-ontology/pull/168)

## [0.18.1]
### Fixed
- [Es] Various fixes
- [Ja] Remove quantifiers in Japanese cardinals
- [Fr] Fixed some interval rules and switched Duration/Datetime priority
- [En] Fixed typos in training examples

### Added
- [Pt] Improved all entities

## [0.18.0]
### Changed
- [Pt] Add Portuguese V0

### Fixed
- Crash when attempting to parse wrong month and day.
- Fix and adjust date written abbreviations in all languages.
- [De] Change end of time span setting to get the right intervals.
- [De] Fix relative minute for value=1.
- [It] Fix financial rule with Rubles.
- [Es] Fix percentage pattern and other typos.

## [0.17.7] - 2019-01-17
### Changed
- Fix resolution of decimal numbers in textual form.

## [0.17.6] - 2018-12-13
### Changed
- Fuller coverage of Spanish and Italian

[0.19.3]: https://github.com/snipsco/rustling-ontology/compare/0.19.2...0.19.3
[0.19.2]: https://github.com/snipsco/rustling-ontology/compare/0.19.1...0.19.2
[0.19.1]: https://github.com/snipsco/rustling-ontology/compare/0.19.0...0.19.1
[0.19.0]: https://github.com/snipsco/rustling-ontology/compare/0.18.1...0.19.0
[0.18.1]: https://github.com/snipsco/rustling-ontology/compare/0.18.0...0.18.1
[0.18.0]: https://github.com/snipsco/rustling-ontology/compare/0.17.7...0.18.0
[0.17.7]: https://github.com/snipsco/rustling-ontology/compare/0.17.6...0.17.7
[0.17.6]: https://github.com/snipsco/rustling-ontology/compare/0.17.5...0.17.6
