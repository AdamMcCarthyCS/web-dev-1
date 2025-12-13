
# Web Development 1 – Lab Details

This repository contains all work completed for the **Web Development 1** module as part of a **SETU's HDip in Computer Science**.
The work spans **Lab 1 to Lab 9**, demonstrating a progression from basic HTML/CSS through to **Eleventy, Nunjucks templating, component reuse, and navigation plugins**.

Each lab builds incrementally on previous concepts, with commits documenting experimentation, refactoring, validation, and final walkthrough completion.

---

## Technologies Used

* HTML5 (semantic markup)
* CSS3 (grid, layout, responsive styling)
* Bulma CSS framework
* Eleventy (static site generator)
* Nunjucks templating
* JavaScript (basic interactivity)
* npm / Node.js
* Netlify (deployment)
* W3C HTML & CSS validation

---

## Lab Breakdown

---

## Lab 1 – HTML Fundamentals

**Status:** Completed
**Key focus:** Basic HTML structure, linking pages, images, and validation.

**Highlights**

* Created initial site structure and pages (`index`, `apps`, `directions`)
* Added navigation links between pages
* Included images with `alt` attributes
* Linked external stylesheet and meta tags
* Validated HTML using W3C validator

**Representative commits**

* Initial folder structure and pages (bc3c9a0, 7dff813, 35a43fc)
* Stylesheet creation and linking (e0094be, 5622a0a)
* Exercises completed and documented (7b76cf7, 5e09ac3)

---

## Lab 2 – CSS Styling & Layout Basics

**Status:** Completed
**Key focus:** CSS styling, classes, backgrounds, fonts, and relative paths.

**Highlights**

* Applied background colours, fonts, borders, and text styling
* Introduced CSS classes and reusable styles
* Implemented relative paths for images and links
* Improved readability and visual hierarchy
* Reorganised project structure

**Representative commits**

* Styling exercises (f2c0f82, d3c650c, 47e03d6)
* Relative paths and linking fixes (94eb540, 3bf9c57)
* Validation and refactor (61047b2)

---

## Lab 3 – CSS Grid & Page Layout

**Status:** Completed (Lab 3a & 3b)
**Key focus:** CSS Grid, multi-column layouts, structural refactors.

**Highlights**

* Built multi-column grid layouts (2-column → 4-column)
* Nested grids for main and secondary content
* Positioned header, nav, main, sidebar, and footer using grid
* Wrapped content in semantic containers to support layout changes
* Revalidated HTML/CSS after structural changes

**Representative commits**

* Grid experimentation and refinement (5331933 → f971bc0)
* Semantic refactors and layout cleanup (cce2f45, e3ad485)
* Lab completion and validation (bc85d3b, 04c61a6)

---

## Lab 4 – Advanced CSS, Floats & Validation

**Status:** Completed (Lab 4a & 4b)
**Key focus:** Floats, layout restructuring, validation discipline.

**Highlights**

* Experimented with floats and image wrapping
* Built multi-page layouts with consistent styling
* Split CSS into focused stylesheets
* Highlighted active navigation states
* Validated all HTML and CSS using W3C tools

**Representative commits**

* Float experiments and layout changes (fb48aee → 9346c0b)
* Navigation styling and layout shifts (26fff2a, 6763286)
* Validation and lab completion (e340681, cbee543)

---

## Lab 5 – Eleventy Introduction & Deployment

**Status:** Completed (Lab 5a & 5b)
**Key focus:** Static site generation, templating, deployment.

**Highlights**

* Introduced Eleventy and npm
* Converted static HTML into Eleventy templates
* Added layouts, partials, and shared includes
* Fixed absolute/relative path issues across builds
* Deployed site to Netlify

**Representative commits**

* Eleventy setup and templates (9edc094, 36d2b5a)
* Netlify deployment (962dfe6)
* Layout and partial refactors (e0464ff, b176bdf)
* Sidebar and master layout integration (6ef648b, 416a1e2)

---

## Lab 6 – Semantic HTML & Navigation with Eleventy

**Status:** Completed (Lab 6a & 6b)
**Key focus:** Semantic markup, navigation automation, fonts.

**Highlights**

* Refactored HTML to use semantic tags (`header`, `nav`, `main`, `aside`, `footer`)
* Introduced Eleventy Navigation plugin
* Generated navigation dynamically using front matter
* Added Google Fonts
* Used Nunjucks partials for shared content

**Representative commits**

* Semantic refactors (0ab97f5, ad9eded)
* Eleventy Navigation integration (27825b2, 699e953)
* Partial-based page construction (e789bc4)
* Font integration (2230db6)

---

## Lab 7 – Bulma & Responsive Layouts

**Status:** Completed (Lab 7a & 7b)
**Key focus:** CSS frameworks, responsive design, layout refinement.

**Highlights**

* Introduced Bulma CSS framework
* Built responsive column layouts
* Implemented hero sections, cards, sidebars, and footers
* Used Bulma utilities for spacing, alignment, and typography
* Refactored layout files to remove unnecessary classes

**Representative commits**

* Bulma layout structure (ba3d363 → ff63030)
* Hero, footer, and sidebar components (e99f92c, 413b46e)
* Image ratios and responsive grids (ec5ee65, f891c8c)

---

## Lab 8 – Components, Cards & Navigation UI

**Status:** Completed
**Key focus:** UI components, cards, navbar interactivity.

**Highlights**

* Built reusable card UI using Bulma
* Added images, headers, footers, and buttons to cards
* Implemented responsive navbar with burger menu and JavaScript toggle
* Styled page backgrounds and sections consistently
* Improved visual hierarchy and spacing

**Representative commits**

* Navbar and burger menu (059f6de, 5a813d3)
* Card creation and styling (bfa3e1d → f01cd84)
* Layout polish and fixes (042f58c, 78b7ea0)

---

## Lab 9 – Nunjucks Refactor & Eleventy Navigation

**Status:** Completed
**Key focus:** Maintainability, DRY principles, component-driven templates.

**Highlights**

* Refactored all pages to remove duplicated HTML
* Introduced reusable Nunjucks templates for:

  * Layout
  * Header
  * Navigation
  * Footer
  * Card components
* Converted card content to be driven by front matter
* Integrated Eleventy Navigation plugin with active state handling
* Improved table layout and vertical centring using Bulma utilities

**Representative commits**

* Template creation (213320f, 93f714c, e977889, b8f56fa)
* Card component refactor (0355bbf, 794de14, f291fa3)
* Navigation plugin integration and fixes (2ea56bd, f798419, 0f00b24, 370e4dc)
* Final lab completion (2a9d72f)

---

## Overall Learning Outcomes

Across the module, this repository demonstrates:

* Progressive mastery of HTML, CSS, and layout techniques
* Confident use of CSS Grid, Bulma, and responsive design
* Practical use of Eleventy and Nunjucks for static site generation
* Component-based thinking and DRY principles
* Navigation automation using Eleventy plugins
* Consistent validation, refactoring, and version control discipline

---

## Status

* All labs completed
* All walkthroughs and exercises implemented
* Project builds successfully with Eleventy
* Codebase reflects incremental learning and refactoring
