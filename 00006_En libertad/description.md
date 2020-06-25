Queremos escribir la función `esLibreCostados()`, que determine si el cabezal tiene libertad para moverse hacia los costados (es decir, este y oeste).

Antes que nada, pensemos: ¿qué **tipo** tiene que denotar nuestra función? Será...

* ... ¿un **color**? No.
* ... ¿un **número**? Tampoco.
* ... ¿una **dirección**? Podría, pero no. Fíjate que lo que pide es _"saber si puede moverse"_ y no hacia dónde.
* ... ¿un **booleano**? ¡Sí! :tada: Cómo nos dimos cuenta: lo que está pidiendo tiene pinta de **pregunta** que se responde con sí o no, y eso es exactamente lo que podemos representar con un valor booleano: **verdadero** o **falso**.

Pero, ups, hay un problema más; hay que hacer DOS preguntas: ¿se **puede mover** al este? **Y** ¿se **puede mover** al oeste?. :fearful:

Bueno, existe el operador `&&`, que sirve justamente para eso: toma dos expresiones booleanas y devuelve `True` solo si **ambas** son verdaderas. Si sabes algo de lógica, esto es lo que comunmente se denomina **conjunción**, y se suele representar con el símbolo ∧.

Por ejemplo, si quisiéramos saber si un casillero tiene más de 5 bolitas y el `Rojo` es el color dominante, podríamos escribir:

``` gobstones
nroBolitasTotal() > 5 && rojoEsDominante()
```

> Implementa la función `esLibreCostados()` que indique si el cabezal puede moverse tanto al este como al oeste.
