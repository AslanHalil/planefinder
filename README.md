planefinder is a spring boot project developed by following a book on spring boot. 
It should run simultaneously with planefider in order to to show flights.

Instructions for project to work:
1. Install Erlang.
2. Install RabbitMQ. (RabbitMQ will warn you if you don't have Erlang installed, Erlang is necessary)
3. Download aircraft-positions and planefinder repositories.
4. Run RabbitMQ. (A command prompt like interface should show up and tell you that an instance is running)
5. If your IDE supports multiple instances than you can run both projects in seperate instances of the IDE. 
   Else You can run either project in the IDE. For the other you can use the "./mvnw spring-boot:run" command in the ROOT directory (The directory that contains the mvnw file). 
