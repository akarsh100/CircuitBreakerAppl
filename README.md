# CircuitBreakerAppl
Making a simple spring boot application and then trying out the circuit breaker functionality on top of it

The paymentservice folder contains the payment service files. (I'm not sure if this is the correct project structure that should be used for two services)
The order service depends of the payment service. The effects of the circuit breaker can be seen by shutting down the payment service and trying to run the order service.
Visit http://localhost:8080/actuator/health to see the circuit breaker's current health.
