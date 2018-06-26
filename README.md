# microservicios-netflixoss

## Overview

This repo contains many microservices projects

### Build
Use this way to build the entire project without tests

```bash
$ mvn clean compile package -Dmaven.test.skip=true
```

### Updates
Add the following line of code, in the following classes:

microservice-demo-order/src/main/java/com/ewolff/microservice/order/OrderApp.java
```bash
System.out.println("Added by me in OrderApp");
```
microservice-demo-customer/src/main/java/com/ewolff/microservice/customer/CustomerApp.java
```bash
System.out.println("Added by me in CustomerApp");
```
microservice-demo-catalog/src/main/java/com/ewolff/microservice/catalog/Item.java
```bash
System.out.println("Added by me in Item");


