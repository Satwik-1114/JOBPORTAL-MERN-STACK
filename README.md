# 💼 JOBPORTAL  

A **Full-Stack Job Portal Application** built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js).  
This platform allows **job seekers** to search and apply for jobs, while **employers** can post and manage job listings.  

---

## 🚀 Features  

### 👨‍💻 Job Seekers  
- Register & Login securely  
- Profile management  
- Browse job listings  
- Apply for jobs  
- View applied jobs in dashboard  

### 🏢 Employers  
- Register & Login securely  
- Post new jobs  
- Manage job listings  
- View applicants for each job  
- Employer dashboard  

### 🔒 Security  
- JWT-based authentication  
- HttpOnly cookies for secure login  
- Protected API routes with middleware  

---

## 🛠️ Tech Stack  

### Frontend  
- ⚛️ React.js  
- 🌐 React Router DOM  
- 📦 Axios  
- 🎨 TailwindCSS / Custom CSS  
- 🔔 SweetAlert2  

### Backend  
- 🟢 Node.js  
- 🚂 Express.js  
- 🍃 MongoDB + Mongoose  
- 🔑 JWT Authentication  
- 🍪 Cookie Parser & CORS  

---

## 📂 Project Structure  

Jobportal/

│── Backend/ # Node.js + Express API

│ ├── models/ # Mongoose models (User, Job, Applications)

│ ├── routes/ # Express routes

│ ├── controllers/ # Business logic

│ ├── middlewares/ # Auth middlewares

│ └── server.js # Entry point

│

│── Frontend/ # React.js app

│ ├── src/

│ │ ├── components/ # Reusable UI components

│ │ ├── Layout/ # Dashboard layouts

│ │ ├── context/ # Context API

│ │ ├── pages/ # Pages (Login, Register, Dashboard, etc.)

│ │ └── App.js

│ └── package.json

│

└── README.md


---

## ⚙️ Installation & Setup  

### Clone Repository  
```bash
git clone https://github.com/Satwik-1114/JOBPORTAL.git
cd JOBPORTAL

🔧 Backend Setup
cd Backend
npm install

---

Create .env file inside Backend/:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
COOKIE_SECRET=your_cookie_secret

---

Start Backend:

npm run dev

🎨 Frontend Setup

cd Frontend

npm install

npm start

---

🔗 API Endpoints

Auth

POST /api/v1/auth/register → Register user

POST /api/v1/auth/login → Login user

POST /api/v1/auth/logout → Logout user

GET /api/v1/auth/me → Get logged-in user

---

Jobs

POST /api/v1/jobs → Create job (Employer only)

GET /api/v1/jobs → Get all jobs

GET /api/v1/jobs/:id → Get job by ID

PUT /api/v1/jobs/:id → Update job (Employer only)

DELETE /api/v1/jobs/:id → Delete job (Employer only)

-----

Applications

POST /api/v1/apply/:jobId → Apply for a job

GET /api/v1/applications → Get applications of logged-in user

---

🧑‍💻 Contributors

👨‍💻 Satwik – Full Stack Developer and Refrence from https://www.youtube.com/@mdalmamunit427

 
