## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?
(valor 1.5)
  1.- Asegurar el buen funcionamiento de las BD
  2.-Retención de información de las BD
  3.-Evitar pérdida de datos
  4.-Solucionar incidencias y pérdidas de datos
  5.-Asegurar la seguridad de los dato


2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)

    1.-Instalar, configurar y gestionar bases de datos.
    2.-Dar soporte al equipo de desarrollo, seguridad informática y redes.
    3.-Definir el esquema del diccionario de datos.
    4.- Especificar restricciones de integridad para asegurar los datos.
    5.-Garantizar la alta disponibilidad de la base de datos.


3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)
    1.-Instalar, configurar y gestionar bases de datos.
    2.- Dar soporte al equipo de desarrollo, seguridad informática y redes.
    3.- Definir el esquema del diccionario de datos.
    4.-Especificar restricciones de integridad para asegurar los datos.
    5.-Garantizar la alta disponibilidad de la base de datos.


4. ¿Qué es un Sistema de Información? (valor 1.5)

Un sistema de información es un conjunto de elementos enfocados  al tratamiento y administración de informacion  y datos, organizados y listos para ser usados, que son generados para cubrir una necesidad.

## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias sucursales, con su domicilio, teléfono y un código de
sucursal.

● Cada sucursal tiene varios empleados, de los cuales tendremos su nombre,
apellidos, NIF y teléfono. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias revistas, de las que almacenaremos su título,
número de registro, periodicidad y tipo.

● Una revista puede ser publicada por varias sucursales.

● La editorial tiene periodistas (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las secciones fijas que tiene cada revista, que
constan de un título y una extensión.

● Para cada revista, almacenaremos información de cada ejemplar, que incluirá la
fecha, número de páginas y el número de ejemplares vendidos.

Sucursales
Domicilio
Teléfono 
Código de sucursal 

Empleados
Código de empleado
Nombre
apellido
NIF
teléfono

Revistas
Título
número de registro 
periocidad
Tipo

Periodista
Código 
Nombre
apellido
NIF
teléfono
Especialidad

Secciones 
Título 
extensión

Ejemplar 
fecha
número de pág.
número de ejemplaresvendidos

<img width="935" alt="Screen Shot 2022-05-30 at 10 03 38 PM" src="https://user-images.githubusercontent.com/103067169/171085161-47125767-fab5-4b52-a9da-a43f47da08e3.png">

https://www.db-fiddle.com/f/uVzk1m7TvqCg5Hc7n7XGsM/8
