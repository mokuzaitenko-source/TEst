# ACA Learning Platform (Portfolio Project)

This repository contains my applied work from Intro to Deep Learning plus a custom ACA web app that turns core Python topics into an interactive learning experience.

This project is positioned as a portfolio asset for interviews and applications.

## Why this project matters

- Shows end-to-end ownership: backend, frontend, testing, and documentation.
- Demonstrates practical AI-adjacent engineering, not just notebook experiments.
- Provides concrete code to discuss in interviews (architecture, tradeoffs, security, and testing).

## What is included

- `aca/`: Flask app with lesson paths, in-browser code execution, and progress tracking.
- `lab1/`, `lab2/`, `lab3/`: MIT Intro to Deep Learning lab materials and notebooks.
- `xtra_labs/`: additional experiments.
- `ACA_v4.2_CapabilityPolicy.json` and `ACA_v4.2_SchemaRegistry.yaml`: policy and schema artifacts used in ACA work.

## Tech stack

- Backend: Python, Flask, Flask-WTF
- Frontend: HTML, CSS, JavaScript
- Testing: Flask test client (route and feature checks)

## Quick start

```powershell
cd aca
pip install -r requirements.txt
python app.py
```

Open `http://localhost:5000`.

## Validation

```powershell
cd aca
python test_all_features.py
```

## Interview talking points

- Built a modular Flask app that serves structured learning paths and lesson content.
- Implemented safe server-side code execution patterns and error handling for user-submitted code.
- Added progress tracking and route-level feature tests using Flask's test client.
- Refactored UI and templates for a cleaner learning flow and reusable page structure.

## Repo map

- `aca/app.py`: main web app and routes
- `aca/templates/`: page templates
- `aca/static/`: CSS and JavaScript assets
- `aca/progress.py`: progress state logic
- `aca/test_all_features.py`: integration-style smoke tests

## Publish to GitHub

From repo root:

```powershell
git add README.md
git commit -m "docs: position ACA work as portfolio project"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

If `origin` already exists, use:

```powershell
git remote set-url origin <your-repo-url>
git push -u origin main
```
