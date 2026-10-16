# Tests

Use the cheapest test that gives meaningful confidence. Not every hackathon needs a large test suite, but every project should verify its critical path.

Suggested layers:

- **Unit:** pure functions, calculations, parsing, validation, state transitions.
- **Integration:** API/database/model/service boundaries and their failure cases.
- **Hardware / simulation:** protocol, sensor scaling, controller behaviour, safety limits.
- **Acceptance:** the exact user journey shown in the demo.

Write down the test command and any required fixtures. Keep a reproducible known-good demo path.
