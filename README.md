# ow-marketplace

Oriens World plugin marketplace for Claude Desktop and Claude Code.

## Plugins

| Plugin | Description |
|--------|-------------|
| [ow-plugin](https://github.com/oriensworld/ow-plugin) | System info and greeting — cross-platform proof-of-concept |
| [ow-obsidian](https://github.com/oriensworld/ow-obsidian) | Portable Obsidian knowledge workflows for Claude Code and Codex |

## Usage

**Claude Desktop:**
Settings → Plugins → Add Marketplace → `oriensworld/ow-marketplace`

**Claude Code:**
```bash
claude plugin marketplace add oriensworld/ow-marketplace
claude plugin install @ow-marketplace/ow-plugin
claude plugin install @ow-marketplace/ow-obsidian
```

**Codex CLI:**
```bash
codex plugin marketplace add oriensworld/ow-marketplace
codex plugin add ow-plugin@ow-marketplace
codex plugin add ow-obsidian@ow-marketplace
```

Start a new Codex session from an actual Obsidian vault after installation. No
per-vault skill copies, links, or configuration are required.
