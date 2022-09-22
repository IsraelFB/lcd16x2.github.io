# Exposicion sobre los LCD
##  Cuando los simples indicadores luminosos con led ya no son suficientes, habitualmente el siguiente paso para todo programador es ir por una pantalla lcd 16×2. 



![cooltext419183073128565](https://user-images.githubusercontent.com/104939556/190014568-aaa22c6f-a842-41cc-8436-07488de3267c.png)
### LCD 16×2
El LCD(Liquid Crystal Dysplay) o pantalla de cristal líquido es un dispositivo empleado para la visualización de contenidos o información de una forma gráfica, mediante caracteres, símbolos o pequeños dibujos dependiendo del modelo.
El LCD consta de 16 terminales las cuales podemos dividir en pines de alimentación, control y bus de datos bidireccional. Por lo general podemos encontrar ademas en su estructura los pines de Anodo de led backlight y cátodo de led backlight.

#### Pines de alimentación
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Pin</th>
    <th class="tg-0pky">Descipcion</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">Vss</td>
    <td class="tg-0pky">Gnd</td>
  </tr>
  <tr>
    <td class="tg-0pky">Vdd</td>
    <td class="tg-0pky">+5 voltios</td>
  </tr>
  <tr>
    <td class="tg-0pky">Vee</td>
    <td class="tg-0pky">corresponde al pin de <br>contraste, lo regularemos <br>con un potenciómetro de <br>10K conectado a Vdd.</td>
  </tr>
</tbody>
</table>

#### Pines de control

°RS: Corresponde al pin de selección de registro de control de datos (0) o registro de datos(1). Es decir el pin RS funciona paralelamente a los pines del bus de datos. Cuando RS es 0 el dato presente en el bus pertenece a un registro de    control/instrucción. y cuando RS es 1 el dato presente en el bus de datos pertenece a un registro de datos o un carácter.

°RW: Corresponde al pin de Escritura(0) o de Lectura(1). Nos permite escribir un dato en la pantalla o leer un dato desde la pantalla.
E: Corresponde al pin Enable o de habilitación. Si E(0) esto quiere decir que el LCD no está activado para recibir datos, pero si E(1) se encuentra activo y podemos escribir o leer desde el LCD.

![Bus-de-datos-lcd](https://user-images.githubusercontent.com/104939556/191602656-e848b801-839d-4a8f-a805-304a5c81b91c.jpg)

#### Programa Ccs compiler



#include <18f4550 .h=»»> //incluimos el pic a utilizar
#fuses hs,nowdt,noprotect,nolvp  //fusibles
#use delay(clock=20000000) //Cristal de cuarzo de 20Mhz
#include <lcd .c=»»> //incluimos la libreria del lcd 

void main() //funcion principal
{
delay_ms(25);
lcd_init(); //iniciamos el lcd 


for(;;) //se queda ciclado el programa
{
delay_ms(100);
lcd_putc(«\f Ingenieria»);
lcd_putc(«\n Mecafenix»);
}
  
  
  
  
  Imagen del circuito en proteus:
![Tutorial-lcd](https://user-images.githubusercontent.com/104939556/191602931-3e8b40fe-5103-4a79-ba6e-d0b07cc36c3c.jpg)
  
  
  Programa ejemplo en el simulador:
  https://wokwi.com/projects/343461815639867987
  
  ### DISPLAY LCD 16X2 CON MÓDULO I2C
  
El I2C es un bus de comunicaciones que usa 2 líneas para enviar y recibir información y 2 más para alimentación. La gran cantidad de pines que tiene el display LCD 16x2 (16  pines) hace  necesario en algunas ocasiones que tenga incorporado (o incorporarle) un módulo para permitir la comunicación por I2C ya que con este necesita sólo 4 pines para funcionar.

El conjunto cuenta algunas ventajas más respecto al display por sí solo, como un pequeño potenciómetro para regular el contraste de la pantalla y la posibilidad de imprimir algunos caracteres especiales.

Para hacer uso del conjunto se hace necesaria la librería “Wire.h”, que nos permite la comunicación por I2C y la librería “LiquidCristal_I2C.h” que controla el display. 
  
  A continuación te facilitamos el enlace para que descargues la librería:
  https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library

 

Los pines a conectar en este conjunto son:

 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-fymr{border-color:inherit;font-weight:bold;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-fymr">Pin</th>
    <th class="tg-fymr">Descipcion</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">vcc</td>
    <td class="tg-c3ow">Alimentación de 5 Voltios</td>
  </tr>
  <tr>
    <td class="tg-c3ow">GND</td>
    <td class="tg-c3ow">Referencia negativa</td>
  </tr>
  <tr>
    <td class="tg-baqh">SCL</td>
    <td class="tg-baqh">Pin de señal de reloj</td>
  </tr>
  <tr>
    <td class="tg-c3ow">SDA</td>
    <td class="tg-c3ow">Pin de datos<br></td>
  </tr>
</tbody>
</table>

 

Esquema de conexión en Arduino UNO:
  
  ![LCD-01_large](https://user-images.githubusercontent.com/104939556/191604267-dda6bb5e-9812-424a-9fbb-7fa3f8760f35.jpg)

  
  Nota:

Depende la versión del display también se conecta así:


SDA = A4




SCL = A5


Código:

 

#include <Wire.h> // Esta Librería es la que permite la comunicacion por I2C

#include <LiquidCrystal_I2C.h> //Esta es la librería controladora del LCD propiamente

 

LiquidCrystal_I2C lcd(0x3F, 16, 2); // (Direccion del display, Número de columnas del LCD, Número de filas del LCD)

 

void setup()

{

  lcd.init(); //Inicializamos el LCD

 

  lcd.backlight(); // Con este comando encendemos la luz de fondo

 

  lcd.setCursor(6, 0); //debemos ubicar el cursor antes de escribir así: (columna donde empieza, fila donde empieza)

 

  lcd.print("Arca"); // Escribimos la primera palabra

 

  lcd.setCursor(3, 1); // Ubicamos el cursor en la fila de abajo

 

  lcd.print("Electronica"); // Escribimos la segunda palabra

 

  delay(5000); // Esperamos 5 segundos

 

  lcd.clear(); // comando para borrar el display

 

  lcd.noBacklight(); // comando para apagar la luz de fondo

}

 

void loop()

{

}

 

 

Lo que nos muestra el display:

  
![5_49703049-49f2-4e17-8212-95e98ee98ed6_large](https://user-images.githubusercontent.com/104939556/191604401-34eec7e3-5d60-4a9b-bb88-94335fb3b7c7.jpg)
  
  
  
### Imagen sin modulo I2C
  
  ![SINMODULO](https://user-images.githubusercontent.com/104939556/191604902-a438f487-8120-47ec-9564-21033556d11f.JPG)

### Imagen con modulo I2C
  

![OIPmoduloi2c](https://user-images.githubusercontent.com/104939556/191604735-f45da150-956a-42f8-8fcb-dc881a2817f4.jpg)
  
  
  
  
  
  
  
  
  
  ## Bibliografia:
  
  Arrieta, V. (2018, 18 diciembre). DISPLAY LCD 16X2 CON MÓDULO I2C. arcaelectronica Recuperado 21 de septiembre de 2022, de https://www.arcaelectronica.com/blogs/tutoriales/display-lcd-16x2-con-modulo-i2c
  
  Mecafenix, I. (2022, 15 junio). ¿Qué es un LCD de 16×2? Ingeniería Mecafenix. Recuperado 21 de septiembre de 2022, de https://www.ingmecafenix.com/electronica/lcd/
  
  Valle, L. (s. f.). Texto en movimiento en un LCD con Arduino. programarfacil.com. Recuperado 21 de septiembre de 2022, de https://programarfacil.com/blog/arduino-blog/texto-en-movimiento-en-un-lcd-con-arduino/
