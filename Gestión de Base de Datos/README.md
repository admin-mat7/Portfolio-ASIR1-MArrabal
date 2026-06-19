# Proyecto de Diseño y Gestión de Bases de Datos

Este repositorio contiene el desarrollo completo para el diseño, normalización e implementación de la base de datos para el sistema de gestión del proyecto. El trabajo abarca desde la conceptualización teórica hasta la creación física del modelo relacional.

## Herramientas Utilizadas

* Microsoft Visio: Diseño del Diagrama Entidad-Relación (E/R) y Modelo Relacional.
* Microsoft Access: Implementación física de la base de datos (archivos ACCDB / MDB).

---

## Fases del Proyecto

### 1. Normalización de Datos
Para garantizar la integridad de la información y evitar la redundancia, se han aplicado las reglas de normalización a las entidades del sistema:
* Primera Forma Normal (1FN): Eliminación de grupos repetidos y definición de claves primarias.
* Segunda Forma Normal (2FN): Eliminación de dependencias parciales, asegurando que todos los atributos no clave dependan de la clave primaria completa.
* Tercera Forma Normal (3FN): Eliminación de dependencias transitivas, garantizando que los atributos no clave dependan únicamente de la clave primaria.

### 2. Diagrama Entidad-Relación (E/R)
* Diseñado en Microsoft Visio.
* Define las entidades, atributos, claves primarias (PK) y claves foráneas (FK).
* Establece las cardinalidades correspondientes (1:1, 1:N, N:M) y la resolución de relaciones muchos a muchos mediante tablas intermedias.

### 3. Orden de Llenado de Datos (Integridad Referencial)
Para evitar errores de restricción de clave foránea al insertar los registros en Access, se sigue un orden lógico de inserción que va desde las tablas independientes hacia las dependientes:
* Tablas Maestras (Nivel 1): Tablas que no dependen de ninguna otra (ej. entidades principales con datos base).
* Tablas Secundarias (Nivel 2): Tablas que dependen directamente de las tablas maestras al incluir sus claves como FK.
* Tablas Relacionales/Transaccionales (Nivel 3): Tablas intermedias o de registro de actividad que requieren la existencia previa de los registros de los niveles 1 y 2.

### 4. Implementación en Microsoft Access
* Creación de tablas con sus respectivos tipos de datos, tamaños de campo y restricciones.
* Configuración de las relaciones en el motor de Access activando la opción de Exigir integridad referencial y las actualizaciones/eliminaciones en cascada según el diseño.
* Desarrollo de la estructura necesaria para consultas, formularios e informes.

---

## Estructura del Entregable

* /Diseno: Archivos de Microsoft Visio con los diagramas de bloques y relacionales.
* /BaseDeDatos: Archivo de Microsoft Access listo para su ejecución y pruebas.
* README.md: Este archivo con la descripción técnica del proyecto.
