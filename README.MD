# CSS Notes for Beginners

Welcome to the **CSS Notes for Beginners** repository! This project is designed as a step-by-step guide to help you understand the fundamentals of Cascading Style Sheets (CSS) and how to apply them to your HTML documents.

## Project Structure

The project is organized into levels to represent a progressive learning path:

### [Level 0](./Level%200/) - CSS Basics & Internal Styling
- **Concepts Covered:**
    - Understanding the basic CSS syntax.
    - **Inline CSS:** Applying styles directly to HTML elements using the `style` attribute.
    - **Internal CSS:** Using the `<style>` block within the `<head>` section of an HTML file.
    - Basic selectors (e.g., `h1`, `p`) and properties like `color`.
- **Quick Tip:** In VS Code, type `!` and press `Enter` to quickly generate a boilerplate HTML structure.

### Level 1 - External Styling & Specificity
- **Concepts Covered:**
    - **External CSS:** Linking a separate `.css` file to your HTML document using the `<link>` tag.
    - **CSS Priority (Specificity):** Understanding the order in which styles are applied:
        1. Inline styles (highest priority)
        2. Internal styles
        3. External styles (lowest priority)
    - **File Linking:** Learn how to use `<link rel="stylesheet" href="style.css">` to keep your code clean and organized. 

### Level 2 - Colors & Backgrounds
- **Concepts Covered:**
    - **RGB Color System:** Understanding `rgb()` values for colors.
    - **Hex Color System:** Understanding hexadecimal color codes (`#RRGGBB`).
    - `background-color` property: Setting the background color of elements.
    - `color` property: Setting the foreground color of text.

### Level 3 - Advanced Selectors
- **Concepts Covered:**
    - **Universal Selector (`*`):** Targeting all elements.
    - **Type Selector:** (e.g., `p`, `h1`, `div`) - Targeting all elements of a specific type.
    - **Class Selector (`.my-class`):** Targeting elements with a specific class.
    - **ID Selector (`#my-id`):** Targeting a unique element with a specific ID.

### Level 4 - Text Styling (Part 1)
- **Concepts Covered:**
    - `text-align` property: Aligning text (left, right, center, justify, start, end).
    - `text-decoration` property: Adding lines to text (none, underline, overline, line-through, blink).
    - Customizing text decoration: `text-decoration-color`, `text-decoration-style`, `text-decoration-thickness` (with browser compatibility notes).
    - `font-weight` property: Setting the boldness of text (normal, bold, bolder, lighter, 100-900).
    - `font-family` property: Specifying font faces and fallback options.

### Level 5 - Text Styling (Part 2)
- **Concepts Covered:**
    - `font-size` property: Controlling the size of text.
    - `line-height` property: Adjusting the spacing between lines of text.
    - `text-transform` property: Changing text case (uppercase, lowercase, capitalize).

## How to Use This Repository

1.  **Explore Level 0:** Open the `index.html` file in the Level 0 folder to see how internal styles work. Experiment by changing the colors in the `<style>` block.
2.  **Progress to Level 1:** Move to the Level 1 folder to see how to separate your styles into an external file.
3.  **Continue through Levels 2-5:** Each level introduces new CSS properties and concepts. Review the `style.css` and `index.html` files in each respective folder to understand the examples.
4.  **Practice:** Try adding new HTML elements and styling them using the different methods and properties described in each level.

## Getting Started with CSS

To get started, you only need a text editor (like VS Code) and a web browser.

1. Create an `index.html` file.
2. Add your content.
3. Apply styles using one of the three methods:
   - **Inline:** `<h1 style="color: blue;">`
   - **Internal:** Inside `<style>` tags in the `<head>`.
   - **External:** In a separate `.css` file.

Happy Coding! 🚀