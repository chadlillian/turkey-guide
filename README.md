# Highlights of Turkey: a historical and New Testament companion

A single-page travel guide for the Highlights of Turkey tour (15–24 October 2026): 25 stops from Istanbul to Ephesus, each with its history, people, politics and New Testament connections. It also has a route map, an itinerary, a scripture finder and a downloadable PDF of the same guide.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site. Styles and scripts are built in. |
| `Highlights-of-Turkey-Companion.pdf` | The printable guide, linked from the site's "Download PDF" button |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish on GitHub Pages

**From the command line**

```bash
cd turkey-guide            # the unzipped folder
git init -b main
git add .
git commit -m "Highlights of Turkey guide"
git remote add origin git@github.com:YOUR-USERNAME/turkey-guide.git   # create the empty repo on github.com first
git push -u origin main
```

Then on GitHub, go to **Settings → Pages → Build and deployment**. Set the source to **Deploy from a branch**, choose **main** and **/ (root)**, and save. About a minute later the site will be live at `https://YOUR-USERNAME.github.io/turkey-guide/`.

**From the browser:** create a new public repository, click **uploading an existing file**, drag in `index.html` and the PDF, commit, then turn on Pages as above.

A Pages site is public. Hosting Pages from a private repository requires a paid GitHub plan.

## Photos

The photos load directly from Wikimedia Commons, so the repository stays small. Each caption has a **Photo: Wikimedia Commons** link to the file's page, which shows the photographer and the licence. The full list is under **Photo credits** at the bottom of the page. Most Commons photos are CC BY or CC BY-SA, and those licences require credit to the author. If you want author names on the page itself, copy them from those file pages into the captions. If a photo is ever removed from Commons, the page hides its frame automatically.
