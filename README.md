# Personal Portfolio Website

A multi-page personal portfolio website built with pure HTML. The project focuses on semantic structure, clean markup, accessibility, and search engine optimization without any CSS or JavaScript dependencies.

## Author

**Shivam Kumar**
AI and Full-Stack Developer | Computer Science and Data Science Student
Email: shivamkingkumar5@gmail.com
Location: India

## Project Structure

```
Basic HTML Website/
    index.html        - Homepage (introduction, skills, featured work)
    projects.html     - Project showcase
    articles.html     - Articles and blog posts
    contact.html      - Contact form and information
    README.md         - Project documentation
```

## Pages

### Homepage (index.html)

The landing page introduces the author and provides an overview of skills and featured projects. It contains three main sections: an about me introduction, a categorised skills listing, and a preview of selected work with links to the full projects page.

### Projects (projects.html)

A dedicated page listing portfolio projects. Each project is presented as a standalone article element containing a title, a descriptive summary, and a placeholder link. Current entries include Cloud Service Referee, a full-stack e-commerce platform, a real-time analytics dashboard, and a generative AI chatbot.

### Articles (articles.html)

A collection of written articles and blog posts. Topics covered include an introduction to generative AI, cloud computing fundamentals, a personal full-stack development journey, and a beginner guide to machine learning in Python.

### Contact (contact.html)

Provides a contact form with fields for name, email, and message, along with a direct email link. All form inputs include proper labels and validation attributes for accessibility.

## Technical Details

### Constraints

- No CSS (external, internal, or inline)
- No JavaScript
- No third-party libraries or frameworks
- Pure HTML5 markup only

### Semantic HTML

All pages use semantic HTML5 elements throughout:

- `<header>` for the site banner and title
- `<nav>` for navigation links
- `<main>` for primary page content
- `<section>` for thematic content groupings
- `<article>` for self-contained entries (projects, articles)
- `<footer>` for copyright and contact information
- `<form>`, `<label>`, and `<input>` for accessible form controls

No unnecessary `<div>` or `<span>` elements are used.

### SEO

Every page includes the following meta tags in the document head:

| Tag               | Purpose                                      |
|--------------------|----------------------------------------------|
| `<title>`          | Unique, descriptive page title               |
| `meta description` | Page-specific summary for search engines     |
| `meta keywords`    | Relevant keywords for discoverability        |
| `meta author`      | Author attribution                           |
| `meta viewport`    | Responsive viewport configuration            |

### Accessibility

- All form inputs are associated with `<label>` elements via the `for` attribute
- Required fields are marked with the `required` attribute
- Proper heading hierarchy is maintained (single `<h1>` per page, followed by `<h2>` and `<h3>`)
- Semantic landmark elements enable screen reader navigation

## How to Use

1. Clone or download the repository.
2. Open `index.html` in any web browser.
3. Navigate between pages using the links in the navigation bar.

No build tools, servers, or dependencies are required.

## License

Copyright 2026 Shivam Kumar. All rights reserved.
