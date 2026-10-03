# Xu Renjie Academic Website — GitHub Desktop update

This package updates the root `index.html` used by GitHub Pages. The name and clickable email in the header use the same font size.

## Apply the update

1. In GitHub Desktop, choose **Repository → Show in Explorer**. This opens the exact local repository folder currently selected.
2. Extract this ZIP into that folder. The ZIP entries are at the repository root (not inside an extra wrapper folder). Choose **Replace files in destination** if asked. Do not remove the hidden `.git` folder.
3. Return to GitHub Desktop. You should see changes, including `index.html`. If it still says `0 changed files`, check that you extracted into the folder opened by **Show in Explorer**.
4. Commit the changes to `main`, then click **Push origin**.

The `contents/` and `static/` directories are included to match the existing repository layout. The current homepage is self-contained in `index.html`.
