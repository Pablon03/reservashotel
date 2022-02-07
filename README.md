# Sistema de habitaciones de un hotel
_Práctica 5 del módulo de Programación perteneciente al Grado Superior de Diseño de Aplicaciones Web_
## Problema
Se dispone de la clase Hotel. Se pide: 
1. Crear la clase Habitación que tenga como atributos el número de habitación, el 
tipo (simple, doble o triple) y si está ocupada o no.
2. Se desea incluir en la clase Hotel, un atributo habitaciones (array de 
Habitación). Cuando se cree el hotel se indicará cuántas habitaciones tiene de 
los tres tipos y se creará el array de habitaciones con todas las habitaciones 
libres. Se asignarán los números de habitaciones en este orden: primero las 
simples, luego las dobles y luego las triples. Así mismo, será necesario modificar 
la clase Hotel proporcionada según se estime oportuno.
3. Incluir un método del Hotel para ocupar una habitación (check-in). Se le pasará
el tipo de habitación que se desea y devolverá el número de habitación asignado. 
Si no existe habitación libre de ese tipo se indicará el error.
4. Incluir un método de la clase Hotel para liberar una habitación (chek-out). Se le 
pasará el número de habitación y se quedará libre. En caso de que la habitación 
esté libre o no exista el número de habitación, se indicará el error.
5. Crear un programa principal que cree un Hotel y pruebe los métodos anteriores, 
implementando el siguiente menú
```
.:MENU:.
1. Realizar check-in.
2. Realizar check-out.
3. Consultar información de habitación y hotel.
4. Salir
Introduzca la opción deseada.
```
