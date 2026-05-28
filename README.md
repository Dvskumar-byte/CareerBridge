# CareerBridge

<p align="center">
  A Full Stack MERN-based Career & Recruitment Platform with Recruiter Verification Workflow, Role-Based Access Control, and Admin Moderation System.
</p>

---

## 🚀 Overview

CareerBridge is a modern job recruitment platform designed to streamline hiring for applicants, recruiters, startups, and administrators.

Unlike traditional job portals, CareerBridge includes a recruiter verification pipeline where startup recruiters must be approved by administrators before gaining access to hiring features. This creates a more secure and controlled recruitment ecosystem.

The platform supports applicants searching and applying for jobs, recruiters managing hiring workflows, and admins moderating recruiter access and platform activity.

---

# ✨ Key Features

## 👨‍💼 Applicant Features

* User Registration & Login
* Browse Available Jobs
* Search & Filter Jobs
* Save Jobs
* Apply for Jobs
* Resume Upload
* Profile Management
* Password Update
* Applied Jobs Tracking

---

## 🏢 Recruiter Features

* Recruiter Registration
* Protected Recruiter Dashboard
* Job Posting & Management
* Application Review System
* Candidate Resume Access
* Hiring Analytics Dashboard
* Edit/Delete Job Posts

---

## 🛡️ Admin Features

* Admin Dashboard
* Recruiter Verification Workflow
* Approve/Reject Recruiters
* Recruiter Moderation System
* Platform Analytics
* User Monitoring
* Job Monitoring
* Application Monitoring

---

# 🔐 Recruiter Verification System

CareerBridge introduces a recruiter moderation architecture:

### Recruiter States

* `pending`
* `trusted`
* `rejected`

### Workflow

1. Recruiter registers using startup/company email
2. Recruiter account enters pending state
3. Admin reviews recruiter request
4. Admin approves or rejects recruiter
5. Only trusted recruiters gain access to:

   * Post jobs
   * Manage applications
   * Access recruiter dashboard

This prevents unauthorized recruiters from misusing platform features.

---

# 🧠 Tech Stack

## Frontend

* React.js
* Redux Toolkit
* Tailwind CSS
* Mantine UI
* Framer Motion

## Backend

* Node.js
* Express.js
* JWT Authentication

## Database

* MongoDB Atlas
* Mongoose

## Cloud & Services

* Cloudinary
* Render / Vercel Deployment

---

# 📁 Project Structure

```bash
CareerBridge/
│
├── client/
│   ├── src/
│   ├── public/
│   └── ...
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   └── ...
│
└── README.md
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/CareerBridge.git
```

---

## 2. Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

## 3. Backend Setup

```bash
cd ../server
npm install
npm run dev
```

---

# 🔑 Environment Variables

Create a `config.env` file inside the server directory.

Example:

```env
PORT=3000

MONGO_URI=your_mongodb_uri

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
```

---

# 📸 Screenshots

* Applicant Dashboard
* Recruiter Dashboard
* Admin Verification Panel
* Recruiter Approval Workflow
* Job Management System

(Add your screenshots here after deployment)

---

# 📈 Future Improvements

* Real-time Notifications
* AI Resume Matching
* Interview Scheduling
* Recruiter Messaging System
* Advanced Job Recommendation Engine

---

# 🌐 Deployment

Frontend can be deployed using:

* Vercel
* Netlify

Backend can be deployed using:

* Render
* Railway

Database:

* MongoDB Atlas

---

# 👨‍💻 Author

Developed and customized by DVS.

---

# 📄 License

This project is intended for educational and portfolio purposes.
