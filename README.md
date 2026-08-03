# ivanwowk.xyz — locked page

Static replica of the Webflow "Locked for now" holding page, so the Webflow
subscription can be paused.

Everything is self-contained: one `index.html` (styles + canvas animation
inline), the two favicons pulled off the Webflow CDN, and a `404.html` that
sends any stray path back to `/` (matching the redirect the Webflow site had).

Only external dependency is Google Fonts (DM Serif Display, Work Sans,
Libre Franklin) — free and independent of Webflow.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000
