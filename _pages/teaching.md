---
layout: page
permalink: /teaching/
title: docencia/tfg-tfm
description: Oferta de TFG/TFM, TFG/TFM dirigidos y en dirección, y cursos impartidos.
nav: true
nav_order: 2
---

## Oferta de TFG/TFM

### Desarrollo de técnicas de IA para diagnóstico médico y detección de contaminantes

<details>
<summary>Planteamiento</summary>
<br>
Las técnicas de Inteligencia Artificial (IA) han conseguido que problemas anteriormente irresolubles sean afrontables a día de hoy. Uno de ellos es la estimación de propiedades dieléctricas de materiales no homogéneos a partir de medidas de antena o de sensores.
<br>
En esta temática hay varias opciones disponibles (regularización del problema, fabricación de dispositivos HW, definición de parámetros de modelos de aprendizaje máquina) en función del perfil del interesado.
<br>
<br>
</details>

### Desarrollo de técnicas de IA para identificación de agua o petróleo en terreno desconocido (colaboración con el BSC)

<details>
<summary>Planteamiento</summary>
<br>
Las técnicas de Inteligencia Artificial (IA) han conseguido que problemas anteriormente irresolubles sean afrontables a día de hoy. Uno de ellos es la identificación de reservorios (compuestos por agua, petróleo o gas, por ejemplo) a partir de medidas de antena o de sensores a muy baja frecuencia.
<br>
Fundamentalmente, hay que tratar con el etiquetado de problemas a correr en HPC y el entrenamiento de clasificadores (basados en árboles de decisión o en redes neuronales) en infraestructuras del BSC.
<br><br>
</details>

### Estudio comparativo de lenguajes de programación (python, julia, MATLAB) en un software de elementos finitos

<details>
<summary>Planteamiento</summary>
<br>
El mundo de la programación científica es muy cambiante y cada cierto tiempo salen nuevos actores que dicen que son los más rápidos, o los más eficientes.
<br>
Python lleva muchos años clamando ser el killer language de todos los lenguajes "user-friendly" o fáciles de programar, aunque sus prestaciones no parecen ser muy elevadas. MATLAB es un lenguaje que ha mejorado mucho en los últimos años, especialmente su paradigma de orientación a objetos. Finalmente, julia, con su multiple dispatch, insiste en ser igual de rápido que versiones compiladas (C, Fortran) pero más fácil de aprender.
<br>
El objetivo del TFG es correr una serie de problemas o rutinas y establecer cuál es el mejor para una aplicación de elementos finitos. Para ello, el alumno no empezaría de cero sino que ya hay algunas rutinas programadas en MATLAB que habría que comparar con los nuevos códigos desarrollados.
<br><br>
</details>

### Diseño de pruebas unitarias para una suite de elementos finitos

<details>
<summary>Planteamiento</summary>
<br>
Es muy importante que la programación de nuevas funcionalidades en una librería de software sea retrocompatible: esto es,
que no se pierdan anteriores características por incorporar unas nuevas. Esto es especialmente crítico a la hora de
trabajar en equipo, ya que el trabajo de cada miembro del equipo afecta al de los demás.
<br>
En este proyecto se propone la integración de pruebas unitarias por medio de un gestor de cambios (git) de forma que,
para que se incorporen cambios a una determinada versión de software, sea necesario que se pasen una serie de pruebas
unitarias. Se sugiere experimentar con *GitHub Actions*.
<br>
En función del perfil del alumno se trabajará con diferentes lenguajes de programación, aunque preferiblemente se
usará Fortran, MATLAB, Python o Julia.
<br><br>
</details>

### Procesado en Python de medidas de campo cercano de un sistema de antenas

<details>
<summary>Planteamiento</summary>
<br>
Python se ha erigido en los últimos tiempos como uno de los abanderados del Big Data. Permite trabajar de forma mucho más intuitiva y sencilla con muchos agregados de datos gracias a las librerías panda y NumPy.
<br>
En la actualidad, se dispone de un software "legacy" escrito en Octave que genera unas hojas de Excel que posteriormente se procesan para generar un informe Word. Se busca automatizar todos estos pasos por medio de Python de forma que parsee los ficheros originales (ficheros en texto de 1 GB), lo transforme a un DataFrame y llame a las diferentes librerías (o se reprogramen, en función de la viabilidad del proyecto).
<br><br>
</details>

### Orientación de mallas semi estructuradas en electromagnetismo

<details>
<summary>Planteamiento</summary>
<br>
Para un software de elementos finitos, la orientación de las diferentes aristas de los elementos es clave para hacer el ensamblado de las matrices que surgen al resolver un problema de electromagnetismo. Está demostrado que para geometrías suaves o estructuradas existe una orientación global posible de las aristas que facilita mucho el proceso de ensamblado para hexaedros.
<br>
En este proyecto, el alumno tendrá disponible un código de MATLAB que orienta prismas triangulares de forma satisfactoria en la mayoría de las veces. Se busca optimizar este algoritmo (probablemente con teoría de grafos) para hacerlo más rápido y que funcione en todas las ocasiones. El código se realizará en MATLAB.
<br><br>
</details>

### Alimentación uniforme de diferentes malladores para un software de elementos finitos

<details>
<summary>Planteamiento</summary>
<br>
Un problema electromagnético necesita ser mallado para poder resolverlo de forma aproximada con el método de los elementos finitos. Hay múltiples alternativas en la comunidad científica para llevar a cabo esto: `gmsh`, `CubIt`, `GiD`...
<br>
La idea es desarrollar una librería que coja los diferentes elementos (tanto 2D como 3D) y los alimente con un determinado formato a una librería ya existente en MATLAB de elementos finitos. Hay un prototipo ya desarrollado que habría que unificar y expandir a otros malladores para mejorar el número de problemas que se pueden resolver en la librería.
<br><br>
</details>

### Definición y fabricación de circuitos de alta frecuencia para docencia presencial en laboratorio

<details>
<summary>Planteamiento</summary>
<br>
En este proyecto se busca identificar y fabricar diferentes circuitos de alta frecuencia (adaptadores de impedancia, acopladores híbridos, diplexores...) para su posterior identificación en el laboratorio con equipos de medida.
<br><br>
</details>

***

## TFG/TFM dirigidos

### Plataforma web de simulación remota en un cluster de computación científica

<details>
<summary>PFC en Ingeniería de Telecomunicación</summary>
<br>
Cristina García Muñoz, octubre 2014. 
<br>
Publicación en URSI 2013. 
<br>
Calificación: SOBRESALIENTE 10 (matrícula de honor).
<br><br>
</details>

### Clasificación y detección de contaminantes en datos generados por microondas

<details>
<summary>TFM en Máster Universitario en Inteligencia Artificial Aplicada </summary>
<br>
César Turienzo Forcada, julio 2023. 
<br>
Publicación en URSI 2023. 
<br>
Calificación: SOBRESALIENTE 10 (nominado matrícula de honor).
<br><br>
</details>

### Predicción de resultados de circuitos de alta frecuencia con técnicas de inteligencia artificial

<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación</summary>
<br>
Antonio Rueda Escalona, julio 2023. 
<br>
Publicación en URSI 2023. 
<br>
Calificación: SOBRESALIENTE 10 (matrícula de honor).
<br><br>
</details>

### Creación e investigación de un prototipo para la identificación de materiales en la banda de microondas

<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Pablo Iglesias García, septiembre 2023. 
<br>
Calificación: SOBRESALIENTE 9.1
<br><br>
</details>

### Sonda de monitorización para redes privadas

<details>
<summary>TFM en Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas </summary>
<br>
Marta López Izquierdo, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 10 (nominado matrícula de honor).
<br><br>
</details>

### Comparison between LTE Cat 1, LTE Cat 1 bis and LTE-M cellular technologies

<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Marta López Izquierdo, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 9.5
<br><br>
</details>

### Implementación de un simulador 2D de elementos finitos en Julia

<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Mario Núñez Domínguez, marzo 2024. 
<br>
Publicación en URSI 2024. 
<br>
Calificación: SOBRESALIENTE 9.3
<br><br>
</details>

### Desarrollo de una interfaz para Paraview desde Fortran

<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Macarena Fernández Rodríguez, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 10 (nominada matrícula de honor).
<br><br>
</details>

### Envío de datos por redes IoT para caracterización de materiales a través de microondas

<details>
<summary>TFM en Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas </summary>
<br>
Pablo Iglesias García, septiembre 2024. 
<br>
Calificación: NOTABLE 8.8
<br><br>
</details>

### Implementación de un sensor para la identificación de materiales en la banda de microondas

<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Antonio Javier Ruiz Cascales, septiembre 2024. 
<br>
Calificación: NOTABLE 7.0
<br><br>
</details>

### Avanzando en el diagnóstico médico del futuro: identificación de lesiones cutáneas con radiofrecuencia e IA.

<details>
<summary>TFM en Máster Universitario en Inteligencia Artificial Aplicada </summary>
<br>
Fernando Martín San Bruno, septiembre 2024. 
<br>
Calificación: SOBRESALIENTE 9.4
<br><br>
</details>

### Estudio comparativo de diferentes software de diferenciación automática

<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Alberto López de Lerma del Olmo, septiembre 2024. 
<br>
Calificación: .
<br><br>
</details>

### Design, simulation and development of improvements for material characterization technologies.

<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Carlos de Quinto Cáceres, septiembre 2024. 
<br>
Calificación: .
<br><br>
</details>

***

## TFG/TFM en dirección

### Diseño y fabricación de circuitos de adaptación para uso docente

<details>
<summary>TFG en Grado en Ingeniería de Comunicaciones Móviles y Espaciales </summary>
<br>
Luis María Casla Gárate, febrero 2025. 
<br>
Calificación: .
<br><br>
</details>

### Estudio de los efectos del modelado electromagnético sobre técnicas de inteligencia artificial

<details>
<summary>TFG en Grado en Ingeniería de Comunicaciones Móviles y Espaciales </summary>
<br>
Lucía Diéguez González, febrero 2025. 
<br>
Calificación: .
<br><br>
</details>

### Estudio de técnicas de Inteligencia Artificial para la caracterización de materiales en la banda de microondas

<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Alejandro Fernández-Vegue García-Caro, febrero 2025. 
<br>
Calificación: .
<br><br>
</details>

***

## Cursos en el extranjero

### Computational Electromagnetics: a review and future developments for finite element methods
10 horas en el Politecnico di Torino en mayo de 2023. Financiado por la convocatoria Erasmus+.

### Métodos numéricos en el electromagnetismo computacional
8 horas en la Pontificia Universidad Católica del Perú en mayo de 2023. Financiado por la convocatoria Erasmus+.

***

## Cursos Impartidos

### 2024/2025

<details>
<summary>Asignaturas</summary>
<br>
<h4> Campos Electromagnéticos </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Coordinador, profesor de grupo reducido y prácticas.
<br><br>
<h5> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h5>
Coordinador, profesor de grupo reducido.
<br><br>
<h4> Tecnologías de Alta Frecuencia </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de grupo reducido.
<br><br>
<h4> Dispositivos inalámbricos en IoT </h4> 
<h5> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h5>
Coordinador, profesor de teoría y de prácticas.
<br><br>
<h4> Prácticas en empresa </h4> 
<h5> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h5>
Coordinador.
<br><br>
<h4> Fundamentals on computational electromagnetism applied to communications I </h4>
<h5> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h5>
Profesor de teoría.
<br><br><br><br>
</details>

### 2023/2024

<details>
<summary>Asignaturas</summary>
<br>
<h4> Campos Electromagnéticos </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Coordinador, profesor de grupo reducido y prácticas.
<br><br>
<h5> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h5>
Coordinador, profesor de grupo reducido.
<br><br>
<h4> Tecnologías de Alta Frecuencia </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de grupo reducido.
<br><br>
<h4> Dispositivos inalámbricos en IoT </h4> 
<h5> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h5>
Coordinador, profesor de teoría y de prácticas.
<br><br>
<h4> Fundamentals on computational electromagnetism applied to communications I </h4>
<h5> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h5>
Profesor de teoría.
<br><br><br><br>
</details>

### 2022/2023

<details>
<summary>Asignaturas</summary>
<br>
<h4> Subsistemas de Radiofrecuencia y Antenas </h4>
<h5> Máster Universitario en Ingeniería de Telecomunicación</h5>
Profesor de repaso.
<br><br>
<h4> Campos Electromagnéticos </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de grupo reducido.
<br><br>
<h5> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h5>
Coordinador, profesor de grupo reducido.
<br><br>
<h4> Tecnologías de Alta Frecuencia </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de grupo reducido y responsable de prácticas.
<br><br>
<h4> Dispositivos inalámbricos en IoT </h4> 
<h5> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h5>
Coordinador, profesor de teoría y de prácticas.
<br><br>
<h4> Fundamentals on computational electromagnetism applied  to communications I </h4>
<h5> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h5>
Profesor de teoría.
<br><br><br><br>
</details>

### 2021/2022

<details>
<summary>Asignaturas</summary>
<br>
<h4> Subsistemas de Radiofrecuencia y Antenas </h4> 
<h5> Máster Universitario en Ingeniería de Telecomunicación </h5>
Profesor de repaso y responsable de prácticas.
<br><br>
<h4> Campos Electromagnéticos </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de grupo reducido.
<br><br>
<h5> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h5>
Coordinador, profesor de grupo reducido.
<br><br>
<h4> Tecnologías de Alta Frecuencia </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de grupo reducido y responsable de prácticas.
<br><br>
<h4> Dispositivos inalámbricos en IoT </h4> 
<h5> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h5>
Profesor de teoría y responsable de prácticas.
<br><br>
<h4> Fundamentals on computational electromagnetism applied  to communications I </h4>
<h5> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h5>
Profesor de teoría.
<br><br>
<h4> Fundamentals on computational electromagnetism applied  to communications II </h4>
<h5> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h5>
Profesor de teoría.
<br><br><br><br>
</details>

### 2020/2021

<details>
<summary>Asignaturas</summary>
<br>
<h4> Campos Electromagnéticos </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de grupo reducido.
<br><br>
<h4> Tecnologías de Alta Frecuencia </h4> 
<h5> Grado en Ingeniería de Tecnologías de Telecomunicación. </h5>
Profesor de dos grupos reducidos y responsable de prácticas.
<br><br>
<h4> Dispositivos inalámbricos en IoT </h4> 
<h5> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h5>
Profesor de teoría y responsable de prácticas.
<br><br>
<h4> Fundamentals on computational electromagnetism applied  to communications I </h4>
<h5> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h5>
Profesor de teoría.
<br><br><br><br>
</details>