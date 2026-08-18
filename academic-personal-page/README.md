# Simple academic personal page

This site uses only a few files:

- `index.html` contains the words and page structure.
- `style.css` controls colors, spacing, and appearance.
- `images/profile-placeholder.svg` is the temporary profile image.

No installation or build command is needed.

## Preview on your computer

The easiest method is to double-click `index.html`. It will open in your web browser.

You can also open a terminal in this folder and run:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000> in your browser. Stop the server with `Control+C`.

## Publish with GitHub Pages

1. On GitHub, create a public repository named `YOUR-USERNAME.github.io`. Replace `YOUR-USERNAME` with your actual GitHub username.
2. Upload `index.html` and `style.css` to the top level of that repository.
3. Open the repository's **Settings**, then select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then click **Save**.
6. After a few minutes, visit `https://YOUR-USERNAME.github.io`.

## First changes to make

Open `index.html` in a text editor and:

1. Add your portrait to the `images` folder. A square image works best.
2. Change `images/profile-placeholder.svg` in `index.html` to your filename, such as `images/yijue.jpg`.
3. Change the photo's `alt` text from `Profile placeholder for Yijue Wang` to `Portrait of Yijue Wang`.
4. Replace the placeholder Google Scholar URL with your profile URL.
5. Replace the placeholder LinkedIn URL with your profile URL.
6. Check names, author order, and publication titles against the final papers.
7. Add paper links later by wrapping a title in a link, for example:

```html
<p class="paper-title">
  <a href="https://doi.org/your-paper-link">Your paper title</a>
</p>
```

Save the file and refresh your browser after each change. If you make a mistake, GitHub keeps the history, so you can restore an earlier version.

## A tiny HTML guide

- `<h1>...</h1>` is the main heading.
- `<h2>...</h2>` is a section heading.
- `<p>...</p>` is a paragraph.
- `<a href="...">...</a>` is a link.
- `<strong>...</strong>` makes important text bold.
- `<!-- ... -->` is a note for you that visitors do not see.

Keep the closing tags (such as `</p>` and `</a>`) when editing.
