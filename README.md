# After Dark FC — website prototype

A mobile-friendly, static interactive teamsheet for After Dark FC 27 Pro Clubs.

## Features
- Five tactical formations and an 11-position pitch
- Clickable football shirts and provisional player claims
- Browser-local persistence, so claims survive refresh on the same device
- Responsive club dashboard using the official After Dark crest
- Home, Fixtures, Teamsheets, Squad, Results pages

## IMPORTANT
This is a **prototype**. No Discord login, Discord server role verification, shared database, manager permissions, or realtime synchronization is connected yet. The Discord button is intentionally disabled with an informational message. Browser-local claims are not secure and must never be treated as real match selections.

## GitHub Pages setup
Upload `index.html` and `assets/crest.png` to the repository main branch. In repository **Settings > Pages**, choose **Deploy from a branch**, select `main`, folder `/ (root)`, then save. The eventual site address is `https://NikkiMoonXO.github.io/after-dark-fc/`.

## Next development phase
- Supabase auth with Discord OAuth2
- Secure Discord membership and role verification through server-side functions
- Postgres tables for fixtures, player profiles, provisional claims and confirmed selections
- Row-level security, atomic claim insertion, and role-protected manager actions
