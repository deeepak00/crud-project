This repository contains a CRUD (Create, Read, Update, Delete) project implemented using PhpMyAdmin and XAMPP. It allows you to perform basic database operations on a web application.

Prerequisites
To run this project, you need to have the following software installed on your machine:

XAMPP: A software package that includes Apache, MySQL, and PHP. You can download it from the official website: https://www.apachefriends.org.
Setup Instructions
Follow the steps below to set up and run the CRUD project:

Clone the repository: Start by cloning this repository to your local machine using Git or by downloading the ZIP file and extracting it.

Start XAMPP: Open the XAMPP control panel and start the Apache and MySQL services.

Import the database: Open your web browser and go to http://localhost/phpmyadmin. Create a new database and import the database.sql file from the project's root directory.

Configure the database connection: In the project's root directory, open the config.php file. Update the database connection details (hostname, username, password, and database name) according to your XAMPP configuration.

Start the project: Open your web browser and go to http://localhost/crud-project (assuming you placed the project files in the crud-project directory under the web server's document root). You should see the CRUD application.

Usage
Once the project is set up and running, you can perform the following operations:

Create: Click on the "Add Record" button to create a new record in the database. Fill in the form and click "Save" to add the record.

Read: The table displayed on the main page shows the existing records in the database. You can view the details of a specific record by clicking on the "View" button.

Update: To update a record, click on the "Edit" button next to the record you want to modify. Make the necessary changes in the form and click "Save" to update the record.

Delete: To delete a record, click on the "Delete" button next to the record you want to remove. Confirm the deletion when prompted.

Contributing
If you'd like to contribute to this project, you can follow these steps:

Fork the repository on GitHub.

Create a new branch with a descriptive name for your feature or bug fix.

Make the necessary changes in your branch.

Test your changes thoroughly.

Commit your changes and push your branch to your forked repository.

Submit a pull request to the original repository, explaining your changes and providing any relevant details.

License
This project is licensed under the MIT License.

Acknowledgments
This project was developed as a learning exercise and may contain simplified code and concepts. Feel free to use it as a starting point for your own projects.
