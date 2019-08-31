# eureka-service
Spring Cloud Learning eureka-service
## What Is It?
Spring cloud components learning.
## Spring Cloud components
### Spring boot 2.1.4.RELEASE
### Actuator
## Download & Installation
1. Download a Java SE Runtime Environment (JRE),release version 8 or later, from http://www.oracle.com/technetwork/java/javase/downloads/index.html
2. Download Apache maven
Download Apache maven 3.6.0 here
http://maven.apache.org/download.cgi
3. Set Java Home or JRE Home.
4. Set Maven Home.
5. Import project as Existing maven projects.
6. Use mvn clean install to install this project.
## Demo
本例主要目的在于利用spring cloud的eureka组件对服务情况进行获取。
启动[eureka-service](https://github.com/ChenLin12138/eureka-service)和[organization-service](https://github.com/ChenLin12138/organization-service)后
http://localhost:8761/eureka/apps/
或者
http://localhost:8761/eureka/apps/organizationservice
获取Eureka中已经注册的服务信息
https://github.com/ChenLin12138/eureka-service/blob/master/pic/eureka%E4%B8%AD%E7%9A%84%E6%9C%8D%E5%8A%A1.png
也可调整accept参数为application/json以json方式查看
https://github.com/ChenLin12138/eureka-service/blob/master/pic/eureka%E4%B8%AD%E7%9A%84%E6%9C%8D%E5%8A%A1json%E6%A0%BC%E5%BC%8F.png
