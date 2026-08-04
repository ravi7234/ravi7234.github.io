# Ravi Ranjan — Personal Site

Single-page site rebuilt from the original Google Site, styled with a minimalist academic look (inspired by abhishek-bhardwaj.com). No build step — plain HTML/CSS. Sections: Home / Working Papers / Teaching / Contact, linked via anchor nav.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `ranjan-ravi.github.io` for a user site, or any name for a project site).
2. Upload the contents of this folder (`index.html`, `styles.css`) to the repo root.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save. Your site will be live at `https://<username>.github.io/<repo>/` within a minute or two.

## Editing content

- Everything (bio, photo, links, papers, teaching, contact) lives in `index.html`, in order: hero, `#research`, `#teaching`, `#contact`.
- Colors, fonts, spacing: `styles.css` (`:root` variables at the top).

## Notes

- The profile photo currently hotlinks to the original Google-hosted image URL. If you'd rather host it yourself, save a copy as `assets/photo.jpg` and update the `<img src>` in `index.html`.
- The Teaching section carries over the (currently empty) original content — add course listings whenever ready.
