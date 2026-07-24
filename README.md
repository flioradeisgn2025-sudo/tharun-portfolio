# Tharun Kumar — Portfolio

A single-page portfolio for Tharun Kumar, AI Designer & No-Code Developer.

Interaction-heavy dark theme with a scroll-scrubbed hero, a rolling 3D-style project gallery, filterable work, project detail pages, and a light contact section that wipes in on scroll.

## Tech
- Vanilla HTML / CSS / JavaScript — a single `index.html`, no build step
- [GSAP](https://gsap.com/) + ScrollTrigger for scroll animation
- [Lenis](https://github.com/darkroomengineering/lenis) for smooth scrolling
- [Three.js](https://threejs.org/) for the hero light field
- Google Fonts: Inter Tight + Playfair Display

## Run locally
Projects images load over the network, so just serve the folder:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy
Static site — deploy to GitHub Pages, Vercel, or Netlify as-is.
