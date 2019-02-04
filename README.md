# RestFulSampleApplication
This is a Sample Restful Application which  exposes RestFul API as a service
This Application performs getAllMetrics,getMetricsById,createMetrics,updatesMetricsById
To Deploy & test the application we need Tomcat server,PostMan(to test),
There is no Database for this project.I have used Hash map to manipulate data and hard coded 2 values
Download the ZIP folder and extract the files and import into eclipse workspace and start the Tomcat Server
Use the below url to test the output in Postman
http://localhost:8080/restexample/webapi/metrics --- To get all metrics (Select Request type GET in Postman )
http://localhost:8080/restexample/webapi/metrics/{id} ---To get all metrics for that ID(Select Request type GET in Postman )
http://localhost:8080/restexample/webapi/metrics ---To create a metric(Select Request type POST in Postman and give values in body type)
http://localhost:8080/restexample/webapi/metrics/{id} ---To update metric(Select Request type PUT in Postman and give values in body type)
