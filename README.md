# By Mischa

Marketplace for my Claude Code plugins. One marketplace add unlocks them all.

```
/plugin marketplace add mischasigtermans/by-mischa
```

## What's here

- **[Library](https://github.com/mischasigtermans/claude-library)**: local searchable mirror of your Claude chats, readable from any Code session.
- **[Parley](https://github.com/mischasigtermans/claude-parley)**: talk to your other Claude Code projects from any session.
- **[Personas](https://github.com/mischasigtermans/claude-personas)**: a growing library of field-expert advisors plus the dispatcher that runs them. Each persona installs as its own plugin; see the [Claude Personas index](https://github.com/mischasigtermans/claude-personas#personas) for the current set.
- **[Ralph](https://github.com/mischasigtermans/claude-ralph)**: an opinionated take on the Ralph autonomous loop. Describe a feature, walk away, come back to commits.

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
