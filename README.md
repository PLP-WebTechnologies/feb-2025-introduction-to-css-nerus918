# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header Section -->
    <div id="header">
        <h1>Welcome to My Stylish Page</h1>
    </div>

    <!-- Main Content Section -->
    <div class="container">
        <h2>About This Page</h2>
        <p class="content">This page demonstrates how to apply CSS styles using classes, IDs, colors, typography, margins, paddings, and borders.</p>
        <img src="https://via.placeholder.com/600x300" alt="Placeholder Image">
    </div>

    <!-- Footer Section -->
    <div id="footer">
        <p>&copy; nelly 2025 My Website. All rights reserved.</p>
    </div>

</body>
</html>

/* General Styles */
body {
    font-family: 'Verdana', sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
}

/* Styling elements using ID selector */
#header {
    background-color: #3498db;
    color: white;
    text-align: center;
    padding: 20px;
    margin-bottom: 30px;
}

#footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 15px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Styling elements using Class selector */
.container {
    margin: 30px auto;
    padding: 20px;
    max-width: 800px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.content {
    margin: 20px 0;
    padding: 10px;
    font-size: 16px;
    line-height: 1.6;
}

/* Styling Images */
img {
    width: 100%;
    max-width: 600px;
    height: auto;
    border: 3px solid #3498db;
    margin: 20px 0;
}
