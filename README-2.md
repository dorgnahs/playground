# Portfolio Landing Page — Editorial Modern

Structure follows the wireframe: nav (wordmark / links / actions) → hero
(title + subtitle) → 3×2 grid of blocks → footer (mark + email + socials).
Voice follows Monocle: serif masthead type, uppercase letterspaced utility
text, hairline rules dividing every band, one dark footer module. Palette
carries the warm paper / cacao / caramel from the mood boards. No patterns,
no JavaScript, no build step.

## Files
- `index.html` — structure and content
- `style.css` — design tokens at the top; everything derives from them

## Customize
1. Replace "Maya Okafor" and the `M·O` wordmark throughout `index.html`.
2. Point the nav links at your subpages (`work.html`, etc.) and reuse
   this stylesheet on those pages.
3. Rewrite the six grid cards — each is one `<article class="cell">`
   with a tag, title, body and link. The grid collapses 3 → 2 → 1
   columns on smaller screens automatically.
4. Update the footer email + social links.
5. Retint via `:root` in `style.css` (`--paper`, `--ink`, `--caramel`,
   `--dark`).

## Deploy on GitHub Pages
**Personal site:** repo named `<username>.github.io`, push to `main`,
visit `https://<username>.github.io`.

**Project site:** any repo → Settings → Pages → Deploy from a branch →
`main` / root → publishes at `https://<username>.github.io/<repo>/`.

Only external dependency is Google Fonts (linked in `<head>`).
