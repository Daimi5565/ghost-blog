# Ghost Blog with Substack Integration (Kubernetes Deployment)

This project sets up a **Ghost CMS blog**, imports data from **Substack**, and runs on a **Kubernetes cluster** for scalability and automation. It also includes tools for **automating post uploads** to Ghost using the Admin API.

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
  - [Deploying Ghost on Kubernetes](#deploying-ghost-on-kubernetes)
- [Configuring Ghost CMS](#configuring-ghost-cms)
- [Importing Data from Substack](#importing-data-from-substack)
  - [Exporting Substack Data](#exporting-substack-data)
  - [Importing Posts](#importing-posts)
  - [Importing Subscribers](#importing-subscribers)
- [Admin API Authentication](#admin-api-authentication)
- [Automating Post Uploads](#automating-post-uploads)
- [Troubleshooting Common Issues](#troubleshooting-common-issues)
- [Maintaining Your Repository](#maintaining-your-repository)
- [Documentation](#documentation)
- [License](#license)

## 🔹 Project Overview

This project deploys a **Ghost CMS instance** within a Kubernetes cluster to manage blog posts and newsletters. It integrates **Substack**, allowing seamless import of articles and subscriber lists, and includes automation scripts for **bulk post uploads** using the Ghost Admin API.

## 🚀 Features
✔ **Ghost CMS running on Kubernetes**  
✔ **Substack data import for posts & subscribers**  
✔ **Automated post uploads with API integration**  
✔ **Self-hosted & scalable setup**  
✔ **Documented troubleshooting & best practices**  

## 🛠️ Requirements
- Docker & Kubernetes (Minikube or local K8s setup)
- Helm (for Ghost deployment)
- Ghost Admin API Key (for automation)
- Substack account for data export
- Node.js (for running automation scripts)

## 📌 Deploying Ghost on Kubernetes
### **Step 1: Apply Kubernetes Manifests**
1️⃣ Clone the repository:
```bash
git clone https://github.com/Daimi5565/ghost-blog.git
cd ghost-blog
