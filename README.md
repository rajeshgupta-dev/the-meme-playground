# 🎨 The Meme Playground

**The Meme Playground** is a full-stack web application built during the **Masai Hackathon** — a creative platform where users can **create, share, and explore memes** in a fun and collaborative environment.  

The project blends humor and technology, focusing on clean UI, smooth user experience, and reliable backend functionality — making it a true “playground” for internet creativity.

---

## 🚀 Project Overview

The Meme Playground enables users to:
- ✏️ **Design and customize memes** with an intuitive canvas editor  
- 📤 **Upload and share memes** securely with others  
- 🔐 **Register and log in** with JWT-based authentication  
- 💬 **Browse and engage** with community-created memes  
- 🧭 **Navigate easily** with a responsive, modern interface  

This project was developed collaboratively during the Masai Hackathon, emphasizing teamwork, clean coding practices, and real-world functionality.

---

## 👨‍💻 Team Members

| Name | Role | GitHub |
|------|------|--------|
| **Ankit Kumar** | Backend Developer / Team Lead  | [@ankit-kumar](https://github.com/) |
| **Rajesh Gupta** | Full Stack Developer | [@rajeshgupta-dev](https://github.com/rajeshgupta-dev) |
| **Rupyam Das** |  Frontend Developer | [@rupyam-das](https://github.com/) |

---

## 🧩 Tech Stack

### **Frontend**
- ⚛️ **React 19** – Component-based UI framework  
- ⚡ **Vite** – Fast modern frontend tooling  
- 💅 **Chakra UI** + **Tailwind CSS** – Responsive, modern styling  
- 🎨 **Fabric.js** – Canvas-based meme editor  
- 🔄 **Axios** – HTTP client for API requests  
- 🧭 **React Router DOM** – Client-side routing  
- ✅ **Formik + Yup** – Form management and validation  
- 🔔 **React Toastify** – Notifications and alerts  

### **Backend**
- 🧩 **Node.js + Express 5** – RESTful API server  
- 🗄️ **MongoDB + Mongoose** – Database and data modeling  
- 🔐 **JWT + bcryptjs** – Authentication and password hashing  
- ☁️ **Cloudinary + Multer** – Image upload and storage  
- 📧 **Nodemailer** – Email notifications  
- 🌍 **CORS + Cookie Parser** – Cross-origin and session handling  
- ⚙️ **Dotenv** – Environment configuration  

---

## 📁 Project Structure

```

📦 The-Meme-Playground
├── client/             # React frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── server/             # Node.js backend
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
├── uploads/
├── server.js
└── package.json

````

---

## ⚙️ Getting Started

### **1. Clone the repository**
```bash
git clone https://github.com/rajeshgupta-dev/the-meme-playground.git
cd the-meme-playground
````

### **2. Install dependencies**

Frontend:

```bash
cd client
npm install
```

Backend:

```bash
cd ../server
npm install
```

### **3. Setup environment variables**

Create `.env` files in both `client` and `server` with configuration like MongoDB URI, JWT secret, Cloudinary credentials, etc.

### **4. Run the application**

Start the backend:

```bash
cd server
npm start
```

Start the frontend:

```bash
cd ../client
npm run dev
```

Visit **[http://localhost:5173](http://localhost:5173)** to use the app.

---

## 🌟 Key Features

* 🖼️ Intuitive meme creation with Fabric.js
* 🧑‍💻 Secure authentication and user management
* ☁️ Cloud-based image hosting
* ⚙️ Modern MERN stack architecture
* 💡 Clean, responsive, and user-friendly design
* 🤝 Collaborative hackathon project built by a team of three developers

---

## 🔍 Future Enhancements

* 🗳️ Meme voting and leaderboard system
* 💬 Commenting and social interactions
* 🔔 Real-time notifications
* 📱 Mobile app integration

---

## 🧾 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 💬 Acknowledgements

We thank the **Masai Hackathon** mentors and organizers for providing a platform to build and innovate under real-world conditions.

> *Built with ❤️ by Rajesh Gupta, Ankit Kumar, and Rupyam Das during the Masai Hackathon.*
