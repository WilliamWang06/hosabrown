# Brown HOSA website

Single-page site for Brown HOSA. It is plain HTML, CSS and JavaScript with no build step.

## Files
- `index.html`: the whole site (styles, script and the vector logo are inside it)
- `favicon.svg`: browser tab icon

## Updating content
Edit `index.html` on GitHub (pencil icon) or locally, then commit. The site updates a minute or two after each commit.

- **Calendar dates:** search for `var EV = [` in the script near the bottom (month calendar and "next event" card), and for `id="ev-` in the page body (the date list). Update both.
- **Contacts:** search for `class="person"`.
- **Interest form and Instagram links:** search for `forms.gle` and `instagram.com`.
- **Official-chapter notice:** search for `officially recognized chapter` (appears in the Join section and the footer). Update or remove it once the chapter is official.

## Hosting
GitHub Pages: repository Settings, Pages, deploy from the `main` branch, root folder.

## Sources for dates
Rhode Island and national dates come from hosa.org (State Conferences list and International Leadership Conference page). Check rihosa.weebly.com or the RI State Advisor for changes.
