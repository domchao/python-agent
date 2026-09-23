# python-agent

A Python AI Agent monorepo (heavily inspired by [Pi](https://github.com/earendil-works/pi/tree/main)) - built for fun.

## Commands

| Task | Command |
|------|---------|
| Install everything, all packages | `uv sync --all-packages` (run from root) |
| Install/sync just one package | `uv sync --package coding_agent` |
| Run the coding agent CLI | `uv run --package coding_agent coding-agen`t` |
| Run tests for one package only | `uv run --package agent_core pytest` |
| Add an external dep to one package | `cd packages/ai && uv add httpx` |
| Re-lock after any dependency change | `uv lock` (always operates on the whole workspace) |
