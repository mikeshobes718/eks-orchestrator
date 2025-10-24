# EKS Orchestrator

[![CI](https://github.com/mikeshobes718/eks-orchestrator/actions/workflows/ci.yml/badge.svg)](https://github.com/mikeshobes718/eks-orchestrator/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Python CLI for Amazon EKS cluster/nodegroup lifecycle, RBAC, add-ons, manifest rollout, and a job runner — with dry-run plans and safe apply.

## Features
- Create/update EKS clusters and node groups with guardrails
- RBAC bootstrap and service account management
- Add-on lifecycle (VPC CNI, CoreDNS, metrics-server)
- Manifest rollout with health checks and progressive delivery
- Dry-run plans, idempotent operations, and safe rollback

## Quickstart
```bash
# Coming soon: CLI entrypoint
pip install -r requirements.txt
python -m eks_orchestrator --help
```

## Architecture
- Python + boto3 + kubectl/helm execs
- Declarative inputs, generated plans, and audited changes

## Roadmap
- Cluster blueprints
- Drift detection and remediation
- Multi-cluster orchestration

## License
MIT
