Installation Instructions
Follow the steps below to set up the project on your local machine.

Step 1: Clone the Project
First, clone the project from the GitHub repository to your local system by running the following command:

bash
Copy code
git clone https://github.com/unlisted02/Internet-Banking.git
Step 2: Navigate to the Project Directory
After cloning, navigate into the project directory:

bash
Copy code
cd Internet-Banking
Step 3: Move the Project Folder
Inside your XAMPP installation directory (htdocs folder), paste the extracted project folder:

Do not paste the .zip file; instead, use the extracted project folder.
For example:

plaintext
Copy code
C:\xampp\htdocs\Internet-Banking
Step 4: Set Up the Database
Open your web browser (we recommend Google Chrome or Mozilla Firefox).
Go to the following URL to access phpMyAdmin:
plaintext
Copy code
http://localhost/phpmyadmin
Create a new database using the name provided in the 01 LOGIN DETAILS & PROJECT INFO.txt file found in the project folder.
After creating the database, click on the Import tab.
Choose the .sql file located in the DATABASE FILE folder, and import it into the newly created database.
Step 5: Run the Application
Once the database is set up, open your browser and navigate to the following URL to access the Internet Banking System:

plaintext
Copy code
http://localhost/Internet-Banking
Step 6: Login
Login credentials are provided in the 01 LOGIN DETAILS & PROJECT INFO.txt file inside the project folder. Use these details to access the application.

Notes
Ensure that XAMPP or any other local server is running.
If you encounter any issues, refer to the project documentation or contact the repository owner for assistance.
