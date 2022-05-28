# INFORME LABORATORIO

## OBJETIVOS

### OBJETIVO GENERAL

Analizar el funcionamiento y aplicación de las leyes de Kirchhoff, por medio de la elaboración de un circuito eléctrico utilizando herramientas digitales, para demostrar como se aplican los postulados de Kirchhoff por medio de cálculos previos y mediciones aplicadas.

### OBJETIVOS ESPECIFICOS

-	Elaborar un circuito eléctrico mixto en TINKERCAD.
-	Comprobar que el circuito cumpla con las leyes de voltaje y corriente de Kirchhoff de manera teórica y práctica.

## MARCO TEÓRICO

### LEYES DE KIRCHHOFF

Gustav Kirchhoff

Nació en 1842, Königsberg, Prusia. Fue un físico alemán el cuál aplicó métodos de análisis espectro gráfico para determinar la composición del sol. Aún así su mayor descubrimiento fue las leyes de Kirchhoff, útiles para el cálculo de tensiones, intensidades y resistencias en una malla eléctrica.
Las leyes de Kirchhoff son dos leyes que, junto a la ley de ohm, indican un conjunto de ecuaciones que permiten la resolución de un circuito eléctrico complejo, basándose en el principio de conservación de la carga eléctrica y conservación de la energía.

Las leyes de Kirchhoff se dividen en dos, siendo la primera conocida como la ley de las corrientes o regla de los nodos y la segunda ley conocida como ley de los voltajes o ley de las mallas.

A continuación, se hablará cada una de ellas:

#### 1. Primera Ley de corrientes de Kirchhoff (LCK)

La primera ley de Kirchhoff trata el comportamiento de las corrientes presentes en un nodo del circuito eléctrico.
Esta ley dicta “En cualquier nodo, la suma de las corrientes que entran en ese nodo es igual a la suma de las corrientes que salen. De forma equivalente, la suma algebraica de todas las corrientes que pasan por el nodo es igual a cero.”
Por tanto, en forma matemática la primera ley se expresa como:

![image](https://user-images.githubusercontent.com/105565683/170562008-90106ff8-b94f-4f0b-81bb-bfc0a51fb64e.png)

#### 2. Segunda ley de corrientes de Kirchoff (LVK)

La segunda ley de Kirchoff trata el comportamiento del voltaje en un lazo cerrado (trayectoria cerrada alrededor de un circuito) o malla (lazo que no contiene otros lazos en su interior), con esta ley se puede determinar las caídas de voltaje de cada elemento correspondiente a la malla a analizar.

Esta ley dicta “En un lazo cerrado, la suma de todas las caídas de tensión es igual a la tensión total administrada. De forma equivalente, la suma algebraica de las diferencias de potencial eléctrico en un lazo es igual a cero.”

Por tanto, en forma matemática, la segunda ley se expresa como:

![image](https://user-images.githubusercontent.com/105565683/170562269-43db2589-6b2f-4fff-8a6e-376a5c50984f.png)

## EXPLICACIÓN DEL PROCEDIMIENTO

### ELABORACIÓN DEL CIRCUITO

#### MATERIALES

![image](https://user-images.githubusercontent.com/105565683/170573455-396becb9-ac8a-4332-a667-97279cda64c0.png)

![image](https://user-images.githubusercontent.com/105565683/170573893-f8a09d37-542f-4f40-895a-874e9155bdde.png)

#### PROCESO

1)	Ubicamos las resistencias como se muestra en el esquema del circuito.

![image](https://user-images.githubusercontent.com/105565683/170574224-c2d3e048-fc8e-4bad-8fd8-58ea73923f35.png)

2)	Conectar las resistencias por medio de los cables de acuerdo con el esquema, que cumpla con el circuito mixto.

![image](https://user-images.githubusercontent.com/105565683/170574704-9c6e507c-7d7b-428a-908a-2308ac19e6ce.png)

3)	Conectamos la fuente de voltaje C.D. (en caso de simulador), de acuerdo al esquema, en los polos positivo y negativo de las resistencias.

![image](https://user-images.githubusercontent.com/105565683/170575296-5d6443f1-a0bf-452b-9aee-1c2c56123b97.png)

### CALCULO DE LOS VOLTAJES Y CORRIENTES

![image](https://user-images.githubusercontent.com/105565683/170568728-db5ac8de-ce04-4c03-8d8b-0ab5a3195fc3.png)

Basándonos en el esquema de circuitos, podemos ver que las resistencias R1 de 1 kΩ y R5 de 1.8 KΩ están conectadas directamente al suministrador de energía de 5 V, que genera una corriente de 1.03 mA. 

Calculamos el voltaje para R1 y R5 basándonos en la ley de ohm.

![image](https://user-images.githubusercontent.com/105565683/170568960-1e502aea-9675-41d8-bfce-49cabded17ef.png)

Teniendo en cuenta que es un circuito mixto, R2 tiene una corriente distinta a R1 y R5. La calculamos de forma independiente, con ley de ohm.

![image](https://user-images.githubusercontent.com/105565683/170569082-6ed2c569-5925-478a-8c3f-7ca30b1be591.png)

Como R2, R3 y R4 conforman la segunda parte del circuito en forma paralela, siendo un circuito en serie R3 y R4 por los nodos, en este caso R2 es aquel que proporciona energía para R3 y R4.

![image](https://user-images.githubusercontent.com/105565683/170569445-4197477b-2655-4aeb-ba18-2830f2b63eac.png)

### CALCULOS DE LA LEY DE VOLTAJE DE KIRCHHOFF

Teniendo en cuenta el esquema del circuito, podemos trazar tres trayectorias:

![image](https://user-images.githubusercontent.com/105565683/170569663-933b638b-68d1-4089-a0db-cf668df99634.png)

![image](https://user-images.githubusercontent.com/105565683/170569876-68d0e2e6-c4a1-4ca9-bce7-031e71731bc6.png)

![image](https://user-images.githubusercontent.com/105565683/170569996-3934bb32-8f5f-476f-9a37-0fd2fc6cad28.png)

![image](https://user-images.githubusercontent.com/105565683/170570121-6909738a-7c25-4746-a1f3-f3ae2c781429.png)

![image](https://user-images.githubusercontent.com/105565683/170570237-fc991b9d-80a1-436c-811e-0de7438a4b0e.png)

### CALCULOS DE LA LEY DE CORRIENTE DE KIRCHHOFF

Teniendo en cuenta el esquema del circuito ubicamos 5 nodos

![image](https://user-images.githubusercontent.com/105565683/170570390-a7614fcd-7868-4a7f-a481-758dade672af.png)

![image](https://user-images.githubusercontent.com/105565683/170570755-d57833f3-ac90-4be2-8297-a77dd1c8ca7d.png)

![image](https://user-images.githubusercontent.com/105565683/170570903-7d5a2406-32a3-47d8-b6a6-b7923c92fd57.png)

![image](https://user-images.githubusercontent.com/105565683/170570971-7acbf8fd-2210-4f7c-8cb6-1cdd4167c3f4.png)

![image](https://user-images.githubusercontent.com/105565683/170571033-0484cb25-d6d3-431e-b375-9f19c474bfba.png)

![image](https://user-images.githubusercontent.com/105565683/170571107-cfc4220f-b827-4381-8023-218955808a3b.png)

![image](https://user-images.githubusercontent.com/105565683/170571182-24b26372-26a6-464b-871c-75ef52b9c03a.png)

## RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

### MEDICIONES DE VOLTAJE Y CORRIENTE

1. Medir el voltaje en cada elemento del circuito con el multímetro.

![image](https://user-images.githubusercontent.com/105565683/170576301-8fb5f6cf-294e-484a-8e82-ea653017ef3b.png)

2. Medir la corriente en cada elemento del circuito con el multímetro. 

![image](https://user-images.githubusercontent.com/105565683/170576423-b057b9a9-6c82-4016-8205-96e0462a50a2.png)

3. Comparar los resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

![image](https://user-images.githubusercontent.com/105565683/170576640-64b676bb-5cde-4369-8f48-6afb2de4a6e2.png)

4. Verificar si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada, considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con signo negativo.

![image](https://user-images.githubusercontent.com/105565683/170576972-15fad499-446f-40f9-9855-86aa8d4ddce8.png)

5. Verificar si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando con signo positivo las corrientes que entran al nodo y con signo negativo las que salen del nodo.

![image](https://user-images.githubusercontent.com/105565683/170579694-7a77af8a-7126-4d5f-b97f-5156fde2edf6.png)

### RESULTADOS

Los valores calculados y obtenidos, cumplen con la ley de voltaje de kirchoff de que La suma de las caídas de voltaje en una trayectoria cerrada es igual a la suma de las elevaciones de voltaje en la misma, de igual manera los valores cumplen con la ley de corriente de kircchhoff en que La suma de las corrientes que entran a un nodo es igual a la suma de las corrientes que salen del mismo. 

Respecto al margen de error, se reduce a milésimas, puesto que el simulador TINKERCAD, tiende a redondear los resultados a dos decimales, pero en un espectro general, los valores tanto calculados como medidos, son los mismos.

## VIDEO

https://www.youtube.com/watch?v=eCNUlQ0LSIQ

## CONCLUSIONES

- En el circuito eléctrico se utilizó un análisis y comprensión adecuado del esquema del circuito, por medio de materiales adecuados, para que el circuito cumpliera con todo lo solicitado.
- Se determino que el circuito eléctrico cumple con todas las leyes de Kirchhoff, tanto en los cálculos previos, como en los resultados obtenidos de las mediciones.

## BIBLIOGRAFÍA

- Acosta, I. (19 de Marzo de 2016). geekelectrónica. Obtenido de https://geekelectronica.com/leyes-de-kirchhoff/
- Tomás, F., & Tamaro, E. (2004). Biografías y Vidas. Obtenido de https://www.biografiasyvidas.com/biografia/k/kirchhoff.htm
- Zapata, F. (2021). lifeder. Obtenido de https://www.lifeder.com/leyes-kirchhoff/

