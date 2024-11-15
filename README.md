# Sistema de Gestión de Tiendas Online-
Descripción General

Este proyecto consiste en el desarrollo de un sistema backend para la gestión de una tienda en línea. El sistema permite a los usuarios (clientes) explorar productos, agregar productos al carrito de compras, realizar pedidos y revisar su historial de compras. Por otro lado, administradores podrán gestionar el catálogo de productos, procesar pedidos y controlar el inventario. También se incluyen funcionalidades para generar reportes de ventas y productos populares.

Características del Sistema

Clientes:
Navegar por el catálogo de productos.
Agregar productos al carrito.
Realizar pedidos.
Consultar historial de compras.
Administradores:
Gestión del catálogo de productos.
Procesamiento de pedidos.
Gestión del inventario.
Generación de reportes de ventas y análisis de productos populares.
Requisitos Técnicos

Lenguaje: Java
Base de Datos: MariaDB (comentada en el archivo readme.txt).
Framework ORM: Hibernate para el mapeo objeto-relacional.
Framework: Spring Boot para la gestión de dependencias y APIs REST.
Frontend: Implementado también con Spring Boot (enfocado en funcionalidad, no en diseño estético).
Colecciones y Streams: Uso de Streams en Java para procesar y filtrar listas de productos, pedidos y clientes.
APIs: Exposición de APIs REST para la gestión de pedidos.
Diagramas UML

Los siguientes diagramas están incluidos en el repositorio:

Diagrama de Clases: Define las clases principales y sus relaciones.
Diagrama de Secuencias: Ilustra los flujos de interacción para escenarios clave.
Diagrama de Interfaz (opcional): Describe las interfaces de usuario (si se incluye).
Diagrama de Flujo (opcional): Representa el flujo general del sistema (si se incluye).
Instalación y Ejecución

Pre-requisitos
Java: Asegúrate de tener Java 8 o superior instalado.
Maven: Este proyecto utiliza Maven para la gestión de dependencias.
MariaDB: La base de datos predeterminada es MariaDB. Asegúrate de tenerla configurada y en funcionamiento.
Instrucciones
Clonar el repositorio:
git clone https://github.com/Sama2308/PROYECTO-FINAL-.git
cd PROYECTO-FINAL
Configurar la Base de Datos:
En el archivo de configuración application.properties, actualiza los datos de conexión a MariaDB.
Utiliza el script de inicialización incluido (init.sql) para crear la base de datos y las tablas necesarias:
mysql -u [usuario] -p < init.sql
Ejecutar el proyecto con Maven:
mvn spring-boot:run
Estructura del Proyecto

Controladores: Manejan las solicitudes HTTP y exponen las APIs REST necesarias para el frontend.
Servicios: Implementan la lógica de negocio del sistema, como el procesamiento de pedidos y la gestión de inventario.
Repositorios: Manejan la interacción con la base de datos utilizando Hibernate.
Entidades: Representan las tablas de la base de datos en el código Java.
Notas adicionales

El archivo init.sql contiene todas las instrucciones SQL para inicializar la base de datos, crear las tablas e insertar datos de prueba.
Se recomienda revisar el archivo application.properties para ajustar configuraciones específicas de la base de datos.
La aplicación está diseñada para ser funcional sin necesidad de una interfaz gráfica avanzada; el enfoque es la funcionalidad backend.
Contribución

Este proyecto fue desarrollado en colaboración con el equipo asignado en clase, con el objetivo de aplicar los conocimientos adquiridos en el curso. La entrega se realiza en GitHub para facilitar la revisión y evaluación.

Licencia

Este proyecto es de carácter educativo y forma parte del curso de programación, por lo que su uso y distribución están restringidos a fines académicos
