# Ecem Artworks — independent gallery website

A static GitHub Pages gallery for **Ecem Bozkurt**. No Wix or paid hosting required. Includes 30 optimized artwork images sourced from the uploaded Wix media archive. Originals were not modified.

## Publish

1. Create a new GitHub repository, e.g. `ecem-artworks-gallery`.
2. Upload the **contents** of this folder (not the ZIP itself) to the repository root.
3. In GitHub Settings → Pages, select **Deploy from a branch**, `main`, `/ (root)`.
4. Visit `https://YOUR_USERNAME.github.io/ecem-artworks-gallery/`. Keep Wix live and do not change DNS until the new gallery is reviewed.

## Edit paintings

Open `data/artworks.json` in GitHub and edit entries. Fields: `title`, `category`, `year`, `medium`, `dimensions`, `status`, `etsy_url`. If an artwork is listed on Etsy, paste its full listing URL in `etsy_url`. Otherwise, the artwork uses an email inquiry button.

**Important:** Titles are temporarily `Untitled`, and dates/dimensions/availability are intentionally blank or `On inquiry`. Verify against your own inventory before launch. Several photographs may show the same physical painting, and not all archive images are suitable for public display; this is a curated *draft*, not an authenticated catalogue.

## Before going live

- Verify which paintings are included, their titles, dates, media, dimensions, and availability.
- Replace the artist statement draft with Ecem's own wording.
- Replace `hello@ecemartworks.com` in `index.html` and `assets/site.js` with an email that actually receives mail.
- Confirm Etsy listing links, and optionally remove artworks you do not want shown.
- Keep your original high-resolution images backed up outside GitHub.
- Connect `ecemartworks.com` only after testing. Check whether Wix is your domain registrar before cancelling services.

## Attribution

Creator: Ecem Bozkurt. Original artwork and creative direction by Ecem Bozkurt; website implementation developed with AI assistance. Generated 2026-10-21. Project ID: ecem-artworks-gallery-v2.
