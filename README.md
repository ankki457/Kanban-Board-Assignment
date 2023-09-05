# Kanban Board
Project Overview: Kanban Board for Task Management

Front-end:

1. Homepage: Displays tasks grouped into three categories: To Do, Doing, and Done.

2. Task Card: Each task is represented as a card with its title and description.

3. Add Task: Provides a form to create a new task by entering a title and description.

4. Edit Task: Allows users to edit an existing task's title and description.

5. Delete Task: Enables users to permanently remove a task.

6. Task Status: Supports drag-and-drop functionality to move tasks between the To Do, Doing, and Done categories.

7. Responsive Design: Ensures the application is user-friendly and visually coherent on mobile devices.

Back-end:

1. API Endpoints: Provides a set of endpoints for performing CRUD (Create, Read, Update, Delete) operations on tasks.

2. Database: Utilizes MongoDB to store task data, with each task containing fields for title, description, and status.

How it Works:

1. Users can visit the homepage and see their tasks categorized into To Do, Doing, and Done columns.

2. To add a new task, they use the "Add Task" form, specifying the title and description. This data is sent to the server via an API request, and the task is stored in the database.

3. Users can edit task details or delete tasks using dedicated interfaces.

4. To change a task's status, they can simply drag and drop it between columns, reflecting the progress of the task.

Technology Stack:

- Front-end: Developed using React for the user interface.
- Back-end: Built with Node.js and Express, serving as the API server.
- Database: MongoDB stores task data.
- The application supports responsive design for mobile devices.
- Drag-and-drop functionality for task management is achieved through libraries like `react-beautiful-dnd`.

Next Steps:

The project can be extended and enhanced by adding features such as user authentication, due dates, labels, and task assignment. Additionally, you can improve error handling, validation, and security in both the front-end and back-end components. This Kanban board can be a valuable tool for individuals or teams to manage tasks effectively and visualize their workflow.

![kanban-1](Kanban-Board-Assignment.png)
