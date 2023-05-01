# domotica
Proxecto de domótica con Home Assistant e ESP32, ESP8266

Creación dun servidor IoT con Home Assistant sobre unha Raspberry Pi
Utilizamos ESPHome para conectar ESP32 e ESP8266 ao servidor. 
Conectamos sensores e actuadores aos GPIO das ESP para programar automatizacións e recibir lecturas dos sensores.
No proxecto final colocamos os sensores e actuadores na maqueta do instituto para recrear unha vivenda cunha instalación de domótica.

![EdificioSinPortas(1)](https://user-images.githubusercontent.com/126872606/228348099-7fb05715-eebd-4826-916e-fc07074e7c42.png)

Visualización das tarefas realizadas:
![Mapa Mental](https://user-images.githubusercontent.com/126872606/235425098-43155a56-0149-4694-9ab4-f6a71be46451.jpg)
![Fluxo de traballo](https://user-images.githubusercontent.com/126872606/235425115-98739843-454b-4425-beaf-e427c1c25d46.jpg)



Utilizamos unha ESP32 WROOM conectada aos sensores e actuadores comopodes ver na táboa de conexións GPIO e na seguinte imaxe:

![EsquemaConexions_bb](https://user-images.githubusercontent.com/126872606/234692499-df68bb9e-6d42-405d-8644-8cca9cc090bc.svg)

Para programar cada un dos dispositivos podes ler a información sobre o mesmo en cada unha das páxinas ás que podes acceder desde o documento 'LigazonsESPHome.pdf'
Os pasos do proxecto da maqueta domótica son:
1. Instalar e configurar Home Assistant nunha Raspberry Pi 3 ou 4.
2. Acceder ao servidor Home Assistant desde a aplicación web, sempre desde a mesma rede.
3. Instalar ESPHome en Home Assistant
4. Engadir o ESP32 ou ESP8266 que vaiamos a utilizar para controlar os sensores e actuadores.
5. Ir configurando, nese ESP, os dispositivos dun en un e probando o seu correcto funcionamento.
6. Construir a maqueta e instalar todo o sistema nela.
![maqueta2](https://user-images.githubusercontent.com/126872606/234694990-3771611c-b1ca-49fd-b593-96d3eef1c890.jpg)
