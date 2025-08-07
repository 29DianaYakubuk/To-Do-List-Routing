### To Do List with Routing

A simple yet modular React-based to-do list application that supports task creation, sorting, searching, and navigation across routes.

##  Features

-  Add, delete, and update tasks
-  Real-time search with debounce
- Sorting by creation date
- Task data stored in `db.json` (mock API)
-  Modular component structure
-  React Router for page navigation
-  Clean UI with `CSS Modules`
-  Error boundary with NotFound page

##  Tech Stack

- **React**
- **React Router**
- **CSS Modules**
- **JSON Server** (for mock backend)
- **JavaScript (ES6+)**
- **Debounce utility**

##  Available Scripts

In the project directory, you can run:

```bash
npm install     # Install dependencies
npm start       # Run in development mode
npm run build   # Build the app for production
```

Make sure `json-server` is running if you're using the mock `db.json` as backend:

```bash
npx json-server --watch db.json --port 3001
```

##  Routes

- `/` – Main To Do List page
- `/todo/:id` – Task detail view
- `*` – Not Found page
