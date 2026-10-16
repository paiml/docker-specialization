# Docker, Terminal First

A five-course specialization on Docker, taught entirely at the terminal. Every
lesson is a real recording of real commands, and every demo ends with a
machine-checked `contract:` line that proves what you watched.

## Courses

| # | Course | Focus |
|---|--------|-------|
| 1 | [Docker from Zero](https://github.com/paiml/docker-from-zero) | Images, layers, containers, volumes, networks |
| 2 | Production images | Multi-stage builds, distroless bases, buildx, static binaries |
| 3 | Compose and local development | Compose files, environments, healthchecks |
| 4 | Container supply-chain security | Scanning, SBOMs, signing |
| 5 | Capstone | Ship a signed, scanned, minimal image |

Course 1 ships with `imgscope`, a small read-only Rust tool that opens an image
tarball and verifies its layers without a daemon. Later courses add their own
tested code in their own repositories as they publish.

## Layout

This repository is the index. Each course keeps its code, fixtures and tests in
its own public repository, linked above.

## License

MIT
