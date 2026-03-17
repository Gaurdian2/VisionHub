# VisionHub

> **From Vision to Market-Ready Products**

VisionHub is a product management platform built for college student teams — helping them organize, collaborate, and ship projects from idea to reality.

---

Pages

| Page | Description |
|------|-------------|
| `index.html` | Landing page — hero section, features overview |
| `about.html` | Our story, mission, and team section |
| `portfolio.html` | Showcase of products and services |
| `services.html` | Services offered by the team |
| `login.html` | User authentication page |

---

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom design system, flexbox layouts
- **Vanilla JavaScript** — no frameworks

---

## Design System

| Token | Value |
|-------|-------|
| Background | Dark navy |
| Accent | Sunrise gradient (yellow → orange) |
| Text | White |
| Card borders | Orange |

---

## Auth System

Login state is managed via `localStorage` using a shared `auth.js` script loaded across all pages.

- After login, the navbar replaces the **"Log in"** link with a **username chip**
- Auth persists across page navigation until the user logs out

### How it works

```js
// auth.js handles login state across pages
// Checks localStorage on page load
// Dynamically updates navbar based on session
```

---

## Project Structure

```
VisionHub/
├── index.html
├── about.html
├── portfolio.html
├── services.html
├── login.html
├── css/
│   └── style.css
├── js/
│   └── auth.js
└── assets/
    └── images/
```

---

## Getting Started

No build tools needed. Just open any `.html` file in a browser or use a local server:

```bash
# Using VS Code Live Server or:
npx serve .
```

---

## Notes

- This is a school team project built solo as part of a Grade 11 Computer Science coursework
- The site is intentionally built without frameworks to demonstrate core web fundamentals

---

*VisionHub — From Vision to Market-Ready Products*
