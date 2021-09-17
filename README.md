# Trabajo-Extra-PACKET-TRACER


<div align="center">

# UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

AUTORES

Ariel Santiago Munoz Pallo

NRC
  
5412

INGENIERO

Ing. Darwin Omar Alulema Flores

# PRÁCTICA CASA SMART
  
</div>

# 1 OBJETIVOS

**1.1. OBJETIVO DE LA PRÁCTICA**

1.1.1. Objetivo general

- Proponer una red tipo IoT dentro de una casa simulada por medio de la aplicación Packet Tracer que sirve como base de entendimiento para posibles conexiones a la red en un futuro además analizar el programa con sus funciones especificas para realizar dichas conexiones información que nos ayudara para mejor entendimiento de la materia en un futuro.


1.1.2. Objetivos específicoso

•	Conocer sobre la aplicación Packet Tracer y sus posibles creaciones. 

•	Analizar profundamente sobre el concepto de Iot.

•	Demostración simulada de conexiones por medio de una red en el programa Packet Tracer.

**1.2. REQUISITOS PREVIOS**

Investigue Sobre como descargar el Programa además visualizar videos para saber cual es su funcionalidad por medio de este link 

https://drive.google.com/drive/u/0/folders/1x9LZWTWsSsAvuANDUcftXcXvqut3liPx




**1.3. INFORMACIÓN GENERAL**

<div align="center">
  
  **CASA SMART**

[![1.jpg](https://i.postimg.cc/VLLjZC6j/1.jpg)](https://postimg.cc/c62gr6fH)

</div>


# 2 MARCO TEÓRICO

<div align="center">
  

Packet Tracer de Cisco es un programa de simulación de redes que permite a los estudiantes experimentar con el comportamiento de la red simulados con sus elementos incluidos.
En este programa se crea una topología física de la red simplemente arrastrando los dispositivos a la pantalla es decir simulados. Luego haciendo clic sobre ellos se puede ingresar a sus consolas de configuración para una posible modificación. Allí están soportados todos los comandos del Cisco IOS  para su mejor rendimiento
Una vez completada la configuración física y lógica de la red, también se pueden hacer simulaciones de conectividad (pings, traceroutes) todo ello desde las mismas consolas incluidas.
  
# 2.1. Que es IoT y como Funciona ?
  
El Internet de las cosas o también llamado (IoT) es el proceso que permite conectar elementos físicos cotidianos al Internet: desde objetos domésticos comunes, como las bombillas de luz, hasta recursos para la atención de la salud, como los dispositivos médicos; incluso los sistemas de las ciudades inteligentes.
El término IoT hace referencia a los sistemas físicos que reciben y transfieren datos a través de redes inalámbricas con poca intervención humana, lo cual es posible gracias a la integración de los dispositivos informáticos en todo tipo de objetos.
  
IoT empresarial:
  
 IoT para empresas les permiten mejorar los modelos comerciales actuales y entablar nuevas relaciones con los clientes y los partners. No obstante, su implementación presenta ciertos desafíos. El volumen de datos que genera un sistema de dispositivos inteligentes puede volverse abrumador. y configurar el análisis de datos para poder utilizarlos puede resultar complicado.

IoT y edge computing:
  
El edge computing proporciona mayor potencia informática en los extremos de una red de IoT para reducir la latencia de comunicación entre los dispositivos de IoT y las redes de TI centrales a las que se conectan.
La capacidad de los dispositivos para utilizar esta potencia informática en el análisis rápido e inmediato de los datos es cada vez más valiosa.  El IoT nació gracias al envío y la recepción de datos, pero el futuro radica en la capacidad de enviarlos, recibirlos y analizarlos con las aplicaciones del IoT.


</div>

# 3 Interface del Programa

[![2.jpg](https://i.postimg.cc/vTddHy1s/2.jpg)](https://postimg.cc/ZBjQV1F7)


Las diversas áreas de la zona de trabajo de Packet Tracer son:

•	Menú principal: dispone de opciones como File, Edit, Options, View, Tools, Extensions y Help.

•	Main Toolbar: con las típicas funciones como abrir, guardar, imprimir, zoom in/out, deshacer, rehacer, etc.

•	Secondary Toolbar: son las opciones de Packet Tracer, como seleccionar, borrar, añadir formas o enviar datos.

•	Button Toolbar: contiene todos los dispositivos y conexiones que dispone el programa y que se añaden en el diseño y configuración de una red. Esta barra se divide en dos partes, la primera de la izquierda, donde están las distintas categorías de los dispositivos, y una segunda donde se despliegan los dispositivos y conexiones para añadirlos


•	Área de Trabajo: la zona más amplia de la interfaz, donde se realiza el diseño de la red, añadiendo los dispositivos y conexiones, y donde se visualiza la simulación.










  
</div>

# 4 EXPLICACIÓN DEL PROCEDIMIENTO

**4.5 PROCEDIMIENTO**

**4.5.1. Creación de una casa Smart **

<div align="center">
  
Primero abriremos nuestro programa para poder visualizar nuestra interface que nos acompañara  por este ejercicio.

[![3.jpg](https://i.postimg.cc/SKJXc6gK/3.jpg)](https://postimg.cc/QBZx3TGL)

Al entender nuestra interface gracias a esta guía comenzaremos a realizar nuestro ejercicio
El primer paso a completar es colocar nuestro formato de casa o edificio que deseemos poner las conexiones IoT para hacer esto cargaremos la imagen desde el botón Set Background Image.
Hecho esto colocaremos un wireless device llamado AP-PT que nos dará una conexión inalámbrica como inicio de nuestra interface.
[![4.jpg](https://i.postimg.cc/bNmNLGDS/4.jpg)](https://postimg.cc/WhJv117s)

Segundo paso es configurar nuestra interface para inicializarlo como un dador de datos para esto daremos click derecho ir a configuraciones en port 1 y pondremos el nombre y contraseña de nuestro dador de datos esto claro inicializado como WPA2-PSK.

[![5.jpg](https://i.postimg.cc/nL0khGCc/5.jpg)](https://postimg.cc/f3SXHXc6)

Hecho esto pondremos nuestra interface Servidor para poder entregar los datos de comunicación inalámbrica con un servidor donde podremos controlar nuestras conexiones para esto pondremos un End Device llamado Server en este servidor configuraremos Desktop con un código de puerta normalmente usada para poder usar internet.


[![55.jpg](https://i.postimg.cc/Kv1vqGn9/55.jpg)](https://postimg.cc/RNzBqzpf)



Posteriormente verificaremos si se encuentra verificado en Configuraciones Fastethernet0

Ahora conectamos nuestro servidor con el Display hecho esto colomacoms en nuesta Casa Smart los electrodomésticos que deseemos usar 



[![Whats-App-Image-2021-09-17-at-10-09-53-AM.jpg](https://i.postimg.cc/Jn7BtfS9/Whats-App-Image-2021-09-17-at-10-09-53-AM.jpg)](https://postimg.cc/sB82NNjc)


modificamos el DHCP para poner conectar el servidor
y prendemos la opción IoT


[![7.jpg](https://i.postimg.cc/SKCwj5c7/7.jpg)](https://postimg.cc/McZsF9Pv)


Para conectar nuestros objetos entramos en la configuración de los mismos señalamos wriless y colocamos en usuario y la contraseña de nuestra Display ya antes colocado Así se colocara una línea entrecortada para poder saber que esta enlazados

[![56.jpg](https://i.postimg.cc/jSXNZRVk/56.jpg)](https://postimg.cc/hXXfGWt9)


[![57.jpg](https://i.postimg.cc/PqCxYHdD/57.jpg)](https://postimg.cc/8FVNgqJk)

 

Hecho esto ya podemos crear nuestra cuenta para poder controlar nuestro aparatos desde nuestro Servidor para ello vamos a In monitor y configuramos nuestras contraseñas y datos solicitados 

[![58.jpg](https://i.postimg.cc/T2L4S43c/58.jpg)](https://postimg.cc/w3z2RFJt)


Hecho esto estamos listos para poder correr nuestra conecion desde el servidor de el programa y listo asi se vería una casa Smart 

[![59.jpg](https://i.postimg.cc/52xpx7bT/59.jpg)](https://postimg.cc/jLFychW4)






</div>

# 5 VIDEO

https://www.youtube.com/watch?v=RSFVn47Ghe8


# 6 CONCLUSIONES 

Este programa a mi parecer es uno de los mejores programas para una conexión  tipo IoT porque además de ser didáctico y llamativo a los ojos humanos te enseña las conexiones y si no sabes pues te obliga a investigar con la facilidad de entender por medio de gráficos sencillos y didácticos.

Cabe recalcar que por este medio logramos hacer varias conexiones y sin sufrir ningún atraso a su señal y menos aún parálisis del programa.

Personalmente es un programa que me interezo mucho ya que forma parte de nuestro conocimiento como son las telecomunicaciones y redes en su máxima expresión  



# 7 BIBLIOGRAFÍAS

https://www.netacad.com/es/courses/packet-tracer

https://www.ambit-bst.com/blog/todo-lo-que-debes-saber-de-cisco-packet-

https://www.ecured.cu/Cisco_Packet_Tracer
