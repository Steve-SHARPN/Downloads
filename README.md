# Downloads

Files offered for download on www.sharpn.co.uk, served at **files.sharpn.co.uk**.

## How it works
- This repo is published by Cloudflare Pages. Every change to `main` (including uploads through the GitHub website) republishes the site within a minute or two.
- A file at `course-outlines/example.pdf` here is served at `https://files.sharpn.co.uk/course-outlines/example.pdf`.
- `_headers` makes PDF, PowerPoint, Excel, Word, zip and Quick Access Toolbar (`.exportedUI`) files download instead of opening in the browser.

## Adding or updating a file
1. Upload it into the right folder (create the folder if it's new):
   - `course-outlines/` course outline PDFs
   - `training/` files for course attendees
   - `resources/` free downloadable resources (templates, toolbars and so on)
2. Name it the way it should arrive on someone's computer: lowercase, hyphens, no spaces, starting `sharpn-`. For example `sharpn-quick-access-toolbar.zip`.
3. To update a file, upload a new version with exactly the same name and folder. The link stays the same, so website buttons keep working.

## Important
This repo is **public**. Anyone can browse it on GitHub and anyone with a link can download a file. Don't put anything here that should only reach paying attendees.
