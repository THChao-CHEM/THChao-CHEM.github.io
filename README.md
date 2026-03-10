# GitHub Pages Personal Website Starter

A simple dark-mode personal website starter designed for an industry-facing PhD portfolio.

## Best setup for your use case

Create a **user site** repository named:

```text
your-username.github.io
```

That publishes your site at:

```text
https://your-username.github.io
```

A user site is usually better than a project site for job searching because the URL is cleaner and looks more professional.

## Files

- `index.html` - main page
- `styles.css` - dark theme and layout
- `script.js` - small footer year script
- `.nojekyll` - tells GitHub Pages to serve the site directly without Jekyll processing

## How to publish

1. Create a new GitHub repository named `your-username.github.io`.
2. Upload all files from this folder to the root of that repository.
3. In GitHub, open **Settings > Pages**.
4. Set the source to deploy from your default branch if needed.
5. Visit `https://your-username.github.io` after GitHub Pages finishes deploying.

GitHub’s documentation notes that GitHub Pages can publish from repositories and supports custom domains, and that `.nojekyll` bypasses Jekyll processing when you want to deploy static files directly. See the official docs for current details.

## What to customize first

Replace these placeholders in `index.html`:

- `Your Name`
- `your.email@example.com`
- `your-profile`
- `your-username`
- `resume.pdf`

Then rewrite the three case studies so each one answers:

1. What problem were you solving?
2. What computational method did you build or apply?
3. What was the result?
4. Why would an industry team care?

## Recommended website sections

Keep it simple:

- Hero
- About
- Research themes
- Selected projects / case studies
- Publications
- Resume link
- Contact

## Nice next upgrades

- Add a custom domain like `yourname.com`
- Add a headshot
- Add one figure per project
- Add a downloadable resume PDF
- Add Google Analytics or Plausible
- Add a GitHub Actions workflow later if you want a more advanced build pipeline
