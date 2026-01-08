---
layout: page
permalink: /teaching/
title: teaching/tfg-tfm
description: Oferta de TFG/TFM, TFG/TFM dirigidos y en dirección, y cursos impartidos.
nav: true
nav_order: 2
---

<div class="teaching">

## Oferta de TFG/TFM
{::nomarkdown}
<div class="section" id="sec-oferta">
  <div class="section-toolbar">
    <button type="button" class="btn-small btn-expand" aria-pressed="false">Expand all</button>
    <button type="button" class="btn-small btn-collapse">Collapse all</button>
  </div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Desarrollo de técnicas de IA para diagnóstico médico y detección de contaminantes

{::nomarkdown}
<details>
<summary>Planteamiento</summary>
<br>
Las técnicas de Inteligencia Artificial (IA) han conseguido que problemas anteriormente irresolubles sean afrontables a día de hoy. Uno de ellos es la estimación de propiedades dieléctricas de materiales no homogéneos a partir de medidas de antena o de sensores.
<br>
En esta temática hay varias opciones disponibles (regularización del problema, fabricación de dispositivos HW, definición de parámetros de modelos de aprendizaje máquina) en función del perfil del interesado.
<br>
<br>
</details>
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Desarrollo de técnicas de IA para identificación de agua o petróleo en terreno desconocido (colaboración con el BSC)

{::nomarkdown}
<details>
<summary>Planteamiento</summary>
<br>
Las técnicas de Inteligencia Artificial (IA) han conseguido que problemas anteriormente irresolubles sean afrontables a día de hoy. Uno de ellos es la identificación de reservorios (compuestos por agua, petróleo o gas, por ejemplo) a partir de medidas de antena o de sensores a muy baja frecuencia.
<br>
Fundamentalmente, hay que tratar con el etiquetado de problemas a correr en HPC y el entrenamiento de clasificadores (basados en árboles de decisión o en redes neuronales) en infraestructuras del BSC.
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Estudio comparativo de lenguajes de programación (python, julia, MATLAB) en un software de elementos finitos

{::nomarkdown}
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
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Diseño de pruebas unitarias para una suite de elementos finitos

{::nomarkdown}
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
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Procesado en Python de medidas de campo cercano de un sistema de antenas

{::nomarkdown}
<details>
<summary>Planteamiento</summary>
<br>
Python se ha erigido en los últimos tiempos como uno de los abanderados del Big Data. Permite trabajar de forma mucho más intuitiva y sencilla con muchos agregados de datos gracias a las librerías panda y NumPy.
<br>
En la actualidad, se dispone de un software "legacy" escrito en Octave que genera unas hojas de Excel que posteriormente se procesan para generar un informe Word. Se busca automatizar todos estos pasos por medio de Python de forma que parsee los ficheros originales (ficheros en texto de 1 GB), lo transforme a un DataFrame y llame a las diferentes librerías (o se reprogramen, en función de la viabilidad del proyecto).
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Orientación de mallas semi estructuradas en electromagnetismo

{::nomarkdown}
<details>
<summary>Planteamiento</summary>
<br>
Para un software de elementos finitos, la orientación de las diferentes aristas de los elementos es clave para hacer el ensamblado de las matrices que surgen al resolver un problema de electromagnetismo. Está demostrado que para geometrías suaves o estructuradas existe una orientación global posible de las aristas que facilita mucho el proceso de ensamblado para hexaedros.
<br>
En este proyecto, el alumno tendrá disponible un código de MATLAB que orienta prismas triangulares de forma satisfactoria en la mayoría de las veces. Se busca optimizar este algoritmo (probablemente con teoría de grafos) para hacerlo más rápido y que funcione en todas las ocasiones. El código se realizará en MATLAB.
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Alimentación uniforme de diferentes malladores para un software de elementos finitos

{::nomarkdown}
<details>
<summary>Planteamiento</summary>
<br>
Un problema electromagnético necesita ser mallado para poder resolverlo de forma aproximada con el método de los elementos finitos. Hay múltiples alternativas en la comunidad científica para llevar a cabo esto: `gmsh`, `CubIt`, `GiD`...
<br>
La idea es desarrollar una librería que coja los diferentes elementos (tanto 2D como 3D) y los alimente con un determinado formato a una librería ya existente en MATLAB de elementos finitos. Hay un prototipo ya desarrollado que habría que unificar y expandir a otros malladores para mejorar el número de problemas que se pueden resolver en la librería.
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Desarrollo de un código FEM 2D/3D para la simulación de estructuras SIW

{::nomarkdown}
<details>
<summary>Planteamiento</summary>
<br>
Los circuitos SIW (*Substrate Integrated Waveguide*, por sus siglas en inglés) son circuitos con altas prestaciones en las bandas de radiofrecuencia ya que combinan las ventajas de tecnologías planares (microstrip, stripline) con prestaciones comparables a las de guías de onda tradicionales, lo que las hace especialmente atractivas para aplicaciones satelitales. Sin embargo, son circuitos difíciles de analizar con la precisión necesaria debido al nivel de detalle necesario que introducen las vías que confinan el campo electromagnético.
<br>
En este trabajo, se propone implementar un código FEM de 2D que aproveche la geometría de los circuitos SIW (básicamente, un circuito planar que se extrusiona en el tercer eje) para comparar sus prestaciones con las de simuladores in-house de los que se dispone en el grupo de investigación, adecuados también para este tipo de geometrías (prismas triangulares con diferentes órdenes de aproximación).
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
<div class="teachingDetail">
{:/}

##### Definición y fabricación de circuitos de alta frecuencia para docencia presencial en laboratorio

{::nomarkdown}
<details>
<summary>Planteamiento</summary>
<br>
En este proyecto se busca identificar y fabricar diferentes circuitos de alta frecuencia (adaptadores de impedancia, acopladores híbridos, diplexores...) para su posterior identificación en el laboratorio con equipos de medida.
<br><br>
</details>
{:/}

{::nomarkdown}</div>{:/}

{::nomarkdown}</div>{:/}

## TFM dirigidos

{::nomarkdown}
<div class="section" id="sec-tfm-dirigidos">
  <div class="section-toolbar">
    <button type="button" class="btn-small btn-expand" aria-pressed="false">Expand all</button>
    <button type="button" class="btn-small btn-collapse">Collapse all</button>
  </div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Plataforma web de simulación remota en un cluster de computación científica

{::nomarkdown}
<details>
<summary>Cristina García Muñoz</summary>
<br>
PFC en Ingeniería de Telecomunicació, octubre 2014. 
<br>
Publicación en URSI 2013. 
<br>
Calificación: SOBRESALIENTE 10 (matrícula de honor)
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Clasificación y detección de contaminantes en datos generados por microondas

{::nomarkdown}
<details>
<summary>César Turienzo Forcada</summary>
<br>
TFM en Máster Universitario en Inteligencia Artificial Aplicada, julio 2023. 
<br>
Publicación en URSI 2023. 
<br>
Calificación: SOBRESALIENTE 10
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Creación e investigación de un prototipo para la identificación de materiales en la banda de microondas

{::nomarkdown}
<details>
<summary>Pablo Iglesias García</summary>
<br>
TFM en Máster Universitario en Ingeniería de Telecomunicación, septiembre 2023. 
<br>
Calificación: SOBRESALIENTE 9.1
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Sonda de monitorización para redes privadas

{::nomarkdown}
<details>
<summary>Marta López Izquierdo</summary>
<br>
TFM en Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 10 (nominado matrícula de honor)
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Comparison between LTE Cat 1, LTE Cat 1 bis and LTE-M cellular technologies

{::nomarkdown}
<details>
<summary>Marta López Izquierdo</summary>
<br>
TFM en Máster Universitario en Ingeniería de Telecomunicación, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 9.5
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Envío de datos por redes IoT para caracterización de materiales a través de microondas

{::nomarkdown}
<details>
<summary>Pablo Iglesias García</summary>
<br>
TFM en Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas, septiembre 2024. 
<br>
Calificación: NOTABLE 8.8
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Implementación de un sensor para la identificación de materiales en la banda de microondas

{::nomarkdown}
<details>
<summary>Antonio Javier Ruiz Cascales</summary>
<br>
TFM en Máster Universitario en Ingeniería de Telecomunicación, septiembre 2024. 
<br>
Calificación: NOTABLE 7.0
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Avanzando en el diagnóstico médico del futuro: identificación de lesiones cutáneas con radiofrecuencia e IA.

{::nomarkdown}
<details>
<summary>Fernando Martín San Bruno</summary>
<br>
TFM en Máster Universitario en Inteligencia Artificial Aplicada, septiembre 2024. 
<br>
Calificación: SOBRESALIENTE 9.4
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Estudio de la variabilidad de posición de un material bajo medida con técnicas de Inteligencia Artificial

{::nomarkdown}
<details>
<summary>Antonio Rueda Escalona</summary>
<br>
TFM en Máster Universitario en Ingeniería de Telecomunicación, febrero 2025. 
<br>
Calificación: SOBRESALIENTE 9.5
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Recognizing Emotions in 360-degree Video Communications using Deep Learning Models

{::nomarkdown}
<details>
<summary>Silvia Casino Colom</summary>
<br>
TFM en Máster Universitario en Ingeniería de Telecomunicación, septiembre 2025. 
<br>
Calificación: SOBRESALIENTE 10
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Implementación de un sistema de selección de audio basado en lenguaje natural mediante técnicas de inteligencia artificial

{::nomarkdown}
<details>
<summary>Rubén Ribes Serrano</summary>
<br>
TFM en Máster Universitario en Inteligencia Artificial Aplicada, julio 2025. 
<br>
Calificación: SOBRESALIENTE 9.5
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}</div>{:/}

## TFG dirigidos

{::nomarkdown}
<div class="section" id="sec-tfg-dirigidos">
  <div class="section-toolbar">
    <button type="button" class="btn-small btn-expand" aria-pressed="false">Expand all</button>
    <button type="button" class="btn-small btn-collapse">Collapse all</button>
  </div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Predicción de resultados de circuitos de alta frecuencia con técnicas de inteligencia artificial

{::nomarkdown}
<details>
<summary>Antonio Rueda Escalona</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicació, julio 2023. 
<br>
Publicación en URSI 2023. 
<br>
Calificación: SOBRESALIENTE 10 (matrícula de honor)
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Implementación de un simulador 2D de elementos finitos en Julia

{::nomarkdown}
<details>
<summary>Mario Núñez Domínguez</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, marzo 2024. 
<br>
Publicación en URSI 2024. 
<br>
Calificación: SOBRESALIENTE 9.3
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Desarrollo de una interfaz para Paraview desde Fortran

{::nomarkdown}
<details>
<summary>Macarena Fernández Rodríguez</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 10 (nominada matrícula de honor)
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Estudio comparativo de diferentes software de diferenciación automática

{::nomarkdown}
<details>
<summary>Alberto López de Lerma del Olmo</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, septiembre 2024. 
<br>
Calificación: NOTABLE 8.2
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Design, simulation and development of improvements for material characterization technologies.

{::nomarkdown}
<details>
<summary>Carlos de Quinto Cáceres</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, septiembre 2024. 
<br>
Calificación: SOBRESALIENTE 9.7
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Estudio de técnicas de Inteligencia Artificial para la caracterización de materiales en la banda de microondas

{::nomarkdown}
<details>
<summary>Alejandro Fernández-Vegue García-Caro</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, julio 2025. 
<br>
Calificación: SOBRESALIENTE 9.7 
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Diseño experimental de un array de antenas para comunicaciones con HAPS (High Altitude Platform Station)

{::nomarkdown}
<details>
<summary>Rodrigo Ruiz Bustos</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, julio 2025. 
<br>
Calificación: NOTABLE 8.6 
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Diseño experimental de una antena para generación de imagen por microondas

{::nomarkdown}
<details>
<summary>Miguel Ángel Hurtado Manchado</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, julio 2025. 
<br>
Calificación: NOTABLE 8.6 
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Refactorización de un código de elementos finitos en Julia

{::nomarkdown}
<details>
<summary>Alberto Trufero Martínez</summary>
<br>
TFG en Grado en Ingeniería de Tecnologías de Telecomunicación, septiembre 2025. 
<br>
Calificación: NOTABLE 8.5 
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Estudio de los efectos del modelado electromagnético para la detección no invasiva de lesiones cutáneas.

{::nomarkdown}
<details>
<summary>Lucía Diéguez González</summary>
<br>
TFG en Grado en Ingeniería de Comunicaciones Móviles y Espaciales, septiembre 2025. 
<br>
Calificación: SOBRESALIENTE 9.7 
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}</div>{:/}

## TFG/TFM en dirección

{::nomarkdown}
<div class="section" id="sec-endireccion">
  <div class="section-toolbar">
    <button type="button" class="btn-small btn-expand" aria-pressed="false">Expand all</button>
    <button type="button" class="btn-small btn-collapse">Collapse all</button>
  </div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Diseño y fabricación de circuitos de adaptación para uso docente

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Comunicaciones Móviles y Espaciales </summary>
<br>
Luis María Casla Gárate, septiembre 2026. 
<br>
Calificación: ---
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Estudio de técnicas de detección de tejidos anómalos por medio de simulación electromagnética e inteligencia artificial

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Sara Rodríguez Galán, junio 2026. 
<br>
Calificación: ---
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### Cosimulación de parte activa y pasiva en el desarrollo de sensores activos para caracterización biológica

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Alejandro Thomas Oliva, junio 2026. 
<br>
Calificación: ---
<br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}</div>{:/}

## Cursos internacionales

{::nomarkdown}
<div class="teachingDetail">
{:/}
##### Computational Electromagnetics: a review and future developments for finite element methods
10 horas en el Politecnico di Torino en mayo de 2023. Financiado por la convocatoria Erasmus+.

##### Métodos numéricos en el electromagnetismo computacional
8 horas en la Pontificia Universidad Católica del Perú en mayo de 2023. Financiado por la convocatoria Erasmus+.

##### Artificial Intelligence in Electromagnetics and Antennas
An invited talk about *Fundamentals on Antennas* in European School of Antennas. The slides are [here](/assets/pdf/ai_slides_aamor.pdf).

## Cursos Impartidos

{::nomarkdown}
<div class="section" id="sec-cursos">
  <div class="section-toolbar">
    <button type="button" class="btn-small btn-expand" aria-pressed="false">Expand all</button>
    <button type="button" class="btn-small btn-collapse">Collapse all</button>
  </div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}

##### 2025/2026

{::nomarkdown}
<details>
<summary>Asignaturas</summary>
<br>
<h5> Campos Electromagnéticos </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Coordinador, profesor de grupo reducido y prácticas.
<br><br>
<h6> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h6>
Coordinador, profesor de grupo reducido.
<br><br>
<h5> Tecnologías de Alta Frecuencia </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido.
<br><br>
<h5> Dispositivos inalámbricos en IoT </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Coordinador, profesor de teoría y de prácticas.
<br><br>
<h5> Prácticas en empresa </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Coordinador.
<br><br><br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### 2024/2025

{::nomarkdown}
<details>
<summary>Asignaturas</summary>
<br>
<h5> Campos Electromagnéticos </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Coordinador, profesor de grupo reducido y prácticas.
<br><br>
<h6> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h6>
Coordinador, profesor de grupo reducido.
<br><br>
<h5> Tecnologías de Alta Frecuencia </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido.
<br><br>
<h5> Dispositivos inalámbricos en IoT </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Coordinador, profesor de teoría y de prácticas.
<br><br>
<h5> Prácticas en empresa </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Coordinador.
<br><br>
<h5> Fundamentals on computational electromagnetism applied to communications I </h5>
<h6> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h6>
Profesor de teoría.
<br><br><br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### 2023/2024

{::nomarkdown}
<details>
<summary>Asignaturas</summary>
<br>
<h5> Campos Electromagnéticos </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Coordinador, profesor de grupo reducido y prácticas.
<br><br>
<h6> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h6>
Coordinador, profesor de grupo reducido.
<br><br>
<h5> Tecnologías de Alta Frecuencia </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido.
<br><br>
<h5> Dispositivos inalámbricos en IoT </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Coordinador, profesor de teoría y de prácticas.
<br><br>
<h5> Fundamentals on computational electromagnetism applied to communications I </h5>
<h6> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h6>
Profesor de teoría.
<br><br><br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### 2022/2023

{::nomarkdown}
<details>
<summary>Asignaturas</summary>
<br>
<h5> Subsistemas de Radiofrecuencia y Antenas </h5>
<h6> Máster Universitario en Ingeniería de Telecomunicación</h6>
Profesor de repaso.
<br><br>
<h5> Campos Electromagnéticos </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido.
<br><br>
<h6> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h6>
Coordinador, profesor de grupo reducido.
<br><br>
<h5> Tecnologías de Alta Frecuencia </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido y responsable de prácticas.
<br><br>
<h5> Dispositivos inalámbricos en IoT </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Coordinador, profesor de teoría y de prácticas.
<br><br>
<h5> Fundamentals on computational electromagnetism applied  to communications I </h5>
<h6> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h6>
Profesor de teoría.
<br><br><br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### 2021/2022

{::nomarkdown}
<details>
<summary>Asignaturas</summary>
<br>
<h5> Subsistemas de Radiofrecuencia y Antenas </h5> 
<h6> Máster Universitario en Ingeniería de Telecomunicación </h6>
Profesor de repaso y responsable de prácticas.
<br><br>
<h5> Campos Electromagnéticos </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido.
<br><br>
<h6> Grado en Ingeniería de Comunicaciones Móviles y Espacio. </h6>
Coordinador, profesor de grupo reducido.
<br><br>
<h5> Tecnologías de Alta Frecuencia </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido y responsable de prácticas.
<br><br>
<h5> Dispositivos inalámbricos en IoT </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Profesor de teoría y responsable de prácticas.
<br><br>
<h5> Fundamentals on computational electromagnetism applied  to communications I </h5>
<h6> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h6>
Profesor de teoría.
<br><br>
<h5> Fundamentals on computational electromagnetism applied  to communications II </h5>
<h6> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h6>
Profesor de teoría.
<br><br><br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
<div class="teachingDetail">
{:/}
{::nomarkdown}
<div class="teachingDetail">
{:/}

##### 2020/2021

{::nomarkdown}
<details>
<summary>Asignaturas</summary>
<br>
<h5> Campos Electromagnéticos </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de grupo reducido.
<br><br>
<h5> Tecnologías de Alta Frecuencia </h5> 
<h6> Grado en Ingeniería de Tecnologías de Telecomunicación. </h6>
Profesor de dos grupos reducidos y responsable de prácticas.
<br><br>
<h5> Dispositivos inalámbricos en IoT </h5> 
<h6> Máster Universitario en Internet de las Cosas:  Tecnologías Aplicadas. </h6>
Profesor de teoría y responsable de prácticas.
<br><br>
<h5> Fundamentals on computational electromagnetism applied  to communications I </h5>
<h6> Máster Universitario en Tecnología Avanzada de  Comunicaciones. </h6>
Profesor de teoría.
<br><br><br><br>
</details>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}
</div>
{:/}

{::nomarkdown}</div>{:/}

{::nomarkdown}</div>{:/}

{::nomarkdown}
<script>
document.addEventListener('DOMContentLoaded', function () {
  // Un toolbar por cada sección (Oferta, Dirigidos, Cursos, ...)
  document.querySelectorAll('.teaching .section').forEach(section => {
    const btnExpand   = section.querySelector('.btn-expand');
    const btnCollapse = section.querySelector('.btn-collapse');
    if (!btnExpand || !btnCollapse) return;

    const detailsIn = () => Array.from(section.querySelectorAll('details'));

    function updateState() {
      const ds = detailsIn();
      const openCount = ds.filter(d => d.open).length;
      const allOpen = ds.length > 0 && openCount === ds.length;
      btnExpand.setAttribute('aria-pressed', allOpen ? 'true' : 'false');
    }

    function setAll(open) {
      detailsIn().forEach(d => { d.open = !!open; });
      updateState();
    }

    btnExpand.addEventListener('click', () => setAll(true));
    btnCollapse.addEventListener('click', () => setAll(false));

    // Si el usuario abre/cierra manualmente, recalculamos el estado del botón
    section.addEventListener('toggle', (e) => {
      if (e.target.tagName !== 'DETAILS') return;
      updateState();
    }, true);

    updateState();
  });
});
</script>
{:/}
