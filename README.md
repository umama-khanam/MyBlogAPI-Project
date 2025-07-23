# MyBlogAPI-Project
MyBlogAPI is a full-stack blog application that allows users to perform complete CRUD operations (Create, Read, Update, Delete) on blog posts. The project is built with Node.js and Express.js, featuring a custom-built RESTful Blog API that communicates with a dynamic frontend through HTTP requests.
The project consists of:

-A Blog API server (index.js) running on port 4000, handling all backend requests.
-A Frontend Blog Website (server.js) running on port 3000, where users can interact via a clean UI to manage blog entries.
-Both servers run independently in separate terminals but are tightly integrated for smooth, real-time blog management.
-A custom-built backend server (index.js) that handles API logic and needs to be running on localhost:4000.
-A frontend server (server.js) that makes HTTP requests to that backend and runs on localhost:3000.
-The two parts are dependent on each other and must both be running locally for the app to function.

## 🚀 Tech Stack

- **Node.js**
- **Express.js**
- **HTML / CSS / JavaScript**
- **RESTful API**
- **Middleware (body-parser, etc.)**
- **Fetch API** for client-server communication

---
## ✨ Features

- ✅ Add new blog posts via a user-friendly form
- 📄 View all existing blog posts
- ✏️ Edit/update blog posts
- ❌ Delete blog posts
- 🔁 Real-time interaction between frontend and backend
- 🔗 Two servers connected via Fetch API (frontend ➝ backend)

---
## ⚙️ How It Works

- **Backend API** runs on **port 4000** (`index.js`)
  - Handles all blog data with RESTful routes
  - Stores blog data in-memory (or use JSON if implemented)

- **Frontend server** runs on **port 3000** (`server.js`)
  - Serves HTML, CSS, and JS files
  - Uses `fetch()` to communicate with the backend API

- Both servers must be running **in separate terminals** for the project to work properly.

---
## 📸 Project Preview

### 🔹 Homepage View
![Blog Homepage](./screenshots/blog-ui.png)

### 🔹 Create/Edit Blog View
![Blog Form](./screenshots/blog-form.png)

## 🚫 Live Hosting Not Available

> This project **cannot be hosted live** because it runs two local servers (frontend and backend).  
> To view and use this project, you must **run it locally** on your computer by following the steps below.

---

## ⚙️ How to Run the Project Locally

### ✅ Prerequisites

- Node.js installed on your system
- Any code editor (VS Code recommended)
- Terminal or command prompt access

---

### 🧩 Step-by-Step Setup

1. **Clone the Repository**
2. **Start the Backend API Server (Port 4000)**
3. cd backend
   npm install
   node index.js
Backend will start on: http://localhost:4000
4.**Start the Frontend Server (Port 3000)**
    cd frontend
    npm install
    node server.js
Frontend website will run on: http://localhost:3000

## 🙋‍♀️ Author
-Made with ❤️ by Umama Khanam

-Feel free to explore and contribute

 
