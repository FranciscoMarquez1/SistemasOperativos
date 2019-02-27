## Objetivo
Modificar al programa sh.c para ejecutar el comando anterior

## Herramientas
git
make
gcc

## Conceptos
1) Como se crean nuevos procesos
+ Un programa padre (sh.c) ejecuta la llamada a sistema fork
+ La llamada a sistema fork clona al proceso padre
+ El proceso hijo manda a llamar a exec para ejecutar otro codigo.

## Que aprendi:
Aprendí que C a veces es un poco complicado de usar y tiene ciertas mañanas y cosas donde debemos de poner extra atencion. Además de que existen ciertas practicas donde podemos aprovechar codigo que ya ha sido desarrollaod para adaptarlo y mejorar ciertos metodos.

## Url del commit:
https://github.com/FranciscoMarquez1/SistemasOperativos/commit/b5ab1b41ff59cbc7e9db2e1db49d08fbb5ca988b
