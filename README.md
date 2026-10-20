# crypto-cap

A Python project using a `src/` layout.

## Setup

Create and activate a virtual environment, then install the package and development tools:

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -e ".[dev]"
```

## Checks

```sh
python -m pytest
python -m ruff check .
```