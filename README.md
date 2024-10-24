
Contact Form Project
Overview
This project consists of a simple contact form built with HTML, CSS, and JavaScript. The form includes fields for the user's name, email, and message. Upon submission, a success message is displayed without refreshing the page, providing a seamless user experience.

File Structure:
index.html: The main HTML file that contains the structure of the contact form.
index.js: An external JavaScript file that handles form submission and displays the success message.
index.css: An external CSS file that provides styling for the form and its elements.

Features:
User-Friendly Form: The form collects the user's name, email, and message, ensuring all fields are required for submission.
Dynamic Feedback: A success message is displayed without reloading the page, enhancing user experience.
Responsive Design: The form is styled to be visually appealing and is adaptable to various screen sizes.

Code Explanation:

index.html:
Contains the structure of the contact form.
Links to the external CSS (index.css) for styling and JavaScript (index.js) for functionality.
Includes a container to center the form and apply padding.

index.js:
Listens for the form submission event.
Prevents the default form submission behavior using event.preventDefault().
Displays a success message by changing the CSS display property.
Optionally clears the form fields after submission using this.reset().

index.css:
Applies styles to the body, container, form elements, and button.
Ensures a modern and clean look with padding, border-radius, and hover effects on the button.

Customization:
Feel free to modify the styles in index.css to fit your design preferences. You can also extend the JavaScript functionality to include form validation or integration with a backend service for message handling.

License:
This project is open source and available for use and modification.

