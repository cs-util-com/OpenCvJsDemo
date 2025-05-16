# Image Sharpness Detector

A web application that uses OpenCV.js to analyze and measure the sharpness of uploaded images.

## Demo

Try the application online: [https://cs-util-com.github.io/OpenCvJsDemo/](https://cs-util-com.github.io/OpenCvJsDemo/)

## Features

- Drag-and-drop interface for easy image uploading
- Real-time sharpness analysis using Laplacian variance method
- Side-by-side display of original and processed grayscale images
- Numerical sharpness score calculation
- Responsive design built with Tailwind CSS

## How It Works

1. The application loads OpenCV.js from the official CDN
2. Users upload images via drag-and-drop or file selection
3. The uploaded image is processed using the following algorithm:
   - Convert the image to grayscale
   - Apply Laplacian operator to detect edges
   - Calculate the variance of the Laplacian (a measure of sharpness)
   - Display the sharpness score (higher values indicate sharper images)

## Technical Details

- Built with pure JavaScript and HTML
- Uses OpenCV.js 4.9.0 for image processing
- Styled with Tailwind CSS
- No server-side processing (all computation happens in the browser)

## Browser Compatibility

Works in modern browsers that support:
- WebAssembly (for OpenCV.js)
- HTML5 File API
- ES6+ JavaScript

## License

See the LICENSE file for details.
