# 📖 Gitslate

**Gitslate** is a minimalist, high-readability publishing template for GitHub. It transforms standard Markdown files into a professional, book-like reading experience without the "noise" of a typical code repository.

---

## 🎯 What is Gitslate?

Unlike traditional documentation themes that focus on code and technical APIs, **Gitslate** is built for the **written word**. It is a digital printing press that uses GitHub's infrastructure to host essays, digital books, research notes, and project manifestos in an environment optimized for human eyes[cite: 1].

### Key Features:
*   **Text-First Typography**: Uses a classic serif font for main content to provide the comfort of a printed book[cite: 1].
*   **Full Automation**: A semi-automated sidebar menu controlled by a single root file (`navigation.yml`)[cite: 2].
*   **Zero-Touch Branding**: Configure project names, author details, and UI labels entirely through `_config.yml`[cite: 1].
*   **Night-Reader Ready**: Includes a built-in Dark Mode toggle with cookie persistence to remember user preferences[cite: 1].
*   **Universal Structure**: Works seamlessly with files in the root folder or nested subdirectories[cite: 1].

---

## 🛠 What to use it for?

Gitslate is versatile and can be used for any project where the text is the main event:

*   **Project Documentation**: Create clean, accessible manuals for non-technical tools or community projects.
*   **Self-Publishing**: Host your own essays, articles, or serialized books with version control.
*   **Knowledge Bases**: Organize personal research, wikis, or study notes into a structured format.
*   **Open Letters & Manifestos**: Share structured ideas in a stable, permanent location.

---

## 🚀 Quick Start

1.  **Clone** this repository or copy the `_layouts/`, `_config.yml`, and `navigation.yml` files to your repo[cite: 1].
2.  **Edit** `_config.yml` to set your project title and author[cite: 1].
3.  **Update** `navigation.yml` to build your sidebar menu[cite: 2].
4.  **Write** your content in Markdown and add the following at the top of your files:
    ```markdown
    ---
    layout: default
    title: Page Name
    ---
    ```
5.  **Enable** GitHub Pages in your repository settings[cite: 1].

---

## ⚖️ License

This project is released under the **Unlicense**, meaning it is free and unencumbered software released into the public domain. You can copy, modify, and publish it however you wish[cite: 2].

---
> "Gitslate: Turning repositories into readers."
