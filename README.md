# Laura Elizabeth Moreno-Gama — academic website

A static, unpublished first draft. No dependencies, build tools, external fonts, or JavaScript are required.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open the local server in your browser when running on your own computer. Stop with Ctrl+C. Cloud onboarding does not provide a browser preview link; a local HTTP request can validate the page.

## Edit the content

- `index.html` contains all text and sections. Research descriptions are explicit placeholders, not publication claims. Review the introductory biography before publishing.
- `assets/style.css` controls colors, spacing, typography, and mobile layouts.
- Portrait: add your photo under `assets/`, then replace the `.portrait-frame` div with an `img` using a relative path, descriptive alt text, and suitable width/height. Adjust its styling as needed.
- CV: add `assets/cv.pdf` when supplied, then replace `.cv-placeholder` with an actual link to that file. There is intentionally no broken download link.
- Contact: replace the placeholders with your supplied email and profile links. No contact details have been assumed.

## Publication

All asset paths are relative and work at the root of lmorenogama.github.io. The site can be served directly by GitHub Pages when you choose to enable it. This task does not enable Pages or publish the site.

## Review checklist

Check desktop and narrow mobile layouts, keyboard navigation and visible focus, the skip link, every section link, and supplied personal details before publication. No automated test suite is configured.
