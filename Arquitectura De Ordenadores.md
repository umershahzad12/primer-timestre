# Arquitectura De Ordenadores
 
 Aqui esta los apuntes sobre arquitectura de ordenadores
 
 ![](https://informaticaenmicasa.com/wp-content/uploads/2014/06/placa-base-1-300x179.png)


## Índice (Index)

- [Clase de binario](#binario)

# Apuntes de Classe
  ### Portátil

    Transformador externo

    Fuentes de Alimentación

    Batería
## Creacion de Ordinador
![](https://raw.githubusercontent.com/Hanzla55/primer-trimestre/main/pc.png)

![](https://raw.githubusercontent.com/Hanzla55/primer-trimestre/main/PC.png)

El Precio total es 992,27€


### Procesador

El microprocesador es un circuito integradoformado por millones de transistores, cuya función es procesar los datos y las instruccionesque recibe de la memoria RAM. El área ocupada por dicho circuito viene a ser un cuadrado de 1 cm de lado, pero la gran cantidad de patillas de conexión que necesita para conectarse a la placa base, hace que su tamaño total sea mayor.

[Fuente: apuntes del profesor](https://grandecovian.es/FGC/files/D.%20Tecnolog%C3%ADa/TIC%20I/Arquitectura/Arquitectura%20de%20ordenadores.pdf)

### Ram

La memoria RAM es donde el ordenador almacena temporalmente los datos y los programas con los que está trabajando. Todo lo que hay en ella almacenado se borra cuando apagamos o reiniciamos el ordenador. Físicamente es una placa rectangular de circuito impreso con varios chips, que se acopla a la placa base a través de una ranura específica.

Suelen tener distintas capacidades (2GB,4GB,8GB,etc...) También tienen distintos tipos de memoria, por ejemplo, DDR, DDR2, DDR3 y DDR4.

### Teclado
Son dispositivos de entrada activados por la pulsación de teclas. Incorporan un circuito de entrada que se comunica con el pc. Su conexión es USB.

## Tarjeta gráfica

La función básica de una tarjeta gráfica es convertirla información procesada por el ordenador, o la propia tarjeta, en una señalque pueda entender el monitor, para mostrarlaen forma de imagenen  la pantalla.

### Que es GPU?
 
 El procesador gráfico. Denominado GPU (Unidad de Procesamiento Gráfico)Es el encargado de procesar toda la información gráfica, realizando los cálculos necesarios para obtener la imagen final. Igual que el procesador del ordenador, el procesador de la TG trabaja a una determinada velocidad o frecuencia de reloj, expresada en megahercios (de 200  a  500  MHz).  Para  evitar  su  deterioro  por  calentamiento,  deben  ser  refrigerados mediante disipadores térmicos, a los que se añade, generalmente, un pequeño ventilador.
 
 ### Que es la memoria grafica?
 Velocidades:

    GPU Boost Clock
        OC Mode 1506 MHz
        Gaming Mode 1468 MHz
    GPU Base Clock
        OC Mode 1266 MHz
        Gaming Mode 1228 MHz
Es  una memoria de tipo RAM en la que se almacena gran parte de la información gráfica que debe procesar la GPU. Otra parte de dicha información gráfica puede almacenarse en la memoria RAM de la placa base, debiendo acceder a ella la tarjeta a través del puente norte. La memoria gráfica se caracteriza por su capacidad, (expresada en MB), por  su velocidad  de  trabajo(expresada  en  MHz)  y  por  el tipo(DDR,  DDR2,  GDDR3). La tarjetas actuales suelen tener entre 512 MB  y 4 GB de capacidad y funcionan a frecuencias comprendidas entre 200 MHz y 1000 MHz, aproximadamente.

### Tipo de interfaz:

Existen dos tipos de interfaz: -AGP 8X. Es la última versión del bus AGP, que se caracteriza por un ancho de banda (por ejemplo de 2 GB/s) en el sentido placa base -> tarjeta y otro (por ejemplo de 266 MB/s) en el sentido inverso (en el ejemplo, 2,26 GB/s en total). -PCI-Express 16X. Sistema de bus para tarjetasgráficas, cuyo ancho de banda es de 4 GB/s en ambos sentidos (8 GB/s en total). El acceso a la memoria RAM de la placa base está gestionado por hardware desde el propio procesador gráfico. Ahora mismo es más rápido que AGP.

### Tipos de conexiones externas:

Se trata de diferentes conectores de salida de señal video: -Puerto VGA.  Emite  una  señal  de  video  analógica,  apta  para  monitores  de  tipo  CRT (normales).-Puerto DVI. Emite una señal de video digital, que suelen utilizar los monitores de tipo LCD plano.-Puerto S-Video. Emite una señal de video analógica, apta para un televisor o un vídeo.


### Caracteristicas de Tarjeta Grafica     Asus GeForce GT 1030 Silent 2GB GDDR5

Processador gráfico: NVIDIA GeForce® GT 1030.
Tipo de Interfaz: PCI Express x16 3.0.
Memoria Grafica: GDDR5.
Tamaño de memoria: 2048 MB.
Salidas de video: HDMI (1), DVI-D (1).
Velocidades:

    GPU Boost Clock
        OC Mode 1506 MHz
        Gaming Mode 1468 MHz
    GPU Base Clock
        OC Mode 1266 MHz
        Gaming Mode 1228 MHz
        
 ### Discos Duros
 
 #### Formateo y Sectores 
 
 Tengo un disco duro magnetico de 100gb.
 
 Cuantos sectores tiene si cada sector es de 512 bytes?
 
 Aproximadomente 209 Millones de sectores.
  
 
 ### Formatos de Archivo

Windows: FAT, FAT32, NTFS

Linux: EXT2, EXT3, EXT4


## Internet y redes 

### Redes Locales LAN
 
LAN: Local Area Network

Protocolo TCP/IP ---> IPv4, tiene 4 bytes y tienen rango de 0 a 256, por ejemplo 192.168.0.1 ( El propio PC)

Un switch es un dispositivo de interconexión utilizado para conectar equipos en red formando lo que se conoce como una red de área local (LAN) y cuyas especificaciones técnicas siguen el estándar conocido como Ethernet (o técnicamente IEEE 802.3). De esta [página](http://www.trabajosocial.unlp.edu.ar/uploads/docs/switch__routers_y_acces_point__conceptos_generales.pdf).

Servidor Wi-fi o punto de acesso Wi-fi tiene Protocolo TCP/IP, pero no tiene porque tener internet.

DHCP--> Asignar de forma automática las ips de los ordenadores conectados, por ejemplo 255.255.0.193. Antes se hacia de forma manual.

Ataque DDOS--> Pedir a la vez demasiadas cosas a un mismo servidor.

Stream : Arroyo de Datos--> Corriente de agua

UTP

Puertos---> Puertas, Abiertas o Cerradas---> 80---> htts y 442 --> https  Ambos son hipertextos
         
LAN 

4 bytes IPv4

255.255.255.255  Hay un máximo 4228250625 de ordenadores en IPv4, IPv6 permiten que se conecten más dispositivos.
 
 
 
 ### Tarjetas de sonido

Velocidad = Frecuencia x Ancho de banda

160000 bits/s = 160000 ÷ 8 ÷ 1024 = 19,5 KB/s

Los buses de datos tienen una determinada capacidad de transmisión de información. Esta capacidad se mide en información/segundo, por ejemplo bits/s, KB/s, MB/s, GB/s.

Para pasar de una unidad a otra tendremos que multplicar o dividir. 

Para pasar de bits (b) a bytes (B) dividimos entre 8, que es el número de bits en un byte.

Para pasar de byte (b) a Kilobyte (KB) dividimos entre 1024, que es el número de bytes en un KiloByte.

Para pasar de Kilobyte (KB) a MegaByte (MB) dividimos entre 1024, que es el número de KiloBytes.

Para pasar de MegaByte (MB) a GigaByte (GB) dividimos entre 1024, que es el número de MegaBytes.

Para pasar de GigaByte (GB) a Terabyte (TB) dividimos entre 1024, que es el número de GigaBytes.

Su hubiera que pasar de bit a MB, se unen varias divisiones, en este caso : primero divimos entre 8 y luego 2 veces entre 1024.

Si pasamos de unidades grandes a pequeñas multiplicaremos en vez de dividir.

La velocidad de transmisión es iguala de a la frecuencia de transmisión del bus multplicidado por el mínimo de bits por paquete. El número de bits de paquete depende de cuantas conexiones tenga.



Unidades de la frecuencia

La frecuencia se mide en Hertz, herzios o segundos a la menos 1 (1/s)

1 herzio representa que algo ocurre una vez por segundo

0,1 herzios representa que algo ocurre una vez cada 10 segundos.

5 herzios representa que algo ocurre 5 veces por segundo.

En informática estas frecuencias pueden referirse habitualmente a
     
     - Frecuencias de reloj para transmitir datos (MHz, GHz)
     
     - Frecuencias de sonido (Hz, KHz)
     
Para cambiar la unidad, se utiliza el sistema internacional, es decir múltiplos y submúltiplos en base decimal. 

Es decir: 1 MHz = 1.000.000 Hz  1KHz = 1000 Hz

25 Mhz    512 bytes/paquete         ¿Velocidad?

25 Mill  x 512 bytes/paquete       12.800.000.000 b/s = 11,9 GB/s


### Sistema Operativo

Windows 10, Linux (ubuntu), iOS, Android, MacOS

Funciones básicas:
 
 - Hablar con el hardware

 - Establecer conexiones (wi-fi, LAN, BT, 4G)

 - Interfaz básica de usuario

 - Acceder y administrar discos 

 - Acesso básico de archivos

 - Permitir instalar otros programas






## Binario 
El sistema binario funciona con potencias de 2, por ejemplo 2,4,8,16,32,64.

Sistema Decimal = 10 , Sistema Binario = 2 , Sistema Octal = 8 , Sistema Hexadecimal = 16

[Info RGB](https://es.wikipedia.org/wiki/RGB)

0 = 0

1 = 1

2 = 10

3 = 11

4 = 100

5 = 101

6 = 110

7 = 111

8 = 1000

9 = 1001

10 = 1010

16 = 10000

1 000 000 en España  1.000.000 en EEUU  1000000 en Calculadora 

### Notación Binaria 

0b  Se utiliza para decirle a un ordenador que un número está en binario.
Ox  Se utiliza para decirle a un ordenador que un número está en hexadecimal.

1000 = Decimal

0b 1000 = BinarioClase de binario.md

0x 1000 = Hexadecimal



### Ejercicios de consevasion

Cuanto es 100000 en binario?   
100000 en binario es 11000011010100000

Cuanto es 100010111100100111 en decimal?   
100010111100100111 en decimal es 143143


