# Nora Ellis Photography

A one-page personal website for a freelance wedding and portrait photographer.

- `index.html` holds the whole page (HTML and CSS, no build step).
- `images/` holds the portfolio photos.
- `vercel.json` sets up static hosting on Vercel.

Open `index.html` in a browser to view it. Swap the placeholder name and email, then drop more photos into the grid.

## Deploy to Vercel

This is a static site, so there is nothing to build.

1. Sign in at vercel.com and choose Add New, then Project.
2. Import this GitHub repository.
3. Leave the framework preset as Other and the build and output settings at their defaults. `vercel.json` already tells Vercel to serve the repo root as is.
4. Select Deploy.

Every push to `main` then redeploys the site automatically. To add a custom domain, open the project's Domains settings in Vercel.

To deploy from a terminal instead, install the Vercel CLI (`npm i -g vercel`) and run `vercel` in this folder.
