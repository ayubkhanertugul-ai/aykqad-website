# AYKQAD Website

Simple, single-page static website for AYKQAD (Men's Islamic libas, handcrafted topis, oriental attars).

Files:
- index.html — main website (contains CSS + JS inline).

How to use:
1. Put `index.html` into a folder (optionally add `favicon.ico`) and open in a browser to preview.
2. Replace contact numbers/email/Instagram handle in the file if needed.

Quick deployment options:
- GitHub Pages:
  - Create a repository and push this file to the `main` branch.
  - In repo settings -> Pages -> Source choose `main` branch and `/ (root)`.
  - Your site will be available at `https://<username>.github.io/<repo>/`.

- Netlify:
  - Drag & drop the folder into Netlify Drop (https://app.netlify.com/drop).
  - Or connect your GitHub repo and deploy.

- Vercel:
  - `vercel` CLI or connect repo in the Vercel dashboard, deploy as a static site.

Notes & suggestions:
- Add `favicon.ico` and an Open Graph image for better sharing on social platforms.
- Consider adding server-side form handling if you'd like orders stored in a database (instead of only WhatsApp).
- For analytics, add Privacy-aware analytics (e.g., Plausible) or Google Analytics with user consent.
- For multilingual support (Arabic labels), consider adding proper RTL styling for Arabic text blocks.

If you want, I can:
- Push this to a GitHub repository for you and set up GitHub Pages.
- Create a small backend (Netlify Functions / serverless) to log orders.
- Generate favicons and social preview images.
