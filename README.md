## Technologies Uses
HTML Structure
CSS Styling
JavaScript Functionality

## Description
This project allows you users to generate custom progress certificates for their students. The user can enter the student's name, a personalized message, and the course name. Once the user clicks the "Generate Certificate" button, a modal will appear displaying the generated certificate.


## How to Use
HTML Structure
This application uses a basic HTML structure, with a form for the user to input the student's name, personalized message, and course name. The form has a submit event listener that triggers the JavaScript code to generate a certificate when the user clicks the "Generate Certificate" button.

The certificate is displayed in a modal, which is hidden by default and shown when the certificate is generated.

## CSS Styling
The CSS file, index.css, styles the HTML elements to make the application look visually appealing. The modal and the certificate are styled with appropriate colors and fonts.

## JavaScript Functionality
The JavaScript file, index.js, handles the following functionalities:

## Event listener for the form submission.
Generates a certificate by creating a new div element, adding the student's name, personalized message, and course name, and then appending it to the certificateContent element.
Shows the modal when the certificate is generated and hides it when the user clicks the "X" button.

## Steps to using the application:

Open the index.html file in a web browser.
Enter the student's name, personalized message, and course name in the form.
Click the "Generate Certificate" button.
The certificate will appear in the modal.
To close the modal, click the "X" button.
