# HTML & CSS

## Everyday build Layouts with CSS Grid - 12 Column Grid 



### Fonts poppins

Ex

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap');

font-family: 'Poppins', sans-serif;
```
- main img { ... }
- grid-column: span 6;: This property makes the image element span across 6 columns in the grid. In a grid with 12 columns, this would make the image occupy half the available grid width.

- width: 100%;: The image will take up the full width of the grid columns it spans. This ensures that the image scales to fit within the grid area.

- border-radius: 15px;: This property rounds the corners of the image with a radius of 15 pixels, giving it a softer, more polished look.


- main .welcome { ... }
```css
grid-column: 8 / span 5;
```

- : This property places the .welcome element starting at the 8th column and makes it span 5 columns. This means the .welcome element begins at column 8 and extends through column 12 (8th to 12th column).