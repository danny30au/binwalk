# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v3.20] - 2026-03-28
### :sparkles: New Features
- [`e1225f4`](https://github.com/danny30au/binwalk/commit/e1225f419666b24fda8adb44d63551d91b28663d) - Add support for ARJ archives *(commit by [@clark-ja](https://github.com/clark-ja))*
- [`eeaa577`](https://github.com/danny30au/binwalk/commit/eeaa577896f0aa8b79f1e41de2a2f0321dc8daec) - Add more elf_machines *(commit by [@clark-ja](https://github.com/clark-ja))*
- [`b1dd6c7`](https://github.com/danny30au/binwalk/commit/b1dd6c75852be51efcbe6dda8fc1b42b32a929f1) - Add 'no file type' to elf_types *(commit by [@clark-ja](https://github.com/clark-ja))*
- [`0068c8a`](https://github.com/danny30au/binwalk/commit/0068c8a8fb5e04bade99b0540f2a602fa4cc20a4) - Extend elf_osabi map *(commit by [@clark-ja](https://github.com/clark-ja))*
- [`6dfa9cf`](https://github.com/danny30au/binwalk/commit/6dfa9cf4d907931585fa60d91bde7fc5dbd16c1a) - Allow unknown ELF machine types *(commit by [@clark-ja](https://github.com/clark-ja))*
- [`b65242a`](https://github.com/danny30au/binwalk/commit/b65242aa348b2eba8251ca2b22f002081db93721) - Add more PEM signatures *(commit by [@clark-ja](https://github.com/clark-ja))*
- [`9bcaa60`](https://github.com/danny30au/binwalk/commit/9bcaa607236f03309021bdc823a8755749c2bc91) - Add support for QEMU QCOW images *(commit by [@clark-ja](https://github.com/clark-ja))*

### :recycle: Refactors
- [`8a9f4b8`](https://github.com/danny30au/binwalk/commit/8a9f4b850ee317fe26b80164bba813f088029f26) - replace &String with &str to enhance generality *(commit by [@Integral-Tech](https://github.com/Integral-Tech))*

### :white_check_mark: Tests
- [`c24c501`](https://github.com/danny30au/binwalk/commit/c24c5010cf65e5ca4f27db8dcc5a38e0a7f638b2) - Add integration test for ARJ archive *(commit by [@clark-ja](https://github.com/clark-ja))*
- [`475b5fa`](https://github.com/danny30au/binwalk/commit/475b5fa85bf30454cf706f6b06a0f08201018afe) - Add integration test for QEMU QCOW image *(commit by [@clark-ja](https://github.com/clark-ja))*

[v3.20]: https://github.com/danny30au/binwalk/compare/v3.1.0...v3.20
