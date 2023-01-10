# laboratorio-5

Carrión Said

Macías Henry

Pilaguano José

Objetivos

1.- Objetivo General

Estudiar el teorema de Thévenin en circuitos mixtos apoyandose de los simuladores para comprobar que se cumple el teorema con los resultados analíticos mediante el presente laboratorio para relacionar y comprender de mejor manera la relación con los conocimientos aprendidos en un circuito eléctrico entendiendo de mejor manera dichos conceptos y aplicarlos en cualquier campo que se requieran.

OBJETIVOS ESPECÍFICOS

• Conocer el teorema de Thévenin para encontrar valores desconocidos, que nos pidan en un circuito eléctrico, 

Identificar la resistencia de Thévenin con la ayuda del amperímetro y voltímetro en los simuladores

• Reconocer los diferentes instrumentos de medida que tenemos en el laboratorio asi como el funcionamiento del mismo, analizar el circuito y su comportamiento al

momento de hacer hacer cero las fuentes de voltaje y calcular la resistencia equivalente.

• Resolver el laboratorio para afianzar el conocimiento y utilización del teorema de Thévenin en los circuitos, para poder llevar a cabo lo teórico a lo práctico,

Comparar los datos en el simulador con resultados calculados y realizar el cálculo del error.

2.- Marco Teórico

[![c14.jpg](https://i.postimg.cc/YCNjbMty/c14.jpg)](https://postimg.cc/3kRKwM4g)

[![c15.png](https://i.postimg.cc/zfJvQ6BD/c15.png)](https://postimg.cc/VJVzr7n2)

[![c16.webp](https://i.postimg.cc/W3z3NZgQ/c16.webp)](https://postimg.cc/Q9LsSH6b)

 3.- Diagramas

Circuito General

[![C6.png](https://i.postimg.cc/P5vkK4h3/C6.png)](https://postimg.cc/Mnw4p1nV)

Voltaje y corriente en R5

[![C7.png](https://i.postimg.cc/vmRwKVZQ/C7.png)](https://postimg.cc/rD9H0z4b)

Voltaje cuando la R5 se desconecta


[![C8.png](https://i.postimg.cc/769vbtM6/C8.png)](https://postimg.cc/WFdYHnyL)

R5 desconectada y dos fuentes de voltaje en 0, para medir la resistencia

[![C9.png](https://i.postimg.cc/JhbCCzsj/C9.png)](https://postimg.cc/p9X6DxYd)

Implementación del circuito Thevenin

[![C10.png](https://i.postimg.cc/d1wPscCp/C10.png)](https://postimg.cc/VSGHgTDW)

4.- Lista de componentes

[![C11.png](https://i.postimg.cc/GtmWDPqj/C11.png)](https://postimg.cc/mzKpf9xc)

5.- Explicación

5.1.- Procedimiento

[![C2.png](https://i.postimg.cc/28KD4JpL/C2.png)](https://postimg.cc/4mVqGWxX)

[![C3.png](https://i.postimg.cc/gkn9kDwz/C3.png)](https://postimg.cc/nCbS3qYg)

[![C4.png](https://i.postimg.cc/59PdVG2K/C4.png)](https://postimg.cc/DmbYQxs1)

[![C5.png](https://i.postimg.cc/SR1wfXPb/C5.png)](https://postimg.cc/V0MGYN1K)

Se ingresa a la plataforma Tinkercad, se crea una cuenta, a continuación en el apartado de circuitos seleccionar nuevo circuito.

Se seleccionan los materiales que vamos a utilizar, una placa de pruebas, 5 resistencias, multimetros digitales y dos fuente de voltaje.

En la primera fuente de voltaje, se la configura con 12 V, mientras que la segunda fuente de voltaje tendrá un valor de 2 V.

Se procede a configurar cada resistencia con el valor ya establecido en el circuito.

De la fuente positiva de 12 V se conecta hacia hacia un extremo de la resistencia de 560 ohms.

Del extremo de la resistencia 1, se conecta hacia la resistencia de 4.7 kohms, del otro extremo de esta resistencia se la conecta hacia el negativo de la fuente

Se conecta la fuente de voltaje de 2 V, el lado negativo se conecta hacia el nodo de R1 y R2, el lado positivo irá conectado hacia un extremo de la resistencia de 330 ohms.

Del otro extremo de la resistencia de 330 ohms, se conectará hacia R2.

La resistencia de 100 ohms, va conectada en el nodo formado por la fuente de voltaje de 2 voltios y por la R3.

Finalmente la resistencia de 1 kohm, se conecta hacia la resistencia 4 y el otro extremo hacia la R3.

Se mide el voltaje y la corriente en R5

Se desconecta el resistor 5 y con el voltímetro en paralelo se mide el voltaje, que es 5.06 V.

Las 2 fuentes de voltaje se hacen 0 y con el multímetro en paralelo se mide resistencia que nos da un valor de 299 ohms.

Con esos valores, se procede a hacer el circuito equivalente de Thevenin, con la resistencia de 299 ohms, el voltaje de 5 V y la resistencia de 1 kohm.

5.2.- Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla

Para medir el voltaje se tiene que conectar el voltímetro en paralelo a la resistencia y para medir la corriente se conecta en paralelo, poniendo la primera terminal al extremo de la R4 y la otra terminal al inicio de la R5.

5.3.- Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla

Para medir el voltaje se coloca en la R4 la terminal del multímetro y la otra terminal hacia la R3.

5.4.- Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla

Con la misma conexión que hicimos anteriormente se coloca el multímetro en Resistencia, y las fuentes de voltaje se las deja con un valor de 0.

5.5.- Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla

Con el resultado que nos dio en el punto 5.4. se deja esa resistencia, con una sola fuente de voltaje con el valor que medimos en el punto 5.3. a continuacióm, se conecta en serie con la R5.

6. Tabla de valores del Circuito Equivalente de Thévenin.

[![c12.png](https://i.postimg.cc/hjQBZ19P/c12.png)](https://postimg.cc/R6myNfsj)

Tabla de comprobación del Teorema de Thévenin

[![c13.png](https://i.postimg.cc/RhrzkJR1/c13.png)](https://postimg.cc/CB4tD19d)

7. Vídeo

https://youtu.be/LWQ8vo_UnF4

  8. Conclusiones

 * Sin la ayuda de los instrumentos de medición como el amperímetro o voltímetro nuestros datos no serian concretos, ya que estos nos ayudan en los cálculos de varios métodos como por ejemplo el calculo con la ayuda de mallas.
  
 * El comportamiento del circuito al hacer cero las dos fuentes, dio la disponibilidad de un análisis mucho mas breve ya que se disminuían los elementos en el mismo.

 * En conclusión, al usar el método de Thevenin y el método de resolución por mallas, se observo que arrojaba un mínimo error ya que los valores calculados eran casi exactos.


  10. Bibliografía

Floyd, T.L. (2007). Principios de circuitos eléctricos (Octava ed.)






