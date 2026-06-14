# System Design Architecture Handbook

A professional GitBook-style handbook covering distributed systems, databases, scalability, and real-world system designs from first principles.

## Getting Started

### Prerequisites
Make sure you have Python installed, then install the dependencies:
```bash
pip install mkdocs-material
```

### Run Locally
Start the live-reloading development server:
```bash
python -m mkdocs serve
```
Then open your browser and navigate to `http://127.0.0.1:8000/`.

### Build Static Site
To compile the site into static HTML files (output will be in the `/site` directory):
```bash
python -m mkdocs build
```

---

## Deployment
This repository is configured to deploy automatically to GitHub Pages on every push to the `main` branch via GitHub Actions.

The deployment configuration is located in `.github/workflows/ci.yml`.
