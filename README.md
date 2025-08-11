# gh-deployment-workflow

A simple GitHub Actions workflow to automatically deploy static websites or project pages to **GitHub Pages**.

## 📌 Overview
This repository demonstrates how to:
- Set up GitHub Pages deployment using **Deploy from a branch** or **GitHub Actions**.
- Automatically publish updates whenever you push changes to the `main` branch.
- Serve static HTML/CSS/JS files directly from GitHub.

## 🛠 How It Works
1. Push your project files (including `index.html`) to the `main` branch.
2. GitHub Pages is configured to build from `main` → `/` (root folder).
3. Site will be live at:
   ```
   https://anweshapanigrahi.github.io/gh-deployment-workflow/
   ```

## 📂 Repository Structure
```
gh-deployment-workflow/
│
├── index.html                  # Main webpage file
├── Workflow directory          #to define the workflow for github actions
└── README.md                   # Project documentation
```

## 🚀 Deployment
1. Go to **Settings → Pages**.
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**.
4. Site will be live now



