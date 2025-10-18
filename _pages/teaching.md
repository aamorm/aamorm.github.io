---
layout: page
permalink: /teaching/
title: docencia/tfg-tfm
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


## TFG/TFM dirigidos

{::nomarkdown}
<div class="section" id="sec-dirigidos">
  <div class="section-toolbar">
    <button type="button" class="btn-small btn-expand" aria-pressed="false">Expand all</button>
    <button type="button" class="btn-small btn-collapse">Collapse all</button>
  </div>
{:/}

##### Plataforma web de simulación remota en un cluster de computación científica

{::nomarkdown}
<details>
<summary>PFC en Ingeniería de Telecomunicación</summary>
<br>
Cristina García Muñoz, octubre 2014. 
<br>
Publicación en URSI 2013. 
<br>
Calificación: SOBRESALIENTE 10 (matrícula de honor)
<br><br>
</details>
{:/}

##### Clasificación y detección de contaminantes en datos generados por microondas

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Inteligencia Artificial Aplicada </summary>
<br>
César Turienzo Forcada, julio 2023. 
<br>
Publicación en URSI 2023. 
<br>
Calificación: SOBRESALIENTE 10
<br><br>
</details>
{:/}

##### Predicción de resultados de circuitos de alta frecuencia con técnicas de inteligencia artificial

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación</summary>
<br>
Antonio Rueda Escalona, julio 2023. 
<br>
Publicación en URSI 2023. 
<br>
Calificación: SOBRESALIENTE 10 (matrícula de honor)
<br><br>
</details>
{:/}

##### Creación e investigación de un prototipo para la identificación de materiales en la banda de microondas

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Pablo Iglesias García, septiembre 2023. 
<br>
Calificación: SOBRESALIENTE 9.1
<br><br>
</details>
{:/}

##### Sonda de monitorización para redes privadas

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas </summary>
<br>
Marta López Izquierdo, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 10 (nominado matrícula de honor)
<br><br>
</details>
{:/}

##### Comparison between LTE Cat 1, LTE Cat 1 bis and LTE-M cellular technologies

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Marta López Izquierdo, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 9.5
<br><br>
</details>
{:/}

##### Implementación de un simulador 2D de elementos finitos en Julia

{::nomarkdown}
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
{:/}

##### Desarrollo de una interfaz para Paraview desde Fortran

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Macarena Fernández Rodríguez, marzo 2024. 
<br>
Calificación: SOBRESALIENTE 10 (nominada matrícula de honor)
<br><br>
</details>
{:/}

##### Envío de datos por redes IoT para caracterización de materiales a través de microondas

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Internet de las Cosas: Tecnologías Aplicadas </summary>
<br>
Pablo Iglesias García, septiembre 2024. 
<br>
Calificación: NOTABLE 8.8
<br><br>
</details>
{:/}

##### Implementación de un sensor para la identificación de materiales en la banda de microondas

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Antonio Javier Ruiz Cascales, septiembre 2024. 
<br>
Calificación: NOTABLE 7.0
<br><br>
</details>
{:/}

##### Avanzando en el diagnóstico médico del futuro: identificación de lesiones cutáneas con radiofrecuencia e IA.

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Inteligencia Artificial Aplicada </summary>
<br>
Fernando Martín San Bruno, septiembre 2024. 
<br>
Calificación: SOBRESALIENTE 9.4
<br><br>
</details>
{:/}

##### Estudio comparativo de diferentes software de diferenciación automática

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Alberto López de Lerma del Olmo, septiembre 2024. 
<br>
Calificación: NOTABLE 8.2
<br><br>
</details>
{:/}

##### Design, simulation and development of improvements for material characterization technologies.

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Carlos de Quinto Cáceres, septiembre 2024. 
<br>
Calificación: SOBRESALIENTE 9.7
<br><br>
</details>
{:/}

##### Estudio de la variabilidad de posición de un material bajo medida con técnicas de Inteligencia Artificial

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Antonio Rueda Escalona, febrero 2025. 
<br>
Calificación: SOBRESALIENTE 9.5
<br><br>
</details>
{:/}

##### Estudio de técnicas de Inteligencia Artificial para la caracterización de materiales en la banda de microondas

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Alejandro Fernández-Vegue García-Caro, julio 2025. 
<br>
Calificación: SOBRESALIENTE 9.7 
<br><br>
</details>
{:/}

##### Diseño experimental de un array de antenas para comunicaciones con HAPS (High Altitude Platform Station)

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Rodrigo Ruiz Bustos, julio 2025. 
<br>
Calificación: NOTABLE 8.6 
<br><br>
</details>
{:/}

##### Diseño experimental de una antena para generación de imagen por microondas

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Miguel Ángel Hurtado Manchado, julio 2025. 
<br>
Calificación: NOTABLE 8.6 
<br><br>
</details>
{:/}

##### Recognizing Emotions in 360-degree Video Communications using Deep Learning Models

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Ingeniería de Telecomunicación </summary>
<br>
Silvia Casino Colom, septiembre 2025. 
<br>
Calificación: SOBRESALIENTE 10
<br><br>
</details>
{:/}

##### Implementación de un sistema de selección de audio basado en lenguaje natural mediante técnicas de inteligencia artificial

{::nomarkdown}
<details>
<summary>TFM en Máster Universitario en Inteligencia Artificial Aplicada </summary>
<br>
Rubén Ribes Serrano, julio 2025. 
<br>
Calificación: SOBRESALIENTE 9.5
<br><br>
</details>
{:/}

##### Refactorización de un código de elementos finitos en Julia

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Tecnologías de Telecomunicación </summary>
<br>
Alberto Trufero Martínez, septiembre 2025. 
<br>
Calificación: NOTABLE 8.5 
<br><br>
</details>
{:/}

##### Estudio de los efectos del modelado electromagnético para la detección no invasiva de lesiones cutáneas.

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Comunicaciones Móviles y Espaciales </summary>
<br>
Lucía Diéguez González, septiembre 2025. 
<br>
Calificación: SOBRESALIENTE 9.7 
<br><br>
</details>
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

##### Diseño y fabricación de circuitos de adaptación para uso docente

{::nomarkdown}
<details>
<summary>TFG en Grado en Ingeniería de Comunicaciones Móviles y Espaciales </summary>
<br>
Luis María Casla Gárate, septiembre 2025. 
<br>
Calificación: ---
<br><br>
</details>
{:/}

{::nomarkdown}</div>{:/}

## Cursos en el extranjero

##### Computational Electromagnetics: a review and future developments for finite element methods
10 horas en el Politecnico di Torino en mayo de 2023. Financiado por la convocatoria Erasmus+.

##### Métodos numéricos en el electromagnetismo computacional
8 horas en la Pontificia Universidad Católica del Perú en mayo de 2023. Financiado por la convocatoria Erasmus+.

## Cursos Impartidos

{::nomarkdown}
<div class="section" id="sec-cursos">
  <div class="section-toolbar">
    <button type="button" class="btn-small btn-expand" aria-pressed="false">Expand all</button>
    <button type="button" class="btn-small btn-collapse">Collapse all</button>
  </div>
{:/}

##### 2025/2026

{::nomarkdown}
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
<br><br><br><br>
</details>
{:/}

##### 2024/2025

{::nomarkdown}
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
{:/}

##### 2023/2024

{::nomarkdown}
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
{:/}

##### 2022/2023

{::nomarkdown}
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
{:/}

##### 2021/2022

{::nomarkdown}
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
{:/}

##### 2020/2021

{::nomarkdown}
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
{:/}

{::nomarkdown}</div>{:/}

{::nomarkdown}</div>{:/}

{::nomarkdown}
<style>
/* Toolbar y botones */
.teaching .section-toolbar{
  display:flex; gap:.5rem; justify-content:flex-end; margin:.5rem 0 1rem;
}
.teaching .btn-small{
  font:inherit; line-height:1; padding:.35rem .6rem;
  border:1px solid var(--global-divider-color);
  background:var(--global-card-bg-color);
  color:var(--global-text-color);
  border-radius:.35rem; cursor:pointer;
}
.teaching .btn-small:hover{
  border-color:var(--global-theme-color); color:var(--global-theme-color);
}
.teaching .section.all-expanded .btn-expand{
  border-color:var(--global-theme-color); color:var(--global-theme-color);
}

/* Details y comportamiento “todo expandido” por sección */
.teaching details{ border-top:1px solid var(--global-divider-color); padding-top:.5rem; }
.teaching summary{ cursor:pointer; list-style:none; }
.teaching summary::-webkit-details-marker{ display:none; }
.teaching summary::after{ content:"▸"; margin-left:.5rem; transition:transform .2s; display:inline-block; }
.teaching details[open] > summary::after{ transform:rotate(90deg); }

/* En modo all-expanded de UNA sección, escondemos summaries */
.teaching .section.all-expanded details > summary{ display:none; }
.teaching .section.all-expanded details{ padding-top:.25rem; }
</style>
{:/}

{::nomarkdown}
<script>
document.addEventListener('DOMContentLoaded', function () {
  // Repite este bloque para cada sección con toolbar (o selecciona todas si tienes varias)
  document.querySelectorAll('.section').forEach(section => {
    const btnExpand   = section.querySelector('.btn-expand');
    const btnCollapse = section.querySelector('.btn-collapse');
    if (!btnExpand || !btnCollapse) return;

    const detailsIn = () => Array.from(section.querySelectorAll('details'));

    function setAll(open) {
      detailsIn().forEach(d => d.open = !!open);
      // siempre ocultamos los summaries en ambos estados
      section.classList.add('hide-summaries');
      // marca visual de "todo abierto"
      section.classList.toggle('all-expanded', !!open);
      // aria-pressed del botón expand
      btnExpand.setAttribute('aria-pressed', open ? 'true' : 'false');
    }

    // Al hacer Expand all: abre todo y oculta summaries
    btnExpand.addEventListener('click', () => setAll(true));

    // Al hacer Collapse all: cierra todo y oculta summaries (quedan sólo H3)
    btnCollapse.addEventListener('click', () => setAll(false));

    // Si el usuario interactúa manualmente con un <details>, salimos de los estados “globales”
    section.addEventListener('toggle', (e) => {
      if (e.target.tagName !== 'DETAILS') return;
      const det = detailsIn();
      const allOpen = det.length > 0 && det.every(d => d.open);
      const allClosed = det.length > 0 && det.every(d => !d.open);

      // si está todo abierto/cerrado, mantenemos hide-summaries;
      // si hay mezcla (estado manual), mostramos summaries otra vez
      if (allOpen) {
        section.classList.add('hide-summaries', 'all-expanded');
        btnExpand.setAttribute('aria-pressed', 'true');
      } else if (allClosed) {
        section.classList.add('hide-summaries');
        section.classList.remove('all-expanded');
        btnExpand.setAttribute('aria-pressed', 'false');
      } else {
        section.classList.remove('hide-summaries', 'all-expanded');
        btnExpand.setAttribute('aria-pressed', 'false');
      }
    }, true);

    // Estado inicial: colapsado y sin summaries (sólo títulos) si quieres; si no, comenta la línea:
    // setAll(false);
  });
});
</script>
{:/}
