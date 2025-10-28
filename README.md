
# static-website-githubpages

Simple static site for DevOps Internship — hosted on GitHub Pages.

**Live site:** https://manoharrmnhr.github.io/static-website-githubpages/

**How to run locally**
Open `index.html` in a browser.

**Built with**
- HTML, CSS
MD

# TASK 6 — Host a Static Website with GitHub Pages

## 🎯 Objective
Deploy a simple HTML website using **GitHub Pages**.

## 🧰 Tools
- GitHub  
- GitHub Pages

## 📦 Deliverables
- Live Website Link  
- GitHub Repository Link

---

## 📝 Summary
In this task, you will create a simple HTML website and host it using GitHub Pages.  
The steps include creating an `index.html` file, pushing it to GitHub, enabling GitHub Pages, and customizing it with CSS.

---

## ⚙️ Steps to Follow

### 1️⃣ Create Project and `index.html`
```bash
mkdir static-website-githubpages
cd static-website-githubpages
nano index.html
```
Add the following content:
```bash
<!DOCTYPE html>
<html>
<head>
  <title>My Static Website</title>
</head>
<body>
  <h1>Welcome to My Static Website!</h1>
  <p>Hosted with GitHub Pages 🚀</p>
</body>
</html>
```
### 2️⃣ Initialize Git and Commit
```bash
git init
git add .
git commit -m "Initial commit - static website"
```
### 3️⃣ Create a New GitHub Repository
Go to GitHub → New Repository
Name it (e.g., static-website-githubpages)
Keep it Public
Click Create Repository

### 4️⃣ Push Code to GitHub
```bash
git remote add origin https://github.com/manoharrmnhr/static-website-githubpages.git
git branch -M main
git push -u origin main
```
### 5️⃣ Enable GitHub Pages
Go to Repo → Settings → Pages
Under Source, select main branch and /(root) folder
Click Save

### 6️⃣ Access Your Live Website
GitHub will provide a live link like:
👉 https://manoharrmnhr.github.io/static-website-githubpages/

### ✅ Final Deliverables
GitHub Repo: https://github.com/manoharrmnhr/static-website-githubpages
Live Website: https://manoharrmnhr.github.io/static-website-githubpages/

---

## 👤 Author
**Name:** Manohar R  
**Role:** DevOps Intern  
**Task:** TASK 6 — Host a Static Website with GitHub Pages  
**Date:** October 2025 
