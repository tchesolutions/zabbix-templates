# Template para OLT Raisecom
### Modelo testado: ISCOM 5508 e 6820
---
Coletas:
* Network interfaces (tráfego, status, etc)
* Alocação de cada PON
* Sinal de Rx da ONU
* Chassis (CPU, temperatura, uptime, etc)
---
Instalação:

* Importar a template
* Add o set de expressões regulares
![regex-raisecom](https://user-images.githubusercontent.com/63215450/151564792-55486301-9b3b-4b0b-bbae-32ab748f0446.jpg)
* Add o filtro de expressões regulares na template de "Network Interfaces"
* ![filtro-raisecom](https://user-images.githubusercontent.com/63215450/151564853-4717e32d-777d-4f92-966c-267072e5c67e.jpg)
