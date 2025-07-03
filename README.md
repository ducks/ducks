# whoami

Software engineer who enjoys working on developer tooling, backend services,
observability infrastructure, distributed systems.


## tech

<div>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rust/rust-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nixos/nixos-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vim/vim-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/terraform/terraform-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/prometheus/prometheus-plain-wordmark.svg" width="100" />
</div>

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
[blog post](https://jakegoldsborough.com/blog/2025/introducing-shelltrax/)

### GitVote (Decentralized Git-based voting system)

A fully decentralized, verifiable voting system built entirely on Git:

- Votes submitted via forked branches and pull requests
- Immutable hash-linked blocks generated post-merge
- CI-enforced validation of vote format, schema compliance, and duplicate
  prevention
- Fully auditable offline: entire election state lives in the Git repo
- No servers, backend, or blockchain infrastructure required
- Rust CLI tool with modular subcommands (`cast`, `validate`, `build-chain`,
  `tally`)

[repo](https://github.com/ducks/gitvote)
[blog post](https://jakegoldsborough.com/blog/2025/building-a-voting-system-with-git/)

## Interests

- Rust, TypeScript, Node.js
- Systems design
- Observability & monitoring
- Infrastructure automation
- TUIs
