# CMS-Blog-Site
[![License: MIT License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://choosealicense.com/licenses/mit/)
 
**Project name**: Model-View-Controller (MVC) Challenge

**Description**: This project purpose was to test skills learned with Sequelize and Express-Handlebars and further skills using node.js & Express.

**Special Notes**: This application is applied to a Heroku live site. For testing purpose you are automatically logged off after 5 minutes of being Idle.

**Installation**: 	

access Github repository here: https://github.com/cjsmith1988/CMS-Blog-Site

Live URL: https://pure-wildwood-95738.herokuapp.com/

To download this application localy follow these steps:

- Clone repository

- Open command line with node.js installed and you are located in the cloned directory.

- In the command line type "npm i"

- Open a command line in the location of the cloned directory and type "mysql -u root -h localhost -p" and "source ./db/schema.sql;" and "use cms_blog_db;"

- create a new file in the directory to store your connection information by using the git bash command "touch ./.env"

- next enter this command: "echo "DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='<<your mySQL password>>' > ./.env"

- Back in the GItBash console type "npm start" to start the application

**Usage**: This was used for testing sequelize methods and Express-Handlebars.

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

**Questions**:

  View my: [GitHub profile](https://www.github.com/cjsmith1988)

  If you have any further questions regarding this project please email: [cj1988333@hotmail.com](mailto:cj1988333@hotmail.com?subject=[Question]CMS-Blog-Site).

![Homepage view](https://github.com/cjsmith1988/CMS-Blog-Site/blob/main/public/images/HomeScreenCap.PNG?raw=true)
![Dashboard view](https://github.com/cjsmith1988/CMS-Blog-Site/blob/main/public/images/DashboardScreenCap.PNG?raw=true)
![Login view](https://github.com/cjsmith1988/CMS-Blog-Site/blob/main/public/images/LoginScreenCap.PNG?raw=true)
![Login view](https://github.com/cjsmith1988/CMS-Blog-Site/blob/main/public/images/EditPostScreenCap.PNG?raw=true)


