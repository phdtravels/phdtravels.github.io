# Peter — Personal landing page

Static GitHub Pages site for https://phdtravels.github.io/.

## Routes

- `/` → `index.html` (landing page)
- Unknown root-site paths, such as `/abc-xyz` → `404.html` (GitHub Pages custom 404)
- `/PersonalNotes/` → separately deployed Astro repository `PersonalNotes` (not a directory in this repo)

## Publish

1. Upload `index.html`, `404.html`, `.nojekyll` and the `assets/` folder to the **root of the `main` branch** in `phdtravels/phdtravels.github.io`.
2. Keep Settings → Pages → Source: **Deploy from a branch**; Branch: **main**; Folder: **/(root)**.
3. Open https://phdtravels.github.io/ and https://phdtravels.github.io/abc-xyz to test. Check PersonalNotes separately.

No additional workflow, framework or hosting is needed.

**Important:** The Journal and Tech cards link to `/PersonalNotes/` intentionally. They do not assume a specific Astro sub-route. Update these hrefs only after confirming your site's actual route paths.
