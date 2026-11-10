# Kanayochi Okeke — Portfolio

A lightweight, responsive, static portfolio for GitHub Pages. Built with vanilla HTML, CSS and JavaScript. No framework, package manager, backend or build step is required.

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server.

For example, with Python installed:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `kanayochi-portfolio`.
2. Push the contents of this folder to the repository's `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **GitHub Actions** as the source.
5. The included workflow (`.github/workflows/deploy.yml`) will deploy the site after a push to `main`.
6. Wait for the workflow to finish. GitHub will show the published URL under **Settings → Pages**.

The usual project-site URL will be:

`https://YOUR-GITHUB-USERNAME.github.io/kanayochi-portfolio/`

Replace the placeholder with your GitHub username and repository name.

## Custom domain (optional)

Add your domain in **Settings → Pages**. Then create the DNS records requested by GitHub. If you use a custom domain, add a `CNAME` file at the repository root containing only the domain name.

## Before publishing

- Check that the email and LinkedIn links are correct.
- Review every experience statement and metric for accuracy and client disclosure approval.
- Do not add confidential architecture diagrams, internal URLs, repository names, customer data or security implementation details.
- The page intentionally publishes only email and LinkedIn as contact methods; it does not display a phone number.
- The Google Fonts import is optional. If you want zero third-party font requests, remove the `@import` line at the top of `css/main.css`; the system font fallbacks will remain.

## Updating content

Edit `index.html`. Styling lives in `css/main.css`, and the small mobile-navigation/year script lives in `js/main.js`.
