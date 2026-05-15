# SLIM — Claude Code Plugin

Adds a `/slim` skill to Claude Code for converting documents to [SLIM format](https://slimformat.org) (Structured LLM Instruction Markup v2.0).

## What it does

- **Convert** Markdown, JSON, or plain text → SLIM `.slm` format
- **Validate** existing `.slm` files against the SLIM v2 spec
- **Report** token savings (typically 30–45% reduction)
- **Write** new SLIM documents, agent configs, system prompts, RAG docs

## Install

```bash
claude plugin install https://github.com/nagandla-sasidhar/slim-claude-plugin
```

## Usage

Trigger the skill by saying anything like:

- `"convert this to SLIM"`
- `"make this SLIM"`
- `"is this valid SLIM?"`
- `"write a SLIM agent config for..."`
- `/slim` (explicit slash command)

## About SLIM

SLIM v2.0 is a token-efficient format for AI documents. It replaces verbose Markdown with terse, structured syntax that LLMs parse more efficiently.

- **Website**: https://slimformat.org
- **Playground**: https://slimformat.org/playground.html
- **Docs**: https://slimformat.org/docs.html
- **Spec repo**: https://github.com/nagandla-sasidhar/TAML

## License

MIT © 2026 Sasidhar Nagandla
