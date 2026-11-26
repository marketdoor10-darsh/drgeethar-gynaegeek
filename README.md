# Dr. Geetha R – Website

This folder contains the static website prepared for GitHub Pages.

## Publish using GitHub Pages

1. Create a new **public** repository on GitHub (for example, `dr-geetha-website`).
2. Upload **all files in this folder** to the repository's top/root level. Make sure `index.html` is at the top level, not inside another folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the GitHub Pages deployment to finish. The website URL will appear in Settings → Pages.

## Important checks before launch

- The appointment form currently has no form-processing service connected. It will display, but submissions will not reach the clinic until a form backend or WhatsApp/email workflow is configured.
- Confirm the doctor's phone number, email, clinic address, qualifications, services, photos, and all medical claims before publishing.
- This page loads Tailwind CSS and fonts from external CDNs, so visitors need an internet connection for those resources.
- GitHub Pages provides HTTPS automatically once the site is published.

## Files

- `index.html` – website homepage (required by GitHub Pages).
