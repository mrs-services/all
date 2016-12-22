## MRS (Meeting room Reservation System) services

as a Spring Cloud showcase

![image](https://cloud.githubusercontent.com/assets/106908/21414902/53b3b398-c847-11e6-85b1-a0eb494b506e.png)

## Services

* [UI](mrs-ui)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client, Ribbon, Hystrix)
    * Spring Cloud Stream
    * Spring Cloud Sleuth
    * Spring Cloud Security (OAuth 2 SSO)
* [Reservation](reservation)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client, Ribbon, Hystrix)
    * Spring Cloud Stream
    * Spring Cloud Sleuth
    * Spring Cloud Security (Resource Server)
    * Spring Cloud Contract
* [Notification](notification)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client)
    * Spring Cloud Sleuth
    * Spring Cloud Security (Resource Server)
    * Spring Cloud Contract
* [Account](account)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client)
    * Spring Cloud Sleuth
    * Spring Cloud Security (Authorization Server, Resource Server)
    * Spring Cloud Connectors

## Backends

* [Config Server](local-backends/config-server)
    * Spring Cloud Config
* [Eureka Server](local-backends/eureka-server)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Server)
* [Zipkin Server](local-backends/zipkin-server)
    * Spring Cloud Config
    * Spring Cloud Stream
    * Spring Cloud Sleuth
* [Turbine Server](local-backends/turbine-server)
    * Spring Cloud Config
    * Spring Cloud Netflix (Turbine Stream)
    * Spring Cloud Stream
* [Hystrix Dashboard](local-backends/hystrix-dashboard)
    * Spring Cloud Config
    * Spring Cloud Netflix (Hystrix Dashboard)