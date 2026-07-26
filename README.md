# ShasthyaSetu

ShasthyaSetu is a web-based health report analysis app that helps users review medical documents more easily. The interface is designed for a simple workflow: upload or scan a report, extract text with OCR, and analyze the information in a structured way.

## What this project does

- Provides a modern web interface for report analysis
- Supports OCR-based text extraction from uploaded images
- Offers a bilingual-friendly experience for Bangla and English users
- Helps users review health-related document information more quickly

## Project structure

- index.html - Main app entry point and UI
- css/ - Stylesheets
- js/ - JavaScript logic
- assets/ - Images and other static assets

## Getting started

Because this is a static web project, you can run it locally without a build step.

### Option 1: Open directly in a browser

- Open index.html in your browser.

### Option 2: Serve it locally

If you want a more reliable local experience, run a simple web server from the project folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- The app uses CDN-based libraries for OCR and icons, so an internet connection is required for full functionality.
- For the best experience, use a modern browser such as Chrome or Edge.

## Future improvements

Possible enhancements include:

- Better report parsing and summarization
- Support for more document formats
- Improved data validation and user feedback
- Export options for reports
