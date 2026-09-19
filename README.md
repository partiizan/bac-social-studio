# Barb Arnold Creative — Social Studio

Interactive GitHub Pages proof of concept, branded from https://www.barbarnoldcreative.com/.

## Enable the website
1. Open repository Settings → Pages.
2. Under Build and deployment, select **GitHub Actions** as Source.
3. Open Actions → Deploy Social Studio to GitHub Pages → Run workflow.
4. After the workflow succeeds, visit https://partiizan.github.io/bac-social-studio/.

Subsequent pushes to main deploy automatically.

## Included
- Shared composer with separate Facebook Page, LinkedIn profile/company, Instagram, and Threads previews and overrides.
- Curated career/communications sample drafts (not live AI).
- Local JPG/PNG/WebP uploads, resize/fit/crop presets, downloadable branded tip cards.
- Browser-local drafts and images; export to JSON.
- Calendar with demo scheduling and simulated per-channel publishing results.
- Illustrative analytics and account authorization explanations.
- Responsive layout, keyboard-accessible controls, and character-limit checks.

## Boundaries
No accounts are connected and no social content is sent. Scheduling does not run in the background. Analytics are examples. Instagram personal accounts require manual posting; professional accounts would be needed for future direct publishing. All saved posts remain in localStorage for this browser and origin and do not sync across devices. Clearing browser storage removes them. Export drafts to retain a copy.

The static site is public; saved draft content is not committed to this repository or transmitted to a server. No API keys, OAuth secrets, or tokens belong in these files. Google Fonts is used with local system fallbacks.

## Local preview
Serve this directory with any static HTTP server, e.g. `python -m http.server 8000`.
No build step or package installation is needed.

## Future live integration
Add an authenticated backend for OAuth authorization and encrypted token storage, platform API publishing, persistent media hosting, durable scheduling, and AI generation. Provider account types, app permissions/review, and reporting access must be verified for each platform. Keep real and simulated modes visually distinct. Never place service secrets in browser code.
