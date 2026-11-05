# Downloads

Files offered for download on www.sharpn.co.uk, served at **files.sharpn.co.uk**.

## How it works
- This repo is published by Cloudflare Pages (project connected to this repo; custom domain files.sharpn.co.uk via a CNAME in the SHARPN DNS). Every change to `main` (including uploads through the GitHub website) republishes the site within a minute or two.
- A file at `course-outlines/example.pdf` here is served at `https://files.sharpn.co.uk/course-outlines/example.pdf`.
- `_headers` makes PDF, PowerPoint, Excel, Word, zip and Quick Access Toolbar (`.exportedUI`) files download instead of opening in the browser.

## Adding or updating a file
1. Upload it into the right folder (create the folder if it's new):
   - `course-outlines/` course outline PDFs
   - `training/` files for course attendees
   - `resources/` free downloadable resources (templates, toolbars and so on)
   - `share-images/` Open Graph (LinkedIn) share images, 1200 x 630 PNG. These open in the browser rather than download, so Webflow can use them by URL.
2. Name it the way it should arrive on someone's computer: lowercase, hyphens, no spaces, starting `sharpn-`. For example `sharpn-quick-access-toolbar.zip`.
3. To update a file, upload a new version with exactly the same name and folder. The link stays the same, so website buttons keep working.

## Share images (from 5 Nov 2026)
New pages get their share image from here, not from Webflow's asset library. Build the 1200 x 630 PNG, commit it to `share-images/` with the design system's name (for example `sharpn_share_course-storytelling_1200x630_v1.png`), then in Webflow set the page's Open Graph image by URL: `https://files.sharpn.co.uk/share-images/<file>`. To change an image later, commit a new version number and update the URL, because LinkedIn caches each image by its address. The 17 pages that existed before 5 Nov still point at Webflow-hosted copies; the same files are here for reference.

## Important
This repo is **public**. Anyone can browse it on GitHub and anyone with a link can download a file. Don't put anything here that should only reach paying attendees.
