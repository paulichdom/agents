# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Common Commands

- **Install dependencies:** `pipenv install --dev`
- **Run the main application:** `pipenv run python main.py`
- **Run tests:** This project does not have a configured test runner. A suggested test command is `pipenv run pytest`.
- **Lint code:** This project does not have a configured linter. A suggested lint command is `pipenv run pylint .`

## Code Architecture

This appears to be a Python application that uses the `langchain` and `langchain-openai` libraries. The entry point is likely `main.py`. The `Pipfile` manages the project's dependencies.
