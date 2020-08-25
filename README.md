# Máquina de estado de Control de nivel de tanques para líquidos coloreados por sensor de luz:

### Memoria descriptiva:

![Preview](https://raw.githubusercontent.com/brianpeluffo/Control-de-nivel-para-tanque/master/Maquina%20de%20estado.jpg)

La máquina de estado anteriormente diagramada representa un control de llenado de tanques de líquidos coloreados, con un sensor de luz como sensor principal y un delta (variación en el volumen del líquido). El volumen es medido por el sensor que se encuentra al nivel deseado por el cliente.

En principio, el tanque se encuentra vacío y se va ingresando el líquido deseado, mientras el tanque se encuentre con un volumen por debajo de la altura máxima elegida seguirá ingresando el líquido. Una vez que el tanque se encuentre lleno hasta el nivel seleccionado, un led se encenderá dando por entendido que se ha completado el ciclo de llenado y se procederá a cerrar por automático la válvula. Cuando el tanque se vacié, se procederá a apagar el led y la válvula se abrirá automáticamente nuevamente hasta completar el ciclo.

-__SET__: Bandera de fin de inicialización.

-__n__: Nivel leído.

-__n_set__: Nivel ingresado.

-__deltaN__: Diferencia en el nivel.

-__N__: Nivel de referencia (normalmente puesto en valor cero).

 
 
