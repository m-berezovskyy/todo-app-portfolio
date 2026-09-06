# Todo App - Task Management Application

A responsive task management application that helps users organize their daily activities. It supports the complete todo workflow and synchronizes changes with a REST API.

## Live Preview

Experience the application online: [Todo App Demo](https://m-berezovskyy.github.io/todo-app-portfolio/)

## Design Reference

The interface and interaction patterns are based on the [TodoMVC](https://todomvc.com/) application.

## Technologies Used

### Core

- **React 18.3.1** - component-based user interface.
- **TypeScript 5.2.2** - static typing and safer development.
- **SCSS 1.77.8** - modular application styling.

### UI

- **Bulma 1.0.1** - reusable interface styles.
- **Font Awesome 6.5.2** - interface icons.
- **Classnames 2.5.1** - conditional CSS class management.

### Data

- **Fetch API** - communication with the REST API.
- **REST API** - remote todo storage and CRUD operations.

### Development and Deployment

- **Vite 5.3.1** - development server and production build tool.
- **Cypress 13.13.0** - end-to-end testing.
- **ESLint, Stylelint, and Prettier** - code quality and formatting.
- **GitHub Pages** - application hosting and deployment.

## Getting Started

Follow these steps to run the project locally.

1. Clone the repository and enter the project directory:

   ```bash
   git clone https://github.com/m-berezovskyy/todo-app-portfolio.git
   cd todo-app-portfolio
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

## Features

- **Todo management:** Create, edit, complete, and delete tasks.
- **Status filters:** Display all, active, or completed todos.
- **Bulk actions:** Toggle all tasks or remove all completed tasks at once.
- **Active task counter:** See how many todos are still incomplete.
- **API synchronization:** Persist all changes through a REST API.
- **Loading states:** Track pending operations for individual tasks.
- **Error handling:** Display clear notifications when an API request fails.
- **Responsive layout:** Use the application on desktop and mobile screens.
