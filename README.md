# Web Development 1 (Semester 1 - Autumn 2025)

**Computer Science Conversion Course – Web Development 1**

This repository showcases my progression through **Web Development 1** as part of a **SETU's HDip in Computer Science**, moving from foundational HTML/CSS into **component-based static site generation using Eleventy and Nunjucks**.

The work demonstrates an emphasis on **clean structure, refactoring, maintainability, and modern front-end workflows**, with all changes tracked through disciplined Git commits.

---

## Core Technologies

* HTML5 (semantic markup)
* CSS3 (Grid, layout systems)
* Bulma CSS framework
* Eleventy (static site generator)
* Nunjucks templating
* JavaScript (basic interactivity)
* npm / Node.js
* Netlify deployment
* W3C HTML & CSS validation

---

## What This Project Demonstrates

### Progressive Front-End Development

* Built sites from first principles using raw HTML and CSS
* Introduced layout systems (CSS Grid, columns, responsive design)
* Migrated static pages into Eleventy templates
* Refactored markup into reusable layouts, partials, and components

### Component-Driven Architecture

* Reusable **layout**, **header**, **navigation**, **footer**, and **card** components
* Content driven via **front matter**, not duplicated markup
* Clear separation of structure, content, and presentation

### Navigation & UX

* Dynamic navigation generation using **Eleventy Navigation**
* Active state handling via front matter metadata
* Responsive navbar with burger menu and JavaScript toggle

### Styling & Layout

* Consistent UI built with **Bulma**
* Responsive columns, cards, tables, and hero sections
* Vertical centring and layout refinement using utility classes

### Professional Workflow

* Incremental commits with clear intent (`feat`, `refactor`, `fix`, `chore`)
* Continuous refactoring rather than one-off rewrites
* Regular validation using W3C tools
* Deployment to Netlify during development

---

## Notable Technical Highlights

* Refactored a fully static HTML site into a **maintainable Eleventy project**
* Implemented **DRY templating** with Nunjucks includes and layouts
* Converted hard-coded UI sections into **data-driven components**
* Integrated and configured third-party Eleventy plugins
* Cleaned up legacy markup without breaking layout or navigation

---

## Representative Work

* **Eleventy layout & includes system**
  Centralised head, scripts, navigation, and footer into shared templates.

* **Card component system**
  Replaced repeated markup with reusable card templates driven by front matter.

* **Dynamic navigation with active states**
  Pages declare navigation metadata; the nav renders automatically and highlights the active page.

* **Responsive UI with Bulma**
  Cards, tables, hero sections, and navigation adapt cleanly across screen sizes.

---

## Outcome

By the end of this module, the project evolved from simple static pages into a **structured, component-based static site** that reflects:

* Strong fundamentals in front-end development
* Understanding of static site generators
* Attention to maintainability and code quality
* Comfort with modern tooling and workflows

This repository represents **deliberate progression**, not just final output.

---

## Live Deployment

The site was deployed during development using **Netlify** as part of the coursework workflow.

---

## Notes on Workflow

- Starting 23/11/25, PR descriptions for this repository are generated using ChatGPT and a visual Git graph (`git log --all --decorate --oneline --graph`),
with commit subject lines manually entered in capitalized conventional commit format.
- Git versioning is used to maintain a neat record of work. This is **not** required for the course.
- **Important:** No code in this repository has been generated or edited by ChatGPT — only PR documentation is assisted.
