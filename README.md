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

