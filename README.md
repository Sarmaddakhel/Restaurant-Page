# Restaurant-Page
# ​​ Restaurant Page

A sleek and responsive JavaScript-powered restaurant website. This project features dynamic navigation and modular design, built using **Webpack**, **ES6 modules**, **HTML**, and **CSS**. It includes a homepage, menu section, about page, and contact information — all rendered dynamically without full page reloads.

---

##  Live Demo

Explore the fully hosted version here:  
https://sarmaddakhel.github.io/Restaurant-Page/

---

##  Key Features

- **Dynamic Single-Page Experience** — Section content (Home / Menu / About / Contact) is dynamically loaded, enabling smooth transitions without reloading the entire page.
- **Modular Architecture** — HTML is generated via JavaScript modules, leveraging Webpack for clean bundling and maintainable structure.
- **Custom Styling** — Clean and responsive design using custom CSS.

---

##  Tech Stack

| Technology     | Purpose                                             |
|----------------|-----------------------------------------------------|
| HTML5          | Base markup for the page                            |
| CSS3           | Custom styling and responsive layout                |
| JavaScript (ES6 Modules) | Dynamic DOM rendering and navigation         |
| Webpack        | Asset bundling and development workflow             |

---

##  Project Structure

```plaintext
restaurant-page/
├── src/
│   ├── index.js        # Entry point for app initialization
│   ├── home.js         # Module for Home section content
│   ├── menu.js         # Module for Menu section content
│   ├── about.js        # Module for About section content
│   ├── contact.js      # Module for Contact section content
│   └── styles.css      # Primary stylesheet
├── dist/               # Bundled assets (ready for GitHub Pages)
├── index.html          # Main HTML template
├── package.json        # Project dependencies and scripts
├── webpack.config.js   # Build configuration
└── README.md
