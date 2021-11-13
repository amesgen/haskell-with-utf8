# Changelog

## Unreleased

Allow build with GHC 9.2.1.

### Changed

- Allow base 4.16

## 1.0.2.0

Improve `utf8-troubleshoot` to make it useful for identifying tricky cases.

### Changed

- `utf8-troubleshoot`: improve available locale detection
- `utf8-troubleshoot`: display raw results from C libraries

## 1.0.1.0

GHC 8.10 compatibility and a new troubleshooting tool.

### Added

- `utf8-troubleshoot` – the troubleshooting tool

### Changed

- Bump `base` for GHC 8.10


## 1.0.0.0

Initial release.

### Added

- `withUtf8`
- `withStdTerminalHandles`
- `setHandleEncoding`
- `withHandle`
- `setTerminalHandleEncoding`
- `withTerminalHandle`
- `openFile`
- `withFile`
- `readFile`
- `writeFile`
