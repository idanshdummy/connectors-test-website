# Connectors Test Website

A simple multi-page website designed for GitHub Pages hosting.

## Pages

- **Home** (`index.html`) - Main landing page
- **Page 1** (`page1.html`) - First additional page
- **Page 2** (`page2.html`) - Second additional page
- **Page 3** (`page3.html`) - Third additional page

Each page contains unique content and an accompanying image.

## Setup for GitHub Pages

1. Push this repository to GitHub
2. Go to your repository settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select the branch you want to use (typically `main` or `master`)
5. Click "Save"
6. Your site will be available at `https://[your-username].github.io/connectors-test-website/`

## Local Development

Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Structure

```
connectors-test-website/
├── index.html          # Homepage
├── page1.html          # Page 1
├── page2.html          # Page 2
├── page3.html          # Page 3
├── styles.css          # Main stylesheet
├── images/             # Image assets
│   ├── home.svg
│   ├── page1.svg
│   ├── page2.svg
│   └── page3.svg
└── README.md           # This file
```

## Features

- Responsive design that works on mobile and desktop
- Clean, modern UI with gradient backgrounds
- Consistent navigation across all pages
- Each page includes a unique image

