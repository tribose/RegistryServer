# RegistryServer
RegistryServer Registers Product microservice (ProductMS) and Client microservice (ClientMS) applications

Points to be noted:
1. RegistryService App is the Registration Server for both the Client/Consumer side application i.e ClientMS and Provider side application i.e. ProductMS. It is developed using Spring Cloud Eureka Discovery server.

2. I've mentioned the URL patterns to access all services in the comment section of ClientMSController.java file of ClinetMS application
   (RURL for ClientMS - https://github.com/tribose/ClientMS) 

3. For monitoring microservice application, default behavior of "Actuator" is implemented and you can use the following links to monitor application.
  a) http://localhost:1111/health
  b) http://localhost:1111/trace
  c) http://localhost:1111/metrics
  d) http://localhost:1111/info
