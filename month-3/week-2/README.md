# 🐳 Week 10 — Docker and CI/CD

> **Days 68–74 · Production · Progress:** 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦⬜

## 🎯 Mission

Make the application reproducible, testable, and deployable from a clean checkout.

## ✅ Outcomes

You can containerize the app, manage configuration safely, run tests in CI, enforce evaluation gates, and produce a deployable artifact.

## 🗺️ Daily roadmap

| Day | Focus | Build / evidence |
| --- | --- | --- |
| 68 | Container basics | Create a small, non-root image. |
| 69 | Local composition | Run API, vector DB, and dependencies together. |
| 70 | Configuration | Add `.env.example` and secret boundaries. |
| 71 | Unit and integration tests | Run tests in a clean environment. |
| 72 | CI workflow | Add lint, type check, tests, and build jobs. |
| 73 | Evaluation gate | Fail CI when thresholds regress. |
| 74 | Deployment rehearsal | Build, tag, and smoke-test the release artifact. |

## 📚 Learn

- Image layers, caching, and multi-stage builds
- Non-root containers and health checks
- Environment configuration and secret management
- GitHub Actions jobs, artifacts, and environments
- Deployment promotion and rollback
- Supply-chain and dependency hygiene

## 🔗 Core resources

- [Docker — Get Started](https://docs.docker.com/get-started/)
- [Docker — Build Best Practices](https://docs.docker.com/build/building/best-practices/)
- [GitHub Actions — Quickstart](https://docs.github.com/en/actions/get-started/quickstart)
- [GitHub Actions — Security Hardening](https://docs.github.com/en/actions/security-for-github-actions/security-guides/security-hardening-for-github-actions)
- [Trivy — Container Scanning](https://trivy.dev/latest/)
- [SLSA — Supply Chain Security](https://slsa.dev/)

## 🧪 Build lab: release pipeline

Add `Dockerfile`, `.env.example`, `docker-compose.yml`, unit tests, evaluation jobs, image build, and a deployment script. Keep real credentials out of Git and make failing tests or evaluation thresholds block release.

## 📦 Deliverables

- Reproducible Docker image
- Local Compose environment
- CI workflow with test and eval gates
- Deployment or release script
- Container scan result
- Rollback notes

## 🚀 Stretch roadmap

- Add image signing and provenance
- Add dependency update automation
- Use preview environments for pull requests
- Add blue/green or canary deployment

## 🏁 Definition of done

A clean checkout can build and test the same artifact that is deployed, and the pipeline visibly blocks unsafe or regressed releases.

---

[← Previous: Week 1 — Backend and API](../week-1/README.md) | [Next: Week 3 — Observability and Cost Tracking →](../week-3/README.md)
