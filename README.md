# Homebrew Tap — Nesbot

Homebrew formulae for the [Nesbot](https://github.com/NesloTechnologies/nesbot) CLI.

## Install

```sh
brew tap NesloTechnologies/nesbot
brew install nesbot
```

## Upgrade

```sh
brew upgrade nesbot
```

## Verify

```sh
nesbot doctor --repo .
```

## What is Nesbot?

Deterministic, policy-driven engineering automation. Nesbot enforces engineering standards across repositories through structured lawpacks, produces auditable review artifacts, and integrates directly into GitHub pull request workflows.

- **PR Review** — AI-powered code review against configured lawpacks
- **Task Engine** — structured planning, implementation, and review lifecycle
- **Lawpack Scanner** — discovers conventions and generates draft standards

## Requirements

- macOS (Apple Silicon)
- Node.js 22+ (installed automatically as a Homebrew dependency)
