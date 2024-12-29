# TaskMate - Professional Task Management Application

Welcome to **TaskMate**, a React-based task management application designed to help you track and manage tasks effectively. This project is developed with a focus on clean design, intuitive user experience, and modular code structure.

## Features

- **Intuitive Task Management**: Add tasks with a title, description, due date, and assign them to the appropriate category (To-Do, In Progress, Completed).
- **Bootstrap Styling**: A sleek and responsive UI built with Bootstrap.
- **Hover Effects**: Interactive hover effects for task cards to improve user experience.
- **Dynamic Task Allocation**: Tasks can be dynamically added to specific categories.
- **Modular Architecture**: Organized project structure for easy scalability and maintenance.

---

## Project Structure

Here is the complete structure of the TaskMate project in IntelliJ:

```
.
├── public
│   ├── index.html        # Main entry point for the app
│   └── manifest.json     # Metadata for progressive web apps
┌── src
    ├── App.js            # Main application file
    ├── App.css           # Global styles
    ├── index.js         # Entry point for React
    ├── components
    │   ├── Navbar
    │   │   ├── Navbar.jsx      # Navbar component
    │   │   └── Navbar.module.css # Navbar-specific styles
    │   ├── TaskBoard
    │   │   ├── TaskBoard.jsx   # TaskBoard for displaying task categories
    │   │   └── TaskBoard.module.css # TaskBoard-specific styles
    │   ├── TaskModal
    │   │   ├── TaskModal.jsx  # Modal for adding tasks
    │   │   └── TaskModal.module.css # TaskModal-specific styles
    │   ├── TaskColumn
    │   │   ├── TaskColumn.jsx # Columns for categories (To-Do, In Progress, Completed)
    │   │   └── TaskColumn.module.css # TaskColumn-specific styles
    └── assets
        ├── images          # Placeholder for all static assets
        └── icons
```

---

## Setup Instructions

To run the project locally, follow these steps:

### Prerequisites

Ensure you have the following installed on your system:
- **Node.js** (v14+)
- **npm** or **yarn**
- **IntelliJ IDEA** (or any preferred IDE for React projects)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/taskmate.git
   cd taskmate
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Install Bootstrap for styling:
   ```bash
   npm install bootstrap
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The app will be live at [http://localhost:3000](http://localhost:3000).

---

## Components Overview

### Navbar
- Contains navigation links: **Home**, **Tasks**, and **Settings**.
- Positioned at the top of the application.

### Task Board
- Displays task categories: **To-Do**, **In Progress**, **Completed**.
- Dynamically updates when tasks are added or removed.

### Task Modal
- Modal for adding new tasks.
- Includes fields for:
  - **Column**: Dropdown to select the category.
  - **Title**: Text input for task title.
  - **Description**: Textarea for task description.
  - **Due Date**: Date picker for deadlines.

### Task Column
- Displays tasks for a specific category.
- Cards are styled with hover effects for interactivity.

---

## Styling

- **Global Styling**: `App.css` contains the base styling for the application.
- **Component-Specific Styling**:
  - Navbar: `Navbar.module.css`
  - Task Board: `TaskBoard.module.css`
  - Task Modal: `TaskModal.module.css`
  - Task Column: `TaskColumn.module.css`

---

## Screenshots

### Application Overview
_Add screenshots here_

### Add Task Modal
_Add screenshots here_

---

## Future Enhancements

1. **Drag and Drop**:
   - Implement drag-and-drop functionality to move tasks between columns.

2. **Search Functionality**:
   - Add a search bar to filter tasks by keywords.

3. **User Authentication**:
   - Integrate login and registration functionality.

4. **Task Priority**:
   - Add priority levels (High, Medium, Low) for tasks.

---

## Contribution Guidelines

We welcome contributions to improve TaskMate! Follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request for review.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any queries or feedback, please reach out at:
- **Email**: your-email@example.com
- **GitHub**: [your-username](https://github.com/your-username)

---

Thank you for using **TaskMate**! We hope it makes your task management easier and more efficient!

