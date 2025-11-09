# 🌐 My WebApp


A simple static web application demonstrating **DevOps fundamentals** — version control with **Git & GitHub**, and containerization with **Docker**.
for SGA-2 of Sofware development and practices course BITS Pilani.

This repository contains three static HTML pages and a Dockerized Python application that prints "Hello, World from Docker!" to the console.


---

## 📁 Project Structure

```

my-webapp/
├── index.html
├── about.html
├── contact.html
├── app.py
└── Dockerfile

````

- `index.html` – Homepage  
- `about.html` – About the project or team  
- `contact.html` – Contact information page  
- `app.py` – Simple Python "Hello World" app (used for Docker demonstration)  
- `Dockerfile` – Instructions to build the Docker image

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/my-webapp.git
cd my-webapp
````

### 2. Open Web Pages Locally

Simply open any HTML file in your browser:

```
index.html
about.html
contact.html
```

---

## 🐳 Running the Docker Application

### 1. Build the Docker Image

```bash
docker build -t mydockeruser/hello-world-app:1.0 .
```

### 2. Run the Container

```bash
docker run --rm mydockeruser/hello-world-app:1.0
```

**Expected Output:**

```
Hello, World from Docker!
```

---

## ☁️ Push Image to Docker Hub

1. Login to Docker Hub:

   ```bash
   docker login
   ```

2. Push the image:

   ```bash
   docker push mydockeruser/hello-world-app:1.0
   ```

You can now pull the image on any system with Docker installed.

---

# Git Commands Used

| Purpose        | Command                          |
| -------------- | -------------------------------- |
| Initialize Git | `git init`                       |
| Check status   | `git status`                     |
| Add files      | `git add .`                      |
| Commit changes | `git commit -m "Initial commit"` |
| View history   | `git log`                        |
| Create branch  | `git branch feature-update`      |
| Switch branch  | `git switch feature-update`      |
| Push to GitHub | `git push -u origin main`        |

---


## 👤 Author

**Aabid Sofi**

