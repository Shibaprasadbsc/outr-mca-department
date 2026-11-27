# OUTR MCA Department Website — Question 8

This folder contains your existing Question 7 website, prepared for static hosting and basic SEO.

## Files
- `index.html` — complete website (HTML, CSS and JavaScript)
- `robots.txt` — crawler instructions
- `sitemap.xml` — one-page sitemap template
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing

## IMPORTANT: before publishing
1. Open `sitemap.xml`.
2. Replace `YOUR-GITHUB-USERNAME` with your exact GitHub username.
3. If you rename the repository from `outr-mca-department`, also change that part of the URL in `sitemap.xml`.
4. Open `robots.txt`, remove the `#` at the start of the Sitemap line, and make sure its URL matches the sitemap URL exactly.
5. In `index.html`, the website is described as a student academic demonstration project. Do not present it as the university's official website unless the university has authorized that claim.

## Publish using GitHub Pages
1. Sign in at https://github.com/ or create a free account.
2. Click **New repository**.
3. Name it exactly `outr-mca-department`.
4. Choose **Public**, then create the repository.
5. Open the new repository and click **Add file → Upload files**.
6. Extract this ZIP on your computer. Upload the CONTENTS of the `outr-mca-department` folder (not the ZIP itself). Ensure `index.html`, `robots.txt`, `sitemap.xml`, and `.nojekyll` appear at the repository root.
7. Add a commit message such as `Publish MCA department website`, then click **Commit changes**.
8. Open **Settings → Pages**.
9. Under **Build and deployment**, choose **Deploy from a branch**.
10. Select branch **main**, folder **/(root)**, then click **Save**.
11. Wait for the Pages deployment to finish. Open the URL shown in **Settings → Pages**. For this repository name it normally follows:
    `https://YOUR-GITHUB-USERNAME.github.io/outr-mca-department/`
12. Test the published URL on a phone and another browser. Check navigation, buttons, layout, images/logo, and all sections.

## Basic SEO after publishing
1. Replace the username placeholder in `sitemap.xml` and `robots.txt` with the actual live URL and commit the changes.
2. Open Google Search Console: https://search.google.com/search-console/
3. Add your published URL as a **URL-prefix property** and complete one of the verification methods offered by Google. Use the HTML file or meta-tag method if available; follow the exact instructions Search Console gives you.
4. In Search Console, open **Sitemaps**, enter `sitemap.xml`, and submit it.
5. Use **URL Inspection** to request indexing for the home page.
6. Keep the title and description accurate, use meaningful headings, and update the page with real, verified department information.

A sitemap submission is only a discovery hint; it does not guarantee indexing or a particular Google ranking.

## Important functionality limitations in the supplied Question 7 code
The site is a static front-end project. The contact form currently validates the fields and displays a message; it does not send an email. Login/signup only validates the form in the browser; it does not create accounts or authenticate users. Event registration only displays a demonstration message. Do not collect real passwords or personal information with this demo until a secure backend/authentication service is connected.

The page contains sample faculty, notices, gallery placeholders and demonstration text. Replace these with accurate content and images you are allowed to publish.

## If the website does not appear
- Confirm `index.html` is at the repository root, not inside an extra nested folder.
- Confirm Pages is set to `main` and `/(root)`.
- Check the **Actions** tab for a failed Pages deployment.
- Wait a few minutes, then refresh the Pages URL.
- After changing files, commit the changes; GitHub Pages redeploys from the selected source.
