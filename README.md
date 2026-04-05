# wony-skills

Personal Claude Code plugin marketplace.

## Plugins

| Plugin | Type | Description |
|--------|------|-------------|
| `wony-custom-skills` | Skills | doc-coauthoring |
| `mcp-basic` | MCP | context7, sequential-thinking |

## Setup (per machine)

Add to `~/.claude/settings.json`:

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

Then install:

```
/plugin install wony-custom-skills@wony-skills
/plugin install mcp-basic@wony-skills
```
