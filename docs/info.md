<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

El proyecto almacena bits en una memoria de 8bits con flip-flops tipo D con un reloj. Con una determinada contraseña (numero 69) se logra mandar la señal por el output. Se muestra el encendido de un Led cuando se almacena el numero correcto

## How to test

En la simulación del proyecto se puede ingresar bits (0 o 1 con un switch conectado a vcc o al Gnd), apretando el botón de Step se puede avanzar el reloj y guardar ese bit en el primer FF y mover la cadena de bits a lo largo de los otros FF encadenados.

## External hardware

Un led que se prende cuando se guarda el numero 69
