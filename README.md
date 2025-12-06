<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>1ASI0728 Arquitecturas De Software Emergentes</strong><br>
    <strong>202520</strong><br>
    <strong>NRC: 7322</strong><br>
    <strong>Profesor: Christian Luis De Los Rios Fernandez</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>

<h4 style="text-align: center;"><strong>Nombre del Producto: AquaConecta</strong></h4>


<h5> Integrantes:</h5>

<div style="text-align: center;">
<table style="margin-left: auto; margin-right: auto; text-align: center;">
  <thead>
    <tr>
      <th>Member</th>
      <th>Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Periche Quiroga, Piero Fernando </td>
      <td>U202210192</td>
    </tr>
    <tr>
      <td>Oliveira Paucar, Mauricio</td>
      <td>U201719831 </td>
    </tr>
    <tr>
      <td>Cortez Quezada, Joaquin Antonio</td>
      <td>U202212648</td>
    </tr>
    <tr>
      <td> Mathias Adriano Hidalgo López </td>
      <td>u202213222 </td>
    </tr>
  </tbody>
</table>

<br><h5>Diciembre de 2025<h5><br><br><br><br><br>

</div>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

<div align="center">


|**Versión**|**Fecha**|**Autor**|                                   **Descripción de modificación**                                   |
| :-: | :-: | :-: |:---------------------------------------------------------------------------------------------------:|
|TB1|20/09/2025| Cortez Quezada Joaquin Antonio, Oliveira Paucar Mauricio, Periche Quiroga Piero, Hidalgo Lopez Mathias Adriano | Capítulos dentro del desarrollo del  proyecto: <br>• Capitulo I: Introducción  <br>• Capitulo II: Requirements  Elicitation & Analysis <br>• Capitulo III: Requirements Specification <br>• Capítulo IV: Product Architecture Design | 
TP|11/10/2025| Cortez Quezada Joaquin Antonio, Oliveira Paucar Mauricio, Periche Quiroga Piero, Hidalgo Lopez Mathias Adriano | Capítulos dentro del desarrollo del  proyecto: <br>• Capitulo I: Introducción  <br>• Capitulo II: Requirements  Elicitation & Analysis <br>• Capitulo III: Requirements Specification <br>• Capítulo IV: Product Architecture Design• Capitulo V: Tactical-Level Software Design <br>• Capitulo VI: Solution UX Design <br> |
TB2|16/11/2025| Cortez Quezada Joaquin Antonio, Oliveira Paucar Mauricio, Periche Quiroga Piero, Hidalgo Lopez Mathias Adriano | Capítulos dentro del desarrollo del  proyecto: <br>• Capitulo I: Introducción  <br>• Capitulo II: Requirements  Elicitation & Analysis <br>• Capitulo III: Requirements Specification <br>• Capítulo IV: Product Architecture Design• Capitulo V: Tactical-Level Software Design <br>• Capitulo VI: Solution UX Design <br>• Capitulo VII: Product Implementation, Validation & Deployment <br> |
TF|04/12/2025| Cortez Quezada Joaquin Antonio, Oliveira Paucar Mauricio, Periche Quiroga Piero, Hidalgo Lopez Mathias Adriano | Capítulos dentro del desarrollo del  proyecto: <br>• Capitulo I: Introducción  <br>• Capitulo II: Requirements  Elicitation & Analysis <br>• Capitulo III: Requirements Specification <br>• Capítulo IV: Product Architecture Design• Capitulo V: Tactical-Level Software Design <br>• Capitulo VI: Solution UX Design <br>• Capitulo VII: Product Implementation, Validation & Deployment <br> |

</div>


# Contenido

[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)    
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)

[2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specifications](#capítulo-iii-requirements-specification)

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)

[3.2. User Stories](#32-user-stories)

[3.3. Impact Mapping](#33-impact-mapping)

[3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)

[4.1. Strategic-Level Atrribute-Driven Desing](#41-strategic-level-domain-driven-design)   
[4.1.1. Design Purpose](#411-event-storming)             
[4.1.2. Attribute-Driven Design Inputs](#4111-candidate-context-discovery)    
[4.1.3. Architectural Design Backlog](#4112-domain-message-flows-modeling)    
[4.1.4. Architectural Design Decisions](#4113-bounded-context-canvases)    
[4.1.5. Quality Attribute Scenario Refirements](#412-context-mapping)

[4.2. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)   
[4.2.1. Event Storming](#411-event-storming)             
[4.2.2. Candidate Context Discovery](#4111-candidate-context-discovery)    
[4.2.3. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)    
[4.2.4. Bounded Context Canvases](#4113-bounded-context-canvases)    
[4.2.5. Context Mapping](#412-context-mapping)

[4.3. Software Architecture](#413-software-architecture)    
[4.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)        
[4.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-container-level-diagrams)      
[4.3.3. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)   
[4.3.4 Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)  

[Capitulo V: Tactical-Level Software Design](#capitulo-v-tactical-level-software-design)

[5.1. Analytics Bounded Context](#51-analytics-bounded-context)

[5.2. Water Management Bounded Context](#52-health-management-bounded-context)

[5.3. User & Profile Bounded Context](#53-user--profile-bounded-context)

[5.4. Requests Bounded Context](#54-requests-bounded-context)

[5.5. Subscriptions Bounded Context](#55-subscriptions-bounded-context)

[5.6. Predictive Analytics Bounded Context](#57-predictive-analytics-bounded-context)

[Capitulo VI: Solution UX Design](#capitulo-vi-solution-ux-design)

[6.1. Style Guidelines](#61-style-guidelines)

[6.2. Software Architecture](#62-software-architecture)

[6.3. Landing Page UI Design](#63-landing-page-ui-design)

[6.4. Applications UX/UI Design](#64-applications-uxui-design)

[6.5. Applications Prototyping](#65-applications-prototyping)

[Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)

[7.1. Software Configuration Management](#71-software-configuration-management)

[7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)

[7.1.2. Source Code Management](#712-source-code-management)

[7.1.3. Source Code Style Guide & Conventions](#713-source-code-style-guide--conventions)

[7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)

[7.2. Solution Implementation](#72-solution-implementation)

[7.2.1. Sprint 1](#721-sprint-1)

[7.2.1.1. Sprint Planning 1](#7211-sprint-planning-1)

[7.2.1.2. Sprint Backlog 1](#7212-sprint-backlog-1)

[7.2.1.3. Development Evidence for Sprint Review](#7213-development-evidence-for-sprint-review)

[7.2.1.4. Testing Suite Evidence for Sprint Review](#7214-testing-suite-evidence-for-sprint-review)

[7.2.1.5. Execution Evidence for Sprint Review](#7215-execution-evidence-for-sprint-review)

[7.2.1.6. Services Documentation Evidence for Sprint Review](#7216-services-documentation-evidence-for-sprint-review)

[7.2.1.7. Software Deployment Evidence for Sprint Review](#7217-software-deployment-evidence-for-sprint-review)

[7.2.1.8. Team Collaboration Insights during Sprint](#7218-team-collaboration-insights-during-sprint)

[7.3. Validation Interviews](#73-validation-interviews)

[7.3.1. Diseño de Entrevistas](#731-diseño-de-entrevistas)

[7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)

[7.3.3. Evaluaciones según heurísticas](#733-evaluaciones-según-heurísticas)

[7.4. Video About-the-Product](#74-video-about-the-product)


[Conclusiones](#conclusiones)

[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

[Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:
ABET – EAC - Student Outcome 3 <br>
Capacidad de comunicarse efectivamente con un rango de audiencias.  
Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando 
estrategias de aprendizaje apropiadas. 
En el siguiente cuadro se describe las acciones realizadas de cada integrante y enunciados de 
conclusiones por parte del equipo, que permiten sustentar al haber alcanzado el logro del ABET – 
EAC –Student Outcome 3.


| **Criterio Específico** | **Acciones Realizadas** | **Conclusiones** |
|-------------------------|-------------------------|------------------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **Joaquin Cortez Quezada** <br>**TB1:**<br> En el desarrollo de la TB1, realicé una profunda investigación sobre el problema a solucionar, considerando el aspecto social y económico, además, identifiqué posibles bounded context con el proceso de EventStorming exponiendo los procesos de forma clara y entendible estableciendo el lenguaje ubicuo en cada uno.<br><br>**TP:**<br>Durante el TP, expuse el diseño táctico y la arquitectura del sistema AquaConecta, explicando las funciones de cada bounded context y la integración de los sistemas emergentes. Además, presenté el diseño UX/UI, destacando cómo la solución mejora la experiencia del usuario y la eficiencia operativa.<br><br>**TB2:**<br>Durante la TB2, participé activamente en el desarrollo e implementación del Frontend y Backend, promoví una comunicación efectiva dentro del equipo de desarrollo. Esto me permitió expresar con claridad y objetividad los avances técnicos del proyecto y asegurando que todos comprendieran la lógica detrás de las decisiones tomadas.<br><br>**TF:**<br>En el TF, lideré la comunicación oral relacionada con la implementación del bounded context de Predictive Analytics en el backend. Presenté al equipo técnico y al docente las decisiones arquitectónicas del módulo de predicción de consumo, explicando objetivamente el flujo de datos, la integración con machine learning y los endpoints REST desarrollados. Esta presentación facilitó que tanto compañeros técnicos como stakeholders no especializados comprendieran el valor funcional y la complejidad técnica de la solución implementada.<br><br>**Oliveira Paucar, Mauricio** <br>**TB1:**<br> Durante el desarrollo del proyecto, elaboré el modelado C4 de la solución, estructurando los diferentes niveles de abstracción necesarios para comprender el sistema. <br><br>**TP:**<br>Para esta entrega se agregaron los nuevos puntos solicitados para el capitulo 5 y 6 mientras se mejoro toda la primera entrega con la retroalimentacion recibida por el docente. Este nuevo avance me permitió comunicar de manera clara y objetiva tanto la visión general como los detalles técnicos, adaptando la explicación para la comprensión de mis compañeros del equipo y docente.<br><br>**TB2:**<br>La comunicación oral en esta entrega me permitió presentar y sustentar la implementación del primer sprint (Cap. 7.2), incluyendo la demostración del software funcional y la ejecución de pruebas. Además, se expusieron los resultados cualitativos obtenidos en las entrevistas de validación (Cap. 7.3), facilitando la discusión objetiva del feedback del usuario y los siguientes pasos del despliegue.<br><br>**TF:**<br>Durante el TF, presenté oralmente los resultados finales de la implementación del Sprint 2, destacando las mejoras en el backend y la integración del bounded context de Predictive Analytics. Expuse de manera clara y objetiva las métricas de rendimiento, los casos de prueba ejecutados y los resultados de las validaciones técnicas, facilitando que tanto el equipo de desarrollo como los evaluadores comprendieran el alcance y la calidad del trabajo realizado.<br><br>**Piero Periche Quiroga** <br>**TB1:**<br> En el desarrollo de la tb1, me encargue del analisis del proyecto, con el desarrollo del c4 model y el proceso de EventStorming, mostrando y explicando de forma clara y precisa los procesos. <br><br>**TP:**<br>La comunicación oral fue clave para presentar y sustentar el diseño de la solución. Expuse los mockups (web y mobile) al equipo y docente, explicando objetivamente el flujo de usuario y el diseño de la interfaz para recibir feedback. Asimismo, sustenté oralmente la arquitectura de software propuesta, justificando las decisiones técnicas (componentes, tecnologías) a un público de diferentes especialidades (mis compañeros de equipo) y niveles jerárquicos (docente), asegurando que el plan de implementación del front-end fuera comprendido por todos.<br><br>**TB2:**<br>Durante la TB2, La comunicación oral en esta entrega me permitió liderar y ejecutar las entrevistas de validación con los usuarios. Esto requirió sustentar el prototipo y sus funcionalidades (desarrolladas en front, back y mobile) a un público de diferente especialidad. Posteriormente, expuse los resultados cualitativos y el feedback obtenido de manera objetiva al equipo, facilitando la discusión para definir las correcciones y siguientes pasos del proyecto.<br><br>**TF:**<br>En el TF, expuse oralmente al equipo las actualizaciones finales del backend relacionadas con el módulo de Predictive Analytics. Comuniqué de forma clara y objetiva los desafíos técnicos superados durante la integración, las decisiones de diseño tomadas para optimizar el rendimiento del sistema y los resultados obtenidos en las pruebas de estrés. Esta comunicación permitió que tanto desarrolladores como evaluadores entendieran el valor técnico de las mejoras implementadas.<br><br>**Hidalgo Lopez Mathias Adriano** <br>**TB1:**<br> Durante la fase de investigación, conduje entrevistas con dos grupos distintos: residentes de las comunidades afectadas y proveedores del servicio de agua. Para lograr una comunicación efectiva, adapté mi lenguaje y enfoque: con los residentes, utilicé un tono empático para comprender sus necesidades diarias, mientras que con los proveedores, empleé un lenguaje más técnico para discutir los desafíos operativos. Además, expuse oralmente al equipo las decisiones de diseño arquitectónico (como la elección de un monolito modular y el uso de un Edge Node), traduciendo conceptos técnicos complejos en justificaciones claras y comprensibles para todos.<br><br>**TP:**<br>Fui responsable de elaborar y estructurar la presentación oral del proyecto (PPT). En esta, sinteticé los hallazgos clave y las decisiones de diseño, especialmente las relacionadas con el Capítulo 6 de UX/UI, para exponerlas de manera clara y objetiva ante el docente y compañeros. Además, comuniqué verbalmente al equipo las correcciones necesarias en diversas secciones del informe, facilitando la cohesión y la mejora continua del trabajo presentado.<br><br>**TB2:**<br>Durante la TB2, La comunicación oral en esta entrega me permitió presentar y sustentar los avances técnicos correspondientes al desarrollo del front-end. En las reuniones de equipo, discutí y argumenté objetivamente las decisiones de implementación y las soluciones a los problemas encontrados, facilitando la coordinación con otras áreas del proyecto (como el back-end) y reportando el progreso a un nivel jerárquico superior.<br><br>**TF:**<br>En el TF, comuniqué oralmente las actualizaciones y mejoras realizadas en el backend durante el Sprint 2, especialmente las relacionadas con el bounded context de Predictive Analytics. Presenté de manera objetiva y estructurada el funcionamiento del módulo de predicción de consumo, los algoritmos utilizados y su integración con el sistema existente, asegurando que tanto el equipo técnico como los evaluadores comprendieran la complejidad y el valor de la solución desarrollada.<br> | **TB1:**<br>La comunicación oral permitió presentar con claridad la problemática social del acceso al agua y sus causas, así como los resultados del EventStorming y los bounded contexts. Esto facilitó que los hallazgos y decisiones arquitectónicas fueran entendidos por públicos de distintas especialidades y niveles.<br><br>**TP:**<br>La comunicación oral permitió presentar de manera clara y precisa los avances técnicos y de diseño, demostrando dominio sobre los aspectos arquitectónicos y de experiencia de usuario. Esto contribuyó a que los interlocutores comprendieran la coherencia entre la visión de negocio, la estructura del sistema y la solución tecnológica propuesta.<br><br>**TB2:**<br>El equipo presentó los avances técnicos y de diseño de forma clara y estructurada, facilitando la comprensión entre miembros de distintas especialidades. Las reuniones permitieron alinear criterios y justificar decisiones ante docentes y stakeholders con precisión técnica.<br><br>**TF:**<br>La comunicación oral en la entrega final permitió presentar de manera integral y objetiva el funcionamiento completo del sistema, incluyendo el módulo de Predictive Analytics. El equipo logró transmitir con claridad técnica la arquitectura del backend, los algoritmos implementados y los resultados obtenidos, facilitando que evaluadores de diferentes especialidades comprendieran el valor y la complejidad de la solución desarrollada.|
| Comunica por escrito con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.<br> | **Joaquin Cortez Quezada** <br>**TB1:**<br> Participé en la elaboración de la documentación escrita del proyecto, estructurando de manera clara y objetiva los apartados técnicos y conceptuales. Redacté descripciones de historias de usuario, escenarios de calidad, bounded context canvas y el context mapping, empleando un lenguaje accesible tanto para compañeros de ingeniería como para un público no especializado. <br><br>**TP:**<br>Elaboré un documento técnico que describe la arquitectura táctica, los diagramas estructurales y el diseño UX/UI de AquaConecta, comunicando de forma clara y precisa las decisiones técnicas y visuales del proyecto a públicos especializados y no técnicos.<br><br>**TB2:**<br>Durante la TB2, participé activamente en el desarrollo e implementación del Frontend y Backend, y promoví una comunicación efectiva dentro del equipo de desarrollo. Esto me permitió documentar con claridad y objetividad los avances técnicos del proyecto, adaptando el lenguaje y el nivel de detalle según el perfil de los destinatarios.<br><br>**TF:**<br>En el TF, documenté de manera exhaustiva la implementación del bounded context de Predictive Analytics en el backend. Redacté especificaciones técnicas, diagramas de secuencia y documentación de API para los endpoints desarrollados, empleando un lenguaje técnico preciso pero accesible. Esta documentación garantizó que tanto desarrolladores futuros como evaluadores técnicos pudieran comprender el diseño, la lógica de negocio y las decisiones arquitectónicas tomadas durante la implementación.<br><br>**Oliveira Paucar, Mauricio** <br>**TB1:**<br> En el marco del proyecto, desarrollé el modelado C4 de la solución, documentando de manera estructurada los distintos niveles de abstracción requeridos.  <br><br>**TP:**<br>En la entrega del TP, se mejoro los puntos entregados en la TB1 y se agrego el nuevo contenido técnico solicitado para el capitulo 5 y 6. Este trabajo escrito permitió presentar con objetividad tanto la visión general como los detalles técnicos, de modo que mis compañeros pudieran comprender la propuesta desde una perspectiva de ingeniería, y al mismo tiempo el docente evaluador tuviera claridad sobre la coherencia y justificación del diseño planteado.<br><br>**TB2:**<br>La comunicación escrita fue fundamental para documentar objetivamente el primer ciclo de desarrollo. Esto incluyó la gestión de configuración de software y el registro detallado de la implementación del Sprint 1, abarcando desde el backlog hasta la evidencia de pruebas y despliegue. Asimismo, se estructuró el diseño y los resultados de las entrevistas de validación, asegurando la trazabilidad del feedback del usuario.<br><br>**TF:**<br>Durante el TF, redacté la documentación completa del Sprint 2, incluyendo el Sprint Planning, Sprint Backlog, evidencia de desarrollo y pruebas relacionadas con el bounded context de Predictive Analytics. Mi comunicación escrita permitió presentar con objetividad los commits realizados, las historias de usuario implementadas y los resultados de las validaciones técnicas, garantizando que la documentación fuera comprensible tanto para el equipo técnico como para los evaluadores académicos.<br><br>**Piero Periche Quiroga** <br>**TB1:**<br> En el proyecto desarrollé y aporte en el modelado c4 model de la solucion, documentando de forma clara los niveles de arquitectura requeridos. Esto permitio dejar en claro los detalles de arquitectura, para que asi la solucion tenga una vista clara desde la vision de ingeniería.<br><br>**TP:**<br> La comunicación escrita se materializó en la creación de los artefactos de diseño y arquitectura, que son documentos de ingeniería en sí mismos. Los mockups sirvieron como una guía visual objetiva que comunicó el diseño de la solución. Adicionalmente, documenté la arquitectura (mediante diagramas y especificaciones técnicas), creando un registro objetivo que permitió al equipo (público de diferentes especialidades) entender la estructura del proyecto y proceder con el desarrollo del front-end de manera coherente.<br><br>**TB2:**<br>Durante la TB2, La comunicación escrita fue fundamental para documentar los hallazgos de las entrevistas de validación y participar activamente en las correcciones generales del reporte. Mi labor incluyó asegurar que el feedback del usuario y la evidencia del desarrollo (front, back y mobile) estuvieran registrados con objetividad, garantizando un informe coherente y comprensible para los evaluadores.<br><br>**TF:**<br>En el TF, participé activamente en la documentación técnica del Sprint 2, redactando las secciones relacionadas con la implementación del backend y el bounded context de Predictive Analytics. Mi trabajo escrito incluyó la descripción de los endpoints REST, los diagramas de clases actualizados y los casos de prueba ejecutados, asegurando que la información fuera precisa, objetiva y comprensible para diferentes niveles de especialización técnica.<br><br>**Hidalgo Lopez Mathias Adriano** <br>**TB1:**<br> Participé activamente en la redacción de la documentación del proyecto, especialmente en las secciones de diseño de software (4.1.3, 4.1.4 y 4.1.5). Mi objetivo fue estructurar estas secciones de forma clara y objetiva, explicando decisiones complejas como la arquitectura de monolito modular y el Edge Node, detallando no solo los aspectos técnicos, sino también sus justificaciones y las alternativas consideradas. Esto asegura que la información sea comprensible tanto para un público técnico (compañeros y profesor) como para una audiencia no especializada que necesite entender el porqué del diseño.<br><br>**TP:**<br>Me encargué de la redacción completa del Capítulo 6: Solution UX Design, donde documenté de forma escrita y objetiva las directrices de estilo, los wireframes y los mockups de la aplicación. Mi objetivo fue asegurar que el diseño de la experiencia de usuario fuera comprensible para un público técnico y no especializado. Adicionalmente, realicé una revisión integral del documento, aplicando correcciones de redacción, formato y coherencia para garantizar que la comunicación escrita del informe final fuera de alta calidad.<br><br>**TB2:**<br>Durante la TB2, La comunicación escrita fue fundamental para gestionar y aplicar las correcciones del reporte del proyecto. Mi rol se centró en revisar y asegurar que la documentación técnica, especialmente la vinculada al desarrollo del front-end y la implementación, estuviera plasmada con objetividad y precisión, garantizando la calidad y claridad del documento final para los evaluadores.<br><br>**TF:**<br>En el TF, me enfoqué en la documentación escrita del Sprint 2, redactando las secciones técnicas relacionadas con el desarrollo del backend y la integración del bounded context de Predictive Analytics. Documenté con objetividad y precisión los diagramas de arquitectura actualizados, las especificaciones de los modelos de machine learning y las evidencias de despliegue, garantizando que la información fuera comprensible para evaluadores técnicos y académicos con diferentes niveles de especialización.<br>  | **TB1:**<br>La comunicación escrita permitió documentar de forma objetiva la problemática identificada, sus causas y las soluciones propuestas mediante historias de usuario, escenarios y canvases. Esto aseguró que los resultados fueran comprensibles y útiles para diferentes públicos dentro del proyecto.<br><br>**TP:**<br>La comunicación escrita permitió documentar rigurosamente los aspectos técnicos y de diseño del sistema, asegurando que las decisiones arquitectónicas, los flujos de usuario y los prototipos fueran comprensibles y trazables. Esto consolidó la claridad y consistencia del proyecto, garantizando su valor como documento técnico y herramienta de comunicación profesional.<br><br>**TB2:**<br>Se documentaron rigurosamente los aspectos técnicos del sistema, incluyendo arquitectura, flujos y pruebas. La redacción objetiva y adaptada a distintos perfiles aseguró la trazabilidad del proyecto y su valor como soporte técnico.<br><br>**TF:**<br>La comunicación escrita en la entrega final consolidó la documentación completa del proyecto, incluyendo la implementación del bounded context de Predictive Analytics en el backend. El equipo logró plasmar con objetividad y precisión técnica las especificaciones de API, los diagramas de arquitectura actualizados y las evidencias de desarrollo y pruebas, garantizando que la documentación fuera comprensible y útil para evaluadores técnicos, académicos y futuros desarrolladores del sistema.|


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

AquaConecta es una empresa emergente que se destaca por su enfoque innovador en la implementación de soluciones IoT para optimizar el acceso y la distribución de agua potable. Fundada con el propósito de mejorar la gestión del suministro en comunidades que no cuentan con un servicio continuo, AquaConecta ha logrado posicionarse como un actor clave en el sector gracias a su capacidad para desarrollar plataformas tecnológicas que conectan a proveedores de agua con usuarios finales de manera eficiente y transparente. <br><br>

Nuestra empresa se caracteriza por su compromiso con la innovación, la sostenibilidad y el impacto social. En AquaConecta, creemos firmemente en el poder de la tecnología para transformar la forma en que las personas acceden a recursos esenciales. Por ello, nos enfocamos en ofrecer soluciones inteligentes que permitan monitorear en tiempo real la calidad y cantidad del agua, mejorando la toma de decisiones tanto para proveedores como para usuarios.<br><br>

Como empresa emergente, estamos comprometidos con un crecimiento sostenible y con la expansión de nuestro alcance tanto a nivel nacional como internacional. Nos enorgullece ser parte de una revolución tecnológica en la gestión del agua potable, y estamos entusiasmados por seguir desarrollando herramientas que promuevan una distribución más justa, eficiente y segura mediante nuestra tecnología IoT avanzada

#### Visión

La visión de AquaConecta es ser líder en soluciones IoT para el acceso y distribución eficiente de agua potable, ofreciendo tecnología de vanguardia que garantice la calidad, disponibilidad y gestión inteligente del recurso hídrico en comunidades de todo el mundo.

#### Misión

La misión de AquaConecta es desarrollar y ofrecer soluciones tecnológicas basadas en IoT que mejoren el acceso al agua potable, facilitando la conexión entre proveedores y comunidades sin suministro continuo, mediante herramientas que garanticen una distribución eficiente, transparente y sostenible.

### 1.1.2. Perfiles de los integrantes
| Nombre                   | Descripción | Foto |
|--------------------------|-------------|------|
|  Mauricio Oliveira Paucar | Tengo 25 años, me gusta mucho aprender cosas nuevas sobre mi carrera, trabajar en equipo de manera proactiva y lograr los objetivos junto a mis compañeros. Me considero una persona ambiciosa, ya que mi meta es llegar a obtener un alto cargo en una empresa que me agrade o formar mi propia empresa relacionada al software. <br><br>**Habilidades Técnicas**<br>- Desarrollo Frontend con Angular y Vue<br>- Desarrollo Backend con Java, .NET y Spring Boot<br>- Manejo intermedio de SQL Server y MongoDB<br>- Experiencia en Docker, Git y Domain-Driven Design (DDD) |<img src="./assets/img/oliveirapaucarimg.png" width="350" height="170"> |
| Joaquin Antonio Cortez Quezada | Soy Joaquin Antonio Cortez Quezada, actualmente estoy cursando el octavo ciclo de la carrera de Ingeniería de Software en la UPC (Universidad Peruana de Ciencias Aplicadas). Me considero una persona perseverante, responsable, con la capacidad de aprender y adaptarme de forma rápida para enfrentar diversos desafíos tecnológicos.<br><br>**Habilidades Técnicas**<br>- Desarrollo Frontend con **Angular** y **Vue**<br>- Desarrollo Backend con **Java** y **Spring Boot**<br>- Conocimientos en **C++**, **Python**<br>- Manejo intermedio de **MySQL**, **PostgreSQL** | <img src="./assets/img/cortezquezadaimg.jpeg" width="350" height="170"> |
| Piero Fernando Periche Quiroga | Soy Piero Fernando Periche Quiroga, estoy cursando el octavo ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona responsable, perseverante y con la capacidad de aprender y aportar buenas ideas al equipo frente a los problemas que se puedan presentar.<br><br>**Habilidades Técnicas**<br>- Desarrollo Frontend con **Vue** y **Angular**<br>- Desarrollo Backend con **Java** y **C#**<br>- Conocimiento en **MySQL** y **MongoDB** | <img src="https://i.imgur.com/IIMIR5W.jpeg" width="350" height="170"> |
| Mathias Adriano Hidalgo Lopez | Soy Mahtias Adriano Hidalgo Lopez, Actualmente curso el octavo ciclo d ela carrera de ingenieria de software en la UPC. Me caracterizo por ser una persona responsable, empatica, trabajadora, con una capacidad de captar la informacion al instante.<br><br>**Habilidades Técnicas**<br>- Desarrollo Frontend con **Vue** y **Angular**<br>- Desarrollo Backend con **Java** y **C#**<br>- Conocimiento en **MySQL** y **MongoDB** | <img src="./assets/img/Carnet1.jpg" width="350" height="170"> |



## 1.2. Solution Profile

AquaConecta nace como respuesta a la necesidad de mejorar el acceso y la distribución de agua potable en comunidades sin suministro constante. A través de una plataforma inteligente con tecnología IoT, conecta a proveedores con usuarios, permitiendo monitorear en tiempo real la calidad y cantidad del agua disponible.

Gracias a sus sensores y acceso desde dispositivos móviles o web, la solución facilita la planificación de rutas de distribución y brinda a los usuarios control total sobre su consumo. Su enfoque automatizado, accesible y centrado en datos la convierte en una herramienta eficiente para optimizar la gestión del agua y generar un impacto positivo en la calidad de vida de las personas

### 1.2.1. Antecedentes y problemática

El acceso limitado al agua potable representa uno de los desafíos más críticos que enfrenta la región Ica. Según el Instituto Nacional de Estadística e Informática (INEI), Ica es la tercera región del Perú con el menor porcentaje de hogares que cuentan con acceso continuo a este servicio básico, con apenas el 13.3% de los hogares. Esta estadística revela una realidad alarmante: 9 de cada 10 hogares no tienen acceso a agua durante las 24 horas del día [(INEI, citado en Infobae, 2024)](https://www.infobae.com/peru/2024/05/16/inei-la-pobreza-y-un-deficiente-manejo-del-gobierno-para-enfrentar-la-crisis-economica-que-afecta-a-millones-de-peruanos/).

Esta deficiencia estructural del 86.7% de hogares sin servicio continuo conlleva una serie de problemas socioeconómicos y de salud cuantificables. En primer lugar, genera un sobrecosto económico para las familias, que se ven obligadas a comprar agua a precios más altos a los camiones cisterna privados. Se estima que, en algunas zonas, el costo por metro cúbico puede ser hasta 5 a 10 veces mayor que la tarifa regulada de una EPS, impactando desproporcionadamente a los hogares de menores ingresos. En segundo lugar, la discontinuidad del servicio obliga a la dependencia de métodos manuales y riesgosos de almacenamiento, como cisternas o baldes que, al no contar con un mantenimiento adecuado o tapas herméticas, se convierten en focos de proliferación del zancudo Aedes Aegypti, incrementando el riesgo de brotes de dengue, chikungunya y zika en la provincia, según advertencias de la Dirección Regional de Salud (DIRESA). Además, la restricción horaria limita las oportunidades laborales y educativas, ya que el tiempo de los miembros del hogar, usualmente mujeres y niños, debe dedicarse a la "caza del agua" (esperar y acarrear el suministro).

En la provincia de Chincha específicamente, miles de familias enfrentan serias dificultades de acceso al agua potable bajo la responsabilidad de la Empresa de Servicio Municipal de Agua Potable y Alcantarillado de Chincha Sociedad Anónima –EPS SEMAPACH S.A., mientras que la mayoría de hogares depende del abastecimiento mediante camiones cisterna. La magnitud del problema ha generado una creciente tensión social, evidenciada cuando los pobladores de Chincha, cansados del deficiente servicio de agua que les brinda SEMAPACH, organizaron un plantón en 2025 para exigir mejor servicio de agua potable (Diario Correo, 2025).

El problema se evidenció con particular intensidad en noviembre de 2024, cuando comunidades como el asentamiento humano 28 de Julio, en el distrito de Pueblo Nuevo (Chincha), quedaron sin agua potable en sus viviendas durante varios días consecutivos. Este mismo asentamiento forma parte de las comunidades que participaron en las protestas de 2025, demostrando la persistencia del problema. Según el [Diario Correo (2024)](https://diariocorreo.pe/edicion/ica/chincha-miles-de-familias-padecen-por-falta-de-agua-hasta-por-una-semana-noticia/?ref=dcr#google_vignette), cientos de familias tuvieron que recurrir a cisternas y almacenar agua en condiciones precarias, con un impacto directo en la higiene personal, la alimentación y la salud de niños y adultos mayores.

Esta situación genera múltiples problemáticas: falta de trazabilidad y control por vivienda, ya que no hay un registro automatizado de cuánta agua se entrega a cada familia; distribución ineficiente donde algunas zonas no reciben agua a tiempo o quedan fuera de la planificación; riesgos en la calidad del agua, pues no siempre se verifica si el agua distribuida por cisterna cumple los estándares de salubridad; dependencia de métodos manuales donde muchas decisiones logísticas se toman sin apoyo de datos en tiempo real; y problemas sanitarios graves, ya que el almacenamiento en baldes o tanques sin tapa incrementa el riesgo de enfermedades como el dengue.

Esta realidad evidencia la necesidad urgente de adoptar soluciones tecnológicas, como sistemas de monitoreo IoT y plataformas digitales, que permitan optimizar la planificación de reparto, mejorar la transparencia y garantizar la calidad del agua entregada. AquaConecta surge como respuesta a este contexto, ofreciendo una plataforma que combina sensores IoT instalados en tanques de las viviendas con una aplicación web y móvil para proveedores y usuarios. De esta manera, se recopilan datos en tiempo real sobre cantidad y calidad de agua, lo que facilita la trazabilidad, priorización de zonas críticas y una gestión más eficiente del recurso. Con ello, no solo se mejora la distribución, sino que se promueve una transformación digital de los servicios de agua en beneficio de comunidades vulnerables como las de Pueblo Nuevo.

Asimismo, para garantizar la sostenibilidad del proyecto, se consideran como **aliados estratégicos potenciales** al programa **AquaFund del BID**, que financia proyectos innovadores de agua y saneamiento en zonas rurales, y a Water.org, cuyo modelo **Water Credit** puede facilitar que las familias financien la instalación de sensores en sus tanques. Estos actores representan un soporte clave para el despliegue del piloto en Chincha y su futura escalabilidad a otras comunidades.

#### Técnica de las 5W's y 2H's

##### ¿What? - ¿Cuál es el problema?

 Falta de control y visibilidad sobre el agua en tanques domésticos, lo que impide a las familias saber cuánta agua tienen y su calidad, y a los proveedores gestionar eficientemente las entregas.

##### ¿Who? - ¿Quienes son los beneficiarios?

 Las familias sin acceso continuo a agua potable y los proveedores de agua como empresas, municipalidades y ONGs que buscan optimizar la distribución y monitoreo del recurso.

 ##### ¿When? - ¿Cuando se origina el problema?
 El problema se origina de forma continua, especialmente cuando no hay acceso constante al agua potable, durante cortes inesperados, épocas de sequía o cuando el usuario no puede supervisar manualmente el estado del agua almacenada.

##### ¿Why? - ¿Por qué se origina el problema?

El problema se origina por el acceso limitado o intermitente al agua potable y la falta de control sobre su almacenamiento, lo que dificulta una distribución eficiente y transparente.

##### ¿Where? - ¿Dónde ocurre el problema?

El problema ocurre en hogares y comunidades de zonas urbanas periféricas y rurales con acceso limitado al agua, como Ica y Chincha, donde se depende de tanques y camiones cisterna para el abastecimiento.


##### ¿How? - ¿Como se origina el problema?

El problema se origina por la falta de visibilidad sobre el nivel y la calidad del agua en los tanques, debido a la ausencia de herramientas que permitan monitoreo continuo y acceso a información en tiempo real. Esto genera ineficiencia, desperdicio y desinformación.

##### ¿How much? - ¿Cuánto dinero está implicado?

AquaConecta ofrece planes mensuales entre S/500 y S/1,000, según la cantidad de usuarios que la empresa de agua gestione, e incluye monitoreo y gestión en tiempo real.
 
---                                                                                            
### 1.2.2 Lean UX Process.

El proceso Lean UX aborda la visión del modelo de negocio que respalda nuestro proyecto, siendo el producto principal nuestro software. A lo largo de este documento y en este capítulo, exploramos varios elementos clave de este proceso.

Comenzamos con los "Problem Statements", que abarcan aspectos como el dominio, los segmentos de clientes, los puntos de dolor, las brechas, la visión/estrategia y el segmento inicial. Siguiendo la metodología Lean UX, también consideramos las "Assumptions Statements" y las "Hypothesis Statements".

#### 1.2.2.1. Lean UX Problem Statements.

En comunidades vulnerables de la provincia de Chincha, como el **asentamiento humano 28 de Julio en Pueblo Nuevo**, el acceso al agua potable es limitado e irregular debido a una distribución ineficiente y a la falta de información confiable sobre la calidad del recurso. Actualmente no existen mecanismos efectivos de monitoreo en tiempo real, lo que dificulta identificar problemas, impide una gestión basada en datos y limita la capacidad de tomar decisiones oportunas para garantizar un suministro seguro.

Hemos observado que los proveedores locales y las municipalidades enfrentan dificultades para planificar rutas de distribución con cisternas, mientras que los habitantes carecen de herramientas que les permitan conocer el nivel y la calidad del agua almacenada en sus tanques. Esta situación provoca desperdicio, retrasos en la atención y riesgos sanitarios en la población.

¿Cómo podemos implementar un sistema de monitoreo accesible y en tiempo real que permita a los proveedores de agua y municipalidades mejorar la planificación de la distribución y, al mismo tiempo, brinde a las familias de sectores como Pueblo Nuevo información clara sobre la calidad y cantidad de agua disponible en sus hogares?


#### 1.2.2.2. Lean UX Assumptions.

En esta sección, veremos los Assumptions que podemos esperar de nuestra solución, desde los Features que debe tener, hasta los Outcomes en nuestra perspectiva y la de los usuarios.

**Features:**

Aqui veremos las herramientas que planeamos implementar en nuestra solución.

- Monitoreo en Tiempo Real de Calidad y Cantidad de Agua: Sensores IoT que recopilan datos sobre el caudal, presión, nivel de cloro, turbidez, entre otros parámetros del agua, enviando la información a una plataforma centralizada.
- Alertas Automatizadas: Notificaciones en tiempo real sobre anomalías en la calidad del agua o interrupciones en el suministro, dirigidas a autoridades locales, técnicos o responsables comunitarios.
- Dashboard Centralizado de Datos: Plataforma accesible desde dispositivos móviles o PC para visualizar gráficamente el estado del suministro, históricos y predicciones de comportamiento hídrico.
- Reportes Automáticos para Toma de Decisiones: Generación de reportes periódicos para los tomadores de decisiones, con métricas claves para planificación y mejora de la infraestructura.

**Business Outcomes:**

Acquisition (Base): [3,000 visitantes]
Las comunidades rurales, organizaciones sociales y municipalidades se enteran de nuestra solución a través de campañas en redes sociales, ferias tecnológicas rurales, charlas con ONGs y contenido educativo. Además, se realizarán alianzas con entidades públicas y privadas que promuevan la transformación digital en zonas rurales. Estimamos alcanzar inicialmente a 3,000 personas interesadas en el tema de gestión del agua.

Activation (Plateau): [900 usuarios : 100%]
De los visitantes, se espera que el 30% (900 usuarios) participen activamente en una demostración del sistema o soliciten un diagnóstico gratuito para su comunidad. En esta fase, los usuarios nos comparten información básica como ubicación de su sistema de agua, número de conexiones, tipo de infraestructura y principales problemas. También acceden por primera vez a nuestra plataforma con credenciales temporales.

Retention (Plateau + 1 level): [540 usuarios : 60%]
Tras la activación, un 60% de las comunidades implementan el sistema de manera continua y lo usan para monitorear su infraestructura hídrica. Estas comunidades acceden regularmente a los datos del sistema, reciben alertas automáticas y visualizan mejoras progresivas en su servicio, lo que incentiva el uso constante. Aquí se empieza a notar la reducción del 40% en interrupciones y se ve reflejada la mejora del 25% en la calidad del agua, validando la funcionalidad del producto.

Revenue (Plateau + 2 levels): [80 usuarios : ~15%]
De los usuarios retenidos, se proyecta que al menos el 15% opte por un plan de monitoreo avanzado, que incluye mantenimiento predictivo, personalización de alertas y análisis más profundo de los datos. Este grupo valora la capacidad del sistema para reducir un 30% los costos de operación, y está dispuesto a pagar por estas funcionalidades premium.

Referral (Top): [27 usuarios : 5% del total inicial]
Un 5% de los usuarios referirán nuestra solución a otras comunidades, ONGs o municipios, gracias a su experiencia positiva. Estos promotores naturales ayudan a amplificar nuestro alcance de forma orgánica, aportando nuevas oportunidades de implementación y reforzando nuestra posición como referente en soluciones IoT para zonas rurales.



## Users

En esta sección creamos un Proto-Persona como una suposición de cómo son nuestros usuarios, enfocándonos más en el aspecto de actitud.

| Demográfica                                   | Comportamiento                                                                                          | Necesidades / Obstáculos                                                                                      |
|----------------------------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| Gestores de Agua Rurales:                    | - Supervisan el sistema de distribución de agua de toda una comunidad                                     | - Necesitan visibilidad total del estado del sistema hídrico                                                   |
| Municipalidad, ONG, Junta de usuarios        | - Tienen experiencia gestionando recursos públicos o sociales                                             | - Requieren reportes detallados para tomar decisiones técnicas y presupuestales                               |
|                                              | - Se enfrentan constantemente a reclamos por fallas o baja calidad del agua                               | - Necesitan detectar fallas rápidamente para reducir tiempos de respuesta e interrupciones                    |
|                                              | - Buscan optimizar los recursos disponibles y generar confianza con la comunidad                          | - Buscan fortalecer la transparencia y generar reportes públicos                                               |
| Personas en zonas vulnerables:               | - Sufren cortes de agua frecuentes o reciben agua de baja calidad                                         | - Quieren saber si el agua que consumen es segura para su familia                                              |
| Residentes de comunidades rurales            | - No cuentan con acceso directo a la gestión del agua                                                     | - Necesitan una forma accesible para reportar fallas o problemas                                                |
|                                              | - Se enteran de las fallas solo cuando el problema ya está avanzado                                       | - Buscan tener más información sobre lo que sucede con el servicio de agua                                     |
|                                              | - Participan en asambleas o reuniones comunales para expresar sus necesidades                             | - Necesitan confiar en los gestores del agua y saber que sus necesidades están siendo atendidas               |

## User Outcomes & Benefits


En esta sección se busca el lado más emocional y empatizar con el usuario para darles los outcomes correctos.

El usuario busca asegurar el acceso a agua segura y confiable para su comunidad, así como mejorar la eficiencia en la gestión del recurso hídrico. En este proceso, desea sentirse tranquilo, empoderado y respaldado por información clara que le permita tomar decisiones oportunas sin depender únicamente de inspecciones manuales. Nuestra solución IoT lo acerca a este logro personal al proporcionarle datos en tiempo real sobre la calidad del agua, permitiéndole anticiparse a posibles problemas y demostrando así su capacidad de liderazgo dentro de la comunidad. El usuario recurriría a nuestro producto porque necesita una herramienta accesible que le facilite detectar a tiempo contaminaciones o fallas en la red de distribución, sin requerir grandes conocimientos técnicos ni inversiones elevadas. Como resultado, observamos un cambio de comportamiento donde consulta la plataforma con mayor frecuencia, responde con rapidez ante eventos anómalos, informa de forma más precisa a su comunidad y optimiza los recursos en la gestión del agua, evidenciando que ha alcanzado su objetivo.


A partir de los problemas detectados en las entrevistas y el contexto rural, proponemos las siguientes soluciones tecnológicas:


- Monitoreo de calidad del agua (pH, turbidez, temperatura):

Problema: Las comunidades no tienen forma de detectar a tiempo si el agua está contaminada.

Solución: Sensores que miden en tiempo real parámetros como pH, turbidez y temperatura del agua.

Resultado: El sistema emite alertas inmediatas si se detecta contaminación, lo que permite prevenir enfermedades y mejorar la salud pública.

- Alertas automáticas ante condiciones críticas:

Problema: La falta de monitoreo continuo genera respuestas tardías ante emergencias sanitarias.

Solución: Plataforma que notifica automáticamente a los gestores mediante SMS o app cuando se detectan valores anómalos.

Resultado: Reducción significativa del tiempo de reacción ante problemas, lo que minimiza riesgos sanitarios.

- Panel de control comunitario:

Problema: Los gestores y ciudadanos no tienen acceso a información visual y clara sobre el estado del agua.

Solución: Dashboard con indicadores simples y accesibles (semáforo de calidad, gráficas por día, semana y mes).

Resultado: Mejora de la transparencia, empoderamiento ciudadano y participación comunitaria en el cuidado del agua.

- Historial de datos y reportes automáticos:

Problema: No se cuenta con registros para evaluar tendencias o realizar auditorías.

Solución: Almacenamiento de datos históricos accesibles en cualquier momento y generación de reportes descargables.

Resultado: Mejora de la planificación, mantenimiento predictivo e informes técnicos para autoridades o donantes.

- Funcionalidad offline y bajo consumo energético:

Problema: En zonas remotas no hay conectividad constante ni acceso a energía eléctrica.

Solución: Uso de sensores con batería solar, comunicación vía redes LoRa o GSM y almacenamiento local en el dispositivo.

Resultado: Asegura la continuidad del monitoreo en cualquier entorno, incluso sin internet.



**Business Assumptions:**

Estos son los puntos que podemos asumir de nuestro negocio.

1. Existe una necesidad urgente de mejorar la gestión del agua en zonas rurales, especialmente en lugaers en vías de desarrollo.
2. Esta necesidad puede resolverse con una solución IoT accesible, autónoma y fácil de usar por personal técnico o líderes comunitarios.
3. El valor principal que buscan los clientes es una forma confiable y económica de monitorear y mejorar el sistema hídrico sin requerir grandes inversiones.
4. Nuestros clientes potenciales serán principalmente gobiernos locales, ONGs, cooperativas y empresas sociales con foco en desarrollo rural.
5. Obtendremos ingresos a través de un modelo mixto: venta de kits IoT + suscripción a la plataforma de monitoreo, con opciones de personalización e integración.
6. Aunque existen soluciones similares, muchas son costosas o complejas. Nuestra ventaja está en la adaptabilidad, escalabilidad y soporte local.
7. El mayor riesgo es la falta de conectividad o acceso a tecnologías en zonas remotas.
8. Planeamos mitigar este riesgo mediante tecnologías de bajo consumo energético, almacenamiento offline y comunicación vía redes alternativas (LoRa, GSM, etc.).



#### 1.2.2.3. Lean UX Hypothesis Statements.
### Hipótesis del Proyecto

- **Hipótesis 1:**  
  Creemos que lograremos el posicionamiento como referentes en soluciones IoT para comunidades rurales,  
  si los gestores de agua obtienen una experiencia clara y visualmente intuitiva mediante el uso del dashboard centralizado de datos.

- **Hipótesis 2:**  
  Creemos que obtendremos una mejora significativa en la eficiencia operativa,  
  si los técnicos de mantenimiento reciben alertas automatizadas en tiempo real ante problemas en el sistema de distribución de agua.

- **Hipótesis 3:**  
  Creemos que se logrará una mejora en la calidad del agua distribuida,  
  si los gestores de agua pueden monitorear constantemente parámetros como turbidez, cloro y presión a través de los sensores IoT instalados.

- **Hipótesis 4:**  
  Creemos que se reducirá el tiempo de respuesta ante incidentes,  
  si los técnicos y responsables locales reciben notificaciones inmediatas mediante el sistema de alertas inteligentes.

- **Hipótesis 5:**  
  Creemos que la transparencia y la confianza comunitaria aumentarán,  
  si los líderes comunitarios tienen acceso a reportes automáticos y comprensibles sobre la calidad y cantidad de agua disponible.

- **Hipótesis 6:**  
  Creemos que se logrará una reducción en los costos operativos del sistema de agua,  
  si los responsables de gestión pueden planificar mantenimientos preventivos usando datos históricos y predicciones del sistema.

- **Hipótesis 7:**  
  Creemos que podremos expandir la adopción de nuestra solución en comunidades rurales diversas,  
  si ofrecemos una plataforma adaptable a distintos niveles tecnológicos y conectividad, gracias al uso de tecnologías como LoRa y GSM.

#### 1.2.2.4. Lean UX Canvas.

A partir de todo lo que hemos investigado, creamos el Lean UX Canvas.

# Lean UX Canvas

| **Sección** | **Contenido** |
|:------------|:--------------|
| **1. Business Problem** | En el AA.HH. 28 de Julio (Pueblo Nuevo, Chincha), las familias sufren un acceso irregular al agua potable. La distribución por cisternas es ineficiente y sin trazabilidad, lo que impide a proveedores y municipalidad planificar adecuadamente, y a los hogares conocer la cantidad y calidad del agua que reciben. |
| **2. Business Outcomes** | - Ser reconocidos como referentes en soluciones IoT para comunidades rurales.<br>- Reducción del 40% en el tiempo de respuesta ante problemas de suministro.<br>- Mejora del 25% en estándares de calidad del agua en zonas intervenidas.<br>- Reducción del 30% en gastos de mantenimiento gracias al análisis predictivo.<br>- Mayor transparencia y confianza por parte de la comunidad. |
| **3. Users** | - **Proveedores locales de agua:** encargados de distribuir, gestionar y mantener el servicio.<br>- **Habitantes de viviendas:** consumidores de agua que podrían recibir alertas y monitorear calidad básica. |
| **4. User Outcomes & Benefits** | - Acceso a datos en tiempo real sobre calidad y cantidad del agua.<br>- Toma de decisiones informadas ante emergencias.<br>- Menor riesgo sanitario mediante acciones preventivas.<br>- Simplificación de la gestión técnica.<br>- Empoderamiento ciudadano en la gestión del recurso.<br>- Mayor confianza entre comunidad y proveedores. |
| **5. Solutions** | - **Monitoreo en Tiempo Real:** uso de sensores IoT (caudal, presión, turbidez, cloro).<br>- **Alertas Automatizadas:** notificaciones ante anomalías.<br>- **Dashboard Centralizado:** visualización y reportes desde PC o móvil.<br>- **Reportes para Toma de Decisiones:** informes periódicos para autoridades y líderes. |
| **6. Hypotheses** | - Creemos que lograremos reconocimiento como referentes IoT si los usuarios obtienen una experiencia clara en el dashboard.<br>- Creemos que aumentará la eficiencia si los técnicos reciben alertas en tiempo real.<br>- Creemos que mejorará la calidad del agua mediante monitoreo constante.<br>- Creemos que se reducirá el tiempo de respuesta si las alertas llegan instantáneamente.<br>- Creemos que se aumentará la confianza comunitaria si los reportes son comprensibles.<br>- Creemos que se reducirán costos si los mantenimientos son planificados con base en datos. |
| **7. What's the Most Important Thing We Need to Learn First?** | - Los usuarios comprenden y valoran el dashboard como herramienta útil.<br>- Las alertas en tiempo real llegan de forma adecuada y ayudan a técnicos.<br>- El monitoreo de parámetros mejora efectivamente la calidad del agua.<br>- Los reportes automáticos generan confianza en la comunidad. |
| **8. What's the Least Amount of Work We Need to Do to Learn the Next Most Important Thing?** | - **Encuestas Rápidas:** a líderes comunitarios y técnicos.<br>- **Pruebas de Concepto:** piloto básico con sensores y dashboard.<br>- **Análisis de Factibilidad Técnica:** validar conectividad en zonas objetivo.<br>- **Recolección de Feedback:** iterar con base en la experiencia de usuarios. |


## 1.3. Segmentos objetivo.
| Variables    | Segmento 1 - Habitantes | Segmento 2 - Proveedores |
|--------------|-------------------------|---------------------------|
| Geográfica   | Familias del AA.HH. 28 de Julio en Pueblo Nuevo (Chincha) y zonas similares, con acceso intermitente al agua potable mediante cisternas y sin información clara sobre su cantidad y calidad. | Empresas de servicios hidráulicos, ONG ambientales o proveedores locales de tecnología situados en zonas rurales, periurbanas o cercanas a zonas de alta necesidad hídrica. |
| Demográfica  | Personas de diversa edad y género, principalmente familias o individuos interesados en mejorar su acceso a agua segura y en cuidar su entorno ambiental. | Profesionales técnicos o comerciales, de edad adulta, con formación o experiencia en gestión de recursos hídricos, instalación de sensores IoT o mantenimiento de redes de agua. |
| Psicológica  | Alta preocupación por la salud, calidad del agua y sostenibilidad. Buscan soluciones simples y accesibles para controlar su propio consumo y asegurar el bienestar familiar. | Enfoque orientado a brindar servicios de alta eficiencia. Valoran la innovación tecnológica para monitorear remotamente sensores, optimizar el uso del agua, cumplir estándares ambientales y ofrecer mantenimiento predictivo. |
# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

#### a) Competidores directos
Corresponden a organizaciones y soluciones que utilizan tecnologías IoT y plataformas digitales para la gestión del agua:

- **Xylem (internacional):** empresa global especializada en tecnología del agua, con soluciones de monitoreo de redes y sensores de calidad.
- **Kamstrup (internacional):** fabricante de medidores inteligentes de agua con transmisión de datos en tiempo real.
- **Agualimpia (Perú):** organización que ha desarrollado proyectos piloto de telemetría en comunidades rurales, aunque con un enfoque más orientado al tratamiento del agua.
- **Isla Urbana (México):** iniciativa que implementa sistemas de captación y monitoreo de agua de lluvia, con aplicaciones tecnológicas a nivel comunitario.

Estos actores comparten el uso de tecnologías inteligentes; sin embargo, su foco principal está en redes urbanas consolidadas o en proyectos de captación de agua, mientras que **AquaConecta** se orienta a la trazabilidad del consumo y a la optimización de la distribución mediante cisternas en comunidades vulnerables.

---

#### b) Competidores indirectos
Se trata de los proveedores de agua existentes que operan bajo esquemas manuales y con limitada digitalización:

- **EPS SEMAPACH S.A. (Chincha):** empresa municipal responsable del servicio de agua potable en la zona, cuyo modelo actual presenta deficiencias en continuidad y trazabilidad.
- **Camiones cisterna privados:** proveedores informales que abastecen a los hogares sin red de distribución formal, con ausencia de control de calidad y planificación.
- **Juntas administradoras de agua rural (JAAR):** organizaciones comunitarias que gestionan el servicio en áreas rurales, sin apoyo de herramientas tecnológicas.

La diferencia principal con **AquaConecta** radica en que estas entidades cumplen la función de abastecimiento, pero sin mecanismos de monitoreo en tiempo real ni registros automatizados que garanticen transparencia y eficiencia.

---

#### c) Competidores potenciales
Son instituciones que, aunque actualmente funcionan como aliados estratégicos, podrían desarrollar o financiar soluciones tecnológicas similares:

- **Water.org:** organización internacional que promueve mecanismos de financiamiento para proyectos de agua y saneamiento, con capacidad para incorporar modelos tecnológicos en el futuro.
- **AquaFund del BID:** programa que financia proyectos innovadores en agua y saneamiento en América Latina.

---

### 2.1.1. Análisis competitivo

<table> 
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Para proporcionar información valiosa acerca de los competidores, lo cual nos servirá para mejorar la calidad de nuestra aplicación.</td>
  </tr>
  <tr>
    <td colspan="5"></td>
  </tr>
  <tr>
    <td colspan="3"></td>
    <td colspan="1" valign="top" style="font-weight: bold;">AquaConecta</td>
    <td colspan="1" valign="top" style="font-weight: bold;">AguaClara</td>
    <td colspan="1" valign="top" style="font-weight: bold;">Ingeniería Ambiental SAC</td>
    <td colspan="1" valign="top" style="font-weight: bold;">Transporte de Agua Potable Espinoza</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">
      AquaConecta optimiza la distribución de agua potable conectando proveedores con comunidades sin acceso continuo, mediante monitoreo en tiempo real usando un enfoque tecnológico (IoT).
    </td>
    <td colspan="1" valign="top">
      AguaClara mejora el acceso al agua potable en comunidades rurales mediante un sistema de distribución eficiente, coordinado con gobiernos y ONGs. 
    </td>
    <td colspan="1" valign="top">
      La empresa se especializa en el abastecimiento de agua potable e industrial. Proporcionan cisternas adecuadamente equipadas para el transporte de agua hacia ubicaciones remotas.
    </td>
    <td colspan="1" valign="top">
      La empresa se dedica a la venta y distribución de agua potable para consumo. Cuenta con una flota moderna de camiones cisterna.
    </td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">
      Brinda distribución eficiente, monitoreo inteligente y mayor transparencia en el acceso al agua potable.
    </td>
    <td colspan="1" valign="top">
      Ofrece acceso continuo a agua segura en zonas rurales mediante una distribución organizada y siguiendo un modelo de bajo costo.
    </td>
    <td colspan="1" valign="top">
      Brinda abastecimiento de agua para una variedad de aplicaciones y brinda precios personalizados basados en las necesidades del cliente.
    </td>
    <td colspan="1" valign="top">
      Ofrece el servicio de distribución de agua potable en zonas donde el suministro puede ser intermitente o limitado.
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">
      Comunidades en zonas urbanas y rurales con servicio intermitente de agua potable. Empresas proveedoras de agua.
    </td>
    <td colspan="1" valign="top">
      Comunidades rurales con acceso limitado a agua potable. Instituciones públicas o ONG's interesadas en desarrollos de proyectos sostenibles.
    </td>
    <td colspan="1" valign="top">
      Proyectos industriales que necesitan gran volumen de agua.
    </td>
    <td colspan="1" valign="top">
      Hogares que carecen de suministro de agua potable. Proyectos comerciales o industriales.
    </td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">
      Alianzas estratégicas con municipalidades y ONG's, además de una fuerte presencia en las redes sociales.
    </td>
    <td colspan="1" valign="top">
      Cuenta con alianzas estratégicas con municipalidades y ONG's. Además, comunidades beneficiadas recomiendan el servicio a través del boca a boca.
    </td>
    <td colspan="1" valign="top">
      Ofrece tarifas ajustadas a las necesidades específicas de cada cliente. Además, cuenta con atención disponible las 24 horas a través de canales como WhatsApp, teléfono y correo.
    </td>
    <td colspan="1" valign="top">
      Brindan confiabilidad, puntualidad y se centran en la satisfacción del cliente.
    </td>
  </tr>
  <tr>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">
      Distribución de agua potable y monitoreo en tiempo real del nivel y calidad del agua a través de sensores.
    </td>
    <td colspan="1" valign="top">
      Servicio de distribución de agua potable mediante rutas planificadas para camiones cisterna.
    </td>
    <td colspan="1" valign="top">
      Alquiler de cisternas y abastecimiento de agua potable para proyectos mineros, laboratorios, comedores, etc.
    </td>
    <td colspan="1" valign="top">
      Distribución de agua potable para consumo humano, obras civiles, agrícolas o eventos especiales.
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">
      Precios personalizados que se ajustan a las necesidades específicas de cada cliente.
    </td>
    <td colspan="1" valign="top">
      Costo bajo o subsidiado ya que trabajan junto a gobiernos o ONG's.
    </td>
    <td colspan="1" valign="top">
      Precios personalizados que se ajustan a las necesidades específicas de cada cliente.
    </td>
    <td colspan="1" valign="top">
      Precios personalizados que se ajustan a las necesidades específicas de cada cliente.
    </td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">
      Sitio web con información esencial para nuestros usuarios, además de una aplicación web y móvil.
    </td>
    <td colspan="1" valign="top">
      Implementación física directa del equipo técnico, no posee una plataforma web comercial.
    </td>
    <td colspan="1" valign="top">
      Canales de comunicación por correo y telefonía. Asimismo, cuenta con un sitio web para gestionar solicitudes.
    </td>
    <td colspan="1" valign="top">
      Canales de comunicación por correo, telefonía y redes sociales.
    </td>
  </tr>
  <tr>
    <td colspan="2">Análisis SWOT - Introducción</td>
    <td colspan="4">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="4"><p>Análisis SWOT</p></td>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">
      Implementación de tecnologías IoT para el monitoreo en tiempo real del agua.
    </td>
    <td colspan="1" valign="top">
      Fuerte colaboración con gobiernos locales y ONG's. Presencia en zonas rurales.
    </td>
    <td colspan="1" valign="top">
      Monitoreo de camiones cisterna por GPS, servicio personalizado y sólida experiencia en el sector.
    </td>
    <td colspan="1" valign="top">
      Experiencia en el rubro de distribución de agua y atención las 24 horas del día.
    </td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">
      Alta dependencia de la conectividad a internet para operar.
    </td>
    <td colspan="1" valign="top">
      Limitada incorporación de tecnologías IoT.
    </td>
    <td colspan="1" valign="top">
      Costos variables pueden generar incertidumbre en los costos finales.
    </td>
    <td colspan="1" valign="top">
      Falta de presencia digital sólida y poca innovación tecnológica.
    </td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">
      Aprovechamiento de la baja penetración de tecnologías similares en el sector hídrico.
    </td>
    <td colspan="1" valign="top">
      Aumento del alcance con plataforma web e implementación de soluciones digitales como aplicaciones móviles.
    </td>
    <td colspan="1" valign="top">
      Implementación de soluciones tecnológicas como aplicaciones móviles.
    </td>
    <td colspan="1" valign="top">
      Integración de tecnologías IoT para monitoreo en tiempo real de entregas.
    </td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">
      Posible resistencia al cambio por parte de proveedores convencionales.
    </td>
    <td colspan="1" valign="top">
      Dificultad para operar sistemas en zonas remotas sin soporte técnico constante.
    </td>
    <td colspan="1" valign="top">
      Aparición de soluciones tecnológicas más eficientes.
    </td>
    <td colspan="1" valign="top">
      Problemas logísticos por tráfico o escasez de agua.
    </td>
  </tr>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

AquaConecta implementará una estrategia de diferenciación tecnológica al ofrecer un sistema de monitoreo inteligente del consumo de agua en tiempo real, una propuesta que actualmente no es atendida de forma precisa por sus principales competidores. Esto permitirá posicionarse como una solución innovadora tanto para hogares como para proveedores de agua.

Nuestra estrategia se basa en aprovechar las principales debilidades detectadas en los competidores actuales del mercado. En primer lugar, la limitada incorporación de tecnologías IoT representa una oportunidad clave para diferenciarnos. Integramos sensores inteligentes que permiten monitorear en tiempo real tanto la cantidad como la calidad del agua, así como el estado de los tanques. Esto no solo optimiza el servicio, sino que también proporciona datos valiosos para la toma de decisiones y el mantenimiento predictivo.

En segundo lugar, frente a la incertidumbre generada por los costos variables que ofrecen otras empresas, implementamos un modelo de tarifa plana mediante suscripción, que brinda a los usuarios mayor previsibilidad, control y confianza sobre sus pagos mensuales. Esto también fortalece la relación a largo plazo con nuestros clientes al eliminar sorpresas financieras.

Por último, ante la escasa presencia digital y la falta de innovación tecnológica de nuestros competidores, hemos desarrollado una plataforma web y móvil robusta, intuitiva y moderna, que permite a los usuarios registrarse, actualizar sus datos, revisar el estado del servicio y realizar solicitudes de forma rápida y sencilla. Esta propuesta refuerza nuestro posicionamiento como una empresa innovadora, accesible y centrada en la experiencia del usuario.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas
**Preguntas Generales**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿Que navegador usa?
5. ¿Que dispositivo usa con mas frecuencia y de que marca es?
6. ¿En que distrito se encuentra?

**Entrevistas usuario segmento (Habitantes)**

1. ¿Cómo obtienen actualmente el agua para el consumo diario?
2. ¿Sienten que el agua que reciben es segura? ¿Por qué?
3. ¿Han tenido problemas de salud relacionados con el agua en los últimos años?
4. ¿Qué hacen cuando sospechan que el agua está contaminada?
5. ¿Con qué frecuencia reciben información sobre la calidad del agua?
6. ¿Quién les informa actualmente sobre el estado del agua?
7. ¿Confían en la información que reciben sobre la calidad del agua?
8. ¿Les gustaría recibir alertas si el agua no es apta para el consumo?
9. ¿Qué tan importante consideran la calidad del agua en su bienestar diario?
10. ¿Estarían dispuestos a participar en el cuidado o monitoreo del sistema si eso ayudara a su comunidad?

**Entrevistas usuario segmento (Proveedores de agua)**
1. ¿Cuáles son los principales retos que enfrentan en la supervisión de la calidad del agua?
2. ¿Qué procesos siguen actualmente para analizar el agua en zonas rurales?
3. ¿Con qué frecuencia se realiza el control de calidad del agua?
4. ¿Qué tipo de datos les gustaría poder monitorear en tiempo real (pH, turbidez, cloro, etc.)?
5. ¿Qué herramientas utilizan para almacenar y analizar los datos del agua?
6. ¿Cómo actúan cuando detectan un problema de calidad en alguna zona?
7. ¿Qué costos están asociados actualmente al monitoreo de agua?
8. ¿Cuánto tiempo tardan en detectar y responder a una posible contaminación?
9. ¿Qué impacto creen que tendría un sistema IoT en su trabajo y en la comunidad?
10. ¿Qué funcionalidades consideran imprescindibles en una solución como esta?

### 2.2.2. Registro de entrevistas

**Entrevistas usuario segmento (Habitantes)**

**Segmento Doméstico**  
Nombre: Marilyn Lopez Tineo
<br>
- Edad: 20
<br>
- Ocupación: Estudiante de Gerencia
<br>
- Browser: Google Chrome
<br>
- Device: Teléfono Samsum
<br>
- Distrito: San Martin-Tarapoto
<br>
  [link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213222_upc_edu_pe/EdnO3obrxGxOiLsD_5HvpcQBoz5dMgew1ZBBfGTt6G7zsQ?e=QVokj8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
<br>

<div style="text-align: center;">
  <img src="./assets/img/InterviewMarilyn.png" 
       alt="Entrevista 1 Segmento habitantes" 
       width="500"/>
</div>


Marilyn, una joven residente de Tarapoto, nos cuenta que desde pequeño recuerda cómo llega y recibe el agua a su hogar a travez de una pileta ubicada a unas cuantas cuadras de su vivienda. Tambien comenta que en su distrito estan desarrollando un proyecto en el cual aun no esta del todo completo y parece ser que pinta para el fracaso. Ademas que el agua que le llega a su hogar a veces esta en mal estado, sea por pequeñas particulas o este de otro color, siendo mas el marron. Ella estaria dispuesta a participar en el proyecto para ayudar a que el agua sea mas pura para el consumo y uso diario en su distrito.




**Entrevistas usuario segmento (Proveedor de agua)**


Nombre: Tracy Cordova
<br>
- Edad: 34
<br>
- Ocupación: Trabajadora de Sedapal
<br>
- Browser: Google Chrome
<br>
- Device: Teléfono Samsung
<br>
- Distrito: Jesus Maria
<br>
- Timing: 10:35
<br>
- Marca: Sunass
<br>
<div style="text-align: center;">
    
![image](https://github.com/user-attachments/assets/0d69bec6-92cc-4777-8801-7e17d4432b3e)

</div>

Tracy, trabajadora de Sedapal, explicó que uno de los principales retos en su labor es la falta de monitoreo en tiempo real, lo que retrasa la detección de problemas en la calidad del agua. Actualmente, el análisis de muestras puede demorar entre 3 y 7 días, dependiendo de la zona, lo cual limita la capacidad de respuesta.
Mencionó que usan herramientas básicas como hojas de cálculo y GIS, pero no cuentan con un sistema automatizado. Los costos logísticos son altos, especialmente en zonas rurales. Tracy considera que una solución IoT sería de gran ayuda, ya que permitiría detectar problemas al instante y proteger a la población. Sugiere incluir alertas automáticas, monitoreo constante y facilidad de uso.

Nombre: Kamila Panduro
<br>
- Edad: 20
<br>
- Ocupación: Trabajadora de Sedapal
<br>
- Browser: Google Chrome
<br>
- Device: Teléfono Samsung
<br>
- Distrito: Santiago de Surco
<br>
- Timing: 13:53
<br>
- Marca: Sunass
<br>
<div style="text-align: center;">
    
![image](https://github.com/user-attachments/assets/6ef23f17-1237-4248-82eb-8016f7965f8a)


</div>

Kamila, trabajadora de una empresa proveedora de agua, señaló que los principales retos que enfrentan son la falta de equipos modernos, personal capacitado y los altos costos logísticos para llegar a zonas rurales. El proceso de análisis actual es lento, ya que deben recolectar muestras y enviarlas a laboratorios, lo que puede tomar varios días.
Indicó que utilizan principalmente hojas de cálculo y registros físicos, y en algunos casos herramientas como QGIS, pero no cuentan con un sistema digital integrado. Kamila considera que un sistema IoT sería clave para mejorar su trabajo, ya que permitiría una detección inmediata de problemas, reduciría costos y fortalecería la confianza de la comunidad. Sugiere que la solución incluya alertas automáticas, acceso a datos históricos y sensores que funcionen sin conexión constante.

Nombre: André Alonso Arroyo Ormeño
<br>
- Edad: 28
<br>
- Ocupación: Coordinador de monitoreo de calidad de agua
<br>
- Browser: Google Chrome
<br>
- Device: Samsung (móvil) / Acer (laptop)
<br>
- Distrito: Pueblo Nuevo, Chincha (Ica)

<br>
<div style="text-align: center;">
    
<img src="./assets/img/entrevista_andre.png"> 

[Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201719831_upc_edu_pe/IQAh77okvtbsRaFbmxJWP-dDAXTLvEN-xgelUIPuUu6O900?e=A7L9EV)
</div>

André, Coordinador de monitoreo de calidad de agua de 28 años que coordina el monitoreo en Pueblo Nuevo, comenta que sus mayores retos son la ausencia de datos en tiempo real, los tiempos muertos entre muestreo y resultados de laboratorio, y la dispersión de la información en planillas. Detalla que hoy el proceso incluye inspección en campo, mediciones rápidas in situ (cloro, pH, temperatura) y envío a laboratorio para análisis fisicoquímicos y microbiológicos; el control de cloro/pH es semanal o quincenal y el microbiológico mensual, con campañas extraordinarias ante incidentes. Le gustaría monitorear en tiempo real cloro, turbidez, pH, temperatura, conductividad, presión, caudal y nivel de tanque. Actualmente almacenan datos en Excel/Sheets y usan QGIS para mapas. Ante problemas, notifican, aíslan tramos, ajustan dosificación de cloro, purgan la red y activan abastecimiento alterno, informando a la comunidad. Los costos clave son transporte/viáticos, insumos y análisis de laboratorio. La detección puede darse en horas, pero la confirmación tarda 3–7 días. Considera que un sistema IoT permitiría alertas tempranas, mayor trazabilidad y transparencia, además de optimizar rutas y mantenimiento. Ve como imprescindibles alertas configurables, dashboard web/móvil con históricos, georreferenciación, modo offline/energía solar, gestión de roles y API para integrar con sistemas existentes.

### 2.2.3. Análisis de entrevistas
**Segmento 1: Habitantes**

**Estadísticas y Aspectos comunes:**
- Edades entre 20 y 34 años.
- Uso principal de teléfonos móviles (iPhone y Samsung).
- Navegadores más usados: Google Chrome.
- Procedencia de zonas urbanas marginales y rurales (Chincha Alta, Ica, Pueblo Libre).

**Características Objetivas:**
- Consumo de agua proveniente de camiones cisterna.
- Bajo acceso a información oficial sobre calidad del agua.
- Métodos caseros como hervir el agua para intentar garantizar su consumo.
- Uso activo de dispositivos móviles para la comunicación y búsqueda de información.

**Características Subjetivas:**
- Preocupación constante por la calidad del agua.
- Desconfianza hacia las fuentes oficiales de información sobre el estado del agua.
- Disposición a participar en iniciativas comunitarias que busquen mejorar el acceso y control del agua.
- Alta valoración de la transparencia y la información en tiempo real para mejorar su calidad de vida.

---

**Segmento 2: Proveedores**

**Estadísticas y Aspectos comunes:**
- Edad promedio de 24 años.
- Profesionales técnicos relacionados al sector hídrico.
- Uso de dispositivos móviles y laptops (Samsung, Acer).
- Trabajo basado en mediciones físicas y reportes manuales en zonas urbanas como SMP.

**Características Objetivas:**
- Dificultad para obtener datos rápidos sobre calidad del agua.
- Dependencia de procedimientos manuales y supervisión técnica tradicional.
- Costos logísticos relevantes asociados al monitoreo de agua (transporte, personal, tiempo).
- Uso de tecnologías básicas (correo, teléfono) para comunicación.

**Características Subjetivas:**
- Alta apertura a soluciones tecnológicas que agilicen la toma de decisiones.
- Reconocimiento de la necesidad de alertas en tiempo real sobre problemas de calidad del agua.
- Interés por optimizar procesos de medición y respuesta a través de tecnologías IoT.
- Valoración de herramientas que mejoren la eficiencia y reduzcan costos operativos.

### Datos Estadisticos

![Es1](./assets/img/Comparacion_Edad_Promedio.png)

![Es2](./assets/img/Ubicaciones_por_Segmento.png)

Los gráficos presentan datos relevantes sobre segmentos demográficos y su distribución geográfica. En la Comparación de Edad Promedio por Segmento, se observa que la edad promedio varía significativamente entre los segmentos analizados (habitantes y proveedores), con un rango de 0 a 25 años. Esto sugiere diferencias generacionales marcadas, donde un grupo podría ser notablemente más joven que el otro, lo que podría influir en patrones de consumo, necesidades de servicios o dinámicas laborales. Sin embargo, la falta de valores exactos limita una interpretación más precisa.

Por otro lado, el gráfico Ubicaciones por Segmento revela la distribución geográfica de habitantes y proveedores en localidades como Chincha Alta, Ica, Pueblo Libre y SMP. Las cantidades, representadas en una escala de 0.0 a 0.8, indican variaciones en la concentración de estos segmentos según la zona.

## 2.3. Needfinding

Para crear una solución que responda a las necesidades específicas de los usuarios, realizaremos la identificación del User persona, User Task Matrix, User Journey Maps, Empathy Mapping y As-is Scenario Mapping.

### 2.3.1. User Personas

Se han elaborado los User Persona correspondientes a cada uno de nuestros segmentos objetivos. Estos segmentos incluyen, por un lado, a los pobladores de zonas urbanas y rurales que enfrentan dificultades para acceder y gestionar un suministro de agua potable; y por otro lado, a los proveedores de agua. La construcción de estos perfiles se ha basado en los datos obtenidos a partir de las entrevistas realizadas. 

Los user persona nos permiten entender el perfil y comportamiento de cada segmento, ayudando a identificar sus necesidades técnicas y objetivos de forma general.

### Segmento 1: Habitantes

Presentamos a Mario López, un joven que reside en una zona urbana y enfrenta serias dificultades con el abastecimiento de agua. Este user persona representa a otro de nuestros segmentos objetivos, y fue creado a partir del análisis de problemáticas reales identificadas durante el proceso de entrevistas.

**Enlace para visualizar el User Persona de Habitantes realizado en UXPressia:**
[https://uxpressia.com/w/mDdvz/p/mIlB8](https://uxpressia.com/w/mDdvz/p/mIlB8)

<img src="./assets/user-personas/segmento-domestico.png"/>

### Segmento 2: Proveedores

Presentamos a Gabriel Gonzales, un user persona construido a partir de la información recopilada durante las entrevistas. Gracias a este proceso, fue posible identificar sus habilidades, motivaciones, frustraciones, canales de comunicación, permitiendo así una comprensión más profunda del perfil correspondiente a uno de nuestros segmentos objetivos.

**Enlace para visualizar el User Persona de Proveedores realizado en UXPressia:** [https://uxpressia.com/w/mDdvz/p/SLYog](https://uxpressia.com/w/mDdvz/p/SLYog)

<img src="./assets/user-personas/segmento-negocio.png"/>


### 2.3.2. User Task Matrix
El user task matrix permite identificar y comparar los procesos clave de cada segmento, destacando sus similitudes en cuanto a frecuencia e importancia.


|**Necesidad / Función**|**Importancia (Habitantes)**|**Frecuencia (Habitantes)**|**Importancia (Proveedores de Agua)**|**Frecuencia (Proveedores de Agua)**|
| :- | :- | :- | :- | :- |
|Solicitar agua potable	|Alta|Alta|Alta|Alta|
|Coordinar horarios de entrega	|Alta|Alta|Alta|Alta|
|Verificar calidad del agua	|Alta|Media|Alta|Alta|
|Pagar por el servicio	|Alta|Media|Alta|Alta|
|Reportar problemas|Media|Media|Alta|Media|
|Planificar rutas de distribución	|Baja|Baja|Alta|Media|
|Gestionar inventario de agua disponible|Baja|Alta|Alta|<p>Media</p><p></p>|




En la matriz presentada, se pueden observar las siguientes tareas con mayor frecuencia e importancia:

- **Habitantes**:

  - **Solicitar agua potable y coordinar horarios de entrega**  
    Funcionalidad **más crítica**, con **alta importancia y frecuencia**. 
    Los habitantes necesitan un sistema confiable para pedir agua y conocer los horarios exactos de entrega, eliminando la incertidumbre actual.

  - **Verificar calidad del agua y pagar por el servicio**  
    Tareas de **alta importancia**pero **frecuencia media**.
    Requieren métodos sencillos para comprobar la calidad del agua y realizar pagos seguros.

  - **Reportar problemas**  
    De **importancia y frecuencia media**. No forman parte de su rutina diaria, por lo que pueden ofrecerse como funciones secundarias u opcionales.
    Necesitan un canal formal para reportar incidencias, con seguimiento garantizado.


- **Proveedores de Agua**:

  - **Verificar calidad del agua, gestionar inventario y planificar rutas**  
    Tareas **críticas y frecuentes**, esenciales esenciales para su operación diaria.
    Requieren herramientas para optimizar rutas, controlar inventarios en tiempo real y garantizar la calidad del servicio.

  - **Consultar historial de consumo y calidad** y **gestionar múltiples sensores IoT**  
    Funcionalidades con **alta importancia y frecuencia**.
    Necesitan un sistema integrado para gestionar pagos digitales y atender reportes de manera eficiente.

  - **Coordinar horarios de entrega**  
    Actividades de **alta importancia** y de **frecuencia alta**.
    


### 2.3.3. User Journey Mapping
El User Journey Mapping se desarrolló para comprender la experiencia de los usuarios al interactuar con nuestra plataforma. Este mapeo detalla cada paso que el usuario realiza, los obstáculos que puede encontrar, y las emociones que surgen en el proceso. Así, nos ayuda a identificar oportunidades para mejorar la usabilidad y satisfacción del usuario.

### Segmento 1: Habitantes

En este User Journey Map se muestra la experiencia actual del habitante responsable de gestionar el agua en su hogar. El proceso incluye la detección manual del nivel de agua, la solicitud de abastecimiento, la recepción y el almacenamiento. Identificamos problemas como la falta de precisión, comunicación ineficiente y riesgos de contaminación, lo que genera frustración e incertidumbre en el usuario.

**Enlace para visualizar el User Journey Map de Habitantes realizado en UXPressia:** [https://uxpressia.com/w/mDdvz/m/Q2oFD](https://uxpressia.com/w/mDdvz/m/Q2oFD)

![segmento-habitante](./assets/img/segmento-habitante.png)


### Segmento 2: Proveedores

En este User Journey Map decribimos el recorrido actual del proveedor responsable de coordinar y supervisar la distribución de agua. Desde la planificación de rutas hasta la presentación de informes a las autoridades, el proveedor enfrenta limitaciones como la falta de información en tiempo real, baja eficiencia en la comunicación y poca visibilidad operativa. Estas dificultades afectan la toma de decisiones, el seguimiento de entregas y el cumplimiento con las normas.

**Enlace para visualizar el User Journey Map de Proveedores realizado en UXPressia:** 

[https://uxpressia.com/w/mDdvz/m/wtXHH](https://uxpressia.com/w/mDdvz/m/wtXHH)

![segemnto-proveedores](<./assets/img/gabrielGonzales.png>)


### 2.3.4. Empathy Mapping

Para la creación del Empathy Map, hemos utilizado la información obtenida de nuestros dos User Personas que representan nuestro segmento objetivo. Este mapa nos permite profundizar en la comprensión de las necesidades, pensamientos, emociones y comportamientos de los usuarios, ayudándonos a diseñar soluciones más alineadas con sus expectativas y experiencias reales.


### Segmento 1: Habitantes
En el siguiente Empathy Map tenemos a Mario Lopez, un joven que vive en una zona urbana en Chincha. Él lucha diariamente por garantizar agua segura para su familia y su comunidad. Podemos observar su experencia, la cual refleja los desafíos de miles de personas que dependen de camiones cisterna.

**Enlace para visualizar el Empathy Map de Proveedores realizado en UXPressia:**
[https://uxpressia.com/w/mDdvz/p/ZQOfG](https://uxpressia.com/w/mDdvz/p/ZQOfG) 
<img src="./assets/empathy-mapping/segmento-domestico.png"/>

### Segmento 2: Proveedores
En el siguiente Empathy Map observamos la perspectiva de Gabriel Gonzales, encargado del
área principal de la proveedora de agua más grande Chincha. Dentro de su perfil podemos observar los desafíos sa los que se enfrenta como gestionar de recursos limitados mientrasse cumplen regulaciones estrictas y demandas de usuarios insatisfechos.

**Enlace para visualizar el Empathy Map de Proveedores realizado en UXPressia:**
[https://uxpressia.com/w/mDdvz/p/wA0jm](https://uxpressia.com/w/mDdvz/p/wA0jm) 
<img src="./assets/empathy-mapping/segmento-negocio.png"/>

### 2.3.5. As-is Scenario Mapping

Aquí tenemos el As-Is Scenario para el segmento de habitantes, que contiene un proceso donde los pedidos se realizan por llamadas o mensajes sin confirmación inmediata, las entregas se coordinan verbalmente sin horarios fijos, los pagos son en efectivo sin comprobantes, no se verifica la calidad del agua y no existe un sistema formal de seguimiento o quejas.
### Segmento 1: Habitantes
**Enlace para visualizar el As-is Scenario Map de Proveedores realizado en Miro:** 
[https://miro.com/app/board/uXjVMhdPpY8=/?share_link_id=712775907835](https://miro.com/app/board/uXjVMhdPpY8=/?share_link_id=712775907835)


**Brainstorming:**

<img src="./assets/as-is-scenario-mapping/brainstorming/segmento-domestico.png"/>

**Identify the highs and lows:**

<img src="./assets/as-is-scenario-mapping/segmento-domestico.png"/>

**Positive Areas:**
* Alivio si le toca temprano.

**Negative Areas:**
* Rabia ante respuestas automáticas.
* Vergüenza al pedir ayuda.

**Blank Areas:**
* Podría ser útil explorar cómo es el flujo de la comunicación al solicitar agua.

Tenemos el As-Is Scenario para el segmento de proveedores, que contiene una operación desorganizada donde la gestión de pedidos se hace en libretas o por mensajes, las rutas se planifican manualmente, los cobros son en efectivo sin registros digitales, no hay control de inventario ni historial de entregas, y no pueden demostrar la calidad del agua que distribuyen.

### Segmento 2: Proveedores
**Enlace para visualizar el As-is Scenario Map de Proveedores realizado en Miro:** 
[https://miro.com/app/board/uXjVMhdPpY8=/?share_link_id=712775907835](https://miro.com/app/board/uXjVMhdPpY8=/?share_link_id=712775907835)


**Brainstorming:**

<img src="./assets/as-is-scenario-mapping/brainstorming/segmento-negocio.png"/>


**Identify the highs and lows:**


<img src="./assets/as-is-scenario-mapping/segmento-negocio.png"/>

**Positive Areas:**
* ***"El operario nuevo no sabe mentir"*** (esto nos indica tranparecia en su trabajo).

**Negative Areas:**
* Destruye evidencias de errores.
* ***"Los datos antiguos son mi coartada"***

**Blank Areas:**
* Profundizar en la carga emocional que conlleva manipular reportes.


## 2.4. Ubiquitous Languange
| **Term**                             | **Definition** |
|--------------------------------------|----------------|
| **Resident**                       | End user who consumes water at home and uses the platform to stay informed about service quality, water level, and alerts. |
| **Provider**                   | Entity responsible for monitoring, managing, and distributing water in a community or locality. |
| **IoT Sensor**                       | Device installed at strategic points that measures parameters such as water level, quality, or pressure in real time. |
| **Water Quality**                    | Value indicating whether the water is safe for consumption, based on chemical, physical, and biological parameters. |
| **Water Level**                      | Height of stored or distributed water, measured by sensors to anticipate shortages or overflows. |
| **Alert**                            | Automatic notification sent to users when a low level or unsafe water is detected. |
| **Consumption and Quality History**  | Record of water levels and quality over time, useful for analysis and monitoring. |
| **Report**                           | Automatically generated document with historical data, alerts, consumption, and water conditions. |
| **Dashboard**                        | Customized view (for inhabitants or providers) displaying relevant data, graphs, and alerts. |
| **Water Distribution**               | Logistical and technical process through which water is delivered from its source to households. |
| **Edge Computing**             | Procesamiento de datos realizado localmente en el nodo (sensor) para reducir latencia y operar sin internet. |
| **Web Platform/Mobile App**          | Digital interface accessible via computer or smartphone where users view and manage water service information. |
| **Device Monitoring**                | Functionality that allows providers to configure, monitor, or troubleshoot installed IoT sensors. |
| **Real-Time Visualization**          | Dynamic and continuous display of current data about the water system. |
| **Registered Users**                 | People with authenticated access to the platform, either inhabitants or providers, with differentiated functionalities. |
| **Machine Learning Model**                    | Algoritmo entrenado con datos históricos para detectar patrones y predecir el consumo futuro. |
| **Bronze Layer (Capa Bronce)**                    | Datos crudos y sin procesar recibidos directamente de la telemetría de los sensores IoT (Edge). |
| **Gold Layer (Capa Oro)**                    | Datos refinados y agregados (KPIs, reportes) listos para la toma de decisiones en el Dashboard Administrativo. |
| **IAM (Identity Management)**                    | Sistema centralizado (Auth0) que garantiza la autenticación segura y el control de acceso único (SSO). |
| **RBAC (Role-Based Access)**                    | Política de seguridad que restringe el acceso según el perfil del usuario (ej. Proveedor vs. Residente). |
| **Bounded Context**                    | Límite lógico que agrupa funcionalidades específicas del negocio (ej. "Gestión de Agua" separado de "Suscripciones"). |
| **Container (Contenedor)**                    | Unidades de software ejecutables y desplegables por separado, como la App Móvil, Web App o la API REST. |


# Capítulo III: Introducción

## 3.1. To-Be Scenario Mapping

En esta sección se describe cómo serían los escenarios ideales (To-Be) una vez implementada la solución propuesta por nuestro equipo. A partir de los mismos escenarios utilizados en el análisis As-Is, se plantea una visión futura optimizada, en la que los problemas identificados han sido resueltos o mitigados gracias a nuestra intervención.

Cada mapeo To-Be representa la experiencia del usuario mejorada, los escenarios están divididos por segmentos para mantener un enfoque claro y específico.

### Segmento 1: Habitantes 

Enlace para visualizar el As-is Scenario Map de Habitantes realizado en Miro: https://miro.com/app/board/uXjVIBKpWJQ=/?share_link_id=18556028670 

### Brainstorming:

![Brainstorming](./assets/img/Brain_Hab.png)

### To-Be Scenario Mapping 

![to be](./assets/img/to-be-hab.png)

### Segmento 2: Proveedores

Enlace para visualizar el As-is Scenario Map de Proveedores realizado en Miro: https://miro.com/app/board/uXjVIBKpWJQ=/?share_link_id=18556028670

### Brainstorming:

![Brainstorming](./assets/img/Brain_Prov.png)

### To-Be Scenario Mapping 

![to be](./assets/img/to-be-prov.png)

## 3.2. User Stories

El apartado de User Stories permite identificar las diversas situaciones que experimenta el usuario al interactuar con las diferentes áreas del proyecto, desde la página de inicio de sesión hasta las funcionalidades técnicas implementadas por el equipo de desarrollo. Su relevancia radica en que facilita la creación de un product backlog y, mediante los criterios de aceptación, podemos comprobar si estas historias se han cumplido correctamente.


**Epics y User Stories de AquaConecta**

|**Epic / Story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Relacionado con (Epic ID)**|
| - | - | - | - | - |
|**EP01**|**Dashboard and Analytics**|<p>**Como** usuario,</p><p>**Quiero** visualizar métricas de los sensores</p><p>**Para** garantizar un seguimiento continuo de mis tanques de agua.</p>|||
|**HU01**|**Ver nivel actual del agua de los habitantes**|<p>**Como** proveedor, </p><p>**Quiero** visualizar el nivel actual del agua de un habitante </p><p>**Para** conocer la cantidad disponible.</p>|<p>**Escenario 1: Vista general de todos los clientes**<br>**Dado** que el proveedor accede al dashboard de métricas,<br>**Cuando** visualiza la pantalla principal,<br>**Entonces** el sistema muestra el número total de clientes activos, consumo promedio y alertas pendientes.</p><p>**Escenario 2: Ver detalles por cliente<br>Dado** que el proveedor ver la información de residente,<br>**Cuando** selecciona un residente en específico,<br>**Entonces** el sistema muestra las métricas agrupadas por esa zona.</p>|**EP01**|
|**HU02**|**Ver métricas de del tanque de agua**|<p>**Como** habitante, </p><p>**Quiero** visualizar el resumen de métricas de mi tanque</p><p>**Para** conocer la cantidad disponible y solicitar el reabastecimiento correspondiente.</p>|<p>**Escenario 1: El sistema muestra correctamente la distancia medida<br>Dado** que el tanque tiene agua y el sensor funciona correctamente,<br>**Cuando** el sistema mide el nivel de agua,<br>**Entonces** la información se procesa y se registra para mostrar cuántos centímetros de agua hay disponibles.</p><p>**Escenario 2: Vista resumen móvil<br>Dado** que el habitante accede desde su dispositivo móvil,<br>**Cuando** ingresa a la pantalla principal,<br>**Entonces** el sistema muestra un resumen con consumo actual, promedio del mes y nivel del tanque.</p><p>**Escenario 3: Notificaciones de métricas<br>Dado** que el habitante tiene habilitadas las notificaciones,<br>**Cuando** su consumo es total<br>**Entonces** recibe una notificación con el resumen del consumo.</p>|**EP01**|
|**HU03**|<p>**Ver calidad del agua**</p><p></p><p></p>|<p>**Como** habitante, </p><p>**Quiero** que el sistema mida la calidad del agua, </p><p>**Para** saber si es segura para el consumo de mi familia.</p>|<p>**Escenario 1: Lectura de TDS exitosa<br>Dado** que el sensor de calidad está funcionando <br>**Cuando** se mide el nivel de sólidos disueltos (TDS),<br>**Entonces** el sistema calcula el valor en ppm y lo clasifica como excelente, buena, aceptable, mala, no potable o contaminada.</p><p>**Escenario 2: El sistema informa cuando el agua no es apta<br>Dado** que el valor de TDS supera los 600 ppm,<br>**Cuando** se realiza la medición,<br>**Entonces** el sistema muestra una advertencia indicando que el agua no debe consumirse.</p>|**EP01**|
|<p>**HU04**</p>|**Recibir datos actualizados constantemente**|<p>**Como** habitante,</p><p>**Quiero** que el sistema realice lecturas frecuentes del agua,</p><p>**Para** asegurarme de que la información sobre el nivel y la calidad esté siempre actualizada</p>|**Escenario 1: Lectura automática cada segundo<br>Dado** que el sistema está encendido,<br>**Cuando** pasa un segundo,<br>**Entonces** se ejecutan nuevas mediciones de nivel y calidad de agua sin que el usuario tenga que hacer nada.<br><br><p>**Escenario 2: Reintento ante fallo de lectura<br>Dado** que el sistema intenta actualizar los datos automáticamente, <br>**Cuando** una lectura falla por pérdida de conexión o error del sensor, <br>**Entonces** el sistema reintenta la actualización en el siguiente ciclo y muestra un mensaje de advertencia si el problema persiste.</p>|**EP01**|
|**EP02**|**Profile and Preferences**|<p>**Como** proveedor,</p><p>**Quiero** observar información detallada de mi empresa,</p><p>**Para** tomar decisiones informadas sobre el sistema</p>|||
|**HU05**|**Historial de alertas**|<p>**Como** proveedor,</p><p>**Quiero** ver una lista con todos reportes de los problemas que han tenido mis clientes, </p><p>**Para** tener un registro del problema y poder solucionarlo lo antes posible.</p>|**Escenario 1: Visualizar la sección de reportes**<br>**Dado** que el proveedor se encuentra en la página principal del sistema, <br>**Cuando** se dirige a la sección de reporte de problemas, <br>**Entonces** el sistema muestra la lista de los reportes generados por los clientes del proveedor con el nombre del residente, titulo del reporte, fecha de emisión y estado del reporte.<br><br><p>**Escenario 2: Visualizar detalles del reporte**<br>**Dado** que el proveedor visualiza su lista de reportes por cliente, <br>**Cuando** seleciona un reporte que requiere atención inmediata, <br>**Entonces** el sistema muestra detalles adicionales como descripción del problem.</p><br><p>**Escenario 3: Atender reporte generado por cliente**<br>**Dado** que el proveedor visualiza los datos adicionales de un reporte , <br>**Cuando** selecciona el botón de status, <br>**Y** lo actualiza dependiendo del estado en el que se encuentra el reporte, <br>**Entonces** el sistema actualiza el estado del reporte para el habitante.</p>|**EP02**|
|<p>**HU06**</p>|**Gestionar solicitudes de agua de residentes**|<p>**Como** proveedor, </p><p>**Quiero** visualizar y gestionar las solicitudes de agua de mis residentes,</p><p>**Para** atender eficientemente las necesidades de suministro de agua de mi comunidad.</p>|<p>**Escenario 1: Visualización de solicitudes de agua<br>Dado que** eel proveedor accede a la sección de solicitudes de agua<br>**Cuando** navega a sus Peticiones de Agua, <br>**Entonces** puede ver una lista de todas las solicitudes de agua registradas, <br>**Y** se visualiza el estado actual de cada solicitud.</p><p>**Escenario 2: Revisión de detalles de solicitud específica**<br>**Dado que** proveedor está viendo la lista de solicitudes<br>**Cuando** selecciona una solicitud especifica, <br>**Entonces** el sistema le da acceso a los detalles completos de la solicitud</p><p>**Escenario 3: : Actualización de fecha de entrega de agua**<br>**Dado que** el proveedor está revisando una solicitud de agua,<br>**Cuando** selecciona una nueva fecha de entrega, <br>**Y** confirma la actualización, <br>**Entonces** el sistema actualiza la fecha de entrega programada</p>|**EP02**|
|<p>**HU07**</p>|**Visualizar suscripciones activas del proveedor**|<p>**Como** proveedor, </p><p>**Quiero** ver todas las suscripciones de usuarios activas</p><p>**Para** tener un registro de todos mis usuarios/habitantes activos</p>|<p>**Escenario 1: Visualización de información detallada<br>Dado que** el proveedor** visualiza su información detallada<br>**Cuando** accede a su perfil de usuario<br>**Entonces** el sistema muestra todos sus datos registrados como nombre, email, RUC.</p><p>**Escenario 2: Visualización de suscripciones activas**<br>**Dado que** el proveedor visualiza la informacion de su cuenta, <br>**Cuando** ingresa a la seccion de sus suscripciones <br>**Entonces** se muestra el número de suscripciones activas</p>|**EP02**|
|**EP03**|**Landing Page** |**Como** usuario interesado en soluciones de acceso a agua,<br>**Quiero** navegar por una página clara, informativa y responsiva,                  **Para** comprender los beneficios de Aqua Conecta, explorar planes y contactar al equipo fácilmente.|||
|**HU08**|**Presentación clara de beneficios de valor**|**Como** visitante del sitio web,<br>**Quiero** visualizar claramente los beneficios de la plataforma Aqua Conecta,<br>**Para** entender cómo puede mejorar el acceso y control del agua en mi comunidad.|<p>**Escenario 1: Visualización de información importante de AquaConecta<br>Dado** que el visitante accede a la landing page desde cualquier dispositivo,                               **Cuando** navega hacia la sección “¿Por qué elegir Aqua Conecta?”,                    **Entonces** visualiza un mensaje informativo sobre AquaConecta.</p><p>**Escenario 2:  Visualizar beneficios principales<br>Dado** que el visitante quiere conocer sobre los beneficios,<br>**Cuando** sigue en la sección de beneficios<br>**Entonces** visualiza una lista detallada de todos los beneficios que se ofrecen</p>|**EP03**|
|**HU09**|**Información sobre segmentación de perfiles de usuario**|<p>**Como** usuario potencial**,**</p><p>**Quiero** identificar si la solución Aqua Conecta está dirigida a mi tipo de necesidad</p><p>**Para** saber si puedo beneficiarme directamente de sus servicios.</p>|<p>**Escenario 1: Comprensión de públicos objetivos para habitantes<br>Dado** que un visitante desea saber si la solución se alinea con sus necesidades,<br>**Cuando** accede a la sección “A quiénes queremos ayudar”,<br>**Entonces** puede leer y diferenciar los beneficios específicos para el segmento de habitantes.</p><p>**Escenario 2: Comprensión de públicos objetivos para proveedores<br>Dado** que un visitante desea saber si la solución se alinea con sus necesidades,<br>**Cuando** accede a la sección “A quiénes queremos ayudar”,<br>**Entonces** puede leer y diferenciar los beneficios específicos para el segmento de proveedores.</p><p></p>|**EP03**|
|**HU10**|**Comunicación del problema y la solución**|<p>**Como** visitante interesado,</p><p>**Quiero** entender el contexto del problema del acceso al agua y cómo AquaConecta lo resuelve,</p><p>**Para** evaluar el valor real que la solución puede aportar a mi comunidad o negocio.</p>|<p>**Escenario 1: Explicación clara sobre el desafío actual<br>Dado** que un visitante necesita entender el contexto de la crisis de agua,<br>**Cuando** llega a la sección “La problemática del agua”,<br>**Entonces** visualiza información y porcentajes sobre la problemática que está abordando.</p><p>**Escenario 2: Explicación clara sobre la solución<br>Dado** que un visitante necesita conocer en qué consiste la solución,<br>**Cuando** llega a la sección “Nuestra Solución”,<br>**Entonces** visualiza información sobre la implementación de la solución.</p>|**EP03**|
|**HU11**|**Comparación de planes y acciones de compra**|<p>**Como** visitante interesado en adquirir un servicio,</p><p>**Quiero** revisar los planes, precios y características de AquaConecta,</p><p>**Para** decidir si deseo solicitar un plan o contactar por asesoría.</p>|<p>**Escenario 1: Visualización de planes y precios<br>Dado** que un visitante desea conocer los planes disponibles,<br>**Cuando** navega a la sección “Nuestros Servicios”**,<br>Entonces** puede ver los planes disponibles, su precio y características, con opción para solicitar o agendar.</p><p>**Escenario 2: Visualización de servicios<br>Dado** que un visitante desea conocer los servicios disponibles,<br>**Cuando** navega a la sección “Nuestros Servicios”**,<br>Entonces** puede ver los servicios disponibles con su información.</p>|**EP03**|
|**HU12**|**Envío efectivo de consultas por formulario**|<p>**Como** usuario con preguntas o interés en Aqua Conecta,</p><p>**Quiero** poder llenar y enviar un formulario de contacto,</p><p>**Para** recibir asistencia, cotización o más información directamente del equipo**.**</p>|<p>**Escenario 1: Visualización del formulario de contacto<br>Dado** que un visitante tiene preguntas o desea más información,<br>**Cuando** se dirige a la sección “Contacta con nosotros”,<br>**Entonces** puede visualizar todas las secciones del formulario de contacto.</p><p>**Escenario 2: Envío de formulario de contacto<br>Cuando** un visitante quiere enviar su información de contacto<br>**Cuando** completa el formulario<br>**Entonces** se le enviaran todos los datos de contacto.</p>|**EP03**|
|**EP04**|**Identity and Access Management**|<p>**Como** usuario de la plataforma,</p><p>**Quiero** poder crear una cuenta, iniciar sesión y gestionar mi información personal, </p><p>**Para** acceder a los servicios del sistema de forma segura y personalizada.</p>|||
|**HU13**|**Registro de usuario Web**|<p>**Como** proveedor,</p><p>**Quiero** registrarme desde la plataforma web ingresando mis datos,</p><p>**Para** crear una cuenta y comenzar a gestionar mis servicios.</p>|<p>**Escenario 1: Registro completo desde el sitio web<br>Dado** que el usuario está en el formulario de registro<br>**Cuando** completa sus datos correctamente<br>**Entonces** se crea su cuenta y es redirigido al login.</p><p>**Escenario 2: Validación de campos vacíos<br>Dado** que el usuario no completa todos los campos requeridos<br>**Cuando** intenta registrar los datos<br>**Entonces** el sistema muestra mensajes de validación en los campos incompletos</p>|**EP04**|
|**HU14**|**Inicio de sesión de usuario móvil**|<p>**Como** habitante,</p><p>**Quiero** iniciar sesión desde la aplicación móvil,</p><p>**Para** acceder a mi cuenta y monitorear el estado del agua en mi hogar.</p>|<p>**Escenario 1: Inicio de sesión exitoso<br>Dado** que el usuario ingresa sus credenciales válidas en la aplicación<br>**Cuando** se encuentra en la sección de login<br>**Entonces** el sistema valida los datos y redirígeme al panel principal </p><p>**Escenario 2: Contraseña Incorrecta<br>Dado** que el usuario ingresa un nombre de usuario correcto pero contraseña incorrecta<br>**Cuando** intenta iniciar sesión<br>**Entonces** el sistema muestra un mensaje de error</p>|**EP04**|
|**HU15**|**Inicio de sesión de usuario web.**|<p>**Como** proveedor,</p><p>**Quiero** ingresar a la plataforma web con mis credenciales,</p><p>**Para** gestionar mis servicios y usuarios asociados de forma segura.</p>|<p>**Escenario 1: Inicio de sesión exitoso<br>Dado** que el usuario ingresa sus credenciales válidas en la aplicación<br>**Cuando** se encuentra en la sección de login<br>**Entonces** el sistema valida los datos y redirígeme a la lista de residentes.</p><p>**Escenario 2: Contraseña Incorrecta<br>Dado** que el usuario ingresa un nombre de usuario correcto pero contraseña incorrecta<br>**Cuando** intenta iniciar sesión<br>**Entonces** el sistema muestra un mensaje de error.</p>|**EP04**|
|**HU16**|**Visualización y Edición del perfil de usuario móvil**|<p>**Como** habitante,</p><p>**Quiero** ver y editar mi información personal desde la aplicación móvil,</p><p>**Para** mantener mis datos actualizados fácilmente.</p>|<p>**Escenario 1: Acceso al perfil desde menú<br>Dado** que el usuario accede al menú de la aplicación<br>**Cuando** se dirige a la sección de perfil<br>**Entonces** el sistema muestra su información personal actual</p><p>**Escenario 2: Edición exitosa de perfil<br>Dado** que el usuario móvil accede a la pantalla de perfil<br>**Cuando** accede a la edición de sus datos<br>**Y** los actualiza<br>**Entonces** el sistema confirma los cambios con un mensaje</p><p>**Escenario 3: Error por formato inválido<br>Dado** que el usuario intenta ingresar un número de teléfono inválido<br>**Cuando** intenta guardar los datos<br>**Entonces** el sistema bloquea el envío y muestra un mensaje de error.</p>|**EP04**|
|**HU17**|**Visualización y Edición del perfil de usuario web**|<p>**Como** proveedor,</p><p>**Quiero** acceder y modificar mi perfil desde la plataforma web,</p><p>**Para** gestionar mis datos de contacto y empresa de manera segura.</p>|<p>**Escenario 1: Acceso al perfil desde la pantalla principal<br>Dado** que el usuario accede a la pantalla principal de la web<br>**Cuando** se dirige a la sección de perfil <br>**Entonces** el sistema muestra su información personal actual </p><p>**Escenario 2: Edición exitosa de perfil<br>Dado** que el usuario web accede a la pantalla de perfil<br>**Cuando** accede a la edición de sus datos<br>**Y** los actualiza<br>**Entonces** el sistema confirma los cambios con un mensaje</p><p>**Escenario 3: Error por formato inválido<br>Dado** que el usuario intenta ingresar un número de teléfono inválido<br>**Cuando** intenta guardar los datos<br>**Entonces** el sistema bloquea el envío y muestra un mensaje de error.</p>|**EP04**|
|**HT01**|**Registro de credenciales de acceso**|<p>**Como** desarrollador,</p><p>**Quiero** implementar un endpoint para registrar nuevas cuentas de usuario,</p><p>**Para** permitir el acceso inicial a la plataforma de forma segura.</p>|<p>**Escenario 1: Registro exitoso de usuario a través de la API<br>Dado** que el endpoint "/api/v1/authentication/sign-up" está disponible  <br>**Cuando** se envía una solicitud POST con un username y password válidos  <br>**Entonces** se recibe una respuesta con estado 201  <br>**Y** el cuerpo de la respuesta incluye los datos del nuevo usuario junto con un identificador único.</p><p>**Escenario 2: Credenciales inválidas<br>Dado** que el endpoint "/api/v1/authentication/sign-up" está disponible  <br>**Cuando** se envía una solicitud POST con un rol incorrecto<br>**Entonces** se recibe una respuesta con estado 400.</p>|**EP04**|
|**HT02**|**Inicio de sesión de usuario a través de la API**|<p>**Como** desarrollador,</p><p>**Quiero** permitir que los usuarios inicien sesión mediante la API,</p><p>**Para** autenticar su identidad y generar tokens válidos de acceso.</p>|<p>**Escenario 1: Inicio de sesión exitoso <br>Dado** que el endpoint "/api/v1/authentication/sign-in" está disponible<br>**Cuando** se envía una solicitud POST con un correo electrónico y contraseña válidos<br>**Entonces** se recibe una respuesta con estado 200<br>**Y** el cuerpo de la respuesta incluye un token de autenticación válido y datos básicos del usuario.</p><p>**Escenario 2: Fallo al iniciar sesión con credenciales incorrectas<br>Dado** que el endpoint "/api/v1/authentication/sign-in" está disponible<br>**Cuando** se envía una solicitud POST con un correo electrónico o contraseña incorrectos<br>**Entonces** se recibe una respuesta con estado 401<br>**Y** el cuerpo de la respuesta incluye el mensaje "Credenciales incorrectas".</p>|**EP04**|
|**HT03**|**Gestión de perfiles a través de la API**|<p>**Como** desarrollador,</p><p>**Quiero** permitir que los usuarios inicien sesión mediante la API,</p><p>**Para** autenticar su identidad y generar tokens válidos de acceso.</p>|<p>**Escenario 1: Inicio de sesión exitoso <br>Dado** que el endpoint "/api/v1/authentication/sign-in" está disponible<br>**Cuando** se envía una solicitud POST con un correo electrónico y contraseña válidos<br>**Entonces** se recibe una respuesta con estado 200<br>**Y** el cuerpo de la respuesta incluye un token de autenticación válido y datos básicos del usuario</p><p>**Escenario 2: Fallo al iniciar sesión con credenciales incorrectas<br>Dado** que el endpoint "/api/v1/authentication/sign-in" está disponible<br>**Cuando** se envía una solicitud POST con un correo electrónico o contraseña incorrectos<br>**Entonces** se recibe una respuesta con estado 401<br>**Y** el cuerpo de la respuesta incluye el mensaje "Credenciales incorrectas".</p>|**EP04**|
|**EP05**|**Subscriptions and Payments**|<p>**Como** usuario del sistema,</p><p>**Quiero** gestionar y consultar suscripciones asociadas a sensores IoT,</p><p>**Para** asegurar un monitoreo adecuado de los dispositivos asignados a los residentes, con control de acceso y estado.</p><p></p>|||
|**HU18**|**Registrar un nuevo residente**|<p>**Como** proveedor, </p><p>**Quiero** registrar un nuevo residente </p><p>**Para** que se genere automáticamente una suscripción que incluya el sensor y habilite el monitoreo del servicio de agua.</p>|<p>**Escenario 1: Redirección al formulario de registro de residente<br>Dado** que el proveedor está en la lista de residentes,<br>**Cuando** se dirige a "Nuevo Residente",<br>**Entonces** es llevado al formulario de registro que incluye información del residente y procesamiento de pago.</p><p>**Escenario 2: Activación de suscripción tras completar registro y pago<br>Dado** que el proveedor completa los datos del residente en el formulario (nombre, apellido, documento, email, teléfono, dirección),<br>**Y** el sistema de pago MercadoPago procesa exitosamente el monto de S/ 200.00,<br>**Cuando** se confirma la transacción de pago,<br>**Entonces** se muestra que la suscripción quedó activa y vinculada al sensor y al residente.</p> <p>**Escenario 3: Manejo de error en el pago<br>Dado** que el proveedor completa los datos del residente, <br>**Cuando** el procesamiento del pago falla o es rechazado,<br>**Entonces** se muestra un mensaje de error específicon,<br>**Y** no se crea el residente ni la suscripción.</p>||
|**HU19**|**Añadir una nueva suscripción a un residente ya registrado**|<p>**Como** proveedor, </p><p>**Quiero** agregar una nueva suscripción a un residente ya registrado , </p><p>**Para** que mi cliente pueda tener varios sensores asignados a sus tanques de agua.</p>|<p>**Escenario 1: Visualizar lista de residentes<br>Dado** que el proveedor quiere buscar a un residente en especifico,<br>**Cuando** se dirige a su lista de residentes,<br>**Y** ingresa su nombre o id en la barra de búsqueda<br>**Entonces** el sistema le muestra el residente que esta buscando.</p><p>**Escenario 2: Agregar una nueva suscripció<br>Dado** que el proveedor encontró al residente,<br>**Cuando** lo selecciona,<br>**Y** agrega una nueva suscripción <br>**Entonces** el sistema le mostrar una ventana emergente donde se registra la cantidad de litro que tendrá el tanque.</p><p>**Escenario 3: Finalizar pago de nueva suscripción<br>Dado** que el proveedor ingreso el tamaño de almacenamiento del tanque,<br>**Cuando** confirma el pago,<br>**Entonces** el sistema muestra un mensaje de confirmación.</p>||
|**HU20**|**Ver suscripciones activas por residente**|<p>**Como** proveedor, </p><p>**Quiero** visualizar las suscripciones activas asociadas a los sensores de cada residente,</p><p>**Para** conocer el estado de monitoreo de mis habitantes.</p>|<p>**Escenario 1: Registro de nuevo sensor<br>Dado** que el proveedor está revisando la información de sus sensores,<br>**Cuando**decide agregar uno nuevo,<br>**Entonces** es llevado al formulario para registrar la suscripción correspondiente.</p><p>**Escenario 2: Activación de suscripción tras pago exitoso<br>Dado** que el proveedor completa los datos del sensor y realiza el pago,<br>**Cuando** la transacción se confirma con éxito,<br>**Entonces** se muestra que la suscripción quedó activa y vinculada al sensor y al residente.</p>||
|**HU21**|**Ver todas las suscripciones del sistema**|<p>**Como** administrador,</p><p>**Quiero** visualizar todas las suscripciones del sistema, </p><p>**Para** supervisar el uso de la plataforma por parte de proveedores y residentes.</p><p></p>|<p>**Escenario 1: Visualización de todas las suscripciones del sistema<br>Dado** que el administrador quiere revisar las suscripciones registradas,<br>**Cuando** accede a la opción correspondiente,<br>**Entonces** se muestra una lista con todas las suscripciones, incluyendo proveedor, residente, sensor y estado.</p><p>**Escenario 2: No hay suscripciones registradas<br>Dado** que el administrador intenta revisar las suscripciones,<br>**Cuando** no se encuentra ninguna registrada,<br>**Entonces** se muestra un mensaje indicando que no existen registros disponibles.</p>||
|**HU22**|**Visualizar suscripción del residente**|<p>**Como residente,** </p><p>**Quiero consultar el estado de mi suscripción** </p><p>**Para saber si mi sensor está activo y en funcionamiento.**</p>|<p>**Escenario 1: Visualizar suscripción del residente<br>Dado** que el residente inicia sesión,<br>**Cuando** revisa la opción “Mi suscripción”,<br>**Entonces** se muestra la información del sensor asociado y el estado actual de la suscripción (activa o inactiva).</p><p>**Escenario 2: Sin suscripción registrada<br>Dado** que el residente no tiene ninguna suscripción activa,<br>**Cuando** accede a “Mi suscripción”,<br>**Entonces** se muestra un mensaje indicando que aún no tiene sensores registrados o suscritos.</p>||
|**HU23**|**Chatbot de asistencia inteligente**|<p>**Como residente,** </p><p>**Quiero interactuar con un chatbot en la aplicación móvil para consultar el nivel de agua, estado de mi suscripción o solicitar reabastecimiento,** </p><p>**Para obtener respuestas rápidas y asistencia sin necesidad de conocimientos técnicos ni navegación compleja en la app.**</p>|<p>**Escenario 1: Consulta de nivel de agua por chatbot<br>Dado** que el residente abre el chatbot en la app móvil,<br>**Cuando** escribe "¿Cuánto agua tengo en mi tanque?",<br>**Entonces** el chatbot responde con el nivel de agua más reciente registrado por el sensor.</p><p>**Escenario 2: Solicitud de reabastecimiento por chatbot<br>Dado** que el habitante interactúa con el chatbot,<br>**Cuando** escribe "Necesito más agua" o selecciona la opción de solicitar reabastecimiento,<br>**Entonces**el chatbot genera automáticamente una solicitud en el sistema y envía confirmación al usuario.</p>||
|**HU24**|**CPredicción de consumo y solicitud automática**|<p>**Como proveedor,** </p><p>**Quiero que el sistema use un modelo de machine learning,** </p><p>**Para predecir el consumo de agua de los residentes y generar solicitudes automáticas de reabastecimiento.**</p>|<p>**Escenario 1: Predicción de consumo en base a patrones históricos<br>Dado** que el sistema ha almacenado al menos 30 días de datos de consumo de un residente,<br>**Cuando** el modelo de ML procesa los patrones de consumo,<br>**Entonces** predice con un margen de error máximo del 10% el nivel estimado de agua que tendrá el residente en los próximos 3 días.</p><p>**Escenario 2: Generación automática de solicitud de reabastecimiento<br>Dado** que el modelo de ML predice que el nivel del tanque bajará de 20% en menos de 48 horas,<br>**Cuando** el sistema valida la predicción,<br>**Entonces** genera automáticamente una solicitud de reabastecimiento y la asigna al proveedor correspondiente.</p>||
|**HT04**|**Crear suscripción a través de API REST**|<p>**Como** desarrollador,</p><p>**Quiero** crear una suscripción a través de la API</p><p>**Para** que cada sensor quede vinculado a un residente y a un proveedor, y así se habilite el monitoreo.</p><p></p>|<p>**Escenario 1: Crear suscripción con datos válidos<br>Dado** que el endpoint POST /subscriptions está disponible,<br>**Cuando** se envía una solicitud con los valores sensorId, residentId y providerId,<br>**Entonces** se responde con un código 201 Created,<br>**Y** en el cuerpo de la respuesta se incluye el subscriptionId, la fechaInicio y el estado con valor ACTIVA.</p><p>**Escenario 2: Crear suscripción para un sensor ya suscrito<br>Dado** que el endpoint POST /subscriptions está disponible,<br>**Y** el sensor ya cuenta con una suscripción activa,<br>**Cuando** se intenta crear otra suscripción usando el mismo sensorId,<br>**Entonces** se responde con un código 409 Conflict,<br>**Y** en el cuerpo se muestra el mensaje: "Ya existe una suscripción activa para este sensor."</p>||
|**HT05**|<p>**Obtener suscripciones por residente**</p><p></p>|<p>**Como** desarrollador, </p><p>**Quiero** exponer un endpoint que permita obtener las suscripciones asociadas a un residente, </p><p>**Para** que puedan ser consultadas fácilmente cuando se necesite.</p><p></p>|<p>**Escenario 1: Residente con suscripciones registradas<br>Dado** que el endpoint GET /residents/{id}/subscriptions está disponible,<br>**Cuando** se realiza una solicitud utilizando un residentId válido,<br>**Entonces** se responde con un código 200 OK,<br>**Y** el cuerpo de la respuesta incluye una lista de suscripciones, cada una con su sensorId, estado, fechaInicio y fechaFin.</p><p>**Escenario 2: Residente sin suscripciones<br>Dado** que el endpoint GET /residents/{id}/subscriptions está disponible,<br>**Cuando** se consulta a un residente que no tiene suscripciones registradas,<br>**Entonces** se responde con un código 200 OK,<br>**Y** el cuerpo de la respuesta contiene una lista vacía o un mensaje que indica que no hay suscripciones registradas.</p>||
|**HT06**|**Obtener todas las suscripciones del sistema**|<p>**Como** desarrollador,</p><p>**Q**uiero exponer un endpoint que permita listar todas las suscripciones registradas,** </p><p>**Para** que el administrador pueda supervisar su uso y gestión.</p><p></p>|<p>**Escenario 1: Usuario con rol administrador accede al listado<br>Dado** que el endpoint GET /subscriptions está disponible,<br>**Cuando** un usuario autenticado con rol ADMIN realiza la solicitud,<br>**Entonces** se responde con un código 200 OK,<br>**Y** en el cuerpo se devuelve una lista de suscripciones que incluye la información del sensor, proveedor, residente y el estado de cada una.</p><p>**Escenario 2: Usuario sin permisos accede al listado<br>Dado** que el endpoint GET /subscriptions está disponible,<br>**Cuando** un usuario autenticado sin el rol ADMIN intenta acceder,<br>**Entonces** se responde con un código 403 Forbidden,<br>**Y** se incluye un mensaje que indica que no cuenta con los permisos necesarios para acceder a este recurso.</p>||



## 3.3. Impact Mapping

### Segmento 1: Habitantes

Para el segmento del usuario final se elaboró un Impact Mapping con el objetivo de aumentar la participación activa en la plataforma y reducir la incertidumbre sobre la calidad del agua. Esta herramienta nos permitió identificar los comportamientos clave que se desean promover en los usuarios, como consultar el estado del agua y configurar alertas personalizadas. A partir de ello, se definieron deliverables y user stories que guían el desarrollo de funcionalidades útiles y alineadas con las necesidades reales de los habitantes.
**Enlace para visualizar el Impact Map de Habitantes realizado en UXPressia:**
[https://uxpressia.com/w/mDdvz/i/0Fem9](https://uxpressia.com/w/mDdvz/i/0Fem9)

<img src="./assets/impact-mapping/segmento-domestico.png"/>


### Segmento 2: Proveedores

En el caso del proveedor, el Impact Mapping se enfocó en facilitar la gestión de sensores y la producción de reportes para la toma de decisiones. Gracias a ello se establecieron los impacts esperados, como registrar y monitorear sensores activos, así como generar estadísticas clave del sistema. Esto permitió definir deliverables específicos y user stories que aseguran un desarrollo enfocado en la eficiencia operativa y el control del servicio por parte del proveedor.
**Enlace para visualizar el Impact Map de Proveedores realizado en UXPressia:**
[https://uxpressia.com/w/mDdvz/i/Ue2yy](https://uxpressia.com/w/mDdvz/i/Ue2yy)

<img src="./assets/impact-mapping/segmento-negocio.png"/>


## 3.4. Product Backlog

El Product Backlog es una lista priorizada de tareas, funcionalidades y requisitos necesarios para el desarrollo del proyecto, asegurando que se trabaje en los elementos más importantes y alineados con los objetivos del proyecto. Cada ítem del backlog incluye una descripción, prioridad y título.


<table>
  <thead>
    <tr>
      <th>Orden</th>
      <th>User Story Id</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>HU01</td>
      <td>Ver nivel actual del agua de los habitantes</td>
      <td>Como proveedor, quiero visualizar el nivel actual del agua de un habitante, para conocer la cantidad disponible.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>HU02</td>
      <td>Ver métricas del tanque de agua</td>
      <td>Como habitante, Quiero visualizar el resumen de métricas de mi tanque Para conocer la cantidad disponible y solicitar el reabastecimiento correspondiente.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>3</td>
      <td>HU03</td>
      <td>Ver calidad del agua</td>
      <td>Como habitante, Quiero que el sistema mida la calidad del agua, Para saber si es segura para el consumo de mi familia.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>4</td>
      <td>HU04</td>
      <td>Recibir datos actualizados constantemente</td>
      <td>Como habitante, Quiero que el sistema realice lecturas frecuentes del agua, Para asegurarme de que la información sobre el nivel y la calidad esté siempre actualizada.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>5</td>
      <td>HU05</td>
      <td>Historial de problemas de habitantes</td>
      <td>Como proveedor, Quiero ver una lista con todos reportes de los problemas que han tenido mis clientes, Para tener un registro del problema y poder solucionarlo lo antes posible.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>6</td>
      <td>HU06</td>
      <td>Gestionar solicitudes de agua de residentes</td>
      <td>Como proveedor, Quiero visualizar y gestionar las solicitudes de agua de mis residentes, Para atender eficientemente las necesidades de suministro de agua de mi comunidad.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>HU07</td>
      <td>Visualizar suscripciones activas del proveedor</td>
      <td>Como proveedor, Quiero ver todas las suscripciones de usuarios activas Para tener un registro de todos mis usuarios/habitantes activos.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>8</td>
      <td>HU08</td>
      <td>Presentación clara de beneficios de valor</td>
      <td>Como visitante del sitio web, Quiero visualizar claramente los beneficios de la plataforma Aqua Conecta, Para entender cómo puede mejorar el acceso y control del agua en mi comunidad.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>9</td>
      <td>HU09</td>
      <td>Información sobre segmentación de perfiles de usuario</td>
      <td>Como usuario potencial, Quiero identificar si la solución Aqua Conecta está dirigida a mi tipo de necesidad Para saber si puedo beneficiarme directamente de sus servicios.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>10</td>
      <td>HU10</td>
      <td>Comunicación del problema y la solución</td>
      <td>Como visitante interesado, Quiero entender el contexto del problema del acceso al agua y cómo AquaConecta lo resuelve, Para evaluar el valor real que la solución puede aportar a mi comunidad o negocio.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>11</td>
      <td>HU11</td>
      <td>Comparación de planes y acciones de compra</td>
      <td>Como visitante interesado en adquirir un servicio, Quiero revisar los planes, precios y características de AquaConecta, Para decidir si deseo solicitar un plan o contactar por asesoría.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>12</td>
      <td>HU12</td>
      <td>Envío efectivo de consultas por formulario	</td>
      <td>Como usuario con preguntas o interés en Aqua Conecta, Quiero poder llenar y enviar un formulario de contacto, Para recibir asistencia, cotización o más información directamente del equipo.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>13</td>
      <td>HU13</td>
      <td>Registro de usuario web</td>
      <td>Como proveedor, Quiero registrarme desde la plataforma web ingresando mis datos, Para crear una cuenta y comenzar a gestionar mis servicios.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>14</td>
      <td>HU14</td>
      <td>Inicio de sesión de usuario móvil</td>
      <td>Como habitante, Quiero iniciar sesión desde la aplicación móvil, Para acceder a mi cuenta y monitorear el estado del agua en mi hogar.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>15</td>
      <td>HU15</td>
      <td>Inicio de sesión web</td>
      <td>Como proveedor, Quiero ingresar a la plataforma web con mis credenciales, Para gestionar mis servicios y usuarios asociados de forma segura.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>16</td>
      <td>HU16</td>
      <td>Visualización y edición de perfil móvil</td>
      <td>Como habitante, Quiero ver y editar mi información personal desde la aplicación móvil, Para mantener mis datos actualizados fácilmente.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>17</td>
      <td>HU17</td>
      <td>Visualización y edición de perfil web</td>
      <td>Como proveedor, Quiero acceder y modificar mi perfil desde la plataforma web,Para gestionar mis datos de contacto y empresa de manera segura.
</td>
      <td>3</td>
    </tr>
    <tr>
      <td>18</td>
      <td>HU18</td>
      <td>Registrar nuevo residente</td>
      <td>Como proveedor, Quiero registrar un nuevo residente Para que se genere automáticamente una suscripción que incluya el sensor y habilite el monitoreo del servicio de agua.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>19</td>
      <td>HU19</td>
      <td>Añadir una nueva suscripción a un residente ya registrado</td>
      <td>Como proveedor, Quiero agregar una nueva suscripción a un residente ya registrado , Para que mi cliente pueda tener varios sensores asignados a sus tanques de agua.
    </td>
      <td>5</td>
    </tr>
    <tr>
      <td>20</td>
      <td>HU20</td>
      <td>Ver suscripciones activas por residente</td>
      <td>Como proveedor, Quiero visualizar las suscripciones activas asociadas a los sensores de cada residente, Para conocer el estado de monitoreo de mis habitantes.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>21</td>
      <td>HU21</td>
      <td> Ver todas las suscripciones del sistema	</td>
      <td>Como administrador, Quiero visualizar todas las suscripciones del sistema, Para supervisar el uso de la plataforma por parte de proveedores y residentes.</td>
      <td>3</td>
    </tr>
      <tr>
      <td>22</td>
      <td>HU22</td>
      <td>Visualizar suscripción del residente	</td>
      <td>Como residente, Quiero consultar el estado de mi suscripción Para saber si mi sensor está activo y en funcionamiento.</td>
      <td>2</td>
    </tr>
          <tr>
      <td>23</td>
      <td>HU23</td>
      <td>Chatbot de asistencia inteligente</td>
      <td>Como habitante,
Quiero interactuar con un chatbot en la aplicación móvil para consultar el nivel de agua, estado de mi suscripción o solicitar reabastecimiento,
Para obtener respuestas rápidas y asistencia en la app.</td>
      <td>5</td>
    </tr>
          <tr>
      <td>24</td>
      <td>HU24</td>
      <td>Predicción de consumo y solicitud automática</td>
      <td>Como proveedor,
Quiero que el sistema use un modelo de machine learning para predecir el consumo de agua de los residentes y generar solicitudes automáticas de reabastecimiento.</td>
      <td>8</td>
    </tr>
          <tr>
      <td>25</td>
      <td>HT01</td>
      <td>Registro de credenciales de acceso</td>
      <td>Como desarrollador, Quiero implementar un endpoint para registrar nuevas cuentas de usuario, Para permitir el acceso inicial a la plataforma de forma segura.</td>
      <td>5</td>
    </tr>
          <tr>
      <td>26</td>
      <td>HT02</td>
      <td>Inicio de sesión API</td>
      <td>Como desarrollador, Quiero permitir que los usuarios inicien sesión mediante la API, Para autenticar su identidad y generar tokens válidos de acceso.
</td>
      <td>5</td>
    </tr>
          <tr>
      <td>27</td>
      <td>HT03</td>
      <td>Gestión de perfiles vía API</td>
      <td>Como desarrollador, Quiero permitir que los usuarios inicien sesión mediante la API, Para autenticar su identidad y generar tokens válidos de acceso.
</td>
      <td>5</td>
    </tr>
          <tr>
      <td>28</td>
      <td>HT04</td>
      <td>Crear suscripción vía API REST</td>
      <td> Como desarrollador, Quiero crear una suscripción a través de la API Para que cada sensor quede vinculado a un residente y a un proveedor, y así se habilite el monitoreo
</td>
      <td>8</td>
    </tr>
              <tr>
      <td>29</td>
      <td>HT05</td>
      <td>Obtener suscripciones por residente</td>
      <td>Como desarrollador, Quiero exponer un endpoint que permita obtener las suscripciones asociadas a un residente, Para que puedan ser consultadas fácilmente cuando se necesite.
</td>
      <td>3</td>
    </tr>
              <tr>
      <td>30</td>
      <td>HT06</td>
      <td>Obtener todas las suscripciones del sistema</td>
      <td>Como desarrollador, Quiero exponer un endpoint que permita listar todas las suscripciones registradas, Para que el administrador pueda supervisar su uso y gestión.</td>
      <td>2</td>
    </tr>
  </tbody>
</table>



# Chapter IV: Solution Software Design

## 4.1. Strategic-Level Atrribute-Driven Desing

### 4.1.1. Design Purpose

El propósito del diseño arquitectónico del sistema AquaConecta es definir una solución tecnológica integral que soporte de manera robusta los procesos de monitoreo, gestión y distribución de agua potable en comunidades vulnerables. Dado que el sistema combina dispositivos físicos (sensores IoT en tanques domésticos) con aplicaciones digitales (plataforma web para proveedores y aplicación móvil para habitantes), la arquitectura debe responder a una serie de desafíos estratégicos:

- **Conectar el mundo físico con el digital**: Integrar los sensores IoT instalados en los tanques de agua de los habitantes con la nube y las aplicaciones cliente, asegurando que los datos sobre cantidad y calidad del agua se transmitan y procesen en tiempo real.

- **Soportar distintos perfiles de usuarios**: Diseñar un ecosistema donde proveedores de agua y habitantes puedan acceder a información confiable, cada uno con vistas y permisos específicos. Esto implica manejar autenticación segura, gestión de perfiles y trazabilidad de acciones.

- **Asegurar la sostenibilidad y escalabilidad**: La arquitectura debe ser lo suficientemente flexible para comenzar en un piloto acotado (Pueblo Nuevo, Chincha) y escalar gradualmente hacia más comunidades sin que el desempeño del sistema se degrade. Se busca garantizar que, a medida que se integren más sensores y usuarios, la infraestructura tecnológica pueda crecer horizontal y verticalmente.

- **Garantizar atributos de calidad críticos**:

  **Disponibilidad**: Que el sistema esté accesible incluso en entornos con conectividad limitada.

  **Seguridad**: Protección de datos sensibles de usuarios y de métricas ambientales.

  **Rendimiento**: Procesar datos en tiempo real sin retrasos que afecten la toma de decisiones.

  **Mantenibilidad**: Facilitar la incorporación de nuevas funcionalidades, como predicción de consumo mediante machine learning o integración con chatbots de soporte.

- **Apoyar la toma de decisiones basada en datos**: El diseño arquitectónico busca transformar datos crudos provenientes de los sensores en información visual, comprensible y accionable para habitantes y proveedores. Esto incluye reportes, alertas automáticas y dashboards que contribuyan a mejorar la eficiencia del servicio.

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1 Primary Functionality (Primary User Stories)

El núcleo funcional de AquaConecta se centra en habilitar la trazabilidad y transparencia en el acceso al agua potable, tanto para los habitantes como para los proveedores. Se identifican como funcionalidades primarias las siguientes:

- **Monitoreo de agua en tiempo real (HU01, HU02, HU03, HU04)**:
Estas historias permiten que los habitantes visualicen el nivel de agua, métricas de su tanque y la calidad del recurso, mientras que los proveedores pueden conocer la disponibilidad de agua en cada vivienda. El objetivo es ofrecer información confiable y en tiempo real que guíe la toma de decisiones sobre consumo y distribución.

- **Gestión de solicitudes y problemas (HU05, HU06)**:
A través de estas funcionalidades, los proveedores reciben solicitudes de reabastecimiento y reportes de incidencias de los habitantes, lo que mejora la eficiencia operativa y la capacidad de respuesta ante situaciones críticas.

- **Gestión de suscripciones y residentes (HU18, HU19, HU20, HU22)**:
Estas historias aseguran que cada habitante esté vinculado a sensores activos en sus tanques mediante una suscripción gestionada por el proveedor. Permiten registrar nuevos residentes, añadir sensores adicionales y consultar el estado de la suscripción, garantizando un monitoreo continuo y confiable.

- **Funcionalidades emergentes de inteligencia artificial (HU23, HU24)**:
Estas historias representan la innovación central del sistema. El chatbot inteligente (HU23) permite a los habitantes interactuar fácilmente con la plataforma para consultar niveles de agua, estado de sus suscripciones o generar solicitudes, sin necesidad de conocimientos técnicos. Por su parte, la predicción de consumo y generación automática de solicitudes (HU24) habilita a los proveedores a optimizar la distribución anticipándose a la demanda, mediante modelos de machine learning que aprenden patrones de uso y reducen el riesgo de desabastecimiento.

En conjunto, estas historias de usuario constituyen la columna vertebral del sistema AquaConecta, ya que sin ellas no sería posible habilitar el servicio principal: el monitoreo y gestión inteligente del agua potable en comunidades con acceso limitado.

#### 4.1.2.2 Quality attribute Scenarios


#### Escenario 1: Disponibilidad en la consulta de datos


| **Campo** | **Descripción** |
|-----------|----------------|
| **ID** | QA-01 |
| **Atributo** | Disponibilidad |
| **Fuente** | Habitante |
| **Estímulo** | Consulta el nivel de agua en su aplicación móvil |
| **Artefacto** | Aplicación móvil – módulo de visualización de tanque |
| **Entorno** | Conectividad móvil limitada (3G/4G) |
| **Respuesta** | El sistema retorna el nivel de agua registrado más reciente, incluso si no hay conexión estable |
| **Medida** | Tiempo de respuesta < 3 segundos en el 99% de las consultas |

**Descripción:** Cada vez que un habitante consulta el estado de su tanque, el sistema debe mostrar de manera inmediata la última medición registrada, ya sea desde la nube o desde un caché local en el dispositivo. En caso de baja conectividad, la app debe funcionar en modo offline y sincronizar automáticamente los datos al restablecerse la red, garantizando que ninguna lectura se pierda o muestre valores desactualizados por más de 15 minutos.

#### Escenario 2: Seguridad en autenticación

| **Campo** | **Descripción** |
|-----------|----------------|
| **ID** | QA-02 |
| **Atributo** | Seguridad |
| **Fuente** | Proveedor |
| **Estímulo** | Intenta iniciar sesión desde la plataforma web |
| **Artefacto** | Módulo de autenticación web |
| **Entorno** | Usuario externo accediendo desde red pública |
| **Respuesta** | El sistema valida credenciales mediante autenticación segura y encripta la sesión |
| **Medida** | 100% de los datos transmitidos deben estar cifrados (TLS 1.2+) |

**Descripción:** Cada intento de inicio de sesión debe validar credenciales mediante un servidor seguro, con encriptación en tránsito (TLS 1.2+) y en reposo (AES-256). Si se detectan intentos de acceso no autorizados, el sistema debe registrar el evento y bloquear al usuario tras 5 intentos fallidos consecutivos. Además, todas las sesiones deben expirar automáticamente tras 15 minutos de inactividad para reducir riesgos de secuestro de sesión.

#### Escenario 3: Escalabilidad en la gestión de sensores

| **Campo** | **Descripción** |
|-----------|----------------|
| **ID** | QA-03 |
| **Atributo** | Escalabilidad |
| **Fuente** | Sistema (incremento en la red IoT) |
| **Estímulo** | Se duplican los sensores activos en la comunidad (de 500 a 1000) |
| **Artefacto** | API backend de recepción de datos IoT |
| **Entorno** | Operación normal con crecimiento de usuarios |
| **Respuesta** | El sistema procesa los datos sin pérdida ni retraso significativo |
| **Medida** | Latencia promedio de actualización < 5 segundos por sensor |

**Descripción:** Cuando se incremente el número de sensores conectados, el backend debe ser capaz de recibir y almacenar lecturas concurrentes en tiempo real sin pérdida de paquetes. Todas las nuevas mediciones deben reflejarse correctamente en los dashboards de proveedores y habitantes en un tiempo máximo de 5 segundos desde su recepción. Además, el sistema debe escalar horizontalmente con la incorporación de más instancias de procesamiento en la nube sin requerir interrupciones en el servicio.

#### Escenario 4: Confiabilidad ante desconexión de sensores

| **Campo** | **Descripción** |
|-----------|----------------|
| **ID** | QA-04 |
| **Atributo** | Confiabilidad |
| **Fuente** | Sensor IoT en tanque domiciliario |
| **Estímulo** | El sensor pierde conexión con el servidor central |
| **Artefacto** | Microcontrolador IoT con almacenamiento local |
| **Entorno** | Red inestable en zonas rurales |
| **Respuesta** | El sensor almacena temporalmente los datos y los envía cuando se restablece la conexión |
| **Medida** | Reintento automático con sincronización en un máximo de 5 minutos |

**Descripción:** Ante una pérdida de conectividad, el sensor debe continuar realizando mediciones locales en intervalos de 5 minutos y almacenarlas en memoria. Una vez reestablecida la conexión, el dispositivo debe transmitir de forma ordenada y sin pérdida todos los datos acumulados al servidor, asegurando consistencia en las gráficas de consumo. En ningún caso deben existir huecos en el historial de datos superiores a 10 minutos.

#### Escenario 5: Usabilidad en la interfaz de usuario

| **Campo** | **Descripción** |
|-----------|----------------|
| **ID** | QA-05 |
| **Atributo** | Usabilidad |
| **Fuente** | Habitante |
| **Estímulo** | Ingresa a la aplicación móvil para verificar el estado de su suscripción y tanque |
| **Artefacto** | Interfaz gráfica móvil |
| **Entorno** | Usuario con conocimientos básicos de tecnología |
| **Respuesta** | El sistema presenta el estado del agua y de la suscripción en máximo 3 pasos de navegación |
| **Medida** | 90% de los usuarios pueden completar la tarea sin necesidad de soporte |

**Descripción:** La aplicación debe mostrar en la pantalla principal el nivel actual de agua y el estado de la suscripción, con iconografía clara y colores diferenciados para estados críticos (ej. tanque vacío o sensor inactivo). Todas las interacciones deben requerir un máximo de 3 clics, y los textos deben estar redactados en un lenguaje sencillo. El diseño debe validarse mediante pruebas de usabilidad con al menos 10 habitantes del piloto, asegurando que la mayoría complete las tareas sin asistencia externa.

#### Escenario 6: Precisión en la predicción de consumo

| **Campo** | **Descripción** |
|-----------|----------------|
| **ID** | QA-06 |
| **Atributo** | Exactitud / Confiabilidad |
| **Fuente** | Proveedor del servicio de agua |
| **Estímulo** | El proveedor consulta las predicciones de consumo generadas por el modelo de machine learning. |
| **Artefacto** | Módulo de predicción de consumo (ML). |
| **Entorno** | El sistema cuenta con un histórico de al menos 30 días de datos de consumo de cada residente. |
| **Respuesta** | El modelo de ML calcula el consumo esperado para los próximos 3 días y actualiza el sistema con los valores proyectados. |
| **Medida** | El margen de error de las predicciones no debe superar el 10% respecto al consumo real registrado. |

**Descripción:** El sistema de predicción debe ser capaz de anticipar la demanda de agua de cada residente con una precisión suficiente para que los proveedores puedan planificar de forma eficiente las rutas de distribución. La exactitud del modelo se evalúa comparando los consumos reales con las predicciones realizadas, y el error aceptable es de hasta un 10%. Esto asegura que las solicitudes automáticas de reabastecimiento se generen de forma confiable, evitando tanto el desabastecimiento como los envíos innecesarios.

#### 4.1.2.3 Constraints

El diseño arquitectónico de AquaConecta se encuentra condicionado por un conjunto de restricciones que definen los límites técnicos, operativos y organizacionales dentro de los cuales debe desarrollarse la solución. A continuación, se detallan las principales restricciones identificadas.

**Restricciones Tecnológicas**:

- Hardware IoT: El sistema debe operar con microcontroladores de bajo costo (ej. ESP32/ESP8266) programados en C++, capaces de medir niveles y calidad del agua.

- Arquitectura IoT: Se debe incorporar un nodo Edge (raspberry pi u otro gateway ligero) que procese localmente los datos de los sensores. Este nodo realizará filtrado, agregación y envío diferido hacia la nube, garantizando resiliencia en entornos con conectividad limitada.

- Estilo arquitectónico backend: El backend debe implementarse bajo un monolito modular, con separación de capas (presentación, lógica de negocio y persistencia). Esta decisión se debe a que el equipo es reducido y se prioriza la simplicidad, mantenibilidad y menor costo de despliegue inicial frente a arquitecturas distribuidas más complejas.

- Aplicaciones cliente: Web desarrollada con Angular y móvil desarrollada con Flutter (Android/iOS).

- Infraestructura en la nube: Despliegue en servicios escalables tipo PaaS/IaaS (ej. AWS, GCP o Azure), con soporte para balanceo de carga y almacenamiento relacional/noSQL.

- Inteligencia artificial: La arquitectura debe integrar un motor de IA conversacional para soporte al usuario y un módulo de machine learning predictivo para anticipar patrones de consumo, ya sea alojados en la nube o en el edge, con capacidad de entrenar y actualizar modelos.

**Restricciones Operativas**:

- Conectividad limitada: El sistema debe garantizar operación en zonas rurales con acceso intermitente a internet, habilitando almacenamiento temporal en sensores y sincronización a través del edge node.

- Entorno geográfico: El piloto inicial está delimitado al asentamiento humano 28 de Julio en Pueblo Nuevo, Chincha, lo que condiciona la instalación y pruebas de campo a esa realidad local.

- Integración con actores externos: La plataforma debe ser capaz de interoperar con sistemas de municipalidades, EPS Semapach y ONGs mediante reportes exportables o servicios API.

- Mantenimiento en campo: Los sensores deben ser fáciles de instalar y reemplazar, con soporte remoto desde el edge node para actualizaciones de firmware.

- Disponibilidad de datos históricos: Para entrenar el modelo predictivo, el sistema debe garantizar el almacenamiento seguro y estructurado de al menos 30 días de datos de consumo antes de que el módulo ML pueda ser operativo.

**Restricciones Económicas y Organizacionales**:

- Financiamiento inicial limitado: El proyecto depende de alianzas con ONGs como AquaFund y Water.org, lo que obliga a priorizar hardware IoT de bajo costo y servicios cloud costo-eficientes.

- Implementación por fases: La arquitectura debe permitir un despliegue incremental (MVP → piloto → expansión regional) evitando reestructuraciones costosas.

- Recursos humanos: Dado el tamaño reducido del equipo, se prioriza el uso de frameworks maduros y librerías existentes sobre desarrollos personalizados.

- Capacitación de usuarios: Se deben considerar talleres o capacitaciones básicas para que los habitantes puedan interactuar fácilmente con el chatbot, especialmente en comunidades con baja alfabetización digital.

### 4.1.3. Architectural Design Backlog

| Prioridad | ID de Tarea | Tarea de Diseño Arquitectónico | Justificación | Atributos de Calidad Relacionados |
| :--- | :--- | :--- | :--- | :--- |
| **1** | ADB-01 | Definir el esquema de comunicación y almacenamiento de datos para operación offline | Esencial para garantizar la **disponibilidad** y **confiabilidad** en zonas con conectividad intermitente, lo cual es una restricción clave del proyecto. | Disponibilidad, Confiabilidad |
| **2** | ADB-02 | Diseñar el modelo de autenticación y autorización basado en roles | Crítico para la **seguridad** del sistema, protegiendo los datos de los residentes y asegurando que solo los proveedores autorizados gestionen la información. | Seguridad |
| **3** | ADB-03 | Estructurar la API REST del monolito modular para la ingesta de datos IoT | Fundamental para el **rendimiento** y la **escalabilidad**, permitiendo procesar datos de múltiples sensores en tiempo real sin degradar el servicio. | Rendimiento, Escalabilidad |
| **4** | ADB-04 | Diseñar la arquitectura del Edge Node para el procesamiento local de datos | Clave para mejorar el **rendimiento** y la **disponibilidad**, ya que reduce la latencia y la dependencia de la nube al filtrar y agregar datos en el borde de la red. | Rendimiento, Disponibilidad, Confiabilidad |
| **5** | ADB-05 | Definir la estrategia de despliegue en la nube (PaaS/IaaS) | Necesario para la **escalabilidad** y **mantenibilidad**, permitiendo un crecimiento flexible de la infraestructura y facilitando las actualizaciones. | Escalabilidad, Mantenibilidad |
| **6** | ADB-06 | Integrar el motor de IA conversacional y el módulo de Machine Learning | Importante para la **usabilidad** y la **funcionalidad avanzada**, diferenciando la solución al ofrecer soporte inteligente y predicciones de consumo. | Usabilidad, Confiabilidad |

### 4.1.4. Architectural Design Decisions

A continuación, se detallan las decisiones arquitectónicas clave tomadas para el desarrollo de AquaConecta, basadas en los requisitos funcionales, atributos de calidad y restricciones del proyecto.

#### 4.1.4.1. Adopción de un Monolito Modular con Separación de Capas

* **Decisión:** Se optó por una arquitectura de **monolito modular** para el backend en lugar de microservicios. La lógica de negocio estará organizada en módulos que se corresponden con los Bounded Contexts identificados (ej. `	
Water Management Context
`, `Subscriptions`, `Requests`). Internamente, cada módulo seguirá un patrón de capas (Presentación, Lógica de Negocio, Acceso a Datos).
* **Justificación:** Esta decisión responde a la restricción de un **equipo de desarrollo reducido** y la necesidad de una **implementación inicial rápida y de bajo costo**. Un monolito modular simplifica el despliegue, las pruebas y el mantenimiento en las primeras fases del proyecto. La modularidad interna permitirá una futura migración a microservicios si la escalabilidad lo requiere, mitigando el riesgo de un rediseño completo.
* **Alternativas Consideradas:** Se evaluó una arquitectura de microservicios, pero se descartó debido a la complejidad operativa (gestión de servicios, comunicación entre procesos, despliegue distribuido) y los costos iniciales más elevados, que no se justifican para la etapa de piloto del proyecto.

#### 4.1.4.2. Implementación de un Edge Node para Procesamiento de Datos IoT

* **Decisión:** Se implementará un **Edge Node** (utilizando un dispositivo como Raspberry Pi) que actuará como intermediario entre los sensores IoT y la nube. Este nodo será responsable de la agregación de datos, el filtrado de ruido y el almacenamiento temporal (caché) antes de enviar la información al backend.
* **Justificación:** Esta arquitectura responde directamente a la restricción de **conectividad limitada** en zonas rurales. El Edge Node garantiza la **confiabilidad** y **disponibilidad** del sistema, ya que los sensores pueden seguir operando y almacenando datos localmente incluso sin una conexión a Internet estable. Además, mejora el **rendimiento** al reducir la cantidad de datos brutos enviados a la nube.
* **Alternativas Consideradas:** Una conexión directa de los sensores a la nube (vía MQTT o HTTP) fue considerada. Sin embargo, esta opción fue descartada por su alta dependencia de la conectividad y el mayor riesgo de pérdida de datos en entornos inestables.

#### 4.1.4.3. Uso de Flutter para el Desarrollo de la Aplicación Móvil

* **Decisión:** La aplicación móvil para residentes se desarrollará utilizando el framework **Flutter**.
* **Justificación:** Flutter permite crear una base de código única para plataformas Android e iOS, lo cual es ideal para un equipo pequeño, ya que reduce el tiempo y el costo de desarrollo y mantenimiento. Esto responde a las restricciones **económicas y organizacionales**. Además, su rendimiento nativo y la flexibilidad en el diseño de interfaces facilitan la creación de una experiencia de usuario fluida y accesible, cumpliendo con el atributo de **usabilidad**.
* **Alternativas Consideradas:** Se consideró el desarrollo nativo para Android (Kotlin) e iOS (Swift), pero fue descartado por requerir el doble de esfuerzo de desarrollo. También se evaluaron otras tecnologías multiplataforma como React Native, pero se prefirió Flutter por su rendimiento y el ecosistema de widgets.

### 4.1.5. Quality Attribute Scenario Refirements

| Escenario (Refinado) | ID | Atributo | Descripción Refinada |
| :--- | :--- | :--- | :--- |
| **Disponibilidad en la consulta de datos** | QA-01-R | Disponibilidad | En un entorno de **conectividad intermitente**, la app móvil usará el **caché local** sincronizado por el **Edge Node**. La respuesta en la UI no superará los **3 segundos**. La sincronización entre el Edge y la nube se hará en lotes cada **5 minutos**, evitando pérdidas de datos superiores a este intervalo. |
| **Seguridad en autenticación** | QA-02-R | Seguridad | La autenticación se hará con **OAuth 2.0 (JWT)**. La comunicación será vía **HTTPS (TLS 1.3)**. El sistema bloqueará cuentas tras **5 intentos fallidos** y los tokens de sesión expirarán tras **15 minutos** de inactividad. |
| **Escalabilidad en la gestión de sensores** | QA-03-R | Escalabilidad | Al duplicar los sensores (500 a 1000), el backend en **PaaS** escalará horizontalmente. El **Edge Node** pre-procesará los datos para reducir la carga. La latencia total desde la captura hasta la visualización no superará los **5 segundos**. |

## 4.2. Strategic-Level Domain-Driven Design
### 4.2.1. EventStorming

Llevamos a cabo nuestro proceso de Event Storming utilizando la herramienta MURAL, donde construimos todo el flujo del sistema. Iniciamos con la fase de **Exploración No Estructurada**, en la que intercambiamos ideas y discutimos libremente los eventos del dominio, guiándonos por las recomendaciones establecidas para esta etapa.

![alt text](./assets/img/eventStor1.png)

#### 4.2.2. Candidate Context Discovery.

El proceso de Candidate Context Discovery fue ejecutado con el objetivo de establecer una aproximación inicial a los posibles bounded contexts presentes en el dominio. Se aplicó la técnica start-with-value, orientada a identificar los elementos core del dominio que representan el mayor valor estratégico para el negocio. Como resultado de esta exploración, se determinaron los siguientes bounded contexts:

![alt text](assets/bounded/Captura%20de%20pantalla%202025-10-26%20173643.png)
![alt text](assets/bounded/all-bounded%20contexts2.png)

* User & Access Management

  Administra el registro, autenticación y gestión de perfiles de proveedores y residentes. Permite la creación de cuentas, asignación de credenciales y actualización de información personal o de empresa. Garantiza el acceso seguro y controlado al sistema, funcionando como la puerta de entrada para todos los actores.

* Subscriptions

  Gestiona la relación entre residentes, proveedores y sensores. Cada suscripción activa asegura que un tanque de agua cuente con un sensor vinculado y operativo. Controla la creación, cancelación y administración de suscripciones, permitiendo que los proveedores gestionen fácilmente a sus residentes y los sensores asociados.

* Water Management Context

  Supervisa y administra los datos provenientes de los sensores instalados en los tanques. Ofrece a los residentes una vista detallada del nivel, calidad y pH del agua en tiempo real, mientras que los proveedores pueden visualizar y gestionar la información de todos sus residentes. También almacena el historial de consumo y genera alertas en caso de anomalías o condiciones críticas.

* Requests

  Centraliza la gestión de solicitudes y reportes de los residentes. Permite generar solicitudes de reabastecimiento de agua y reportes de problemas relacionados con sensores o calidad del recurso. Los proveedores reciben estas solicitudes, actualizan su estado y gestionan la atención correspondiente. Este Bounded Context es clave para coordinar la interacción diaria entre residentes y proveedores.

* Analytics

  Consolida y presenta métricas globales y reportes históricos. Integra información de Water Management, Subscriptions y Requests para ofrecer un panorama completo del servicio. Los administradores pueden visualizar indicadores como promedios de nivel y calidad del agua, número de solicitudes atendidas y métricas financieras, facilitando decisiones estratégicas y de mejora del servicio.

* Predictive Analytics

  Analiza datos históricos y actuales para generar predicciones de consumo y detectar patrones críticos. A partir de estas predicciones, puede emitir alertas preventivas o generar solicitudes automáticas de reabastecimiento. Además, alimenta al módulo de Analytics con métricas de predicción y desempeño del modelo. Representa una capacidad diferenciadora al anticipar la demanda de agua y optimizar la distribución.

#### 4.2.3. Domain Message Flows Modeling.

En esta sección, aplicamos Domain Storytelling para modelar cómo los bounded contexts colaboran mediante flujos de mensajes, resolviendo los casos de uso del negocio. Esta técnica nos permitió visualizar las interacciones entre actores (usuarios, sistemas y servicios), secuenciar los pasos clave y validar el modelo con expertos del dominio. Estos diagramas clarifican dependencias, identifican riesgos y facilitan la alineación entre equipos técnicos y de negocio, asegurando una arquitectura coherente con las necesidades del dominio. 

- **Scenario 1: Habitante revisa el estado del agua de su tanque.**
  
El habitante consulta desde la app móvil el estado de su tanque de agua. El módulo de Water Management recupera datos del sensor asociado, mostrando nivel, calidad y consumo reciente. Si no hay transmisión, se notifica indisponibilidad. En casos críticos, el sistema genera una alerta preventiva para el usuario.

![alt text](./assets/bounded/scenario1.png)

- **Scenario 2:  Proveedor registra y habilita suscripcion de habitante.**
  
El proveedor accede a la plataforma web para registrar a un nuevo habitante. El módulo de User & Profile Management valida y guarda sus datos, y luego el módulo de Subscription crea una nueva suscripción vinculada a un sensor activo. Si el registro falla (datos incompletos o duplicados), se notifica al proveedor para corregirlos antes de habilitar la suscripción.
![alt text](./assets/bounded/scenario2.png)
- **Scenario 3: Residente solicita abastecimiento de agua a su proveedor.**

El residente ingresa a la app móvil y crea una solicitud de abastecimiento de agua. El sistema de Requests recibe el pedido y consulta al módulo de User & Profile Management para validar los datos del residente y su suscripción activa. Una vez confirmada la información, la solicitud se registra y queda visible para el proveedor. Si la suscripción no es válida o el residente no tiene sensores activos, la solicitud se rechaza con una notificación en la app.
![alt text](./assets/bounded/c3.png)
- **Scenario 4: Proveedor consulta predicciones de consumo de su residente y genera reabasteciento.**

El proveedor accede a la plataforma web para consultar el patrón de consumo de un residente. El módulo de Predictive Analytics, utilizando datos históricos de Water Management, genera una proyección del consumo futuro y estima la fecha en que el tanque alcanzará niveles críticos. Con base en esta información, el proveedor puede decidir generar automáticamente una solicitud de reabastecimiento en el módulo de Requests. Si no existen suficientes datos históricos, el sistema informa que no es posible generar una predicción en ese momento.
![alt text](./assets/bounded/scenario4.png)

- **Scenario 4: Residente realiza consulta al chatbot.**

El residente accede a la aplicación móvil y abre el chatbot integrado para resolver una consulta sobre el servicio de agua. El chatbot, basado en un modelo de IA conversacional, procesa la pregunta y accede a información del sistema, como su suscripción, historial de consumo o estado de solicitudes, para brindar una respuesta inmediata. Si la consulta excede las capacidades del asistente virtual, el chatbot deriva automáticamente el caso al módulo de Requests, generando un ticket que será atendido por el proveedor.
![alt text](./assets/bounded/c5.png)

#### 4.2.4. Bounded Context Canvases. 

- Bounded context Subscription & Payment

Este canvas gestiona la creación y administración de suscripciones que vinculan a los residentes con sus sensores y proveedores. Garantiza que cada suscripción esté activa y asociada a un sensor para habilitar el monitoreo del tanque. Las decisiones de negocio incluyen validar que un residente esté registrado antes de generar la suscripción y cancelar automáticamente aquellas que se desactiven por decisión del proveedor o el administrador. El lenguaje ubicuo abarca términos como “Suscripción activa”, “Sensor asignado” y “Estado de suscripción”.

![alt text](./assets/bounded/sus%20can.png)

- Bounded context Water Management 

Este canvas administra la captura de datos de los sensores y la visualización en tiempo real del estado del agua. Asegura que residentes y proveedores accedan a métricas actualizadas y que las alertas críticas se emitan sin retrasos. Sus decisiones de negocio incluyen definir intervalos de actualización y enviar notificaciones cuando se superan umbrales de calidad o cantidad. El lenguaje ubicuo incluye “Lectura de sensor”, “Alerta de umbral” e “Historial de consumo”. Las métricas miden precisión de lecturas y latencia de alertas, mientras que las preguntas abiertas tratan sobre protocolos de conectividad y manejo de fallos de sensores.

![alt text](./assets/bounded/moni%20can.png)

- Bounded context Analytics

Este canvas se centra en consolidar datos de consumo, calidad y suscripciones en reportes accesibles para el administrador. Garantiza que los reportes reflejen fielmente la operación global del sistema y sirvan para auditorías o decisiones estratégicas. Las decisiones de negocio determinan que solo el administrador puede acceder a métricas agregadas y que los históricos se mantengan disponibles. El lenguaje ubicuo incluye “Reporte de consumo agregado” y “Indicador de calidad promedio”. Sus métricas se enfocan en la frecuencia y exactitud de generación de reportes, mientras que las preguntas abiertas discuten exportación de datos y nivel de detalle requerido.

![alt text](./assets/bounded/litys%20can.png)


- Bounded context User & Profile Management

Este canvas regula la autenticación, registro y mantenimiento de perfiles de residentes y proveedores. Asegura que el acceso al sistema sea seguro y que cada usuario gestione sus propios datos. Sus decisiones de negocio incluyen exigir credenciales únicas, restringir cambios de perfil a usuarios legítimos y verificar a los proveedores antes de permitirles registrar residentes. El lenguaje ubicuo abarca “Credenciales de acceso” y “Perfil de usuario”. Las métricas incluyen tasas de registro exitoso y accesos fallidos, y las preguntas abiertas se centran en posibles integraciones con sistemas externos de autenticación o gestión de fraudes.

![alt text](./assets/bounded/iam%20can.png)


- Bounded context Requests

Este canvas administra las solicitudes de reabastecimiento y reportes de problemas generados por residentes. Asegura que los proveedores tengan un canal transparente para gestionar dichas solicitudes y mantener informados a los usuarios. Las decisiones de negocio incluyen vincular cada request a una suscripción activa y exigir a los proveedores que actualicen su estado. El lenguaje ubicuo usa términos como “Solicitud de agua” y “Estado de request”. Las métricas miden tiempos de respuesta y tasas de resolución, mientras que las preguntas abiertas se centran en mecanismos de priorización y notificación automática.

![alt text](./assets/bounded/req%20can.png)

- Bounded context Predictive Analytics

Este canvas analiza datos históricos de consumo para generar predicciones sobre futuros niveles de agua. Permite a los proveedores anticipar necesidades de reabastecimiento y evitar desabastecimientos. Las decisiones de negocio establecen que toda predicción se base en datos recientes y requiera validación humana antes de ejecutar acciones. El lenguaje ubicuo incluye “Predicción de consumo” y “Estimación de desabastecimiento”. Sus métricas evalúan precisión y rapidez de las predicciones, y las preguntas abiertas abarcan el horizonte temporal del modelo y el tipo de técnicas de análisis a usar.

![alt text](./assets/bounded/ml%20can.png)

### 4.2.5. Context Mapping.

En este diagrama se visualiza las relaciones clave entre los bounded contexts del sistema.



![Context Mapping](./assets/bounded/acl.png)


### 4.3. Software Architecture.

#### 4.3.1. Software Architecture System Landscape Diagram.
![alt text](<./assets/img/Context2.png>)
#### 4.3.2. Software Architecture Context Level Diagrams.

En el diagrama de contexto se muestra la interacción de los diferentes actores con el sistema central AquaConecta. Los residentes utilizan la aplicación móvil para monitorear en tiempo real el nivel y la calidad del agua, recibir alertas, solicitar reabastecimientos e interactuar con un chatbot asistido por un servicio externo de NLP. Los proveedores acceden a la plataforma web para gestionar residentes, suscripciones, solicitudes y visualizar predicciones de consumo generadas por el módulo de Analítica Predictiva. Los administradores supervisan las operaciones globales a través de reportes y paneles analíticos.

El sistema central se integra con los dispositivos IoT instalados en los tanques, que capturan métricas de agua y transmiten los datos a través de un nodo de procesamiento en el borde (Edge Node). Asimismo, se conecta con Mercado Pago para la gestión de transacciones seguras y con servicios externos de Machine Learning y NLP que fortalecen las capacidades de predicción y soporte conversacional.

![alt text](<./assets/img/Context2.png>)


#### 4.3.3. Software Architecture Container Level Diagrams.

El diagrama de contenedores ilustra las interacciones de alto nivel entre los usuarios, las aplicaciones y los servicios del sistema AquaConecta. Antes de detallar los flujos, es importante distinguir que el proyecto plantea dos visiones arquitectónicas: una **Arquitectura Ideal**, diseñada para escalabilidad y producción masiva, y una **Arquitectura de la Demo**, optimizada para la implementación actual y validación académica.

#### A. Actores y Flujo General (Común a ambas arquitecturas)

Independientemente de la arquitectura subyacente, los actores principales y el flujo de datos en el "Borde" (*Edge*) se mantienen constantes:

* **Usuarios:**
    * **Residentes:** Utilizan la aplicación móvil (Flutter) para monitorear su consumo de agua, recibir alertas de niveles críticos y enviar reportes.
    * **Proveedores:** Gestionan residentes, suscripciones y atienden solicitudes mediante la aplicación web (Angular).
    * **Administradores:** Supervisan el desempeño global y los reportes analíticos del sistema.

* **IoT y Edge Computing:**
    * Los sensores AquaConecta miden calidad y nivel de agua en los tanques.
    * Una aplicación embebida recolecta estos datos y los envía al **Edge Processing Node**.
    * Este nodo preprocesa la información, genera recomendaciones locales y almacena datos temporalmente en una base de datos **MySQL** local antes de transmitirlos a la plataforma central, optimizando el ancho de banda y asegurando disponibilidad offline.

---

#### B. Arquitectura de la Solución Ideal (Target Architecture)

Esta arquitectura representa la visión a largo plazo de AquaConecta. Está diseñada bajo el patrón de **Microservicios** con bases de datos descentralizadas para garantizar alta cohesión y escalabilidad.

![Diagrama de Arquitectura Ideal](conteneodres2-1.png)

**Características clave:**

1.  **Patrón Backend for Frontend (BFF):** Se implementan gateways específicos para cada tipo de cliente (*API Gateway Web, API Gateway Mobile, API Gateway IoT*). Esto permite que cada interfaz reciba los datos formateados exactamente como los necesita, reduciendo el *over-fetching* y mejorando la experiencia de usuario.
2.  **Desacoplamiento de Datos (Database per Service):** Cada contexto delimitado (*Bounded Context*), como Usuarios, Suscripciones o Monitoreo, posee su propia base de datos. Esto evita que un fallo en un módulo afecte a la integridad de todo el sistema.
3.  **Comunicación Asíncrona (Message Broker):** Se introduce un *Message Broker* para gestionar eventos entre servicios, desacoplando la comunicación directa y mejorando la resiliencia.
4.  **Arquitectura Medallion (Data Analytics):** Para la analítica avanzada, se observa una sección inferior estructurada bajo el concepto de "Medallion Architecture". Los datos fluyen a través de capas lógicas (Bronce para datos crudos, Plata para datos limpios y Oro para datos agregados/de negocio), permitiendo procesar grandes volúmenes de información histórica para los modelos de Machine Learning sin impactar el rendimiento transaccional.

---

#### C. Arquitectura de la Demo (Implementación Actual)

Para efectos de la demostración académica y validación funcional del MVP (*Producto Mínimo Viable*), se ha optado por una arquitectura que simplifica la infraestructura de datos pero mantiene la lógica de segregación de responsabilidades.

![Diagrama de Arquitectura Demo](<as is.png>)

**Diferencias y adaptaciones:**

1.  **Persistencia del Patrón BFF:** Al igual que en la arquitectura ideal, la demo mantiene el patrón **Backend for Frontend**. Los gateways (Web, Mobile e IoT) siguen estando separados para gestionar la lógica de presentación específica de cada cliente, demostrando una buena práctica arquitectónica desde la fase de prototipo.
2.  **Base de Datos Compartida:** A diferencia de la solución ideal, la demo utiliza una instancia centralizada de MySQL. Aunque los servicios (APIs en Spring Boot) están lógicamente separados por contextos, todos persisten información en el mismo repositorio para facilitar la integración, el despliegue rápido y la validación de relaciones entre entidades.
3.  **Comunicación Síncrona:** La interacción entre los servicios se realiza principalmente a través de llamadas REST directas.
4.  **Machine Learning Integrado:** El módulo de Analítica Predictiva interactúa directamente con la base de datos central para obtener el histórico de consumo y generar las proyecciones de demanda.

Esta estrategia dual permite demostrar la funcionalidad completa del sistema hoy (Arquitectura Demo) respetando los patrones de diseño modernos como el BFF, mientras se tiene una hoja de ruta técnica clara para el crecimiento futuro hacia una arquitectura distribuida y basada en datos (Arquitectura Ideal).

#### 4.3.4. Software Architecture Deployment Diagrams.

El diagrama de despliegue muestra cómo se distribuyen los distintos componentes de software en su entorno de ejecución. El sistema está compuesto por una aplicación web desarrollada con Angular y una aplicación móvil desarrollada con Flutter, ambas desplegadas sobre Firebase. Estas aplicaciones se comunican mediante JSON/HTTPS con una API REST construida con Spring Boot (Java), que encapsula toda la lógica de negocio organizada por contextos delimitados. La API, a su vez, realiza operaciones de lectura y escritura sobre una base de datos MySQL, que almacena información de usuarios, suscripciones, sensores, alertas y registros administrativos. Además, el backend se integra con el sistema de pagos externo Mercado Pago, utilizado para procesar transacciones.

![alt text](<./assets/img/deployment.jpeg>)

# Chapter V: Tactical-Level Software Design

## 5.1 Analytics Bounded Context

### 5.1.1 Domain Layer 

### **Entity**

  - DashboardSummary:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `totalProviders` | `long` | Número total de proveedores registrados en el sistema |
| `totalResidents` | `long` | Número total de residentes registrados en el sistema |
| `activeSubscriptions` | `long` | Cantidad de suscripciones actualmente activas |
| `totalIncome` | `float` | Ingresos totales acumulados de todas las suscripciones |
| `monthlyIncome` | `float` | Ingresos generados en el mes actual |

### **Servicios de Dominio**
| Servicio | Tipo | Responsabilidad |
|----------|------|----------------|
| `DashboardQueryService` | Query Service | Obtiene métricas consolidadas del sistema, estadísticas de usuarios activos, reportes de consumo y datos de monitoreo |

### 5.1.2 Interface Layer 

### **Controladores REST**
| Controlador | Responsabilidad |
|-------------|----------------|
| `DashboardController` | Expone endpoints para obtener métricas consolidadas, dashboards personalizados por tipo de usuario y reportes ejecutivos |

### 5.1.3 Application Layer

#### **Servicios de Aplicación**
| Tipo   | Responsabilidad |
|------|----------------|
| **Command Services** |   Procesamiento de comandos para configuración de dashboards personalizados |
| **Query Services** | Orquestación de consultas complejas que involucran múltiples bounded contexts |
| **Data Aggregation Services**  | Consolidación de datos provenientes de Profiles, Requests, Water Management y Subscriptions |

### 5.1.4 Infrastructure Layer

#### **Componentes de Infraestructura**
| Componente | Responsabilidad |
|------------|----------------|
| **Cache Management** | Sistema de cache para optimizar consultas frecuentes de métricas |
| **Data Integration** | Servicios de integración con otros bounded contexts vía ACL |
| **Reporting Engine** | Motor de generación de reportes en tiempo real |
| **Analytics Services** | Procesamiento de analytics y KPIs del negocio |

### 5.1.5 Bounded Context Software Architecture Component Level Diagrams

El diagrama de componentes del bounded context Analytics muestra cómo la aplicación web y móvil se conecta con el DashboardController que expone los endpoints REST necesarios para gestionar las consultas de métricas y resúmenes del dashboard. El controlador delega su lógica al DashboardServiceImpl, el cual implementa la interfaz DashboardQueryService y se encarga de procesar operaciones de agregación y cálculo de métricas como totales de proveedores, residentes, suscripciones activas e ingresos. A su vez, el servicio interactúa con Context Facades (ProfileContextFacade y SubscriptionContextFacade) que implementan el patrón Anti-Corruption Layer para acceder de forma controlada a los datos de otros bounded contexts. El servicio genera instancias de la entidad DashboardSummary que encapsula todas las métricas calculadas para su posterior serialización y envío al cliente. Este patrón de consulta cruzada permite al bounded context Analytics actuar como un read model agregado sin duplicar datos, manteniendo la consistencia y separación de responsabilidades entre bounded contexts.

![alt text](<./assets/CAPITULO5/Analitys/structurizr-101610-AnalyticsComponentDiagram3213.png>)

### 5.1.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.1.6.1 Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Domain Layer del bounded context Analytics ilustra la estructura y relaciones entre las principales abstracciones del dominio. La interfaz DashboardQueryService define el contrato para obtener métricas del dashboard, siendo implementada por DashboardServiceImpl que actúa como el servicio de aplicación principal. La entidad DashboardSummary representa el agregado central que encapsula todas las métricas calculadas del sistema, incluyendo totales de usuarios, suscripciones activas e ingresos, además de metadatos como fecha de actualización y estado. El DashboardController actúa como punto de entrada REST, delegando las operaciones al servicio de dominio. Los repositorios externos (ProviderRepository, ResidentRepository, SubscriptionRepository) proporcionan acceso de solo lectura a los datos de otros bounded contexts, manteniendo el principio de separación de responsabilidades. Esta arquitectura permite que el bounded context Analytics funcione como un read model eficiente que consolida información de múltiples fuentes sin crear dependencias fuertes entre bounded contexts.

![alt text](<./assets/CAPITULO5/Analitys/hLJRRjim37tFL-ZHHfj-m504xLeCwCE0hjuFg3QR2j0beAW0nhP_dnsteMhHIp0q3p50ddD87P6wYQIHahChrLeTexhNyVKvQEn-9C2-0ToR5jIlbNhxNLyRJu0lkeNDvXYzs08TcLNDAaroJcD_J-60_RCQF_DI3CeAhMtmMqM1j7t4i3STO9IIJn27dATvKhTa.png>)

#### 5.1.6.2 Bounded Context Database Design Diagram

El diagrama de base de datos del bounded context Analytics muestra la estructura de persistencia que soporta las operaciones de consulta y agregación de métricas. La tabla principal DASHBOARD_SUMMARY actúa como una entidad persistente que almacena los resultados calculados de las métricas del dashboard, incluyendo metadatos de control como fecha de actualización y estado. Esta tabla se relaciona conceptualmente con las tablas PROVIDER, RESIDENT y SUBSCRIPTION que pertenecen a otros bounded contexts, de las cuales lee datos mediante consultas de solo lectura. La arquitectura permite que el bounded context Analytics mantenga un cache persistente de métricas calculadas, reduciendo la carga computacional en consultas frecuentes y mejorando los tiempos de respuesta. Las relaciones indican el flujo de datos desde las tablas fuente hacia el resumen agregado, manteniendo la integridad referencial conceptual sin crear dependencias físicas entre bounded contexts. Este diseño facilita la escalabilidad al permitir que las consultas analíticas operen sobre datos precomputados mientras mantiene la consistencia eventual con los bounded contexts fuente.

![alt text](<./assets/CAPITULO5/Analitys/Untitled diagram _ Mermaid Chart-2025-10-03-163011.png>)

---
### 5.2 Water Management Bounded Context

### 5.2.1 Domain Layer

#### **Aggregates**

- Device Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `type` | `String` | Tipo de dispositivo IoT (sensor de nivel, calidad, etc.) |
| `status` | `String` | Estado actual del dispositivo (activo, inactivo, mantenimiento) |
| `description` | `String` | Descripción detallada del dispositivo y su función |
| `residentId` | `Long` | Identificador del residente propietario del dispositivo |

- Event Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `eventType` | `String` | Tipo de evento generado (alerta, medición, falla) |
| `qualityValue` | `String` | Valor de calidad del agua medido por el sensor |
| `levelValue` | `String` | Nivel de agua registrado en el tanque |
| `sensorId` | `Long` | Identificador del sensor que generó el evento |

#### **Device Commands y Queries**

- Device Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateDeviceCommand` | Registrar nuevo dispositivo IoT en el sistema |
| `UpdateDeviceCommand` | Actualizar configuración y estado del dispositivo |
| `DeleteDeviceCommand` | Remover dispositivo del sistema |

- Device Queries:

| Query | Propósito |
|-------|-----------|
| `GetDeviceByIdQuery` | Obtener información específica de un dispositivo |
| `GetDevicesByResidentIdQuery` | Listar dispositivos de un residente específico |
| `GetActiveDevicesQuery` | Obtener todos los dispositivos activos del sistema |

#### **Event Commands y Queries**

- Event Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateEventCommand` | Registrar nuevo evento de monitoreo |
| `ProcessEventCommand` | Procesar y categorizar eventos recibidos |
| `ArchiveEventCommand` | Archivar eventos antiguos |

- Event Queries:

| Query | Propósito |
|-------|-----------|
| `GetEventByIdQuery` | Obtener detalles de un evento específico |
| `GetEventsBySensorIdQuery` | Historial de eventos de un sensor |
| `GetRecentEventsQuery` | Eventos recientes para dashboard |
| `GetEventsByDateRangeQuery` | Eventos en rango de fechas específico |

#### **Servicios de Dominio**

| Servicio | Tipo | Responsabilidad |
|----------|------|----------------|
| `DeviceCommandService` | Command Service | Gestión del ciclo de vida de dispositivos, validación de configuraciones |
| `DeviceQueryService` | Query Service | Consultas complejas sobre dispositivos y su estado |
| `EventCommandService` | Command Service | Procesamiento y almacenamiento de eventos, reglas de negocio para alertas |
| `EventQueryService` | Query Service | Análisis histórico de eventos, generación de reportes de monitoreo |


### 5.2.2 Interface Layer

#### **Controladores REST**
| Controlador | Responsabilidad |
|-------------|----------------|
| `DeviceController` | CRUD de dispositivos, configuración de parámetros, gestión de estados |
| `EventController` | Recepción de eventos IoT, consultas de historial, gestión de alertas |

#### **Anti-Corruption Layer (ACL)**
| Facade | Responsabilidad |
|---------|----------------|
| `WaterManagementContextFacade` | Exposición controlada de información de dispositivos y eventos para otros contextos |

### 5.2.3 Application Layer

#### **Servicios de Aplicación**
| Implementación | Responsabilidad |
|----------------|----------------|
| `DeviceCommandServiceImpl` | Lógica de negocio para creación, actualización y eliminación de dispositivos |
| `DeviceQueryServiceImpl` | Implementación de consultas complejas, filtros y búsquedas avanzadas |
| `EventCommandServiceImpl` | Procesamiento de eventos en tiempo real, aplicación de reglas de alertas |
| `EventQueryServiceImpl` | Generación de reportes, análisis de tendencias, consultas de performance |
| `AlertProcessingService` | Servicio especializado en detección y notificación de alertas críticas |
| `DataValidationService` | Validación de integridad de datos recibidos de sensores IoT |

### 5.2.4 Infrastructure Layer

#### **Repositorios JPA**
| Repositorio | Responsabilidad |
|-------------|----------------|
| `DeviceRepository` | Persistencia de dispositivos con consultas optimizadas |
| `EventRepository` | Almacenamiento masivo de eventos con estrategias de particionamiento |

#### **Servicios de Infraestructura**
| Servicio | Responsabilidad |
|----------|----------------|
| **IoT Gateway** | Comunicación con dispositivos físicos vía protocolos IoT (MQTT, CoAP) |
| **Time Series Database** | Almacenamiento especializado para datos temporales de sensores |
| **Real-time Processing** | Procesamiento en tiempo real de streams de datos IoT |
| **Device Configuration** | Gestión remota de configuración de dispositivos |


### 5.2.5 Bounded Context Software Architecture Component Level Diagrams

El diagrama de componentes del bounded context Water Management muestra cómo los controladores REST (DeviceController, EventController) gestionan la interacción entre los usuarios y el sistema para el monitoreo de dispositivos y eventos IoT. Los controladores delegan la lógica a los servicios de aplicación (DeviceCommandServiceImpl, EventCommandServiceImpl, DeviceQueryServiceImpl, EventQueryServiceImpl), que implementan los contratos definidos en el dominio. Los servicios de dominio gestionan los agregados Device y Event, así como los comandos y queries asociados.

![alt text](structurizr-101610-WaterManagementComponents.png)

### 5.2.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.2.6.1 Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Domain Layer del bounded context Water Management ilustra la estructura y relaciones entre los principales agregados (Device, Event), los servicios de dominio y los comandos/queries. Los servicios de comando y consulta definen los contratos para la gestión de dispositivos y eventos, mientras que los agregados encapsulan la lógica de negocio y las reglas de validación. Los comandos permiten la creación y actualización de entidades, y los queries facilitan la obtención de información específica. Este diseño promueve la claridad y la extensibilidad, permitiendo agregar nuevas funcionalidades de monitoreo sin afectar la arquitectura base.

![alt text](<./assets/CAPITULO5/monitoringh/nLXTRzfA47s_lyAF849-m5M4GZxk5LAaAYJjQ-NO0xMqzjBTDIfgcz_UOLSEn_RWsY8jFBGmPpxEdfbnlRssBZQkpDK_4NyI5LiRtT4sIoZwpgRmkRgQhzU6rh6ZQAcrcytUeEc3BjPHbXuCJyvaR7Ax3RMCNCoLjcLEoIOcsxXC5ut4XcoMKk4MAG99hEwOo.png>)

#### 5.2.6.2 Bounded Context Database Design Diagram

El diagrama de base de datos del bounded context Water Management representa la estructura de persistencia para los dispositivos y eventos monitoreados. Incluye las tablas principales para Device y Event, así como las relaciones entre ellas y con otras entidades relevantes. La base de datos almacena información histórica y actual de los dispositivos IoT, permitiendo consultas eficientes y la trazabilidad de los eventos generados por los sensores. La integración con el broker externo se realiza a nivel de infraestructura, permitiendo la ingesta y procesamiento de datos en tiempo real, lo que es fundamental para la operación continua y la respuesta rápida ante situaciones críticas en el sistema.

![alt text](<./assets/CAPITULO5/monitoringh/Untitled diagram _ Mermaid Chart-2025-10-03-170913.png>)
---

### 5.3 User & Profile Bounded Context

### 5.3.1 Domain Layer

#### **Aggregates**

- Profile Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `name` | `PersonName` | Value Object que encapsula firstName y lastName |
| `email` | `String` | Correo electrónico para comunicaciones |
| `direction` | `String` | Dirección física completa del perfil |
| `documentNumber` | `String` | Número de documento de identidad |
| `documentType` | `String` | Tipo de documento (DNI, pasaporte, etc.) |
| `userId` | `Long` | Referencia al usuario del sistema IAM |
| `phone` | `String` | Número de teléfono de contacto |

- Provider Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `taxName` | `String` | Razón social o nombre comercial del proveedor |
| `ruc` | `String` | Registro Único de Contribuyente para identificación fiscal |
| `userId` | `Long` | Referencia al usuario del sistema IAM |

- Resident Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `firstName` | `String` | Primer nombre del residente |
| `lastName` | `String` | Apellido del residente |
| `userId` | `Long` | Referencia al usuario del sistema IAM |
| `providerId` | `Long` | Referencia al proveedor que atiende al residente |

#### **Value Objects**

- PersonName:

| Value Object | Atributos | Descripción |
|--------------|-----------|-------------|
| `PersonName` | `firstName: String`, `lastName: String` | Encapsula el nombre completo con validaciones de negocio |

#### **Profile Commands y Queries**

- Profile Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateProfileCommand` | Crear nuevo perfil base en el sistema |
| `UpdateProfileCommand` | Actualizar información del perfil existente |

- Profile Queries:

| Query | Propósito |
|-------|-----------|
| `GetProfileByUserIdQuery` | Obtener perfil asociado a un usuario específico |
| `GetProfileByIdQuery` | Obtener perfil por su identificador único |

#### **Provider Commands y Queries**

- Provider Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateProviderCommand` | Registrar nuevo proveedor de servicios |
| `UpdateProviderCommand` | Actualizar información comercial del proveedor |

- Provider Queries:

| Query | Propósito |
|-------|-----------|
| `GetProviderByUserIdQuery` | Obtener información del proveedor por usuario |
| `GetProviderByIdQuery` | Obtener proveedor por identificador |
| `GetAllProvidersQuery` | Listar todos los proveedores activos |

#### **Resident Commands y Queries**

- Resident Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateResidentCommand` | Registrar nuevo residente en el sistema |
| `UpdateResidentCommand` | Actualizar información personal del residente |

- Resident Queries:

| Query | Propósito |
|-------|-----------|
| `GetResidentByUserIdQuery` | Obtener residente asociado a un usuario |
| `GetResidentsByProviderIdQuery` | Listar residentes atendidos por un proveedor |
| `GetWaterRequestsByResidentIdQuery` | Obtener solicitudes de agua de un residente |

#### **Servicios de Dominio**

| Servicio | Tipo | Responsabilidad |
|----------|------|----------------|
| `ProfileCommandService` | Command Service | Gestión del ciclo de vida de perfiles, validaciones de integridad |
| `ProfileQueryService` | Query Service | Consultas complejas sobre perfiles y relaciones |
| `ProviderCommandService` | Command Service | Lógica de negocio específica para proveedores |
| `ResidentCommandService` | Command Service | Gestión de residentes y sus relaciones con proveedores |

### 5.3.2 Interface Layer

#### **Controladores REST**

| Controlador | Responsabilidad |
|-------------|----------------|
| `ProfilesController` | CRUD de perfiles generales, gestión de información común |
| `ProviderController` | Operaciones específicas de proveedores, gestión comercial |
| `ResidentController` | Gestión de residentes, asignación de proveedores |

##### Anti-Corruption Layer (ACL)
| Facade | Responsabilidad |
|---------|----------------|
| `ProfilesContextFacade` | Exposición de información de perfiles para integración |
| `ProviderContextFacade` | Servicios específicos de proveedores para otros contextos |
| `ResidentContextFacade` | Información de residentes para solicitudes y suscripciones |

### 5.3.3 Application Layer

#### **Servicios de Aplicación**
| Implementación | Responsabilidad |
|----------------|----------------|
| `ProfileCommandServiceImpl` | Coordinación de creación y actualización de perfiles |
| `ProfileQueryServiceImpl` | Implementación de búsquedas y filtros avanzados |
| `ProviderManagementService` | Servicios de alto nivel para gestión integral de proveedores |
| `ResidentManagementService` | Orquestación de operaciones complejas de residentes |
| `ProfileValidationService` | Validación de reglas de negocio y consistencia de datos |
| `RelationshipService` | Gestión de relaciones entre proveedores y residentes |

### 5.3.4 Infrastructure Layer

#### **Repositorios JPA**
| Repositorio | Responsabilidad |
|-------------|----------------|
| `ProfileRepository` | Persistencia de perfiles con consultas optimizadas |
| `ProviderRepository` | Gestión de datos de proveedores con índices especializados |
| `ResidentRepository` | Almacenamiento de residentes con relaciones complejas |

#### **Servicios de Infraestructura**
| Servicio | Responsabilidad |
|----------|----------------|
| **Document Validation** | Integración con servicios externos para validación de documentos |
| **Notification Services** | Sistema de notificaciones para cambios en perfiles |
| **Data Synchronization** | Sincronización con sistemas externos de clientes |


### 5.3.5 Bounded Context Software Architecture Component Level Diagrams

El diagrama de componentes muestra cómo los controladores REST (ProfilesController, ProviderController, ResidentController) exponen los endpoints para la gestión de perfiles, proveedores y residentes. Cada controlador delega la lógica a servicios de aplicación que implementan los contratos definidos en el dominio. Los servicios gestionan los agregados Profile, Provider y Resident, así como los comandos y queries asociados. La infraestructura incluye repositorios y la integración con servicios externos como validación de documentos, geolocalización y notificaciones. Los componentes ACL (Context Facades) permiten exponer información controlada a otros bounded contexts, asegurando el aislamiento y la integridad de los datos. Este diseño facilita la extensibilidad y la integración segura entre módulos, manteniendo la consistencia y la separación de responsabilidades.


![alt text](<./assets/CAPITULO5/Profile/structurizr-101610-ProfilesComponentDiagram222.png>)

### 5.3.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.3.6.1 Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Domain Layer ilustra la estructura y relaciones entre los principales agregados (Profile, Provider, Resident), value objects, servicios de dominio y comandosqueries. Los servicios de comando y consulta definen los contratos para la gestión de entidades, mientras que los agregados encapsulan la lógica de negocio y las reglas de validación. Los value objects como PersonName garantizan la inmutabilidad y la igualdad por valor. Los comandos permiten la creación y actualización de entidades, y los queries facilitan la obtención de información específica. Este diseño promueve la claridad, la extensibilidad y la protección de invariantes de negocio, permitiendo agregar nuevas funcionalidades sin afectar la arquitectura base.

![alt text](<./assets/CAPITULO5/Profile/tLhTRjms4xt_dc8lL_3dF40H676Sf33W9gcJj9U5B77NAYHnenyZHbi_UobhPpsq3dsMLb07peMpo_dXp3d3ePRKgxPBcwwlolyjtB-iJDjsyR6ngw8qYx_SsFZlvSlZzRenwxGpYtDhkwEZdUZmpDRhHP7V3NmqJMlhzsbb5hNxSoVur3M5qpLLMfIJqRneJD.png>)
#### 5.3.6.2 Bounded Context Database Design Diagram

El diagrama de base de datos representa la estructura de persistencia para los perfiles, proveedores y residentes. Incluye las tablas principales PROFILE, PROVIDER y RESIDENT, así como las relaciones con la tabla de usuarios externos (USER). La base de datos almacena información histórica y actual de cada entidad, permitiendo consultas eficientes y la trazabilidad de las relaciones entre usuarios, proveedores y residentes. Se definen restricciones de unicidad y claves foráneas para garantizar la integridad referencial y la consistencia de los datos. Este diseño soporta la escalabilidad y la seguridad, facilitando la integración con otros módulos y la implementación de consultas especializadas para reportes y validaciones.


![alt text](<./assets/CAPITULO5/Profile/Captura de pantalla 2025-10-03 124141.png>)
---

## 5.4 Requests Bounded Context

### 5.4.1 Domain Layer

#### **Aggregates**

- WaterSupplyRequest Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `residentId` | `Long` | Identificador del residente que realiza la solicitud |
| `providerId` | `Long` | Identificador del proveedor asignado para atender |
| `requestedLiters` | `String` | Cantidad de litros de agua solicitados |
| `emissionDate` | `String` | Fecha y hora de emisión de la solicitud |
| `status` | `String` | Estado actual (pendiente, en proceso, completada, cancelada) |
| `deliveredAt` | `LocalDateTime` | Fecha y hora de entrega del suministro |

- IssueReport Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `residentId` | `Long` | Identificador del residente que reporta el problema |
| `providerId` | `Long` | Identificador del proveedor responsable de resolver |
| `title` | `String` | Título descriptivo del problema reportado |
| `description` | `String` | Descripción detallada del problema o incidencia |
| `emissionDate` | `String` | Fecha y hora del reporte |
| `status` | `String` | Estado del reporte (abierto, en revisión, resuelto, cerrado) |

#### **WaterSupplyRequest Commands y Queries**

- WaterSupplyRequest Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateWaterSupplyRequestCommand` | Generar nueva solicitud de suministro de agua |
| `UpdateWaterSupplyRequestCommand` | Actualizar estado y información de entrega |
| `CancelWaterSupplyRequestCommand` | Cancelar solicitud pendiente |

- WaterSupplyRequest Queries:

| Query | Propósito |
|-------|-----------|
| `GetAllWaterSupplyRequestsQuery` | Obtener todas las solicitudes del sistema |
| `GetWaterSupplyRequestByIdQuery` | Obtener solicitud específica por identificador |
| `GetWaterSupplyRequestsByResidentIdQuery` | Historial de solicitudes de un residente |
| `GetAllWaterSupplyRequestsByProviderQuery` | Solicitudes asignadas a un proveedor |
| `GetPendingWaterSupplyRequestsQuery` | Solicitudes pendientes de atención |

#### **IssueReport Commands y Queries**

- IssueReport Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateIssueReportCommand` | Crear nuevo reporte de problema |
| `UpdateIssueReportCommand` | Actualizar estado y resolución del reporte |
| `CloseIssueReportCommand` | Cerrar reporte resuelto |

- IssueReport Queries:

| Query | Propósito |
|-------|-----------|
| `GetAllIssueReportsQuery` | Obtener todos los reportes del sistema |
| `GetIssueReportByIdQuery` | Obtener reporte específico por identificador |
| `GetAllIssueReportsByResidentIdQuery` | Reportes realizados por un residente |
| `GetAllIssueReportsByProviderIdQuery` | Reportes asignados a un proveedor |
| `GetOpenIssueReportsQuery` | Reportes pendientes de resolución |

#### **Servicios de Dominio**
| Servicio | Tipo | Responsabilidad |
|----------|------|----------------|
| `WaterSupplyRequestCommandService` | Command Service | Gestión del ciclo de vida de solicitudes, validaciones de negocio |
| `WaterSupplyRequestQueryService` | Query Service | Consultas complejas sobre solicitudes y métricas |
| `IssueReportCommandService` | Command Service | Procesamiento de reportes, asignación automática |
| `IssueReportQueryService` | Query Service | Análisis de reportes, tendencias y estadísticas |


### 5.4.2 Interface Layer

#### **Controladores REST**
| Controlador | Responsabilidad |
|-------------|----------------|
| `WaterSupplyRequestController` | CRUD de solicitudes, gestión de estados, asignaciones |
| `IssueReportController` | Gestión de reportes, seguimiento de resoluciones |

#### **Anti-Corruption Layer (ACL)**
| Facade | Responsabilidad |
|---------|----------------|
| `WaterSupplyRequestContextFacade` | Integración de solicitudes con otros contextos |
| `IssueReportContextFacade` | Exposición de información de reportes |

### 5.4.3 Application Layer

#### **Servicios de Aplicación**
| Implementación | Responsabilidad |
|----------------|----------------|
| `WaterSupplyRequestCommandServiceImpl` | Orquestación de creación y actualización de solicitudes |
| `WaterSupplyRequestQueryServiceImpl` | Implementación de búsquedas y reportes de solicitudes |
| `IssueReportCommandServiceImpl` | Coordinación de creación y seguimiento de reportes |
| `IssueReportQueryServiceImpl` | Análisis y consultas complejas de reportes |
| `RequestAssignmentService` | Asignación automática de solicitudes a proveedores |
| `NotificationService` | Notificaciones automáticas sobre cambios de estado |
| `SLAMonitoringService` | Monitoreo de tiempos de respuesta y SLAs |

### 5.4.4 Infrastructure Layer

#### **Repositorios JPA**
| Repositorio | Responsabilidad |
|-------------|----------------|
| `WaterSupplyRequestRepository` | Persistencia optimizada para consultas por estado y fecha |
| `IssueReportRepository` | Almacenamiento con búsqueda full-text en descripciones |

#### **Servicios de Infraestructura**
| Servicio | Responsabilidad |
|----------|----------------|
| **Workflow Engine** | Motor de flujo de trabajo para estados de solicitudes |
| **Priority Assignment** | Sistema de priorización automática de solicitudes |
| **Delivery Tracking** | Integración con sistemas de tracking de entregas |
| **Analytics Engine** | Procesamiento de métricas de performance y satisfacción |

### 5.4.5 Bounded Context Software Architecture Component Level Diagrams

El diagrama de componentes muestra cómo los controladores REST (WaterSupplyRequestController, IssueReportController) exponen los endpoints para la gestión de solicitudes de agua y reportes de problemas. Cada controlador delega la lógica a servicios de aplicación que implementan los contratos definidos en el dominio. Los servicios gestionan los agregados WaterSupplyRequest e IssueReport, así como los comandos y queries asociados. Los componentes ACL (Context Facades) permiten exponer información controlada a otros bounded contexts, asegurando el aislamiento y la integridad de los datos. Este diseño facilita la extensibilidad y la integración segura entre módulos, manteniendo la consistencia y la separación de responsabilidades.


![alt text](<structurizr-101610-RequestManagementComponents (1).png>)

### 5.4.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.4.6.1 Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Domain Layer ilustra la estructura y relaciones entre los principales agregados (WaterSupplyRequest, IssueReport), value objects, servicios de dominio y comandos/queries. Los servicios de comando y consulta definen los contratos para la gestión de entidades, mientras que los agregados encapsulan la lógica de negocio y las reglas de validación. Los value objects como IssueReportStatus garantizan la inmutabilidad y la igualdad por valor. Los comandos permiten la creación y actualización de entidades, y los queries facilitan la obtención de información específica. Este diseño promueve la claridad, la extensibilidad y la protección de invariantes de negocio, permitiendo agregar nuevas funcionalidades sin afectar la arquitectura base.

![alt text](<./assets/CAPITULO5/request/xLhTRjj64xtFK_2IWk8ym8V0YECe7mIuTYgbpcL0asELBN-KtPKReOsVlPHMaGur6WtfhMCOY2zactlcpC-U7NANUcDTOjoYB5waHM9jz2bnPAQB-RnOJkZBWgoB_duHRNvUlpwRpGpD6amqgMjtUheTEhcegrcKPtiN3DayeygDzmVcfhvhHWmEJ9t9Lp (1).png>)

#### 5.4.6.2 Bounded Context Database Design Diagram

El diagrama de base de datos representa la estructura de persistencia para las solicitudes de agua y los reportes de problemas. Incluye las tablas principales WATER_SUPPLY_REQUEST e ISSUE_REPORT, así como las relaciones con las tablas de residentes y proveedores. La base de datos almacena información histórica y actual de cada entidad, permitiendo consultas eficientes y la trazabilidad de las relaciones entre usuarios, proveedores y residentes. Se definen restricciones de unicidad y claves foráneas para garantizar la integridad referencial y la consistencia de los datos. Este diseño soporta la escalabilidad y la seguridad, facilitando la integración con otros módulos y la implementación de consultas especializadas para reportes y métricas.

![alt text](<./assets/CAPITULO5/request/Captura de pantalla 2025-10-03 122241.png>)
---

## 5.5 Subscriptions Bounded Context

### 5.5.1 Domain Layer

#### **Aggregates**

- Subscription Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `startDate` | `LocalDate` | Fecha de inicio de la suscripción al servicio |
| `endDate` | `LocalDate` | Fecha de finalización de la suscripción |
| `status` | `String` | Estado actual (activa, suspendida, cancelada, expirada) |
| `sensorId` | `Long` | Identificador del sensor IoT asociado |
| `residentId` | `Long` | Identificador del residente suscrito |
| `providerId` | `Long` | Identificador del proveedor del servicio |
| `waterTankSize` | `Float` | Capacidad del tanque de agua en litros |

#### **Subscription Commands y Queries**

- Subscription Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateSubscriptionCommand` | Crear nueva suscripción al servicio |
| `UpdateSubscriptionCommand` | Actualizar términos y condiciones de suscripción |
| `CreateAdditionalSubscriptionCommand` | Crear suscripción adicional para mismo residente |
| `SuspendSubscriptionCommand` | Suspender temporalmente la suscripción |
| `ReactivateSubscriptionCommand` | Reactivar suscripción suspendida |

- Subscription Queries:

| Query | Propósito |
|-------|-----------|
| `GetAllSubscriptions` | Obtener todas las suscripciones del sistema |
| `GetSubscriptionByUserId` | Obtener suscripción asociada a un usuario |
| `GetSubscriptionsByProviderId` | Suscripciones gestionadas por un proveedor |
| `GetAllSubscriptionsByResidentId` | Todas las suscripciones de un residente |
| `GetActiveSubscriptionsQuery` | Suscripciones actualmente activas |
| `GetExpiringSubscriptionsQuery` | Suscripciones próximas a vencer |

- ##### **Servicios de Dominio**
| Servicio | Tipo | Responsabilidad |
|----------|------|----------------|
| `SubscriptionCommandService` | Command Service | Gestión del ciclo de vida completo de suscripciones |
| `SubscriptionQueryService` | Query Service | Consultas complejas y reportes de suscripciones |
| `SubscriptionValidationService` | Domain Service | Validaciones de reglas de negocio específicas |


### 5.5.2 Interface Layer

#### **Controladores REST**
| Controlador | Responsabilidad |
|-------------|----------------|
| `SubscriptionController` | CRUD de suscripciones, gestión de renovaciones automáticas |

#### **Anti-Corruption Layer (ACL)**
| Facade | Responsabilidad |
|---------|----------------|
| `SubscriptionContextFacade` | Integración con sistemas de billing y facturación |


### 5.5.3 Application Layer

#### **Servicios de Aplicación**

| Implementación | Responsabilidad |
|----------------|----------------|
| `SubscriptionCommandServiceImpl` | Lógica de creación, renovación y cancelación de suscripciones |
| `SubscriptionQueryServiceImpl` | Implementación de consultas de suscripciones y reportes |
| `BillingIntegrationService` | Integración con sistemas de facturación y pagos |
| `RenewalManagementService` | Gestión automática de renovaciones y vencimientos |
| `SubscriptionMetricsService` | Cálculo de métricas de retención y churn |
| `NotificationSchedulerService` | Programación de notificaciones de vencimiento |


### 5.5.4 Infrastructure Layer

#### **Repositorios**
| Repositorio | Responsabilidad |
|-------------|----------------|
| `SubscriptionRepository` | Persistencia con índices para consultas por fecha y estado |
| `SubscriptionQueryService` | Consultas especializadas con proyecciones optimizadas |

#### **Servicios de Infraestructura**
| Servicio | Responsabilidad |
|----------|----------------|
| **Payment Gateway** | Integración con procesadores de pagos externos |
| **Billing System** | Sistema de generación automática de facturas |
| **Renewal Scheduler** | Programador de tareas para renovaciones automáticas |
| **Usage Tracking** | Seguimiento de uso de servicios por suscripción |

### 5.5.5 Bounded Context Software Architecture Component Level Diagrams

El diagrama de componentes muestra cómo el controlador REST (SubscriptionController) expone los endpoints para la gestión de suscripciones y operaciones relacionadas. El controlador delega la lógica a servicios de aplicación que implementan los contratos definidos en el dominio. Los servicios gestionan el agregado Subscription y los comandos y queries asociados. La infraestructura incluye repositorios y la integración con servicios externos para notificaciones y validaciones. Los componentes ACL (Context Facades) permiten exponer información controlada a otros bounded contexts, asegurando el aislamiento y la integridad de los datos. Este diseño facilita la extensibilidad y la integración segura entre módulos, manteniendo la consistencia y la separación de responsabilidades.

![alt text](structurizr-101610-SubscriptionComponents.png)

### 5.5.6 Bounded Context Software Architecture Code Level Diagrams

#### 5.5.6.1 Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Domain Layer ilustra la estructura y relaciones entre el agregado principal (Subscription), los servicios de dominio y los comandos/queries. Los servicios de comando y consulta definen los contratos para la gestión de suscripciones, mientras que el agregado encapsula la lógica de negocio y las reglas de validación. Los comandos permiten la creación y actualización de entidades, y los queries facilitan la obtención de información específica. Este diseño promueve la claridad, la extensibilidad y la protección de invariantes de negocio, permitiendo agregar nuevas funcionalidades sin afectar la arquitectura base.

![alt text](<./assets/CAPITULO5/suscripcion/xLbVRnit37_VfxX76vxx0OOYg9CsGu0Lw-mKUnoK4-qAkvDkeiwDzoUVVP9L9vHrTEH3i0B5yc3OH_AddtuYPT9vWqvOrxVDTvN_gnk1MAtwEwojwfmoklhB6-BVwzUBpSR2HZYebiQuYuj7q_mdepULalH1BPgtmNM_G7WtP0GjKzFAMQKt8SZrU8IFeD7O6t.png>)

#### 5.5.6.2 Bounded Context Database Design Diagram

El diagrama de base de datos representa la estructura de persistencia para las suscripciones. Incluye la tabla principal SUBSCRIPTION y sus relaciones con las tablas de residentes y proveedores. La base de datos almacena información histórica y actual de cada suscripción, permitiendo consultas eficientes y la trazabilidad de las relaciones entre usuarios, proveedores y residentes. Se definen restricciones de unicidad y claves foráneas para garantizar la integridad referencial y la consistencia de los datos. Este diseño soporta la escalabilidad y la seguridad, facilitando la integración con otros módulos y la implementación de consultas especializadas para reportes y métricas.


![alt text](<./assets/CAPITULO5/suscripcion/Captura de pantalla 2025-10-03 133949.png>)


---

## 5.6 Predictive Analytics Bounded Context

### 5.6.1 Domain Layer


#### **Aggregates**

- PredictionModel Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `modelId` | `String` | Identificador único del modelo predictivo |
| `modelType` | `ModelType` | Tipo de modelo (CONSUMPTION_PREDICTION, DEMAND_FORECASTING, ANOMALY_DETECTION) |
| `version` | `String` | Versión del modelo entrenado |
| `accuracy` | `Float` | Precisión del modelo en validaciones |
| `trainingDate` | `LocalDateTime` | Fecha de último entrenamiento |
| `status` | `ModelStatus` | Estado del modelo (TRAINING, ACTIVE, DEPRECATED, FAILED) |
| `parameters` | `ModelParameters` | Parámetros de configuración del modelo |

- ConsumptionPrediction Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `predictionId` | `String` | Identificador único de la predicción |
| `residentId` | `Long` | Identificador del residente para quien se predice |
| `providerId` | `Long` | Identificador del proveedor asociado |
| `predictedConsumption` | `Float` | Consumo predicho en litros |
| `predictionPeriod` | `PredictionPeriod` | Período de la predicción (DAILY, WEEKLY, MONTHLY) |
| `confidence` | `Float` | Nivel de confianza de la predicción (0.0 - 1.0) |
| `generatedAt` | `LocalDateTime` | Momento de generación de la predicción |
| `factors` | `List<PredictionFactor>` | Factores considerados en la predicción |

- AlertRule Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `ruleId` | `String` | Identificador único de la regla de alerta |
| `ruleName` | `String` | Nombre descriptivo de la regla |
| `condition` | `AlertCondition` | Condición que dispara la alerta |
| `threshold` | `Float` | Umbral numérico para activar la alerta |
| `severity` | `AlertSeverity` | Severidad de la alerta (LOW, MEDIUM, HIGH, CRITICAL) |
| `isActive` | `Boolean` | Estado de activación de la regla |
| `targetContext` | `String` | Contexto de destino para la acción automática |

- DataPattern Aggregate:

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| `patternId` | `String` | Identificador único del patrón detectado |
| `patternType` | `PatternType` | Tipo de patrón (SEASONAL, TREND, ANOMALY, CYCLIC) |
| `description` | `String` | Descripción del patrón identificado |
| `detectionDate` | `LocalDateTime` | Fecha de detección del patrón |
| `confidence` | `Float` | Confianza en la detección del patrón |
| `affectedResidents` | `List<Long>` | Lista de residentes afectados por el patrón |
| `metadata` | `Map<String, Object>` | Metadatos adicionales del patrón |

#### **Value Objects**
| Value Object | Atributos | Descripción |
|--------------|-----------|-------------|
| `ModelType` | `CONSUMPTION_PREDICTION, DEMAND_FORECASTING, ANOMALY_DETECTION` | Tipos de modelos de machine learning |
| `ModelStatus` | `TRAINING, ACTIVE, DEPRECATED, FAILED` | Estados del modelo predictivo |
| `PredictionPeriod` | `DAILY, WEEKLY, MONTHLY, QUARTERLY` | Períodos de tiempo para predicciones |
| `AlertSeverity` | `LOW, MEDIUM, HIGH, CRITICAL` | Niveles de severidad de alertas |
| `PatternType` | `SEASONAL, TREND, ANOMALY, CYCLIC` | Tipos de patrones detectables |
| `ModelParameters` | `hyperparameters: Map<String, Object>` | Parámetros de configuración del modelo |

#### **PredictionModel Commands y Queries**

- PredictionModel Commands:

| Comando | Propósito |
|---------|-----------|
| `TrainPredictionModelCommand` | Entrenar nuevo modelo predictivo |
| `UpdateModelParametersCommand` | Actualizar parámetros del modelo |
| `DeployModelCommand` | Desplegar modelo entrenado a producción |
| `RetireModelCommand` | Retirar modelo obsoleto |

- PredictionModel Queries:

| Query | Propósito |
|-------|-----------|
| `GetActiveModelsQuery` | Obtener modelos activos por tipo |
| `GetModelPerformanceQuery` | Métricas de rendimiento del modelo |
| `GetModelHistoryQuery` | Historial de versiones del modelo |

#### **ConsumptionPrediction Commands y Queries**

- ConsumptionPrediction Commands:

| Comando | Propósito |
|---------|-----------|
| `GeneratePredictionCommand` | Generar nueva predicción de consumo |
| `BatchPredictionCommand` | Generar predicciones masivas |
| `ValidatePredictionCommand` | Validar precisión de predicciones pasadas |

- ConsumptionPrediction Queries:

| Query | Propósito |
|-------|-----------|
| `GetPredictionsByResidentQuery` | Predicciones de un residente específico |
| `GetPredictionsByProviderQuery` | Predicciones agrupadas por proveedor |
| `GetPredictionAccuracyQuery` | Análisis de precisión de predicciones |

#### **AlertRule Commands y Queries**

- AlertRule Commands:

| Comando | Propósito |
|---------|-----------|
| `CreateAlertRuleCommand` | Crear nueva regla de alerta predictiva |
| `UpdateAlertRuleCommand` | Modificar condiciones de alerta existente |
| `TriggerAutomaticActionCommand` | Ejecutar acción automática basada en alerta |

- AlertRule Queries:

| Query | Propósito |
|-------|-----------|
| `GetActiveAlertRulesQuery` | Obtener reglas activas de alerta |
| `GetTriggeredAlertsQuery` | Historial de alertas disparadas |
| `GetAlertStatisticsQuery` | Estadísticas de efectividad de alertas |

#### **DataPattern Commands y Queries**

- DataPattern Commands:

| Comando | Propósito |
|---------|-----------|
| `DetectPatternsCommand` | Ejecutar detección de patrones en datos |
| `AnalyzeAnomaliesCommand` | Análisis específico de anomalías |

- DataPattern Queries:

| Query | Propósito |
|-------|-----------|
| `GetPatternsByTypeQuery` | Patrones detectados por tipo |
| `GetAnomaliesQuery` | Anomalías detectadas en período específico |
| `GetSeasonalPatternsQuery` | Patrones estacionales identificados |

#### **Servicios de Dominio**
| Servicio | Tipo | Responsabilidad |
|----------|------|----------------|
| `ConsumptionPredictionService` | Domain Service | Predicciones de consumo de agua basadas en datos históricos |
| `PatternDetectionService` | Domain Service | Detección automática de patrones y tendencias en datos |
| `AutoRequestGenerationService` | Domain Service | Generación automática de solicitudes basada en predicciones |
| `ModelTrainingService` | Domain Service | Entrenamiento y validación de modelos de machine learning |
| `AnomalyDetectionService` | Domain Service | Detección de anomalías y comportamientos atípicos |

### 5.6.2 Interface Layer

#### **Controladores REST**
| Controlador | Responsabilidad |
|-------------|----------------|
| `PredictionController` | Endpoints para consultar y generar predicciones |
| `ModelManagementController` | Gestión de modelos de machine learning |
| `AlertController` | Configuración y monitoreo de alertas predictivas |

#### **Anti-Corruption Layer (ACL)**
| Facade | Responsabilidad |
|---------|----------------|
| `PredictiveAnalyticsContextFacade` | Integración con plataformas de ML y otros bounded contexts |


### 5.6.3 Application Layer

#### **Servicios de Aplicación**
| Implementación | Responsabilidad |
|----------------|----------------|
| `MachineLearningOrchestrator` | Orquestación completa de procesos de machine learning |
| `PredictiveAnalyticsService` | Servicios de alto nivel para análisis predictivo |
| `AutomatedWorkflowService` | Flujos automáticos basados en predicciones y alertas |
| `ModelLifecycleService` | Gestión del ciclo de vida completo de modelos ML |
| `DataPipelineService` | Pipelines de datos para alimentar modelos predictivos |
| `ForecastingService` | Servicios especializados en pronósticos de demanda |


### 5.6.4 Infrastructure Layer

#### **Repositorios JPA**
| Repositorio | Responsabilidad |
|-------------|----------------|
| `PredictionModelRepository` | Persistencia de modelos y metadatos |
| `ConsumptionPredictionRepository` | Almacenamiento de predicciones con índices temporales |
| `AlertRuleRepository` | Gestión de reglas de alerta y configuraciones |
| `DataPatternRepository` | Persistencia de patrones detectados |

#### **Servicios de Infraestructura**
| Servicio | Responsabilidad |
|----------|----------------|
| **TensorFlow Integration** | Integración con TensorFlow para modelos de deep learning |
| **Azure Machine Learning** | Plataforma cloud para entrenamiento y deployment de modelos |
| **Apache Spark Connector** | Procesamiento distribuido de grandes volúmenes de datos |
| **Time Series Analytics** | Servicios especializados para análisis de series temporales |
| **Model Registry** | Registro y versionado de modelos de machine learning |
| **Data Lake Integration** | Conexión con repositorios de datos históricos |


### 5.6.5 Bounded Context Software Architecture Component Level Diagrams

El diagrama de componentes muestra cómo los controladores REST (PredictionController, ModelController) permiten la interacción entre el usuario y el módulo de análisis predictivo. Los servicios de aplicación gestionan el flujo de predicción, entrenamiento y despliegue de modelos, integrando el servicio externo de Machine Learning (TensorFlow Platform) para el procesamiento y entrenamiento de modelos. La infraestructura conecta con los bounded contexts de Water Management, Requests, Analytics y Subscriptions para obtener datos históricos y enviar resultados de predicción. El diseño asegura la extensibilidad y la integración segura, permitiendo que el módulo de análisis predictivo anticipe la demanda de agua, detecte patrones críticos y genere alertas o solicitudes automáticas.

![alt text](structurizr-101610-PredictiveAnalyticsComponents.png)

### 5.6.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.6.6.1 Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Domain Layer ilustra la estructura y relaciones entre los agregados principales (Prediction, MLModel), los value objects y los servicios de dominio. Los servicios de comando y consulta definen los contratos para la gestión de predicciones y modelos, mientras que los agregados encapsulan la lógica de negocio y las reglas de validación. Los value objects como PredictionType y ModelStatus garantizan la inmutabilidad y la claridad semántica. Este diseño promueve la extensibilidad y la protección de invariantes, permitiendo agregar nuevos algoritmos y flujos de predicción sin afectar la arquitectura base.

![alt text](<./assets/CAPITULO5/Predictive Analytics/bHZRSfiwyBrVmQCpf_c3JgVK48SvyQKsQQTF7HNMZivmuKZ2hTkSVFiHeB82hM6IXrZQ-sMrMl51AYPKdMTlFFsNP4nARoSWvOdYPR4kKyYytnhN_TqUbE35oSiRU9GYl2MCBnLeb5avJ6SGKij4-5rMCkMn9Aa5Iou8VoWJbWLCGSnpy9HWlD3y3M2ayA.png>)

#### 5.6.6.2 Bounded Context Database Design Diagram

El diagrama de base de datos representa la estructura de persistencia para las predicciones, modelos de machine learning y métricas de desempeño. Incluye las tablas principales PREDICTION, ML_MODEL y MODEL_METRICS, así como sus relaciones. La base de datos almacena información histórica y actual de cada predicción y modelo, permitiendo consultas eficientes, trazabilidad y análisis de desempeño. Se definen claves foráneas y campos JSON para flexibilidad y escalabilidad, facilitando la integración con otros módulos y la mejora continua de los algoritmos predictivos.

![alt text](<./assets/CAPITULO5/Predictive Analytics/Captura667.png>)
---

# Chapter VI: Solution UX Design

## 6.1 Style Guidelines
### 6.1.1. General Style Guidelines

Los siguientes elementos se han considerado para mejorar la experiencia del usuario.
COLOR: Para los colores hemos elegido un esquema monocromático del color #81c9fa

![alt text](<./assets/img/colores.png>)


Se eligió este esquema debido a que el color azul y blanco representan un entorno ordenado, limpio y poco complejo, lo que son practicamente caracteristicas que nos ayudarán con los procesos de gestion

Tiporafía: Para la tipografia se está usando Comfortaa principalmente pr su simplicidad y buen diseño en las paginas web.
<br>![alt text](<./assets/img/Comfortaa.png>)

Branding: Nuestro logotipo nuestra el nombre del producto AquaConecta, resaltando en azul parte del mismo, pensamos en un logo minimalista que con el hecho de verse el logo se pueda distinguir quienes somos.
![alt text](<./assets/img/logo.png>)

### 6.1.2. Web Style Guidelines
En nuestra app web y landing page estamos usando los colores ya mencionados en diferentes maneras.
Background: Color Primario: 539BCA Color Secundario: BAE0FC Color Terniario: 6A9CDE y 003785
![alt text](<./assets/img/aquawire.png>)
Text Styles: (H1, H2, p, a,) Nuestros estilos de texto van a depender del color que tengan detras, para colores mas osucros como 003785 se usa EEEEEE para dar contraste, mientras que si es un color claro se usa 00628D para que el color del texto pueda resaltar.
![alt text](<./assets/img/ola.png>)

Icons: (Fondo blanco con los iconos que vamos a usar)

Los iconos que estaremos usando seran de las redes sociales en el caso de la landing page junto a otros relacionados a los beneficios. Seguidamente, se estaran utilizando menos iconos en la web aplication siendo los mas prominentes la lupa, icono de residente y proveedores
<br>
![alt text](<./assets/img/search.png>)


Estaremos usando nav vars, tablas y dashboards para poner informacion de sensores, reportes y el historial.

![alt text](<./assets/img/navbar.png>)

## 6.2 Software Architecture

### 6.2.1 Organization System

La aplicación **AquaConecta** utiliza un sistema de organización secuencial. Desde la pantalla principal, los usuarios pueden navegar paso a paso por las funcionalidades críticas del sistema: como el acceso al panel de administrador, solicitud de suministros, generación de reportes, gestión de proveedores, visualización de residentes y monitoreo del historial de sensores. Este enfoque facilita la navegación y asegura que los usuarios completen tareas en un orden lógico y estructurado.

![alt text](<./assets/img/dashboard1.png>)
*Pantalla principal del administrador.*


![alt text](<./assets/CAPITULO6/Captura de pantalla 2025-10-07 182009.png>)
*Pantalla principal de los proveedores.*


### 6.2.2 Labeling System
Se han implementado etiquetas claras y concisas para representar funciones específicas dentro de la aplicación. Estas etiquetas ayudan a los usuarios a comprender fácilmente la función de cada módulo. Las etiquetas principales son:

- `Admin Dashboard`
- `Supply Requests`
- `Report List`
- `Providers List`
- `Provider Profile`
- `Residents`
- `Sensor Monitoring`
- `Consumption Predictions`

Estas permiten una identificación directa de las secciones sin necesidad de interpretación adicional.

### 6.2.3 SEO Tags and Meta Tags 

Para optimizar la visibilidad en buscadores y ofrecer contexto sobre la aplicación, se proponen las siguientes etiquetas:

Título: AquaConecta | Solución Inteligente de Gestión del Agua

Description: meta name="description" content="Gestión eficiente de agua a través de sensores, reportes y control de usuarios y proveedores. Plataforma integral para comunidades." /

Palabras clave: Gestión del agua, sensores de agua, AquaConecta, plataforma hídrica, sistema de suministro, comunidades rurales"


### 6.2.4. Searching Systems 
¿Qué se busca?: El usuario puede buscar residentes, proveedores o registros históricos de sensores.
¿Qué resultados se mostrarán?: La búsqueda devolverá registros específicos como nombres de usuarios, reportes o datos de sensores.
Interfaz de búsqueda: En el panel principal se presentan botones con acceso directo a funcionalidades clave. Aunque actualmente no hay un ícono de lupa visible, se recomienda su implementación en secciones como Residents o Sensor History para mejorar la usabilidad y facilitar la búsqueda contextual.

### 6.2.5. Navigation Systems
La navegación se basa en un sistema global donde, desde la pantalla de inicio, los usuarios pueden acceder directamente a cualquier sección mediante botones claramente etiquetados. Esta navegación plana y accesible garantiza una experiencia intuitiva, reduciendo la necesidad de múltiples clics o rutas complejas.

## 6.3 Landing Page UI Design 

### 6.3.1 Landing Page Wireframe
![alt text](<./assets/img/wireframelanding.png>)

### 6.3.2 Landing Page Mock Up

![alt text](<./assets/img/mockuplanding.png>)


## 6.4 Applications UX/UI Design.

### 6.4.1 Applications Wireframes
En esta sección, se presentan los wireflows de la aplicación guiándose de las historias de usuario en la herramienta Figma.

https://www.figma.com/design/qX7HAGMI1mEN4ddBdaNBLh/Untitled?node-id=2-753&t=tRdexuYpspb54rXk-0



Application web wireframes

![alt text](<./assets/img/iniciowirefram.png>)
<br>
![alt text](<./assets/img/supplywire.png>)
<br>
![alt text](<./assets/img/schedulewire.png>)
<br>![alt text](<./assets/img/providerswire.png>)
![alt text](<./assets/img/nosewire.png>)<br>
![alt text](<./assets/img/profilewire.png>)<br>

![alt text](<./assets/CAPITULO6/createResident.png>)<br>
![alt text](<./assets/img/pagowire.png>)<br>

![alt text](<./assets/img/residentswire.png>)<br>
![alt text](<./assets/CAPITULO6/inforesident.png>)<br>
![alt text](<./assets/CAPITULO6/payment1.png>)<br>
![alt text](<./assets/CAPITULO6/payment.png>)<br>
![alt text](<./assets/img/listreportwire.png>)<br>
![alt text](<./assets/img/reportdetailwire.png>)<br>


![alt text](<./assets/CAPITULO6/chooseResidentDevice.png>)<br>
![alt text](<./assets/CAPITULO6/choosedevice.png>)<br>
![alt text](<./assets/CAPITULO6/devicedata.png>)<br>
![alt text](<./assets/CAPITULO6/PrediccionB.png>)<br>



Application mobile wireframe

![alt text](<./assets/img/mobile1.png>)<br>
![alt text](<./assets/img/mobile2.png>)<br>
![alt text](<./assets/img/mobile3.png>)<br>
![alt text](<./assets/img/mobile4.png>)<br>
![alt text](<./assets/img/mobile5.png>)<br>
![alt text](<./assets/img/mobile6.png>)<br>

### 6.4.2 Applications Wireflow Diagrams

Los Wireflows se utilizan principalmente en el diseño UX o por sus siglas, experiencia de usuario y especialmente para aplicaciones que involucran flujos de trabajo e interacciones complejas.



Aplicación web: Dentro de la aplicación web desarrollamos los wireframes para las vistas de proveedores y administrador. Por ello, lo adecuamos a los siguientes user goals.

Se pueden visualizar los diagramas mediante el siguiente link:

[Wireflow Diagrams](https://miro.com/welcomeonboard/eGsxNWkweU5aa1ZaSU44NXMweXNaZmp2N1FxVlNTTVptbVg1NXFwaTFCbnJRc3JyOHZPZlV4VHJhenRlM0lSako3UXdNcFRGYThmbEg5Ym93QzVTWXRkV3ZzVi9DRDZwOHFYSUFQMk8vU0NlczNibDFmTnlBTDR4b2F6MnJWUENBS2NFMDFkcUNFSnM0d3FEN050ekl3PT0hdjE=?share_link_id=175649095908)

- **User goal:** Iniciar sesión

  Como admnistrador o proveedor quiero autenticarme en la aplicaión web para acceder al monitoreo de habitantes y/o proveedores.
![alt text](./assets/wireflow-diagrams/web-app/log-app-web.png)

**Proveedores**

- **User goal:** Crear nuevo habitante

  Como proveedor quiero registrar nuevo residente completando toda la información requerida (nombre, ubicación, contacto) y confirmar su correcta incorporación al sistema.
![alt text](assets/wireflow-diagrams/web-app/create-resident-provider.png)

- **User goal:** Crear una nueva suscripcion para un residente

  Como proveedor quiere crear y asignar una nueva suscripcion a un residente ya registrado para tener un mejor manejo de datos en caso el residente tenga mas de un tanque de agua 
![alt text](assets/wireflow-diagrams/web-app/add-new-susb.png)

- **User goal:** Ver información de los habitantes

  Como proveedor quiero ver la información de cada uno de mis habitantes para conocer su informacion detallada en caso la necesite.
![alt text](assets/wireflow-diagrams/web-app/view-residents-information1.png)

- **User goal:** Ver solicitudes de abastecimiento

  Como proveedor quiero visualizar las solicitudes de abastecimiento para editar el status y agendar la fecha de entrega.
![alt text](assets/wireflow-diagrams/web-app/view-supply-requests-provider.png)

- **User goal:** Ver reportes de problemas 

  Como proveedor quiero visualizar los reportes de fallas en sensores para solucionar los respectivos problemas.
![alt text](assets/wireflow-diagrams/web-app/view-reports-provider.png)

- **User goal:** Ver datos de los sensores
 
  Como proveedor quiero visualizar los datos de los sensores para tener registros sobre el nivel, calidad de todos mis residentes.
![alt text](assets/wireflow-diagrams/web-app/visualizar-device-data.png)


- **User goal:** Ver Prediccion de consumo

  Como proveedor, quiero ver la predicción de consumo de mis residentes para identificar anomalías, entender tendencias y tomar decisiones operativas basadas en datos.
![alt text](assets/wireflow-diagrams/web-app/image.png)


**Administrador**

- **User goal:** Ver información de provedores 
  
  Como admnistrador quiero ver la información de todos los proveedores para tener control de planes activos.
![alt text](assets/wireflow-diagrams/web-app/view-providers-info-admin.png)

- **User goal:** Ver solicitudes de abastecimiento
  
  como admnistrador quiero ver la información de todas las solicitudes de abastecimiento realizadas por cada habitante.
![alt text](assets/wireflow-diagrams/web-app/view-supply-request-admin.png)

- **User goal:** Ver reportes
  
  Como administrador quiero ver toda la información de los reportes acerca de problemas en los sensores.
![alt text](assets/wireflow-diagrams/web-app/view-reports-admin.png)


**Aplicación móvil:** Para la aplicación móvil hemos implementado los wireframes para los habitantes. Se presentan los diagramas de acuerdo a los usuer goals.

Se pueden visualizar los diagramas mediante el siguiente link:
[Wireflow Diagrams - Resident](https://lucid.app/lucidchart/d1e8d447-b081-4f2b-9758-7f90eac5e376/edit?invitationId=inv_3e49c8d7-d258-460c-9086-4e3648af4619)

- **User goal:** Iniciar sesión, como habitante quiero autenticarme en la aplicaión móvil con las credenciales brindadas por el proveedor para visualizar la información del agua en mi tanque.
![alt text](assets/wireflow-diagrams/mobile-app/log-in-mobile-app.png)

- **User goal:** Editar perfil, como residente quiero editar y actualizar la información de mi perfil. 
![alt text](assets/wireflow-diagrams/mobile-app/edit-profile-resident.png)

- **User goal:** Ver reportes, como residente deseo ver un historial de reportes acerca de los problemas de los sensores en el tanque.
![alt text](assets/wireflow-diagrams/mobile-app/view-reports-resident.png)

### 6.4.3 Applications Mockups

En esta sección, se presentan los mockups de la aplicación guiándose de las historias de usuario en la herramienta Figma.


 Link del figma: https://www.figma.com/design/zz3FlEYCsPIEo1Ah1tWQpx/AquaConecta-ASE?node-id=34-2&t=JZIevX0Fmshp0IZ4-1
 <br>
 ![alt text](<./assets/wireflow-diagrams/mockups/12.png>)<br>
 ![alt text](<./assets/img/mockup1.png>)<br>
![alt text](<./assets/img/mockup2.png>)<br>
![alt text](<./assets/img/mockup6.png>)<br>
![alt text](<./assets/img/mockup3.png>)<br>
![alt text](<./assets/img/mockup5.png>)<br>
![alt text](<./assets/img/mockup7.png>)<br>
![alt text](<./assets/img/mockup10.png>)<br>
![alt text](<./assets/img/mockup4.png>)<br>
![alt text](<./assets/wireflow-diagrams/mockups/18.png>)<br>
![alt text](<./assets/wireflow-diagrams/mockups/16.png>)<br>
![alt text](<./assets/wireflow-diagrams/mockups/17.png>)<br>
![alt text](<./assets/img/mockup9.png>)<br>
![alt text](<./assets/img/mockup11.png>)<br>
![alt text](<./assets/wireflow-diagrams/mockups/13.png>)<br>
![alt text](<./assets/wireflow-diagrams/mockups/14.png>)<br>
![alt text](<./assets/wireflow-diagrams/mockups/15.png>)<br>
![alt text](<./assets/CAPITULO6/Prediccion.png>)<br>

Application mobile mockup

![alt text](<./assets/img/mockupmobile1.png>)<br>
![alt text](<./assets/img/mockupmobile2.png>)<br>
![alt text](<./assets/img/mockupmobile3.png>)<br>
![alt text](<./assets/img/mockupmobile4.png>)<br>
![alt text](<./assets/img/mockupmobile5.png>)<br>
![alt text](<./assets/img/chatmock.png>)<br>
![alt text](<./assets/img/chatmenssa.png>)<br>


### 6.4.4 Applications User Flow Diagrams
Esta sección presenta la propuesta de User Flows. Se considera un User Flow para cada User goal, considerando los User Persona para cada aplicación que forma parte del alcance. Estos User Flows deben ser consistentes con los Wireflows de los cuales se derivan.

En este caso los user flow que definimos serian:


Login de Usuario Proveedor/Admin:

![alt text](./assets/wireflow-diagrams/UserFlow/fd11.png)

Programacion de fecha:

![alt text](./assets/img/fd3.png)

Creacion de nuevo residente:

![alt text](./assets/img/fd4.png)

Creacion de nueva suscripcion para residente:

![alt text](./assets/wireflow-diagrams/UserFlow/Captura%20de%20pantalla%202025-10-08%20170354.png)

Visualizar detalles de Residente:

![alt text](./assets/img/fd5.png)

Visulizar Reportes:

![alt text](./assets/wireflow-diagrams/UserFlow/fd5.png)

Visualizar Detalles de Proveedores:

![alt text](./assets/img/fd7.png)

Visualizar datos de los sensores:

![alt text](./assets/wireflow-diagrams/UserFlow/Captura%20de%20pantalla%202025-10-08%20170408.png)

Visualizar Prediccion de consumo:

![alt text](./assets/wireflow-diagrams/UserFlow/image.png)

## 6.5 Applications Prototyping.

Esta sección incluye Prototipos de UI para Desktop y Mobile Web Browser con simulación de interacción y navegación, acorde con la propuesta de paths de User Flow Diagrams. Esta sección inicia con una introducción en la que se explica los principales criterios para las decisiones de interacción.
<br>
 ![alt text](<./assets/wireflow-diagrams/mockups/12.png>)
<br>

Link del Figma: https://www.figma.com/design/zz3FlEYCsPIEo1Ah1tWQpx/AquaConecta-ASE?node-id=34-2&t=XN4NAi451gnm4mcn-1

## Capítulo VII: Product Implementation, Validation & Deployment

### 7.1. Software Configuration Management.

#### 7.1.1. Software Development Environment Configuration.

Figma: https://www.figma.com/

Es una herramienta visual, donde diseñamos el prototipo de la pagina web. Se usó para crear los wireframes, mock-ups, asi como los desktop and mobile application del proyecto.

LucidChart: https://lucid.app/

Es una plataforma, la cual tiene opciones que nos ayudaron en la creación de diagramas, mapas y flujos usando plantillas y tableros. Fue usado para la creación del event storming

PlantText: https://www.planttext.com/

Es una plataforma que permite interpretar código uml y diagramarlo. Fue usado para la creación de los diagramas de clase.

Software Development: Para el desarrollo de la landing page se utilizarón las tecnologías basicas del desarrollo web: HTML, CSS Y JS.

Frontend Web Applications

Para el desarrollo del Frontend de la aplicación web se utilizó Vue.Js junto con algunas librerias de material design como PrimeVue y PrimeFlex, además de Chart.Js para la generación de dashboards.

Software Deployment

Netlify: https://www.netlify.com/

Es una plataforma en la cual hospedamos la lading page del proyecto, se integra con repositorios en Git.

Vercel: https://vercel.com/

Es una plataforma en la cual hospedamos la aplicación web.

Software Documentation

Vertabelo: https://vertabelo.com/

Es una herramienta online la cual ayuda en el desarrollo y creacion de base de datos. Se usó para la base de datos del proyecto.

Structurizr: https://www.structurizr.com/

Esta plataforma permite el modelado de diagramas de arquitectura de software. Se usó para la creación de los diagramas C4


#### 7.1.2. Source Code Management.

Para la gestión y actualización del proyecto, se creó una organización via GitHub, en la cual se tuvo un control sobre los cambios a lo largo del ciclo de vida del proyect. Se organizo de la siguiente manera.

Organization: https://github.com/AquaConecta-ASE

Report repository: https://github.com/AquaConecta-ASE/Final-Project

Backend repository: https://github.com/AquaConecta-ASE/Backend

Frontend repository: https://github.com/AquaConecta-ASE/frontend

Mobile repository: https://github.com/AquaConecta-ASE/mobile

ML repository: https://github.com/AquaConecta-ASE/ML-Service

Para controlar de manera eficiente el flujo de trabajo se utilizó GitFlow, donde contamos con una rama principal main que es donde se encuentra la versión más estable y lista para pasar a producción del proyecto.

Ramas auxiliares:


feature: Son las ramas donde se desarrollan las funcionalidades del proyecto. Luego de completarlas, se fusionan con la rama develop.

Commit Conventions

Para el formato de los commits se siguió la estructura de Conventional Commits 1.0.0, la cual tiene la siguiente estructura:

< type > [optional scope]: < description > Donde:

type: Es el tipo de cambio. Tenemos valores como: fix, feat, build, chore, ci, docs, style, refactor, perf, test, etc. scope: Indica donde se realizó el commit (opcional). description: Menciona las actualizaciones del codigo.

#### 7.1.3. Source Code Style Guide & Conventions.

Durante el desarrollo en HTML y CSS, se optó por seguir la **Guía de Estilo de Google para HTML/CSS**. Algunos principios clave incluyen:

- Iniciar el documento con la declaración del tipo de documento y etiquetas meta adecuadas.
- Incluir la etiqueta `<title>` dentro de la sección `<head>`.
- Aplicar una **sangría de dos espacios** de manera consistente.
- Usar **letras minúsculas** para elementos HTML, atributos, valores, propiedades y selectores CSS.
- Encerrar los atributos HTML entre **comillas**.
- Asegurarse de que todos los elementos tengan su **etiqueta de cierre correspondiente**.
- Evitar líneas de código demasiado extensas.
- Las imágenes deben tener definidos su `width`, `height` y un atributo `alt` descriptivo.

Para JavaScript, se sigue la **guía de estilo de Google para C#**, que establece lo siguiente:

- Todas las instrucciones deben finalizar con un **punto y coma (`;`)**.
- Los nombres de variables y funciones deben escribirse en **UpperCamelCase**.
- Los valores de tipo cadena deben colocarse entre **comillas simples**.

En cuanto a las pruebas de aceptación escritas en **Gherkin**, se aplican las **convenciones para especificaciones legibles**, haciendo uso de palabras clave como `Dado`, `Cuando`, `Entonces` y `Y`, manteniendo sangría adecuada y comentarios bien organizados.

Para el desarrollo en **C#**, se respetan las **convenciones de nomenclatura de Microsoft**, las cuales contemplan:

- Reglas para nombrar carpetas, clases y métodos.
- Organización del código con una sangría clara y consistente.
- División de líneas largas para facilitar la lectura.
- Coincidencia entre el nombre del archivo y la clase que contiene.
- Uso de un **salto de línea** tras cada declaración.

En **C++**, se adoptan las pautas de la **Google C++ Style Guide**, donde:

- Se utiliza **CamelCase** para nombres de clases.
- Se emplea **snake_case** para variables, funciones y archivos.
- Se priorizan nombres descriptivos, evitando abreviaturas innecesarias.
- La sangría debe ser consistente, comúnmente de dos espacios.

Finalmente, para el lenguaje **Dart**, se siguen las normas de la **Effective Dart Style Guide**. Estas incluyen:

- Uso de **lowerCamelCase** para variables, funciones y parámetros.
- Uso de **UpperCamelCase** para clases, tipos y enumeraciones.
- Los archivos deben nombrarse usando **snake_case**.
- Es importante evitar líneas largas y mantener la consistencia en la sangría.

#### 7.1.4. Software Deployment Configuration.

Para el despliegue de la Landing Page y la Aplicación Web, se utiliza **GitHub Pages** y **Firebase Hosting** como servicios principales. 

Durante las primeras fases del desarrollo, se emplea **json-server en local** para simular datos (mock) y validar funcionalidades. Esta configuración permite trabajar sin una base de datos real durante las pruebas iniciales. Una vez que se tenga una base de datos definitiva, esta configuración será reemplazada por una conexión real.

### 7.2. Solution Implementation.

#### 7.2.1. Sprint 1

##### 7.2.1.1. Sprint Planning 1.

<table border="1">
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="3">Sprint Planning Background</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>2025-10-31</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>19:20 PM</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>La reunión se realizó virtualmente vía Discord</td>
        </tr>
        <tr>
            <td>Prepared By</td>
            <td>Cortez Quezada, Joaquin Antonio</td>
        </tr>
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>
                Oliveira Paucar, Mauricio / Hidalgo López, Mathias Adriano / Cortez Quezada, Joaquin Antonio / Periche Quiroga, Piero Fernando
            </td>
        </tr>
        <tr>
            <td>Sprint n – 1 Review Summary</td>
            <td>No aplica</td>
        </tr>
        <tr>
            <td>Sprint n – 1 Retrospective Summary</td>
            <td>No aplica</td>
        </tr>
        <tr>
            <td>Sprint n Goal</td>
            <td>
              El objetivo de este sprint es desarrollar una versión inicial de la aplicación web. Estas primeras versiones permitirán presentar la propuesta de valor del proyecto, mostrar sus beneficios y sentar las bases para futuras funcionalidades orientadas al usuario final.
            </td>
        </tr>
        <tr>
            <td>Sprint n Velocity</td>
            <td>26</td>
        </tr>
        <tr>
            <td>Sum of Story Points</td>
            <td>(Colocar la suma de los Story Points para los User Stories que se están incluyendo en este Sprint n.)</td>
        </tr>
    </tbody>
</table>

##### 7.2.1.2. Sprint Backlog 1.

| Sprint #    | Sprint 1 |           |             |             |                     |             |                                          |
|-------------|----------|-----------|-------------|-------------|---------------------|-------------|------------------------------------------|
| User Story  |          | Work-Item / Task |         |             |                     |             |                                          |
| Id          | Title    | Id        | Title       | Description | Estimation (Hours)   | Assigned To | Status (To-do / InProcess / ToReview / Done) |
| HU01 | Ver nivel actual del agua de los habitantes | T01 | Crear vista de monitoreo por habitante |Como proveedor quiero visualizar el nivel actual del agua de un habitante Para conocer la cantidad disponible. | 3 | Piero Periche | Done |
| HU05 | Historial de problemas de habitantes | T02 | Crear lista de reporte| Como proveedor quiero ver una lista con todos reportes de los problemas que han tenido mis clientes | 2 |Mathias Hidalgo | Done |
| HU06 | Gestionar solicitudes de agua de residentes | T03 | Crear una tabla con las solicitudes registradas | Como proveedor, quiero visualizar y gestionar las solicitudes de agua de mis residentes | 3 | Mauricio Oliveira | Done |
| HU07 | Visualizar suscripciones activas del proveedo | T04 | Crear vista detallada del proveedor | Como proveedor, Quiero ver todas las suscripciones de usuarios activas Para tener un registro de todos mis usuarios/habitantes activos. | 5 | Mauricio Oliveira | Done |
| HU13 | Registro de usuario web | T05 | Implementar formulario de autentificacion externo  | Como proveedor, Quiero registrarme desde la plataforma web ingresando mis datos | 5 | Joaquín Cortez | Done |
| HU14 | Inicio de sesión de usuario móvil | T06 | Implementar formulario de autentificacion externo | Como habitante, Quiero iniciar sesión desde la aplicación móvil, Para acceder a mi cuenta y monitorear el estado del agua en mi hogar. | 5 | Joaquín Cortez | Done |
| HU15 | Inicio de sesión web | T07 |Implementar formulario de autentificacion externo | Como proveedor, Quiero ingresar a la plataforma web con mis credenciales, Para gestionar mis servicios y usuarios asociados de forma segura. | 5 | Joaquín Cortez | Done |
| HU16 | Visualizacion y edicion de perfil | T08 | Formulario con informacion del usuario| Como habitante, Quiero ver y editar mi información personal desde la aplicación móvil | 3 | Mathias Hidalgo | Done |
| HU17 | Visualización y edición de perfil web | T09 | Formulario con informacion del usuario| Como proveedor, Quiero acceder y modificar mi perfil desde la plataforma web,Para gestionar mis datos de contacto y empresa de manera segura. | 3 | Piero Periche | Done |
| HU18 | Registrar nuevo residente | T10 | Formulario para registro |Como proveedor, Quiero registrar un nuevo residente Para que se genere automáticamente una suscripción que incluya el sensor y habilite el monitoreo del servicio de agua. | 8 | Joaquín Cortez | Done |
| HU19 | Añadir una nueva suscripción a un residente ya registrado | T11 | Formulario para registro | Como proveedor, Quiero agregar una nueva suscripción a un residente ya registrado | 5 | Joaquín Cortez | Done |

##### 7.2.1.3. Development Evidence for Sprint Review.

| Repository                   | Branch  | Commit Id | Commit Message                                                  | Commit Message Body                                           | Committed on (Date) |
|-----------------------------|---------|-----------|-----------------------------------------------------------------|----------------------------------------------------------------|---------------------|
|AquaConecta-ASE/Frontend|feature/iam|b551ce4|                                                     feat(iam): implementar callback Auth0 — token, perfil y redirecciónrequest                                                      ||09/10/2025 10:46 PM|
|AquaConecta-ASE/Frontend|feature/iam|9ec5aaa|                                              feat(iam): simplificar pantalla de login para Auth0 — UI y estilos table                                              ||09/10/2025 10:53 PM|
|AquaConecta-ASE/Frontend|feature/iam|d27524f|                                               fix(monitoring): fix device selection and event filtering                                           ||09/10/2025 11:03 PM|
|AquaConecta-ASE/Frontend|feature/iam|029012b|                          fix(monitoring): update device monitoring template and modal bindings                          ||09/10/2025 10:54 AM|
|<p>AquaConecta-ASE/Frontend</p><p></p>|feature/iam|f7e9655|                          fix(iam): fix provider profile load/create logic and persist correct IDs in localStorage                          ||09/10/2025 11:05 AM|
|<p>AquaConecta-ASE/Frontend</p><p></p>|feature/iam|6339482|                          feat(iam): provider profile form layout, validation messages and action buttons                          ||09/10/2025 11:08 AM|
|<p>AquaConecta-ASE/Frontend</p><p></p>|feature/iam|227f72b|                          fix(profiles): provider-summary, provider-api, device-data service and models - improve ID handling and event aggregation                        ||09/10/2025 11:16 AM|
|<p>AquaConecta-ASE/Frontend</p><p></p>|feature/iam|c12883b|                                       fix(residents): make ResidentService robust — handle object/array responses, use /residents/complete, and load provider profile correctly                                        ||09/10/2025 10:13 PM|
|AquaConecta-ASE/Frontend|feature/iam|ed19188|                                                 feat(iam): update home dashboard - metrics, filtering and UI fixes                                                 ||09/10/2025 10:47 AM|
|AquaConecta-ASE/Frontend|feature/iam|b014ea9|                                              fix(issue-reports): validate providerId and use providers/{id}/profiles; add logging for debugging                                               ||09/10/2025 12:18 PM|
|AquaConecta-ASE/Frontend|feature/iam|392fead|                                           fix(issue-reports): load and filter reports per provider, attach resident profile and normalize status labels                                            ||09/10/2025 12:54 PM|
|AquaConecta-ASE/Frontend|feature/iam|ba66caa|                                                    fix(water-requests): validate providerId, fix provider/resident endpoints and add debug logs                                                    ||09/10/2025 11:44 PM|
|AquaConecta-ASE/Frontend|feature/iam|ee12ec3|                                                    fix(subscriptions): remove MercadoPago and simplify add-subscription dialog logic                                                   ||09/10/2025 11:44 PM|
|AquaConecta-ASE/Frontend|feature/iam|87f27d9|                                                    feat(subscriptions): replace payment UI with simple create subscription form and actions                                                    ||09/10/2025 11:44 PM|
|AquaConecta-ASE/Frontend|feature/iam|a9a7d74|                                                    feat(iam): add create-resident component (form, styles, password reset modal)                                                    ||09/10/2025 11:44 PM|
|AquaConecta-ASE/Frontend|feature/iam|f1027aa|                                                    feat(iam): integrate Auth0 for authentication and add related routes and translations                                                    ||09/10/2025 11:44 PM|
|AquaConecta-ASE/Backend|feature/iam|754abc6|                                                    feat(iam): add Auth0UserSyncInterceptor and Auth0UserService to sync Auth0 users, roles and entities                                                    ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|49e54a5|                                                   feat(iam): add IamContextFacade and SignUpHandler (Auth0 user creation & facade)                                                   ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|303b8d1|                                                    feat(iam): add SignUpCommand and Role domain models                                                    ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|ca76eae|                                                    feat(monitoring): add DeviceController endpoints for devices and events (get device, get device events)                                                   ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|da2dac2|                                                    feat(profiles): add ProfileCommandServiceImpl, ProviderCommandServiceImpl and ResidentCommandServiceImpl (profile/provider/resident flows + Auth0 integration)                                                    ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|cfc9aad|                                                    feat(profiles): add Profile, CreateProfileCommand and Resident domain models                                                    ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|b14349a|                                                    feat(profiles): add CompleteResident resources and ResidentController endpoints for complete resident flow                                                    ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|61e3caf|                                                    feat(auth0): add Auth0ManagementService (create users, link metadata, password ticket)                                                    ||09/10/2025 1:05 AM|
|AquaConecta-ASE/Backend|feature/iam|461eee4|                                                    chore(project): add subscription facade, app entry, app properties and updated .gitignore                                                    ||09/10/2025 1:05 AM|

##### 7.2.1.4. Testing Suite Evidence for Sprint Review.

Durante el desarrollo del sprint 1 se implementaron pruebas unitarias e integrales para validar el comportamiento de las clases de negocio. Esto ayuda a asegurarnos que cada componente funcione correctamente, cumpliendo con su responsabilidad.

|Repository|Branch|Commit Id|Commit Message|Commit Message Body|Commited on (Date)|
| :- | :- | :- | :- | :- | :- |
|IronCoders-IOT / Backend|test|3d8c574|feature: Add unit tests for create provider||Nov 14, 2025, 11:47 A.M.|
|IronCoders-IOT / Backend|test|ce794ee|feature: Add unit tests for create resident||Nov 14, 2025, 11:47 A.M.|
|IronCoders-IOT / Backend|test|2c470ba|feature: Add integration tests for provider (create and update)||Nov 14, 2025, 11:48 A.M.|
|IronCoders-IOT / Backend|test|3c434a5|feature: Add integration tests for resident (create and update)||Nov 14, 2025, 11:48 A.M.|

A continuación, se presentarán imágenes de las pruebas unitarias y la prueba integral.

![alt text](assets/tests/Captura%20de%20pantalla%202025-11-14%20185826.png)
![alt text](assets/tests/Captura%20de%20pantalla%202025-11-14%20190109.png)
![alt text](assets/tests/Captura%20de%20pantalla%202025-11-14%20190139.png)
![alt text](assets/tests/Captura%20de%20pantalla%202025-11-14%20190218.png)


##### 7.2.1.5. Execution Evidence for Sprint Review.

En nuestro video de exposición, hemos incluido una demostración de la aplicación AquaConecta, donde se muestra cómo los proveedores pueden gestionar sus servicios. A continuación, se presentan capturas de pantalla que ilustran las funcionalidades clave de la aplicación:

- Se muestra captura de código del proyecto.
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192522.png)

- Se muestran las diversas vistas dentro de la aplicación web:
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20191517.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192002.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192016.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192036.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192050.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192101.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192119.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192130.png)
![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192142.png)

Se adjunta enlace para ingresar al video en el que se muestra lo logrado en este sprint 1.

- **Link de YouTube:**
[https://youtu.be/8PBCHlpW2zA](https://youtu.be/8PBCHlpW2zA)

##### 7.2.1.6. Services Documentation Evidence for Sprint Review.

Se hizo uso de Swagger para documentar los servicios de la aplicación AquaConecta. Esta herramienta permite a los desarrolladores y usuarios explorar y entender las API de manera interactiva. A continuación, se presentan capturas de pantalla que muestran la documentación generada por Swagger:

![alt text](assets/Services-Documentation/Captura%20de%20pantalla%202025-11-14%20195614.png)

![alt text](assets/Services-Documentation/Captura%20de%20pantalla%202025-11-14%20195710.png)

![alt text](assets/Services-Documentation/Captura%20de%20pantalla%202025-11-14%20195746.png)

##### 7.2.1.7. Software Deployment Evidence for Sprint Review.

La aplicación AquaConecta ha sido desplegada en Netlify, lo que permite a los usuarios acceder a la aplicación de manera sencilla y rápida. A continuación, se presentan capturas de pantalla que muestran el proceso de despliegue y el estado actual de la aplicación en Netlify:

![alt text](assets/sprint1/netly.png)

##### 7.2.1.8. Team Collaboration Insights during Sprint.

Finalmente, se presentan los insights de colaboración del equipo durante el Sprint 1, los cuales reflejan la coordinación efectiva y el trabajo continua entre los miembros en el desarrollo de los distintos productos de la solución AquaConecta. 

Backend:

![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-16%20021633.png)

Frontend:

![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-16%20022444.png)

Mobile:

![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-16%20022710.png)


#### 7.2.2. Sprint 2

##### 7.2.2.1. Sprint Planning 2.

<table border="1">
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="3">Sprint Planning Background</td>
        </tr>
        <tr>
            <td>Date</td>
            <td>2025-11-30</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>19:20 PM</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>La reunión se realizó virtualmente vía Discord</td>
        </tr>
        <tr>
            <td>Prepared By</td>
            <td>Cortez Quezada, Joaquin Antonio</td>
        </tr>
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>
                Oliveira Paucar, Mauricio / Hidalgo López, Mathias Adriano / Cortez Quezada, Joaquin Antonio / Periche Quiroga, Piero Fernando
            </td>
        </tr>
        <tr>
            <td>Sprint n – 2 Review Summary</td>
            <td>En este sprint hemos logrado desarrollar en su totalidad la funcionalidad del las prediciones sobre el consumo de agua de los residentes con machine learning y la implementacion del patron BFF consideran las aplicaciones de escritorio y dispositivos moviles</td>
        </tr>
        <tr>
            <td>Sprint n – 2 Retrospective Summary</td>
            <td>Se destacó el cumplimineto de todas las tareas en este sprint. Se identificó como mejora la necesidad de definir muy bien los criterios de aceptacion antes de empezar a hacer las tareas.</td>
        </tr>
        <tr>
            <td>Sprint n Goal</td>
            <td>
              Nuestro enfoque está en habilitar una experiencia integral de gestión y monitoreo del sistema AquaConecta en sus diferentes capas (dispositivo, borde, cloud y aplicaciones). Creemos que esto brinda visibilidad en tiempo real, automatización de procesos clave y una experiencia clara e informativa tanto para habitantes como para proveedores. Esto se confirmará cuando los habitantes puedan consultar el estado de su consumo desde la app móvil, los proveedores accedan a paneles centralizados en la web, el backend reciba datos seguros desde sensores cada 60 segundos.
            </td>
        </tr>
        <tr>
            <td>Sprint n Velocity</td>
            <td>103</td>
        </tr>
        <tr>
            <td>Sum of Story Points</td>
            <td>43</td>
        </tr>
    </tbody>
</table>

##### 7.2.2.2. Sprint Backlog 2.

| Sprint #    | Sprint 2 |           |             |             |                     |             |                                          |
|-------------|----------|-----------|-------------|-------------|---------------------|-------------|------------------------------------------|
| User Story  |          | Work-Item / Task |         |             |                     |             |                                          |
| Id          | Title    | Id        | Title       | Description | Estimation (Hours)   | Assigned To | Status (To-do / InProcess / ToReview / Done) |
| HU02 | Ver métricas del tanque de agua | T01 | Implementar dashboard de métricas en app móvil | Como habitante, Quiero visualizar el resumen de métricas de mi tanque Para conocer la cantidad disponible y solicitar el reabastecimiento correspondiente. | 5 | Mathias Hidalgo | Done |
| HU03 | Ver calidad del agua | T02 | Integrar medición de calidad del agua | Como habitante, Quiero que el sistema mida la calidad del agua, Para saber si es segura para el consumo de mi familia. | 4 | Piero Periche | Done |
| HU04 | Recibir datos actualizados constantemente | T03 | Implementar actualización en tiempo real de sensores | Como habitante, Quiero que el sistema realice lecturas frecuentes del agua, Para asegurarme de que la información sobre el nivel y la calidad esté siempre actualizada | 6 | Mauricio Oliveira | Done |
| HU20 | Ver suscripciones activas por residente | T04 | Crear vista de suscripciones por residente | Como proveedor, Quiero visualizar las suscripciones activas asociadas a los sensores de cada residente, Para conocer el estado de monitoreo de mis habitantes. | 4 | Joaquín Cortez | Done |
| HU21 | Ver todas las suscripciones del sistema | T05 | Implementar panel de administrador para suscripciones | Como administrador, Quiero visualizar todas las suscripciones del sistema, Para supervisar el uso de la plataforma por parte de proveedores y residentes. | 3 | Piero Periche | Done |
| HU22 | Visualizar suscripción del residente | T06 | Crear vista de suscripción en app móvil | Como residente, Quiero consultar el estado de mi suscripción Para saber si mi sensor está activo y en funcionamiento. | 3 | Mathias Hidalgo | Done |
| HU24 | Predicción de consumo y solicitud automática | T07 | Integrar modelo ML para predicción de consumo | Como proveedor, Quiero que el sistema use un modelo de machine learning, Para predecir el consumo de agua de los residentes y generar solicitudes automáticas de reabastecimiento. | 8 | Mauricio Oliveira | Done |
| HT04 | Crear suscripción a través de API REST | T08 | Implementar endpoint POST /subscriptions | Como desarrollador, Quiero crear una suscripción a través de la API Para que cada sensor quede vinculado a un residente y a un proveedor, y así se habilite el monitoreo. | 4 | Joaquín Cortez | Done |
| HT05 | Obtener suscripciones por residente | T09 | Implementar endpoint GET /subscriptions/resident/{id} | Como desarrollador, Quiero exponer un endpoint que permita obtener las suscripciones asociadas a un residente, Para que puedan ser consultadas fácilmente cuando se necesite. | 3 | Joaquín Cortez | Done |
| HT06 | Obtener todas las suscripciones del sistema | T10 | Implementar endpoint GET /subscriptions | Como desarrollador, Quiero exponer un endpoint que permita listar todas las suscripciones registradas, Para que el administrador pueda supervisar su uso y gestión. | 3 | Piero Periche | Done |
| HU23 | Chatbot de asistencia inteligente | T11 | Implementar chatbot conversacional en app móvil | Como residente, Quiero interactuar con un chatbot en la aplicación móvil para consultar el nivel de agua, estado de mi suscripción o solicitar reabastecimiento, Para obtener respuestas rápidas sin necesidad de conocimientos técnicos. | 10 | Mathias Hidalgo | To-do |


##### 7.2.2.3. Development Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **AquaConecta-ASE/Backend** | deployment | 85283ed | Remove outdated unit and integration tests for Resident and Provider services; add Azure deployment configuration and GitHub Actions workflow for automated deployment to Azure App Service. | | 02/12/2025 |
| **AquaConecta-ASE/Backend** | deployment | c7eadee | fix: update ML service URL to production endpoint | | 27/11/2025 |
| **AquaConecta-ASE/Backend** | deployment | 099b537 | Merge pull request #5 from AquaConecta-ASE/feature/iam | | 27/11/2025 |
| **AquaConecta-ASE/Backend** | deployment | 18b05f1 | feat(cors): remove CORS configuration as handled by BFF Gateway | | 27/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 51fe577 | home(init): detectar/sincronizar providerId y recargar datos del dashboard | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 9df1a44 | home(ui): estilos para banner de advertencia de perfil incompleto | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | d70e207 | add watertanksize as numbre | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | a31133a | providers(profile): sincronizar providerId/userId y robustecer creación/actualización de perfil | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 398dd49 | residents(summary): agregar columna waterTankSize en la tabla de suscripciones | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 8fe6419 | residents(summary): loguear suscripciones y mostrar waterTankSize en consola | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 44fa370 | providers(api): usar /providers/me/profile y añadir logs detallados | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 8b01eee | iam(login): ajustar botones de Auth0 (inicio/crear cuenta) para consistencia UI | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | b9534df | iam(callback): robustecer flujo Auth0 (obtener token, consultar/crear perfil y mapear providerId/userId) | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | e58651c | iam(auth): cargar usuario desde localStorage y exponer userProfileReady para notificar perfil completo | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 570d493 | analytics(predictive): soportar múltiples suscripciones y predicciones por residente | | 29/11/2025 |
| **AquaConecta-ASE/Frontend** | feature/iam | 4e18387 | analytics(predictive): mejorar estilos y estados de UI para predicciones | | 29/11/2025 |
| **AquaConecta-ASE/ML-Service** | main | 9d11320 | Update package versions in requirements.txt | | 27/11/2025 |
| **AquaConecta-ASE/ML-Service** | main | 15b75b9 | Add gunicorn and ensure numpy is listed | | 27/11/2025 |
| **AquaConecta-ASE/ML-Service** | main | 3ccd604 | first commit | | 03/11/2025 |
| **AquaConecta-ASE/web-bff** | main | 6b17667 | fix(env): update serverBasePath to include API endpoint for AquaConecta | | 29/11/2025 |
| **AquaConecta-ASE/web-bff** | main | 4aeab40 | fix(docs): correct typo in deprecated POST endpoint for predictive analytics | | 29/11/2025 |
| **AquaConecta-ASE/web-bff** | main | a831b48 | fix(config): update API base paths for consistency across environments | | 29/11/2025 |
| **AquaConecta-ASE/web-bff** | main | 915f062 | api(reports): usar /providers/me/profile y añadir logs de diagnóstico | | 29/11/2025 |
| **AquaConecta-ASE/web-bff** | main | 7277c92 | api(water): usar /providers/me/profile y añadir logs de diagnóstico | | 29/11/2025 |
| **AquaConecta-ASE/web-bff** | main | 529d5f0 | ui(resident): actualizar estilos y color del botón Crear Residente | | 29/11/2025 |
| **AquaConecta-ASE/web-bff** | main | dd6889c | i18n: agregar y refinar claves de traducción para residentes y water tank | | 29/11/2025 |
| **AquaConecta-ASE/mobile-bff** | deployment | e32085b | Refactor application configuration for dynamic backend URL and port settings | | 02/12/2025 |
| **AquaConecta-ASE/mobile-bff** | deployment | b400e55 | Initialize BFF Mobile Gateway with Spring Boot, OAuth2 security, and API routing for mobile clients | | 02/12/2025 |
| **AquaConecta-ASE/mobile-bff** | deployment | 39e6bf5 | fix: remove comment from server port configuration in application.yml | | 29/11/2025 |
| **AquaConecta-ASE/mobile-bff** | deployment | c7ec1cf | fix: revert java.version to 21 in pom.xml | | 29/11/2025 |
| **AquaConecta-ASE/mobile-bff** | deployment | b367904 | first commit | | 29/11/2025 |

##### 7.2.2.4. Testing Suite Evidence for Sprint Review.
Durante el desarrollo del sprint 2 se implementaron pruebas unitarias e integrales para validar el comportamiento de las clases de negocio. Esto ayuda a asegurarnos que cada componente funcione correctamente, cumpliendo con su responsabilidad.

|Repository|Branch|Commit Id|Commit Message|Commit Message Body|Commited on (Date)|
| :- | :- | :- | :- | :- | :- |
|IronCoders-IOT / Backend|deployment|58e356b|feature: Add unit tests for consumption calculation service||Dec 05, 2025, 11:47 A.M.|
|IronCoders-IOT / Backend|deployment|9b5f4cb|test: Add unit tests for prediction command service||Dec 05, 2025, 11:47 A.M.|
|IronCoders-IOT / Backend|deployment|92e09a9|test: Add unit tests for subscription command service||Dec 05, 2025, 11:48 A.M.|
|IronCoders-IOT / Backend|deployment|ea7e474|test: Add unit tests for event command service||Dec 05, 2025, 11:48 A.M.|
|IronCoders-IOT / Backend|deployment|09223ed|test: Add unit tests for water supply request command service||Dec 05, 2025, 11:48 A.M.|

A continuación, se presentarán imágenes de las pruebas unitarias y la prueba integral.

![alt text](image-15.png)

![alt text](image-16.png)

![alt text](image-17.png)

![alt text](image-18.png)

![alt text](image-19.png)

##### 7.2.2.5. Execution Evidence for Sprint Review.
En nuestro video de exposición, hemos incluido una demostración de la aplicación AquaConecta, donde se muestra cómo los proveedores pueden gestionar sus servicios. A continuación, se presentan capturas de pantalla que ilustran las funcionalidades clave de la aplicación:

- Se muestra captura de código del proyecto.
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192522.png)

- Se muestran las diversas vistas dentro de la aplicación web:
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20191517.png)
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192002.png)
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192016.png)
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192036.png)
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192050.png)
  ![alt text](image-6.png)
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192101.png)
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192119.png)
  ![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-14%20192130.png)
  ![alt text](image-4.png)
  ![alt text](image-5.png)

- Capturas de pantalla del la aplicación mobile:

  ![alt text](image-7.png)
  ![alt text](image-8.png)
  ![alt text](image-9.png)
  ![alt text](image-10.png)
  ![alt text](image-11.png)
  ![alt text](image-12.png)

Se adjunta enlace para ingresar al video en el que se muestra lo logrado en este sprint 1.

- **Link de YouTube:**
  [https://youtu.be/8PBCHlpW2zA](https://youtu.be/8PBCHlpW2zA)


##### 7.2.2.6. Services Documentation Evidence for Sprint Review.

Se hizo uso de Swagger para documentar los servicios de la aplicación AquaConecta. Esta herramienta permite a los desarrolladores y usuarios explorar y entender las API de manera interactiva. A continuación, se presentan capturas de pantalla que muestran la documentación generada por Swagger:

- **Link de swagger:**
  [https://aquaconecta-backend-app.azurewebsites.net/swagger-ui](https://aquaconecta-backend-app.azurewebsites.net/swagger-ui/index.html#/)

![alt text](assets/Services-Documentation/Captura%20de%20pantalla%202025-11-14%20195614.png)

![alt text](assets/Services-Documentation/Captura%20de%20pantalla%202025-11-14%20195710.png)

![alt text](assets/Services-Documentation/Captura%20de%20pantalla%202025-11-14%20195746.png)

![alt text](image-3.png)

##### 7.2.2.7. Software Deployment Evidence for Sprint Review.


La aplicacion fue desplegada en Azure App Service, lo que permite a los usuarios acceder a la aplicación de manera sencilla y rápida. A continuación, se presentan capturas de pantalla que muestran el proceso de despliegue y el estado actual de la aplicación en Azure, asi como la implementacion el Auth0:

- **Aplicacion Web:**
  [https://aquaconecta-ase.netlify.app](https://aquaconecta-ase.netlify.app)

![alt text](assets/1.jpeg)

![alt text](assets/2.jpeg)

![alt text](assets/3.jpeg)

![alt text](assets/4.jpeg)

![alt text](assets/5.jpeg)

![alt text](assets/6.jpeg)

![alt text](assets/7.jpeg)

##### 7.2.2.8. Team Collaboration Insights during Sprint.

Finalmente, se presentan los insights de colaboración del equipo durante el Sprint 2, los cuales reflejan la coordinación efectiva y el trabajo continua entre los miembros en el desarrollo de los distintos productos de la solución AquaConecta.

Backend:

![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-16%20021633.png)

Frontend:

![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-16%20022444.png)

Mobile:

![alt text](assets/sprint1/Captura%20de%20pantalla%202025-11-16%20022710.png)

Mobile API Gateway:



Web API Gateway:

![alt text](image-14.png)

Machine Learning:

![alt text](image-13.png)

### 7.3. Validation Interviews.

#### 7.3.1. Diseño de Entrevistas.

#### Preguntas Generales

El propósito de estas preguntas es romper el hielo y confirmar el perfil del entrevistado.

* ¿Cuál es su nombre?
* ¿Qué edad tiene?
* ¿A qué se dedica?
* ¿En qué distrito o asentamiento humano vive/trabaja?
* ¿Actualmente cómo se informa sobre el nivel o la calidad del agua en su tanque/cisterna?

#### Preguntas Dirigidas a Proveedores

El objetivo es validar el dashboard de gestión, la claridad de los datos agregados y la utilidad de las funciones de monitoreo.

* *(Se muestra el Dashboard)* Al ver esta pantalla, ¿qué es lo primero que le llama la atención? ¿Entiende de un vistazo el estado general del servicio?
* ¿Le parece clara la información sobre el nivel y la calidad del agua de cada residente?
* Si viera una alerta de "Mala Calidad" en uno de sus residentes, ¿qué acción esperaría poder tomar desde esta plataforma?
* La herramienta que anticipa qué residentes necesitarán agua pronto. ¿Le parece útil esta información para planificar sus rutas de reparto?
* ¿Considera que faltan indicadores o datos clave que usted necesita en su día a día y que no estamos mostrando?
* ¿Qué tan fácil o difícil le pareció navegar y encontrar la información que buscaba?
* ¿Confiaría en los datos de esta plataforma para tomar decisiones operativas importantes?
* ¿Qué funcionalidad le pareció la más valiosa?
* ¿Qué es lo que menos le gustó o le pareció más confuso?

#### Preguntas Dirigidas a Habitantes

El objetivo es validar la facilidad de uso de la app móvil, la comprensión de los datos del sensor (nivel y calidad) y la utilidad de las alertas.

* ¿Qué entiende al ver este gráfico/indicador? (Ej. mostrar el nivel de 53% o la calidad "Aceptable").
* Sabiendo que tiene esta información en su celular, ¿se siente más tranquilo o mejor informado sobre el agua que usa?
* ¿Considera que esta información le ayudaría a planificar mejor su consumo o sus tareas diarias?
* Si le llegara una notificación como esta ("Nivel bajo" o "Agua no potable"), ¿qué haría? ¿Le parece útil recibir este tipo de alertas?
* Si quisiera solicitar más agua a su proveedor, ¿cómo cree que lo haría usando la aplicación?
* ¿Le pareció fácil de entender y usar la aplicación? (Escala de 1 a 5).
* ¿Hay algo en la pantalla que no entienda o que le cause confusión?
* ¿Con qué frecuencia cree que revisaría esta aplicación en una semana normal?
* ¿Qué es lo que más le gustó de la aplicación?
* ¿Hay algo que le gustaría cambiar, mejorar o agregar?

#### 7.3.2. Registro de Entrevistas.

**Entrevistas usuario segmento (Habitantes):** 

Nombre: Belen Ramos

- Edad: 25
- Ocupación: Estudiante
- Distrito: Chincha Alta

<br>

<div style="text-align: center;">
    
<img src="./assets/SCR-20251116-oler.png"> 

[Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210192_upc_edu_pe/IQBhWOp2KubZSY04RZ7yg73_AbZbVBh-AyvCoj-lWd9aiV0?e=3hQ2ae&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

</div>

Belén comenta que, antes de usar AquaConecta, solo podía guiarse por la experiencia diaria para saber si había suficiente agua, ya que no contaba con herramientas para monitorear el nivel o la calidad. Al probar la aplicación, señala que la interfaz le pareció “clara”, “ordenada” y que entender los gráficos no le tomó más de unos segundos.

La característica que más le llamó la atención fue la posibilidad de ver el nivel del tanque en cualquier momento, lo que, según dice, le ayudaría a organizar actividades como lavado, limpieza o almacenamiento. También considera muy valiosas las alertas de cambios en nivel o calidad, pues recibirlas en tiempo real le permitiría evitar usos riesgosos o ajustar su consumo antes de quedarse sin agua.

Aunque afirma sentirse cómoda con la aplicación, menciona que algunos términos técnicos podrían acompañarse de una breve explicación para mayor claridad. Por último, propone incorporar un modo de lectura más simple, pensado para usuarios mayores, así como una opción que permita revisar el historial semanal o mensual del consumo para hacer un uso más eficiente del recurso.
<br>

Nombre: Carla Cordova

- Edad: 22
- Ocupación: Estudiante
- Distrito: Chincha Alta

<br>

<div style="text-align: center;">
    
<img src="./assets/SCR-20251116-onot.png"> 

[Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210192_upc_edu_pe/IQBc7hpdjjQUSL2xG6PKGraqARBtVrzMGvZ1pBcrxxn93G0?e=OC47CV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
</div>

Carla indica que, antes de usar AquaConecta, no tenía forma clara de conocer el nivel ni la calidad del agua en su vivienda y que dependía únicamente de la experiencia diaria y de esperar a que el agua se acabara. Afirma que la aplicación le resulta “fácil de entender”, “clara” y que los gráficos son “muy intuitivos”.

La funcionalidad que más valora es la visualización en tiempo real del nivel del agua, ya que le permite planificar mejor su consumo y evitar inconvenientes. También destaca que las alertas automáticas —como “Nivel bajo” o “Agua no potable”— son especialmente útiles porque le permitirían anticiparse y tomar decisiones inmediatas, evitando riesgos de salud o interrupciones en sus actividades.

Aunque considera confiables los datos mostrados, menciona que sería ideal contar con explicaciones adicionales en algunos indicadores (como niveles de calidad) para personas que no están familiarizadas con términos técnicos. Finalmente, sugiere añadir un modo para personas mayores con textos más grandes y un historial de consumo para entender mejor sus patrones de uso.
<br>


**Entrevistas usuario segmento (Proveedor de agua):**

Nombre: William Ramos Vicente

- Edad: 32
- Ocupación: Ingeniero sanitario
- Distrito: Chincha Alta

<br>
<div style="text-align: center;">
    
<img src="./assets/img/entrevista_vi_william.png"> 

[Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201719831_upc_edu_pe/IQDkoqPLUJW4SJ-MI1_cLyNvAe6Hh9wSJoM94pQ7PNOnPAg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=kKq8LH)

</div>

William Ramos confirma que su proceso de monitoreo actual es manual y que los resultados de laboratorio para la calidad del agua tardan de 3 a 7 días. Considera que la plataforma web de AquaConecta es "muy intuitiva" y "fácil de aprender".

La funcionalidad que más valora es la automatización, ya que le ahorraría mucho tiempo y costos operativos. Las "alertas automáticas de calidad" le parecen la función más valiosa, pues reducen el tiempo de detección de días a minutos.

Antes de confiar al 100% en los datos, realizaría un "benchmark" (comparación) con los resultados de un laboratorio tradicional. Finalmente, sugiere que se añada la capacidad de personalizar más parámetros de medición y reitera la importancia de un modo offline para zonas sin conectividad.
<br>

Nombre: André Alonso Arroyo Ormeño

- Edad: 28
- Ocupación: Ingeniero sanitario
- Distrito: Chincha Alta

<br>
<div style="text-align: center;">
    
<img src="./assets/img/entrevista_vi_andre.png"> 

[Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201719831_upc_edu_pe/IQDjZnPkoq2kR7iYEfS8LwiJAZ4hLiPDi3_M58l2fbNllg0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=BorDVq)

</div>

André también valida que su proceso actual es manual y que los resultados de laboratorio "demoraban como unos 3 a 7 días". Considera la plataforma "demasiado útil" y un "cambio radical" respecto a sus planillas de Excel.

Destaca la analítica predictiva como una herramienta clave que les permitiría optimizar las rutas de las cisternas y pasar de ser "reactivos a preventivos", ahorrando combustible, tiempo y quejas. Al igual que William, la funcionalidad que considera más valiosa son las "alertas automáticas de calidad".

Su principal sugerencia es la necesidad de georreferenciación (ver las alertas en un "mapa tipo GIS") y pide diferenciar claramente en la interfaz si un "Issue Report" es una queja de un residente o una alerta automática del sensor, para evitar confusiones operativas.
<br>



#### 7.3.3. Evaluaciones según heurísticas.

#### UX Heuristics & Principles Evaluation
##### Usability – Inclusive Design – Information Architecture

**CARRERA:** Ingeniería de Software  
**CURSO:** Arquitecturas De Software Emergentes  
**SECCIÓN:** 7322 
**PROFESORES:** Todos  
**AUDITOR:** IronCoders  
**CLIENTE(S):** Todos  
**SITE o APP A EVALUAR:** AquaConecta  

#### TAREAS A EVALUAR:
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Boton call to action
2. Navegación principal y estructura de botones
3. Jerarquía visual y organización de información
4. Búsqueda y filtrado de datos


No están incluidas en esta versión de la evaluación las siguientes tareas:

- Funcionalidades de sensores IoT en tiempo real
- Módulos de facturación y pagos
- Integración con sistemas externos

#### ESCALA DE SEVERIDAD:
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

| Nivel | Descripción |
|-------|-------------|
| 1     | Problema superficial: puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

#### TABLA RESUMEN:

| # | Problema | Escala de severidad | Heurística/Principio violada(o) |
|---|----------|---------------------|---------------------------------|
| 1 | Uso del botón call to action | 2 | Visibilidad del estado del sistema y Libertad y control del usuario |
| 2 | Navegación confusa y redundante | 3 | Usability: Consistencia y estándares |
| 3 | Funcionalidad de búsqueda limitada | 2 | Usability: Flexibilidad y eficiencia de uso |
| 4 | Tabla de historial excesivamente ancha | 3 | Usability: Diseño estético y minimalista |


#### DESCRIPCIÓN DE PROBLEMAS:

#### PROBLEMA #1: Uso del botón call to action

**Severidad:** 2
**Heurística violada:** Visibilidad del estado del sistema y Libertad y control del usuario

**Descripción:** Actualmente solo existe un boton con el cual se puede acceder a la informacion completa de un residente. Este boton puede llegar a ser poco intuitivo para los usuarios debido al tamaño y colores seleccionados, lo cual puede limitar el acceso a la informacion revelantes para los proveedores sobre sus residentes.


![alt text](<assets/heuristics-evaluation/Captura de pantalla 2025-11-16 024128.png>)


**Solución propuesta:** Reemplazar el botón por una CTA clara (ícono + texto "Ver residente") que destaque visualmente en la fila, con etiqueta/tooltip "Ver información completa del residente", versión solo-ícono en móvil y un pequeño indicador (badge) para alertas; así los proveedores localizarán y accederán fácilmente a la información del residente.

#### PROBLEMA #2: Navegación confusa y redundante
**Severidad:** 3  
**Heurística violada:** Usability: Consistencia y estándares

**Descripción:** En la pantalla de inicio el proveedor encuentra varios botones que apuntan a la misma funcionalidad, lo que genera redundancia y confusión.

![alt text](image-2.png)


**Solución propuesta:** Reorganizar la navegación agrupando elementos relacionados, establecer una jerarquía clara y reducir la redundancia.

#### PROBLEMA #3: Funcionalidad de búsqueda limitada
**Severidad:** 2  
**Heurística violada:** Usability: Flexibilidad y eficiencia de uso  
**Descripción:** El campo de búsqueda solo permite buscar por ID, limitando la capacidad de los usuarios para encontrar solicitudes usando otros criterios relevantes como nombre del residente, fecha de emisión, o estado.  

![alt text](heuristic9.png)

**Solución propuesta:** Expandir la funcionalidad de búsqueda para incluir múltiples campos (nombre, fecha, estado) o implementar filtros avanzados que permitan búsquedas más granulares.

#### PROBLEMA #4: Tabla de historial excesivamente ancha
**Severidad:** 3  
**Heurística violada:** Usability: Diseño estético y minimalista
**Descripción:** La tabla "Sensor Activity History" se extiende innecesariamente por todo el ancho de la pantalla, creando líneas de lectura muy largas que dificultan el escaneo visual y hacen que los datos se vean dispersos y poco organizados.

![alt text](image-1.png)

**Solución propuesta:** Reducir el ancho de la tabla para mejorar la legibilidad y el enfoque visual. Se recomienda establecer un ancho máximo y centrar la tabla en la página, además de ajustar el tamaño de las columnas para que solo ocupen el espacio necesario.


### 7.4. Video About-the-Product.

En esta sección colocamos el video de About the Product. En este video se puede visualizar tanto la app web y móvil para que los usuarios puedan observar cómo funciona nustra solución. 

**Link del video:** [About the Product](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212648_upc_edu_pe/IQBhxKSLVx_JSY9JiKEDbTLAAY6BJEpEr1EJ1y1hUkO1-ms?e=5cihZx&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)



## Conclusiones

#### TF:

Con la finalización del proyecto AquaConecta, se logró la implementación completa de una solución tecnológica integral que aborda la problemática del acceso al agua potable mediante tecnologías emergentes. La integración exitosa de Machine Learning para la predicción de consumo, dispositivos IoT para el monitoreo en tiempo real y la aplicación del patrón arquitectónico Backend for Frontend (BFF) demuestran la viabilidad de arquitecturas modernas y especializadas para resolver desafíos sociales complejos.

Durante el desarrollo del trabajo, el equipo adquirió conocimientos profundos sobre el diseño e implementación de arquitecturas de software emergentes, comprendiendo la importancia de seleccionar patrones arquitectónicos adecuados según el dominio del problema y los requisitos no funcionales del sistema. La aplicación de Domain-Driven Design (DDD), la implementación de bounded contexts bien definidos y la utilización de tecnologías como Spring Boot, Angular, Flutter y servicios IoT permitieron construir una solución escalable, mantenible y alineada con las mejores prácticas de la ingeniería de software moderna.

El proyecto consolidó la capacidad del equipo para diseñar arquitecturas óptimas considerando aspectos críticos como la escalabilidad, el rendimiento, la seguridad y la experiencia de usuario. La implementación del bounded context de Predictive Analytics, junto con los módulos de Analytics, Water Management, User & Profile, Requests y Subscriptions, evidencian un sistema cohesivo que responde eficientemente a las necesidades de los usuarios finales y proveedores de agua. Esta experiencia formativa ha fortalecido nuestras competencias técnicas y nuestra visión estratégica para enfrentar proyectos de software de alta complejidad en contextos reales.

#### Tecnología Emergente Aplicada a la Distribución de Agua:

La aplicación de Machine Learning (ML) predictivo, complementada por el Internet de las Cosas (IoT), representa una disrupción fundamental en la gestión de la distribución de agua a comunidades sin infraestructura de red fija. Nuestro proyecto concluye que esta integración tecnológica transforma la distribución de un esquema reactivo, ineficiente y generador de estrés hídrico en un modelo proactivo, optimizado y socialmente equitativo.

La esencia del cambio radica en la capacidad predictiva del ML. Al analizar continuamente los patrones de consumo de cada hogar mediante sensores IoT, el sistema no solo registra el uso, sino que aprende y anticipa con 3 a 7 días de antelación cuándo cada tanque se acercará a un umbral crítico. Esta anticipación elimina la ansiedad hídrica de las familias y permite a los proveedores migrar de la respuesta a llamadas urgentes a una planificación de rutas optimizada. Esta mejora no es trivial: reduce significativamente los costos operativos por concepto de combustible y tiempos muertos, elevando la eficiencia operativa y la rentabilidad del servicio.

La optimización va más allá de la eficiencia en el transporte. El modelo agrega valor al permitir la identificación de patrones de demanda zonales imposibles de detectar manualmente. Esta visibilidad en tiempo real no solo facilita la gestión de inventarios y recursos humanos, sino que también garantiza la continuidad del suministro, asegurando el acceso al agua, un derecho humano fundamental, en comunidades históricamente desatendidas. Adicionalmente, el sistema fomenta la transparencia y el uso responsable, al generar alertas ante consumos anómalos que podrían indicar fugas o desperdicio, promoviendo una cultura de conservación.

En términos de sostenibilidad, la contribución es doble. Primero, la optimización de rutas reduce directamente la huella de carbono de los camiones cisterna, contribuyendo a la mitigación del cambio climático. Segundo, la capacidad de detección temprana de fugas y desperdicios se alinea con los Objetivos de Desarrollo Sostenible (ODS), logrando la conservación efectiva de miles de litros de agua.

En retrospectiva, la implementación del Machine Learning en la distribución de agua es un poderoso ejemplo de cómo la tecnología emergente puede ser adaptada para cerrar brechas de desigualdad y transformar servicios básicos en operaciones inteligentes, justas y sostenibles. El sistema no solo garantiza un suministro predecible, sino que también sienta las bases para una gestión hídrica futura basada en datos reales, mejorando la resiliencia comunitaria frente a los desafíos del cambio climático y el crecimiento poblacional.

# Video About-the-Team

**Link del video:** **FALTA AGREGAR**[About the Team]( )

# Bibliografía

## Referencias

- Infobae. (2024, septiembre 8). *Alarma por la falta de acceso continuo a agua potable en Ica: solo el 13.3% de los hogares cuenta con el servicio las 24 horas*. Infobae. [https://www.infobae.com/peru/2024/09/08/alarma-por-la-falta-de-acceso-continuo-a-agua-potable-en-ica-solo-el-133-de-los-hogares-cuenta-con-el-servicio-las-24-horas/](https://www.infobae.com/peru/2024/09/08/alarma-por-la-falta-de-acceso-continuo-a-agua-potable-en-ica-solo-el-133-de-los-hogares-cuenta-con-el-servicio-las-24-horas/)

- Diario Correo (2024). Asentamiento humano 28 de Julio queda sin agua potable durante varios días consecutivos. Diario Correo. <br> https://diariocorreo.pe/edicion/ica/chincha-miles-de-familias-padecen-por-falta-de-agua-hasta-por-una-semana-noticia/?ref=dcr#google_vignette


- Diario Correo (2025). Pobladores de Chincha protestan por deficiente servicio de agua de SEMAPACH. Diario Correo. <br> https://diariocorreo.pe/edicion/ica/chincha-planton-contra-semapach-por-mejor-servicio-de-agua-potable-noticia/?ref=dcr

- Superintendencia Nacional de Servicios de Saneamiento (Sunass). (2025, febrero 28). *Sunass monitorea abastecimiento y continuidad del agua potable en más de 200 colegios de Ica*. Gobierno del Perú. [https://www.gob.pe/institucion/sunass/noticias/1118140-sunass-monitorea-abastecimiento-y-continuidad-del-agua-potable-en-mas-de-200-colegios-de-ica](https://www.gob.pe/institucion/sunass/noticias/1118140-sunass-monitorea-abastecimiento-y-continuidad-del-agua-potable-en-mas-de-200-colegios-de-ica)

- Superintendencia Nacional de Servicios de Saneamiento (Sunass). (2025, enero 10). *Sunass fiscaliza a Semapach ante interrupción del servicio de agua potable en Chincha*. Gobierno del Perú. [https://www.gob.pe/institucion/sunass/noticias/886137-ica-sunass-fiscaliza-a-semapach-ante-interrupcion-del-servicio-de-agua-potable-en-chincha](https://www.gob.pe/institucion/sunass/noticias/886137-ica-sunass-fiscaliza-a-semapach-ante-interrupcion-del-servicio-de-agua-potable-en-chincha)

- Infobae. (2024, mayo 9). *El 73.7% de peruanos no tiene acceso a agua de manera segura, según INEI*. Infobae. [https://www.infobae.com/peru/2024/05/09/el-737-de-peruanos-no-tiene-acceso-a-agua-de-manera-segura-segun-inei/](https://www.infobae.com/peru/2024/05/09/el-737-de-peruanos-no-tiene-acceso-a-agua-de-manera-segura-segun-inei/)


