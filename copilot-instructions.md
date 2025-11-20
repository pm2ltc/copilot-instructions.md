# Copilot Instructions

## General
- Use Python 3.12.
- Always include type hints.
- Keep functions small and purpose-driven.
- Prefer composition over inheritance.
- Avoid global state.

## Backend Standards
- Use FastAPI for API development.
- Use Pydantic BaseModel for all request and response schemas.
- Use async endpoints.
- Use HTTPX for async HTTP calls.
- Include error handling with custom exceptions and FastAPI exception handlers.
- Follow REST conventions: `/resource`, `/resource/{id}`.

## Testing
- Use pytest for all tests.
- Use pytest-asyncio for async functions.
- Mock external calls with `httpx.MockTransport`.
- Maintain >85% coverage when generating tests.

## DevOps Guidelines
- Use Terraform for IaC.
- Use Dockerfiles with multi-stage builds.
- Use GitHub Actions for CI/CD.
- Prefer kubectl and kubernetes Python client for cluster interactions.
- Log using the `structlog` library with JSON output.

## Style
- Follow Black formatting and Ruff linting.
- Use snake_case for functions and variables.
- Use PascalCase for class names.
- Use descriptive commit messages and docstrings.

## Documentation
- Generate docstrings in Google style.
- Include endpoint examples when generating API routes.
