# Ruby's Lens — photography website starter

A free static website for GitHub Pages. The imagery supplied is **placeholder artwork**; swap it for your own photographs before launching.

## Publish on GitHub
1. Unzip this folder on your computer.
2. Visit https://github.com/rubymfrancis/rubyslens and choose **Add file → Upload files**.
3. Upload `index.html`, `style.css`, `script.js`, and the entire `images` folder (keeping paths intact). GitHub's browser file uploader may not accept a folder directly on all browsers: you can select all files within the folder and upload them with drag-and-drop, ensuring the images are saved in `images/` (or use the GitHub web editor to create them individually). **Do not upload the outer `rubyslens-starter` folder as the site root.**
4. Commit changes to `main`.
5. In repository **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
6. The temporary URL should be https://rubymfrancis.github.io/rubyslens/ once published.

## Replace photos
- Replace images/hero.svg and the other `.svg` files with your own `.jpg` or `.webp` images. Update the `.svg` filenames in `index.html` to match (e.g. `images/hero.jpg`).
- Keep images compressed for fast loading (typically 150–400 KB for thumbnails and 300–800 KB for large photos, depending on quality).
- Update the placeholder captions, project names, and About paragraph in `index.html`.

## Custom domain later
- Set `rubyslens.co.uk` under Settings → Pages → Custom domain, **before** changing DNS in Fasthosts.
- Then create GitHub's official four A records for `@` in Fasthosts and a `www` CNAME to `rubymfrancis.github.io`.
- Check existing DNS/email records before changing anything. Enable Enforce HTTPS when available.

No build system or paid services required. Google Fonts is an optional third-party font dependency; the site has fallback fonts.
