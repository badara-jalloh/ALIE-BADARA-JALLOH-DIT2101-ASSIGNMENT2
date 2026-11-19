# ALIE-BADARA-JALLOH-DIT2101-ASSIGNMENT2
# Blue Tide | Seafood & Coastal Kitchen

A responsive five-page website for a fictional seafood restaurant, built with **HTML and CSS only** (no JavaScript).

**Course:** DCOMP 204 Web Design
**Assignment:** Assignment 2 - HTML, CSS & Responsive Website
**Based on:** the wireframes from Assignment 1

---

## Live Site

> Add your link here after enabling GitHub Pages:
> `https://YOUR-USERNAME.github.io/blue-tide/`

## Pages

| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Hero introduction, key facts, featured dishes, link to sourcing |
| Our Story | `our-story.html` | Restaurant background and the three values that guide the kitchen |
| Menu | `menu.html` | Dishes grouped by category: Signature, Small plates, Sides, Drinks |
| Sustainability | `sustainability.html` | "Our coastal promise": sourcing practices and guest information panel |
| Contact | `contact.html` | Contact form, opening hours and location illustration |

## Project Structure

```
blue-tide/
├── index.html
├── our-story.html
├── menu.html
├── sustainability.html
├── contact.html
├── style.css            # one stylesheet shared by every page
├── hero.svg             # home page illustration
├── story.svg            # Our Story illustration
├── promise.svg          # Sustainability illustration
├── contact.svg          # Contact illustration
├── sea-bass.svg         # menu dish illustrations
├── prawns.svg
├── crab-cakes.svg
├── platter.svg
├── plantain.svg
├── drink.svg
└── README.md
```

## Design

**Colour palette** (white, black and blue only)

| Colour | Hex | Use |
|--------|-----|-----|
| Blue | `#0b4fb3` | Buttons, links, accents |
| Dark blue | `#083a85` | Hover states, gradients |
| Light blue | `#e6effc` | Backgrounds, panels |
| Black | `#111111` | Text, footer, call-to-action bands |
| White | `#ffffff` | Page background, cards |

All colours are defined as CSS variables at the top of `style.css`, so the whole theme can be changed in one place.

**Typography:** Arial / Helvetica, with a clear size scale from headings down to labels.

**Style features:** rounded cards, soft shadows, hover effects, wave dividers, gradient hero and call-to-action sections, and a gentle load animation (all CSS).

## Responsive Design

Built mobile-first with two breakpoints:

| Screen | Width | Layout |
|--------|-------|--------|
| Mobile | under 700px | Single column, collapsible menu |
| Tablet | 700px and up | Two-column card grids, side-by-side menu items |
| Desktop | 1000px and up | Full navigation bar, four-column dish grid, two-column contact and sustainability layouts |

The mobile navigation menu opens and closes with a hidden checkbox and CSS, so no JavaScript is needed.

## Accessibility

- Semantic HTML5 elements: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- "Skip to main content" link for keyboard users
- Descriptive `alt` text on every image
- Form fields have linked `<label>` elements
- Visible focus outlines on links, buttons and inputs
- `aria-current="page"` marks the active navigation link
- Animations are switched off for visitors who prefer reduced motion
- Text and background colours chosen for strong contrast

## Run Locally

No build step or server is needed.

1. Download or clone this repository
2. Open `index.html` in any web browser

```bash
git clone https://github.com/YOUR-USERNAME/blue-tide.git
cd blue-tide
```

## Deploy with GitHub Pages

1. Push the project to a GitHub repository
2. Go to **Settings > Pages**
3. Under **Source**, choose the `main` branch and the `/ (root)` folder
4. Click **Save**. The site will be live in about a minute.

## Known Limitations

- The contact form has no backend, because JavaScript and server code were not used. It shows the layout but does not send messages.
- Images are illustrated SVG placeholders and can be replaced with real photography.
- Restaurant name, menu items, prices, address and opening hours are fictional sample content.

## Browser Support

Tested in current versions of Chromium-based browsers. CSS features used (Grid, Flexbox, custom properties) are supported in all modern browsers.

## Author

**Your Name**
DCOMP 204 Web Design, 2026

## Licence

Student project for coursework purposes.
