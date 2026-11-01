# Assignment 13: Responsive Web Design

## Aim
To understand responsive design and adapt web pages to different screen sizes.

## Theory

### 1. Responsive Design
Responsive web design allows a page to adjust to different viewport sizes and devices while maintaining readability and usability.

### 2. Viewport Meta Tag
The viewport meta tag helps mobile browsers display a page using the device's viewport width.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### 3. Media Queries
CSS media queries apply styles when specified conditions are satisfied, such as a viewport width being below a breakpoint.

Example:

```css
@media (max-width: 600px) {
    .container {
        grid-template-columns: 1fr;
    }
}
```

### 4. Flexible Layouts
Relative units, flexible images, Flexbox, and Grid help layouts adapt to different screen dimensions.

### 5. Mobile-First Design
A mobile-first approach begins with styles for smaller screens and progressively adds layout enhancements for larger screens.

## Tasks
1. Create a responsive page layout.
2. Apply media queries for different viewport sizes.
3. Test the page at multiple screen widths.

## Conclusion
This assignment demonstrates how responsive design techniques improve the experience across desktop, tablet, and mobile devices.