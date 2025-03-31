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
 - Happy Coding! 💻✨

SOLUTION

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="title">Welcome to My Styled Page</h1>
  </header>
  
  <section>
    <p id="intro">This is an example of styling elements using external CSS.</p>
    <img class="featured-image" src="example.jpg" alt="Example Image">
  </section>

  <footer>
    <p>Thank you for visiting!</p>
  </footer>
</body>
</html>
css
/* Styling header using a class */
.title {
  color: darkblue;
  font-family: 'Georgia', serif;
  font-size: 32px;
  text-align: center;
}

/* Styling paragraph using an ID */
#intro {
  color: darkgray;
  font-family: 'Arial', sans-serif;
  font-size: 18px;
  margin: 20px;
  padding: 10px;
  border: 2px solid lightgray;
  background-color: #f9f9f9;
}

/* Styling image using a class */
.featured-image {
  margin: 20px auto;
  padding: 10px;
  border: 5px solid darkblue;
  display: block;
  max-width: 100%;
  height: auto;
}


