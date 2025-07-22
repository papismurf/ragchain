# Project Overview

This is a Python-based RAG (Retrieval-Augmented Generation) chain project in early development. The project uses:
- **uv** for dependency management and packaging
- **Python 3.12+** as the minimum runtime
- **Jupyter notebooks** for experimentation (ragchain.ipynb)
- **LangSmith** for tracing and monitoring (configured in notebook)

## Project Structure

```
ragchain/
├── main.py           # Entry point with basic hello world
├── ragchain.ipynb    # Jupyter notebook for experimentation
├── pyproject.toml    # Project configuration and dependencies
├── uv.lock          # Dependency lockfile
└── README.md        # 
```

## Development Commands

### Environment Setup
```bash
# Install dependencies
uv sync

# Run the main application
uv run python main.py
```

### Jupyter Development
```bash
# Start Jupyter notebook for experimentation
jupyter notebook ragchain.ipynb
```

## Architecture Notes

- The project is in initial stages with minimal dependencies
- LangSmith integration is configured for tracing RAG operations

## Dependencies

#TODO
