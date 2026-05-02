---
layout: default
title: Setup Guide
---

# Getting Started with Gitslate

This guide explains how to integrate **Gitslate** into your workflow. Whether you are starting a fresh project or adding a reading interface to a repository full of existing text, the process is designed to be straightforward.

---

## 1. The Quickest Way: Cloning the Repository
The simplest way to use Gitslate is to use it as the foundation for a new project.

*   **Clone the Project**: Use your terminal or a Git desktop client to clone the Gitslate repository.
*   **Rename & Clean**: Delete any example Markdown files you do not need.
*   **Push to GitHub**: Upload the folder to a new repository on your GitHub account.
*   **Activate Pages**: In your repository **Settings** > **Pages**, set the source to "Deploy from a branch" and select `main`.

---

## 2. Integration into Existing Repositories
If you already have a repository filled with Markdown files and folders, you can manually "inject" Gitslate to provide a reading interface.

### Files to Transfer
Manually copy these files and folders from Gitslate into the root of your existing repository:

*   **`_layouts/`**: Contains the `default.html` engine that wraps your text[cite: 1].
*   **`_config.yml`**: Your identity hub for project names and UI labels[cite: 1].
*   **`navigation.yml`**: The file where you define your sidebar menu structure.
*   **`LICENSE`**: To ensure your project remains completely free under the Unlicense.

### Adjusting Your Markdown Files
For Gitslate to wrap your existing texts, add this **Front Matter** block to the very top of each `.md` file you want to publish:
```markdown
---
layout: default
title: Name of this Page
---
```

