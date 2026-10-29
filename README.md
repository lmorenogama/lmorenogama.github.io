# Laura Elizabeth Moreno-Gama — academic website

A static, unpublished first draft. No dependencies, build tools, external fonts, or JavaScript are required.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open the local server in your browser when running on your own computer. Stop with Ctrl+C. Cloud onboarding does not provide a browser preview link; a local HTTP request can validate the page.

## Edit the content

- `index.html` is the quiet landing page. `about.html`, `research.html`, `cv.html`, and `contact.html` contain the individual sections. Research descriptions are explicit placeholders, not publication claims. Review the introductory biography before publishing.
- `assets/style.css` controls colors, spacing, typography, and mobile layouts.
- Portrait: `assets/Laura.jpg` is displayed on the home page without cropping or changing the original photo. Replace that file to update the portrait.
- CV: `assets/cv.pdf` is the supplied original, linked from `cv.html`. Replace the PDF when updating the CV.
- Content and email are drawn from the supplied CV. Academic profile URLs remain unprovided; add only confirmed links. Research titles and collaborators follow the CV; abstracts and publication metadata have not been inferred.


Always use Laura Elizabeth Moreno-Gama in visible name references. The site uses white backgrounds. The Colombian flag accents and Spanish welcome celebrate her Colombian roots without attributing unprovided personal history.

## Publication

All asset paths are relative and work at the root of lmorenogama.github.io. The site can be served directly by GitHub Pages when you choose to enable it. This task does not enable Pages or publish the site.

## Review checklist

Check desktop and narrow mobile layouts, keyboard navigation and visible focus, the skip link, every section link, and supplied personal details before publication. No automated test suite is configured.
