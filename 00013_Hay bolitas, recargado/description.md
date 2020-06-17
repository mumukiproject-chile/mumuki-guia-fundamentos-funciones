Escribamos ahora una versión mejorada de `hayBolitasAl`, que funcione **siempre**. ¿Qué quiere decir esto? Que tiene que devolver un booleano **aún cuando no haya más tablero** en la dirección especificada. Para diferenciarla de la anterior, la llamaremos `hayTableroYBolitasAl`.

Si es posible moverse en la dirección, la función deberá comportarse igual que `hayBolitasAl`, pero si no **puede moverse** deberá devolver Falso.

> Usando `hayBolitasAl`, programá la función `hayTableroYBolitasAl(direccion, color)` que se comporte como dijimos.