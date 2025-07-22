Host a Website on Firebase using Termux

This repository provides a complete guide to hosting a **static website** on [Firebase Hosting](https://firebase.google.com/docs/hosting) using **Termux** on an Android device.

---

## 📦 Requirements

- Android phone with Termux installed
- Google Account
- Basic knowledge of HTML/CSS
- Static website (HTML, CSS, JS files)

---

## 🛠️ Setup Instructions

### 1. Update & Install Node.js

pkg update && pkg upgrade
pkg install nodejs

2. Install Firebase CLI

npm install -g firebase-tools

3. Login to Firebase

firebase login

> This will open a browser. Sign in with your Google account.



4. Initialize Firebase Project

mkdir mywebsite
cd mywebsite
firebase init

Choose Hosting

Select or create a project

Set public directory (e.g., public)

Configure as single-page app (Y/N)

Choose whether to overwrite index.html


5. Add Website Files

Place your static site files (HTML, CSS, JS) in the public folder.

6. Deploy to Firebase

firebase deploy

After deploying, you'll get a URL like:

https://your-project-id.web.app




🔧 Common Firebase CLI Commands

Command	Description

firebase login	Sign in to Firebase
firebase init	Initialize Firebase in your folder
firebase deploy	Deploy to Firebase Hosting
firebase logout	Sign out
firebase projects:list	List your Firebase projects
firebase serve	Preview your site locally

