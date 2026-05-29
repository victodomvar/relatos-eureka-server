# relatos-eureka-server

Servidor Eureka para descubrimiento de servicios de Relatos de Papel.

## Requisitos

- Java 17
- Maven 3.9 o superior

## Ejecutar en local

```bash
mvn spring-boot:run
```

La consola de Eureka estará disponible en:

```text
http://localhost:8761
```

## Compilar

```bash
mvn clean package
```

El artefacto generado queda en `target/relatos-eureka-server-0.0.1-SNAPSHOT.jar`.

## Configuración principal

- `server.port=8761`
- `spring.application.name=eureka-server`
- `eureka.client.register-with-eureka=false`
- `eureka.client.fetch-registry=false`
