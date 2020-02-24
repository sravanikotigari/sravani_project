# sravani_project



ShoppingCart 
Developed an end to end Ecommerce web Application using Spring MVC with multiple modules

Functionalities:

  User Registeration

CRUD Operations like

  User can add product to his cart
  Admin can add product to the product list
  Admin can edit the product details
  Admin can delete the product from the list

Spring Security

  User can login the site
  The entire site will change according the role. Whether the client is User or Admin
  user can logout after completing.
  Spring WebFlow
  after adding products the cart the User can checkout using spring WebFlow
  Confirming User Details
  Confirming Shipping and Billing Address
Receipt

  If the user cancel the webflow it will go to cancel Page
  If the user submits the checkout it will go to thank you page with the timing of delivery Report
  Tools and Technologies:
  Technology : Bootstrap, Java, Spring MVC, Hibernate, JSP, Maven.
  Application Servicer: Apache Tomcat Server
  Database : H2 Database.
Installation:

Development Platform - Eclipse / IntelliJ Idea

Download Eclipse
Download IntelliJ Idea
Server - Apache Tomcat Server

Download Apache Server
Build Tool - Maven

Download Maven
Database - H2 Database

Download H2 Database
Configuring tomcat with Eclipse (windows) - Click Here

Installation of maven in eclipse - Click Here

Clone the repository and import it to eclipse

Run your H2 Database.

Configure your databse configuration in application-context.xml

Database properties:

   <bean id="dataSource"
     class="org.springframework.jdbc.datasource.DriverManagerDataSource">
     <property name="driverClassName" value=YOUR DB DRIVER CLASS NAME" />
     <property name="url" value="YOUR DB URL" />
     <property name="username" value="YOUR DB USERNAME" />
     <property name="password" value="YOUR DB PASSWORD" />
   </bean>
Database Dialect:

<prop key="hibernate.dialect">YOUR DB DIALECT</prop>
Run the server.
