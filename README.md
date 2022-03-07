# Trabajo Extra - Creación de una Aplicación móvil en App inventor para el calculo con amplificadores operacionales de sumador, restador, multiplicador e integrador 
Creación de una Aplicación móvil en App inventor para el calculo con amplificadores operacionales de sumador, restador, multiplicador e integrador.


### 1. OBJETIVOS


##### 1.1. OBJETIVO GENERAL 

- Dieseñar y construir una calculadora en App inventor que permita calcular apmlificadores operacionales.

##### 1.2. OBJETIVOS ESPECÍFICOS

- Comprender la programacion por medio de bloques y las ventajas que tiene.
- Investigar y analizar los aplificadores operqacionales.
- 


### 2. MARCO TEÓRICO


![Diagrama en blanco (12)](https://user-images.githubusercontent.com/93899658/156412004-0c3daa9b-7a8f-4286-ac99-998bfbbefcea.png)

![Diagrama en blanco (13)](https://user-images.githubusercontent.com/93899658/156416181-29ba60df-3e72-4c70-b040-fa6a183f16ba.png)

### 3. EXPLICACIÓN DEL PROCEDIMIENTO

##### 3.1. Creacion de la cuenta en App Invento y creacion de un nuevo proyecto.

      - Se debe dirigir directamente al siguiente enlace 
   [AppInventor](https://appinventor.mit.edu)    

![image](https://user-images.githubusercontent.com/93899658/157027710-06d4a36c-062a-45f2-b287-86410b4bfb2b.png)

      - Luego, la plataforma automáticamente permitirá crear la aplicación.

![image](https://user-images.githubusercontent.com/93899658/157031157-2cada614-9ccb-4cf4-8da7-af9a5073df51.png)

![image](https://user-images.githubusercontent.com/93899658/157031823-70a9d146-97e1-4bd9-85cd-ab67334c50d8.png)
 
      - Finalmente, se abrira la interface para crear el App

##### 3.2. Creacion de las ventanas para cada ampplificador operacional

![image](https://user-images.githubusercontent.com/93899658/157051689-1ededcbd-61df-4619-aee5-e4d74d649060.png)

      - Es recomendable poner un nombre a cada ventana para mantener un orden y evitar confusiones.


##### 3.3. Creacion del menu principal "Amplificadores Operacionales"

![image](https://user-images.githubusercontent.com/93899658/157053226-27700a42-5bb6-4806-bcb0-6437595e72cb.png)




#### 3.4. Creacion de la calculadora SUMADOR


![image](https://user-images.githubusercontent.com/93899658/157056383-10b6e305-ff15-4c75-9c7c-a612569d9efb.png)

      - Los elementos que componen la interface de CALCULADORA SUMADOR estan anidadas como se muestra en la lista de componentes.
      
 ##### 3.4.1. Algoritmo

      - Para la creacion del algoritmo SUMADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo
      
![image](https://user-images.githubusercontent.com/93899658/157058037-f588ce4a-8e10-4895-8581-7d76b7ce854d.png)

![image](https://user-images.githubusercontent.com/93899658/157061046-416512a8-94d0-4f78-bbde-8a589109f5fe.png)

#### 3.5. Creacion de la calculadora RESTADOR


![image](https://user-images.githubusercontent.com/93899658/157061404-e84930d0-5622-45db-88b4-3975d0f418ce.png)

     - Los elementos que componen la interface de CALCULADORA RESTADOR estan anidadas como se muestra en la lista de componentes.


##### 3.5.1. Algoritmo

     - Para la creacion del algoritmo SUMADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo

![image](https://user-images.githubusercontent.com/93899658/157061921-7bd7ca9b-f176-4c10-8013-0ef2f9d5c138.png)

![image](https://user-images.githubusercontent.com/93899658/157062698-47e18d1b-c020-426a-a381-364d6fe2a932.png)



#### 3.6.  Creacion de la calculadora MULTIPLICADOR

![image](https://user-images.githubusercontent.com/93899658/157063512-d9b6d262-5e2e-46ca-a634-49d125f8f99f.png)

     - Los elementos que componen la interface de CALCULADORA MULTIPLICADOR estan anidadas como se muestra en la lista de componentes.

##### 3.6.1. Algoritmo


     - Para la creacion del algoritmo MULTIPLICADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo
![image](https://user-images.githubusercontent.com/93899658/157064116-51adc2a4-1f00-49ab-80ff-1754c3450f84.png)

![image](https://user-images.githubusercontent.com/93899658/157064772-705537e0-f217-483e-995f-690d79ede8ee.png)


#### 3.7.  Creacion de la calculadora INTEGRADOR

![image](https://user-images.githubusercontent.com/93899658/157066855-100f7a3e-8e46-4074-bad9-71626da9f4f1.png)

     - Los elementos que componen la interface de CALCULADORA INTEGRADOR estan anidadas como se muestra en la lista de componentes.

##### 3.7.1. Algoritmo


     - Para la creacion del algoritmo INTEGRADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo
     
![image](https://user-images.githubusercontent.com/93899658/157067111-ac200936-a471-4eb0-b324-5506c74024cb.png)

![image](https://user-images.githubusercontent.com/93899658/157070631-633e75be-5496-46c9-a308-bc0ec42402b6.png)

     - Se debe tomar en encuenta la caracteristica de una integral y es que es es la sumatoria de rectangulos que tienen una altura f(x) y ancho infinitesimal dx, dando como resultado el area bajo la curva.
     - Los limites de la integral deben ser los adecuados.
 
![image](https://user-images.githubusercontent.com/93899658/157073528-6d40c0e9-16e3-42d4-8129-5bce5a854ad2.png)

- Teniendo encuenta las caracteristicas anteriores se procede a construir el alfgoritmo para calcular la integral de funcion seno.
![image](https://user-images.githubusercontent.com/93899658/157075454-010046da-3b98-427e-8ca9-d4d190265770.png)
- El ancho del diferencial **dx** puede ser el que sea, aunque debemos recordar que mientras más pequeño sea ese valor más exacto es el resultado.
     - Para comprender mejor este algoritmo, a continuación tenemos lo mismo pero en C++
     
      #include <iostream>
      #include <conio.h>
      #include <math.h>

      using namespace std;

      int main()

      {
      float i,a,n,dx,s;
      cout<<"ingresar primer extremo.: ";
      cin>> a;
      cout<<"ingresar 2do extremo.: ";
      cin>>n;
      dx=0.0005;
      s=0;


      for(i=a;i<=n;i=i+dx)
      { 
      s=s+sin(i+dx)*dx;
      }

      cout<<" la integral es: "<<s;
      getch();
      }

### 4. RESULTADOS

#### 4.1. SUMADOR

![image](https://user-images.githubusercontent.com/93899658/157082192-7c973a90-0c2d-489e-a78a-fe2258aee5a2.png)

#### 4.2. RESTADOR

![image](https://user-images.githubusercontent.com/93899658/157082578-d6ec99a4-2ede-4b9c-b692-584c752e2163.png)

#### 4.3. MULTIPLICADOR

![image](https://user-images.githubusercontent.com/93899658/157083008-687bda88-5427-48b0-8192-82bfae96dd36.png)

#### 4.5. INTEGRADOR

![image](https://user-images.githubusercontent.com/93899658/157085725-10c4088c-0eb4-4ae8-a06c-5fb9f6f3150a.png)


##### 3.2.5. Se conectan el diac y el triac.

      - El segundo terminal del triac se conecta a la linea del resistor de 1 kΩ
      - La compuerta G se conecta con el diac 
      - El primer terminal se conecta en la linea de los capacitores cerámicos.
      



##### 3.2.6. Para mayor facilidad se conecta en la linea de la resistencia positiva y en la linea negativa de los capacitores dos cables para realizar una extension.



##### 3.2.7. Conexión completa del circuito en el protoboard.



##### 3.2.8. Para la boquilla del foco.

      - Se conecta al puerto del neutro de la boquilla el cable que viene directo de la fuente.
      - Al puerto de fase de la boquilla se conecta un cable el cual será conectado a la línea positiva del protoboard.



##### 3.2.9. Se encaja el foco. 


##### 3.2.10. Conectamos los terminales en la protoboard.

      - El terminal que sale del foco se conecta a la línea del positivo del protoboard.
      - El terminal que viene directo de la fuente de C.A. se conecta a la línea del negativo del protoboard.


##### 3.2.11. Se conecta a la fuente de corriente alterna de 110 V a 60 Hz.

      - Se comienza a regular el potenciómetro hasta alcanzar el voltaje suficiente para que logre encender el foco.
      - Al regular se puede modificar la intensidad lumínica del foco.



### 4. RESPUESTAS A INTERROGANTES




### 5. VIDEO


### 6. CONCLUSIONES 




### 6. BIBLIOGRAFIAS 


