# DevOps Demo

This repository is created for demonstrating Jenkins integration with GitHub.

## Objective

The objective of this project is to configure Jenkins with a GitHub repository and automatically retrieve the latest source code for Continuous Integration.

## Project Files

- `README.md` – Contains information about the project.
- `index.html` – Simple HTML webpage.
- `app.py` – Python program used to verify the Jenkins build.

## Jenkins Integration

Jenkins is configured to connect with this GitHub repository using the Git plugin. When the Jenkins job is executed, it checks out the latest source code from the `main` branch and performs the configured build steps.

## Expected Output

The Jenkins console should display a successful Git checkout and build result.

**Build Status:** Successful
