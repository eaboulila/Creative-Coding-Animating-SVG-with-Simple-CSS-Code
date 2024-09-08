# Creative Coding: Animating SVG with Simple CSS Code

Welcome to the **Creative Coding: Animating SVG with Simple CSS Code** project repository! This repository contains project files, code snippets, and resources related to the Skillshare class.

## Course Overview

This course explores how to animate SVG files using CSS. By the end of the course, you'll be able to create visually engaging and interactive web elements using scalable vector graphics (SVG) and CSS animations.

## Project Instructions

For the class project:
1. Select one vector graphic in SVG format from the provided exercises package (or use your own SVG artwork).
2. Apply your own CSS animations to the chosen SVG. You can decide which aspects of the SVG to animate—whether it's color, scale, rotation, or more complex animations.
3. Share your work by:
    - Uploading code snippets or project files
    - Adding screenshots or video demonstrations of your animations
    - Providing a link to a CodePen or live demo (optional)

## How to Use This Repository

- **Project Files**: All SVG and CSS files used in the project are stored in the `/projects` directory.
- **Code Snippets**: Specific CSS animation code snippets are available in the `/snippets` directory.

### Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/eaboulila/creative-coding-svg-css.git
    ```

2. Navigate into the project directory:

    ```bash
    cd creative-coding-svg-css
    ```

3. Open the HTML file in your preferred browser to view the animations.

### Example Animation Code

```css
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

svg path {
  animation: spin 2s linear infinite;
}
```

## Resources

- [Skillshare Course](https://www.skillshare.com/en/classes/creative-coding-animating-svg-with-simple-css-code/1735436116)
- [MDN Web Docs - CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)
- [MDN Web Docs - SVG](https://developer.mozilla.org/en-US/docs/Web/SVG)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
