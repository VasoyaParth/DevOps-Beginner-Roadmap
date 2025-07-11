# 🚀 DevOps 0 to Hero Roadmap for Absolute Beginners (2025 Edition)

Welcome to your **DevOps Journey**! Whether you're transitioning from software development or just starting out, this roadmap will take you from **0% knowledge** to a **solid DevOps foundation**. This guide is designed with 💯 clarity, 🧠 beginner-friendly explanations, 🎥 YouTube resources, 📸 visuals, and ✅ actionable daily steps.

---

## 📅 10‑Day DevOps Prep Roadmap

| Day | 🔍 Focus Area       | 📚 Topics & Goals |
|-----|---------------------|------------------|
| 1️⃣ | Linux & Bash        | Terminal commands, bash scripting |
| 2️⃣ | Version Control     | Git basics, GitHub, pull requests |
| 3️⃣ | Python for DevOps   | Automating with Python scripts |
| 4️⃣ | Networking & Security | OSI model, DNS, HTTPS, SSH |
| 5️⃣ | CI/CD Foundations   | Jenkins, GitHub Actions basics |
| 6️⃣ | Docker              | Build & run containers, Dockerfile |
| 7️⃣ | Kubernetes          | Pods, deployments, kubectl |
| 8️⃣ | Infrastructure as Code | Terraform, Ansible |
| 9️⃣ | Monitoring & Logging | Prometheus, Grafana, ELK stack |
| 🔟 | DevSecOps & Metrics | Scanning, secrets, DORA metrics |

---

## 📺 Recommended YouTube Tutorials (Day-wise)

| Day | 🔗 YouTube Video Title |
|-----|------------------------|
| 1 | [Linux Command Line Full Course](https://www.youtube.com/watch?v=ZtqBQ68cfJc) |
| 2 | [Git & GitHub Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk) |
| 3 | [Automate with Python (Crash Course)](https://www.youtube.com/watch?v=VXwx5l0vY-w) |
| 4 | [Networking Fundamentals Explained](https://www.youtube.com/watch?v=qiQR5rTSshw) |
| 5 | [Jenkins Full Course for Beginners](https://www.youtube.com/watch?v=6YZvp2GwT0A) |
| 6 | [Docker Tutorial for Beginners](https://www.youtube.com/watch?v=pTFZFxd4hOI) |
| 7 | [Kubernetes Explained Simply](https://www.youtube.com/watch?v=X48VuDVv0do) |
| 8 | [Terraform Crash Course](https://www.youtube.com/watch?v=7xngnjfIlK4) & [Ansible Crash Course](https://www.youtube.com/watch?v=wgQ3rHvdXp4) |
| 9 | [Prometheus + Grafana Stack](https://www.youtube.com/watch?v=h4Sl21AKiDg) |
| 10 | [DevSecOps Basics & DORA Metrics](https://www.youtube.com/watch?v=IednZgBfBik) |

---

## 📘 Daily Usage Tips

- 📌 **Pomodoro Schedule**: 25 min study + 5 min break × 3–4 rounds/day
- 📝 Keep a **DevOps notebook** (physical or Notion/Obsidian)
- 🧪 Do **hands-on labs**: Use [Play with Docker](https://labs.play-with-docker.com/), GitHub Actions, etc.
- 🧰 Use **free cloud**: [AWS Free Tier](https://aws.amazon.com/free/), [Google Cloud Free Tier](https://cloud.google.com/free)

---
## 🧾 DevOps Cheatsheet

### 📂 Linux / Bash
- `ls`, `cd`, `mkdir`, `touch`, `rm`, `cat`, `grep`, `chmod`, `chown`
- `scp`, `ssh`, `.bashrc`, `alias`

### 🔁 Git & GitHub
- Basics: `git init`, `git clone`, `git add`, `git commit -m "message"`, `git push`
- Branching: `git branch`, `git checkout`, `git merge`
- Collaboration: Pull Requests (PRs), merge conflict resolution

### 🐍 Python for DevOps
- Automation: File handling, REST APIs with `requests`
- Common modules: `os`, `subprocess`, `argparse`, `json`, `yaml`

### 🌐 Networking & Security
- Concepts: OSI model, IP addressing, DNS, HTTP vs HTTPS
- Security Tools: SSL/TLS, Firewalls, SSH, Public/Private Key Auth

### 🔄 CI/CD (GitHub Actions & Jenkins)
- **GitHub Actions**:
  - Workflow: `.github/workflows/main.yml`
  - Triggers: `on: push`
  - Jobs: `jobs: build`
- **Jenkins**:
  - Types: Freestyle Jobs, Pipeline Jobs
  - Pipeline: `Jenkinsfile`

### 🐳 Docker
- Commands:
  - `docker build -t image .`
  - `docker run -d -p 80:80 image`
  - `docker exec -it container bash`
- Dockerfile Instructions: `FROM`, `COPY`, `RUN`, `CMD`, `ENTRYPOINT`

### ☸️ Kubernetes
- Commands:
  - `kubectl apply -f file.yaml`
  - `kubectl get pods`
  - `kubectl logs pod-name`
  - `kubectl describe pod-name`
- Resources: Pod, Deployment, Service, ConfigMap, Secret

### 🔧 Infrastructure as Code (IaC)
- **Terraform**:
  - Commands: `terraform init`, `plan`, `apply`
  - Language: HCL (HashiCorp Configuration Language)
- **Ansible**:
  - Usage: `ansible-playbook`
  - Components: `hosts`, `tasks`, `vars`, `handlers`

### 📊 Monitoring & Logging
- **Prometheus**: Targets, Metrics, Alerting Rules
- **Grafana**: Dashboards, Panels, Query Builder
- **ELK Stack**:
  - Elasticsearch (storage & search)
  - Logstash (log ingestion)
  - Kibana (visualization)

### 🔐 DevSecOps
- **DORA Metrics**:
  - Lead Time for Changes
  - Deployment Frequency
  - Mean Time to Recovery (MTTR)
  - Change Failure Rate
- **Security Tools**: `Trivy`, `Snyk`
- **Secrets Management**: `.env` files, GitHub Secrets, HashiCorp Vault


## 🧠 Bonus: What Else to Learn Next?

- **Cloud Providers**: AWS (EC2, S3, IAM, CloudWatch)
- **Service Mesh**: Istio basics
- **GitOps**: ArgoCD or Flux
- **SRE Mindset**: SLAs, SLOs, Error Budgets
- **Platform Engineering Tools**: Backstage, Crossplane

---



## 💼 Sample Mini Project (Do After Day 10)

**Project**: Deploy a Flask App with CI/CD on Kubernetes

1. Write a simple Flask app
2. Dockerize it and push to DockerHub
3. Set up GitHub Actions for CI
4. Write Kubernetes YAML for deployment
5. Deploy to local Minikube or cloud cluster
6. Monitor with Prometheus & Grafana

---

## ✅ Final Thoughts

You're not expected to master all in 10 days. But this journey will:
- Give you a **vocabulary** to understand training
- Make you comfortable with **tools and commands**
- Give you a **project to show** and confidence to ask questions

---

Feel free to fork this repo, track your learning journey, and share your notes. Good luck future DevOps Engineer! 💪🔥

> 💬 Have questions or want PDF export? Message me!

---

## 📜 Disclaimer

All external resources, videos, and diagrams referenced in this guide are the property of their respective content creators and copyright holders. This roadmap is intended for educational and personal learning purposes only.

If you're a content creator and would like your content removed or credited differently, please feel free to open an issue or contact the repository maintainer.

No copyright infringement is intended.
