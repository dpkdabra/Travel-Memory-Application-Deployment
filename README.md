# 🚀 TravelMemory MERN Deployment on AWS

## 🌐 Live Application
https://ranked-farming-markets-pamela.trycloudflare.com

---

## 🧰 Tech Stack

- AWS EC2 (Ubuntu)
- Node.js
- React.js
- MongoDB Atlas
- Nginx
- PM2
- Application Load Balancer
- Cloudflare Tunnel (HTTPS)

---

## ⚙️ Backend Deployment

- Cloned backend repository
- Configured `.env` with MongoDB Atlas
- Backend running on port 3000
- Managed using PM2

---

## 🎨 Frontend Deployment

- Updated API base URL
- Created production build
- Deployed using Nginx

---

## 🔁 Reverse Proxy (Nginx)

Routes:

- `/` → React frontend
- `/api` → Node.js backend

---

## 📈 Scalability & Load Balancing

- Created 2 EC2 instances
- Configured Target Group
- Attached to Application Load Balancer
- Health checks enabled

---

## 🔐 Public Access with HTTPS

Application exposed securely using:

- Cloudflare Tunnel
- Auto-generated HTTPS URL

---

## 🏗 Architecture Diagram

See `/architecture` folder.

---

## 🔒 Security Best Practices

- Environment variables for secrets
- Reverse proxy
- Process manager (PM2)
- Load balancer for high availability

---

## 🚀 Future Improvements

- Auto Scaling Group
- CI/CD pipeline
- Docker containerization
- Route53 custom domain
