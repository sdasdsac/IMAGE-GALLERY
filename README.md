# IMAGE-GALLERY
This HTML document creates an interactive image gallery with a welcoming message and stylish navigation controls. Below is a detailed description of the key elements and features implemented in the code:

HTML Structure
<html> and <head>:

Declares the document as HTML5 and sets meta information including charset and viewport settings.
Includes a <title> tag for the page title.
Contains a <style> block to define CSS styles.
<body>:

Central element of the document where the gallery and welcome message are defined.
Welcome Message
<div class="welcome" id="welcomeMessage">:
Displays a large, centered welcome message at the top of the page.
Uses CSS for styling: fixed position, full width, background color, large font size, and bold text.
The message fades out and hides after 3 seconds using a JavaScript timeout.
Gallery Container
<div class="gallery-container">:
Contains the image gallery.
Uses CSS to style it with a light background, box shadow, rounded corners, and margin-top to avoid overlap with the welcome message.
Image Gallery
<div class="gallery">:

Flex container holding all the images.
Transitions between images using CSS transform properties.
<img class="gallery-image" src="gallery/imageX.png" alt="Image X">:

Defines each image within the gallery.
Uses CSS for responsive sizing and positioning.
Controls
<div class="controls">:

Contains navigation buttons and an input field to jump to specific images.
Styles the controls with padding, background color, and shadow effects.
Buttons and Input:

Previous and Next buttons: Navigate through images.
Go button: Jumps to a specific image based on user input.
Input field: Allows users to enter an image number to view.
JavaScript Functionality
Navigation Functions (showImage, nextImage, prevImage, goToImage):

showImage(index): Updates the gallery position to display the specified image.
nextImage(): Advances to the next image.
prevImage(): Goes back to the previous image.
goToImage(): Jumps to an image based on the input field value.
Welcome Message Timer:

DOMContentLoaded event listener triggers a timeout to hide the welcome message after 3 seconds.
CSS Styling
General Styles:

Centers the content on the page.
Sets a light gray background for a clean look.
Uses a sans-serif font for readability.
Welcome Message:

Styled with fixed positioning, a dark background, and large, bold text.
Includes a transition for opacity and visibility changes.
Gallery Container:

Responsive design with a max-width to fit larger images.
Adds shadow and rounded corners for a polished appearance.
Controls:

Flexbox layout for spacing.
Larger, rounded buttons with hover effects for better user interaction.
Input field styled for consistency with buttons.
Responsive Design:

Adjusts styles for smaller screens to ensure usability and readability on mobile devices.
This document provides an aesthetically pleasing and user-friendly image gallery with smooth transitions, easy navigation, and a welcoming user experience.
