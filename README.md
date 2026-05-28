# CoreNuc Poker League Manager Site

This repository contains the static support website for CoreNuc Poker League Manager, a home poker league and Texas Holdem tournament management application from CoreNucApps.

## Site Pages

- `index.html` - Product overview and support contact information.
- `release.html` - Latest app release notes and what changed.
- `technology.html` - Technology stack used to build the CoreNuc Poker League Manager application.
- `screenshots.html` - App screenshots with detailed screen descriptions.
- `helppage.html` - Full user help guide for tournament setup and operation.
- `privacy.html` - Privacy policy for the application and support website.

## Assets

- `corenucapps_logo_small.png` - CoreNucApps logo used in the shared site header.
- `help_app_icon.png` - Help page icon copied from the application assets.
- `screenshots/` - Store-ready application screenshots used by the screenshots page.

## Local Preview

Because this is a static site, you can open `index.html` directly in a browser. For a closer match to GitHub Pages behavior, run a simple local web server from the repository root:

```powershell
python -m http.server 8123 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:8123/
```

## GitHub Pages

When GitHub Pages is enabled for the `main` branch from the repository root, the site is available at:

```text
https://mthomps19692003.github.io/corenuc-home-poker-director-site/
```

## Updating The Site

Keep the shared navigation consistent across all HTML pages when adding a new page. If app screenshots or release notes change, update the matching content on `screenshots.html` and `release.html`.
