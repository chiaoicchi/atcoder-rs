# AtCoder Environment for Rust

## Environment

- Rust 1.89.0 (pinned via [fenix](https://github.com/nix-community/fenix))
- [cargo-compete](https://github.com/qryxip/cargo-compete) for contest management
- Nix flake for reproducible development environment

## Setup

### Prerequisites

- [Nix](https://nixos.org/) with flakes enabled
- [direnv](https://github.com/direnv/direnv) (optional)

### Getting Started

Enter the development environment:

```bash
nix develop
```

Or, if you have direnv set up:

```bash
direnv allow
```

## Dependencies

- [proconio](https://crates.io/crates/proconio)
- [itertools](https://crates.io/crates/itertools)
