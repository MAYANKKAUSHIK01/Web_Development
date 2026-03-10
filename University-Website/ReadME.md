# Eduford University Website

A multi-page static university website built with HTML and CSS.

## Project Structure

```
├── index.html          # Homepage
├── About_us.html       # About Us page
├── Courses.html        # Courses & Facilities page
├── Blog.html           # Blog / Certificate Programs page
├── Contact_us.html     # Contact page with map
├── style.css           # Global stylesheet
└── eduford_img/        # Image assets
    ├── logo.png
    ├── banner.png
    ├── banner2.jpg
    ├── background.jpg
    ├── about.jpg
    ├── certificate.jpg
    ├── library.png
    ├── basketball.png
    ├── cafeteria.png
    ├── london.png
    ├── newyork.png
    ├── washington.png
    ├── user1.jpg
    └── user2.jpg
```

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero banner, courses, campus locations, facilities, testimonials, CTA |
| About | `About_us.html` | University overview and mission |
| Courses | `Courses.html` | Course offerings (Intermediate, Degree, Post Grad) and facilities |
| Blog | `Blog.html` | Certificate & online program article with comment form and categories |
| Contact | `Contact_us.html` | Embedded Google Map, contact details, and contact form |

## Features

- **Responsive design** — mobile-friendly with a hamburger menu (toggles at ≤700px)
- **Sticky navigation** with hover underline animation
- **Hero section** with full-viewport background image and overlay
- **Campus gallery** with red hover overlay effect
- **Testimonials** section with star ratings
- **Call-to-action** section with background image
- **Blog** with sidebar post categories and comment form
- **Contact** with embedded Google Maps iframe and contact info
- **Footer** with social media icons (Font Awesome)

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — flexbox layout, transitions, media queries
- **Google Fonts** — Poppins (300, 400, 600, 800)
- **Google Material Icons** — menu / close icons
- **Font Awesome 6.5.1** — social media and contact icons
- **Vanilla JavaScript** — mobile menu toggle

## Getting Started

1. Clone or download the project.
2. Place all image files inside a folder named `eduford_img/` in the project root.
3. Open `index.html` in any modern browser — no build step required.

```bash
# Quick start with a local server (optional)
npx serve .
# or
python -m http.server 8000
```

## Customisation

- **Colors:** The primary accent color is `#eb1e1b` (red). Update occurrences in `style.css` to retheme the site.
- **Fonts:** Swap the Google Fonts import in `style.css` to change typography.
- **Content:** Replace Lorem Ipsum text in each HTML file with real content.
- **Images:** Replace files in `eduford_img/` with your own — keep the same filenames or update the `src` attributes.
- **Map:** In `Contact_us.html`, replace the Google Maps `iframe` `src` with your own embed URL.

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). IE is not supported.

## Credits

Built by **Mayank**. Images sourced from stock photography.
