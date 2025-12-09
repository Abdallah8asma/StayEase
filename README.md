# 🏡 Guest House Management System

## 📌 Description

**Guest House Management System** est une application web permettant de gérer une maison d’hôte via un **dashboard d’administration**.

L’application permet de :

* Gérer les maisons d’hôtes
* Gérer les utilisateurs (clients / admin)
* Gérer les réservations
* Suivre l’état des disponibilités
* Administrer l’application via un dashboard moderne

---

## 🧱 Architecture

Le projet est composé de :

* **Backend** : API REST
* **Dashboard** : Interface d’administration
* **Docker** : Conteneurisation des services
* **Kubernetes (K8s)** : Orchestration des containers
* **CI/CD** : Jenkins Pipeline
* **Sécurité** : Scan des images avec Trivy
* **Qualité** : Analyse du code avec SonarQube
* **Cloud** : AWS ECR pour stocker les images Docker

---

## 🖼️ Aperçu de l’application

Crée un dossier nommé **images** à la racine du projet et ajoute tes captures d’écran dedans.

Structure attendue :

```text
project-root/
 ├── images/
 │   ├── dashboard.png
 │   ├── login.png
 │   └── reservations.png
```

### 🔐 Page Login

![Login](images/login.png)

### 📊 Dashboard Admin

![Dashboard](images/Capture d'écran 2025-12-08 171252.png)

### 📅 Gestion des Réservations

![Reservations](images/reservations.png)

  ### 📅 SAST : SonarQube

![SonarQube](images/Capture d'écran 2025-12-08 171406.png)

  ### 📅 Trivy

![Trivy](images/Capture d'écran 2025-12-08 173215.png)

  ### 📅 Amazon ECR

![Amazon ECR](images/Capture d'écran 2025-12-08 171450.png)

  ### 📅 Kubernetes

![Kubernetes](images/Capture d'écran 2025-12-08 172730.png)

  ### 📅 Pipeline jenkins

![jenkins](images/Capture d'écran 2025-12-08 173142.png)

  ### 📅 Prometheus

![Prometheus](images/Capture d'écran 2025-12-08 171612.png)

  ### 📅 Grafana

![Grafana](images/Capture d'écran 2025-12-08 171922.png)


---

## ⚙️ Pipeline Jenkins – CI/CD

Ce projet utilise un pipeline Jenkins automatisé pour :

* Cloner le code depuis GitLab
* Analyser la qualité du code avec SonarQube
* Construire les images Docker
* Scanner les vulnérabilités avec Trivy
* Publier les images sur AWS ECR
* Déployer l’application sur Kubernetes
* Envoyer des notifications Slack et Email

---

## 🛡️ Sécurité

Le projet intègre :

* L’analyse de vulnérabilités des images Docker
* Le contrôle de la qualité du code avec SonarQube

---

## ✉️ Notifications

Le pipeline envoie automatiquement :

* Des notifications sur Slack
* Des emails après chaque exécution du pipeline

---

## 👩‍💻 Réalisé par

**Nom :** Asma Abdallah
**Email :** [ab.abdallahasma@gmail.com](mailto:ab.abdallahasma@gmail.com)

---

