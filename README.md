# Mountaineer Area Robotics Team 2614 Wiki 🦾

This repository contains documentation for our FRC team — including robot software, hardware schematics, and developer guides. It is built with **MkDocs** and the **Material for MkDocs** theme.

---

## 📥 Prerequisites

Before you can run the wiki locally, make sure you have:

- **Python 3.9+** installed  
- **Git** installed  
- (Optional) A code editor like **VS Code** for editing markdown files  

---

## 🛠 Installing MkDocs

1. Open a terminal or command prompt.
2. Install MkDocs using pip:

```bash
pip install mkdocs
```

Install the Material theme:
```bash
pip install mkdocs-material
```

Verify installation:
```bash
mkdocs --version
```

You should see something like MkDocs 1.5.2.

## 🚀 Running the Wiki Locally

To preview the wiki on your own machine:

- Navigate to the root of this repository:

```bash
cd path/to/team-wiki
```

- Serve the site locally:

```bash
mkdocs serve
```

- Open a browser and go to:

```
http://127.0.0.1:8000/
```

## 📤 Publishing via GitHub Pages

- Make sure your repository is pushed to GitHub.
- Build and deploy the site:

```bash
mkdocs gh-deploy
```

This will generate the site and push it to the *gh-pages* branch.
GitHub Pages will automatically serve it at:

```
https://<your-github-username>.github.io/<repository-name>/
```

Tip: Update site_url in mkdocs.yml with your GitHub Pages URL so all links work correctly.

## 📝 Editing the Wiki

- All content is in the docs/ folder.
- Navigation is controlled via mkdocs.yml.
- Use Markdown (.md) to add or update pages.
- Images and assets go in docs/assets/.

⚠️ Note: Make sure to commit your changes to the main branch before deploying with mkdocs gh-deploy.