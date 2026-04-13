# Good Neighbor Tech

Friendly tech help for seniors in Missoula, Montana.

## Google Analytics (GA4)

Every HTML page on this site must include the following tracking snippet **immediately after the `<head>` tag** (before any other tags like `<meta>`). Do not add more than one Google tag per page.

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-B87GG61EHW"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-B87GG61EHW');
</script>
```

**Measurement ID:** `G-B87GG61EHW`

When creating any new page for this site, always include this tag.

## Site Structure

- `index.html` — Homepage
- `blog.html` — Blog listing page
- `resources.html` — Resources page
- `ai-grandfather-story-missoula.html` — Featured article (AI grandfather story)
- `scam-prevention-missoula-seniors.html` — Scam prevention guide
- `password-management-missoula-seniors.html` — Password management guide
- `share-photos-family-missoula-seniors.html` — Photo sharing guide
- `video-call-grandkids-missoula-seniors.html` — Video calling guide
- `logo.png` — Site logo
- `missoula-hero1.png` — Hero image

## Design System

See `../ARTICLE-STYLE-GUIDE.md` for the full design system (colors, fonts, component styles). The canonical article example is `ai-grandfather-story-missoula.html`.

## Deployment

This site is deployed via AWS Amplify from this GitHub repository.
No build step required — static HTML/CSS/JS only.
