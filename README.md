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
