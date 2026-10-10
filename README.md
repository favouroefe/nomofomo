# NoMo FOMO

**More memories. Less money.**

A Dublin student hackathon website concept for discovering affordable activities by interest, budget, time and transport preference.

## Pages

- `index.html` — project overview and prototype screens
- `find.html` — interactive plan finder
- `activities.html` — activity library
- `contact.html` — project contact/feedback page
- `data/nomo-fomo-activities.json` — curated activity records used by the finder and library
- `assets/` — local logo and prototype screen images

## Run locally

This is a static website. From the repository root, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/>. A local static server is recommended because the pages load the activity data from JSON.

The pages use Tailwind CSS from its CDN, so an internet connection is needed for styling. The activity list uses curated information and cost estimates; it is not a live event feed, booking service, or price-verification system.

## Project status

This repository contains a copy of the currently published website pages and their referenced local assets. It is intended as a starter source repository for continued development. The published site remains hosted separately on Manus unless deployment is configured independently.
