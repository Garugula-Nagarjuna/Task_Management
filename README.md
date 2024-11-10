Task Management Application
A full-featured task management application with CRUD operations, task categories, and a calendar date picker. Built using React and TypeScript for the frontend, and Node.js with Express for the backend. This app allows users to add, edit, and delete tasks, and organize them by categories.

Table of Contents
Features
Tech Stack
Project Structure
Setup and Installation
Usage
Contributing
Features
Task Management: Add, edit, delete, and organize tasks.
Category Slider: Filter tasks by categories using a horizontal slider.
Calendar Integration: Pick deadlines using a calendar date picker.
Modular UI Components: Clear and organized component structure.
Responsive Design: Works across desktop and mobile screens.
Tech Stack
Frontend: React, TypeScript, CSS Modules
Backend: Node.js, Express, TypeScript
Deployment: Frontend on Vercel 

project-root/
│   ├── src/
│   │   ├── components/        # Reusable UI components
│   │   │   ├── Sidebar.tsx    # Sidebar for task categories and adding tasks
│   │   │   ├── TaskList.tsx   # Component for listing tasks
│   │   │   ├── TaskItem.tsx   # Individual task item component
│   │   │   ├── Calendar.tsx   # Calendar component for selecting dates
│   │   │   └── Modal.tsx      # Modal for adding/editing tasks
│   │   ├── pages/             # Main application pages
│   │   ├── services/          # API integration and fetch calls
│   │   ├── App.tsx            # Main app component
│   │   └── index.tsx          # Entry point
│   ├── public/
│   └── package.json           # Frontend dependencies
Usage
Open the application in a browser.
Navigate the Sidebar for views of expired, active, and completed tasks.
Add a Task: Click the "Add Task" button, input task details, and set a deadline using the date picker.
Category Slider: Use the horizontal slider to filter tasks by categories.
Responsive UI: Check it out on different screen sizes for a fully responsive experience.
UI Components
Sidebar: Contains task status categories (Expired, Active, Completed) and an "Add Task" button that opens a modal for adding tasks.
Modal: A popup form to input new task details, with a date selection option.
Calendar Component: A custom calendar for setting deadlines with integrated React DatePicker.
TaskList: Displays a list of tasks, divided into three categories: To Do, On Progress, and Done.
Task Item: Each task displays title, description, priority, and deadline, with edit and delete options.
Category Slider: Helps users filter tasks by specific categories for better organization.
Contributing
Fork the repository.
Create a new branch: git checkout -b feature/YourFeature.
Commit your changes: git commit -m 'Add a new feature'.
Push to the branch: git push origin feature/YourFeature.
Open a pull request.
License
This project is open source and available under the MIT License.
