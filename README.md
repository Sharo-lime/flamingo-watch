# Flamingo Watch

A single-page website by Saul about flamingos and the threats they face. Sections (My story, Threats, Facts, Gallery, Species) switch without reloading, and every page has its own link such as `index.html#threats`.

## Files
- `index.html` has all the page content and the small scripts for navigation, the range map, the population chart and the quiz.
- `styles.css` has all the styling.
- `images/` has the six gallery photos (`flamingo-1.jpg` to `flamingo-6.jpg`).

Keep these together in one folder, because `index.html` loads `styles.css` and the photos by name.

## Run it in VS Code
1. Open this folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension, then right-click `index.html` and choose "Open with Live Server".

## Put it on GitHub
1. Create a new repository on github.com (for example `flamingo-watch`).
2. In the VS Code terminal, run:
   ```
   git init
   git add .
   git commit -m "Flamingo Watch"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/flamingo-watch.git
   git push -u origin main
   ```
3. On GitHub, open Settings > Pages, choose the `main` branch and the root folder, and save. Your site will be live at `https://YOUR-USERNAME.github.io/flamingo-watch/`.
4. Optional: in `index.html`, find the commented `og:image` line near the top, fill in your real address and remove the comment markers so shared links show a preview photo.

## Photo credits
Each gallery photo has a caption in `index.html` (search for "Photo credit"). If you know a photographer or source, add the name there.

## Keeping facts current
Conservation statuses and population numbers come from IUCN and BirdLife International figures and change over time. Re-check them at iucnredlist.org now and then.
