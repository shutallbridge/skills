# skills

Shu Takahashi's personal agent skills.

| Skill                                         | What it does                                                         |
| --------------------------------------------- | -------------------------------------------------------------------- |
| [literature-add](skills/literature-add)       | Add a paper to the library from a PDF, DOI, arXiv ID, or URL         |
| [literature-search](skills/literature-search) | Search and answer questions across the papers in your library        |
| [literature-manage](skills/literature-manage) | Set up the library, delete or rename papers, validate, rebuild index |

The `literature` plugin bundles these three skills with the [literature-tools](https://github.com/shutallbridge/literature-tools) MCP server.

## Install

Any agent (skills only):

```bash
npx skills add shutallbridge/skills
```

Claude Code (skills plus their MCP servers):

```
/plugin marketplace add shutallbridge/skills
/plugin install literature@shutallbridge
```
