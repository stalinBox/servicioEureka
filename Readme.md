## SERVICIO DE REGISTRO Y DESCUBRIMIENTO EUREKA

##### *Servicio Spring Cloud Eureka*
Permite al resto de microservicios registrarse en su directorio

##### *Modo de registro*

1. En el archivo de inicio del servicio a registrar incovar a la siguiente anotacion: @EnableEurekaServer
2. Habilitar las librerias de actuator en cada microservicio
3. En el archivo *.properties escribir la direccion del servicio eureka: eureka.client.serviceUrl.defaultZone=${api.server.ip}servicio_eureka/eureka

