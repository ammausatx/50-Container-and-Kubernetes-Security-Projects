# 50 Container and Kubernetes Security Projects

A hands-on portfolio of 50 authorized, lab-focused projects covering container security, Docker hardening, image and supply-chain assurance, Kubernetes configuration, cluster access control, runtime defense, and incident response.

> **Safety:** Perform testing only in clusters, images, registries, and workloads you own or are explicitly authorized to assess. Use disposable labs for intentionally vulnerable workloads. Never run destructive commands against production systems.

## Learning path

| Level | Projects | Focus |
|---|---:|---|
| Beginner | 01–15 | Docker fundamentals, image hygiene, baseline hardening, Kubernetes basics |
| Intermediate | 16–35 | RBAC, network policies, admission controls, supply chain, secrets, runtime monitoring |
| Advanced | 36–50 | Threat modeling, cluster attack simulations, detection engineering, response, platform architecture |

## Project index

### Beginner

- [Project 01 — Build a Secure Dockerfile Baseline](projects/01-secure-dockerfile-baseline/README.md)
- [Project 02 — Inspect and Minimize Container Images](projects/02-minimize-container-images/README.md)
- [Project 03 — Scan Container Images with Trivy](projects/03-trivy-image-scanning/README.md)
- [Project 04 — Harden Docker Daemon Configuration](projects/04-docker-daemon-hardening/README.md)
- [Project 05 — Run Containers as Non-Root](projects/05-non-root-containers/README.md)
- [Project 06 — Apply Read-Only Container Filesystems](projects/06-read-only-filesystems/README.md)
- [Project 07 — Limit Container Linux Capabilities](projects/07-linux-capabilities/README.md)
- [Project 08 — Configure Docker Resource Limits](projects/08-container-resource-limits/README.md)
- [Project 09 — Secure Container Environment Variables](projects/09-environment-variable-security/README.md)
- [Project 10 — Create a Docker Compose Security Baseline](projects/10-docker-compose-baseline/README.md)
- [Project 11 — Deploy a Local Kubernetes Lab](projects/11-local-kubernetes-lab/README.md)
- [Project 12 — Explore Kubernetes Workload Security Contexts](projects/12-kubernetes-security-contexts/README.md)
- [Project 13 — Audit Kubernetes Manifests with Kubescape](projects/13-kubescape-manifest-audit/README.md)
- [Project 14 — Configure Kubernetes Namespaces and Resource Quotas](projects/14-namespaces-resource-quotas/README.md)
- [Project 15 — Create a Container and Kubernetes Security Report](projects/15-security-assessment-report/README.md)

### Intermediate

- [Project 16 — Implement Kubernetes RBAC Least Privilege](projects/16-kubernetes-rbac-least-privilege/README.md)
- [Project 17 — Build Kubernetes Network Policies](projects/17-network-policies/README.md)
- [Project 18 — Secure Kubernetes Secrets at Rest](projects/18-secrets-at-rest/README.md)
- [Project 19 — Configure Pod Security Admission](projects/19-pod-security-admission/README.md)
- [Project 20 — Enforce Image Provenance and Trusted Registries](projects/20-image-provenance-trusted-registries/README.md)
- [Project 21 — Scan Kubernetes Clusters with kube-bench](projects/21-kube-bench-cluster-audit/README.md)
- [Project 22 — Audit Kubernetes API Server Exposure](projects/22-api-server-exposure/README.md)
- [Project 23 — Secure Ingress Controllers and TLS](projects/23-ingress-tls-hardening/README.md)
- [Project 24 — Harden Helm Charts Before Deployment](projects/24-helm-chart-security/README.md)
- [Project 25 — Add Kyverno Admission Policies](projects/25-kyverno-admission-policies/README.md)
- [Project 26 — Deploy Falco for Runtime Threat Detection](projects/26-falco-runtime-detection/README.md)
- [Project 27 — Monitor Kubernetes Audit Logs](projects/27-kubernetes-audit-logs/README.md)
- [Project 28 — Secure Persistent Volumes and Storage](projects/28-persistent-volume-security/README.md)
- [Project 29 — Harden Node and Kubelet Configuration](projects/29-node-kubelet-hardening/README.md)
- [Project 30 — Configure Workload Identity and Service Accounts](projects/30-workload-identity/README.md)
- [Project 31 — Build a Container SBOM Pipeline](projects/31-container-sbom-pipeline/README.md)
- [Project 32 — Sign and Verify Images with Cosign](projects/32-cosign-image-signing/README.md)
- [Project 33 — Create CI Image Vulnerability Gates](projects/33-ci-image-vulnerability-gates/README.md)
- [Project 34 — Detect Kubernetes Drift with GitOps](projects/34-gitops-drift-detection/README.md)
- [Project 35 — Assess Container Escape Risk in a Safe Lab](projects/35-container-escape-risk-lab/README.md)

### Advanced

- [Project 36 — Threat Model a Multi-Tenant Kubernetes Platform](projects/36-multi-tenant-threat-model/README.md)
- [Project 37 — Simulate and Detect Kubernetes Credential Abuse](projects/37-credential-abuse-detection/README.md)
- [Project 38 — Investigate Suspicious Container Runtime Activity](projects/38-runtime-activity-investigation/README.md)
- [Project 39 — Build Kubernetes Incident Response Playbooks](projects/39-kubernetes-incident-response/README.md)
- [Project 40 — Design a Zero-Trust Cluster Network](projects/40-zero-trust-cluster-network/README.md)
- [Project 41 — Implement Multi-Cluster Security Governance](projects/41-multi-cluster-governance/README.md)
- [Project 42 — Create Runtime Detection Rules for Container Threats](projects/42-runtime-detection-rules/README.md)
- [Project 43 — Assess Kubernetes Supply-Chain Compromise Scenarios](projects/43-supply-chain-compromise-scenarios/README.md)
- [Project 44 — Build an Automated Cluster Security Posture Pipeline](projects/44-automated-posture-pipeline/README.md)
- [Project 45 — Perform a Kubernetes Control-Plane Security Review](projects/45-control-plane-security-review/README.md)
- [Project 46 — Design Secure Workload Isolation with Sandboxing](projects/46-workload-sandbox-isolation/README.md)
- [Project 47 — Create a Container Forensics Evidence Workflow](projects/47-container-forensics-workflow/README.md)
- [Project 48 — Run a Kubernetes Ransomware Readiness Exercise](projects/48-ransomware-readiness-exercise/README.md)
- [Project 49 — Build a Policy-as-Code Security Framework](projects/49-policy-as-code-framework/README.md)
- [Project 50 — Deliver an Enterprise Container Security Architecture](projects/50-enterprise-container-security-architecture/README.md)

## Repository structure

Each project includes objectives, authorization boundaries, prerequisites, lab setup, a guided workflow, commands or configuration examples, expected observations, risk interpretation, remediation, validation, evidence guidance, and three clearly labeled simulated training illustrations.

## Completion status

- [x] Beginner: 15/15
- [x] Intermediate: 20/20
- [x] Advanced: 15/15
- [x] Overall: 50/50

Illustrations are synthetic training visuals, not screenshots from a real assessment.