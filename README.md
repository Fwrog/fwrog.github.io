# Yikai WU Academic Homepage

This repository hosts the source code for Yikai WU's academic homepage. The site is built with Jekyll and adapted from the AcadHomepage template for a compact research profile covering urban informatics, smart transport, remote sensing, computer vision, and AI for science.

Published site target: `https://fwrog.github.io/`

## Main Content

- Profile and contact information: `_config.yml`
- Homepage sections: `_pages/about.md`
- Top navigation: `_data/navigation.yml`
- Local image assets: `images/`
- Small homepage style additions: `assets/css/main.scss`

## Local Preview

Install the Ruby dependencies once:

```powershell
bundle install
```

Build the site:

```powershell
bundle exec jekyll build
```

Serve locally:

```powershell
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

## Deployment

This repository is configured for GitHub Pages deployment through GitHub Actions. For the site to publish at `https://fwrog.github.io/`, the GitHub repository must be named `Fwrog.github.io` and Pages must use GitHub Actions as its publishing source.

## Update Checklist

1. Edit `_pages/about.md` when adding publications, projects, awards, or internships.
2. Edit `_config.yml` when updating email, affiliation, avatar, or profile links.
3. Keep claims conservative: mark manuscripts as "in preparation", "submitted", or "accepted" only when that status is accurate.
4. If Google Scholar citation automation is needed, configure `GOOGLE_SCHOLAR_ID` in GitHub Actions secrets before relying on the existing crawler workflow.

## Credits

This site is adapted from [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io), which builds on Minimal Mistakes and Academic Pages.
