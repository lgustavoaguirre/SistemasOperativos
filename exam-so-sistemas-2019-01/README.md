# Examen Parcial de Sistemas Operativos
##  Solucion al Punto N°1

Se edita el codigo  del programa threads.c de
*[tarea_01_ostep](tarea_01_ostep) con las instrucciones dadas en el documento del parcial.

#### caso 1:
Se coloca ´´cerrar_ puerta´´  antes del ciclo ´´for´´ y abrimos la puerta una vez se haya finalizado el ciclo,
los tiempos de ejecución aproximadamente con el argumento threads.c 10000000 son:

* ejecucion N.1  56.856 ms *se descarta*
* ejecucion N.2  56.713 ms
* ejecucion N.3  56.328 ms *se descarta*
* ejecucion N.4  56.664 ms
* ejecucion N.5  56.683 ms
#### caso 2:
Se coloca ´´cerrar_puerta´´ antes de incrementar la variable
Los tiempos de ejecución aproximadamente con el argumento threads.c 10000000 son :
* ejecucion N.1   447.51   ms   *se descarta*
* ejecucion N.2   457.447  ms   *se descarta*
* ejecucion N.3   454.124  ms
* ejecucion N.4   447.708  ms
* ejecucion N.5   452.545  ms
#### explicación de los casos
La gran diferecia entre los tiempos se da porque en el programa ´´threads.c´´ la puerta se esta cerrando y abriendo fuera del ciclo ´´for´´
## Solucion al Punto N°2


