# 🎯 JobHunter Web Application
An end-to-end MERN stack job portal where users can create profiles, post job listings, and apply for jobs, integrated with Cloudinary for media uploads and MongoDB for robust data storage.

### 🌐 Live Preview
🚀 Frontend: [Coming Soon]
🔙 Backend: [Coming Soon]

### 💡 Update the FRONTEND_URL and links after deployment.

---

## 🛠️ Tech Stack
### Frontend:
- React.js (with Vite)
- Tailwind CSS
- Axios

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- Cloudinary (Image Uploads)
- Nodemailer (Email Service)

#### Authentication:
- JWT (JSON Web Tokens)
- Bcrypt for password hashing

---

## 🔧 Features
✅ User Signup/Login
✅ Recruiter and Candidate Roles
✅ Job Posting and Management
✅ Resume Upload via Cloudinary
✅ Email Verification
✅ Secure Password Storage
✅ Mobile Responsive UI
✅ RESTful API Integration

## 📁 Folder Structure (Simplified)
- /client       → Frontend code (React)
- /server       → Backend code (Node + Express)
- /uploads      → For resume/image uploads (if stored locally)
- /env.example  → Environment variable setup guide

## 📦 Environment Variables
Create a .env file in the backend and frontend folders. Example variables:
### Backend .env
- PORT=8000
- SECRET_KEY=your_secret_key
- MONGO_URI=your_mongodb_connection_string

- CLOUDINARY_CLOUD_NAME=your_cloud_name
- CLOUDINARY_API_KEY=your_api_key
- CLOUDINARY_API_SECRET=your_api_secret

- EMAIL_USER=your_email@gmail.com
- EMAIL_PASS=your_email_app_password

- FRONTEND_URL=http://localhost:3000  # or deployed frontend URL

## 🚀 Getting Started
### 1. Clone the Repository
git clone https://github.com/hraj46/JobHunter-WebApplication.git
cd JobHunter-WebApplication

### 2. Install Dependencies
Install backend:

cd server
npm install
Install frontend:

cd ../client
npm install

### 3. Run the Project
Start backend:

cd ../server
npm start
Start frontend:

cd ../client
npm run dev
## 📸 Screenshots
<img width="1872" height="919" alt="Screenshot (208)" src="https://github.com/user-attachments/assets/10fbca7c-3e71-4561-948a-ba3ed1f62c0d" />
<img width="1895" height="916" alt="Screenshot (209)" src="https://github.com/user-attachments/assets/40ea7041-53e5-4990-bef1-82929b2d49c1" />
<img width="1897" height="919" alt="Screenshot (210)" src="https://github.com/user-attachments/assets/0ba3baca-f2ba-481c-be1a-b08e1b51bfb2" />
<img width="1891" height="913" alt="Screenshot (211)" src="https://github.com/user-attachments/assets/54c50bc4-091d-408e-8139-99cbcce76ad8" />

## 🤝 Contributing
Contributions, suggestions, and issues are welcome!
Please open a pull request or issue for any changes or questions.

## 📜 License
MIT License © Himanshu Raj
