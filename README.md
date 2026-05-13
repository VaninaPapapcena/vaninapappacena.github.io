# GitHub Pages portfolio

This folder contains the static portfolio prepared to replace the current Framer site with a GitHub Pages site under `vaninapappacena.com`.

## Files
- `index.html` — main page
- `styles.css` — styles
- `CNAME` — custom domain configuration for GitHub Pages

## Recommended publishing path
Create a public repository named:

`<your-github-username>.github.io`

Then upload the contents of this folder to the root of that repository.

## How to publish
1. Create a new public repository on GitHub named `<your-github-username>.github.io`.
2. Upload `index.html`, `styles.css`, and `CNAME`.
3. Commit the files to the `main` branch.
4. Open the repository settings on GitHub.
5. Go to **Pages**.
6. Confirm deployment from the `main` branch / root.
7. Verify that the published URL works at `https://<your-github-username>.github.io/`.

## Connect the custom domain
The `CNAME` file is already configured for:

`vaninapappacena.com`

In GitHub Pages settings, set the custom domain to the same value and then update the DNS with your domain provider.

### Typical DNS setup
- `A` record → `185.199.108.153`
- `A` record → `185.199.109.153`
- `A` record → `185.199.110.153`
- `A` record → `185.199.111.153`
- `CNAME` record for `www` → `<your-github-username>.github.io`

After DNS propagation, both `vaninapappacena.com` and `www.vaninapappacena.com` can point to the GitHub Pages site.

## Before publishing
- Adjust any copy you want to personalize.
- If you want a downloadable CV or PDF portfolio, add the file to this folder and link it from the page.
- If the old Framer site is still live, keep only one platform connected to the domain at a time to avoid DNS conflicts.
