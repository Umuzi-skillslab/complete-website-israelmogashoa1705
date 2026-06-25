# Portfolio Website

## Overview

This portfolio website showcases my web development skills and projects. The goal was to transform the incomplete starter code into a fully functional, accessible, and professionally styled multi-page website using only HTML and CSS.

---

## Detailed Issues Log

| #  | Category          | Issue Found                              | Fix Applied                                                      |
| -- | ----------------- | ---------------------------------------- | ---------------------------------------------------------------- |
| 1  | Semantic HTML     | Missing `<header>` element               | Added semantic `<header>` element                                |
| 2  | Semantic HTML     | Missing `<main>` element                 | Added semantic `<main>` element                                  |
| 3  | Semantic HTML     | Missing `<footer>` element               | Added semantic `<footer>` element                                |
| 4  | Semantic HTML     | Overuse of non-semantic `<div>` elements | Replaced with semantic HTML elements where appropriate           |
| 5  | Navigation        | Incomplete navigation menu               | Added all required navigation links                              |
| 6  | Navigation        | Navigation inconsistent across pages     | Standardised navigation on all pages                             |
| 7  | Accessibility     | Images missing alt text                  | Added descriptive alt attributes                                 |
| 8  | Accessibility     | Poor colour contrast                     | Updated colour scheme for readability                            |
| 9  | Accessibility     | Missing form labels                      | Added labels to all form controls                                |
| 10 | Accessibility     | Limited screen reader support            | Improved page structure using semantic HTML                      |
| 11 | Forms             | Contact form incomplete                  | Added all required fields                                        |
| 12 | Forms             | Missing validation attributes            | Added required validation where appropriate                      |
| 13 | Forms             | Limited input types                      | Added multiple input types including email and textarea          |
| 14 | Tables            | About page missing structured data table | Created skills table with headings and rows                      |
| 15 | Tables            | Missing table headers                    | Added `<th>` elements                                            |
| 16 | CSS               | Limited selector usage                   | Added element, class, ID, descendant, and pseudo-class selectors |
| 17 | CSS               | Navigation lacked hover effects          | Added hover styling                                              |
| 18 | CSS               | Table lacked visual styling              | Added borders and alternating row colours                        |
| 19 | CSS               | Form styling inconsistent                | Improved spacing and layout                                      |
| 20 | Responsive Design | Images were not responsive               | Added responsive image sizing rules                              |

---

## Fixes Implemented

* Replaced non-semantic `<div>` elements with semantic HTML5 tags
* Created a consistent navigation menu on all four pages with working links
* Added descriptive alt text for all images and adjusted image sizes for responsiveness
* Built a data table on the About page with headers and rows for skills
* Completed the contact form with 5+ input types, labels, and validation attributes
* Expanded CSS selectors to include element, class, ID, descendant, and pseudo-class selectors
* Styled the navigation with hover effects, styled tables with borders and alternating rows, and improved form styling
* Fixed colour contrast to meet accessibility standards

---

## Final HTML Structure and Semantic Choices

Each page uses the following semantic elements appropriately:

* `<header>` contains the site title and navigation
* `<nav>` holds the navigation menu links
* `<main>` wraps the main content sections of each page
* `<section>` is used to group related content inside the main area
* `<footer>` contains contact information and appears consistently on all pages

Non-semantic `<div>` tags are limited and only used for styling purposes where necessary.

---

## CSS Styling Approach and Selectors Used

* Used a variety of CSS selectors: element (`header`), class (`.profile-img`), ID (`#form`), descendant (`nav ul`), and pseudo-classes (`a:hover`)
* Applied box model properties extensively, including margins, padding, and borders for spacing and layout
* Improved typography and colour scheme for readability and accessibility
* Created responsive image sizes and hover transitions for interactive elements
* Styled navigation with hover colour changes, tables with borders and alternating row colours, and forms with clear visual hierarchy

---

## Accessibility Improvements

* Added descriptive alt text to all images for screen readers
* Ensured colour contrast ratios meet WCAG 2.1 AA standards
* Added labels to all form inputs, improving form accessibility
* Used semantic HTML elements to help screen readers understand page structure
* Improved keyboard navigation by making sure all links and form controls are accessible

---

## Validation Results

### HTML Validation

All HTML files were tested using the W3C Markup Validation Service.

* index.html – Passed validation
* about.html – Passed validation
* projects.html – Passed validation
* contact.html – Passed validation

### CSS Validation

The stylesheet was tested using the W3C CSS Validation Service.

* style.css – Passed validation

---

## Wireframes

Wireframes for all four pages are included in the `/wireframes` folder:

* Home Page Wireframe
* About Page Wireframe
* Projects Page Wireframe
* Contact Page Wireframe

---

## Screenshots

Screenshots are included in the `/screenshots` folder and show:

* Home Page
* About Page
* Projects Page
* Contact Page
* The contact form with improvements
* The styled data table on the About page
* The navigation menu with hover effects

---

## Reflection

This project strengthened my understanding of semantic HTML, accessibility principles, and CSS styling.

One of the most valuable lessons learned was the importance of semantic HTML for improving both accessibility and code organisation. I also gained experience designing forms, improving navigation consistency, and creating more visually appealing layouts using CSS.

The most challenging aspect was ensuring consistency across all pages while maintaining accessibility standards and responsive design principles.

If I were to continue improving this project, I would:

* Add JavaScript functionality for greater interactivity
* Improve responsiveness for a wider range of screen sizes
* Expand the portfolio with additional projects
* Add animations and transitions for enhanced user experience
* Implement a dark mode option

Overall, this project improved my confidence in building accessible, responsive, and professionally structured websites using HTML and CSS.

---

## How to View the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Umuzi-skillslab/complete-website-israelmogashoa1705.git
```

### 2. Navigate to the Project Folder

```bash
cd complete-website-israelmogashoa1705
```

### 3. Open the Project in Visual Studio Code (Optional)

```bash
code .
```

Alternatively, open VS Code manually and select **File > Open Folder**, then choose the project folder.

### 4. Open the Website

Locate the `index.html` file and open it in your preferred web browser.

### 5. Using VS Code Live Server (Recommended)

For a better development experience:

1. Install the Live Server extension in Visual Studio Code.
2. Open the project folder in VS Code.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

The website will automatically open in your browser and refresh whenever changes are saved.

### Project Pages

* `index.html` – Home Page
* `about.html` – About Page
* `projects.html` – Projects Page
* `contact.html` – Contact Page

Use the navigation menu to move between pages.
