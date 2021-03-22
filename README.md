# zuul-gateway

Acts as a router and load balncer for the incoming requests to multiple microservices hosted. Currently order-service and batch-order-service are routed via this module. More instances of the microservices could also be added so that this module acts as a load balancer. Filters for the requests for various purposes like logging could be added here.
