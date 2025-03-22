> **Objetivo De la Practica 5** Mediante el `ESP32-S3` poder conectar y utilizar perifericos como una pantalla led y un detector de humedad  

## Primera Parte
La primera parte de la práctica, utilizamos la placa **ESP32-S3** y primero de todo tenemos que obtener la **Dirección I2C** del _periferico_ que en este caso es el display.
Después conectamos _correctamente_ el display a la placa y junto a las librerias `Adafruit_GFX.h` , `Adafruit_SSD1306.h` y `Wire.h` podemos _imprimir información_ al display.
> En esta práctica es muy importante la Dirección **I2C** de los perifericos que se quieran conectar

 ![Foto del display](Fotos_Pràctica_5_PD/Foto_5_1_Monitor.jpg)
## Segunda Parte
En esta segunda parte de la práctica, tenemos que hacer exactamente lo mismo que en el [primer apartado](##Primera-Parte) solo que también conectaremos un **detector de humedad.** Para usar el detector de humedad tenemos que encontrar la **Dirección I2C** del _periferico_ y utilizar la libreria `AHT10.h`. 
> En este caso al tener _2 perifericos conectados_, la **circuitería** es un poco más _compleja_ que en la Primera Parte, devido a que usan **los mismos pines** de _control._

  ![Foto del_display_&_detector_de_humedad_&_protoboard](Fotos_Pràctica_5_PD/Foto_5_2_Monitor_&_Temperatura.jpg)
  ![Foto del_display_&_detector_de_humedad](Fotos_Pràctica_5_PD/Foto_5_2_Monitor_&_Temperatura_Gran.jpg)

