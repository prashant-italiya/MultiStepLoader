# MultiStepLoader

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

A lightweight, customizable multi-step loading animation for web applications built with vanilla JavaScript. This component provides a visually appealing way to show users the progress of background operations.

## Demo

You can try the live demo by simply downloading the `loader.html` file and opening it in your browser. No server setup required!

**[Try the live demo](https://codepen.io/multisteploader/pen/demo)** (Hosted on CodePen)

*Note: For the CodePen demo link to work, you would need to create a CodePen account and upload your loader there. Alternatively, you can host it on GitHub Pages after publishing this repository.*

## Features

- 📱 Fully responsive design
- 🎨 Easy to customize (colors, animations, steps)
- 🔧 No dependencies required
- ⚡ Lightweight (<5KB minified)
- 🌐 Compatible with all modern browsers
- 🎭 Smooth animations using CSS transitions

## Installation

### Option 1: Direct Download

Download `loader.html` from this repository and include it in your project.

### Option 2: CDN (Coming Soon)

```html
<script src="https://cdn.example.com/multisteploader.min.js"></script>
<link rel="stylesheet" href="https://cdn.example.com/multisteploader.min.css">
```

## Usage

1. Include the CSS and JavaScript in your HTML file:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
<script src="path/to/multisteploader.js"></script>
```

2. Add the container element to your HTML:

```html
<div class="loading-steps-container" id="loadingSteps">
    <div class="blur-overlay"></div>
    <div class="steps-list" id="stepsList">
        <!-- Steps will be added dynamically -->
    </div>
</div>

<button class="start-button" id="startButton">Start Process</button>
```

3. Initialize with custom steps:

```javascript
const steps = [
    'Initializing application...',
    'Loading user data...',
    'Fetching configurations...',
    'Setting up workspace...',
    'Ready to start!'
];

// Initialize the loader
// More customization options coming soon!
```

## Customization

You can customize the appearance by modifying the CSS variables:

```css
:root {
  --loader-primary-color: #007bff;
  --loader-success-color: #28a745;
  --loader-background: rgba(255, 255, 255, 0.8);
  --loader-text-color: #333;
  --loader-icon-color: #666;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Check out our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Font Awesome](https://fontawesome.com/) for the icons