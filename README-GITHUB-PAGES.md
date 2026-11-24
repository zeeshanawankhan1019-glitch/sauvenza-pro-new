# Sauvenza Official Website (`sauvenza.github.io`)

Official product documentation, privacy policy, developer profile, and disclaimer for **Sauvenza — Crash-Proof Tab & Session Manager (v1.2.1)**.

## How to Deploy on GitHub Pages ($0 Forever) & Verify in Google Search Console

1. **Create Repository:** Create a public GitHub repository named `sauvenza.github.io` (or `<your-username>.github.io`).
2. **Upload Files:** Upload all files from this folder (`index.html`, `privacy.html`, `developers.html`, `disclaimer.html`, `404.html`, `styles.css`, `sitemap.xml`, `robots.txt`, `llms.txt`, and the `assets/` folder) to the root of the `main` branch.
   - *Note:* If your URL is `https://<your-username>.github.io/sauvenza/` instead of `https://sauvenza.github.io/`, do a quick find-and-replace of `https://sauvenza.github.io` with your exact GitHub Pages URL across the HTML/XML/TXT files.
3. **Enable GitHub Pages:** Open **Repository Settings → Pages → Build and deployment**, choose **Deploy from a branch** → `main` / `(root)`, and click **Save**.
4. **Verify in Google Search Console (GSC):**
   - Open [Google Search Console](https://search.google.com/search-console) using the **same Google account** as your Chrome Web Store Developer Dashboard.
   - Click **Add Property → URL prefix** and enter `https://sauvenza.github.io/`.
   - Choose **HTML file** (upload the `googleXXXX.html` file to your repo root) or **HTML tag** (paste the `<meta>` tag inside `<head>` of `index.html`) and click **Verify**.
   - In GSC, open **Sitemaps** and submit `sitemap.xml`.
5. **Link on Chrome Web Store Developer Dashboard:**
   - Open **Store listing → Additional fields → Official URL** and select `https://sauvenza.github.io/` from the dropdown.
   - Open **Privacy** tab and set your Privacy Policy URL to `https://sauvenza.github.io/privacy.html`.
