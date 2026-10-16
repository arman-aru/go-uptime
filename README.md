# go-uptime

> Concurrent website monitor in Go — checks status, SSL expiry and response time for many sites, sends alerts, and exposes Prometheus metrics.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

A lightweight website monitor written in Go. It checks many sites concurrently for availability, response time and SSL certificate expiry, sends alerts, and exposes metrics for Prometheus.

## Features

- Concurrent checks for many URLs with a configurable worker pool
- HTTP status and response-time monitoring
- SSL certificate expiry warnings
- Alerts via Telegram and email, without duplicate spam
- Prometheus `/metrics` endpoint + ready-made Grafana dashboard
- Single binary or Docker image, configured with YAML

## Tech stack

Go · Prometheus client · YAML config · Telegram/email alerts · Docker

## License

[MIT](LICENSE) © Arman Salek
