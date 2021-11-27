
###Projeto Desenvolvido para a Universidade Presbiteriana Mackenzie

Aluno Tiago Lima Da Silva

Matéria: Objeto Inteligentes Conectados

Professor: Wilian Franca Costa

Descrição do Projeto 

O projeto tem como objetivo a capitação da temperatura e umidade do ambiente para o controle do fluxo de ar controlando assim a qualidade do ar,
podendo ser utilizado em todos os ambientes de sua residencia. 
O objetivo do projeto é a facilidade de mobilidade e utilização sendo utilizado o protocol MQTT


- Controle de Temperatura.
- Controle de Umidade. 
- Abertura e fechamento (janela).

A parte prototipo do projeto:

![image](https://user-images.githubusercontent.com/89432768/143663970-ad6b4df4-d580-4d34-b041-db35e7abdb05.png)

Os Componentes Utilizados Para o Projeto foi:

- 1 Placa NodeMCU ESP8266 Wi-Fi
- 1 Sensor DHT11
- 1 Display Oled 0.95
- 1 Led Verde
- 1 Protoboard 830 Pontos MB-102
- 1 Motor Servo SG90
- 2 fios fêmea-fêmea
- 13 fios fêmea-macho
- 1 Cabo USB
- Arduino IDE
- MQTTBox (Web)

Circuito Desenvolvido CIRCUITO.IO

![image](https://user-images.githubusercontent.com/89432768/143662499-b3dc953d-5686-41b1-9c80-bab77937c755.png)

O sensor utilizado no Circuito.io é o DHT22 sua diferença entre o DHTT11,
pois ele abrange uma faixa maior de temperatura e umidade.

Descrição Tecnica do Projeto:

Foi utilizado a Arduino IDE, utilizando as seguintes bibliotecas,

As seguintes bibliotecas foram incluídas para que o circuito funcionasse: 
 
 <ESP8266WiFi.h> : Responsável por trazer os setups para o funcionamento da Placa ESP8266
 <PubSubClient.h>: Responsável para a comunicação MQTT e pelo qual os métodos de publicação e subscrição realizados
 <Adafruit_Sensor.h>: Responspavel para as configurações do Sensor PIR
 <DHT.h>: Responsável para as configurações do sensor de temperatura e umidade DHT11
 <Servo.h>: Responsável para as configurações  do Servomotor SG90
 <SSD1306.h> Responsável por transmitir as informações no display oled  
    
    
Comunicação com o MQTT (Message Queuing Telemetry Transport):

Foi utilizado o MQTTBOX que percente a empresa GOOGLE, com ele é capaz de acompanhar em tempo real
as ações do publiser e do subscriber que foram configurados no broker.

broker utilizado: broker.mqtt-dashboard.com

![image](https://user-images.githubusercontent.com/89432768/143662954-a8f6fcf8-ce79-4a21-abf4-c720892b276f.png)

Resultado final:

Todos os objetivos que foram criados e colocados em pratica no desenvolvimento do projeto;
foi realizado testes e correção durante o desenvolvimento do projeto, o Protocolo MQTT é 
muito util sua utilização facilita a comunicação com outros objetos, garantindo qualidade e 
segurança.

