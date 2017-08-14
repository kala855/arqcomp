# Instrucciones: El lenguaje del Procesador

Las "palabras" de un procesador se conocen como **Instrucciones** y su vocabulario se suele llamar **Conjunto de Instrucciones**.

## Operaciones del Hardware del Procesador

Como es bien sabido resulta determinante que una arquitectura de cómputo (Procesador), esté en la capacidad de realizar **Operaciones** sobre datos. A estas operaciones normalmente se les pueden llamar Instrucciones, y generalmente son realizadas sobre un máximo de tres elementos, de allí que se conozcan como operaciones **triádicas**

Por ejemplo, la instrucción **suma** utilizando variables se puede establecer de la siguiente forma. Recordemos que estamos hablando de una arquitectura **SPARCV8 (Scalable Processor ARChitecture)**:

```
a = b + c; --> add b,c,a
```

En el ejemplo, como podemos observar, las variables __b__ y __c__ serán conocidas como operandos y la variable __a__ será nuestra elemento destino, donde se almacenará el resultado de la operación.
