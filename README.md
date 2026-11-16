# Chess website for GitHub Pages

This folder is a static website. It runs Stockfish 19 in the browser; it does not need Node.js or a server process.

## Publish with GitHub Desktop

The Stockfish WebAssembly file is about 99 MB. GitHub's web uploader has a 25 MB per-file limit, so upload this folder with GitHub Desktop (or Git), not by dragging it into github.com.

1. Install and sign in to GitHub Desktop.
2. Create a new GitHub repository and choose a local folder.
3. Copy the **contents** of this folder into the repository's top level, so `index.html` is at the top level.
4. In GitHub Desktop, commit the files and choose **Publish repository**.
5. On github.com, open the repository's **Settings → Pages**. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
6. Open the Pages URL shown there. The first engine start downloads about 95 MB to the browser.

The opening database and Stockfish assets are included. The site still shows the engine's best two lines by default, updates recommendations as you move, and lets you change how many lines are shown.
