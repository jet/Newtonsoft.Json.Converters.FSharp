# Changelog

The repo is versioned based on [SemVer 2.0](https://semver.org/spec/v2.0.0.html) using the tiny-but-mighty [MinVer](https://github.com/adamralph/minver) from [@adamralph](https://github.com/adamralph). [See here](https://github.com/adamralph/minver#how-it-works) for more information on how it works.

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

The `Unreleased` section name is replaced by the expected version of next release. A stable version's log contains all changes between that version and the previous stable version (can duplicate the prereleases logs).

## [Unreleased]

### Added

- `tests/FsCodec.NewtonsoftJson.Tests/examples.fsx` counterpart to the README

### Changed

- Exposed `TypeSafeEnum`

### Removed
### Fixed

- Pushed `TypeShape`'s `PackageReference` down into `FsCodec.NewtonsoftJson`

<a name="1.0.1-rc1"></a>
## [1.0.0-rc1] - 2019-08-30

Initial release based on merge of [Jet.JsonNet.Converters v0](https://github.com/jet/FsCodec/tree/v0) and the codecs formerly known as `Equinox.Codec` from [Equinox](https://github.com/jet/equinox) [#15](https://github.com/jet/FsCodec/pull/15)

<a name="0.2.2."></a>
## Jet.JsonNet.Converters [0.2.2]

Final release of Jet.JsonNet.Converters archived on [v0 branch](https://github.com/jet/FsCodec/tree/v0)

[Unreleased]: https://github.com/jet/equinox/compare/1.0.0-rc1...HEAD
[1.0.0-rc1]: https://github.com/jet/FsCodec/compare/0.2.2...1.0.0-rc1
[0.2.2]: https://github.com/jet/FsCodec/compare/0eb459b3aca873a40492d6a6c19cab4111d8f53e...0.2.2