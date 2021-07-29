# DashboardCompose
Docker-compose project, for running docker-compose images.

run  {docker-compse up --build} for building and running services, include RabbitMQ image. 

After running the command on your docker, you can test it with Postman WebSocker.

Request example: 

ws://localhost:8080/connect
Accepts: "X-Forwarded-For" header : Ip address; "User-Agent" header : Client OS and Browser information.

You can see response in "dashboard-ui" - image console, as it triggered by connecting to "dashboard:api" image (ws://localhost:8080/connect);
    
