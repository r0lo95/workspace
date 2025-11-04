# Mi Primer Proyecto Spring Boot

## Información del Proyecto

- **Nombre:** mi-primer-springboot
- **Versión de Spring Boot:** 3.x.x
- **Java:** 17
- **Build Tool:** Maven


## Estructura del Proyecto

Explica brevemente cada directorio/archivo:

### src/main/java/dev/alefiengo/miprimerspringboot/
- `MiPrimerSpringbootApplication.java`: Es la clase main de la aplicaiocn spring boot, se encarga de iniciar el framework


### src/main/resources/
- `application.properties`: Archivo central de configuracion de parametros de conexion a otros servicios o configuracion de logging
- 
### src/test/
- Contiene clases destinadas a realziar pruebas unitarias

### pom.xml
- Es el archivo donde se definene las dependencias que el proyecto requiere, como debe contruirse y la version de JAva

### target/
- Contiene el artefacto y cualquier otro recurose que sera utilziado para desplegar el proyecot (.jar , .war )

## Cómo Ejecutar

\```bash
mvn spring-boot:run
\```
Ubicado donde esta el pom.xml ejecutar el mvn spring-boot:run por linea de comandos
## Dependencias Principales

Lista las dependencias en `pom.xml` y explica brevemente cada una:
- spring-boot-starter-web: Starter que incluye las dependencias para crear aplicaciones web
- spring-boot-starter-test: Starte que incluiye las dependencias para pruebas unitarias

## Conceptos Aprendidos

- ¿Qué es Spring Boot?
  * Es un Framework que simplifica la creacion de aplicaciones standalone.
- ¿Qué es Maven?
  * Herramienta de automatizacion de construccion
- ¿Qué significa "Tomcat started on port 8080"?
  * Siginifca que el puerto abierto para el servicio creado es el 8080 y esta iniciado
- ¿Para qué sirve la anotación @SpringBootApplication?
  * Es una anotación de conveniencia que combina tres anotaciones clave:
    @Configuration: Marca la clase como fuente de definiciones de beans de configuración.
    
    @EnableAutoConfiguration: Le indica a Spring Boot que configure automáticamente el framework basándose en las dependencias que encuentra.
  
    @ComponentScan: Le indica a Spring que busque otros componentes, configuraciones y servicios en el paquete actual (y sus subpaquetes).

## Autor
Carlos Eduardo Rodrigo Loza - Curso Spring Boot & Kafka
