# Aria Code product website

A dependency-free responsive product page based on the approved image concept. Header and footer branding are text only. Screenshots and walkthrough content are illustrative, not live product execution.

## Preview

From this directory: `python3 -m http.server 4173 --directory dist`

## Source

- `dist/index.html`: page content
- `dist/styles.css`: responsive layout
- `dist/app.js`: demo stages, sample approval, use-case dialogs, installation platform selection, clipboard

Installation links and commands point to the official Aria Code repository. No account, model call, or backend is needed.

`dist/assets/hero.png` is the standalone hero artwork with a text-only terminal title.


## Interactive IP update

The original hero artwork is retained. Transparent hit areas add click greetings, a soft halo, and eye blinks; there is no redesigned mascot. The motion switch and system reduced-motion preference stop character animation. The demo supports coding, research and inventory scenarios, pauses on the proposed change/method, and continues after approval. All content remains illustrative and runs in the browser; it does not invoke a model or modify files.

Checked in the browser at 1280, 390 and 320 pixels: task selection, card-to-demo navigation, approval progression, completion marks, motion toggle, and page overflow.


## Frame-based mascot

`dist/assets/aria-ip-atlas.png` is an eight-pose transparent 4 × 2 atlas generated with the built-in image tool, using the existing hero mascot as the reference. Prompt: preserve the black organic silhouette, two white eyes and purple aura; neutral, look left, look right, blink, greeting, thinking, working and complete. Each pose has a measured registration offset to keep its body centered. The control-panel mascot changes gaze with pointer position, moves at most 3 px horizontally / 2 px vertically, greets on click, and follows demo state. The original hero remains intact. Reduced motion shows a static neutral pose. Browser checks covered click greeting, pointer gaze and offsets; JavaScript syntax was checked.

## Deploy to Vercel

Import `artheras/aria-code-web` into Vercel. Framework: Other. Root directory: repository root. Output directory: `dist`. Build and install commands are empty; the site has no runtime dependencies or environment variables. These settings are checked in as `vercel.json`.

The product source remains at https://github.com/artheras/aria-code. This repository contains the website only. Task examples run locally in the browser and do not call a live AI backend.
