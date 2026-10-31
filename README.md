# Studyflow

Studyflow is a simple, responsive study planner for keeping track of assignments and study tasks.

## Features

- Add tasks, mark them complete, or remove them.
- Every new task requires a title and a subject or course name.
- Tasks are saved in your browser and remain after a refresh.
- Blank task titles and subject/course names are rejected with a helpful message.
- An empty list shows a friendly prompt to add a task.

## Run the app

Open `index.html` in a web browser. No installation or build step is needed.

## Project files

- `index.html` — application structure
- `styles.css` — responsive layout and visual styles
- `task-fields.css` — task form and subject label styles
- `app.js` — task actions and browser storage
- `FIGMA-DESIGN.md` — UI/UX design handoff

Tasks, including their subject or course name, are stored locally in the browser using `localStorage`. Tasks saved before the subject field was added are labeled “Subject not set.”
