# LS MAYA ERP — React frontend starter

This repository is a frontend-only React implementation scaffold for the 31-screen LS MAYA Figma design.

## Run locally
1. Install Node.js 20+.
2. Extract this ZIP.
3. Open the project folder in a terminal.
4. Run `npm install`.
5. Run `npm run dev`.
6. Open the local Vite URL printed in the terminal.

## Build
Run `npm run build`.

## GitHub
Create an empty GitHub repository, then from this folder:
```bash
git init
git add .
git commit -m "Initial LS MAYA React frontend"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

Then import that repository in Google AI Studio Build mode.

## Important scope and design note
- All 31 Figma screen routes are represented.
- This is a React frontend starter with a shared LS MAYA visual system, navigation, demo tables, local form interactions and print-preview components.
- It is NOT connected to Supabase, a POS, payment gateway, live barcode hardware, or production APIs.
- Sample figures and sample rows are demo data and must be replaced with approved business data.
- This first code package is a structured implementation baseline, not a pixel-perfect automated Figma export of every individual frame. Compare each route side-by-side with the corresponding Figma frame and adjust any screen-specific differences before client sign-off.
- The exact supplied LS MAYA logo vector from the Figma file is included in `public/ls-maya-logo.svg`.
- No secrets, API keys or database credentials are included.
