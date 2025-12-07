# CLAUDE.md

This file provides guidance to Claude Code when working in this repository.

## Project Overview

This is the official Claude Code repository - Anthropic's agentic coding CLI tool. The repository contains the public-facing documentation, official plugins, example configurations, and utility scripts for Claude Code.

## Repository Structure

```
├── .claude/
│   └── commands/           # Custom slash commands for this repo
├── plugins/                # Official Claude Code plugins
│   ├── agent-sdk-dev/      # Agent SDK development toolkit
│   ├── code-review/        # Automated PR review
│   ├── commit-commands/    # Git workflow automation
│   ├── feature-dev/        # Feature development workflow
│   ├── hookify/            # Custom hook creation
│   ├── plugin-dev/         # Plugin development toolkit
│   ├── pr-review-toolkit/  # Comprehensive PR review agents
│   ├── security-guidance/  # Security pattern monitoring
│   └── ...                 # Additional plugins
├── examples/
│   └── hooks/              # Example hook implementations
├── scripts/                # Utility scripts (issue management)
└── README.md               # Main documentation
```

## Plugin Development Guidelines

When working with plugins in this repository:

1. **Follow the standard plugin structure:**
   ```
   plugin-name/
   ├── .claude-plugin/
   │   └── plugin.json      # Plugin metadata (required)
   ├── commands/            # Slash commands (optional)
   ├── agents/              # Specialized agents (optional)
   ├── skills/              # Agent skills (optional)
   ├── hooks/               # Event handlers (optional)
   ├── .mcp.json            # MCP server config (optional)
   └── README.md            # Documentation (required)
   ```

2. **Plugin metadata** must include name, version, description, and author
3. **Document all commands and agents** with clear usage examples
4. **Test plugins** in isolation before integration

## Custom Commands

Available slash commands in this repository:

- `/commit-push-pr` - Commit changes, push branch, and create a PR
- `/dedupe` - Find duplicate GitHub issues
- `/oncall-triage` - Triage GitHub issues and label critical ones

## Code Conventions

- Use TypeScript for scripts when type safety is needed
- Follow existing patterns in the codebase
- Keep plugin READMEs comprehensive and up-to-date
- Use descriptive commit messages that explain the "why"

## Testing

- Test plugin commands before committing
- Verify hook implementations don't break normal workflows
- Check agent responses for accuracy and helpfulness

## Common Tasks

### Adding a new plugin
1. Create a new directory under `plugins/`
2. Add `.claude-plugin/plugin.json` with metadata
3. Implement commands, agents, or hooks as needed
4. Write comprehensive README.md
5. Update `plugins/README.md` to include the new plugin

### Modifying existing plugins
1. Read the plugin's README and understand its purpose
2. Make targeted changes without breaking existing functionality
3. Update documentation if behavior changes

## External Resources

- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code/overview)
- [Plugin System Documentation](https://docs.claude.com/en/docs/claude-code/plugins)
- [Report Issues](https://github.com/anthropics/claude-code/issues)
