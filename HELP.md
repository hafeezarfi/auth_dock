# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.4/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.4/maven-plugin/reference/html/#build-image)
* [Spring Security](https://docs.spring.io/spring-boot/docs/3.1.4/reference/htmlsingle/index.html#web.security)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.4/reference/htmlsingle/index.html#web)

### Guides
The following guides illustrate how to use some features concretely:

* [Securing a Web Application](https://spring.io/guides/gs/securing-web/)
* [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
* [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

### Testing/ Debugging setup locally

- [Docker](https://www.docker.com/get-started/) desktop
- Create container with mysql by running below
- <code>docker run --name <container-name> -e MYSQL_ROOT_PASSWORD=yourPassword -e MYSQL_DATABASE=<database-name> -d -p 3306:3306 mysql:latest</code>
- Make sure to update password and database-name in <b>application.properties</b> located in resources as defined above.
- run the application file via intellij or follow instruction on how to run maven app
- ENDPOINTS 
  - login : http://localhost:8080/login
  - register : http://localhost:8080/register 