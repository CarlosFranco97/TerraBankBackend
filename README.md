# Proyecto: TerraBank

## Descripción

TerraBank es una aplicación backend desarrollada en Java utilizando JDBC para la conexión con phpMyAdmin (MySQL). La aplicación permite el registro de usuarios, la generación de tarjetas de crédito y la gestión de clientes por parte de un administrador. Se ha implementado un diseño basado en Programación Orientada a Objetos (POO) para estructurar la lógica de negocio.

## Tecnologías utilizadas

Java 17: Lenguaje de programación principal.

JDBC: Para la conexión con la base de datos MySQL.

MySQL: Base de datos utilizada, administrada a través de phpMyAdmin.

Programación Orientada a Objetos (POO): Para una mejor organización del código.

Manejo de Excepciones: Para evitar errores inesperados en la aplicación.

## Características principales

✅ Registro de usuarios con validaciones.
✅ Generación de tarjetas de crédito automática para los usuarios registrados.
✅ Autenticación de administradores para la gestión de clientes.
✅ CRUD de usuarios y tarjetas con operaciones de inserción, consulta y eliminación.
✅ Conexión segura a MySQL mediante JDBC.

## Instalación y configuración

1. Clonar el repositorio
git clone https://github.com/carlosfranco97/terrabankpoo.git

2. Acceder al directorio del proyecto:
cd terrabank

3. Configurar la base de datos MySQL:
Crear una base de datos en phpMyAdmin

4. Crear una base de datos en phpMyAdmin:
-CREATE DATABASE terrabank;
-Importar el esquema de la base de datos desde el archivo db/terrabank.sql.

5. Configurar la conexión en el archivo DatabaseConnection.java:
private static final String URL = "jdbc:mysql://localhost:3306/terrabank";
private static final String USER = "tu_usuario";
private static final String PASSWORD = "tu_contraseña";

6. Compilar y ejecutar la aplicación:
javac -d bin src/*.java
java -cp bin Main

## Autor

Carlos Franco - GitHub
