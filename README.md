# Codex Plugins

A Codex plugin marketplace for Aaron Friel's Codex plugins.

## Install With Codex CLI

```sh
codex plugin marketplace add AaronFriel/codex-plugins --ref main
codex plugin add plans-md@codex-plugins
codex plugin add skill-deslop@codex-plugins
```

## Install With Codex App

In Codex App, add a marketplace:

- Source: `AaronFriel/codex-plugins`
- Git ref: `main`
- Sparse paths: leave empty

Then install `PLANS.md` or `Deslop` from the marketplace.

Plugins:

- `plans-md`: make Codex get work done with plan files.
- `skill-deslop`: revise unclear writing into specific prose.
