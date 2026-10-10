# SHAX — Legal Documents

Public-facing legal and privacy documents for the SHAX Discord bot.

## Files
- `privacy-policy.html` — public Privacy Policy page for GitHub Pages
- `privacy-policy.md` — editable Markdown version
- `terms-of-service.html` — public Terms of Service page
- `terms-of-service.md` — editable Markdown version
- `data-deletion.md` — data access and deletion instructions
- `security.md` — security vulnerability contact instructions

## Contact
- Email: velionmods@gmail.com
- Official Discord: https://discord.gg/shax

## Publish using GitHub Pages
1. Create a public GitHub repository, for example `shax-legal`.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

If your GitHub username is `YOUR-USERNAME` and the repository is `shax-legal`, your pages will usually be:
- `https://YOUR-USERNAME.github.io/shax-legal/privacy-policy.html`
- `https://YOUR-USERNAME.github.io/shax-legal/terms-of-service.html`

Use the actual published Privacy Policy URL in Discord Developer Portal.

## Review before publishing
These documents are templates and must match your real bot implementation. Review and edit:
- The legal identity/name of the operator and any required postal/business information.
- The actual hosting, database, logging, monitoring, and storage providers.
- Which information the bot actually stores and for how long.
- Whether individual users can opt out of any processing.
- Whether stored information and backups are encrypted as required.
- Whether any data is used to train AI or machine-learning models.
- Any international data transfers and safeguards.

Do not claim that users can opt out, data is encrypted, or data is deleted within a specific period unless this is actually implemented and verified. Consider professional legal review, particularly for GDPR compliance.
