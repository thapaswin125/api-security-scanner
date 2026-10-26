API SCANNER

> Full-stack API vulnerability scanner targeting the OWASP API Security Top 10 with configurable scan modules and a React dashboard.

*Learn docs here: [learn modules](#learn).*

## Project Attribution

This repository is maintained by [thapaswin125](https://github.com/thapaswin125) as an adapted and independently published version of the
[original API security scanner](https://github.com/CarterPerez-dev/Cybersecurity-Projects/tree/main/PROJECTS/intermediate/api-security-scanner).
The original project attribution and AGPLv3 license are preserved.

## What It Does

- Scans REST APIs against OWASP API Security Top 10 vulnerability categories
- Tests for authentication bypass, injection flaws, IDOR, and rate limiting weaknesses
- SQLi, authentication, IDOR, and rate limit scanner modules with configurable payloads
- JWT auth with bcrypt password hashing and session management
- Scan history tracking with detailed vulnerability reports per endpoint
- Full React dashboard for configuring scans and reviewing results

## Quick Start

```bash
docker compose up -d
```

Visit `http://localhost:8080` to open the dashboard.

> [!TIP]
> This project uses [`just`](https://github.com/casey/just) as a command runner. Type `just` to see all available commands.
>
> Install: `curl -sSf https://just.systems/install.sh | bash -s -- --to ~/.local/bin`

## Stack

**Backend:** FastAPI, SQLAlchemy, PostgreSQL, Alembic, httpx, aiohttp

**Frontend:** React, TypeScript, Vite

## Learn

This project includes step-by-step learning materials covering security theory, architecture, and implementation.

| Module | Topic |
|--------|-------|
| [00 - Overview](learn/00-OVERVIEW.md) | Prerequisites and quick start |
| [01 - Concepts](learn/01-CONCEPTS.md) | Security theory and real-world breaches |
| [02 - Architecture](learn/02-ARCHITECTURE.md) | System design and data flow |
| [03 - Implementation](learn/03-IMPLEMENTATION.md) | Code walkthrough |
| [04 - Challenges](learn/04-CHALLENGES.md) | Extension ideas and exercises |


## License

AGPL 3.0
