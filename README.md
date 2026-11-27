<p align="center">
  <img src="./assets/profile-banner.svg" alt="" width="810" />
</p>

# Mohamed ElBeltagy

**Cloud and AI security engineer · Published security researcher**

I build and secure cloud platforms and AI systems. I work on Kubernetes hardening, cloud access controls, and ways to trace security failures in AI agents. My published research focuses on lightweight image encryption.

[ResearchGate](https://www.researchgate.net/profile/Mohamed-Elbeltagy-4) · [DEV Community](https://dev.to/le_beltagy) · [Portfolio](https://beltagyy.github.io/) · [LinkedIn](https://www.linkedin.com/in/beltagyy/) · [Email](mailto:mohamedbeltagyy@gmail.com)

<p align="center">
  <img src="https://raw.githubusercontent.com/beltagyy/beltagyy/1cdbc86bfc43e1a5f31f31cda2b666f64d38828b/assets/profile-divider.svg" alt="Lavender rabbit nibbling a carrot" width="640" />
</p>

[Research](#research-and-publications) · [Engineering](#engineering-work) · [Projects](#selected-projects) · [Writing](#writing-on-dev)

## Research and publications

I earned my M.Sc. in Networks Engineering from the German University in Cairo. In my published work, I studied how cellular automata, chaotic systems, and substitution boxes can be used to encrypt images with low computational overhead.

- [RGB Image Encryption through Cellular Automata, S-Box and the Lorenz System](https://doi.org/10.3390/sym14030443) · *Symmetry*, 2022
- [Image Encryption Through Rössler System, PRNG S-Box and Recamán’s Sequence](https://dblp.org/rec/conf/ccwc/ElBeltagyAEMH22) · IEEE CCWC, 2022
- [Lightweight Image Encryption: Cellular Automata and the Lorenz System](https://doi.org/10.1109/ICM52667.2021.9664961) · IEEE ICM, 2021

## Engineering work

| Focus | What I work on |
| :--- | :--- |
| **Cloud security** | Kubernetes hardening, identity and access, secrets management, and software supply chain controls. I’ve built compliance checks into CI/CD for AWS, Azure, and GCP. |
| **AI security** | Agent forensics, tool-call policies, and audit trails. My work with X0R Labs includes schema-based policy checks and decision logging in X0R Core. |
| **HPC and AI infrastructure** | At Baker Hughes, I work with NVIDIA DGX systems and NVIDIA Run:ai for GPU workload scheduling and resource allocation. |
| **Platform engineering** | I use Terraform, Ansible, and Argo CD to deliver infrastructure changes, and Prometheus and Grafana to understand how services behave in production. I build operational tooling in Python and Go. |

Previously, I worked as a cloud engineer at AWS in Dublin and helped automate AWS infrastructure for SaaS launches in the UAE and Canada.

## Selected projects

| Project | What it does |
| :--- | :--- |
| [**AI Forensics**](https://github.com/beltagyy/ai-forensics-poc) | A Python proof of concept that records multi-agent activity so investigators can trace a compromised tool response back to its source. |
| [**X0R Core**](https://github.com/X0R-labs/core) | A self-hosted backend for document retrieval, tool-calling AI agents, evaluations, and token usage tracking. |
| [**Talos Kubernetes lab**](https://github.com/beltagyy/gitops) | My bare-metal GitOps lab with Talos Linux, Cilium and eBPF networking, Argo CD, distributed storage, and monitoring. |
| [**VehicleMetrics**](https://github.com/beltagyy/vehicle-metrics) | A prototype that streams and visualizes autonomous vehicle telemetry with FastAPI, React, and Kubernetes. |
| [**Job Digest**](https://github.com/beltagyy/job-digest) | A Python service that matches job listings to a profile and sends an email digest. [Next.js demo](https://github.com/beltagyy/job-digest-demo) |

## Writing on DEV

I write about what I learn while building and running systems, including what broke and how I fixed it.

- [Replacing kube-proxy with eBPF and debugging a monitoring outage](https://dev.to/le_beltagy/i-replaced-kube-proxy-with-ebpf-in-production-and-why-my-monitoring-went-blind-for-6-hours-1n18)
- [Building a bare-metal Kubernetes lab with Talos on a budget](https://dev.to/le_beltagy/i-run-bare-metal-kubernetes-on-200-of-scrap-hardware-and-why-i-burned-3-sd-cards-learning-34cb)
- [Learning Go by working on Kubernetes RBAC in k9s](https://dev.to/le_beltagy/i-learned-go-in-3-weeks-yesterday-my-code-merged-into-k9s-2dg4)
- [Reorganizing 45 Kubernetes manifests for GitOps](https://dev.to/le_beltagy/how-i-reorganized-45-kubernetes-manifests-and-saved-hours-of-development-time-1m80)
