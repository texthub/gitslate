---
layout: default
title: Welcome to Gitslate
---

# Gitslate: Narrative Reading for GitHub

**Gitslate** is a minimalist, high-readability template designed to transform standard GitHub Markdown files into a polished, book-like reading experience. By leveraging GitHub’s native Jekyll engine, it bridges the gap between raw documentation and an immersive digital publication.

---

## How It Works

Gitslate operates as a "silent engine" behind your repository. It doesn't interfere with your writing workflow; it simply wraps your content in a professional interface.

### 1. The Content Layer
Your stories, documentation, or notes stay exactly where they are—as standard `.md` files in your main folder or subdirectories. Gitslate uses the **Front Matter** (the block between the `---` lines at the top of this file) to identify which pages should be rendered using the reader template[cite: 1].

### 2. The Configuration Hub
The entire project identity is managed through a single file: `_config.yml`. Here, you can change the project name, the author, and even the text on the UI buttons without ever touching a line of HTML or CSS[cite: 1].

### 3. Automated Navigation
The sidebar menu is controlled by `navigation.yml` located in your root folder. This file allows you to structure your content into sections and links. Whenever you add a new chapter or page, you simply update the YAML list, and the menu updates globally across the entire site[cite: 2].

### 4. Interactive Reading Experience
Gitslate is optimized for long-form reading:
*   **Dual-Font System**: A clean sans-serif for the interface keeps the navigation sharp, while a classic serif font for the main text reduces eye strain during long sessions[cite: 1].
*   **Dark Mode Persistence**: A floating toggle allows you to switch between light and dark modes. Your preference is saved via a cookie, so the site remembers your choice the next time you visit[cite: 1].

---

## Getting Started

To publish your own "Slate," simply ensure your repository has the `_layouts` folder and the `_config.yml` and `navigation.yml` files in place. Once GitHub Pages is enabled in your repository settings, your Markdown files will be live at your custom GitHub URL.

> "Gitslate: Where your code's story finally gets the layout it deserves."

---
