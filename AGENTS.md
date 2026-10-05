# AGENTS.md

- This is a plain static site with no framework and no build step. `netlify.toml` publishes `public/`.
- `public/index.html` is self-contained. Styles, scripts and base64-embedded images are all inline, which makes the file about 2.5 MB. Edit it in place.
- Product data and the cart logic live in the inline `<script>` at the bottom of the file.
