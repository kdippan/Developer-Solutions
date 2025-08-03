# Developer Solutions - Animation Maker with Tailwind CSS

![Developer Solutions Logo](https://iili.io/Fr4AkZu.png)

A powerful animation generator tool that creates CSS animations using Tailwind CSS classes. Part of the Developer Solutions suite for modern web development.

## Live Demo

🌐 [View Live Demo](https://developersolutions.netlify.app/Animation-Maker-using-Tanwind/)

## Features

🎬 **Animation Controls**
- 6+ animation types (bounce, spin, ping, pulse, fade, slide)
- Customizable duration (100ms to 3000ms)
- Multiple timing functions (linear, ease-in, ease-out, etc.)
- Animation delay options
- Iteration count control (finite or infinite)
- Direction options (normal, reverse, alternate)

🖼️ **Visual Preview**
- Multiple element types (box, circle, text, button)
- Color customization
- Real-time animation preview

💻 **Code Generation**
- HTML with Tailwind classes
- Just the animation classes
- Complete CSS with keyframes
- One-click copy functionality

## Installation

No installation required! Use the live demo or:

1. Clone the repository:
```bash
git clone https://github.com/kdippan/Developer-Solutions.git
```

2. Navigate to the Animation Maker folder:
```bash
cd Developer-Solutions/Animation-Maker-using-Tanwind/
```

3. Open `index.html` in your browser.

## Usage

1. **Select Animation Properties**:
   - Choose animation type from dropdown
   - Adjust duration, timing function, delay, etc.

2. **Customize Preview Element**:
   - Select element type (box, circle, text, or button)
   - Choose color from palette

3. **Apply Animation**:
   - Click "Apply Animation" to see it in action
   - Tweak settings until perfect

4. **Copy Generated Code**:
   - Use the copy buttons to grab HTML, Tailwind classes, or raw CSS
   - Paste into your project

## Examples

### Tailwind Classes Output
```html
<div class="animate-bounce duration-1000 ease-in-out delay-500 infinite"></div>
```

### Custom CSS Output
```css
@keyframes bounce {
  0%, 100% {
    transform: translateY(-25%);
    animation-timing-function: cubic-bezier(0.8,0,1,1);
  }
  50% {
    transform: none;
    animation-timing-function: cubic-bezier(0,0,0.2,1);
  }
}
.animate-bounce {
  animation: bounce 1000ms ease-in-out 500ms infinite;
}
```

## Technologies Used

- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Font Awesome](https://fontawesome.com/) - Icon toolkit
- Vanilla JavaScript - No frameworks or libraries
- Custom CSS animations - For additional effects

## Tailwind CSS CDN

Add this to your project's `<head>` to use the same Tailwind configuration:
```html
<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: {
      extend: {
        animation: {
          'spin-slow': 'spin 3s linear infinite',
          'bounce-slow': 'bounce 2s infinite',
          'pulse-slow': 'pulse 3s infinite',
        }
      }
    }
  }
</script>
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

- [JSON/CSV Converter](https://github.com/kdippan/Developer-Solutions/tree/main/CSV-JSON%20Converter)
- [Lorem Ipsum Generator](https://github.com/kdippan/Developer-Solutions/tree/main/Lorem-Ipsum-Generator)

## Contact

For questions or feedback, please open an issue on GitHub.

---

Made with ❤️ by [Developer Solutions](https://developersolutions.netlify.app/)