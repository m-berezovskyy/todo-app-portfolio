# Todo App

A task management application built with React and TypeScript. It provides a clean interface for creating, editing, completing, filtering, and deleting todos while keeping data synchronized with an external API.

## Project Description

Todo App is a single-page application designed to make everyday task management simple and convenient. Users can add new tasks, update their titles, mark individual or all tasks as completed, filter the list by status, and remove completed items. All changes are sent to the Mate Academy Students API, while loading states and error notifications provide clear feedback during requests.

## Technical Requirements

To run this project locally, you will need:

- **Node.js 20.x:** The runtime used to build and run the development environment.
- **NPM:** The package manager used to install dependencies and run project scripts.

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/m-berezovskyy/todo-app-portfolio.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-app-portfolio
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

The application will open in your browser automatically. If it does not, use the local URL displayed in the terminal.

## Usage

Enter a task in the input field and press **Enter** to add it. Use the checkbox to change its completion status, or double-click the task title to edit it. The footer controls let you switch between all, active, and completed tasks and clear all completed items at once.

## Features

- Create and save new todos.
- Mark individual todos as active or completed.
- Toggle the status of all todos at once.
- Edit todo titles by double-clicking them.
- Delete individual todos or clear all completed todos.
- Filter todos by **All**, **Active**, or **Completed** status.
- View the number of active tasks remaining.
- See loading indicators and user-friendly error notifications during API requests.
- Use the application comfortably on desktop and mobile screens.

## Live Demo

You can view the deployed application here: [Todo App Demo](https://m-berezovskyy.github.io/todo-app-portfolio/)

## Technologies Used

- **React:** Builds the component-based user interface.
- **TypeScript:** Adds static typing and improves code reliability.
- **Vite:** Provides the development server and production build tooling.
- **SCSS:** Organizes and maintains the application styles.
- **Bulma:** Supplies reusable UI styles and layout utilities.
- **Classnames:** Handles conditional CSS classes.
- **Font Awesome:** Provides interface icons.
- **Fetch API:** Communicates with the external REST API.
- **Cypress:** Supports end-to-end testing.
- **ESLint, Stylelint, and Prettier:** Maintain consistent code quality and formatting.
- **GitHub Pages:** Hosts the deployed application.

## Available Scripts

- `npm start` — start the local development server.
- `npm run build` — create an optimized production build.
- `npm run lint` — format the source files and run JavaScript and style checks.
- `npm run deploy` — build and deploy the application to GitHub Pages.

## Contributing

1. Fork the repository.
2. Clone your fork locally.
3. Create a branch for your feature or fix.
4. Commit and push your changes.
5. Open a pull request with a clear description of the changes.

## License

This project is distributed under the [GNU General Public License v3.0](LICENSE).
