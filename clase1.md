# ¿Qué es Arquitectura de Computadores?

Puede verse como una ciencia o arte que busca la interconexión de diversos 
dispositivos para lograr un objetivo específico de funcionalidad.

# Breve Reseña Histórica de las Generaciones de los Computadores

La idea es que demos un repaso a las diferentes generaciones de los computadores
fijándonos sólo en aspectos que resaltarán entre cada una. Así que iniciemos:

## Primera Generación - La válvula o tubo de vacío (1946-1954)

* 1943 -> ENIAC -> 30 toneladas -> 140 Kw.
* 1946 -> Máquina de John Von Neumann (Arquitectura utilizada hasta nuestros días)
* 1953 -> IBM crea algunas máquinas (701, 704, 709).

## Segunda Generación - El Transistor (1957-1964)

* 1948 -> En los Laboratorios Bell inventaron el transistor y con este desarrollo se ganaron el premio Nobel de física. 
* 1961 -> La empresa Digital Equipment Corporation (DEC) lanza un computador conocido como el PDP-1 con una RAM de 120 KB, basado en transistores y la venta al público era de USD $120.000. En este mismo año IBM lanza el IBM 7090 y tenía 32 KB de RAM
* 1964 -> Sale al mercado el CDC 1600 -> Primera Máquina paralela.

## Tercera Generación - El Circuito Integrado (1964-1971)

* 1964 -> Aparece el S/360 -> Registros de 32 bits con direccionamiento de memoria de 2^24 posiciones.
* 1959 -> Texas Instruments desarrolla el primer circuito integrado con 12 transistores.

## Cuarta Generación - Large Scale Integration (LSI), Very Large Scale Integration (VLSI), Microprocesador (1971-1983)

* Decenas de miles de transistores en un chip (LSI -> Large Scale Integration)
* Cientos de miles de transistores en un chip (VLS -> Very Large Scale Integration)
* Microprocesador.
* Caída de precios por lo que la IBM desarrolla el primer PC.

## Quinta Generación - Very High Scale Integration (VHLSI), PC's (1990-????)

* Very High Large Scale Integration -> millones de transistores. 

# Máquina de Von Neumann

Características: 

* La memoria es unidimensional.
* Existe una sola memoria para almacenar instrucciones y datos. Este concepto varía un poco en la
actualidad donde podemos encontrar comúnmente procesadores con memoria de datos e instrucciones 
a parte.
* Las instrucciones se ejecutan de manera secuencial. Deben existir instrucciones de salto
que permitan romper esta secuencialidad. Esto es aún cierto en la actualidad.

![ArqVonNeumann](./images/arqVon.jpg "Diagrama de Bloques de una Arquitectura de Von Neumann Típica")

