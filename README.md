# Laura Elizabeth Moreno-Gama — academic website

A static, unpublished first draft. No dependencies, build tools, external fonts, or JavaScript are required.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open the local server in your browser when running on your own computer. Stop with Ctrl+C. Cloud onboarding does not provide a browser preview link; a local HTTP request can validate the page.

## Edit the content

- `index.html` combines Home and the academic biography. `research.html`, `cv.html`, `fieldwork.html`, `life.html`, and `contact.html` contain individual sections. `about.html` redirects older bookmarks to Home. Research titles and collaborators follow the supplied CV. Review the introductory biography before publishing.
- `assets/style.css` controls colors, spacing, typography, and mobile layouts.
- Banner: `assets/community-energy-banner.webp` is an AI-generated conceptual illustration of communities, landscapes, and energy transitions inspired by the Colombian Andes. It is not a photograph, actual map, or depiction of a specific field site. The revised illustration includes a conceptual gathering of Indigenous community leaders. It does not represent named individuals, a specific Indigenous nation, or a documented field event. The full image displays without cropping; visible captions are intentionally omitted. The layout follows the supplied reference’s wide banner, stacked identity/navigation, and portrait sidebar while retaining the site’s typography and white background.
- Portrait: `assets/Laura.jpg` is displayed on the home page without cropping or changing the original photo. Replace that file to update the portrait.
- CV: `assets/cv.pdf` is the supplied original, linked from `cv.html`. Replace the PDF when updating the CV.
- Content and email are drawn from the supplied CV. Academic profile URLs remain unprovided; add only confirmed links. Research titles and collaborators follow the CV; abstracts and publication metadata have not been inferred.


Always use Laura Elizabeth Moreno-Gama in visible name references. The site uses white backgrounds. Colombian pride is expressed only on the Life outside academia page; flags and repeated pride labels have been removed. Personal interests, Cleopatra, places lived, and the Ecuador/Waorani reflection come from Laura Elizabeth’s own notes. Colombia fieldwork stories await further details. `fieldwork.html` and `fieldwork-colombia.html` provide the two location tabs using ordinary links, with no JavaScript dependency.

## Publication

All asset paths are relative and work at the root of lmorenogama.github.io. The site can be served directly by GitHub Pages when you choose to enable it. This task does not enable Pages or publish the site.

## Review checklist

Check desktop and narrow mobile layouts, keyboard navigation and visible focus, the skip link, every section link, and supplied personal details before publication. No automated test suite is configured.

## Research content notes

Project overviews are preliminary scope descriptions based on titles and the owner's supplied topics, not abstracts or reported findings. Paasha Mahdavi's collaboration is supplied by Laura Elizabeth. The master's thesis title, year, institution, and advisors follow the supplied CV; it is listed as earlier work rather than undergraduate work. Crossref and RePEc lookup requests were blocked by the environment, so the article has a labeled Google Scholar title search pending a direct publication URL. The thesis links directly to the IDEAS/RePEc and EconPapers records supplied by Laura Elizabeth.
