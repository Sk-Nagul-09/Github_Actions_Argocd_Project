# 🚀 GitOpsFlow  
## ⚙️ GitHub Actions → 🚢 Argo CD → ☸️ Kubernetes  

An **end-to-end GitOps-based CI/CD pipeline** that automatically builds, versions, and deploys a Java web application to Kubernetes using modern DevOps practices.

✨ **Code → Container → Kubernetes → Automated Deployment** ✨

---

## 🌟 Why This Project?

This project demonstrates how a **real-world DevOps pipeline** works using **GitHub Actions** for CI and **Argo CD** for GitOps-based CD.

- 🔹 No manual deployments  
- 🔹 Git as the single source of truth  
- 🔹 Fully automated image versioning  
- 🔹 Kubernetes-ready production workflow  
 
---

## 🔄 End-to-End Workflow

```text
Git Push 🚀
   ↓
GitHub Actions ⚙️ (Build & Test)
   ↓
Docker Image 🐳 (Build & Push)
   ↓
Update K8s Manifest ✍️
   ↓
Commit Back to GitHub 🔁
   ↓
Argo CD 🚢 (Auto Sync)
   ↓
Kubernetes Deployment ☸️
```
# 💥 Zero-touch deployment using GitOps 💥

---

## 🧰 Tech Stack

| Category        | Tools                          |
|-----------------|--------------------------------|
| CI/CD           | GitHub Actions ⚙️             |
| Containerization| Docker 🐳                      |
| Orchestration   | Kubernetes ☸️                  |
| GitOps          | Argo CD 🚢                     |
| Build Tool      | Maven ☕                        |
| Application     | Java (JSP Web App)             |
| Cloud           | Cloud-native setup ☁️          |

---

## 📂 Project Structure

```bash
📦 Github_Actions_Argocd_Project
 ┣ 📂 deploymentfiles
 ┃ ┗ 📄 deployment.yml        # Kubernetes Deployment & Service
 ┣ 📂 .github/workflows
 ┃ ┗ 📄 cicd.yml              # GitHub Actions pipeline
 ┣ 📄 Dockerfile
 ┣ 📄 pom.xml
 ┣ 📄 README.md
 ┗ 📂 src
```
# ☸️ Kubernetes Highlights
## 🚀 Deployment
Replicas: 2

Container Port: 8080

Auto-updated image tags

## 🌐 Service
Type: LoadBalancer

Port mapping: 80 → 8080

## ⚙️ GitHub Actions – CI Phase
✔️ Checkout source code

✔️ Build application using Maven

✔️ Build Docker image

✔️ Push image to Docker Hub 🐳

✔️ Auto-update deployment manifest

✔️ Commit changes back to GitHub

## 🚢 Argo CD – CD Phase
✔️ Git repository monitored continuously

✔️ Detects manifest changes automatically

✔️ Syncs application to Kubernetes

✔️ Ensures desired state matches Git

👉 True GitOps in action 🔥


## 🌍 Application Output
🚀 Welcome To DevOps World 💻

Hi all, this is Sk Nagul. I am an AWS DevOps enthusiast with hands-on experience in deploying CI/CD pipelines using GitHub Actions and Argo CD.


# 🔐 GitHub Secrets Used
🔑 DOCKER_USERNAME

🔑 DOCKER_PASSWORD

🔑 ARGOCD_SERVER

🔑 ARGOCD_PASSWORD


## 🎯 Key Takeaways
✨ Built a production-style CI/CD pipeline

✨ Implemented GitOps using Argo CD

✨ Automated Docker image versioning

✨ Deployed applications to Kubernetes

✨ Solved real CI/CD & Argo CD issues


## 🚀 Future Enhancements
🔸 Helm-based deployments

🔸 Ingress + HTTPS (TLS)

🔸 Argo CD Image Updater

🔸 Monitoring with Prometheus & Grafana


# 📸 Screenshots

## 🖥️ Application Output


![Application Output](screenshot/<img width="1920" height="1080" alt="Screenshot (184)" src="https://github.com/user-attachments/assets/de59970e-0719-4607-9640-35f46d6462e1" />)

## 🖥️ Argo CD Application View


![Argo CD Application View](screenshot/<img width="1920" height="1080" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/43b2e2ea-ab24-42cd-9a83-c7b1dc4f298d" />
)

## 🖥️ Kubernetes Cluster Nodes


![Kubernetes Cluster Nodes](screenshot/<img width="1920" height="1080" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/7cef8ff1-7379-4256-a712-47d59ddb6190" />
)


