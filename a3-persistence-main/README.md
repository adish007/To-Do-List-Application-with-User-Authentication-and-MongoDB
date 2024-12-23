# To-Do List Application with User Authentication and Persistent Storage

This is a robust to-do list application designed for managing tasks efficiently. The application features user authentication, account registration, and a responsive, accessible design. It integrates a MongoDB database for persistent data storage, an Express.js backend, and a sleek front-end powered by the Sakura CSS framework.

## Features

### Core Functionality
- **User Authentication and Registration**:
  - Secure user login system leveraging MongoDB for credential storage.
  - Ability to register new user accounts directly from the application.
- **Task Management**:
  - Add, edit, and delete tasks with ease.
  - Tasks are stored persistently, ensuring data is saved across sessions.
- **Dynamic Data Retrieval**:
  - Retrieve a user's personalized task list dynamically upon login.
  - Manage tasks in real time using intuitive forms and responsive elements.

### Accessibility and Design
- **Accessibility Standards**:
  - Implements W3C Accessibility Guidelines:
    - Form labels and alternative text for images.
    - Keyboard accessibility for all interactive elements.
    - Logical document structure with headings and semantic HTML.
- **Responsive Design**:
  - The interface adjusts seamlessly to various screen sizes, offering a consistent experience on desktop and mobile devices.
- **Sleek Aesthetic**:
  - Uses the Sakura CSS framework for a minimalistic, professional look.

## Technologies Used

### Backend
- **Node.js** with **Express.js**: Backend server with endpoints for user authentication, task management, and CRUD operations.
- **MongoDB**:
  - Stores user credentials and task data.
  - Supports dynamic updates to individual task lists.
- **RESTful API**:
  - Routes for managing user accounts and tasks (`/login`, `/register`, `/get-list`, `/submit`, etc.).

### Frontend
- **HTML5** and **JavaScript**:
  - Dynamic task creation and modification via forms and event listeners.
- **CSS**:
  - Sakura CSS framework for responsive and accessible styling.

### Tools and Standards
- **Environment Variables**:
  - Securely manage database credentials using `.env`.
- **Version Control**:
  - Repository managed using Git for collaboration and change tracking.
- **Testing**:
  - Achieved 100% Lighthouse scores in performance, accessibility, and best practices.


Actual Website : https://a3-adish-jain.glitch.me (may not be maintained)

  
