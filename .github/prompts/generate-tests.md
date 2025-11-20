Generate pytest unit tests for the selected Python file.

Rules:
- Use pytest-asyncio for async functions.
- Mock external HTTP calls with httpx.MockTransport.
- Include both success and failure scenarios.
- Use fixtures for common resources.
- Ensure >85% coverage if applicable.
