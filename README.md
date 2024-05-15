# challenge14techblog

## Description

Tech Blog is a CMS-style blog site where developers can publish their blog posts and comment on other developers’ posts. This application is built completely from scratch and deployed to Heroku. It follows the MVC (Model-View-Controller) paradigm in its architectural structure, utilizing Handlebars.js as the templating language, Sequelize as the ORM (Object-Relational Mapping), and the express-session npm package for authentication.

## Installation

To run the application locally, follow these steps:

Clone the repository: git clone <repository-url>
Navigate to the project directory: cd tech-blog
Install dependencies: npm install
Set up the database:
Create a .env file in the root directory.
Add your database credentials to the .env file.
Initialize the database: npm run seed
Start the server: npm start
Open your browser and navigate to http://localhost:3001

## Credit

Credit to our great instructor Phil for help and guidance building the project and its deployment to Heroku

## License

MIT License 

## Features

User Authentication: Users can sign up, log in, and log out securely using the express-session npm package for authentication.
Create and Publish Blog Posts: Authenticated users can create, edit, and publish their blog posts.
Commenting: Users can comment on blog posts created by other users.
Responsive Design: The application is responsive and works seamlessly across different devices and screen sizes.

Technologies Used:

Node.js
Express.js
Sequelize
Handlebars.js
Express-session