## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2) 

Es un sistema que agrega y combina información de diferentes fuentes en un almacén de datos único y centralizado

2. Realiza un diseño del modelo en estrella (valor 2)

![image](https://user-images.githubusercontent.com/103210431/171796484-f27df108-fd21-4351-bed2-12f7a67dc26c.png)


3. Realiza un diseño del modelo copo de nieve (valor 2)

![image](https://user-images.githubusercontent.com/103210431/171798488-a740e9f3-713e-4c25-9fd8-fae0514d9254.png)


## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/103210431/171669376-1293c98a-c66d-41f6-9af1-fb0ed3695545.png)

![image](https://user-images.githubusercontent.com/103210431/171669588-71e79ec9-0a9c-4259-9e33-cc5cb62eb313.png)


2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)

https://www.db-fiddle.com/f/sk85j5yM9qAV8Z4tpB5T6q/4

![image](https://user-images.githubusercontent.com/103210431/171786614-31073672-7e23-431f-b70d-d29e80856f92.png)

![image](https://user-images.githubusercontent.com/103210431/171786642-e569b059-93de-42b2-81ab-81b79539aaa9.png)


3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![image](https://user-images.githubusercontent.com/103210431/171784833-b6d0d247-c429-4a56-a709-00346531fedc.png)

![image](https://user-images.githubusercontent.com/103210431/171784858-e12b669a-bf89-4c8e-a974-7cfdb1f9cef6.png)

https://www.db-fiddle.com/f/2jzdSyYAMzpCMuYZV3ZFkz/0

4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

https://www.db-fiddle.com/f/2jzdSyYAMzpCMuYZV3ZFkz/2

![image](https://user-images.githubusercontent.com/103210431/171785948-bd2685c3-65ad-4d70-bab8-296673b1bae4.png)

![image](https://user-images.githubusercontent.com/103210431/171785972-59a0eba0-5b31-441e-bb77-1ab8b686f295.png)




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
