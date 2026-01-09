# Image Converter

## Overview
- The Image Converter is a client-side web application that converts images into different formats directly in the browser
- Supports batch processing, folder uploads, drag-and-drop input, quality adjustment, and optional ZIP output
- All processing is performed locally and no files are uploaded to any server

## Features
- Convert images to WebP, JPEG, PNG, and AVIF
- Batch processing for multiple files or folders
- Drag-and-drop image input
- Adjustable output quality
- Optional inclusion of original files
- ZIP archive output for batch downloads
- Folder structure preserved in ZIP output
- Automatic cancellation of previous processing sessions
- Memory-safe processing with cleanup
- No external backend or API required

## Supported Browsers
- Google Chrome (recommended)
- Microsoft Edge
- Firefox (limited AVIF support depending on version)
- Safari (AVIF support depending on system version)

## File Structure
- `index.html`
- `styles.css`
- `script.js`
- `README.md`

## Usage
1. Open `index.html` in a modern web browser
2. Select images using one of the following methods:
   - Select Folder
   - Select Files
   - Drag and drop images into the drop zone
3. Choose the target output format
4. Adjust the quality slider as needed
5. Enable or disable optional settings:
   - Include Originals
   - ZIP Output
6. Click **Download** to retrieve the processed images

## Processing Notes
- All image processing is done locally in the browser
- No files are uploaded or stored remotely
- Large batches are processed incrementally to avoid freezing
- Changing settings cancels the previous processing session automatically
