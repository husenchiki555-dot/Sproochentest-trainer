# Sproochentest Trainer

A static Luxembourgish study website with 20 progressive lessons, 400 flashcards, 20 listening passages, 80 comprehension questions, speaking timers, progress tracking and a teacher view.

## Run locally

Open `index.html` in a modern browser, or serve the folder with any static web server.

## GitHub Pages

1. Create a new GitHub repository, for example `sproochentest-trainer`.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages** and set the source to **GitHub Actions**.
4. The included `.github/workflows/pages.yml` workflow deploys the site after each push to `main`.

## Audio

Audio uses the browser Web Speech API with `lb-LU` requested. Actual Luxembourgish voice availability depends on the device/browser.

## Storage

Progress stays only in the browser's `localStorage`; there is no account or external database.
