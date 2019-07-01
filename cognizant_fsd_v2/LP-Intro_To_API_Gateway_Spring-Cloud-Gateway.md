# Introduction to API Gateways with Spring Cloud Gateway

### Objective

By the end of this lesson the student should be able to:
1. Describe the API Gateway pattern in general terms.
1. Understand how SCG implements the API Gateway specifically.
1. Build a SCG service that works seamlessly with JWT tokens and spring security.


## Overview
1. Show the group how jwt, scg, and spring security work together.
2. Have the class explore the sample app and apply the concepts to their projects.

### Resources
Slide Deck
[Spring Cloud Gateway Example App](https://spring.io/guides/gs/gateway/)

### Instructions

1. Present the slides.
1. Discuss why we might need a gateway
1. Possibly discuss some of the other projects in Spring Cloud and how they might fit
1. Demonstrate how the sample app works.
    1. pay special attention to the changes needed for in memory credentials.
    1. show how the login routing works (and talk through how you'd do account creation)
    1. explain how the role mappings are setup and compare and contrast how this is different from a db driven design.
    1. show how the routing table is setup and explain the difference between yaml and properites files.
1. Code review the demo app and point out the differences in how it handles the security components.
1. Challenge the class to add this approach to the user login service in their project.

## Additional Resources
