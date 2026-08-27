# Ali Naser — Engineering Portfolio

This folder is ready for a static GitHub/Cloudflare Pages deployment.

## Included

- Animated engineering intro (`index.html`)
- Complete portfolio (`portfolio.html`)
- Huawei HCIA-CT V1.0 Course Certificate of Completion
- Eight matched WRN assignment PDFs and a combined assignment archive
- CV, cover letter, project reports, project evidence, and embedded photos
- Responsive navigation, certificate/project lightboxes, print support, favicon, and social preview artwork

## Deploy

Upload every file and folder in this package to the root of the existing website repository. Keep the `assignments` folder intact. The site opens from `index.html`, plays the intro, and then launches `portfolio.html`.

The included `.assetsignore` prevents Cloudflare Workers from publishing repository metadata when deploying with `wrangler --assets .`.

After the hosting platform finishes redeploying, hard-refresh the live page with `Ctrl+Shift+R`.
