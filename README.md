# CMS-Blog-Site
[![License: MIT License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://choosealicense.com/licenses/mit/)
 
**Project name**: Model-View-Controller (MVC) Challenge

**Description**: This project purpose was to test skills learned with Sequelize and Handlebars and further node.js & Express.

**Special Notes**: This application is applied to a Heroku live site.

**Installation**: 	

access Github repository here: https://github.com/cjsmith1988/CMS-Blog-Site

Live URL: https://immense-ridge-01896.herokuapp.com/api/



To download this application localy follow these steps:

- Clone repository

- Open command line with node.js installed and you are located in the cloned directory.

- In the command line type "npm i"

- Open a command line in the location of the cloned directory and type "mysql -u root -h localhost -p" and "CREATE DATABASE ecommerce_db;" and "use ecommerce_db;"

- this will create the mySQL database

- create a new file in the directory to store your connection information by using the git bash command "touch ./.env"

- next enter this command: "echo "DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='<<your mySQL password>>' > ./.env"

- Back in the GItBash console type "npm start" to start the application

**Usage**: This was used for testing sequelize methods.

**Contributing**: open for contribution, keep in seperate branch

**Credits**: This page was made by Curtis Smith

**License**: MIT License

### User Story:

AS A developer who writes about tech

I WANT a CMS-style blog site

SO THAT I can publish articles, blog posts, and my thoughts and opinions

### Requirements:

GIVEN a CMS-style blog site

WHEN I visit the site for the first time

THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in

WHEN I click on the homepage option

THEN I am taken to the homepage

WHEN I click on any other links in the navigation

THEN I am prompted to either sign up or sign in

WHEN I choose to sign up

THEN I am prompted to create a username and password

WHEN I click on the sign-up button

THEN my user credentials are saved and I am logged into the site

WHEN I revisit the site at a later time and choose to sign in

THEN I am prompted to enter my username and password

WHEN I am signed in to the site

THEN I see navigation links for the homepage, the dashboard, and the option to log out

WHEN I click on the homepage option in the navigation

THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created

WHEN I click on an existing blog post

THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment

WHEN I enter a comment and click on the submit button while signed in

THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created

WHEN I click on the dashboard option in the navigation

THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post

WHEN I click on the button to add a new blog post

THEN I am prompted to enter both a title and contents for my blog post

WHEN I click on the button to create a new blog post

THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post

WHEN I click on one of my existing posts in the dashboard

THEN I am able to delete or update my post and taken back to an updated dashboard

WHEN I click on the logout option in the navigation

THEN I am signed out of the site

WHEN I am idle on the page for more than a set time

THEN I am automatically signed out of the site 

![Homepage view](https://github.com/cjsmith1988/CMS-Blog-Site/blob/main/public/images/HomeScreenCap.PNG?raw=true)
![Api Product view](https://github.com/cjsmith1988/E-Commerce-Back-End/blob/main/images/insomniaProductsScreenGrab.PNG?raw=true)
![Api Product POST view](https://github.com/cjsmith1988/E-Commerce-Back-End/blob/main/images/insomniaProductsPOSTScreenGrab.PNG?raw=true)
