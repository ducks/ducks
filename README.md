# whoami

Software engineer who enjoys working on developer tooling, backend services,
observability infrastructure, distributed systems.


## tech

![My Skills](https://skillicons.dev/icons?i=nodejs,rust,ts,py,react,docker,postgres,nix,linux,bash,vim,kubernetes,terraform,git,prometheus)

## recent projects

### PostgreSQL Prometheus Exporter

A full-featured, PostgreSQL exporter for Prometheus:

- Multi-database scrape support via config-driven connection pools
- Dynamic metric registration from SQL queries (`queries.json`)
- Full scrape fault isolation using `Promise.allSettled`
- API key secured `/metrics` endpoint
- Self-observability metrics (scrape duration, scrape errors, scrape lockouts)
- Graceful shutdown & pool-level error handling
- Fully containerized with Docker Compose
- CI pipeline with automated tests using Vitest

[repo](https://github.com/ducks/node-postgres-exporter)
[blog post](https://jakegoldsborough.com/blog/2025/building-node-postgres-exporter/)

### Shelltrax (TUI music player in Rust)

Lightweight terminal-based music player inspired by cmus:

- Built with async Rust, crossterm, and Symphonia for audio decoding
- Supports FLAC metadata extraction and seeking
- Direct screen selection (non-cycling interface)
- Custom library indexing and local file scanning

[repo](https://github.com/ducks/shelltrax)

### Reverse Engineering the UDisc API

A multi-part technical blog series reverse engineering the UDisc `.data` API format,
used internally by their web app. This project explores:

- Schema-indexed binary JSON payload decoding
- Dynamic schema mapping and key resolution
- Building a standalone TypeScript client library to parse `.data` responses
- Resolving nested course, layout, hole, and smart layout structures

[repo](https://github.com/ducks/open-udisc-api)
[blog post](https://jakegoldsborough.com/blog/2025/reverse-engineering-udisc-api-part-1/)

## Interests

- Rust, TypeScript, Node.js
- Systems design
- Observability & monitoring
- Infrastructure automation
- TUIs
