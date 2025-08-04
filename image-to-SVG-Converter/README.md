# Developer Solutions - Image to SVG Converter

![Developer Solutions Logo](https://iili.io/Fr4AkZu.png)

A professional tool for converting images to SVG format with ImgBB API integration. Part of the Developer Solutions suite for web developers.

## Live Demo

🌐 [View Live Demo](https://developersolutions.netlify.app/image-to-svg-converter/)

## Features

### 🖼️ Image Upload & Hosting
- **Drag & Drop Interface**: Easily upload images by dragging or browsing
- **ImgBB API Integration**: Automatic image hosting on reliable CDN
- **Multiple Formats**: Supports JPG, PNG, GIF, and WEBP (up to 5MB)
- **Upload Progress**: Real-time progress bar during uploads

### ✨ SVG Generation
- **Automatic SVG Creation**: Generates clean SVG code with `<image>` tag
- **Custom Dimensions**: Set custom width and height
- **Aspect Ratio Control**: Preserve original proportions or stretch to fit
- **ViewBox Optimization**: Automatically calculates proper viewBox

### 👁️ Interactive Preview
- **Image Preview**: See your uploaded image before conversion
- **SVG Preview**: Visualize the generated SVG output
- **Responsive Design**: Works perfectly on all device sizes

### 💻 Developer-Friendly Output
- **Syntax Highlighting**: Beautifully formatted SVG code
- **One-Click Copy**: Copy SVG code or embeddable HTML
- **Download Option**: Save SVG file directly
- **Hosted Image URL**: Get permanent image URL from ImgBB

## Installation

No installation required! Use the live demo or:

1. Clone the repository:
```bash
git clone https://github.com/kdippan/Developer-Solutions.git
```

2. Navigate to the Image-To-SVG-Converter folder:
```bash
cd Developer-Solutions/Image-To-SVG-Converter/
```

3. Open `index.html` in your browser.

## Usage Guide

### 1. Upload Your Image
- Drag and drop an image file onto the upload zone
- Or click to browse your files
- Supported formats: JPG, PNG, GIF, WEBP (max 5MB)

### 2. Set SVG Options
- **Width/Height**: Set custom dimensions (leave blank for original)
- **Preserve Aspect Ratio**: Keep original proportions (recommended)
- The tool automatically calculates the optimal viewBox

### 3. Generate & Use SVG
- Click "Generate SVG Code" to create your SVG
- **Copy SVG Code**: One-click copy of the generated SVG
- **Download SVG**: Save as .svg file
- **Copy Embed Code**: Get HTML-ready embed snippet
- **Image URL**: Permanent hosted URL from ImgBB

## API Integration

This tool uses the [ImgBB API](https://api.imgbb.com/) with:

- **API Key**: Included in client-side code
- **Rate Limits**: Standard ImgBB limits apply
- **Data Retention**: Images hosted indefinitely
- **Privacy**: Only image file is sent to ImgBB

## Code Examples

### Generated SVG Output
```svg
<svg xmlns="http://www.w3.org/2000/svg" width="500" height="400" preserveAspectRatio="xMidYMid meet" viewBox="0 0 800 600">
  <image href="https://i.ibb.co/example.jpg" width="100%" height="100%" preserveAspectRatio="xMidYMid meet"/>
</svg>
```

### Embeddable HTML
```html
<div class="svg-container">
  <svg xmlns="http://www.w3.org/2000/svg" width="500" height="400" viewBox="0 0 800 600">
    <image href="https://i.ibb.co/example.jpg" width="100%" height="100%"/>
  </svg>
</div>
```

## CDNs Used

```html
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Highlight.js -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.7.0/styles/atom-one-dark.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.7.0/highlight.min.js"></script>

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

## Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Related Projects

- [3D CSS Transform Playground](https://github.com/kdippan/Developer-Solutions/tree/main/3D-Transform-Playground)
- [Image to Base64 Converter](https://github.com/kdippan/Developer-Solutions/tree/main/Image-Base64-Converter)
- [Animation Maker](https://github.com/kdippan/Developer-Solutions/tree/main/Animation-Maker)

## Support

For questions or issues, please [open an issue](https://github.com/kdippan/Developer-Solutions/issues).

---

Made with ❤️ by [Developer Solutions](https://developersolutions.netlify.app/)