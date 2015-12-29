##1-Two microservices running and registered
###Microservice account service
![Account service running and registered](https://raw.github.com/Gascon95/Laboratory-6-microservices/master/accounts.png)
###Microservice web service 
![Web service running and registered](https://raw.github.com/Gascon95/Laboratory-6-microservices/master/web.png)

##2-Microservices registered in the registration service
![Registration service dashboard](https://raw.github.com/Gascon95/Laboratory-6-microservices/master/dashboard.png)

##3-Second microservice account service running and registered
![Second account service running and registered](https://raw.github.com/Gascon95/Laboratory-6-microservices/master/accounts2.png)

##4-Brief report on killing the first microservice account service
If the web service tries to execute any operation it'll find that the known account service is no
longer avalaible. It'll then return a "Connection refused" error. After that, the web service will
ask the registration service another account service, and the registration will return the second
account service registered, the one on the 4444 port. Shortly, the web service operations will be 
once more avalaible.
