# open-web-playground

[![Build Status](https://img.shields.io/github/actions/workflow/status/Faizan-902/open-web-playground/ci.yml?branch=main)](../../actions)
[![License](https://img.shields.io/github/license/Faizan-902/open-web-playground)](./LICENSE)
[![Hacktoberfest](https://img.shields.io/badge/Hacktoberfest-2025-%23FF8AE2)](https://hacktoberfest.com/)

A beginner-friendly, collaborative playground for practicing and learning HTML, CSS, and JavaScript. Perfect for first-time contributors and small web experiments.

---

## Table of Contents
- About
- Prerequisites
- Installation
- Usage
- Screenshots / Demo
- Running Tests
- Project Structure
- Contributing
- License
- Show Your Support

## 📚 About
open-web-playground provides a simple environment to practice web development skills, contribute to open source, and learn by doing. Whether you're just starting out or looking to sharpen your skills, this playground welcomes all contributors.

### Purpose
- Offer simple, self-contained examples for learning HTML/CSS/JS
- Provide good first issues for open-source newcomers
- Encourage testing habits with a minimal Jest setup

## 🚦 Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js (v14+) for running tests and tooling: https://nodejs.org/
- A text editor (VS Code recommended)

## ⚙️ Installation
1) Clone the repository
```bash
git clone https://github.com/Faizan-902/open-web-playground.git
cd open-web-playground
```
2) (Optional) Install dependencies for tooling/tests
```bash
npm install
```

## 🧑‍💻 Usage
- Open index.html directly in your browser to view the project
- Edit HTML/CSS/JS files and refresh the page to see changes
- Explore the examples/ directory for small focused demos

Common scripts
```bash
# Start a simple local server (if you install one, e.g. serve)
npx serve .
```

## 📸 Screenshots / Demo
- Static preview: open index.html locally
- Example demos are in the examples/ directory

> If you have a hosted demo or screenshots, add them here (e.g., GitHub Pages link).

## 🧪 Running Tests
This project uses Jest for unit testing JavaScript code.

Run all tests
```bash
npm test
```
Watch mode
```bash
npm run test:watch
```
Coverage report
```bash
npm run test:coverage
```
The coverage report is generated in coverage/; open coverage/index.html in your browser for details.

## 📁 Project Structure
```
open-web-playground/
├─ index.html
├─ styles.css
├─ script.js
├─ utils.js
├─ examples/
├─ tests/
├─ package.json
└─ README.md
```

## 🤝 Contributing
We welcome contributions of all sizes. Please read the CONTRIBUTING.md for guidelines, coding standards, and how to get started. Good first issues are labeled accordingly.

### Code Quality
- Keep examples small and focused
- Write/maintain tests where applicable
- Run tests locally before submitting PRs

## 📝 License
This project is licensed under the MIT License. See LICENSE for details.

## 🌟 Show Your Support
- Star this repository if you find it useful
- Share it with friends participating in Hacktoberfest
- Open PRs for documentation, examples, and small fixes
