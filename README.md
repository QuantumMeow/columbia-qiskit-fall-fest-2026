# Qiskit Fall Fest 2026 — Columbia University Website

A clean, modern static website for Qiskit Fall Fest 2026 at Columbia University, built with Jekyll and hosted on GitHub Pages.

## Overview

This website serves as the central information hub for Qiskit Fall Fest 2026 at Columbia University. It features:

- **Home Page:** Hero section with event overview and quick access to key information
- **Events Page:** Detailed list of all Fall Fest events with registration links
- **Register Page:** Simple registration form link
- **Resources Page:** Curated links to Qiskit and quantum computing resources
- **Team Page:** Meet the student organizers
- **Why Qiskit Page:** Learn about Qiskit and why it matters

## Design Philosophy

- **Simple > Impressive** — Clean, minimal design that prioritizes clarity
- **Easy to Update** — Content stored in Markdown for non-developers to edit
- **Mobile-First** — Fully responsive design for all devices
- **Fast & Lightweight** — Static site with no complex dependencies

## Getting Started

### Local Development

1. Install Ruby and Jekyll:
   ```bash
   gem install bundler jekyll
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/QuantumMeow/columbia-qiskit-fall-fest-2026.git
   cd columbia-qiskit-fall-fest-2026
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

5. Open `http://localhost:4000` in your browser

## Updating Content

### Event Information

Edit `events.md` and replace `XXXXX` placeholders with:
- Event dates
- Event times
- Event locations
- Event descriptions
- Registration links

### Team Members

Edit `team.md` to add team members:
- Replace placeholder photos with actual images or emoji
- Add names and roles
- Write short biographies

### Resources

Edit `resources.md` to add or update external links:
- Qiskit tutorials
- IBM Quantum documentation
- Learning materials

### Dates and Details

Replace `XXXXX` placeholders throughout the site with actual event information.

## File Structure

```
.
├── _config.yml              # Jekyll configuration
├── _layouts/
│   └── default.html         # Main layout template
├── _includes/
│   ├── navigation.html      # Top navigation bar
│   └── footer.html          # Footer
├── assets/
│   └── css/
│       └── style.css        # Main stylesheet
├── index.md                 # Home page
├── events.md                # Events page
├── register.md              # Register page
├── resources.md             # Resources page
├── team.md                  # Team page
├── why-qiskit.md            # Why Qiskit page
└── README.md                # This file
```

## Colors & Branding

The site uses a sophisticated palette inspired by Columbia and Qiskit:

- **Dark Navy:** `#1e1b4b` — Primary text and accents
- **Primary Blue:** `#312e81` — Links and secondary elements
- **Accent Pink:** `#ec4899` — Call-to-action buttons and highlights
- **Light Cream:** `#f8f6f0` — Background and card backgrounds
- **Light Gray:** `#9ca3af` — Secondary text

## Customization

### Adding Team Member Photos

Replace the emoji placeholders in `team.md` with actual photos:

1. Add image files to `assets/images/`
2. Update the HTML to reference the image path

### Changing Fonts

The site uses Google Fonts (Inter and Syne). To change fonts, edit `assets/css/style.css` and update the `@import` statement and CSS variables.

### Adding a Columbia Logo

To add the Columbia University logo:

1. Save the logo file to `assets/images/`
2. Update `_includes/navigation.html` to use the logo instead of the SVG icon

## Deployment

This site is automatically deployed to GitHub Pages. Just push changes to the `main` branch and the site will update automatically.

### GitHub Pages Settings

1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose `main` branch and `/ (root)` folder
4. Save

## Questions?

For issues or questions about maintaining this site, contact the Fall Fest organizing team.

---

**Built with Jekyll | Hosted on GitHub Pages | 2026**
