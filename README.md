# InformeLaboratorio3
**1. TEMA:**

Análisis de Nodos

**2. OBJETIVO**

**2.1. Objetivo General**

Comprobar experimentalmente el Análisis de Nodos.

**2.2. Objetivos Específicos**

- Definir lo que es malla, rama y nodo.
- Entender cómo se utiliza el análisis de malla y cómo se lo aplica en un circuito.
- Apender a identificar las mallas de un circuito.
- Realizar el circuito propuesto de manera correcta y funcional.
- Tomar las medidas de las corrientes en cada malla en Tinkercad, Multisim y de forma manual para aplicar el método de mallas.
- Analizar los resultados obtenidos de cada programa y compararlos para definir si el análisi de mallas es funcional o no.


**3. MARCO TEÓRICO**

**3.1. Rama, Mallas y Nodos**

[![Ramas-Mallas-y-Nodos.png](https://i.postimg.cc/d0x7Dqyy/Ramas-Mallas-y-Nodos.png)](https://postimg.cc/jWyqFYvx)

**3.2. Ley de Kirchhoff en nodos**

Las leyes de Kirchhoff, junto con la Ley de Ohm, son las principales herramientas con las cuales se cuenta para analizar el valor de los parámetros eléctricos de un circuito. Mediante el análisis de nodos (primera ley) es factible hallar los valores de las corrientes y las caídas de tensión que se presenten en cualquier punto del montaje.

[![M-todo-de-An-lisis-de-Nodos.png](https://i.postimg.cc/BvQ9pjBN/M-todo-de-An-lisis-de-Nodos.png)](https://postimg.cc/jD9Fdd9J)

**3.3. Análisis de Nodo**

[![An-lisis-de-Nodos.png](https://i.postimg.cc/yx5cQ3RR/An-lisis-de-Nodos.png)](https://postimg.cc/8fR7s5tk)

**4. EXPLICACIÓN DEL PROCEDIMIENTO**

**4.1.** Se realizará el siguiente circuito mixto en Tinkercad. Se utilizarán las siguientes herramientas:

- Una Placa de pruebas pequeña.
- Cinco Resistencias.
- Dos Suminitradores de Energía.
- Un multímetro.

 [![78.png](https://i.postimg.cc/PrS5jnV6/78.png)](https://postimg.cc/zVRrC6rW)
 
**4.2.** Conectaremos los dos suministradores de energía en la placa pequeña de tal forma que los dos negativos (tierra) se unan, esto debido a que seguiemos el mismo modelo dado en el diagrama.
 
 [![98.png](https://i.postimg.cc/6QNSbyVF/98.png)](https://postimg.cc/w1007xGk)
 
**4.3.** Ahora posicionaremos los resistores y los conectaremos con un cable celeste, siguiendo el modelo. Al final conectaremos los resistores 3 y 4 al cable negro (negativo) para poder cerrar el circuito con los dos suministradores de energía.

 [![445.png](https://i.postimg.cc/vZSjM0sF/445.png)](https://postimg.cc/K1BQDrjJ)

[![ji.png](https://i.postimg.cc/63hf6Qv2/ji.png)](https://postimg.cc/zbVg08p8)

**5. RESULTADOS OBTENIDOS**

**5.1**. Para poder medir las corrientes de cada nodo, primero debemos identificar los nodos del circuito.

[![Nod.png](https://i.postimg.cc/pTvmTnSf/Nod.png)](https://postimg.cc/xksfpqn8)

En total tenemos 6 nodos; sin embargo, el nodo A y D no se deberá considerar en el análisis de nodos, en su busqueda de voltaje debido a que ya conocemos sus voltajes; esto será explicado mejor luego (vease capítulo **5.3.**). De igual manera, el nodo E, el cuál es considerado como el nodo de referencia debido a que no hay ningún componente ahí, será considerado como nuestra tierra.

Por lo tanto, nuestro circuito quedaría de esta forma.

[![ui.png](https://i.postimg.cc/d1jQHsBw/ui.png)](https://postimg.cc/TLhXhXF4)

**5.2.** Ahora vamos a reconocer las direcciones por las cuales fluye la corriente en cada nodo en este circuito.

[![i.png](https://i.postimg.cc/3w5Wwbf4/i.png)](https://postimg.cc/68cBjzXt)

**5.3.** Una vez establecidas los nodos y la dirección por la que fluye la corriente tomaremos medidas de las corrientes en cada nodo. Primero lo haremos a través de Tinkercad.

[![iop.png](https://i.postimg.cc/prRFdVC6/iop.png)](https://postimg.cc/LYQXCprt)

Como se puede observar los nodos A y D poseen el mismo voltaje que sus suministradores de corriente, por lo tanto no es necesario hacer el calculo respectivo con esos nodos; pese a eso, se los utilizará para lograr calcular manualmente los nodos B y C y ver si el análisis en Tinkercad es correcto.

**5.4.** Ahora tomaremos las medidas de voltaje del circuito realizado en el simulador multisim.

[![45.png](https://i.postimg.cc/mDcZ4v7F/45.png)](https://postimg.cc/TL6vqH7R)

**5.5.** Ahora realizaremos manualmente el análisis de nodos, para observar si los resultados varian o no.

[![Whats-App-Image-2021-12-02-at-3-07-16-AM.jpg](https://i.postimg.cc/WpkRLQ9g/Whats-App-Image-2021-12-02-at-3-07-16-AM.jpg)](https://postimg.cc/mhBp76Wg)

[![Whats-App-Image-2021-12-02-at-3-07-16-AM-1.jpg](https://i.postimg.cc/BZxhCsYY/Whats-App-Image-2021-12-02-at-3-07-16-AM-1.jpg)](https://postimg.cc/yW8X1qzc)

**5.6.** Cómo ya poseemos todos los datos necesarios; rellenamos la tabla con los voltajes de las nodos.

| NODO  | Resultados Analíticos  | Resultados Experimentales  | Resultados Simulados  |
| ------------ | ------------ | ------------ | ------------ |
| A  | 12 V  | 12 V  | 12 V  |
| B  | 2.808 V  | 2.82 V  | 2.8203 V  |
| C  | 4.763 V  | 4.80 V  | 4.8020 V  |
| D  | 8 V  | 8 V  | 8 V |
| E  | 0 V  | 0 V  | 0 V |

**6. CONCLUSIONES**

Con este experimento pudimos entender de mejor manera el análisis de nodos. En este informe vimos lo que son los nodos y cómo reconocerlos en un circuito formado, al igual que diferenciarlos a cada uno. Vimos, de nuevo, la importancia de las leyes de Kirchhoff y de Ohm, y de cómo estas son aplicables incluso en este análisis. Logramos definir que es un análisis de nodos y sus pasos a seguir para poder conseguir las corrientes y voltajes.

Realizamos el procedimeintos del circuito dado de manera correcta y eficaz, mostrando en las imagenes el resultado y el funcionamieno de esta en Tinkercad, de igual manera pudimos simularla en Simulist. Luego fuimos capaces de reconocer los nodos y lograr sacar los voltajes de estos con el mulímetro. De igual manera, gracias al aprendizaje de un análisis de nodos, pudimos corroborar estos resultados manualmente, proporcionando las fórmulas para sacar los voltajes. 

Al final logramos identifcar cada voltaje de todas las formas solicitadas, y por lo tanto se concluye que el análisis de nodos es eficaz y más sencillo que otros análisis, debido a que logró cumplir con los voltajes medidos y el método de resolución fue sencillo. 

**7. BIBLIOGRAFÍA**

- Circuit. (2010). Multisim. Obtenido de https://www.multisim.com/create/
- Ministerio de Educaión . (2011). inet. Obtenido de http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf
- Eris, N. (20 de Noviembre de 2017). Sesoricx. Obtenido de https://sensoricx.com/circuitos-electricos-dc/analisis-de-circuitos-empleando-nodos/
- Hain, J. (14 de Septiembre de 2019). Khan Academy. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-node-voltage-method





