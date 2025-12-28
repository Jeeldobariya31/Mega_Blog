# 📝 BlogZillas 🚀  
### Modern Full-Featured Blogging Platform

![Vercel](https://img.shields.io/badge/Deployed-Vercel-black?logo=vercel)
![React](https://img.shields.io/badge/React-18-blue?logo=react)
![Redux](https://img.shields.io/badge/Redux-Toolkit-purple?logo=redux)
![Appwrite](https://img.shields.io/badge/Backend-Appwrite-pink?logo=appwrite)
![TinyMCE](https://img.shields.io/badge/Editor-TinyMCE-green?logo=tinymce)
![License](https://img.shields.io/badge/License-Open--Source-success)

---

## 🌐 Live Demo

👉 **https://blogzillas.vercel.app**

---

## 📖 About BlogZillas

**BlogZillas** is a modern, scalable, and full-featured blogging web application built using **React**, **Appwrite App Server**, and **TinyMCE**.

It allows users to securely authenticate, write rich blog content, manage posts, and publish blogs through a clean and responsive user interface.  
Designed for developers, writers, and content creators who want a powerful blogging experience ✨

---

## 🚀 Features

- 🔐 Secure User Authentication (Signup / Login / Logout)
- 🛡 Protected Routes (Auth Layout)
- ✍️ Rich Text Editor using **TinyMCE**
- 🗂 Create, Edit, Delete & Read Blog Posts
- 📰 View All Blogs & Single Blog Pages
- 📬 Contact Page with Email Utility
- 📄 Privacy Policy & Terms Pages
- 🧠 Global State Management using **Redux Toolkit**
- 🎨 Reusable UI Components
- 📱 Fully Responsive Design
- ⚡ Fast & Scalable Backend powered by **Appwrite**
- ☁️ Deployed on **Vercel**

---

## 🛠️ Tech Stack

### 🎨 Frontend
- ⚛️ React (Vite)
- 🧠 Redux Toolkit
- 🔀 React Router DOM
- 🎨 CSS

### 🖥 Backend / Services
- 🚀 Appwrite (App Server)
  - Authentication
  - Database
  - Storage

### ✍️ Editor
- 📝 TinyMCE Rich Text Editor

### ☁️ Deployment
- Vercel

---

## 📂 Project Structure (With Explanation)

```bash
src/
│
├── appWrite/
│   ├── auth.js        # Appwrite authentication logic
│   ├── conf.js        # Environment & project configuration
│   ├── config.js     # Database, collection & bucket setup
│   └── index.js      # Appwrite client initialization
│
├── components/
│   ├── AuthLayout.jsx # Protected route wrapper
│   ├── Button.jsx    # Reusable button component
│   ├── Header/       # App header & navigation
│   ├── Footer/       # Footer component
│   └── container/    # Layout containers
│
├── pages/
│   ├── Home.jsx          # Landing page
│   ├── Login.jsx         # Login page
│   ├── Signup.jsx        # Signup page
│   ├── AddPost.jsx       # Create new blog
│   ├── EditPost.jsx      # Edit existing blog
│   ├── AllPosts.jsx      # View all blogs
│   ├── Post.jsx          # Single blog view
│   ├── Contact.jsx       # Contact page
│   ├── PrivacyPolicy.jsx # Privacy policy
│   └── Term.jsx          # Terms & conditions
│
├── store/
│   ├── authSlice.js   # Redux authentication state
│   └── store.js      # Redux store configuration
│
├── utils/
│   └── email.js      # Email helper utility
│
├── App.jsx           # Root component
├── App.css           # Global styles
└── main.jsx          # Application entry point


⚙️ Environment Variables

Create a .env file in the project root:

VITE_APPWRITE_URL=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
VITE_APPWRITE_BUCKET_ID=your_bucket_id
VITE_TINYMCE_API_KEY=your_tinymce_api_key


🧑‍💻 How to Clone & Run Locally

1️⃣ Clone the Repository
git clone https://github.com/your-username/blogzillas.git
cd blogzillas

2️⃣ Install Dependencies
npm install

3️⃣ Run Development Server
npm run dev


🌍 Open in browser:
http://localhost:5173


🔐 Authentication Flow

🔒 Only logged-in users can:
- Create blogs
- Edit blogs

🧠 Auth state managed using Redux Toolkit  
🛡 Protected routes handled via AuthLayout


✍️ TinyMCE Editor Highlights

✨ Rich text formatting  
🖼 Image embedding  
🔗 Links & lists  
🧾 Clean HTML output  
📰 Professional blogging experience  


📦 Deployment

🚀 Deployed on Vercel

npm run build

Connect your GitHub repository to Vercel and deploy instantly.


🤝 Contributing

Contributions are welcome! 🙌
- Fork the repository
- Create your feature branch
- Commit your changes
- Open a Pull Request


👑 Owner

-Jeel Dobariya  
-Project Owner & Maintainer 
-Building modern, scalable & high-quality web applications
TechSphere Devs  
-📧 Contact Email: techsphere.devs@gmail.com


📜 License

This project is open-source and available for learning, personal, and educational use.


⭐ Support

If you like this project:
- ⭐ Star the repository
- 🔁 Share it with others


🔥 Happy Blogging with BlogZillas! 📝🚀
