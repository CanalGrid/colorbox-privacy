# colorbox-privacy

Public pages for the Android game **Color Block: HuePop** (`com.canalgrid.colorbox`, v2.0.0+) by Canal Grid.
HuePop replaced *Color Box: Tidy the Shelves* (≤ v1.4.0) on the same Play listing; the policy keeps a short section on those earlier versions.
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
Today HuePop has no ads, no purchases, no analytics, no notifications and no network calls; the weekly
scoreboard is offline with computer-generated players. Update the pages (and Play Console → Data safety) if any of these change:

- ads, in-app purchases, or an analytics / crash-reporting SDK are added
- the scoreboard goes online, or any score or name is uploaded
- Google Play Games, accounts, or cloud save are added
- notifications or new permissions are added
- the save data changes (list in `privacy/index.html` §2 and the table in `privacy/delete-account.html`)

Change the "Last updated" date on a page whenever its text changes.
