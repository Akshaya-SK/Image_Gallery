# Ex.08 Design of Interactive Image Gallery

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
gallery.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gemstone Gallery</title>
    <link rel="stylesheet" href="C:\Users\admin\Desktop\interactivegallery\gallery\static\style.css">
</head>
<body>

    <header>
        Gemstone Gallery
    </header>

    <div class="gallery-container">
        <!-- Replace with valid static paths to your images -->
        <img src="C:\Users\admin\Desktop\interactivegallery\images\amethyst.png" alt="Amethyst">
        <img src="C:\Users\admin\Desktop\interactivegallery\images\crystal.png" alt="Crystal">
        <img src="C:\Users\admin\Desktop\interactivegallery\images\emerald.png" alt="Emerald">
        <img src="C:\Users\admin\Desktop\interactivegallery\images\opal.png" alt="Opal">
        <img src="C:\Users\admin\Desktop\interactivegallery\images\pinkquartz.png" alt="Pink Quartz">
        <img src="C:\Users\admin\Desktop\interactivegallery\images\ruby.png" alt="Ruby">
        <img src="C:\Users\admin\Desktop\interactivegallery\images\sappire.png" alt="Sapphire">
        <img src="C:\Users\admin\Desktop\interactivegallery\images\turquoisegemstone.png" alt="Turquoise">
    </div>

    <footer>
        &copy; 2024 Gemstone Gallery
    </footer>

</body>
</html>
```
style.css
```
/* Apply box-sizing for consistent padding/margin */
*,
*::before,
*::after {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
    background-color: black; /* Background color */
    color: gold; /* Text color */
    font-family: 'Cursive', Arial, sans-serif; /* Cursive font fallback */
    text-align: center;
}

header {
    font-size: 48px; /* Large font size */
    font-weight: bold; /* Bold text */
    margin: 20px 0;
}

.gallery-container {
    display: flex;
    overflow-x: auto; /* Enable horizontal scrolling */
    gap: 20px; /* Space between images */
    padding: 20px;
    scroll-behavior: smooth; /* Smooth scrolling */
}

.gallery-container img {
    height: 150px; /* Fixed height for images */
    width: auto; /* Maintain aspect ratio */
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 10px 0;
    color: gold;
    background-color: #222;
}
```

## OUTPUT

![image](https://github.com/user-attachments/assets/f3f003eb-533b-4676-b957-fbad0b27db5c)


## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
