Springboot microservices tutorial, covering core microservices concepts the microservices are:

-API-Gateway: for routing external and internal api calls to our micro-services, all service calls go via the api gateway,

-Zipkin server for log tracing, instrument the micro-services to send log tracing details to zipkin server

-Sleuth work in collaboration with zipking to allow the microservices to send log-tracing to zipkin server

-cloud-config: externalize and centralize all the micro-services configurations

-hystrix-dashboard a service that controls the interaction between microservices to provide latency and fault tolerance, this allows the micro-services to be resilient,

Hystrix is a library from Netflix. Hystrix isolates the points of access between the services, stops cascading failures across them and provides the fallback options.

-department-service: service to create a department

-user-service: service to create a user, linked to a department, makes use of the department service, when creating a user object,
------------
next task is deploy all those components into a kubernetes cluster,
