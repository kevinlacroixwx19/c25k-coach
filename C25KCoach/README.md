# C25K Coach PWA

A standalone progressive web app with 27 sessions, local workout completion tracking, run/walk countdowns, spoken interval cues, and optional Screen Wake Lock.

## Publish for free using GitHub Pages (Windows PC)

1. Create a free GitHub account, sign in, and create a **public** repository named `c25k-coach`.
2. Use **Add file > Upload files** to upload the five files from this folder (index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png) to the repository root. Commit the files.
3. Open **Settings > Pages**, choose **Deploy from a branch**, `main`, `/ (root)`, and Save.
4. Wait for deployment. Open `https://YOUR-USERNAME.github.io/c25k-coach/` in iPhone Safari.
5. Tap **Share > Add to Home Screen > Add**, then launch the Home Screen icon.

GitHub Pages uses HTTPS, required for service workers and Screen Wake Lock. Changes to files may take a few minutes to publish; installed PWAs may need reopening to pick up updates.

## Music and iOS limitations

Play music in Spotify/Apple Music first, then switch to C25K Coach. Speech synthesis may pause or duck music; it depends on iOS and the other app. Safari/iOS may suspend a PWA when locked or backgrounded, and speech cues are **not guaranteed** while locked. Enable Keep screen awake, keep the app foregrounded, and test before relying on it. Wake Lock may be unsupported or revoked by iOS. For reliable lock-screen coaching, build a native iOS app.

## Program

Three days weekly with at least one rest day between. Every workout adds 5-minute warm-up and cool-down walks. Weeks 1–4 interval workouts repeat across all 3 days. Week 5 and 6 have three different workouts. Weeks 7–9 are continuous 25-, 28-, and 30-minute runs. Weeks 1–4 use simplified interval schedules; they are not an exact reproduction of any branded program.

## Storage and privacy

Progress stays in the browser's localStorage. No accounts, tracking, server, or third-party services. Clearing Safari website data removes progress.
