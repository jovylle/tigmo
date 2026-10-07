# Tigmo Bisaya

Mga tradisyonal nga bugtong (riddles) sa **Wikang Cebuano** — ibinahagi sa
[Tigmo Bisaya Facebook page](https://www.facebook.com/profile.php?id=61595359612687)
ug ini nga website.

## Live

https://tigmo.uft1.com

## Deploy

Deploys to Cloudflare Pages on every push to `main`:

```bash
npx wrangler pages deploy site --project-name tigmo
```

## Develop

```bash
npx serve site  # or any static server
```

No build step — pure single-file HTML/CSS/JS, zero external dependencies.
