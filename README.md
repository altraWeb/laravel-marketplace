# altraWeb Laravel Plugin Marketplace

Neutral host repo for the `laravel-{stack}-superpowers` Claude Code plugin family.

## Available plugins

| Plugin | Stack | Status |
|---|---|---|
| `laravel-livewire-superpowers` | Laravel + Livewire 4 + Flux Pro v2 + Pest 4 | Released (v3.0.0-alpha.1+) |
| `laravel-vue-superpowers` | Laravel + Vue 3 (Composition API) + Inertia v2 + Pest 4 | Planned |

## Install

```bash
claude /plugin marketplace add altraWeb/laravel-marketplace
claude /plugin install laravel-livewire-superpowers@altraweb-laravel
```

For the Vue variant when it ships:

```bash
claude /plugin install laravel-vue-superpowers@altraweb-laravel
```

## Why a separate marketplace repo?

Previously the marketplace lived inside the `laravel-superpowers` plugin repo (now renamed `laravel-livewire-superpowers`). When the Vue variant was planned, that arrangement would have made the Livewire repo the implicit "primary" host. Splitting the marketplace into a neutral repo keeps the two plugin variants symmetric.

## Migrating from v2 of laravel-superpowers

See [`UPGRADING.md`](https://github.com/altraWeb/laravel-livewire-superpowers/blob/main/UPGRADING.md) on the renamed plugin repo for the migration steps.
