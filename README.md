# MERN Module 21: Book Search Engine
   
## Description

The MERN Module 21: Book Search Engine is a full-stack web application that allows users to search and save books from the Google Books API. Built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), this project provides a seamless and intuitive user experience for discovering and managing a personal collection of books.

**[Deployed Application](https://immense-bayou-59566.herokuapp.com/)**
  
Screenshot:

![Screenshot](./client/public/Screenshots.jpg)

## User Story

```
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Acceptance Criteria

```
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
```
   
## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Technologies Used](#technology-used)


  ## Technologies Used:

* MongoDB: A NoSQL database used to store and manage book data and user information.
* Express.js: A minimal and flexible web application framework for building robust APIs and server-side functionalities.
* React.js: A JavaScript library for building user interfaces, allowing for efficient and dynamic rendering of components.
* Node.js: A JavaScript runtime environment used for server-side scripting and running the backend server.
* Google Books API: An API provided by Google that allows access to the vast collection of books and related information.








