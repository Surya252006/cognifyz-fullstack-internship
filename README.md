# Cognifyz Week 1 - Task 1 & Task 2 (Express + EJS)

## What this project does
- Shows a clean HTML form (Task 1 + Task 2) using **EJS**.
- Adds **client-side validation** (inline JavaScript) to catch common mistakes early.
- Adds **server-side validation** in Express route handler.
- Stores validated submissions temporarily in a **server-side in-memory array**.

## File Structure
```
.
├─ package.json
├─ README.md
├─ src
│  ├─ server.js
│  └─ routes
│     └─ index.js
└─ views
   └─ index.ejs
└─ TODO.md
```

## Run the project
1. Open terminal in this project folder: `d:/full stack project`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start server:
   ```bash
   npm start
   ```
4. Open in browser:
   - http://localhost:3000

## Notes
- The stored submissions reset when the server restarts because they live in memory.

