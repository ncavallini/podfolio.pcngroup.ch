# podfolio.pcngroup.ch
Website for the PodFolio App - made by PCN Group

Static site served by GitHub Pages at https://podfolio.pcngroup.ch.

- `en/index.html`: the English page (same layout as the Italian one). Both
  pages have an IT/EN switch in the header.
- `index.html`: the Italian page, including the "Ascolta su PodFolio" link generator
  for podcasters (section "Hai un podcast?")
- `badge.svg`, `badge-en.svg`: the button podcasters embed on their sites
- `privacy-policy.html`: privacy policy
- `screens/`: raw app screenshots
- `img/`: icons, link-preview image and captioned screenshots. The captioned
  ones are generated in the app repo by `tooling/compose_store_screenshots.py`
  (output in `assets/store/listing/landing/`; English in
  `assets/store/listing/en/landing/`, copied to `img/en/`).

Button links (web app, Google Play, App Store) are set in `LINKS` at the
bottom of `index.html`. Leave the App Store link empty to hide its button.
