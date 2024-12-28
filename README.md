# Task-Management-Web-Application-


This is a simple Task Management Web Application that allows users to manage their tasks efficiently. The application is built using **React** for the frontend and **Django** for the backend. A RESTful API facilitates communication between the two, enabling CRUD operations for tasks.

---

## Features

### Frontend (React)
- **Task Creation**: A form to add a new task with the following fields:
  - Title (required)
  - Description (optional)
  - Due Date (required)
  - Status (choices: "Pending", "In Progress", "Completed")
- **Task Listing**: View all tasks in a table or card layout.
- **Task Editing and Deletion**: Update or remove tasks directly from the UI.
- **Task Filtering**: Filter tasks based on their status.
- **Navigation**: React Router is used to navigate between pages.
- **Responsive Design**: Ensures compatibility across devices.

### Backend (Django)
- **Django REST Framework** (DRF) is used to build a RESTful API.
- **SQLite Database** (or other databases) for data storage.
- **Task Entity**:
  - `id` (auto-generated primary key)
  - `title` (string, max length 100)
  - `description` (text, optional)
  - `due_date` (date)
  - `status` (choices: "Pending", "In Progress", "Completed")
- **API Endpoints**:
  - `POST /tasks/` - Create a new task.
  - `GET /tasks/` - Retrieve a list of all tasks.
  - `GET /tasks/<id>/` - Retrieve details of a specific task.
  - `PUT /tasks/<id>/` - Update a specific task.
  - `DELETE /tasks/<id>/` - Delete a specific task.
- **Validation**: Ensures data integrity (e.g., title cannot be empty, valid due date, etc.).

---

## Getting Started

### Prerequisites
1. **Node.js** (for React frontend)
2. **Python 3.x** and **pip** (for Django backend)

---
**Clone the repository**
   git clone https://github.com/nijiyaks/Task-Management-Web-Application-.git
