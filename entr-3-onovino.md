# Entregable informática - 3 - clase 15 [onovino]

## ¿Por qué un lenguaje de programación sólo puede utilizarse en algunos sistemas operativos y en otros no?.
Un lenguaje de programación compila a lenguaje ensamblador el cual es ejecutado por el sistema operativo, este lenguaje ensamblador depende de 2 cosas, de la arquitectura del procesador y la interpretación que le de el sistema operativo, entonces se puede usar en cualquier sistema operativo siempre y cuando se cuente con un compilador compatible.

## ¿Qué tipo de máquina virtual soporta virtualBox?.
Soporta máquinas virtuales de tipo sistema.

## ¿Qué función cumple el hypervisor en la virtualización?
Es el software que cumple la función de monitor de máquinas virtuales, desde su creación hasta su ejecución. Permite que un servidor de virtualización preste soporte a varias máquinas virtuales hospedadas.

## Si tengo más de una máquina virtual instalada, y una se rompe, ¿esto afecta a las demás? ¿por qué?
No, pues son creadas de forma independiente. Cada una tiene sus propios recursos, por ende si una de estas falla no debería de
afectar a las otras, a pesar de que se ejecuten en el mismo servidor son instancias que no dependen entre sí.
