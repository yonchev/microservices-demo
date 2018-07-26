# microservices-demo

* Spring boot 2.0.3-RELEASE 
* Java 8
* notes can be found in repositories of this demo 

## Configuration of sprint cloud
* configuration for services is centralized in a repository (git or svn)
	* create a configuration git project in your local or github (for this demo is created in my local in a folder named _configuration_)
	* store services configurations (i.e. _config-client-development.properties_)
	  * simple property value: `message=Hello Microservice`
	  * encrypted property value: `message={cipher}52b9b3356c1847042d5c81aa6ca43858c995549639b00eac1d7c439118da995db376812f0a0d5c44737087fc2a093cb0`
	
* create a project with spring boot and spring cloud starter config server
	* demo in [spring-microservices-config-server](https://github.com/maurofokker/spring-microservices-config-server)
* create a project with spring boot and spring cloud starter config client
	* demo in [spring-microservices-config-client](https://github.com/maurofokker/spring-microservices-config-client)
