# Book Search Engine Refactor

## Description

This application refactors a functioning Google Books search engine built with a RESTful API into a GraphQL API built with Appollo Server. 

You may view the deployed application by [clicking this link](https://git.heroku.com/peaceful-refuge-87466.git).


## Technologies

- The application uses GraphQL queries and mutation to fetch and modify data, replacing the RESTful API.
- The existing authentication middleware was also modified so that it works in the context of GraphQL ALI.
- An appolloProvider was created to communicate requests with an Appollo Server.
- The application is deloyed on Heroku.

## Criteria

**User Story**

AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

**Acceptance Criteria**

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

## Accomplishments and Challenges

The application .....

**Below are a screenshots of the app showing the functionality:**
 
<br />
![login view](./client/public/assets/login.jpg)  
<br />
![search results](./client/public/assets/search.jpg)  
<br />

## Contributing

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## Credits

**The following resources were used to complete this project:**
1. UCONN Coding Bootcamp's modules on MERN Stacks
2. [Express](https://devdocs.io/express/) Documentation 
3. [Appollo Client](https://www.apollographql.com/docs/tutorial/client) Documentation 
4. [GraphQL](https://graphql.org/learn/) Documentation 


## License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

