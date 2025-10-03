# GitHub Pages Deployment with GitHub Actions

This project demonstrates a simple CI/CD workflow using **GitHub Actions** to deploy a static site to **GitHub Pages**.

## How it works
- Whenever a change is pushed to the `main` branch **and it affects `index.html`**, the GitHub Actions workflow (`deploy.yml`) will:
  1. Build the project (in this case just copy the static file).
  2. Deploy it to the `gh-pages` branch.
- GitHub Pages serves content from the `gh-pages` branch.

## Live Website
The site will be available at:  
`https://Ndkkqueenie.github.io/gh-deployment-workflow/`
