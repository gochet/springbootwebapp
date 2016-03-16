# Spring Boot Web Application
This repository has the project files for a tutorial series on Spring Boot available from by website at [Spring Framework Guru](https://springframework.guru)

4:15 PM Tuesday, March 15, 2016
Downloaded yesterday as a way to sharpen my skills.  Took me all day yesterday, and most of today to figure out why it wouldn't build or run.
Turns out, it was trying to use a postgresql DB instead of H2, which resides in-memory, and is simple and useful for testing.  So problem number One solved.
I believe that tomorrow, I will try to implement Postgresql and see what happens.

12:09 PM Wednesday, March 16, 2016
Began making slight changes to HTML pages, and realized that I need to re-build and restart the application every time I want to see changes.
Have spent the morning trying to understand how to remedy this.  It appears to be a function of running TomCat within Spring Boot.  Adjusting 
Thymeleaf settings was supposed to help, but has not.