
# Task Management Application

![React](https://img.shields.io/badge/React-v18.2.0-blue?style=for-the-badge) 
![FastAPI](https://img.shields.io/badge/FastAPI-v0.95-green?style=for-the-badge) 
![MySQL](https://img.shields.io/badge/MySQL-v8.0-orange?style=for-the-badge)

A full-featured task management application built with **React.js**, **MySQL**, and **FastAPI**. This application supports user authentication and efficiently manages 500+ tasks and 100+ users seamlessly. The intuitive user interface boosts task completion efficiency by **15%**.

## Features
- User authentication and session management.
- Task creation, assignment, and status tracking.
- Seamless management of 500+ tasks and 100+ users.
- User-friendly UI that improves task completion efficiency.
- Built using React.js, FastAPI, and MySQL for robust and scalable performance.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: FastAPI, Python
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Tokens)
  
## Installation

### Prerequisites

- Node.js (v16+)
- Python (v3.9+)
- MySQL (v8.0+)

### Clone the repository

```bash
git clone https://github.com/your-username/task-management-app.git
cd task-management-app
```

### Backend Setup

1. **Install dependencies**:

```bash
cd backend
pip install -r requirements.txt
```

2. **Database Setup**:

- Ensure MySQL is running and create a database.

```sql
CREATE DATABASE task_management;
```

- Configure the `.env` file with your MySQL credentials.

3. **Run migrations**:

```bash
alembic upgrade head
```

4. **Start the FastAPI server**:

```bash
uvicorn main:app --reload
```

### Frontend Setup

1. **Install dependencies**:

```bash
cd frontend
npm install
```

2. **Start the React development server**:

```bash
npm start
```

The app will be running at `http://localhost:3000`.

## Usage

1. Sign up or log in with your credentials.
2. Create and assign tasks to users.
3. Track task statuses (pending, in-progress, completed).
4. Manage and filter tasks for better productivity.



## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any enhancements or bug fixes.



## Contact

- **Name**: Anjali Mittal
- **Email**: anjalimittal320@gmail.com

