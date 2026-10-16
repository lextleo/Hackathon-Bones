# API / component contract

Use this for HTTP endpoints, events, shared functions, or messages between the UI, backend, model, and device. Delete it if the project has no meaningful interface boundary.

## Contract table

| Name | Method / type | Input | Output | Failure behaviour |
| --- | --- | --- | --- | --- |
| `/health` | `GET` | none | service status | non-2xx if unavailable |
| `[replace]` |  |  |  |  |

## Example response shape

```json
{
  "ok": true,
  "data": {},
  "error": null,
  "requestId": "example-only"
}
```

Replace this example with the actual contract. Do not return stack traces, API keys, or sensitive internal details to clients.

## Interface rules

- Name fields consistently and document units.
- Define required versus optional inputs.
- State timeouts, retries, and rate limits where applicable.
- Version the contract if a breaking change will affect parallel work.
- Keep example payloads small and free of real personal data.
