# 🚀 Flask Portfolio Website (Dockerized)

A modern and responsive portfolio website built with **Flask**, **HTML**, and **CSS**, containerized using **Docker** for easy deployment.

## 📸 Preview

![Portfolio Screenshot](images/portfolio.png)

---

## 🛠️ Tech Stack

- 🐍 Python
- 🌐 Flask
- 🎨 HTML5
- 🎨 CSS3
- 🐳 Docker
- 🔧 Git & GitHub

---

## ✨ Features

- Responsive Portfolio Landing Page
- Modern UI Design
- Flask Backend
- Dockerized Application
- Easy Deployment
- Lightweight and Fast

---

## 📂 Project Structure

```
flask-app-simple-portfolio/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── static/
│   ├── css/
│   └── images/
├── templates/
│   └── index.html
└── README.md
```

---

## 🐳 Run with Docker

### Clone Repository

```bash
git clone https://github.com/hdarji1912/flask-app-simple-portfolio.git
cd flask-app-simple-portfolio
```

### Build Docker Image

```bash
docker build -t flask-portfolio .
```

### Run Container

```bash
docker run -d -p 80:80 --name flask-portfolio 
```

Open in browser:

```
http://localhost:80

aws -- ec2 -instance - ipv4 address - copy and paste into browser you will see the result 

```

## 📚 Docker Commands Used

```bash
docker build -t flask-portfolio .

docker images

docker run -d -p 80:80 flask-portfolio

docker ps

docker stop <container-id>

docker rm <container-id>
```

---

## 🎯 Learning Outcomes

- Building a Flask application
- Creating a Dockerfile
- Docker Image Creation
- Running Containers
- Port Mapping
- Containerized Deployment
- Git & GitHub Workflow


---

## 👨‍💻 Author

**Hardik Darji**

Aspiring DevOps Engineer 🚀

### Skills

- Linux
- Git & GitHub
- Shell Scripting
- Python
- Docker

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

Happy Learning! 🚀
