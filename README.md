# 8-Week Calisthenics: phone app

This folder is an installable web app. Once it's on your home screen, it opens full-screen with its own icon, works offline, and keeps the screen awake during a session.

## 1. Put it online (one time, about 5 minutes)

The phone has to load the app from an https address once. The easiest free option is GitHub Pages:

1. On github.com, create a new **public** repository, for example `calisthenics`.
2. Choose **Add file → Upload files**, then drag in everything in this folder. That's `index.html`, `manifest.webmanifest`, `sw.js` and the `icons` folder. Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, pick **Deploy from a branch**, then branch `main`, folder `/ (root)`. Save.
4. After a minute or two, the app is live at `https://<your-username>.github.io/calisthenics/`.

Anything that serves static files over https works too, such as Netlify, Cloudflare Pages or your own server.

The files contain no personal data. Your workout log is stored only on your phone.

## 2. Install it on your phone

- **iPhone:** open the address in **Safari**, tap **Share**, then **Add to Home Screen**.
- **Android:** open it in **Chrome**, tap **⋮**, then **Install app** (or **Add to Home screen**).

Always launch it from the home-screen icon. The installed app and the browser tab keep separate logs.

## 3. Keep your log safe

Your log lives only on the phone. Every week or two, go to **Log → Backup → Copy backup** and paste the text into Notes or an email to yourself. To move to a new phone, use **Restore from a backup**.

## Updating the app

Upload a changed `index.html` to the same repository. The app picks it up the next time you open it while online.
