# Agent Context

This file is a lightweight reference for future documentation updates in this repository.

## Project Summary
- Personal homelab project focused on learning by building step by step
- Main themes: Linux administration, networking, SSH, Kubernetes, and practical DevOps

## Current Hardware
- `iMac 1`: Ubuntu Server main node
- `iMac 2`: Ubuntu Server worker node
- `Raspberry Pi 4`: planned utility node

## Current State
- Ubuntu Server installed
- Static networking configured
- SSH access confirmed
- First `k3s` cluster established
- Cluster verification completed with:
  - `sudo kubectl get nodes`
  - `sudo kubectl get pods -A`

## Verified Outcome
- The main node appears in the node list and shows `Ready`
- System pods in `kube-system` are running

## Rough Roadmap
1. Completed: Static networking
2. Completed: SSH
3. Completed: `k3s` cluster
4. Next: NodePort exposure
5. Later: Ingress with Traefik
6. Later: Scale deployments
7. Later: More realistic apps, possibly `n8n`
8. Later: Monitoring, GitOps, and TLS

## Documentation Map
- `README.md`: high-level overview, current status, roadmap
- `notes/setup.md`: setup steps and cluster verification notes

## Documentation Style
- Keep notes chronological and practical
- Prefer short sections with clear completed outcomes
- Record verification commands when a milestone is confirmed
