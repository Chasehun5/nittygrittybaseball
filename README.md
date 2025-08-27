
# Nitty Gritty Baseball — Static Site Starter

A simple, responsive multi-page site for a small baseball team. Built with HTML + Tailwind (CDN) so you can edit text/images and deploy fast.

## Pages
- `/index.html` — Home
- `/schedule.html` — Schedule (Google Calendar embed + table)
- `/roster.html` — Roster cards
- `/gallery.html` — Photo grid
- `/contact.html` — Contact form (Formspree) + mailto

## Quick Start in VS Code
1. Unzip the project.
2. Open the folder in VS Code.
3. Install the **Live Server** extension (by Ritwick Dey).
4. Right-click `index.html` → **Open with Live Server**.

## Customization
- Replace the email in `contact.html` (`mailto:`) with your team's Gmail if different.
- If using Formspree: create a form on formspree.io and replace `YOUR_FORM_ID` in `contact.html`.
- To embed a team Google Calendar: in `schedule.html`, replace the `src` query param with your calendar embed URL.

## Deploy (later)
- Drag-and-drop the folder to Netlify/Vercel OR push to GitHub and connect.
- Add a custom domain when ready.

Enjoy!
