# Ocean Mallik — Personal Website

This repository holds a small, multi-page personal website for oceanmallik.com built with plain HTML, CSS and vanilla JavaScript. There is no build step or dependencies — deploy the files as static assets.

## Live

- Main site: https://www.oceanmallik.com/
- Blog: https://blog.oceanmallik.com/
- Link hub: https://link.oceanmallik.com/

## Quick preview (local)

Serve the site locally from the project root and open http://localhost:8000:

```bash
python3 -m http.server 8000
# or, if you have Node.js installed:
npx serve -s .  # or `npx http-server`
```

## What you'll find

- Static pages: `index.html`, `pages/about.html`, `pages/activities.html`, `pages/achievements/index.html`, `pages/support/index.html`, `pages/support/payment.html`
- Styling in `style.css` and behavior in `script.js`
- `myWorks.json` contains structured data used by the site
- `CNAME` for the custom domain

## Features

- Responsive layout for desktop and mobile
- Theme switcher (5 themes) persisted in `localStorage`
- Activity cards with status indicators
- Achievements/certificates showcase
- Support/donation flow with an internal payment page

## Project structure

```text
.
├── CNAME
├── index.html
├── myWorks.json
├── README.md
├── script.js
├── style.css
└── pages/
    ├── about.html
    ├── activities.html
    ├── achievements/
    │   └── index.html
    └── support/
        ├── index.html
        └── payment.html
```

## Contributing

This project is simple static content. To contribute:

1. Fork the repo and create a branch for your change.
2. Edit or add files and test locally (see Quick preview).
3. Open a pull request with a short description of your change.

## License

This project is licensed under the MIT License — see `LICENSE`.

---

If you'd like a different style, more detailed install instructions, or want me to add a `LICENSE`, tell me which license to use and I can add it.
