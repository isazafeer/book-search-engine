# book-search-engine

This application is a fully function book search engine that allows a user to login/sign up, search for a book, save it and delete it from thier saved collection.

## Acceptance Criteria

```md
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

## Usage

- Download or clone the repository and open in VSC
- Right click on the repository and click on 'open in integrated terminal'
- Run `npm i` to install dependencies
- Run `npm run develop` to run the application
- The terminal should return a message to say that the application is running on port 3000

## Images

<img width="1440" alt="Screenshot 2024-06-24 at 17 59 05" src="https://github.com/isazafeer/book-search-engine/assets/116819407/106f4713-8359-499e-8093-71daa28835aa">

<img width="835" alt="Screenshot 2024-06-24 at 17 59 25" src="https://github.com/isazafeer/book-search-engine/assets/116819407/9027b000-e199-4946-bf73-e0fb4afcc76d">

<img width="1423" alt="Screenshot 2024-06-24 at 18 00 56" src="https://github.com/isazafeer/book-search-engine/assets/116819407/9376b373-7c88-4de5-bef0-b0cb32338144">

Link to depolyed application:

