# vaanii-privacy-policy

Static site served by GitHub Pages at **https://www.vaaniiapp.com**.

Hosts the public Privacy Policy for **Vaanii**, the Gujarati alphabet learning app by
DreamCrafters Innovations (`com.dreamcraftersinnovations.vaanii`).

## URLs

| Path | Purpose |
| --- | --- |
| `https://www.vaaniiapp.com/` | Landing page |
| `https://www.vaaniiapp.com/privacy-policy/` | **Privacy Policy** — submit this URL to Google Play and App Store Connect |

## Files

```
CNAME                     custom domain (www.vaaniiapp.com)
.nojekyll                 serve files as-is, no Jekyll build
index.html                landing page
privacy-policy/index.html the policy (source of truth for the live page)
PRIVACY_POLICY.md         same text in Markdown, for reference/diffing
404.html                  not-found page
```

## Editing the policy

Edit `privacy-policy/index.html`, mirror the change in `PRIVACY_POLICY.md`, bump the
**Last Updated** date in both, then commit and push to `main`. GitHub Pages redeploys
automatically, usually within a minute.

Material changes to how children's data is collected or used must be published
**before** the change takes effect in the app.

## DNS

Managed at Hostinger. `www` is a CNAME to `krushang18.github.io`; the apex uses
GitHub Pages' four A records so `vaaniiapp.com` redirects to `www`.
