# Python Data Access Utilities

This package provides utility functions for accessing our internal data infrastructure, including Azure Blob Storage and PostgreSQL databases.

## Directory Structure

```
.
├── requirements.txt        # Project dependencies
├── requirements-dev.txt    # Project development dependencies
├── setup.cfg               # Package configuration
├── pyproject.toml          # Package configuration
├── src/                    # Source code for utilities 
└── examples/               # Usage examples
```

## Developer Setup

1. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
pip install -r requirements-dev.txt
```

3. Install package in development mode:
```bash
pip install -e .
```

4. Set up the following environment variables in a `.env` file:
```
# TODO
```

### Pre-Commit

All code is formatted according to black and flake8 guidelines. The repo is set-up to use pre-commit. Before you start developing in this repository, you will need to run

```
pre-commit install
```

You can run all hooks against all your files using

```
pre-commit run --all-files
```

## Usage Example

```python
# TODO
```

For more examples, check the `examples/` directory.