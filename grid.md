# CSS Grid Image Gallery

In this exercise, you will create a simple image gallery using CSS Grid. The gallery will display images in a grid layout with three columns. Each gallery item will contain an image with a border, border radius, and a subtle box shadow. Images will be responsive. You can add image links from Google Images or use placeholder images.

## HTML Structure (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <main class="image-gallery">
        <div class="gallery-item"><img src="image1.jpg" alt="Image 1"></div>
        <div class="gallery-item"><img src="image2.jpg" alt="Image 2"></div>
        <div class="gallery-item"><img src="image3.jpg" alt="Image 3"></div>
        <div class="gallery-item"><img src="image4.jpg" alt="Image 4"></div>
        <div class="gallery-item"><img src="image5.jpg" alt="Image 5"></div>
        <div class="gallery-item"><img src="image6.jpg" alt="Image 6"></div>
    </main>
</body>
</html>
```

CSS (styles.css)
```css
/* Apply basic styles for the image gallery */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.image-gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
    padding: 20px;
}

.gallery-item {
    text-align: center;
}

.gallery-item img {
    max-width: 100%;
    height: auto;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
}
```

# CSS Grid Image Gallery

### Task 1: HTML Structure

- Start with a basic HTML structure that includes an `<img>` element for each image you want to display in the gallery.
- Wrap all the `<img>` elements in a container, which will be your grid.

### Task 2: CSS Grid Layout

- Define a CSS class (e.g., `.image-gallery`) for the grid container in your CSS file.
- Use the `display: grid;` property to create a grid layout.
- Set the number of columns in the grid using the `grid-template-columns` property. You can use `repeat()` to specify the number of columns and their width (e.g., `grid-template-columns: repeat(3, 1fr);` for three equally spaced columns).
- Add `grid-gap` to create spacing between grid items (images).
- Apply padding to the grid container to provide some spacing around the gallery.

### Task 3: Styling Grid Items

- Create a CSS class (e.g., `.gallery-item`) for styling individual gallery items.
- Apply `text-align: center;` to center the content within each grid item.
- Style the images (inside `.gallery-item img`) to be responsive by setting `max-width: 100%;` and `height: auto;`. This ensures the images scale properly on different screen sizes.
- Add a border, border radius, and a subtle box shadow to make the images visually appealing.

You can use these tasks as a guide to create your CSS Grid image gallery. Customize the HTML and CSS as needed for your specific images and styling preferences.

## HTML Solution:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid Image Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <main class="image-gallery">
        <div class="gallery-item"><img src="image1.jpg" alt="Image 1"></div>
        <div class="gallery-item"><img src="image2.jpg" alt="Image 2"></div>
        <div class="gallery-item"><img src="image3.jpg" alt="Image 3"></div>
        <div class="gallery-item"><img src="image4.jpg" alt="Image 4"></div>
        <div class="gallery-item"><img src="image5.jpg" alt="Image 5"></div>
        <div class="gallery-item"><img src="image6.jpg" alt="Image 6"></div>
    </main>
</body>
</html>
```
## CSS Solution:

```css
/* Apply basic styles for the image gallery */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.image-gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
    padding: 20px;
}

.gallery-item {
    text-align: center;
}
```

## Exercise 1: Create a CSS Grid-Based Product Display

Task: Create a simple product grid using CSS Grid. The grid should display product items in a 3-column layout. Each product item should have a background color, text content, and a subtle box shadow for a card-like appearance.

HTML Structure (index.html):

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Grid</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <main class="product-grid">
        <div class="product">Product 1</div>
        <div class="product">Product 2</div>
        <div class="product">Product 3</div>
        <div class="product">Product 4</div>
        <div class="product">Product 5</div>
        <div class="product">Product 6</div>
    </main>
</body>
</html>
```

CSS (styles.css):
```css
/* Apply basic styles for the product grid */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
    padding: 20px;
}

.product {
    text-align: center;
    background-color: #3498db;
    color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
}
```

## Exercise 2: Create a Responsive Photo Gallery with CSS Grid
Task: Create a responsive photo gallery using CSS Grid. The gallery should display photos in a grid layout that adjusts its columns based on the available width. Each photo item should have a background color, text content, and a subtle box shadow.

HTML Structure (index.html):
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <main class="photo-gallery">
        <div class="photo">Photo 1</div>
        <div class="photo">Photo 2</div>
        <div class="photo">Photo 3</div>
        <div class="photo">Photo 4</div>
        <div class="photo">Photo 5</div>
        <div class="photo">Photo 6</div>
    </main>
</body>
</html>
```

CSS (styles.css):
```css
/* Apply basic styles for the photo gallery */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.photo-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 20px;
    padding: 20px;
}

.photo {
    text-align: center;
    background-color: #3498db;
    color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
}
```
