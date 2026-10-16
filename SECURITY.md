# Security notes

This is a starter template, not a security audit or a guarantee of production readiness.

- Never commit API keys, passwords, private certificates, personal data, or production `.env` files.
- Use local fake data in screenshots and demo recordings.
- Give tokens only the permissions required for the task; rotate any secret that was accidentally exposed.
- Validate input at system boundaries, especially when accepting uploads, device messages, or model output.
- Do not expose debug consoles, database ports, or device-control endpoints publicly without appropriate access controls.
- Before deployment, review dependencies, authentication, authorization, logging, data retention, and the threat model for the actual project.

For a private vulnerability report, use the repository's private vulnerability reporting feature if enabled, or contact the maintainer through a trusted private channel. Do not publish exploitable details in a public issue.
