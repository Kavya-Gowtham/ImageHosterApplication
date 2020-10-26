# ImageHosterApplication

Problem Statement
In this course, you have learnt about software engineering topics ranging from version control to extreme programming, as well as backend development using Spring Boot, JPA, and PostgreSQL to build a backend application.

 

In this assignment, you’ll apply everything you have learnt in course 4 to build an image hoster similar to Imgur, one of the top 100 most visited websites in the world.

 

Goals of This Assignment 
Through working on the image uploader, you’ll get a chance to experience what it is like to join an engineering team as a new, junior software engineer. Specifically, you’ll get a chance to familiarize yourself with the codebase by fixing a few bugs in the codebase. You’ll also get a chance to implement a few well-defined features to the image uploader and improve its functionalities.

Lastly, this project will also introduce you to new concepts to Spring MVC, JPA, PostgreSQL and unit testing. Some of these concepts will be explained to you, and some concepts, you need to Google and Stack Overflow to learn those concepts on your own. This experience will further enhance the experience of joining a new team as a junior software developer as mentioned above.

 

Stub File
As all of you have implemented the ‘Image Hoster’ project given in MVC architecture and Database & ORMs assessments, you will continue working on the same project as a part of this assignment. 
Let us discuss in brief, the features implemented in the ‘Image Hoster’ project till now.

The application runs on localhost and the user is redirected to the landing page of the application displaying all the images in the application.
A new user can register in the application by entering the details such as username, password, full name, email address, and mobile number, and after the successful registration, he is redirected to the login page.
The user can log in the application by entering the username and password, and after successful login to the application, the user is redirected to the user homepage, displaying all the images in the application.
After a user successfully logs in the application, he can click on the title of any image and the image details will be displayed including the description and tags of the image, along with the option to edit and delete the image.
A user can also upload the image by entering the details such as image title, description, image file, and tags related to the image.
You may register in the application and upload the images in the application, to check all the features discussed above.
ImageHoster_assignment_stubfile_download	Download
 

Instructions:
You must manually create a database named ‘imageHoster’ in PostgreSQL with the user as ‘postgres’ using pgAdmin as the UI.
Change the username and password in the stub file in the ‘src/main/java/imageHoster/config/JpaConfig.java’ file and ‘src/main/resources/META-INF/persistence.xml’ file according to your PostgreSQL username and password. 
Note that it is mandatory to assign at least one tag/category to an image while you upload the image. If you do not assign any tag to the image, the image will get uploaded in the application. But when you try to edit the image, the application throws an error. 
 

You need to download the above-given stub file and run the code on IntelliJ. Run the application on localhost and observe all the working features of the application as mentioned above. Also, to improve the presentation of web pages, some HTML files have been updated using the external CSS file. However, you are only expected to work on the backend development and the details for any changes required in the presentation logic are clearly mentioned in the problem statement and also you can find the relevant comments in the stub file. In this assignment, you need to fix certain bugs and add some more features to the application. The details of the bugs to be fixed and the new features to be added in the application are provided in the next segment.

 

Additional Notes
Spring, Unit Testing, and Mocking
Although you have learnt about unit testing in this course, you are yet to learn about unit testing in the context of a Spring Boot project.
Therefore, in the Image Uploader project, we have written the unit tests of the controllers for you. We have also added comments to those unit tests to make the tests legible, so you can read the tests and understand what those tests are trying to accomplish.
If you would like to learn more about unit testing and mocking with Spring Boot, please refer to the following resources:

Spring MVC Test Framework
Spring: Testing the Web Layer
Spring Boot - Unit Testing and Mocking with Mockito and JUnit
Uncomment the unit tests written for the controller classes and confirm that all the test cases are successfully passed. Lastly, please feel to experiment with the unit tests, and write additional unit tests on your own.
 

Http Session
In the Image Uploader project, you’ll see that we are storing a User object (representing the currently logged in user) in a HttpSession object. This allows us to check the details of the currently logged in user. 
Please refer to the following resources to read more about HTTP Sessions, and how to use them in Spring:

What are sessions? How do they work?
Using Http Session With Spring Based Web Applications
 

Version Control Best Practices
Please follow the following best practice as you are using Git and Github to conduct version control of your code. This will make you a more effective software engineer.

Commit often
Make small, incremental commits
Write good commit messages
Make sure your code works before committing it
Use branches -- Keep your code for bug fixes and feature development in different branches.
Here are additional readings on best Git practices:

Git Common Practices
Commit Often, Fix it Later, Publish Once: Git Best Practices
