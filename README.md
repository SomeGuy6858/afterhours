# After Hours — Legal pages

Static **Terms of Service** and **Privacy Policy** pages for
[After Hours](https://github.com/SomeGuy6858/afterhours), the dating app for
people who'd rather stay in together. These are designed to be hosted for free
on **GitHub Pages**.

## Files

| File          | Purpose                                              |
| ------------- | ---------------------------------------------------- |
| `index.html`  | Landing page linking to both documents              |
| `terms.html`  | Terms of Service                                     |
| `privacy.html`| Privacy Policy                                       |
| `styles.css`  | Shared styling (on-brand dark / violet + cyan theme) |
| `.nojekyll`   | Tells GitHub Pages to serve the HTML as-is           |

No build step — these are plain HTML/CSS.

## Enable GitHub Pages

1. Merge this branch into `main` (or whichever branch you point Pages at).
2. On GitHub, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick the branch (e.g. `main`) and the **`/ (root)`** folder, then **Save**.
5. After a minute, your pages are live at:
   - `https://someguy6858.github.io/afterhours/`
   - `https://someguy6858.github.io/afterhours/terms.html`
   - `https://someguy6858.github.io/afterhours/privacy.html`

(If you set up a custom domain, add a `CNAME` file with your domain.)

## Before you publish — customize these

These pages are a solid, app-specific starting point, but they are **not legal
advice**. Before relying on them, please:

- Replace the **governing law / venue** placeholder in `terms.html`
  (section 13) with your actual jurisdiction.
- Confirm the **legal entity name** and **contact email**
  (`info@piedmontsys.com` is used throughout) are correct.
- Have both documents **reviewed by a qualified lawyer**, and make sure they
  meet the requirements that apply to you (e.g. GDPR, UK GDPR, CCPA/CPRA) and
  the policy/privacy-label requirements of the **Apple App Store** and
  **Google Play**.

The "Last updated" date is set to **June 18, 2026** — update it whenever you
change the content.
