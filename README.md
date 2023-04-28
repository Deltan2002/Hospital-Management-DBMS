# Hospital Management System

Hospital Management System is a web application built using MySQL, PHP, and Bootstrap. It is designed to automate various tasks performed in a hospital, including appointments, prescriptions, payments, and more.

## Areas for Improvement:

1. The system needs to be updated to allow doctors to accept or reject appointments, notifying patients of the approval status.

2. Users should not be able to register with an email address that has already been registered.

3. Passwords should be encrypted and hidden in the admin panel.

4. The addition of pagination to all the list views would improve the user experience.

5. A bug has been identified that causes multiple records to appear on bill payment receipts when a patient has seen the same doctor multiple times.

6. More fields need to be added to the prescription statement to provide additional specificity.

7. More details about payments, such as the date and amount paid, need to be included.

8. An export button needs to be added to the admin module to export all details to an Excel sheet.

## Prerequisites

Before you can run the project, you will need to have the following installed on your machine:

1. XAMPP web server
2. An editor, preferably VS Code or Sublime Text
3. A web browser with the latest version

## Languages and Technologies Used

The Hospital Management System uses the following languages and technologies:

1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. PHP
6. MySQL (An RDBMS that uses SQL)
7. TCPDF (to generate PDFs)

## Steps to Run the Project

Follow these steps to run the project on your machine:

1. Download and install XAMPP.
2. Clone or download the repository.
3. Extract all the files and move them to the 'htdocs' folder of your XAMPP directory.
4. Start Apache and MySQL in your XAMPP control panel.
5. Open your web browser and type 'localhost/phpmyadmin'.
6. In phpMyAdmin, create a new database from the left panel and name it 'myhmsdb'.
7. Import the file 'myhmsdb.sql' into your new database and click 'OK'.
8. Open a new tab and type 'localhost/foldername' in the URL of your browser.
9. Congratulations! You can now use the Hospital Management System.

### Software Used

The following software was used to build the Hospital Management System:

- XAMPP was installed on an Ubuntu 19.04 machine, and Apache2 Server and MySQL were initialized. Files were built inside opt/lampp/htdocs/myhmsp.
- Sublime Text 3.2 was used as the text editor.
- Google Chrome Version 77.0.3865.90 was used to run the project (localhost/myhmsp was used as the URL).

### Starting Apache and MySQL in XAMPP

The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.

![XAMPP Control Panel](https://user-images.githubusercontent.com/36665975/59350977-fcc68900-8d3a-11e9-9450-e5c478497caa.png)


  




