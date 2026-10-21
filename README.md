# Meerab Jamshaid — Premium Portfolio

A responsive, warm editorial-style portfolio built with HTML, CSS and vanilla JavaScript.

## Included

- Responsive homepage, about, education, skills, services, projects, experience, certificates and contact sections
- Light/dark theme toggle
- Project category filters and editable project cards
- Owner workspace for profile edits, project entries, certificates, CV and files
- Real file selection, preview where supported, download, category changes and delete controls
- JSON content export/import
- Email contact form that opens a prefilled email draft
- Keyboard focus styles and reduced-motion support

## Run it locally

1. Extract the ZIP.
2. Open the `meerab-portfolio` folder.
3. Double-click `index.html` to view it in your browser.

For the most reliable local preview, use VS Code:
1. Open the folder in VS Code.
2. Install the **Live Server** extension if you don't already have it.
3. Right-click `index.html` and choose **Open with Live Server**.

No npm install or build step is required.

## Edit your content

1. Open the site.
2. Click **Owner area** in the top-right corner.
3. Use Profile, Projects, Files & CV, Certificates, and Backup tabs.
4. Changes save to this browser's local storage.

The owner area is a convenience editing panel, **not a secure login**. Do not treat it as private on a shared computer. Anyone with access to this browser can open it.

## Important storage limitation

This starter uses `localStorage` in your browser. Uploaded files are converted to data URLs and stored on this device/browser only. They are **not uploaded to a cloud server**, will not automatically appear on another device, and may be lost if browser site data is cleared. Browser storage is limited; use small files and keep external backups. The JSON backup exports text/content data but does not bundle uploaded files. Download important files separately.

Do not upload sensitive identity documents into a public portfolio or shared computer. The starter does not have real authentication, a database, server-side file storage, or privacy permissions.

## Publish with GitHub Pages

GitHub Pages hosts static files. It is suitable for the public portfolio display, but it does not provide private file uploads or a secure owner dashboard backend.

1. Sign in to GitHub and create a new repository, e.g. `meerab-portfolio`.
2. Extract this ZIP and upload `index.html`, `styles.css`, `app.js`, and `README.md` to the repository root (not the ZIP itself).
3. Open repository **Settings → Pages**.
4. Under build/deployment, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to provide your public site URL.
7. Open the URL on desktop and mobile and test every section.

You can also use Netlify or Vercel to host the static site. Static hosting still will not add cloud file uploads or secure editing automatically.

## If you want secure cloud uploads later

A production version needs a backend or managed service, for example Supabase (database + Storage + Authentication) or Firebase (database/storage + Authentication). Configure access policies so only your authenticated account can edit private content. Keep private files in a private bucket and generate temporary signed URLs when needed. Never put administrator passwords or service-role keys in frontend JavaScript.

## Before publishing checklist

- [ ] Replace or upload your real profile photo.
- [ ] Review your professional title and biography.
- [ ] Verify degree titles, dates, board and equivalence statements.
- [ ] Upload your final CV and verified certificates.
- [ ] Add real project descriptions, screenshots, demo links and repositories.
- [ ] Remove any information you do not want public.
- [ ] Test dark/light mode and mobile navigation.
- [ ] Test contact form (it opens your email app; it does not send by itself).
- [ ] Keep a backup of uploaded files and exported portfolio JSON.
- [ ] Remember that browser-local edits do not update the deployed website for other visitors.

## Notes

- Starter content avoids invented clients, testimonials, achievements and proficiency percentages.
- The photo and CV have dedicated controls. The owner workspace is intentionally simple and browser-local.
- For public content that needs to update across devices, migrate the data layer to a database and cloud storage with authentication.
