# Feather Rush PWA

This folder is a complete installable Progressive Web App package for GitHub Pages.

## Publish it

Upload the *contents* of this folder to the root of the existing `Feather-Rush-game` repository, replacing its current `index.html`. Keep `manifest.webmanifest`, `service-worker.js`, and the `icons` folder beside it. Commit the changes and wait for GitHub Pages to deploy.

The existing GitHub Pages address stays the same: `https://sn0rkdev.github.io/Feather-Rush-game/`.

## Install on Android

Open the site in Chrome. Use the browser menu and choose **Install app** or **Add to Home screen**.

## Install on iPhone

Open the site in Safari, tap **Share**, then choose **Add to Home Screen**. iPhone does not show the same install prompt as Android; the Safari share menu is the installation path.

After the first visit the service worker caches the game shell, so it can open offline. Online leaderboard access still requires an internet connection and Supabase configuration.
