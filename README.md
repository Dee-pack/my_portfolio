# Daniel Esosa | Portfolio

Personal portfolio, a smart contract security researcher and full-stack web developer.

[**My Portfolio**](https://danielesosa.com.ng/)

## Built with

Plain HTML, CSS and JavaScript. No framework, no build step, no dependencies.

## Project structure

```
index.html       page content (sections, project cards)
style.css        all styling
script.js        settings, nav, animations, contact form
images/          portrait and project screenshots
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Editing

- **Your details:** the `PROFILE` block at the top of `script.js` (email, GitHub, LinkedIn).
- **Project links:** the `PROJECT_LINKS` block in `script.js`.
- **Text and project cards:** `index.html`.
- **Colours:** the CSS variables at the top of `style.css`.
- **Portrait:** replace `images/portrait.jpg`.

## Contact form

The form opens the visitor's email app with the message addressed to the email set in `script.js`.

## Deployment

Hosted as a static site. Publish the repository root; no build command is needed.
