# Video_Game_Management_PHP_Web_App
This is my project about creating a Managing Video Game PHP Web Application

Project Description
This project involves the development of a web application for managing video game entities, encompassing the four basic CRUD (Create, Read, Update, Delete) operations. The application will store and manage data in a MySQL database and is to be developed using PHP, HTML, JavaScript, and optionally CSS. The project starts with a base of preexisting code, marked with “TODO” tags to guide further development.

Project Requirements
Technologies and Constraints:

Use PHP, HTML, JavaScript, and optionally CSS for development.
External libraries and frameworks are prohibited.
All new code must be original, except for provided exam materials.
The index page should redirect to the entity creation page.
Implement Object-oriented PHP.
Utilize a MySQL Database for data storage.
Employ parameterized SQL statements.
Use PDO for database access.
Setup:

Begin by extracting the provided project files into the htdocs directory of an XAMPP installation, ensuring the directory structure is maintained.
Modify the index page for initial setup, including personal identification and redirection functionality.
Database Creation:
Using XAMPP as MySQL Database Server Management
Create a games table with specific fields including id, title, genre, developer, release_year, and date_created.
Populate the table with initial test data for games like "Counter-Strike", "Dark Souls", and "Hearts of Iron II".
Developing the Business Logic:

Develop a VideoGame class for modeling video game entities with encapsulation for data validation.
Implement CRUD operations within the VideoGame class.
Complete the PdoConnector class for creating and managing PDO connections, utilizing configuration from a config.json file.
Develop an api.php script to handle requests for creating, updating, and deleting entities.
Entity Creation Page:

Design an HTML form for creating new game entities, with appropriate input types and client-side validation.
Implement AJAX POST requests for form submission to avoid default form behavior, facilitated by a JavaScript script in create.js.
Entity Display, Edition, and Deletion Page:

Design a page with forms for viewing, modifying, and deleting specific game entities, including server-side data retrieval based on passed IDs.
Ensure input types and client-side validation are appropriate, with certain fields made non-editable as necessary.
Use AJAX POST requests for form submissions, with JavaScript implementations in view.js.
Testing the Application:

Test the application by creating, modifying, and deleting a game record with specified values, verifying database changes at each step.
Development Workflow
Initial Setup:

Extract and organize project files according to the provided instructions.
Prepare the index page for redirection to the entity creation page.
Database Preparation:

Create the games database table and insert initial test data.
Business Logic Implementation:

Develop the VideoGame and PdoConnector classes for handling game entities and database connections.
Implement CRUD operations through an api.php endpoint.
Front-end Development:

Create the entity creation and display/edit/delete pages, ensuring interactive functionality through AJAX and adherence to input validation requirements.
Application Testing:

Conduct thorough testing to ensure all functionalities work as expected and the application interacts correctly with the database.
This project emphasizes the integration of object-oriented PHP with front-end technologies to create a functional web application for video game management, highlighting the importance of secure and efficient database interactions.
