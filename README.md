# Hey, I'm Nathan 👋

I enjoy building tools for cloud infrastructure management, with a focus on reliability, observability, and automation.

---

## 🚀 Current Projects

### AWS Cost Analyzer — Cloud Cost Optimization Tool
- Identifies cost leaks in AWS accounts (EC2, EBS, Snapshots, Elastic IPs)
- Multi-region scanning with parallel execution
- Docker containerized with CI/CD pipeline

### LogDrain — Centralised Log Pipeline
- Bash log generator produces realistic access, error, and auth logs at a steady rate, with periodic "incident" bursts of 5xx responses
- Promtail tails the log files and ships them to Loki, which indexes by label (job, filename, log_type) for fast LogQL queries
- Grafana dashboard auto-provisions with log volume, error rate, top error messages, and a live log stream — fully containerised with `make up`

### NetProbe — Networking, DNS & TLS Toolkit
- Multi-service setup behind an Nginx reverse proxy with local TLS (mkcert), routing PulseStack and LogDrain through a single HTTPS entry point
- DNS resolution exercises with `dig` and `/etc/hosts` overrides, plus packet capture and analysis with `tcpdump`/Wireshark
- Building a Bash network diagnostic script (`netprobe.sh`) that wraps `mtr`, `ss`, `curl -w` timing, and TLS cert inspection — the kind of toolkit you'd actually reach for during an outage

---

## 💻 Tech Stack

### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-web-services&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326CE5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)

### Observability & Reliability
![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)

### CI/CD & Automation
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232088FF.svg?style=for-the-badge&logo=github-actions&logoColor=white)

### Languages
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-%234EAA25.svg?style=for-the-badge&logo=gnubash&logoColor=white)

---

## 🎯 Goals for 2026

- [ ] Build deep expertise in observability — metrics, logs, and distributed tracing (Prometheus, Grafana, OpenTelemetry)
- [ ] Master incident management: on-call practices, runbooks, SLOs, and postmortems
- [ ] Level up Kubernetes skills — cluster operations, autoscaling, and reliability patterns
- [ ] Earn AWS Solutions Architect or CKA (Certified Kubernetes Administrator) certification

---

## 📫 Connect

- 📧 [nathanl1605@gmail.com](mailto:nathanl1605@gmail.com)
