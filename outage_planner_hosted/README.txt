Outage Planner (host-ready)

Two zero-code hosting options:

A) Netlify Drop (fastest)
1) Go to https://app.netlify.com/drop
2) Drag the entire 'site' folder onto the page.
3) Netlify gives you a public https:// URL immediately.
4) Open that URL: everything will be fully interactive.

B) GitHub Pages (company-friendly)
1) Create a new GitHub repo (public or internal).
2) Upload the contents of the 'site' folder (index.html and README.txt) to the repo root.
3) In the repo Settings → Pages, set "Deploy from a branch", branch = main, folder = /root.
4) GitHub publishes it at https://<your-username>.github.io/<repo>/

Notes
- This is a single-file web app (index.html). No build step, no dependencies.
- The app stores edits in your browser's localStorage per user (Eric will have his own saved state).
- Export month as printable HTML to print or save as PDF.
- You can import/export placements via CSV in the Tools panel.

If you need the app preloaded with a 2025 schedule, provide a placements CSV with columns:
year,month,date,slot,title,bg,font
e.g. 2025,1,2025-01-15,AM,QUAD RUN,#b1a0c7,#000000
Then use 'Import placements CSV' in the app.
