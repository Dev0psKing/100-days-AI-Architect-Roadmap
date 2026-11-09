# Week 2 — Docker and CI/CD

**Days 68–74**

## Learn

- Containers
- Environment variables
- Secrets
- Build pipelines
- Deployment pipelines

## Read

- [Docker Get Started](https://docs.docker.com/get-started/)
- [GitHub Actions Quickstart](https://docs.github.com/en/actions/get-started/quickstart)

## Build

Add:

- `Dockerfile`
- `.env.example`
- `docker-compose.yml`
- GitHub Actions workflow
- Unit tests
- Evaluation test job
- Deployment script

Never commit real credentials. Make the pipeline fail when tests or required evaluation thresholds fail.

## Output

Every push can install dependencies, run tests, run evaluations, and build the application image.

---

[← Previous: Week 1 — Backend and API](../week-1/README.md) | [Next: Week 3 — Observability and Cost Tracking →](../week-3/README.md)
