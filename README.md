[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YDjuDFNG)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23194763&assignment_repo_type=AssignmentRepo)
# Portfolio Website Starter Code

This is the starter codebase for your portfolio website project. The code is approximately 70% complete but contains errors, omissions, and areas that need improvement.

## Overview

This portfolio website showcases my web development skills and projects. The goal was to transform the incomplete starter code into a fully functional, accessible, and professionally styled multi-page website using only HTML and CSS.

---

## Issues Found

- Missing semantic HTML5 tags like `<header>`, `<main>`, and `<footer>`
- Navigation menus incomplete and inconsistent across pages
- Images missing descriptive alt text and had sizing issues
- The About page lacked a properly structured data table
- The contact form was incomplete, missing labels and input variety
- CSS had limited selectors, poor styling, and lacked responsive design
- Accessibility issues including colour contrast and missing labels

---

## Fixes Implemented

- Replaced non-semantic `<div>` elements with semantic HTML5 tags
- Created a consistent navigation menu on all four pages with working links
- Added descriptive alt text for all images and adjusted image sizes for responsiveness
- Built a data table on the About page with headers and rows for skills
- Completed the contact form with 5+ input types, labels, and validation attributes
- Expanded CSS selectors to include element, class, ID, descendant, and pseudo-class selectors
- Styled the navigation with hover effects, styled tables with borders and alternating rows, and improved form styling
- Fixed colour contrast to meet accessibility standards

---

## Final HTML Structure and Semantic Choices

Each page uses the following semantic elements appropriately:

- `<header>` contains the site title and navigation
- `<nav>` holds the navigation menu links
- `<main>` wraps the main content sections of each page
- `<section>` is used to group related content inside the main area
- `<footer>` contains contact information and appears consistently on all pages

Non-semantic `<div>` tags are limited and only used for styling purposes where necessary.

---

## CSS Styling Approach and Selectors Used

- Used a variety of CSS selectors: element (`header`), class (`.profile-img`), ID (`#form`), descendant (`nav ul`), and pseudo-classes (`a:hover`)
- Applied box model properties extensively, including margins, paddings, and borders for spacing and layout
- Improved typography and colour scheme for readability and accessibility
- Created responsive image sizes and hover transitions for interactive elements
- Styled navigation with hover colour changes, tables with borders and alternating row colours, and forms with clear visual hierarchy

---

## Accessibility Improvements

- Added descriptive alt text to all images for screen readers
- Ensured colour contrast ratios meet WCAG 2.1 AA standards
- Added labels to all form inputs, improving form accessibility
- Used semantic HTML elements to help screen readers understand page structure
- Improved keyboard navigation by making sure all links and form controls are accessible

## Screenshots

Screenshots are included in the `/screenshots` folder and show:

- All four pages (Home, About, Projects, Contact)
- The contact form with improvements
- The styled data table on the About page
- The navigation menu with hover effects