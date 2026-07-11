# Weekly Meal Planner v1.0 - web tool 2026

> **Build a seven-day meal schedule in the browser, turn it into a grouped shopping list, and export the whole plan as a PDF with Weekly Meal Planner v1.0.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/chrisio78/weekly-meal-planner-v1?style=flat-square)](https://github.com/chrisio78/weekly-meal-planner-v1)

---

<p align="center">
  <a href="https://chrisio78.github.io/weekly-meal-planner-v1/">
    <img src="https://img.shields.io/badge/Download-Weekly%20Meal%20Planner%20Latest-brightgreen?style=for-the-badge" alt="Download Weekly Meal Planner">
  </a>
</p>

> **[Download Weekly Meal Planner v1.0](https://chrisio78.github.io/weekly-meal-planner-v1/)**

---

[Download Latest Build](https://chrisio78.github.io/weekly-meal-planner-v1/)

---

## Overview

Weekly Meal Planner is a static, browser-first web utility for structuring meals across a full week. Everything is designed to run on the client side, so you can use the core workflow directly in the browser without a backend or a conventional install step.

It is aimed at anyone who wants a straightforward way to organize meals and convert them into a practical shopping list with minimal effort. Weekly planning, grouped ingredient output, and PDF export are combined in a compact interface, which makes it suitable for personal use or as a GitHub Pages project.

---

## What it can do

- Day-by-day weekly meal planning interface
- Automatic shopping list creation from the selected meal plan
- Grouped ingredient output for easier review
- PDF export for saving or printing plans right away
- Client-side workflow with no backend required
- Static app layout that works well on GitHub Pages
- Browser-based operation with no installation needed
- Built-in Stripe Checkout support for compatible payment flows

---

## Getting started

1. Download or clone the repository:
   `git clone https://github.com/chrisio78/weekly-meal-planner-v1.git

2. Open the project folder:
   `cd weekly-meal-planner`

3. Start the app by opening the main HTML file in a browser, or deploy the folder to a static host such as GitHub Pages.

If you prefer to run it locally, a basic static server also does the job:
`python -m http.server`

Then open the local address printed in your terminal.

---

## How to use it

1. Open the application in your browser.
2. Enter meals for each day of the week.
3. Inspect the shopping list that is generated automatically.
4. Export the plan to PDF whenever you need a printable version.
5. If your deployment includes payment-related flows, complete the Stripe Checkout prompt shown by the app.

Common workflow:
- create a weekly menu
- review the ingredient groupings
- export the finished plan
- print or share the PDF as needed

---

## Configuration notes

Because this is a client-side static app, most behavior is handled through the project files and browser-side settings instead of server configuration.

When customizing the project, look for:
- meal data or plan definitions in the HTML/JavaScript files
- checkout settings related to Stripe integration
- assets and export options used by the PDF generator

For hosted setups, configuration usually comes down to the site path or the GitHub Pages publishing configuration.

---

## Requirements

- A modern browser
- JavaScript enabled
- Static hosting support if you plan to publish it online
- Enough local browser storage for saved planning data, if the app uses it
- Optional: a static web server for local testing

---

## FAQ

### Does this require a backend?
No. It is built as a client-side static web app that runs in the browser.

### Can I deploy it on GitHub Pages?
Yes. The repository is meant to work with a GitHub Pages-style deployment.

### How do I update the app?
Replace the files in your deployment with the newest version from the repository, then refresh the browser cache if needed.

### Where are the app settings changed?
Check the repository files, especially the HTML and script files that control planning, export, and checkout behavior.

### What should I do if PDF export fails?
Confirm that JavaScript is enabled and test in a modern browser. If the problem continues, inspect the browser console for errors.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
