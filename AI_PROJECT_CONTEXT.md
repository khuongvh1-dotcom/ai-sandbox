# AI Project Context — ai-sandbox

A tiny Python project used to test the AI Dev Orchestrator end-to-end.

## Architecture
- `calc.py` — plain Python module with small functions.
- `tests/` — pytest tests. Tests import modules from the repo root.

## Commands
- Install: `pip install pytest`
- Test: `pytest -q`

## Conventions
- Keep functions small and pure. No external dependencies.
- Do not change `.github/**` or CI config.
- Match existing style (4-space indent, snake_case).
