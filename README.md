This project demonstrates two ways to make an image disappear when the mouse hovers over it and reappear when the mouse moves away. The first method uses JavaScript, while the second uses only CSS.

Features
The image disappears when the mouse hovers over it.
The image reappears when the mouse moves away from it.
Implemented in two ways:
Using JavaScript (No CSS)
Using CSS (No JavaScript)
Files
index.html (JavaScript Implementation): This HTML file contains the implementation using JavaScript. It listens for mouseover and mouseout events to hide and show the image.

onlycss.html (CSS Implementation): This file contains the implementation using only CSS. The hover effect is achieved with the :hover selector and the visibility property.

Usage
Clone the repository:

bash
Copy code
git clone https://github.com/namitha3041/taskeleven.git
Open the index.html file in your browser to see the JavaScript implementation in action.

For the CSS implementation, open onlycss.html in your browser.

How the JavaScript Implementation Works
The image is downloaded from the internet  (cat.jpg).
When the mouse hovers over the image, JavaScript sets style.display = 'none', making the image disappear.
When the mouse moves out of the image, JavaScript sets style.display = 'block', making the image reappear.
How the CSS Implementation Works
The same image is used as in the JavaScript example.
The CSS :hover selector is applied to hide the image using visibility: hidden when the mouse hovers over it.
Future Improvements
Add more advanced hover animations or transitions.
Allow customization of the image URL through a form or configuration.
