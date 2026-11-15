BRAIN TRAP – ONLY 5% CAN SOLVE IT! (Version 2.0)

CONTENTS
- index.html          Main game
- manifest.json       Installable PWA metadata
- sw.js               Offline service worker
- icon.svg            App icon
- privacy-policy.html Basic privacy policy for this offline/local-save version

LOCAL TEST
1. Extract this ZIP.
2. For a quick preview, open index.html in a browser. Some PWA features only work on HTTPS or localhost.
3. For full install/offline testing, upload the whole folder to an HTTPS static host.

PUBLISH AS A WEBSITE (GLOBAL PLAYERS)
1. Create a GitHub account and a public repository named brain-trap-game.
2. Upload ALL files from this folder to the repository root (not the ZIP itself).
3. Open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish. Your public URL will look like:
   https://YOUR-USERNAME.github.io/brain-trap-game/
6. Test that URL on mobile and desktop, then share it worldwide.

IMPORTANT
- This version stores scores/progress on each player's own device. It does NOT yet have a global online leaderboard or cloud accounts.
- The privacy policy contact section must be completed with a real support email before public launch.
- For a real global leaderboard, connect a backend/database (for example Supabase or Firebase), add user identity/anti-cheat protections, and update the privacy policy.
- Google Play publication is a separate Android packaging and review process. A website ZIP is NOT an Android App Bundle (.aab).
- A Trusted Web Activity can package a hosted PWA for Play, but it requires Digital Asset Links and a verified website/domain association. Google Play may reject low-value or simple webview-only apps; ensure the game has sufficient original functionality and follows all policies.


PWA ICONS
- icon-192.png and icon-512.png are included for Android/Chrome installability metadata.

BEFORE PUBLIC LAUNCH
- Replace the placeholder contact text in privacy-policy.html with a real monitored support email.
