# Business Landing Page

This is a small static landing page. Quick notes:

- Preview locally: open `index.html` in your browser or use Live Server for a better dev experience:

```powershell
npx live-server --port=5500
```

- Images: hero and about images have optimized formats available in `images/`:
  - `teamwork-hero.jpg` (original hero)
  - `teamwork-hero-web.webp` and `teamwork-hero-web.avif` (optimized)
  - `teamwork-about.jpg` (original about)
  - `teamwork-about-web.webp` and `teamwork-about-web.avif` (optimized)

- Regenerating images: an `optimize-images` npm script is present in `package.json` that would run conversion scripts if they were included. If you want the scripts restored (or to use a different tool), tell me and I can add them back.

- To further reduce size: I can generate WebP/AVIF versions at different sizes and update responsive srcset values.

If you'd like, I can also create a clean distribution folder with only the files needed for deployment.
