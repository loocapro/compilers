# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.1](https://github.com/foundry-rs/compilers/releases/tag/v0.3.1) - 2024-02-02

### Other

- Flatten fix ([#68](https://github.com/foundry-rs/compilers/issues/68))

## [0.3.0](https://github.com/foundry-rs/compilers/releases/tag/v0.3.0) - 2024-01-31

### Dependencies

- Remove unnecessary dependencies ([#65](https://github.com/foundry-rs/compilers/issues/65))
- Bump to 0.8.24 in tests ([#59](https://github.com/foundry-rs/compilers/issues/59))

### Miscellaneous Tasks

- Release 0.3.0
- Enable some lints ([#64](https://github.com/foundry-rs/compilers/issues/64))
- Remove wasm cfgs ([#61](https://github.com/foundry-rs/compilers/issues/61))
- Add more tracing around spawning Solc ([#57](https://github.com/foundry-rs/compilers/issues/57))
- Rename output to into_output ([#56](https://github.com/foundry-rs/compilers/issues/56))
- Add some tracing ([#55](https://github.com/foundry-rs/compilers/issues/55))

### Other

- Flatten fixes ([#63](https://github.com/foundry-rs/compilers/issues/63))
- Update actions@checkout ([#66](https://github.com/foundry-rs/compilers/issues/66))
- Add concurrency to ci.yml ([#62](https://github.com/foundry-rs/compilers/issues/62))
- Fix tests name ([#60](https://github.com/foundry-rs/compilers/issues/60))

### Refactor

- Rewrite examples without wrapper functions and with no_run ([#58](https://github.com/foundry-rs/compilers/issues/58))

### Testing

- Ignore old solc version test ([#67](https://github.com/foundry-rs/compilers/issues/67))

## [0.2.5](https://github.com/foundry-rs/compilers/releases/tag/v0.2.5) - 2024-01-29

### Miscellaneous Tasks

- Release 0.2.5
- [clippy] Make clippy happy ([#54](https://github.com/foundry-rs/compilers/issues/54))

### Other

- New flattening impl ([#52](https://github.com/foundry-rs/compilers/issues/52))

## [0.2.4](https://github.com/foundry-rs/compilers/releases/tag/v0.2.4) - 2024-01-27

### Dependencies

- Bump svm builds ([#53](https://github.com/foundry-rs/compilers/issues/53))

### Miscellaneous Tasks

- Release 0.2.4

## [0.2.3](https://github.com/foundry-rs/compilers/releases/tag/v0.2.3) - 2024-01-26

### Features

- Add EVM version Cancun ([#51](https://github.com/foundry-rs/compilers/issues/51))

### Miscellaneous Tasks

- Release 0.2.3
- Add unreleased section to cliff.toml
- Add error severity fn helpers ([#48](https://github.com/foundry-rs/compilers/issues/48))

### Other

- Small fixes to typed AST ([#50](https://github.com/foundry-rs/compilers/issues/50))

## [0.2.2](https://github.com/foundry-rs/compilers/releases/tag/v0.2.2) - 2024-01-19

### Miscellaneous Tasks

- Release 0.2.2

### Other

- Rewrite dirty files discovery ([#45](https://github.com/foundry-rs/compilers/issues/45))

## [0.2.1](https://github.com/foundry-rs/compilers/releases/tag/v0.2.1) - 2024-01-10

### Miscellaneous Tasks

- Release 0.2.1
- Exclude useless directories
- Exclude useless directories

## [0.2.0](https://github.com/foundry-rs/compilers/releases/tag/v0.2.0) - 2024-01-10

### Dependencies

- [deps] Bump alloy ([#42](https://github.com/foundry-rs/compilers/issues/42))

### Miscellaneous Tasks

- Release 0.2.0

## [0.1.4](https://github.com/foundry-rs/compilers/releases/tag/v0.1.4) - 2024-01-06

### Bug Fixes

- Account for unicode width in error syntax highlighting ([#40](https://github.com/foundry-rs/compilers/issues/40))

### Miscellaneous Tasks

- Release 0.1.4

## [0.1.3](https://github.com/foundry-rs/compilers/releases/tag/v0.1.3) - 2024-01-05

### Features

- Add evmVersion to settings ([#41](https://github.com/foundry-rs/compilers/issues/41))
- Use Box<dyn> in sparse functions ([#39](https://github.com/foundry-rs/compilers/issues/39))

### Miscellaneous Tasks

- Release 0.1.3
- Clippies and such ([#38](https://github.com/foundry-rs/compilers/issues/38))
- Purge tracing imports ([#37](https://github.com/foundry-rs/compilers/issues/37))

## [0.1.2](https://github.com/foundry-rs/compilers/releases/tag/v0.1.2) - 2023-12-29

### Bug Fixes

- Create valid Standard JSON to verify for projects with symlinks ([#35](https://github.com/foundry-rs/compilers/issues/35))
- Create verifiable Standard JSON for projects with external files ([#36](https://github.com/foundry-rs/compilers/issues/36))

### Features

- Add more getter methods to bytecode structs ([#30](https://github.com/foundry-rs/compilers/issues/30))

### Miscellaneous Tasks

- Release 0.1.2
- Add `set_compiled_artifacts` to ProjectCompileOutput impl ([#33](https://github.com/foundry-rs/compilers/issues/33))

### Other

- Trim test matrix ([#32](https://github.com/foundry-rs/compilers/issues/32))

### Styling

- Update rustfmt config ([#31](https://github.com/foundry-rs/compilers/issues/31))

## [0.1.1](https://github.com/foundry-rs/compilers/releases/tag/v0.1.1) - 2023-11-23

### Bug Fixes

- Default Solidity language string ([#28](https://github.com/foundry-rs/compilers/issues/28))
- [`ci`] Put flags inside matrix correctly ([#20](https://github.com/foundry-rs/compilers/issues/20))

### Dependencies

- Bump Alloy
- Bump solc ([#21](https://github.com/foundry-rs/compilers/issues/21))

### Miscellaneous Tasks

- Release 0.1.1
- [meta] Update CODEOWNERS
- Remove LosslessAbi ([#27](https://github.com/foundry-rs/compilers/issues/27))

### Performance

- Don't prettify json when not necessary ([#24](https://github.com/foundry-rs/compilers/issues/24))

### Styling

- Toml
- More test in report/compiler.rs and Default trait for CompilerInput ([#19](https://github.com/foundry-rs/compilers/issues/19))

## [0.1.0](https://github.com/foundry-rs/compilers/releases/tag/v0.1.0) - 2023-11-07

### Bug Fixes

- Add changelog.sh ([#18](https://github.com/foundry-rs/compilers/issues/18))

### Dependencies

- Bump solang parser to 0.3.3 ([#11](https://github.com/foundry-rs/compilers/issues/11))
- Remove unneeded deps ([#4](https://github.com/foundry-rs/compilers/issues/4))

### Features

- [`ci`] Add unused deps workflow ([#15](https://github.com/foundry-rs/compilers/issues/15))
- Migration to Alloy ([#3](https://github.com/foundry-rs/compilers/issues/3))
- [`ci`] Add deny deps CI ([#6](https://github.com/foundry-rs/compilers/issues/6))
- [`ci`] Add & enable ci/cd ([#1](https://github.com/foundry-rs/compilers/issues/1))
- Move ethers-solc into foundry-compilers

### Miscellaneous Tasks

- Release 0.1.0
- Add missing cargo.toml fields + changelog tag ([#17](https://github.com/foundry-rs/compilers/issues/17))
- Add missing telegram url ([#14](https://github.com/foundry-rs/compilers/issues/14))
- Remove alloy-dyn-abi as its an unused dep ([#12](https://github.com/foundry-rs/compilers/issues/12))
- Make clippy happy ([#10](https://github.com/foundry-rs/compilers/issues/10))
- Run ci on main ([#5](https://github.com/foundry-rs/compilers/issues/5))
- Add more files to gitignore ([#2](https://github.com/foundry-rs/compilers/issues/2))
- Correct readme

### Other

- Repo improvements ([#13](https://github.com/foundry-rs/compilers/issues/13))

<!-- generated by git-cliff -->