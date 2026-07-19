# ow-marketplace

Oriens World plugin marketplace for Claude Desktop and Claude Code.

## Plugins

| Plugin | Version | Description |
|--------|---------|-------------|
| [ow-plugin](https://github.com/oriensworld/ow-plugin) | 0.5.0 | MCP tools, Git helpers, and reusable development workflows |

## ow-plugin Features

### Skills (slash commands)

| Skill | Description |
|-------|-------------|
| `/greet` | Greet the user and show system info |
| `/echo` | Test MCP round-trip connectivity |
| `/sysinfo` | Display machine information |
| `/git-commit` | Auto-generate conventional commit messages |
| `/git-rollback` | Interactive branch rollback to historical versions |
| `/git-worktree` | Manage Git worktrees alongside your project |
| `/git-clean-branches` | Find and clean merged/stale branches |
| `/feat` | Structured feature development workflow |
| `/workflow` | Six-stage dev workflow (Research → Design → Plan → Execute → Optimize → Review) |
| `/init-project` | Generate AI-facing project context (CLAUDE.md) |
| `/init-architect` | Adaptive repository scan with architecture docs |
| `/planner` | Break complex projects into phased plans |
| `/diagnostics` | Verify plugin health and MCP connectivity |
| `/get-current-datetime` | Return accurate local timestamp |
| `/ui-ux-designer` | UI/UX design guidance and specifications |

### MCP Server (`@oriensworld/ow-server`)

- `echo` — Round-trip communication test
- `get_system_info` — System hostname, platform, arch, memory, uptime

### Platform Support

| Component | Claude Code | Claude Desktop | Codex |
|-----------|:-----------:|:--------------:|:-----:|
| Skills | Yes | Yes | Yes |
| Agents | Yes | — | Yes |
| Hooks | Yes | — | — |
| MCP Server | Yes | — | — |

## Installation

**Claude Desktop:**
Settings → Plugins → Add Marketplace → `oriensworld/ow-marketplace`

**Claude Code:**
```bash
claude plugin marketplace add oriensworld/ow-marketplace
claude plugin install @ow-marketplace/ow-plugin
```

## Requirements

- Node.js >= 18 (for MCP server)
- No API keys or authentication needed
