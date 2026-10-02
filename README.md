# New Hinata

An atmospheric, scroll-driven fan experience inspired by Hinata's quiet devotion. A lantern, falling petals, and a sequence of illustrated frames bring the story to life in the browser.

**Maintained and deployed by Sayed Sadiq**

[LinkedIn](https://www.linkedin.com/in/sayed-sadiq45/) · [GitHub](https://github.com/SayedSadiq45)

**Live site:** [new-hinata-sayed-sadiq.vercel.app](https://new-hinata-sayed-sadiq.vercel.app)

## The Experience

- Scroll through a 65-frame illustrated sequence.
- Explore the lantern scene, where the light follows the pointer on desktop.
- Move through the swing scene with layered parallax and falling petals.
- Respect reduced-motion preferences and adapt the layout for mobile screens.

## Run Locally

No build step or package installation is required. Open `index.html` in a browser, or serve this folder with any static web server.

For example, with Python installed:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy to Vercel

This static site is deployed as a separate Vercel project named `new-hinata-sayed-sadiq`. Deployments can be made directly from this folder with `npx vercel deploy --prod`; no framework preset or build step is needed. The original GitHub remote belongs to another account, so it is not connected for automatic deployments.

## Project Files

- `index.html` contains the page, styles, interaction, and animation logic.
- `frames/` contains the locally loaded WebP artwork and sequence frames.

## Source and Rights

This project is based on the existing [Hinata repository](https://github.com/Meghamittal0920/hinata). Its original commit history is preserved. This is a fan-made work using Naruto characters; all associated character and artwork rights remain with their respective owners.

No license is added by this README. Confirm the rights and intended license for the existing code and assets before publishing a license for the repository.
