# Von Aivan De Guzman — Portfolio

A fast, accessible, single-file portfolio site. No build step, no dependencies.

## Customize
1. Open `index.html`.
2. Replace "Your Name", the email, and the GitHub and LinkedIn links.
3. Edit the `PROJECTS`, `JOBS` and `SKILLS` lists in the `<script>` block.
4. Change the colors in the `:root` block at the top of the `<style>`.

## Deploy on GitHub Pages
1. Create a repository and push these files to the `main` branch.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site goes live at `https://<username>.github.io/<repo>/`. Name the repo `<username>.github.io` to use the root URL.

## Features
- Light and dark themes, following the system setting with a manual toggle
- Headline that responds to the cursor (disabled for reduced-motion users)
- Responsive layout, keyboard focus styles, semantic HTML

## License
MIT. See `LICENSE`.

## Adding your images
The work list links to public Google Drive folders. To show images on the site itself:
1. Set each Drive folder to "Anyone with the link can view", or download the files.
2. Export web-sized copies (under 2 MB each) into `assets/<category>/`. GitHub rejects files over 100 MB, and several originals (large PNGs and GIFs) are near or above that.
3. Convert big GIFs to MP4 or WebM to keep pages fast.
