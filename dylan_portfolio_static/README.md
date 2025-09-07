# Static Portfolio for Dylan Galvan

This folder contains a self‑contained, static version of Dylan Galvan’s one‑page portfolio.  Everything is implemented using plain HTML, Tailwind CSS loaded from a CDN and AOS (Animate On Scroll) for simple scroll‑triggered animations.

## Structure

- **index.html** – the single page that renders all content.  It includes the About, Projects, Experience and Contact sections with details drawn from Dylan’s resumes.
- **assets/logos/** – placeholder logos used next to each company name.  Replace any image in this directory with the appropriate company logo (keeping the same file name) to customize the page.
- **assets/resume/** – contains a copy of Dylan’s resume.  The “Download Resume” button at the top of the page links to this file.

## Running

Because this is a static site there’s no build step; simply open `index.html` in a browser.  If you’re hosting it, you can upload all files in this directory to a static hosting provider (e.g. GitHub Pages, Netlify or any web server).  Make sure the directory structure remains intact so that images and the resume load correctly.

## Customization

- **Content:** To update text, dates or bullet points, edit `index.html` directly.  Each project and experience entry is annotated in the source so you can find them easily.
- **Adding Projects/Experiences:** To add more entries, duplicate one of the existing `<div>` blocks in the relevant section and modify its content accordingly.
- **Styling:** Tailwind CSS is included via a CDN link.  If you want to customize colours or other styles without editing the HTML, you can add additional `<style>` rules in the `<head>` of `index.html`.

## Animations

Scroll‑based animations are handled by [AOS](https://michalsnik.github.io/aos/).  You can tune the animation duration or easing in the small script at the bottom of `index.html`.