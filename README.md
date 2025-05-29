# Literalura

Este proyecto es una aplicación de gestión de literatura desarrollada con Spring Boot. A continuación, se detalla la estructura del proyecto y algunas instrucciones básicas para su configuración y ejecución.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```
literatura
│
├── .idea
│   └── ...
│
├── .mvn
│   └── ...
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.alura.literatura
│   │   │       ├── config
│   │   │       ├── dto
│   │   │       ├── model
│   │   │       ├── principal
│   │   │       ├── repository
│   │   │       ├── service
│   │   │       └── LiteraturaApplication.java
│   │   │
│   │   └── resources
│   │       ├── application.properties
│   │       └── logback-spring.xml
│   │
│   └── test
│       └── ...
│
└── target
    ├── .gitattributes
    ├── .gitignore
    ├── HELP.md
    ├── mvnw
    ├── mvnw.cmd
    ├── pom.xml
    └── README.md
```

## Descripción de los Directorios y Archivos

- **.idea**: Directorio de configuración de IntelliJ IDEA.
- **.mvn**: Directorio de configuración de Maven Wrapper.
- **src/main/java/com.alura.literatura**: Paquete principal de la aplicación.
    - **config**: Configuraciones adicionales de la aplicación.
    - **dto**: Data Transfer Objects utilizados para transferir datos.
    - **model**: Modelos de datos que representan la estructura de la base de datos.
    - **principal**: Clase principal de la aplicación.
    - **repository**: Interfaces de repositorio para acceder a la base de datos.
    - **service**: Servicios que contienen la lógica de negocio.
    - **LiteraturaApplication.java**: Clase principal que inicia la aplicación Spring Boot.
- **src/main/resources**: Recursos de la aplicación.
    - **application.properties**: Archivo de configuración de la aplicación.
    - **logback-spring.xml**: Configuración de logging.
- **src/test**: Directorio para las pruebas unitarias y de integración.
- **target**: Directorio donde se compilan los archivos generados por Maven.
    - **.gitattributes**: Configuración de atributos de Git.
    - **.gitignore**: Archivos y directorios ignorados por Git.
    - **HELP.md**: Archivo de ayuda.
    - **mvnw** y **mvnw.cmd**: Scripts de Maven Wrapper para ejecutar comandos de Maven.
    - **pom.xml**: Archivo de configuración de Maven.
    - **README.md**: Archivo de documentación del proyecto.





