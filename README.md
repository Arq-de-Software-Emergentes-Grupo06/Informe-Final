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
