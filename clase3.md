# Instrucciones: El lenguaje del Procesador

Las "palabras" de un procesador se conocen como **Instrucciones** y su vocabulario se suele llamar **Conjunto de Instrucciones**.

## Operaciones del Hardware del Procesador

Como es bien sabido resulta determinante que una arquitectura de cómputo (Procesador), esté en la capacidad de realizar **Operaciones** sobre datos. A estas operaciones normalmente se les pueden llamar Instrucciones, y generalmente son realizadas sobre un máximo de tres elementos, de allí que se conozcan como operaciones **triádicas**. La arquitectura __SPARCV8__ contiene un total de 71 instrucciones aproximadamente, el tamaño de las instrucciones es de 32 bits fijo, lo que permite que sea una arquitectura tipo __RISC__.

Por ejemplo, la instrucción **suma** utilizando variables se puede establecer de la siguiente forma. Recordemos que estamos hablando de una arquitectura **SPARCV8 (Scalable Processor ARChitecture)**:

```
a = b + c; --> add b,c,a
```
Tenemos una asignación simple en __C__, donde estamos sumando las variables __b__ y __c__ y guardando el resultado en __a__. Cabe aclarara que para que el ejemplo tenga sentido estamos asumiendo que las tres variables han sido declaradas previamente y adicionalmente que tanto __b__ como __c__ han sido inicializadas.

En el ejemplo, como podemos observar, las variables __b__ y __c__ serán conocidas como operandos y la variable __a__ será nuestra elemento destino, donde se almacenará el resultado de la operación.

El hecho de que se trabaje con instrucciones que a lo sumo serán __triádicas__ le da sentido al primer principio de diseño de toda arquitectura de cómputo en la cual se menciona:

* La simplicidad favorece la regularidad.

Entendiéndose como regularidad a que el procesador deberá funcionar correctamente siempre. Esto tiende a ser mucho más viable si nuestros diseños se mantienen simples.

## Operandos del Hardware del Procesador

