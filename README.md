---
# Recreate Layout Using HTML and CSS (Media Query)

This project involves recreating a specific layout using HTML and CSS, with a focus on responsive design through media queries. The layout includes several frames with particular content, styled accurately to reflect the layout, colors, and font styles of the provided image.

## Project Overview

- **HTML**: Defines the structure of the webpage.
- **CSS**: Styles the webpage, including layout, colors, fonts, and responsive behavior via media queries.
- **Media Queries**: Ensure the design is responsive, adapting to different screen sizes.

## Project Files

- **index.html**: Contains the HTML structure.
- **style.css**: Contains the CSS for styling the webpage, including media queries.
- **assets/**: (Optional) Directory for any images, fonts, or other assets used in the project.

## Layout Description

The layout consists of multiple frames, each with specific content:

- **Frame 1:** Placeholder or default content.
- **Frame 2:** Placeholder or default content.
- **Frame 3:** Contains the text **"Assignment"** and **"Full Stack Web Development"**.
- **Frame 4:** Placeholder or default content.
- **Frame 5:** Placeholder or default content.

The layout is designed to be responsive, adjusting to different screen sizes using media queries.

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/repository-name.git
   ```

2. Open the `index.html` file in a web browser to view the layout:

   ```bash
   open index.html
   ```

   or

   ```bash
   start index.html
   ```

3. The webpage should display the recreated layout with accurate colors, fonts, and frame positioning.

## HTML Structure

The HTML file is structured with `div` elements representing each frame:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recreated Layout</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="frame frame1">Frame 1</div>
    <div class="frame frame2">Frame 2</div>
    <div class="frame frame3">
        <h1>Assignment</h1>
        <p>Full Stack Web Development</p>
    </div>
    <div class="frame frame4">Frame 4</div>
    <div class="frame frame5">Frame 5</div>
</body>
</html>
```

## CSS Styling

The CSS file defines the styles for the layout:

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    height: 100vh;
}

.frame {
    display: flex;
    align-items: center;
    justify-content: center;
    border: 1px solid #000;
    background-color: #f4f4f4;
    font-size: 1.2em;
}

.frame3 h1 {
    margin: 0;
    font-size: 1.5em;
    color: #333;
}

.frame3 p {
    margin: 5px 0 0 0;
    font-size: 1.2em;
    color: #666;
}

/* Media Query for responsive design */
@media (max-width: 768px) {
    body {
        grid-template-columns: 1fr;
        grid-template-rows: repeat(5, 1fr);
    }

    .frame {
        font-size: 1em;
    }
}
```

## Conclusion

This project showcases how to recreate a specific layout using HTML and CSS, ensuring it is responsive to different screen sizes through the use of media queries.

---

Make sure to update the `git clone` URL to match your actual GitHub repository URL, and adjust the content according to your specific project setup if necessary.
