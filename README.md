# cf_ai_benw

An AI-powered chat agent built on Cloudflare's developer platform using the Agents SDK.

## Live Demo

https://cf-ai-benw.kur1sho.workers.dev

## What it does

A fully-featured AI chat agent with:

- Streaming AI responses powered by Workers AI
- Persistent conversation memory via Durable Objects
- Weather lookup tool
- Calculator with human-in-the-loop approval
- Task scheduling (one-time, delayed, cron)
- Image understanding (drag and drop an image)
- MCP server support
- Real-time WebSocket connection with automatic reconnection

## Stack

- Cloudflare Workers
- Cloudflare Workers AI
- Durable Objects (persistent state and memory)
- Agents SDK (AIChatAgent)
- TypeScript / React

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:5173

## Deploy

```bash
npm run deploy
```
