En la practica 4 titulada "Modulaciones Angulares", se analizaron señales de modulación angular de banda ancha (PM) para diferentes valores del parámetro Kp*Am.Se realizaron mediciones tanto en el dominio del tiempo como en el espectro utilizando un osciloscopio y un analizador de espectro. Se evaluó el comportamiento de la señal para valores bajos de Kp*Am, observando su forma de onda y estimando la potencia de la envolvente compleja, así como el ancho de banda de la señal modulada.

Posteriormente, se aumentó la frecuencia de muestreo a 6.25 MHz para analizar el comportamiento de la señal con valores más altos de Kp*Am.Este cambio mostró un incremento en los armónicos de la señal. Finalmente, se compararon los coeficientes de Bessel teóricos con los resultados experimentales, utilizando herramientas como Wolfram y Matlab para estimar la potencia total de la señal modulada.

PARTE A:
![imagen](https://github.com/user-attachments/assets/4b992461-9289-4f3f-b391-8afd8a175057)
La imagen anterior es el espectro captado en GNU radio, donde se pueden evidenciar los componentes espectrales de la señal, como lo es la señal piloto, la componenten mono, estereo. Ademas aunque aparentan estar otros componentes se debe a la demodulacion que hace el radio empleado.
![imagen](https://github.com/user-attachments/assets/638942bf-d700-40b2-abbf-85498f494414)
Se intenta medir el ancho de banda de la señal considerando la regla de los 20dB, aunque no se logra tener una gran aproximacion por la dificultad de la medida en el computador. Se mira tambien el maximo espectro de la señal para asi ver el comportamiento y saber la medida del ancho de banda.
![imagen](https://github.com/user-attachments/assets/9e592c68-6406-4afe-9a41-73b80ec42dfe)

https://github.com/JairoM02/GNURADIO_LABCOMUIS_2024_2_E1B_G6/blob/da033abb19f7fd9a711734eaaa1c358df2e65db4/PUNTO%201/Demodulacion%20de%20Emisoras%20FM.pdf

Con el analizador de espectros se busca tener una mejor medida del BW, al poder ser mas exactos y tener cursores que nos ayudan. A continuacion se presenta el link al pdf el cual tiene un analisis y las imagenes especificadas.
https://github.com/JairoM02/GNURADIO_LABCOMUIS_2024_2_E1B_G6/blob/da033abb19f7fd9a711734eaaa1c358df2e65db4/PUNTO%202/Punto%202.pdf

PARTE B:

Se mira el comportamiento de la señal con una pequeña modulacion PM menores a 0.1, la cual hace que se comporte teoricamente como una modulacion AM.
![imagen](https://github.com/user-attachments/assets/0daed52d-282f-49bc-971b-74965f7da613)

Con modulaciones mayores se pude ver como varia su comportamiento y fase, algo que por su naturaleza es muy dificil de medir pero se puede observar.
![imagen](https://github.com/user-attachments/assets/b28c5176-016e-4c1f-b999-4154695fb43a)

![imagen](https://github.com/user-attachments/assets/5670bcd8-8655-4169-8fe0-bc4b36569a66)

Se busca medir en el analizador de espectros la potencia de los armonicos segun el coeficiente de bessel, como se muestra en la tabla del PDF.
A continuacion se presenta el link al pdf el cual tiene un analisis y las imagenes especificadas.
(https://github.com/JairoM02/GNURADIO_LABCOMUIS_2024_2_E1B_G6/blob/e28ae8f7baa07010ff1387ab23884783d7b26a8d/PUNTO%202/TablaLaboratorioPM_20232%201.pdf)
