# Developer Solutions - SVG Path Animator

![Developer Solutions Logo](https://iili.io/Fr4AkZu.png)

A professional tool for creating and customizing SVG path animations with a visual interface. Part of the Developer Solutions suite for modern web development.

## Live Demo

🌐 [View Live Demo](https://developersolutions.netlify.app/svg-path-animator/)

## Features

🖋️ **Path Editing**
- Direct SVG path data input
- Preset paths (curve, heart, spiral)
- Real-time path preview
- Stroke width and color customization

🎬 **Animation Types**
- Path drawing (stroke-dashoffset)
- Path morphing (shape changing)
- Dash offset animation
- Path following (for objects)

⚙️ **Animation Controls**
- Adjustable duration (0.5-5 seconds)
- Multiple easing functions
- Play/pause/stop functionality
- Real-time preview

💻 **Code Generation**
- SVG with SMIL animations
- JavaScript Web Animations API
- GSAP implementation code
- One-click copy for all formats

## Installation

No installation required! Use the live demo or:

1. Clone the repository:
```bash
git clone https://github.com/kdippan/Developer-Solutions.git
```

2. Navigate to the SVG Path Animator folder:
```bash
cd Developer-Solutions/SVG-Path-Animator/
```

3. Open `svg-animator.html` in your browser.

## Usage Guide

### 1. Creating Your Path
- Type SVG path data directly into the input field
- Use preset buttons for quick shapes:
  - **Curve**: Smooth bezier curve
  - **Heart**: Heart shape path
  - **Spiral**: Circular spiral path
- Or start with a blank path by clicking "Clear"

### 2. Choosing Animation
Select from four animation types:
1. **Draw Path**: Animate the path being drawn
2. **Morph Path**: Transform into another shape (provide target path)
3. **Dash Offset**: Create marching ants/dashed line effects
4. **Follow Path**: Make objects follow along the path

### 3. Customizing Animation
- **Duration**: Set animation length (0.5-5 seconds)
- **Easing**: Choose from 5 easing functions
- **Stroke**: Adjust width (1-10px) and color
- **Playback**: Use play/pause/stop buttons to test

### 4. Exporting Code
Copy ready-to-use code in three formats:
1. **SVG with SMIL**: For simple inline animations
2. **JavaScript**: Using Web Animations API
3. **GSAP**: For advanced animations with GreenSock

## CDNs Used

This tool uses the following CDN resources:

```html
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- GSAP Animation Library -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.4/gsap.min.js"></script>

<!-- SVG Path Properties Calculator -->
<script src="https://cdn.jsdelivr.net/npm/svg-path-properties@1.0.4/dist/svg-path-properties.min.js"></script>

<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

## Examples

### SVG with SMIL Animation
```html
<svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <path d="M10 10 C20 20, 40 20, 50 10..."
    stroke="#3b82f6"
    stroke-width="3"
    fill="none">
    <animate 
      attributeName="stroke-dashoffset"
      from="250"
      to="0"
      dur="2s"
      fill="freeze" />
  </path>
</svg>
```

### GSAP Morph Animation
```javascript
gsap.to("#path", {
  duration: 2,
  ease: "power1.inOut",
  morphSVG: "M10 50 Q25 10 40 50 T70 50"
});
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Related Projects

- [Animation Maker](https://github.com/kdippan/Developer-Solutions/tree/main/Animation-Maker)
- [JSON/CSV Converter](https://github.com/kdippan/Developer-Solutions/tree/main/CSV-JSON%20Converter)
- [Lorem Ipsum Generator](https://github.com/kdippan/Developer-Solutions/tree/main/Lorem-Ipsum-Generator)

## Contact

For questions or feedback, please open an issue on GitHub.

---

Made with ❤️ by [Developer Solutions](https://developersolutions.netlify.app/)