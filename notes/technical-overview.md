---
slug: github-european-gas-imports-note-technical-overview
id: github-european-gas-imports-note-technical-overview
title: European Gas Imports
repo: justin-napolitano/european-gas-imports
githubUrl: https://github.com/justin-napolitano/european-gas-imports
generatedAt: '2025-11-24T18:35:46.944Z'
source: github-auto
summary: >-
  This repo manages and analyzes European natural gas import data. It automates
  documentation generation and deployment using Python, shell scripts, and
  Jupyter notebooks.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo manages and analyzes European natural gas import data. It automates documentation generation and deployment using Python, shell scripts, and Jupyter notebooks.

### Key Components:
- **Automation**: Uses a Makefile for building HTML docs.
- **Backup**: Saves generated HTML to Dropbox via Python.
- **Documentation**: Structured with Sphinx and MyST notebooks.

### Tech Stack:
- Python 3.5+
- Bash for scripts
- Sphinx with relevant extensions
- Dropbox API for backups

### Getting Started:
1. Clone the repo:
    ```bash
    git clone https://github.com/justin-napolitano/european-gas-imports.git
    cd european-gas-imports
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set your Dropbox API token in `backup_html.py`.

### Quick Commands:
- Build docs: 
    ```bash
    make html
    ```
- Deploy to GitHub Pages:
    ```bash
    ./deploy.sh
    ```

### Gotchas:
Make sure you have a valid Dropbox API token and that Python dependencies are correctly installed before running scripts.
