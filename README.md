# GitHub Backup Manager — OAuth information pages

This **Public** repository hosts only the static Google OAuth consent information for a **personal-use desktop backup tool**. The actual backup manager and backup files are NOT hosted here.

## GitHub Pages setup
1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source: Deploy from a branch**; choose **main** and **/(root)**; click **Save**.
3. Wait for deployment, then verify BOTH live HTTPS addresses:
   - https://workhyun-hash.github.io/github-backup-oauth-info/
   - https://workhyun-hash.github.io/github-backup-oauth-info/privacy.html
4. In **Google Auth Platform → Branding**, use the live URLs as Application home page and Application privacy policy link. Add `workhyun-hash.github.io` under Authorized domains if accepted; follow any domain ownership checks required by Google.
5. In **Audience**, retry **Publish app** after completing Branding. Publishing does not guarantee Google verification.

No runtime JavaScript, analytics, client credentials, API tokens, backup passwords, source backups, or GitHub private data belongs in this repository. Standard GitHub Pages deployment may use GitHub's Pages build infrastructure, but the private manager's CI/runner is separate.
