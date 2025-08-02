# 🚀 DevOps CI/CD Demo App

This is a demo Node.js + Express application showcasing a complete CI/CD pipeline. The app is deployed using [Railway](https://railway.app), and every push to the GitHub repository triggers an automatic build and deployment.

---

## 📦 Tech Stack

- 🟩 Node.js
- 🚂 Express.js
- 📦 Railway for hosting & CI/CD
- 💻 GitHub for version control and deployment automation

---

## 🔧 Project Structure

devops-demo-app/
├── .github/
│ └── workflows/
│ └── deploy.yml # GitHub Actions workflow
├── public/ # Static files (CSS, images, etc.)
├── routes/
│ ├── index.js # Main route
│ └── users.js # Example route
├── views/
│ ├── index.jade # Homepage UI
│ └── layout.jade # Layout wrapper
├── .gitignore
├── app.js # Express app setup
├── package.json
└── README.md

yaml
Copy
Edit



---

## 🚀 Setup Locally

```bash
git clone https://github.com/your-username/devops-demo-app.git
cd devops-demo-app
npm install
npm start


🔁 CI/CD Pipeline (Using GitHub + Railway)

Every push to main triggers a GitHub Action workflow
The app is automatically deployed on Railway
No manual deployment steps needed!


🌐 Live Demo
Once deployed, your app will be live at: 
https://devops-assignment-production.up.railway.app
