# Opus Standard Prompt Library

**Goal:** Make the experience of every model approximate Claude Opus 4.6 as closely as possible.

**Core strategy:** Explicitly compensate for each model's known weaknesses via prompt

## What this repo contains

- One `.md` file per model under [`prompts/`](./prompts)
- The full mirrored article in [`article.md`](./article.md)
- A concise index and context in this README

## Baseline idea

- strong intent recognition
- high first-pass accuracy
- better cross-file / structural reasoning
- intellectual honesty
- low sycophancy / low over-compliance
- deep reasoning
- stable long-context behavior

## Models

| Model | File |
|---|---|
| Claude Sonnet 4.6 | [`prompts/01-claude-sonnet-46.md`](./prompts/01-claude-sonnet-46.md) |
| GPT-5.4 | [`prompts/02-gpt-54.md`](./prompts/02-gpt-54.md) |
| GPT-5.3-Codex | [`prompts/03-gpt-53-codex.md`](./prompts/03-gpt-53-codex.md) |
| Gemini 3.1 Pro | [`prompts/04-gemini-31-pro.md`](./prompts/04-gemini-31-pro.md) |
| GLM-5 | [`prompts/05-glm-5.md`](./prompts/05-glm-5.md) |
| Kimi K2.5 | [`prompts/06-kimi-k25.md`](./prompts/06-kimi-k25.md) |
| MiniMax M2.5 | [`prompts/07-minimax-m25.md`](./prompts/07-minimax-m25.md) |
| Gemini 3 Flash | [`prompts/08-gemini-3-flash.md`](./prompts/08-gemini-3-flash.md) |
| Gemini 3.1 Flash-Lite | [`prompts/09-gemini-31-flash-lite.md`](./prompts/09-gemini-31-flash-lite.md) |
| GPT-5.3 Instant | [`prompts/10-gpt-53-instant.md`](./prompts/10-gpt-53-instant.md) |
| GPT-5.4 Mini | [`prompts/11-gpt-54-mini.md`](./prompts/11-gpt-54-mini.md) |
