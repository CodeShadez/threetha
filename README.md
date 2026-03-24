# Theertha Portfolio

Professional static portfolio website for Theertha Anilkumar.

## Live Site

After enabling GitHub Pages, your site will be available at:

- `https://<username>.github.io/<repository>/`

Replace placeholders with your actual GitHub username and repository name.

## Project Structure

- `index.html` - Main production page
- `assets/` - Branding assets (favicon and social preview image)
- `404.html` - Friendly not-found page for GitHub Pages
- `robots.txt` - Search crawler instructions
- `sitemap.xml` - Search indexing map
- `.nojekyll` - Prevents Jekyll processing on GitHub Pages
- `.github/workflows/deploy-pages.yml` - Automated deployment pipeline

## Deploy With GitHub Pages

1. Push this repository to GitHub.
2. In GitHub, go to `Settings > Pages`.
3. Set source to `GitHub Actions`.
4. The included workflow will build and deploy automatically on push to `main`.

## Final Deployment Checklist

1. Replace placeholders in `robots.txt` and `sitemap.xml` with your real deployed URL.
2. Confirm `assets/favicon.svg` and `assets/og-image.svg` are reachable in production.
3. Run a hard refresh once after deploy to clear old cache (`Ctrl+F5`).
4. Verify homepage, contact links, and 404 page all load correctly.
5. Re-submit the updated sitemap URL in Google Search Console.

## Local Preview

Open `index.html` in a browser.

## Notes

- Keep `index.html` in the repository root for GitHub Pages.
- Update placeholders in `sitemap.xml` and `robots.txt` with your final URL.
