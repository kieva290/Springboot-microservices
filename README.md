# Springboot-microservices
Springboot microservices tutorial, covering core microservices concepts the microservices are:

-API-Gateway: to routing external and internal api calls to our micro-services

-Zipkin server for log tracing

-Sleuth work in collaboration with zipking to allow the microservices to end log-tracing to zipkin server

-cloud-config: extenalize and centralize all the micro-services configurations

-hystrix-dashboard a service that controls the interaction between microservices to provide latency and fault tolerance, 
this allows the micro-services to be resilient,

Hystrix is a library from Netflix. Hystrix isolates the points of access between the services, 
stops cascading failures across them and provides the fallback options. 

-depart-service

-user-service

-service-registry: for registering all our micro-services
------------
next task is deploy all those components into a kubernetes cluster,
