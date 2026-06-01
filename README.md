# Conniq website

Dit is een statische onepage website voor Conniq.

## Bestanden

- `index.html` - de volledige website
- `style.css` - alle styling
- `script.js` - mobiel menu en kleine animaties
- `assets/logo-placeholder.svg` - tijdelijk logo
- `assets/favicon.svg` - icoon voor browser-tab

## Logo vervangen

Het echte logo is toegevoegd als `assets/logo-conniq.png`.
Als jullie logo bijvoorbeeld `logo.png` heet, zet het in de map `assets` en pas in `index.html` deze regels aan:

```html
<img src="assets/logo.png" alt="Conniq logo" class="brand-logo" />
```

## Contactknop aanpassen

Zoek in `index.html` naar:

```html
<a class="btn btn-primary" href="#" aria-label="Contactlink nog toevoegen">Contactlink toevoegen</a>
```

Vervang `#` door bijvoorbeeld een LinkedIn-link, Calendly-link of formulierlink.
