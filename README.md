# Personal Portfolio Website

A responsive personal portfolio built with vanilla HTML, CSS, and JavaScript. It has no build step and no dependencies.

## Run locally

1. Open `index.html` directly in a browser, or serve the folder with a local static server.
2. For example, with VS Code, install the Live Server extension and choose **Open with Live Server** from `index.html`.

A simple alternative with Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Customize

- Replace `Your Name`, the email address, social URLs, and GitHub URLs in `index.html`.
- Update the bio, skills, and project cards with your own content.
- Change colors and layout values in `styles.css` through the variables at the top of the file.
- Replace the page title and description in the `<head>` section for better search previews.

## Deploy to GitHub Pages

1. Create a new GitHub repository, then push this folder to its default branch.
2. In the repository, open **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select your default branch and the `/ (root)` folder, then click **Save**.
5. GitHub will publish the site at `https://yourusername.github.io/repository-name/` after the Pages workflow completes.

Because this is a static site, no build command or server configuration is required.
