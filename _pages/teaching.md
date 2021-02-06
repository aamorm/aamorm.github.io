---
layout: page
permalink: /teaching/
title: teaching
description: Oferta de trabajos personalizados e impartición de cursos.
nav: true
---

## Oferta de TFG/TFM

### Simulación de sistemas IoT con métodos de descomposición de dominios

Basado en un código MATLAB de elementos finitos, la idea básica está en aplicar la teoría de descomposición de dominios a la simulación de diferentes antenas de radiofrecuencia en el mismo escenario.

Se necesitan competencias de programación (orientada a objetos) y de radiofrecuencia.

### Estudio comparativo de lenguajes de programación (python, julia, MATLAB) en un software de elementos finitos

El mundo de la programación científica es muy cambiante y cada cierto tiempo salen nuevos actores que dicen que son los más rápidos, o los más eficientes.

Python lleva muchos años clamando ser el killer language de todos los lenguajes "user-friendly" o fáciles de programar, aunque sus prestaciones no parecen ser muy elevadas. MATLAB es un lenguaje que ha mejorado mucho en los últimos años, especialmente su paradigma de orientación a objetos. Finalmente, julia, con su multiple dispatch, insiste en ser igual de rápido que versiones compiladas (C, FORTRAN) pero más fácil de aprender.

El objetivo del TFG es correr una serie de problemas o rutinas y establecer cuál es el mejor para una aplicación de elementos finitos. Para ello, el alumno no empezaría de cero sino que ya hay algunas rutinas programadas en MATLAB que habría que comparar con los nuevos códigos desarrollados.


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

<!-- 
For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->
