# Horologium — Daily Routines & Work Habits Atlas

A self-contained static web application showcasing the documented 24-hour routines, work habits, quotes, and source citations of **250 historical and modern figures** across writers, scientists, philosophers, military leaders, athletes, tech founders, and artists.

## What's Included
- `index.html` — Complete self-contained application (HTML, Tailwind CSS, vanilla JS, and all 250 audited schedules).
- `_headers` — Security and cache headers for Cloudflare Pages.
- `wrangler.jsonc` — Ready-to-use config if deploying via Cloudflare Wrangler CLI.
- `.gitignore` — Clean Git defaults.

## Deploy via GitHub + Cloudflare Pages (No Build Step)
1. **Unzip** this archive on your computer.
2. **Create a new repository** on GitHub and upload all files from the unzipped folder (`index.html`, `_headers`, `wrangler.jsonc`, `README.md`, `.gitignore`) to the root of your `main` branch.
3. In the **Cloudflare Dashboard**, go to **Workers & Pages → Create → Pages → Connect to Git**.
4. Select your new GitHub repository and use these build settings:
   - **Framework preset:** `None`
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` *(or leave empty)*
5. Click **Save and Deploy**. Your site will be live on `*.pages.dev` within seconds.

## Optional: Deploy via Wrangler CLI
```bash
npx wrangler deploy
```
