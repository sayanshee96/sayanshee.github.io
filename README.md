# Dr. Sayan Shee academic website

This is a static, GitHub Pages-ready website. Open `index.html` locally in a browser to preview it.

## Publish with GitHub Pages

1. Create a GitHub repository. For `https://YOUR-USERNAME.github.io`, name it `YOUR-USERNAME.github.io`.
2. Upload the contents of this folder (not the enclosing folder itself) to the repository root.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, branch `main`, and folder `/ (root)`.
4. Save. GitHub will publish the site within a few minutes.

## Edit the site

- Update page text in the corresponding `.html` file.
- Add a portrait or research image to `assets/images/`, then reference it from the relevant HTML page. No image was included in the source package, so the current home hero uses an abstract CSS graphic instead.
- Add verified Google Scholar, ResearchGate, LinkedIn, Facebook, and Twitter/X profile links once their exact URLs are available. Their presence was supported by the legacy site; their URLs were not captured.
- Add publisher/DOI links to publications only after verifying each URL.
- The contact form is visual only on GitHub Pages. Connect it to Formspree, Netlify Forms, or another form service following that service's documentation.

## Files

- `index.html` — home page
- `about.html` — experience, education, and achievements
- `research.html` — verified research-focus summary
- `publications.html` — all 21 supplied publications with search and year filtering
- `useful-links.html` — journal, database, and lab-resource links
- `contact.html` — legacy contact information and a contact-form interface
- `assets/css/style.css` — site design and responsive layout
- `assets/js/script.js` — mobile menu, publication filtering/search, and static form feedback

## Source fidelity note

The site preserves facts from the supplied About and Publications PDFs and the prior legacy-site extraction. It does not invent a portrait, social profile URLs, DOI URLs, or detailed research-project descriptions that were not provided.
