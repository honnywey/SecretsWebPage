# Secrets Page: A Secure Web App for Storing Secrets

Welcome to the Secrets Page project! This web application was created as part of a web development course to enhance skills in MongoDB, EJS templating, bcrypt password encryption, and implementing Google API login with Gmail accounts. It also leverages HTML, CSS, Node.js, and JavaScript to provide a secure platform for storing and retrieving secrets.

## Getting Started

1. Clone this repository to your local machine.
2. Add your own `CLIENT_ID`, `CLIENT_SECRET`, and `SECRET` to the .env file (these sensitive keys have been omitted from version control).
3. Run `npm install` to install the necessary dependencies.
4. Start the application using `node app.js`.
5. Access the application at `http://localhost:3000` in your web browser.

## Features

- Securely store and retrieve secrets.
- Google API login with Gmail accounts for enhanced security.
- Utilizes EJS for dynamic templating.
- Demonstrates practical use of MongoDB for database management.
- Implements bcrypt for password encryption (Note: bcrypt is currently commented out in the code; you can uncomment it and use the `SECRET` in the .env file for a different hashing method if desired).
- Responsive design with HTML and CSS.

## Technologies Used

- HTML
- CSS
- JavaScript
- Node.js
- EJS
- MongoDB
- bcrypt (currently commented; can be uncommented if desired)
- Google API

## Acknowledgements

This project serves as a hands-on example of applying web development concepts to create a secure and interactive web application. Feel free to explore the code to learn more about how these technologies were integrated to build the Secrets Page.

Remember to keep sensitive information such as API keys and secrets private by adding them to the .env file and excluding it from version control. You can also choose to activate bcrypt by uncommenting the relevant code and using the `SECRET` in the .env file for a different hashing method.
