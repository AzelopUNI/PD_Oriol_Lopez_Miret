> **Objetivo de la Practica 7** Mediante el `ESP32-S3` y el protocolo `SPI` conectar un periferico **SD** y mediante el protoclo `I2S` connectar un **Altavoz**

# Primera Parte
La primera parte de la práctica, mediante la placa **ESP32-S3** conectaremos un **Altavoz** mediante el protocolo _I2S_. Utilizamos las librerias `driver/i2s.h`.
Dentro del codigo hemos generado un sonido a una _frequéncia concreta_ para que suene por el **Altavoz**.

# Segunda Parte
En esta segunda parte, tenemos que hacer _exactamente_ lo mismo que en la [Primera Parte](##Primera-Parte), solo que utilizando el periferico de lectura de un **SD**. Mediante las librerias `driver/i2s.h` y  `SD.h`.
en este caso, no _habiá_ ningun archivo dentro de la **SD**, por lo que en primera instància, tuvimos que _añadir_ un archivo de audio dentro de la **SD**. Una vez con el archivo, el codigo tiene que leer el archivo y hacerlo sonar por el **Altavoz** mediante el protocolo `I2S`.
