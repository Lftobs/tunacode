# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Modified CLI commands processing
- Updated REPL functionality
- Enhanced output display formatting
- Refactored main.py to reduce file size from 691 to 447 lines
- Improved ESC key handling with double-press safety and unified abort behavior
- Added comprehensive ESC key investigation documentation

### Added

- New helper module `agent_helpers.py` for common agent operations
- Streaming cancellation with AbortableStream for better ESC key response
- Memory anchors and documentation organization improvements

### Fixed

- ESC key double-press safety restoration
- Unified ESC and Ctrl+C abort handling in REPL
- Pre-commit hook configuration for file length checks

### Contributors

Special thanks to our community contributors:
- **mohaidoss** - ESC key interrupt functionality (#29)
- **MclPio** - Token cost tracking feature (#17)
- **prudentbird** - Context window management (#17)
- **Lftobs** - Todo tool functionality and @-file-ref enhancements (#17, #2)
- **ColeMurray** - Security fix for B108 vulnerability (#25)
- **ryumacodes** - Fix for RuntimeWarnings in REPL tests (#71)

## [0.0.23] - 2025-01-06

### Added

- Fallback response handling for agent iterations

## [0.0.22] - 2025-01-06

### Added

- Control-C handling improvements for smooth exit

## [0.0.21] - 2025-01-06

### Fixed

- Various bug fixes and improvements

## [0.0.19] - 2025-01-06

### Added

- Orchestrator features with planning visibility
- Background manager implementation

### Changed

- Updated README with orchestrator features
- System prompt updates

## [0.0.18] - 2025-01-05

### Fixed

- Circular import in ReadOnlyAgent
- Orchestrator integration to use TunaCode's LLM infrastructure

## [0.0.17] - 2025-01-05

### Changed

- General codebase cleanup

## [0.0.16] - 2025-01-05

### Fixed

- Publish script to use temporary deploy venv
- Improved .gitignore

## [0.0.15] - 2025-01-05

### Added

- Shell command support with `!` prefix
- Updated yolomode message

### Fixed

- Escape-enter keybinding test

## [0.0.14] - 2025-01-04

### Changed

- Various improvements and bug fixes

## [0.0.13] - 2025-01-04

### Changed

- Initial stable release with core features
