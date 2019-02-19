# cse-bank-new
The objective of this projects is to develop a secure banking system. The main aim of the project is to incorporate real world banking features like money transfer, view statement and manager approvals. This report is an overview of key technologies, security aspects and also vulnerabilities or attack patterns and solutions used to prevent them in our system.

2.	Implementation 
2.1	Implementation details of Frontend

The Front end is developed using HTML and CSS. Client side interactions are handled using JavaScript along with additional libraries like AJAX, JQuery and templates like Mustache JS. Different interfaces are provided for different actors like employees, manager, admin and customers. Each user is transferred to an appropriate page based on his account credentials where he can perform a function depending on his role.
2.2	 Implementation details of Middleware
The middleware of this application is developed using Spring MVC. Controllers are written for each function which take the user input from a page, validate and process the input and call an appropriate service in the backend

2.3	Implementation details of Backend
The backend of this application is written using Java and JDBC. Service classes are written for different functionalities where every service class takes input from the middleware, processes the information, encrypts sensitive information and stores it in MySQL database 
2.4 Handling security aspects of the software
Application uses security mechanisms like public key certificate (PKI), SSL/TSL with HTTPS redirection service, One-Time Password, multiple session functionality, malicious login controls, trust management for devices, email notifications on login and many others.

                     3. Description of Results
A secure web application which satisfies all the functional and security requirements specified in design doc is developed. Upon testing from members of other groups, only two security vulnerabilities reported by them are deemed valid by our team.

           4.  Description of my Contributions to the Project
4.1 Database design: I have designed the database schema of the project with other backend team members of the project based on inputs given from front end team
4.2 Development of backend: Developed, tested and fixed errors in several modules of backend like Service classes for Users which handle the logic for user functionalities, Service classes for transactions which handle logic for money transactions.
4.3 Development of Middleware: Developed and tested few controller classes like transaction and user which handle take user input from front end and send it to backend.
4.4 Deployment and Testing: Performed end-end testing of application and contributed to deployment in Thothlab.
