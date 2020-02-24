### How to use this spring-boot project

- Install packages with `mvn package`
- Run `mvn spring-boot:run` for starting the application (or use your IDE)

Application (with the embedded H2 database) is ready to be used ! You can access the url below for testing it :

- Swagger UI : http://localhost:8080/swagger-ui.html
- H2 UI : http://localhost:8080/h2-console

> Don't forget to set the `JDBC URL` value as `jdbc:h2:mem:testdb` for H2 UI.



### Instructions

- Fork this project
- Enhance the code in any ways you can see, you are free!. Some possibilities:
  - add tests
  - change syntax
  - improve doc and comments
  - fix any bug you might find
- Make a PR on the original repo (`https://github.com/alj-devops/java-challenge`) from github.com
- if you think of some possible enhancement you could have made with more time, please describe it in the comment of your PR



#### Restrictions
- use java 8


#### What we will look for
- Readability of your code
- Documentation
- Comments in your code 
- Appropriate usage of spring boot
- Appropriate usage of packages
- Is the application running as expected
- No performance issues


#### Implemented
- Data Transfer Object passed around rather than Domain objects
- Uniqueness of record enforced by treating (EMPLOYEE_NAME, DEPARTMENT) as unique key pair
- Step Builders have been added for object instantiation
- Log statements and formatting
- REST endpoint made descriptive
- Request payload validation
- Exceptions thrown for invalid use cases
- Documentation of classes and methods
- Integration test added

#### TODOs
- Add authentication and authorization to the application
- Hide salary details except for Admin or HR users
- Refactor the Response from Controller to better handle exceptions
- Add Unit tests with Mocking
