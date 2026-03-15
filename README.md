# Blogger Theme Development Repository

This repository contains a custom Blogger theme built using Blogger XML templates, CSS, and JavaScript.

The project is designed to be compatible with AI coding agents such as OpenAI Codex to assist with development, refactoring, and feature generation.

---

# Project Goal

Create a modern, responsive, and SEO-friendly Blogger theme while maintaining full compatibility with Blogger template tags.

---

# Important Files

The main files used in this repository:

theme.xml
Main Blogger template containing layout, sections, and widgets.

assets/css/style.css
Main stylesheet for the theme.

assets/js/main.js
JavaScript used for interactive features.

docs/spec.md
Documentation describing theme requirements.

AGENTS.md
Instructions for AI coding agents working in this repository.

---

# Project Structure

theme-blogger/

theme.xml
assets/
css/style.css
js/main.js
docs/
spec.md
AGENTS.md
README.md

---

# Blogger Template Rules

When modifying theme.xml:

DO NOT remove Blogger template tags such as:

<b:section>
<b:widget>
[data:blog.title](data:blog.title)
[data:post.title](data:post.title)
[expr:...](expr:...)

These tags are required for Blogger compatibility.

---

# Development Guidelines

Follow these rules when editing files:

1. Keep Blogger XML structure valid.
2. Avoid removing widget sections.
3. Maintain responsive layout.
4. Separate CSS and JavaScript into the assets folder.
5. Use clean semantic HTML where possible.

---

# Installation

To install the theme:

1. Download theme.xml
2. Go to Blogger Dashboard
3. Open Theme menu
4. Click Backup/Restore
5. Upload theme.xml

---

# Features (Planned)

Responsive layout
Dark mode support
Optimized loading speed
SEO-friendly structure

---

# License

MIT License
