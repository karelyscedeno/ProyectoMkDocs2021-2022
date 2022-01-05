##UNIDAD 1
#APE 1.3-Contador de dos cifra
##En la presente actividad se va a desarrollar la simulación de un contador decimal de dos cifras, 0 a 99.
- Elige los componentes electrónicos o CI que cumplen con las siguientes condiciones: temporizador, que realicen un conteo, que muestren información.
- Una vez que ha encontrado los CI, revise las hojas de especificaciones de cada uno de ellos, para que obtenga información de su funcionamiento.
- Realice las configuraciones necesarias para alimentar los dispositivos electrónicos.
- Realice la simulación de un circuito para evaluar el funcionamiento del CI en una configuración básica.
- Realice la configuración del circuito que cuente de 0 a 99
![Texto alternativo](https://i.ibb.co/pWVnCTQ/contador1.png)
![Texto alternativo](https://i.ibb.co/nfDJWWm/contador2.png)
##¿CÓMO FUNCIONA EL CIRCUITO?
El siguiente circuito representa un contado de 2 cifras. El primer chip (555) se encarga de mandar pulsos con un intervalo de tiempo regular (el tiempo se regula con el valor de resistencia R2), este pulso llega al chip (4026-1-U3) el cual está encargado de emitir una señal la cual será recibida por el led verde formando los dígitos. Posteriormente cada decimo número el chip (4026-1-U3) emitirá un pulso el cual será inviado al chip (4026-2-U4), cuando esta reciba un pulso mandará una señal al led rojo este representará la cantidad de decenas en el conteo, el switch conectado a los pines #3 de cada chip (4026) será el que arranque el circuito y el que está conectado al chip (555) será el que inicie el conteo. 

- La gráfica #1 representa el circuito arrancado.
![Texto alternativo](https://i.ibb.co/3Sn5n70/contador3.png)

- La gráfica #2 representa el circuito haciendo el conteo.
![Texto alternativo](https://i.ibb.co/cXTwtkQ/contador4.png)

- La gráfica #3 representa el máximo conteo del circuito.
![Texto alternativo](https://i.ibb.co/0J9YrZx/contador5.png)