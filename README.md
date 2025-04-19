<h3 align="center">Universidad Peruana de Ciencias Aplicadas - Ingeniería de Software - 2025-10</h3>
<div align="center">
  <img width=140 src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"/>
</div>
<h3 align="center">1ASI0572 - Desarrollo de Soluciones IOT</h3>
<h3 align="center">NRC: 2941</h3>
<h3 align="center">Profesor: Leon Baca, Marco Antonio</h3>
<h1 align="center">Informe de Trabajo Final</h1>
<h3 align="center">Startup: Integradis</h3>
<h3 align="center">Producto: Greenhouse</h3>

<table align="center" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Código</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Astuyauri Calderon, Jherson David</td>
      <td>U202218451</td>
    </tr>
    <tr>
    <tr>
      <td>Espinoza Rodríguez, Nicolás Antonio</td>
      <td>U202110278</td>
    </tr>
    <tr>
      <td>Galavis Du Bois, Alan Enrique</td>
      <td>U202110223</td>
    </tr>
    <tr>
      <td>Seminario Garbin, Carlo Luca</td>
      <td>U20211A475</td>
    </tr>
    <tr>
      <td>Soto Kong Requena, Andrés Eduardo</td>
      <td>U202116113</td>
    </tr>
  </tbody>
</table>

<h3 align="center">Abril del 2025</h3>

# Registro de versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| ------- | ----- | ----- | --------------------------- |
| 1.0     |       |       |                             |

# Project Report Collaboration Insights

### TB1

| Integrante                          | Tareas Asignadas |
| ----------------------------------- | ---------------- |
| Astuyauri Calderon, Jherson David    | <p> - Desarrollo del Capítulo II: Requirements Elicitation & Analysis. </p> <p> - Student Outcome del TB1. </p>          |
| Espinoza Rodríguez, Nicolás Antonio |                  |
| Galavis Du Bois, Alan Enrique       |                  |
| Seminario Garbin, Carlo Luca        |                  |
| Soto Kong Requena, Andrés Eduardo   |                  |

# Contenido
1. [**Capítulo I: Introducción.**](#1.) <br>
1.1. [Startup Profile.](#1.1.) <br>
1.1.1. [Descripción del startup.](#1.1.1.)<br>
1.1.2.[Perfiles de los integrantes del equipo.](#1.1.2.)<br>
1.2. [Solution Profile.](#1.2.)<br>
1.2.1. [Antecedentes y Problemática.](#1.2.1.)<br>
1.2.2. [Lean UX Process.](#1.2.2.)<br>
1.2.2.1. [Lean UX Problem Statements.](#1.2.2.1.)<br>
1.2.2.2. [Lean UX Assumptions.](#1.2.2.2.)<br>
1.2.2.3. [Lean UX Hypothesis Statements.](#1.2.2.3.)<br>
1.2.2.4. [Lean UX Canvas.](#1.2.2.4.)<br>
1.3. [Segmentos objetivo.](#1.3.)<br>
2. [**Capítulo II: Requirements Elicitation & Analysis.**](#2.)<br>
2.1. [Competidores.](#2.1.)<br>
2.1.1. [Análisis competitivo.](#2.1.1.)<br>
2.1.2. [Estrategias y tácticas frente a competidores.](#2.1.2.)<br>
2.2. [Entrevistas.](#2.2.)<br>
2.2.1. [Diseño de entrevistas.](#2.2.1.)<br>
2.2.2. [Registro de entrevistas.](#2.2.2.)<br>
2.2.3. [Análisis de entrevistas.](#2.2.3.)<br>
2.3. [Needfinding.](#2.3.)<br>
2.3.1. [User Personas.](#2.3.1.)<br>
2.3.2. [User Task Matrix.](#2.3.2.)<br>
2.3.3. [User Journey Mapping.](#2.3.3.)<br>
2.3.4. [Empathy Mapping.](#2.3.4.)<br>
2.3.5. [As-is Scenario Mapping.](#2.3.5.)<br>
2.4. [Ubiqutous Language.](#2.4.)<br>
3. [**Capítulo III: Requirements Specification.**](#3.)<br>
3.1. [To-Be Scenario Mapping.](#3.1.)<br>
3.2. [User Stories.](#3.2.)<br>
3.3. [Impact Mapping.](#3.3.)<br>
3.4. [Product Backlog.](#3.4.)<br>
4. [**Capítulo IV: Solution Software Design.**](#4.)<br>
4.1. [**Strategic-Level Domain-Driven Design.**](#4.1.)<br>
4.1.1. [**EventStorming.**](#4.1.1.)<br>
4.1.1.1. [**Candidate Context Discovery.**](#4.1.1.1.)<br>
4.1.1.2. [**Domain Message Flows Modeling.**](#4.1.1.2.)<br>
4.1.1.3. [**Bounded Context Canvases.**](#4.1.1.3.)<br>
4.1.2. [**Context Mapping.**](#4.1.2.)<br>
4.1.3. [**Software Architecture.**](#4.1.3.)<br>
4.1.3.1. [**Software Architecture System Landscape Diagram.**](#4.1.3.1.)<br>
4.1.3.2. [**Software Architecture Context Level Diagrams.**](#4.1.3.2.)<br>
4.1.3.3. [**Software Architecture Container Level Diagrams.**](#4.1.3.3.)<br>
4.1.3.4. [**Software Architecture Deployment Diagrams.**](#4.1.3.4.)<br>
4.2. [**Tactical-Level Domain-Driven Design.**](#4.2.)<br>
4.2.1. [**Bounded Context: **](#4.2.1.)<br>
4.2.1.1. [**Domain Layer.**](#4.2.1.1.)<br>
4.2.1.2. [**Interface Layer.**](#4.2.1.2.)<br>
4.2.1.3. [**Application Layer.**](#4.2.1.3.)<br>
4.2.1.4. [**Infrastructure Layer.**](#4.2.1.4.)<br>
4.2.1.5. [**Bounded Context Software Architecture Component Level Diagrams.**](#4.2.1.5.)<br>
4.2.1.6. [**Bounded Context Software Architecture Code Level Diagrams.**](#4.2.1.6.)<br>
4.2.1.6.1. [**Bounded Context Domain Layer Class Diagrams.**](#4.2.1.6.1.)<br>
4.2.1.6.2. [**Bounded Context Database Design Diagram.**](#4.2.1.6.1.)<br>
5. [**Capítulo V: Solution UI/UX Design.**](#5.)<br>
5.1. [Style Guidelines.](#4.1.)<br>
5.1.1. [General Style Guidelines.](#4.1.1.)<br>
5.1.2. [Web, Mibuke and IoT Style Guidelines.](#4.1.2.)<br>
5.2. [Information Architecture.](#4.2.)<br>
5.2.1. [Organization Systems.](#4.2.1.)<br>
5.2.2. [Labeling Systems.](#4.2.2.)<br>
5.2.3. [SEO Tags and Meta Tags](#4.2.3.)<br>
5.2.4. [Searching Systems.](#4.2.4.)<br>
5.2.5. [Navigation Systems.](#4.2.5.)<br>
5.3. [Landing Page UI Design.](#4.3.)<br>
5.3.1. [Landing Page Wireframe.](#4.3.1.)<br>
5.3.2. [Landing Page Mock-up.](#4.3.2.)<br>
5.4. [Applications UX/UI Design.](#4.4.)<br>
5.4.1. [Applications Wireframes.](#4.4.1.)<br>
5.4.2. [Applications Wireflow Diagrams.](#4.4.2.)<br>
5.4.3. [Applications Mock-ups.](#4.4.3.)<br>
5.4.4. [Applications User Flow Diagrams.](#4.4.4.)<br>
5.5. [Applications Prototyping.](#4.5.)<br>

# Student Outcome

<table cellpadding="5" cellspacing="0">
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>
      <td>
      <b>Astuyauri Calderón, Jherson David:</b>
      <br/>
      <i>TB1: Lideré la elaboración del Capítulo II: Requirements Elicitation & Analysis, incluyendo el análisis competitivo, diseño de entrevistas y herramientas UX como User Personas y Empathy Mapping. Guié al equipo hacia decisiones centradas en el usuario,   fomentando el liderazgo compartido y el consenso en todo momento.</i><br/><br/>
      <b>Espinoza Rodríguez, Nicolás Antonio:</b>
      <br/>
      <i>TB1</i><br/>
      <b>Galavis Du Bois, Alan Enrique:</b>
      <br/>
      <i>TB1</i><br/>
      <b>Seminario Garbín, Carlo Luca:</b>
      <br/>
      <i>TB1</i><br/>
      <b>Soto Kong Requena, Andrés Eduardo:</b>
      </td>
      <td></td>
    </tr>
    <tr>
    <tr>
      <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. </td>
      <td>
      <b>Astuyauri Calderón, Jherson David:</b>
      <br/>
      <i>TB1: Desarrollé y estructuré gran parte del Capítulo II, gestionando tareas como el As-is Scenario Mapping y la planificación del análisis de entrevistas. Promoví un entorno inclusivo con metas claras y coordinación efectiva para cumplir los objetivos del equipo.</i><br/><br/>
      <b>Espinoza Rodríguez, Nicolás Antonio:</b>
      <br/>
      <i>TB1</i><br/>
      <b>Galavis Du Bois, Alan Enrique:</b>
      <br/>
      <i>TB1</i><br/>
      <b>Seminario Garbín, Carlo Luca:</b>
      <br/>
      <i>TB1</i><br/>
      <b>Soto Kong Requena, Andrés Eduardo:</b>
      </td>
      <td></td>
    </tr>
  </tbody>
</table>

<h1 id='1.'>Capítulo I: Introducción</h1>
<h2 id='1.1.'>Startup Profile</h2>
En esta sección se presenta la descripción del startup y los perfiles de los miembros del equipo.
<h3 id='1.1.1.'>Descripción de la Startup</h3>
Integradis es una startup que busca modernizar el proceso de documentación de actividades y automatizar la medición de parámetros ambientales en las fábricas productoras de champiñones del Perú. El equipo identificó que el uso de sensores manuales y mantener una documentación escrita en la industria actual no solo es arcaico e ineficiente, sino que puede llevar a mediciones imprecisas, lo cual impacta directamente en la calidad y cantidad de la producción final. Bajo este contexto, el equipo identificó una oportunidad para brindar una solución IoT que permita llevar un mejor control sobre estos procesos, con el fin de mitigar los errores asociados al factor humano, y de fomentar el registro digital de procesos.
Misión: Agilizar e impulsar la digitalización de la documentación y monitoreo de los principales procesos de las fábricas productoras de champiñones del Perú.
Visión: Dentro de los próximos 6 años, ser reconocidos como un modelo de negocio sostenible, líder en el desarrollo de plataformas que modernicen la cadena de producción de champiñones a nivel nacional.
Valores:

- Adaptabilidad: Estamos siempre dispuestos a adaptarnos a las necesidades de nuestros usuarios, a los cambios del mercado y las nuevas tendencias en el sector de agricultura.
- Confianza: Trabajamos de manera constante para generar confianza y seguridad en todas nuestras actividades.
- Constancia: Nos esforzamos por mantener una constante mejora en la calidad de nuestros servicios.
- Disponibilidad: Contamos con un equipo disponible gran parte del día para atender todas las necesidades, dudas o problemas que tengan nuestros usuarios en los diferentes productos o servicios que ofrecemos.

<h3 id='1.1.2.'>Perfiles de integrantes del equipo</h3>

| Foto | Nombres y apellidos | Código de alumno | Carrera | Descripción |
|----- | --------------------|------------------| --------| ------------|
| <img src="assets/images/chapter_1/team_members/JhersonAstuyauri.jpg" alt="Jherson Astuyauri" width="700" /> | **Jherson David Astuyauri Calderón** | U202218451 | Ingeniería de Software | Hola, soy Jherson Astuyauri. Tengo 20 años y actualmente curso el séptimo ciclo de la carrera de Ingeniería de Software. Elegí esta carrera porque me apasiona la tecnología y su impacto en la evolución del mundo, así como en la mejora de la calidad de vida de las personas. Actualmente, me interesan especialmente las áreas de inteligencia artificial y ciberseguridad. Puedo aportar al equipo con los conocimientos técnicos que he adquirido a lo largo de los cursos previos, además de mi capacidad para trabajar en equipo de manera efectiva, con una actitud proactiva y responsabilidad. |
| | **Nicolás Antonio Espinoza Rodríguez** | U202110278 | Ingeniería de Software | |
| <img src="assets/images/chapter_1/team_members/AlanGalavis.jpg" alt="Alan Galavis" width="700" /> | **Alan Enrique Galavís Du Bois** | U202110223 | Ingeniería de Software | Mi nombre es Alan Galavis, tengo 21 años y actualmente curso el noveno ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Mi formación académica se ha centrado en el diseño y desarrollo de proyectos de alta calidad, desde simples landing pages hasta aplicaciones web y móviles con RESTful APIs. Para este proyecto puedo aportar con mi capacidad de crear un software eficiente y escalable que brinda las mejores experiencias de usuario. Mi compromiso y conocimientos en gestión de proyectos ágiles me permiten colaborar de manera exitosa en equipos de trabajo. |
| <img src="assets/images/chapter_1/team_members/CarloSeminario.jpg" alt="Carlo Seminario" width="700" /> | **Carlo Luca Seminario Garbín** | U20211A475 | Ingeniería de Software | Mi nombre es Carlo Luca Seminario, tengo 21 años de edad y actualmente curso el noveno ciclo de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Considero que soy una persona que es capaz de trabajar bajo presión, además de ser responsable y perseverante. En cuanto a cualidades para la realización del trabajo considero que soy bueno identificando problemáticas y buscando soluciones, a lo que le puedo sumar los conocimientos adquiridos en cursos de programación y prácticas|
| | **Andrés Eduardo Soto Kong Requena** | U202116113 | Ingeniería de Software | |

<h2 id='1.2.'>Solution Profile</h2>
<h3 id='1.2.1.'>Antecedentes y problemática</h3>
A continuación, se presentan las secciones de Antecedentes y Problemática, y Lean UX Process. La primera consta del enunciado de problema y una descripción de los puntos más importantes que debe resolver la solución, del mismo modo se presentan los objetivos y restricciones que delimitan el alcance del proyecto. La segunda sección es el resultado de la ejecución del Lean UX Process sobre el dominio del problema.

#### **What? (¿Qué?)**

**¿Cuál es el problema?**

Actualmente, las fábricas de champiñones del Perú emplean un registro manual de las actividades que realizan. Esta práctica es difícil de mantener, poco sostenible con el medio ambiente y susceptible a ineficiencias relacionadas con errores humanos, así como a la pérdida de documentos físicos. 
Por otro lado, los administradores de dichas empresas no cuentan con un método confiable para recibir en tiempo real los reportes del estado de los cultivos. Como consecuencia, los administradores se ven en la necesidad de realizar con gran frecuencia visitas a las fábricas, las cuales en su mayoría están ubicadas en zonas lejanas.

#### **When? (¿Cuándo?)**

**¿Cuándo sucede el problema?**

El problema está presente al momento de entablar un análisis del estado y evolución de los procesos llevados a cabo en la fábrica. Debido a que los registros están en formato físico, se necesita buscar entre los archivos de la fábrica y revisar individualmente cada uno de los informes, lo cual resulta tedioso dado el volumen extenso de información registrada a lo largo del tiempo. Además, está presente al momento de medir y ajustar los parámetros de las naves de cultivo, ya que, actualmente, los trabajadores deben de utilizar periódicamente sensores manuales para controlar las condiciones ambientales, lo cual está sujeto a errores asociados al factor humano.

#### **Where? (¿Dónde?)**

**¿Dónde surge el problema?**

El problema se manifiesta en las fábricas de champiñones ubicadas a nivel nacional, y, por lo tanto, en cada una de las áreas que la componen (Patio de preparación del compost, búnker, túnel de pasteurización y naves).

#### **Who? (¿Quién?)**

**¿Quiénes están involucrados? ¿Quién lo utilizará?**

Los usuarios del sistema serían los técnicos encargados de la supervisión y cuidado de los cultivos, y los administradores de las fábricas champiñoneras en Perú. Por un lado los administradores de la fábrica utilizarán la plataforma para visualizar las mediciones registradas por sus trabajadores y por el sistema IoT. Por otro lado, los técnicos supervisores registrarán los procesos que no pueden ser medidos a través de sensores ni controlados por medio de actuadores, como el listado de materiales para elaborar el compost, y las actividades realizadas en el patio. Los datos recopilados en la aplicación permitirá que los trabajadores tomen decisiones estratégicas informadas sobre la asignación de recursos, la programación de tareas y la identificación de áreas de mejora en la producción.

#### **Why? (¿Por qué?)**

**¿Cuál es la causa del problema?**

La causa principal del problema es la ausencia de un programa que permita registrar con facilidad y de manera digital las actividades de la fábrica. Excel no se presenta como una alternativa viable, puesto que son pocos los trabajadores de las fábricas de champiñones que cuentan con la experiencia y habilidades necesarias para utilizarlo eficientemente.

#### **How? (¿Cómo?)**

**¿Cómo se utilizará el producto?**

Los técnicos y administradores tendrán la posibilidad de acceder a la aplicación a través de sus dispositivos móviles o desde un navegador. La aplicación móvil será usada por técnicos supervisores para registrar datos en formularios digitales específicos para los procesos que no pueden ser automatizados por sensores y actuadores, como la preparación del sustrato (compost), la siembra o el proceso de pasteurización en el túnel. Los datos se almacenarán en una base de datos segura y se presentarán en gráficos y listas fácil de entendimiento para el usuario cuando éste lo solicite.
Por otro lado, los administradores de las fábricas utilizarán la aplicación web para supervisar de manera remota los informes periódicos registrados por los técnicos y por el sistema IoT, con el objetivo de tener una visión general en tiempo real del estado de la producción.

**¿Cómo lograremos desarrollar la correcta gestión de cultivos de champiñones dentro de la plataforma?**

El proceso de cultivo de champiñones está dividido en cuatro etapas distintas: La preparación de la mezcla del compost en el patio, la cocción de la mezcla en el búnker, la pasteurización del compost en el túnel y la incubación, cobertura, inducción y cosecha de los champiñones en las naves de crecimiento. La aplicación abarca cada una de estas fases y la distingue de manera adecuada. Cabe recalcar que el sistema IoT únicamente se enfocará en la última etapa del cultivo de champiñones, es decir, aquellos procesos que se realizan en las naves de cultivo. Específicamente, se utilizarán sensores IoT para medir la temperatura y humedad del ambiente.
Las fábricas mantienen un seguimiento del estado y progreso de las actividades realizadas en cada una de las fases de cultivo, por ello, es fundamental que los técnicos supervisores utilicen nuestra aplicación para presentar informes periódicos correspondientes a sus labores. La aplicación, a su vez, permitirá visualizar reportes estadísticos para evaluar el rendimiento y la eficiencia de cada fase del proceso de producción de champiñones.  

#### **How much? (Cuánto)**

**¿Cuál es la magnitud del problema?**

Según Agro Perú (2023), en el año 2022, el Perú exportó 850 toneladas de champiñones secos por un valor de USD 7,1 millones. Ello representó un aumento del 11 % en volumen y 4 % en valor más que en el año 2021. Estos datos indican que el número de exportaciones aparenta ser próspero, lo que confirma la solidez del mercado seleccionado. 
Sin embargo, una encuesta realizada por Cajo y Rosales (2022) revela que, de las 58 empresas agroindustriales peruanas, el 33.9% no administra ni actualiza de manera adecuada el inventario, las características y los cambios en los cultivos. Por otro lado, el resto de las empresas aún realiza estos procesos de forma manual y, por tanto, con márgenes de error muy altos por el factor humano. Por esta razón, resulta necesario el acceso a un software amigable (aplicación móvil) con un proceso de automatización adecuado para agilizar y monitorear el registro de las fases involucradas en la producción de cultivos de estas industrias.
De acuerdo con The Yield Lab (2019), el reto para los startups de la industria agrícola es alcanzar soluciones para la producción de alimentos de una forma más sustentable y eficiente debido al incremento de la demanda en Latinoamérica. Es ahí que se ve implicada Greenhouse como alternativa de solución.

**¿Qué porcentaje del personal de la industria champiñonera se verá beneficiado por el servicio?**

El sistema puede ser utilizado por múltiples técnicos, supervisores y administradores, quiénes incorporan al personal de las fábricas dedicadas a la producción de champiñones. No hay un límite preciso en cuanto al número de usuarios; sin embargo, se estima que alrededor del 35% de usuarios dentro de este sector se verán beneficiados de la implementación de la aplicación.

<h3 id='1.2.2.'>Lean UX Process</h3>
<h4 id='1.2.2.1.'>Lean UX Problem Statements</h4>
<h4 id='1.2.2.2.'>Lean UX Assumptions</h4>
<h4 id='1.2.2.3.'>Lean UX Hypothesis Statements</h4>
<h4 id='1.2.2.4.'>Lean UX Canvas</h4>
<h2 id='1.3.'>Segmentos objetivo</h2>
