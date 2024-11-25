# User Management Role-Based Access Control (RBAC) System

This project is a comprehensive **User Management System** built with **React.js**. It allows administrators to manage users, roles, and permissions in a structured and user-friendly interface. The system supports features like adding, editing, and deleting users and roles, all while ensuring persistence through **localStorage**.

## Features

### User Management
- **Add Users**: Easily add new users by filling out a form with fields like name, email, and role. Email validation ensures accuracy.
- **Edit Users**: Modify existing user details via a pre-filled form for quick and intuitive updates.
- **Delete Users**: Remove users permanently with a simple button click.
- **Status Toggle**: Mark users as Active or Inactive to control their system access.

### Role Management
- **Create and Edit Roles**: Define roles and update them as needed.
- **Assign Roles**: Dynamically assign roles to users during creation or editing.
- **Permissions Management**: Configure and display permissions for roles to control user access.

### Data Persistence
- **localStorage Utilization**: 
  - Save user and role data locally to ensure persistence across page reloads.
  - Retrieve stored data on subsequent visits to maintain the system state.

### Responsive Design
- Built using **Tailwind CSS**, the application is optimized for all devices, ensuring a seamless user experience on desktops, tablets, and mobile devices.

---

## Technologies Used

- **React.js**: For building a dynamic, component-based UI.
- **Tailwind CSS**: For modern, responsive styling.
- **localStorage**: For client-side data persistence without external dependencies.

---

## How to Use

### Clone the Repository
```bash
git clone https://github.com/nimishsara12/RBAC-Project.git


```
## Start the Application
Launch the development server using the following command:
npm start
The application will be available at http://localhost:3000.

---

## Interacting with the Application
Role Creation:
Navigate to the Role Management section.
Add roles that can be assigned to users.
User Management:
Adding Users:
Click the "Add User" button.
Fill in the details (e.g., name, email, and role) and save.
Editing Users:
Use the "Edit" button to modify user details, including their assigned role.
Deleting Users:
Remove users permanently by clicking the "Delete" button.
Data Persistence:
Changes are saved locally in the browser using localStorage.
Data remains intact across page refreshes, ensuring a seamless user experience.

---

## Why Choose This Project?
### Focus on Security:
Email Validation: Ensures accurate data input for user accounts.
Role-Based Access Control: Limits user permissions based on assigned roles.
### User-Centric Design:
- Clean, intuitive interface for managing users and roles.
- Fully responsive and accessible across multiple devices.
### Extendable Architecture:
- Modular Codebase: Easy to maintain and extend with new features.
- API Ready: The system can be integrated with backend APIs for real-time functionality.


## Future Enhancements
### API Integration:
- Replace localStorage with RESTful API calls for better scalability and real-time updates.
### Advanced Features:
- Add search, filtering, and sorting capabilities for better navigation.
- Include activity logs to track user and role changes.
### Enhanced Security:
- Implement role-based view restrictions to ensure controlled access.
- Add multi-factor authentication (MFA) for secure login.
