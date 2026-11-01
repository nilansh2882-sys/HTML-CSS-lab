# Assignment 09: CSS Variables and Typography

## Aim
To understand CSS custom properties and typography styling.

## Theory

### 1. CSS Custom Properties
CSS custom properties, commonly called CSS variables, store reusable values.

Example:

```css
:root {
    --primary-color: #2563eb;
}

h1 {
    color: var(--primary-color);
}
```

Custom properties are declared using a name beginning with `--` and accessed using `var()`.

### 2. The Root Selector
The `:root` pseudo-class selects the document's root element. It is commonly used to define variables that should be available throughout a page.

### 3. Typography
Typography controls how text appears. Important properties include:
- `font-family`: Typeface selection.
- `font-size`: Text size.
- `font-weight`: Text thickness.
- `line-height`: Spacing between lines.
- `letter-spacing`: Spacing between characters.
- `text-transform`: Text capitalization.

### 4. Maintainability
Reusable variables make it easier to maintain a consistent design and update shared values across a website.

## Tasks
1. Declare and use CSS custom properties.
2. Apply typography styles to headings and paragraphs.
3. Create a consistent visual theme.

## Conclusion
This assignment demonstrates how CSS variables and typography improve design consistency and readability.