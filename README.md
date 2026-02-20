# The Haber Process Site

If you found this folder in Google Drive and want to view the site locally, follow these steps.

## 1. Download the folder correctly

- Download the whole folder, not just `haber.html`.
- Keep the `images` folder where it is.
- Extract the contents of the folder

## 2. Open the site (quickest way)

- Double-click `haber.html`.
- It should open in your default browser.

## 3. How to navigate

- Use the `Next` and `Back` buttons on each page.
- Use `Restart` on the final page to return to the intro.

## 5. Better local preview (recommended)

If animations/assets do not load as expected, run a local server:

```powershell
cd path\to\electrochem_media_project
python -m http.server 8000
```

Then open:

`http://localhost:8000/haber.html`

## Troubleshooting

- If images are missing, confirm the `images` folder is present and not renamed.
- If text looks odd, try Chrome or Edge.
- If nothing opens, right-click `haber.html` and choose `Open with` your browser.
