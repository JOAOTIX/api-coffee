# ☕ Cavosh Coffee - Backend  

Este repositorio contiene el **backend de Cavosh Coffee**, desarrollado con **Spring Boot**, **Java 17** y **H2 Database** para el entorno de desarrollo.  

---

## 📋 Requisitos Previos  

- [Java 17](https://adoptium.net/)  
- [Maven 3.8+](https://maven.apache.org/)  
- IDE recomendado: [IntelliJ IDEA](https://www.jetbrains.com/idea/)  

---

## ⚙️ Configuración del Proyecto  

1. Clonar el repositorio:  
   ```bash
   git clone
   cd cavosh-coffee-backend

2. Abrir el proyecto con **IntelliJ IDEA** (o el IDE de tu preferencia).
3. Construir con Maven:

   ```bash
   mvn clean install
   ```
4. Ejecutar la aplicación:

   ```bash
   mvn spring-boot:run
   ```

---

## 🗄️ Base de Datos

* En desarrollo se utiliza **H2 Database en memoria**.

* Consola accesible en:

  👉 [http://localhost:8080/h2-console](http://localhost:8080/h2-console)

* Configuración por defecto:

  ```
  Driver Class: org.h2.Driver
  JDBC URL: jdbc:h2:mem:coffee
  User: sa
  Password: (vacío)
  ```

⚠️ Nota: los datos se pierden al reiniciar la aplicación, ya que la base de datos está en memoria.

---

## 📡 Endpoints

* Dentro de la carpeta `/postman` encontrarás una colección exportada para **Postman**.
* Puedes importarla y probar todos los endpoints de la API fácilmente.

---

## 📂 Estructura del Proyecto

```
/src
   /main
      /java
         com.tuorg.cavoshcoffee   # Código fuente
      /resources
         application.properties   # Configuración
/postman   # Colección de Postman para pruebas
```

---

## 🚀 Tecnologías Utilizadas

* Spring Boot 3.5.5
* Spring Web
* Spring Security
* Spring Data JPA
* H2 Database
* Maven
