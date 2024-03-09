# Tech-Blog

## Description
    This Application uses Model-View-Controller(MVC) paradigm to create a blog-style app where developers can create an account, edit their information, make or edit posts and comment on other users posts.
    
## Tables of content:
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributors](#contributors)
  * [Test](#test)
  * [Questions](#questions)
  * [Live Links](#url)
  

## Installation

1. Install NODE.js to run this application
2. Create a .gitignore file and include node_modules/ to prevent the node_modules directory from being tracked or uploaded to GitHub.
3. Make sure your repository includes a package.json file with the required dependencies. You can create one by running npm init when setting up the project.
4. Run command npm npm install mysql2 to install mysql package to connect with database and perfrom queries.
5. Run command npm install to install all dependencies for this project.
6. Create database and insert data.
7. Run command mysql -u root to be in mysql.
8. Run command source node seeds/index.js.
9. The application will be invoked by using the following command: npm start.This will start localhost server on PORT 3000.
10. Open browser and type http://localhost:3000 to run this application on your local machine.
     

## Usage 

1. The app will follow the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.
2. When a user visits the site for the first time, they are presented with the homepage, which includes existing blog posts if any have been posted, navigation links for the homepage and the dashboard, and the option to log in.
3. When clicking on any other links in the navigation, they are prompted to either sign up or login.
4. On sign up, they are prompted to enter a username, email, and password. Upon clicking sign up, the user is created and signed in to the application.
5. On Login, users can enter their username and password created during sign up and can log in to the application on their next visit.
6.Once logged in, users see navigation links for the homepage, the dashboard, and the option to log out.
7.Clicking on Home takes the user to the homepage and presents existing blog posts, including the post title, content, post creator’s username, and date created for that post.
8.Clicking on an existing blog post on the home page presents the post title, contents, post creator’s username, and date created for that post, with the option to leave a comment.
9.Upon entering a comment and clicking on the submit button while signed in, the comment is saved, and the post is updated to display the comment, the comment creator’s username, and the date created.
10.Clicking on the dashboard link in the navigation takes the user to the dashboard and presents any blog posts that have already been created and the option to add a new blog post or delete a post.
11.Clicking on the logout option in the navigation signs the user out of the site.


## Contributors
Christian Douglas, Armond Guze, Justin Ramirez

## Test
npm start


## Questions
For questions about the project, please contact [email](mailto:andrewcasablanca@yahoo.com).

GitHub: [ajcasablanca](https://github.com/ajcasablanca)



## Live LInks
1. [Heroku](https://secret-inlet-32925-909dfa80ce1f.herokuapp.com/)

2. [GitHub](https://ajcasablanca.github.io/Tech-Blog/)

3. [Demo](https://drive.google.com/file/d/1VDZ-TexDxvU37rqg2MXS9JG4xlIyBKJr/view?usp=sharing)
