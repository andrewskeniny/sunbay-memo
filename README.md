# Sunbay.io investment memo — static site

Single-file static page (index.html). No build step.

Deploy on Vercel (CLI):
  npm i -g vercel
  cd sunbay-memo-site
  vercel          # first run: login + accept defaults
  vercel --prod   # production URL

Or push this folder to a GitHub repo and import it at vercel.com/new
(Framework preset: Other, no build command, output directory: ./).
