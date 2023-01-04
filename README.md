![Express](download.jpg)
## BLOG APP

This project is a simple Backed  Application  using express a nodejs framework. That allows users to signup , login , create blog , add blog , update blog and deletee blogs . Blogs can be save in two different form on this app (draft or published). User can get the blog endpoint, either the user is been login or not. 

#### Getting started:
To get started we need to ensure that we have nodejs running on our  local terminal . If we don't have  nodejs on our local machine ,  we need to install it by downloading the latest version of it. 

### Note: 
**Create a package.json file by running npm init -y command  on your working terminal**

***Let dive deep .***

![MVC pattern](mvc%20pattern.jpg)
###### This project was developed using the MVC  design pattern .By  creating  the Models folder , Routes folder, Controller folder. With  some  folders and some single file, which i will  explain below   .This project has two main route the blog route and the user route. 



The models folder contains the blogmodel file and usermodel file. Where i created  their  Schemas and exported them to the controller folder. The blogmodel Schema conatains  the blog title , description , author, state[draft or publish], read count, and reading time. 

The Controllers folder contains the blogController file and userController file . Where i imported the models files to . I created the CRUD method in the controller file. 

The MVC pattern is not complete without the view folder. But in this case the view folder is not necessary to create,  because we can use some alternatives like Thunder Client and postman as our view. Which i actually use in my own case.

The Route folder is the final stage of my MVC pattern . Where i created my express router and  imported the CRUD methods of my blogController and userController  as a  route .

App file , this file serves as the module file for my project .


![Depend](express.jpg)
#### The following dependecies were installed for this project:
- ***nodemon***
- ***bcrypt***
- ***body-parser***
- ***connect-ensure-in***
- ***dotenv***
- ***ejs***
- ***express***
- ***express-session***
- ***jest***
- ***jsonwebtoken***
- ***mongoose***
- ***passport***
- ***passport-jwt***
- ***passport-local***
- ***passport-local-mongoose***
- ***supertest***

***Built with***
- Express: Express is nodejs framework that makes project to be easy to build using javascript as the programming language.
- Supertest/jest: This npm packages make the develop to test the project when needed. Supertest is for integration testing while jest is for unit testing. 
- nodemon: This npm package refreshes your project when ever you  update it without running the command (nodemon app/server) multiple times. 

##### To save our time , you can read more on the dependencies. Using their documentations.
 
 Please check out my project by clicking on this link [BLOG APP](https://github.com/anikiyusuf/blog-project/tree/master). You are free to contribute to the project. 



#### Code with love by Yusuf Aniki 
##### Happy coding 




