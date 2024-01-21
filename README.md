# Spring Boot MicroServices
With the help of this repository you can run microservices using Spring Boot


The application consists of 6 different services



## <a name="application-architecture"></a>Application Architecture

![screenshot!](images/image.png)


## <a name="project-overview"></a>Project Overview
* This project that mocks an e-commerce API .

* This project uses KAFKA 


## <a name="project-run"></a>How To Run ?
* You can run the project using following steps:
    * Install latest version of **Docker**  in your machine.
    * Clone this **GIT** repository.
    * Go to directory `spring-boot-microservice` on your system.
    * Run `docker-compose up --build` and then `docker-compose up`.
 
 
## <a name="rest-end"></a>Rest End Points.

* **To create a new customer- http://localhost:8080/v1/api/customer/create** :


 
* **To create a new order- http://localhost:8080/v1/api/order/create** :
 
 
* **To get the token for secure resource- http://localhost:8080/v1/api/secure/oauth/token** :

 
* **The above end point will produce response like below** :

 

* **To access secure resource or to delete all customers- http://localhost:8080/v1/api/customer/delete/all** :
 

 
