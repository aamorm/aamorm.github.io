---
layout: page
permalink: /teaching/
title: teaching
description: Oferta de TFG/TFM y cursos impartidos.
nav: true
nav_order: 2
---

## Oferta de TFG/TFM

### Desarrollo de técnicas de IA para diagnóstico médico y detección de contaminantes

Las técnicas de Inteligencia Artificial (IA) han conseguido que problemas anteriormente irresolubles sean afrontables a día de hoy. Uno de ellos es la estimación de propiedades dieléctricas de materiales no homogéneos a partir de medidas de antena o de sensores.

En esta temática hay varias opciones disponibles (regularización del problema, fabricación de dispositivos HW, definición de parámetros de modelos de aprendizaje máquina) en función del perfil del interesado.

### Estudio comparativo de lenguajes de programación (python, julia, MATLAB) en un software de elementos finitos

El mundo de la programación científica es muy cambiante y cada cierto tiempo salen nuevos actores que dicen que son los más rápidos, o los más eficientes.

Python lleva muchos años clamando ser el killer language de todos los lenguajes "user-friendly" o fáciles de programar, aunque sus prestaciones no parecen ser muy elevadas. MATLAB es un lenguaje que ha mejorado mucho en los últimos años, especialmente su paradigma de orientación a objetos. Finalmente, julia, con su multiple dispatch, insiste en ser igual de rápido que versiones compiladas (C, Fortran) pero más fácil de aprender.

El objetivo del TFG es correr una serie de problemas o rutinas y establecer cuál es el mejor para una aplicación de elementos finitos. Para ello, el alumno no empezaría de cero sino que ya hay algunas rutinas programadas en MATLAB que habría que comparar con los nuevos códigos desarrollados.

### Diseño de pruebas unitarias para una suite de elementos finitos
Es muy importante que la programación de nuevas funcionalidades en una librería de software sea retrocompatible: esto es,
que no se pierdan anteriores características por incorporar unas nuevas. Esto es especialmente crítico a la hora de
trabajar en equipo, ya que el trabajo de cada miembro del equipo afecta al de los demás.

En este proyecto se propone la integración de pruebas unitarias por medio de un gestor de cambios (git) de forma que,
para que se incorporen cambios a una determinada versión de software, sea necesario que se pasen una serie de pruebas
unitarias. Se sugiere experimentar con *GitHub Actions*.

En función del perfil del alumno se trabajará con diferentes lenguajes de programación, aunque preferiblemente se
usará Fortran, MATLAB, Python o Julia.

### Procesado en Python de medidas de campo cercano de un sistema de antenas
Python se ha erigido en los últimos tiempos como uno de los abanderados del Big Data. Permite trabajar de forma mucho más intuitiva y sencilla con muchos agregados de datos gracias a las librerías panda y NumPy.

En la actualidad, se dispone de un software "legacy" escrito en Octave que genera unas hojas de Excel que posteriormente se procesan para generar un informe Word. Se busca automatizar todos estos pasos por medio de Python de forma que parsee los ficheros originales (ficheros en texto de 1 GB), lo transforme a un DataFrame y llame a las diferentes librerías (o se reprogramen, en función de la viabilidad del proyecto).

### Orientación de mallas semi estructuradas en electromagnetismo
Para un software de elementos finitos, la orientación de las diferentes aristas de los elementos es clave para hacer el ensamblado de las matrices que surgen al resolver un problema de electromagnetismo. Está demostrado que para geometrías suaves o estructuradas existe una orientación global posible de las aristas que facilita mucho el proceso de ensamblado para hexaedros.

En este proyecto, el alumno tendrá disponible un código de MATLAB que orienta prismas triangulares de forma satisfactoria en la mayoría de las veces. Se busca optimizar este algoritmo (probablemente con teoría de grafos) para hacerlo más rápido y que funcione en todas las ocasiones. El código se realizará en MATLAB.

### Alimentación uniforme de diferentes malladores para un software de elementos finitos
Un problema electromagnético necesita ser mallado para poder resolverlo de forma aproximada con el método de los elementos finitos. Hay múltiples alternativas en la comunidad científica para llevar a cabo esto: `gmsh`, `CubIt`, `GiD`...

La idea es desarrollar una librería que coja los diferentes elementos (tanto 2D como 3D) y los alimente con un determinado formato a una librería ya existente en MATLAB de elementos finitos. Hay un prototipo ya desarrollado que habría que unificar y expandir a otros malladores para mejorar el número de problemas que se pueden resolver en la librería.

## Cursos Impartidos

### 2022/2023
#### Subsistemas de Radiofrecuencia y Antenas
##### Máster Universitario en Ingeniería de Telecomunicación
Profesor de repaso.

#### Campos Electromagnéticos
##### Grado en Ingeniería de Tecnologías de Telecomunicación.
Profesor de grupo reducido.

##### Grado en Ingeniería de Comunicaciones Móviles y Espacio.
Coordinador, profesor de grupo reducido.

#### Tecnologías de Alta Frecuencia
##### Grado en Ingeniería de Tecnologías de Telecomunicación.
Profesor de grupo reducido y responsable de prácticas.

#### Dispositivos inalámbricos en IoT
##### Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas.
Coordinador, profesor de teoría y de prácticas.

#### Fundamentals on computational electromagnetism applied to communications I
##### Máster Universitario en Tecnología Avanzada de Comunicaciones.
Profesor de teoría.

### 2021/2022
#### Subsistemas de Radiofrecuencia y Antenas
##### Máster Universitario en Ingeniería de Telecomunicación
Profesor de repaso y responsable de prácticas.

#### Campos Electromagnéticos
##### Grado en Ingeniería de Tecnologías de Telecomunicación.
Profesor de grupo reducido.

##### Grado en Ingeniería de Comunicaciones Móviles y Espacio.
Coordinador, profesor de grupo reducido.

#### Tecnologías de Alta Frecuencia
##### Grado en Ingeniería de Tecnologías de Telecomunicación.
Profesor de grupo reducido y responsable de prácticas.

#### Dispositivos inalámbricos en IoT
##### Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas.
Profesor de teoría y responsable de prácticas.

#### Fundamentals on computational electromagnetism applied to communications I
##### Máster Universitario en Tecnología Avanzada de Comunicaciones.
Profesor de teoría.

#### Fundamentals on computational electromagnetism applied to communications II
##### Máster Universitario en Tecnología Avanzada de Comunicaciones.
Profesor de teoría.

### 2020/2021

#### Campos Electromagnéticos
##### Grado en Ingeniería de Tecnologías de Telecomunicación.
Profesor de grupo reducido.

#### Tecnologías de Alta Frecuencia
##### Grado en Ingeniería de Tecnologías de Telecomunicación.
Profesor de dos grupos reducidos y responsable de prácticas.

#### Dispositivos inalámbricos en IoT
##### Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas.
Profesor de teoría y responsable de prácticas.

#### Fundamentals on computational electromagnetism applied to communications I
##### Máster Universitario en Tecnología Avanzada de Comunicaciones.
Profesor de teoría.
