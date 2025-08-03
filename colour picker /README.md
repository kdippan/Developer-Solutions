# Developer Solutions - Advanced Color Picker Tool

## Overview

The Advanced Color Picker is a comprehensive tool for designers and developers that provides multiple ways to select, analyze, and work with colors. It includes a visual color picker with support for various color formats (HEX, RGB, HSL, CMYK) and an image color extraction feature that generates palettes from uploaded images.

## Features

### Color Picker
- Interactive color selection canvas
- Real-time color preview
- Multiple color format outputs:
  - HEX (#RRGGBB)
  - RGB (rgb(R, G, B))
  - HSL (hsl(H, S%, L%))
  - CMYK (cmyk(C%, M%, Y%, K%))
- One-click copy for HEX and RGB values

### Image Color Extractor
- Upload images via drag & drop or file browser
- Extract dominant colors from images
- Generate color palette swatches
- Click swatches to copy color values
- Clear/reset functionality

## How to Use

### Color Picker
1. Click anywhere on the color gradient canvas to select a color
2. View the selected color in the preview box
3. See the color values in all supported formats
4. Click "Copy HEX" or "Copy RGB" to copy the values to clipboard

### Image Color Extractor
1. Drag & drop an image or click to browse files
2. View the uploaded image preview
3. Click "Extract Colors" to generate a color palette
4. Click any color swatch to copy its values to the color picker
5. Use "Clear" to reset the image and palette

## Technical Details

### Color Conversions
The tool performs real-time conversions between color spaces:
- RGB to HEX
- RGB to HSL
- RGB to CMYK

### Image Processing
When extracting colors from images:
1. The image is drawn to a canvas element
2. Pixel data is analyzed to identify dominant colors
3. Colors are sorted by frequency
4. Top 10 colors are displayed as swatches

### Technologies Used
- HTML5 Canvas for color picker
- FileReader API for image uploads
- Clipboard API for copying color values
- Vanilla JavaScript (no external dependencies)

## Installation

No installation required! This is a client-side web application that runs entirely in the browser. Simply open the HTML file in any modern web browser.

## Browser Support

The tool should work in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge
- Opera

Note: Some features may have limited support in older browsers.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is open source under the MIT License. See the LICENSE file for details.

## About Developer Solutions

Developer Solutions is a collection of free, open-source tools designed to make developers' lives easier. Visit our [GitHub repository](https://github.com/kdippan/Developer-Solutions) to explore more tools.

---

**Note:** This tool is client-side only - no data is sent to any server. All processing happens in your browser for maximum privacy and security.