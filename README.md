# Her Name (Today, Anyway)

A single-page app for a D&D character whose chaos-genie wife's name changes
every time someone says it. Tap the button to summon the next name. Your
place in the list is saved in your browser, so closing and reopening the
page picks up where you left off.

- 409 unique names, shuffled: a mix of everyday names (Tabitha, Sarah,
  Rebecca...), whimsical chaos-flavored names (Kerfuffle, Snickerdoodle,
  Widget...), a handful of moodier fantasy names, and real names drawn from
  17 different cultures.
- No build step, no dependencies, no backend. It's one HTML file.
- "Reset" puts you back at name #1 if you ever want to start the list over.

## Run it locally

Just double-click `index.html`. It works straight from your file system,
no server needed.

## Put it on GitHub Pages (so you have a link you can open anywhere)

1. Create a new repository on GitHub (public or private both work, but
   GitHub Pages on a free plan requires **public** for it to be visible
   without signing in).
2. Upload `index.html` to the repo (drag-and-drop on the GitHub website
   works fine, or `git add` / `commit` / `push` if you're using git).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch."
5. Set **Branch** to `main` (or `master`) and folder to `/ (root)`, then
   **Save**.
6. GitHub will give you a URL that looks like:
   `https://your-username.github.io/your-repo-name/`
   It can take a minute or two to go live the first time.

That's it — that URL is a working link to the app from any device.

## A note on the saved progress

The app remembers your position using your browser's local storage, which
is tied to *this specific site + this specific browser*. That means:

- Closing the tab, closing the browser, or restarting your phone/computer
  won't reset it.
- Opening the app in a different browser, or in private/incognito mode,
  will start fresh (or not save at all, in private mode).
- It won't sync across devices — your phone and your laptop each keep
  their own separate position, since they're different browsers.

If you ever want to wipe it and start over, just hit **Reset** in the app,
or clear your browser's site data for the page.
