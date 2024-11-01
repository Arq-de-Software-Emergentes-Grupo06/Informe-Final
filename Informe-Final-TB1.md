![UPC_logo_transparente (1)](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2ff342be-dc34-415c-925e-1e7133e49abf)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2024-02

# ARQUITECTURA DE SOFTWARE EMERGENTES

Sección SW82

Profesor: Rojas Malasquez, Royer Edelwer

***INFORME DE TRABAJO FINAL - TB2***

**Startup: CuriDev**

**Producto: SafeFlow - IOT**

**Integrantes:**
- Alarcon Rondon. Sandro Fourfive
- Espejo Macuri, Paolo Andre
- Gonzales Carrión, Jorge Enrique
- Laguerre Chalco, Fabrizzio Hernan
- Pozo Campos, Rodrigo Jair

Octubre del 2024

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
| 1.00 | 15/08/2024 | Alarcon Rondon. Sandro Fourfive | To Be Scenario Map, Diseño de historia de usuarios, constrains v.1|
| 1.10 | 20/08/2024 | Espejo Macuri, Paolo Andre | Diseño de historia de usuario, EventStorming v.1 |
| 1.20 | 21/08/2024 | Gonzales Carrión, Jorge Enrique| Strategic-Level Attribute-Driven Design, Strategic-Level Domain-Driven Design, Software Architecture, diseño y registro de entrevistas |
| 1.30 | 21/08/2024 | Laguerre Chalco, Fabrizzio Hernan | EventStorming, Bounded Context Candidates, diseño y registro de entrevistas |
| 1.40 | 01/09/2024 | Pozo Campos, Rodrigo Jair | Diseño de user stories, analisis de entrevistas, proceso Lean UX, Constrains v.1 |
| 2.00 | 18/09/2024 | Gonzales Carrión, Jorge Enrique | Diseño de Strategical Driven Design y mockups/wireframes de app movil |
| 2.10 | 18/09/2024 |  Pozo Campos, Rodrigo Jair  | Diseño de Landing Page (mockups y wireframes) |
| 2.20 | 18/09/2024 |  Alarcon Rondon. Sandro Fourfive | Diseño de Web App (mockups y wireframes) |
| 2.30 | 18/09/2024 |  Espejo Macuri, Paolo Andre | Diseño de Strategical Driven Design |
| 2.40 | 18/09/2024 |  Laguerre Chalco, Fabrizzio Hernan | Elaboración de wireflows |
| 3.00 | 30/10/2024 |  Gonzales Carrión, Jorge Enrique  | Desarrollo de apliación móvil y sprint backlog |
| 3.10 | 30/10/2024 | Pozo Campos, Rodrigo Jair   | Desarrollo de aplicación embebida IoT y registro de entrevistas de validación |
| 3.20 | 30/10/2024 | Espejo Macuri, Paolo Andre   | Desarrollo de API Web y evaluación de heuristicas |
| 3.30 | 30/10/2024 | Laguerre Chalco, Fabrizzio Hernan   | Registro de entrevistas y desarrollo de video about the product |
| 3.40 | 30/10/2024 | Alarcon Rondon. Sandro Fourfive   | Registro de entrevistas y desarrollo de aplicación móvil |
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

Registro de commits:
![image](https://github.com/user-attachments/assets/500ba39d-a9c5-4940-a872-bf7857b7909e)

TP: Se han desarrollado las actividades correspondientes para la entrega TP en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final

Para la elaboración del informe se realizaron actividades tales como:

-Primera versión de Software Architecture, Strategic-Level Domain-Driven Design

- Applications MockUps y Wireframes

- Applications wireflows y userflow


Registro de commits:

![image](https://github.com/user-attachments/assets/d33f0acd-2e33-46fd-930d-d11933729ae4)

TB2: Se han desarrollado las actividades correspondientes para la entrega TB2 en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final

Para la elaboración del informe se realizaron actividades tales como:

-Primera versión de los productos digitales tales como:

- Mobile App

- Embedded App IoT

- API Web (Beeceptor)


Registro de commits:

![imagen](https://github.com/user-attachments/assets/c752f5e0-8fd2-47b9-8969-fa46099cf371)




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
    
## [Capítulo V: Tactical-Level Software Design](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#cap%C3%ADtulo-v-tactical-level-software-design)
- [5.1. Bounded Context: IAM](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#51-bounded-context-iam)
  - [5.1.1. Domain Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#511-domain-layer)
  - [5.1.2. Interface Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#512-interface-layer)
  - [5.1.3. Application Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#513-application-layer)
  - [5.1.4. Infrastructure Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#514-infrastructure-layer)
  - [5.1.6. Bounded Context Software Architecture Component Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#516-bounded-context-software-architecture-component-level-diagrams)
  - [5.1.7. Bounded Context Software Architecture Code Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#517-bounded-context-software-architecture-code-level-diagrams)
    - [5.1.7.1. Bounded Context Domain Layer Class Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#5171-bounded-context-domain-layer-class-diagrams)
    - [5.1.7.2. Bounded Context Database Design Diagram](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#5172-bounded-context-database-design-diagram)
- [5.2. Bounded Context: Management](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#52-bounded-context-management)
  - [5.2.1. Domain Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#521-domain-layer)
  - [5.2.2. Interface Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#522-interface-layer)
  - [5.2.3. Application Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#523-application-layer)
  - [5.2.4. Infrastructure Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#524-infrastructure-layer)
  - [5.2.6. Bounded Context Software Architecture Component Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#526-bounded-context-software-architecture-component-level-diagrams)
  - [5.2.7. Bounded Context Software Architecture Code Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#527-bounded-context-software-architecture-code-level-diagrams)
    - [5.2.7.1. Bounded Context Domain Layer Class Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#5271-bounded-context-domain-layer-class-diagrams)
    - [5.2.7.2. Bounded Context Database Design Diagram](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#5272-bounded-context-database-design-diagram)
- [5.3. Bounded Context: Records](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#53-bounded-context-records)
  - [5.3.1. Domain Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#531-domain-layer)
  - [5.3.2. Interface Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#532-interface-layer)
  - [5.3.3. Application Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#533-application-layer)
  - [5.3.4. Infrastructure Layer](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#534-infrastructure-layer)
  - [5.3.6. Bounded Context Software Architecture Component Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#536-bounded-context-software-architecture-component-level-diagrams)
  - [5.3.7. Bounded Context Software Architecture Code Level Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#537-bounded-context-software-architecture-code-level-diagrams)
    - [5.3.7.1. Bounded Context Domain Layer Class Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#5371-bounded-context-domain-layer-class-diagrams)
    - [5.3.7.2. Bounded Context Database Design Diagram](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#5372-bounded-context-database-design-diagram)

## [Capítulo VI: Solution UX Design](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#cap%C3%ADtulo-vi-solution-ux-design)
- [6.1. Style Guidelines](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#61-style-guidelines)
  - [6.1.1. General Style Guidelines](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#611-general-style-guidelines)
  - [6.1.2. Web, Mobile & Devices Style Guidelines](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#612-web-mobile--devices-style-guidelines)
- [6.2. Information Architecture](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#62-information-architecture)
  - [6.2.2. Labeling Systems](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#622-labeling-systems)
  - [6.2.3. Searching Systems](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#623-searching-systems)
  - [6.2.4. SEO Tags and Meta Tags](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#624-seo-tags-and-meta-tags)
  - [6.2.5. Navigation Systems](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#625-navigation-systems)
- [6.3. Landing Page UI Design](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#63-landing-page-ui-design)
  - [6.3.1. Landing Page Wireframe](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#631-landing-page-wireframe)
  - [6.3.2. Landing Page Mock-up](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#632-landing-page-mock-up)
- [6.4. Applications UX/UI Design](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#64-applications-uxui-design)
  - [6.4.1. Applications Wireframes](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#641-applications-wireframes)
  - [6.4.2. Applications Wireflow Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#642-applications-wireflow-diagrams)
  - [6.4.3. Applications Mock-ups](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#643-applications-mock-ups)
  - [6.4.4. Applications User Flow Diagrams](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#644-applications-user-flow-diagrams)
- [6.5. Applications Prototyping](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#65-applications-prototyping)

## [7.1. Software Configuration Management](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#71-software-configuration-management)
- [7.1.1. Software Development Environment Configuration](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#711-software-development-environment-configuration)
- [7.1.2. Source Code Management](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#712-source-code-management)
- [7.1.3. Source Code Style Guide & Conventions](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#713-source-code-style-guide--conventions)
- [7.1.4. Software Deployment Configuration](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#714-software-deployment-configuration)

## [7.2. Solution Implementation](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#72-solution-implementation)
- [7.2.1. Sprint n](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#721-sprint-n)
  - [7.2.1.1. Sprint Planning 1](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7211-sprint-planning-1)
  - [7.2.1.2. Sprint Backlog 1](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7212-sprint-backlog-1)
  - [7.2.1.3. Development Evidence for Sprint Review](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7213-development-evidence-for-sprint-review)
  - [7.2.1.4. Testing Suite Evidence for Sprint Review](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7214-testing-suite-evidence-for-sprint-review)
  - [7.2.1.5. Execution Evidence for Sprint Review](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7215-execution-evidence-for-sprint-review)
  - [7.2.1.6. Services Documentation Evidence for Sprint Review](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7216-services-documentation-evidence-for-sprint-review)
  - [7.2.1.7. Software Deployment Evidence for Sprint Review](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7217-software-deployment-evidence-for-sprint-review)
  - [7.2.1.8. Team Collaboration Insights during Sprint](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#7218-team-collaboration-insights-during-sprint)

## [7.3. Validation Interviews](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#73-validation-interviews)
- [7.3.1. Diseño de Entrevistas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#731-dise%C3%B1o-de-entrevistas)
- [7.3.2. Registro de Entrevistas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#732-registro-de-entrevistas)
- [7.3.3. Evaluaciones según heurísticas](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#733-evaluaciones-seg%C3%BAn-heur%C3%ADsticas)

## [7.4. Video About-the-Product](https://github.com/Arq-de-Software-Emergentes-Grupo06/Informe-Final/blob/main/Informe-Final-TB1.md#74-video-about-the-product)



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
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | Sandro Alarcón - TB1: Expuso el To Be Scenario Map al equipo, presentando de manera clara las historias de usuario y restricciones iniciales. <br> Paolo Espejo - TB1: Explicó a través de una sesión de Event Storming los flujos de trabajo, detallando las historias de usuario identificadas. <br> Jorge Gonzales - TB1: Comunicó mediante una reunión al equipo de desarrollo propuestas para la arquitectura del software, enfocándose en el diseño estratégico. <br> Fabrizzio Laguerre - TB1: Expuso los resultados del Event Storming, detallando la identificación de los Bounded Contexts y su impacto en la solución. <br> Rodrigo Pozo - TB1: Explicó el proceso Lean UX y los hallazgos del análisis de entrevistas, detallando las implicancias en el diseño de historias de usuario y restricciones. <br> Sandro Alarcón - TP: Expuso propuestas de diseño de aplicaciones web al equipo de manera clara y objetiva. <br> Paolo Espejo - TP: Explicó a través de una sesión de desarrollo, los posibles aggregates, controllers entre otros elementos de diseño de arquitectura al equipo <br> Jorge Gonzales - TP: Comunicó mediante una reunión al equipo de desarrollo propuestas para la arquitectura del software, enfocándose en el diseño estratégico y la realización de propuestas para el diseño móvil de la aplicación. <br> Fabrizzio Laguerre - TP: Expuso los resultados del diseño de wireflows apps y propuestas de diseño de arquitectura <br> Rodrigo Pozo - TP: Explicó el posible diseño de la landing page y su separación entre secciones  <br> Jorge Gonzales - TB2: Explicó los avances en el desarrollo de la aplicación móvil y el progreso en el sprint backlog. <br> Rodrigo Pozo - TB2: Presentó el desarrollo de la aplicación embebida IoT y discutió el registro de entrevistas de validación. <br> Paolo Espejo - TB2: Explicó el desarrollo de la API Web y los resultados de la evaluación de heurísticas. <br> Fabrizzio Laguerre - TB2: Expuso los hallazgos en las entrevistas de validación y presentó el avance del video "About the Product". <br> Sandro Alarcón - TB2: Comunicó el progreso en el desarrollo de la aplicación móvil y el registro de entrevistas de validación. | TB1: Los miembros del equipo demostraron capacidad para comunicar oralmente sus ideas y resultados de manera efectiva, adaptando su lenguaje y nivel de detalle según la audiencia, logrando una comprensión común del proyecto y sus desafíos. TP: los miembros del equipo demostraron capacidad para comunicarse oralmente y exponer sus ideas ante decisiones de diseño de arquitectura y prototipado complejas. <br> TB2: El equipo de desarrollo logró comunicar sus ideas y aportes de manera oral para el desarrollo de las primeras verisones de los productos digitales |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | Sandro Alarcón - TB1: Documentó las historias de usuario y restricciones v.1, asegurando claridad y detalle en los escenarios planteados. <br> Paolo Espejo - TB1: Redactó las descripciones de las historias de usuario y detalló los resultados del Event Storming v.1 en formato escrito. <br> Jorge Gonzales - TB1: Propuso textualmente una lista de alternativas para la arquitectura del software, integrando conceptos de diseño estratégico y resultados de entrevistas. <br> Fabrizzio Laguerre - TB1: Registró en un informe las entrevistas realizadas y detalló el proceso de Event Storming, asegurando que los hallazgos sean entendibles por todos los involucrados. <br> Rodrigo Pozo - TB1: Redactó los resultados del análisis de entrevistas y formalizó el proceso Lean UX, destacando los insights y restricciones identificadas. <br> Sandro Alarcón - TP: Redactó propuestas de versión final para diseño de web apps <br> Paolo Espejo - TP: Elaboró el informe final detallando los aggregates y controllers identificados durante las sesiones de arquitectura.<br> Jorge Gonzales - TP: Escribió un documento con las propuestas de diseño de la arquitectura para la aplicación móvil, detallando alternativas y justificaciones técnicas.<br> Fabrizzio Laguerre - TP: Documentó el análisis de wireflows y la propuesta final de diseño para las aplicaciones web y móviles, explicando su impacto en la solución general.<br> Rodrigo Pozo - TP: Redactó el reporte final del diseño de la landing page, asegurando que las secciones y su estructura sean entendibles para stakeholders no técnicos. <br> Jorge Gonzales - TB2: Documentó el desarrollo de la aplicación móvil y el progreso del sprint backlog. <br> Rodrigo Pozo - TB2: Redactó el reporte del desarrollo de la aplicación embebida IoT y registró las entrevistas de validación. <br> Paolo Espejo - TB2: Redactó el informe de desarrollo de la API Web y la evaluación de heurísticas. <br> Fabrizzio Laguerre - TB2: Documentó el registro de entrevistas y el guion del video "About the Product". <br> Sandro Alarcón - TB2: Escribió el registro de entrevistas de validación y el avance en la aplicación móvil. | TB1: El equipo logró comunicar de manera escrita sus ideas y resultados de forma objetiva y comprensible, permitiendo que personas de diferentes especialidades comprendieran los avances y propuestas del proyecto. TP: El equipo logró comunicar de manera escrita sus ideas y resultados de forma clara y objetiva, adaptando la terminología y el nivel de detalle según la audiencia, contribuyendo a una comprensión común del progreso y decisiones del proyecto. TB2: El equipo de desarrollo logró comunicar sus ideas y aportes de manera escrita para el desarrollo de las primeras verisones de los productos digitales |


# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

El startup que se introduce en el presente informe recibe como nombre “CuriDev”. Actualmente conformado por un conjunto de estudiantes de la Universidad Peruana de Ciencias Aplicadas, con la ambición de querer ayudar a la sociedad con nuestra grán pasión a la tecnología e informática, creamos esta startup tomando como objetivo asegurar la integridad y mejorar los procesos de trabajo de las empresas de transporte de productos peligrosos.

Como misión se plantea “Incrementar la calidad del servicio de transporte de combustibles con eficiencia, seguridad y transparencia entre conductores y empresas”. Asimismo, la visión de la startup plantea desarrollar la solución IoT más reconocida en el Perú para asegurar la integridad de los transportes de productos peligrosos.

### 1.1.2. Perfiles de integrantes del equipo

Mi nombre es Jorge Enrique Gonzales Carrión tengo 19 años de edad y curso el octavo ciclo de la carrera Ingeniería de Software. Me considero una persona con sentido de responsabilidad y la suficiente capacidad de trabajar en equipo aportando ideas innovadoras. Además, en cualidades me considero asertivo y colaborativo, puntos que pueden mejorar el proceso de elaboración de los distintos trabajos del curso. Finalmente, poseo conocimientos de programación que brindaron los ciclos anteriores al presente.

![Captura de pantalla 2024-09-06 144610](https://github.com/user-attachments/assets/b5b2784a-20bf-4713-bb72-0fb6a0d0d1e3)

---

Mi nombre es Fabrizzio Hernán Laguerre Challco, tengo 19 años, desde pequeño siempre he sentido un interés por aprender a usar ciertos dispositivos siendo uno de estos los más útiles que tenemos en la actualidad, las computadoras, por ello me esforzado en practicar y aprender ciertas habilidades en ofimática, edición de videos, programación y en aprender inglés, habilidades que puedo ofrecer para contribuir al grupo.

![1689649934031](https://github.com/user-attachments/assets/5ceaee27-7da3-4863-9518-4910ba33e5f5)


---

Mi nombre es Paolo Andre Espejo Macuri, tengo 20 años de edad, estoy cursando el sexto ciclo de la carrera de Ingeniería de Software en la UPC. Soy hábil con las TICs y soy una persona creativa para proporcionar ideas innovadoras. Aprendo de forma rápida nuevos temas al practicarlos y se me da bien la programación y la solución de errores.

![Captura de pantalla 2024-09-06 144650](https://github.com/user-attachments/assets/af7177ed-5125-4721-b19e-4c1c48f97030)


---

Mi nombre es Rodrigo Pozo Campos, soy una persona responsable y que trata de mantener todo losentregables en orden. Tengo conocimientos endistintos frameworks tanto para el frontendcomo para el backend. Creo que puedo ser degran ayudar para nuestro grupo y de estamanera poder realizar un buen producto.

![365285357-ec8735da-0684-4c9d-9aae-8d337837177e](https://github.com/user-attachments/assets/efa706b0-b122-403d-bc66-b4aceeb0c594)


---

Mi nombre es Sandro Alarcón, me considero un miemrbo clave para el equipo debido a mis conocimientos y compromiso. Poseo capacidad para enfrentar desafíos y su disposición para colaborar en el backend y frontend

![116916774](https://github.com/user-attachments/assets/c1f90e8a-2b89-487e-a49a-089e40ff8be7)


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

Los productos/servicios existentes no abordan adecuadamente el problema crítico de la detección temprana de fugas de gases combustibles (GNV) durante su transporte, lo que pone en riesgo tanto la seguridad de los conductores como la reputación de las empresas.

Nuestra solución abordará esta brecha proporcionando un sistema de monitoreo en tiempo real que, a través de sensores, detectará rápidamente cualquier fuga de gas antes de que alcance la cabina del conductor y se convierta en una amenaza.

Nos enfocaremos inicialmente en empresas de transporte de gases combustibles que necesiten mejorar sus medidas de seguridad y reducir riesgos operativos.

Sabremos que hemos tenido éxito cuando observemos una reducción significativa en los incidentes relacionados con fugas de gas, junto con una mejora en la percepción de seguridad por parte de los conductores y las empresas involucradas.
 

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

**Segmento objetivo: Transportistas**

***Primera Entrevista:***

Nombres y apellidos: Jean Pierre Morin

Edad: 20

Inicio: 14:39

Fin: 25:55

Duración: 11:16

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista1t](https://github.com/user-attachments/assets/5e605c66-95f7-4179-8a19-0af2427b68c6)

Resumen:
- Hemos entrevistado a Jean Pierre de 20 años de edad, lleva trabajando 2 años dentro de su empresa y radica en Lima, que tuvo experienca de primera mano con una fuga de gas, sus principales inconvenientes son los factores externos tales como tráfico, problemas de conectividad y problemas con la carretera. Principalmente utiliza un GPS y un walkie-talkie durante su desempeño laboral. Busca recibir notificaciones a través de una aplicación movil.

***Segunda Entrevista:***

Nombres y apellidos: Ian Perez

Edad: 25

Inicio: 25:55

Fin: 31:34

Duración: 05:39

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista2t](https://github.com/user-attachments/assets/fadb0fcb-c20a-44fd-b714-401c9a28501f)

- Hemos entrevistado a Ian Perez de 25 años de edad y vive en Ate Vitarte. Aunque no ha enfrentado incidentes graves, tuvo una experiencia cercana con una fuga de gas menor, en la que reaccionó de acuerdo con los protocolos de seguridad. Entre sus principales frustraciones están la incertidumbre sobre el estado de la carga y la falta de comunicación eficiente en algunas rutas. Actualmente, usa un sistema básico de rastreo GPS que le ofrece algunas ventajas, pero señala que no proporciona suficiente información sobre la seguridad de la carga. Está dispuesto a utilizar una solución tecnológica de monitoreo en tiempo real para mejorar la seguridad, siempre que sea fácil de usar y no represente una distracción. Considera esenciales los sensores de nivel de líquidos, presión y gases para monitorear combustibles, y prefiere recibir notificaciones a través de una pantalla en el vehículo o mediante una aplicación móvil. Utiliza principalmente el GPS y su teléfono móvil durante su jornada de trabajo.



***Tercera Entrevista:***

Nombres y apellidos: Luis Cornejo

Edad: 25

Inicio: 31:34

Fin: 39:17

Duración: 07:43

![Captura de pantalla 2024-09-06 171745](https://github.com/user-attachments/assets/6570a2ce-794a-41f8-870c-1fa46d93ea19)


Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

- Hemos entrevistado a Luis Cornejo de 25 años de edad y vive en San Borja. Nos cuenta que tienemedidas de seguridad como extintores, un sistema de detección de fugas y equipo de comunicación para reportar problemas. Aunque no ha enfrentado incidentes graves, tuvo una fuga menor que gestionó siguiendo los protocolos de seguridad. Entre sus principales frustraciones están la incertidumbre sobre el estado de la carga y la falta de comunicación eficiente en rutas complicadas. Actualmente, solo usa un sistema básico de rastreo que no le brinda información detallada sobre la seguridad de la carga. Está interesado en adoptar una solución tecnológica de monitoreo en tiempo real, especialmente con sensores de nivel de líquidos, presión y gases, para mejorar la prevención de fugas y peligros.



**Segmento objetivo: Empresas de transporte de productos peligrosos**

***Primera Entrevista:***

Nombre: Paolo Checa

Inicio: 0:00

Fin: 4:30

Duración: 4:30

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista2e](https://github.com/user-attachments/assets/a8db29a9-6d0b-473a-992b-9c071af4750c)

- Hemos entrevistado a Paolo Checa, quien explicó que actualmente cuentan solo con un sistema de GPS para monitorear los vehículos, y un seguro de vida para los transportistas, sin medidas específicas adicionales para su protección. La capacitación se limita a recomendaciones básicas como evitar exponer la carga a fuego o movimientos bruscos, y prefieren contratar transportistas experimentados. Aparte del GPS y los teléfonos proporcionados por la empresa, no disponen de otras tecnologías para la seguridad de las cargas.


***Segunda Entrevista:***

Nombre: Lissane Mareni

Inicio: 4:30

Fin: 8:48

Duración: 4:18

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista3e](https://github.com/user-attachments/assets/8c7c6c22-70f1-4775-9212-80a7b8fb3c28)

- Hemos entrevistado a Lisanne, quien mencionó que actualmente solo cuentan con un sistema de GPS para rastrear los vehículos y proporcionan un seguro de vida a los transportistas, pero no implementan medidas adicionales específicas para protegerlos. La capacitación que se ofrece es básica, enfocándose en evitar que la carga esté expuesta a fuentes de calor o movimientos bruscos, y se prefiere contratar conductores con experiencia. Además del GPS y los teléfonos entregados por la empresa, no utilizan tecnologías adicionales para garantizar la seguridad de las cargas.
  


***Tercera Entrevista:***

Nombre: Jose Luis Castillo

Inicio: 8:48

Fin: 14:38

Duración: 5:50

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EVhL7w8-vyZKl68ljP0MwdYB7jwPNv07LyALip-7_Lmg2w?e=sL9c5x&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista1e](https://github.com/user-attachments/assets/ade12b09-87c0-4c4e-8ddb-7cf14e5a830c)

- Hemos entrevistado Jose Luis Castillo de 22 años de edad que vive en Santiago de Surco, quien mencionó que implementan protocolos rigurosos para garantizar la seguridad de los transportistas y la carga, como la señalización adecuada, límites de velocidad, rutas seguras y revisiones periódicas de los vehículos. La capacitación de los transportistas incluye entrenamiento regular en el manejo de materiales peligrosos, procedimientos de emergencia y el uso de equipos de protección personal.



### 2.2.3. Análisis de entrevistas

- En las entrevistas realizadas a conductores y representantes de empresas de transporte de productos peligrosos, se pueden identificar varios temas recurrentes que destacan la importancia de la seguridad, el monitoreo en tiempo real y la adopción de nuevas tecnologías como soluciones IoT. A continuación, se presentan los principales puntos de análisis:

- Las empresas dependen demasiado de la experiencia de los conductores y las medidas reactivas, como el uso de extintores o comunicación básica. Hay una oportunidad de mejorar los protocolos de seguridad mediante capacitaciones más detalladas y el uso de tecnología avanzada para la prevención de incidentes.
  
- El uso de tecnologías avanzadas como sensores de gas, temperatura y presión es limitado, lo que representa una debilidad. Las empresas y conductores podrían beneficiarse enormemente de soluciones IoT que ofrezcan un monitoreo en tiempo real, brindando mayor visibilidad sobre la seguridad de la carga durante el transporte.
  
- El interés en las soluciones IoT es fuerte debido a los beneficios que pueden ofrecer, como la mejora de la seguridad, la optimización de las operaciones y el cumplimiento de las normativas de seguridad. Este interés sugiere que existe una clara oportunidad para implementar tecnologías que puedan proporcionar estas capacidades de monitoreo avanzado.
  
- Aunque el interés en las soluciones IoT es alto, existen barreras para su adopción, principalmente relacionadas con la inversión económica y la posibilidad de fallos en zonas con poca conectividad. Las empresas tecnológicas que ofrezcan estas soluciones deben enfocarse en asegurar la confiabilidad y la facilidad de uso para mitigar estas preocupaciones.
  
- La demanda por notificaciones en tiempo real es clara, y cualquier solución IoT que se implemente debe incluir un sistema de alertas que no interfiera con las tareas diarias de los conductores, pero que brinde información oportuna y precisa en el momento correcto.
  
- La adopción de tecnologías emergentes puede posicionar a las empresas de transporte como líderes en seguridad dentro del sector. Aquellas que adopten estas soluciones de manera temprana no solo mejorarán sus operaciones, sino que también podrían atraer a más clientes al garantizar un servicio más seguro y confiable.

- En conclusión, Las entrevistas revelan una clara necesidad de mejorar los protocolos de seguridad y adoptar tecnologías avanzadas, como soluciones IoT para el monitoreo en tiempo real. Existe un fuerte interés en estas soluciones debido a los beneficios que ofrecen en términos de seguridad y eficiencia operativa, pero las preocupaciones sobre la confiabilidad y los costos de implementación deben abordarse. Las empresas que logren implementar con éxito estas tecnologías tendrán una ventaja competitiva en el mercado y podrán mejorar significativamente la seguridad de sus operaciones.


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

•	Dashboard (Panel de control): Un panel de control es un componente de la interfaz de usuario que proporciona una visión general de la información relevante y las acciones disponibles para el usuario, como la gestión de eventos para los organizadores o la configuración de la cuenta para los asistentes.

•	Confirmation (Confirmación): Una confirmación es un reconocimiento o notificación proporcionada a los usuarios después de completar una solicitud o registro de incidente.

•	Event Listing (Listado de eventos): Un listado de eventos es una colección o pantalla de eventos disponibles para que los usuarios los examinen y seleccionen.

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
![image](https://github.com/user-attachments/assets/c5d9bbff-01ac-4111-8638-5a62cc7b1e40)

![image](https://github.com/user-attachments/assets/8027d267-90bf-4513-8589-bc8096e62f76)

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

![image](https://github.com/user-attachments/assets/579455f2-88ac-4f21-a78d-ba428afc5caa)

![image](https://github.com/user-attachments/assets/0e275f07-8f13-4e0d-9d7c-184bdbfd0aca)


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

En el desarrollo de la plataforma de transporte de productos peligrosos, es fundamental tener en cuenta ciertas restricciones que no pueden ser negociadas y que son impuestas tanto por los clientes como por los propios requisitos del negocio. Estas restricciones son necesarias para garantizar la seguridad, el cumplimiento de las normas legales y la eficiencia del sistema. 

A continuación, se presentan los principales constraints a considerar en el desarrollo de la solución, los cuales guiarán las decisiones de diseño, implementación, y despliegue de la plataforma.

| **Technical Story ID** | **Título**                                         | **Descripción**                                                                                                                                               | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** |
|------------------------|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| TSC01                   | Cumplimiento con Normativas de Transporte          | La plataforma debe cumplir con todas las normativas locales e internacionales para el transporte de productos peligrosos, incluidas las certificaciones necesarias para los transportistas.            | **Escenario 1: Verificación de Cumplimiento Normativo**. Dado que se está registrando un transportista, cuando proporciona la información requerida, entonces el sistema valida que todas las certificaciones y permisos cumplan con las normativas establecidas por la ley.                              | EP01                         |
| TSC02                   | Seguridad y Privacidad de los Datos                 | La plataforma debe asegurar la privacidad y seguridad de los datos sensibles de los transportistas y las empresas, siguiendo los estándares de protección de datos, como GDPR y CCPA.                  | **Escenario 1: Almacenamiento Seguro de Datos**. Dado que un usuario registra información en la plataforma, cuando la información es enviada, entonces los datos deben ser encriptados y almacenados de acuerdo con los estándares de seguridad especificados (e.g., AES-256).                             | EP01                         |
| TSC03                   | Alta Disponibilidad del Sistema                     | La plataforma debe garantizar una alta disponibilidad (99.9%) para que las empresas y transportistas puedan acceder a las funcionalidades críticas en cualquier momento.                               | **Escenario 1: Redundancia de Sistema**. Dado que un servicio esencial esté inactivo, cuando el sistema detecta la falla, entonces se debe activar un sistema de respaldo automáticamente para garantizar la continuidad del servicio sin afectar a los usuarios.                                          | EP03                         |
| TSC04                   | Integración con Sistemas de Terceros                | La plataforma debe integrarse con sistemas de terceros, como proveedores de seguros, servicios de monitoreo de vehículos, y APIs de mapas, para ofrecer una funcionalidad completa y eficiente.        | **Escenario 1: Integración con API de Mapas**. Dado que el sistema requiere la planificación de rutas, cuando un usuario planifica un viaje, entonces el sistema debe integrarse con un API de mapas de terceros para mostrar las rutas más seguras y eficientes.                                            | EP02                         |
| TSC05                   | Escalabilidad para Manejar el Crecimiento del Negocio| La plataforma debe ser escalable para manejar un aumento en la cantidad de transportistas y empresas que se registran, así como el volumen de solicitudes de transporte y transacciones diarias.       | **Escenario 1: Aumento de Carga de Usuarios**. Dado que hay un aumento en el número de usuarios concurrentes, cuando la carga alcanza un umbral crítico, entonces el sistema debe escalar automáticamente los recursos (e.g., servidores, bases de datos) para mantener el rendimiento óptimo.                | EP03                         |
| TSC06                   | Validación de Identidad de Usuarios                 | La plataforma debe incluir un sistema de validación de identidad para todos los usuarios (transportistas y empresas) para evitar fraudes y mantener la integridad del servicio.                       | **Escenario 1: Autenticación de Usuario**. Dado que un nuevo usuario intenta registrarse, cuando se ingresan los datos y documentos de identidad, entonces el sistema debe validar la autenticidad de estos documentos antes de activar la cuenta del usuario.                                                | EP01                         |
| TSC07                   | Trazabilidad de Incidentes                          | La plataforma debe permitir la trazabilidad de todos los incidentes reportados durante los transportes para una gestión efectiva y la mejora continua de los procesos.                               | **Escenario 1: Registro de Incidentes**. Dado que un incidente ocurre durante un transporte, cuando el transportista o empresa lo reporta, entonces el sistema debe registrar todos los detalles relevantes del incidente para su análisis posterior.                                                          | EP03                         |



### 4.1.3. Architectural Drivers Backlog

| Driver ID | Título de Driver          | Descripción              | Importancia para Stakeholders (High, Medium, Low) | Impacto en Architecture Technical Complexity (High, Medium, Low) |
|-----------|---------------------------|--------------------------|---------------------------------------------------|---------------------------------------------------------------|
|      QS-1    |              Availability             |          Garantizar la disponibilidad del software en todo, en especifico los procesos de monitoreo y registro de incidentes. Garantizando un sistema operable y comprometido en cumplir la misión del usuario               |                 High                                  |                            High                                   |
|      QS-2    |              Usability             |          Facilitar la experiencia de usuario es de suma importancia dado que el transportista necesita visualizar las notifiaciones visualmente clara y rapida, asimismo los reportes y formularios deben tener opción de "cancelar". De esta manera se garantiza una experiencia de  usuario completa acorde con el dominio del negocio               |                 High                                  |                            Medium                                   |
|      QS-3    |              Security            |          Garantizar la seguridad de los datos personales              |                 High                                  |                            High                                   |
|      TSC01    |              Cumplimiento con Normativas de Transporte           |          Garantizar el cumplmiento de estandarez de seguridad acorde al país establecido          |                 High                                  |                            High                                   |
|      TSC02    |              Seguridad y Privacidad de los Datos               |         Se debe seguir los estándares de protección de datos, como GDPR y CCPA.        |                 High                                  |                            High                                   |
| TSC03                   | Alta Disponibilidad del Sistema                     | La plataforma debe garantizar una alta disponibilidad (99.9%) para que las empresas y transportistas puedan acceder a las funcionalidades críticas en cualquier momento.                               |                 High                                  |                            Medium                                |
| TSC04                   | Integración con Sistemas de Terceros                | La plataforma debe integrarse con sistemas de terceros, como proveedores de seguros, servicios de monitoreo de vehículos, y APIs de mapas, para ofrecer una funcionalidad completa y eficiente.        |         High                                  |                            Medium                                |
| TSC05                   | Escalabilidad para Manejar el Crecimiento del Negocio                   |  La plataforma debe ser escalable para manejar un aumento en la cantidad de transportistas y empresas que se registran, así como el volumen de solicitudes de transporte y transacciones diarias.        |         High                                  |                            Medium                                |
| TSC06                   | Validación de Identidad de Usuarios                 | La plataforma debe incluir un sistema de validación de identidad para todos los usuarios (transportistas y empresas) para evitar fraudes y mantener la integridad del servicio.                       | 
| TSC07                   | Trazabilidad de Incidentes                          | La plataforma debe permitir la trazabilidad de todos los incidentes reportados durante los transportes para una gestión efectiva y la mejora continua de los procesos.                               |  High                                  |                            Medium                                |

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

![whatesigma](https://github.com/user-attachments/assets/05749b3f-3869-41d2-882f-27f4aaa67c64)

### 4.2.4. Bounded Context Canvases

-**IAM**
![boundediam](https://github.com/user-attachments/assets/145f3968-f66e-4eae-a37e-67867137b619)

-**MANAGEMENT**
![boundedmanage](https://github.com/user-attachments/assets/44a6fc1d-0319-4151-9415-d2779d365840)

-**RECORDS**
![boundedrecor](https://github.com/user-attachments/assets/f192d683-5dbd-4c57-8a0f-50ffbf7e5199)

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

![image](https://github.com/user-attachments/assets/c2919b47-a4ec-4995-8677-6ea207f04029)


### 4.3.2. Software Architecture Context Level Diagrams

![image](https://github.com/user-attachments/assets/b0a73a76-60b2-4ca8-90b5-b1d30959cf41)



### 4.3.3. Software Architecture Container Level Diagrams

![image](https://github.com/user-attachments/assets/78fbd047-7632-49c4-9a42-4c9d2458946f)




### 4.3.4. Software Architecture Deployment Diagrams

![image](https://github.com/user-attachments/assets/09fe9c0e-a68f-43fa-811c-fc093ee347bf)


# Capítulo V: Tactical-Level Software Design

## 5.1. Bounded Context: IAM

Descripción: El contexto de IAM (Gestión de Identidad y Acceso) se encarga de la autenticación, autorización y administración de roles de los usuarios dentro del sistema. Proporciona un control centralizado para la creación, modificación, y eliminación de usuarios, además de gestionar los permisos y las políticas de acceso a los distintos servicios y datos dentro de la plataforma.

### 5.1.1. Domain Layer

<table>
    <tr>
        <td colspan="4" align="center">Aggregate</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>User</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Representación de los usuarios del segmento objetivo</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>Long</td>
        <td>Private</td>
        <td>Identificador unico</td>
    </tr>
    <tr>
        <td>userName</td>
        <td>String</td>
        <td>Private</td>
        <td>Nombre de usuario</td>
    </tr>
     <tr>
        <td>email</td>
        <td>String</td>
        <td>Private</td>
        <td>Correo electronico</td>
    </tr>
     <tr>
        <td>password</td>
        <td>String</td>
        <td>Private</td>
        <td>Contraseña del usuario</td>
    </tr>
     <tr>
        <td>role</td>
        <td>String</td>
        <td>Private</td>
        <td>rol del usuario</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>getUsername</td>
        <td>username</td>
        <td>Public</td>
        <td>Obtención de nombre de usuario</td>
    </tr>
    <tr>
        <td>getEmail</td>
        <td>email</td>
        <td>Public</td>
        <td>Obtención de correo electrónico</td>
    </tr>
    <tr>
        <td>getPassword</td>
        <td>password</td>
        <td>Public</td>
        <td>Obtención de contraseña</td>
    </tr>
     <tr>
        <td>getRoles</td>
        <td>srtRoles</td>
        <td>Public</td>
        <td>Obtención del rol del usuario</td>
    </tr>
</table>

### 5.1.2. Interface Layer

<table>
    <tr>
        <td colspan="4" align="center">Controller</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>AuthController</td>
        <td>Controller</td>
        <td colspan="2">Controlador para autenticación</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>authService</td>
        <td>AuthService</td>
        <td>Private</td>
        <td>Servicio de autenticación</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>authenticateUser</td>
        <td>authenticatedResource</td>
        <td>Public</td>
        <td>Metodo para autenticar usuario</td>
    </tr>
    <tr>
        <td>registerUser</td>
        <td>signInResource</td>
        <td>Public</td>
        <td>Metodo de registro de usuario</td>
    </tr>
</table>

<table>
    <tr>
        <td colspan="4" align="center">Controller</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>UsersController</td>
        <td>Controller</td>
        <td colspan="2">Controlador para usuarios</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>userQueryService</td>
        <td>UserQueryService</td>
        <td>Private</td>
        <td>Servicio de consultas de usuario</td>
    </tr>
    <tr>
        <td>userCommandService</td>
        <td>UserCommandService</td>
        <td>Private</td>
        <td>Servicio de registro de usuario</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>getAllUsers</td>
        <td>usersResource</td>
        <td>Public</td>
        <td>Metodo para obtener todos los usuarios/td>
    </tr>
    <tr>
        <td>getUserById</td>
        <td>userResource</td>
        <td>Public</td>
        <td>Metodo para obtener un usuario por id</td>
    </tr>
</table>


### 5.1.3. Application Layer

<table>
    <tr>
        <td colspan="4" align="center">Service</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>UserCommandService</td>
        <td>Service</td>
        <td colspan="2">Servicio con reglas de negocio para usuario</td>
    </tr>
    <tr>
        <td>UserQueryService</td>
        <td>Service</td>
        <td colspan="2">Servicio con reglas de negocio para usuario</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>UserRepository</td>
        <td>Long</td>
        <td>private</td>
        <td>Repositorio de usuario</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>existByUsername</td>
        <td>user</td>
        <td>Public</td>
        <td>Metodo para validar usuario por nombre de usuario</td>
    </tr>
    <tr>
        <td>findByUsername</td>
        <td>user</td>
        <td>Public</td>
        <td>Metodo para obtener usuario por nombre de usuario</td>
    </tr>
</table>


### 5.1.4. Infrastructure Layer


<table>
    <tr>
        <td colspan="4" align="center">Repository</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>UserRepository</td>
        <td>Repository</td>
        <td colspan="2">Repositorio que guarda la información de los usuario</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>existsByUsername</td>
        <td>user</td>
        <td>Public</td>
        <td>Metodo para validar usuario por nombre de usuario</td>
    </tr>
    <tr>
        <td>findByUsername</td>
        <td>user</td>
        <td>Public</td>
        <td>Metodo para buscar usuario por nombre de usuario</td>
    </tr>
</table>

### 5.1.5 Bounded Context Software Architecture Component Level Diagrams

![image](https://github.com/user-attachments/assets/1706f69f-e7cd-48f5-9803-a96f1a0d59b8)


### 5.1.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.1.6.1. Bounded Context Domain Layer Class Diagrams

![image](https://github.com/user-attachments/assets/756ee8f2-a2c0-4d8b-95d1-69b36efe7740)


#### 5.1.6.2. Bounded Context Database Design Diagram

![image](https://github.com/user-attachments/assets/666e0d91-610b-4b67-bdf8-bb1e61c41a33)


## 5.2. Bounded Context: MANAGEMENT

Descripción: El contexto de Notificación gestiona los procesos relacionados con la creación, envío y seguimiento de notificaciones sobre incidentes o eventos relevantes que deben ser reportados a los transportistas, operadores o supervisores del sistema. Este contexto facilita la comunicación en tiempo real, proporcionando alertas y actualizaciones del estado de los incidentes.

### 5.2.1. Domain Layer

<table>
    <tr>
        <td colspan="4" align="center">Aggregate</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Transporte</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Gestionar los servicios de transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>Long</td>
        <td>Private</td>
        <td>Identificador unico</td>
    </tr>
     <tr>
        <td>formTransport</td>
        <td>String</td>
        <td>Private</td>
        <td>Información del formulario</td>
    </tr>
     <tr>
        <td>serviceStatus</td>
        <td>String</td>
        <td>Private</td>
        <td>Estado del servicio</td>
    </tr>
     <tr>
        <td>routes</td>
        <td>String</td>
        <td>Private</td>
        <td>	Ruta asignada para el transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>acceptService</td>
        <td>void</td>
        <td>Public</td>
        <td>Método para aceptar el servicio</td>
    </tr>
    <tr>
        <td>getRoute</td>
        <td>String</td>
        <td>Public</td>
        <td>Obtener la ruta segura asignada</td>
    </tr>
</table>

### 5.2.2. Interface Layer

<table>
    <tr>
        <td colspan="4" align="center">Controller</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>TransportController</td>
        <td>Controller</td>
        <td colspan="2">Controlar la gestión del transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>transportService</td>
        <td>TransportService</td>
        <td>Private</td>
        <td>Servicio para gestión del transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>createTransport</td>
        <td>void</td>
        <td>Public</td>
        <td>Crear nuevo servicio de transporte</td>
    </tr>
    <tr>
        <td>getTransportById</td>
        <td>Transport</td>
        <td>Public</td>
        <td>Obtener servicio de transporte por id</td>
    </tr>
</table>


### 5.2.3. Application Layer

<table>
    <tr>
        <td colspan="4" align="center">Service</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>TransportService</td>
        <td>Service</td>
        <td colspan="2">	Servicio para gestionar reglas de negocio del transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>transportRepository</td>
        <td>TransportRepository</td>
        <td>private</td>
        <td>Repositorio de transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>addTransport</td>
        <td>void</td>
        <td>Public</td>
        <td>Registrar un nuevo servicio</td>
    </tr>
    <tr>
        <td>findTransport</td>
        <td>bool</td>
        <td>Public</td>
        <td>Validar datos del transporte</td>
    </tr>
</table>


### 5.2.4. Infrastructure Layer


<table>
    <tr>
        <td colspan="4" align="center">Repository</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>TransportRepository</td>
        <td>Repository</td>
        <td colspan="2">Almacenar datos de transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>findById</td>
        <td>Transport</td>
        <td>Public</td>
        <td>Buscar transporte por ID</td>
    </tr>
</table>

### 5.2.5 Bounded Context Software Architecture Component Level Diagrams

![image](https://github.com/user-attachments/assets/8ca7eb70-a86e-404d-ab35-728b2d409ff0)


### 5.2.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.2.6.1. Bounded Context Domain Layer Class Diagrams

![image](https://github.com/user-attachments/assets/c761b97d-bb67-41b9-850b-3bb3b343b9b2)



#### 5.2.6.2. Bounded Context Database Design Diagram

![image](https://github.com/user-attachments/assets/c49df029-5113-471d-9c1a-d3205afe9ef0)


## 5.3. Bounded Context: RECORDS

Descripción: El contexto de Management está diseñado para supervisar y administrar los servicios de transporte y carga. Este contexto permite el seguimiento y la gestión de los recursos, la planificación de rutas, y la actualización de registros relacionados con los servicios en curso, así como la toma de decisiones operativas basadas en el estado actual del transporte y la carga.

### 5.3.1. Domain Layer

<table>
    <tr>
        <td colspan="4" align="center">Aggregate</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>IncidentNotification</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Gestiona los incidentes</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>Long</td>
        <td>Private</td>
        <td>Identificador unico</td>
    </tr>
     <tr>
        <td>incidentRegistrado</td>
        <td>Bool</td>
        <td>Private</td>
        <td>Si el incidente ha sido registrado</td>
    </tr>
     <tr>
        <td>serviceStatus</td>
        <td>String</td>
        <td>Private</td>
        <td>Estado del servicio</td>
    </tr>
     <tr>
        <td>transportNotificaton</td>
        <td>Bool</td>
        <td>Private</td>
        <td>	Si el transportista ha sido notificado</td>
    </tr>
     <tr>
        <td>indicentDetails</td>
        <td>String</td>
        <td>Private</td>
        <td>	Si el transportista ha sido notificado</td>
    </tr>
     <tr>
        <td>reportUpdate</td>
        <td>Bool</td>
        <td>Private</td>
        <td>Indica si el reporte fue actualizado</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>addIncident</td>
        <td>void</td>
        <td>Public</td>
        <td>Envía una notificación al transportista</td>
    </tr>
    <tr>
        <td>notificationTransport</td>
        <td>void</td>
        <td>Public</td>
        <td>Envía una notificación al transportista</td>
    </tr>
    <tr>
        <td>updateReport</td>
        <td>void</td>
        <td>Public</td>
        <td>Actualiza el reporte del incidente</td>
    </tr>
    <tr>
        <td>isUpdate</td>
        <td>Bool</td>
        <td>Public</td>
        <td>Verifica si el reporte fue actualizado</td>
    </tr>
</table>

### 5.3.2. Interface Layer

<table>
    <tr>
        <td colspan="4" align="center">Controller</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>IncidentsController</td>
        <td>Controller</td>
        <td colspan="2">Controlar la gestión del transporte</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>notificationService</td>
        <td>NotificationService</td>
        <td>Private</td>
        <td>Servicio para gestionar las notificaciones</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>sendNotification</td>
        <td>void</td>
        <td>Public</td>
        <td>	Envía notificación de incidente a transportista</td>
    </tr>
    <tr>
        <td>getNotificationById</td>
        <td>notification</td>
        <td>Public</td>
        <td>Obtener notificación de incidente por ID</td>
    </tr>
    <tr>
        <td>addIncident</td>
        <td>void</td>
        <td>Public</td>
        <td>Registra un nuevo incidente</td>
    </tr>

</table>


### 5.3.3. Application Layer

<table>
    <tr>
        <td colspan="4" align="center">Service</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>IncidentService</td>
        <td>Service</td>
        <td colspan="2">	Servicio para gestionar reglas de negocio de los incidentes</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Atributos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>notificationRepository</td>
        <td>NotificationRepository</td>
        <td>private</td>
        <td>Repositorio de notificaciones</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>addNotification</td>
        <td>void</td>
        <td>Public</td>
        <td>Registrar una nueva notificación</td>
    </tr>
    <tr>
        <td>findNotification</td>
        <td>bool</td>
        <td>Public</td>
        <td>Validar los datos de la notificación</td>
    </tr>
</table>


### 5.3.4. Infrastructure Layer


<table>
    <tr>
        <td colspan="4" align="center">Repository</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>IncidentRepository</td>
        <td>Repository</td>
        <td colspan="2">Almacenar datos de incidentes</td>
    </tr>
    <tr>
        <td colspan="4" align="center">Métodos</td>
    </tr>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>findById</td>
        <td>Transport</td>
        <td>Public</td>
        <td>Buscar transporte por ID</td>
    </tr>
    <tr>
        <td>save</td>
        <td>void</td>
        <td>Public</td>
        <td>Guardar una nueva notificación</td>
    </tr>
    <tr>
        <td>update</td>
        <td>void</td>
        <td>Public</td>
        <td>Actualizar los datos de una notificación</td>
    </tr>
</table>

### 5.3.5 Bounded Context Software Architecture Component Level Diagrams

![image](https://github.com/user-attachments/assets/5deba9be-fbe4-431d-90a9-8ab879ff6221)


### 5.3.6 Bounded Context Software Architecture Code Level Diagrams
#### 5.3.6.1. Bounded Context Domain Layer Class Diagrams

![image](https://github.com/user-attachments/assets/5ad524c5-8b65-41de-af10-ad17fbf42884)



#### 5.3.6.2. Bounded Context Database Design Diagram

![image](https://github.com/user-attachments/assets/d318cce8-35bc-42c3-9a38-35745f961429)


# Capítulo VI: Solution UX Design
## 6.1 Style Guidelines

Mediante la solución IoT SafeFlow se busca que los usuarios gocen de una interfaz que transmite formalidad, profesionalismo y lo más minimalista posible que transmita una sensación de facil uso ante el monitoreo de la carga y su rapida respuesta frente a posibles accidentes. Por ello, el equipo tomó la decisión de emplear recursos visuales que capten la atención de los segmentos objetivos y que sean fáciles de identificar. Como estrategia se utilizaron colores llamativos, con comibnaciones resaltantes, junto con fuentes tipográficas con diferentes tamaños y espaciados ligeramente amplios, con el propósito de generar placer visual y lograr que el texto sea más visible. Cabe destacar que no se emplearán texturas, pues se busca mantener un aspecto minimalista.

**Brand Overview**

La solución IOT SafeFlow, surge a partir de la necesidad de mejorar la seguridad de los transportistas de productos peligrosos y aumentar la calidad del servicio de las empresas de estos mismos. Debido a ello, se propuso desarrollar una solución completa incluyendo IOT, que facilitará el monitoreo atiempo real de la carga de combustible, entre otras funciones con el fin de atender las necesidades previamente mencionadas.

El branding detrás de SafeFlow se fortalece aún más al comunicar un mensaje claro y directo: proteger el flujo de transporte en entornos críticos, mejorando tanto la calidad del servicio como la seguridad operacional, lo que refuerza la reputación de las empresas que lo adoptan. En resumen, SafeFlow no es solo un sistema, es una promesa de seguridad y eficiencia en un sector donde estos elementos son clave para el éxito.

**Brand Name**

El nombre SafeFlow encapsula de manera precisa y potente la misión central de la solución IOT: asegurar un flujo seguro en el transporte de combustibles peligrosos. Al unir las palabras "Safe" (seguridad) y "Flow" (flujo), el nombre comunica inmediatamente dos aspectos críticos: la prioridad por mantener altos estándares de seguridad y la importancia del movimiento continuo y controlado de las cargas.

La elección del nombre SafeFlow no solo resalta el compromiso con la seguridad, sino que también refleja la eficiencia y la confianza que las empresas y transportistas pueden esperar al integrar este sistema en sus operaciones. SafeFlow se convierte así en un sinónimo de protección para quienes manejan cargas peligrosas y para el entorno en el que operan, generando tranquilidad tanto para el operador como para el cliente final.

![image](https://github.com/user-attachments/assets/44cd783b-487f-4b18-a427-d0d142cf0c7f)

**Colores**:

Colores primarios: La paleta de colores mostrada va desde tonos claros hasta oscuros, todos en la gama de amarillos y naranjas. Comienza con los tonos más suaves, como el #FFF8BC (Claro V3) y el #FFF0A2 (Claro), que evocan luz y calidez con su suavidad. Avanza hacia un amarillo más intenso y brillante con #FFE589 (Claro V2) y #FFDF6F (Regular), que transmiten energía y vitalidad. Luego, los tonos naranjas empiezan a tomar protagonismo con #FCB658 (Regular V1) y #FFAC3C (Oscuro), que aportan una sensación de dinamismo y audacia. Finalmente, el tono más oscuro, #E09735 (Oscuro V2), ofrece una sensación más terrosa y sólida, cerrando la progresión con un color más profundo y fuerte.

![image](https://github.com/user-attachments/assets/8080af10-fc8b-463d-b746-7c8045670664)


Colores secundarios: La paleta de colores presentada, que abarca desde tonos claros hasta oscuros, refleja una identidad visual de seguridad, confiabilidad y profesionalismo, clave para SafeFlow. Los tonos claros evocan transparencia y confianza, mientras que los medios sugieren responsabilidad y conexión con el entorno. Los tonos oscuros, por su parte, aportan una sensación de fuerza y protección, elementos esenciales en una solución IOT que monitorea la carga peligrosa. Esta combinación equilibra accesibilidad y autoridad, proyectando una imagen robusta y seria, ideal para transmitir la misión de SafeFlow.

![image](https://github.com/user-attachments/assets/228bb94b-5e0b-4898-a060-2cb1114b3cb3)


Colores adicionales: Como colores adicionales se seleccionaron blanco, negro y dos tonalidades diferentes de rojo. Estos serán empleados dentro de la tipografía, botones y mensajes de la aplicación. El blanco también será empleado para algunos fondos que requieran que la visibilidad del texto resalte con mayor ímpetu.

![image](https://github.com/user-attachments/assets/bc5ea6a4-e539-42be-8313-798507e1c7bb)

**Tipografia:**

El equipo seleccionó la fuente de letra Archivo, un estilo tradicional y fácil de leer. La separación del interletraje es de 0,15 px, el interlineado es de 0,5 px y el tamaño de la fuente varía dependiendo de la finalidad de uso, por ejemplo, para los títulos se opta por un tamaño de 56 px, y para el texto redactado por el usuario 27 px. 

![Tipografia](https://github.com/JorgeGonzales15/SW51-GreatMinds-OpenSource/assets/104078975/2e9abaf9-db14-4c7f-b000-2a60df98a8c6)

Tono de comunicación y lenguaje aplicado
El tipo de lenguaje a emplear será serio y formal junto con entusiasmo y serenidad. Dado que se agregarán mejoras y pasos que captarán la atención del usuario. Asimismo, se agregaron elementos para perfeccionar la interfaz y diseño final para los clientes.


### 6.1.2 Web, Mobile and IoT Style Guidelines

Con respecto a la página web, está diseñada para mostrarse en el dispositivo que se esté usando, ya sea desde una computadora o dispositivo móvil (responsive), el sitio web estará disponible en ambas plataformas para proporcionar una mejor experiencia de usuario. Además, el patrón de diseño web usado es Flat Design, para que el usuario tenga una alta comprensión y una fácil interacción al momento de estar en la interfaz. 

Se utilizará el patrón Z:

![image](https://github.com/user-attachments/assets/0b4b3e9c-c055-4da0-b4b9-c4da4d384186)

Asimismo, se tienen contemplados los siguientes puntos relacionados a responsive web interfaces:

- Grid System: Generalmente un sistema de 12 columnas para permitir que la interfaz se adapte a diferentes tamaños de pantalla.
- Breakpoints: Definir puntos de quiebre (breakpoints) para adaptarse a pantallas pequeñas (móviles), medianas (tabletas) y grandes (escritorios). Ejemplos comunes son 320px, 768px y 1200px.
- Escalado en tipografía: Asegurarse de que el texto sea legible tanto en pantallas grandes como pequeñas. Por ejemplo, un tamaño mínimo de 16px para móviles.
- Consistencia en la paleta de colores: Usar una paleta de colores uniforme con variaciones para estados interactivos (hover, focus, active).
- Botones y Links: Tienen que ser lo suficientemente grandes para interactuar en pantallas táctiles (mínimo 44px de altura).
- Iconografía: Uso de iconos universales y reconocibles para navegación y acciones.

Con respecto a las interfaces de la aplicación móvil, se contemplan los siguientes puntos:

- Single Column: Ideal para aplicaciones de lectura de contenido (blogs, redes sociales), formularios simples, y listas de artículos o productos.
- Bottom Navigation: La barra de navegación principal se coloca en la parte inferior de la pantalla, donde es más fácil de alcanzar con el pulgar, especialmente en dispositivos móviles más grandes.
- Overlays: Utiliza capas superpuestas para mostrar información adicional sin cambiar de pantalla. Por ejemplo, ventanas emergentes que muestran más detalles o permiten realizar acciones rápidas.
- Floating Action Button: Un botón flotante que suele ubicarse en la esquina inferior derecha y proporciona acceso a la acción principal de la aplicación.

No se contemplan diseños de interfaz para la IoT embedded app debido a que la solución IOT no lo implica.

## 6.2 Information Architecture

En la presente sección, se establecerá la estructura de la solución IOT según cada segmento objetivo. Del mismo modo, los distintos elementos que se emplearán en la navegación dentro de las aplicaciones.

### 6.2.1 Organization Systems

En este punto se indicarán los grupos de información en los cuales se aplicarán los tipos de estructuración visual, además, se indicará para qué segmento objetivo está diseñado y qué tipo de categorización se utilizará.

**Segmento: Transportistas de productos peligrosos**

- **Jerárquica:**
  - **Monitoreo en tiempo real:** El transportista podrá visualizar de manera jerárquica la información sobre las condiciones de seguridad (sensores de detección de fugas de gas, temperatura, presión, etc.), organizada por niveles de prioridad.
  
- **Secuencial:**
  - **Atención de alertas inmediatas:** El transportista seguirá un proceso secuencial en el manejo de alertas, comenzando desde la recepción de la alerta, verificación de la condición peligrosa, hasta la toma de decisiones como la activación de protocolos de emergencia.
  
- **Matricial:**
  - **Registro histórico de datos de seguridad:** El transportista podrá acceder a una visualización matricial del historial de los eventos de seguridad del vehículo. La información se dispondrá por fecha, tipo de evento y gravedad, lo que facilitará el análisis cruzado de los datos.

**Segmento: Empresas de transporte de productos peligrosos**

- **Jerárquica:**
  - **Integración con sistemas de gestión de flota:** Las empresas podrán gestionar la seguridad de su flota de forma jerárquica, priorizando alertas de mayor relevancia, desde la visión global de la flota hasta el detalle de cada vehículo.
  
- **Secuencial:**
  - **Mejora continua en protocolos de seguridad:** Las empresas podrán revisar y ajustar sus protocolos de seguridad de forma secuencial, basándose en los datos obtenidos del registro histórico, siguiendo pasos como análisis, identificación de fallas y ajuste de medidas preventivas.

**Funcionalidades ofrecidas para ambos segmentos:**

- **Jerárquica:**
  - **Landing Page:** En esta sección se presentará información relevante sobre el sistema de monitoreo de seguridad para productos peligrosos, organizada en categorías que van desde las características principales hasta los detalles técnicos.
  
- **Matricial:**
  - **Menú de opciones:** Tanto transportistas como empresas de transporte tendrán un menú de funcionalidades, como monitoreo en tiempo real, alertas y registro histórico, organizadas sin un orden específico pero accesibles según las necesidades del usuario.

Las funcionalidades contempladas permiten monitorear en tiempo real, recibir alertas inmediatas, analizar datos históricos y gestionar flotas de transporte de manera más eficiente y segura.

6.2.2 Labeling Systems

A continuación, el equipo mostrará el sistema de etiquetado que otorgará una descripción breve y clara de la información brindada por la Landing Page.

Encabezados de la Landing Page:

- **Inicio/Home:** Sección preseleccionada por defecto que brindará una frase representativa y el logo de la aplicación, además de una idea principal del objetivo de esta.
  
- **Sobre nosotros/About Us:** Sección donde el cliente obtiene información acerca del equipo de desarrollo, será capaz de visualizar nuestra misión, visión, quiénes somos y qué hacemos.

- **Services/Funcionalidades:** Sección dividida para cada segmento objetivo, donde se mostrarán las funcionalidades que otorga la aplicación para ellos.

- **Contáctanos/Contact Us:** Sección donde se muestran nuestros canales de comunicación.

---

A continuación, el equipo mostrará el sistema de etiquetado que otorgará una descripción breve y clara de las funcionalidades brindadas por la aplicación web.

Encabezados para Transportistas:

- **Inicio/Home:** Página principal personalizada para transportistas.

- **Mis viajes:** Sección donde el transportista podrá gestionar y ver el estado de sus viajes en curso o programados.

- **Registro de incidentes:** Permite al transportista registrar cualquier incidente ocurrido durante un viaje, proporcionando detalles clave para una resolución rápida.

- **Historial:** Sección que almacena un historial detallado de todos los viajes realizados, incluyendo los incidentes reportados y su resolución.

---

Encabezados para Empresas:

- **Inicio/Home:** Página principal personalizada para empresas.

- **Incidentes publicados:** Sección donde la empresa puede visualizar y gestionar los incidentes que han sido reportados por los transportistas.

- **Reportes:** Permite generar y ver reportes detallados sobre los viajes, incidentes, y la seguridad de la flota.

- **Monitoreo de viajes:** Ofrece una visión en tiempo real del estado de los viajes que están en curso, con indicadores de seguridad y alertas.



### 6.2.3 SEO Tags and Meta Tags

En esta sección, se presentarán las etiquetas que identificarán y diferenciarán al sitio web de los demás en internet. Gracias a ellas, se podrá encontrar a SafeFlow en los diversos buscadores.

Para el sitio web estático:

- **Title:** SafeFlow
- **Description:** SafeFlow - CuriDev Oficial Landing Page
- **Keywords:** hazardous transport, safety monitoring, incident management, transport security
- **Authors:** CuriDev team

Para la aplicación web:

- **Title:** SafeFlow
- **Description:** SafeFlow - CuriDev Oficial Web Page
- **Keywords:** hazardous transport, safety monitoring, incident management, transport security, fleet management
- **Authors:** CuriDev team

Para la aplicación móvil:

- **Title:** SafeFlow
- **Description:** SafeFlow - CuriDev Oficial Mobile App
- **Keywords:** hazardous transport, safety monitoring, incident management, transport security, fleet management
- **Authors:** CuriDev team


### 6.2.4 Searching Systems

En esta sección se presentarán los sistemas de búsqueda que se implementarán en la aplicación web, móvil y landing page. Al hacer uso de estos sistemas, los usuarios podrán encontrar la información que requieran.

En el sitio web estático:
Los usuarios podrán utilizar la barra de navegación para buscar información acerca del producto solución de SafeFlow. De manera interactiva, se utilizará un botón que alternará entre “Para transportistas” y “Para empresas”, permitiendo a los usuarios acceder rápidamente a las funcionalidades diseñadas para cada segmento.

En la aplicación web y móvil:

Segmento: Transportistas de productos peligrosos

- **Mis viajes:**  
  Esta sección permitirá al transportista realizar el seguimiento de sus viajes en curso o programados. El sistema de búsqueda incluirá un filtro que permitirá buscar viajes según origen, destino o fecha. Adicionalmente, podrá visualizar incidentes registrados durante los viajes o alertas de seguridad.

- **Registro de incidentes:**  
  En esta sección, los transportistas podrán registrar y gestionar incidentes ocurridos durante los viajes. El sistema de búsqueda permitirá filtrar incidentes según fecha, tipo de incidente, o nivel de gravedad. Los transportistas también podrán visualizar incidentes resueltos o en proceso de revisión.

Segmento: Empresas de transporte de productos peligrosos

- **Monitoreo de viajes:**  
  Las empresas podrán realizar el seguimiento de todos los viajes de su flota. Se habilitará un sistema de búsqueda y filtro por vehículo, conductor, fecha o estado del viaje (en curso, finalizado, en alerta). Esto permitirá a las empresas gestionar mejor la seguridad de sus operaciones.

- **Incidentes publicados:**  
  En esta sección, las empresas podrán visualizar y gestionar los incidentes reportados por los transportistas. El sistema de búsqueda contará con filtros por fecha, tipo de incidente, y estado (resuelto o en revisión), lo que facilitará la gestión y análisis de los problemas ocurridos en la flota.

#### Funcionalidades compartidas para ambos segmentos:

- **Reportes y análisis:**  
  Tanto transportistas como empresas podrán acceder a un sistema de búsqueda para generar reportes. Podrán buscar reportes históricos según la fecha, tipo de incidente, viajes completados, y datos de monitoreo. Esto permitirá generar reportes personalizados para análisis de seguridad y optimización de protocolos.


### 6.2.5 Navigation Systems

A continuación, el equipo mostrará los sistemas de navegación con los que contará SafeFlow para permitir a los usuarios navegar de manera rápida y segura a cualquier bloque de información.

En la Landing Page:
Se contará con encabezados que representarán las diversas secciones presentes. Estos encabezados estarán ubicados en la parte superior de la página en un menú horizontal que siempre estará visible mientras se navega por la página, ya sea al bajar o subir. Para evitar que el usuario tenga que desplazarse manualmente por toda la página, podrá utilizar estos encabezados para dirigirse directamente a la sección deseada. El visitante deberá leer el título de cada encabezado para asegurarse de que se está ubicando en la sección correcta. Este sistema permitirá una navegación rápida, fácil e intuitiva.

En la aplicación web:
El sistema de navegación será similar al de la Landing Page, con un menú principal que permitirá a los usuarios trasladarse a diferentes páginas del sitio web. Las opciones de este menú variarán de acuerdo con el segmento objetivo al que pertenezca el usuario (transportista o empresa). Además, se presentarán listados organizados para distintos grupos de elementos, como viajes, incidentes o reportes. Dentro de estos listados, los usuarios podrán aplicar filtros para navegar entre las opciones de manera más eficiente y personalizada.

En la aplicación móvil:
La navegación en la aplicación móvil tendrá un **scroll limitado**, mostrando carruseles de opciones en la sección **Home**, como viajes recientes o alertas activas. Además, se utilizará un **bottom navigation bar** (barra de navegación inferior) para facilitar la navegación entre las principales secciones de la aplicación, como "Mis viajes", "Alertas", o "Reportes". Las opciones en esta barra variarán según el tipo de usuario (transportista o empresa), ofreciendo un acceso rápido a las funcionalidades más relevantes para cada segmento.


## 6.3 Landing Page UI Design
### 6.3.1 Landing Page Wireframe
En la etapa de diseño de la interfaz de usuario (UI) de la página de destino (landing page), uno de los primeros pasos cruciales es la creación del "Landing Page Wireframe". Este wireframe actúa como el esqueleto inicial de la página, proporcionando una representación estructural y funcional de los elementos clave que compondrán la interfaz final. En este caso presentamos las secciones: Navbar (dentro de Hero), Hero, Services, About, Testimonials, Download y Footer.

Link: https://www.figma.com/design/tItLy7WiwLwugLfArdOF5R/Arquitectura-de-Software?node-id=0-1&t=zAsUH4WkDUedpPmn-1

Hero:

![image](https://github.com/user-attachments/assets/b86cb4e5-0a37-41e1-9899-d56269a77566)


Services:

![image](https://github.com/user-attachments/assets/64ddb97e-8939-4c16-9f5c-eb31112450e1)


About us:

![image](https://github.com/user-attachments/assets/b17a32cc-2342-4798-a5e4-ebf266daa709)


Testimonials:

![image](https://github.com/user-attachments/assets/de1e37a9-10a0-4b8a-92bc-cd3f20469074)


Download:

![image](https://github.com/user-attachments/assets/fdbced71-0f47-4428-9ca1-ca2ec049e67f)


Footer:
![image](https://github.com/user-attachments/assets/c9150348-3670-4bbc-90ec-a85a0721c088)



### 6.3.2 Landing Page Mock-up

 En la fase de diseño de la interfaz de usuario de la página de destino (landing page), el siguiente paso fundamental es la creación del "Landing Page Mock-up". Este mock-up representa la materialización visual de nuestra página, brindando una vista detallada y práctica de cómo se verá y funcionará la interfaz final.


 NavBar y Hero:

![image](https://github.com/user-attachments/assets/1ae0b12e-71bc-4464-9db2-8b57541b79fc)



 Services:

![image](https://github.com/user-attachments/assets/0b70ce28-c01d-43d2-9b2f-5b4e5691ba1e)


 about us:

![image](https://github.com/user-attachments/assets/454d4010-55d2-4d4a-ad41-0c9c5512c8b0)



 Testimonials:

![image](https://github.com/user-attachments/assets/ffd0c5dc-e962-4b56-8e50-48ecfb8ef81f)


 Download:
 
![image](https://github.com/user-attachments/assets/5621d1c3-8f58-4c2c-a3de-e2107989074c)


 Footer:

![image](https://github.com/user-attachments/assets/4cb1b613-c998-4887-9bf4-9ff81e885c63)





## 6.4 Applications UI/UX Design
### 6.4.1 Applications Wireframes


Wireframes Web aplication:

![image](https://github.com/user-attachments/assets/63586d6f-474e-4be2-995d-d8ce52c983a5)
![image](https://github.com/user-attachments/assets/b372a7fd-b32c-4e32-8b8b-968252b67af4)


Wireframes Mobile:

![image](https://github.com/user-attachments/assets/1d66d831-2319-4cc4-9eb5-27a1d815defa)


### 6.4.2 Applications Wireflow Diagrams

Wireflow Diagrams Web application:
![Diagrams Web application(1)](https://github.com/user-attachments/assets/247e9d16-d64b-4b43-b615-f825825ce5e2)
![Diagrams Web application(2)](https://github.com/user-attachments/assets/70015937-9912-43b6-964f-ebbd3af8b0ad)

Wireflow Diagrams Mobile:
![Diagrams Mobile(1)](https://github.com/user-attachments/assets/32d32887-4bf2-4046-afe9-f0f13df479e8)
![Diagrams Mobile(2)](https://github.com/user-attachments/assets/f7cc7fdd-1ce6-4511-9f4a-d18d5b30554d)


### 6.4.3 Applications Mock-ups


Web aplication Mock-up

![image](https://github.com/user-attachments/assets/0a7ee345-addd-4bd4-bc46-5ab80e65ccf6)
![image](https://github.com/user-attachments/assets/1f98dff1-01da-4dba-bde4-8967abe6aabd)


Mobile Mock-ups:

![image](https://github.com/user-attachments/assets/019c4b88-3751-4595-94a8-8636f14859ff)


### 6.4.4 Applications User Flow Diagrams

En esta sección, se presentaran los User Flows, donde se mostrarán las rutas Happy y Unhappy que los usuarios pueden tener al momento de usar la aplicación web. Se utilizó la herramienta LucidChart.

User Goal: Registrar usuarios

Task Flow:

- Primero el usuario debe estar en la pantalla Sign In
- Luego, si quiere crear un nuevo usuario va a la pantalla Sign Up
- Si quiere crear cuenta como transportista va a la pantalla Sign Up
- Dependendiendo de su tipo de cuenta se le redirige a la sección Home correspondiente

![image](https://github.com/user-attachments/assets/06aba8c5-a4ae-4277-a6b7-fb94f1f46a6e)

---

User Goal: Ver servicios disponibles como transportista

Task Flow: 

- Si el transportista está interesado en aceptar una entrega
- Entra a la sección de "Solicitation"
- Y se visualiza los servicios
  
![image](https://github.com/user-attachments/assets/3cee9eec-d2f0-46c2-8176-637203eb26f3)

---

User Goal: Publicar servicios como administrador

Task Flow:

- Si el usuario autenticado como adminsitrador se encunetra en la sección
- Entonces se le muestra un formulario para publicar un servicio
- Si es aceptado, entonces es mostrado en la interfaz de los transportistas
  
![image](https://github.com/user-attachments/assets/d3c1cb58-d4c9-4b7f-afbf-c732a86e46df)

User Goal: Visualizar perfil de transportista

Task Flow:

- Si el administrador desea verificar el perfil del transporista
- Al aceptar un envío, el administradorpuede ver el perfil
- Si es así, entonces se le muestra el perfil a detalle

![image](https://github.com/user-attachments/assets/c433cf19-edcb-47d0-9c0f-30363472bd22)


Enlace para acceder a LucidChart: (https://lucid.app/lucidchart/0b82c162-acc6-49cb-9450-d24843d59da7/edit?viewport_loc=60%2C352%2C5142%2C2330%2C0_0&invitationId=inv_8d44bcea-0ce3-4f21-a988-d58f3d99dfae)

## 6.5 Appilcations Prototyping

En esta sección, se puede acceder al prototipo en la herramienta Figma. Asismismo se pueden evidenciar los principios de arquitectura de información, esto hace que la aplicación se vea lo más eficiente posible.

Principio de elección: Procuramos que la aplicación web Y MOVIL posea una cantidad de secciones a todo momento, por lo que se cuenta con la barra superior siempre en la aplicación con 4 secciones, los cuales podrá acceder a las funcionalidades rapidamente desde cualquier pantalla.

Principio de divulgación: La información presentada se separa por partes, de tal manera que el usuario encuentre lo que desee. Esto se evidencia en los detalles al seleccionar un cultivo.

Video Exposición:

![image](https://github.com/user-attachments/assets/889ea49c-1a85-4414-9619-adcb29f53c04)

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EYwhwGkv7p1Ch4gSwp711G4BK8TA4xMN8AA3GrA22SXcWw?e=Xgdvon&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![image](https://github.com/user-attachments/assets/55afc192-dcc2-46ed-8123-ccc241182fd9)
![image](https://github.com/user-attachments/assets/4a25eb97-9828-49aa-a82c-c764484cf5fe)

# Capítulo VI: Solution UX Design
## 7.1. Software Configuration Management


### 7.1.1. Software Development Environment Configuration

Utilizaremos principalmente como IDEs: Visual Studio Code o WebStorm, cada una con su configuración debida para no causar conflictos con carpetas personalizadas de cada IDE. Más adelante se hará uso de IntelliJ IDEA para la implementación de las Web APIs.

Como herramientas de desarrollo se hará uso de la última versión disponible de Node.js. Para el frontend, se usará el framework web Angular versión 13. El cual se instalará mediante nvm en su versión de Windows. Como framework de diseño se usará Angular Material UI. Finalmente, para el backend, se utilizará el lenguaje de programación de Java.

Como IDE de desarrollo para la aplicación móvil, se usará Visual Studio junto con un emulador y el SDK de Flutter más reciente, esto nos permite desarrollar con una amplia gamma de extensiones para facilitar la codificación y todas las opciones que brinda flutter en sus componentes.

Como herramientas SaSS, se usará GitHub como herramienta para colaboración de código. También usaremos Trello para la elaboración de los Product Backlog. Vertabelo, para la elaboración del diagrama de base de datos. Codegram, para la elaboración del diagrama de clases y LucidChart, para diagramas adicionales.

Como herramienta de desarrollo para el Embedded IOT Application se usará el simulador Wokwim, con el lenguaje de programación C++.

Para el desarrollo del landing page, se decidió con el equipo usar HTML, JS y CSS. Para llevarlo a cabo se eligieron diversas herramientas tecnológicas de las cuales el equipo ya está acostumbrado y tienen un cierto dominio. Estas herramientos son las siguientes:

Visual Studio Code: Es un editor de código gratuito, moderno y potente gracias a que cuenta con varias funciones y extensiones para trabajar con cualquier lenguaje de programación. Además es bastante conocida por todos los integrantes del equipo y debido a ello se decidió trabajar con Visual Studio Code. Para la instalación del programa, se puede conseguir desde su página web oficial: una vez descargado se puede proceder con la instalación de forma rápida y fácil.

Git y Github: Se usaron estas herramientas por la razón de que hoy en día es un estándar usar Git para el control de versiones de software y se eligió GitHub por ser la plataforma más popular y fácil de usar para crear y manejar repositorios, tener funciones para ver cambios, commits, pull request, entre otros. El enlace de descarga del instalador de GitHub Desktop es

Live Server: Finalmente, para acelerar el desarrollo del landing page, se usó esta extensión que sirve para visualizar los cambios inmediatamente después de alguna modificación en el código así se evita estar recargando la página, lo cual es un ahorro de tiempo y comodidad al desarrollar.

Discord: Aunque originalmente se diseñó como una plataforma de comunicación para gamers, Discord también se utiliza para diseñar y crear comunidades en línea y mejorar la experiencia de usuario a través de la comunicación y colaboración en grupos.

WhatsApp: WhatsApp es una aplicación de mensajería instantánea que se utiliza para la comunicación en tiempo real. Aunque no es una herramienta de gestión de proyectos, se puede usar para mantenerse en contacto con miembros del equipo y colaborar en cierta medida.

Zoom: Zoom es una plataforma de comunicación que ofrece videoconferencias y reuniones en línea. Aunque se utiliza principalmente para comunicarse y realizar reuniones virtuales, también puede ser útil para la gestión de proyectos remotos y la colaboración en tiempo real.

Requirements Management:

Miro: Miro es una plataforma de pizarra en línea que se utiliza para colaborar en la ideación, planificación y diseño de proyectos. Es especialmente útil para la colaboración visual, como la creación de mapas mentales, diagramas y prototipos.

Google Docs: Google Docs es una suite de aplicaciones de procesamiento de texto, hojas de cálculo y presentaciones en línea. Aunque no es específicamente una herramienta de gestión de requisitos, se puede utilizar para documentar y colaborar en la definición y seguimiento de requisitos de proyectos.

Product UX/UI Design:

Figma: Figma es una herramienta de diseño de interfaz de usuario (UI) y experiencia de usuario (UX) basada en la nube. Se utiliza para crear prototipos interactivos, diseños de aplicaciones y colaboración en tiempo real en proyectos de diseño.

UXPressia: UXPressia es una herramienta especializada en la creación de mapas de experiencia de usuario, perfiles de clientes y otros elementos relacionados con el diseño de UX. Ayuda a visualizar y comprender la experiencia del usuario en un producto o servicio.

LucidChart: es una herramienta para crear diagramas de clases, flujo y entre otros, de manera facil e intuitiva. Nos va a servir para hacer los user flows y el diagrama de clases para el proyecto.

Software Development:

Visual Studio Code: Visual Studio Code es un editor de código fuente altamente configurable y ampliable. Se utiliza principalmente para la codificación, depuración y desarrollo de software en varios lenguajes de programación.

Git: Git es un sistema de control de versiones distribuido. Aunque no es un programa en sí mismo, es una tecnología esencial para el desarrollo de software y se usa para rastrear cambios en el código fuente y facilitar la colaboración entre programadores.

Software Documentation:

GitHub: GitHub es una plataforma de desarrollo colaborativo que utiliza el sistema de control de versiones Git. Se utiliza para alojar, revisar y colaborar en proyectos de desarrollo de software, lo que facilita la colaboración entre desarrolladores.

Software Testing:

Lenguaje Gherkin: El lenguaje Gherkin es un lenguaje de dominio específico utilizado para escribir pruebas de aceptación en un formato legible por humanos. Se utiliza junto con herramientas de prueba de comportamiento, como Cucumber, para automatizar pruebas funcionales.


### 7.1.2. Source Code Management

Como mencionamos anteriormente, se utilizará GitHub para llevar un control de las versiones de desarrollo y poder trabajar de forma colaborativa. Para ello, se creó una organización llamada:

Repositorio de Landing Page: https://github.com/Arq-de-Software-Emergentes-Grupo06/Landing-Page

Repositorio de pruebas de aceptación: https://github.com/Arq-de-Software-Emergentes-Grupo06/acceptance-test

Repositorio Mobile App: https://github.com/Arq-de-Software-Emergentes-Grupo06/fastflow_mobileapp

Repositorio Embedded App IoT: https://github.com/Arq-de-Software-Emergentes-Grupo06/Wokwi-Simulacion

### 7.1.3. Source Code Style Guide & Conventions

A continuación, se darán a conocer las convenciones, formatos, estilos y entre otras propiedades de los lenguajes trabajados en la presente solución las cuales son: HTML, JavaScript/TypeScript, CSS:

HTML: Se hará uso de la guía “HTML Style Guide and Coding” de la página W3Schools, la cual menciona las convenciones y estándares de este lenguaje de etiquetas. Hemos considerado las siguientes como las más importantes:

Declarar siempre el tipo documento: Es decir, colocar siempre la etiqueta en la primera línea del código.

Utilizar el nombre de las etiquetas y sus atributos en minúscula: Por un tema de estética y orden del código para que este se vea más limpio y sea más fácil de escribir.

Cerrar todas las etiquetas: Esto evita futuros problemas o errores de sintaxis.

Siempre coloca comillas para los valores de los atributos de las etiquetas: De esta forma los valores son más fáciles de leer y se deben utilizar obligatoriamente si este contiene espacios.

Especificar siempre los atributos alt, width y height para las imágenes: Es importante en caso de que la imagen no se pueda mostrar por algún motivo y también ayuda con el tema de la accesibilidad de los usuarios.

No omitir la etiqueta ni los metadatos: Estas etiquetas son importantes para la optimización de motores de búsqueda (SEO).

CSS: Se siguió la guía “Google HTML/CSS Style Guide” donde se indican las convenciones, reglas y buenas prácticas para este lenguaje. Hemos considerado las siguientes recomendaciones como las más destacadas:

Nombre de clases: Se recomienda usar nombres generales para las clases, no deben ser específicas por la razón de que deben comportarse como padres.

Usar nombres de clase cortos: Se recomienda utilizar nombres de clase que sean cortos y descriptivos, para transmitir la idea de lo que representa de manera concisa.

Usar delimitadores de nombres de clase adecuados: Se debe de separar las palabras en los nombres de clase con solo guiones.

Evitar los selectores de ID: No se recomienda implementar este tipo de selectores, por la razón de que estos deben ser únicos en toda la página y en proyectos grandes que tengan muchos componentes es difícil de garantizar esa unicidad, es preferible usar selectores de clase.

Usar propiedades abreviadas: Es muy recomendable usar propiedades que soporten ser declarados de forma abreviada (por ejemplo, la propiedad padding, margin, border, etc.) por la razón de que reduce de forma significativa la cantidad de líneas de código, y es más legible para el programador o diseñador.

JavaScript: Se consideró importante seguir una guía de buenas prácticas para un mejor desarrollo del código, para este caso se eligió la guía de la wiki “JavaScript best practices“ del World Wide Web (W3C). Lo cual se destaca lo siguiente:

Usar nombres cortos y fáciles de leer: Es recomendable nombrar adecuadamente las variables, clases, funciones y otros elementos para que sea más sencillo de leer y comprender.

Evitar el uso de variables globales (keyword “var”): No se recomienda el uso de este tipo de variables en un proyecto, porque pueden generar muchos errores a medida que el proyecto crece y estas pueden sobrescribirse fácilmente afectando el valor y se pueden declarar otros elementos como funciones con el mismo nombre de la variable y generar errores.

Comentar y documentar lo necesario: Se recomienda comentar líneas de código que son complejos de entender a simple vista explicando o dejando mensajes para que otros programadores lo entiendan.

Usar notaciones sencillas de entender: Javascript cuenta con diversas notaciones y operadores para crear o modificar ciertas estructuras de datos como objetos, arrays, selectivas, etc.

Gherkin: Se consideró conveniente usar la guía y convenciones que se mencionan en “Gherkin Conventions for Readable Specifications” para una correcta realización de las pruebas. A continuación, se mencionan los puntos que consideramos más importantes para nuestro trabajo:

Los bloques “Give-When-Then” deben ser diferenciados: Se recomienda usar una correcta indentación de esos bloques para identificar mejor las secciones de la prueba y también añadiendo la keyword “And” para añadir otra línea en los pasos y otro bloque.

Usar tablas para los pasos: Si uno de los pasos requiere de más información es recomendable usar tablas para organizar dicha información y tenga un aspecto más ordenado.

Usar comillas simples para los parámetros: Se recomienda esta práctica para una mejor legibilidad de los parámetros en un paso y tener una sintaxis más simple.

Separar los escenarios con comentarios: Si se da el caso de tener muchos escenarios en una prueba, es usar los comentarios como separadores para que visualmente sea más organizado, fácil de leer y distinguir mejor.

En resumen, las convenciones o estilos de programación, se seguirá la guía de estilos de Google para programar en HTML (Google HTML), CSS (CSS Style Guide) y JavaScript (JS) en el caso de la landing page. En el caso de la implementación del frontend, se utilizará Angular Framework utilizando HTML5, CSS3 y JavaScript para aspectos estáticos de templates y TypeScript como lenguaje de programación.

Para el almacenamiento y control de versiones de código se utilizará GIT gestionado desde GitHub aplicando GitFlow Workflow, Conventional Commits y Semantic Versioning. Además, todos los hotfixes se realizan en ella, para así poder tener los arreglos desplegados de forma automática.

El lenguaje de diseño de Landing Page y Web Applications estará basado en Material Design. Como biblioteca de componentes de UI se utilizará Angular Material.

Para el desarrollo de Web Services, se realizará bajo RESTful API architectural style y se hará uso de Spring Boot Framework, utilizando Java como lenguaje de Programación.

Para el desarrollo de Mobile App, se hará uso de Flutter/Dart como lenguaje y se utilizará el mismo Web Service anteriormente mencionado.

### 7.1.4. Software Deployment Configuration

Para el despliegue de la landing page y la aplicación web, se usará netlify, donde se seguirán los siguientes pasos:

Primero se debe iniciar sesión en Netlify con una cuenta de Github, luego ir a "Sites" donde se ubica el siguiente botón:

![image](https://github.com/user-attachments/assets/627ccab8-2b59-4d70-a682-697ddbdc32f6)

Luego, se debe seleccionar la organización del proyecto en Github, y seleccionar el repositorio deseado:

Para la landing page, al ser un sitio estático, no es necesario configurar rutas para acceder al proyecto, por ende solo es necesario darle al botón de "Deploy"

![image](https://github.com/user-attachments/assets/da55e807-ebaa-4f47-9537-dd43092cefa6)

De esta manera se la plataforma se encarga del build y en pocos minutos estaría desplegada la Landing Page y la aplicación web.

## 7.2. Solution Implementation
### 7.2.1. Sprint 1
#### 7.2.1.1. Sprint Planning 1

| Sprint # | 1 | 
| - | - | 
| **Sprint Planning Background** | - |
| Date | 2024 - 09 - 10 |
| Time | 19:00 PM |
| Location | Virtual via Google Meet |
| Prepared By | Gonzales Carrión, Jorge Enrique |
| Attendees (to planning meeting) | Gonzales Carrión, Jorge Enrique / Espejo Macuri, Paolo Andre / Alarcon Rondon. Sandro Fourfive / Laguerre Chalco, Fabrizzio Hernan / Pozo Campos, Rodrigo Jair |
| Sprint 1 - Review Summary | No aplica (Es el primer Sprint) |
| Sprint 1 - Retrospective Summary  | No aplica (Es el primer Sprint) |
| **Sprint Goal & User Stories** | - |
| Sprint 1 Goal| Nuestro objetivo es brindar infomraicón pertinente en las secciones de la landing apge acerca de la solución IoT y visualizar los viajes o servicios de transporte de combustible en la aplicación móvil. <br> Creemos que esto genera una base sólida acerca de las funcionalidades de FastFlow para los visitantes y permitir a los transportistas visualziar sus viajes. Esto será confirmado cuando los visitantes se suscriban a las aplicaciones.   |
| Sprint 1 - Velocity | El equipo puede aceptar 28 Story Points|
| Sprint 1 - Story Points | La suma de los Story Points de los User Sotires que se atenderá es 18|

#### 7.2.1.2. Sprint Backlog 1

<table><tr><th valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 1</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Description</td><td valign="top">Estimation (Hours)</td><td valign="top">Assigned To</td><td valign="top"><p>Status </p><p>(To-do / </p><p>InProcess / </p><p>To Review / </p><p>Done)</p></td></tr>
<tr><td rowspan="2" valign="top">US16</td><td rowspan="2" valign="top">Sección Hero y Botón Call-to-Action</td><td valign="top">16.1</td><td valign="top">Implementar vistas con estilos</td><td valign="top">Realizar las secciones de hero y calltoaction</td><td valign="top">4</td><td valign="top">Jorge Gonzales</td><td valign="top">Done</td></tr>
<tr><td valign="top">16.2</td><td valign="top">Implementar sección responsive </td><td valign="top">Realizar las secciones con proporciones responsive</td><td valign="top">2</td><td valign="top">Laguerre Chalco, Fabrizzio Hernan</td><td valign="top">Done</td></tr>

<tr><td rowspan="1" valign="top"> US14</td><td rowspan="1" valign="top">Landing Page responsive</td><td valign="top">12.1</td><td valign="top">Implementar vistas responsive</td><td valign="top">Realizar los estilos de las secciones responsive</td><td valign="top">4</td><td valign="top">Alarcon Rondon. Sandro Fourfive</td><td valign="top">Done</td></tr>


<tr><td rowspan="1" valign="top">US15</td><td rowspan="1" valign="top"> 	Visualización de características de la aplicación web o móvil web en Landing Page</td><td valign="top">15.1</td><td valign="top">Implementar sección de funcionalidades y beneficios</td><td valign="top">Realizar la sección con los estilos e iconografía correspondiente</td><td valign="top">2</td><td valign="top">Gonzales Carrión, Jorge Enrique</td><td valign="top">Done</td></tr>

<tr><td rowspan="1" valign="top"> 	US12</td><td rowspan="1" valign="top">Publicación de Solicitudes de Transporte de Productos Peligrosos</td><td valign="top">12.1</td><td valign="top">Implementar sección propuesta</td><td valign="top">Realizar la sección con los estilos e iconografía correspondiente</td><td valign="top">2</td><td valign="top">Pozo Campos, Rodrigo Jair</td><td valign="top">Done</td></tr>

<tr><td valign="top"> 	US06</td><td valign="top"> 	Seguimiento en Tiempo Real de los Transportes Activos</td><td valign="top">16.1</td><td valign="top">Implementar sección en la aplicación movil</td><td valign="top">Realizar los estilos de la sección para empresarios </td><td valign="top">2</td><td valign="top">Pozo Campos, Rodrigo Jair</td><td valign="top">Done</td></tr>

</table>

Como herramienta de control para este Sprint se usó Trello con un board exclusivo para esta iteración:

![imagen](https://github.com/user-attachments/assets/4530452c-8947-412a-9e51-43d16987e4fc)

Link: https://trello.com/invite/b/6723b55cb861b5f50c919ad1/ATTIbe94b7237c6fb5c7b24da3ef2b093337A2994F8F/safeflow-sprint-1

#### 7.2.1.3. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| Wokwi-Simulacion | gas-sensor-version-1 | 3eca40b | feat: added files  | - | 30/10/2024 |
| Wokwi-Simulacion | temp-sensor-version-1 | 1519a1a| feat: added files temp sensor  | - | 30/10/2024 |
| Landing-Page  | EN | af2f987 | add landing page  | - | 23/09/2024 |
| Landing-Page  | ES | 0a1226c | add landing page ES  | - | 23/09/2024 |
| safeflow_mobileapp | feature/crop-detail | 13fa79a | fix: sales indentation  | - | 30/10/2024 |
| safeflow_mobileapp | feature/crop-detail | 13fa79a | fix: sales indentation  | - | 30/10/2024 |
| safeflow_mobileapp | feature/crop-detail | 13fa79a | fix: sales indentation  | - | 30/10/2024 |

#### 7.2.1.4. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| - | - | - | - | - | - |
| acceptance-test-IoT | test/UserStories | 524f950 | Acceptance-test-1.feature  | - | 30/10/2023 |
| acceptance-test-IoT | test/UserStories | f2a5a88 | Acceptance-test-2.feature  | - | 30/10/2023 |
| acceptance-test-IoT | test/UserStories | 89bf09e | Acceptance-test-3.feature  | - | 30/10/2023 |
| acceptance-test-IoT | test/UserStories | 65442d8 | Acceptance-test-4.feature  | - | 30/10/2023 |
| acceptance-test-IoT | test/UserStories | ca70f9b | Acceptance-test-5.feature  | - | 30/10/2023 |

Link de repositorio: https://github.com/Arq-de-Software-Emergentes-Grupo06/acceptance-test

#### 7.2.1.5. Execution Evidence for Sprint Review

En el Sprint 1 se alcanzó a desarrollar una primera versión de la landing page, la aplicación móvil y el IoT Embedded App, como principales caracteristicas tenemos las vistas de Dashboard de monitoreo de carga, Home, servicios realizados, etc. A continuación se muestra un video de lo realizado:

![imagen](https://github.com/user-attachments/assets/a5aa28f9-62f8-43d7-aab4-d809d53beeab)

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/ETFA7fskBvxPushstcTMdUcBTRvGthfXhE509_zzZ5B5sg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=5OXzRm

#### 7.2.1.6. Services Documentation Evidence for Sprint Review

Para este sprint 1, debido a que no existe la incorporación de los Web Services, se decidió usar Beeceptor como alternativa a consumir datos.
Beeceptor: https://fastflow.free.beeceptor.com

| Endpoint | Detalles |
| - | - | 
| /users| En este endpoint se almacenan la información de los usuarios, tales como username, email, password, role, photo y token | 
| /deliveries | En este endpoint se almacenan las entregas que aun no tienen ligadas un incidente | 
| /services  | En este endpoint se almacena laos servicios realizados pro parte de las empresas | 
| /incidents | En este endpoint almacena los incidentes registrados manualmente | 



#### 7.2.1.7. Software Deployment Evidence for Sprint Review

Para el despliegue de la web app y landing page se usó Netlify, a continuación se detallará paso a paso para este Sprint 1:

Ejecutamos el comando “ng build” en la ruta de nuestro projecto en angular, nos muestra lo siguiente:

![image](https://github.com/user-attachments/assets/04bc0a04-824c-472c-93e2-f28ee2533092)


Se genera la carpeta dist, luego, se añade el archivo “netlify.toml” para que netlify pueda entender las rutas de nuestro programa en angular con la siguiente configuración.

Y pasamos la carpeta que se encuentra dentro de la carpeta dist generada en nuestro proyecto. Y se obtiene el registro del despliegue dentro de Netlify

![imagen](https://github.com/user-attachments/assets/6504f90b-c985-438f-9c32-33dff1161df1)


De esta manera el avance del Sprint 1 queda desplegado.

![imagen](https://github.com/user-attachments/assets/07b7df99-e8ac-4045-9f1b-68efad6365d7)

Link de landing page: (https://safe-flow-landing.netlify.app/)

Link de simulaciones en Wokwi: https://wokwi.com/projects/413180120059730945

https://wokwi.com/projects/413204204342722561


#### 7.2.1.8. Team Collaboration Insights during Sprint

Landing Page:
![imagen](https://github.com/user-attachments/assets/ac56c310-0bef-4bd3-9ce3-218553a27db7)

Embedded App IoT:
![imagen](https://github.com/user-attachments/assets/c402209f-f367-4377-aeb5-c019727fd87e)

Mobile App:
![imagen](https://github.com/user-attachments/assets/6c7f1fc6-f38e-40c4-9ae1-7e8e93c9c30b)

## 7.3. Validation Interviews

En esta sección, se registra las actividades correspondientes a las entrevistas de validación del proyecto. Estas entrevistas van dirigidas a ambos segmentos objetivos donde se evidencia la interacción con el landing page y con las aplicaciones.

### 7.3.1. Diseño de Entrevistas

Segmento objetivo: Empresarios de transporte de combustible:

Explicación de los alcances de la demostración:

- Landing Page
- Principales tareas en la app movil
- Simulación de sensores

Preguntas:

- ¿Consideras atractiva la manera en la que el producto SafeFlow está promocionado en la Landing Page?
- ¿Consideras que el landing page ofrece toda la información necesaria para tener un entendimiento adecuado del funcionamiento, propósito y funcionalidades ofrecidas por la aplicación móvil?
- ¿Resulta agradable a la vista la manera en la que la información está presentada?
- ¿Qué dispositivo utilizaste para acceder al Landing Page? ¿La página presenta algún tipo de inconveniente de diseño que impida navegar de manera fluida?
- Del 1 al 10, ¿cómo calificarías el diseño de la Landing Page?
- Con respecto a la aplicación móvil, ¿consideras que es complicado encontrar un servicio realizado?
- ¿Los detalles de los servicios y de los incidentes son adecuados en las secciones? ¿Qué otros apartados te gustaría visualizar?
- ¿Qué opinas acerca de la distribución de secciones?
- ¿Cómo describirías nuestra aplicación móvil en pocas palabras?
- ¿Qué características específicas deseas que agreguemos a la aplicación móvil?
- ¿Utilizas actualmente una aplicación móvil con IoT para administrar tus ventas u obtener información sobre los incidentes con combustibles? De ser así, ¿qué características logras diferenciar entre esa aplicación y la nuestra?
- De todas las características evidenciadas en la aplicación móvil, ¿cuál crees que debería mejorarse? ¿Por qué?
- ¿Consideras que el diseño es adecuado?

Segmento objetivo: Transportistas de combustibles peligrosos:

Explicación de los alcances de la demostración:

- Landing Page
- Principales tareas en la app movil
- Simulación de sensores

Preguntas:

- ¿Consideras atractiva la manera en la que el producto SafeFlow está promocionado en la Landing Page?
- ¿Consideras que el landing page ofrece toda la información necesaria para entender el funcionamiento, propósito y funcionalidades ofrecidas por la aplicación móvil para obtener información de sensores y registrar incidentes?
- ¿Resulta agradable a la vista la manera en la que la información está presentada?
- ¿Qué dispositivo utilizaste para acceder al Landing Page? ¿La página presenta algún tipo de inconveniente de diseño que impida navegar de manera fluida?
- Del 1 al 10, ¿cómo calificarías el diseño de la Landing Page?
- Con respecto a la aplicación móvil, ¿consideras que es complicado encontrar el historial de incidentes registrados?
- ¿Los detalles de los incidentes y los datos obtenidos de los sensores son adecuados en las secciones? ¿Qué otros apartados te gustaría visualizar?
- ¿Qué opinas acerca de la distribución de secciones para la obtención de datos de sensores y el registro de incidentes?
- ¿Cómo describirías nuestra aplicación móvil en pocas palabras?
- ¿Qué características específicas relacionadas con el monitoreo de sensores o el registro de incidentes te gustaría que agreguemos a la aplicación móvil?
- ¿Utilizas actualmente una aplicación móvil con IoT para obtener información de sensores y registrar incidentes? De ser así, ¿qué características logras diferenciar entre esa aplicación y la nuestra?
- De todas las características evidenciadas en la aplicación móvil para monitorear sensores y registrar incidentes, ¿cuál crees que debería mejorarse? ¿Por qué?
- ¿Consideras que el diseño es adecuado para la visualización de datos de sensores y el registro de incidentes?

### 7.3.2. Registro de Entrevistas

**Segmento objetivo: Transportistas**

***Primera Entrevista:***

Nombres y apellidos: Ian Perez

Edad: 25

Inicio: 8:13

Fin: 15:04

Duración: 6:52

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EeCFl9gZqCRGhALIlvfC2EEBTEySrlhkidIA6kU9Y0vBzg?e=NydcCz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![imagen](https://github.com/user-attachments/assets/5e2e730c-e23d-46d5-9b82-2750d973f57b)

Resumen:
Ian menciona que la landing page de SafeFlow es atractiva y clara, destacando el monitoreo en tiempo real como clave para la seguridad en el transporte de materiales peligrosos. Sugiere incluir ejemplos prácticos y mejorar la adaptación a dispositivos móviles. Sobre la app, destaca la facilidad para acceder al historial de incidentes y propone añadir predicciones de datos y alertas personalizadas. Aunque considera el diseño adecuado, sugiere una mejor organización de gráficos para resaltar datos críticos en emergencias y mejorar la velocidad de respuesta ante incidentes.

***Tercera Entrevista:***

Nombres y apellidos: Favio Landeo

Edad: 25

Inicio: 15:04

Fin: 22:03

Duración: 6:57

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EeCFl9gZqCRGhALIlvfC2EEBTEySrlhkidIA6kU9Y0vBzg?e=NydcCz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![imagen](https://github.com/user-attachments/assets/a41e672e-38c1-49b6-92d7-01bd6185b02a)

Resumen:

Favio considera que la landing page de SafeFlow es atractiva y adecuada para explicar sus ventajas de seguridad en el transporte de combustibles. Aunque la presentación es clara, sugiere incluir ejemplos prácticos y mejorar la explicación sobre la instalación de sensores.

En cuanto a la app, destaca su fácil navegación y acceso al historial de incidentes, sugiriendo agregar un apartado de mantenimiento y acceso rápido a contactos de emergencia. Favio propone incluir alertas de audio o vibración para situaciones críticas y mejorar el sistema de alertas con tonos de prioridad. Describe la app como "una herramienta efectiva para monitorear y reaccionar ante incidentes en el transporte de materiales peligrosos."

**Segmento objetivo: Empresas de transporte de productos peligrosos**

***Primera Entrevista:***

Nombres y apellidos: Sharon Barrial

Edad: 20

Inicio: 00

Fin: 08:13

Duración: 08:13

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EeCFl9gZqCRGhALIlvfC2EEBTEySrlhkidIA6kU9Y0vBzg?e=NydcCz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![imagen](https://github.com/user-attachments/assets/026998aa-03cc-4175-b7fa-3323daa6e409)

Resumen:

Sharon opina que la landing page de SafeFlow es atractiva y resalta bien las ventajas de monitoreo de seguridad, esenciales para el transporte de combustibles peligrosos. Aunque considera que la página explica adecuadamente el sistema, sugiere agregar ejemplos prácticos para mejorar la comprensión.

Ella accedió desde un celular y notó que la página está bien optimizada para dispositivos móviles. Califica el diseño con un 9, destacando que es funcional, aunque recomienda mayor claridad en el proceso de instalación de sensores.

Sobre la app, Sharon considera intuitiva la navegación y destaca la facilidad para encontrar el historial de incidentes. Sugiere un apartado de mantenimiento y un acceso rápido a contactos de emergencia. Propone añadir alertas de audio o vibración para cambios críticos y comenta que SafeFlow es superior a otras apps de monitoreo por su enfoque en seguridad. Además, sugiere mejorar las alertas con tonos de prioridad para distinguir entre situaciones menores y críticas.



***Segunda Entrevista:***

Nombre: Sebastian Mendez

Inicio: 22:03

Fin: 31:44

Duración: 9:41

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EeCFl9gZqCRGhALIlvfC2EEBTEySrlhkidIA6kU9Y0vBzg?e=NydcCz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![imagen](https://github.com/user-attachments/assets/b25b22bf-da94-4bc8-890b-3e1d5be5234d)


Resumen:

Sebastián considera que la landing de SafeFlow es atractiva y destaca bien los beneficios en seguridad, recomendando agregar casos prácticos y testimonios para mejorar la confianza. La calificó con un 8, tras revisarla desde una computadora de escritorio, resaltando su funcionalidad e intuitividad. Sobre la app, destaca su fácil navegación, sugiriendo un análisis mensual de incidentes y reportes financieros para decisiones estratégicas. Actualmente usa una solución IoT básica, pero valora la especialización de SafeFlow en transporte de combustibles, proponiendo mejorar los reportes para justificar la inversión. 


### 7.3.3. Evaluaciones según heurísticas

UX Heuristics & Principles Evaluation

En esta sección se realizará el reporte de Heurísticas de usabilidad que se ecnotnraron en la realización de la validación con posibles usuarios según su segmento.

**Usability – Inclusive Design – Information Architecture**

**CARRERA : Ingeniería de Software**

**CURSO : Arquitectura de Software Emergente**

**SECCIÓN : SW82**

**PROFESORES : Todos**

**AUDITOR : Equipo de desarrollo Curidev** 

**CLIENTE(S) : SafeFlow ** 


- **SITE o APP A EVALUAR:**

SafeFlow - Solución IoT de prevención de accidentes con combustibles peligrosos 

- **TAREAS A EVALUAR:**

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Desktop landing page
   1. Información y descripción de la aplicación móvil y sus funcionalidades
   2. Visualización de botón call to action
   3. Header y footer apropiado para la landing page
2. Mobile Application
   1. Registro de nuevo usuario
   2. Inicio de sesión de usuario existente
   3. Botones interactivos y de uso intuitivo
   5. Navegación y orientación dentro de las secciones
   6. Proceso de visualización de transportes


- **ESCALA DE SEVERIDAD:**

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

|**Nivel:**|**Descripción**|
| :- | :- |
|**1**|<p>Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco </p><p>frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.</p>|
|**2**|<p>Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de </p><p>superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente </p><p>reléase</p>|
|**3**|<p>Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es </p><p>importante que sean corregidos y se les debe asignar una prioridad alta.</p>|
|**4**|<p>Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de </p><p>la herramienta. Es imperativo que sea corregido antes del lanzamiento</p>|



- **TABLA RESUMEN:**

1. **Mobile App**

|*#*|*Problema*|*Escala de severidad*|*Heurística/Principio violada(o)*|
| :-: | :-: | :-: | :-: |
|*1*|*El formato de diseño elegido para los botones es inconsistente*|*1*|*Usabilidad - Consistencia y estándares*|
|*2*|*Al estar en una de las secciones, resulta imposible de diferenciar entre estos debido a que la barra de navegación no indica en qué sección se encuentra el usuario*|*1*|*Usabilidad - Reconocer antes que recordar*|
|*3*|*No existe un apartado de edición de perfil*|*2*|*Usabilidad - Control de usuario y libertad*|
|*4*|*Inconsistencia en tamaño de tipografía*|*2*|*Usabilidad - Consistencia y estándares*|

2. **Landing page**

|*#*|*Problema*|*Escala de severidad*|*Heurística/Principio violada(o)*|
| :-: | :-: | :-: | :-: |
|*1*|*El contenido de funcionalidades no se actualiza periódicamente*|*3*|*Information Architecture - Is it credible?*|



- **DESCRIPCIÓN DE PROBLEMAS:**



1. **Mobile Application**

***PROBLEMA #1:** El formato de diseño elegido para los botones es inconsistente*

***Severidad:** 1*

*Heurística violada: Usabilidad - Consistencia y estándares*

***Problema:***
Botones en sección "Sign In y Sign Up"

![imagen](https://github.com/user-attachments/assets/cb1e674a-ad47-4a3f-a6d8-f7fde1f1ff77)


*El formato de diseño elegido para los botones “Sign In” es inconsistente a comparación de todas las secciones de la aplicación móvil. Esto incluye el color y bordes del botón que permite identificarlos. Como consecuencia, esto puede provocar que potencialmente los usuarios se desorienten y no puedan diferenciar el texto de un botón con el cual pueden interactuar.*

***Recomendación:**
Utilizar el mismo estilo de botones para mostrar más información en todas las secciones, de manera que el usuario se familiarice mejor con la aplicación web.*

***PROBLEMA #2:** Al estar en una de las secciones, resulta imposible de diferenciar entre estos debido a que la barra de navegación no indica en qué sección se encuentra el usuario*

***Severidad:** 1*

*Heurística violada: Usabilidad - Reconocer antes que recordar*

***Problema:***

Barra de navegación:

![imagen](https://github.com/user-attachments/assets/ebd6bb64-6767-49c6-a411-781d0ab73ce8)


*Dentro de las secciones que se ofrecen para ambos roles, no existe ningún indicador resaltante que permita indicar al usuario en qué sección se encuentra, potencialmente provocando que se desubique.*

***Recomendación:**
Resaltar con un cuadro de color resaltante la sección que se seleccione dentro de la barra de navegación, con la finalidad de orientar al usuario.*

***PROBLEMA #3:** No existe un apartado de edición de perfil*

***Severidad:** 2*

*Heurística violada: Usabilidad - Control de usuario y libertad*

***Problema:***

*Dentro de la barra de navegación no hay un apartado de edición de perfil, esto ocasiona que el usuario no brinde y proporcione datos quepeuden llegar a ser relevantes, como teléfono de contacto entre otros campos.*

***Recomendación:**
Implementar un boton o apartado para editar perfil de usuario.*


***PROBLEMA #5:** Inconsistencia en tamaño de tipografía *

***Severidad:** 2*

*Heurística violada: Usabilidad - Consistencia y estándares*

***Problema:***

![imagen](https://github.com/user-attachments/assets/8d451433-4046-4121-8df8-7ff313378f23)

*En las pantallas de home para ambos roles, existe una incosistencia en el tamaño de la tipografía, lo que ocasiona insatisfacción visual al usuario al momento de navegar por las pantallas de home*


***Recomendación:**
Corregir la tipografía en todas las secciones de un tamaño equivalente*


1. **Landing Page**

***PROBLEMA #1:**  El contenido de funcionalidades no se actualiza periodicamente*

***Severidad:** 3*

*Heurística violada: Information Architecture - Is it credible?*

***Problema:***

*En la sección de funcionalidades, algunas de estas ya no se están implementando, por lo que el usuario puede ser confundido al querer usar esas caracteristicas*

***Recomendación:**
Corregir las funcionalidades mostradas en las listas de la sección*


## 7.4. Video About-the-Product

A continuación, se mostrará el Video About the Product, donde se mostrará las carácteristicas de la Landing Page para los segmentos objetivos interesados. De igual manera, se mostrará lo avanzado en el primer Sprint. Finalmente, también incluye un testimonio de uso realizado en una entrevista de validación:

![imagen](https://github.com/user-attachments/assets/51495328-6782-4e60-ada1-2637785d043c)



Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EZ8pn120ONFLgzEQqZUlhEwBhF5bqBj2-IUZeVuQn6lrWw?e=IPwTzV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

# Conclusión

En esta primera entrega se realizaron tareas relacionadas a la captura de requisitos y toma de decisiones a la solución tecnoloógica con tecnologías emergentes, en este caso utilizanod IOT. Se planteó el dominio de negocio y a que problemática responde. 

En esta segunda entrega, se desarrolló la primera versión de la arquitectura del sistema, aplicando herramientas de Domain Driven Design tales como EventStorming, Bounded Context Canvas. Todo esto nos permitió establecer las bases para la arquitectura de la solución con tecnología emergente.

En esta tercera entrega, se desarrollaron las primeras versiones de los productos digitales que componene la solución IoT, de esta manera sentando las bases de funcionaldiades escenciales para el correcto funcionamiento y satisfacción de los segmentos objetivos. Por otro lado, se realizaron diversas actividades para mejorar la calidad del Sprint, tales como entrevistas de validación y evaluaciones según heuristicas.

## Video About-the-Team

A continuación se presenta el video about the team, donde cada integrante exponse una retrospectiva grupal y personal acerca de su desempeño a lo largo del sprint y del proyecto, seguido de una retrospectiva del lider del equipo. Además, se detallan las tareas que realizó cada uno. 

![imagen](https://github.com/user-attachments/assets/54f33add-bee4-4e0e-bb4d-0d80997d45b9)

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EROydnGPR7FBjIxC-2pELpgBPJBsHIr8yYxrV3-KJdCJgg?e=NjwchP&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

# Bibliografía

López-Atamoros, L. G., Fernández-Villagómez, G., Cruz-Gómez, M. J., & Durán-de-Bazúa, C. (2010). Integración de una Base Nacional de Datos de Accidentes durante el Transporte de Gas LP (BNDAT@ GLP) 1998-2009: Sustento para un estudio de evaluación de riesgo. Tecnología, Ciencia, Educación, 25(2), 99-112.

Soto, J. A. S., González, D. L. E., Sánchez, J. F. I., Reyes, J. A., & Layva, J. M. E. (2023). DISEÑO DE DISPOSITIVO PARA PREVENIR ACCIDENTES CAUSADOS POR FUGAS DE GAS. Revista IPSUMTEC, 6(4), 11-14.


# Anexos

Video exposición TB1: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EUiUUIC1kXRJv5Z6QIk1Md8Bq0XGdR6M1aGMuusUgAx86g?e=NIx2JJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Video Exposición TP: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EQtY02wGc-9BruKxA4zePMcBrf0g5p57enTfLFNF-meycg?e=pUGkME&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Video Exposición TB2: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202118468_upc_edu_pe/EXDfUlVMe99Dj1wfrVGCjYEBvtEY3ACW-IaXp7ZIkBneVA?e=5vTZFm&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
