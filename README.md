# Private Media Site

A simple password-protected static website hosted on GitHub Pages.

- Background image with two buttons linking to OneDrive Audio and Videos folders.
- Client-side password protection (password: `password_goes_here`).

## Files

- `index.html` – the password-protected page
- `background.jpg` – the beach background image

## How to deploy to GitHub Pages

1. Create a new repository on GitHub (https://github.com/new).
   - Name it something like `private-media` (or `yourusername.github.io` for a root site).
   - Make the repository **Public**.
   - Do **not** initialize it with a README, .gitignore, or license.

2. Upload the files:
   - On the empty repository page, click **uploading an existing file**.
   - Drag and drop (or select) both `index.html` and `background.jpg`.
   - Click **Commit changes**.

3. Enable GitHub Pages:
   - Go to the repository **Settings** → **Pages** (left sidebar).
   - Under **Build and deployment** → **Source**, select **Deploy from a branch**.
   - Branch: `main` (or `master`), Folder: `/ (root)`.
   - Click **Save**.

4. Wait 1–2 minutes, then open your site at:
   ```
   https://YOUR-USERNAME.github.io/REPO-NAME/
   ```
   (Replace `YOUR-USERNAME` and `REPO-NAME` with your actual values.)

## Password

The site password is: **password_goes_here**

Once entered correctly, it stays unlocked for the current browser session.

## Notes

- This is client-side protection only (suitable for casual privacy, not highly sensitive data).
- The OneDrive links open in a new tab.
- You can change the password later by editing the SHA-256 hash in `index.html` (or ask for a new version).

## Optional customizations

Want a different title, button labels, colors, or longer password memory (localStorage instead of sessionStorage)? Just let me know.
