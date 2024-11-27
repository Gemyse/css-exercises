# CSS Notes for Beginners: Text Styling

## Fonts

### Font Family

- **Property:** `font-family`
- **Usage:** Defines the font of an element.
- **Example:**
  ```css
  body {
    font-family: Arial, sans-serif;
  }
  ```
- **Best Practice:** Always define a fallback font (e.g., `sans-serif`, `serif`, `monospace`) for compatibility.

### Font Size

- **Property:** `font-size`
- **Usage:** Sets the size of the text.
- **Units:**
  - `px` (pixels)
  - `em` (relative to parent element)
  - `rem` (relative to root element)
  - `%` (relative to parent element)
- **Example:**
  ```css
  p {
    font-size: 16px;
  }
  ```
- **Best Practice:** Use `rem` for scalable and accessible designs.

### Font Weight

- **Property:** `font-weight`
- **Usage:** Specifies the thickness of the font.
- **Values:**
  - `normal`
  - `bold`
  - Numeric values (e.g., `100` to `900`)
- **Example:**
  ```css
  h1 {
    font-weight: bold;
  }
  ```
- **Best Practice:** Use numeric values for finer control.

### Font Style

- **Property:** `font-style`
- **Usage:** Sets the style of the font (e.g., italic, normal).
- **Example:**
  ```css
  em {
    font-style: italic;
  }
  ```

## Text Decoration

- **Property:** `text-decoration`
- **Usage:** Adds decoration to text (e.g., underline, overline).
- **Values:**
  - `none`
  - `underline`
  - `line-through`
  - `overline`
- **Example:**
  ```css
  a {
    text-decoration: none;
  }
  ```

## Text Transform

- **Property:** `text-transform`
- **Usage:** Controls capitalization of text.
- **Values:**
  - `none`
  - `capitalize`
  - `uppercase`
  - `lowercase`
- **Example:**
  ```css
  h2 {
    text-transform: uppercase;
  }
  ```

## Text Alignment

- **Property:** `text-align`
- **Usage:** Aligns text horizontally.
- **Values:**
  - `left`
  - `right`
  - `center`
  - `justify`
- **Example:**
  ```css
  p {
    text-align: justify;
  }
  ```

## Line Height

- **Property:** `line-height`
- **Usage:** Sets the spacing between lines of text.
- **Example:**
  ```css
  p {
    line-height: 1.5;
  }
  ```
- **Best Practice:** Use relative values (e.g., `1.5`) for better scalability.

## Letter Spacing

- **Property:** `letter-spacing`
- **Usage:** Adjusts space between characters.
- **Example:**
  ```css
  h1 {
    letter-spacing: 2px;
  }
  ```

## Color

- **Property:** `color`
- **Usage:** Sets the color of the text.
- **Values:**
  - Named colors (e.g., `red`, `blue`)
  - Hex values (e.g., `#ff0000`)
  - RGB values (e.g., `rgb(255, 0, 0)`)
  - HSL values (e.g., `hsl(0, 100%, 50%)`)
- **Example:**
  ```css
  p {
    color: #333;
  }
  ```
- **Best Practice:** Use contrast-friendly colors for accessibility.

## Background and Backdrop Fonts

### Background Color

- **Property:** `background-color`
- **Usage:** Sets the background color of an element.
- **Example:**
  ```css
  body {
    background-color: #f5f5f5;
  }
  ```

### Backdrop Filter (Advanced)

- **Property:** `backdrop-filter`
- **Usage:** Applies effects to the area behind an element.
- **Example:**
  ```css
  .frosted {
    backdrop-filter: blur(10px);
  }
  ```
- **Best Practice:** Use sparingly for performance reasons.

## Best Practices Summary

1. Always provide fallback fonts in `font-family` for better compatibility.
2. Use relative units like `rem` and `em` for scalability and accessibility.
3. Maintain sufficient contrast between text and background for readability.
4. Test your text styles on multiple devices and browsers to ensure consistency.
5. Avoid excessive use of decorative styles like `italic` or `underline` unless necessary for emphasis.
