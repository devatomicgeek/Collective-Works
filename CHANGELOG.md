# Changelog

## v4.8 — Framer Reference Edition
- Public pages now load published portfolio, Life Log, homepage hero, and About portrait from repository `content.json` instead of localStorage.
- Added Studio **DOWNLOAD PUBLISHED CONTENT** export for GitHub Pages.
- Export excludes drafts and rejects embedded local image uploads.
- Preserved the existing Studio editing workflow, local backups, design, and v4.7 Life Log video layout.
- Updated version labels and GitHub publishing instructions.
- Studio PIN remains a temporary client-side gate, not secure authentication.

## v4.9
- Studio Overview: removed the general New Entry button; create entries from their respective sections.
- Studio editor: Article, Creative Design and Photography show image and text fields; Video and Videography show YouTube and text fields plus optional cover thumbnail. Hidden inputs retain their values when switching types.
- Video and Videography publishing requires a valid YouTube URL or video ID. Drafts may be incomplete.
- Public video popups continue to omit cover thumbnails and galleries; article and photo popups retain galleries.
- Existing browser storage and manual GitHub content.json publishing are unchanged.
