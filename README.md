# CAMUNDA

## General

Digitization of matriculation process of the Technische Hochschule Brandenburg

(This repository hold the files for the Camunda Engine)

![](https://i.ibb.co/qdZgG3S/Architektur.jpg)

![](https://i.ibb.co/xfNzQcG/Immatrikulationsprozess.jpg)
 
### Links to releated Gits

| Plugin | README |
| ------ | ------ |
| Frontend | [github.com/pvb89/imma-frontend][frontend] |
| Backend | [github.com/pvb89/imma-backend][backend] |

### Version information
| Purpose | Tool  | Version |
| ------ | ------ | ------ |
| Frontend | VueJS | 2.6.11 |
| Backend | Node | 13.0.1 |
| Database | MySQL | 8.0.19 |
| Process Automation | Camunda Engine | 7.12.0 |
| DMS | Codia D3 | Cloud Product |

## Deploy:

#### Download and start Camunda Engine

Download the Engine from the [Camunda Website][camundaDownload] and follow the instructions to start it

#### Deploy BPMN, DMN and Form´s to Camunda Engine
To deploy the matriculation process you can use the implemented batch Script
```
bash upload.bat
```

#### Open Webinterface
Open the [Camunda Interface][camundaLogin] and use the follow credentials
```
Username: demo
Password: demo
```

#### Ports
```
Frontend: 3000
Server: 4000
Camunda: 8080
```

 [frontend]: <www.github.com/pvb89/imma-frontend>
 [backend]: <www.github.com/pvb89/imma-backend>
 [camundaLogin]: <http://localhost:8080/camunda-welcome/index.html>
 [camundaDownload]: <https://camunda.com/download/>
