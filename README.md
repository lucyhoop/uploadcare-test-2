# Uploadcare Ad Uploader

This project integrates Uploadcare's File Uploader with custom validation to ensure uploaded ads meet specific criteria.

## Validation Criteria

- **File Formats**: GIF, JPG, PNG
- **Maximum File Size**: ≤ 500 KB
- **Required Dimensions**:
  - 300x250
  - 728x90
  - 300x600
  - 160x600
  - 320x50
  - 320x480

If an uploaded file doesn't meet these specifications, the upload is rejected, and an error message is displayed.

## Setup Instructions

1. Replace `YOUR_PUBLIC_KEY` in `index.html` with your actual Uploadcare public key.
2. Open `index.html` in a web browser to test the uploader.

## Deployment

You can deploy this project using GitHub Pages or any static site hosting service.

## License

This project is licensed under the MIT License.
