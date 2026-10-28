STUDYFLOW — ADVANCED PREMIUM STUDENT PLANNER

Features
- Starts with the original 7 subjects and 22 college tasks.
- Add as many subjects and tasks as your device storage reasonably supports.
- Rename subjects; deleting asks whether to delete tasks, keep them uncategorized, or cancel.
- Deadlines, priorities, notes, task completion, search, filters and sorting.
- Dashboard statistics, subject progress, light/dark mode.
- JSON backup and restore.
- Local browser storage and offline caching after first successful online load.

PUBLISH TO GITHUB PAGES
1. Download and unzip this project.
2. Open your repository: raki12545-source/Student-planner-for-diploma-.
3. Keep a copy of the current repository files first. If your current planner has tasks you need to keep, use its Backup feature before replacing anything. This new version uses its own storage key, so existing app data will not automatically transfer.
4. Upload the files from this folder to the repository root, replacing index.html, manifest.json, and service-worker.js, and adding/replacing icon-192.png and icon-512.png. README.txt is included too.
5. Commit changes to the main branch. GitHub Pages should redeploy automatically.
6. Open the site online and refresh. If an old version remains, close the installed app and clear the site's cached data in Chrome, then reopen online.

DATA SAFETY
Tasks are stored locally in this browser on this device. They do not automatically sync to another phone or account. Use Backup regularly. Importing a backup replaces current local data after confirmation.

Keep index.html, manifest.json, service-worker.js, and icon files together in the published root. GitHub Pages uses HTTPS, which is required for service-worker offline support.
