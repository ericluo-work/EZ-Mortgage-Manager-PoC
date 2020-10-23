# EZ-Mortgage-Manager-PoC
This is EZ Mortgage Manager Proof of Concept

Caliber Home Loans is a nationwide home loan lender. EZ Mortgage Manager is a mortgage and loan account management software for loaners. This project focused on the development of the account management system. Users are able to simply view the loan balance, APR and payment due date. Moreover, users can even change payment method and contact loan consultant in EZ Mortgage Manager.

We use Spring Boot 2 to build microservices.
We use Hibernate 5 for object relational mapping to map user account, loan account model to MySQL 8 database.
We use spring security OAuth 2 to implement secured user log in functionality. 
We integrate RabbitMQ as our message broker for sending messages between loaners and loan consultants. Users would be able to contact their loan consultants through this application.
We designed web application view with Bootstrap 4. 
