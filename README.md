# SEVEN DIGITS DISPLAY Y LED RGB

![](https://i.imgur.com/oUoM72I.png)

------------

### Los displays de 7 segmentos son dispositivos electrónicos de visualización utilizados como una forma fácil de representar numerales decimales y una alternativa a los displays de matriz de puntos más complejos. Se llaman displays de segmentos porque están compuestos por varios segmentos que se encienden y apagan para dar la apariencia del glifo deseado. Los segmentos generalmente son LED individuales o cristales líquidos. 

![image](https://user-images.githubusercontent.com/106705252/190072737-21905130-1197-4b9d-a1c7-17af8391d21d.png)

### En esta tabla se ven los distintos valores que se tienen para poder activar un numero con los distintos pines que estos estan representados en la imagen anterior. Los displays de 7 segmentos empezaron a usarse de forma generalizada como una forma popular para visualizar números. Los displays de siete segmentos se emplean ampliamente en relojes digitales, medidores electrónicos, calculadoras básicas, pantallas de electrodomésticos, coches, y muchos otros dispositivos que muestran información numérica.

**Codigo 7 Segmentos Catodo Comun**

| Numero |   | g | f | e | d | c | b | a |
|:------:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|    0   | 0 | 0 | 1 | 1 | 1 | 1 | 1 | 1 |
|    1   | 0 | 0 | 0 | 0 | 0 | 1 | 1 | 0 |
|    2   | 0 | 1 | 0 | 1 | 1 | 0 | 1 | 1 |
|    3   | 0 | 1 | 0 | 0 | 1 | 1 | 1 | 1 |
|    4   | 0 | 1 | 1 | 0 | 0 | 1 | 1 | 0 |
|    5   | 0 | 1 | 1 | 0 | 1 | 1 | 0 | 1 |
|    6   | 0 | 1 | 1 | 1 | 1 | 1 | 0 | 1 |
|    7   | 0 | 0 | 0 | 0 | 0 | 1 | 1 | 1 |
|    8   | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
|    9   | 0 | 1 | 1 | 0 | 0 | 1 | 1 | 1 |

------------

![](https://i.imgur.com/b3jc0Zl.png)

### Su funcionamiento es bastante simple, se conecta la corriente al semiconductor superior del diodo (funciona gracias al trasvase de electrones entre dos materiales semiconductores, una pareja positivo-negativo) LED lo cual permitirá el paso de corriente eléctrica y hará que el semiconductor emita luz. El pin 3 es el anodo y el pin 8 el catodo comun para el caso que tengamso o utilicemos. 

### Los displays de 7 segmentos pueden usar pantallas de cristal líquido (LCD), un diodo emisor de luz (LED) para cada segmento u otras técnicas de control o generación de luz como la descarga de gas de cátodo frío (Panaplex), fluorescente vacío, filamentos incandescentes (Numitron).

![](https://i.imgur.com/5EP8bap.png)

### El display ánodo común es aquel cuyos ánodos están conectados al mismo punto. Este tipo de display es controlado por ceros, le asigna a cada segmento un cero lógico. 

### El display cátodo común es aquel que tiene el pin común conectado a los negativos de los LED’s. Esto significa que este tipo de display se controla con ‘1’ s lógicos o voltaje positivo.

### El display de 7 segmentos funciona al activar y desactivar cada uno de los leds para formar los números deseados. En la siguiente imagen se muestra el numero 6 por catodo comun. 1	1	1	1	1	0	1, lo que activa los leds indicados al mandar un valor binario de activar.

![](https://i.imgur.com/mGtHGtt.png)

------------

![](https://i.imgur.com/O1oJ3Qf.png)

------------

### LED RGB significa LED rojo, azul y verde. Los productos LED RGB combinan estos tres colores para producir más de 16 millones de tonos de luz. Pero no todos los colores son posibles. Algunos se encuentran "fuera" del triángulo formado por los LED RGB.

  **Tabla sobre brillo necesario para generar el color**

| Color      | Red | Green | Blue |
|------------|-----|-------|------|
| White      | 255 | 255   | 255  |
| Off        | 0   | 0     | 0    |
| Red        | 255 | 0     | 0    |
| Green      | 0   | 255   | 0    |
| Blue       | 0   | 0     | 255  |
| Light blue | 0   | 255   | 255  |
| Pink       | 255 | 0     | 255  |
| Yellow     | 255 | 255   | 0    |
| Orange     | 255 | 48    | 0    |
| Cyan       | 0   | 255   | 48   |
| Purple     | 48  | 0     | 255  |

### En otras palabras, es la unión de tres LEDs de los colores básicos (rojo, verde y azul) en un encapsulado común. En función de la tensión que pongamos en cada pin podemos conseguir la mezcla de color que deseemos con relativa sencillez. Un LED RGB tiene 4 patas, 1 para controlar cada color y la que queda es por donde entra o sale la electricidad, dependiendo de si es de ánodo (la pata más larga es por donde entra la electricidad) o cátodo común (la pata más larga es por donde sale la electricidad). 

### Delante de cada una de las patas de color del LED RGB siempre se tendrá que poner una resistencia con un valor suficiente para no romper el LED. En este caso, pondremos una resistencia de 220 ohmios.

### Se muestra Led de catodo comun ![](https://i.imgur.com/ARQBHKS.png)

------------

![](https://i.imgur.com/b3jc0Zl.png)

### Una luz LED funciona gracias al trasvase de electrones entre dos materiales semiconductores, una pareja p-n (positivo-negativo), que es lo que habitualmente se conoce como un diodo. Al establecerse un voltaje entre la pareja, se crea un flujo de partículas desde cada uno de los semiconductores al otro.

### En esta imagen vemos como al conectarse los 3 pines de las raspberry estos para positivo y la pata mas larga negativo siguiendo el ejemplo de un Led RGB catodo comun.

![](https://i.imgur.com/j5rxitC.png)

### Los LED modernos están disponibles en las longitudes de onda visibles, ultravioleta e infrarroja. Trabajan con una alta eficiencia de emisión, gracias a la cual producen mucha luz de forma que ahorran energía. Los productos modernos de este tipo están hechos de una variedad de materiales semiconductores, dependiendo del color. 

### Actualmente, los LEDs rojos se fabrican con fosfuro de aluminio y galio de indio (AlInGaP), lo que los hace más eficientes que los elementos con GaP o AlGaAs. Los diodos LED azules y verdes están compuestos principalmente por nitruro de galio y nitruro de galio e indio (GaN e InGaN). La cantidad de indio determina el color: cuanto más indio, mayor es la longitud de onda.

![](https://i.imgur.com/nhu17Fp.png)
# CODIGO
###### import time
###### import board
###### import digitalio

###### a = digitalio.DigitalInOut(board.GP4)
###### a.direction = digitalio.Direction.OUTPUT
###### b = digitalio.DigitalInOut(board.GP5)
###### b.direction = digitalio.Direction.OUTPUT
###### c = digitalio.DigitalInOut(board.GP8)
###### c.direction = digitalio.Direction.OUTPUT
###### d = digitalio.DigitalInOut(board.GP9)
###### d.direction = digitalio.Direction.OUTPUT
###### e = digitalio.DigitalInOut(board.GP12)
###### e.direction = digitalio.Direction.OUTPUT
###### f = digitalio.DigitalInOut(board.GP13)
###### f.direction = digitalio.Direction.OUTPUT
###### g = digitalio.DigitalInOut(board.GP22)
###### g.direction = digitalio.Direction.OUTPUT

###### a.value = True
###### b.value = True
###### c.value = True
###### d.value = True
###### e.value = True
###### f.value = True
###### g.value = True
###### time.sleep(2.5)

###### while True:
######   a.value = False
######   b.value = False
######   c.value = True
######   d.value = False
######   e.value = False
######   f.value = True
######   g.value = False

![](https://i.imgur.com/H7jgeq3.gif)
