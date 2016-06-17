# Struts2RestWS

   Strust2 with Restfull Webservice (for begin) with ModelDriven

###Runing Project

  - Install Maven in your OS and set Maven home path.
  - Clone or download Struts2RestWS and extract.
  - Using command prompt, go to root directory of Struts2RestWS.
  - Run maven command : mvn clean package.
~~~  
   mvn clean
   mvn install
~~~ 
  - Within target directory, you will get WAR file.
  - Deploy war file in tomcat.
    1. goto tomcat path.
    2. copy war file in project and paste it in :
~~~  
   rootpath/webapps
~~~ 
  - start tomcat: startup.bat
~~~ 
    path: rootpath/bin
~~~ 
  -  go to URL:

 1. *[`http://localhost:8080/struts2rest-1/employee.json`](http://localhost:8080/struts2rest-1/employee.json)*
 2. *[`http://localhost:8080/struts2rest-1/employee/111.json`](http://localhost:8080/struts2rest-1/employee/111.json)*
 3. *[`http://localhost:8080/struts2rest-1/employee/555/add.json`](http://localhost:8080/struts2rest-1/employee/555/add.json)*

###Resource:
  *[`http://struts.apache.org/docs/rest-plugin.html#RESTPlugin-RESTfulURLMappingLogic`](http://struts.apache.org/docs/rest-plugin.html#RESTPlugin-RESTfulURLMappingLogic)*
  *[`http://www.concretepage.com/struts-2/struts-2-rest-web-service-integration-example`](http://www.concretepage.com/struts-2/struts-2-rest-web-service-integration-example)*



