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

## Maintaining these public pages

For an update or feedback request, use current GitHub `main` and this README to identify the **actual affected public consent/privacy page**, then check the relevant HTML and live deployed URL where available. Preserve the valid earlier privacy/consent wording and corrections in Git history; fix only an evidenced mistake and verify the actual public-facing consumer before calling it delivered. A commit or Pages configuration instruction alone does not prove that Google accepts the app or that the live pages match.

The general feedback-memory and original-task resumption principle comes from [`resources_materials` Durable Memory policy](https://github.com/workhyun-hash/resources_materials/blob/main/docs/DURABLE_MEMORY_DOCUMENTATION_POLICY.md); this static site does **not** inherit a stock-research Worker scheduler, extra Guard, approval queue or blanket CI. Privacy, client-data and Google platform authorization remain separate constraints.
