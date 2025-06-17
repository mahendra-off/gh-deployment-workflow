GitHub Pages Deployment Workflow
 This repository demonstrates a GitHub Actions workflow to automatically deploy changes to `index.html` to GitHub Pages.

 ## Project Structure

 - `index.html`: The main HTML file that gets deployed to GitHub Pages.
 - `.github/workflows/deploy.yml`: The GitHub Actions workflow file that handles deployment.
 - `README.md`: This file, explaining the project.

 ## How It Works

 - The GitHub Actions workflow triggers on any push to the `main` branch.
 - It checks if `index.html` has been modified.
 - If changes are detected, it deploys the file to GitHub Pages.
 - The deployed site is accessible at project URL:- https://mahendra-off.github.io/gh-deployment-workflow/.

 ## Prerequisites

 - A GitHub account.
 - Git installed on your local machine.

 ## Setup Instructions

 1. Clone the repository.
 2. Add or update `index.html`.
 3. Commit and push changes to the `main` branch.
 4. Enable GitHub Pages in the repository settings.
 5. View the deployed site at the provided URL.

