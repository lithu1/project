# CI/CD Pipeline for Dockerized Flask Application

This project demonstrates a complete CI/CD pipeline setup for a simple Python Flask web application using Docker and GitHub Actions. The pipeline automatically builds and pushes the Docker image to Docker Hub when changes are pushed to the `main` branch.

---

## 🚀 Project Objective

- Automate the deployment of a Flask app using GitHub Actions.
- Build and push Docker images to Docker Hub using a secure token.
- Run the app locally using Docker.

---

## 🛠️ Tools & Technologies Used

- Python 3.9  
- Flask Web Framework  
- Docker  
- GitHub Actions  
- Docker Hub  
- Linux (WSL/Ubuntu)

---

## 📁 Folder Structure

```
project/
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── templates/
│       └── index.html
├── Dockerfile
└── .github/
    └── workflows/
        └── ci.yml
```

---

## ⚙️ How It Works

1. A Flask app is containerized using Docker.
2. A GitHub Actions workflow is triggered on each push to the `main` branch.
3. The workflow logs in to Docker Hub, builds the image, and pushes it.
4. The final image is publicly available on Docker Hub.

---

## 🔐 GitHub Secrets Required

Set these secrets in your GitHub repository:

| Secret Name       | Description                         |
|-------------------|-------------------------------------|
| `DOCKER_USERNAME` | Your Docker Hub username (`lithu213`) |
| `DOCKER_PASSWORD` | Your Docker Hub access token        |

---

## 🐳 Docker Image

- **Docker Hub Repo**: [lithu213/project](https://hub.docker.com/r/lithu213/project)
- **Pull the Image**:
  ```bash
  docker pull lithu213/project:latest
  ```

---

## ▶️ Run the Application Locally

```bash
docker run -p 5000:5000 lithu213/project:latest
```

Then visit: [http://localhost:5000](http://localhost:5000)

---

## ✅ CI/CD Workflow (GitHub Actions)

The CI/CD pipeline (`ci.yml`) performs the following:

- Checks out the repository
- Logs in to Docker Hub
- Builds the Docker image
- Pushes the image to Docker Hub

---

## 📸 Screenshots

> Include the following screenshots in your submission:
- GitHub Actions: Successful build log
- Docker Hub: Image listed with `latest` tag
- Web browser showing `http://localhost:5000`
- Terminal showing `docker run` log


![image](https://github.com/user-attachments/assets/5afc6d25-07fe-44b2-9603-27f3407c63a3)
![image](https://github.com/user-attachments/assets/9a46d5f7-6356-46a4-a684-d652b769fe4a)
# CI/CD Pipeline for Dockerized Flask Application

This project demonstrates a complete CI/CD pipeline setup for a simple Python Flask web application using Docker and GitHub Actions. The pipeline automatically builds and pushes the Docker image to Docker Hub when changes are pushed to the `main` branch.

---

## 🚀 Project Objective

- Automate the deployment of a Flask app using GitHub Actions.
- Build and push Docker images to Docker Hub using a secure token.
- Run the app locally using Docker.

---

## 🛠️ Tools & Technologies Used

- Python 3.9  
- Flask Web Framework  
- Docker  
- GitHub Actions  
- Docker Hub  
- Linux (WSL/Ubuntu)

---

## 📁 Folder Structure

```
project/
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── templates/
│       └── index.html
├── Dockerfile
└── .github/
    └── workflows/
        └── ci.yml
```

---

## ⚙️ How It Works

1. A Flask app is containerized using Docker.
2. A GitHub Actions workflow is triggered on each push to the `main` branch.
3. The workflow logs in to Docker Hub, builds the image, and pushes it.
4. The final image is publicly available on Docker Hub.

---

## 🔐 GitHub Secrets Required

Set these secrets in your GitHub repository:

| Secret Name       | Description                         |
|-------------------|-------------------------------------|
| `DOCKER_USERNAME` | Your Docker Hub username (`lithu213`) |
| `DOCKER_PASSWORD` | Your Docker Hub access token        |

---

## 🐳 Docker Image

- **Docker Hub Repo**: [lithu213/project](https://hub.docker.com/r/lithu213/project)
- **Pull the Image**:
  ```bash
  docker pull lithu213/project:latest
  ```

---

## ▶️ Run the Application Locally

```bash
docker run -p 5000:5000 lithu213/project:latest
```

Then visit: [http://localhost:5000](http://localhost:5000)

---

## ✅ CI/CD Workflow (GitHub Actions)

The CI/CD pipeline (`ci.yml`) performs the following:

- Checks out the repository
- Logs in to Docker Hub
- Builds the Docker image
- Pushes the image to Docker Hub

---

## 📸 Screenshots

> Include the following screenshots in your submission:
- GitHub Actions: Successful build log
- Docker Hub: Image listed with `latest` tag
- Web browser showing `http://localhost:5000`
- Terminal showing `docker run` log



![image](https://github.com/user-attachments/assets/c600f1fc-31f9-4155-a736-545d396e0a9a)
![image](https://github.com/user-attachments/assets/5afc6d25-07fe-44b2-9603-27f3407c63a3)
![image](https://github.com/user-attachments/assets/9a46d5f7-6356-46a4-a684-d652b769fe4a)
![image](https://github.com/user-attachments/assets/a75f0162-506f-4112-ad73-808c06e7158d)




---






---


