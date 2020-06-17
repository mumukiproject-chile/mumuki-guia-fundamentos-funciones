Como ya sabés, las expresiones no sólo sirven para operar con números. Vamos a construir ahora una función que denota un valor **booleano** (`True` / `False`).

Lo que queremos averiguar es si el color Rojo es dominante dentro de una celda. Para que sea dominante, se tiene que cumplir que su cantidad de bolitas debe **ser mayor** que la suma de las bolitas de los otros colores.

Por ejemplo, si ejecutamos `rojoEsDominante()` sobre una celda con...

* ...2 rojas, 1 verde, 3 negras, 4 azules, **denota** `False` (hay 2 bolitas rojas contra 8 de otros colores)
* ...9 rojas, 1 verde, 3 negras, 4 azules, **denota** `True` (hay 9 bolitas rojas contra 8 de otros colores)

> Escribí la función `rojoEsDominante()`.