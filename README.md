# Clasificador de Señales
Este trabajo se ha centrado en el estudio de uno de los módulos de la conducción autónoma, la predicción de señales de 
tráfico. Para ello se ha desarrollado una aplicación que permita detectar y clasificar señales de tráfico en tiempo real mediante 
el uso de visión por computador. La aplicación usando entrada por video y una red neuronal previamente entrenada es capaz 
de generar salidas prediciendo la señal que se muestra en la imagen.
Para ello, a lo largo del proyecto, se han entrenado redes neuronales con características cambiantes, para poder aprender 
sobre su comportamiento. Extrayendo conclusiones y resultados sobre los datos extraídos de las redes neuronales 
entrenadas, ha permitido generar un modelo sólido funcional que realiza predicciones en tiempo real.

This work has focused on the study of one of the modules of autonomous driving, traffic sign prediction. To this end, an  application has been developed to detect and classify traffic signs in real time using computer vision. The application using video input and a previously trained neural network is able to generate outputs predicting the signal shown in the image. To this end, throughout the project, neural networks with changing characteristics have been trained in order to learn about their  behaviour. By extracting conclusions and results from the data extracted from the trained neural networks, it has been possible  to generate a solid functional model that makes predictions in real time.

## Aplicación Móvil
Para ejecutar la aplicación en el móvil se tienen que seguir los siguientes pasos:
* Descargar repositorio en local
* Entrar a la carpeta Codigo
* Entrar a la carpeta App
* Abrir cmd en la carpeta App (Para ello escribir cmd en el buscador de carpetas y presionar enter)
* Ejecutar el siguiente comando: *python -m http.server puerto*, substituir puerto por el valor desado, ej.4200. Por lo tanto el comando quedaria *python -m http.server 4200*
* Abrir el ejecutable ngrok
* Ejecutar el siguiente comando: *ngrok.exe http puerto*, substituir puerto por el valor desado, ej.4200. Por lo tanto el comando quedaria *ngrok.exe http 4200*
* En el dispositivo móvil, abrir cuanquier buscador y abrir url que indica forwarding. *Ejemplo: https://6cd4-80-174-219-216.eu.ngrok.io*
* En el caso de abrir la aplicación y no obtener cargar las imagenes de predicción, cerrar el navegador y volver a abrir. Repetir este ultimo paso las veces que sean necesarias.  

## Python
Para ejecutar el codigo, se tienen que seguir los siguientes pasos:
* Descargar repositorio en local
* Descargar todas las bases de datos del documento .txt *Descargar bases de datos*
* Guardarlas los archivos .zip en local en la carpeta donde esta el documento .txt previamiento mencionado
* Descomprimir todas las bases de datos
* Abrir jupyterNotebook, en el caso de no estar instalado, se debe instalar
* Abrir archivo que se desea ejectuar
* Clicar en Kernel => Restart and Run All
