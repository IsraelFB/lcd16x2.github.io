# Exposicion sobre los LCD
##  Cuando los simples indicadores luminosos con led ya no son suficientes, habitualmente el siguiente paso para todo programador es ir por una pantalla lcd 16×2. 



![cooltext419183073128565](https://user-images.githubusercontent.com/104939556/190014568-aaa22c6f-a842-41cc-8436-07488de3267c.png)
### LCD 16×2
El LCD(Liquid Crystal Dysplay) o pantalla de cristal líquido es un dispositivo empleado para la visualización de contenidos o información de una forma gráfica, mediante caracteres, símbolos o pequeños dibujos dependiendo del modelo.
El LCD consta de 16 terminales las cuales podemos dividir en pines de alimentación, control y bus de datos bidireccional. Por lo general podemos encontrar ademas en su estructura los pines de Anodo de led backlight y cátodo de led backlight.

#### Pines de alimentación

°Vss: Gnd
°Vdd: +5 voltios
°Vee: corresponde al pin de contraste, lo regularemos con un potenciómetro de 10K conectado a Vdd.

#### Pines de control

°RS: Corresponde al pin de selección de registro de control de datos (0) o registro de datos(1). Es decir el pin RS funciona paralelamente a los pines del bus de datos. Cuando RS es 0 el dato presente en el bus pertenece a un registro de    control/instrucción. y cuando RS es 1 el dato presente en el bus de datos pertenece a un registro de datos o un carácter.

°RW: Corresponde al pin de Escritura(0) o de Lectura(1). Nos permite escribir un dato en la pantalla o leer un dato desde la pantalla.
E: Corresponde al pin Enable o de habilitación. Si E(0) esto quiere decir que el LCD no está activado para recibir datos, pero si E(1) se encuentra activo y podemos escribir o leer desde el LCD.
