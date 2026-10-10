# Perspective: Ihsan Ibrahim's Portfolio

A single-file portfolio site (`index.html`). Everything (HTML, CSS, JS, images) lives in that one file. Hosted on Vercel, source on GitHub.

- **Repo:** https://github.com/ihsanibrahim387/portfolio-website
- **Live site:** https://perspective-by-ihsan.vercel.app/

## How to update the site

1. **Upload `index.html`** to Claude. Use the latest version from the website folder or the GitHub repo.
2. **Write the prompt** describing the change. Be specific, for example:
   - "Change the Instagram link to ..."
   - "Add a new project called ... after project 06"
   - "Update the price of the 3D renders gig to $70"
3. **Download the updated HTML** from Claude's reply.
4. **Upload to GitHub via the web UI:**
   - Open the repo, click **Add file → Upload files**
   - Drag in the new `index.html` (keep the exact filename so it replaces the old one)
   - Write a short commit message, e.g. `Update social links`
   - Click **Commit changes**
5. **Check the live site.** Vercel redeploys automatically within about a minute. Hard refresh (Ctrl/Cmd + Shift + R) if you don't see the change.

## Tips

- Keep a backup copy of the working `index.html` before each change.
- The file is large (about 4 MB) because the images are embedded, so uploads can take a moment.
- Ask Claude to change only what you need and to leave everything else untouched.

## Quick edits you can do by hand

Open `index.html` in a text editor and search for:

| What | Search for |
|---|---|
| Social links | `var SOCIAL=` |
| Game discount code | `PERSPECTIVE10` |
| Gig prices | `from $` |
| Fiverr buttons | `Order on Fiverr` / `Message me on Fiverr` |

## Current social links

- Instagram: https://www.instagram.com/_ih_s_a_a_n_
- Behance: https://www.behance.net/ihsanibrahim3
- Pinterest: https://pin.it/UZNZimMUy
