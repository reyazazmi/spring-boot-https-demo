# Read Me First
The following was discovered as part of building this project:

* The original package name 'com.example.spring-boot-https-demo' is invalid and this project uses 'com.example.springboothttpsdemo' instead.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.4.0/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.4.0/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.4.0/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)


# Command to create self signed SSL Certificate JKS
 keytool -genkey -alias https-alias-demo -storetype JKS -keyalg RSA -keysize 2048 -validity 365 -keystore https-demo.jks

#To Secured access resource
 https://localhost:8443/hello - returns 'Hello World'
