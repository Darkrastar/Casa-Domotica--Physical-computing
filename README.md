# CasaDomotica
This project was developed to show the design and simulation of a home automation. 

# Folder structure
```
ProyectoFinal-----------Contains the scenario made in Unity 
ProyectoFinalCF---------It contains the code of the sensors in Arduino, the simulation of the sensors in Proteus and, the extraction and sending of data to ubidots
CasaDómotica.docx.pdf---Contains an article that explains the complete process of the project with images included 
```
Proteus simulates data from the placed sensors, these data are output to Python, through the serial port, which will send to the ubidots and simultaneously, will send them to Unity and in the simulation of the scenario, certain actions are carried out depending on the data sent ( Lights come on, the door closes automatically).

# Versions
```
Python---------------Version 3.8
Proteus--------------Version 8.5 SP0 (Build 22067)
Unity----------------Version 2019.4.0f1
VSPE-----------------Version 6.2.9200.2
Visual Studio Code---Version 1.53.2

Library
ArduinoJson---------Version 6.17.2
ApiClient-----------Version 1.0.3
```


