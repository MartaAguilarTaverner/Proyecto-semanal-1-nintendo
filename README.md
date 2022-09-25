# Proyecto-semanal-1-nintendo
He tenido bastantes problemas aplicando el grid general, se me movian las cosas y no cuadraban las cosas, 
al igual que al intentar poner el flex dentro también me creaba fallos.

Al final he consiguedo que me cuadrara un poco, aunque la proporción de los botones he tenido que cambiarla varias veces y al final no me ha quedado como
  queria en una primera instancia.
  
En cada paso que daba el grid me generaba más problemas y lo he conseguido sacar en el ultimo momento. No tiene todos los detalles que me gustaría pero
no me ha dado para más.

He empezado creando un grid general para crear una nintendo switch, ya que la tenía en casa, cogi todas las medidas y las pase a pixeles teniendo en cuenta la medida 
general que iba a tener. 

Para los mandos, en la parte del plus y el minus he utilizado un flex, pues estoy más acostumbrada a el y se manejarlo mejor y al ser solo un boton
lo he podido colocar con justify, align y paddings y borders.

Para la parte de conjunto de 4 botones he utilizado un grid, hice al principio menos casillas pero se me movia a cada paso, asi que decidí reducir el tamaño de los
botones para evitar ese problema, o al menos durante parte del proyecto me funcionó.

Luego los botones de home y "square" como he llamado al del lado del mando azul los he puesto con flex, pero cómo no quería que creara disonancia con los 4 anteriores
los he temnido que reducir en tamaño.

El agujero lo he conseguido al final jugando con un z-index inferior he logrado despues de un rato que me cuadrara bien, y aqui el grid se ha vuelto loco y me ha movido
todo durante el proceso, al igual que cuando he intentado crear los botones exteriores, y con los ultimos he acabado rindiendome y poniendolos como border como bien
he podido para que no se me movieran las columnas. Las medidas de cada una de ellas a cada paso variaban y se modificaban aún estando preestablecidas, en definitiva
no me llevo muy bien con el grid.

La pantalla al tener puesto lo de las muescas tambien me ha dado problemas, sobre todo con el borde de fuera.

Mi estructura de codigo se ha basado en containers, he creado un container general, que a su vez ha almacenado tres containers (mandos y pantalla) y a su vez estos han 
almacenado otros, y para detalles más específicos he utilizado identificadres.

He decidido a mitad del proyecto por la cantidad de css que tenia separarlo en tres partes, uno para cada mando y uno general, que tiene datos generales y pantalla, 
de esa forma me ha resultado más facil trabajar y comparar cuando el grid me daba problemás.

Siento si no esta del todo bien, espero ir mejorando con el tiempo.
