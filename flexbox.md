# Flexbox Exercise

## Table of Contents
- [Task Description](#task-description)
- [Hints](#hints)
- [Solution](#solution)

## Task Description

For the provided HTML structure, your task is to add Flexbox styling using CSS. Below is the HTML structure you'll be working with:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Header</h1>
    </header>
    <main>
        <section class="flex-container">
            <div class="box">1</div>
            <div class="box">2</div>
            <div class="box">3</div>
        </section>
    </main>
    <footer>
        <p>Footer</p>
    </footer>
</body>
</html>
```

# CSS Styling and Flexbox Exercise

## Table of Contents
- [Task Description](#task-description)
- [Hints](#hints)
- [Task Details](#task-details)

## Task Description

In this exercise, you will create a CSS file (styles.css) and define the necessary styles to achieve the following:

1. Set the body's background color to a light gray or any color of your choice.
2. Style the header and footer with background color, padding, and text alignment.
3. Create a `.flex-container` class and apply Flexbox properties to it.
4. Create `.box` class styles to represent three boxes inside the flex container.
5. Apply different background colors, padding, and margins to make the boxes visually distinct.
6. Use Flexbox properties like `display: flex;`, `flex-direction: row;`, `justify-content: space-between;`, etc., to arrange the boxes horizontally with space between them.

Your task is to create a horizontal row of three boxes within the main section. The boxes should be evenly spaced and visually distinct. The header and footer should have a distinct appearance as well.

## Hints

### Task 1: HTML Structure

- Create an HTML structure with header, main content area, and footer using appropriate HTML tags (`<header>`, `<main>`, `<footer>`).
- Inside the main content area, create a `<section>` with a class of "flex-container" to hold the flex items (boxes).

### Task 2: CSS Styling

- Create a CSS file (styles.css) and link it to your HTML document.
- Set the background color for the body to create a visually distinct canvas.
- Style the header and footer with background color, padding, and text alignment to make them visually appealing.

### Task 3: Create a Flex Container

- Define the `.flex-container` class in your CSS.
- Apply `display: flex;` to make it a flex container.
- Set `flex-direction` to "row" to arrange items horizontally.
- Use `justify-content` property to evenly space items along the main axis.

### Task 4: Create Flex Items (Boxes)

- Define the `.box` class in your CSS to style the boxes.
- Apply different background colors, padding, and margins to make the boxes visually distinct.
- You can set the `flex` property on the boxes to control their individual sizing within the flex container.

### Task 5: Testing

- Test your layout by resizing the browser window to ensure that the flex items adjust and maintain their layout as the screen size changes.
- Verify that the header and footer also adjust their appearance for different screen sizes.

# Flexbox Exercise - Solution

In this section, you'll find the solution for the HTML and CSS files based on the provided exercise.

## Solution for index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Header</h1>
    </header>
    <main>
        <section class="flex-container">
            <div class="box">1</div>
            <div class="box">2</div>
            <div class="box">3</div>
        </section>
    </main>
    <footer>
        <p>Footer</p>
    </footer>
</body>
</html>
```
## Solution for styles.css

```css
body {
    background-color: #f2f2f2;
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

header, footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

main {
    padding: 20px;
    text-align: center;
}

.flex-container {
    display: flex;
    justify-content: space-between;
}

.box {
    flex: 1;
    background-color: #3498db;
    color: #fff;
    text-align: center;
    padding: 20px;
    margin: 10px;
}
```







## Task 1: Create a Navigation Menu with Flexbox
Create a horizontal navigation menu using Flexbox. The menu should be centered within the header, and the menu items should be evenly spaced. Apply styles for links and background colors.

HTML Structure (index.html):

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Navigation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav class="nav-menu">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Portfolio</a>
            <a href="#">Contact</a>
        </nav>
    </header>
</body>
</html>
```

CSS (styles.css):
```css
/* Apply basic styles for the navigation menu */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

.nav-menu {
    display: flex;
    justify-content: space-around;
    background-color: #444;
    padding: 10px 0;
}

.nav-menu a {
    text-decoration: none;
    color: #fff;
    padding: 5px 10px;
    transition: background-color 0.3s ease;
}

.nav-menu a:hover {
    background-color: #555;
}
```

## Task 2: Create a Simple Card Layout with Flexbox
Create a simple card layout using Flexbox. The cards should be evenly spaced within a container and have a distinct background color and some text content. Feel free to customize the styles and content as you like.

HTML Structure (index.html):

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Card Layout</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <main class="card-container">
        <div class="card">Card 1</div>
        <div class="card">Card 2</div>
        <div class="card">Card 3</div>
    </main>
</body>
</html>
```

CSS (styles.css):
```css
/* Apply basic styles for the card layout */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.card-container {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.card {
    flex: 1;
    background-color: #3498db;
    color: #fff;
    text-align: center;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
}
```
