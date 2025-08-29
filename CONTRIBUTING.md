# Contributing to Bitget API Python Client

Thank you for considering contributing to this project!  
We welcome issues, feature requests, and pull requests to improve the Bitget API Python client.

---

## How to Contribute

### Reporting Issues
- Use the [GitHub Issues](../../issues) tab to report bugs or request new features.
- When reporting a bug, please include:
  - Your Python version
  - Operating system
  - A minimal code example that reproduces the issue
  - The expected and actual behavior

### Suggesting Features
- Before suggesting a new feature, please check if it has already been discussed in the Issues.
- Provide a clear use case and why it would be valuable for the project.

---

## Development Setup

1. Fork the repository and clone your fork:
   ```bash
   git clone https://github.com/tty666/bitget-api-client.git
   cd bitget-api-client
   ```

2. Create a new virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   pip install -r requirements-dev.txt
   ```

---

## Coding Guidelines

- Follow **PEP 8** for Python style.
- Use **type hints** everywhere.
- Each public method must have a **Google-style docstring** (see existing methods for examples).
- Run code formatters before committing:
   ```bash
   black .
   isort .
   flake8 .
   ```
- Write tests for new functionality.

---

## Submitting a Pull Request

1. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature/my-new-feature
   ```

2. Commit your changes with a clear message:
   ```bash
   git commit -m "Add support for XYZ endpoint"
   ```

3. Push your branch:
   ```bash
   git push origin feature/my-new-feature
   ```

4. Open a Pull Request against the `v0.1.x` development branch, not `stable`.

---

## Tests

- Tests should be added under the `tests/` directory.
- Run all tests before submitting a PR:
   ```bash
   pytest -v
   ```

---

## Code of Conduct

This project is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).  
By participating, you are expected to uphold it.