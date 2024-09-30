# PhotoGallery
This project showcases a simple photo gallery built with HTML and CSS.


Files:
index.html: This file contains the HTML structure of the photo gallery.
styles.css: This file contains the CSS styles applied to the gallery for formatting and layout.

Functionality:
The code displays a grid of cat photos using CSS Flexbox. Here's a breakdown of its features:

Responsive Layout: The gallery adapts its layout based on the screen size, ensuring the photos are displayed neatly on various devices.
Image Grid: Flexbox arranges the images in a grid format, automatically adjusting the number of images displayed per row based on the available space.
Image Styling: Each photo has a maximum width, ensuring consistency in the layout. The object-fit: cover property makes full use of the available space within the designated width and height, while rounded corners add a touch of style.
Centered Display: The gallery is centered horizontally on the page, creating a balanced visual presentation.

How to Run the Code:
- Save both HTML and CSS files in the same directory.
- Open the index.html file in a web browser to view the photo gallery.


Code Breakdown:
HTML:
- The header element displays the page title.
- The gallery class encompasses the container for all image elements.
- Each img element represents a photo with its corresponding source and alt text for accessibility.

CSS:
The box-sizing: border-box ensures consistent element sizing across browsers.
The body styles define the overall layout, including margins, font family, and background color.
The header styles configure the header section with text-align, text transformation (uppercase), padding, background color, text color, and a bottom border.
The gallery styles utilize Flexbox properties to achieve the desired grid layout:
display: flex: Initializes the container as a flexbox element.
flex-direction: row: Arranges the images in a row-wise direction.
flex-wrap: wrap: Allows images to automatically wrap onto new rows when space is limited.
justify-content: center: Centers the entire image grid horizontally within the container.
align-items: center: Vertically aligns the image content within each row.
gap: 16px: Introduces spacing between images for better visual separation.
max-width: 1400px: Sets a maximum width for the entire gallery container.
margin: 0 auto: Centers the gallery horizontally within the page.
padding: 20px 10px: Adds padding to the top and bottom and left and right sides of the gallery container, respectively.
.gallery img: Styles applied to individual image elements define their width, maximum width, height, object-fit for scaling, and rounded corners using border-radius.
.gallery::after: This pseudo-element is used to address a potential issue with the last image not filling the remaining space in a row. It's a hidden element with a width equal to the maximum image width, ensuring a consistent layout.

Customization:
You can easily swap out the images in the HTML with your own photos by modifying the src attribute of the img elements.
Modify the CSS styles to change the overall appearance of the photo gallery, such as adjusting color schemes, image sizes, and spacing.
Explore additional Flexbox properties to experiment with different layout configurations.
This code provides a basic structure for a photo gallery. Feel free to explore further and customize it to showcase your own collection of images!

Este código é baseado em um tutorial do freeCodeCamp, que oferece recursos gratuitos de aprendizado de programação. Para saber mais sobre o freeCodeCamp e explorar outros projetos, visite o site: https://www.freecodecamp.org/
