# RedNeuronal-Celsius-a-Fahrenheit

Este código fuente sirve como apoyo para el video de exportación de modelos de Tensorflow a Tensorflow.js

Se trata de un conversor en tiempo real de grados Celsius a Fahrenheit utilizando Tensorflow.js, en base aun modelo entrenado en Python con Tensorflow

# Para probar proyecto en vivo

http://localhost:8000/index.html

# Inicia un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso puedes usar cualquier servidor, pero aquí hay una forma de hacerlo:
- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000

# Uso
Mueve la barra deslizadora de grados celsius, y se mostrará la predicción en grados fahrenheit
