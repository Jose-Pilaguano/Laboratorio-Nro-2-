# Laboratorio-Nro-2-

INTEGRANTES DEL GRUPO 

Jose Pilaguano

Sahid Carrion

Henry Macías

Objetivos:

1.- Objetivo General

Estudiar el comportamiento de la corriente en las distintas mallas ayudandose de los simuladores para comprobar con los resultados analíticos.

1.1.- Objetivos específicos

Identificar los nodos que contiene cada circuito para realizar el cálculo de las mallas.

Analizar y distinguir las mallas en el circuito para poder resolverlo .

Comparar los datos en el simulador como en los resultados calculados y realizar el cálculo del error.

2.- Marco Teórico

![image](https://user-images.githubusercontent.com/116677175/202754881-18b5b297-a2aa-4268-b746-069dddf965a3.png)

3.- Diagramas

Corriente que circula por malla 1.

![image](https://user-images.githubusercontent.com/116677175/202754978-336d5876-ad39-46e0-9c8b-ee54cbf1df22.png)

Corriente que circula por malla 2.

![image](https://user-images.githubusercontent.com/116677175/202755061-bd888a4e-a25d-4b39-a958-5906bf991ce0.png)

Corriente que circula por malla 3.

![image](https://user-images.githubusercontent.com/116677175/202755159-62ef8e2f-8729-4a11-9ef3-fd3bbeb5d0e6.png)

Circuito con todos los elementos de medida.

![image](https://user-images.githubusercontent.com/116677175/202755278-a0e5eb0e-cd98-411e-a56d-e7f20f1daef1.png)

4. Lista de componentes

![image](https://user-images.githubusercontent.com/116677175/202755498-cf956783-0e66-4556-a7ce-285567be5770.png)

5.- Explicación

5.1.- Procedimiento

Se ingresa a la plataforma Tinkercad, se crea una cuenta, a continuación en el apartado de circuitos seleccionar nuevo circuito.

Se seleccionan los materiales que vamos a utilizar, una placa de pruebas, 5 resistencias, multimetros digitales y dos fuente de voltaje.

En la primera fuente de voltaje, se la configura con 18 V, mientras que la segunda fuente de voltaje tendrá un valor de 5V.

Se procede a configurar cada resistencia con el valor ya establecido en el circuito.

La fuente de voltaje positivo ira hacia un extremo de la resistecia de 820 ohms.

Del otro extremo de la resistencia de 820 ohms se conectará a un extremo de la resistencia de 1kohms.

Del extremo de la resistencia de 1kohms se conectara hacia el lado negativo de nuestra fuente de 18V.

Del nodo que se forma entre la resistencia de 820 ohms y la resistencia de 1kohms se conectará una resistencia de 1.2kohms.

Del otro extremo de la resistencia de 1.2kohms se conectará una resistencia de 2.2kohms.

El otro extremo de la resistencia de 2.2kohms se conectará a la resistencia de 1kohm.

Del nodo que se forma entre la resistencia de 1.2kohm y la resistencia de 2.2kohm se conectará la resistencia de 390ohm.

Desde el extremo de la resistencia de 390 kohm se conectara al lado positivo de nuestra fuente de voltaje de 5V.

Desde el lado negativo de la fuente de voltaje se conectará a la resistencia de 2.2kohm.

5.2.- Mida cada una de las corrientes de la malla y anote los resultados en la tabla

![image](https://user-images.githubusercontent.com/116677175/202755657-087a8db5-c976-4769-9140-4a538a73a394.png)

La tabla cuenta de tres columnas, en la primera columna tenemos el número de nodos con los que el circuito cuenta, depues de analizar el circuito se llega a la conclusión que tiene tres nodos. En la segunda columna, tenemos los resultados analíticos, estos resultados son obtenidos mediante el cálculo de fórmulas. Finalmente, en la tercera columna, obtenemos los resultados experimentales, estos fueron obtenidos con la ayuda del simulador Tinkercad y la conexión de los elementos de medida. 

![image](https://user-images.githubusercontent.com/116677175/202755792-1d11b8a4-6c6d-41d9-b663-9239f26b22ed.png)

5.3.- Compare los valores de la tabla y realice sus conclusiones.

En conclusión, como se puede observar en la tabla, los valores varian por unos decimales. Esto es debido a que en el programa Tinkercad redondea hasta dos decimales, de esa manera perdiendo muchas cifras significativas. Mientras tanto, cuando realizamos los resultados analíticos, utilizamos como máximo 3 decimales, por lo que omitimos muchos de ellos, entonces al seguir realizando los cálculos nos puede marcar un pequeño error porcentual. Al ser valores muy próximos y al solo variar por decimales, el error porcentual es muy bajo y en algunos casos nulo, debido a que encanja perfectamente en ambos casos de resultados analíticos y resultados experimentales.

Error porcentual malla 1.

![image](https://user-images.githubusercontent.com/116677175/202755886-52deddcb-6e8e-4f81-8653-36a727ff2dff.png)

Error porcentual malla 2.

![image](https://user-images.githubusercontent.com/116677175/202755948-2c09f36b-f7fb-4bd7-968a-94db714e3aa4.png)

Error porcentual malla 3.

![image](https://user-images.githubusercontent.com/116677175/202756001-eff3a481-57f8-4ec0-9d2d-0f21ae8a3d3e.png)

7. Vídeo : https://www.youtube.com/watch?v=hlGrobf1XZk 

8.- Conclusiones

En conclusión, cuando 2 o más elementos (como resistencias, leds, etc.) dentro de un circuito, ya sea serie, paralelo o mixto, están unidos son denominados nodos Y estos permitirán realizar los cálculos de una manera más ordenada.

Al analizar los datos que refleja el simulador, el cálculo de error no va más allá de decimales, lo cual significa que el desarrollo del método de circuitos en malla fue correctamente realizado.

Concluimos que, al utilizar el método de circuitos de malla, estas se pueden subdividir dependiendo de los nodos y los elementos que conforman el circuito.

9.- Bibliografía

Floyd, T.L (2007). Principios de Circuitos Electrónicos. México: Pearson educación.

