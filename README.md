# Tech-Blog

## Description
For Module 14 MVC, this is a CMS-style blog site that uses a Model-View-Controller paradigm to allow for user sign in, post creation, and commenting. 

## Link to Repo

https://github.com/jrargent/Tech-Blog

## Link to Deployed Website

https://tranquil-dawn-57244.herokuapp.com/

## Installation

Download the codebase from this GitHub repo and unzip the files. Once the files are on your local machine, open the command terminal and enter the command 'npm i' to download the dependencies and npm files necessary.

Enter "node server.js" in the terminal to start the program. Finally, navigate to "http://localhost:3001/" in a web browser to access the program on your machine. 

## Acceptance Criteria

```
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
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```



## Things I learned in this project
- I really enjoy the backend, more-so than the front-end  
  - This is evidenced by the fact that I saved all css styling until the very end
- I gained a better understanding of the Model-View-Controller paradigm
- I gained a better understanding of API calls
