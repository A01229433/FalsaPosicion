# FalsaPosicion

La falsa posición es una alternativa a la bisección basada en una visualización gráfica. Un inconveniente del método de bisección es que al dividir el intervalo de xl a xu en mitades iguales, no se toman en consideración las magnitudes de f(xl) y f(xu). Por ejemplo, si f(xl) está mucho más cercana a cero que f(xu), es lógico que la raíz se encuentre más cerca de xl que de xu. Un método alternativo que aprovecha esta visualización gráfica consiste en unir f(xl) y f(xu) con una línea recta. La intersección de esta línea con el eje de las x representa una mejor aproximación de la raíz. El hecho de que se reemplace la curva por una línea recta da una “falsa posición” de la raíz; de aquí el nombre de método de la falsa posición, o en latín, regula falsi. También se le conoce como método de interpolacion lineal.

Usando triángulos semejantes, la intersección de la línea recta con el eje de las x se estima mediante una semajanza de triangulos, en la cual se despeja xr.

![uno](http://1.bp.blogspot.com/-OGqfrUfX01c/VHlQ5C6oZWI/AAAAAAAAACU/zZy2erBUrTw/s1600/Met%2BFalsa%2BPos%2B2.jpg)

Ésta es la fórmula de la falsa posición. El valor de xr calculado con la ecuación, reemplazará, después, a cualquiera de los dos valores iniciales, xl o xu, y da un valor de la función con el mismo signo de f(xr). De esta manera, los valores xl y xu siempre encierran la verdadera raíz.
