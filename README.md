# LB_Portfolio

A personal portfolio website for Louis Birch showcasing projects, CV and demos. This repository contains the static site source (HTML, CSS, JS and assets).

Branch note
- This README is updated on the `develop` branch. Changes should be merged into `main` when ready for production.

Live demo
- Deploy via GitHub Pages or any static site host. Example GitHub Pages URL once enabled:
  https://loucas781.github.io/LB_Portfolio/

Table of contents
- Overview
- Repo structure
- Local preview
- Deployment
- License & reuse
- Contributing
- Contact

Overview
This repository contains a static portfolio site (index.html, all.css, assets folders). It is intended to present project work, downloads (CV) and images.

Repo structure (important files/folders)
- index.html — main site
- all.css — global stylesheet (consider splitting/minifying for production)
- LICENSE — All rights reserved (see License & reuse)
- favicon.png — favicon
- img/ — images used on site
- js/ — JavaScript
- fonts/ — custom fonts
- downloads/ — CV and downloadable files
- projects/, masters-projects/, undergrad-projects/ — project folders
- README.md — this file (develop branch)

Local preview
Clone the repo:
```
git clone https://github.com/loucas781/LB_Portfolio.git
cd LB_Portfolio
git checkout develop
```
Open index.html in your browser, or serve with a simple HTTP server for correct relative paths:
- Python 3: `python3 -m http.server 8000` and open http://localhost:8000

Deployment
- GitHub Pages: Repository settings -> Pages -> Source: `main` branch (or `develop` while testing) -> Root.
- Or deploy to Netlify/Vercel/Cloudflare Pages by connecting the repository and selecting the branch to publish.

Performance & accessibility notes
- all.css is large; consider splitting, removing unused rules and minifying (e.g., css/all.min.css). Use PurgeCSS or similar if you use tooling.
- Optimize images (resize, compress, WebP) and enable lazy-loading for non-critical images.
- Ensure semantic HTML and descriptive alt attributes on images.
- Add meta tags (title, description, viewport) and Open Graph tags for better social sharing.

License & reuse
- LICENSE in this repository is an "All rights reserved" statement.
- Copyright (c) 2026 Louis Birch. All rights reserved.
- No part of this repository may be reproduced, distributed, transmitted, displayed, or otherwise used without the prior written permission of the copyright owner.
- If you need permission to use any part of this repository, contact the author (see Contact below).

Contributing
- This project is not currently open for public reuse under an open-source license. Contributions are accepted by agreement—please contact the repository owner to propose changes.
- If you maintain contributions internally: use feature branches from `develop`, follow descriptive commit messages and open pull requests to merge into `develop` and then into `main`.

Contact
- Author: Louis Birch — https://github.com/loucas781
- Email: (add preferred contact email here if you want it public)

Notes / Next steps (recommended)
- Add screenshots or a GIF to this README to showcase the site.
- Move all.css into a css/ directory and create a minified production version.
- Add .gitignore (if missing) and remove .DS_Store from the repository.
- Consider adding automated checks (linting, basic Lighthouse run) in GitHub Actions for future PRs.

---

Copyright (c) 2026 Louis Birch. All rights reserved.