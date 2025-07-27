# Blog Website

This repository contains a simple HTML page that acts as the skeleton for a future blog. The page lives at `.github/blog_index_Version4.html` and loads Markdown posts dynamically using the `marked` JavaScript library.

## Serving the page locally

1. From the repository root, launch a small HTTP server:
   ```bash
   python3 -m http.server
   ```
2. Open your browser and navigate to `http://localhost:8000/.github/blog_index_Version4.html`.

The script in the page fetches Markdown files from a `posts` directory and renders them into the `<article>` section. At the moment only a placeholder entry is listed and no markdown files are provided.

## Future plans

The project is at an early stage. Upcoming improvements may include:

- Adding actual blog posts in a `posts/` directory.
- Styling via a `styles.css` file.
- Moving the HTML file to a more appropriate location.
- Expanding the GitHub Actions workflow for automated deployment.

Feel free to fork the repository and adapt it for your own blogging experiments.
