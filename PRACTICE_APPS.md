# Full-Stack Practice – 5 Mini Apps

The goal of this practice exercise is to **get comfortable with the process of wiring up a frontend and backend**.
If you can do these 5 apps, you’ll know how to:

* spin up an **Express backend**,
* connect it to a **React frontend**,
* pass data back and forth via **HTTP requests**,
* and keep state consistent across both sides.

This is about the workflow, not about complexity.
No databases, no authentication, no deployment — just the absolute basics.

Each one of these apps should take you less than 30 minutes, after some practice.

---

## App 1 — Hello Counter

1. **Backend (Express)**

   * Keep a single counter in memory.
   * `GET /count` → returns the current number.
   * `POST /count/increment` → increments the number.

2. **Frontend (React)**

   * Display the counter value.
   * Button to “+1” which calls the backend and refreshes the count.

**Goal:** Verify that frontend and backend can talk to each other.

---

## App 2 — Todo List Lite

1. **Backend (Express)**

   * `GET /todos` → returns all todos.
   * `POST /todos` → adds a new todo (just text).
   * `DELETE /todos/:id` → removes a todo.

2. **Frontend (React)**

   * Input box + “Add Todo” button.
   * Display list of todos.
   * Each todo has a “Delete” button.

**Goal:** Practice basic CRUD between React and Express.

---

## App 3 — Joke Fetcher

1. **Backend (Express)**

   * Store an array of jokes.
   * `GET /joke` → returns one random joke.

2. **Frontend (React)**

   * Button “Tell me a joke.”
   * Displays the joke when clicked.

**Goal:** Practice hitting a backend API on demand.

---

## App 4 — Mini Guestbook

1. **Backend (Express)**

   * `POST /messages` → add a new message `{ name, text }`.
   * `GET /messages` → return all messages.

2. **Frontend (React)**

   * Form with name + message.
   * Submit adds message via backend.
   * Show all past messages below.

**Goal:** Practice forms, posting data, and re-rendering from API.

---

## App 5 — Yes/No Poll

1. **Backend (Express)**

   * `POST /vote/:option` → option is “yes” or “no”.
   * `GET /results` → return `{ yes: n, no: m }`.

2. **Frontend (React)**

   * Two buttons: “Yes” and “No.”
   * Show current tally.

**Goal:** Practice updating backend state and showing results.

---

Would you like me to also create a **“Day 1 / Day 2” style progression schedule** for these 5 apps (e.g. App 1 + 2 on Day 1, App 3 on Day 2, etc.) so your students can follow a paced bootcamp structure?
