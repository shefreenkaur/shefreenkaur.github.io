# Shefreen Kaur — Portfolio

Data analyst portfolio. Built with vanilla HTML/CSS and React (via CDN).

## Deploying to GitHub Pages

### Option A: New repo (recommended)
1. Create a new public GitHub repo — name it `shefreenkaur.github.io` if you want the clean URL, or anything else (e.g. `portfolio`) for a `/portfolio` subdomain URL.
2. Upload all files from this folder, keeping the folder structure intact:
   ```
   index.html
   3dproject.html
   resume.html
   colors_and_type.css
   assets/
     portfolio-3d/
       buildings.png
       character-inside.png
       character-rigging.png
       palace-exterior.png
       palace-interior.png
       village-exterior.png
   ```
3. Go to **Settings → Pages → Source** and set it to `Deploy from a branch` → `main` → `/ (root)`.
4. GitHub will give you a URL like `https://shefreenkaur.github.io` or `https://shefreenkaur.github.io/portfolio` within a minute or two.

### Option B: Existing repo
Same as above, but push to whatever branch your Pages is configured to deploy from.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main portfolio page |
| `3dproject.html` | 3D Village Animation case study |
| `resume.html` | One-page resume (print to PDF from here) |
| `colors_and_type.css` | Design system tokens (fonts, colors, spacing) |
| `assets/portfolio-3d/` | 3D project images |

## Saving the resume as PDF
Open `resume.html` on GitHub Pages and click the **PRINT / SAVE AS PDF** button (or Cmd/Ctrl+P), then choose "Save as PDF" as the destination. The print button hides itself in the output.
