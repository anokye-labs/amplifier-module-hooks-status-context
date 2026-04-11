# Amplifier Module Hooks Status Context

Injects environment info (working directory, platform, OS, date), session context, and optional git status into agent context before each prompt. Ensures agent has fresh contextual information for decisions.

## Tech Stack
- Python 3.11+
- Part of the Amplifier framework ecosystem

## Development
```bash
pip install -e ".[dev]"
python -m pytest
```

## Structure
This is an Amplifier hooks module that provides status context hooks.

## Conventions
- Follow existing code patterns
- Include type hints
- Write docstrings for public functions
