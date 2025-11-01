# Changelog

All notable changes to credential-enumeration are documented here.

### [2026-01-24]
- test: implement mock service for end-to-end integration tests

### [2026-02-10]
- perf: optimize memory allocation in buffer pool

### [2026-02-20]
- fix: handle malformed HTTP header parsing without crashing

### [2026-02-28]
- test: verify backward compatibility with legacy message format

### [2026-03-25]
- security: harden cryptographic salt generation against entropy dips

### [2026-03-27]
- test: add unit tests for boundary input cases and error branches

### [2026-04-10]
- feat: add support for custom timeout configuration via CLI flags

### [2026-04-17]
- perf: replace linear search with hash map lookup for fast querying

### [2026-04-18]
- fix: ensure file descriptors are properly closed on error exits

### [2026-04-30]
- perf: minimize redundant heap allocations in hot loop

### [2026-05-03]
- fix: resolve memory leak in idle connection reaper

### [2026-05-06]
- fix: correct endianness conversion in raw packet parser

### [2026-05-26]
- test: implement mock service for end-to-end integration tests

### [2026-06-02]
- feat: implement verbose output mode for troubleshooting

### [2026-07-07]
- security: sanitize input strings to mitigate format string risks

### [2026-07-16]
- refactor: extract validation logic into dedicated helper module

### [2026-08-07]
- test: implement mock service for end-to-end integration tests

### [2026-08-08]
- fix: correct endianness conversion in raw packet parser

