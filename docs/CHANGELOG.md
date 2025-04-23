# Changelog

All notable changes to Azure Terminal will be documented in this file. This project adheres to [Semantic Versioning](https://semver.org/).

---

## [Unreleased] - 26/02/2025 - Build #0
### Added
- Basic structure for Azure Terminal.

## v1.0.0 - 27/02/2025 - Build #1
### Added
- Basic system commands like `ls` & `quit`.
- Custom modules can now be added modularity.

## v1.1.0 - 09/03/2025 - Build #2
### Added
- System command, `clear`, to clear terminal screen.
- Rounding off capability in `math` custom module.
- `config` folder for all of Azure Terminal user configuration.
### Bug Fix
- Fixed system and module commands not working when having spaces in input.

## v1.1.1 - 15/03/2025 - Build #3
### Added
- `system_library` for all custom libraries in Azure Core

## v1.2.0 - 15/03/2025 - Build#4
### Added
- `appearance.json` for user config.
- `-a`, `-h` and multiple command options handling for `ls` system command.
- Help screen for all system commands and custom modules.
### Changed
- Updated all system commands and custom modules to implement user config in output.

## v1.2.1 - 19/03/2025 - Build#5
### Changed
- Moved system command and custom module importing into the same program.

# v1.2.2 - 05/04/2025 - Build#6
### Added
- `echo` system command.

---

### Note:
- All changes, updates, and fixes will be reflected here to keep track of Azure Terminal's evolution.
- This changelog follows [Semantic Versioning](https://semver.org/) to indicate the types of changes made in each release.
- All dates follow the `DD/MM/YYYY` format.
- The build number increases with each version to indicate the release order
