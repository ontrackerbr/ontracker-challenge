# ontracker-challenge v0.0.1

Dado que a `Ontracker` é uma empresa de tecnologia em `IOT` fornecendo plataformas para monitoramento, rastreamento, gestão de frotas, gestão de telemetria... o nosso desafio aqui para vc q está afim de fazer parte da nossa equipe é:

Hoje temos diversos tipos de dipostivos em campo transmitindo dados usando a internet no protocolo `TCP/UDP`. O formato dos dados transmitidos podem variar de dipositivo para dispositvo por exemplo:

##### Formato de Dados do Dispotivo X:
```
+RESP:GTFRI,860599002977247,-46.552865,-23.572365,20220211042233
```
onde temos o seguinte layout:

```
HEADER,DEVICE_ID,LAT,LNG,DATE_TIME
```


##### Formato de Dados do Dispotivo Y:
```
ST300STT;205620351;20190718;07:00:11;-23.572467;-46.552977
```
onde temos o seguinte layout:
```
HEADER,DEVICE_ID,DATE,HOUR,LAT,LNG
```


