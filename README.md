<img src="docs/images/wire_logo_transparent.png" alt="Wire Framework" width="220">

# Wire Framework — Gemini CLI Extension

Wire is a structured delivery system for data platform engagements, built on top of Gemini CLI. It encodes analytics engineering methodology as workflow specifications that the AI reads before generating anything — consistent output, traceable to requirements, automatically validated.

---

## Documentation

- [Documentation site](https://wire-plugin.readthedocs.io/en/latest/) — full documentation with search, covering all release types, commands, skills, and MCP servers
- [User Guide](GEMINI.md) — command reference and extension usage

---

## Installation

```bash
gemini extensions install https://github.com/rittmananalytics/wire-extension
```

All `/wire:*` commands are available immediately after installation.

---

## Quick start

```
/wire:new                          — Create a new engagement
/wire:status                       — Check status of all active engagements
/wire:autopilot <sow-path>         — Autonomous end-to-end execution from SOW
```

---

## Release types

Wire supports 12 release types covering the full data platform delivery lifecycle: Discovery Shape-Up, Discovery SOP, Kick-off Deck, Full Platform, Pipeline/dbt, dbt Development, Dashboard Extension, Dashboard First, Enablement, Agentic Commerce, Platform Migration, and Agentic Data Stack.

See the [documentation site](https://wire-plugin.readthedocs.io/en/latest/) for full coverage of each release type, all commands, and configuration options.

---

## Claude Code version

If you use Claude Code rather than Gemini CLI, install the Wire plugin instead:

```
/plugin marketplace add rittmananalytics/wire-plugin
/plugin install wire@rittman-analytics
/reload-plugins
```

---

## Issues and support

File issues at [github.com/rittmananalytics/wire-extension/issues](https://github.com/rittmananalytics/wire-extension/issues).
