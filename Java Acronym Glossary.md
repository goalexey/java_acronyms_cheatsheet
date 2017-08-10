### AOP
**Aspect Oriented Programming**<br>

### Component
*Self contained functional software assembled into a Java EE application.*

### Container
*Execution environment for components, which also provides management and control services for those components.*

- Web Containers provide "robust" web application environments. A JEE web container (web server) supports such technologies as Servlets, Java Server Pages (JSP), JSP Standard Tag Library (JSTL), and Java Server Faces (JSF).

### Dependency

### Dispatcher Servlet
*Servlet class provided by the Spring Framework. It is a super controller that knows how to route incoming HTTP requests to other controllers based on certain logic.*

### Eclipse
*Java-based open source platform that allows a software developer to create a customized development environment (IDE) from plug-in components built by Eclipse members.*

### EJB
**Enterprise JavaBeans**<br>
*EJB is a server-side software component that encapsulates business logic of an application. It is one of several Java APIs for modular construction of enterprise software.*

### IDE
**Integrated Development Environment**.<br>
*It is a software application that provdes comprehensive facilities to computer programmers for software development. An IDE normally consists of a source code editor, build automation tools and a debugger.*

### IoC
**Inversion of Control**<br>
*IoC container is a component of Spring Framework that contains Beans (simple Java Objects) and manages their lifecycle.*<br>
[IoC documentation](http://docs.spring.io/spring/docs/current/spring-framework-reference/html/beans.html)

### J2EE
**Java 2 Enterprise Edition**

- Until J2EE 1.4 was released in November of 2003, developers working with the technology had to cope with steep learning curves and painfully slow exectution times. Development at the time was clunky, unwieldy and deployment experienced poor runtime performance.
- J2EE was originally designed to solve distributed computing and application scalability problems that only the biggest enterprises encounter.
- Back then, most developers used J2EE to develop small to middle sized web applications. The "enterprise features" were seldom used by most developers and unfortunately they only added to the complexity of building simple web applications.
- Since release of **Spring Framework** in 2004 many developers started migrating to it instead of using J2EE.
![](images/J2EE.png)
- Developers at Java saw the trend and in 2006 J2EE came out rebranded as Java EE 5. EJB components were throughly overhauled to make them more lightweight and easier to develop with.

### Java EE
**Java Enterprise Edition**<br>
aka JEE - considered to be bad practice to use JEE acronym.<br>

*It is a collection of technologies and APIs for the Java platform, designed to support "Enterprise" applications.*<br>

- Enterprise applications can generally be classed as large-scale, distributed, transactional, and highly-available applications, designed to support mission-critical business requirements. 
- *Example* - software for banks, stock exchanges.

### JDBC
**Java Database Connectivity**<br>
*JDBC is an application program interface (API) specification for connecting programs written in Java to the data in popular databases.*

- The application program interface lets you encode access request statements in Structured Query Language (SQL) that are then passed to the program that manages the database. It returns the results through a similar interface.
- JDBC is very similar to the SQL Access Group's Open Database Connectivity (ODBC) and, with a small "bridge" program, you can use the JDBC interface to access databases through the ODBC interface.

### JDK
**Java Development Kit**<br>
*JDK is a superset of a JRE and contains tools for Java programmers, e.g. a javac compiler.* 

- The Java Development Kit is provided free of charge either by Oracle Corporation directly, or by the OpenJDK open source project, which is governed by Oracle.

### JSP
**Java Server Pages**
*Server-side programming technology that enables the creation of dynamic web pages.*

- JSPs helps developers to embed java code in normal HTML pages by making use of special JSP tags.

### JSTL
**The JavaServer Pages Standard Tag Library**<br>
*Collection of useful JSP tags*

- These tags look somewhat similar to HTML tags and are used in JSP files.
- JSTL tags help to implement a lot of core functionality that is commonly used in JSP, such as iteration and conditionals tags for manipulating XML documents etc.

### JRE
**Java Runtime Environment**<br>
*JRE is a software package that contains what is required to run a Java program. It includes a Java Virtual Machine implementation together with an implementation of the Java Class Library. The Oracle Corporation, which owns the Java trademark, distributes a Java Runtime environment with their Java Virtual Machine called HotSpot.*



### JVM
**Java Virtual Machine**<br>

*JVM is an abstract computing machine that enables a computer to run a Java program.*

- There are three notions of the JVM: specification, implementation, and instance. The specification is a document that formally describes what is required of a JVM implementation. Having a single specification ensures all implementations are interoperable. A JVM implementation is a computer program that meets the requirements of the JVM specification. An instance of a JVM is an implementation running in a process that executes a computer program compiled into Java bytecode.

### JSE


### JDBC
### JNDI
### EJBs
### RMI
### Java servlets

### Maven
*Maven is a build automation tool used primarily for Java projects.*

- in Yiddish, the word **maven** means "accumulator of knowledge".
- Maven Website with Installation - [http://maven.apache.org/](http://maven.apache.org/)
- Maven project can be created with the help of certain project templates called **Archetypes**.
- Archetype is defined as an original pattern or model from which all other things of the same kind are made.
- [Page with info](https://maven.apache.org/guides/introduction/introduction-to-archetypes.html)
- [Page with folder structure](https://maven.apache.org/archetypes/index.html)

### REST
**Representational State Transfer**<br>
*It is Architectural style for Web Services*

### Servlet
*Server side technology used to create web applications*

- A Servlet is a Java class that extends the capabilities of the web server. It intercepts incoming requests and responds accordingly.
- A Servlet is a JEE component that can be deployed on the server to create dynamic web pages.


### Scriplet
*Block of Java code embedded directly inside JSP code*

### SOA
**Service Oriented Architecture**

### Spring IDE
*A set of plugins for Eclipse. It's an open-source project. These plugins make Eclipse Spring-aware.*

- It makes building Spring projects in Eclipse much easier and more convenient. It provides various wizards for creating Spring projects.

**List of Spring IDE Features**

- Spring-specific **content-assist** and validation for your spring config files.
- Spring-specific **refactoring** support for your spring config filees.
- Graphical visualization of your beans and their dependencies.
- Direct integration of the "getting started" guides from [http://spring.io/guides](http://spring.io/guides)
- A number of example and reference applications to learn from.

### Spring Tool Suite (STS)
*Ready-to-use distribution of the latest Eclipse release with Spring IDE components pre-installed. STS also includes the tc Server integration for Eclipse and various other components.*

**STS includes:**

- Eclipse JEE, which is Eclipse release that supports full fledged Java EE based development.
- Spring IDE
- Maven support, which includes plugins such as m2e, m2e-wtp.
- Git Integration - includes plugins such as egit. 
- Cloud foundry integration. (Cloud Foundry is an open source cloud platform on which developers can build, deploy and run applications. It is now part of Pivotal Software.
- tc server integration - tc Server is an enterprise version of Apache Tomcat 

### Tomcat
*Application server from the Apache Software Foundation that executes Java servlets and renders Web pages that include Java Server Page coding.
Tomcat requires a Java Runtime Enterprise Environment that conforms to JRE 1.1 or later.*

### URL
**Uniform Resource Locator**

- It is used to specify addresses on the World Wide Web. A URL is the fundamental network identification for any resource connected to the web (e.g., hypertext pages, images, and sound files). 


### URI
**Uniform Resource Identifier**

- It is a string of characters used to identify a resource. Such identification enables interaction with representations of the resource over a network, typically the World Wide Web, using specific protocols.

### Web.xml
*Deployment Descriptor file*

- Every JEE or Spring project has a Web.xml file.
- It contains data informtation about the web applicaion such as the configuration of the servlet, startup parameters, session management, initialization of parameters and so on.