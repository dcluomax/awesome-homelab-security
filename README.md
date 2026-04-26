# Awesome Homelab Security 🔒

> A curated list of tools, guides, and best practices for securing your homelab infrastructure.

## Contents

- [Network Security](#network-security)
- [Container Security](#container-security)
- [Monitoring & SIEM](#monitoring--siem)
- [Secrets Management](#secrets-management)
- [Backup & Recovery](#backup--recovery)
- [Guides & Articles](#guides--articles)

---

## Network Security

- [pfSense](https://www.pfsense.org/) — Open-source firewall and router
- [OPNsense](https://opnsense.org/) — Fork of pfSense with modern UI
- [WireGuard](https://www.wireguard.com/) — Fast, modern VPN
- [Tailscale](https://tailscale.com/) — Zero-config mesh VPN built on WireGuard
- [Pi-hole](https://pi-hole.net/) — Network-wide DNS-level ad blocking
- [Network Segmentation for a Secure Homelab](https://orthogonal.info/network-segmentation-for-a-secure-homelab/) — VLAN isolation walkthrough

## Container Security

- [Trivy](https://github.com/aquasecurity/trivy) — Vulnerability scanner for containers
- [Falco](https://falco.org/) — Runtime security for Kubernetes
- [Docker Bench Security](https://github.com/docker/docker-bench-security) — CIS benchmark checker
- [Cosign](https://github.com/sigstore/cosign) — Container image signing
- [Dockle](https://github.com/goodwithtech/dockle) — Container image linter

## Monitoring & SIEM

- [Wazuh](https://wazuh.com/) — Open-source security monitoring
- [CrowdSec](https://www.crowdsec.net/) — Collaborative security engine
- [Grafana](https://grafana.com/) + [Prometheus](https://prometheus.io/) — Metrics and alerting
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) — Self-hosted uptime monitoring
- [Graylog](https://graylog.org/) — Log management and analysis

## Secrets Management

- [Vault](https://www.vaultproject.io/) — HashiCorp secrets management
- [SOPS](https://github.com/getsops/sops) — Encrypted file editor for GitOps
- [External Secrets Operator](https://external-secrets.io/) — K8s secrets from external stores
- [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) — Encrypt secrets for GitOps

## Backup & Recovery

- [TrueNAS](https://www.truenas.com/) — Enterprise storage with ZFS
- [Restic](https://restic.net/) — Fast, secure backup program
- [Velero](https://velero.io/) — Kubernetes backup and disaster recovery
- [BorgBackup](https://www.borgbackup.org/) — Deduplicating archiver

## Guides & Articles

- [Network Segmentation for a Secure Homelab](https://orthogonal.info/network-segmentation-for-a-secure-homelab/)
- [Secure Self-Hosted LLM: Enterprise Practices at Home](https://orthogonal.info/secure-self-hosted-llm-enterprise-practices-at-home/)
- [GitOps vs GitHub Actions: Security-First](https://orthogonal.info/gitops-vs-github-actions-security-first-production/)
- [CI/CD Pipeline Security Guide](https://orthogonal.info/ci-cd-pipeline-in-devops-secure-scalable-guide/)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — Essential web security risks
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) — Security configuration guides

---

## Contributing

PRs welcome! Please suggest tools/resources you've actually used.

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
