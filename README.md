# Ayoub Ait Belhaj

**DevOps / Platform Engineer** · Ben Guerir, Morocco · open to relocation across Europe and to remote roles

I run the delivery and runtime platform for a production application at **Startgate (UM6P)**: CI/CD with security gates, containers on Kubernetes, a hardened TLS edge, object storage, and everything provisioned as code. My systems background comes from **1337 (42 Network)**, where I built clusters, cloud deployments and low-level security tooling from scratch.

## What I work with

| Area | Tools |
|---|---|
| CI/CD and quality | GitHub Actions, Jenkins, SonarQube, Trivy, automated tests, performance gates |
| Containers and orchestration | Docker, Podman, Kubernetes (K3s, K3d), Helm, Argo CD, Vagrant |
| Infrastructure as code and cloud | Terraform, Ansible, Azure, AWS, Linux administration |
| Edge and security | Nginx reverse proxy, Let's Encrypt / Certbot, rate limiting, security headers, binary auditing |
| Data and storage | PostgreSQL, Redis / BullMQ, S3-compatible storage (SeaweedFS, MinIO) |
| Languages | Python, Bash, TypeScript, C, C++, SQL |

## What I do at Startgate (Aug 2025 to present)

- Built and own the delivery pipeline: tests, SonarQube quality gates and Trivy image and dependency scans on every change, then promotion through test, staging and production.
- Run the platform (Next.js, Prisma, PostgreSQL, Redis workers) as Docker microservices on a K3s cluster, including deployments, rollbacks and environment configuration.
- Hardened the production edge with Nginx, automated TLS, rate limiting and security headers.
- Operate S3-compatible storage and debugged a firewall-related upload failure across the network, storage and application layers.
- Supervise interns in the Forge program: onboarding, code review, runbooks.

The production code is private. The repositories below are public work that shows the same practices.

## Featured projects

| Project | What it shows |
|---|---|
| [**Inception-of-Things**](https://github.com/aaitbelh/Inception-of-things-Devops-) | K3s clusters with Vagrant, host-based ingress routing, and a GitOps flow with Argo CD. Also a self-hosted GitLab via Helm. |
| [**cloud-1 on Azure**](https://github.com/aaitbelh/Wordpress_Azure-Cloud-1-) | Terraform builds the Azure network and VM, then Ansible installs Docker and brings up a WordPress stack. |
| [**BADASS (BGP at the Doors of Autonomous Systems)**](https://github.com/aaitbelh/Bgp-At-Doors-of-Autonomous-Systems-is-Simple) | Network emulation with GNS3 and Docker. I implemented the VXLAN part: static and dynamic overlays and traffic encapsulation. |
| [**Minishell**](https://github.com/aaitbelh/Minishell) | A Unix shell in C: parsing, pipes, redirections, signals. |
| [**WebServe**](https://github.com/aaitbelh/WebServe) | An HTTP server in C++. |
| [**philosophers**](https://github.com/aaitbelh/philosophers) | Concurrency and synchronisation in C. |

The rest of my repositories are 42 school exercises, kept for reference.

## Contact

- Email: aitbelhajayoub566@gmail.com
- LinkedIn: [aitbelhaj-ayoub](https://www.linkedin.com/in/aitbelhaj-ayoub-799515241)
