## Summary
Enhances the Password Generator UI with improved typography and layout. Introduces Google Fonts and polished styling for the page, button, and password tiles. No JavaScript logic changes.

## Changes
- Add Google Fonts (Karla) via preconnect and stylesheet links in `index.html`.
- Refine layout and typography in `index.css`:
  - Centered `main` container (max-width 600px, padding).
  - Global font-family set to Karla; improved colors and line-height.
  - Clear visual hierarchy for `h1` and `p`.
  - Styled `.button` for the generate action.
  - Flex-based `.passwords` container with spacing and top border; fixed width 600px.
  - Styled password tiles inside `.passwords` for contrast and alignment.
  - Accent color for `.random-password`.
- Keep existing password generation behavior in `index.js` (two 15‑char passwords on click).

## How to test
```bash
npm install
npm start
```
Then open the app (Vite default preview) and click "Generate passwords". Verify two passwords appear in styled tiles and overall typography/layout reflects the updates.

## Diff summary
2 files changed, 71 insertions, 5 deletions.

## Base / Head
- Base: `origin/main`
- Head: `feat/password-generator-m1-completion`

## Commit(s)
- 122ef1b — Enhance styling and layout for password generator interface; add Google Fonts for improved typography

## Impact & risks
- UI-only changes; minimal risk to functionality. No dependency or logic changes.

## Notes
- Consider a follow-up for responsive behavior (fixed 600px widths) if needed.


