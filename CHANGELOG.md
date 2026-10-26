# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- The engine contract: `Engine`, its values and events, and the `Store` and
  `Toolbox` ports, in `kataloop-core`; `Engine.stream` is typed
  `AsyncGenerator[Event, None]`, so that a caller closes it without a cast.
  Specified in `docs/specs/engine.md`.
- `LocalToolbox`, the tools of the process's own, and `MemoryStore`, memory
  that lasts as long as the process.

[Unreleased]: https://github.com/the-guish/kataloop/commits/main
