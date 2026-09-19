# Give Energy Make Smiles — Static Site

A plain static rebuild of giveenergymakesmiles.com, ready for **GitHub Pages**.
Built September 2026 with the business co-owner's approval.

## What's inside

- **Pages (11):** Home, About (Meet Kayla), Therapy Modalities, Conditions Treated,
  Rates/Insurance, FAQ, Testimonials, Resources, Blog index, Contact, Privacy Policy
- **Blog:** all **85 posts** with full text, publish dates, and cover images, newest first
- **Images:** 101 files in `assets/img/`, all local (no hotlinking)
- Clean URLs: one directory per page (`/about/`, `/blog/<slug>/`, …)
- Mobile-responsive, no build step, no JavaScript framework

## Not included (per owner request)

Store, Digital Wellness Hub, Voyager pages, Sound Sanctuary, game, challenges,
membership plans, and duplicate `copy-of-*` draft pages.

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `give-energy-make-smiles`).
2. From this folder:
   ```
   git remote add origin https://github.com/YOUR-USERNAME/give-energy-make-smiles.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Deploy from a branch → `main` / root**.
4. To use giveenergymakesmiles.com: **Settings → Pages → Custom domain**,
   enter the domain, then point the domain's DNS (A records or CNAME) at GitHub
   per the instructions GitHub shows.

## Rebuilding

The build scripts live outside this repo (they were one-shot tools):

- Content was scraped from the Wix sitemaps + pages, images downloaded from
  `static.wixstatic.com` and verified as real image bytes.
- To regenerate, re-run the saved build script against the scrape data.

## Notes

- Contact info on the site: shawn@giveenergymakesmiles.com, 407-906-2891.
- Booking is a free 10–15 minute consultation via the Contact page (no store checkout).
- Crisis strip in the footer links to 988.
