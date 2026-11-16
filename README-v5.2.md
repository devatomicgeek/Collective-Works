# Collective Works v5.2

Based on v5.1. Changes:
- THE SELECTS: 1080 x 1080 square image guidance, preview, validation and public square framing.
- Responsive hero: headline and photo separated; mobile supporting text aligned in one row.
- Removed local image upload controls from content editor and About page; use public image URLs.
- Studio ABOUT PHOTO renamed THE PROFILE, with editable introduction, heading, greeting, title, biography and Google Drive photo URL.
- Public About page reads published Profile settings from content.json.

## Deploy
1. Export a FULL BACKUP in the existing Studio before updating.
2. Replace `index.html` and `studio.html` in GitHub Pages repository; do not replace your existing `content.json`.
3. In Studio, edit THE PROFILE and THE SELECTS, then use Media / Backup to download published `content.json` and commit it to GitHub.
4. Existing published issues with non-square photos remain available; replace their photos with 1080 x 1080 images to meet new validation.

**Caution:** Studio uses browser localStorage and a client-side PIN, not secure authentication. Google Drive images must be publicly accessible. Local-only image data cannot be exported for publishing.
