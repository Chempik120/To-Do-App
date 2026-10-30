# To-Do App — Feature-Rich Task Management Application

A powerful, responsive, and intuitive task management application built with **React** and **TypeScript**. It connects to a REST API to store, manage, filter, and track daily tasks seamlessly.

## Live Preview

Check out the live application: [Click here to launch To-Do App](https://Chempik120.github.io/To-Do-App/)

## Technologies Used

### Core Framework & Logic

* **React (v18+)** – Component-based UI library with custom hooks (`useState`, `useEffect`, `useMemo`, `useRef`)

* **TypeScript** – Static typing and interface definitions for strict type safety

* **CSS / SCSS / Bulma** – UI styling, layouts, and interactive notifications

### API & Asynchronous Handling

* **REST API Integration** – Fetching, posting, updating, and deleting tasks asynchronously

* **Promise.allSettled** – Concurrent batch requests for bulk updates and task clearing

### Code Quality & Testing

* **ESLint / Stylelint** – Code quality and style consistency checks

* **Cypress (`data-cy`)** – Built-in data attributes for end-to-end testing support

## Key Features

* **Full CRUD Operations:** Create, read, update, and delete tasks in real time via API requests.

* **Inline Task Editing:** Double-click any task title to modify its contents directly.

* **Task Filtering:** Seamlessly switch between **All**, **Active**, and **Completed** tasks.

* **Batch Actions:**
  * **Toggle All:** Mark all tasks as completed or active with a single click.
  * **Clear Completed:** Remove all finished tasks concurrently.

* **Optimistic UI & Loaders:** Smooth user experience featuring temporary tasks (`tempTodo`), overlay loaders for pending items, and auto-focus fields.

* **Error Handling:** Dynamic notification system with auto-dismissal for network failures or input errors.

## Getting Started

Follow these steps to run the application locally on your computer:

### 1. Clone the repository:

```bash
git clone https://github.com/Chempik120/To-Do-App.git
cd To-Do-App
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Run the development server:

```bash
npm start
```

*The app will automatically open in your browser at `http://localhost:3000`.*

---

*Organize your daily workflow effortlessly!*