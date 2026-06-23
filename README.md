🎓 Student Management System

A full stack web application to efficiently manage student academic records with features like adding, updating, searching, soft-deleting, and restoring student data.

📌 Project Description

The Student Management System is a full stack web application built using React.js for the frontend and Node.js with Express.js for the backend, connected to a MongoDB database. It allows administrators to manage student records efficiently with a clean and user-friendly interface.

✨ Features

- ✅ Add new student records
- ✅ View all active students
- ✅ Search students by Roll No, Name or Department
- ✅ Update existing student details
- ✅ Soft delete students (data is not permanently lost)
- ✅ Restore deleted students
- ✅ View all deleted students separately
- ✅ Responsive and clean UI

📁 Project Structure
student-management/

├── backend/

│   ├── node_modules/

│   ├── package.json

│   └── server.js

└── frontend/

├── node_modules/

├── public/

├── src/

│   ├── pages/

│   │   ├── Home.jsx

│   │   ├── ShowStudent.jsx

│   │   ├── AllStudents.jsx

│   │   └── DeletedStudents.jsx

│   ├── App.jsx

│   └── main.jsx

├── index.html

├── package.json

└── vite.config.js



How to Run the Project

Prerequisites
Make sure you have these installed:
- Node.js → https://nodejs.org
- MongoDB → https://www.mongodb.com
- Git → https://git-scm.com

Step 1 — Clone the repository
```bash
git clone https://github.com/YourUsername/student-management-system.git
cd student-management-system
```

Step 2 — Setup Backend
```bash
cd backend
npm install
node server.js
```
Backend runs on → http://localhost:8080

Step 3 — Setup Frontend
Open a new terminal:
```bash
cd frontend
npm install
npm run dev
```
Frontend runs on → http://localhost:5173


📸 Screenshots

🏠 Home Page
Add, Update and Delete student records from the home page.

🔍 Show Student
Search students by Roll No, Name or Department.

📋 All Students
View all active students in a sorted list with delete option.

🗑️ Deleted Students
View all soft deleted students with option to restore them.



🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | /save | Save a new student |
| GET | /showall | Get all active students |
| GET | /search/:type/:query | Search student by field |
| POST | /update | Update student details |
| POST | /delete | Soft delete a student |
| GET | /deleted | Get all deleted students |
| POST | /restore | Restore a deleted student |


👩‍💻 Author

**Sabari Sri P**
- 🎓 B.Tech AI and Data Science
- 🏫 Kongu Engineering College
- 📧 sabaripremkumar3@gmail.com



📄 License

This project is open source and available under the MIT License.
