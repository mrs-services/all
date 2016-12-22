## MRS (Meeting room Reservation System) services

as a Spring Cloud showcase

![image](https://cloud.githubusercontent.com/assets/106908/21414902/53b3b398-c847-11e6-85b1-a0eb494b506e.png)

## Services

* [UI](https://github.com/mrs-services/mrs-ui)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client, Ribbon, Hystrix)
    * Spring Cloud Stream
    * Spring Cloud Sleuth
    * Spring Cloud Security (OAuth 2 SSO)
* [Reservation](https://github.com/mrs-services/reservation)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client, Ribbon, Hystrix)
    * Spring Cloud Stream
    * Spring Cloud Sleuth
    * Spring Cloud Security (Resource Server)
    * Spring Cloud Contract
* [Notification](https://github.com/mrs-services/notification)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client)
    * Spring Cloud Sleuth
    * Spring Cloud Security (Resource Server)
    * Spring Cloud Contract
* [Account](https://github.com/mrs-services/account)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Client)
    * Spring Cloud Sleuth
    * Spring Cloud Security (Authorization Server, Resource Server)
    * Spring Cloud Connectors

## Backends

* [Config Server](https://github.com/mrs-services/local-backends/config-server)
    * Spring Cloud Config
* [Eureka Server](https://github.com/mrs-services/local-backends/eureka-server)
    * Spring Cloud Config
    * Spring Cloud Netflix (Eukreka Server)
* [Zipkin Server](https://github.com/mrs-services/local-backends/zipkin-server)
    * Spring Cloud Config
    * Spring Cloud Stream
    * Spring Cloud Sleuth
* [Turbine Server](https://github.com/mrs-services/local-backends/turbine-server)
    * Spring Cloud Config
    * Spring Cloud Netflix (Turbine Stream)
    * Spring Cloud Stream
* [Hystrix Dashboard](https://github.com/mrs-services/local-backends/hystrix-dashboard)
    * Spring Cloud Config
    * Spring Cloud Netflix (Hystrix Dashboard)