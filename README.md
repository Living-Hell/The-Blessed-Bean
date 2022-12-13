## The Blessed Bean
This fully responsive website gives information about the Coffee shop ’The Blessed Beans’ based out of Baker’s Street London.

![1](https://user-images.githubusercontent.com/74912161/196609564-9004f0c4-2f26-4999-88c2-498f91e75ad5.png)

## Features and Functionalities
  * This is an infomatory website for an imaginary Coffee Shop 'The Blessed Bean'.
  * Users can checkout about the shop in the 'About' Page.
  * The website features a member‑access blog that provides a showcase of recipes for different types of coffee blends.
  * The blogs requires user authentication in order to access it.
  * New users can register on the register page to access the blogs. 
  * The information entered during the registeration process is validated, encrypted and stored in the database for future login purpose. 
  * Exisitng users can simply login in order to view the blogs.
  * The registeration form shows error message if the data insputted in the form is incorrect in format without the page getting refreshed. 
  * Users can also contact the coffee shop through the contact page.
  * The Contact Page has a map showing the exact location of the coffee shop and email address & the phone no. of the coffee shop.
  * Users can also contact the shop regarding any query through the contact form present on the contact page.
  * The information entered into the form is validated and stored in a database for future references.
  * The message entered is also sent to a specific email address specified by the coffee shop.
  
## Development
  * This front-end layout of this website was developed using a Bootstrap theme.
  * The registeration form has PHP validation with XML integration to display error messages without getting refreshed.
  * The data was stored in a SQL database using MySQL.
  * The data is escaped of any special character using 'mysqli_escape_real_string()' to prevent SQL injection.
  * The password is hashed before storing into the database using 'password_hash()' and the 'PHP Bcrypt' method is used for encryption.
  * PHP session variables is used to indicate the status of the users.
  * For the location of the shop on the map, Google Maps API is used.
  * The PHP library 'PHP Mailer' is used to send the message from the contact page to the speciifed email address.

## Check out the website: [Link](https://the-blessed-beans.herokuapp.com/)
