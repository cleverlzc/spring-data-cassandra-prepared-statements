## How to run application

- Clone the application
- Build the application with Maven
  ```
  mvn install
  ```
- Then just start the containers
  ```
  docker-compose up
  ```
That's all you need to do.

It will persist a record to Cassandra and print it out on the command line.

The blog post that accompanies this repository is: [Cached Prepared Statements with Spring Data Cassandra](https://lankydanblog.com/2018/10/23/cached-prepared-statements-with-spring-data-cassandra/)