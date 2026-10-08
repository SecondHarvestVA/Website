# Second Harvest website

Single-page website for **Second Harvest**, a youth-led 501(c)(3) nonprofit in Loudoun County, VA (Aldie). It runs on GitHub Pages with no build step.

## Structure

- `index.html`: the whole site (HTML, CSS and JS in one file). Pages are sections switched by the URL hash:
  `#/` Home, `#/about`, `#/impact`, `#/start-a-chapter`, `#/testimonials`, `#/news`, `#/contact`
- `assets/`: logo, favicon and photos
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Fill in your links (one place)

Near the bottom of `index.html`, find `const SITE = { ... }`. All four are set; change them there if a link ever changes:

| Key | What to put |
|---|---|
| `email` | Contact email (every "Email us" and "Send a message" button uses it) |
| `instagram` | Full Instagram profile URL |
| `chapterForm` | Chapter application form link (e.g. a Google Form) |
| `ambassadorForm` | LCPS ambassador form link |

If a value is left empty, its buttons point to the Contact page.

## Other TODOs

Search `index.html` for `TODO` to find:
- The mission and vision wording (drafts, confirm or replace)
- The classroom "Quick Facts" figures on the About page (confirm the sources)
- Chapter eligibility, requirements and FAQ wording
- Real testimonials (a copy-paste template is in the Testimonials section)
- More media links

## Publish on GitHub Pages

1. Merge this branch into `main`.
2. On GitHub, go to **Settings → Pages**, then set **Source** to "Deploy from a branch", **Branch** to `main` and the folder to `/ (root)`.
3. The site goes live at `https://secondharvestva.github.io/website/` within a minute or two.

## Brand

The colors are sampled from the logo: sage `#979D61`, deep sage `#858C4C`, cream `#FBF5E7`, bread `#EE9A5A`, crust `#92431A`, basket tan `#E5C093` and deep olive text `#2B3316`. The fonts are Unbounded (display) and Figtree (body) from Google Fonts.
