# team78.net

Static website for team78.net. Single `index.html` plus image assets.

## Deployment

Live at [team78.net](https://www.team78.net), hosted on **Netlify** (deploy URL: `fanciful-figolla-7696cf.netlify.app`).

Originally deployed via Netlify Drop (drag-and-drop) on 2025-01-14. This repo was imported from the live Netlify bundle on 2026-04-12 to establish version control and enable git-based deployment.

## Updating

1. Edit files locally
2. `git push origin main`
3. Netlify auto-deploys from the main branch

## DNS

- A records: Netlify edge (`75.2.60.5` plus AWS edges)
- `www` CNAME: `fanciful-figolla-7696cf.netlify.app`
- Email: Outlook 365 (MX `team78-net.mail.protection.outlook.com`), Postmark for transactional
