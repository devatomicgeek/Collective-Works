# Collective Works v4.8 — Framer Reference Edition

Static GitHub Pages portfolio with a separate local Studio editor.

## Publish the public website
1. Upload `index.html`, `studio.html`, `content.json`, and the `assets` folder to the root of a GitHub repository.
2. Enable GitHub Pages under Settings > Pages, deploying from the root of your main branch.
3. Visit your GitHub Pages URL. The public site reads `content.json` on every page load.

## Add content
1. Open `studio.html` on the **same origin and browser** where you have your existing Studio data. Use a full backup/import if moving to a new origin.
2. Create entries, paste public image URLs (Google Drive links may fail to embed even when shared), and set entries to Published.
3. Open Media / Backup > **DOWNLOAD PUBLISHED CONTENT**.
4. Upload the downloaded `content.json` to the repository root, replacing the existing file.
5. Wait for Pages to deploy, then refresh the public website.

## Important limitations
- Studio uses browser localStorage for editing and drafts. This is **not** secure, cross-device content management. Its client-side PIN is not authentication. Do not upload private content to the repository.
- Public visitors do **not** need your browser localStorage; they see the published JSON snapshot.
- Local image uploads are blocked from the public export. Use externally hosted image URLs instead.
- Google Drive does not guarantee stable public image embedding; check images in an incognito window.
- GitHub Pages cannot write files to the repository. Publishing requires the manual upload described above.
- Full Studio backups can contain drafts; never upload them to your public repository.
- The YouTube embed restrictions (including error 153) depend on YouTube/browser conditions.
