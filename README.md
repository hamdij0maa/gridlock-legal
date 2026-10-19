# gridlock-legal

Support, privacy policy and legal notice for The Gridlock (English and French), served by GitHub Pages.

Publish (once):
1. Create a public GitHub repository named `gridlock-legal`.
2. Upload everything in this folder to it (including `.nojekyll`).
3. Settings › Pages › Deploy from branch › `main` / root.

The pages then live at:
- https://hamdij0maa.github.io/gridlock-legal/en/support.html (Support URL)
- https://hamdij0maa.github.io/gridlock-legal/en/privacy.html (Privacy Policy URL)
- https://hamdij0maa.github.io/gridlock-legal/en/legal-notice.html (Legal Notice)
- https://hamdij0maa.github.io/gridlock-legal/fr/… (French)

The game's Settings screen links to `https://hamdij0maa.github.io/gridlock-legal/en/privacy.html` and
`https://hamdij0maa.github.io/gridlock-legal/en/support.html`, and to the `fr/` equivalents for French players.
`index.html` sends visitors who open the root URL to their language (English by default); it also accepts
`#support`, `#privacy` and `#legal-notice`.
