# Wipro-Capstone-Project

## 🧑‍💻 Authors

### Ansh Pandey 
### Email: anshpandey8112@gmail.com

# Student Management System (Flask + API)

## 📌 Project Description
This project is a **Student Management System** built using **Flask (Python web framework)** along with a RESTful **API**.  
It allows users to manage student records (add, view, update, delete) through a **web interface** and also provides APIs to perform operations programmatically.

The aim of this project is to demonstrate **full-stack development** using Flask templates for frontend and Flask REST API for backend integration.

### Home Page
<img width="1919" height="966" alt="Image" src="https://github.com/user-attachments/assets/f9f894c8-78e0-4af0-9e5a-c13ff930d96a" />

### Contact Us
<img width="1919" height="984" alt="Image" src="https://github.com/user-attachments/assets/5492e4fd-e6d3-4fe4-a229-e466a182cf39" />

### Student Management Page
<img width="1915" height="972" alt="Image" src="https://github.com/user-attachments/assets/44cff297-96a4-413e-91ca-7cb22901a763" />


---

## ✨ Features
- Add, update, delete, and view student details  
- Search students by name or roll number  
- Simple, responsive web interface (HTML, CSS, Bootstrap)  
- RESTful API endpoints for integration  
- SQLite database for storage  
- Error handling for invalid operations  

---

## 🛠️ Tech Stack
- **Backend:** Python (Flask)  
- **Frontend:** HTML, CSS, Jinja2 templates (Bootstrap)  
- **Database:** SQLite3  
- **API:** Flask-RESTful  

---

## 📂 Project Structure

### 1. Flask (Web Application)

<img width="591" height="662" alt="Image" src="https://github.com/user-attachments/assets/cee56304-d79f-4138-9221-86f5cf1d6c5c" />


### 2. Fast API


<img width="691" height="562" alt="Image" src="https://github.com/user-attachments/assets/3602cfc8-4a12-447f-8e61-f19147c6e1e7" />


---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://gitlab.rpsconsulting.in/w16user39/wipro-capstone-project.git
cd wipro-capstone-project
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Flask App
```bash
python app.py
```

Visit: http://127.0.0.1:5000/

### 5. Run API

```bash
python api.py
```

API available at: http://127.0.0.1:5001/api/students

## 📡 API Endpoints

| Method | Endpoint             | Description            |
| ------ | -------------------- | ---------------------- |
| GET    | `/api/students`      | Get all students       |
| GET    | `/api/students/<id>` | Get student by ID      |
| POST   | `/api/students`      | Add new student        |
| PUT    | `/api/students/<id>` | Update student details |
| DELETE | `/api/students/<id>` | Delete student         |

## 🖥️ Usage

1. Run the Flask web app → manage students through UI.
2. Use the API for external integrations.

### Example with curl:
```bash
curl -X GET http://127.0.0.1:5001/api/students
```
## 🤝 Contributing
- Fork the repo
- Create a feature branch (git checkout -b feature-branch)
- Commit your changes (git commit -m 'Add new feature')
- Push to branch (git push origin feature-branch)
- Open a Merge Request


## Conclusion

Thannks for visiting my webpage 👍😁 








