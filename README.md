# Trabajo Extra - Creación de una Aplicación móvil en App inventor para el calculo con amplificadores operacionales de sumador, restador, multiplicador e integrador 
Creación de una Aplicación móvil en App inventor para el calculo con amplificadores operacionales de sumador, restador, multiplicador e integrador.


### 1. OBJETIVOS


##### 1.1. OBJETIVO GENERAL 

- Investigar y comprender el funcionamiento de un circuito Dimmer mediante la construcción del mismo.   

##### 1.2. OBJETIVOS ESPECÍFICOS

- Ampliar la visión del estudiante con la elaboración de un circuito en forma física aplicando conocimientos teóricos y enfrentarlo a los posibles inconvenientes que surgen al momento de construir cualquier circuito.
- Profundizar en los usos y aplicaciones de cada elemento utilizado en el circuito Dimmer.  


### 2. MARCO TEÓRICO

![Diagrama en blanco (8)](https://user-images.githubusercontent.com/93899658/151405640-8e57000a-c158-4143-b8bb-8c8b5e6ea4eb.png)

### 3. EXPLICACIÓN DEL PROCEDIMIENTO

##### 3.1. Materiales y equipo requerido

|Cantidad|Elemento|
|----|----|
|1|Resistor 1kΩ|
|1|Resistor 10kΩ|
|1|Diac DB3|
|1|Triac BTA12|
|1|Capacitor cerámico 47 nF|
|1|Capacitor cerámico 100 nF|
|1|Potenciometro de 500kΩ|
|1|Protoboard|
|1|Boquilla foco|
|1|Foco de 110V y 9W|
|1|Clavija|
|1|Fuente de V.A. 110V y 60 Hz|

##### 3.2. Procedimiento

##### 3.2.1. Armar el circuito mostrado en la figura 1
![image](https://user-images.githubusercontent.com/93899658/151352207-e222e557-b470-4bef-ae52-4c6ee086a0bd.png)
`Figura 1: diagrama del circuito Dimmer` 

##### 3.2.2. Se ubicama el potenciometro en el protoboard identificando cada terminal
![image](https://user-images.githubusercontent.com/93899658/151381454-b4fafdd1-a158-49a2-b47b-61b40858d8d9.png)

##### 3.2.3. En la terminal dos del potenciometro se conecta el Resistor de 1kΩ

![image](https://user-images.githubusercontent.com/93899658/151382443-294d88fd-c22e-4ac8-bc92-5d5bc708730b.png)

##### 3.2.4. Se conecta el capacitor cerámico de 47 nF y de 100 nF en paralelo con el terminal tres del potenciometro y el Resistor 10kΩ.

![image](https://user-images.githubusercontent.com/93899658/151383217-6d95642c-4119-4bd7-8d1b-f1a45698b52e.png)

##### 3.2.5. Se conectan el diac y el triac.

      - El segundo terminal del triac se conecta a la linea del resistor de 1 kΩ
      - La compuerta G se conecta con el diac 
      - El primer terminal se conecta en la linea de los capacitores cerámicos.
      

![image](https://user-images.githubusercontent.com/93899658/151384687-fff255ed-1bd0-4ea2-af22-0bb297588409.png)

##### 3.2.6. Para mayor facilidad se conecta en la linea de la resistencia positiva y en la linea negativa de los capacitores dos cables para realizar una extension.

![image](https://user-images.githubusercontent.com/93899658/151397038-cf97ff7d-a945-42d4-945a-0a70d557de42.png)

##### 3.2.7. Conexión completa del circuito en el protoboard.

![image](https://user-images.githubusercontent.com/93899658/151397669-bf7c8cd2-4af4-4f0c-b91b-d36e3b86e683.png)

##### 3.2.8. Para la boquilla del foco.

      - Se conecta al puerto del neutro de la boquilla el cable que viene directo de la fuente.
      - Al puerto de fase de la boquilla se conecta un cable el cual será conectado a la línea positiva del protoboard.

![image](https://user-images.githubusercontent.com/93899658/151400732-c0ba8477-785a-4ffd-b657-2a0c33181b04.png)


##### 3.2.9. Se encaja el foco. 

![image](https://user-images.githubusercontent.com/93899658/151401859-048d0af7-b134-4b0a-b71d-b5e083ceb572.png)

##### 3.2.10. Conectamos los terminales en la protoboard.

      - El terminal que sale del foco se conecta a la línea del positivo del protoboard.
      - El terminal que viene directo de la fuente de C.A. se conecta a la línea del negativo del protoboard.

![image](https://user-images.githubusercontent.com/93899658/151402823-599f23b5-1e62-450f-922a-fbee4816757f.png)

##### 3.2.11. Se conecta a la fuente de corriente alterna de 110 V a 60 Hz.

      - Se comienza a regular el potenciómetro hasta alcanzar el voltaje suficiente para que logre encender el foco.
      - Al regular se puede modificar la intensidad lumínica del foco.


![image](https://user-images.githubusercontent.com/93899658/151414839-bc2af994-ee6e-4657-b1f7-5fa2933a21ee.png)

### 4. RESPUESTAS A INTERROGANTES

### 4.1 ¿En que se puede emplear un circuito dimmer?

- Generalmente este tipo de circuitos nos permite tener un lugar con una iluminación variada.
- También es aplicable para la regulación de la velocidad de un motor y con ellos utilizarlos en diferentes actividades.


### 4.2 ¿Que funcion cumple el capacitor en el circuito Dimmer?

- El capacitor afecta un poco la dimerización, pues almacena cierta carga y le da una tolerancia mayor al circuito con respecto a voltajes erróneos.


### 5. VIDEO

https://youtu.be/Anat-oSRWMA

### 6. CONCLUSIONES 

- Pasar un circuito de lo virtual a la realidad conlleva un esfuerzo adicional ya que se deben tomar en cuenta ciertos cuidados para que el proyecto tenga el exito esperado, para ello es necesario medir la continuidad entre cada uno de los elementos y utlizar el equipo adecuado puesto que de no hacerlo pueden causar daños al momento de energizar el circuito. 
- En el estudio de los diodos empleados en el circuito Dimmer cada uno cumple una función especifica al momento de aplicarles voltaje alterno puesto que deforman la onda sinusoidal producida de tal manera que mediante el potenciómetro nos permite regular la intensidad de la luz del foco, aunque lo que realmente sucede es que el triac deja pasar cierta cantidad de voltaje en lapsos de milisegundos lo que hace que el foco se prenda y se apague de forma rápida lo que es difícil de percibir, pero si es evidente cuando disminuye la intensidad lumínica.   


### 6. BIBLIOGRAFIAS 

- areatecnologia.com. (s.f.). AREATECNOLOGIA. Obtenido de TRIAC: https://www.areatecnologia.com/electronica/triac.html

- Curiosoando.com. (Febrero de 4 de 2020). Curiosoando. Obtenido de ¿Qué es un potenciómetro?: https://curiosoando.com/que-es-un-potenciometro

- ELECTRONICA BASICA. (s.f.). ELECTRONICA BASICA. Obtenido de Circuito Dimmer o Regulador de tensión con triac: https://electronicabasica.site/circuito-dimmer-o-regulador-de-tension-con-salida-a-triac/

- Floyd, T. L. (2007). PRINCIPIOS DE CIRCUITOS ELECTRICOS. México : PEARSON EDUCACIÓN.

- Unisalia.com. (s.f.). Obtenido de ¿Qué Es Un DIAC? Funcionamiento De Los Circuitos De Aplicación: https://unisalia.com/que-es-un-diac/
