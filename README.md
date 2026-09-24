# Von Aivan De Guzman — Portfolio

A fast, accessible portfolio site. No build step, no dependencies.

## Customize
1. Open `index.html`.
2. Edit the `WORK`, `JOBS` and `SKILLS` lists in the `<script>` block.
3. Change the colors in the `:root` block at the top of the `<style>`.

## Work dropdowns
Each category in `WORK` reads its files from the `assets` folder, named `<category>-<number>`. Images are compressed WebP files with a small `-th` thumbnail, and videos are short MP4 files. To add a piece, put the files in `assets` using the same naming (`skillo-34.webp`, `skillo-34-th.webp`) and add an entry to that category's `items`.

Keep images under about 2 MB and videos under about 6 MB. GitHub rejects any single file over 100 MB.

## Deploy on GitHub Pages
1. Push all files, including the `assets` folder, to the `main` branch.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site goes live at `https://<username>.github.io/<repo>/`.

## Features
- Light and dark themes, following the system setting with a manual toggle
- Headline that responds to the cursor (disabled for reduced-motion users)
- Dropdown galleries with a full-size preview for images and videos
- Responsive layout, keyboard focus styles, semantic HTML

## License
MIT. See `LICENSE`.
