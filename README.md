# go-uptime

> Concurrent website monitor in Go — checks status, SSL expiry and response time for many sites, sends alerts, and exposes Prometheus metrics.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-Golang-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 1 — Python & Go foundations**). I build in the open — follow the commits and the roadmap below.

## Why this project

Learn Go concurrency on something genuinely useful — keep an eye on every client website from one small binary.

## What I'm learning

- Goroutines, channels, worker pools and `context`
- Timeouts, retries and graceful shutdown
- TLS certificate inspection
- Exposing Prometheus metrics
- Configuration with YAML + environment variables

## Planned stack

Go · Prometheus client · YAML config · Telegram/email alerts · Docker

## Roadmap

- [ ] CLI that checks one URL (status, latency)
- [ ] Concurrent checks with a worker pool + config file
- [ ] SSL expiry checks
- [ ] Alerts (Telegram and email) with de-duplication
- [ ] `/metrics` endpoint for Prometheus
- [ ] Tests with `httptest`
- [ ] Docker image + release binaries
- [ ] Grafana dashboard JSON (used later in k8s-gitops-lab)

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | [lt-vocab-api](https://github.com/arman-aru/lt-vocab-api) | Python | 1 |
| 3 | [parcel-locker-api](https://github.com/arman-aru/parcel-locker-api) | Golang | 1 |
| 4 | **go-uptime** (this repo) | Golang | 1 |
| 5 | [ci-cd-pipelines](https://github.com/arman-aru/ci-cd-pipelines) | DevOps | 2 |
| 6 | [k8s-gitops-lab](https://github.com/arman-aru/k8s-gitops-lab) | DevOps | 2 |
| 7 | [terraform-aws-platform](https://github.com/arman-aru/terraform-aws-platform) | Cloud Computing | 3 |
| 8 | [serverless-media-pipeline](https://github.com/arman-aru/serverless-media-pipeline) | Cloud Computing | 3 |
| 9 | [site-audit-agent](https://github.com/arman-aru/site-audit-agent) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek
