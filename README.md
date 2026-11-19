# Academic website

Public academic website: https://gonzalobuenob.github.io/.

## Maintenance

- Edit `index.html` for biography, research, tools, presentations, education and teaching. Check publication status, authorship, titles, dates and links before publishing.
- Replace `cv.pdf` when updating the public CV; keep its stable filename and verify the link in the page.
- Store only approved public paper PDFs in `papers/`; update the corresponding links in `index.html`. Private or unapproved manuscripts must not be committed to this public repository, even temporarily.
- Update `photo.jpeg` only when replacing the public profile photo.
- Maintain the canonical URL, metadata and structured data in `index.html`; keep `robots.txt` and `sitemap.xml` aligned with the public URL and update the sitemap last-modified date when the published page changes materially.

## Before and after publishing

Preview locally (for example, `python3 -m http.server 8000` from the repository root), check layout and links, and confirm that only intended public material is included in the diff. Commit and push approved changes to `main`, then verify the live GitHub Pages site and its PDF links. Check the repository's Pages settings if deployment does not reflect the commit.

The public site is separate from the private research manuscript inventory used for conference screening. Updating a private manuscript does not authorize public release; reconcile public bibliographic details manually and publish only material approved for circulation.
