# Personal Website — Jekyll

Dark-themed personal CV site built with Jekyll. Designed to start as a resume/CV and grow into a full portfolio.

## Quick Start

```bash
# Install dependencies
bundle install

# Serve locally (with live reload)
bundle exec jekyll serve --livereload

# Open in browser
open http://localhost:4000
```

## Customize Your Info

All your personal content lives in **`_config.yml`** — no need to touch HTML or CSS for the basics.

Edit these sections:

- `author:` — name, title, email, GitHub, LinkedIn, location, summary
- `skills:` — add/remove skill categories and items
- `experience:` — your work history
- `education:` — your degrees

## Project Structure

```
├── _config.yml         ← Your content & site config
├── _layouts/
│   └── default.html    ← Base HTML template
├── _includes/
│   ├── nav.html        ← Header/navigation
│   └── footer.html     ← Footer
├── assets/
│   ├── css/main.css    ← All styles
│   └── js/main.js      ← Nav toggle, scroll animations
├── index.html          ← Homepage (About, Experience, Skills, Education)
└── portfolio/
    └── index.html      ← Portfolio stub page (expand later)
```

## Adding Portfolio Projects

When you're ready to add projects, edit `portfolio/index.html` and replace the placeholder with project cards.

You can also create a `_portfolio/` collection in `_config.yml` and loop over project files — ask Claude to help when you're ready!

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to Settings → Pages → Source: `main` branch, `/ (root)`
3. Your site will be live at `https://yourusername.github.io`

For a custom domain, add a `CNAME` file with your domain name.
