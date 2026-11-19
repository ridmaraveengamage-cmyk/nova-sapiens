# Nova Sapiens — Portfolio Website

The portfolio site for **Nova Sapiens**, a Sri Lankan studio for branding & marketing, content development, digital marketing, corporate communication and tech solutions.

**Live site:** https://ridmaraveengamage-cmyk.github.io/nova-sapiens/

## What's inside

A single, self-contained `index.html` (HTML, CSS and JavaScript, no build step) with:

- Floating pill navigation that hides on scroll down and highlights the current section
- Pinned hero with a rotating Nova Star and floating project artwork
- Scroll-scrubbed statement, orbit-style service cards, counters and a moving client strip
- Pinned horizontal case-study reel and a filterable work gallery with phone mock-ups
- Full case-study pages on their own links: `#genova`, `#avishka`, `#awakaasha`
- Testimonials, About, process timeline and a contact form
- Respects `prefers-reduced-motion`

All project artwork is drawn in SVG inside `index.html`, so there are no image files yet.

## Before going live

- [ ] Replace the **sample** results and quotes (marked "Sample" on the page) with real figures and approved client quotes
- [ ] Replace the sample contact details (email, phone) and social links
- [ ] Add real project photos and designs (see below)
- [ ] Confirm each client is happy to be featured publicly

## Adding real images

1. Put images in an `images/` folder, e.g. `images/genova/carousel-01.jpg`.
2. In `index.html`, the `art(id)` helper renders the SVG artwork. Swap a piece for a photo with
   `<div class="art"><img src="images/genova/carousel-01.jpg" alt="..." style="width:100%;height:100%;object-fit:cover"></div>`,
   or ask Claude Code to do it for you.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted with **GitHub Pages** from the `main` branch (root folder). Every push to `main` updates the live site within a minute or two.
