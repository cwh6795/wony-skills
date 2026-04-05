# wony-skills

Personal Claude Code plugin marketplace.

## Plugins

| Plugin | Type | Description |
|--------|------|-------------|
| `wony-custom-skills` | Skills | doc-coauthoring |
| `mcp-basic` | MCP | context7, sequential-thinking |

## Quick Install

```
/plugin marketplace add cwh6795/wony-skills
/plugin install wony-custom-skills@wony-skills
/plugin install mcp-basic@wony-skills
```

## Manual Setup

Alternatively, add the marketplace directly to `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "wony-skills": {
      "source": {
        "source": "github",
        "repo": "cwh6795/wony-skills"
      }
    }
  }
}
```

Then run the install commands from Quick Install above.
