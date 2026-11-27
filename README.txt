NETRUNNER (PWA build 0.15.0-mwydcxf5)

This folder is the whole game. To play it as an installable app, host the
folder on any HTTPS static host, then open the address on your phone:

  - Netlify Drop: drag this folder onto https://app.netlify.com/drop
  - GitHub Pages, Cloudflare Pages or Vercel also work (free)

Install it:
  - iPhone/iPad (Safari): Share button > Add to Home Screen
  - Android (Chrome): menu > Install app (or the install banner)

After the first visit it works offline. Progress is saved on the device.

Testing on a computer: from inside this folder run
  npx serve .        (or: python3 -m http.server 8080)
and open http://localhost:3000 (or :8080). Opening index.html directly from
the file system runs the game, but it can't install or work offline.
