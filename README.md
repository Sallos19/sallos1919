# Role Scout

A small static watchlist for a UK job search: AI, crypto, and moderation, in English and Slovak. Remote first. Hybrid in London is in scope.

The page is one file you can open in a browser. There is no build step, no backend, and no account.

## Preview locally

Open `index.html` in a browser.

```bash
xdg-open index.html   # Linux
open index.html       # macOS
start index.html      # Windows
```

You can also drag `index.html` into a browser window. Styles live in `styles.css`. Links are relative, so the page works from disk and from a host.

## Update the board

- Watch criteria, standing gigs, and notes are in `index.html`.
- Outlier, Mindrift, and TELUS AI Community are standing mentions. Their links point at `example.com` placeholders. Replace each `href` when you have the real URL.
- To log a scout takeaway, copy an `<article class="note">` block in the Notes section and put the newest one first. The page includes a short “How to add a note” disclosure with the same steps.

## GitHub Pages (optional)

After this is on the branch you want to publish:

1. Open the repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select that branch and the `/ (root)` folder, then save.

GitHub will serve the site at `https://<user>.github.io/<repo>/`. Project sites need the relative asset paths already used here (`styles.css`, `favicon.svg`), so no extra base-path setup is required.

## Earlier practice files

`Test` is the original repository bootstrap note from the first commit. It is unchanged.
