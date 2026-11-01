# Assignment 12: CSS Grid Layout

## Aim
To understand CSS Grid and create layouts using rows and columns.

## Theory

### 1. CSS Grid
CSS Grid is a two-dimensional layout system that organizes elements into rows and columns.

### 2. Grid Container
Setting `display: grid` creates a grid container. Its direct children become grid items.

### 3. Defining Columns and Rows
- `grid-template-columns`: Defines column sizes.
- `grid-template-rows`: Defines row sizes.
- `gap`: Sets spacing between grid cells.
- `grid-column`: Controls an item's column placement or span.
- `grid-row`: Controls an item's row placement or span.

### 4. Fractional Units
The `fr` unit represents a fraction of the available space in a grid container.

Example:

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
}
```

### 5. Flexbox and Grid
Flexbox is generally suited to one-dimensional arrangements, while Grid is designed for two-dimensional layouts. They can be used together in the same page.

## Tasks
1. Create a grid container.
2. Define rows, columns, and gaps.
3. Arrange content using grid placement properties.

## Conclusion
This assignment demonstrates how CSS Grid creates structured, flexible two-dimensional layouts.