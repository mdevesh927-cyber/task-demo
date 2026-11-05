# Task Tracker & GitHub Learning Project

A lightweight, interactive Task Tracker web application designed to help practice basic Git workflows and GitHub Pages deployment.

## Features
- Add, complete, and delete tasks.
- Categorize tasks (Git Step, Personal, Work).
- Task status filtering (All, Active, Completed).
- Dark / Light theme toggle.
- Local storage persistence.

## How to Deploy to GitHub Pages

1. **Unzip the downloaded project folder.**
2. **Open your terminal / Git Bash** in the project directory:
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit of task tracker project"
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/task-tracker.git
   git push -u origin main
   ```
3. **Enable GitHub Pages:**
   - Go to your GitHub repository in your browser.
   - Click on **Settings** > **Pages**.
   - Under **Build and deployment** -> **Branch**, select `main` and click **Save**.
   - Your app will be published online in 1-2 minutes!
