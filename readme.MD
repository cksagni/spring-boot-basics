# A web app to create a movie ticket booking service

# Use maven plugin to package jar
$ ./mvnw package

# to run Spring boot app from cmd line
$ java -jar target/movie-ticket-booking-0.0.1-SNAPSHOT.jar

# Use maven plugin to run the spring boot app
$ ./mvnw spring-boot:run
 
# Run and configure MySQL as a docker container
1. Install Docker
2. Run command - 
   $ docker run -d --name <container_name> -e MYSQL_ROOT_PASSWORD=<strong_password> -p 3306:3306 mysql:8.0
3. To start docker container - $ docker container start <container_name>
4. Configure mysql workbench to connect to this mysql server
