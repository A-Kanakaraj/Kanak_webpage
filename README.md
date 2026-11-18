# Kanakaraj Arangasamy — personal website

A single-page static site, ready for GitHub Pages. No build step.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site (HTML, CSS and a few lines of JS in one file) |
| `Kanakaraj_CV.pdf` | CV download linked from the page |
| `Kanakaraj_CV.docx` | Word version of the CV |
| `photo.jpg` | Your portrait (replace with a higher-resolution one any time, same filename) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish on GitHub Pages (about 5 minutes)

1. Sign in to GitHub and create a **new public repository** named exactly
   `<your-username>.github.io` (for example `kanakaraj-a.github.io`).
   Don't add a README, licence or .gitignore.
2. On the empty repository page click **uploading an existing file**, drag in
   every file from this folder (including `.nojekyll`), and click **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment* set
   *Source* = **Deploy from a branch**, *Branch* = **main** / **(root)**, then **Save**.
4. Wait a minute or two. The site is live at `https://<your-username>.github.io/`.

Updating later: edit `index.html` on GitHub (pencil icon) or upload a replacement
file; the site refreshes within a minute.

## Edit the content

Everything is plain HTML in `index.html`. Search for the section ids
`#about`, `#expertise`, `#experience`, `#research`, `#awards`, `#contact`.
Text wrapped in `<span class="ph">[...]</span>` is a placeholder that still
needs your input.
