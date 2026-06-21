# Personal Portfolio Website

A modern, fully responsive personal portfolio website built with pure **HTML5** and **CSS3** — no JavaScript required.

## Features

- Sticky navigation bar with CSS-only mobile hamburger menu
- Hero section with animated blob and floating profile image
- About section (two-column layout, circular image)
- Skills section with hover-lift cards and progress bars
- Projects section with image overlay and tech tags
- Resume section with download button
- Contact section with info cards and a styled form
- Footer with social icons, quick links, and copyright

## Folder Structure

```
portfolio/
├── index.html       # Main HTML file
├── style.css        # All styles (CSS variables, sections, media queries)
├── resume.pdf       # Your resume (replace with actual PDF)
├── README.md        # This file
└── images/
    ├── profile.jpg  # Your profile photo
    ├── project1.jpg # Personal Portfolio screenshot
    ├── project2.jpg # Calculator App screenshot
    ├── project3.jpg # Weather App screenshot
    └── project4.jpg # Firebase Auth App screenshot
```

## Getting Started

1. Replace all instances of `Your Name` with your real name.
2. Update contact details (email, phone, location).
3. Add your actual profile photo as `images/profile.jpg`.
4. Add project screenshots as `images/project1.jpg` – `project4.jpg`.
5. Replace `resume.pdf` with your actual resume PDF.
6. Update social media links in the footer.
7. Open `index.html` in any browser — no build step needed.

## Customisation

All colours are defined as CSS custom properties at the top of `style.css`:

```css
:root {
  --primary:      #2563eb;   /* change to your preferred accent colour */
  --primary-dark: #1d4ed8;
  --secondary:    #6366f1;
  /* … */
}
```

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). Requires no polyfills.

## License

Free to use for personal and commercial projects.
