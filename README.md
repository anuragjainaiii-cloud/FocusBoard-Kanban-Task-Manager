# FocusBoard — Product Manager Kanban

A responsive, personal Kanban task manager built with React and Vite.

## Features
- To Do, In Progress, Done columns
- Add, edit, delete and move tasks (drag and drop or status dropdown)
- Priority, due date, category, description
- Search, priority filter, overdue indicator, progress metrics
- Persistent browser localStorage; sample tasks on first launch
- Responsive design

## Run locally
```bash
npm install
npm run dev
```

## Publish to GitHub
Create a new empty GitHub repository, then run from this folder:
```bash
git init
git add .
git commit -m "Initial FocusBoard release"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

## Deploy on Vercel
Import the GitHub repository at https://vercel.com/new. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`. Deploy.

## Data and privacy
This is a client-only MVP. Tasks are saved to **localStorage on the current browser/device**, not to GitHub or Vercel. Clearing browser data can erase tasks. There is no login or multi-device sync. Do not store confidential enterprise information in this demo without appropriate security review.
