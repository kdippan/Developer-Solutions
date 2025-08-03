# CSS Animation Generator - Developer Solutions

## Overview

A powerful tool for generating custom CSS animations with real-time previews. Create beautiful animations without writing any code, then simply copy the generated CSS to use in your projects.

## Features

- **15+ Pre-built Animations**: Choose from bounce, fade, slide, rotate, flip, and more
- **Customizable Parameters**:
  - Adjustable duration (0.1-5 seconds)
  - Configurable delay (0-5 seconds)
  - Iteration count (1-3 or infinite)
  - Multiple timing functions (ease, linear, etc.)
- **Real-time Preview**: See animations play as you adjust settings
- **Production-ready CSS**: Clean, formatted output with syntax highlighting
- **One-click Copy**: Easily copy the generated CSS to your clipboard

## How to Use

1. **Select an animation** from the dropdown menu
2. **Adjust the settings**:
   - Set how long the animation should run (duration)
   - Add a delay before the animation starts
   - Choose how many times it should repeat
   - Select the timing function for smoothness
3. **View the live preview** of your animation
4. **Copy the generated CSS** and paste it into your project
5. **Apply the animation class** to your HTML elements

## Example Usage

```css
/* Generated CSS */
@keyframes bounce {
  0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
  40% { transform: translateY(-30px); }
  60% { transform: translateY(-15px); }
}

.bounce-animate {
  animation: bounce 1s ease 0s 1;
}
```

```html
<!-- Apply to your HTML -->
<div class="bounce-animate">This will bounce!</div>
```

## Supported Animations

- Bounce
- Fade
- Slide
- Rotate
- Flip
- Pulse
- Shake
- Swing
- Zoom
- Flash
- Jello
- Wobble
- Tada
- Rubber Band
- Light Speed

## Browser Support

Works in all modern browsers that support CSS animations (Chrome, Firefox, Safari, Edge). The generated code includes standard properties without vendor prefixes for cleaner output.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

MIT License - Free to use in personal and commercial projects

---

**Tip:** For best results, combine these animations with other CSS properties like transforms and transitions for more complex effects.