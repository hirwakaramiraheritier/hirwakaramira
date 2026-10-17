# Hirwa Karamira Heritier — Portfolio Website

A responsive personal portfolio built with HTML, CSS, and vanilla JavaScript. No build step, no backend, no tracking.

## Files
- `index.html` — page structure and content
- `style.css` — design (cream/earth palette, orange accents) and responsive rules
- `script.js` — mobile menu, project filters, reveal animations, footer year
- `images/profile-placeholder.svg` — temporary portrait placeholder

## Preview locally
Extract the folder and open `index.html` in any modern browser.

## Before publishing (checklist)
1. **Photo:** add your portrait to `images/` (e.g. `profile.jpg`) and change the `src` of `#profilePhoto` in `index.html`.
2. **Certificates:** check each name, issuer, and date against the original certificates. The iLead Program entry has no date or issuer yet.
3. **GitHub:** when you have a profile, uncomment the GitHub block in the Contact section of `index.html`.
4. **CV:** "Request my CV" currently opens an email. To offer a download, put `cv.pdf` in the folder and point the button's `href` to it.
5. **Phone number:** it is shown publicly in Contact. Remove that block if you prefer not to share it.
6. **Project visuals:** the card artwork is illustrative. Add real screenshots, repo links, or demos as projects mature.
7. Test every link, and view the site on your phone.

## Free hosting (GitHub Pages)
Create a GitHub repository, upload the contents of this folder (so `index.html` is at the top level), then go to Settings → Pages and publish from the main branch. You'll get a free `username.github.io` address. Netlify Drop and Cloudflare Pages also work by drag-and-drop.

## Notes
- Google Fonts load from the internet; offline, the site falls back to system fonts.
- There is no contact form; the email buttons open the visitor's mail app.
