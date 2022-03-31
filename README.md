# ontracker-challenge v0.0.1

Dado que a `Ontracker` é uma empresa de tecnologia em `IOT` fornecendo plataformas para monitoramento, rastreamento, gestão de frotas, gestão de telemetria... o nosso desafio aqui para você que está afim de fazer parte da nossa equipe é:

Hoje temos diversos tipos de dispositivos em campo transmitindo dados usando a internet através do protocolo `TCP/UDP`. O formato dos dados transmitidos podem variar de dispositivo para dispositivo por exemplo:

##### Dispositivo X:
```
+RESP:GTFRI,860599002977247,-46.552865,-23.572365,20220211042233
```
onde temos o seguinte layout:
```
HEADER,DEVICE_ID,LAT,LNG,DATE_TIME
```

##### Dispositivo Y:
```
ST300STT;205620351;20190718;07:00:11;-23.572467;-46.552977
```
onde temos o seguinte layout:
```
HEADER,DEVICE_ID,DATE,HOUR,LAT,LNG
```

Dado o desenho:
![image](https://user-images.githubusercontent.com/797845/161099155-55b32939-58a7-422c-aa6d-18621b2b5c73.png)

queremos que você desenvolva uma solução onde:

* teremos um único modelo de dados na Ontracker
* listagem do histórico de transmissão do dispositivo com os seguintes filtros:
  * todos os dispositivos
  * pelo device_id
  * por período de transmissão
* uma das três apps no desenho para visualização dos requisitos acima

Obs:
* pode usar uma linguagem de sua preferência (usamos muito java aqui)
* para o desenvolvimento web usamos `vue.js`
* para o mobile usamos `flutter`
* para o client api linguagem de sua preferẽncia


como vamos avaliar ?

* criar um projeto privado no `GitHub` e fornecer acesso para a seguinte conta `robsonoduarte`
* é extremamente necessário ter um `README` explicando no mínimo como rodoar o projeto localmente
* executaremos  em uma `VM` (linux) onde não teremos `nenhum` ambiente configurado, portanto precisaremos de instruções para as configurações
