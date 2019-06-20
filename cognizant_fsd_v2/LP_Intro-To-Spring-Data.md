# Database access in Java
### A long history

## Objectives
At the end of this lesson students should be able to... 
1. directly interact with with relational databases using Spring JDBC 
1. understand the difference between JDBC and JPA including when each technology should be employed.
1. be able to implement db access using JdbcTemplate
1. be able to implement db access using JPA

## Overview
* Original method for database access (just show what it looked like)
  * Download driver library, and put in classpath
  * Create a connection and open it
  * Create a prepared statement
  * Execute the statement and collect the results
  * Catch errors and respond properly
  * Finally block to close prepared statement and connection.
	
	
* Spring JDBC - JDBC Template
  * Much less stuff
	
Spring JPA 
  * Very little coding
	
Resources
	GitHub starter for labs (DB definition and data)
	
	
Instructions
1. Live code old school JDBC
1. Live code Spring JDBC using interfaces to make JPA easier
  * Note the complexities 
  * Discuss differences from old style
1. Live code previous example using JPA (like Ken's lesson)
1. Lab: Code both examples using starter
	
Additional Resources
* [Spring Data Documentation](https://spring.io/projects/spring-data)
* [Ken Kousen - Using JDBC Template](http://www.kousenit.com/springboot/#_using_the_jdbc_template)
