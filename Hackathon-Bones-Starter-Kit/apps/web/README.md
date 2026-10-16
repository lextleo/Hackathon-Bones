# Web app

Frontend entry point. Choose a framework only if the project benefits from one; do not add a frontend service if a CLI, mobile app, or device UI is enough.

Suggested layout once implemented:

```text
web/
├── src/            # routes, views, components
├── public/         # static public assets
├── tests/          # UI tests, if useful
├── .env.example    # browser-safe configuration only
└── README.md       # exact install, dev, test, and build commands
```

Document the supported runtime, package manager, local start command, production build command, and where the UI gets its data. Never embed private server API keys in frontend environment variables.
