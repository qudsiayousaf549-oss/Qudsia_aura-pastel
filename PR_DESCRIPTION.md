# Pull Request: Add Atelier Noir luxury site

This PR adds a 6-page ultra-luxury furniture website prototype built with HTML, CSS, Vanilla JS, Three.js, and GSAP. It includes interactive 3D viewers with photoreal fallback assets, synthesized cinematic audio hooks, and placeholder model/audio assets so you can preview immediately.

What this PR includes

- Pages:
  - home.html — Homepage with interactive 3D viewer
  - collections.html — Product grid, quick view modal
  - showroom.html — Immersive 3D showroom scene
  - bed-closet.html — Centered bed and interactive closet
  - our-story.html — Brand story, materials, testimonials
  - contact.html — Contact form and showroom info

- Model placeholders in /models/ for easy swap-in
- Asset READMEs under /models and /assets to guide replacements
- Synthesized audio fallback (in-browser) and hooks to add mastered audio files

Notes & next steps

- I have not deleted any files from your default branch. If you want files removed, provide exact paths and I will include those deletions in this PR for review.
- To preview with high-quality visuals, upload optimized GLB files to models/ and replace the placeholder filenames used in each page (or update MODEL_URLs in the HTML to point to CDN-hosted GLBs).

How to review

- Visit the branch: https://github.com/qudsiayousaf549-oss/Qudsia_aura-pastel/tree/site/atelier-noir
- Run locally: clone the repo and check out site/atelier-noir, then serve with a static server (python3 -m http.server) to preview pages.

