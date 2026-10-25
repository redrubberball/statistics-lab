# Statistics Lab

A collection of free, interactive statistics learning tools suitable for embedding in course pages and online homework.

## Published pages

- `/` — Statistics Lab homepage
- `/normal-curve/` — Standard Normal Curve Explorer

## Publishing (GitHub Pages)

1. Create a **public** GitHub repository named `statistics-lab`.
2. Upload all contents of this folder into the repository root, preserving `normal-curve/index.html`.
3. In the repository, go to **Settings > Pages**, set Source to **Deploy from a branch**, Branch to **main**, Folder to **/(root)**, and click **Save**.
4. Your pages will appear at `https://YOUR-USERNAME.github.io/statistics-lab/` and `https://YOUR-USERNAME.github.io/statistics-lab/normal-curve/`.

## Editing

- Update `normal-curve/index.html` to edit the interactive while retaining the same student-facing URL.
- Update root `index.html` to change the homepage.
- Add future tools as their own folders, each with its own `index.html`.
- During an active class assignment, test changes before publishing them; for major redesigns, preserve a semester-specific version.

## Embedding

Canvas/MyOpenMath HTML example:

```html
<iframe src="https://YOUR-USERNAME.github.io/statistics-lab/normal-curve/" width="100%" height="650" style="border:0;" title="Interactive Standard Normal Curve"></iframe>
```

The embedding platform may filter external iframe code; check in student preview and provide a normal link as backup.

## Data and privacy

The included tool runs in the browser and does not require student accounts. Do not upload student records, private course data, or copyrighted material you do not have rights to share to a public repository.
