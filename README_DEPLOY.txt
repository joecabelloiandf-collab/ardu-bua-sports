ARDÚ BUA SPORTS — GITHUB + CLOUDFLARE PAGES PREVIEW PACKAGE

This is a repackaging of the previously approved Ardú Bua website files; the website content and design are unchanged.

GITHUB UPLOAD
1. Unzip this file on your computer.
2. Visit https://github.com/joecabelloiandf-collab/ardu-bua-sports
3. Select Add file > Upload files (or the initial upload link if repository is empty).
4. Upload the THREE files inside this ZIP (not the ZIP itself): index.html, _redirects, robots.txt.
5. Commit the files to the 'main' branch. Ensure index.html sits at the root of the repository.

CLOUDFLARE PAGES
1. In https://dash.cloudflare.com/ open Workers & Pages > Create > Pages > Connect to Git.
2. Select the GitHub repository joecabelloiandf-collab/ardu-bua-sports.
3. Project name: ardu-bua-sports (if available)
4. Production branch: main
5. Framework preset: None
6. Build command: leave empty
7. Build output directory: / (project root; use '.' if your UI requires a relative directory)
8. Deploy. Cloudflare assigns an available pages.dev subdomain.

NOTES
- This is the earlier website prototype intended for a preview deployment, not a final production launch.
- Check and configure the contact form before making a public launch; in this version it displays a demo message rather than transmitting enquiries.
- Confirm all contact details, privacy/legal links and copy before launch.
- Hosting on Cloudflare Pages is separate from registering a custom domain.
