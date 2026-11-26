# Udruga kapetana – Zagreb

A simple Croatian landing page for the Zagreb association of master mariners and deck officers. Plain HTML and CSS, with no installation or build step.

## Preview locally

Open `index.html` directly in a browser. All styles, images and links also work when the page is hosted under a GitHub Pages repository path.

## Publish with GitHub Pages

1. Commit and push this folder to `AlbertGregl/master-mariners-zagreb-static-page` on the `master` or `main` branch.
2. In the GitHub repository, open **Settings → Pages** and select **GitHub Actions** as the source.
3. Open **Actions → Deploy static site to GitHub Pages** and choose **Run workflow**, or push another change to the publishing branch.
4. The workflow publishes the site. Its deployment summary provides the live URL, normally `https://albertgregl.github.io/master-mariners-zagreb-static-page/`.

Future pushes to `master` or `main` deploy automatically. The workflow uploads only the page, stylesheet, images, statute and `.nojekyll` file. Repository settings and account plan must permit GitHub Pages.

See the [GitHub Pages workflow documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages).

## Edit the content

- `index.html`: Croatian introduction, association aims, membership information, founding date, postal address and email contact.
- `statut.html`: full statute as a styled, printable page with a linked table of contents and article anchors (`#clanak-1` through `#clanak-57`).
- `styles.css`: responsive layout and blue colour palette.
- `assets/logo.png`: existing association logo.
- `assets/brod-zagreb.png`: existing photograph of the ship Zagreb.
- `assets/crs-logo.svg`: official Croatian Register of Shipping logo from [its website](https://www.crs.hr/Portals/_default/skins/crs2021//images/CI/logoEN.svg), displayed in the “Prijatelji udruge” section with a link to [CRS](https://www.crs.hr/hr/).
- `documents/statut.txt`: original statute text, dated 28 September 2015. Keep this source and `statut.html` in sync when updating the statute.

Text, email address and images were taken from the neighbouring `master-mariner` project. Descriptions of the association's aims and membership were adapted from its statute. The statute text itself is preserved as supplied; confirm its currency before public release.

There are no login or contact forms, blog, member profiles, application APIs, database integrations, analytics, external fonts or JavaScript dependencies. Email links open the visitor's email application.

The original `master-mariner` project is unchanged. No site has been published by creating these local files.
