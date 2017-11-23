---
layout:     post
title:      Spring Master Class - Learn the magic of Spring Framework
date:       2017-10-15 12:31:19
summary:    Learn the magic of Spring Framework. From IOC (Inversion of Control), DI (Dependency Injection), Application Context to the world of Spring Boot, AOP, JDBC and JPA. Get set for an incredible journey. 
categories: Spring Boot, Spring Framework
permalink:  /spring-master-class
---

Learn the magic of Spring Framework. From IOC (Inversion of Control), DI (Dependency Injection), Application Context to the world of Spring Boot, AOP, JDBC and JPA. Get set for an incredible journey.

Spring Framework remains as popular today as it was when I first used it 12 years back. How is this possible in the incredibly dynamic world where architectures have completely changed?

## What You will learn

- You will learn the basics of Spring Framework - Dependency Injection, IOC Container, Application Context and Bean Factory.
- You will understand how to use Spring Annotations - @Autowired, @Component, @Service, @Repository, @Configuration, @Primary....
- You will understand Spring MVC in depth - DispatcherServlet , Model, Controllers and ViewResolver
- You will use a variety of Spring Boot Starters - Spring Boot Starter Web, Starter Data Jpa, Starter Test
- You will learn the basics of Spring Boot, Spring AOP, Spring JDBC and JPA
- You will learn the basics of Eclipse, Maven, JUnit and Mockito
- You will develop a basic Web application step by step using JSP Servlets and Spring MVC
- You will learn to write unit tests with XML, Java Application Contexts and Mockito

## Getting Ready

### Installing Tools

- Installation Video : https://www.youtube.com/playlist?list=PLBBog2r6uMCSmMVTW_QmDLyASBvovyAO3
- GIT Repository For Installation : https://github.com/in28minutes/getting-started-in-5-steps
- PDF : https://github.com/in28minutes/SpringIn28Minutes/blob/master/InstallationGuide-JavaEclipseAndMaven_v2.pdf

### Running Examples

- Download the zip or clone the Git repository.
- Unzip the zip file (if you downloaded one)
- Open Command Prompt and Change directory (cd) to folder containing pom.xml
- Open Eclipse 
   - File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip
   - Select the right project
- Choose the Spring Boot Application file (search for @SpringBootApplication)
- Right Click on the file and Run as Java Application
- You are all Set
- For help : use our installation guide - https://www.youtube.com/playlist?list=PLBBog2r6uMCSmMVTW_QmDLyASBvovyAO3

### Troubleshooting Guide

- [A 50 page troubleshooting guide with more than 200 Errors and Questions answered](https://github.com/in28minutes/in28minutes-initiatives/blob/master/The-in28Minutes-TroubleshootingGuide-And-FAQ)


## Step By Step Detaiils

### Spring Framework in 10 Steps
- Link - Spring Framework in 10 Steps
- Github Folder -

### Eclipse in 5 Steps
- Link - Eclipse in 5 Steps
- Github Folder -

### Maven in 5 Steps
- Link - Maven in 5 Steps
- Github Folder -

### Spring in Depth
- Step 11 - Dependency Injection - A few more examples
- Step 12 - Autowiring in Depth - by Name and @Primary
- Step 13 - Autowiring in Depth - @Qualifier annotation
- Step 14 - Scope of a Bean - Prototype and Singleton
- Step 15 - Complex scenarios with Scope of a Spring Bean - Mix of Prototype and Singleton
- Step 15B -  Difference Between Spring Singleton and GOF Singleton
- Step 16 - Using Component Scan to scan for beans
- Step 17 - Lifecycle of a Bean - @PostConstruct and @PreDestroy
- Step 18 - Container and Dependency Injection (CDI) - @Named, @Inject
- Step 19 - Removing Spring Boot in Basic Application
- Step 20 - Fixing minor stuff - Add Logback and Close Application Context
- Step 21 - Defining Spring Application Context using XML - Part 1
- Step 22 - Defining Spring Application Context using XML - Part 2
- Step 23 - Mixing XML Context with Component Scan for Beans defined with Annotations
- Step 24 - IOC Container vs Application Context vs Bean Factory
- Step 25 - @Component vs @Service vs @Repository vs @Controller
- Step 26 - Read values from external properties file

### JUnit in 5 Steps
- Link - JUnit in 5 Steps
- Github Folder -

### Mockito in 5 Steps
- Link - Mockito in 5 Steps
- Github Folder -

### Unit Testing with Spring Framework
- Step 27 - Spring Unit Testing with a Java Context
- Step 28 - Spring Unit Testing with an XML Context
- Step 29 - Spring Unit Testing with Mockito

### Basic Web Application

0000 - 09 - Section Introduction - Basic Web Application

### Steps 1 to 7 - Build a normal Web Application
- Understand Basics of HTTP 
- HttpRequest - GET/POST, Request Parameters
- HTTP Response - Response Status - 404,200,500 etc
- Introduction to JSP, Servlets,  Scriptlets and EL
- HTML Form -  Method, Action & Form Data
- Understand Basics of using Maven, Tomcat and Eclipse
- Using Request Attributes for passing Model between Servlet and View

### Steps 11 to 17 : Basics of Spring MVC
- Step 11 : Configure application to use Spring MVC
- Step 12 : First Spring MVC Controller, @ResponseBody, @Controller
- Step 13 : Redirect to Login JSP - LoginController, @ResponseBody and View Resolver
- Step 14 : DispatcherServlet and Log4j
- Step 15 : Show userid and password on the welcome page - ModelMap and @RequestParam 
- Step 16 : LoginService and Remove all JEE Servlets based code
- Step 17 : Spring Auto-wiring and Dependency Management - @Autowired and @Service

### Spring Boot in 10 Steps
- Link - Spring Boot in 5 Steps
- Github Folder -

### Spring AOP
- Step 01 - Setting up AOP Example - Part 1 
- Step 02 - Setting up AOP Example - Part 2
- Step 03 - Defining an @Before advice
- Step 04 - Understand AOP Terminology - Pointcut, Advice, Aspect, Join Point, Weaving and Weaver
- Step 05 - Using @After, @AfterReturning, @AfterThrowing advices
- Step 06 - Using @Around advice to implement performance tracing
- Step 07 - Best Practice : Use common Pointcut Configuration
- Step 08 - Quick summary of other Pointcuts
- Step 09 - Creating Custom Annotation and an Aspect for Tracking Time


### Spring JDBC and JPA
- 0000 - 12 - Section Introduction - Spring JDBC, JPA and Spring Data
- Step 01 - Setting up a project with JDBC, JPA, H2 and Web Dependencies
- Step 02 - Launching up H2 Console
- Step 03 - Creating a Database Table in H2
- Step 04 - Populate data into Person Table
- Step 05 - Implement findAll persons Spring JDBC Query Method
- Step 06 - Execute the findAll method using CommandLineRunner
- Step 07 - A Quick Review - JDBC vs Spring JDBC
- Step 08 - Whats in the background? Understanding Spring Boot Autoconfiguration
- Step 09 - Implementing findById Spring JDBC Query Method
- Step 10 - Implementing deleteById Spring JDBC Update Method
- Step 11 - Implementing insert and update Spring JDBC Update Methods
- Step 12 - Creating a custom Spring JDBC RowMapper
- Step 13 - Quick introduction to JPA
- Step 14 - Defining Person Entity
- Step 15 - Implementing findById JPA Repository Method
- Step 16 - Implementing insert and update JPA Repository Methods
- Step 17 - Implementing deleteById JPA Repository Method
- Step 18 - Implementing findAll using JPQL Named Query
- Step 19 - Introduction to Spring Data JPA
- Step 20 - Connecting to Other Databases

### Spring in depth
- Quick Review of Terminologies
 - Dependency
 - Autowiring
- How does Spring do Autowiring?
	- What are the different kinds of matching used by Spring for Autowiring?
	- Autowiring Options
	  - No Option Found
	  - Multiple Options Found
	  - One Option Found
- How do you debug problems with Spring Framework?
	- What is @Primary?
	- What is @Qualifier?
- Bean Scopes
 - Example of Prototype vs Singleton
 - What is the default scope of a bean?
	- Are Spring beans thread safe?
	- What are the other scopes available?
	- How is Spring’s singleton bean different from Gang of Four Singleton Pattern?
- What is a Component Scan? 
	- How does Spring know where to search for Components or Beans?
	- How is it done with Spring Boot?
- Bean Lifecycle
- What is CDI (Contexts and Dependency Injection)? 
	- Does Spring Support CDI?
	- Would you recommed to use CDI or Spring Annotations?
- Remove Spring Boot 
- How do you create an application context with Spring?
	- What are the different options available to create Application Contexts for Spring?
	- What is the difference between XML and Java Configurations for Spring?
	- How do you choose between XML and Java Configurations for Spring?
	- How do you define a component scan in XML and Java Configurations?
- IOC Container vs Application Context vs Bean Factory
- @Component vs @Service vs @Repository vs @Controller
- Spring Profiles
- Spring Properties

### Spring & Unit Testing
- How does Spring Framework Make Unit Testing Easy?
- What is Mockito?
- What is your favorite mocking framework?
- How do you do mock data with Mockito?

### Spring & AOP
- What are cross cutting concerns?
- How do you implement cross cutting concerns in a web application?
- If you would want to log every request to a web application, what are the options you can think of?
- If you would want to track performance of every request, what options can you think of?
- What is an Aspect and Pointcut in AOP?
- What are the different types of AOP advices?
- What is weaving?
- Compare Spring AOP vs AspectJ?

### Spring & JDBC & JPA
- Introduction to Spring JDBC
- Converting it to JPA

### Other Notes
- LEARN key Spring features: Core, Annotations, Java Config, AOP, MVC, Hibernate CRUD, Hibernate Query
- Injecting Values from a Properties File - Overview
- An Assignment

## Step By Step Notes and Code

### Spring in Depth

#### Step 11 - Dependency Injection - A few more examples

#### Step 12 - Autowiring in Depth - by Name and @Primary

#### Step 13 - Autowiring in Depth - @Qualifier annotation

```
@Component
@Scope(ConfigurableBeanFactory.SCOPE_SINGLETON)
public class BinarySearchImpl {

	@Autowired
	@Qualifier("bubble")
	private SortAlgorithm sortAlgorithm;
```

```
@Component
@Qualifier("bubble")
public class BubbleSortAlgorithm implements SortAlgorithm {
```

```
@Component
@Qualifier("quick")
public class QuickSortAlgorithm implements SortAlgorithm {
```

#### Step 14 - Scope of a Bean - Prototype and Singleton

#### Step 15 - Complex scenarios with Scope of a Spring Bean - Mix of Prototype and Singleton

```java
package com.in28minutes.spring.basics.springin5steps.scope;

import org.springframework.beans.factory.config.ConfigurableBeanFactory;
import org.springframework.context.annotation.Scope;
import org.springframework.context.annotation.ScopedProxyMode;
import org.springframework.stereotype.Component;

@Component
@Scope(value=ConfigurableBeanFactory.SCOPE_PROTOTYPE, 
		proxyMode = ScopedProxyMode.TARGET_CLASS)
public class JdbcConnection {
	public JdbcConnection() {
		System.out.println("JDBC Connection");
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps.scope;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Component;

@Component
public class PersonDAO {

	@Autowired
	JdbcConnection jdbcConnection;

	public JdbcConnection getJdbcConnection() {
		return jdbcConnection;
	}

	public void setJdbcConnection(JdbcConnection jdbcConnection) {
		this.jdbcConnection = jdbcConnection;
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;

import com.in28minutes.spring.basics.springin5steps.scope.PersonDAO;

@SpringBootApplication
public class SpringIn5StepsScopeApplication {
	
	private static Logger LOGGER = 
			LoggerFactory.getLogger(SpringIn5StepsScopeApplication.class); 
	
	public static void main(String[] args) {

		ApplicationContext applicationContext = 
				SpringApplication.run(SpringIn5StepsScopeApplication.class, args);
		
		PersonDAO personDao = 
				applicationContext.getBean(PersonDAO.class);
		
		PersonDAO personDao2 = 
				applicationContext.getBean(PersonDAO.class);
		
		LOGGER.info("{}", personDao);
		LOGGER.info("{}", personDao.getJdbcConnection());
		
		LOGGER.info("{}", personDao2);
		LOGGER.info("{}", personDao.getJdbcConnection());
		
	}
}
```

#### Step 15B -  Difference Between Spring Singleton and GOF Singleton

#### Step 16 - Using Component Scan to scan for beans

```java
package com.in28minutes.spring.basics.componentscan;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Component;

@Component
public class ComponentDAO {

	@Autowired
	ComponentJdbcConnection jdbcConnection;

	public ComponentJdbcConnection getJdbcConnection() {
		return jdbcConnection;
	}

	public void setComponentJdbcConnection(ComponentJdbcConnection jdbcConnection) {
		this.jdbcConnection = jdbcConnection;
	}
}
```

```java
package com.in28minutes.spring.basics.componentscan;

import org.springframework.beans.factory.config.ConfigurableBeanFactory;
import org.springframework.context.annotation.Scope;
import org.springframework.context.annotation.ScopedProxyMode;
import org.springframework.stereotype.Component;

@Component
@Scope(value=ConfigurableBeanFactory.SCOPE_PROTOTYPE, 
		proxyMode = ScopedProxyMode.TARGET_CLASS)
public class ComponentJdbcConnection {
	public ComponentJdbcConnection() {
		System.out.println("JDBC Connection");
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;
import org.springframework.context.annotation.ComponentScan;

import com.in28minutes.spring.basics.componentscan.ComponentDAO;

@SpringBootApplication
@ComponentScan("com.in28minutes.spring.basics.componentscan")
public class SpringIn5StepsComponentScanApplication {
	
	private static Logger LOGGER = 
			LoggerFactory.getLogger(SpringIn5StepsComponentScanApplication.class); 
	
	public static void main(String[] args) {

		ApplicationContext applicationContext = 
				SpringApplication.run(SpringIn5StepsComponentScanApplication.class, args);
		
		ComponentDAO componentDAO = 
				applicationContext.getBean(ComponentDAO.class);
		
		LOGGER.info("{}", componentDAO);
		
	}
}
```

#### Step 17 - Lifecycle of a Bean - @PostConstruct and @PreDestroy

BinarySearchImpl.java
```
	@PostConstruct
	public void postConstruct() {
		logger.info("postConstruct");
	}

	@PreDestroy
	public void preDestroy() {
		logger.info("preDestroy");
	}

```
#### Step 18 - Container and Dependency Injection (CDI) - @Named, @Inject

/pom.xml
```
<dependency>		
	<groupId>javax.inject</groupId>
	<artifactId>javax.inject</artifactId>
	<version>1</version>
</dependency>
```

```java
package com.in28minutes.spring.basics.springin5steps;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;

import com.in28minutes.spring.basics.springin5steps.cdi.SomeCdiBusiness;

@SpringBootApplication
public class SpringIn5StepsCdiApplication {
	
	private static Logger LOGGER = 
			LoggerFactory.getLogger(SpringIn5StepsCdiApplication.class); 
	
	public static void main(String[] args) {

		ApplicationContext applicationContext = 
				SpringApplication.run(SpringIn5StepsCdiApplication.class, args);
		
		SomeCdiBusiness business = 
				applicationContext.getBean(SomeCdiBusiness.class);
		
		LOGGER.info("{} dao-{}", business, business.getSomeCDIDAO());
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps.cdi;

import javax.inject.Inject;
import javax.inject.Named;

@Named
public class SomeCdiBusiness {
	
	@Inject
	SomeCdiDao someCdiDao;

	public SomeCdiDao getSomeCDIDAO() {
		return someCdiDao;
	}

	public void setSomeCDIDAO(SomeCdiDao someCdiDao) {
		this.someCdiDao = someCdiDao;
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps.cdi;

import javax.inject.Named;

@Named
public class SomeCdiDao {

}
```

#### Step 19 - Removing Spring Boot in Basic Application

pom.xml
```xml
<dependency>
	<groupId>org.springframework</groupId>
	<artifactId>spring-core</artifactId>
</dependency>
<dependency>
	<groupId>org.springframework</groupId>
	<artifactId>spring-context</artifactId>
</dependency>
<dependency>
	<groupId>org.slf4j</groupId>
	<artifactId>slf4j-api</artifactId>
</dependency>
<dependency>
	<groupId>ch.qos.logback</groupId>
	<artifactId>logback-classic</artifactId>
</dependency>

```

```java
package com.in28minutes.spring.basics.springin5steps;

import org.springframework.context.ApplicationContext;
import org.springframework.context.annotation.AnnotationConfigApplicationContext;
import org.springframework.context.annotation.ComponentScan;
import org.springframework.context.annotation.Configuration;

import com.in28minutes.spring.basics.springin5steps.basic.BinarySearchImpl;

@Configuration
@ComponentScan
public class SpringIn5StepsBasicApplication {

	public static void main(String[] args) {

		ApplicationContext applicationContext =
				new AnnotationConfigApplicationContext(SpringIn5StepsBasicApplication.class);

```

#### Step 20 - Fixing minor stuff - Add Logback and Close Application Context

```
<dependency>
	<groupId>ch.qos.logback</groupId>
	<artifactId>logback-classic</artifactId>
</dependency>
```

```java
@Configuration
@ComponentScan
public class SpringIn5StepsBasicApplication {

	public static void main(String[] args) {

		try (AnnotationConfigApplicationContext applicationContext = 
				new AnnotationConfigApplicationContext(
				SpringIn5StepsBasicApplication.class)) {
			//No change in code
		}
	}
}
```
Same changes in 
- SpringIn5StepsCdiApplication
- SpringIn5StepsComponentScanApplication
- SpringIn5StepsScopeApplication

#### Step 21 - Defining Spring Application Context using XML - Part 1
#### Step 22 - Defining Spring Application Context using XML - Part 2
```java
package com.in28minutes.spring.basics.springin5steps;

import org.springframework.context.annotation.ComponentScan;
import org.springframework.context.annotation.Configuration;
import org.springframework.context.support.ClassPathXmlApplicationContext;

import com.in28minutes.spring.basics.springin5steps.xml.XmlPersonDAO;

@Configuration
@ComponentScan
public class SpringIn5StepsXMLContextApplication {

	public static void main(String[] args) {

		try (ClassPathXmlApplicationContext applicationContext = new ClassPathXmlApplicationContext(
				"applicationContext.xml")) {

			XmlPersonDAO personDao = applicationContext.getBean(XmlPersonDAO.class);
			System.out.println(personDao);
			System.out.println(personDao.getXmlJdbcConnection());
		}
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps.xml;

public class XmlJdbcConnection {
	public XmlJdbcConnection() {
		System.out.println("JDBC Connection");
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps.xml;

public class XmlPersonDAO {

	XmlJdbcConnection xmlJdbcConnection;

	public XmlJdbcConnection getXmlJdbcConnection() {
		return xmlJdbcConnection;
	}

	public void setXmlJdbcConnection(XmlJdbcConnection jdbcConnection) {
		this.xmlJdbcConnection = jdbcConnection;
	}
}
```

```xml
<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://www.springframework.org/schema/beans
        http://www.springframework.org/schema/beans/spring-beans.xsd">

    <bean id="xmlJdbcConnection" 
    	class="com.in28minutes.spring.basics.springin5steps.xml.XmlJdbcConnection">
    </bean>

    <bean id="xmlPersonDAO" class="com.in28minutes.spring.basics.springin5steps.xml.XmlPersonDAO">
    		<property name="xmlJdbcConnection" ref="xmlJdbcConnection"/>
    </bean>

</beans>
```

#### Step 23 - Mixing XML Context with Component Scan for Beans defined with Annotations

```
public class SpringIn5StepsXMLContextApplication {

	private static Logger LOGGER = LoggerFactory.getLogger(SpringIn5StepsScopeApplication.class);

	public static void main(String[] args) {

		try (ClassPathXmlApplicationContext applicationContext = new ClassPathXmlApplicationContext(
				"applicationContext.xml")) {

			LOGGER.info("Beans Loaded -> {}", (Object) applicationContext.getBeanDefinitionNames());
			// [xmlJdbcConnection, xmlPersonDAO]
```

```
	<context:component-scan base-package="com.in28minutes.spring.basics"/>
```

#### Step 24 - IOC Container vs Application Context vs Bean Factory
#### Step 25 - @Component vs @Service vs @Repository vs @Controller

```
@Repository
public class ComponentDAO {

```

```
@Service
@Scope(ConfigurableBeanFactory.SCOPE_SINGLETON)
public class BinarySearchImpl {
```

```
@Service
@Qualifier("bubble")
public class BubbleSortAlgorithm implements SortAlgorithm {
```

```
@Service
@Qualifier("quick")
public class QuickSortAlgorithm implements SortAlgorithm {
```

```
@Repository
public class PersonDAO {
```
#### Step 26 - Read values from external properties file

```java
package com.in28minutes.spring.basics.springin5steps;

import org.springframework.context.annotation.AnnotationConfigApplicationContext;
import org.springframework.context.annotation.ComponentScan;
import org.springframework.context.annotation.Configuration;
import org.springframework.context.annotation.PropertySource;

import com.in28minutes.spring.basics.springin5steps.properties.SomeExternalService;

@Configuration
@ComponentScan
// 
@PropertySource("classpath:app.properties")
public class SpringIn5StepsPropertiesApplication {

	public static void main(String[] args) {

		try (AnnotationConfigApplicationContext applicationContext = new AnnotationConfigApplicationContext(
				SpringIn5StepsPropertiesApplication.class)) {

			SomeExternalService service = applicationContext.getBean(SomeExternalService.class);
			System.out.println(service.returnServiceURL());
		}
	}
}
```

```java
package com.in28minutes.spring.basics.springin5steps.properties;

import org.springframework.beans.factory.annotation.Value;
import org.springframework.stereotype.Component;

@Component
public class SomeExternalService {
	
	@Value("${external.service.url}")
	private String url;
	
	public String returnServiceURL(){
		return url;
	}

}
```

/src/main/resources/app.properties

```properties
external.service.url=http://someserver.dev.com/service
```

### Unit Testing with Spring Framework

#### Step 27 - Spring Unit Testing with a Java Context

```
<dependency>
	<groupId>org.springframework</groupId>
	<artifactId>spring-test</artifactId>
</dependency>
<dependency>
	<groupId>junit</groupId>
	<artifactId>junit</artifactId>
</dependency>
```

```
@RunWith(SpringRunner.class)
//@SpringBootTest
public class SpringIn5StepsBasicApplicationTests {
```

```java
package com.in28minutes.spring.basics.springin5steps.basic;

import static org.junit.Assert.assertEquals;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.test.context.ContextConfiguration;
import org.springframework.test.context.junit4.SpringRunner;

import com.in28minutes.spring.basics.springin5steps.SpringIn5StepsBasicApplication;

//Load the context
@RunWith(SpringRunner.class)
@ContextConfiguration(classes = SpringIn5StepsBasicApplication.class)
public class BinarySearchTest {

	// Get this bean from the context
	@Autowired
	BinarySearchImpl binarySearch;

	@Test
	public void testBasicScenario() {
		
		// call method on binarySearch
		int actualResult = binarySearch.binarySearch(new int[] {}, 5);

		// check if the value is correct
		assertEquals(3, actualResult);

	}

}
```

#### Step 28 - Spring Unit Testing with an XML Context

/src/test/resources/testContext.xml
```xml
<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xmlns:context="http://www.springframework.org/schema/context"
    xsi:schemaLocation="http://www.springframework.org/schema/beans
        http://www.springframework.org/schema/beans/spring-beans.xsd
        http://www.springframework.org/schema/context
        http://www.springframework.org/schema/context/spring-context.xsd">
	
	<import resource="classpath:applicationContext.xml"/>
	
</beans>
```

```java
package com.in28minutes.spring.basics.springin5steps.basic;

import static org.junit.Assert.assertEquals;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.test.context.ContextConfiguration;
import org.springframework.test.context.junit4.SpringRunner;

//Load the context
@RunWith(SpringRunner.class)
@ContextConfiguration(locations="/testContext.xml")
public class BinarySearchXMLConfigurationTest {

	// Get this bean from the context
	@Autowired
	BinarySearchImpl binarySearch;

	@Test
	public void testBasicScenario() {
		
		// call method on binarySearch
		int actualResult = binarySearch.binarySearch(new int[] {}, 5);

		// check if the value is correct
		assertEquals(3, actualResult);

	}

}
```

#### Step 29 - Spring Unit Testing with Mockito

```
public class SomeCdiBusiness {

	// SAME OLD CODE

	public int findGreatest() {
		int greatest = Integer.MIN_VALUE;
		int[] data = someCdiDao.getData();
		for (int value : data) {
			if (value > greatest) {
				greatest = value;
			}
		}
		return greatest;
	}

}
```

Add a new method
```java
package com.in28minutes.spring.basics.springin5steps.cdi;

import javax.inject.Named;

@Named
public class SomeCdiDao {
	
	public int[] getData() {
		return new int[] {5, 89,100};
	}

}
```


```java
package com.in28minutes.spring.basics.springin5steps.cdi;

import static org.junit.Assert.assertEquals;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.mockito.InjectMocks;
import org.mockito.Mock;
import org.mockito.Mockito;
import org.mockito.junit.MockitoJUnitRunner;

@RunWith(MockitoJUnitRunner.class)
public class SomeCdiBusinessTest {

	// Inject Mock
	@InjectMocks
	SomeCdiBusiness business;

	// Create Mock
	@Mock
	SomeCdiDao daoMock;

	@Test
	public void testBasicScenario() {
		Mockito.when(daoMock.getData()).thenReturn(new int[] { 2, 4 });
		assertEquals(4, business.findGreatest());
	}

	@Test
	public void testBasicScenario_NoElements() {
		Mockito.when(daoMock.getData()).thenReturn(new int[] { });
		assertEquals(Integer.MIN_VALUE, business.findGreatest());
	}

	@Test
	public void testBasicScenario_EqualElements() {
		Mockito.when(daoMock.getData()).thenReturn(new int[] { 2,2});
		assertEquals(2, business.findGreatest());
	}

}
```

```
<dependency>
	<groupId>org.mockito</groupId>
	<artifactId>mockito-core</artifactId>
</dependency>
```



### Spring AOP

#### Step 01 - Setting up AOP Example - Part 1 

Creating a Spring AOP Project with Spring Initializr is a cake walk. 

> Spring Initializr [http://start.spring.io/](http://start.spring.io/){:target="_blank"} is great tool to bootstrap your Spring Boot projects.

Notes
- Launch Spring Initializr and choose the following
  - Choose `com.in28minutes.spring.aop` as Group
  - Choose `spring-aop` as Artifact
  - Choose the following Dependencies
    - AOP
- Click Generate Project.
- Import the project into Eclipse.
- If you want to understand all the files that are part of this project, you can go here.

#### Step 02 - Setting up AOP Example - Part 2

```java
package com.in28minutes.spring.aop.springaop;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

@Service
public class Business1 {
	
	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Autowired
	private Dao1 dao1;
	
	public String calculateSomething(){
		String value = dao1.retrieveSomething();
		logger.info("In Business - {}", value);
		return value;
	}
}
```
---

```java
package com.in28minutes.spring.aop.springaop;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

@Service
public class Business2 {
	
	@Autowired
	private Dao2 dao2;
	
	public String calculateSomething(){
		//Business Logic
		return dao2.retrieveSomething();
	}
}
```
---

```java
package com.in28minutes.spring.aop.springaop;

import org.springframework.stereotype.Repository;

@Repository
public class Dao1 {

	public String retrieveSomething(){
		return "Dao1";
	}

}
```
---


```java
package com.in28minutes.spring.aop.springaop;

import org.springframework.stereotype.Repository;

@Repository
public class Dao2 {

	public String retrieveSomething(){
		return "Dao2";
	}

}
```

#### Step 03 - Defining an @Before advice

```
public class SpringAopApplication implements CommandLineRunner {

	@Autowired
	private Business1 business1;

	@Autowired
	private Business2 business2;
	
	@Override
	public void run(String... args) throws Exception {
		logger.info(business1.calculateSomething());
		logger.info(business2.calculateSomething());

```

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Before;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.context.annotation.Configuration;

//AOP
//Configuration
@Aspect
@Configuration
public class UseAccessAspect {
	
	private Logger logger = LoggerFactory.getLogger(this.getClass());
	
	//What kind of method calls I would intercept
	//execution(* PACKAGE.*.*(..))
	
	@Before("execution(* com.in28minutes.spring.aop.springaop.business.*.*(..))")
	public void before(JoinPoint joinPoint){
		logger.info(" Check for user access ");
		logger.info(" Allowed execution for {}", joinPoint);
	}
}
```
#### Step 04 - Understand AOP Terminology - Pointcut, Advice, Aspect, Join Point, Weaving and Weaver
#### Step 05 - Using @After, @AfterReturning, @AfterThrowing advices
#### Step 06 - Using @Around advice to implement performance tracing
```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.annotation.After;
import org.aspectj.lang.annotation.AfterReturning;
import org.aspectj.lang.annotation.AfterThrowing;
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Before;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.context.annotation.Configuration;

//AOP
//Configuration
@Aspect
@Configuration
public class AfterAopAspect {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@AfterReturning(value = "execution(* com.in28minutes.spring.aop.springaop.business.*.*(..))", 
			returning = "result")
	public void afterReturning(JoinPoint joinPoint, Object result) {
		logger.info("{} returned with value {}", joinPoint, result);
	}
	
	@After(value = "execution(* com.in28minutes.spring.aop.springaop.business.*.*(..))")
	public void after(JoinPoint joinPoint) {
		logger.info("after execution of {}", joinPoint);
	}
}
```

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.ProceedingJoinPoint;
import org.aspectj.lang.annotation.Around;
import org.aspectj.lang.annotation.Aspect;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.context.annotation.Configuration;

@Aspect
@Configuration
public class MethodExecutionCalculationAspect {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Around("execution(* com.in28minutes.spring.aop.springaop.business.*.*(..))")
	public void around(ProceedingJoinPoint joinPoint) throws Throwable {
		long startTime = System.currentTimeMillis();

		joinPoint.proceed();

		long timeTaken = System.currentTimeMillis() - startTime;
		logger.info("Time Taken by {} is {}", joinPoint, timeTaken);
	}
}
```

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Before;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.context.annotation.Configuration;

//AOP
//Configuration
@Aspect
@Configuration
public class UserAccessAspect {
	
	private Logger logger = LoggerFactory.getLogger(this.getClass());
	
	//What kind of method calls I would intercept
	//execution(* PACKAGE.*.*(..))
	//Weaving & Weaver
	@Before("execution(* com.in28minutes.spring.aop.springaop.data.*.*(..))")
	public void before(JoinPoint joinPoint){
		//Advice
		logger.info(" Check for user access ");
		logger.info(" Allowed execution for {}", joinPoint);
	}
}
```

#### Step 07 - Best Practice : Use common Pointcut Configuration

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.annotation.Pointcut;

public class CommonJoinPointConfig {
	
	@Pointcut("execution(* com.in28minutes.spring.aop.springaop.data.*.*(..))")
	public void dataLayerExecution(){}
	
	@Pointcut("execution(* com.in28minutes.spring.aop.springaop.business.*.*(..))")
	public void businessLayerExecution(){}

}
```

```
public class MethodExecutionCalculationAspect {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Around("com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.businessLayerExecution()")
```
public class AfterAopAspect
```
	@AfterReturning(value = "com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.businessLayerExecution()", returning = "result")
	@After(value = "com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.businessLayerExecution()")
```

```
public class UserAccessAspect {
	
	@Before("com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.dataLayerExecution()")
```

#### Step 08 - Quick summary of other Pointcuts

#### Step 09 - Creating Custom Annotation and an Aspect for Tracking Time

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.annotation.Pointcut;

public class CommonJoinPointConfig {
	
	@Pointcut("execution(* com.in28minutes.spring.aop.springaop.data.*.*(..))")
	public void dataLayerExecution(){}
	
	@Pointcut("execution(* com.in28minutes.spring.aop.springaop.business.*.*(..))")
	public void businessLayerExecution(){}
	
	@Pointcut("dataLayerExecution() && businessLayerExecution()")
	public void allLayerExecution(){}
	
	@Pointcut("bean(*dao*)")
	public void beanContainingDao(){}
	
	@Pointcut("within(com.in28minutes.spring.aop.springaop.data..*)")
	public void dataLayerExecutionWithWithin(){}

	@Pointcut("@annotation(com.in28minutes.spring.aop.springaop.aspect.TrackTime)")
	public void trackTimeAnnotation(){}

}
```
```java
package com.in28minutes.spring.aop.springaop.aspect;

import java.lang.annotation.ElementType;
import java.lang.annotation.Retention;
import java.lang.annotation.RetentionPolicy;
import java.lang.annotation.Target;

@Target(ElementType.METHOD)
@Retention(RetentionPolicy.RUNTIME)
public @interface TrackTime {

}
```


```
@Aspect
@Configuration
public class MethodExecutionCalculationAspect {

	@Around("com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.trackTimeAnnotation()")
	public void around(ProceedingJoinPoint joinPoint) throws Throwable {
```

```
public class Business1 {
		
	@TrackTime
	public String calculateSomething(){

```

```
@Repository
public class Dao1 {
	
	@TrackTime
	public String retrieveSomething(){

```

### Spring JDBC and JPA
#### Step 01 - Setting up a project with JDBC, JPA, H2 and Web Dependencies

Creating a Spring JDBC Project with Spring Initializr is a cake walk. 

> Spring Initializr [http://start.spring.io/](http://start.spring.io/){:target="_blank"} is great tool to bootstrap your Spring Boot projects.

Notes
- Launch Spring Initializr and choose the following
  - Choose `com.in28minutes.database` as Group
  - Choose `database-demo` as Artifact
  - Choose the following Dependencies
    - Web
    - JDBC
    - JPA
    - H2
- Click Generate Project.
- Import the project into Eclipse.
- If you want to understand all the files that are part of this project, you can go here.

#### Step 02 - Launching up H2 Console

/src/main/resources/application.properties 
```
spring.h2.console.enabled=true
```

Launching H2
- URL - http://localhost:8080/h2-console
- Make sure to check the db url - jdbc:h2:mem:testdb


#### Step 03 - Creating a Database Table in H2

/src/main/resources/data.sql

```
create table person
(
   id integer not null,
   name varchar(255) not null,
   location varchar(255),
   birth_date timestamp,
   primary key(id)
);
```

#### Step 04 - Populate data into Person Table
#### Step 05 - Implement findAll persons Spring JDBC Query Method

```java
package com.in28minutes.database.databasedemo.entity;

import java.util.Date;

public class Person {
	private int id;
	private String name;
	private String location;
	private Date birthDate;

	public Person(int id, String name, String location, Date birthDate) {
		super();
		this.id = id;
		this.name = name;
		this.location = location;
		this.birthDate = birthDate;
	}

	public int getId() {
		return id;
	}

	public void setId(int id) {
		this.id = id;
	}

	public String getName() {
		return name;
	}

	public void setName(String name) {
		this.name = name;
	}

	public String getLocation() {
		return location;
	}

	public void setLocation(String location) {
		this.location = location;
	}

	public Date getBirthDate() {
		return birthDate;
	}

	public void setBirthDate(Date birthDate) {
		this.birthDate = birthDate;
	}

}
```
---

/src/main/java/com/in28minutes/database/databasedemo/jdbc/PersonJbdcDao.java

```java
package com.in28minutes.database.databasedemo.jdbc;

import java.util.List;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.jdbc.core.BeanPropertyRowMapper;
import org.springframework.jdbc.core.JdbcTemplate;
import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
public class PersonJbdcDao {
	@Autowired
	JdbcTemplate jdbcTemplate;

	public List<Person> findAll() {
		return jdbcTemplate.query("select * from person", 
				new BeanPropertyRowMapper(Person.class));
	}
}
```
---

Add insert statements into data.sql
/src/main/resources/data.sql
```
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) 
VALUES(10001,  'Ranga', 'Hyderabad',sysdate());
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) 
VALUES(10002,  'James', 'New York',sysdate());
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) 
VALUES(10003,  'Pieter', 'Amsterdam',sysdate());
```
#### Step 06 - Execute the findAll method using CommandLineRunner

```
public class DatabaseDemoApplication implements CommandLineRunner {
	
	private Logger logger = LoggerFactory.getLogger(this.getClass());
	
	@Autowired
	PersonJbdcDao dao;
	
	@Override
	public void run(String... args) throws Exception {
		logger.info("All users -> {}", dao.findAll());
```

Modified
```
@Repository
public class PersonJbdcDao {
	@Autowired
	JdbcTemplate jdbcTemplate;

	public List<Person> findAll() {
		return jdbcTemplate.query("select * from person", 
				new BeanPropertyRowMapper<Person>(Person.class));
	}
}
```

#### Step 07 - A Quick Review - JDBC vs Spring JDBC
#### Step 08 - Whats in the background? Understanding Spring Boot Autoconfiguration
#### Step 09 - Implementing findById Spring JDBC Query Method
#### Step 10 - Implementing deleteById Spring JDBC Update Method

Modified
```java
package com.in28minutes.database.databasedemo.jdbc;

import java.util.List;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.jdbc.core.BeanPropertyRowMapper;
import org.springframework.jdbc.core.JdbcTemplate;
import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
public class PersonJbdcDao {

	@Autowired
	JdbcTemplate jdbcTemplate;

	public List<Person> findAll() {
		return jdbcTemplate.query("select * from person", new BeanPropertyRowMapper<Person>(Person.class));
	}

	public Person findById(int id) {
		return jdbcTemplate.queryForObject
				("select * from person where id=?", new Object[] { id },
				new BeanPropertyRowMapper<Person>(Person.class));
	}
	
	public int deleteById(int id) {
		return jdbcTemplate.update
				("delete from person where id=?", new Object[] { id });
	}

	
}
```
DatabaseDemoApplication
```
		logger.info("User id 10001 -> {}", dao.findById(10001));
		logger.info("Deleting 10002 -> No of Rows Deleted - {}", dao.deleteById(10002));

```
#### Step 11 - Implementing insert and update Spring JDBC Update Methods

```
	public int deleteById(int id) {
		return jdbcTemplate.update("delete from person where id=?", new Object[] { id });
	}

	public int insert(Person person) {
		return jdbcTemplate.update("insert into person (id, name, location, birth_date) " + "values(?,  ?, ?, ?)",
				new Object[] { person.getId(), person.getName(), person.getLocation(),
						new Timestamp(person.getBirthDate().getTime()) });
	}

	public int update(Person person) {
		return jdbcTemplate.update("update person " + " set name = ?, location = ?, birth_date = ? " + " where id = ?",
				new Object[] { person.getName(), person.getLocation(), new Timestamp(person.getBirthDate().getTime()),
						person.getId() });
	}
```

```
	logger.info("Deleting 10002 -> No of Rows Deleted - {}", 
				dao.deleteById(10002));
		
		logger.info("Inserting 10004 -> {}", 
				dao.insert(new Person(10004, "Tara", "Berlin", new Date())));
		
		logger.info("Update 10003 -> {}", 
				dao.update(new Person(10003, "Pieter", "Utrecht", new Date())));
	
```
#### Step 12 - Creating a custom Spring JDBC RowMapper

Inner class in PersonJbdcDao
```
class PersonRowMapper implements RowMapper<Person>{
	@Override
	public Person mapRow(ResultSet rs, int rowNum) throws SQLException {
		Person person = new Person();
		person.setId(rs.getInt("id"));
		person.setName(rs.getString("name"));
		person.setLocation(rs.getString("location"));
		person.setBirthDate(rs.getTimestamp("birth_date"));
		return person;
	}
	
}

public List<Person> findAll() {
	return jdbcTemplate.query("select * from person", new PersonRowMapper());
}
```

PersonJbdcDao
```
```

#### Step 13 - Quick introduction to JPA
#### Step 14 - Defining Person Entity

```java
package com.in28minutes.database.databasedemo.entity;

import java.util.Date;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.Id;

@Entity
public class Person {
	
	@Id
	@GeneratedValue
	private int id;
	
	//No change in rest of the code	
	
}
```

#### Step 15 - Implementing findById JPA Repository Method

DatabaseDemoApplication renamed to SpringJdbcDemoApplication

```java
package com.in28minutes.database.databasedemo.jpa;

import javax.persistence.EntityManager;
import javax.persistence.PersistenceContext;
import javax.transaction.Transactional;

import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
@Transactional
public class PersonJpaRepository {
	
	//connect to the database
	@PersistenceContext
	EntityManager entityManager;
	
	public Person findById(int id) {
		return entityManager.find(Person.class, id);//JPA
	}
}
```
---

/src/main/resources/application.properties
```
spring.jpa.show-sql=true
```
/src/main/resources/data.sql - Comment Everything
```
/*
*/
```


JpaDemoApplication
```java
package com.in28minutes.database.databasedemo;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import com.in28minutes.database.databasedemo.jpa.PersonJpaRepository;

@SpringBootApplication
public class JpaDemoApplication implements CommandLineRunner {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Autowired
	PersonJpaRepository repository;

	public static void main(String[] args) {
		SpringApplication.run(JpaDemoApplication.class, args);
	}

	@Override
	public void run(String... args) throws Exception {
		
		logger.info("User id 10001 -> {}", repository.findById(10001));

		/*
		logger.info("All users -> {}", repository.findAll());
		logger.info("Deleting 10002 -> No of Rows Deleted - {}", 
				repository.deleteById(10002));
		
		logger.info("Inserting 10004 -> {}", 
				repository.insert(new Person(10004, "Tara", "Berlin", new Date())));
		
		logger.info("Update 10003 -> {}", 
				repository.update(new Person(10003, "Pieter", "Utrecht", new Date())));
		*/
	}
}
```


#### Step 16 - Implementing insert and update JPA Repository Methods
#### Step 17 - Implementing deleteById JPA Repository Method
#### Step 18 - Implementing findAll using JPQL Named Query
```
		logger.info("Inserting -> {}", 
				repository.insert(new Person("Tara", "Berlin", new Date())));
		repository.deleteById(10002);

```

```
@Entity
@NamedQuery(name="find_all_persons", query="select p from Person p")
public class Person
```

```java
package com.in28minutes.database.databasedemo.jpa;

import java.util.List;

import javax.persistence.EntityManager;
import javax.persistence.PersistenceContext;
import javax.persistence.TypedQuery;
import javax.transaction.Transactional;

import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
@Transactional
public class PersonJpaRepository {

	// connect to the database
	@PersistenceContext
	EntityManager entityManager;

	public List<Person> findAll() {
		TypedQuery<Person> namedQuery = entityManager.createNamedQuery("find_all_persons", Person.class);
		return namedQuery.getResultList();
	}

	public Person findById(int id) {
		return entityManager.find(Person.class, id);// JPA
	}

	public Person update(Person person) {
		return entityManager.merge(person);
	}

	public Person insert(Person person) {
		return entityManager.merge(person);
	}

	public void deleteById(int id) {
		Person person = findById(id);
		entityManager.remove(person);
	}

}
```

#### Step 19 - Introduction to Spring Data JPA



JpaDemoApplication - comment out @SpringBootApplication

```java
package com.in28minutes.database.databasedemo.springdata;

import org.springframework.data.jpa.repository.JpaRepository;
import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
public interface PersonSpringDataRepository 
				extends JpaRepository<Person, Integer>{
}
```


```java
package com.in28minutes.database.databasedemo;

import java.util.Date;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import com.in28minutes.database.databasedemo.entity.Person;
import com.in28minutes.database.databasedemo.springdata.PersonSpringDataRepository;

@SpringBootApplication
public class SpringDataDemoApplication implements CommandLineRunner {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Autowired
	PersonSpringDataRepository repository;

	public static void main(String[] args) {
		SpringApplication.run(SpringDataDemoApplication.class, args);
	}

	@Override
	public void run(String... args) throws Exception {
		
		logger.info("User id 10001 -> {}", repository.findById(10001));
		
		logger.info("Inserting -> {}", 
				repository.save(new Person("Tara", "Berlin", new Date())));
		
		logger.info("Update 10003 -> {}", 
				repository.save(new Person(10003, "Pieter", "Utrecht", new Date())));
		
		repository.deleteById(10002);

		logger.info("All users -> {}", repository.findAll());
	}
}
```

#### Step 20 - Connecting to Other Databases


#### Connecting to My SQL and Other Databases

Spring Boot makes it easy to switch databases! Yeah really simple.

##### Steps
- Install MySQL and Setup Schema
- Remove H2 dependency from pom.xml
- Add MySQL (or your database) dependency to pom.xml
```xml
<dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
</dependency>
```
- Configure application.properties

```properties
spring.jpa.hibernate.ddl-auto=none
spring.datasource.url=jdbc:mysql://localhost:3306/person_example
spring.datasource.username=personuser
spring.datasource.password=YOUR_PASSWORD
```

- Restart the app and You are ready!

> Spring Boot can setup the database for you using Hibernate

Things to note:
- Spring Boot chooses a default value for you based on whether it thinks your database is embedded (default create-drop) or not (default none).
- ```spring.jpa.hibernate.ddl-auto``` is the setting to perform SchemaManagementTool actions automatically
   - none : No action will be performed.
   - create-only : Database creation will be generated.
   - drop : Database dropping will be generated.
   - create : Database dropping will be generated followed by database creation.
   - validate : Validate the database schema
   - update : Update the database schema
- Reference : https://docs.jboss.org/hibernate/orm/5.2/userguide/html_single/Hibernate_User_Guide.html#configurations-hbmddl


application.properties
```
#none, validate, update, create, create-drop
spring.jpa.hibernate.ddl-auto=create
```

##### Installing and Setting Up MySQL

- Install MySQL https://dev.mysql.com/doc/en/installing.html
  - More details - http://www.mysqltutorial.org/install-mysql/
  - Trouble Shooting - https://dev.mysql.com/doc/refman/en/problems.html
- Startup the Server (as a service)
- Go to command prompt (or terminal)
   - Execute following commands to create a database and a user

```
mysql --user=user_name --password db_name
create database person_example;
create user 'personuser'@'localhost' identified by 'YOUR_PASSWORD';
grant all on person_example.* to 'personuser'@'localhost';
```

- Execute following sql queries to create the table and insert the data

Table

```sql
create table person
(
	id integer not null,
	birth_date timestamp,
	location varchar(255),
	name varchar(255),
	primary key (id)
);

```

Data

```sql
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) VALUES(10001,  'Ranga', 'Hyderabad',sysdate());
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) VALUES(10002,  'James', 'New York',sysdate());
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) VALUES(10003,  'Pieter', 'Amsterdam',sysdate());
```

#### Notes

##### JdbcTemplate AutoConfiguration
```
=========================
AUTO-CONFIGURATION REPORT
=========================

DataSourceAutoConfiguration matched:
   - @ConditionalOnClass found required classes 'javax.sql.DataSource', 'org.springframework.jdbc.datasource.embedded.EmbeddedDatabaseType'; @ConditionalOnMissingClass did not find unwanted class (OnClassCondition)

DataSourceTransactionManagerAutoConfiguration matched:
   - @ConditionalOnClass found required classes 'org.springframework.jdbc.core.JdbcTemplate', 'org.springframework.transaction.PlatformTransactionManager'; @ConditionalOnMissingClass did not find unwanted class (OnClassCondition)

H2ConsoleAutoConfiguration matched:
   - @ConditionalOnClass found required class 'org.h2.server.web.WebServlet'; @ConditionalOnMissingClass did not find unwanted class (OnClassCondition)
   - found ConfigurableWebEnvironment (OnWebApplicationCondition)
   - @ConditionalOnProperty (spring.h2.console.enabled=true) matched (OnPropertyCondition)

JdbcTemplateAutoConfiguration matched:
   - @ConditionalOnClass found required classes 'javax.sql.DataSource', 'org.springframework.jdbc.core.JdbcTemplate'; @ConditionalOnMissingClass did not find unwanted class (OnClassCondition)
   - @ConditionalOnSingleCandidate (types: javax.sql.DataSource; SearchStrategy: all) found a primary bean from beans 'dataSource' (OnBeanCondition)

JdbcTemplateAutoConfiguration.JdbcTemplateConfiguration#jdbcTemplate matched:
   - @ConditionalOnMissingBean (types: org.springframework.jdbc.core.JdbcOperations; SearchStrategy: all) did not find any beans (OnBeanCondition)

```


## Complete Code Example

### Spring in Depth & Unit Testing with Spring


### /pom.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>

	<groupId>com.in28minutes.spring.basics</groupId>
	<artifactId>spring-in-5-steps</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<packaging>jar</packaging>

	<name>spring-in-5-steps</name>
	<description>Demo project for Spring Boot</description>

	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.0.0.M3</version>
		<relativePath /> <!-- lookup parent from repository -->
	</parent>

	<properties>
		<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>
		<java.version>1.8</java.version>
	</properties>

	<dependencies>

		<dependency>
			<groupId>org.springframework</groupId>
			<artifactId>spring-core</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework</groupId>
			<artifactId>spring-context</artifactId>
		</dependency>

		<dependency>
			<groupId>javax.inject</groupId>
			<artifactId>javax.inject</artifactId>
			<version>1</version>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-aop</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-jdbc</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>

		<dependency>
			<groupId>com.h2database</groupId>
			<artifactId>h2</artifactId>
		</dependency>

		<dependency>
			<groupId>junit</groupId>
			<artifactId>junit</artifactId>
		</dependency>

		<dependency>
			<groupId>org.mockito</groupId>
			<artifactId>mockito-core</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework</groupId>
			<artifactId>spring-test</artifactId>
		</dependency>
		<!-- <dependency> <groupId>org.springframework.boot</groupId> <artifactId>spring-boot-starter-test</artifactId> 
			<scope>test</scope> </dependency> -->
	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
		</plugins>
	</build>

	<repositories>
		<repository>
			<id>spring-snapshots</id>
			<name>Spring Snapshots</name>
			<url>https://repo.spring.io/snapshot</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</repository>
		<repository>
			<id>spring-milestones</id>
			<name>Spring Milestones</name>
			<url>https://repo.spring.io/milestone</url>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
		</repository>
	</repositories>

	<pluginRepositories>
		<pluginRepository>
			<id>spring-snapshots</id>
			<name>Spring Snapshots</name>
			<url>https://repo.spring.io/snapshot</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</pluginRepository>
		<pluginRepository>
			<id>spring-milestones</id>
			<name>Spring Milestones</name>
			<url>https://repo.spring.io/milestone</url>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
		</pluginRepository>
	</pluginRepositories>


</project>
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/AfterExecutionAOPConfig.java

```java
package com.in28minutes.spring.basics.springin5steps.aop;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.annotation.After;
import org.aspectj.lang.annotation.Aspect;
import org.springframework.context.annotation.Configuration;

@Aspect
@Configuration
public class AfterExecutionAOPConfig {
	@After("com.in28minutes.spring.basics.springin5steps.aop.AOPArchitectureConfig.anyMethod()")
	//@AfterReturning
	//@AfterThrowing
	public void after(JoinPoint joinPoint) {
		System.out.println("Clean up after " + joinPoint.getSignature().toString());
	}

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/AOPArchitectureConfig.java

```java
package com.in28minutes.spring.basics.springin5steps.aop;

import org.aspectj.lang.annotation.Pointcut;

public class AOPArchitectureConfig {
	
	//@Pointcut("within(com.in28minutes.spring.basics.springin5steps.aop.business..*)")
	//@Pointcut("businessService() && dataService()")
	@Pointcut("execution(* com.in28minutes.spring.basics.springin5steps.aop.business.*.*(..))")
    public void businessService() {}

	@Pointcut("execution(* com.in28minutes.spring.basics.springin5steps.aop.data.*.*(..))")
    public void dataService() {}

	@Pointcut("bean(*dao*)")
    public void daoServices() {}

	//@Pointcut("execution(* com.in28minutes.spring.basics.springin5steps.aop.*.*.*(..))")
	@Pointcut("within(com.in28minutes.spring.basics.springin5steps.aop..*)")
	public void anyMethod() {}
	
	@Pointcut("@annotation(com.in28minutes.spring.basics.springin5steps.aop.business.TrackTime) ")
	public void trackTime() {}

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/business/Business1.java

```java
package com.in28minutes.spring.basics.springin5steps.aop.business;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

import com.in28minutes.spring.basics.springin5steps.aop.data.Dao1;

@Service
public class Business1 {
	@Autowired
	private Dao1 dao;
	
	@TrackTime
	public String getSomething(){
		return dao.retrieveSomeData();
	}
}

```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/business/Business2.java

```java
package com.in28minutes.spring.basics.springin5steps.aop.business;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

import com.in28minutes.spring.basics.springin5steps.aop.data.Dao2;

@Service
public class Business2 {
	
	@Autowired
	private Dao2 dao;
	
	public String getSomething(){
		return dao.retrieveSomeData();
	}
}

```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/business/TrackTime.java

```java
package com.in28minutes.spring.basics.springin5steps.aop.business;

import java.lang.annotation.ElementType;
import java.lang.annotation.Retention;
import java.lang.annotation.RetentionPolicy;
import java.lang.annotation.Target;

@Target(ElementType.METHOD)
@Retention(RetentionPolicy.RUNTIME)
public @interface TrackTime {

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/BusinessAcessCheckAOPConfig.java

```java
package com.in28minutes.spring.basics.springin5steps.aop;

import java.util.Arrays;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Before;
import org.springframework.context.annotation.Configuration;

@Aspect
@Configuration
public class BusinessAcessCheckAOPConfig {
	@Before("com.in28minutes.spring.basics.springin5steps.aop.AOPArchitectureConfig.businessService()")
	public void before(JoinPoint joinPoint) {
		System.out.println("Before ");
		System.out.println(joinPoint.getSignature().toString() + " called with ");
		System.out.println(Arrays.toString(joinPoint.getArgs()));
		System.out.println("I Will check if the user has the right access");
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/data/Dao1.java

```java
package com.in28minutes.spring.basics.springin5steps.aop.data;

import org.springframework.stereotype.Repository;

@Repository
public class Dao1 {

	public String retrieveSomeData() {
		return "Dao1";
	}

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/data/Dao2.java

```java
package com.in28minutes.spring.basics.springin5steps.aop.data;

import org.springframework.stereotype.Repository;

@Repository
public class Dao2 {
	public String retrieveSomeData() {
		return "Dao2";
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/aop/LogExecutionTimeAOPConfig.java

```java
package com.in28minutes.spring.basics.springin5steps.aop;

import org.aspectj.lang.ProceedingJoinPoint;
import org.aspectj.lang.annotation.Around;
import org.aspectj.lang.annotation.Aspect;
import org.springframework.context.annotation.Configuration;

@Aspect
@Configuration
public class LogExecutionTimeAOPConfig {
	@Around("com.in28minutes.spring.basics.springin5steps.aop.AOPArchitectureConfig.trackTime()")
	public Object around(ProceedingJoinPoint joinPoint) throws Throwable {

		long startTime = System.currentTimeMillis();
		Object proceed = joinPoint.proceed();
		System.out.println("Time taken by " + joinPoint.getSignature().toString() + " is "
				+ (System.currentTimeMillis() - startTime));
		return proceed;
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/basics/BinarySearchImpl.java

```java
package com.in28minutes.spring.basics.springin5steps.basics;

import javax.annotation.PostConstruct;
import javax.annotation.PreDestroy;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Component;

@Component
public class BinarySearchImpl {

	@Autowired
	private SortAlgorithm sortAlgorithm;
	
	public int binarySearch(int[] numbers, int numberToSearchFor) {

		int[] sortedNumbers = sortAlgorithm.sort(numbers);
		System.out.println(sortAlgorithm);
		// Search the array
		return 3;
	}

	
	@PostConstruct
	public void postConstruct(){
		System.out.println("Post construct");
	}
	
	@PreDestroy
	public void preDestroy(){
		System.out.println("Pre Destroy");
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/basics/BubbleSortAlgorithm.java

```java
package com.in28minutes.spring.basics.springin5steps.basics;

import org.springframework.context.annotation.Primary;
import org.springframework.stereotype.Component;

@Component
@Primary
public class BubbleSortAlgorithm implements SortAlgorithm {
	public int[] sort(int[] numbers) {
		// Logic for Bubble Sort
		return numbers;
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/basics/QuickSortAlgorithm.java

```java
package com.in28minutes.spring.basics.springin5steps.basics;

import org.springframework.stereotype.Component;

@Component
public class QuickSortAlgorithm implements SortAlgorithm {
	public int[] sort(int[] numbers) {
		// Logic for Quick Sort
		return numbers;
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/basics/SortAlgorithm.java

```java
package com.in28minutes.spring.basics.springin5steps.basics;

public interface SortAlgorithm {
	public int[] sort(int[] numbers);
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/cdi/SomeCDIBusiness.java

```java
package com.in28minutes.spring.basics.springin5steps.cdi;

import javax.inject.Inject;
import javax.inject.Named;

@Named
public class SomeCDIBusiness {
	@Inject
	private SomeCDIDAO someDao;

	public SomeCDIBusiness() {
		super();
	}

	public SomeCDIBusiness(SomeCDIDAO someDao) {
		super();
		this.someDao = someDao;
	}

	public void setSomeDao(SomeCDIDAO someDao) {
		this.someDao = someDao;
	}

	public int sum() {
		int[] data = someDao.getData();
		int sum = 0;
		for (int value : data) {
			sum += value;
		}
		return sum;
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/cdi/SomeCDIDAO.java

```java
package com.in28minutes.spring.basics.springin5steps.cdi;

import javax.inject.Named;

@Named
public class SomeCDIDAO {
	public int[] getData() {
		return new int[] { 1, 2, 3, 4, 5 };
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/jdbc/Person.java

```java
package com.in28minutes.spring.basics.springin5steps.jdbc;

import java.util.Date;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.Id;
import javax.persistence.NamedQuery;

@Entity
@NamedQuery(query = "select p from Person p", name = "find_all_persons_query")
public class Person {

	@Id
	@GeneratedValue
	private int id;

	private String name;

	private String location;

	private Date birthDate;

	public Person(int id, String name, String location, Date birthDate) {
		super();
		this.id = id;
		this.name = name;
		this.location = location;
		this.birthDate = birthDate;
	}

	public Person() {

	}

	public Person(String name, String location, Date birthDate) {
		super();
		this.id = id;
		this.name = name;
		this.location = location;
		this.birthDate = birthDate;
	}

	public int getId() {
		return id;
	}

	public void setId(int id) {
		this.id = id;
	}

	public String getName() {
		return name;
	}

	public void setName(String name) {
		this.name = name;
	}

	public String getLocation() {
		return location;
	}

	public void setLocation(String location) {
		this.location = location;
	}

	public Date getBirthDate() {
		return birthDate;
	}

	public void setBirthDate(Date birthDate) {
		this.birthDate = birthDate;
	}

	@Override
	public String toString() {
		return String.format("\nPerson [id=%s, name=%s, location=%s, birthDate=%s]", id, name, location, birthDate);
	}

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/jdbc/PersonJpaRepository.java

```java
package com.in28minutes.spring.basics.springin5steps.jdbc;

import java.util.List;

import javax.persistence.EntityManager;
import javax.persistence.PersistenceContext;
import javax.persistence.Query;
import javax.transaction.Transactional;

import org.springframework.stereotype.Repository;

@Repository
@Transactional
public class PersonJpaRepository {

	@PersistenceContext
	private EntityManager entityManager;

	public List<Person> findAll() {
		Query query = entityManager.createNamedQuery("find_all_persons_query", Person.class);
		return query.getResultList();
	}

	public Person findById(int id) {
		return entityManager.find(Person.class, id);
	}

	public void insert(Person person) {
		entityManager.merge(person);
	}

	public void update(Person person) {
		entityManager.merge(person);
	}

	public void deleteById(int id) {
		Person person = findById(id);
		entityManager.remove(person);
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/jdbc/PersonSpringJdbcDao.java

```java
package com.in28minutes.spring.basics.springin5steps.jdbc;

import java.sql.ResultSet;
import java.sql.SQLException;
import java.sql.Timestamp;
import java.util.List;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.jdbc.core.JdbcTemplate;
import org.springframework.jdbc.core.RowMapper;
import org.springframework.stereotype.Component;

@Component
public class PersonSpringJdbcDao {

	@Autowired
	JdbcTemplate jdbcTemplate;

	// new BeanPropertyRowMapper(Person.class)
	class PersonMapper implements RowMapper<Person> {
		@Override
		public Person mapRow(ResultSet rs, int rowNum) throws SQLException {
			Person person = new Person(rs.getInt("id"), rs.getString("name"), rs.getString("location"),
					rs.getTimestamp("birth_date"));
			return person;
		}
	}

	public List<Person> findAll() {
		return jdbcTemplate.query("SELECT * FROM person", new PersonMapper());

	}

	public Person findById(int id) {

		return jdbcTemplate.queryForObject("SELECT * FROM person where id=?", new Object[] { id }, new PersonMapper());

	}

	public void insert(Person person) {
		jdbcTemplate.update("insert into person(id, birth_date,location, name) values(?,?,?,?)", person.getId(),
				new Timestamp(person.getBirthDate().getTime()), person.getLocation(), person.getName());

	}

	public void update(Person person) {
		jdbcTemplate.update("Update person set name=?, location=?, birth_date=? where id=?", person.getName(),
				person.getLocation(), new Timestamp(person.getBirthDate().getTime()), person.getId());

	}

	public void deleteById(int id) {
		jdbcTemplate.update("delete from person where id=?", id);
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/profiles/Cacheable.java

```java
package com.in28minutes.spring.basics.springin5steps.profiles;

public interface Cacheable {
	void doSomething();
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/profiles/DistributedCache.java

```java
package com.in28minutes.spring.basics.springin5steps.profiles;

public class DistributedCache implements Cacheable {

	@Override
	public void doSomething() {
		System.out.println("Distributed Cache");
	}

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/profiles/NormalCache.java

```java
package com.in28minutes.spring.basics.springin5steps.profiles;

public class NormalCache implements Cacheable {

	@Override
	public void doSomething() {
		System.out.println("Normal Cache");
	}

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/profiles/ProfileConfiguration.java

```java
package com.in28minutes.spring.basics.springin5steps.profiles;

import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;
import org.springframework.context.annotation.Profile;

@Configuration
public class ProfileConfiguration {
	@Bean
	@Profile("default")
	public Cacheable getDev() {
		return new NormalCache();
	}

	@Bean
	@Profile("prod")
	public Cacheable getProd() {
		return new DistributedCache();
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/properties/SomeExternalService.java

```java
package com.in28minutes.spring.basics.springin5steps.properties;

import org.springframework.beans.factory.annotation.Value;
import org.springframework.stereotype.Component;

@Component
public class SomeExternalService {
	
	@Value("${service.url}")
	private String service;
	
	public void callService(){
		System.out.println(service);
	}
	

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/scope/PersonDAO.java

```java
package com.in28minutes.spring.basics.springin5steps.scope;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.beans.factory.config.ConfigurableBeanFactory;
import org.springframework.context.annotation.Scope;
import org.springframework.stereotype.Component;

@Component
@Scope(value = ConfigurableBeanFactory.SCOPE_SINGLETON)
public class PersonDAO {

	@Autowired
	private PersonJDBCConnection connection;

	public PersonJDBCConnection getConnection() {
		return connection;
	}

	public void setConnection(PersonJDBCConnection connection) {
		this.connection = connection;
	}

}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/scope/PersonJDBCConnection.java

```java
package com.in28minutes.spring.basics.springin5steps.scope;

import org.springframework.beans.factory.config.ConfigurableBeanFactory;
import org.springframework.context.annotation.Scope;
import org.springframework.context.annotation.ScopedProxyMode;
import org.springframework.stereotype.Component;

@Component
@Scope(value = ConfigurableBeanFactory.SCOPE_PROTOTYPE, proxyMode = ScopedProxyMode.TARGET_CLASS)
public class PersonJDBCConnection {
	public PersonJDBCConnection() {
		System.out.println("new PersonJDBCConnection");
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsApplication.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Arrays;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;

import com.in28minutes.spring.basics.springin5steps.basics.BinarySearchImpl;
import com.in28minutes.spring.basics.springin5steps.scope.PersonDAO;

@SpringBootApplication
public class SpringIn5StepsApplication {

	public static void main(String[] args) {

		ApplicationContext applicationContext = SpringApplication.run(SpringIn5StepsApplication.class, args);
		System.out.println(Arrays.toString(applicationContext.getBeanDefinitionNames()));
		BinarySearchImpl binarySearch = applicationContext.getBean(BinarySearchImpl.class);
		int result = binarySearch.binarySearch(new int[] { 12, 4, 6 }, 3);
		System.out.println(result);
		PersonDAO personDAO1 = applicationContext.getBean(PersonDAO.class);
		PersonDAO personDAO2 = applicationContext.getBean(PersonDAO.class);
		System.out.println(personDAO1);
		System.out.println(personDAO2);
		System.out.println(personDAO1.getConnection());
		System.out.println(personDAO2.getConnection());

	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsAspectApplication.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Arrays;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;

import com.in28minutes.spring.basics.springin5steps.aop.business.Business1;
import com.in28minutes.spring.basics.springin5steps.aop.business.Business2;

@SpringBootApplication
public class SpringIn5StepsAspectApplication {
	public static void main(String[] args) {
		ApplicationContext applicationContext = SpringApplication.run(SpringIn5StepsAspectApplication.class, args);
		System.out.println(Arrays.toString(applicationContext.getBeanDefinitionNames()));
		Business1 business1 = applicationContext.getBean(Business1.class);
		Business2 business2 = applicationContext.getBean(Business2.class);
		System.out.println(business1.getSomething());
		System.out.println(business2.getSomething());
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsCacheableApplication.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Arrays;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;
import org.springframework.context.annotation.Profile;
import org.springframework.test.context.ActiveProfiles;

import com.in28minutes.spring.basics.springin5steps.basics.BinarySearchImpl;
import com.in28minutes.spring.basics.springin5steps.profiles.Cacheable;
import com.in28minutes.spring.basics.springin5steps.scope.PersonDAO;

@SpringBootApplication
public class SpringIn5StepsCacheableApplication {
	
	public static void main(String[] args) {

		ApplicationContext applicationContext = SpringApplication.run(SpringIn5StepsCacheableApplication.class, args);
		System.out.println(Arrays.toString(applicationContext.getBeanDefinitionNames()));
		BinarySearchImpl binarySearch = applicationContext.getBean(BinarySearchImpl.class);
		int result = binarySearch.binarySearch(new int[] { 12, 4, 6 }, 3);
		System.out.println(result);
		PersonDAO personDAO1 = applicationContext.getBean(PersonDAO.class);
		PersonDAO personDAO2 = applicationContext.getBean(PersonDAO.class);
		System.out.println(personDAO1);
		System.out.println(personDAO2);
		System.out.println(personDAO1.getConnection());
		System.out.println(personDAO2.getConnection());
		
		Cacheable cache = applicationContext.getBean(Cacheable.class);
		cache.doSomething();
		
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsJavaContext.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Arrays;

import org.springframework.context.annotation.AnnotationConfigApplicationContext;
import org.springframework.context.annotation.ComponentScan;
import org.springframework.context.annotation.Configuration;

import com.in28minutes.spring.basics.springin5steps.basics.BinarySearchImpl;
import com.in28minutes.spring.basics.springin5steps.cdi.SomeCDIBusiness;

@ComponentScan
@Configuration
public class SpringIn5StepsJavaContext {

	public static void main(String[] args) {

		try(AnnotationConfigApplicationContext applicationContext = new AnnotationConfigApplicationContext(SpringIn5StepsJavaContext.class)){
			System.out.println(Arrays.toString(applicationContext.getBeanDefinitionNames()));

			BinarySearchImpl binarySearch = applicationContext.getBean(BinarySearchImpl.class);

			int result = binarySearch.binarySearch(new int[] { 12, 4, 6 }, 3);

			System.out.println(result);

			SomeCDIBusiness someCDIBusiness = applicationContext.getBean(SomeCDIBusiness.class);

			int result2 = someCDIBusiness.sum();

			System.out.println(result2);
		};


	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsJdbcApplication.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Date;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;

import com.in28minutes.spring.basics.springin5steps.jdbc.Person;
import com.in28minutes.spring.basics.springin5steps.jdbc.PersonSpringJdbcDao;

@SpringBootApplication
public class SpringIn5StepsJdbcApplication implements CommandLineRunner {

	public static void main(String[] args) {
		ApplicationContext applicationContext = SpringApplication.run(SpringIn5StepsJdbcApplication.class, args);
	}

	@Autowired
	PersonSpringJdbcDao jdbcService;

	@Override
	public void run(String... args) throws Exception {

		jdbcService.insert(new Person(10001, "Ranga Karanam", "Hyderabad", new Date()));
		jdbcService.insert(new Person(10002, "Jack", "Charleston", new Date()));
		jdbcService.insert(new Person(10003, "Ravi", "Charleston", new Date()));
		jdbcService.insert(new Person(10004, "Satish", "Charleston", new Date()));
		jdbcService.insert(new Person(10005, "Jim", "Charleston", new Date()));

		jdbcService.update(new Person(10002, "Jack", "Greenville", new Date()));

		System.out.println(jdbcService.findById(10002));

		System.out.println(jdbcService.findAll());

		jdbcService.deleteById(10002);
		System.out.println("After deleting 10002");
		System.out.println(jdbcService.findAll());
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsJpaApplication.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Date;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ApplicationContext;

import com.in28minutes.spring.basics.springin5steps.jdbc.Person;
import com.in28minutes.spring.basics.springin5steps.jdbc.PersonJpaRepository;

@SpringBootApplication
public class SpringIn5StepsJpaApplication implements CommandLineRunner {

	public static void main(String[] args) {
		ApplicationContext applicationContext = SpringApplication.run(SpringIn5StepsJpaApplication.class, args);
	}

	@Autowired
	PersonJpaRepository jpaService;

	@Override
	public void run(String... args) throws Exception {

		jpaService.insert(new Person("Ranga Karanam", "Hyderabad", new Date()));
		jpaService.insert(new Person("Jack", "Charleston", new Date()));
		jpaService.insert(new Person("Ravi", "Charleston", new Date()));
		jpaService.insert(new Person("Satish", "Charleston", new Date()));
		jpaService.insert(new Person("Jim", "Charleston", new Date()));

		jpaService.update(new Person(2, "Jack", "Greenville", new Date()));

		System.out.println(jpaService.findById(2));

		System.out.println(jpaService.findAll());

		jpaService.deleteById(2);
		System.out.println("After deleting 2");
		System.out.println(jpaService.findAll());
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsPropertiesContext.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Arrays;

import org.springframework.context.annotation.AnnotationConfigApplicationContext;
import org.springframework.context.annotation.ComponentScan;
import org.springframework.context.annotation.Configuration;
import org.springframework.context.annotation.PropertySource;

import com.in28minutes.spring.basics.springin5steps.properties.SomeExternalService;

@ComponentScan
@Configuration
@PropertySource("classpath:app.properties")
public class SpringIn5StepsPropertiesContext {

	public static void main(String[] args) {

		try (AnnotationConfigApplicationContext applicationContext = new AnnotationConfigApplicationContext(
				SpringIn5StepsPropertiesContext.class)) {
			System.out.println(Arrays.toString(applicationContext.getBeanDefinitionNames()));

			SomeExternalService someBean = applicationContext.getBean(SomeExternalService.class);
			someBean.callService();
		}
		;

	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsXMLContext.java

```java
package com.in28minutes.spring.basics.springin5steps;

import java.util.Arrays;

import org.springframework.context.support.ClassPathXmlApplicationContext;

import com.in28minutes.spring.basics.springin5steps.basics.BinarySearchImpl;
import com.in28minutes.spring.basics.springin5steps.xml.SomeBusiness;

public class SpringIn5StepsXMLContext {

	public static void main(String[] args) {

		ClassPathXmlApplicationContext applicationContext = new ClassPathXmlApplicationContext("applicationContext.xml");
		
		System.out.println(Arrays.toString(applicationContext.getBeanDefinitionNames()));

		SomeBusiness someBusiness = applicationContext.getBean(SomeBusiness.class);

		int result = someBusiness.sum();

		System.out.println(result);
		
		BinarySearchImpl binarySearch = applicationContext.getBean(BinarySearchImpl.class);

		int result2 = binarySearch.binarySearch(new int[] { 12, 4, 6 }, 3);

		System.out.println(result2);
		
		applicationContext.close();
		
		System.out.println("Context Closed");

	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/xml/SomeBusiness.java

```java
package com.in28minutes.spring.basics.springin5steps.xml;

public class SomeBusiness {
	private SomeDAO someDao;

	public SomeBusiness() {
		super();
	}

	public SomeBusiness(SomeDAO someDao) {
		super();
		this.someDao = someDao;
	}

	public void setSomeDao(SomeDAO someDao) {
		this.someDao = someDao;
	}

	public int sum() {
		int[] data = someDao.getData();
		int sum = 0;
		for (int value : data) {
			sum += value;
		}
		return sum;
	}
}
```
---

### /src/main/java/com/in28minutes/spring/basics/springin5steps/xml/SomeDAO.java

```java
package com.in28minutes.spring.basics.springin5steps.xml;

import javax.inject.Named;

@Named
public class SomeDAO {
	public int[] getData() {
		return new int[] { 1, 2, 3, 4, 5, 6 };
	}
}
```
---

### /src/main/resources/app.properties

```properties
service.url=http://some.server.com/doSomething
```
---

### /src/main/resources/app_prod.properties

```properties
service.url=http://prod.server.com/doSomething
```
---

### /src/main/resources/application.properties

```properties
#logging.level.org.springframework = debug
spring.h2.console.enabled=true
spring.jpa.show-sql=true
```
---

### /src/main/resources/applicationContext.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!-- Search Google For "spring documentation example spring application context" -->
<beans xmlns="http://www.springframework.org/schema/beans"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:context="http://www.springframework.org/schema/context"
	xsi:schemaLocation="http://www.springframework.org/schema/beans
        http://www.springframework.org/schema/beans/spring-beans.xsd
         http://www.springframework.org/schema/context
           http://www.springframework.org/schema/context/spring-context.xsd">
	<context:component-scan base-package="com.in28minutes.spring.basics.springin5steps"></context:component-scan>

	<bean id="someDao" class="com.in28minutes.spring.basics.springin5steps.xml.SomeDAO">
		<!-- collaborators and configuration for this bean go here -->
	</bean>

	<bean id="someBusiness"
		class="com.in28minutes.spring.basics.springin5steps.xml.SomeBusiness">
		<!-- <property name="someDAO" ref="someDAO" /> -->
		<!-- <property name="someDao" ref="someDao" /> -->
		<property name="someDao" ref="someDao" />
	</bean>
	<!-- <bean id="someBusiness2" class="com.in28minutes.spring.basics.springin5steps.xml.SomeBusiness"> 
		<constructor-arg> <ref bean="someDao" /> </constructor-arg> </bean> -->

	<!-- more bean definitions go here -->

</beans>
```
---

### /src/main/resources/data.sql

```
/*
create table person
(
	id integer not null,
	birth_date timestamp,
	location varchar(255),
	name varchar(255),
	primary key (id)
);
*/
```
---

### /src/main/resources/log.txt

```
Searching directory [/in28Minutes/git/getting-started-in-5-steps/spring-in-5-steps/target/classes/com/in28minutes/spring/basics/springin5steps] for files matching pattern [/in28Minutes/git/getting-started-in-5-steps/spring-in-5-steps/target/classes/com/in28minutes/spring/basics/springin5steps/**/*.class]
Identified candidate component class: file [/in28Minutes/git/getting-started-in-5-steps/spring-in-5-steps/target/classes/com/in28minutes/spring/basics/springin5steps/BinarySearchImpl.class]
Identified candidate component class: file [/in28Minutes/git/getting-started-in-5-steps/spring-in-5-steps/target/classes/com/in28minutes/spring/basics/springin5steps/BubbleSortAlgorithm.class]

Creating instance of bean 'binarySearchImpl'
Creating instance of bean 'bubbleSortAlgorithm'
Finished creating instance of bean 'bubbleSortAlgorithm'

Constuctor - Autowiring by type from bean name 'binarySearchImpl' via constructor 
to bean named 'bubbleSortAlgorithm'
Setter -  Autowiring by type from bean name 'binarySearchImpl' to bean named 'bubbleSortAlgorithm'
No Setter or Constructor - Autowiring by type from bean name 'binarySearchImpl' to bean named 'bubbleSortAlgorithm'


Finished creating instance of bean 'binarySearchImpl'
```
---

### /src/test/java/com/in28minutes/spring/basics/springin5steps/SpringIn5StepsApplicationTests.java

```java
package com.in28minutes.spring.basics.springin5steps;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.springframework.test.context.junit4.SpringRunner;

//@RunWith(SpringRunner.class)
//@SpringBootTest
public class SpringIn5StepsApplicationTests {

	@Test
	public void contextLoads() {
	}

}
```
---

### /src/test/java/com/in28minutes/spring/basics/springin5steps/xml/SomeBusinessJavaTest.java

```java
package com.in28minutes.spring.basics.springin5steps.xml;

import static org.junit.Assert.assertEquals;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.test.context.ContextConfiguration;
import org.springframework.test.context.junit4.SpringRunner;

import com.in28minutes.spring.basics.springin5steps.SpringIn5StepsJavaContext;
import com.in28minutes.spring.basics.springin5steps.basics.BinarySearchImpl;

@RunWith(SpringRunner.class)
@ContextConfiguration(classes = SpringIn5StepsJavaContext.class)
public class SomeBusinessJavaTest {

	@Autowired
	private BinarySearchImpl search;

	@Test
	public void contextLoads() {
		int result = search.binarySearch(new int[] {}, 5);
		assertEquals(3, result);
	}

}
```
---

### /src/test/java/com/in28minutes/spring/basics/springin5steps/xml/SomeBusinessMockTest.java

```java
package com.in28minutes.spring.basics.springin5steps.xml;

import static org.junit.Assert.assertEquals;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.mockito.InjectMocks;
import org.mockito.Mock;
import org.mockito.Mockito;
import org.mockito.junit.MockitoJUnitRunner;

@RunWith(MockitoJUnitRunner.class)
public class SomeBusinessMockTest {

	@InjectMocks
	private SomeBusiness business;

	@Mock
	private SomeDAO dao;

	@Test
	public void contextLoads() {
		Mockito.when(dao.getData()).thenReturn(new int[] { 1, 2, 3 });
		int result = business.sum();
		assertEquals(6, result);
	}

}
```
---

### /src/test/java/com/in28minutes/spring/basics/springin5steps/xml/SomeBusinessXMLTest.java

```java
package com.in28minutes.spring.basics.springin5steps.xml;

import static org.junit.Assert.assertEquals;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.test.context.ContextConfiguration;
import org.springframework.test.context.junit4.SpringRunner;

@RunWith(SpringRunner.class)
@ContextConfiguration(locations = "/applicationContext.xml")
public class SomeBusinessXMLTest {
	
	@Autowired
	private SomeBusiness business;

	@Test
	public void contextLoads() {
		int result = business.sum();
		assertEquals(21,result);
	}

}
```
---

### Spring AOP 

### /pom.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>

	<groupId>com.in28minutes.spring.aop</groupId>
	<artifactId>spring-aop</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<packaging>jar</packaging>

	<name>spring-aop</name>
	<description>Demo project for Spring Boot</description>

	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.0.0.M3</version>
		<relativePath/> <!-- lookup parent from repository -->
	</parent>

	<properties>
		<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>
		<java.version>1.8</java.version>
	</properties>

	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-aop</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>
	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
		</plugins>
	</build>

	<repositories>
		<repository>
			<id>spring-snapshots</id>
			<name>Spring Snapshots</name>
			<url>https://repo.spring.io/snapshot</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</repository>
		<repository>
			<id>spring-milestones</id>
			<name>Spring Milestones</name>
			<url>https://repo.spring.io/milestone</url>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
		</repository>
	</repositories>

	<pluginRepositories>
		<pluginRepository>
			<id>spring-snapshots</id>
			<name>Spring Snapshots</name>
			<url>https://repo.spring.io/snapshot</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</pluginRepository>
		<pluginRepository>
			<id>spring-milestones</id>
			<name>Spring Milestones</name>
			<url>https://repo.spring.io/milestone</url>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
		</pluginRepository>
	</pluginRepositories>


</project>
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/aspect/AfterAopAspect.java

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.annotation.After;
import org.aspectj.lang.annotation.AfterReturning;
import org.aspectj.lang.annotation.Aspect;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.context.annotation.Configuration;

//AOP
//Configuration
@Aspect
@Configuration
public class AfterAopAspect {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@AfterReturning(value = "com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.businessLayerExecution()", 
			returning = "result")
	public void afterReturning(JoinPoint joinPoint, Object result) {
		logger.info("{} returned with value {}", joinPoint, result);
	}
	
	@After(value = "com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.businessLayerExecution()")
	public void after(JoinPoint joinPoint) {
		logger.info("after execution of {}", joinPoint);
	}
}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/aspect/CommonJoinPointConfig.java

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.annotation.Pointcut;

public class CommonJoinPointConfig {
	
	@Pointcut("execution(* com.in28minutes.spring.aop.springaop.data.*.*(..))")
	public void dataLayerExecution(){}
	
	@Pointcut("execution(* com.in28minutes.spring.aop.springaop.business.*.*(..))")
	public void businessLayerExecution(){}
	
	@Pointcut("dataLayerExecution() && businessLayerExecution()")
	public void allLayerExecution(){}
	
	@Pointcut("bean(*dao*)")
	public void beanContainingDao(){}
	
	@Pointcut("within(com.in28minutes.spring.aop.springaop.data..*)")
	public void dataLayerExecutionWithWithin(){}

	@Pointcut("@annotation(com.in28minutes.spring.aop.springaop.aspect.TrackTime)")
	public void trackTimeAnnotation(){}

}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/aspect/MethodExecutionCalculationAspect.java

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.ProceedingJoinPoint;
import org.aspectj.lang.annotation.Around;
import org.aspectj.lang.annotation.Aspect;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.context.annotation.Configuration;

@Aspect
@Configuration
public class MethodExecutionCalculationAspect {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Around("com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.trackTimeAnnotation()")
	public void around(ProceedingJoinPoint joinPoint) throws Throwable {
		long startTime = System.currentTimeMillis();

		joinPoint.proceed();

		long timeTaken = System.currentTimeMillis() - startTime;
		logger.info("Time Taken by {} is {}", joinPoint, timeTaken);
	}
}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/aspect/TrackTime.java

```java
package com.in28minutes.spring.aop.springaop.aspect;

import java.lang.annotation.ElementType;
import java.lang.annotation.Retention;
import java.lang.annotation.RetentionPolicy;
import java.lang.annotation.Target;

@Target(ElementType.METHOD)
@Retention(RetentionPolicy.RUNTIME)
public @interface TrackTime {

}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/aspect/UserAccessAspect.java

```java
package com.in28minutes.spring.aop.springaop.aspect;

import org.aspectj.lang.JoinPoint;
import org.aspectj.lang.annotation.Aspect;
import org.aspectj.lang.annotation.Before;
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.context.annotation.Configuration;

//AOP
//Configuration
@Aspect
@Configuration
public class UserAccessAspect {
	
	private Logger logger = LoggerFactory.getLogger(this.getClass());
	
	//What kind of method calls I would intercept
	//execution(* PACKAGE.*.*(..))
	//Weaving & Weaver
	@Before("com.in28minutes.spring.aop.springaop.aspect.CommonJoinPointConfig.dataLayerExecution()")
	public void before(JoinPoint joinPoint){
		//Advice
		logger.info(" Check for user access ");
		logger.info(" Allowed execution for {}", joinPoint);
	}
}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/business/Business1.java

```java
package com.in28minutes.spring.aop.springaop.business;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

import com.in28minutes.spring.aop.springaop.aspect.TrackTime;
import com.in28minutes.spring.aop.springaop.data.Dao1;

@Service
public class Business1 {
	
	private Logger logger = LoggerFactory.getLogger(this.getClass());
	
	@Autowired
	private Dao1 dao1;
	
	@TrackTime
	public String calculateSomething(){
		//Business Logic
		String value = dao1.retrieveSomething();
		logger.info("In Business - {}", value);
		return value;
	}
}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/business/Business2.java

```java
package com.in28minutes.spring.aop.springaop.business;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

import com.in28minutes.spring.aop.springaop.data.Dao2;

@Service
public class Business2 {
	
	@Autowired
	private Dao2 dao2;
	
	public String calculateSomething(){
		//Business Logic
		return dao2.retrieveSomething();
	}
}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/data/Dao1.java

```java
package com.in28minutes.spring.aop.springaop.data;

import org.springframework.stereotype.Repository;

import com.in28minutes.spring.aop.springaop.aspect.TrackTime;

@Repository
public class Dao1 {
	
	@TrackTime
	public String retrieveSomething(){
		return "Dao1";
	}

}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/data/Dao2.java

```java
package com.in28minutes.spring.aop.springaop.data;

import org.springframework.stereotype.Repository;

@Repository
public class Dao2 {

	public String retrieveSomething(){
		return "Dao2";
	}

}
```
---

### /src/main/java/com/in28minutes/spring/aop/springaop/SpringAopApplication.java

```java
package com.in28minutes.spring.aop.springaop;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import com.in28minutes.spring.aop.springaop.business.Business1;
import com.in28minutes.spring.aop.springaop.business.Business2;

@SpringBootApplication
public class SpringAopApplication implements CommandLineRunner{
	
	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Autowired
	private Business1 business1;

	@Autowired
	private Business2 business2;
	
	public static void main(String[] args) {
		SpringApplication.run(SpringAopApplication.class, args);
	}

	@Override
	public void run(String... args) throws Exception {
		logger.info(business1.calculateSomething());
		logger.info(business2.calculateSomething());
	}
}
```
---

### /src/main/resources/application.properties

```properties
```
---

### /src/test/java/com/in28minutes/spring/aop/springaop/SpringAopApplicationTests.java

```java
package com.in28minutes.spring.aop.springaop;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.springframework.boot.test.context.SpringBootTest;
import org.springframework.test.context.junit4.SpringRunner;

@RunWith(SpringRunner.class)
@SpringBootTest
public class SpringAopApplicationTests {

	@Test
	public void contextLoads() {
	}

}
```

### Spring JDBC to JPA


## Complete Code Example


### /pom.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>

	<groupId>com.in28minutes.database</groupId>
	<artifactId>database-demo</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<packaging>jar</packaging>

	<name>database-demo</name>
	<description>Demo project for Spring Boot</description>

	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.0.0.M3</version>
		<relativePath/> <!-- lookup parent from repository -->
	</parent>

	<properties>
		<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>
		<java.version>1.8</java.version>
	</properties>

	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-jdbc</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>

		<dependency>
			<groupId>com.h2database</groupId>
			<artifactId>h2</artifactId>
			<scope>runtime</scope>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>
		
	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
		</plugins>
	</build>

	<repositories>
		<repository>
			<id>spring-snapshots</id>
			<name>Spring Snapshots</name>
			<url>https://repo.spring.io/snapshot</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</repository>
		<repository>
			<id>spring-milestones</id>
			<name>Spring Milestones</name>
			<url>https://repo.spring.io/milestone</url>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
		</repository>
	</repositories>

	<pluginRepositories>
		<pluginRepository>
			<id>spring-snapshots</id>
			<name>Spring Snapshots</name>
			<url>https://repo.spring.io/snapshot</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</pluginRepository>
		<pluginRepository>
			<id>spring-milestones</id>
			<name>Spring Milestones</name>
			<url>https://repo.spring.io/milestone</url>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
		</pluginRepository>
	</pluginRepositories>


</project>
```
---

### /src/main/java/com/in28minutes/database/databasedemo/entity/Person.java

```java
package com.in28minutes.database.databasedemo.entity;

import java.util.Date;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.Id;
import javax.persistence.NamedQuery;

@Entity
@NamedQuery(name="find_all_persons", query="select p from Person p")
public class Person {

	@Id
	@GeneratedValue
	private int id;

	private String name;
	private String location;
	private Date birthDate;

	public Person() {

	}

	public Person(int id, String name, String location, Date birthDate) {
		super();
		this.id = id;
		this.name = name;
		this.location = location;
		this.birthDate = birthDate;
	}

	public Person(String name, String location, Date birthDate) {
		super();
		this.name = name;
		this.location = location;
		this.birthDate = birthDate;
	}

	public int getId() {
		return id;
	}

	public void setId(int id) {
		this.id = id;
	}

	public String getName() {
		return name;
	}

	public void setName(String name) {
		this.name = name;
	}

	public String getLocation() {
		return location;
	}

	public void setLocation(String location) {
		this.location = location;
	}

	public Date getBirthDate() {
		return birthDate;
	}

	public void setBirthDate(Date birthDate) {
		this.birthDate = birthDate;
	}

	@Override
	public String toString() {
		return String.format("\nPerson [id=%s, name=%s, location=%s, birthDate=%s]", id, name, location, birthDate);
	}

}
```
---

### /src/main/java/com/in28minutes/database/databasedemo/jdbc/PersonJbdcDao.java

```java
package com.in28minutes.database.databasedemo.jdbc;

import java.sql.ResultSet;
import java.sql.SQLException;
import java.sql.Timestamp;
import java.util.List;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.jdbc.core.BeanPropertyRowMapper;
import org.springframework.jdbc.core.JdbcTemplate;
import org.springframework.jdbc.core.RowMapper;
import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
public class PersonJbdcDao {

	@Autowired
	JdbcTemplate jdbcTemplate;
	
	class PersonRowMapper implements RowMapper<Person>{
		@Override
		public Person mapRow(ResultSet rs, int rowNum) throws SQLException {
			Person person = new Person();
			person.setId(rs.getInt("id"));
			person.setName(rs.getString("name"));
			person.setLocation(rs.getString("location"));
			person.setBirthDate(rs.getTimestamp("birth_date"));
			return person;
		}
		
	}
	
	public List<Person> findAll() {
		return jdbcTemplate.query("select * from person", new PersonRowMapper());
	}

	public Person findById(int id) {
		return jdbcTemplate.queryForObject("select * from person where id=?", new Object[] { id },
				new BeanPropertyRowMapper<Person>(Person.class));
	}

	public int deleteById(int id) {
		return jdbcTemplate.update("delete from person where id=?", new Object[] { id });
	}

	public int insert(Person person) {
		return jdbcTemplate.update("insert into person (id, name, location, birth_date) " + "values(?,  ?, ?, ?)",
				new Object[] { person.getId(), person.getName(), person.getLocation(),
						new Timestamp(person.getBirthDate().getTime()) });
	}

	public int update(Person person) {
		return jdbcTemplate.update("update person " + " set name = ?, location = ?, birth_date = ? " + " where id = ?",
				new Object[] { person.getName(), person.getLocation(), new Timestamp(person.getBirthDate().getTime()),
						person.getId() });
	}

}
```
---

### /src/main/java/com/in28minutes/database/databasedemo/jpa/PersonJpaRepository.java

```java
package com.in28minutes.database.databasedemo.jpa;

import java.util.List;

import javax.persistence.EntityManager;
import javax.persistence.PersistenceContext;
import javax.persistence.TypedQuery;
import javax.transaction.Transactional;

import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
@Transactional
public class PersonJpaRepository {

	// connect to the database
	@PersistenceContext
	EntityManager entityManager;

	public List<Person> findAll() {
		TypedQuery<Person> namedQuery = entityManager.createNamedQuery("find_all_persons", Person.class);
		return namedQuery.getResultList();
	}

	public Person findById(int id) {
		return entityManager.find(Person.class, id);// JPA
	}

	public Person update(Person person) {
		return entityManager.merge(person);
	}

	public Person insert(Person person) {
		return entityManager.merge(person);
	}

	public void deleteById(int id) {
		Person person = findById(id);
		entityManager.remove(person);
	}
}
```
---

### /src/main/java/com/in28minutes/database/databasedemo/JpaDemoApplication.java

```java
package com.in28minutes.database.databasedemo;

import java.util.Date;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import com.in28minutes.database.databasedemo.entity.Person;
import com.in28minutes.database.databasedemo.jpa.PersonJpaRepository;

//@SpringBootApplication
public class JpaDemoApplication implements CommandLineRunner {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Autowired
	PersonJpaRepository repository;

	public static void main(String[] args) {
		SpringApplication.run(JpaDemoApplication.class, args);
	}

	@Override
	public void run(String... args) throws Exception {
		
		logger.info("User id 10001 -> {}", repository.findById(10001));
		
		logger.info("Inserting -> {}", 
				repository.insert(new Person("Tara", "Berlin", new Date())));
		
		logger.info("Update 10003 -> {}", 
				repository.update(new Person(10003, "Pieter", "Utrecht", new Date())));
		
		repository.deleteById(10002);

		logger.info("All users -> {}", repository.findAll());
	}
}
```
---

### /src/main/java/com/in28minutes/database/databasedemo/springdata/PersonSpringDataRepository.java

```java
package com.in28minutes.database.databasedemo.springdata;

import org.springframework.data.jpa.repository.JpaRepository;
import org.springframework.stereotype.Repository;

import com.in28minutes.database.databasedemo.entity.Person;

@Repository
public interface PersonSpringDataRepository 
				extends JpaRepository<Person, Integer>{
}
```
---

### /src/main/java/com/in28minutes/database/databasedemo/SpringDataDemoApplication.java

```java
package com.in28minutes.database.databasedemo;

import java.util.Date;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import com.in28minutes.database.databasedemo.entity.Person;
import com.in28minutes.database.databasedemo.springdata.PersonSpringDataRepository;

@SpringBootApplication
public class SpringDataDemoApplication implements CommandLineRunner {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Autowired
	PersonSpringDataRepository repository;

	public static void main(String[] args) {
		SpringApplication.run(SpringDataDemoApplication.class, args);
	}

	@Override
	public void run(String... args) throws Exception {
		
		logger.info("User id 10001 -> {}", repository.findById(10001));
		
		logger.info("Inserting -> {}", 
				repository.save(new Person("Tara", "Berlin", new Date())));
		
		logger.info("Update 10003 -> {}", 
				repository.save(new Person(10003, "Pieter", "Utrecht", new Date())));
		
		repository.deleteById(10002);

		logger.info("All users -> {}", repository.findAll());
	}
}
```
---

### /src/main/java/com/in28minutes/database/databasedemo/SpringJdbcDemoApplication.java

```java
package com.in28minutes.database.databasedemo;

import java.util.Date;

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.CommandLineRunner;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import com.in28minutes.database.databasedemo.entity.Person;
import com.in28minutes.database.databasedemo.jdbc.PersonJbdcDao;

//@SpringBootApplication
public class SpringJdbcDemoApplication implements CommandLineRunner {

	private Logger logger = LoggerFactory.getLogger(this.getClass());

	@Autowired
	PersonJbdcDao dao;

	public static void main(String[] args) {
		SpringApplication.run(SpringJdbcDemoApplication.class, args);
	}

	@Override
	public void run(String... args) throws Exception {
		
		logger.info("All users -> {}", dao.findAll());
		
		logger.info("User id 10001 -> {}", dao.findById(10001));
		
		logger.info("Deleting 10002 -> No of Rows Deleted - {}", 
				dao.deleteById(10002));
		
		logger.info("Inserting 10004 -> {}", 
				dao.insert(new Person(10004, "Tara", "Berlin", new Date())));
		
		logger.info("Update 10003 -> {}", 
				dao.update(new Person(10003, "Pieter", "Utrecht", new Date())));
		
	}
}
```
---

### /src/main/resources/application.properties

```properties
spring.h2.console.enabled=true
spring.jpa.show-sql=true
#logging.level.root=debug
```
---

### /src/main/resources/data.sql

```
/*
create table person
(
   id integer not null,
   name varchar(255) not null,
   location varchar(255),
   birth_date timestamp,
   primary key(id)
);
*/

INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) 
VALUES(10001,  'Ranga', 'Hyderabad',sysdate());
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) 
VALUES(10002,  'James', 'New York',sysdate());
INSERT INTO PERSON (ID, NAME, LOCATION, BIRTH_DATE ) 
VALUES(10003,  'Pieter', 'Amsterdam',sysdate());

```
---

### /src/test/java/com/in28minutes/database/databasedemo/SpringJdbcDemoApplicationTests.java

```java
package com.in28minutes.database.databasedemo;

import org.junit.Test;
import org.junit.runner.RunWith;
import org.springframework.boot.test.context.SpringBootTest;
import org.springframework.test.context.junit4.SpringRunner;

@RunWith(SpringRunner.class)
@SpringBootTest
public class SpringJdbcDemoApplicationTests {

	@Test
	public void contextLoads() {
	}

}
```
---
