# glintstack.co.za

The Glintstack company website. Plain static HTML/CSS, no build step, hosted on GitHub Pages.

```
index.html                     landing page
pockard/privacy/               Pockard privacy policy (Play Console URL)
pockard/delete-account/        Pockard account deletion page (Play Console URL)
assets/site.css                shared styles
404.html, robots.txt, sitemap.xml, favicon.svg
CNAME                          custom domain for GitHub Pages
```

## Editing

Edit the HTML directly and push to `main`. GitHub Pages redeploys in about a minute.

When the Pockard privacy policy changes, keep it in step with `assets/legal/privacy_policy.md` in the Pockard app repo, bump the effective date, and update `lastmod` in `sitemap.xml`.
