# VeigaPunk LLM Wiki — Public Static Site

**Status: shipping**

This is the public static face of [VeigaPunk/llm-wiki](https://github.com/VeigaPunk/llm-wiki) (private knowledge vault).

## What this is

A Karpathy-style LLM Wiki: compiled, interlinked Markdown knowledge base maintained by agents, rendered for humans as a browsable static site.

- **Source of truth**: private `VeigaPunk/llm-wiki` (Obsidian vault + agent skills)
- **Public surface**: this repo + GitHub Pages
- **Pattern**: raw sources (immutable) → wiki pages (LLM-compiled, cross-linked) → static HTML

## Live

- Repo: https://github.com/VeigaPunk/llm-wiki-site
- Pages (enable in Settings): https://veigapunk.github.io/llm-wiki-site/

## Next frontier moves

1. Make `llm-wiki` public or publish selected branches as public artifacts.
2. Add Quartz / MkDocs / simple Markdown→HTML pipeline + search index.
3. Enable GitHub Pages on this repo (Settings → Pages → Deploy from branch main / root or /docs).
4. Wire CI to rebuild on vault changes.
5. Emit `llms.txt` for agent consumption.

## Axes (godspeed)

- Public accessibility ↑
- Fidelity to compiled wiki structure =
- Zero-runtime static hosting ↑
- Agent-friendly (llms.txt) ↑

Built under godspeed. Keep moves that improve any axis and harm none.
