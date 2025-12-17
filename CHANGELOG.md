# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2024-12-18

### Added
- Initial release
- `Flow` class for task orchestration
- `Context` class for shared state management
- `State` class for thread-safe value storage
- `TaskOutput` and `NextTask` dataclasses for task chaining
- `StreamChunk` for streaming output support
- Parallel task execution via `ThreadPoolExecutor`
- Support for spawning multiple instances of the same task
- Comprehensive test suite
- Full type hints support (PEP 561)

### Features
- Zero external dependencies - uses only Python standard library
- Thread-safe task scheduling
- Dynamic task orchestration
- Streaming output support
