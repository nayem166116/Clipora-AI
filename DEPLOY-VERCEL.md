# Deploy CrimVid to Vercel

## Drag-and-drop
1. Extract the ZIP.
2. Open https://vercel.com/new.
3. Choose **Deploy without Git** or drag the extracted folder into Vercel.
4. Framework preset: **Other**.
5. Build command: leave empty.
6. Output directory: leave empty.
7. Click **Deploy**.

## Git deployment
1. Push all extracted files to the root of a GitHub repository.
2. Import that repository in Vercel.
3. Use framework preset **Other** with no build command.
4. Deploy.

## Before production launch
- Replace `https://crimvid.com` in `sitemap.xml` and `robots.txt` with the final domain.
- Add the production favicon/logo files if you have final brand assets.
- Connect real authentication, storage, billing, and AI processing before accepting customers.
