<h3 align="center">Universidad Peruana de Ciencias Aplicadas - Ingeniería de Software - 2025-10</h3>
<h3 align="center">1ASI0572 - Desarrollo de Soluciones IOT</h3>
<h3 align="center">NRC: 2941</h3>
<h3 align="center">Profesor: Leon Baca, Marco Antonio</h3>
<h1 align="center">Informe de Trabajo Final</h1>
<h3 align="center">Startup: Integradis</h3>
<h3 align="center">Producto: Greenhouse</h3>

<table align="center" border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Código</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Espinoza Rodriguez, Nicolas Antonio</td>
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
      <td>Soto Kong Requena, Andres Eduardo</td>
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
| Espinoza Rodriguez, Nicolas Antonio |                  |
| Galavis Du Bois, Alan Enrique       |                  |
| Seminario Garbin, Carlo Luca        |                  |
| Soto Kong Requena, Andres Eduardo   |                  |

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
