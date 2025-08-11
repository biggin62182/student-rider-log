# Student Rider Log (Static HTML App)

This is a single-file web app for recording weekly rider logs and printing weekly/monthly PDFs. It stores data **locally** in each browser (no server).

## Deploy on GitHub Pages (free)

1. **Create a repo**
   - Go to GitHub → New repository → name it: `student-rider-log` (public is fine).

2. **Upload files**
   - Add these files to the repo root (top level):
     - `index.html` (the app)
     - `qr.html` (optional QR flyer)
     - `.nojekyll` (empty file to prevent Jekyll processing)
   - Commit the changes.

3. **Enable Pages**
   - Repo **Settings** → **Pages**.
   - Under "Build and deployment", set **Source** to **Deploy from a branch**.
   - Set **Branch** to **main** and **/ (root)**. Click **Save**.
   - Wait ~1–2 minutes. Your site will appear at:
     - `https://<your-username>.github.io/student-rider-log/`

4. **Share it**
   - Send that link to drivers. They can open it on any modern browser (Chrome, Safari, Firefox, Edge), desktop or mobile.
   - Optional flyer: open `.../qr.html` to generate a printable QR code.

### Data & privacy
- Entries are saved to the browser’s **localStorage** on each device. They’re not synced anywhere.
- To move data between devices/browsers, use **Export** on the old device and **Import…** on the new one.
- Incognito/Private windows may clear local storage—prefer a normal window.

### Updating the app
- Replace `index.html` in the repo (commit to main). Changes are live within a minute.
- If someone sees an old version, ask them to hard refresh:
  - Windows: `Ctrl+F5` (or `Shift+Reload`)
  - Mac: `Cmd+Shift+R`
