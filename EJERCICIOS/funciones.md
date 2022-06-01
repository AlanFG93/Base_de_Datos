En base al ejercicio realiza las siguientes consultas

Por error se capturaron mal los siguientes datos, se deben corregir.

![image](https://user-images.githubusercontent.com/91554777/171071745-a92dfd2f-2cf2-4bed-a081-8728f93fc005.png)

USE tienda;

UPDATE producto

SET precio=90.99

WHERE nom_prod='SHAMPOO 500 ML';

UPDATE producto

SET precio=20

WHERE nom_prod='SAL BOLSA';

UPDATE producto

SET precio=56.9

WHERE nom_prod='JABON POLVO 500GR';

UPDATE cliente

SET nom_clie='Daniel Sánchez'

WHERE nom_clie='Daniel Santos';

SELECT *FROM producto;

SELECT *FROM cliente;


![image](https://user-images.githubusercontent.com/103210431/171321783-b43d6254-19aa-4312-87d2-c4810741f4b6.png)

![image](https://user-images.githubusercontent.com/103210431/171321910-0e549be6-b5a0-4b35-b3f0-0c8af8884e74.png)


Realiza las siguientes notas

![image](https://user-images.githubusercontent.com/91554777/171071841-ef5e3549-0235-4c77-846d-62aee10873cf.png)


Agrega un campo en nota que se llame IVA, sabiendo el IVA es de 16% este campo contendrá el valor que corresponda al IVA del subtotal, además de otro campo total donde se mostrará el total de la nota con el IVA.

https://www.db-fiddle.com/f/d869HRuCM9DpUiJTfj9f6A/3
