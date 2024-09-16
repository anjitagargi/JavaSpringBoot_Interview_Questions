# Java Spring Boot Interview Questions and Answers

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions                                                                                                                                                                                                                         |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Basic Questions**                                                                                                                                                                                                               |
| 1   | [What is Spring Boot?](#what-is-spring-boot)                                                                                                                                                                                       |
| 2   | [What are the advantages of Spring Boot?](#what-are-the-advantages-of-spring-boot)                                                                                                                                                 |
| 3   | [What are the main features of Spring Boot?](#what-are-the-main-features-of-spring-boot)                                                                                                                                           |
| 4   | [What are the differences between Spring and Spring Boot?](#what-are-the-differences-between-spring-and-spring-boot)                                                                                                               |
| 5   | [How does Spring Boot simplify development?](#how-does-spring-boot-simplify-development)                                                                                                                                           |
| 6   | [How to create a Spring Boot application using Maven?](#how-to-create-a-spring-boot-application-using-maven)                                                                                                                       |
| 7   | [How to create a Spring Boot project using Spring Initializer?](#how-to-create-a-spring-boot-project-using-spring-initializer)                                                                                                      |
| 8   | [How do you create a simple Spring Boot application?](#how-do-you-create-a-simple-spring-boot-application)                                                                                                                         |
| 9   | [What are Spring Boot Starters?](#what-are-spring-boot-starters)                                                                                                                                                                   |
| 10  | [What is the use of the @SpringBootApplication annotation?](#what-is-the-use-of-the-springbootapplication-annotation)                                                                                                               |
| 11  | [What is the Spring Initializr?](#what-is-the-spring-initializr)                                                                                                                                                                   |
| 12  | [What are the Spring Boot annotations?](#what-are-the-spring-boot-annotations)                                                                                                                                                     |
| 13  | [What is Spring Boot dependency management?](#what-is-spring-boot-dependency-management)                                                                                                                                           |
| 14  | [What are the Spring Boot properties?](#what-are-the-spring-boot-properties)                                                                                                                                                       |
| 15  | [What are Spring Boot starters?](#what-are-spring-boot-starters)                                                                                                                                                                   |
| 16  | [What is Spring Boot Actuator?](#what-is-spring-boot-actuator)                                                                                                                                                                     |
| 17  | [How to connect Spring Boot to the database using JPA?](#how-to-connect-spring-boot-to-the-database-using-jpa)                                                                                                                     |
| 18  | [How to connect Spring Boot application to a database using JDBC?](#how-to-connect-spring-boot-application-to-a-database-using-jdbc)                                                                                               |
| 19  | [What is @RestController annotation in Spring Boot?](#what-is-restcontroller-annotation-in-spring-boot)                                                                                                                           |
| 20  | [What is @RequestMapping annotation in Spring Boot?](#what-is-requestmapping-annotation-in-spring-boot)                                                                                                                           |
| 21  | [How does Spring Boot simplify dependency management?](#how-does-spring-boot-simplify-dependency-management)                                                                                                                       |
| 22  | [What is the role of embedded servers in Spring Boot?](#what-is-the-role-of-embedded-servers-in-spring-boot)                                                                                                                       |
| 23  | [What are Profiles in Spring Boot?](#what-are-profiles-in-spring-boot)                                                                                                                                                             |
|     | **Intermediate Questions**                                                                                                                                                                                                        |
| 1   | [What are the basic Spring Boot annotations?](#what-are-the-basic-spring-boot-annotations)                                                                                                                                         |
| 2   | [Is it possible to change the port of the embedded Tomcat server in Spring Boot?](#is-it-possible-to-change-the-port-of-the-embedded-tomcat-server-in-spring-boot)                                                                 |
| 3   | [What is the starter dependency of the Spring Boot module?](#what-is-the-starter-dependency-of-the-spring-boot-module)                                                                                                             |
| 4   | [What is the default port of Tomcat in Spring Boot?](#what-is-the-default-port-of-tomcat-in-spring-boot)                                                                                                                           |
| 5   | [Can we disable the default web server in the Spring Boot application?](#can-we-disable-the-default-web-server-in-the-spring-boot-application)                                                                                     |
| 6   | [How to disable a specific auto-configuration class?](#how-to-disable-a-specific-auto-configuration-class)                                                                                                                         |
| 7   | [Can we create a non-web application in Spring Boot?](#can-we-create-a-non-web-application-in-spring-boot)                                                                                                                         |
| 8   | [Explain @RestController annotation in Spring Boot.](#explain-restcontroller-annotation-in-spring-boot)                                                                                                                            |
| 9   | [Difference between @Controller and @RestController?](#difference-between-controller-and-restcontroller)                                                                                                                           |
| 10  | [What is the difference between RequestMapping and GetMapping?](#what-is-the-difference-between-requestmapping-and-getmapping)                                                                                                     |
| 11  | [What are Profiles in Spring Boot?](#what-are-profiles-in-spring-boot)                                                                                                                                                             |
| 12  | [How do you enable Actuator in the Spring Boot application?](#how-do-you-enable-actuator-in-the-spring-boot-application)                                                                                                           |
| 13  | [How do you handle exceptions in a Spring Boot application?](#how-do-you-handle-exceptions-in-a-spring-boot-application)                                                                                                           |
| 14  | [What is Swagger in Spring Boot?](#what-is-swagger-in-spring-boot)                                                                                                                                                                 |
| 15  | [How do you implement security in a Spring Boot application?](#how-do-you-implement-security-in-a-spring-boot-application)                                                                                                         |
| 16  | [What are the different ways to configure Spring Boot applications?](#what-are-the-different-ways-to-configure-spring-boot-applications)                                                                                           |
| 17  | [What is Spring Data JPA, and how does it differ from Hibernate?](#what-is-spring-data-jpa-and-how-does-it-differ-from-hibernate)                                                                                                   |
| 18  | [How do you use Spring Boot with Docker?](#how-do-you-use-spring-boot-with-docker)                                                                                                                                                 |
| 19  | [What is the difference between @Component, @Service, and @Repository annotations?](#what-is-the-difference-between-component-service-and-repository-annotations)                                                                   |
| 20  | [How do you test RESTful services in Spring Boot?](#how-do-you-test-restful-services-in-spring-boot)                                                                                                                               |
| 21  | [How do you configure multiple data sources in Spring Boot?](#how-do-you-configure-multiple-data-sources-in-spring-boot)                                                                                                           |
| 22  | [What is the role of the Spring Boot Actuator?](#what-is-the-role-of-the-spring-boot-actuator)                                                                                                                                     |
| 23  | [How do you integrate Kafka with Spring Boot?](#how-do-you-integrate-kafka-with-spring-boot)                                                                                                                                       |
|     | **Advanced Questions**                                                                                                                                                                                                            |
| 1   | [What are the annotations used to create an Interceptor in Spring Boot?](#what-are-the-annotations-used-to-create-an-interceptor-in-spring-boot)                                                                                   |
| 2   | [What is the purpose of Swagger in Spring Boot?](#what-is-the-purpose-of-swagger-in-spring-boot)                                                                                                                                   |
| 3   | [What are the differences between Spring Data JPA and Hibernate?](#what-are-the-differences-between-spring-data-jpa-and-hibernate)                                                                                                 |
| 4   | [How do you use Spring Boot with Docker?](#how-do-you-use-spring-boot-with-docker)                                                                                                                                                 |
| 5   | [How to implement caching in Spring Boot?](#how-to-implement-caching-in-spring-boot)                                                                                                                                               |
| 6   | [How to configure Spring Boot for asynchronous processing?](#how-to-configure-spring-boot-for-asynchronous-processing)                                                                                                             |
| 7   | [How do you configure multiple data sources in Spring Boot?](#how-do-you-configure-multiple-data-sources-in-spring-boot)                                                                                                           |
| 8   | [What is the purpose of @ComponentScan in the class files?](#what-is-the-purpose-of-componentscan-in-the-class-files)                                                                                                              |
| 9   | [How to monitor a Spring Boot application using Actuator?](#how-to-monitor-a-spring-boot-application-using-actuator)                                                                                                               |
| 10  | [How do you implement distributed tracing in a Spring Boot application using OpenTelemetry?](#how-do-you-implement-distributed-tracing-in-a-spring-boot-application-using-opentelemetry)                                           |
| 11  | [How do you enable HTTPS in a Spring Boot application?](#how-do-you-enable-https-in-a-spring-boot-application)                                                                                                                     |
| 12  | [How to configure custom health checks in Spring Boot Actuator?](#how-to-configure-custom-health-checks-in-spring-boot-actuator)                                                                                                   |
| 13  | [How to configure Spring Boot to send and receive messages from an external messaging system like RabbitMQ?](#how-to-configure-spring-boot-to-send-and-receive-messages-from-an-external-messaging-system-like-rabbitmq)           |

</details>

## Core Spring Boot
1. ### What is Spring Boot?

   Spring Boot is an **open-source framework** built on top of the Spring Framework that simplifies the development of Java-based applications. It is designed to make it easier to create stand-alone, production-grade Spring-based applications with minimal configuration.

   **[⬆ Back to Top](#table-of-contents)**

2. ### What are the advantages of Spring Boot?

   The main advantages of Spring Boot include:

   - **Auto-configuration**: Automatically configures Spring and third-party libraries based on project dependencies.
   - **Standalone**: Spring Boot applications can run as standalone Java applications.
   - **Production-ready**: Includes features like metrics, health checks, and externalized configuration.
   - **Microservice-ready**: Ideal for building microservices due to its lightweight and modular design.

   **[⬆ Back to Top](#table-of-contents)**

3. ### What are the main features of Spring Boot?

   Major features of Spring Boot are:

   - **Auto-configuration**: Automatically configures your Spring application based on the dependencies you have added.
   - **Standalone**: Spring Boot applications can be run from the command line.
   - **Production-ready**: Includes built-in features for monitoring and managing your application.
   - **Microservices**: Facilitates building microservices with minimal configuration.

   **[⬆ Back to Top](#table-of-contents)**

4. ### What are the differences between Spring and Spring Boot?

   - **Configuration**: Spring requires extensive XML configuration or Java-based configuration. Spring Boot offers auto-configuration and minimal setup.
   - **Setup**: Spring projects typically need manual setup and configuration, while Spring Boot provides default configurations and embedded servers.
   - **Dependencies**: Spring Boot includes a variety of dependencies and auto-configuration out of the box, reducing the need for manual dependency management.

   **[⬆ Back to Top](#table-of-contents)**

5. ### How does Spring Boot simplify development?

   Spring Boot simplifies development by:

   - **Reducing Configuration**: Provides default configurations and auto-configuration options.
   - **Embedded Servers**: Includes embedded servers like Tomcat, Jetty, or Undertow, eliminating the need for external server setup.
   - **Spring Boot Starter Projects**: Offers pre-configured dependency sets for common tasks.

   **[⬆ Back to Top](#table-of-contents)**

6. ### How to create a Spring Boot application using Maven?

   To create a Spring Boot application using Maven, follow these steps:

   1. Add the Spring Boot dependencies to your `pom.xml`:
   
      ```xml
      <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter</artifactId>
      </dependency>
      ```

   2. Create the main application class with `@SpringBootApplication` annotation:

      ```java
      import org.springframework.boot.SpringApplication;
      import org.springframework.boot.autoconfigure.SpringBootApplication;

      @SpringBootApplication
      public class Application {
        public static void main(String[] args) {
          SpringApplication.run(Application.class, args);
        }
      }
      ```

   3. Run your application using Maven:

      ```bash
      mvn spring-boot:run
      ```

   **[⬆ Back to Top](#table-of-contents)**

7. ### How to create a Spring Boot project using Spring Initializer?

   To create a Spring Boot project using Spring Initializr:

   1. Visit [Spring Initializr](https://start.spring.io/).
   2. Choose the project metadata (e.g., Project, Language, Spring Boot version).
   3. Add dependencies.
   4. Click "Generate" to download a ZIP file containing your Spring Boot project.

   **[⬆ Back to Top](#table-of-contents)**

8. ### How do you create a simple Spring Boot application?

   To create a simple Spring Boot application:

   1. Create a new Maven project and add Spring Boot dependencies.
   2. Create a main application class with `@SpringBootApplication`.

      ```java
      import org.springframework.boot.SpringApplication;
      import org.springframework.boot.autoconfigure.SpringBootApplication;

      @SpringBootApplication
      public class Application {
        public static void main(String[] args) {
          SpringApplication.run(Application.class, args);
        }
      }
      ```

   3. Create a REST controller:

      ```java
      import org.springframework.web.bind.annotation.GetMapping;
      import org.springframework.web.bind.annotation.RequestMapping;
      import org.springframework.web.bind.annotation.RestController;

      @RestController
      @RequestMapping("/api")
      public class HelloController {
        @GetMapping("/hello")
        public String sayHello() {
          return "Hello, Spring Boot!";
        }
      }
      ```

   **[⬆ Back to Top](#table-of-contents)**

9. ### What are Spring Boot Starters?

    Spring Boot Starters are a set of convenient dependency descriptors you can include in your application. They simplify the process of adding commonly used dependencies.

    Example of including a Spring Boot Starter in `pom.xml`:

    ```xml
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    ```

    **[⬆ Back to Top](#table-of-contents)**

10. ### What is the use of the @SpringBootApplication annotation?

    The `@SpringBootApplication` annotation is used to mark the main class of a Spring Boot application. It combines the following annotations:

    - `@Configuration`
    - `@EnableAutoConfiguration`
    - `@ComponentScan`

    It enables auto-configuration and component scanning.

    **[⬆ Back to Top](#table-of-contents)**

11. ### What is the Spring Initializr?

    The Spring Initializr is an online tool that helps generate a Spring Boot project with the desired configuration and dependencies. You can access it at [start.spring.io](https://start.spring.io/).

    **[⬆ Back to Top](#table-of-contents)**

12. ### What are the Spring Boot annotations?

    Key Spring Boot annotations include:

    - `@SpringBootApplication`
    - `@RestController`
    - `@RequestMapping`
    - `@Service`
    - `@Repository`
    - `@Configuration`

    **[⬆ Back to Top](#table-of-contents)**

13. ### What is Spring Boot dependency management?

    Spring Boot manages dependencies by providing default versions and configurations for commonly used libraries through its starter dependencies. It helps avoid version conflicts and simplifies dependency management.

    **[⬆ Back to Top](#table-of-contents)**

14. ### What are the Spring Boot properties?

    Spring Boot properties are configuration settings that can be defined in `application.properties` or `application.yml` files to customize the behavior of your application.

    Example of `application.properties`:

    ```properties
    server.port=8081
    spring.datasource.url=jdbc:mysql://localhost:3306/mydb
    ```

    **[⬆ Back to Top](#table-of-contents)**

15. ### What are Spring Boot starters?

    Spring Boot starters are pre-configured dependency sets for common application needs. They simplify dependency management by grouping related dependencies into a single artifact.

    **[⬆ Back to Top](#table-of-contents)**

16. ### What is Spring Boot Actuator?

    Spring Boot Actuator provides production-ready features such as monitoring, metrics, and health checks. It helps in managing and monitoring your application in production environments.

    **[⬆ Back to Top](#table-of-contents)**

17. ### How to connect Spring Boot to the database using JPA?

    To connect Spring Boot to a database using JPA:

    1. Add JPA and database dependencies to `pom.xml`:

       ```xml
       <dependency>
         <groupId>org.springframework.boot</groupId>
         <artifactId>spring-boot-starter-data-jpa</artifactId>
       </dependency>
       <dependency>
         <groupId>com.h2database</groupId>
         <artifactId>h2</artifactId>
         <scope>runtime</scope>
       </dependency>
       ```

    2. Configure database settings in `application.properties`:

       ```properties
       spring.datasource.url=jdbc:h2:mem:testdb
       spring.datasource.driver-class-name=org.h2.Driver
       spring.datasource.username=sa
       spring.datasource.password=password
       spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
       ```

    3. Create JPA entity and repository:

       ```java
       @Entity
       public class User {
         @Id
         @GeneratedValue(strategy = GenerationType.AUTO)
         private Long id;
         private String name;
         // Getters and setters
       }

       public interface UserRepository extends JpaRepository<User, Long> {}
       ```

    **[⬆ Back to Top](#table-of-contents)**

18. ### How to connect Spring Boot application to a database using JDBC?

    To connect Spring Boot to a database using JDBC:

    1. Add JDBC dependency to `pom.xml`:

       ```xml
       <dependency>
         <groupId>org.springframework.boot</groupId>
         <artifactId>spring-boot-starter-jdbc</artifactId>
       </dependency>
       ```

    2. Configure database settings in `application.properties`:

       ```properties
       spring.datasource.url=jdbc:mysql://localhost:3306/mydb
       spring.datasource.username=root
       spring.datasource.password=root
       ```

    3. Create a `JdbcTemplate` bean:

       ```java
       import org.springframework.context.annotation.Bean;
       import org.springframework.context.annotation.Configuration;
       import org.springframework.jdbc.core.JdbcTemplate;
       import javax.sql.DataSource;

       @Configuration
       public class DataSourceConfig {
         @Bean
         public JdbcTemplate jdbcTemplate(DataSource dataSource) {
           return new JdbcTemplate(dataSource);
         }
       }
       ```

    **[⬆ Back to Top](#table-of-contents)**

19. ### What is @RestController annotation in Spring Boot?

    The `@RestController` annotation is a combination of `@Controller` and `@ResponseBody`. It is used to create RESTful web services by marking a class as a web controller where every method returns a domain object instead of a view.

    Example:

    ```java
    import org.springframework.web.bind.annotation.GetMapping;
    import org.springframework.web.bind.annotation.RequestMapping;
    import org.springframework.web.bind.annotation.RestController;

    @RestController
    @RequestMapping("/api")
    public class HelloController {
      @GetMapping("/hello")
      public String sayHello() {
        return "Hello, Spring Boot!";
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

20. ### What is @RequestMapping annotation in Spring Boot?

    The `@RequestMapping` annotation is used to map web requests to specific handler methods. It can be used at the class or method level to define the URL patterns for which the methods should be invoked.

    Example:

    ```java
    import org.springframework.web.bind.annotation.GetMapping;
    import org.springframework.web.bind.annotation.RequestMapping;
    import org.springframework.web.bind.annotation.RestController;

    @RestController
    @RequestMapping("/api")
    public class HelloController {
      @GetMapping("/hello")
      public String sayHello() {
        return "Hello, Spring Boot!";
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

21. ### How does Spring Boot simplify dependency management?

    Spring Boot simplifies dependency management by:

    - **Providing Starters**: Pre-configured dependency sets for common use cases.
    - **Auto-Configuration**: Automatically configures application components based on the included dependencies.
    - **Dependency Management**: Uses dependency management to handle version conflicts and ensure compatibility.

    **[⬆ Back to Top](#table-of-contents)**

22. ### What is the role of embedded servers in Spring Boot?

    Embedded servers in Spring Boot allow applications to be run as standalone Java applications. Spring Boot includes embedded servers like Tomcat, Jetty, and Undertow, which simplifies deployment and reduces the need for external web server setup.

    **[⬆ Back to Top](#table-of-contents)**

23. ### What are Profiles in Spring Boot?

    Profiles in Spring Boot are used to segregate parts of your application configuration and make it only available in certain environments. They help in managing different configurations for development, testing, and production.

    Example of using profiles:

    ```properties
    # application-dev.properties
    server.port=8081

    # application-prod.properties
    server.port=80
    ```

    **[⬆ Back to Top](#table-of-contents)**

## Intermediate Questions

1. ### What are the basic Spring Boot annotations?

    Basic Spring Boot annotations include:

    - `@SpringBootApplication`
    - `@RestController`
    - `@Service`
    - `@Repository`
    - `@Configuration`
    - `@Component`

    **[⬆ Back to Top](#table-of-contents)**

2. ### Is it possible to change the port of the embedded Tomcat server in Spring Boot?

    Yes, you can change the port of the embedded Tomcat server by setting the `server.port` property in `application.properties`:

    ```properties
    server.port=8081
    ```

    **[⬆ Back to Top](#table-of-contents)**

3. ### What is the starter dependency of the Spring Boot module?

    A Spring Boot starter is a dependency descriptor that simplifies adding common dependencies. For example, `spring-boot-starter-web` is used for building web applications:

    ```xml
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    ```

    **[⬆ Back to Top](#table-of-contents)**

4. ### What is the default port of Tomcat in Spring Boot?

    The default port of Tomcat in Spring Boot is `8080`. You can change it by setting the `server.port` property in `application.properties`:

    ```properties
    server.port=8081
    ```

    **[⬆ Back to Top](#table-of-contents)**

5. ### Can we disable the default web server in the Spring Boot application?

    Yes, you can disable the default web server in a Spring Boot application by using the `spring.main.web-application-type` property. Set it to `none`:

    ```properties
    spring.main.web-application-type=none
    ```

    **[⬆ Back to Top](#table-of-contents)**

6. ### How to disable a specific auto-configuration class?

    You can exclude a specific auto-configuration class by using the `@SpringBootApplication` annotation with the `exclude` attribute:

    ```java
    @SpringBootApplication(exclude = {DataSourceAutoConfiguration.class})
    public class MyApplication {
      public static void main(String[] args) {
        SpringApplication.run(MyApplication.class, args);
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

7. ### Can we create a non-web application in Spring Boot?

    Yes, you can create a non-web application in Spring Boot by setting the `spring.main.web-application-type` property to `none` in `application.properties`:

    ```properties
    spring.main.web-application-type=none
    ```

    **[⬆ Back to Top](#table-of-contents)**

8. ### Explain @RestController annotation in Spring Boot.

    The `@RestController` annotation combines `@Controller` and `@ResponseBody`. It is used to create RESTful web services where each method returns a domain object instead of a view. The response is serialized directly to JSON or XML.

    Example:

    ```java
    @RestController
    @RequestMapping("/api")
    public class HelloController {
      @GetMapping("/hello")
      public String sayHello() {
        return "Hello, Spring Boot!";
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

9. ### Difference between @Controller and @RestController?

    - `@Controller`: Used for creating web controllers that return views (HTML, JSP). Methods typically return the name of a view to be rendered.
    - `@RestController`: Used for creating RESTful web services. Methods return domain objects, and the response is serialized to JSON or XML.

    **[⬆ Back to Top](#table-of-contents)**

10. ### What is the difference between RequestMapping and GetMapping?

    - `@RequestMapping`: Can be used to map HTTP requests to specific handler methods, supporting all HTTP methods (GET, POST, PUT, DELETE, etc.).
    - `@GetMapping`: A specialized version of `@RequestMapping` for handling GET requests.

    Example:

    ```java
    @RequestMapping("/api")
    public class MyController {
      @GetMapping("/hello")
      public String hello() {
        return "Hello!";
      }

      @PostMapping("/hello")
      public String createHello() {
        return "Created!";
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

11. ### What are Profiles in Spring Boot?

    Profiles in Spring Boot allow you to segregate application configuration and make it available only in specific environments. You can define different properties for different profiles (e.g., `dev`, `test`, `prod`).

    Example:

    ```properties
    # application-dev.properties
    server.port=8081

    # application-prod.properties
    server.port=80
    ```

    To activate a profile, use:

    ```properties
    spring.profiles.active=dev
    ```

    **[⬆ Back to Top](#table-of-contents)**

12. ### How do you enable Actuator in the Spring Boot application?

    To enable Actuator, add the `spring-boot-starter-actuator` dependency to your `pom.xml`:

    ```xml
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-actuator</artifactId>
    </dependency>
    ```

    You can then access actuator endpoints such as `/actuator/health` and `/actuator/info`.

    **[⬆ Back to Top](#table-of-contents)**

13. ### How do you handle exceptions in a Spring Boot application?

    You can handle exceptions using `@ControllerAdvice` and `@ExceptionHandler` annotations:

    ```java
    @ControllerAdvice
    public class GlobalExceptionHandler {
      @ExceptionHandler(Exception.class)
      public ResponseEntity<String> handleException(Exception ex) {
        return new ResponseEntity<>("An error occurred: " + ex.getMessage(), HttpStatus.INTERNAL_SERVER_ERROR);
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

14. ### What is Swagger in Spring Boot?

    Swagger is a tool used to document and test RESTful APIs. In Spring Boot, you can integrate Swagger using the `springfox-swagger2` and `springfox-swagger-ui` dependencies.

    Example configuration:

    ```xml
    <dependency>
      <groupId>io.springfox</groupId>
      <artifactId>springfox-swagger2</artifactId>
      <version>2.9.2</version>
    </dependency>
    <dependency>
      <groupId>io.springfox</groupId>
      <artifactId>springfox-swagger-ui</artifactId>
      <version>2.9.2</version>
    </dependency>
    ```

    **[⬆ Back to Top](#table-of-contents)**

15. ### How do you implement security in a Spring Boot application?

    To implement security, add the `spring-boot-starter-security` dependency. Then, configure security settings using `@Configuration` and `@EnableWebSecurity`:

    ```java
    @Configuration
    @EnableWebSecurity
    public class SecurityConfig extends WebSecurityConfigurerAdapter {
      @Override
      protected void configure(HttpSecurity http) throws Exception {
        http
          .authorizeRequests()
            .anyRequest().authenticated()
            .and()
          .formLogin();
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

16. ### What are the different ways to configure Spring Boot applications?

    Spring Boot applications can be configured using:

    - `application.properties` or `application.yml` files
    - Command-line arguments
    - Environment variables
    - Java configuration classes with `@Configuration` and `@Bean`

    **[⬆ Back to Top](#table-of-contents)**

17. ### What is Spring Data JPA, and how does it differ from Hibernate?

    Spring Data JPA is a part of the Spring Data project that simplifies database access and integrates JPA with Spring. Hibernate is a JPA implementation. Spring Data JPA provides additional functionality like repositories and query methods to ease data access.

    **[⬆ Back to Top](#table-of-contents)**

18. ### How do you use Spring Boot with Docker?

    To use Spring Boot with Docker, create a `Dockerfile`:

    ```dockerfile
    FROM openjdk:17-jdk
    COPY target/myapp.jar /myapp.jar
    ENTRYPOINT ["java", "-jar", "/myapp.jar"]
    ```

    Build and run the Docker image:

    ```bash
    docker build -t myapp .
    docker run -p 8080:8080 myapp
    ```

    **[⬆ Back to Top](#table-of-contents)**

19. ### What is the difference between @Component, @Service, and @Repository annotations?

    - `@Component`: Generic stereotype for any Spring-managed component.
    - `@Service`: Specialized form of `@Component`, typically used for service-layer beans.
    - `@Repository`: Specialized form of `@Component`, used for data access layer beans with additional exception translation capabilities.

    **[⬆ Back to Top](#table-of-contents)**

20. ### How do you test RESTful services in Spring Boot?

    You can test RESTful services using `@WebMvcTest` or `@SpringBootTest` with tools like `MockMvc`:

    ```java
    @WebMvcTest(HelloController.class)
    public class HelloControllerTest {
      @Autowired
      private MockMvc mockMvc;

      @Test
      public void testHello() throws Exception {
        mockMvc.perform(get("/api/hello"))
          .andExpect(status().isOk())
          .andExpect(content().string("Hello, Spring Boot!"));
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

21. ### How do you configure multiple data sources in Spring Boot?

    To configure multiple data sources, define multiple `DataSource` beans and use `@Primary` to indicate the default one:

    ```java
    @Configuration
    public class DataSourceConfig {
      @Bean
      @Primary
      @ConfigurationProperties("spring.datasource.primary")
      public DataSource primaryDataSource() {
        return DataSourceBuilder.create().build();
      }

      @Bean
      @ConfigurationProperties("spring.datasource.secondary")
      public DataSource secondaryDataSource() {
        return DataSourceBuilder.create().build();
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

22. ### What is the purpose of the @Autowired annotation?

    The `@Autowired` annotation is used for dependency injection. It allows Spring to automatically inject the required dependencies into a bean.

    **[⬆ Back to Top](#table-of-contents)**

23. ### How do you handle CORS in Spring Boot?

    You can handle CORS by configuring it globally or at the controller level. For global configuration:

    ```java
    @Configuration
    public class WebConfig implements WebMvcConfigurer {
      @Override
      public void addCorsMappings(CorsRegistry registry) {
        registry.addMapping("/**")
          .allowedOrigins("http://localhost:3000")
          .allowedMethods("GET", "POST", "PUT", "DELETE");
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

## Advanced Question

1. ### What are the annotations used to create an Interceptor in Spring Boot?

    To create an Interceptor, use the `@Component` annotation to define it as a Spring bean and implement the `HandlerInterceptor` interface:

    ```java
    @Component
    public class MyInterceptor implements HandlerInterceptor {
      @Override
      public boolean preHandle(HttpServletRequest request, HttpServletResponse response, Object handler) throws Exception {
        // Logic before the request is handled
        return true;
      }
    
      @Override
      public void postHandle(HttpServletRequest request, HttpServletResponse response, Object handler, ModelAndView modelAndView) throws Exception {
        // Logic after the request is handled
      }
    
      @Override
      public void afterCompletion(HttpServletRequest request, HttpServletResponse response, Object handler, Exception ex) throws Exception {
        // Logic after the request completes
      }
    }
    ```

    Register the interceptor with Spring:

    ```java
    @Configuration
    public class WebConfig implements WebMvcConfigurer {
      @Autowired
      private MyInterceptor myInterceptor;

      @Override
      public void addInterceptors(InterceptorRegistry registry) {
        registry.addInterceptor(myInterceptor);
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

2. ### What is the purpose of Swagger in Spring Boot?

    Swagger is used to document and test RESTful APIs. It generates interactive API documentation and provides a user interface for testing endpoints.

    To integrate Swagger, add the following dependencies:

    ```xml
    <dependency>
      <groupId>io.springfox</groupId>
      <artifactId>springfox-swagger2</artifactId>
      <version>2.9.2</version>
    </dependency>
    <dependency>
      <groupId>io.springfox</groupId>
      <artifactId>springfox-swagger-ui</artifactId>
      <version>2.9.2</version>
    </dependency>
    ```

    Configure Swagger:

    ```java
    @Configuration
    @EnableSwagger2
    public class SwaggerConfig {
      @Bean
      public Docket api() {
        return new Docket(DocumentationType.SWAGGER_2)
          .select()
          .apis(RequestHandlerSelectors.any())
          .paths(PathSelectors.any())
          .build();
      }
    }
    ```

    Access the Swagger UI at `/swagger-ui.html`.

    **[⬆ Back to Top](#table-of-contents)**

3. ### What are the differences between Spring Data JPA and Hibernate?

    - **Spring Data JPA**: A part of Spring that simplifies data access and integrates JPA with Spring. It provides a repository abstraction and various query methods.
    - **Hibernate**: A JPA implementation that provides ORM capabilities for mapping Java objects to database tables. Spring Data JPA can use Hibernate as the JPA provider.

    **[⬆ Back to Top](#table-of-contents)**

4. ### How do you use Spring Boot with Docker?

    To use Spring Boot with Docker, create a `Dockerfile` in the root of your project:

    ```dockerfile
    FROM openjdk:17-jdk
    COPY target/myapp.jar /myapp.jar
    ENTRYPOINT ["java", "-jar", "/myapp.jar"]
    ```

    Build and run the Docker image:

    ```bash
    docker build -t myapp .
    docker run -p 8080:8080 myapp
    ```

    **[⬆ Back to Top](#table-of-contents)**

5. ### How to implement caching in Spring Boot?

    To implement caching, add the `spring-boot-starter-cache` dependency and enable caching with `@EnableCaching`:

    ```xml
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-cache</artifactId>
    </dependency>
    ```

    ```java
    @Configuration
    @EnableCaching
    public class CacheConfig {
    }
    ```

    Use the `@Cacheable` annotation to cache method results:

    ```java
    @Service
    public class MyService {
      @Cacheable("myCache")
      public String getCachedValue(String key) {
        // Method logic
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

6. ### How to configure Spring Boot for asynchronous processing?

    Enable asynchronous processing with `@EnableAsync` and use `@Async` for asynchronous methods:

    ```java
    @Configuration
    @EnableAsync
    public class AsyncConfig {
    }
    ```

    ```java
    @Service
    public class MyService {
      @Async
      public CompletableFuture<String> asyncMethod() {
        // Asynchronous logic
        return CompletableFuture.completedFuture("result");
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

7. ### How do you configure multiple data sources in Spring Boot?

    Define multiple `DataSource` beans in a configuration class:

    ```java
    @Configuration
    public class DataSourceConfig {
      @Bean
      @Primary
      @ConfigurationProperties("spring.datasource.primary")
      public DataSource primaryDataSource() {
        return DataSourceBuilder.create().build();
      }

      @Bean
      @ConfigurationProperties("spring.datasource.secondary")
      public DataSource secondaryDataSource() {
        return DataSourceBuilder.create().build();
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

8. ### What is the purpose of @ComponentScan in the class files?

    The `@ComponentScan` annotation is used to specify the packages to scan for Spring components, such as `@Component`, `@Service`, `@Repository`, and `@Controller`.

    ```java
    @Configuration
    @ComponentScan(basePackages = "com.example.myapp")
    public class AppConfig {
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

9. ### How to monitor a Spring Boot application using Actuator?

    Spring Boot Actuator provides monitoring endpoints. Enable it by adding the `spring-boot-starter-actuator` dependency:

    ```xml
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-actuator</artifactId>
    </dependency>
    ```

    Access endpoints like `/actuator/health` and `/actuator/metrics` to monitor the application.

    **[⬆ Back to Top](#table-of-contents)**

10. ### How do you implement distributed tracing in a Spring Boot application using OpenTelemetry?

    Add dependencies for OpenTelemetry and configure it:

    ```xml
    <dependency>
      <groupId>io.opentelemetry</groupId>
      <artifactId>opentelemetry-sdk-extension-autoconfigure-spring-boot</artifactId>
      <version>1.7.2</version>
    </dependency>
    ```

    Configure OpenTelemetry in `application.properties`:

    ```properties
    otel.exporter.otlp.endpoint=http://localhost:4317
    ```

    Use the OpenTelemetry API to instrument your code.

    **[⬆ Back to Top](#table-of-contents)**

11. ### How do you enable HTTPS in a Spring Boot application?

    To enable HTTPS, configure SSL in `application.properties`:

    ```properties
    server.port=8443
    server.ssl.key-store=classpath:keystore.p12
    server.ssl.key-store-password=password
    server.ssl.key-store-type=PKCS12
    ```

    Place the `keystore.p12` file in `src/main/resources`.

    **[⬆ Back to Top](#table-of-contents)**

12. ### What is Spring Boot WebFlux?

    Spring Boot WebFlux is a reactive web framework that supports non-blocking and asynchronous processing. It is an alternative to the traditional Spring MVC framework for building reactive applications.

    **[⬆ Back to Top](#table-of-contents)**

13. ### What is reactive programming in Spring Boot?

    Reactive programming is a paradigm that deals with asynchronous data streams and the propagation of changes. Spring Boot supports reactive programming with the Reactor framework.

    **[⬆ Back to Top](#table-of-contents)**

14. ### How do you deploy a Spring Boot application as a WAR file?

    To deploy as a WAR file, modify `pom.xml` to package the application as a WAR:

    ```xml
    <packaging>war</packaging>
    ```

    Extend `SpringBootServletInitializer` in your main application class:

    ```java
    @SpringBootApplication
    public class MyApplication extends SpringBootServletInitializer {
      @Override
      protected SpringApplicationBuilder configure(SpringApplicationBuilder application) {
        return application.sources(MyApplication.class);
      }

      public static void main(String[] args) {
        SpringApplication.run(MyApplication.class, args);
      }
    }
    ```

    Build the WAR file with:

    ```bash
    mvn clean package
    ```

    **[⬆ Back to Top](#table-of-contents)**

15. ### How do you integrate Spring Boot with RabbitMQ?

    Add the `spring-boot-starter-amqp` dependency:

    ```xml
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-amqp</artifactId>
    </dependency>
    ```

    Configure RabbitMQ settings in `application.properties`:

    ```properties
    spring.rabbitmq.host=localhost
    spring.rabbitmq.port=5672
    ```

    Define a message listener:

    ```java
    @Component
    public class MyMessageListener {
      @RabbitListener(queues = "myQueue")
      public void receiveMessage(String message) {
        System.out.println("Received: " + message);
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

16. ### How do you configure a data source in Spring Boot?

    Configure the data source in `application.properties`:

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/mydb
    spring.datasource.username=root
    spring.datasource.password=password
    ```

    **[⬆ Back to Top](#table-of-contents)**

17. ### How do you use Spring Boot with Kubernetes?

    Create a Docker image of your Spring Boot application and deploy it on Kubernetes using a YAML configuration file. Define a deployment and service in `deployment.yaml`:

    ```yaml
    apiVersion: apps/v1
    kind: Deployment
    metadata:
      name: myapp
    spec:
      replicas: 1
      selector:
        matchLabels:
          app: myapp
      template:
        metadata:
          labels:
            app: myapp
        spec:
          containers:
          - name: myapp
            image: myapp:latest
            ports:
            - containerPort: 8080
    ---
    apiVersion: v1
    kind: Service
    metadata:
      name: myapp-service
    spec:
      ports:
      - port: 80
        targetPort: 8080
      selector:
        app: myapp
    ```

    Apply the configuration with:

    ```bash
    kubectl apply -f deployment.yaml
    ```

    **[⬆ Back to Top](#table-of-contents)**

18. ### How do you secure a Spring Boot REST API using OAuth2?

    Add the `spring-boot-starter-oauth2-client` dependency:

    ```xml
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-oauth2-client</artifactId>
    </dependency>
    ```

    Configure OAuth2 client settings in `application.properties`:

    ```properties
    spring.security.oauth2.client.registration.google.client-id=your-client-id
    spring.security.oauth2.client.registration.google.client-secret=your-client-secret
    ```

    **[⬆ Back to Top](#table-of-contents)**

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊
