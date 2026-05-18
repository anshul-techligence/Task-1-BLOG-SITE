# Blog Page – Semantic HTML & CSS Assignment

## Project Overview

This project is a fully semantic, accessible, and responsive blog webpage built using pure HTML5 and CSS3.  
The webpage was created as part of a frontend fundamentals assignment focused on:

- Internet & browser basics
- Semantic HTML
- Forms & validation
- Accessibility
- CSS architecture
- Git & GitHub workflow

The main goal of this project was to create a clean and professional webpage while following modern web development standards and accessibility guidelines.

---

# Assignment Objectives

The assignment required building a blog-style webpage with:

- Proper semantic HTML structure
- Accessible forms and navigation
- Clean CSS architecture
- External stylesheet only
- CSS custom properties (variables)
- Responsive layout
- Hover and focus states
- Proper heading hierarchy
- W3C-valid code
- GitHub version control workflow

---

# Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure and semantic layout |
| CSS3 | Styling and layout |
| Git | Version control |
| GitHub | Code hosting and repository management |

---

# Project Structure

```bash
project-folder/
│
├── index.html
├── style.css
└── README.md
```

---

# HTML Features

## Semantic HTML Elements

The webpage uses multiple semantic HTML5 tags to improve structure, accessibility, and SEO.

### Semantic Elements Used

| Element | Purpose |
|---|---|
| `<header>` | Website header |
| `<nav>` | Navigation links |
| `<main>` | Main content area |
| `<section>` | Logical grouping of content |
| `<article>` | Individual article/project cards |
| `<aside>` | Sidebar content |
| `<footer>` | Footer information |
| `<time>` | Semantic date representation |

Using semantic tags improves:

- Accessibility for screen readers
- SEO ranking
- Code readability
- Browser understanding of content structure

---

# Page Sections

## 1. Header Section

The header contains:

- Main website title
- Navigation menu
- Internal anchor links

### Features

- Semantic `<header>` tag
- Semantic `<nav>` tag
- Accessible navigation using `aria-label`
- Keyboard focus support

---

## 2. Recent Articles Section

The articles section displays blog article cards.

### Each Article Includes

- Title
- Published date using `<time>`
- Short article excerpt
- Read more link

### Semantic Structure

```html
<article>
  <h3>Article Title</h3>
  <time></time>
  <p></p>
</article>
```

---

## 3. Skills Section

Displays technical skills including:

- AI/ML
- Backend Development
- Git

The section uses semantic lists for structured presentation.

---

## 4. Projects Section

The projects section highlights personal projects.

### Included Projects

#### DataPilot.chat
AI-powered data science platform.

#### Portfolio Website
Portfolio website built using HTML, CSS, JavaScript, and Flask.

---

## 5. Newsletter Signup Sidebar

Implemented using the semantic `<aside>` tag.

### Features

- Name input
- Email input
- Submit button
- Proper labels
- Required validation

---

## 6. Contact Form

The contact section contains:

- Name field
- Email field
- Message textarea
- Submit button

### Accessibility Features

- Labels correctly linked using `for` and `id`
- Required validation attributes
- Keyboard-accessible focus states

---

# CSS Features

## External CSS Architecture

All styling is separated into a dedicated external stylesheet:

```html
<link rel="stylesheet" href="style.css">
```

This follows the principle of:

## Separation of Concerns

- HTML → Structure
- CSS → Styling

No inline styles or `<style>` tags were used.

---

# CSS Custom Properties (Variables)

The project uses CSS variables for reusable and maintainable styling.

### Variables Used

```css
:root {

  --primary-color
  --background-color
  --card-color
  --text-color
  --border-color
  --font-family

}
```

### Benefits

- Easier maintenance
- Consistent design
- Reusable values
- Cleaner code structure

---

# Layout System

The page layout uses CSS Grid:

```css
.container {
  display: grid;
  grid-template-columns: 3fr 1fr;
}
```

### Layout Structure

| Area | Purpose |
|---|---|
| Main Content | Articles, skills, projects |
| Sidebar | Newsletter form |

---

# Typography & Spacing

The project uses:

- `rem` units throughout the stylesheet
- Consistent spacing system
- Readable font hierarchy

### Examples

```css
font-size: 1rem;
padding: 1rem;
margin-bottom: 2rem;
```

---

# Interactive UI Features

## Hover States

Hover effects are added to:

- Navigation links
- Article links
- Buttons
- Article cards

Example:

```css
article:hover {
  border-color: var(--primary-color);
}
```

---

# Focus States

Accessible focus states are implemented for:

- Links
- Buttons
- Form inputs
- Textareas

Example:

```css
outline: 0.125rem solid var(--primary-color);
```

This improves keyboard accessibility.

---

# Accessibility Features

The project follows accessibility best practices.

## Accessibility Improvements

### Proper Heading Hierarchy

```text
h1 → h2 → h3
```

### Form Accessibility

- Labels linked correctly
- Inputs use `required`
- Semantic form structure

### Keyboard Accessibility

- Focus outlines implemented
- Navigation accessible via keyboard

### Semantic Structure

Improves screen reader compatibility.

---

# SEO Features

The webpage includes:

```html
<meta name="description">
<title>
```

These improve:

- Search engine understanding
- Browser tab naming
- Metadata quality

---

# Validation & Standards

The project was built to satisfy:

- W3C HTML validation
- Accessibility guidelines
- Semantic HTML standards
- Clean CSS practices

---

# Responsive Design

The layout is designed for desktop screens and adapts well to different viewport sizes using:

- Flexible grid layout
- Relative sizing
- Responsive spacing

---

# Git & GitHub Workflow

The project was version controlled using Git.

## Commands Used

### Initialize Repository

```bash
git init
```

### Add Files

```bash
git add .
```

### Commit Changes

```bash
git commit -m "Initial commit"
```

### Push to GitHub

```bash
git push
```

# Author
## Anshul Dhamankar

