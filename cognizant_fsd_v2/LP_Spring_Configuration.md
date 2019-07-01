# Objectives
At the end of this lesson students should understand how to manage external configuration of a Spring application using the following techniques...
1. Spring's Auto Config Report
1. when/why to exclude auto-configured items
1. annotations associated with Auto Configuration
1. Override AutoConfiguration using custom configuration
1. Spring Environment Profiles 

### Overview
Time: 1 Block

To prepare students for deploying their application to other environments.  Lesson will explain how to configure Spring with, 
@SpringBootApplication (@Configuration, @ComponentScan, @EnableAutoConfiguration), and environment profiles.

### Resources
* [Slides](https://docs.google.com/presentation/d/1byt2wqDZ6YIhUTcgNvO98-K0X7JWWv1wzYnZ77pB9Ro/edit?usp=sharing)
* GitHub Project

### Instructions
1. Discuss why we might need to have different configurations for an application
1. Present Slides
1. Lab or live demo of lab
1. Debrief with cold calling to confirm objectives

### Lab - Individual or as a group
1. Create a new spring boot web app using [initializer](http://start.spring.io)
1. Generate AUTO-CONFIGURATION REPORT - Save version in project
1. Add Profiles for DEV and TEST
1. Add two @Beans one for DEV and one for TEST
1. Add custom auto configuration to @SpringBootApplication class
    * Exclude 1 or more auto configurations (be sure you don't need them) using "exclude=..."
    * Exclude 1 or more auto configuration using @OnConditional
1. Add Typesafe properties class
1. Add controller that prints out custom properties per profile (requires separate deployment)
1. Commit to a new GitHub repo and send link to instructors via slack

## Additional Resources
PluralSight Course: [Spring Boot: Efficient Development, Configuration and Deployment](https://app.pluralsight.com/library/courses/spring-boot-efficient-development-configuration-deployment)
Spring Docs: [Profiles](https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-profiles.html) 
