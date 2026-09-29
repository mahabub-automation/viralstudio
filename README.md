# Mind Spark BD — policy pages

Static host for the **Privacy Policy** and **Terms of Service** of Mind Spark BD, a short-form content channel publishing finance, health and productivity videos.

Platform API reviews (YouTube Data API, Meta Graph API for Facebook and Instagram) require a publicly reachable privacy policy URL before an app is approved. This repository exists to serve that URL over GitHub Pages.

**Live page:** https://mahabub-automation.github.io/viralstudio/

## Contents

| File | Purpose |
|---|---|
| `index.html` | Single self-contained page — about, privacy policy, terms of service, contact |

No build step and no dependencies: one HTML file with inline CSS, served directly by GitHub Pages.

## Why the repository name does not match

The repository was created as `viralstudio` and the URL is already registered with the platform apps that depend on it. Renaming the repository would change the Pages URL and break those app configurations, so the name stays as-is.

## Editing

Edit `index.html` and push to `main` — GitHub Pages redeploys automatically. Update the *Last updated* dates in both the privacy policy and terms sections whenever the text changes.

## Related

Channels covered by these policies: [YouTube](https://www.youtube.com/@MindSparkBD-j7h) · [Instagram](https://www.instagram.com/mindspark380) · [Facebook](https://www.facebook.com/234694639717095)
