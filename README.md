# 🏠 Homelab

## Overview
This repository documents my personal homelab setup and learning journey.

## Goals
- Learn Linux system administration
- Build and manage a Kubernetes cluster
- Understand networking and SSH
- Practice DevOps concepts step by step

## Hardware

| Device | Description |
|--------|-------------|
| iMac 1 | Ubuntu Server (Main node) |
| iMac 2 | Ubuntu Server (Worker node) |
| Raspberry Pi 4 | Planned utility node |

## Network

| Host | IP (masked) |
|------|-------------|
| imac1 | 192.168.x.86 |
| imac2 | 192.168.x.104 |

## Current Status

- [x] Ubuntu Server installed
- [x] Static IP configured
- [x] SSH access working
- [x] Kubernetes cluster (`k3s`)
- [ ] First deployment

## Roadmap

1. [x] Static networking
2. [x] SSH
3. [x] `k3s` cluster
4. [ ] NodePort exposure
5. [ ] Ingress with Traefik
6. [ ] Scale deployments
7. [ ] More realistic apps (maybe `n8n` later)
8. [ ] Monitoring / GitOps / TLS later

## Notes

See the `notes/` directory for detailed setup steps and learnings.
Internal maintainer context is stored in `AGENT_CONTEXT.md`.
