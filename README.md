<link rel="me" href="https://hachyderm.io/@ducks" />

# whoami

Software engineer who enjoys working on developer tooling, backend services,
observability infrastructure, and distributed systems.


## tech

<div>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rust/rust-original.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ruby/ruby-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" width="100" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rails/rails-plain-wordmark.svg" width="100" />
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

### Scrob - Self-Hosted Music Scrobbling

Self-hosted alternative to Last.fm with public profile pages:

- Built with Rust, Axum, and PostgreSQL
- Token-based authentication with bcrypt password hashing
- RESTful API for submitting scrobbles from music players
- Public profile pages showing listening history and stats
- Embedded migrations via sqlx
- Designed for single-user or small community deployment

[repo](https://github.com/ducks/scrob)
[blog post](https://jakegoldsborough.com/blog/2026/building-scrob-self-hosted-scrobbling/)

### burrow-systemd - VPS Infrastructure Management

Running personal infrastructure with systemd instead of Docker:

- Manages Gitea, Woodpecker CI, Scrob, GoatCounter (3 instances), Caddy, PostgreSQL
- Declarative config in git with simple bash scripts
- Bootstrap script for initial setup, deploy script for updates
- Automated binary updates via GitHub releases API
- Simple, explicit, debuggable - no container orchestration overhead

[repo](https://github.com/ducks/burrow-systemd)
[blog post](https://jakegoldsborough.com/blog/2026/running-infrastructure-with-systemd/)

### JOBL + SRG - Structured Resume Tooling

A TOML-based resume format with strict validation and static generation:

- **JOBL**: Structured resume specification with version-aware parsing
- Type-safe validation with comprehensive error reporting
- Portable `.jobl` files for version control and collaboration
- **SRG**: Static generator converting JOBL to HTML and PDF
- Clean, professional templates optimized for screen and print

[JOBL repo](https://github.com/ducks/JOBL)
[SRG repo](https://github.com/ducks/SRG)

### Yaks - Virtual Currency for Discourse

A Discourse plugin implementing spendable in-forum currency:

- Topic pinning, boosting, and custom flair purchases
- Background jobs for transaction processing
- Integration with Discourse's user system and permissions
- Custom admin interface for currency management

[repo](https://github.com/ducks/discourse-yaks)
[part 1](https://jakegoldsborough.com/blog/2025/building-yaks-virtual-currency-part-1/)
[part 2](https://jakegoldsborough.com/blog/2025/building-yaks-virtual-currency-part-2/)
[part 3](https://jakegoldsborough.com/blog/2025/building-yaks-virtual-currency-part-3/)
[part 4](https://jakegoldsborough.com/blog/2025/building-yaks-virtual-currency-part-4/)

### Shelltrax - TUI Music Player

Lightweight terminal-based music player inspired by cmus:

- Smart metadata handling with directory-based album grouping
- Filename fallbacks for missing ID3 tags
- ZIP import for extracting albums from compressed files
- Search functionality with fuzzy matching
- Playback controls with autoplay and repeat modes
- macOS compatibility

[repo](https://github.com/ducks/shelltrax)
[blog post](https://jakegoldsborough.com/blog/2025/introducing-shelltrax/)

### Shellcast - TUI Podcast Player

Terminal-based podcast player with RSS/Atom feed support:

- Built with ratatui and crossterm
- Podcast discovery via gpodder.net integration
- Episode playback with ALSA/CPAL audio backend
- Feed refresh and episode tracking
- Pause/resume with proper state management
- Persistent library storage

[repo](https://github.com/ducks/shellcast)

## Interests

- Rust (TUI development, audio processing, systems programming)
- TypeScript, Node.js
- Ruby on Rails & Discourse plugin development
- Systems design & distributed systems
- Observability & monitoring (Prometheus, metrics exporters)
- Infrastructure automation (Docker, CI/CD, Makefiles)
- Developer tooling & CLI applications
- Music metadata standards (ID3, RSS/Atom feeds)
