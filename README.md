<h1 align="center">📦 Store It</h1>
<h3 align="center">The only storage solution you need — A Cloud Storage and File Sharing Platform</h3>

<p align="center">
  <a href="https://google-drive-clone-zeta.vercel.app/">🌐 Live Demo</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white"/>
</p>

---

## 🤖 Introduction

**Store It** is a storage management and file sharing platform that lets users effortlessly upload, organize, and share files.  
Built with **Next.js 15**, **React 19**, **Appwrite**, and **TailwindCSS**, it provides a seamless experience for modern file management.

---

## 🚀 Live Demo

👉 Try the deployed app here: [Store It – Vercel Deployment](https://google-drive-clone-zeta.vercel.app/)  

---

## 📸 Screenshots

<p align="center">
  <img src="Store-It.png" width="700" alt="Dashboard Screenshot"/>
</p>

<p align="center">
  <img src="upload.png" width="700" alt="upload"/>
</p>




---
## ⚙️ Tech Stack

- ⚛️ React 19  
- ⬛ Next.js 15  
- 🟣 Appwrite (Auth, DB, Storage)  
- 🎨 TailwindCSS  
- 🧩 ShadCN  
- 🔵 TypeScript  

---

## 🔋 Features

- 🔐 **User Authentication with Appwrite** – Signup, login, and logout  
- 📂 **File Uploads** – Upload docs, images, videos, and audio  
- 👀 **View & Manage Files** – Rename, delete, preview files  
- ⬇️ **Download Files** – Instant access to stored files  
- 🤝 **File Sharing** – Share files with others seamlessly  
- 📊 **Dashboard Insights** – Storage usage, recent uploads, file types summary  
- 🔍 **Global Search** – Quickly find files and shared content  
- 🗂️ **Sorting Options** – By date, name, or size  
- 📱 **Responsive Design** – Minimal, clean UI across all devices  

---

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""
```

Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up &
creating a new project on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm run dev
```
