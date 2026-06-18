# Wooyoung Cheon Portfolio

Static personal website for `https://wooyoungcheon.vercel.app`.

## Local Preview

```powershell
python -m http.server 4173
```

Open `http://localhost:4173`.

## Deploy To Vercel

1. Push this folder to a GitHub repository.
2. Import the repository in Vercel.
3. Keep the framework preset as `Other`.
4. Leave the build command empty.
5. Set the project name to `wooyoungcheon` to target `wooyoungcheon.vercel.app`.

Replace the placeholder links and email in `index.html` and `script.js` before sharing publicly.

Current Notion Growth Log page:

```text
https://app.notion.com/p/3820703e91d781f9a97dcfaccd8dd6b2
```

To use a real ID/profile photo in the header, add it as:

```text
assets/profile-photo.png
```

If that file is missing, the site automatically falls back to `assets/avatar.svg`.

## Search Indexing

The site includes:

- `robots.txt`
- `sitemap.xml`
- canonical URL for `https://wooyoungcheon.vercel.app/`
- JSON-LD Person structured data

After deploying, add the site to Google Search Console and submit:

```text
https://wooyoungcheon.vercel.app/sitemap.xml
```
