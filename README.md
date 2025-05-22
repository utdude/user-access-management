# User Access Management System

A full-stack web application for managing user access to software, with role-based access control (Employee, Manager, Admin).

## Features
- User authentication (register, login, logout)
- Role-based access (Employee, Manager, Admin)
- Software management (add, view, delete)
- Access request workflow (request, approve, reject)
- Admin dashboard for user and software management
- Manager dashboard for request approvals
- Responsive, modern UI

---

## How to Setup and Run

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- PostgreSQL (local or remote)

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

### 2. Backend Setup
```bash
cd user-access-management/backend
cp .env.example .env   # If .env.example exists; otherwise, create a .env file
npm install
```
- **Configure PostgreSQL:**
  - Create a database (e.g., `user_access_management`)
  - Edit your `.env` file with your PostgreSQL user, password, host, and port

**Run the Backend:**
```bash
npm start
```
- The backend will run on [http://localhost:5000](http://localhost:5000)

### 3. Frontend Setup
```bash
cd ../frontend
npm install
```
**Run the Frontend:**
```bash
npm start
```
- The frontend will run on [http://localhost:3000](http://localhost:3000)

### 4. Login
- Use the default admin credentials:
  - **Email:** admin@example.com
  - **Password:** admin123
- Or register a new user.

### 5. Usage
- **Employees:** Request access to software.
- **Managers:** Approve or reject requests.
- **Admins:** Manage users and software.

---

## Tech Stack
- **Frontend:** React, CSS (custom, modern design)
- **Backend:** Node.js, Express
- **Database:** PostgreSQL
- **ORM:** Sequelize

---

## Default Admin Credentials
- **Email:** admin@example.com
- **Password:** admin123

---

## Project Structure
```
user-access-management/
  backend/
    src/
      models/
      routes/
      ...
  frontend/
    src/
      components/
      context/
      ...
```

---

## Customization
- Update styles in `frontend/src/index.css` for branding
- Add new roles or features as needed

---

## License
This project is for educational/demo purposes. You may use and modify it as needed. 
