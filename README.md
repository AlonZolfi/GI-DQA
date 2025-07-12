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

This website is designed to be easily deployed to GitHub Pages. Simply push to your repository and enable GitHub Pages in your repository settings.