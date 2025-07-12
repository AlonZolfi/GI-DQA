# GI-DQA Project Website

This repository contains the website for the GI-DQA (Gradient Inversion of Document Question Answering) project.

## Running Locally

There are several ways to run this website locally:

### Option 1: Using Node.js

If you have Node.js installed:

1. Clone this repository
2. Run the server:
   ```
   node server.js
   ```
3. Open your browser and navigate to: http://localhost:3000/docs/

### Option 2: Using Python

If you prefer Python:

```bash
# Python 3
python -m http.server

# Python 2
python -m SimpleHTTPServer
```

Then open your browser and navigate to: http://localhost:8000/docs/

### Option 3: Using any static file server

You can use any static file server of your choice, just point it to the `docs` directory.

## Deployment

This website is designed to be easily deployed to GitHub Pages:

1. Go to your repository settings
2. Navigate to "Pages" in the sidebar
3. Under "Source", select either:
   - "Deploy from a branch" and choose your main branch
   - Or "GitHub Actions" for more advanced workflows
4. Make sure the root directory is selected (not /docs)
5. Save your changes

### Troubleshooting GitHub Pages 404 Errors

If you're seeing a 404 error on GitHub Pages:

1. Ensure your repository is public
2. Check that GitHub Pages is enabled in repository settings
3. Verify the correct branch is selected as the source
4. Wait a few minutes for changes to propagate
5. Make sure index.html exists in the root or configured directory
6. Check the GitHub Pages URL format: username.github.io/repository-name/
