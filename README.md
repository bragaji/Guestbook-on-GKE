# 📘 Guestbook on GKE

This project deploys a **Guestbook application** on **Google Kubernetes Engine (GKE)** using Kubernetes manifests and Helm charts. The application serves as a simple demonstration of how to manage a multi-tier web application using cloud-native infrastructure.

---

## 🚀 Project Overview

The Guestbook app consists of a **frontend**, **backend**, and **Redis** caching layer, all deployed via Kubernetes on GKE. It provides a real-time comment board where users can post messages that persist across sessions.

---

## 🧰 Tech Stack

- **Google Kubernetes Engine (GKE)**
- **Kubernetes**
- **Helm**
- **Docker**
- **Redis**
- **Google Cloud Platform (GCP)**

---

## 🏗️ Architecture

+------------+ +------------+ +--------------+
| Frontend | <---> | Backend | <---> | Redis |
| (web app) | | (API svc) | | (cache/store)|
+------------+ +------------+ +--------------+

Deployed as:

Frontend Pod + Service

Backend Pod + Service

Redis Pod + Service
