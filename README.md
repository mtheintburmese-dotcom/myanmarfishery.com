# Myanmar Fishery — Static Website

This project is a complete static redesign of the historical Myanmar Fishery and Livestock Online portal. It uses only HTML5, CSS3, vanilla JavaScript, and local image assets. There is no backend, database, framework, package manager, or build step.

## Pages

- `index.html` — homepage and source overview
- `about.html` — preserved introduction, objectives, and source limitations
- `products.html` — fishery categories and historical buying-lead labels
- `services.html` — fair information, exhibitor services, and logistics
- `gallery.html` — local image gallery with filters and accessible lightbox
- `contact.html` — historical contact references and honest static form behavior

## Open locally

Double-click `index.html` or open it from a simple static web server. For example:

```bash
python3 -m http.server 3000
```

Then visit `http://localhost:3000/`.

## Deploy

Upload the complete folder to any static host such as GitHub Pages, Netlify, Cloudflare Pages, or an object-storage website bucket. No install or build command is required. Keep the relative `assets/` paths unchanged.

## Notes

The original domain supplied for extraction was unavailable during research. An indexed mirror preserved the historical pages used for the content report. Historical dates, contact records, fees, and service descriptions are labelled as such and should be verified before use. The contact form validates in the browser but does not send messages without a third-party form service or backend.
