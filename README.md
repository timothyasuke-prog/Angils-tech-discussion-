# AngilsTech Website Redesign

A complete redesign and rebuild of the AngilsTech website using modern web technologies. The project focuses on improving user experience, responsive design, accessibility, maintainability, and performance while preserving the company's existing content and services.

---

## Project Overview

This project involves rebuilding the AngilsTech website from scratch using:

- HTML5
- CSS3
- JavaScript (Vanilla JS)

The primary goal is to modernize the layout, improve responsiveness across all devices, support dark and light themes, and create a scalable structure that can grow with the company.

---

## Objectives

- Modernize the website design
- Improve navigation and user experience
- Ensure full responsiveness on all screen sizes
- Implement Dark Mode and Light Mode support
- Create reusable styling architecture
- Improve accessibility and readability
- Maintain existing company content while improving presentation
- Build a scalable foundation for future features

---

## Features

### Responsive Design

The website is designed to work seamlessly across:

- Mobile Phones
- Tablets
- Laptops
- Desktop Computers 
- Large Displays

### Theme Support

The website includes:

- Light Mode
- Dark Mode
- Theme persistence using Local Storage

### Modern Navigation

- Responsive Navbar
- Mobile Navigation Menu
- Smooth User Experience
- Future-ready dropdown support

### Homepage Sections

The homepage includes:

- Hero Section
- What We Do
- Training Tracks
- Open Talent
- Call-to-Action Sections
- Footer

### Training Tracks

Dedicated Training Tracks page featuring:

- DevOps & Cloud Computing
- Backend Development
- Frontend Development
- Software Testing & Quality Assurance

Each training track includes:

- Overview
- Technologies
- Detailed Description
- Expandable Read More functionality

### Contact Page

Features include:

- Contact Form
- Social Media Links
- WhatsApp Integration
- Contact Information
- Responsive Layout

---

## Project Structure

```text
angilstech/
│
├── index.html
├── training-tracks.html
├── contact.html
├── about.html
│
├── assets/
│
│   ├── css/
│   │
│   ├── global.css
│   ├── navbar.css
│   ├── footer.css
│   ├── index.css
│   ├── contact.css
│   └── training-tracks.css
│
│   ├── js/
│   │
│   ├── navbar.js
│   ├── footer.js
│   ├── index.js
│   ├── contact.js
│   └── training-tracks.js
│
│   └── images/
│
└── README.md
```

---

## Design Principles

### Mobile First

The website is developed using a mobile-first approach to ensure optimal performance on smaller devices before scaling up to larger screens.

### Consistency

Shared design elements include:

- Typography
- Color Palette
- Buttons
- Cards
- Layout Containers
- Shadows
- Spacing

### Accessibility

The project aims to:

- Improve readability
- Maintain proper color contrast
- Use semantic HTML
- Support keyboard navigation

---

## Styling Architecture

### Global Styles

`global.css`

Contains:

- CSS Variables
- Typography
- Buttons
- Layout Containers
- Utility Classes
- Theme Variables

### Page Specific Styles

Each page maintains its own stylesheet for easier readability, maintenance and scalability.

Example:

```text
index.css
contact.css
training-tracks.css
sch.css
```

---

## Theme System

The website supports Dark Mode and Light Mode using:

- CSS Variables
- JavaScript Theme Toggle
- Local Storage Persistence

Theme preference is saved automatically and restored when users revisit the website.

---

## Training Tracks Workflow

Homepage

```text
Home Page
    ↓
More Training Tracks Button
    ↓
Training Tracks Page
    ↓
Expand Read More
    ↓
View Full Track Details
```

This approach keeps the homepage clean while allowing visitors to explore detailed information when needed.

---

## Future Improvements

Planned enhancements include:

- Open Talent Dedicated Page
- Training Application Portal
- Newsletter Subscription
- Testimonials Section
- Blog/Articles Section
- Learning Resources Portal
- Course Enrollment System
- Admin Dashboard
- Backend Integration
- Email Automation
- Analytics Integration

---

## Deployment

The project can be deployed on:

- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Traditional Web Hosting

---

## Development Workflow

### Clone Repository

```bash
git clone https://github.com/yourusername/angilstech-website.git
```

### Navigate to Project

```bash
cd angilstech-website
```

### Open Project

```bash
code .
```

### Run Locally

Open:

```text
index.html
```

using:

- Live Server Extension
- Browser
- Local Development Environment

---

## Team Collaboration

Recommended Git Workflow:

### Create Feature Branch

```bash
git checkout -b feature/navbar
```

### Commit Changes

```bash
git add .
git commit -m "Add responsive navbar"
```

### Push Branch

```bash
git push origin feature/navbar
```

### Create Pull Request

Review changes before merging into the main branch.

---

## Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript ES6+

### Tools

- Git
- GitHub
- VS Code

### Future Integrations

- EmailJS
- Formspree
- Google Analytics
- Cloud Hosting Services

---

## Contributors

AngilsTech Development Team

Special thanks to everyone contributing to the redesign, development, testing, and continuous improvement of the platform.

---

## License

This project is proprietary and developed for AngilsTech.

© AngilsTech. All Rights Reserved.
