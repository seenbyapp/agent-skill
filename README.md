# AI search visibility by Seenby

AI search visibility skill for AI agents. `SKILL.md` teaches an agent to use Seenby's MCP server
(`https://seenbyapp.com/mcp`) or REST API for AI visibility tracking and LLM brand monitoring: brand
mentions in AI answers from ChatGPT, Perplexity, Gemini, Google AI Mode and Google AI Overviews, who is
named instead and which pages each answer cites, as input for generative engine optimization (GEO).

```sh
npx skills add seenbyapp/agent-skill
```

Connect the MCP server separately: add `https://seenbyapp.com/mcp` in a remote MCP client, or run
`npx -y seenby-mcp` for a stdio client with Node.js 22+.

[Website](https://seenbyapp.com) · [MCP repository](https://github.com/seenbyapp/mcp-server)
