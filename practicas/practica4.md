## Objetivo
Hacer un planificador de procesos basado en prioridades. 
El proceso con mayor prioridad se ejecuta primero. 
Si hay dos o mas con misma prioridad, el primero de la lista.

## Herramientas
git

make

gcc

## Conceptos
1) Proceso
2) Planificacion de proceso:
+ Es el mecanismo que el SO tiene para asignarle el cpu a un proceso.
3) Estados de un proceso
4) Cambio de contexto:
+ Ocurre cuando el cpu deja de ejecutar el proceso para ejecutar otro.
+ Guardar el PC y la direccion del stack del proceso actual.
+ Restaurar el PC y la direccion del nuevo proceso.

## Que aprendí:
Aprendí que existe algo llamado scheduler que esta corriendo todo el tiempo en el sistema operativo, este es el encargado de determinar que proceso se debe de estar ejecutando. En este caso comenzamos la practica, realizando 2 funciones basicas, encargadas de definir la prioridad del proceso y otro encargado de imprimirlo y mostrar que el cambio de la prioridad si se esta realizando. 

## Url del commit:
https://github.com/FranciscoMarquez1/SistemasOperativos/commit/1a327cbed21204cd71cf1fc3965f312860f9cab7

## Como se relaciona con los conceptos anteriores:
Llamados a sis
