# Hugo Mock Landing Page - Auto Deployed

This repository contains a mock landing page built with Hugo and automatically deployed to GitHub Pages using a GitHub Actions workflow.

## Workflow Description

The GitHub Actions workflow in this repository automates the deployment process for the Hugo mock landing page:

1. **Trigger:** The workflow is triggered whenever a push is made to the `main` branch.
2. **Setup:** It sets up the Hugo environment, including dependencies required for building the site.
3. **Build:** The workflow builds the Hugo site and generates the static files.
4. **Deploy:** It deploys the generated static files to the `gh-pages` branch, which serves as the source for the GitHub Pages site.

This automation ensures that any updates made to the `main` branch are quickly reflected on the live GitHub Pages site without manual intervention
