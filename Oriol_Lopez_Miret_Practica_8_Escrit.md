> **Objetivo de la Practica 8** Mediante el `ESP32-S3` haremos una *comunicación serie asincrona* **usart**.

Mediante la placa **ESP32-S3** realizaremos un **bucle de comunicacion**. Mandaremos los datos por el terminal `rxd0` que se redirijan a la 
`uart 2 txd2`, y la recepcion de los datos de la `uart2` se reenvien de nuevo a la salida `txd0`.
Esto hace que los _datos_ que enviamos, se **reenvien** a la _pantalla del terminal_ permitiendo _escrivir_ en el terminal de 'PlatformIO'.

 ![Foto_2](Fotos_Pràctica_8_PD/Foto_2.jpg)
> Como se puede observar en la _foto del terminal_, Podemos escrivir en el terminal usando la 'ESP32-S3'

 ![Foto_1](Fotos_Pràctica_8_PD/Foto_1.jpg)
 >Como se puede observar en la _foto del montaje_, si _desconectamos_ el cable la comunicacion se pierde, no pudiendo escrivir en el **terminal**.
