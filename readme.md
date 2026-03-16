# 🚀 CampusCode

**CampusCode** is a coding contest and practice platform designed for colleges, coding clubs, and developer communities.  
It enables administrators to create programming contests, manage problems, evaluate code submissions automatically, and maintain real-time leaderboards.

The platform aims to provide an experience similar to platforms like **Codeforces** and **LeetCode**, but tailored specifically for **campus-level coding competitions**.

---

# 📌 Features

## 👨‍💻 User Features
- User registration and authentication
- Participate in coding contests
- Solve programming problems
- Submit code in multiple languages
- Automated code execution and evaluation
- View submission history
- Real-time leaderboard ranking
- Track contest performance

---

## 🛠️ Admin Features
- Create and manage coding contests
- Add and edit problems
- Upload and manage test cases
- Monitor contest participation
- Manage submissions
- View contest analytics

---

## 🧑‍💼 Super Admin Features
- Platform-level configuration
- Admin management
- Global analytics
- Platform monitoring
- System maintenance tools

---

# 🏗️ System Architecture

```
User
 │
 ▼
Frontend (HTML + Tailwind + JS)
 │
 ▼
Backend API (Node.js + Express)
 │
 ▼
Database (PostgreSQL)
 │
 ▼
Code Execution Engine (Piston API)
```

---

# 🛠️ Tech Stack

| Layer | Technology |
|------|-------------|
| Frontend | HTML, TailwindCSS, JavaScript |
| Backend | Node.js, Express.js |
| Database | PostgreSQL |
| Code Execution | Piston API |
| Authentication | JWT |
| Version Control | Git & GitHub |

---

# 📂 Project Structure

```
campuscode/
│
├── backend/
│   ├── controllers/        # Business logic
│   ├── routes/             # API routes
│   ├── models/             # Database models
│   ├── middleware/         # Auth and validation
│   ├── config/             # Database config
│   └── server.js           # Entry point
│
├── frontend/
│   ├── pages/
│   ├── components/
│   └── assets/
│
├── docs/                   # Project documentation
├── .env                    # Environment variables
├── package.json
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/princekumar-git/campuscode.git
cd campuscode
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

# 🔐 Environment Variables

Create a `.env` file in the root directory and add:

```env
PORT=3000

DATABASE_URL=postgres://username:password@localhost:5432/campuscode_db

JWT_SECRET=your_super_secret_key_123

EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-password
```

---

# 🗄️ Database Setup

Install **PostgreSQL** and create the database:

```sql
CREATE DATABASE campuscode_db;
```

Verify that your `.env` file contains the correct credentials.

---

# ▶️ Running the Application

Start the development server:

```bash
npm run dev
```

Or run normally:

```bash
npm start
```

Server will start on:

```
http://localhost:3000
```

---

# ⚡ Code Execution

CampusCode uses the **Piston API** to run user code in a sandboxed environment.

Supported languages include:

- C++
- Python
- Java
- JavaScript

Example endpoint:

```
https://emkc.org/api/v2/piston/execute
```

---

# 🏆 Contest Workflow

1. Admin creates a contest
2. Admin adds problems with test cases
3. Users register and join the contest
4. Users submit solutions
5. Code is executed using the Piston API
6. Results are evaluated
7. Leaderboard updates automatically

---

# 🔮 Future Improvements

- Real-time leaderboard updates (WebSockets)
- AI-based coding mentor
- Code plagiarism detection
- Advanced analytics dashboard
- Docker deployment
- CI/CD pipeline
- Problem discussion forums
- Code editor with syntax highlighting

---

# 🤝 Contributing

Contributions are welcome.

### Steps to Contribute

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Make changes and commit

```bash
git commit -m "Add new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Prince Kumar**

CSE Student  
Backend Developer  
Building developer tools and coding platforms.

🔗 GitHub  
https://github.com/princekumar-git

---

# ⭐ Support

If you like this project, consider giving it a **star** on GitHub.  
It helps others discover the project and motivates further development.
