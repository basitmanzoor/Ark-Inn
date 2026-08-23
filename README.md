# Ark Inn — Website

A single-page site for Ark Inn, a boutique hotel in Srinagar, Kashmir.

## Folder structure

```
ark-inn-website/
├── index.html      ← the whole site (HTML, CSS, JS in one file)
└── images/          ← photos used across the site
    ├── logo.jpg
    ├── exterior-1.jpg
    ├── exterior-2.jpg
    ├── room-1.jpg
    ├── room-2.jpg
    ├── room-3.jpg
    └── garden.jpg
```

## Before you publish

Open `index.html` and update these placeholders:

- Phone number — search for `[ Add phone number ]`
- Email address — search for `[ Add email address ]`
- Registration / license number — search for `[ Add Registration / License No. ]`
- Full street address — search for `full address on request`
- Instagram/WhatsApp links in the header and footer (`href="#"`)

The reservation form at the bottom is front-end only — it shows a confirmation message but doesn't send anywhere yet. Wire it up to an email service (e.g. Formspree, EmailJS) or your own backend before going live.

## Hosting on GitHub Pages

1. Create a new GitHub repository (e.g. `ark-inn-website`).
2. Upload this whole folder — keep `index.html` and `images/` at the **root** of the repo (don't nest them in a subfolder), so image paths like `images/logo.jpg` resolve correctly.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Pick the `main` branch and `/ (root)` folder, then **Save**.
6. GitHub will publish the site at `https://<your-username>.github.io/ark-inn-website/` within a minute or two.

If you'd rather use a custom domain (e.g. `arkinn.com`), add it under **Settings → Pages → Custom domain** once the site is live.
