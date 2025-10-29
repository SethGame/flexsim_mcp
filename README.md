# flexsim_mcp

MCP server for Flexsim

## Development Setup

This project uses [uv](https://docs.astral.sh/uv/) for fast Python package management and requires Python 3.11+.

### Prerequisites

- Python 3.11 or higher
- uv package manager

### Installation

1. Install uv (if not already installed):
```bash
pip install uv
```

2. Create a virtual environment and install dependencies:
```bash
uv sync --all-extras
```

This will:
- Create a virtual environment in `.venv` with Python 3.11
- Install all project dependencies
- Install development tools (ruff, mypy)

### Development Tools

- **Linting & Formatting**: `ruff` - Fast Python linter and formatter
- **Type Checking**: `mypy` - Static type checker

### Usage

Run linting:
```bash
uv run ruff check src/
```

Format code:
```bash
uv run ruff format src/
```

Type checking:
```bash
uv run mypy src/
```
