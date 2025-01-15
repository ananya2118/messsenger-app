To run this app :
git clone https://github.com/ananya2118/messsenger-app

open the terminal and split them and run these commands in them

Messenger-app, is a messaging application built using Java and Spring Boot. It employs a microservices architecture, with components such as a server, gateway service, and chat service. These services are managed using Maven and communicate over the network to deliver the application's functionality.
The application is launched by running each service individually using Maven commands, and it operates locally on specified ports

Key details:

Tech Stack: Java, Spring Boot, Maven
Architecture: Microservices


cd server
mvn spring-boot:run

cd gateway-service
mvn spring-boot:run

cd chat-service
mvn spring-boot:run

And you can see this services in localhost:9888 and in localhost:9990
