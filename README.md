# By Mischa

Marketplace for Mischa Sigtermans's Claude Code plugins. One marketplace add unlocks them all.

```
/plugin marketplace add mischasigtermans/by-mischa
```

## What's here

- **[Parley](https://github.com/mischasigtermans/parley)** — cross-session bridge. Each Claude Code project becomes a callable agent.
- **[Personas](https://github.com/mischasigtermans/claude-personas/tree/main/manager)** — long-lived advisor personas with project-scoped threads and durable memory.
- **[Steve Jobs](https://github.com/mischasigtermans/claude-personas/tree/main/personas/steve-jobs)** — persona advisor. Product, leadership, strategy.
- **[Taylor Otwell](https://github.com/mischasigtermans/claude-personas/tree/main/personas/taylor-otwell)** — persona advisor. Laravel code reviews.
- **[Raymond Hettinger](https://github.com/mischasigtermans/claude-personas/tree/main/personas/raymond-hettinger)** — persona advisor. Python code reviews.
- **[David Tolnay](https://github.com/mischasigtermans/claude-personas/tree/main/personas/david-tolnay)** — persona advisor. Rust code reviews.
- **[Ralph](https://github.com/mischasigtermans/ralph)** — autonomous loop runner.

## Installing a plugin

After adding the marketplace, install whichever plugins you want:

```
/plugin install parley@by-mischa
/plugin install personas@by-mischa
/plugin install steve-jobs@by-mischa
```

Each plugin has its own README with full installation requirements and quick start. Personas requires Parley. Each persona plugin requires Personas, which requires Parley.

## Adding to this marketplace

Open a PR to this repo with your plugin entry added to `.claude-plugin/marketplace.json`. See the existing entries for the source-type pattern.

## License

MIT. See [LICENSE](LICENSE). Each listed plugin keeps its own license; check the linked repo.
