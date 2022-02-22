# Informe Laboratorio 8
1. OBJETIVOS 

   Objetivo general
   
   Comprobar experimentalmente el funcionamiento y comportamiento de la onda senoidal y los valores que abarca tanto en grafica como en numero 
   mediantes los quipos de mediciones y colocacion correcta de cada componente.

   Objetivos específicos
   
   * Desarrollar el circuito esquematico en los simuladores correspondientes para su verificacion de datos.
   * Comprender las diferentes caracteristicas de un osciloscopio y multimetro.
   
2. MARCO TEORICO

   ![](https://github.com/jlcastro5/Laboratorio-8/blob/1d680b6deaaf4716b069324218879a749a144a2f/labo8.jpeg)
  
3. EXPLICACION DEL PROCEDIMIENTO

   Ajuste el generador de funciones, para que proporcione una señal de **20 Vpp** a una frecuencia de **2.5 Khz.**
   
   ![](https://github.com/jlcastro5/Laboratorio-8/blob/2a7f2e6fff715b3b452438a1d283f60adaf17b71/Elementos.PNG)
   
   **Circuito Esquematico**
   
   ![](https://github.com/jlcastro5/Laboratorio-8/blob/2a7f2e6fff715b3b452438a1d283f60adaf17b71/Circuito%20Esquematico.PNG)
   
   Colocacion del osciloscopio y observacion de datos.
   
   ![](https://github.com/jlcastro5/Laboratorio-8/blob/2a7f2e6fff715b3b452438a1d283f60adaf17b71/Osciloscopio.PNG)
   
   Comparacion de datos en el simulador de proteus en este caso utilizamos dicho simulador para comprobar los valores obtenidos en el DECAClab
   
   ![](https://github.com/jlcastro5/Laboratorio-8/blob/2a7f2e6fff715b3b452438a1d283f60adaf17b71/Proteus.PNG)
   
   Colocacion del multimetro para verificacion del voltaje mediante numeros digitales
   
   ![](https://github.com/jlcastro5/Laboratorio-8/blob/2a7f2e6fff715b3b452438a1d283f60adaf17b71/Multimetro.PNG)
   
   En nuestor simulador de proteus la colocacion del voltimetro AC para comprobar el valor obtenido en DECAClab con proteus.
   
   ![](https://github.com/jlcastro5/Laboratorio-8/blob/2a7f2e6fff715b3b452438a1d283f60adaf17b71/ProteusMultimetro.PNG)
  
 
4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

  * ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida? 
  
  Valor pico se observa un cuadro y un tercio 

  * ¿En qué valor está posicionada la perilla VOLTS/DIV? 
  
  Se encuentra en la posicion de 10 VOLTS/DIV 
  
  * ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida? 
  
  En el osciloscopio se muestra que abarca un ciclo completo de 4 cuadros.

  * ¿En qué valor está posicionada la perilla TIME/DIV?
  
  Su posicion se encuentra en 0.1m
  
  8.5.5¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla 
  del osciloscopio?
  
  Amplitud de voltaje: 13.5(V)
  
  el ciclo cumple de 4 por lo tanto en TIME/DIV nos da el valor de 0.1ms por lo tanto nuestro periodo es
  
  Periodo: 0.4m(s)

  8.5.6 Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de 
  salida.
  
  aplicamos la formula f=1/T es cual nos arroja el valor de f.
  
  f: 2.5k (Hz) 
  
  ω: 5000π(rad/s) 
  ![](https://github.com/jlcastro5/Laboratorio-8/blob/1d680b6deaaf4716b069324218879a749a144a2f/angular.PNG)
  
  85.7 Con el multímetro digital mida el voltaje de salida en RL: **9.704 V**
  
  8.5.8 Compare el voltaje medido en el punto 8.5.5. y el obtenido en el punto 8.5.7. 
  ¿Coinciden?¿Por qué? 
  
  * Primeramente no coiciden con los voltajes medidos en el osciloscopio con el multimetro
  Por que el osciloscopio tienen la capacidad de mostrar visualmente señales complejas en 
  cambio el multimetro nos da para realizar mediciones precisas de señales discretas lo cual
  exite una diferencia de imagen contra numeros.
  

5. VIDEO

   https://www.youtube.com/watch?v=CeuNGdUiwU4

6. CONCLUSIONES

     * Mediante la práctica se observo el comportamiento de la onda senoidal y sus características las se pueden obtener mediante cálculos
      y analizar los valor de cada una se observar la diferencia de voltaje rms y voltaje pico al momento de realizar la práctica y comparar 
      las mediciones con el osciloscopio y el multímetro digital.

     * El Simulador DCACLAB resulta muy eficiaz para realizar mediciones con Osciloscopio por su exactitud y presición en las mediciones dadas.

7. BIBLIOGRAFÍA 

   Latam, M. (2020, 6 julio). Leyes de Kirchhoff. Mecatrónica LATAM. https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/
 
   Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
