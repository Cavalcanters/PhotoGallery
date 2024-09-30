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
- display: flex: Establishes the .gallery container as a flex container, enabling flexible item arrangement.
- flex-wrap: wrap: Allows flex items to wrap onto multiple lines if they don't fit on a single line.
- justify-content: center: Centers the flex items horizontally within the container.
- align-items: center: Centers the flex items vertically within the container.
- gap: Sets the space between flex items.   
- max-width: Limits the maximum width of the container.
- margin: 0 auto: Centers the container horizontally on the page.
- object-fit: cover: Scales the image to fill its container while maintaining aspect ratio.
- border-radius: Rounds the corners of the images.

Customization:
You can easily swap out the images in the HTML with your own photos by modifying the src attribute of the img elements.
Modify the CSS styles to change the overall appearance of the photo gallery, such as adjusting color schemes, image sizes, and spacing.
Explore additional Flexbox properties to experiment with different layout configurations.
This code provides a basic structure for a photo gallery. Feel free to explore further and customize it to showcase your own collection of images!

Este código é baseado em um tutorial do freeCodeCamp, que oferece recursos gratuitos de aprendizado de programação. Para saber mais sobre o freeCodeCamp e explorar outros projetos, visite o site: https://www.freecodecamp.org/
