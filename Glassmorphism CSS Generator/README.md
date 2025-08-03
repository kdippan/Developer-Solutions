# Glassmorphism CSS Generator

## Overview

The Glassmorphism CSS Generator is a web-based tool that helps designers and developers create beautiful "glass" UI effects with customizable parameters. This tool generates ready-to-use CSS code for implementing the popular glassmorphism design trend in your projects.

## Features

- **Real-time Preview**: See your glass effect update instantly as you adjust settings
- **Customizable Parameters**:
  - Blur intensity (0-20px)
  - Transparency level (0-100%)
  - Border thickness (0-5px)
  - Glass color (color picker)
  - Shadow opacity (0-100%)
- **CSS Generation**: Automatically outputs production-ready CSS code
- **Copy Functionality**: One-click copy for easy integration into your projects
- **Responsive Design**: Works on all device sizes
- **Visual Feedback**: Clear indicators when CSS is copied

## How to Use

1. Adjust the sliders to customize your glass effect:
   - **Blur Amount**: Controls the blur intensity behind the element
   - **Transparency**: Sets the opacity of the glass panel
   - **Border Size**: Adds a subtle white border to enhance the effect
   - **Glass Color**: Choose the base color for your glass panel
   - **Shadow Opacity**: Adjusts the darkness of the drop shadow

2. View the live preview updating in real-time

3. Copy the generated CSS code with the "Copy" button

4. Paste the CSS into your project and apply the `glass-effect` class to your elements

## Technical Details

- Built with pure HTML, CSS, and JavaScript (no frameworks)
- Uses modern CSS properties:
  - `backdrop-filter` for the blur effect
  - `rgba()` colors for transparency
  - CSS variables for easy customization
- Responsive design using CSS Grid and Flexbox
- Clipboard API for copying CSS to clipboard

## Browser Support

The generated CSS works in all modern browsers that support:
- `backdrop-filter` (Chrome 76+, Firefox 103+, Safari 9+)
- CSS variables
- The tool itself works in all modern browsers

## Example Output

```css
.glass-effect {
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    background-color: rgba(255, 255, 255, 0.3);
    border: 1px solid rgba(255, 255, 255, 0.15);
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.3);
    border-radius: 16px;
}
```

## License

This project is open source under the MIT License.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

---

**Note:** For best results, apply glassmorphism effects to elements over vibrant backgrounds or images. The effect works by blurring and lightening whatever content is behind the element.