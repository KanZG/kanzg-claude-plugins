# kanzg-claude-plugins

KanZG's plugin marketplace for Claude Code.

## Installation

```
/plugin marketplace add KanZG/kanzg-claude-plugins
```

## Available Plugins

### sprint-loop

Sprint-based autonomous development loop for Claude Code. Plans sprints with DoD, executes via AgentTeam, and auto-transitions on approval.

```
/plugin install sprint-loop@kanzg-claude-plugins
```

**Source:** [KanZG/loop-plugin](https://github.com/KanZG/loop-plugin)

## Adding New Plugins

To add a new plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json`:

```json
{
  "name": "my-plugin",
  "source": {
    "source": "github",
    "repo": "KanZG/my-plugin-repo"
  },
  "description": "Description of the plugin",
  "version": "1.0.0",
  "category": "productivity",
  "tags": ["tag1", "tag2"]
}
```

## License

MIT
