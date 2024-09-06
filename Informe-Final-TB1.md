![UPC_logo_transparente (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2ff342be-dc34-415c-925e-1e7133e49abf)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2024-02

# ARQUITECTURA DE SOFTWARE EMERGENTES

Sección SW82

Profesor: Rojas Malasquez, Royer Edelwer

***INFORME DE TRABAJO FINAL - TB1***

**Startup: CuriDev**

**Producto: SafeFlow - IOT**

**Integrantes:**
- Alarcon Rondon. Sandro Fourfive
- Espejo Macuri, Paolo Andre
- Gonzales Carrión, Jorge Enrique
- Laguerre Chalco, Fabrizzio Hernan
- Pozo Campos, Rodrigo Jair

Agosto del 2024

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
| 1.00 | 15/08/2024 | Alarcon Rondon. Sandro Fourfive | To Be Scenario Map, Diseño de historia de usuarios, constrains v.1|
| 1.10 | 20/08/2024 | Espejo Macuri, Paolo Andre | Diseño de historia de usuario, EventStorming v.1 |
| 1.20 | 21/08/2024 | Gonzales Carrión, Jorge Enrique| Strategic-Level Attribute-Driven Design, Strategic-Level Domain-Driven Design, Software Architecture, diseño y registro de entrevistas |
| 1.30 | 21/08/2024 | Laguerre Chalco, Fabrizzio Hernan | EventStorming, Bounded Context Candidates, diseño y registro de entrevistas |
| 1.40 | 01/09/2024 | Pozo Campos, Rodrigo Jair | Diseño de user stories, analisis de entrevistas, proceso Lean UX, Constrains v.1 |


---
# Project Report Collaboration Insights

TB1: Se han desarrollado las actividades correspondientes para la entrega TB1 en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final

Para la elaboración del informe se realizaron actividades tales como:

-Primera versión de Software Architecture, Strategic-Level Attribute-Driven Design, Strategic-Level Domain-Driven Design

-Lean UX Process

-Diseño y analisis de entrevistas

-Analisis de competidores

-User Stories y Product Backlog



---
# Contenido 
## Tabla de contenidos


## [Capítulo I: Introducción](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#cap%C3%ADtulo-i-introducci%C3%B3n)
- [1.1. Startup Profile](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#11-startup-profile)
  - [1.1.1. Descripción de la Startup](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#111-descripci%C3%B3n-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#121-antecedentes-y-problem%C3%A1tica)
  - [1.2.2. Lean UX Process](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#13-segmentos-objetivo)

## [Capítulo II: Requirements Elicitation & Analysis](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#cap%C3%ADtulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#21-competidores)
  - [2.1.1. Análisis competitivo](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#211-an%C3%A1lisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#212-estrategias-y-t%C3%A1cticas-frente-a-competidores)
- [2.2. Entrevistas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#221-dise%C3%B1o-de-entrevistas)
  - [2.2.2. Registro de entrevistas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#223-an%C3%A1lisis-de-entrevistas)
- [2.3. Needfinding](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#23-needfinding)
  - [2.3.1. User Personas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#231-user-personas)
  - [2.3.2. User Task Matrix](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#232-user-task-matrix)
  - [2.3.3. Empathy Mapping](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#233-empathy-mapping)
  - [2.3.4. As-is Scenario Mapping](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#234-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#24-ubiquitous-language)

## [Capítulo III: Requirements Specification](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#cap%C3%ADtulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#31-to-be-scenario-mapping)
- [3.2. User Stories](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#32-user-stories)
- [3.3. Impact Mapping](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#33-impact-mapping)
- [3.4. Product Backlog](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#34-product-backlog)

## [Capítulo IV: Strategic-Level Software Design](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#cap%C3%ADtulo-iv-strategic-level-software-design)
- [4.1. Strategic-Level Attribute-Driven Design](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#41-strategic-level-attribute-driven-design)
  - [4.1.1. Design Purpose](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#411-design-purpose)
  - [4.1.2. Attribute-Driven Design Inputs](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#412-attribute-driven-design-inputs)
    - [4.1.2.1. Primary Functionality (Primary User Stories)](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#4121-primary-functionality-primary-user-stories)
    - [4.1.2.2. Quality Attribute Scenarios](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#4122-quality-attribute-scenarios)
    - [4.1.2.3. Constraints](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#4123-constraints)
  - [4.1.3. Architectural Drivers Backlog](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#413-architectural-drivers-backlog)
  - [4.1.4. Architectural Design Decisions](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#414-architectural-design-decisions)
  - [4.1.5. Quality Attribute Scenario Refinements](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#415-quality-attribute-scenario-refinements)
- [4.2. Strategic-Level Domain-Driven Design](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#42-strategic-level-domain-driven-design)
  - [4.2.1. EventStorming](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#421-eventstorming)
  - [4.2.2. Candidate Context Discovery](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#422-candidate-context-discovery)
  - [4.2.3. Domain Message Flows Modeling](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#423-domain-message-flows-modeling)
  - [4.2.4. Bounded Context Canvases](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#424-bounded-context-canvases)
  - [4.2.5. Context Mapping](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#425-context-mapping)
- [4.3. Software Architecture](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#43-software-architecture)
  - [4.3.1. Software Architecture System Landscape Diagram](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#431-software-architecture-system-landscape-diagram)
  - [4.3.2. Software Architecture Context Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#432-software-architecture-context-level-diagrams)
  - [4.3.3. Software Architecture Container Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#433-software-architecture-container-level-diagrams)
  - [4.3.4. Software Architecture Deployment Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#434-software-architecture-deployment-diagrams)




## [Conclusiones](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#conclusi%C3%B3n)

## [Referencias](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#bibliograf%C3%ADa)

## [Anexos](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#bibliograf%C3%ADa)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 3

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describe las acciones realizadas y enunciados de 
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro 
del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
| - | - | - |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | Sandro Alarcón - TB1: Expuso el To Be Scenario Map al equipo, presentando de manera clara las historias de usuario y restricciones iniciales. <br> Paolo Espejo - TB1: Explicó a través de una sesión de Event Storming los flujos de trabajo, detallando las historias de usuario identificadas. <br> Jorge Gonzales - TB1: Comunicó mediante una reunión al equipo de desarrollo propuestas para la arquitectura del software, enfocándose en el diseño estratégico. <br> Fabrizzio Laguerre - TB1: Expuso los resultados del Event Storming, detallando la identificación de los Bounded Contexts y su impacto en la solución. <br> Rodrigo Pozo - TB1: Explicó el proceso Lean UX y los hallazgos del análisis de entrevistas, detallando las implicancias en el diseño de historias de usuario y restricciones. | Los miembros del equipo demostraron capacidad para comunicar oralmente sus ideas y resultados de manera efectiva, adaptando su lenguaje y nivel de detalle según la audiencia, logrando una comprensión común del proyecto y sus desafíos.  |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | Sandro Alarcón - TB1: Documentó las historias de usuario y restricciones v.1, asegurando claridad y detalle en los escenarios planteados. <br> Paolo Espejo - TB1: Redactó las descripciones de las historias de usuario y detalló los resultados del Event Storming v.1 en formato escrito. <br> Jorge Gonzales - TB1: Propuso textualmente una lista de alternativas para la arquitectura del software, integrando conceptos de diseño estratégico y resultados de entrevistas. <br> Fabrizzio Laguerre - TB1: Registró en un informe las entrevistas realizadas y detalló el proceso de Event Storming, asegurando que los hallazgos sean entendibles por todos los involucrados. <br> Rodrigo Pozo - TB1: Redactó los resultados del análisis de entrevistas y formalizó el proceso Lean UX, destacando los insights y restricciones identificadas. | El equipo logró comunicar de manera escrita sus ideas y resultados de forma objetiva y comprensible, permitiendo que personas de diferentes especialidades comprendieran los avances y propuestas del proyecto. |

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

El startup que se introduce en el presente informe recibe como nombre “CuriDev”. Actualmente conformado por un conjunto de estudiantes de la Universidad Peruana de Ciencias Aplicadas, con la ambición de querer ayudar a la sociedad con nuestra grán pasión a la tecnología e informática, creamos esta startup tomando como objetivo asegurar la integridad y mejorar los procesos de trabajo de las empresas de transporte de productos peligrosos.

Como misión se plantea “Incrementar la calidad del servicio de transporte de combustibles con eficiencia, seguridad y transparencia entre conductores y empresas”. Asimismo, la visión de la startup plantea desarrollar la solución IoT más reconocida en el Perú para asegurar la integridad de los transportes de productos peligrosos.

### 1.1.2. Perfiles de integrantes del equipo

Mi nombre es Jorge Enrique Gonzales Carrión tengo 19 años de edad y curso el octavo ciclo de la carrera Ingeniería de Software. Me considero una persona con sentido de responsabilidad y la suficiente capacidad de trabajar en equipo aportando ideas innovadoras. Además, en cualidades me considero asertivo y colaborativo, puntos que pueden mejorar el proceso de elaboración de los distintos trabajos del curso. Finalmente, poseo conocimientos de programación que brindaron los ciclos anteriores al presente.

![jroge](https://github.com/upc-pre-202302-GreatMinds-SW51/Informe-Final_OpenSource/assets/104078975/f2ae0bea-109a-48cb-abd8-47db542006c3)


---

## 1.2. Solution Profile

**Product name**


Un nombre adecuado para esta solución podría ser "SafeFlow". Este nombre transmite la idea de un flujo seguro de gases durante el transporte, lo cual es el objetivo principal del sistema de detección y alerta.


**Product Description**

La solución IoT es innovadora dado que se brinda un servicio de transporte de productos peligrosos implementando la supervisión de condiciones de seguridad tanto para el mismo conductor y para el monitoreo de la empresa. Por medio de sensores incluidos en el vehículo, se supervisará el material de carga y se notificará en caso exista alguna fuga. Estos sensores varían desde fuga de gas, temperatura, presión, movimiento, etc. 


**Monetización**

El sistema tendrá una suscripción donde cubra el precio de los dispostivos IOT y el servicio de la plataforma.

### 1.2.1. Antecedentes y problemática

En los últimos años, la industria del transporte de productos peligrosos, como gases inflamables, productos químicos y materiales industriales, la seguridad es una prioridad absoluta. A lo largo de los años, ha habido numerosos incidentes que han resultado en daños graves, tanto para los trabajadores involucrados como para el medio ambiente y las comunidades cercanas. Estos incidentes se han debido principalmente a fugas, explosiones y derrames de materiales peligrosos durante el transporte.

Uno de los principales problemas radica en la detección tardía de fugas y otras condiciones peligrosas durante el transporte. La falta de un monitoreo continuo y en tiempo real dificulta la identificación oportuna de irregularidades, como cambios en la presión, temperatura o movimiento inusual del vehículo. Esta situación aumenta la probabilidad de que un problema menor se convierta en una emergencia antes de ser detectado y abordado.

Otro desafío es la fragmentación de las soluciones actuales de monitoreo. Muchas empresas dependen de sistemas manuales o tecnologías desactualizadas que no proporcionan una supervisión integral. Esta carencia de un sistema centralizado y automatizado crea brechas en la seguridad, dejando a las empresas vulnerables a incidentes que podrían haberse prevenido con un mejor monitoreo.

Además, las exigencias regulatorias en el transporte de materiales peligrosos son cada vez más estrictas. El incumplimiento de estas normativas no solo implica sanciones legales, sino también la pérdida de confianza de los clientes y daños significativos a la reputación de la empresa. Sin herramientas adecuadas para garantizar el cumplimiento, las empresas corren el riesgo de enfrentar graves consecuencias financieras y operativas.

**Herramienta 5W y 2H**

**¿Qué? (What)**

Según Lopez-Atamorors et al. (2010), nos dice que los principales riesgos dentro del servicio de transportes peligros son: Choque, Explosión y Fuga. Debido a ello, el transporte de productos peligrosos, como gases inflamables y productos químicos, significa un alto riesgo que se tiene que afrontar. La falta de monitoreo continuo y en tiempo real impide la identificación oportuna de condiciones peligrosas, como cambios en la presión, temperatura o movimiento del vehículo, también suponen unod estos problemas.

**¿Cuándo? (When)**

Este problema se presenta de manera constante durante el transporte de productos peligrosos, particularmente en situaciones de emergencia o cuando las condiciones de seguridad cambian rápidamente y no se detectan a tiempo.

**¿Dónde? (Where)**

Los problemas surgen en cualquier etapa del transporte de materiales peligrosos, ya sea en carreteras, vías ferroviarias o puertos. Estos incidentes afectan principalmente a las rutas de transporte utilizadas por empresas que manejan productos químicos, gases inflamables y otros materiales industriales peligrosos.

**¿Quién? (Who)**

Los principales afectados son las empresas de transporte de productos peligrosos, los trabajadores que manipulan estos materiales y las comunidades cercanas a las rutas de transporte. También se ven afectadas las autoridades reguladoras que deben supervisar el cumplimiento de las normas de seguridad.

**¿Por qué? (Why)**

Según Chacoón y Domingo (2021): los efectos de fugas de gases pueden aumentar el efecto invernadero, contaminación de atmosfera y otros efectos nocivos, debido a ello es importante. Además, la falta de un sistema de monitoreo eficiente y continuo. Muchos sistemas actuales son manuales o desactualizados, lo que crea brechas de seguridad. Esto se agrava con el incumplimiento de regulaciones, lo cual puede resultar en sanciones legales y pérdidas de reputación.

**¿Cómo? (How)**

La problemática se manifiesta a través de incidentes como fugas, explosiones y derrames que no son detectados a tiempo debido a la falta de monitoreo adecuado. Las empresas a menudo dependen de sistemas fragmentados que no ofrecen una supervisión integral, exponiendo a los trabajadores y al medio ambiente a riesgos significativos.

**¿Cuánto? (How Much)**

Según Soto et al. (2023), en la mayoría de países de latinoamerica, se arroja que en un año promedio se atienden más de 11,00 resportes relacionados con gas L.P y gas natural. Las pérdidas asociadas incluyen daños a la infraestructura, sanciones legales, costos de limpieza y posibles daños a la salud de los trabajadores y el público. Además, el incumplimiento de las regulaciones puede llevar a multas que varían dependiendo de la gravedad del incidente y el impacto ambiental.

**Conclusiones de las 5W + 2H**

Luego de analizar las 5W y 2H, se evidencia que la industria del transporte de productos peligrosos enfrenta desafíos críticos en la detección temprana de fugas y otros incidentes relacionados con la seguridad. La fragmentación y la falta de actualización de las tecnologías de monitoreo son factores clave que impiden una respuesta rápida y efectiva ante emergencias. Para mitigar estos riesgos, se requiere una solución integral que incluya la implementación de tecnologías de monitoreo continuo y en tiempo real, centralizando la supervisión y mejorando la capacidad de respuesta ante condiciones peligrosas. Esto no solo ayudaría a cumplir con las normativas cada vez más estrictas, sino que también protegería a los trabajadores, el medio ambiente y las comunidades circundantes.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

El propósito de esta solución es proporcionar un sistema de monitoreo en tiempo real que detecte posibles fugas de gases combustibles (GNV) durante su transporte. La idea es que, al utilizar sensores avanzados, se pueda identificar rápidamente cualquier fuga que pudiera alcanzar la cabina del conductor sin ser percibida, evitando así riesgos potenciales como explosiones.

Este sistema está diseñado para abordar una problemática crítica en la industria del transporte de gases combustibles: la falta de mecanismos eficaces que permitan alertar a los conductores sobre fugas inminentes antes de que se conviertan en una amenaza. Actualmente, existen pocas soluciones tecnológicas que ofrezcan este nivel de seguridad, lo que hace que nuestra propuesta sea una alternativa innovadora en el mercado.

Sin embargo, hemos observado un factor críticio, que en base a los poisbles incidentes de fuga de gas, no solo puede perjudicar a la empresa en su reputación, sino cobrar vidas humanas debido a la poca atención a este problema

Por tanto, la pregunta clave que este proyecto busca resolver es:

**¿Cómo prevenir eficazmente las fugas de gases combustibles en el transporte para proteger la vida de los conductores y la integridad de la carga?**

#### 1.2.2.2. Lean UX Assumptions

*Bussiness Outcomes:*

- Incremento de la seguridad en el transporte de gases combustibles en un 30%. 

- Reducción del riesgo de explosiones en un 40%.

*Users:*

- **Conductores:** que transportan gases combustibles y necesitan protección frente a posibles fugas.
- **Empresas de transporte:** que desean asegurar la integridad de sus conductores y proteger su carga durante el transporte.

*User Outcomes & Benefits:*

- **Conductores:** Mayor seguridad durante el transporte de gases combustibles. Notificación temprana de posibles fugas, lo que permite tomar acciones inmediatas para evitar accidentes.
- **Empresas de transporte:** Monitoreo en tiempo real de las condiciones de seguridad de sus vehículos. Reducción de riesgos y responsabilidades asociadas a accidentes por fugas de gases.

*Features Assumptions:*

- **Monitoreo en tiempo real:** de las condiciones de seguridad mediante sensores en el vehículo (detección de fugas de gas, temperatura, presión, movimiento, etc.).
- **Alertas inmediatas:** al conductor y al centro de monitoreo en caso de detectar una fuga o condición peligrosa.
- **Registro histórico de datos:** para análisis y mejoras continuas en los protocolos de seguridad.
- **Integración con sistemas de gestión:** de la flota para una visión centralizada de la seguridad en el transporte.

*User Assumptions:*

- **¿Quién es el usuario?** Los usuarios de nuestra solución son conductores de vehículos que transportan gases combustibles y las empresas que gestionan estos transportes.
- **¿Dónde encaja nuestro producto en su trabajo o vida?** Nuestro producto es esencial en el día a día de los conductores, brindándoles una herramienta que les permite realizar su trabajo de manera más segura. Para las empresas, es una solución que mejora la seguridad y eficiencia operativa.
- **¿Qué problemas tiene nuestro producto? ¿Evitar?** Un posible desafío es que los conductores no confíen plenamente en el sistema o lo consideren complejo de usar. Para evitar esto, la interfaz debe ser sencilla y las alertas deben ser claras y precisas.
- **¿Cuándo y cómo es nuestro producto? ¿Usado?** Nuestra solución se utiliza durante todo el transporte de gases combustibles, monitoreando constantemente las condiciones de seguridad y emitiendo alertas en tiempo real.
- **¿Qué características son importantes?** Las características clave incluyen la detección precisa de fugas, la notificación instantánea al conductor, el registro de datos de seguridad y la capacidad de integración con sistemas de gestión de flotas.
- **¿Cómo debe verse nuestro producto y cómo comportarse?** La interfaz debe ser intuitiva y fácil de usar para los conductores. Las alertas deben ser visibles y comprensibles, y el sistema debe responder rápidamente a cualquier cambio en las condiciones de seguridad.

*Business Assumptions:*

- Creemos que nuestros clientes necesitan una mejor manera de asegurar la seguridad en el transporte de gases combustibles.
- Estas necesidades se pueden resolver con una solución IoT que permite el monitoreo en tiempo real y la detección temprana de fugas de gases.
- El valor principal que nuestro cliente quiere de nuestro servicio es la capacidad de prevenir accidentes graves mediante una detección temprana y notificación de fugas.
- El cliente también puede obtener beneficios adicionales como la reducción de costos asociados a accidentes y la mejora en la reputación de la empresa.
- Vamos a adquirir la mayoría de nuestros clientes mediante la promoción en ferias de seguridad, campañas en redes sociales, y recomendaciones de clientes actuales.
- Haremos dinero a través de la venta de dispositivos IoT y suscripciones al servicio de monitoreo.
- Nuestra competencia principal en el mercado serán otras soluciones de monitoreo de seguridad en el transporte de materiales peligrosos.
- Los venceremos debido a la simplicidad de uso de nuestra solución y a la precisión y rapidez en la detección de condiciones peligrosas.
- El mayor riesgo es que las empresas no adopten nuestra solución por considerarla innecesaria o por resistencia al cambio.
- Resolveremos esto a través de demostraciones de la efectividad del sistema y ofreciendo soporte continuo a nuestros clientes.


#### 1.2.2.3. Lean UX Hypothesis Statements

A continuación, se plantean las hipótesis que proponen una solución a la problemática dentro de las funcionalidades de la solución tecnológica. Cada una de estas hipótesis es específica y medible para sustentar el éxito de manera objetiva. Cabe resaltar que las métricas actuales son iguales a promedios generales de soluciones ya existentes.

### Hipótesis 1:
*Creemos que los conductores necesitan una solución que les alerte rápidamente sobre posibles fugas de gases combustibles (GNV).*
*Sabremos que hemos tenido éxito cuando nuestra solución IoT se convierta en una herramienta esencial para la seguridad diaria de los conductores.*

**Métricas:**
1. *Frecuencia de Uso Diario:* Porcentaje de conductores que utilizan el sistema de monitoreo IoT diariamente.
   - Métrica actual: 20%
   - Meta deseada: 60%

2. *Retención a Largo Plazo:* Porcentaje de conductores que siguen utilizando la solución después de 3 meses.
   - Métrica actual: 50%
   - Meta deseada: 70%

---

### Hipótesis 2:
*Creemos que las empresas de transporte necesitan monitorear en tiempo real las condiciones de seguridad de los vehículos que transportan gases combustibles.*
*Sabremos que hemos tenido éxito cuando las empresas adopten nuestra solución para todos sus vehículos de transporte de materiales peligrosos.*

**Métricas:**
1. *Implementación en la Flota:* Porcentaje de vehículos equipados con nuestro sistema IoT.
   - Métrica actual: 10%
   - Meta deseada: 80%

2. *Reducción de Incidentes:* Disminución del número de incidentes relacionados con fugas de gases en los vehículos que usan la solución.
   - Métrica actual: 2 incidentes mensuales
   - Meta deseada: 0 incidentes mensuales

---

### Hipótesis 3:
*Creemos que las empresas de transporte necesitan datos precisos para mejorar sus protocolos de seguridad.*
*Sabremos que hemos tenido éxito cuando las empresas utilicen los datos de nuestra solución para optimizar sus operaciones.*

**Métricas:**
1. *Uso de Datos para la Mejora Continua:* Número de empresas que reportan mejoras en sus protocolos de seguridad basadas en los datos recopilados por el sistema.
   - Métrica actual: 2 empresas
   - Meta deseada: 10 empresas

2. *Reducción en Costos de Seguro:* Porcentaje de reducción en los costos de seguro para las empresas que adoptan nuestra solución.
   - Métrica actual: 5% de reducción
   - Meta deseada: 20% de reducción

---

### Hipótesis 4:
*Creemos que las empresas de transporte deben evaluar constantemente la efectividad de los protocolos de seguridad implementados.*
*Sabremos que hemos tenido éxito cuando la calificación de seguridad de las empresas mejore significativamente gracias a nuestra solución.*

**Métricas:**
1. *Calificación de Seguridad:* Evaluación anual de seguridad por parte de las aseguradoras.
   - Métrica actual: 7/10
   - Meta deseada: 9/10

2. *Feedback de Conductores:* Porcentaje de conductores que reportan sentirse más seguros al utilizar el sistema.
   - Métrica actual: 60%
   - Meta deseada: 90%

---

### Hipótesis 5:
*Creemos que los sensores IoT mejorarán la seguridad en el transporte de gases combustibles.*
*Sabremos que hemos tenido éxito cuando los registros de alertas generadas por los sensores muestren una reducción en los riesgos de fugas.*

**Métricas:**
1. *Alertas por Fugas:* Número de alertas emitidas por fugas detectadas.
   - Métrica actual: 15 alertas mensuales
   - Meta deseada: 5 alertas mensuales

2. *Satisfacción del Cliente:* Estrellas promedio en una escala de 1 a 5 basada en la satisfacción con la solución IoT.
   - Métrica actual: 4.0 estrellas promedio
   - Meta deseada: 4.8 estrellas promedio


#### 1.2.2.4. Lean UX Canvas


![image](https://github.com/user-attachments/assets/206cc4de-3194-4e2d-b4c5-7eb92febd4eb)



## 1.3. Segmentos objetivo

| Tipo de Usuario | Conductores que transportan gases combustibles | Empresas de transporte que operan con materiales peligrosos | 
| - | - | - |
| **Geográfico** | País: Perú <br> Zona de operación: Áreas urbanas y rurales, especialmente rutas de transporte de gases combustibles | País: Perú <br> Zona de operación: Áreas que incluyen rutas de transporte de materiales peligrosos |  
| **Psicográfico** | Clase Social: Media <br> Estilo de Vida: Conductores con experiencia en el transporte de materiales peligrosos, que valoran la seguridad y buscan minimizar riesgos en su trabajo diario. | Clase social: No es relevante dado que puede incluir pequeñas empresas de transporte o grandes corporaciones. <br> Estilo de vida: Empresas comprometidas con la seguridad y la eficiencia en el transporte de materiales peligrosos, interesadas en innovar y mejorar sus protocolos de seguridad. |  
| **Demográfico** | Edad: 25-55 <br> Nivel de Ingreso: No es relevante, dirigido a conductores profesionales con experiencia en la conducción de vehículos de transporte pesado | Edad: 30-60 <br> Nivel de ingreso: No es relevante, dirigido a empresas que manejan flotas de transporte de materiales peligrosos | 


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo
<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 15%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 18%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th rowspan="2">¿Por qué llevar a cabo este análisis?</th>
<th colspan="5">Se hace este analisis para conocer las debilidades y fortalezas y compararlas con el producto solución propuesto</th>
</tr>
<tr class="odd">
<th colspan="5">Llevar a cabo este análisis permite identificar las
ventajas competitivas y oportunidades de mejora de "SafeFlow" frente a
competidores clave, informando estrategias efectivas para destacar en el
mercado agrícola y atraer a agricultores y comerciantes.</th>
</tr>
<tr class="header">
<th></th>
<th></th>
<th>SafeFlow</th>
<th>Grupo Caresny</th>
<th>Dachser</th>
<th>Cargo & Transport</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil</th>
<th>Overview</th>
<th>Es una solución tecnológica integral  que ofrece un sistema 
de detección y alerta para el transporte seguro de productos peligrosos
mediante tecnología IoT..</th>
<th>Es una empresa tradicional en el sector del transporte
de mercancías con un enfoque en soluciones logísticas personalizadas.</th>
<th>Es una multinacional con un enfoque en la logística integral
que abarca transporte terrestre, aéreo y marítimo.</th>
<th>Es una empresa especializada en el transporte de
carga pesada y bienes industriales, con una fuerte presencia en 
mercados emergentes.</th>
</tr>
<tr class="header">
<th>Ventaja competitiva</th>
<th>Su enfoque en la seguridad y supervisión en tiempo real
mediante sensores avanzados que monitorean condiciones como
fugas de gas, temperatura, presión y movimiento.</th>
<th>Amplia red de transporte y servicios logísticos integrados
que permiten una distribución eficiente a nivel global.</th>
<th>Fuerte infraestructura global y capacidades avanzadas en 
gestión de la cadena de suministro.</th>
<th>Experiencia en mercados difíciles y capacidad para manejar
cargas de gran tamaño o peligrosas.</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil de Marketing</th>
<th>Mercado Objetivo</th>
<th>Empresas que transportan productos peligrosos, 
especialmente en la industria química y petrolera.</th>
<th>Empresas que buscan soluciones logísticas personalizadas, 
especialmente en sectores minoristas y de bienes de consumo.</th>
<th>Empresas multinacionales con necesidades complejas de logística
y transporte global.</th>
<th>Industrias pesadas y proyectos de infraestructura en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Estrategias de marketing</th>
<th>Enfoque en la seguridad y cumplimiento normativo, destacando
la innovación tecnológica como diferenciador.</th>
<th>Contratos a largo plazo y servicio al cliente personalizado.</th>
<th>Infraestructura global y tecnología avanzada para la gestión
de la cadena de suministro.</th>
<th>Reputación en fiabilidad y capacidad para manejar cargas complejas.</th>
</tr>
<tr class="odd">
<th rowspan="3">Perfil de Producto</th>
<th>Productos &amp; Servicios</th>
<th>Sistemas IoT para la supervisión del transporte de productos peligrosos.</th>
<th>Soluciones logísticas, transporte terrestre, almacenamiento y distribución.</th>
<th>Servicios de transporte terrestre, aéreo y marítimo, logística contractual
y gestión de la cadena de suministro.</th>
<th>Transporte de carga pesada, logística para proyectos y soluciones 
especializadas para industrias.</th>
</tr>
<tr class="header">
<th>Precios y Costos</th>
<th>Modelo basado en suscripción con costos variables según el número de sensores
y características adicionales.</th>
<th>Costos competitivos, con opciones personalizadas según el servicio requerido.</th>
<th>Varían según la complejidad del servicio y el alcance global.</th>
<th>Costos basados en la complejidad del transporte y el tipo de carga.</th>
</tr>
<tr class="odd">
<th><p>Canales de distribución</p>
<p>(Web y/o Móvil)</p></th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
<th>Plataforma en línea accesible a través de dispositivos móviles y
computadoras.</th>
</tr>
<tr class="header">
<th rowspan="5">Análisis SWOT</th>
<th colspan="5">Realice esto para su startup y sus competidores. Sus
fortalezas deberían apoyar sus oportunidades y contribuir a lo que
ustedes definen como su posible ventaja competitiva.</th>
</tr>
<tr class="odd">
<th>Fortalezas</th>
<th>Innovación tecnológica, enfoque en seguridad, capacidad de 
monitoreo en tiempo real. Plataforma integral.</th>
<th>Red logística establecida, fuerte relación con clientes.</th>
<th>Infraestructura global, experiencia en logística compleja.</th>
<th>Experiencia en manejo de cargas pesadas y peligrosas, 
fuerte presencia en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Debilidades</th>
<th>Dependencia de la tecnología IoT, costos iniciales altos para los clientes.</th>
<th>Falta de innovación tecnológica en comparación con competidores.</th>
<th>Costos operativos altos, dependencia de mercados maduros.</th>
<th>Menor presencia global comparada con competidores más grandes.</th>
</tr>
<tr class="odd">
<th>Oportunidades</th>
<th>Creciente demanda de seguridad en el transporte de productos 
peligrosos, expansión a otros mercados.</th>
<th>Expansión a nuevos mercados y adopción de nuevas tecnologías.</th>
<th>Expansión en mercados emergentes, adopción de tecnologías sostenibles.</th>
<th>Expansión a nuevos sectores industriales, colaboración con nuevas tecnologías.</th>
</tr>
<tr class="header">
<th>Amenazas</th>
<th>Competencia de empresas más grandes con mayores recursos, regulación cambiante.</th>
<th>Competencia de empresas más innovadoras, presión en márgenes de precios.</th>
<th>Competencia en mercados emergentes, fluctuaciones económicas globales.</th>
<th>Competencia en precios, regulaciones ambientales más estrictas.</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

| Estrategia/ Táctica                          | Medidas a tomar                                         |
|----------------------------------------------|---------------------------------------------------------|
| Diferenciación en implementación IoT | \- Destacar la ventaja de la implementación de sensores junto con una aplicación    |
|                                              | \- Resaltar el uso de sensores durante todo el transporte           |
|                                              | \- Alianzas con empresas de transporte |
| Enfoque en la seguridad                    | \- Priorizar la seguridad de los conductores         |
|                                              | \- Ofrecer a las empresas los detalles obtenidos por los sensores en tiempo real         |
| Publicidad mediante redes sociales         | \- Resaltar funcionalidades IoT            |
|                                              | \- Publicitar la solución IoT mediante Facebook, Instagram y Google Ads.           |

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas.

A continuación, se realizaó el diseño de entrevistas para ambos segmentos objetivos contemplados para el proyecto. Las preguntas serán planificadas para que los entrevistados contesten abiertamente y brindando información extra que nos aporte para entenden mejor sus necesidades. Cabe resaltar que no se contemplan las preguntas de introducción, sin embargo, se realizarán al inicio de la entrevista.


**Segmento objetivo: Transportistas**

- ¿Qué medidas de seguridad tienes a tu disposición actualmente para prevenir incidentes durante el transporte de gases combustibles?

- ¿Alguna vez has experimentado o estado cerca de un incidente relacionado con fugas de gas, o algún otro tipo? Si es así, ¿cómo reaccionaste?
  
- ¿Cuáles son las principales frustraciones que ha enfrentado en su trabajo como transportista?

- ¿Utilizas algún tipo de tecnología o dispositivo para monitorear la seguridad de tu carga mientras conduces? ¿Qué ventajas y desventajas encuentras en ella?

- ¿Estarías dispuesto a utilizar una solución técnológica que monitoree las condiciones del cargamento que llevas en tiempo real? ¿Por qué?

- ¿Qué tipo de sensores serían adecuados para realizar el monitoreo de combustibles sobre vehiculos?

- ¿Qué tipo de alertas o notificaciones crees que serían más útiles para prevenir posibles fugas de gases combustibles durante el transporte?
  
- ¿Cómo preferirías recibir estas notificaciones (por ejemplo, a través de una aplicación móvil, mensajes de texto, etc.)?

- ¿Qué barreras crees que podrían existir para adoptar una nueva tecnología de monitoreo de seguridad en tu rutina diaria?
  
- ¿Qué características considerarías indispensables en una solución con tecnologías emergentes para que decidas implementarla en tu trabajo?

- ¿Qué piensas de las soluciones tecnológicas disponibles actualmente en el mercado para la seguridad en el transporte de materiales peligrosos?
  
- ¿Qué aspectos crees que deberían mejorar en estas soluciones para que sean más efectivas?

- ¿Su vehiculo de transporte cuenta con una pantalla de interacción con un sistema operativo?

- ¿Qué dispositivos usa con más frecuencia durante su jornada de trabajo?




**Segmento objetivo: Empresas de transporte de productos peligrosos**


- ¿Qué protocolos de seguridad implementa tu empresa para garantizar la integridad de los transportistas y de la carga durante el transporte de productos peligrosos?
  
- ¿Cómo se maneja la capacitación de los transportistas en cuanto a la prevención de incidentes y la respuesta a emergencias?
  
- ¿Qué tipos de tecnologías o dispositivos utiliza actualmente tu empresa para monitorear la seguridad de las cargas peligrosas?

- ¿Qué tipo de sensores serían adecuados para realizar el monitoreo de combustibles sobre vehiculos?
  
- ¿Estarías interesado en implementar una solución IoT que permita un monitoreo en tiempo real de las condiciones de seguridad? ¿Por qué?
  
- ¿Qué beneficios esperas obtener al implementar una solución IoT para el monitoreo de seguridad?
  
- ¿Qué preocupaciones podrías tener sobre la adopción de esta tecnología en tu empresa?
  
- ¿Cómo prefieres que tu empresa reciba notificaciones o alertas sobre posibles riesgos durante el transporte de productos peligrosos?
  
- ¿De qué manera estas alertas influirían en la toma de decisiones operativas dentro de tu empresa?
  
- ¿Crees que la implementación de una solución IoT de monitoreo de seguridad podría proporcionar una ventaja competitiva a tu empresa? ¿Cómo?
  
- ¿Qué características consideras esenciales para que esta solución se destaque frente a otras opciones tecnológicas disponibles en el mercado?




### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
En esta sección, se buscarán las necesidades implícitas y explícitas de las personas o segmentos para poder diseñar y adaptar el producto solución de manera apropiada.

### 2.3.1. User Personas

Se realiza las User Persona, personaje ficticio para reflejar al cliente ideal, estos user persona son creados en base a la investigación de capitulos previos para identificar a los diferentes tipos de clientes que podrían usar el producto solución. Se utilizó la herramienta UXPressia.

**Transportistas de combustibles peligrosos**

![361573775-97d571cf-7016-4d0d-9b38-ed6343c98e6f](https://github.com/user-attachments/assets/d045a6b1-433a-47e3-ab11-df173cd3438d)


**Empresas de transporte de productos peligrosos**

![Carlo Galavis](https://github.com/user-attachments/assets/fb10e06a-0889-4d9b-a8d0-d005574d1eb8)

### 2.3.2. User Task Matrix

A continuación, se muestra el User Task Matrix para los siguientes segmentos objetivo:


<table>
  <tr>
    <th></th>
    <td colspan="2">TRANSPORTISTAS</td>
    <td colspan="2">EMPRESAS</td>
  </tr>
  <tr>
    <td>TASK</td>
    <td>FREQUENCY</td>
    <td>IMPORTANCE</td>
    <td>FREQUENCY</td>
    <td>IMPORTANCE</td>
  </tr>
  <tr>
    <td>Registrar los envíos de productos combustibles</td>
    <td>Low </td>
    <td>Low</td>
    <td>High</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Coordinar con los demás transportistas detalles acerca del cargamento</td>
    <td>Often</td>
    <td>High</td>
    <td>Rare</td>
    <td>Low</td>
  </tr>
  <tr>
    <td>Trazar la ruta que se tiene que recorrer y sus peligros </td>
    <td>Always</td>
    <td>Medium</td>
    <td>Always</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>Evaluar calidad de los vehiculos de transporte</td>
    <td>Always</td>
    <td>High</td>
    <td>Always</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Evaluar demanda y tendencias</td>
    <td>Often</td>
    <td>High</td>
    <td>Always</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>Revisar el estado del cargamento</td>
    <td>Rare</td>
    <td>Low</td>
    <td>Always</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Inspeccionar la condición del cargamento previo al transporte</td>
    <td>Often</td>
    <td>Low</td>
    <td>Often</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Monitorear la velocidad del transportista</td>
    <td>Rare</td>
    <td>Low</td>
    <td>Always</td>
    <td>High</td>
  </tr>
</table>

**Tareas con Mayor Frecuencia e Importancia:**
- Frecuencia:

> Respecto al segmento objetivo de transportistas, las tareas que se realizan con mayor 
> frecuencia incluyen trazar la ruta que se tiene que recorrer y sus peligros, coordinar con los demás transportistas detalles acerca del cargamento, 
> y evaluar la calidad de los vehículos de transporte. Por otro lado, para el segmento de empresas de transporte de productos peligrosos, las tareas más
> frecuentes son evaluar la calidad de los vehículos de transporte, revisar el estado del cargamento, y trazar la ruta y sus peligros.

- Importancia:

> Para el segmento de empresas de transporte, las tareas más importantes incluyen registrar los 
> envíos de productos combustibles, evaluar la calidad de los vehículos de transporte, y monitorear la velocidad del transportista. 
> En el caso de los transportistas, las tareas de mayor relevancia son coordinar detalles acerca del cargamento, evaluar la 
> calidad de los vehículos de transporte, y trazar la ruta que se tiene que recorrer.

Principales Diferencias y Coincidencias:

Una de las principales diferencias entre los dos segmentos objetivo es que las empresas de transporte tienen una mayor responsabilidad en la supervisión y monitoreo del cargamento, como lo demuestra la alta importancia y frecuencia asignada a tareas como revisar el estado del cargamento y monitorear la velocidad del transportista. Por otro lado, los transportistas se centran más en la planificación de rutas y la coordinación con otros transportistas, lo que refleja su rol más operativo y menos gerencial.

Tanto los transportistas como las empresas coinciden en la alta importancia de la evaluación de la calidad de los vehículos de transporte y la necesidad de trazar rutas seguras y eficientes. Ambas audiencias reconocen la importancia crítica de estas tareas para garantizar la seguridad y la eficiencia en el transporte de productos peligrosos.

### 2.3.3. Empathy Mapping

![Empathy map](https://github.com/user-attachments/assets/ed0e74aa-de6d-4e8f-9ca6-e235f146f6c7)
![Empathy map (1)](https://github.com/user-attachments/assets/ef04d9c0-99cf-47e2-8c70-5f579319d6f7)

### 2.3.4. As-is Scenario Mapping

![image](https://github.com/user-attachments/assets/753224a7-ec79-412f-9fe9-7a5cf13b7c0b)
![image](https://github.com/user-attachments/assets/233c4c8e-0a59-472f-863e-d9023194cdc5)

## 2.4. Ubiquitous Language

•	Profile (Perfil): Un perfil es un registro que contiene información personal sobre un usuario, típicamente almacenado dentro de la base de datos de la aplicación.

•	Registration (Registro): La inscripción es el proceso de crear una cuenta de usuario dentro de la aplicación.

•	FAQ (Frequently Asked Questions) (Preguntas Frecuentes): Las FAQ (Preguntas Frecuentes) son una recopilación de preguntas comúnmente formuladas y sus respectivas respuestas, con el objetivo de proporcionar una ayuda rápida a los usuarios.

•	Dashboard (Panel de control): Un panel de control es un componente de la interfaz de usuario que proporciona una visión general de la información relevante y las acciones disponibles para el usuario, como la gestión de eventos para los organizadores o la configuración de la cuenta para los asistentes.

•	Confirmation (Confirmación): Una confirmación es un reconocimiento o notificación proporcionada a los usuarios después de completar una solicitud o registro de incidente.

•	Event Listing (Listado de eventos): Un listado de eventos es una colección o pantalla de eventos disponibles para que los usuarios los examinen y seleccionen.

•	About Us (Acerca de Nosotros): "Acerca de nosotros" es una sección de la aplicación que contiene información sobre los creadores, la misión y los objetivos de la plataforma.

•	Incident Notification (Notificación de incidentes): El proceso por el cual se informa a los transportistas y empresarios sobre cualquier inconveniente o problema que haya ocurrido durante el servicio de transporte.

•	Transport Service (Servicio de transporte): El conjunto de operaciones logísticas destinadas a transportar bienes desde un punto de origen hasta su destino final.

•	Transporters (Transportistas): Personas o empresas responsables del transporte de bienes desde el origen hasta el destino.

•	Business Owner (Empresario): Persona o entidad encargada de gestionar la logística y la coordinación del transporte de bienes, así como de la relación con los transportistas.

•	Incident Report (Reporte de incidente): Documento que detalla el incidente ocurrido durante el proceso de transporte, incluyendo la causa, el impacto y las acciones correctivas.

•	Transporter Rating (Calificación de transportistas): Proceso mediante el cual los empresarios califican la calidad del servicio ofrecido por los transportistas.

•	Load Monitoring (Monitoreo de carga): Seguimiento en tiempo real del estado y ubicación de la carga durante el proceso de transporte.

•	Transporter Registration (Registro de transportistas): Proceso mediante el cual un transportista crea una cuenta o perfil en la plataforma para ofrecer sus servicios.

•	Login (Iniciar sesión): El proceso mediante el cual un usuario accede a su cuenta en la plataforma.

•	Authentication Policy (Política de autenticación): Conjunto de reglas que definen cómo los usuarios deben autenticarse para acceder a la plataforma, asegurando que solo personas autorizadas puedan ingresar.

•	Service Acceptance (Aceptación del servicio): Confirmación por parte de los transportistas de que aceptan una oferta de servicio de transporte hecha por un empresario.

•	Transport Route (Ruta de transporte): El trayecto que debe seguir el transportista desde el punto de recogida hasta el punto de entrega de la mercancía.




# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

![image](https://media.discordapp.net/attachments/1279250871175217205/1279250982324408340/Scenario_Mapping_Template_-_Frame_2.jpg?ex=66d3c2d1&is=66d27151&hm=54c4b680d9d2eee9426cfcbe1ef072de48a65ecf3ad3690b18a0d15bb38cf318&=&format=webp)

![image](https://media.discordapp.net/attachments/1279250871175217205/1279250984312246332/Scenario_Mapping_Template_-_Frame_1.jpg?ex=66d3c2d1&is=66d27151&hm=f86e1b0ff279b949485d98f0afda095cece2cec945a16ec798576bf58406ead2&=&format=webp)

## 3.2. User Stories

| **Epic ID** | **Epic**                                             | **Descripción**                                                                           |
|-------------|-------------------------------------------------------|--------------------------------------------------------------------------------------------|
| EP01        | Gestión de Transportistas y Documentación de Cumplimiento | Gestión y mantenimiento de perfiles de transportistas, verificación de permisos, y certificaciones. |
| EP02        | Gestión de Solicitudes de Transporte                 | Publicación y administración de solicitudes de transporte por parte de las empresas.       |
| EP03        | Seguimiento y Comunicación en Tiempo Real            | Monitoreo en tiempo real del transporte de productos peligrosos y comunicación de incidentes.|

---

| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** |
|---------------------|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** 
| US01                | Monitoreo del Vehículo                             | Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.                                                         | **Escenario 1: Realizar monitoreo**. Dado que el transportista necesite asegurar el estado del vehículo, cuando inicie la función de monitoreo, entonces el sistema presentará un reporte con el estado del vehículo. **Escenario 2: Error en el monitoreo**. Dado que el sistema presenta un error durante la verificación del estado del vehículo, cuando el transportista intente iniciar la función de monitoreo, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo realizar el monitoreo y sugerir intentar nuevamente o contactar soporte. | EP03                          |
| US02                | Notificaciones de Mantenimiento Preventivo         | Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.                                                                  | **Escenario 1: Notificación de mantenimiento**. Dado que el vehículo se acerque a la fecha de mantenimiento, cuando el sistema detecte la proximidad de esta fecha, entonces se enviará una notificación al transportista. **Escenario 2: Error en la notificación**. Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el transportista revise el sistema, entonces este deberá mostrar un mensaje indicando que hubo un problema y permitir al transportista revisar manualmente las fechas de mantenimiento programadas.         | EP03                          |
| US03                | Verificación de Rutas Seguras                      | Como transportista, quiero verificar rutas seguras antes de iniciar un viaje, para minimizar riesgos.                                                                                                         | **Escenario 1: Verificar ruta**. Dado que el transportista necesite planificar una ruta, cuando el sistema identifique rutas peligrosas, entonces sugerirá rutas alternativas más seguras. **Escenario 2: Error al verificar ruta**. Dado que el sistema no puede cargar las rutas, cuando el transportista intente verificar rutas seguras, entonces el sistema deberá mostrar un mensaje de error e indicar al transportista que intente más tarde o contacte soporte técnico.                                                           | EP03                          |
| US04                | Reporte de Estado del Vehículo                     | Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.                                                                                    | **Escenario 1: Generar reporte**. Dado que el transportista complete la revisión del vehículo, cuando se complete la revisión, entonces el sistema permitirá generar un reporte que puede ser enviado al supervisor. **Escenario 2: Error al generar reporte**. Dado que el sistema falle en generar el reporte, cuando el transportista intente crear el reporte después de la revisión, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo generar el reporte y sugerir reintentar o guardar los datos manualmente. | EP03                          |
| US05                | Seguimiento en Tiempo Real de los Transportes Activos| Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.          | **Escenario 1: Seguimiento del Transporte en Tiempo Real**. Dado que hay un transporte activo en curso, cuando la empresa accede a la sección de seguimiento de transportes, entonces el sistema muestra la ubicación actual y el estado del transporte en tiempo real en un mapa. **Escenario 2: Error en el seguimiento en tiempo real**. Dado que el sistema falle en actualizar la ubicación del transporte, cuando la empresa intente realizar el seguimiento en tiempo real, entonces el sistema deberá mostrar un mensaje indicando que no se puede obtener la ubicación y permitir reintentar o contactar al transportista directamente. | EP03                          |
| US06                | Verificación de Permisos de Transportistas         | Como empresa de transporte de productos peligrosos, quiero verificar los permisos y certificaciones de los transportistas antes de contratarlos.                                                              | **Escenario 1: Verificación de Permisos y Certificaciones**. Dado que la empresa busca contratar un transportista, cuando selecciona un transportista de la lista de disponibles, entonces el sistema muestra un detalle de los permisos, certificaciones y calificaciones del transportista. **Escenario 2: Error al verificar permisos**. Dado que el sistema no pueda cargar los detalles del transportista, cuando la empresa intente verificar permisos y certificaciones, entonces el sistema deberá mostrar un mensaje de error y sugerir intentar más tarde o contactar soporte. | EP02                          |
| US07                | Recibir Notificaciones de Incidentes en Tiempo Real | Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).                     | **Escenario 1: Recepción de Notificaciones de Incidentes**. Dado que un transporte está en curso, cuando ocurre un incidente o evento inesperado, entonces el sistema envía una notificación en tiempo real a la empresa con detalles del incidente y posibles acciones a tomar. **Escenario 2: Error al recibir notificación de incidente**. Dado que el sistema falle en enviar la notificación de incidente, cuando la empresa espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje indicando que no se pudo enviar la notificación y sugerir verificar el estado del transporte manualmente o contactar al transportista. | EP03                          |
| US08                | Registro de Transportista de Combustibles Peligrosos| Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.          | **Escenario 1: Validación del Registro de Transportista**. Dado que el transportista accede a la página de registro, cuando completa todos los campos requeridos y adjunta los documentos de certificación, entonces el sistema valida la información y confirma el registro si todos los datos son correctos. **Escenario 2: Error al registrar transportista**. Dado que el sistema falle en procesar el registro, cuando el transportista intente registrarse, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo completar el registro y sugerir reintentar o contactar soporte técnico.                   | EP01                          |
| US09                | Notificación de Nuevas Solicitudes de Transporte    | Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.                                                                                                           | **Escenario 1: Recepción de Notificación de Nueva Solicitud**. Dado que una empresa de transporte publica una nueva solicitud de transporte de combustibles, cuando el transportista tiene los permisos adecuados y disponibilidad, entonces el transportista recibe una notificación y puede optar por aceptar o rechazar la solicitud. **Escenario 2: Error al recibir notificación de nueva solicitud**. Dado que el sistema falle en enviar la notificación, cuando el transportista espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje de error y sugerir revisar manualmente las solicitudes publicadas o contactar a la empresa de transporte. | EP02                          |
| US10                | Actualización de Estado del Transporte              | Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).                                                                     | **Escenario 1: Actualización del Estado del Transporte en Curso**. Dado que el transportista ha aceptado un trabajo y está en ruta, cuando hay un cambio en el estado del transporte, entonces el transportista puede actualizar el estado y la empresa recibe una notificación con el estado actualizado. **Escenario 2: Error al actualizar estado del transporte**. Dado que el sistema falle en procesar la actualización del estado del transporte, cuando el transportista intente actualizar el estado, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo actualizar el estado y sugerir reintentar o contactar a la empresa directamente. | EP02                          |
| US11                | Publicación de Solicitudes de Transporte de Productos Peligrosos | Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.                              | **Escenario 1: Publicación de Solicitud de Transporte**. Dado que la empresa accede a la sección de solicitud de transporte, cuando completa el formulario de solicitud con toda la información requerida, entonces la solicitud se publica y los transportistas calificados reciben notificaciones. **Escenario 2: Error al publicar solicitud de transporte**. Dado que el sistema falle en procesar la solicitud de transporte, cuando la empresa intente publicar la solicitud, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo publicar la solicitud y sugerir reintentar o contactar soporte técnico. | EP02                          |
| US12                | Visualización de Transportistas Disponibles         | Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.                   | **Escenario 1: Visualización de Transportistas Calificados**. Dado que la empresa ha publicado una solicitud de transporte, cuando hay transportistas calificados disponibles, entonces el sistema muestra una lista de transportistas con sus detalles de calificación, precio, y disponibilidad. **Escenario 2: Error al visualizar transportistas disponibles**. Dado que el sistema falle en cargar la lista de transportistas disponibles, cuando la empresa intente visualizar transportistas calificados, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo cargar la lista y sugerir reintentar o contactar soporte técnico. | EP02                          |
| US13                | Acceso a Historial de Transportes Realizados        | Como transportista de combustibles peligrosos, quiero acceder a un historial de todos los transportes que he realizado, con detalles sobre la carga, rutas, y tiempos de entrega.                            | **Escenario 1: Visualización del Historial de Transportes**. Dado que el transportista está en su panel de control, cuando selecciona la opción de historial de transportes, entonces el sistema muestra una lista de transportes realizados con detalles relevantes como fechas, rutas, tipos de combustible transportado, y tiempos de entrega. **Escenario 2: Error al visualizar historial de transportes**. Dado que el sistema falle en cargar el historial de transportes, cuando el transportista intente acceder a su historial, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo cargar el historial y sugerir reintentar o contactar soporte técnico. | EP01                          |
| US14                | Landing Page responsive       | Como visitante, deseo visitar la landing page desde cualquier dispositivo.                                                      | **Escenario 01**: Dado que el visitante necesita una aplicación web o móvil para mejorar su servicio, cuando busque en el navegador "Monitorear productos peligrosos", entonces accede a la landing page y visualiza las funcionalidades que le ofrece la aplicación web o móvil. **Escenario 02**: Dado que el visitante desea una aplicación web o móvil con características puntuales de seguridad de transporte de productos peligrosos, cuando navegue por la landing page y se encuentre en la sección de beneficios y funcionalidades, entonces visualizará la funcionalidad que se desea y se decide en usar la aplicación web o móvil.      | EP01                          |
| US15                | Visualización de características de la aplicación web o móvil en Landing Page | Como visitante, deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo.                                  | **Escenario 01**: Dado que el visitante accede a la landing page desde su celular, cuando visite la landing page desde el navegador de su celular, entonces la landing page con su diseño responsive puede visualizarse adecuadamente en el navegador del dispositivo móvil. **Escenario 02**: Dado que el visitante recomienda la landing page mediante un dispositivo móvil, cuando el otro visitante recomendado acceda a la landing page desde otro dispositivo móvil con resolución diferente, entonces la landing page se mostrará completamente visible y ordenada dado que es responsive.            | EP01                          |
| US16                | Botón Call to Action       | Como visitante, deseo ir a la aplicación web o móvil desde un solo botón desde la landing page.                                    | **Escenario 01**: Dado que el visitante desea usar la aplicación web o móvil, cuando esté en la sección donde se encuentre el botón call to action y lo use, entonces será dirigido a la aplicación web o móvil. **Escenario 02**: Dado que el visitante quedó satisfecho con la información brindada en la landing page, cuando desee empezar a usar la aplicación web o móvil, entonces puede acceder a ella de forma rápida mediante el botón call to action
| **TS-01** | Implementación de Monitoreo del Vehículo           | Como desarrollador, quiero implementar la funcionalidad de monitoreo del vehículo para que los transportistas puedan verificar el estado del vehículo antes de iniciar un viaje. | **Background:** Implementar el endpoint `GET /api/vehicle-monitoring/{vehicleId}` para obtener el estado actual del vehículo.<br><br>**Scenario 01: Obtener estado del vehículo**<br>Dado que el transportista quiere verificar el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo existe en la base de datos, entonces el sistema devuelve un `response` con `status 200` y los detalles del estado del vehículo en el `Response Body`.<br><br>**Scenario 02: Error al obtener estado del vehículo**<br>Dado que el sistema falla en obtener el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo no existe o hay un problema en el sistema, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP03**                   |
| **TS-02** | Implementación de Notificaciones de Mantenimiento Preventivo | Como desarrollador, quiero implementar el sistema de notificaciones de mantenimiento preventivo para alertar a los transportistas cuando se acerque la fecha de mantenimiento del vehículo. | **Background:** Configurar un sistema de notificaciones automáticas que envíe alertas a través de `POST /api/notifications/maintenance`.<br><br>**Scenario 01: Envío de notificación de mantenimiento**<br>Dado que la fecha de mantenimiento del vehículo se acerca, cuando el sistema detecta que faltan X días para la fecha de mantenimiento, entonces se envía una notificación al transportista y se devuelve un `response` con `status 200` confirmando el envío exitoso.<br><br>**Scenario 02: Error en el envío de notificación de mantenimiento**<br>Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el sistema intenta enviar la notificación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP03**                   |
| **TS-03** | Implementación de Verificación de Permisos de Transportistas | Como desarrollador, quiero implementar la funcionalidad para verificar los permisos y certificaciones de los transportistas, para que las empresas puedan tomar decisiones informadas al contratarlos. | **Background:** Crear un endpoint `GET /api/transporters/{transporterId}/certifications` que devuelva los permisos y certificaciones de un transportista específico.<br><br>**Scenario 01: Obtener permisos y certificaciones del transportista**<br>Dado que la empresa necesita verificar los permisos de un transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, y el transportista tiene permisos registrados, entonces el sistema devuelve un `response` con `status 200` y los detalles de las certificaciones en el `Response Body`.<br><br>**Scenario 02: Error al obtener permisos y certificaciones**<br>Dado que el sistema falla en obtener los permisos del transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP02**                   |
| **TS-04** | Implementación de Monitoreo en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad de monitoreo en tiempo real utilizando la Edge API, para que los dispositivos IoT puedan enviar datos de ubicación y estado directamente desde el transporte. | **Background:** Configurar un endpoint en la Edge API `POST /edge/vehicle-monitoring` que reciba datos en tiempo real desde dispositivos IoT instalados en los vehículos.<br><br>**Scenario 01: Recepción de datos en tiempo real**<br>Dado que el vehículo está en movimiento, cuando el dispositivo IoT envía datos de ubicación y estado al endpoint `/edge/vehicle-monitoring`, entonces la Edge API procesa y almacena los datos en la base de datos central, devolviendo un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de datos**<br>Dado que el sistema IoT falla en enviar los datos al Edge API, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/vehicle-monitoring` y ocurre un error de conexión o datos corruptos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP03**                   |
| **TS-05** | Implementación de Notificaciones de Incidentes en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT envíen notificaciones de incidentes en tiempo real a través de la Edge API, para que la empresa pueda reaccionar rápidamente a situaciones críticas. | **Background:** Configurar un endpoint en la Edge API `POST /edge/incident-notifications` que reciba alertas de incidentes desde los sensores IoT del vehículo.<br><br>**Scenario 01: Recepción de notificación de incidente**<br>Dado que ocurre un incidente durante el transporte, cuando el dispositivo IoT detecta un evento crítico (accidente, desviación, etc.) y envía datos al endpoint `/edge/incident-notifications`, entonces la Edge API procesa la alerta, notifica a la empresa, y devuelve un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de notificación de incidente**<br>Dado que el sistema IoT falla en enviar la notificación de incidente, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/incident-notifications` y ocurre un error de comunicación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP03**                   |
| **TS-06** | Implementación de Actualización de Estado del Vehículo desde Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT en el vehículo actualicen el estado del transporte en tiempo real a través de la Edge API, para que la empresa siempre tenga información precisa sobre el progreso del viaje. | **Background:** Configurar un endpoint en la Edge API `PUT /edge/vehicle-status/{vehicleId}` que permita a los dispositivos IoT actualizar el estado del vehículo (en camino, retraso, entregado, etc.).<br><br>**Scenario 01: Actualización de estado exitosa**<br>Dado que el vehículo cambia su estado (por ejemplo, llega al destino), cuando el dispositivo IoT envía una actualización de estado al endpoint `/edge/vehicle-status/{vehicleId}`, entonces la Edge API actualiza la información en el sistema central y devuelve un `response` con `status 200` para confirmar la actualización exitosa.<br><br>**Scenario 02: Error en la actualización del estado del vehículo**<br>Dado que el sistema IoT falla en actualizar el estado del vehículo, cuando el dispositivo IoT intenta enviar una actualización al endpoint `/edge/vehicle-status/{vehicleId}` y ocurre un error de transmisión o de datos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP02**                   |


## 3.3. Impact Mapping

![image](https://media.discordapp.net/attachments/1279250871175217205/1279250982923931691/Impact_map_1_1.png?ex=66d3c2d1&is=66d27151&hm=620328f456178569c0d3af35b326471546e22dbabfe6360d691a4d93c28c7be1&=&format=webp)


![image](https://media.discordapp.net/attachments/1279250871175217205/1279250983444156538/Impact_map_1.png?ex=66d3c2d1&is=66d27151&hm=892103df7d0a24255cd97616f425c38a778a92ec6ca5e0a97103e79863c57c86&=&format=webp)


## 3.4. Product Backlog

A continuación, se mostrará la herramienta Product Backlog, lista de trabajo ordenado por la prioridad para el equipo de desarrollo de GreatMinds.

|**#Orden**|**User Story Id**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8)**|
| :-: | :-: | :-: | :-: | :-: |
|01|US15|Visualización de características de la aplicación web o móvil web en Landing Page|Como visitante deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo|5|
|02|US14|Landing Page responsive| Como visitante deseo visitar la landing page desde cualquier dispositivo.|5|
|03|US16|Botón Call to Action|Como visitante deseo ir a la aplicación web o móvil web desde un solo botón desde la landing page |5|
|04|US12|Publicación de Solicitudes de Transporte de Productos Peligrosos|Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.|5|
|05|US10|Notificación de Nuevas Solicitudes de Transporte|Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.|8|
|06|US01|Monitoreo del Vehículo|Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.|8|
|07|US03|Notificaciones de Mantenimiento Preventivo|Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.|5|
|08|US13|Visualización de Transportistas Disponibles|Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.|5|
|09|US11|Actualización de Estado del Transporte|Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).|8|
|10|US09|Registro de Transportista de Combustibles Peligrosos|Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.|8|
|11|US07|Verificación de Permisos de Transportistas|Como empresa de transporte de productos peligrosos, quiero verificar los permisos y certificaciones de los transportistas antes de contratarlos.|3|
|12|US08|Recibir Notificaciones de Incidentes en Tiempo Real|Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).|5|
|13|US06|Seguimiento en Tiempo Real de los Transportes Activos|Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.|2|
|14|US05|Reporte de Estado del Vehículo|Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.|3|
|15|US02|Chequeo Automático de Neumáticos|Como transportista, quiero recibir alertas automáticas sobre el estado de los neumáticos, para evitar accidentes en la ruta.|3|


# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design
### 4.1.1. Design Purpose

El propósito del diseño de la plataforma "SafeFlow" se centra en maximizar la eficiencia, satisfacción y seguridad durante todo el servicio del transporte de productos peligrosos, tanto para los transportistas y las empresas que ofrecen el tipo de servicio de transporte de combustibles.

### 4.1.2. Attribute-Driven Design Inputs

A continuación, en esta sección se detallará los 3 puntos relacionados al proceso ADD.

#### 4.1.2.1. Primary Functionality (Primary User Stories)

Con el objetivo de priorizar las historias de usuario clave apra el funcionamiento básico del sistema y la saisfacción de los usuarios finales, se listaron aquellas con más story points en el product backlog.

| **ID** | **Título**                                          | **Descripción**                                                                                                                                                       | **Criterios de aceptación**                                                                                                                                                                                                                                                                                                                                                                          | **Relacionado con (Epic ID)** |
|--------|-----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| US01                | Monitoreo del Vehículo                             | Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.                                                         | **Escenario 1: Realizar monitoreo**. Dado que el transportista necesite asegurar el estado del vehículo, cuando inicie la función de monitoreo, entonces el sistema presentará un reporte con el estado del vehículo. **Escenario 2: Error en el monitoreo**. Dado que el sistema presenta un error durante la verificación del estado del vehículo, cuando el transportista intente iniciar la función de monitoreo, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo realizar el monitoreo y sugerir intentar nuevamente o contactar soporte. | EP03                          |
| US09                | Notificación de Nuevas Solicitudes de Transporte    | Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.                                                                                                           | **Escenario 1: Recepción de Notificación de Nueva Solicitud**. Dado que una empresa de transporte publica una nueva solicitud de transporte de combustibles, cuando el transportista tiene los permisos adecuados y disponibilidad, entonces el transportista recibe una notificación y puede optar por aceptar o rechazar la solicitud. **Escenario 2: Error al recibir notificación de nueva solicitud**. Dado que el sistema falle en enviar la notificación, cuando el transportista espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje de error y sugerir revisar manualmente las solicitudes publicadas o contactar a la empresa de transporte. | EP02                          |
| US10                | Actualización de Estado del Transporte              | Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).                                                                     | **Escenario 1: Actualización del Estado del Transporte en Curso**. Dado que el transportista ha aceptado un trabajo y está en ruta, cuando hay un cambio en el estado del transporte, entonces el transportista puede actualizar el estado y la empresa recibe una notificación con el estado actualizado. **Escenario 2: Error al actualizar estado del transporte**. Dado que el sistema falle en procesar la actualización del estado del transporte, cuando el transportista intente actualizar el estado, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo actualizar el estado y sugerir reintentar o contactar a la empresa directamente. | EP02                          |
| US08                | Registro de Transportista de Combustibles Peligrosos| Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.          | **Escenario 1: Validación del Registro de Transportista**. Dado que el transportista accede a la página de registro, cuando completa todos los campos requeridos y adjunta los documentos de certificación, entonces el sistema valida la información y confirma el registro si todos los datos son correctos. **Escenario 2: Error al registrar transportista**. Dado que el sistema falle en procesar el registro, cuando el transportista intente registrarse, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo completar el registro y sugerir reintentar o contactar soporte técnico.                   | EP01                          |

#### 4.1.2.2. Quality Attribute Scenarios

| **ID** | **Atributo**   | **Fuente**         | **Estímulo**                         | **Artefacto**             | **Entorno**         | **Respuesta**                       | **Medida**                                   |
|--------|----------------|--------------------|--------------------------------------|---------------------------|---------------------|--------------------------------------|----------------------------------------------|
| QS-1   | Disponibilidad | Conexión interna   | Error en un servidor de despliegue   | Conexión con despliegue   | Operación normal    | Resultado de la consulta             | Sin caída de los servicios del programa      |

 El sistema deberá utilizar una conexión con otro servidor de producción de SafeFlow cuando ocurra algún fallo en el servidor utilizado por el usuario para consultas

| **ID** | **Atributo**   | **Fuente**         | **Estímulo**                         | **Artefacto**             | **Entorno**         | **Respuesta**                       | **Medida**                                   |
|--------|----------------|--------------------|--------------------------------------|---------------------------|---------------------|--------------------------------------|----------------------------------------------|
| QS-2   | Usabilidad     | Usuario            | Cancelamiento de un servicio de transporte | Controlador               | Operación           | - Mensaje de éxito en pantalla - Cancelar reserva | # de transportes cuyo estado es cancelado + 1 |

El usuario podrá cancelar un envío de transporte antes de que esté ‘en progreso’ cuando presione el botón “Cancelar”.

| **ID** | **Atributo**   | **Fuente**         | **Estímulo**                         | **Artefacto**             | **Entorno**         | **Respuesta**                       | **Medida**                                   |
|--------|----------------|--------------------|--------------------------------------|---------------------------|---------------------|--------------------------------------|----------------------------------------------|
| QS-3   | Seguridad    | Usuario            | Iniciar sesión | Dispositivo movil con software malicioso              | JWT y Proxy         | Dispositivo móvil con software malicioso | Pruebas de penetración |

El usuario debe ser autenticado con JWT y sus datos son encriptados para que ningún software malicioso acceda a sus datos.


#### 4.1.2.3. Constraints



### 4.1.3. Architectural Drivers Backlog

| Driver ID | Título de Driver          | Descripción              | Importancia para Stakeholders (High, Medium, Low) | Impacto en Architecture Technical Complexity (High, Medium, Low) |
|-----------|---------------------------|--------------------------|---------------------------------------------------|---------------------------------------------------------------|
|      QS-1    |              Availability             |          Garantizar la disponibilidad del software en todo, en especifico los procesos de monitoreo y registro de incidentes. Garantizando un sistema operable y comprometido en cumplir la misión del usuario               |                 High                                  |                            High                                   |
|      QS-2    |              Usability             |          Facilitar la experiencia de usuario es de suma importancia dado que el transportista necesita visualizar las notifiaciones visualmente clara y rapida, asimismo los reportes y formularios deben tener opción de "cancelar". De esta manera se garantiza una experiencia de  usuario completa acorde con el dominio del negocio               |                 High                                  |                            Medium                                   |
|      QS-3    |              Security            |          Garantizar la seguridad de los datos personales              |                 High                                  |                            High                                   |

### 4.1.4. Architectural Design Decisions

![image](https://github.com/user-attachments/assets/d403c417-3264-499b-b8b1-e805f7df36af)


### 4.1.5. Quality Attribute Scenario Refinements

![image](https://github.com/user-attachments/assets/1c383976-be4f-4260-96ae-cb9c3e1af6ca)



## 4.2. Strategic-Level Domain-Driven Design
### 4.2.1. EventStorming

Para la sección de Event Storming el equipo de desarrollo tuvo una reunión donde expusimos ideas acerca de las funcionalidades y caracteristicas a implementar en el proyecto. En el transcurso de la reunión, se lograron plantar varias ideas para la plataforma, adempas de las primeras versiones para los bounded context.

En esta etapa, se identificaron los eventos clave que representan las acciones significativas dentro de la solución tecnológica. La herramienta utilizada fue Miro.

![image](https://github.com/user-attachments/assets/08119e3e-b039-4ab5-9bf3-524da0cb3c01)


**Step 2: Timelines**

Durante esta fase, los eventos identificados fueron agrupados en subgrupos liderados por un evento en general que encapsula la función principal del grupo. Estos grupos incluyen happy paths, que representan los caminos deseados o exitoso, y los unhappy paths, que muestran los posibles problemas o situaciones no deseadas que pudieran surgir. Esto ayudó a darle una estructura a los eventos de manera coherente y a comprender mejor las diferentes secuencias dentro del sistema.

![image](https://github.com/user-attachments/assets/a715602c-a47a-439c-9e30-f6ff791400c6)


**Step 3: Paint Points**

En este proceso, se identificaron paint points o puntos problemáticos, que son áreas donde los usuarios pueden experimentar dificultados o fricciones en su interacción con la aplicación. Estos puntos son cruciales para mejorar la experiencia del usuario y optimizar el diseño del sistema

![image](https://github.com/user-attachments/assets/80e9dda3-c237-425d-9699-514d4a28d421)


**Step 4: Pivotal points**

Se señalaron los pivotal points o puntos clave, que son eventos críticos que marcan hitos improtantes en el flujo de la plataforma. Estos eventos tienden a ser significativos en el comportamiento del sistema o en la experiencia del usuario

![image](https://github.com/user-attachments/assets/01cbc4a0-b909-4840-a70a-3bd2f044a2ed)


**Step 5: Commands**

Cada evento se asoció a un comando en específico que lo desencadena y un actor que lo realiza. Esto ayudó a tener un mejor reconocimiento de cómo interactúan los diferentes usuarios con el sistema.

![image](https://github.com/user-attachments/assets/978c377f-81e8-4ace-88cf-777caadebbd0)


**Step 6: Policies**

Durante esta etapa, se identifican las politicas relevantes para cada contexto del sistema. Estas politica spueden incluir restricciones de negocio, reglas de validación, etc.

![image](https://github.com/user-attachments/assets/87c92947-c5e6-439a-a120-a83cb7d01d0b)


**Step 7: Read Models**

Durante esta fase, se diseñan y desarrollan lso modelos de lectura para cada contexto de sistema, asegurando que proporcionen la información necesaria de manera eficiente y coherente.

![image](https://github.com/user-attachments/assets/dfd3a65d-e07a-44cf-b6fb-dbc3beb86a5a)


**Step 8: External Systems** 

Durante esta etapa, se identifican los sistemas externos relevantes para la plataforma y se establecen las interfaces necesarias para integrarlos de manera efectiva.

![image](https://github.com/user-attachments/assets/547d18ae-44a2-4959-95fd-6eb6dd9e6d7d)


**Step 9: Aggregates**

Durante esta etapa, se definen aggregates para cad contexto del sistema, asegurando que representen ocrrectamente las transacciones y operaciones coherentes dentro del sistema.

![image](https://github.com/user-attachments/assets/8473641f-be07-4664-acb8-4e32231dfbca)

Link de Miro: https://miro.com/welcomeonboard/MmFIalZxRFFmZEpobnVxU2tvVUNmZEN3R2JDbExMdUVybEJTNlI5cnRicWpLRWlCcGVYYmwzRTBhVWJqRHJ1aXwzMDc0NDU3MzU3NDk3MzU0NjE5fDI=?share_link_id=498149078137

### 4.2.2. Candidate Context Discovery

A continuación, elegimos utilizar la técnica de start-with-value ya que el equipo de desarrollo decidió empezar por el valor de la aplicación (core), esto es importante para tener una mejor visión del producto.

- **Identificación de Valores del Negocio** : Analizamos los valores clave del negocio, como la experiencia del usuario al monitorearla carga y registrar un incidente, calificación de transportista y la eficiencia en la gestión de usuarios.

- **Identificación de Funcionalidades clave** : Identificar las funcionalidades esenciales de la aplicación, como la autenticación y registro de usuarios (IAM), el monitoreo y notificación de incidentes (Management) y las funcionalidades relacionadas al registro de incidentes y reportes (Records), que contribuyen directamente a la entre de los valores empresariales.

Candidate para Bounded Context: IAM
![image](https://github.com/user-attachments/assets/8fbd7f62-9488-4edf-88da-c2f1b87ba1e4)


Candidate para Bounded Context: Management
![image](https://github.com/user-attachments/assets/67b0f89a-5324-4e8e-8155-9929101dccc7)


Candidate para Bounded Context: Records
![image](https://github.com/user-attachments/assets/de7a3e2e-54c2-4e5b-8c49-e180f7e6a808)


Vista completa:
![image](https://github.com/user-attachments/assets/9a66c4d3-d5de-442e-9f51-b29718317938)


### 4.2.3. Domain Message Flows Modeling





### 4.2.4. Bounded Context Canvases




### 4.2.5. Context Mapping

Después de realizar el EventStorming se identificó 3 bounded context: IAM, Records y Management. Se ha decidido usar los siguientes patrones:

**IAM y Records (Customer/Supplier Pattern):**

Relación: IAM valida y proporciona la autenticación para los transportistas y empresarios que interactúan con Records. Esta interacción permite el acceso adecuado para reportar y gestionar incidentes.


**IAM y Management (Shared Kernel Pattern):**

Relación: Compartición de datos de autenticación y roles de usuario, lo que permite la ejecución fluida de procesos dentro de Management. Este patrón ayuda a reducir la redundancia y mantener la consistencia en los permisos de acceso.

**Records y Management (Anti-Corruption Layer Pattern):**

Relación: Utilizar un Anti-Corruption Layer permite gestionar la interacción entre la notificación de incidentes y la operación del transporte. Protege los datos internos de Management de cambios que puedan afectar negativamente la funcionalidad de Records y viceversa.

![image](https://github.com/user-attachments/assets/5f6d675d-b452-43a9-8a41-8461d7e18083)




## 4.3. Software Architecture

A continuación se mostrarán los diagramas c4 que exponen la arquitectura del sistema.

### 4.3.1. Software Architecture System Landscape Diagram

![image](https://github.com/user-attachments/assets/f2298318-2b09-4ce5-bc9c-88c8aa668d06)


### 4.3.2. Software Architecture Context Level Diagrams

![image](https://github.com/user-attachments/assets/b0a73a76-60b2-4ca8-90b5-b1d30959cf41)



### 4.3.3. Software Architecture Container Level Diagrams

![image](https://github.com/user-attachments/assets/e1b399c4-6509-4dc9-98fc-0196cb8b8a71)



### 4.3.4. Software Architecture Deployment Diagrams

![image](https://github.com/user-attachments/assets/3330ed52-938f-4075-abe1-8cdd753a0a02)





# Conclusión

En esta primera entrega se realizaron tareas relacionadas a la captura de requisitos y toma de decisiones a la solución tecnoloógica con tecnologías emergentes, en este caso utilizanod IOT. Se planteó el dominio de negocio y a que problemática responde. 


# Bibliografía

López-Atamoros, L. G., Fernández-Villagómez, G., Cruz-Gómez, M. J., & Durán-de-Bazúa, C. (2010). Integración de una Base Nacional de Datos de Accidentes durante el Transporte de Gas LP (BNDAT@ GLP) 1998-2009: Sustento para un estudio de evaluación de riesgo. Tecnología, Ciencia, Educación, 25(2), 99-112.

Soto, J. A. S., González, D. L. E., Sánchez, J. F. I., Reyes, J. A., & Layva, J. M. E. (2023). DISEÑO DE DISPOSITIVO PARA PREVENIR ACCIDENTES CAUSADOS POR FUGAS DE GAS. Revista IPSUMTEC, 6(4), 11-14.


# Anexos

Video exposición TB1: 
