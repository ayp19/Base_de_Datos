
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2)

Es un sistema que agrega y combina información de diferentes fuentes en un almacen de datos único y  centralizado.
Esto permite a una empresa ejecutar análisis potentes en grandes vólumenes.

2. Realiza un diseño del modelo en estrella (valor 2)
<img width="349" alt="Screen Shot 2022-06-02 at 11 52 13 PM" src="https://user-images.githubusercontent.com/103067169/171788997-5d0a6863-aaac-4044-95f9-e6eaf56bf790.png">





3. Realiza un diseño del modelo copo de nieve (valor 2)
<img width="724" alt="Screen Shot 2022-06-02 at 11 55 49 PM" src="https://user-images.githubusercontent.com/103067169/171788942-3263a196-d57e-4b4d-91ce-37c3ac284e1d.png">



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
![imagen](https://user-images.githubusercontent.com/103067169/171878876-064b79dd-2ef0-45d3-ae2a-437a46372fb4.png)



3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![imagen](https://user-images.githubusercontent.com/103067169/171675388-394c9787-2e06-4952-bb49-00349296ff0d.png)

4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

![imagen](https://user-images.githubusercontent.com/103067169/171882553-b388124f-8889-47c4-b0b4-54432fc591ab.png)


  https://www.db-fiddle.com/f/iGVBXUtmfFVDjSnNPxqTsJ/5

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

<img width="298" alt="Screen Shot 2022-06-02 at 10 48 54 PM" src="https://user-images.githubusercontent.com/103067169/171782370-d61ce970-00a4-4967-8e83-ab46d6858612.png">


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
 
 
 1.- Qué es un trigger?
 
 Es un script  que se usa en SQL y son una serie de reglas predefinidas que se asocia a una tabla y se aplican a la base de datos  cuando se realizan determinadas operaciones, al usar los comandos ( INSERT, UPDATE Y DELETE).
 
 2.-Cuál es la función de un trigger?
 
 La función  es contribuir a la mejora de la gestión  de la base de datos de forma autómatica. Se usan generalmente para garantizar la integridad y seguridad de la info. a traves  de restricciones, requerimientos o acciones de verificación para evitar errores y facilitar la sincronización de la info.
 
 3.-Cuáles son los dos escenarios de uso de un trigger?
 
 El primer escenario es cuando no podemos intervenir en el código fuente de la aplicacion que trabaja la BD.
 La segunda es cuando aunque tengamos el código este pertenece a un software desarrollado por terceros y hay riesgo de aplicar actualizaciones o instalar  plugins y se busca modificar el código lo menos posible.
 
 4.- Cuándo se puede usar un trigger?
 
 Se puede usar cuando el usuario realiza una acción relacionada con añadir, actualizar o eliminar información en una tabla ( INSERT, UPDATE,DELETE), esto nos puede ayudar a capturar los eventos que modifican la base de datos y actuar en consecuencia.
 
 
