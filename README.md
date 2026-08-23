# colorbox-privacy

Public pages for the Android game **Color Box: Tidy the Shelves** (`com.canalgrid.colorbox`) by Canal Grid.
Static HTML, no build step, no dependencies — served by GitHub Pages.

| Page | File | URL once Pages is on |
|---|---|---|
| Privacy policy | `privacy/index.html` | `https://canalgrid.github.io/colorbox-privacy/privacy/` |
| Feedback & support | `privacy/feedback.html` | `https://canalgrid.github.io/colorbox-privacy/privacy/feedback.html` |
| Delete your data | `privacy/delete-account.html` | `https://canalgrid.github.io/colorbox-privacy/privacy/delete-account.html` |
| Root redirect | `index.html` | `https://canalgrid.github.io/colorbox-privacy/` → privacy policy |

## Turning on GitHub Pages

Repository → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → **Save**.
The site is usually live a minute or two later.

## Where these URLs go in Play Console

- **App content → Privacy policy** — the privacy policy URL (required before you can publish)
- **Store listing → Support → Website** — either page works; the feedback page is friendlier
- **Store listing → Support → Email** — `vmwnpela@gmail.com`
- **App content → Data deletion** — the "Delete your data" URL (required once you declare the app collects any data)

## Keeping it accurate

The policy describes what the app actually does, so it has to be revisited when the app changes.
Update it if any of these become true:

- an analytics or crash-reporting SDK is added (there is none today)
- in-app purchases go live (Remove Ads is currently a local flag, not a real purchase)
- Google Play Games leaderboards are enabled (compiled out today — needs the `COLORBOX_GPGS` define)
- ads are removed entirely, or a different ad provider replaces Unity LevelPlay

Change the "Last updated" date in `privacy/index.html` whenever the text changes.
