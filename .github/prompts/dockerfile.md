Generate a Dockerfile for a Python app.

Rules:
- Use multi-stage builds.
- Base image: python:3.12-slim.
- Install dependencies using uv or pip.
- Create a non-root user.
- Use environment variables for configuration.
- Keep the final image as small as possible.
