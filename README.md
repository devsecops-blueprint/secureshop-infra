# SecureShop — Infrastructure Repository

GitOps-managed infrastructure for the SecureShop DevSecOps platform.

## What lives here
- Kubernetes manifests (Kustomize overlays for dev/staging/prod)
- ArgoCD App of Apps configuration
- Security policies (Kyverno, Falco, Tetragon)
- Service mesh configuration (Istio)
- Secrets management (HashiCorp Vault)
- Workload identity (SPIFFE/SPIRE)
- Observability stack (Prometheus, Loki, Grafana, Tempo)
- Research paper and threat model documentation

## Access Control
Infrastructure changes require review from CODEOWNERS.
See `.github/CODEOWNERS` for ownership rules.

## Related
- [secureshop-app](https://github.com/madushanka-w/secureshop-app) — Application code & CI pipelines
