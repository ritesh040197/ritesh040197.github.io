# Ritesh Yadav — Portfolio

A one-page portfolio built with plain HTML and CSS. It needs no build step.

## Files
```
index.html                     the whole site
assets/metabit-poster.jpg      photo of the research poster
assets/og-banner.jpg           preview image shown when the link is shared
assets/Ritesh_Yadav_Resume.pdf resume that the "Resume" button opens
```

## Publish on GitHub Pages (about 5 minutes)

1. On GitHub, create a new **public** repository named exactly **`ritesh040197.github.io`**.
2. Upload `index.html`, `README.md` and the `assets/` folder:
   **Add file → Upload files**, drag them in, then **Commit**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main**, and folder to **/(root)**, then click **Save**.
4. After a minute or two, the site is live at **https://ritesh040197.github.io**.

Or use git:
```bash
git init && git add . && git commit -m "Portfolio"
git branch -M main
git remote add origin https://github.com/ritesh040197/ritesh040197.github.io.git
git push -u origin main
```

## Things to update
- **Project links:** the two project cards link to their repos. Update the links if you rename a repo.
- **Resume:** replace `assets/Ritesh_Yadav_Resume.pdf` with a newer version, keeping the same file name.
- **Colors:** edit the `--accent` values at the top of the `<style>` block.
