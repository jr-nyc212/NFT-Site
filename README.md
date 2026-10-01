# Insanely Expensive JPEGs – a satirical NFT landing page

A one-page shop front for "FoolsGold.com", selling wildly overpriced NFTs with
a straight face. The starter came from Scrimba's Fullstack Developer Path as
a pile of unstyled `<div>` tags and an empty stylesheet. Every lesson was
published as its own issue, branch and pull request, so the commit history is
a step-by-step log of the page taking shape.

**Live site:** https://foolsgold-nft.netlify.app/

## What was built

- **Semantic structure.** Replaced the starter's `<div>` wrappers with
  `<header>`, `<main>`, `<section>` and `<footer>`, and added the missing
  doctype so the page renders in standards mode.
- **Typography.** Loaded Roboto from Google Fonts with a sans-serif fallback,
  set base sizes and colours in rem, and tuned heading margins and paragraph
  line height for readability.
- **Full-bleed sections with a centred column.** Background colours sit on the
  outer elements while a `.container` class holds the content to a fixed
  width, so colour runs edge to edge and text stays centred.
- **Flexbox image row.** The two feature images sit at opposite ends of their
  wrapper using `display: flex` and `justify-content: space-between`.
- **Button-style links.** Four links styled as buttons with a shared `.btn`
  base class and three variant classes, plus a single hover and active rule
  that overrides the page's link styles through specificity.
- **DRY stylesheet.** Grouped selectors wherever declarations repeated, and
  organised the file into commented sections for global styles, typography,
  links, buttons, layout and images.

## Run it locally

```
npm install
npm run dev
```

Vite serves the page at http://localhost:5173.

## Built with

HTML, CSS and Vite. No frameworks.

## Course

Built while working through Scrimba's
[Fullstack Developer Path](https://scrimba.com/fullstack-path-c0fullstack/~0b9/s0bmh04a80/head).
The starter code is Scrimba's; the markup and styling are mine.
