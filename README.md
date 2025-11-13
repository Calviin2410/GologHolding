# Golog Holding landing page

This repository now contains a lightweight, front-end only version of the Golog Holding landing page so you can preview and edit the design without any Laravel or Tailwind build tooling.

## Step-by-step guide
1. **Clone or download the repo** – `git clone https://github.com/<your-account>/GologHolding.git` or download the ZIP from your hosting provider.
2. **Open the project folder** – all assets live at the root (`index.html`, `styles.css`, `script.js`, plus the `assets/` folder if you add images).
3. **Preview the page** – double-click `index.html` to open it in any modern browser **or** run a static server (`python -m http.server 8000`) and visit `http://localhost:8000`.
4. **Customize the content** – edit the copy, buttons, and sections directly inside `index.html`. Each section has clear comments (`<!-- Hero -->`, `<!-- Solutions -->`, etc.) so you can find what to change quickly.
5. **Adjust the visual theme** – tweak colors, gradients, spacing, and component styles inside `styles.css`. CSS variables at the top (`:root`) control the neon palette, so you can swap the look without touching every selector.
6. **Enhance interactions** – modify `script.js` if you need to add new behaviors (form submission, analytics, etc.). The current script handles smooth scrolling, the contact-form toast, and the dynamic footer year.
7. **Deploy anywhere** – upload the three files (and any images) to Netlify, Vercel, GitHub Pages, shared hosting, or drop them inside an existing Laravel/Blade view or CMS template.

## Tech stack
- **HTML/CSS/JS only** – everything lives in `index.html`, `styles.css`, and `script.js`.
- **Custom neon/glassmorphism aesthetic** – gradients, cards, and responsive grids are defined in `styles.css`.
- **Progressive enhancement** – `script.js` provides smooth scrolling, form reset feedback, and the live copyright year.

Feel free to drop these files into any CMS, Laravel Blade view, or static hosting platform when you are ready to integrate the design elsewhere.
