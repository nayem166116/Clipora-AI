# CrimVid website

## Run locally

```bash
python3 -m http.server 8080 -d .
```

Open http://localhost:8080. The site uses clean folder-based routes and contains no build dependencies.

## Deploy
Upload the folder to Vercel, Netlify, Cloudflare Pages, or any static host. Replace `crimvid.com` in `sitemap.xml` with the production domain before launch.
