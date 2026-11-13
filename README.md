# Or Akeriv — Personal Website

A lightweight English-language academic portfolio website, ready for GitHub Pages.

## Preview on your computer

Open `index.html` in your browser. No installation required.

## Publish to GitHub Pages

1. Log into GitHub as `akerivor1`.
2. Create a **public** repository named **`akerivor1.github.io`** (exactly).
3. Upload `index.html`, `styles.css`, `script.js` and the whole `assets` folder to the root of the repository. You can drag and drop files in **Add file → Upload files**. Preserve the `assets/` subfolder.
4. Commit the upload.
5. In repository **Settings → Pages**, choose **Deploy from a branch**, then branch **main** and folder **/(root)**. Save.
6. When deployment finishes, visit **https://akerivor1.github.io/**.

Do not upload private research materials or unpublished papers without permission.

## Replace the portrait

Put your photo in `assets` as `portrait.jpg` and change this line in `index.html`:

`<img src="assets/portrait-placeholder.svg" alt="Placeholder for Or Akeriv's portrait"/>`

to:

`<img src="assets/portrait.jpg" alt="Portrait of Or Akeriv"/>`

Also delete the sentence beginning with `Portrait placeholder` from `index.html`.

## Optional CV

After you approve the English CV for public release, upload it as `assets/Or_Akeriv_CV.pdf` and add a link in the social links section:

`<a href="assets/Or_Akeriv_CV.pdf" target="_blank" rel="noopener">CV ↗</a>`

## Updating content

Edit `index.html`. Style lives in `styles.css`. Mobile navigation logic is in `script.js`.

## Before publishing

Confirm every biographical claim, project description, skills list, and external link. The descriptions are an initial draft based on prior profile discussions, not a verified publication record.
