# ow-marketplace

Oriens World plugin marketplace for Claude Desktop, Claude Code, and Codex CLI.
It publishes portable tools for software collaboration and Obsidian knowledge work.

## Plugins

| Plugin | Description |
|--------|-------------|
| [ow-obsidian](https://github.com/oriensworld/ow-obsidian) | Vault-agnostic Obsidian knowledge workflows for research, ingestion, retrieval, linked-note authoring, and vault maintenance. |
| [ow-plugin](https://github.com/oriensworld/ow-plugin) | Cross-platform development collaboration toolkit with Git automation, planning, repository onboarding, UI/UX guidance, and MCP utilities. |

## Usage

### Claude Desktop

Settings → Plugins → Add Marketplace → `oriensworld/ow-marketplace`

### Claude Code

```bash
claude plugin marketplace add oriensworld/ow-marketplace
claude plugin install @ow-marketplace/ow-obsidian
claude plugin install @ow-marketplace/ow-plugin
```

### Codex CLI

```bash
codex plugin marketplace add oriensworld/ow-marketplace
codex plugin add ow-obsidian@ow-marketplace
codex plugin add ow-plugin@ow-marketplace
```

To use `ow-obsidian`, start a new Claude Code or Codex session from the root of
an actual Obsidian vault. The plugin repository is not itself a vault, and no
per-vault skill copies, links, or configuration are required.
