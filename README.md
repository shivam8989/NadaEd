Step 1(HTML code) : 

Creating a solid foundation is crucial. We'll delve into the HTML structure necessary for a contact form. Understanding the purpose of each element will set the stage for seamless integration with CSS and JavaScript.

How to Implement:

Open your preferred text editor.
Start with the <form> tag and define the necessary fields like name, email, and message.
Let's break down the code step by step:

1. <!DOCTYPE html>: Declares the document type and version of HTML (HTML5 in this case).

2. <html lang="en">: The root element of the HTML document. The lang attribute specifies the language of the document as English.

3. <head>: Contains meta-information about the HTML document, including character set, viewport settings, title, and links to external resources.


<meta charset="UTF-8">: Specifies the character encoding of the document as UTF-8.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Instructs Internet Explorer to use the latest rendering engine.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Defines the viewport properties for responsive design.
<title>Contact Page Design</title>: Sets the title of the webpage to "Contact Page Design".
<link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.2/css/all.min.css'>: Links to the Font Awesome CSS file, providing icons for social media.
<link rel="stylesheet" href="styles.css">: Links to an external stylesheet named "styles.css" for additional styling.
4. <body>: Contains the content of the HTML document.

<div class="container">: A container for the main content of the webpage.
<h2>Get in touch</h2>: Heading indicating the purpose of the contact page.
<p>...</p>: Paragraph with a message encouraging users to contact about web development.
<form class="contact-form">: A form with the class "contact-form" for users to input their details.
<div class="input-area">: Container for an input field.
Various input fields for name, email, subject, and a textarea for a message.
<button class="sendbtn">Send</button>: A button to submit the form.
<div class="social-container">: Container for social media links.
<div class="custom-social-container">: Inner container for styling.
<p>Contact me on</p>: A heading indicating the purpose of the social links.
<button class="cross-btn">...</button>: A button with a Font Awesome times icon to potentially close the social links.
<ul>...</ul>: An unordered list containing social media links with Font Awesome icons.
<button class="connect-btn">Get Connected</button>: A button with the class "connect-btn" encouraging users to get connected.
5. <script src="script.js"></script>: Links to an external JavaScript file named "script.js" for additional scripting.

Step 2 (CSS Code):


Aesthetics play a pivotal role in user engagement. We'll guide you through styling the contact form using CSS, ensuring a visually appealing and cohesive design.

How to Implement:

Create a new CSS file and link it to your HTML document.
Define styles for form elements, ensuring consistency and readability.
Consider using modern design principles for an enhanced visual experience.
Let's break down the code step by step:

1. Font Import:


Imports the Poppins font from Google Fonts with specified weights (400, 600, 700, 800, 900).
2. Universal Box Sizing:

Sets the box-sizing property to border-box for all elements.
3. Body Styling:

Set the background color to lavender (#E6E6FA).
Utilizes Flexbox to center content vertically and horizontally.
Applies Poppins font as the default font for the body.
Ensures a minimum height of 100% of the viewport height.
4. Container Styling:


Styled container with a white background, a dark purple border, border-radius, and box shadow.
Uses Flexbox to center content vertically and horizontally within the container.
Sets padding, text alignment, and width properties.
Adjusts styling for smaller screens using media query.
5. Paragraph Styling Inside Container:

Sets color, and letter-spacing for paragraphs inside the container.
6. Form Styling Inside Container:

Sets a fixed width for the form inside the container.
7. Input Area Styling Inside Container:


Defines styling for an input area, including position, margin, height, and width.
8. Input and Textarea Styling Inside Container:

Applies styling for input and textarea elements, including font, padding, height, width, border, and border-radius.
9. Send Button Styling Inside Container:

Styles the send button with background color, text color, font size, padding, border, and border-radius.
Adds hover effect with a different background color.
10. Media Query for Small Screens:


Adjusts container padding for screens with a maximum width of 600 pixels.
11. Social Container Styling:

Fixes the position to the right bottom of the viewport.
Applies a transition effect for smoother visibility changes.
Sets a higher z-index to ensure visibility over other elements.
12. Visible Class for Social Container:

Defines a class to make the social container visible by changing its transform property.
13. Custom Social Container Styling:


Styles a container for social media links with a white background, rounded corners, box shadow, border, and font.
Defines the size limits for the container.
14. Cross Button Inside Social Container:

Creates a cross button with styling for color, cursor, font size, and position.
15. Paragraph Inside Social Container:

Styles a paragraph with background color, border-radius, color, font size, line height, padding, position, top, left, margin, and transform properties.
16. Unordered List Inside Social Container:


Sets styling for an unordered list with flex display, zero padding, and a top margin.
17. List Items Inside Social Container:

Defines margin for list items.
18. Social Media Links Inside Social Container:

Styles links with border, border-radius, color, font size, flex display, height, width, and text decoration.
19. Hover Effect for Social Media Links:

Changes border color and applies a box shadow on hover.
20. Connect Button Styling:

Styles a connect button with border-radius, background color, border, box shadow, color, cursor, font size, line height, padding, position, bottom, right, and z-index properties.
21. Hover Effect for Connect Button:

Changes background color on hover.
22. Media Query for Extra Small Screens:

Adjusts the position of the social container and connect button for screens with a maximum width of 480 pixels.

Step 3 (JavaScript Code):

Now it's time to make your contact page dynamic. We'll introduce JavaScript to add interactive elements, making the user experience more engaging.

How to Implement:

Incorporate JavaScript into your HTML document or link an external script.
Ensure seamless interaction without compromising on performance.
Let me break down the code for you:

1. Contact Form Section:

It selects the HTML element with the class 'contact-form' and 'container'.
It attaches an event listener to the contact form for the 'submit' event.
When the form is submitted, it prevents the default form submission (preventing a page reload).
It then replaces the content of the container with a message thanking the user for their message.
2. Social Media Buttons Section:

It selects HTML elements with the classes 'connect-btn', 'cross-btn', and 'social-container'.
It attaches an event listener to the 'connect-btn' button for the 'click' event.
When the 'connect-btn' is clicked, it toggles the 'visible' class on the 'social-container', meaning it shows/hides the social media buttons.
It attaches an event listener to the 'cross-btn' button for the 'click' event.
When the 'cross-btn' is clicked, it removes the 'visible' class from the 'social-container', hiding the social media buttons.
