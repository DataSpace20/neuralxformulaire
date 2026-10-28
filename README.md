# NEURALX 2.0 | Registration Form

Official registration form for **NEURALX 2.0**, a 3-day data hackathon organized by the **Dataspace** club.

🔗 **Live form:** https://DataSpace20.github.io/neuralx-registration-form/

## Features
- Neon design inspired by the NEURALX visual identity
- Fully responsive (mobile, tablet, desktop)
- Sections: personal info, background, skills, team, motivation, logistics, commitments
- Team fields that appear only when a participant registers as a team
- Built-in spam protection (honeypot field)
- No framework, a single HTML file

## Setup
1. Create a free form at [Formspree](https://formspree.io) and copy its ID.
2. In `index.html`, replace `YOUR_FORM_ID` in the form action:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
3. Replace the placeholder WhatsApp/Discord link in the confirmation message.

## Deploy with GitHub Pages
1. Rename `neuralx-form.html` to `index.html`.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the `/ (root)` folder, then save.
4. Your link will be live in a minute at `https://YOUR-USERNAME.github.io/neuralx-registration-form/`.

## Tech stack
HTML5 · CSS3 · Vanilla JavaScript

## Organized by
**Dataspace**, ENSSEA
