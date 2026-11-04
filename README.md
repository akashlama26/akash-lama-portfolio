AKASH LAMA — COMPLETE PORTFOLIO MANAGER

FILES
- index.html: public portfolio website with a live Selected Work section and existing Journal section.
- admin.html: private dashboard for uploads, portfolio items, articles, drafts, publishing, editing and deleting.
- portfolio-manager-setup.sql: one-time Supabase setup for the portfolio table and media storage.

ONE-TIME INSTALLATION
1. Keep a backup of your current GitHub website files.
2. In Supabase, open SQL Editor, paste the complete contents of portfolio-manager-setup.sql, and click Run. This adds a portfolio_items table and a public portfolio-media storage bucket. It does not delete your existing journal_posts table.
3. In your GitHub portfolio repository, replace index.html and admin.html with the two files in this package. Keep any other assets already in your repository.
4. Netlify should deploy automatically after the GitHub commit.
5. Open https://incomparable-salmiakki-8afc44.netlify.app/admin.html and sign in with akashlama26@gmail.com using the emailed magic link.

AFTER INSTALLATION
Use the admin page to upload images and PDFs (up to 20 MB each), add YouTube/Vimeo links for video, add screenwriting and project descriptions, and publish or save drafts. Published portfolio items appear in the Selected Work section; published articles appear in Journal. No repeated SQL or GitHub editing is needed for ordinary content updates.

VIDEO NOTE
Use an unlisted YouTube or Vimeo URL for videos. The dashboard embeds the video; it does not upload large video files to Supabase.

SECURITY / STORAGE
The dashboard allows only the configured admin email. Uploaded images/PDFs are stored in a public bucket so the public portfolio can display them; do not upload private or confidential documents. Supabase storage usage and bandwidth are subject to your Supabase plan.

