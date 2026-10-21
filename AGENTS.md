# AGENTS.md

Instructions for AI coding agents working in this repository, and a map of how to use yonyon.ai from an agent.

## What this repository is

The GitHub profile repository of Yonatan Gross (`yonatangross/yonatangross`). It holds the profile `README.md` and its images in `assets/`. It is not an application: there is no build, no test suite and no package manifest to install.

## Rules for editing here

- Edit `README.md` and `assets/` only. Keep the layout and badge style that is already there.
- Do not state counts (stars, skills, agents, hooks) in new prose. The badges carry them; hand-written numbers go stale.
- Write plain sentences. No em dashes, en dashes or double hyphens in any text you add.
- Never add a credential, token, private repository name or internal URL. This repository is public.
- Do not add tracking parameters to links, except the existing `utm_source=github&utm_medium=profile` on the booking badge.
- Open a pull request; do not push to `main`.

## How to use yonyon.ai from an agent

yonyon.ai needs no sign-in, no payment and no API key. Pick the cheapest surface that answers the question.

| Goal | Call |
| --- | --- |
| One question, server side | `POST https://yonyon.ai/ask` with `{"query": "..."}` |
| Tool calling | MCP Streamable HTTP at `https://yonyon.ai/api/mcp` (tools: `ask_yonatan`, `browse_projects`, `book_intro_call`) |
| Documentation search | MCP Streamable HTTP at `https://yonyon.ai/api/mcp/docs` (tools: `list_docs`, `search_docs`, `read_docs`) |
| Skills and when to use them | `https://yonyon.ai/.well-known/agent-skills/index.json` |
| Site index for agents | `https://yonyon.ai/llms.txt` |
| Site level guidance | `https://yonyon.ai/.well-known/agent-instructions.md` |

The Agent Plugins manifest for these surfaces is `plugin.json` in this repository. The MCP server card is at `https://yonyon.ai/.well-known/mcp/server-card.json`.

## OrchestKit

OrchestKit is the open-source Claude Code plugin by the same author: `https://github.com/yonatangross/orchestkit`.

```bash
/plugin marketplace add yonatangross/orchestkit
/plugin install ork
```

Its own agent instructions are in that repository's `AGENTS.md`.

## Contact

Email hi@yonyon.ai, or book a free 15 minute intro call at https://cal.com/yonyon.
