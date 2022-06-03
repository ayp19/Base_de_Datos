
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2)
Es un sistema que agraga y combina información de diferentes fuentes en un almacen de datos único y  centralizado.

2. Realiza un diseño del modelo en estrella (valor 2)
![imagen](https://user-images.githubusercontent.com/103067169/171657772-7ed11ff3-db34-4ae2-a585-7e5bae78c61c.png)



3. Realiza un diseño del modelo copo de nieve (valor 2)
4. 
![imagen](https://user-images.githubusercontent.com/103067169/171658171-43b2ccd9-415d-42d0-ba5b-e9167da6ff2a.png)


## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)

![imagen](https://user-images.githubusercontent.com/103067169/171661656-79c64a67-3141-4771-9bbb-3b5cffee12b6.png)

2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)
![imagen](https://user-images.githubusercontent.com/103067169/171676168-d1d0a8fb-665f-437b-8c32-5bf5774688e1.png)


3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![imagen](https://user-images.githubusercontent.com/103067169/171675388-394c9787-2e06-4952-bb49-00349296ff0d.png)

4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

<img width="1175" alt="Screen Shot 2022-06-02 at 7 55 37 PM" src="https://user-images.githubusercontent.com/103067169/171765257-a5bc4c9a-ac4a-4537-9c8a-2b5e66938bca.png">


## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Si el nuevo valor de la nota que se quiere insertar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere insertar es mayor que 10, se
  guarda como 10.

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Si el nuevo valor de la nota que se quiere actualizar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere actualizar es mayor que 10, se
  guarda como 10.
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.
 https://www.db-fiddle.com/f/iGVBXUtmfFVDjSnNPxqTsJ/1
