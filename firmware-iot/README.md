Un sistema de control de clima es un sistema automatizado que se encarga de regular las condiciones ambientales 
en un espacio cerrado, como una casa, una oficina o un autobús, para mantener un ambiente cómodo y adecuado para 
las personas que se encuentran en ese espacio. Esta prueba está enfocada en un sistema de control para un autobús. 
El sistema puede enfriar o calentar, según el valor de temperatura deseado por el conductor y su diferencia con 
la temperatura de la zona que se quiere controlar.  

En esta prueba, el conductor del autobús tiene la posibilidad de establecer la temperatura de zona entre 18 y 30 
grados Celsius. Este sistema cuando está en reposo tiene un valor de presión de baja y de alta de 5 bares. En el 
momento que se demanda frío, la presión de alta comienza a subir y la presión de baja comienza a bajar. La presión 
de alta puede alcanzar los 25 bares de presión, mientras que la de baja puede llegar hasta 0.5 bares.

#### El subsistema de frío está compuesto por los siguientes componentes: 
- __Compresor__: Se activa cuando se requiere enfriar y puede estar en tres estados OFF-MIN-MED-MAX. Está en OFF cuando 
no se demanda frío y el resto depende la demanda de frío.
- __Ventiladores del condensador__: Se activan cuando se activa compresor y varía de 0-100, siendo 0 cuando nó se 
requiere frío y 100 cuando la demanda de frío es máxima.

#### El subsistema de calor está compuesto por los siguientes componentes:
- __Bomba de agua__: Se activa cuando se requiere calor en la zona de control para hacer circular el agua. Puede variar 
de 0-100, siendo 0 que no se requiere calor y 100, cuando la demanda de calor es máxima. 
- __Resistencia eléctrica__: Se activa cuando se requiere calor en la zona de control para calentar el agua. Esta puede 
estar en tres 4 estados diferentes OFF-MIN-MED-MAX. Está OFF cuando no se demanda calor y el resto depende la demanda 
de calor.

#### Elementos comunes: 
- __Sensor de temperatura de zona__: Mide la temperatura de la zona que se quiere controlar.
- __Ventiladores de las evaporadoras__: Se utilizan para introducir el aire en la zona de control de clima, tanto para 
frío como para calor. Su valor varía de 10-100, siendo 10 cuando se ha alcanzado la temperatura deseada.

#### Problema a resolver:   
Usted debe programar un algoritmo de control para este sistema. Para mostrar la solución, el programa debe devolver 
un fichero de salida (csv, json), donde se muestre un conjunto de valores de cada elemento para un valor de entrada 
de temperatura. Además, debe existir la posibilidad de poder observar en pantalla el comportamiento del sistema para 
un valor de temperatura deseada de entrada, mostrando el correspondiente valor del resto sistema.