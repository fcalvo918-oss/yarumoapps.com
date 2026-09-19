# Ferchocol Software portfolio package — not published

This package is designed to be merged into the root of the existing
`fcalvo918-oss/yarumoapps.com` GitHub repository **after approval**.

The included files are:

- `index.html` — proposed Ferchocol Software website-design homepage
- `portfolio.css` — homepage styles
- `assets/FerchocolLogo.svg` — supplied Ferchocol Software logo, unchanged
- `samples/juniper-table/` — fictional restaurant sample and local assets

The package deliberately does **not** contain `CNAME` or `privacy.html`.
Keep both existing repository files unchanged. Do not delete them. The sample
is fictional: it has no live reservations, ordering, customer details, real
restaurant address, or real client endorsement.

## Preview locally in VS Code (Windows)

1. Unzip this package into a separate folder. Do not unzip it into your GitHub
   repository yet.
2. Open this folder in VS Code and select **Terminal > New Terminal**.
3. Run:

   ```powershell
   py -3.10 -m http.server 8000
   ```

4. Open `http://localhost:8000/` for the portfolio homepage.
5. Select **View the sample site**, or open
   `http://localhost:8000/samples/juniper-table/`.
6. Press Ctrl+C in the terminal when finished.

The web fonts load from Google Fonts when online; system fonts are used offline.

## Before any public launch

1. Confirm the wording and design for **Ferchocol Software**. The
   `yarumoapps.com` domain is only the proposed hosting address, not the brand.
2. Choose and add an approved business contact method. This draft has no
   inquiry form, email link, or fabricated contact details.
3. Confirm the proposed package scopes and replace draft copy you do not want.
4. Check the old `privacy.html` redirect continues to work.
5. Make a backup of the GitHub repository before replacing its `index.html`.
6. Obtain your explicit approval before any push or publication.

Updating `index.html` in the live GitHub Pages repository is a public
publication. This package itself does not update the repository or DNS.
