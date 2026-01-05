# Personal Portfolio Website

A responsive portfolio template built with Bootstrap 5 to showcase personal projects, skills, and contact information.

**Built With:** HTML5 • CSS3 • JavaScript • Bootstrap 5.2.3

---

## Overview

This is a multi-page portfolio website that serves as a professional online presence. The site includes sections for displaying work experience, education, projects, and a contact form for potential collaborators or employers to reach out.

---

## Features

| Feature | Description |
|---------|-------------|
| **Homepage** | Hero section with your name and introduction |
| **Resume** | Display education, experience, and skills |
| **Projects** | Gallery to showcase your work |
| **Contact** | Form for visitors to reach you |
| **Responsive** | Works on desktop, tablet, and mobile |
| **Dark Theme** | Modern dark design with teal & purple accents |

---

## Project Structure

```
introduction/               ← Main website folder
├── index.html              ← Homepage
├── resume.html             ← Resume page
├── projects.html           ← Projects gallery
├── contact.html            ← Contact form
├── assets/                 ← Images & media
├── css/
│   └── styles.css          ← All styling
└── js/
    └── scripts.js          ← JavaScript code
```

---

## How It Works

This website follows the standard web development architecture:

- **HTML** provides the structure and content of each page
- **CSS** handles the visual styling and layout
- **JavaScript** adds interactive features and dynamic behavior
- **Bootstrap** provides responsive grid system and pre-built components

The site uses a component-based structure where each page (Home, Resume, Projects, Contact) shares the same navigation and footer, maintaining consistency across the site.

---

## Getting Started

To view the website locally:

1. Navigate to the `introduction/` folder
2. Open `index.html` in your web browser
3. Use the navigation menu to explore different pages

The site can be deployed to any static hosting service (GitHub Pages, Netlify, Vercel).

---

## Customization Guide

The site can be customized by editing the following files:

| Element to Change | File Location | Description |
|-------------------|---------------|-------------|
| Personal information | `index.html` | Update hero section with name and title |
| Work experience | `resume.html` | Modify experience cards with job details |
| Projects showcase | `projects.html` | Add project cards with descriptions and links |
| Color scheme | `css/styles.css` | Adjust CSS custom properties in `:root` |
| Profile photo | `index.html` | Replace image path in hero section |

### Theme Colors

The color palette can be modified by changing CSS variables in `styles.css`:

```css
:root {
    --bs-primary: #14b8a6;    /* Primary accent color */
    --bs-secondary: #8b5cf6;  /* Secondary accent color */
    --bs-body-bg: #0a0a0a;    /* Background color */
}
```

---

## Site Navigation

The website consists of four main pages:

- **Home** - Hero section with introduction and call-to-action buttons
- **Resume** - Education and work experience timeline
- **Projects** - Portfolio showcase with project descriptions and links
- **Contact** - Contact form for inquiries

All pages share a consistent navigation bar and footer for seamless user experience.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Bootstrap 5.2.3 | Responsive grid system and UI components |
| Bootstrap Icons | Icon library for visual elements |
| Google Fonts | Custom typography (Plus Jakarta Sans) |
| JavaScript (ES6) | Interactive features and animations |

---

## Common Issues

| Issue | Solution |
|-------|----------|
| CSS styles not loading | Verify the file path in `<link>` tag points to `css/styles.css` |
| Images not displaying | Ensure relative paths are correct (e.g., `assets/image.jpg`) |
| Changes not visible | Clear browser cache or hard refresh with `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac) |
| JavaScript not working | Check browser console (F12) for errors |

---

## Learning Resources

- [Bootstrap Documentation](https://getbootstrap.com/docs/5.2/) - Official Bootstrap 5 documentation
- [MDN Web Docs](https://developer.mozilla.org/) - Comprehensive web development guides
- [W3Schools](https://www.w3schools.com/) - Tutorials and references for HTML, CSS, and JavaScript

---

## Credits

| Resource | Source | License |
|----------|--------|---------|
| Base Template | [Start Bootstrap - Personal v1.0.1](https://startbootstrap.com/theme/personal) | MIT |
| CSS Framework | [Bootstrap 5.2.3](https://getbootstrap.com/) | MIT |
| Icons | [Bootstrap Icons 1.8.1](https://icons.getbootstrap.com/) | MIT |
| Fonts | [Google Fonts - Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) | Open Font License |

---

## Custom Features

This project is based on the Start Bootstrap "Personal" template. I have added custom JavaScript functionality and styling modifications to enhance the user experience.

### JavaScript Enhancements

The following features were implemented in `introduction/js/scripts.js`:

- **Typing Animation** - Typewriter effect on the homepage hero text
- **Active Navigation** - Highlights the current page in the navigation bar
- **Scroll Animations** - Fade-in effects for cards and sections as user scrolls
- **Back-to-Top Button** - Floating button that appears when scrolling down
- **Theme Toggle** - Dark/light mode switcher with localStorage persistence
- **Form Validation** - Real-time validation for the contact form
- **Smooth Scrolling** - Enhanced scroll behavior for internal anchor links
- **Navbar Effects** - Shadow and blur effects on scroll

These modifications were implemented directly in this repository following standard JavaScript practices. The original template structure and license are maintained.

