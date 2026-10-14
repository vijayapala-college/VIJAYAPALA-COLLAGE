# Vijayapala Maha Vidyalaya website

A responsive, static, English-language website for Vijayapala Maha Vidyalaya, Matale. It is built with HTML, CSS and vanilla JavaScript and has no build step or runtime dependency. The school-provided flag and campus photographs are in `assets/`.

## Preview locally

Open the project folder in VS Code and either:

- Open `index.html` in a browser; or
- Use the free **Live Server** VS Code extension and choose **Go Live** for a local preview with automatic refresh.

The site is also compatible with Python's built-in static server. From this folder, run `python -m http.server 8000` and open `http://localhost:8000`.

## Update the content

- Edit the school name, supplied history, mission, vision and contact address in `index.html`.
- The teacher and student totals are each written once in the homepage community statistics.
- To update imagery, replace the referenced JPEG files under `assets/school photo/` or update their `src` values in `index.html` and the hero image URL in `css/style.css`. Keep descriptive alt text accurate.
- Add events by duplicating the `.event-card` article in `index.html`; only publish details confirmed by the school.
- The palette uses a restrained dark-red, warm-yellow and grey treatment based on the colours supplied in the brief. Adjust the CSS colour tokens if the school provides exact brand values.
- The header navigation links to sections in this single-page site. Update their hashes together with the corresponding section IDs if sections are renamed.
- No contact form is included. A form that delivers messages would require a separately configured backend or form service.

## Accessibility and assets

The page includes semantic landmarks, a skip link, keyboard-visible focus, an accessible collapsible mobile menu, descriptive image alternatives and reduced-motion support. School-provided images are used as supplied; confirm that any identifiable people in the photographs are authorised for public website use before launch.

The flag image is used as a small visual identifier, not recreated as a logo. The photographs supplied do not include an approved standalone logo file. System serif and sans-serif typefaces keep the site self-contained and available offline.

## Free static deployment

**GitHub Pages** can host this static site without a paid service:

1. Create a GitHub repository and add these files.
2. In the repository, open **Settings → Pages**.
3. Select deployment from the `main` branch and the repository root, then save.
4. Use the generated `github.io` URL to review the published site.

Cloudflare Pages is another free static-hosting option. Static hosting does not provide a contact-form backend or guarantee an official school domain. Before public launch, confirm permission to publish the supplied photographs and school identity assets, and provide any missing official telephone/email details or verified location if they should appear.
