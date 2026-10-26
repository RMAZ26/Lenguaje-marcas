static: añade left: 50px a .c1. ¿Se mueve? ¿Por qué? 
No se mueve por que static es el posiscionamiento normal de la pagina por defecto  y los elementos asi predefinidos ignoran los valores de desplazamiento

relative: Deja hueco respecto a su posicion original y como hemos puesto left se aleja 50 px de espacio de la izquierda

absolute: pon c3 en position: absolute con top: 0 y right: 0. ¿A qué esquina va?  
A la de arriba izquierda 

Ahora añade position: relative a .contenedor. ¿Qué cambia? 
.contenedor se convierte como en el ancla o referente de los elementos absolutos que tiene dentro

Y qué hacen los demás cuadros con el hueco de c3?

Los demás cuadros ocupan el hueco inmediatamente como si c3 hubiera desaparecido.
Ocupan su sitio de inmediato. Al ponerse en position: absolute, c3 sale del flujo normal y deja de ocupar espacio físico, como si hubiera desaparecido.