# GitHub Notebook Viewer URL Converter

A lightweight, zero-dependency web utility that converts standard GitHub Jupyter Notebook (`blob`) URLs into direct, hex-encoded `notebooks.githubusercontent.com` render URLs.

## Why Use This?

GitHub renders Jupyter Notebooks (`.ipynb`) using an isolated sandboxed iframe hosted at `notebooks.githubusercontent.com`. Generating this direct render link manually requires converting the raw file URL into a UTF-8 hexadecimal string and assembling specific query parameters. This tool automates the entire process locally in your browser.

## Features

- **Instant Conversion:** Converts standard GitHub `blob` links into `raw.githubusercontent.com` URLs, UTF-8 hex strings, and final `notebooks.githubusercontent.com` viewer links.
- **One-Click Copy:** Copy any of the three generated outputs directly to your clipboard.
- **Direct Preview:** Open the rendered notebook immediately in a new tab.
- **100% Client-Side:** Built with vanilla HTML, CSS, and JavaScript-no backend, build tools, or external dependencies required.

## How It Works

Given an input URL:

```text
https://github.com/username/repo/blob/commit_sha/path_to/your_notebook.ipynb

```

## License

This project is open source and available under the [MIT License](LICENSE).
