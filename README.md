# Deploy Microservices in Kubernetes

## Project objective

Deploy Google's Online Boutique microservices application to Linode LKE
using Kubernetes Deployments and Services, then implement and verify
production and security practices.

Status: repository preparation. Deployment has not yet been performed.

## Source provenance

- Training provider: TechWorld with Nana.
- Upstream repository:
  https://gitlab.com/twn-devops-bootcamp/latest/10-kubernetes/helm-chart-microservices
- Starting branch: `starting-code`.
- Baseline commit: `0b4131e5ac315050b01b5f69ed9d3053adb2642b`.
- Imported file: `config.yaml`, unchanged from the pinned starting source.

The imported file is an unfinished Kubernetes Deployment and Service
skeleton. It does not contain the Online Boutique application source.

The upstream Helm charts, Helmfile, values and installation scripts were
not imported because the current assignment focuses on Kubernetes manifests.

## Attribution

- Google Cloud: original Online Boutique application.
- TechWorld with Nana: training material and starting configuration skeleton.
- Gafari Salaudeen: independent Kubernetes configuration, deployment,
  validation, troubleshooting and documentation developed during this project.

## Git workflow

GitHub is the primary remote (`origin`).
GitLab is the secondary remote (`gitlab`).

Implementation follows:

`feature/<task>` → validated merge into `develop` → final release into `main`.

Feature and release merges use `--no-ff`.

## Documentation

This README and `docs/RUNBOOK.md` will be finalized after implementation
and deployment verification.

The final runbook will contain the complete reproduction procedure,
configuration contents, Git workflow, verification, troubleshooting,
rollback and cleanup.
