# DISEÑO DE UN ROBOT MANIPULADOR DE 4 GDL USANDO ANÁLISIS CINEMÁTICO Y DINÁMICO.
Proyecto de grado del programa de Ingeniería Electrónica  de la Universidad El Bosque 2022-2

Con el diseño de un robot manipulador usando el análisis cinemático y dinámico, se buscó tener mayor visibilidad de las funciones que puede 
desarrollar este tipo de dispositivos en diferentes campos ambientales en los que se someta. Este manipulador es diseñado con 4 GDL con su 
respectivo análisis cinemático directo a partir de los parámetros de Denavit-Hartenderg, cinemática inversa donde se estimó una restricción 
en la articulación número 4 equivalente a q_4=0  para así poder tener una matriz de 3 ecuaciones con 3 incógnitas para hallar el valor de 
q_1,q_2  y q_3. Por último, se obtuvo la velocidad cinemática, cálculo Jacobiano, velocidades en las junturas y singularidades. Ahora bien, 
para el análisis dinámico, se partió del jacobiano en cada una de las articulaciones para poder conocer la energía cinética y potencial para 
poder hallar el lagrangiano seguido de las ecuaciones de movimiento para cada una de las articulaciones, donde se demuestra que se adapta a 
diferentes trabajos por la resistencia que tiene en estructura, en caso que se someta a trabajos de carga, así mismo su desempeño es óptimo 
para desarrollar movimientos más fluidos. Con este diseño matemático, se buscó demostrar los diferentes factores y cálculos importantes a la 
hora de escoger los actuadores, así como obtener un análisis computacional capaz de asemejar a la realidad los movimientos y posiciones en 
los que puede ser sometido teniendo movimientos entre los ±90°.


Palabras Clave: Denavit-Hartenderg, análisis computacional, jacobiano, lagrangiano, junturas.
