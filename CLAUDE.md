# Project Context: CLAUDE.md

## Project Overview

- **Name**: API-Template
- **Description**: This is a boilerplate project. Project dependencies are managed by `uv` (see `pyproject.toml`) and
  allows the end user to FastAPI projects out of the box. Comes with frontend too. The devcontainer is
  already set up for them with some default libraries. Claude is installed by default.
- **Tech Stack**: Python, FastAPI
- **Current Status**: Boilerplate

## Coding Standards

- **Language Style**: Ruff for Python
- **Naming Conventions**: snake_case for variables, PascalCase for classes
- **Testing Strategy**: 80% coverage required, TDD approach

## CI/CD Context

- **Platform**: Docker containers, GitHub Actions
- **Secrets Management**: Stored in GitHub Secrets, never committed

## AI Interaction Guidelines

- **Role**: You are an expert senior developer helping with refactoring and feature implementation.
- **Constraints**:
    - Do not remove existing tests unless explicitly asked.
    - Prefer standard library functions over external dependencies.
    - Always explain *why* a change is suggested.
- **Output Format**:
    - Provide code blocks with language tags.
    - Include a brief summary of changes before the code.
    - Mention any breaking changes immediately.