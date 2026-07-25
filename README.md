# Portfolio Landing Page — Minimal Editorial

A single-column landing page: warm oat ground, dark cacao ink, caramel for
interaction. Serif (Newsreader) for the voice, sans (Inter) for labels.
No patterns, no animation beyond a 2px hover ease. Pure HTML/CSS — no
JavaScript, no build step.

## Files
- `index.html` — structure and content
- `style.css` — design tokens at the top, everything derives from them

## Structure
Header (name, role) → intro paragraph → Index (list of subpage links with
right-hand annotations) → Elsewhere (social links) → footer (email, colophon).

## Customize
1. Replace "Maya Okafor" throughout `index.html` (and the `<title>`).
2. Rewrite the intro paragraph.
3. Edit the Index rows — each `<li>` links to a subpage; duplicate the
   block to add rows. Create the subpages (`work.html`, etc.) reusing the
   same `<head>` and `style.css`.
4. Update the Elsewhere links and footer email.
5. Retint via the `:root` variables in `style.css` (`--oat`, `--cacao`,
   `--caramel`, `--burgundy`).

## Deploy on GitHub Pages
**Personal site:** create a repo named `<username>.github.io`, push these
files to `main`, and visit `https://<username>.github.io`.

**Project site:** push to any repo → Settings → Pages → Deploy from a
branch → `main` / root. Publishes at `https://<username>.github.io/<repo>/`.

Only external dependency is Google Fonts (linked in `<head>`).
