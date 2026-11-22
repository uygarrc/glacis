# Glacis

Website for Glacis, a wearable that reads fingertip skin temperature and warns you, calmly and early, before frostbite.

Static site with no build step: `index.html` plus images.

## Deploy on Vercel
1. Go to vercel.com/new and choose **Import Git Repository**, then pick `uygarrc/glacis`.
2. Framework preset: **Other**. Leave the build command empty, output directory `.`.
3. Deploy. Every push to `main` redeploys.

## Run locally
Open `index.html` in a browser, or run `npx serve .` in this folder.

## Before launch
Replace `[your email]` in the Field trials section of `index.html` with the real contact address.
