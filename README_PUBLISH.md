# Publish TubeLite TV on GitHub Pages

This folder is ready for GitHub Pages. It contains no API key, OAuth client ID, OAuth secret, or other TubeLite app credential.

## 1. Replace placeholders

Before publishing, edit `privacy.html` and `terms.html` and replace:

- `[OPERATOR]`
- `[EMAIL]`
- `[ADDRESS]`
- `[OPERATOR / EMAIL]`

Do not place your YouTube API key, OAuth client secret, or access/refresh tokens anywhere in this website.

## 2. Create a GitHub repository

Recommended repository name: `tubelite-tv`

Upload the contents of this folder to the repository root:

- `index.html`
- `privacy.html`
- `terms.html`
- `styles.css`
- `assets/`

## 3. Enable GitHub Pages

In the GitHub repository:

1. Open **Settings**.
2. Open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**.
5. Save.

GitHub will provide an HTTPS URL similar to:

`https://YOUR-USERNAME.github.io/tubelite-tv/`

Use that HTTPS address as the **Primary Access URL** in the YouTube API audit/quota form.

## 4. How to answer accessibility

While the APK is still private testing, the website can be public while the actual API Client remains non-public. If the form separately asks whether the API Client itself is publicly accessible, answer according to the app's actual distribution status.

## 5. Optional reviewer APK

If Google requests direct access to the application, create a private or controlled reviewer download rather than putting secrets in the website. A GitHub Release can host a signed review APK if you are comfortable making that binary accessible.
