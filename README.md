# 🎓 Result Management System  
A simple Result Management System built using **HTML, CSS & JavaScript** with **LocalStorage** as the database.  
This project includes an **Admin Panel** and **Student Panel** to manage and view student results.

---

## 🌍 Live Demo  
Click the link below to open the hosted version:  
🔗 **https://anshu991047-debug.github.io/Result-Management-System/**

---

## ✨ Features

### 🔐 Admin Panel
- Login as Admin  
- Add a Student
  - Assign username and password  
  - Enter marks for multiple subjects  
  - Percentage / CGPA auto-calculated  
- Remove a Student  
- Stored data persists using LocalStorage  

### 👨‍🎓 Student Panel
- Login using assigned credentials  
- View detailed marks  
- Auto-calculated Percentage & CGPA  

### 🎨 UI Theme
- Modern **Black & Grey** themed interface  

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (LocalStorage)**

---

## 📂 How to Run Locally
1. Download or clone the project files  
2. Open `index.html` in any browser  
3. Login as Admin  
   - Default Admin Credentials:  
     - **Username:** `admin`  
     - **Password:** `admin123`
4. Add students and assign credentials  
5. Students can then log in to view their results  

---

## 📌 LocalStorage Structure Example
```json
{
  "students": [
    {
      "name": "John Doe",
      "username": "john123",
      "password": "12345",
      "marks": {
        "Math": 95,
        "Science": 90,
        "English": 88
      },
      "percentage": 91,
      "cgpa": 9.1
    }
  ]
}
