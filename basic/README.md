# Description
This project providers sample to show working with Spring Cloud Microservices. 

* provider
A Microserivce using Spring Cloud with a REST interface.

* consumer
A Microserivce using Spring Cloud with a REST interface. Consumer calls provider with RestTemplate.

* gateway
A Microserivce using Spring Cloud Gateway to forward requests to consumer.

# Usage
Start 3 microservices and open in browser： http://localhost:9090/sayHello?name=World


# 项目说明

这个项目提供了 Spring Cloud Huawei 的简单例子，例子包括：

* provider
使用 Spring Cloud 开发一个 REST 接口。

* consumer
使用 Spring Cloud 开发一个 REST 接口， 接口实现通过 RestTemplate 调用 provider 的接口。 

* gateway
使用 Spring Cloud Gateway 开发一个网关， 网关将所有请求转发到 consumer。 

## 使用

启动3个微服务， 然后通过界面访问： http://localhost:9090/sayHello?name=World
