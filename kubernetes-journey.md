# My Kubernetes Journey

## Timeline

### 2026-11-19: [KubeRange](https://github.com/gnufred/kuberange)

I moved my home lab into its own repository. KubeRange uses Vagrant and Ansible to provision a disposable Kubernetes cluster offline for troubleshooting and recovery exercises.

### 2026-11-04: Offline lab refresh

I rebuilt the Alpine base box and got the lab running on Kubernetes 1.36.1 using cached packages and images.

### 2026-02: NGINX to Cloudflare and Traefik

I replaced NGINX ingress for Kiln’s production APIs with Cloudflare in front of Traefik on Kubernetes. I owned the implementation and coordinated the rollout across engineering teams without interrupting service.

### 2025-06: PostgreSQL from AWS to Google Cloud

I led the migration of 250 PostgreSQL databases and more than 5 TB of data from AWS to AlloyDB on Google Cloud, using Terraform and Terragrunt for the infrastructure work. The APIs that depended on these databases served thousands of requests per second and stayed online throughout.

### 2024-11-04: [Managing Kubernetes Applications with Helm (LFS244)](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/2b01f0e0-397b-49b8-a81e-1f0628e10548-frdric-potvin-897eb1f2-0c5d-432e-9e14-5fa20504a81c-certificate.pdf)

After working on validator deployments at Kiln, I wanted a deeper understanding of Helm. I read [Learning Helm](https://www.oreilly.com/library/view/learning-helm/9781492083641/) and completed the Linux Foundation course.

### 2024-08: Joined Kiln as an SRE

I wrote Helm charts to deploy validators and nodes for [Hyperliquid](https://hyperliquid.xyz/), [RSS3](https://rss3.io/), and [Aztec](https://aztec.network/) on Kiln’s bare-metal Kubernetes infrastructure. I set up monitoring and alerting with Prometheus and Grafana.

### 2024-05-13: [Certified Kubernetes Administrator](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/2b01f0e0-397b-49b8-a81e-1f0628e10548-frdric-potvin-e4366b32-2f13-452a-accb-adf0ece8782f-certificate.pdf)

I passed the CKA with 86/100 after 11 weeks of study. I lost 30 minutes during the exam when my unplugged laptop stopped responding.

### 2024-05-09: [Killer.sh CKA Simulator](https://killer.sh/cka)

I scored 119/125 across three sessions in 5½ hours. I knew I needed to get faster before the exam.

### 2024-04-23: [LFS258 — Kubernetes Fundamentals](https://training.linuxfoundation.org/training/kubernetes-fundamentals/)

I completed the course and earned my [certificate](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/2b01f0e0-397b-49b8-a81e-1f0628e10548-frederic-potvin-71e80add-19bb-489d-bf43-bf83a5e9be5e-certificate.pdf).

### 2024-03-18: Up and Running!

I finished [Kubernetes: Up and Running](https://www.oreilly.com/library/view/kubernetes-up-and/9781491935668/) and worked through its labs.

### 2024-02-28: LFS258 + CKA Bundle

I bought the LFS258 + CKA bundle, which gave me a year to take the exam.

### 2024-02 to 04: [Home Lab](https://github.com/gnufred/myk8s/blob/main/lab.md)

I used Vagrant and Ansible to build a cluster with an HAProxy load balancer, three control-plane nodes, an NFS server, and six workers.

### 2024-02: Linux and cloud infrastructure

After a year of relearning Go, I completed [Linux System Administration Essentials](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/2b01f0e0-397b-49b8-a81e-1f0628e10548-frdric-potvin-f216780b-5861-4a99-b8bd-68de9b89f4b9-certificate.pdf) and [Introduction to Cloud Infrastructure Technologies](https://courses.edx.org/certificates/b51f3461a2124e77a3916126d5436e47). I also earned my [LFCS certification](https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/2b01f0e0-397b-49b8-a81e-1f0628e10548-frederic-potvin-5a5f270c-2b75-45e6-b648-f28a23c01577-certificate.pdf).

### 2023-04 to 2024-01: [Logslate](https://github.com/gnufred/logslate)

I spent almost a year building Logslate, which became an official security tool used at [Platform.sh](https://platform.sh).

### 2023-03: [Learning Go](https://www.oreilly.com/library/view/learning-go/9781492077206/)

Relearning Go led me to the CNCF ecosystem and eventually to Kubernetes.
