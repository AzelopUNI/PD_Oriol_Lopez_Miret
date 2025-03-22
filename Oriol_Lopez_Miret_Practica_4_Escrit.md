> **Objetivo De la Practica 3** Mediante el `ESP32-S3` comprenderemos el funcionamiento de un **sistema operativo** en tiempo real.

## Primera Parte
La primera parte de la práctica, utilizamos la placa **ESP32-S3** para crear una tasca **vacia**. Como el _loop es infinito_ nunca se detendrá, pero al no hacer nada es inapreciable.

## Segunda Parte
En esta segunda parte volvemos a hacer como en la [Primera Parte](##Primera-Parte), pero esta vez, la tasca tendrá que _encender y apagar_ un led.
  
## Tercera Parte
En esta ultima parte volvemos a hacer com en la [Segunda Parte](##Segunda-Parte), solo que utilizaremos **2 tascas** y un **semaforo**.
La primera tasca tiene que _encender el led_ y la _segunda apagar_, y el semaforo tiene que ir _canviando de tasca _obteniendo el**mismo** resultado que en la [Segunda Parte](##Segunda-Parte).
