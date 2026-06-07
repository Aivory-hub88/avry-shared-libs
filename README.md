# avry-shared-libs

Shared libraries for the Aivory platform — common utilities, types, and SDK packages used across all services.

## Tech Stack

- Python 3.11+
- Shared modules (agents, database, LLM, models, utils)

## Directory Structure

```
avry-shared-libs/
└── app/
    ├── agents/       # Agent base classes
    ├── database/     # Database utilities
    ├── llm/          # LLM client wrappers
    ├── models/       # Shared data models
    ├── prompts/      # Prompt templates
    ├── routes/       # Common route utilities
    ├── services/     # Shared service logic
    ├── utils/        # General utilities
    ├── config.py     # Shared configuration
    └── model_config.py
```

## Usage

Import shared modules in other services:

```python
from app.utils import ...
from app.database import ...
```

## Install as Local Package

```bash
pip install -e .
```

## Part of Aivory

This service is part of the [Aivory platform](https://github.com/ClementHansel/aivory).
