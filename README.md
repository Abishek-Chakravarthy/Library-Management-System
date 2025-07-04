# 📚 Library Management System

This project is a **Library Management System** designed to streamline library operations by providing distinct functionalities for **Librarians** and **Users**. It offers book management, borrowing system, search functionality, and interactive statistics dashboards for both types of users.

---

## 🔗 **Project Presentation**

- [Project Presentation Video](https://drive.google.com/drive/u/0/folders/19hEfE4ooOvsOgmz21zj4Dpnn_OAHQpEx)

---

## 📝 **Project Overview**

The system provides:

- User-friendly registration and login system.
- Role-based access: Regular Users and Librarians.
- Full book and section management for librarians.
- Book borrowing, return, and rating system for users.
- Search functionality based on Title, Author, or Section.
- Statistics dashboards for both users and librarians.

---

## 🎯 **Objectives**

- Provide a platform for users to borrow, return, and rate books.
- Enable librarians to manage sections, books, and user requests.
- Implement a robust search system for efficient book discovery.
- Generate useful statistics to monitor borrowing trends and user activity.
- Ensure data security through authentication and authorization.

---

## 🛠 **Features**

### 👩‍💼 Librarian

- Add, edit, and delete **Sections**.
- Manage **Books** within each section.
- Handle **Borrow Requests**:
  - Accept or reject requests.
  - View detailed user and book information.
  - Revoke accepted requests.
- View **Statistics**:
  - Line graph of total borrowers over time.
  - Book rating distribution.
  - Section-wise book distribution.
  - Top readers list.

### 👨‍💻 User

- Register or log in.
- Browse available books with details like title, author, section, ratings, and readers count.
- Search books by **Title**, **Author**, or **Section**.
- Request to borrow books (max 7 days).
- View current borrowed books.
- Return books with mandatory rating submission.
- View borrowing history and request details.
- Access personalized statistics:
  - Borrowing trends over time.
  - Book rating insights for better decision-making.

---

## 💻 **Technologies Used**

| Technology | Purpose                          |
|------------|-----------------------------------|
| Flask      | Backend web framework            |
| SQLAlchemy | Database ORM                     |
| SQLite     | Lightweight relational database  |
| HTML/CSS   | Frontend structure and styling   |
| JavaScript | Interactivity and search filters |
| Jinja2     | Templating engine for dynamic HTML|

---

## 🗃 **Project Structure (Simplified)**
```
library-management-system/
│
├── app/                  # Flask Application
│   ├── static/           # CSS, JS, images
│   ├── templates/        # HTML templates (Jinja2)
│   ├── models.py         # Database models
│   ├── routes.py         # Application routes
│   └── __init__.py       # App initialization
│
├── database/             # SQLite database file
│
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies
```
## 🚀 **How to Run**

1. Clone the repository:

    ```bash
    git clone <repository-link>
    cd library-management-system
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:

    ```bash
    flask run
    ```

4. Access the app at:

    ```
    http://127.0.0.1:5000
    ```

---

## ✅ **Conclusion**

The Library Management System provides an efficient and interactive platform for managing library resources. By offering role-based functionalities and insightful statistics, it enhances the experience for both users and librarians.

---

## 🙏 **Acknowledgements**

Developed by **Abhishek Chakraborty** as part of the **MAD 1 Project**.
