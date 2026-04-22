# PROMPTS.md

Claude (claude.ai) was used as a coding assistant during development.

## Prompts used

- "I am doing an assignment for a Cloudflare internship position, here is the documentation, point me to where I might start"
- "How do I deploy this to Cloudflare Workers?"
- "I'm having an issue with the Wrangler Auth, I'm using Brave as my browser, what possible reasons could be causing this issue as it's consistently happening? [screenshot of error text]"

## System prompt (sent to the LLM on every request)

See `src/server.ts` — the system prompt configures the agent's behaviour, available tools, and scheduling capabilities.