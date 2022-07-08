# VIM

- Acá se podrá encontrar información relevante respecto a VIM.

## Comandos importantes:

- `ESC`+`ESC`+`:q` para salir de VIM.
- `ESC`+`ESC`+`:q`!` para forzar la salida de VIM en caso que hayamos modificado algo antes.
- `k` es arriba, `j` es abajo, `h` y `l` son izquierda y derecha, respectivamente.
- `w` lleva el cursor hacia el siguiente objeto de texto.
- `b` hace lo mismo que `w` pero hacia atrás.
- `e` desplaza el cursor hasta el final de la palabra.
- Para añadir algún caracter en el entorno VIM se debe apretar primero la tecla `i`. Con la tecla `i` pasamos del modo normal al modo insert. En la parte inferior va a aparecer el mensaje `--INSERTAR--` y el cursor va a transformarse en una barra vertical con la que podemos añadir texto. Para salir hay que apretar dos veces la tecla `ESC`.
- Al apretar `ESC` una sola vez, pasará un tiempo antes de cambiar de modo.
- Al apretar las teclas `a` e `i` se pasa del modo normal al modo insert. La diferencia es que con `a` el cursor se ubicará a continuación del caracter en el que se estaba posicionado.
- Con `A` (entiéndase que es mayúscula) puedo ir al final de una línea de código para insertar algo.
- Con la tecla `x` eliminamos los caracteres que queremos eliminar. Esto va a borrar los caracteres que se ubiquen por delante del cursor.
- `:w` es para guardar el archivo. Ojo que es importante estar en el modo normal para que esto funcione.
- `:wq` es para guardar el archivo y salir del editor de texto.
- `g`+`d` lo utilizo para ver la definición de una función en mi código. `g`+`f` lo utilizo para ver la definición de la función pero en otro archivo.
- Respecto al movimiento del cursor entre las definiciones de funciones en el mismo código y en otros archivos, puedo utilizar los comandos `CTRL`+`o` para moverme hacia atrás en el historial y `CTRL`+`i` para moverme hacia adelante.
- Cuando se está en el modo **normal** se puede eliminar texto apretando las teclas `d`+`w`. Se va eliminando texto como si se apretara la tecla `SUPR`.
- Ppara deshacer algo que hice, apretar en modo **normal** la tecla `u` (de *undo* en inglés).
- A diferencia del comando anterior, para rehacer se debe teclear `CTRL`+`r`.
- `d`+`$` elimina todo el texto que está a la derecha del cursor. Si el cursor está al principio de la línea, borra todo el texto sin borrar la línea.

## Notas

- VIM trabaja con modos. Los modos son como capas que se encuentran encima del teclado. Es como lo que pasa en los teclados tradicionales que si apreto la tecla `SHIFT` o `ALT` antes de apretar una tecla en cuestión, en pantalla me va a aparecer otro caracter.

