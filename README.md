# LibrePaw website

One-page marketing site for [LibrePaw](https://github.com/alkor200/LibrePaw), an open source iOS app for pet GPS tracking.

Static HTML/CSS, no build step. Screenshots in `assets/screenshots/` come straight from the app's own simulator, colors in `styles.css` match the app's own palette (`Color+Theme.swift`).

## Before publishing

- Swap the two "Buy me a coffee" links (`href="#"`) in `index.html` for the real Buy Me a Coffee page URL.
- Swap the "Printables" link (`href="#"`, in the Hardware section) for the real Printables listing once the TPU mount STL is uploaded.
- Update the GitHub links if the repository is ever renamed.

## Viewing locally

```sh
python3 -m http.server 8000
open http://localhost:8000
```
