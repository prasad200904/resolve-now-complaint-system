# 🛠️ ResolveNow – Online Complaint Registration and Management System

ResolveNow is a full-stack web application designed to simplify and streamline the process of complaint registration, tracking, and management. It allows users to raise complaints, agents to respond to them, and admins to manage the entire workflow efficiently.

## 🚀 Features

- 📝 User registration & login (JWT authentication)
- 📢 Complaint submission with category & description
- 📊 Complaint status tracking (Open, In Progress, Resolved)
- 🧑‍💼 Admin dashboard to manage users & complaints
- 🛠️ Agent dashboard to handle assigned complaints
- 🔔 Real-time status updates & notifications (basic)
- 🔒 Secure RESTful API with protected routes

## 💻 Tech Stack

| Layer        | Technology           |
|--------------|----------------------|
| Frontend     | React.js, Tailwind CSS |
| Backend      | Node.js, Express.js   |
| Database     | MongoDB (Mongoose)    |
| Authentication | JWT (JSON Web Tokens) |
| API Testing  | Postman               |

## 📁 Project Structure

resolve-now-complaint-system/
├── client/ # React frontend
│ └── src/
├── server/ # Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── middleware/
├── .env
├── package.json
└── README.md

## ⚙️ Installation & Running Locally

### Backend

```bash
cd server
npm install
# Create a .env file with your MongoDB URI and JWT_SECRET
npm start

cd client
npm install
npm start

🙋‍♂️ Author
Prasad Vundraladurga
B.Tech - Internet of Things
GitHub: @prasad200904

📄 License
This project is licensed under the MIT License.

---

### ✅ How to Use It:

1. Create a file in your project root named `README.md`.
2. Copy-paste the content above into that file.
3. Add any **screenshots** in a `screenshots/` folder and link them inside the README (optional).
4. Include this file in your `.zip` before submitting the project.

---

Let me know if you'd like help:
- Creating `.env` format
- Writing a short **project summary** for submission form
- Deploying this project on Render or Vercel

All the best!
