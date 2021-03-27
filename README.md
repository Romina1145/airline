# airline

                                                   SQL, Models and MigrationS
                                                                             
                                                                             
                                       CS50’s course - Web Programming with Python and JavaScript 
                                                                  
                                                                  
                                                                  
                                                                  
    1. Using  SQL and Django models to efficiently store and access data.
 
 
 Databases
     
     
Before we get into how to use the SQL language, we should discuss how our data is stored. When using SQL, we’ll work with a relational database where we can find all of our data stored in a number of tables. Each of these tables is made up of a set number of columns and a flexible number of rows.

To illustrate how to work with SQL, we’ll use the example of a website for an airline used to keep track of flights and passengers.


    2. Users/Authentification

The last thing is the idea of authentication, or allowing users to log in and out of a website. Fortunately, Django makes this very easy for us, so let’s go through an example of how we would do this. We’ll start by creating a new app called users. Here we’ll go through all the normal steps of creating a new app, but in our new urls.py file, we’ll add a few more routes:
