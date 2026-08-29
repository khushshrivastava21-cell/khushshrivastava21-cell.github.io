# Khushboo Shrivastava — Static Website

A simple HTML + CSS portfolio website for a WordPress & Shopify developer. No frameworks, no build step — just plain HTML and CSS files you can host anywhere.

## Files

```
static-website/
├── index.html        # Home page
├── services.html     # Services
├── portfolio.html    # Portfolio
├── about.html        # About
├── blog.html         # Blog
├── contact.html      # Contact form
├── audit.html        # Free website audit form
├── css/
│   └── style.css     # All styles (one file)
└── README.md
```

## How to edit

- Open any `.html` file in a text editor and change the text directly.
- Colors and fonts are at the top of `css/style.css` under `:root` — change them there and the whole site updates.
- Replace `you@example.com` in `contact.html` and `audit.html` with your real email. For a proper contact form, use a free service like [Formspree](https://formspree.io) and change the form `action`.

## How to publish on GitHub Pages (free hosting)

1. Create a new repository on GitHub (e.g. `my-website`).
2. Upload all these files (keep the folder structure — `css/style.css` must stay in the `css` folder).
3. In the repo, go to **Settings → Pages**.
4. Under "Source", choose the `main` branch and `/ (root)`, then Save.
5. Your site will be live at `https://your-username.github.io/my-website/` within a minute.
