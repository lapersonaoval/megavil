# megavil

Sistema modular en Java 21 con Maven.  
Arquitectura diseñada para crecer de forma clara y controlada.

## Tecnologías
- Java Temurin 21
- Maven
- IntelliJ IDEA

## Arquitectura
- `app/` → punto de entrada
- `system/` → arranque y entorno
- `core/` → núcleo del sistema
- `commands/` → sistema de comandos modular
- `util/` → utilidades generales

## Ejecución
```bash
mvn exec:java
