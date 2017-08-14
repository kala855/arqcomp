## Operandos en Memoria

Como pudo verse, la cantidad de registros a los cuales podremos tener acceso cuando se utilice el procesador es bastante limitado, motivo por el cual es necesario dotar a la arquitectura de algún modo a través del cual se puedan almacenar mayor cantidad de datos. Para esta tarea se deben usar accesos a memorias, la arquitectura __SPARCV8__ contiene 2 instrucciones de acceso a memoria conocidas como :

* **LOAD**: Permite acceder a una direccin de memoria específica y tomar 32 bits que luego serán almacenados en un registro.
* **STORE**: Permite tomar el valor de un registro y almacenarlo en la memoria a partir de la dirección de memoria establecida.

Estas instrucciones tiene la siguiente sintaxis en ensamblador:

```assembly
ld [address], regrd
st regrd, [address]
```

El **address** se calcula como la suma del contenido del registro fuente 1 y el registro fuente 2, normalmente conocidos como **rs1 y rs2**. También se pueden usar valores inmediatos que reemplazan el **rs2**.

Es muy importante tener en cuenta que la arquitectura __SPARCV8__ direcciona por byte.

* Ejemplo:

Tratemos de compilar una asinación asumiendo que un operando se encuentra en memoria, recuerden asumir que las variables que se usan en lenguaje de alto nivel están creadas e inicializadas cuando haga falta.

```c
f = h + A[8];
```

```assembly
ld [%l2+(32)],%l3
add %l1, %l3, %l0
```
