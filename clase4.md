## Operandos en Memoria

Como pudo verse, la cantidad de registros a los cuales podremos tener acceso cuando se utilice el procesador es bastante limitado, motivo por el cual es necesario dotar a la arquitectura de algún modo a través del cual se puedan almacenar mayor cantidad de datos. Para esta tarea se deben usar accesos a memorias, la arquitectura __SPARCV8__ contiene 2 instrucciones de acceso a memoria conocidas como :

* **LOAD**: Permite acceder a una direccin de memoria específica y tomar 32 bits que luego serán almacenados en un registro.
* **STORE**: Permite tomar el valor de un registro y almacenarlo en la memoria a partir de la dirección de memoria establecida.

