## Consigna

El ex�men est� compuesto por dos aplicaciones, un backend escrito en NodeJS el cual expondr�
una API REST para la interacci�n con la aplicaci�n frontend.

**Ejercicio 1: API Rest NodeJS**
Este punto consiste en armar un API REST en Node.js. El mismo ser� utilizado en el ejercicio 2.
La funcionalidad de listado y filtrado de hoteles debe estar soportada por la API y
consumida en la aplicaci�n cliente.
A la hora de dise�ar la estructura de la aplicaci�n, tener en cuenta factores como
escalabilidad, reutilizaci�n y separaci�n de responsabilidades.
Uso de configuraciones para ajustar como se ejecuta la aplicaci�n en entornos productivos
y de desarrollo.

**Ejercicio 2: Frontend**
Maquetar una p�gina de resultado de hoteles, ver im�genes en el repo (solo mobile y desktop).
Consumir la API desarrollada en el ejercicio anterior, implementando las funcionalidades
necesarias para listar y filtar los hoteles.
Utilizar alguna librer�a o framework guiado por componentes ( AngularJS o Angular).
Utilizar alg�n package manager (npm, bower) para manejar dependencias externas.
Utilizar una grilla responsive o similar para el maquetado.
Optimizar todos los recursos para entornos productivos, (minificar, ofuscar, etc).

## Objetivo Maquetaci�n

**Desktop**

![alt text](https://github.com/tebiikun/almundo/blob/master/designs/desktop.png)

**Mobile**

![alt text](https://github.com/tebiikun/almundo/blob/master/designs/mobile.png)

## Build

**npm install**

**npm start**

## Server

http://localhost:3000/

## Demo

https://almundo.herokuapp.com/

## Comentarios

* La aplicacion se automatiza con Gulp para minificar, ofuscar, concatenar, etc
* Los datos son est�ticos tomados del json brindado
* Hay algunas im�genes (pocas) que no se visualizan por problemas en el archivo
* No se est� utilizando ninguna BD
