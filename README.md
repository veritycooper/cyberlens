# CyberLens

An interactive cyber security education platform inspired by a digital science museum.

---

## Overview

CyberLens is an interactive cyber security education project designed to help beginners understand core cyber concepts in a more visual, approachable, and engaging way. Inspired by the idea of a digital science museum, the platform focuses on simplifying topics such as encryption, hashing, phishing, passwords, public WiFi, digital footprints, and social engineering through interactive experiences instead of dense technical explanations.

The project was created to make cyber security feel less intimidating and more accessible to everyday users, including people with little or no technical background. Rather than functioning like a traditional course, CyberLens encourages users to explore concepts at their own pace through visuals, simple interactions, and real-world examples.

It is built as a **static website** (HTML, CSS, and JavaScript) and is designed to run on [GitHub Pages](https://pages.github.com/) without a build step or backend.

---

## Features

- **Password Playground** — explore length, patterns, and strength visually
- **Hashing Sandbox** — see how a tiny text change transforms a digital fingerprint
- **Encryption Visualiser** — a gentle lock-and-key style letter-shift demo
- **Phishing Spotter** — tap clues in a suspicious message and compare safer patterns
- **Public WiFi Simulator** — compare open and protected traffic on a café network
- **Digital Footprint Explorer** — layer everyday data signals into a simple profile
- **Social Engineering Scenarios** — practise safer responses to common manipulation tactics
- **Deeper exhibit pages** — optional “go deeper” views with Level Up notes and advanced examples
- Modern, accessible UI with responsive layouts for different screen sizes

---

## Why I Built It

Cyber security can often feel overwhelming, overly technical, or inaccessible to beginners. I wanted to create a project that focused on curiosity, exploration, and explainability rather than complex terminology or traditional course-style learning.

CyberLens combines my interests in cyber security, user experience design, accessibility, and educational technology to create a more engaging way for people to learn about online safety and digital security concepts.

---

## Tech Stack

- HTML
- CSS
- JavaScript

No framework or package manager is required. The site runs directly in the browser.

---

## Installation

Clone the repository and serve the files locally with any simple static file server.

```bash
git clone https://github.com/veritycooper/cyberlens.git
cd cyberlens
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

If you do not use Python, you can use another static server (for example the “Live Server” extension in VS Code) or open `index.html` directly, though a local server is recommended so exhibit links behave consistently.

---

## Deploy on GitHub Pages

1. Push this repository to GitHub on the `main` branch.
2. Go to **Settings → Pages**.
3. Set **Source** to **Deploy from branch**, branch `main`, folder **/ (root)**.
4. After the site builds, it will be available at:

   `https://veritycooper.github.io/cyberlens/`

---

## Project structure

| File | Purpose |
|------|---------|
| `index.html` | Main museum lobby and inline exhibits |
| `exhibit.html?topic=...` | Deeper dives (`passwords`, `hashing`, `encryption`, `phishing`, `wifi`, `footprint`, `scenarios`) |
| `base.css` | Shared layout and typography |
| `cyberlens.css` | CyberLens styling |
| `cyberlens.js` | Main page interactions |
| `cyberlens-exhibit.js` | Dynamic exhibit detail pages |

---

## Future Plans

- Additional interactive cyber security exhibits
- Gamified learning experiences
- Expanded phishing awareness activities
- Mobile optimisation improvements
- Accessibility enhancements
- More beginner-friendly educational modules

---

## Design Philosophy

CyberLens was designed to feel approachable, modern, and curiosity-driven rather than intimidating or overly technical. The project focuses heavily on visual learning, accessibility, and explainable design to help users feel more confident when exploring cyber security topics.

---

## Credits & Inspiration

Inspired by interactive science museums, explainable technology, and the importance of accessible cyber security education.
