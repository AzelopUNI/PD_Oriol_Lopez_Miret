> **Objetivo de la Practica 6** Mediante el `ESP32-S3` y el protocolo `SPI` conectar un periferico **SD** y **RFID-RC522**

# Primera Parte
La primera parte de la práctica, mediante la placa **ESP32-S3** conectaremos un periferico **SD** mediante el protocolo _SPI_. Utilizamos las librerias `SPI.H` y `SD.h`.
Dentro del codigo, tenemos que _especificar_ que archivo vamos ha _leer_ y al ejecutar el codigo nos tendrá que salir que nos hemos conectado _correctamente_.

 ![Foto_6_1_Display](Fotos_Pràctica_6_PD/Foto_6_1_Disp.jpg)
> Como se puede observar en la _foto de montaje_, al estar usando el **bus SPI**, podemos observar como 2 de los _seis_ cables són la conección **Maestro-Esclavo (MOSI)** y **Esclavo-Maestro (MISO)** siendo la característica principal de los _buses SPI_,
> y el resto siendo el **Reloj (CLK)** el **VIN, GND, y el SS**.

 ![Foto_6_1_Montaje](Fotos_Pràctica_6_PD/Foto_6_1_Perif.jpg)

# Segunda Parte
En esta segunda parte, tenemos que hacer _exactamente_ lo mismo que en la [Primera Parte](##Primera-Parte), solo que utilizando el **RFID-RC522**. Mediante las librerias `SPI.h` y  `MFRC522.h`, en este caso, nos tiene que salir el **UID** de la _tarjeta / llavero_ que le acerquemos an el terminal.

![Foto_6_2_Display](Fotos_Pràctica_6_PD/Foto_6_2_Disp.jpg)

> Al estar utilizando el **bus SPI**, las conecciones són identicas a las de la [Primera Parte](##Primera-Parte).

![Foto_6_2_Montaje](Fotos_Pràctica_6_PD/Foto_6_2_Perif.jpg)
