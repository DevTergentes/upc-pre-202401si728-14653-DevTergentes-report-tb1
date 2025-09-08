<div align="center">

<img width="125" height="125" alt="image" src="https://github.com/user-attachments/assets/998a5621-906e-45a8-9368-0a74b48f0d6e" />

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2025-10

# Arquitecturas De Software Emergentes


NRC 14653

Profesor: Berrocal Navarro, Richard Leonardo 

***INFORME DE TRABAJO - TB1***

**Startup: DevTergentes**

**Producto: SecurOn**

**Integrantes**
| Nombre completo | Código        |
|----------------------------------------------|---------------|
| Amaro Villanueva, Camila Elena               | U202114248    |
| Astuyauri Calderon, Jherson David            | U202218451    |
| Calderon Huaman, Jose Daniel Mario           | U202213076    |
| Antonio Fretel, Jeremi Jose                  | U202219022    |
| Quispesivana Torres, Claudio Sandro          | U202215099    |

</div>
<br><div align="center"><h3>Septiembre 2025</h3></div><br>

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
| 1.00 | 07/09/2025 | Todos los integrantes del equipo  |  |

---

# Project Report Collaboration Insights

**TB1:** Se han desarrollado las actividades correspondientes para la entrega TB1 en el siguiente repositorio de Github dentro de la organización del equipo:
Link de repositorio Github: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*
![image](https://github.com/user-attachments/assets/7010f212-ddcc-470e-b2df-781a12cbd85a)

**TP1:** Se han desarrollado las actividades correspondientes para la entrega TP1 en el siguiente repositorio de GitHub dentro de la organización del equipo:

Link de repositorio GitHub: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*
![image](https://github.com/user-attachments/assets/6c0adc3c-c4fb-4cff-937b-ff5b1cbc21f6)

**TB2:** Se han desarrollado las actividades correspondientes para la entrega TB2 en el siguiente repositorio de GitHub dentro de la organización del equipo:

Link de repositorio GitHub: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*

![image](https://github.com/user-attachments/assets/c7a9982a-f550-487f-ba34-fcc6bd2b2879)

**TF1:** Se han desarrollado las actividades correspondientes para la entrega TF1 en el siguiente repositorio de GitHub dentro de la organización del equipo:

Link de repositorio GitHub: https://github.com/Chemtrack-Grupo4/report

*Registro de commits*

![image](https://github.com/user-attachments/assets/45377e9d-842d-4fa5-9c84-8babf030be20)




---

# Contenido 
## Tabla de contenidos

## [Student Outcome](#student-outcome)
## [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
## [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Journey Mapping](#233-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
## [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1 Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.2. Software Architecture Container Level](#4132-software-architecture-container-level)
      - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1. Bounded Context: IAM](#421-bounded-context-iam)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2. Bounded Context: Management](#422-bounded-context-management)
      - [4.2.2.1. Domain Layer](#4221-domain-layer)
      - [4.2.2.2. Interface Layer](#4222-interface-layer)
      - [4.2.2.3. Application Layer](#4223-application-layer)
      - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
      - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
        - [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3. Bounded Context: Records](#423-bounded-context-records)
      - [4.2.3.1. Domain Layer](#4231-domain-layer)
      - [4.2.3.2. Interface Layer](#4232-interface-layer)
      - [4.2.3.3. Application Layer](#4233-application-layer)
      - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
        - [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
## [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
- [5.1. Style Guidelines](#51-style-guidelines)
  - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
  - [5.1.2. Web, Mobile and IoT Devices Style Guidelines](#512-web-mobile-and-iot-devices-style-guidelines)
- [5.2. Information Architecture](#52-information-architecture)
  - [5.2.1. Organization Systems](#521-organization-systems)
  - [5.2.2. Labeling Systems](#522-labeling-systems)
  - [5.2.3. Searching Systems](#523-searching-systems)
  - [5.2.4. SEO Tags and Meta Tags](#524-seo-tags-and-meta-tags)
  - [5.2.5. Navigation Systems](#525-navigation-systems)
- [5.3. Landing Page UI Design](#53-landing-page-ui-design)
  - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
  - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
- [5.4. Applications UX/UI Design](#54-applications-uxui-design)
  - [5.4.1. Applications Wireframes](#541-applications-wireframes)
  - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
  - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
  - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
- [5.5. Applications Prototyping](#55-applications-prototyping)

## [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
  - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
  - [6.1.2. Source Code Management](#612-source-code-management)
  - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
  - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
  - [6.2.1. Sprint 1](#621-sprint-1)
    - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
    - [6.2.1.2. Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
    - [6.2.1.3. Sprint Backlog 1](#6213-sprint-backlog-1)
    - [6.2.1.4. Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
    - [6.2.1.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.1.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.1.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.1.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.1.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
  - [6.2.2. Sprint 2](#622-sprint-2)
    - [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
    - [6.2.2.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
    - [6.2.2.3. Sprint Backlog 2](#6223-sprint-backlog-2)
    - [6.2.2.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
    - [6.2.2.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.2.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.2.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.2.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.2.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
  - [6.2.3. Sprint 3](#622-sprint-3)
    - [6.2.3.1. Sprint Planning 3](#6221-sprint-planning-3)
    - [6.2.3.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
    - [6.2.3.3. Sprint Backlog 3](#6223-sprint-backlog-3)
    - [6.2.3.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
    - [6.2.3.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
    - [6.2.3.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
    - [6.2.3.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
    - [6.2.3.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
    - [6.2.3.9. Team Collaboration Insights During Sprint](#6219-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)

## [Conclusiones](#conclusiones)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)

## [Video About-the-Team](#video-about-the-team)

## [Bibliografía](#bibliografía)

## [Anexos](#anexos)


---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 5

Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas                                                                                                      | Conclusiones |
| - |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| - |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta. | **TB1**<br>**Camila Elena Amaro Villanueva**<br>Ayude en la en la elaboración de epics junto con sus respectivas user y technical stories teniendo en cuenta las necesidades identificadas en nuestros segmentos objetivos y los posibles escenarios que podrían presentarse. Esto nos permitió anticipar cómo deberíamos actuar ante diferentes situaciones. Asimismo, brindé apoyo en la creación de los impact maps correspondientes a los dos segmentos objetivos definidos.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Apoyé activamente a la identificación de eventos de dominio para mejorar la experiencia de usuario durante las interacciones con funciones centrales de nuestro sistema *Chemtrack*. Para ello, se realizó un proceso completo de event storming siguiendo un patrón de pasos preestablecidos que nos permitió visualizar la lógica correcta del sistema.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Participé en la elaboración de los segmentos objetivo, el análisis de competidores y la definición de estrategias frente a ellos, lo cual requirió coordinación constante con el equipo. Asimismo, realicé el diseño de entrevistas y el análisis de resultados, fomentando el intercambio de ideas y perspectivas para fortalecer la solución final.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Desarrollé la parte de descripción del startup del equipo, así como nuestro solution profile frente a una necesidad identificada, los antecendes que surgieron previamente a esta problemática y las solución que nuestra solución ofrece.<br><br>**Josue Omar Hidalgo Bustamante**<br>Contribuí de manera activa en el desarrollo de los arquetipos de usuarios y en la definición de sus necesidades principales, lo que permitió orientar mejor el diseño de soluciones dentro del proyecto. Además, colaboré en la preparación de los journey maps para visualizar las experiencias de los usuarios en diferentes etapas del proceso. Este trabajo facilitó la identificación de puntos críticos y oportunidades de mejora en el sistema propuesto, asegurando una propuesta de valor más ajustada a las expectativas reales.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Participé en el desarrollo de los modelos de arquitectura del sistema, así como en el Context Mapping, colaborando con el equipo para garantizar una visión unificada y estratégica del sistema. La definición de límites claros entre los contextos permitieron optimizar la comunicación entre el equipo, fomentando una colaboración efectiva que fortaleció la coherencia y robustez de la solución. <br><br> **TP1**<br>**Camila Elena Amaro Villanueva**<br>Apoye en la elaboración de los mockups y wireframes de la app web y móvil teniendo en cuenta las etiquetas planeadas para nuestras aplicaciones y el proceso lean ux realizado previamente donde captamos las necesidades de los usuarios. Asimismo, participe en el desarrollo de la primera versión de la app web. <br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Lideré la ejecución de la planificación del Sprint 1, en la cual, junto con el equipo, realizamos un análisis detallado del estado del proyecto. Durante esta sesión, identificamos las partes faltantes tanto a nivel funcional como técnico. Asimismo, organizamos y priorizamos las tareas clave para el desarrollo del proyecto, incluyendo la planificación estructurada del diseño e implementación de la landing page. Además, definimos los pasos necesarios para construir y desplegar nuestro primer prototipo web funcional, lo que marcó un hito inicial en la validación del producto.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Durante el desarrollo de esta entrega correjí y realicé la mejora de secciones clave del diseño de software, tales como Tactical-Level Software Design, General Style Guidelines y Web, Mobile and IoT Style Guide. Este trabajo fue realizado de manera colaborativa, promoviendo discusiones técnicas, consensuando decisiones de estilo y asegurando la coherencia entre los distintos componentes del sistema<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Durante esta etapa se trabajó en el diseño inicial de la landing page utilizando Figma como herramienta principal. El equipo se enfocó en definir la identidad visual del producto, seleccionando una paleta de colores, tipografías y componentes visuales coherentes con los objetivos del proyecto. Se diseñó un primer wireframe y posteriormente una propuesta de alta fidelidad que refleja la estructura, navegación y funcionalidades clave de la página de inicio del sistema. Este diseño sentó las bases para el posterior desarrollo del prototipo funcional y facilitó una visión clara y compartida entre todos los miembros del equipo.<br><br>**Josue Omar Hidalgo Bustamante**<br>La primera versión de la aplicación web fue desarrollada con mi participación directa en su implementación. Previamente, estuve involucrado en el diseño de sus interfaces, colaborando en la elaboración de mockups y wireframes tanto para la versión web como móvil. Estos se construyeron tomando en cuenta las etiquetas planificadas y los resultados del proceso de Lean UX, en el que identificamos las principales necesidades de los usuarios.<br><br>**Niurka Lucero Huarcaya Quispe**<br> Participé en la recopilación y presentación de las evidencias necesarias para la Sprint Review. Me encargué de documentar el desarrollo, las pruebas, la ejecución de funcionalidades y la documentación de los servicios. Esto permitió al equipo tener una visión clara del progreso del sprint. <br><br>**TB2**<br>**Camila Elena Amaro Villanueva**<br>Contribuyó activamente en solucionar las correcciones señaladas en frontend demostrando compromiso y colaboración constante con el equipo para alcanzar los objetivos técnicos del proyecto.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Se realizaron reuniones Scrum para identificar debilidades del proyecto y promover un trabajo en equipo eficiente, facilitando la toma de decisiones colaborativas y el avance coordinado del grupo.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Durante el desarrollo de esta entrega correjí y realicé la mejora de secciones clave del diseño de software, tales como Sprint Planning y Product Backlog. Este trabajo fue realizado de manera colaborativa, promoviendo discusiones técnicas y asegurando la coherencia entre los distintos componentes del sistema <br><br>**Fabrizzio Hernan Laguerre Challco**<br>Identificó y definió las funcionalidades clave de la versión mobile, lo que permitió guiar el desarrollo orientado a una experiencia de usuario optimizada. Su aporte fue fundamental para alinear al equipo en la construcción de una interfaz coherente, intuitiva y funcional para dispositivos móviles.<br><br>**Josue Omar Hidalgo Bustamante**<br>Colaboró activamente en la construcción de la arquitectura del backend, en la integración de los componentes edge y en el desarrollo de simulaciones en Wokwi, contribuyendo al ensamblaje técnico del sistema y asegurando su funcionamiento coordinado dentro del entorno de Chemtrack.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Brindó apoyo en la validación del servicio, participando activamente en la aplicación de heurísticas para evaluar la usabilidad del sistema. Su contribución fue clave para asegurar la calidad de la experiencia del usuario y fortalecer el proceso colaborativo de mejora continua en el equipo.<br><br> **TF1**<br>**Camila Elena Amaro Villanueva**<br>Para este último Sprint colaboré en mejorar los componentes del frontend para que cumplan con lo planteado inicialmente en las user stories. Asimismo, revisé que los endpoints se llamarán de manera adecuada y realicé entrevistas de validación con los segmentos objetivo para recopilar opiniones respecto a nuestro producto y puntos de mejora. Además, colaboré en la elaboración del prototipo iot físico. <br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Durante este sprint, asumí un rol activo en la organización y seguimiento del proyecto mediante la actualización continua del tablero en Trello, lo cual permitió al equipo tener claridad sobre el avance de cada tarea y priorizar pendientes críticos. Asimismo, lideré la edición final de los videos de entrega, asegurándome de que reflejen fielmente el desarrollo del sistema y cumplan con los criterios de revisión establecidos. Coordiné con los miembros encargados de cada componente para recopilar y validar la evidencia técnica de desarrollo, pruebas, ejecución y despliegue, facilitando una presentación clara y ordenada durante la revisión del sprint.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Apoyé al equipo en el procesamiento y sistematización de la información recogida durante las entrevistas de validación, organizando los hallazgos en categorías relevantes y facilitando su discusión en equipo para la toma de decisiones. A partir de los resultados, propuse tareas de mejora que fueron incorporadas al backlog. Además, promoví un entorno colaborativo al incentivar la participación equitativa de todos los integrantes durante la evaluación heurística, estableciendo tiempos y objetivos claros para cada etapa del análisis, asegurando así que se cumplieran dentro del sprint.<br><br>**Niurka Lucero Huarcaya Quispe**<br> Me aseguré de que las tareas críticas de cierre estuvieran correctamente distribuidas y se cumplieran dentro del sprint final. Organicé y participé en reuniones técnicas donde se definieron los objetivos relacionados a la migración del edge fuera de la nube y la inclusión de la simulación en Wokwi. Además, colaboré con el equipo de backend para aplicar las últimas validaciones, revisando cada endpoint y su consistencia con las reglas de negocio. Impulsé la planificación y ejecución del video integrador, guiando a mis compañeros en qué debía incluirse para reflejar adecuadamente el funcionamiento de cada componente del proyecto. <br><br>**Josue Omar Hidalgo Bustamante**<br> Durante este sprint final, lideré la integración completa del sistema IoT, coordinando con el equipo la actualización del punto del edge para que funcione fuera de la nube, lo cual representó un reto técnico importante. Además, propuse y ejecuté la implementación de un segundo edge en Wokwi para fines de simulación y pruebas en paralelo, facilitando el trabajo de mis compañeros en frontend y mobile. También organicé sesiones internas para revisar la lógica del backend, identificar errores y aplicar validaciones finales. Finalmente, colaboré activamente en la producción del video que demuestra todo el flujo del sistema (web, mobile, edge y Wokwi), asegurando que cada parte estuviera correctamente sincronizada y funcionando.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Me enfoqué en planificar y ejecutar la integración del prototipo con el backend, asegurando que las lecturas del microcontrolador fueran procesadas y almacenadas adecuadamente. Establecí objetivos técnicos claros y coordiné tareas con el equipo para abordar desafíos como la latencia en la transmisión de datos y la validación del flujo completo. Además, fomenté un entorno de colaboración continua mediante pruebas conjuntas, intercambio de avances y resolución colectiva de problemas técnicos, lo cual fue clave para lograr un funcionamiento estable del sistema.<br><br> | **TB1:** Como equipo, trabajamos de manera colaborativa para cubrir todas las etapas clave del desarrollo inicial de Chemtrack, desde la definición del problema y el análisis de mercado hasta la construcción de la solución tecnológica. Cada integrante asumió un rol fundamental en áreas como la elaboración de user stories, la identificación de eventos de dominio, el diseño de entrevistas, la creación de arquetipos, el mapeo de experiencias y el modelado de la arquitectura del sistema. Esta sinergia nos permitió integrar múltiples perspectivas y asegurar una base sólida, estratégica y centrada en el usuario para el desarrollo de nuestra solución. <br><br> **TP1:** Como equipo, trabajamos de manera colectiva y alineada para identificar y corregir los artefactos faltantes en nuestro proyecto. Este proceso nos permitió afinar los detalles y reforzar la definición de nuestra propuesta, asegurando una visión compartida del producto. Gracias a esta colaboración, logramos preparar y desplegar una primera muestra representativa de lo que será nuestra solución final, materializada en la publicación de la landing page y el primer prototipo funcional de la web.<br><br> **TB2:** Como equipo, trabajamos de manera colaborativa para consolidar la segunda entrega del proyecto, enfocándonos en el desarrollo integral del sistema. Se levantaron las observaciones de la entrega anterior y se implementó la versión final de la landing page y de la página web (frontend). Además, se desarrollaron las funcionalidades core del backend, edge, mobile y del sistema embebido (Wokwi), asegurando una interfaz limpia, funcional e integrada.<br><br>**TF1:** Como grupo, logramos consolidar un flujo de trabajo colaborativo y eficiente a lo largo del desarrollo del proyecto. Cada integrante asumió responsabilidades específicas en base a sus fortalezas, permitiendo una ejecución coordinada tanto del backend, frontend, como del sistema físico. Nos apoyamos constantemente mediante sesiones de revisión y pruebas cruzadas, lo que fortaleció la calidad del producto entregado. Además, tomamos decisiones conjuntas en momentos clave del desarrollo, demostrando liderazgo compartido, comunicación efectiva y compromiso colectivo con los objetivos planteados desde el inicio.<br><br>| 
| Crea un entorno colaborativo einclusivo, establece metas, planifica tareas y cumple objetivos. | **TB1**<br>**Camila Elena Amaro Villanueva**<br>Participé de manera activa en las reuniones de planificación del proyecto, así como en su desarrollo. Además, me encargué de organizar las tareas relacionadas con la elaboración de las user stories, basándome en la información recopilada por cada integrante del equipo a través de entrevistas realizadas a usuarios pertenecientes a los segmentos objetivo.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Organicé las diferentes reuniones utilizando la metodología daily scrum hasta la entrega, donde identificamos las partes faltantes de nuestro trabajo, priorizamos tareas pendientes y coordinamos responsabilidades para asegurar el avance constante del proyecto. Donde la comunicación efectiva fue clave dentro del equipo para resolver bloqueos de forma oportuna y mantener la misma alineación.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Contribuí activamente a la creación de un entorno colaborativo, establecimos metas claras desde las fases iniciales del proyecto y organicé tareas relacionadas con el diseño táctico del software, abarcando los distintos Bounded Contexts. Coordiné la elaboración de las distintas capas arquitectónicas y diagramas técnicos, asegurando una planificación eficiente y cumplimiento de los plazos.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>Desarrollé el Lean UX Process, una artefacto fundamental para identificar nuestras funciones claves, segmentos objetivos, identificación y establecimiento de nuestra solución frente a la problemática identificada brindando una gráfica ejemplar y amplia para implementar una solución completa.<br><br>**Josue Omar Hidalgo Bustamante**<br>Apoyé en la validación de requerimientos técnicos y funcionales, asegurando que cada propuesta se ajustara a los objetivos del proyecto. También colaboré activamente en la elaboración de diagramas de flujo y en la definición de entidades clave del sistema. Durante el desarrollo, participé en sesiones de retroalimentación continua, lo que permitió realizar ajustes oportunos y mantener la calidad en cada entrega parcial.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Contribuí en la creación de los modelos de arquitectura del sistema, así como en el Context Mapping, asegurando que cada nivel de arquitectura estuviera alineado con los objetivos estratégicos y técnicos. Además, en equipo, establecimos metas claras, organizamos las tareas de manera estratégica y aseguramos el cumplimiento de los objetivos del proyecto. <br><br> **TP1**<br>**Camila Elena Amaro Villanueva**<br>Participé activamente en las reuniones de planificación del proyecto y en su desarrollo. Además, coordine al grupo en la creación de la aplicación web, guiándolos con base en los mockups previamente diseñados.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Desarrollé el Sprint Backlog 1 identificando y priorizando las tareas clave (core) de nuestro sistema, enfocándome en aquellas funcionalidades esenciales que debían estar presentes en esta primera entrega del prototipo. Esta planificación permitió establecer una hoja de ruta clara para el equipo y asegurar que el prototipado inicial reflejara de manera efectiva los pilares fundamentales de nuestra solución.<br><br>**Andrea Joselyn Garcia Moscoso**<br>Contribuí activamente a la creación de un entorno colaborativo y corrección de los documentos Tactical-Level Software Design, General Style Guidelines y Web, Mobile and IoT Style Guide. Para ello, coordiné con el equipo la definición de metas claras relacionadas con la mejora de la consistencia, calidad del diseño, revisión en función de los tiempos establecidos, y aseguré el cumplimiento de los objetivos propuestos.<br><br>**Fabrizzio Hernan Laguerre Challco**<br>En esta primera entrega se consolidó el diseño de la landing page desarrollado en Figma. A partir de los wireframes y propuestas previas, se logró una versión pulida y funcional que cumple con los objetivos de comunicación del proyecto. El trabajo en Figma permitió una colaboración fluida entre los integrantes del equipo, permitiendo iteraciones rápidas y comentarios en tiempo real. Este diseño no solo representa visualmente el producto, sino que también guió el desarrollo del prototipo inicial. El despliegue de la landing page refleja el compromiso del equipo con la calidad visual y la experiencia del usuario desde las primeras fases del proyecto.<br><br>**Josue Omar Hidalgo Bustamante**<br>Durante el desarrollo del proyecto, asumí un rol activo tanto en la etapa de planificación como en la ejecución. Me encargué de coordinar al equipo, brindando orientación basada en los mockups definidos con anterioridad para asegurar la coherencia en el diseño de la aplicación web.<br><br>**Niurka Lucero Huarcaya Quispe**<br>Se realizó la recolección y elaboración de las evidencias requeridas para la Sprint Review. Se promovió un entorno donde todos los miembros participaron aportando resultados del desarrollo, pruebas, ejecución, documentación de servicios y despliegue del software.<br><br>**TB2**<br>**Camila Elena Amaro Villanueva**<br>Se desarrollaron los módulos de frontend, backend y las simulaciones en Wokwi, con el objetivo de validar el funcionamiento integral del sistema, garantizando la coherencia entre interfaces, lógica de negocio y componentes físicos simulados dentro del entorno de Chemtrack.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Se aplicó Scrum para colaborar activamente en cada tarea, elaborando el video “About the Product” para comunicar el objetivo de Chemtrack y una serie de auditorias de funcionamiento de todos los artefactos desarrollados para validar su calidad.<br><br> **Andrea Joselyn Garcia Moscoso**<br>Contribuí activamente a la creación de un entorno colaborativo y corrección de los documentos en el Sprint Planning. Además, coordiné con el equipo la definición de metas claras relacionadas con la mejora de la consistencia,revisión en función de los tiempos establecidos, y aseguré el cumplimiento de los objetivos propuestos.<BR><BR>**Fabrizzio Hernan Laguerre Challco**<br>Se establecieron metas específicas para la versión mobile, asignando tareas de diseño, desarrollo e integración que facilitaron su avance estructurado y desplegado creando un apk.<br><br>**Josue Omar Hidalgo Bustamante**<br>Se logró cumplir con el desarrollo e integración del backend, el módulo edge y las simulaciones en Wokwi, asegurando su correcto despliegue, funcionamiento y conexión con el resto del sistema, lo que permitió validar su operatividad dentro del ecosistema de Chemtrack. <br><br>**Niurka Lucero Huarcaya Quispe**<br>Se documentó y aplicó evaluaciones heurísticas y validaciones con usuarios, fortaleciendo la calidad del sistema y reflejando los valores de inclusión, colaboración y mejora continua.<br><br>**TF1**<br>**Camila Elena Amaro Villanueva**<br>Revisé que la app web elaborada estuviera de acuerdo a las user stories identificadas al inicio del desarrollo del proyecto y que cumplieran con sus respectivos criterios de aceptación. Además, participé de manera activa en las reuniones de planificación y me encargue de coordinar la elaboración del front con los compañeros de mi equipo y de gestionar reuniones en caso se presentarán bugs en el desarrollo.<br><br>**Sharon Antuanet Ivet Barrial Marin**<br>Me encargué de estructurar y organizar los entregables correspondientes al Sprint Review, coordinando la documentación de evidencias clave como el Sprint Backlog, pruebas realizadas, despliegue del software y servicios desarrollados. Promoví la colaboración entre los integrantes al establecer deadlines internos y alinear los esfuerzos para cumplir con los entregables a tiempo. Además, participé activamente en las reuniones de planificación, proponiendo estrategias para mejorar la gestión visual de tareas a través del Trello, lo que ayudó a optimizar el trabajo en equipo y mantener el enfoque en los objetivos del sprint.<br><br> **Andrea Joselyn Garcia Moscoso**<br>Apoyé al equipo en el procesamiento y sistematización de la información recogida durante las entrevistas de validación, organizando los hallazgos en categorías relevantes y facilitando su discusión en equipo para la toma de decisiones. A partir de los resultados, propuse tareas de mejora que fueron incorporadas al backlog. Además, promoví un entorno colaborativo al incentivar la participación equitativa de todos los integrantes durante la evaluación heurística, estableciendo tiempos y objetivos claros para cada etapa del análisis, asegurando así que se cumplieran dentro del sprint.<BR><BR>**Fabrizzio Hernan Laguerre Challco**<br>Me enfoqué en planificar y ejecutar la integración del prototipo con el backend, asegurando que las lecturas del microcontrolador fueran procesadas y almacenadas adecuadamente. Establecí objetivos técnicos claros y coordiné tareas con el equipo para abordar desafíos como la latencia en la transmisión de datos y la validación del flujo completo. Además, fomenté un entorno de colaboración continua mediante pruebas conjuntas, intercambio de avances y resolución colectiva de problemas técnicos, lo cual fue clave para lograr un funcionamiento estable del sistema.<br><br>**Josue Omar Hidalgo Bustamante**<br>Me aseguré de que las tareas críticas de cierre estuvieran correctamente distribuidas y se cumplieran dentro del sprint final. Organicé y participé en reuniones técnicas donde se definieron los objetivos relacionados a la migración del edge fuera de la nube y la inclusión de la simulación en Wokwi. Además, colaboré con el equipo de backend para aplicar las últimas validaciones, revisando cada endpoint y su consistencia con las reglas de negocio. Impulsé la planificación y ejecución del video integrador, guiando a mis compañeros en qué debía incluirse para reflejar adecuadamente el funcionamiento de cada componente del proyecto. <br><br>**Niurka Lucero Huarcaya Quispe**<br>Mi apoyo en la documentación a lo largo del proyecto ayudó a mantener una comunicación clara y accesible para todos los miembros del equipo. Esta contribución permitió organizar mejor las tareas, definir metas comunes y asegurar que cada integrante participara activamente en el cumplimiento de los objetivos. | **TB1:** El equipo demostró una sólida capacidad para colaborar de forma inclusiva, planificando estratégicamente las tareas y cumpliendo los objetivos del proyecto. A través de reuniones constantes, el uso de metodologías ágiles y una distribución clara de responsabilidades, logramos mantener una comunicación efectiva, anticipar desafíos y avanzar de manera organizada. Esto nos permitió construir una base sólida para el desarrollo de Chemtrack, alineando tanto los aspectos técnicos como los objetivos del negocio. <br><br> **TP1:** Nuevamente se evidenció una sólida capacidad de trabajo en equipo, reflejada en la distribución equitativa de las tareas y el compromiso de cada integrante para cumplir con los objetivos dentro del tiempo estimado. Esta coordinación eficiente nos permitió avanzar con fluidez en el desarrollo del prototipo, fortaleciendo tanto la dinámica grupal como el progreso del proyecto. Logrando tener el despliegue de landing page y de la web. Además de las correcciones levantadas. <br><br> **TB2:** Como equipo, aplicamos la metodología Scrum para fomentar la colaboración activa y la organización del trabajo en cada sprint. Desarrollamos e integramos los módulos de frontend, backend, edge, mobile y embebido mediante una planificación clara de tareas y metas. Usamos Wokwi para simular y validar los dispositivos, y realizamos evaluaciones heurísticas e entrevistas para asegurar una experiencia de usuario óptima. Elaboramos el video “About the Product” para comunicar el objetivo de Chemtrack a nuestros clientes y auditamos cada artefacto del sistema para garantizar su correcto funcionamiento y calidad. <br><br> **TF1:** Durante todo el proyecto, nuestro equipo mantuvo una planificación clara y compartida, utilizando herramientas como Trello, reuniones periódicas y documentación colaborativa para asegurar un avance constante. Fomentamos un entorno de trabajo inclusivo donde todas las opiniones fueron escuchadas y valoradas, lo cual enriqueció el diseño del producto. Gracias a una distribución equitativa de tareas y un enfoque orientado a objetivos, cumplimos con los entregables de cada sprint, logrando integrar satisfactoriamente todas las partes del sistema y presentar un producto funcional validado por usuarios reales. |

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

El startup que se introduce en el presente informe recibe como nombre “TrackTox”. Actualmente conformado por un conjunto de estudiantes de la Universidad Peruana de Ciencias Aplicadas, con la ambición de querer ayudar a la sociedad con nuestra grán pasión a la tecnología e informática, creamos esta startup tomando como objetivo asegurar la integridad y mejorar los procesos de trabajo de las empresas de transporte de productos peligrosos.

Como misión se plantea “Incrementar la calidad del servicio de transporte de combustibles con eficiencia, seguridad y transparencia entre conductores y empresas”. Asimismo, la visión de la startup plantea desarrollar la solución IoT más reconocida en el Perú para asegurar la integridad de los transportes de productos peligrosos.

### 1.1.2. Perfiles de integrantes del equipo

A continuación, presentaremos los perfiles de los integrantes del equipo encargado de desarrollar el proyecto. Cada uno de nuestros miembros aporta una combinación única de habilidades y perspectivas que son fundamentales para el éxito del proyecto.

| **Integrante**                         | **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Imagen**                                                                                                       |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Amaro Villanueva, Camila Elena - u202114248**             |Mi nombre es Camila Elena Amaro Villanueva, cuento con conocimientos de desarrollo frontend y backend, además de lenguajes de programación como C++, Python y JavaScript. Además, entre mis habilidades, puedo resaltar la responsabilidad y creatividad que poseo para aportar en los trabajos en equipo. | <img src="https://github.com/user-attachments/assets/d03388b2-c106-406c-961f-3785e3fae476" alt="Imagen de Camila Amaro" />|
| **Astuyauri Calderon, Jherson David - u202218451**          |Soy Jherson, estudiante de Ingeniería de Software en la UPC (8.º ciclo). Me apasiona la inteligencia artificial y su potencial para transformar el mundo mediante soluciones más inteligentes y humanas. Tengo adaptabilidad, soy una persona responsable y proactiva con muchas ganas de crecer profesionalmente. | <img src="https://jhersonss24-portafolio.netlify.app/assets/profile-front_1.jpg" alt="Imagen de Jherson" />|
| **Quispesivana Torres, Claudio Sandro - u202215099**     |Mi nombre es Claudio Sandro Quispesivana Torres, tengo 20 años y estoy cursando el octavo ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://raw.githubusercontent.com/TechZo-1ASI0732-4453/Report/refs/heads/main/Resources/Chapter-I/Profiles/sandroquispesivana.png" alt="Imagen de Sandro Quispesivana"/> |
| **Calderon Huaman, Jose Daniel Mario - U202213076** |Soy estudiante de 8.º ciclo de Ingeniería de Software con experiencia en desarrollo full-stack. Me considero una persona responsable, organizada y comprometida. Valoro el trabajo en equipo y me esfuerzo por aportar soluciones eficientes y bien estructuradas. He trabajado con tecnologías como React, Tailwind, Express.js, JavaScript y TypeScript, aplicándolas en proyectos reales. También tengo conocimientos en C++, Python y Flutter. | <img src="https://github.com/user-attachments/assets/7a670c75-fa1d-45d8-847c-2e829189ce79" alt="Imagen de Jose Calderon" /> |


## 1.2. Solution Profile

**Product name**


El nombre elegido para nuestra solucion es ChemTrack. Este nombre transmite la idea de un camino seguro en el cuál se llevaran los productos quimicos, lo cual es el objetivo principal del sistema de detección y alerta.


**Product Description**

La solución IoT es innovadora dado que se brinda un servicio de transporte de productos peligrosos implementando la supervisión de condiciones de seguridad tanto para el mismo conductor y para el monitoreo de la empresa. Por medio de sensores incluidos en el vehículo y en el conductor, se supervisará el material de carga y se notificará en caso exista alguna fuga. También se mantendra control del estado de salud del conductor. Estos sensores varían desde fuga de gas, temperatura, presión, movimiento, etc. 


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

Nuestra solución abordará esta brecha proporcionando un sistema de monitoreo en tiempo real que, a través de sensores, detectará rápidamente cualquier anomalía durante el transporte antes de que afecte al conductor o al producto transportado y se convierta en una amenaza.

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
| **Geográfico** | País: Perú <br> Zona de operación: Zonas urbanas y rurales, especialmente aquellas asociadas a rutas de transporte de gases inflamables. | País: Perú <br> Zona de operación: Regiones que abarcan trayectos donde se movilizan materiales peligrosos.|  
| **Psicográfico** | Clase Social: Media <br> Estilo de Vida: Conductores experimentados en el manejo de materiales peligrosos, enfocados en la seguridad y la reducción de riesgos durante sus actividades laborales. | Clase social: No es relevante dado que puede incluir pequeñas empresas de transporte o grandes corporaciones. <br> Estilo de vida: Empresas orientadas a garantizar la seguridad y la eficiencia en el transporte de materiales peligrosos, con interés en la innovación y mejora continua de sus protocolos. |  
| **Demográfico** | Edad: 25 a 55 años <br> Nivel de Ingreso: No determinante; enfocado en conductores profesionales con trayectoria en el manejo de vehículos pesados. | Edad: 30 a 60 años <br> Nivel de ingreso: No es un factor clave; dirigido a empresas que administran flotas dedicadas al transporte de materiales peligrosos. |

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
<th colspan="5">Permite reconocer las ventajas competitivas y áreas de mejora de "Chemtrack" frente a competidores clave, facilitando el diseño de estrategias eficaces para destacarse en el sector agrícola y atraer a agricultores y comerciantes.</th>
</tr>
<tr class="header">
<th></th>
<th></th>
<th>Chemtrack</th>
<th>Grupo Caresny</th>
<th>Dachser</th>
<th>Cargo & Transport</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil</th>
<th>Overview</th>
<th>Plataforma tecnológica integral con sensores IoT para alertar y monitorear condiciones críticas durante el transporte de materiales peligrosos.</th>
<th>Empresa tradicional del rubro logístico, enfocada en soluciones personalizadas.</th>
<th>Multinacional con cobertura global y servicios de transporte terrestre, marítimo y aéreo.</th>
<th>Especialista en carga pesada y bienes industriales, con enfoque en mercados en crecimiento.</th>
</tr>
<tr class="header">
<th>Ventaja competitiva</th>
<th>Seguridad en tiempo real con sensores que detectan fugas, temperatura, presión y movimiento</th>
<th>Amplia red de transporte y servicios integrados.</th>
<th>Gran infraestructura global y experiencia en logística compleja.</th>
<th>Capacidad para operar en entornos difíciles y con cargas especiales.</th>
</tr>
<tr class="odd">
<th rowspan="2">Perfil de Marketing</th>
<th>Mercado Objetivo</th>
<th>Empresas del sector químico, petrolero y otras que gestionan transporte de materiales peligrosos.</th>
<th>Negocios que buscan servicios logísticos a medida, principalmente retail y consumo masivo.</th>
<th>Empresas internacionales con operaciones logísticas complejas.</th>
<th>Industrias pesadas y proyectos de infraestructura en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Estrategias de marketing</th>
<th>Promoción de seguridad y cumplimiento normativo como elementos diferenciadores.</th>
<th>Contratos duraderos y atención personalizada.	</th>
<th>Uso de infraestructura avanzada y tecnología para la cadena de suministro.</th>
<th>Reputación de fiabilidad y capacidad para manejar operaciones complejas.</th>
</tr>
<tr class="odd">
<th rowspan="3">Perfil de Producto</th>
<th>Productos &amp; Servicios</th>
<th>Monitoreo IoT especializado en transporte seguro de productos peligrosos.	</th>
<th>Servicios de transporte terrestre, almacenamiento y logística.</th>
<th>Transporte multimodal y soluciones integradas de cadena de suministro.</th>
<th>Transporte de gran escala, logística para proyectos industriales.</th>
</tr>
<tr class="header">
<th>Precios y Costos</th>
<th>Modelo por suscripción ajustable según cantidad de sensores y funcionalidades.</th>
<th>Tarifas competitivas y adaptables al tipo de servicio.	</th>
<th>Costos variables según la complejidad y cobertura requerida.</th>
<th>Costos determinados por tipo de carga y nivel de dificultad.</th>
</tr>
<tr class="odd">
<th><p>Canales de distribución</p>
<p>(Web y/o Móvil)</p></th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
<th>Plataforma web y móvil accesible desde distintos dispositivos.</th>
</tr>
<tr class="header">
<th rowspan="5">Análisis SWOT</th>
<th colspan="5">Realice esto para su startup y sus competidores. Sus
fortalezas deberían apoyar sus oportunidades y contribuir a lo que
ustedes definen como su posible ventaja competitiva.</th>
</tr>
<tr class="odd">
<th>Fortalezas</th>
<th>Alta innovación tecnológica, monitoreo en tiempo real, y plataforma digital robusta.</th>
<th>Red logística consolidada, relaciones sólidas con clientes.</th>
<th>Cobertura internacional, experiencia en logística avanzada.</th>
<th>Capacidad para manejar cargas especiales, presencia fuerte en mercados emergentes.</th>
</tr>
<tr class="header">
<th>Debilidades</th>
<th>Alta dependencia tecnológica, posibles costos iniciales elevados.</th>
<th>Falta de innovación frente a competidores modernos.</th>
<th>Costos altos, fuerte presencia en mercados maduros más que emergentes.</th>
<th>Cobertura global limitada frente a otras multinacionales.</th>
</tr>
<tr class="odd">
<th>Oportunidades</th>
<th>Mayor demanda por soluciones seguras, posibilidad de expansión internacional.	</th>
<th>Potencial para adoptar nuevas tecnologías y expandirse.	</th>
<th>Crecimiento en mercados emergentes, enfoque sostenible.	</th>
<th>Posibilidad de ingresar a nuevos sectores y alianzas tecnológicas.</th>
</tr>
<tr class="header">
<th>Amenazas</th>
<th>Competencia con grandes corporaciones con más recursos, cambios en la regulación.	</th>
<th>Presión de empresas más tecnológicas y competitivas.	</th>
<th>Volatilidad económica global, competencia en mercados emergentes.	</th>
<th>Restricciones ambientales más estrictas, competencia en precios.</th>
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

A continuación, se diseñaron entrevistas dirigidas a los dos segmentos objetivos definidos para el proyecto. Las preguntas fueron elaboradas con el fin de generar respuestas abiertas y detalladas por parte de los entrevistados, permitiendo así obtener información valiosa que nos ayude a comprender mejor sus necesidades. Cabe mencionar que las preguntas de introducción no están incluidas en esta lista; sin embargo, se realizarán al inicio de cada entrevista.

**Segmento objetivo: Transportistas**

El objetivo de las preguntas del segmento objetivo de los transportistas es identificar las necesidades, desafíos y preferencias de los transportistas en relación con la seguridad y el monitoreo de cargas peligrosas, con el propósito de diseñar una solución tecnológica que mejore su eficiencia y protección durante el transporte.

**Preguntas de introducción**

- ¿Cúal es tu nombre?
- ¿Cuantos años tienes?
- ¿En que distrito vives actualmente?

**Preguntas prinicipales**

- ¿Qué sistemas de seguridad utilizas actualmente para evitar incidentes durante el transporte de gases inflamables?

- ¿Has vivido alguna situación relacionada con fugas de gas u otro tipo de incidente? En caso afirmativo, ¿cómo respondiste ante ello?

- ¿Qué dificultades o problemas encuentras con mayor frecuencia en tu labor como transportista?

- ¿Cuentas con alguna tecnología o dispositivo que te permita monitorear la seguridad de tu carga mientras estás en ruta? ¿Qué ventajas y desventajas has percibido?

- ¿Estarías dispuesto a incorporar una solución tecnológica que permita supervisar en tiempo real las condiciones del cargamento? ¿Cuál sería tu motivación?

- ¿Qué tipos de sensores consideras adecuados para el monitoreo de combustibles durante el transporte en vehículos?

- ¿Qué clase de notificaciones o alertas crees que serían más efectivas para prevenir posibles fugas de gases durante el traslado?

- ¿Cuál sería tu canal preferido para recibir este tipo de alertas (por ejemplo, app móvil, SMS, entre otros)?

- ¿Qué obstáculos crees que podrían dificultar la incorporación de nuevas tecnologías de monitoreo en tu trabajo diario?

- ¿Qué funcionalidades considerarías imprescindibles en una solución tecnológica emergente para adoptarla como parte de tu rutina?

- ¿Cuál es tu opinión sobre las tecnologías actuales que existen en el mercado enfocadas en la seguridad del transporte de materiales peligrosos?

- ¿Qué mejoras consideras necesarias en estas soluciones para que resulten más eficientes y útiles?

- ¿Tu vehículo cuenta con una pantalla que permita la interacción con algún sistema operativo?

- ¿Qué dispositivos usas con mayor frecuencia durante tus jornadas laborales?

**Segmento objetivo: Empresas de transporte de productos peligrosos**

El objetivo de las preguntas del segmento objetivo de las empresas de transporte de productos peligrosos es evaluar las estrategias de seguridad, tecnologías actuales y disposición de las empresas de transporte para adoptar soluciones IoT, con el fin de identificar oportunidades de mejora y diseñar una herramienta que optimice la gestión y seguridad de las operaciones logísticas.

**Preguntas de introducción**

- ¿Cúal es tu nombre?
- ¿Cuantos años tienes?
- ¿En que distrito vives actualmente?

**Preguntas prinicipales**

- ¿Qué medidas de seguridad aplica tu empresa para proteger tanto al personal como a la carga durante el traslado de productos peligrosos?

- ¿Cómo se lleva a cabo la formación del personal en temas de prevención de incidentes y actuación ante emergencias?

- ¿Qué tecnologías o herramientas están actualmente en uso en tu empresa para supervisar la seguridad de las cargas peligrosas?

- ¿Qué tipos de sensores consideras más apropiados para el monitoreo de combustibles en vehículos?

- ¿Tu empresa estaría interesada en adoptar una solución IoT para supervisar en tiempo real la seguridad de los cargamentos? ¿Por qué razón?

- ¿Qué beneficios esperas lograr mediante la implementación de una tecnología IoT enfocada en la seguridad?

- ¿Qué inquietudes podrían surgir respecto a la adopción de esta solución en tu organización?

- ¿De qué forma prefieres que tu empresa reciba alertas sobre posibles riesgos durante el transporte?

- ¿Cómo impactarían estas notificaciones en las decisiones operativas de tu empresa?

- ¿Consideras que una solución de monitoreo basada en IoT podría convertirse en una ventaja competitiva? ¿De qué manera?

- ¿Qué características clave debería tener esta solución para destacar frente a otras propuestas tecnológicas del mercado?

### 2.2.2. Registro de entrevistas

**Segmento objetivo: Transportistas**

***Primera Entrevista:***

Nombres y apellidos: Carolina Torres Torres

Edad: 27

Inicio: 0:00

Fin: 5:07

Duración: 5:07

Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202114248_upc_edu_pe/ESJ2p17qJopCnR5y_ExwldIBFC13m5znCcQtlcKynGLgHw?e=0XxBFT&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

![entrevista1t](https://i.imgur.com/0MFB9Rr.png)

Resumen:

- Carolina es una transportista de productos reactivos y actualmente cuenta con un sistema de GPS y un monitoreo de temperatura básico instalado en su vehículo. Ella nos comentó que su principal motivación para incorporar una solución tecnológica adicional es mejorar su seguridad, ya que esto le permitiría prevenir un mayor número de accidentes que podrían poner en riesgo tanto su integridad como la de las personas a su alrededor. Además, menciona que esta solución también le brindaría mayor tranquilidad durante sus recorridos. Carolina prefiere que las notificaciones se emitan mediante alertas sonoras, ya que considera que así podrá estar más atenta a ellas mientras conduce. En cuanto a las funcionalidades que considera imprescindibles, destaca el monitoreo en tiempo real, las alertas automáticas y el acceso inmediato desde la central.


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

Nombre: Arnhol Castrejon

Inicio: 0:00

Fin: 4:30

Duración: 4:30

Link: 

<img width="1156" height="531" alt="image" src="https://github.com/user-attachments/assets/735a624b-fe54-4c31-b010-2150dd54bdc2" />


Hemos entrevistado a Arnold Alfred, de 26 años, propietario de una pequeña empresa dedicada al transporte de gas en Villa El Salvador. Actualmente, cuentan con medidas básicas de seguridad como la revisión de las unidades antes de cada viaje, el uso de extintores y la entrega de chalecos y cascos al personal. La capacitación se realiza mediante charlas internas y simples recomendaciones de prevención.
En cuanto a tecnología, la empresa utiliza únicamente GPS para el seguimiento de los vehículos, sin otras herramientas de supervisión. Arnold considera que los sensores de fuga de gas y de temperatura serían los más adecuados para su rubro, y manifestó interés en implementar soluciones IoT para mejorar la seguridad en tiempo real, ya que estas permitirían reaccionar más rápido ante emergencias y generar mayor confianza en los clientes.
Entre los beneficios que espera obtener menciona el mayor control de la carga, la reducción de riesgos y la prevención de pérdidas. Sin embargo, también señaló inquietudes relacionadas con el costo de implementación y la adaptación del personal. Finalmente, indicó que preferiría recibir alertas mediante mensajes al celular y aplicaciones móviles, y considera que una solución IoT confiable, fácil de usar y de bajo costo representaría una ventaja competitiva frente a otras empresas del sector.

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

Las entrevistas realizadas tanto a conductores como a representantes de empresas que transportan productos peligrosos han permitido identificar patrones comunes que subrayan la necesidad de fortalecer la seguridad, incorporar monitoreo en tiempo real y adoptar nuevas tecnologías, especialmente aquellas basadas en IoT. A continuación, se detallan los principales hallazgos:

- Actualmente, muchas empresas dependen principalmente de la experiencia del conductor y de acciones reactivas como el uso de extintores o la comunicación básica para manejar emergencias. Esto evidencia una oportunidad para reforzar los protocolos de seguridad a través de capacitaciones más completas y el uso de herramientas tecnológicas que permitan anticiparse a posibles incidentes.

- El uso de dispositivos tecnológicos como sensores de gas, temperatura y presión aún es escaso, lo cual representa una limitación significativa. Tanto las empresas como los transportistas podrían beneficiarse ampliamente de implementar soluciones IoT que proporcionen monitoreo constante y en tiempo real del estado de la carga, aumentando así los niveles de seguridad.

- Existe un marcado interés en adoptar tecnologías IoT, ya que se perciben como medios eficaces para mejorar la seguridad, hacer más eficientes los procesos logísticos y cumplir con normativas vigentes. Esta disposición abre la puerta a la introducción de soluciones que cubran estas necesidades específicas.

- No obstante, pese al interés, existen ciertos obstáculos que dificultan su adopción. Entre ellos destacan los costos asociados a la inversión inicial y los posibles problemas de conectividad en zonas remotas. Por ello, es esencial que las empresas proveedoras de estas tecnologías garanticen soluciones confiables, accesibles y fáciles de operar.

- La necesidad de recibir alertas en tiempo real es una demanda clave. Cualquier sistema basado en IoT debe incluir notificaciones precisas y oportunas, que no interfieran con las actividades del conductor, pero que faciliten la toma de decisiones inmediatas en caso de riesgo.

- La integración de tecnologías emergentes representa una oportunidad para que las empresas de transporte se posicionen como referentes en seguridad dentro del sector. Aquellas que adopten estas innovaciones de forma anticipada no solo optimizarán sus procesos, sino que también podrán atraer más clientes al ofrecer servicios más seguros y confiables.

![image](https://github.com/user-attachments/assets/59ec18cf-bdea-47e8-8ca3-e3801edbbf28)

En resumen, los testimonios obtenidos reflejan una necesidad concreta de actualizar los sistemas de seguridad actuales y apostar por soluciones tecnológicas como el IoT. Aunque el interés es alto, es fundamental abordar las preocupaciones sobre costos y conectividad. Las empresas que logren implementar estas tecnologías de forma efectiva obtendrán una ventaja competitiva y podrán mejorar considerablemente la seguridad en sus operaciones.

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

### 2.3.3. Journey Mapping

<img src="https://i.imgur.com/b1FuQz1.png" style="width:80%">
<img src="https://i.imgur.com/SEZ5r2H.png" style="width:80%">

### 2.3.4. Empathy Mapping

**Transportistas de combustibles peligrosos**

![Empathy map](https://github.com/user-attachments/assets/ed0e74aa-de6d-4e8f-9ca6-e235f146f6c7)

**Empresas de transporte de productos peligrosos**

![Empathy map (1)](https://github.com/user-attachments/assets/ef04d9c0-99cf-47e2-8c70-5f579319d6f7)

### 2.3.5. As-is Scenario Mapping

![image](https://github.com/user-attachments/assets/753224a7-ec79-412f-9fe9-7a5cf13b7c0b)
![image](https://github.com/user-attachments/assets/233c4c8e-0a59-472f-863e-d9023194cdc5)

## 2.4. Ubiquitous Language

Términos y Definiciones

**Dashboard (Panel de Control)**
Un panel de control es un componente de la interfaz de usuario que proporciona una visión general del estado del transporte, incluyendo datos en tiempo real de sensores de gas y temperatura. Permite a los operadores monitorear alertas de seguridad y la ubicación de la carga.

**Incident List (Listado de Incidentes)**
Una pantalla que presenta una lista de todos los incidentes reportados durante los servicios de transporte. Incluye detalles como niveles de gas peligrosos detectados, cambios de temperatura anormales y acciones correctivas tomadas.

**Incident Notification (Notificación de Incidentes)**
El proceso por el cual los transportistas y empresarios son informados de forma automática y en tiempo real sobre fugas de gas, temperaturas fuera del rango seguro u otros problemas detectados por los sensores IoT instalados en los vehículos de transporte.

**Monitoring Package (Monitoreo de Carga)**
Seguimiento en tiempo real del estado de la carga, utilizando sensores IoT para registrar niveles de gas, temperatura y otros parámetros críticos para evitar accidentes durante el transporte de productos peligrosos.

**Transport Service (Servicio de Transporte)**
El conjunto de operaciones logísticas, incluyendo el monitoreo en tiempo real y la detección temprana de riesgos, destinados a transportar bienes peligrosos como gasolina o gas desde un punto de origen hasta su destino final.

**Transporters (Transportistas)**
Personas o empresas responsables de supervisar los vehículos equipados con sensores IoT para garantizar un transporte seguro de productos peligrosos.

**Business Owner (Empresario)**
Persona o entidad encargada de gestionar la logística y la coordinación del transporte de bienes peligrosos, supervisando las métricas de seguridad proporcionadas por la solución IoT.

**Incident Report (Reporte de Incidente)**
Documento generado automáticamente que detalla un incidente detectado por los sensores IoT, como fugas de gas o incrementos bruscos de temperatura. Incluye la causa, impacto y medidas correctivas tomadas.

**Sensor Alerts (Alertas de Sensores)**
Notificaciones automáticas enviadas a través de la plataforma cuando los sensores IoT detectan condiciones peligrosas como niveles altos de gas o temperaturas fuera del rango seguro.

**Transporter Rating (Calificación de Transportistas)**
Evaluación de la calidad del servicio ofrecido por los transportistas basada en su capacidad de respuesta a alertas de seguridad y su cumplimiento con los estándares de manejo de bienes peligrosos.

**Transporter Registration (Registro de Transportistas)**
Proceso mediante el cual un transportista se registra en la plataforma para vincular su flota de vehículos con sensores IoT y ofrecer servicios de transporte seguro.

**Login (Iniciar Sesión)**
El proceso mediante el cual un usuario accede a su cuenta en la plataforma para monitorear, gestionar o responder a alertas relacionadas con el transporte de bienes peligrosos.

**Authentication Policy (Política de Autenticación)**
Conjunto de reglas que garantizan que solo usuarios autorizados, como transportistas y empresarios, puedan acceder a la plataforma y monitorear los datos IoT.

**Transport Route (Ruta de Transporte)**
El trayecto definido que debe seguir el transportista, monitoreado en tiempo real para garantizar el cumplimiento de condiciones seguras a lo largo del recorrido.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
![image](https://github.com/user-attachments/assets/c5d9bbff-01ac-4111-8638-5a62cc7b1e40)

![image](https://github.com/user-attachments/assets/8027d267-90bf-4513-8589-bc8096e62f76)


## 3.2. User Stories

| **Epic ID** | **Epic**                                             | **Descripción**                                                                           |
|-------------|-------------------------------------------------------|--------------------------------------------------------------------------------------------|
| EP01        | Gestión de Transportistas y Documentación de Cumplimiento | Gestión y mantenimiento de perfiles de transportistas, verificación de permisos, y certificaciones. |
| EP02        | Gestión de Solicitudes de Transporte                 | Publicación y administración de solicitudes de transporte por parte de las empresas.       |
| EP03        | Seguimiento en Tiempo Real            | Monitoreo en tiempo real del transporte de productos peligrosos.|
| EP04        | Acciones de prevención            | Acciones a realizar como respuesta ante posibles incidentes que puedan ocurrir con la carga.|

---

| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** |
|---------------------|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **Epic / Story ID** | **Título**                                         | **Descripción**                                                                                                                                                        | **Criterios de Aceptación**                                                                                                                                                                                                                                       | **Relacionado con (Epic ID)** 
| US01                | Monitoreo del Vehículo                             | Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.                                                         | **Escenario 1: Realizar monitoreo**. Dado que el transportista necesite asegurar el estado del vehículo, cuando inicie la función de monitoreo, entonces el sistema presentará un reporte con el estado del vehículo. **Escenario 2: Error en el monitoreo**. Dado que el sistema presenta un error durante la verificación del estado del vehículo, cuando el transportista intente iniciar la función de monitoreo, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo realizar el monitoreo y sugerir intentar nuevamente o contactar soporte. | EP03                          |
| US02                | Notificaciones de Mantenimiento Preventivo         | Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.                                                                  | **Escenario 1: Notificación de mantenimiento**. Dado que el vehículo se acerque a la fecha de mantenimiento, cuando el sistema detecte la proximidad de esta fecha, entonces se enviará una notificación al transportista. **Escenario 2: Error en la notificación**. Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el transportista revise el sistema, entonces este deberá mostrar un mensaje indicando que hubo un problema y permitir al transportista revisar manualmente las fechas de mantenimiento programadas.         | EP04                          |
| US03                | Verificación de Rutas Seguras                      | Como transportista, quiero verificar rutas seguras antes de iniciar un viaje, para minimizar riesgos.                                                                                                         | **Escenario 1: Verificar ruta**. Dado que el transportista necesite planificar una ruta, cuando el sistema identifique rutas peligrosas, entonces sugerirá rutas alternativas más seguras. **Escenario 2: Error al verificar ruta**. Dado que el sistema no puede cargar las rutas, cuando el transportista intente verificar rutas seguras, entonces el sistema deberá mostrar un mensaje de error e indicar al transportista que intente más tarde o contacte soporte técnico.                                                           | EP03                          |
| US04                | Reporte de Estado del Vehículo                     | Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.                                                                                    | **Escenario 1: Generar reporte**. Dado que el transportista complete la revisión del vehículo, cuando se complete la revisión, entonces el sistema permitirá generar un reporte que puede ser enviado al supervisor. **Escenario 2: Error al generar reporte**. Dado que el sistema falle en generar el reporte, cuando el transportista intente crear el reporte después de la revisión, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo generar el reporte y sugerir reintentar o guardar los datos manualmente. | EP03                          |
| US05                | Seguimiento en Tiempo Real de los Transportes Activos| Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.          | **Escenario 1: Seguimiento del Transporte en Tiempo Real**. Dado que hay un transporte activo en curso, cuando la empresa accede a la sección de seguimiento de transportes, entonces el sistema muestra la ubicación actual, la velocidad y el estado del transporte en tiempo real en un mapa. **Escenario 2: Error en el seguimiento en tiempo real**. Dado que el sistema falle en actualizar la ubicación del transporte, cuando la empresa intente realizar el seguimiento en tiempo real, entonces el sistema deberá mostrar un mensaje indicando que no se puede obtener la ubicación y permitir reintentar o contactar al transportista directamente. | EP03                          |
| US06                | Verificación de Permisos de Transportistas         | Como empresa de transporte de productos peligrosos, quiero verificar los permisos y certificaciones de los transportistas antes de contratarlos.                                                              | **Escenario 1: Verificación de Permisos y Certificaciones**. Dado que la empresa busca contratar un transportista, cuando selecciona un transportista de la lista de disponibles, entonces el sistema muestra un detalle de los permisos, certificaciones y calificaciones del transportista. **Escenario 2: Error al verificar permisos**. Dado que el sistema no pueda cargar los detalles del transportista, cuando la empresa intente verificar permisos y certificaciones, entonces el sistema deberá mostrar un mensaje de error y sugerir intentar más tarde o contactar soporte. | EP02                          |
| US07                | Recibir Notificaciones de Incidentes en Tiempo Real | Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).                     | **Escenario 1: Recepción de Notificaciones de Incidentes**. Dado que un transporte está en curso, cuando ocurre un incidente o evento inesperado, entonces el sistema envía una notificación en tiempo real a la empresa con detalles del incidente y posibles acciones a tomar. **Escenario 2: Error al recibir notificación de incidente**. Dado que el sistema falle en enviar la notificación de incidente, cuando la empresa espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje indicando que no se pudo enviar la notificación y sugerir verificar el estado del transporte manualmente o contactar al transportista. | EP04                          |
| US08                | Registro de Transportista de Combustibles Peligrosos| Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.          | **Escenario 1: Validación del Registro de Transportista**. Dado que el transportista accede a la página de registro, cuando completa todos los campos requeridos y adjunta los documentos de certificación, entonces el sistema valida la información y confirma el registro si todos los datos son correctos. **Escenario 2: Error al registrar transportista**. Dado que el sistema falle en procesar el registro, cuando el transportista intente registrarse, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo completar el registro y sugerir reintentar o contactar soporte técnico.                   | EP01                          |
| US09                | Notificación de Nuevas Solicitudes de Transporte    | Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.                                                                                                           | **Escenario 1: Recepción de Notificación de Nueva Solicitud**. Dado que una empresa de transporte publica una nueva solicitud de transporte de combustibles, cuando el transportista tiene los permisos adecuados y disponibilidad, entonces el transportista recibe una notificación y puede optar por aceptar o rechazar la solicitud. **Escenario 2: Error al recibir notificación de nueva solicitud**. Dado que el sistema falle en enviar la notificación, cuando el transportista espere recibir dicha notificación, entonces el sistema deberá mostrar un mensaje de error y sugerir revisar manualmente las solicitudes publicadas o contactar a la empresa de transporte. | EP02                          |
| US10                | Actualización de Estado del Transporte              | Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).                                                                     | **Escenario 1: Actualización del Estado del Transporte en Curso**. Dado que el transportista ha aceptado un trabajo y está en ruta, cuando hay un cambio en el estado del transporte, entonces el transportista puede actualizar el estado y la empresa recibe una notificación con el estado actualizado. **Escenario 2: Error al actualizar estado del transporte**. Dado que el sistema falle en procesar la actualización del estado del transporte, cuando el transportista intente actualizar el estado, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo actualizar el estado y sugerir reintentar o contactar a la empresa directamente. | EP02                          |
| US11                | Publicación de Solicitudes de Transporte de Productos Peligrosos | Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.                              | **Escenario 1: Publicación de Solicitud de Transporte**. Dado que la empresa accede a la sección de solicitud de transporte, cuando completa el formulario de solicitud con toda la información requerida, entonces la solicitud se publica y los transportistas calificados reciben notificaciones. **Escenario 2: Error al publicar solicitud de transporte**. Dado que el sistema falle en procesar la solicitud de transporte, cuando la empresa intente publicar la solicitud, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo publicar la solicitud y sugerir reintentar o contactar soporte técnico. | EP02                          |
| US12                | Visualización de Transportistas Disponibles         | Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.                   | **Escenario 1: Visualización de Transportistas Calificados**. Dado que la empresa ha publicado una solicitud de transporte, cuando hay transportistas calificados disponibles, entonces el sistema muestra una lista de transportistas con sus detalles de calificación, precio, y disponibilidad. **Escenario 2: Error al visualizar transportistas disponibles**. Dado que el sistema falle en cargar la lista de transportistas disponibles, cuando la empresa intente visualizar transportistas calificados, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo cargar la lista y sugerir reintentar o contactar soporte técnico. | EP02                          |
| US13                | Acceso a Historial de Transportes Realizados        | Como transportista de combustibles peligrosos, quiero acceder a un historial de todos los transportes que he realizado, con detalles sobre la carga, rutas, y tiempos de entrega.                            | **Escenario 1: Visualización del Historial de Transportes**. Dado que el transportista está en su panel de control, cuando selecciona la opción de historial de transportes, entonces el sistema muestra una lista de transportes realizados con detalles relevantes como fechas, rutas, tipos de combustible transportado, y tiempos de entrega. **Escenario 2: Error al visualizar historial de transportes**. Dado que el sistema falle en cargar el historial de transportes, cuando el transportista intente acceder a su historial, entonces el sistema deberá mostrar un mensaje de error indicando que no se pudo cargar el historial y sugerir reintentar o contactar soporte técnico. | EP01                          |
| US14                | Control de tiempos de conducción de transporte       | Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento de las horas de conducción por los transportistas activos para evitar manejen en estado de cansancio.                                                      | **Escenario 1: Visualización del tiempo de conducción en curso**. Dado que hay un transporte actualmente en operación, cuando la empresa acceda a la sección de seguimiento de transportes, entonces el sistema deberá mostrar el total de horas que el conductor ha estado manejando durante la jornada actual. **Escenario 2: Fallo en la obtención del tiempo de conducción**. Dado que el sistema no puede recuperar la información sobre las horas de conducción del transportista, cuando la empresa intente acceder al seguimiento en tiempo real, entonces el sistema deberá mostrar un mensaje de error indicando que no fue posible obtener los datos, y ofrecer la opción de reintentar o contactar directamente al conductor.      | EP03                          |
| US15                | Notificación de tiempo de conducción de transporte en exceso        | Como transportista de combustibles peligrosos, quiero recibir una notificación en caso de excederme el total de horas seguidas recomendadas de conducción por día para evitar posibles accidentes al manejar en estado de cansancio.                                                      | **Escenario 1: Visualización del tiempo de conducción en curso**. Dado que el transportista ha excedido la cantidad de horas seguidas recomendadas de conducción por día, cuando el sistema detecte el exceso de tiempo de conducción, entonces se enviara una notificación al conductor que le indique que debe parar sus turnos por el día y que realice un relevo en la conducción con otro conductor del sistema. **Escenario 2: Error en la visualización de la notificación**. Dado que el sistema no logra mostrar correctamente la notificación al transportista, cuando el transportista haya superado el máximo de horas, entonces generará automaticamente una alerta sonora dentro del vehículo.      | EP04                          |
| US16                | Landing Page responsive       | Como visitante, deseo visitar la landing page desde cualquier dispositivo.                                                      | **Escenario 01**: Dado que el visitante necesita una aplicación web o móvil para mejorar su servicio, cuando busque en el navegador "Monitorear productos peligrosos", entonces accede a la landing page y visualiza las funcionalidades que le ofrece la aplicación web o móvil. **Escenario 02**: Dado que el visitante desea una aplicación web o móvil con características puntuales de seguridad de transporte de productos peligrosos, cuando navegue por la landing page y se encuentre en la sección de beneficios y funcionalidades, entonces visualizará la funcionalidad que se desea y se decide en usar la aplicación web o móvil.      | EP01                          |
| US17                | Visualización de características de la aplicación web o móvil en Landing Page | Como visitante, deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo.                                  | **Escenario 01**: Dado que el visitante accede a la landing page desde su celular, cuando visite la landing page desde el navegador de su celular, entonces la landing page con su diseño responsive puede visualizarse adecuadamente en el navegador del dispositivo móvil. **Escenario 02**: Dado que el visitante recomienda la landing page mediante un dispositivo móvil, cuando el otro visitante recomendado acceda a la landing page desde otro dispositivo móvil con resolución diferente, entonces la landing page se mostrará completamente visible y ordenada dado que es responsive.            | EP01                          |
| US18                | Botón Call to Action       | Como visitante, deseo ir a la aplicación web o móvil desde un solo botón desde la landing page.                                    | **Escenario 01**: Dado que el visitante desea usar la aplicación web o móvil, cuando esté en la sección donde se encuentre el botón call to action y lo use, entonces será dirigido a la aplicación web o móvil. **Escenario 02**: Dado que el visitante quedó satisfecho con la información brindada en la landing page, cuando desee empezar a usar la aplicación web o móvil, entonces puede acceder a ella de forma rápida mediante el botón call to action            | EP01                          |
| **TS-01** | Implementación de Monitoreo del Vehículo           | Como desarrollador, quiero implementar la funcionalidad de monitoreo del vehículo para que los transportistas puedan verificar el estado del vehículo antes de iniciar un viaje. | **Background:** Implementar el endpoint `GET /api/vehicle-monitoring/{vehicleId}` para obtener el estado actual del vehículo.<br><br>**Scenario 01: Obtener estado del vehículo**<br>Dado que el transportista quiere verificar el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo existe en la base de datos, entonces el sistema devuelve un `response` con `status 200` y los detalles del estado del vehículo en el `Response Body`.<br><br>**Scenario 02: Error al obtener estado del vehículo**<br>Dado que el sistema falla en obtener el estado del vehículo, cuando el cliente realiza una solicitud `GET` a `/api/vehicle-monitoring/{vehicleId}`, y el vehículo no existe o hay un problema en el sistema, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP03**                   |
| **TS-02** | Implementación de Notificaciones de Mantenimiento Preventivo | Como desarrollador, quiero implementar el sistema de notificaciones de mantenimiento preventivo para alertar a los transportistas cuando se acerque la fecha de mantenimiento del vehículo. | **Background:** Configurar un sistema de notificaciones automáticas que envíe alertas a través de `POST /api/notifications/maintenance`.<br><br>**Scenario 01: Envío de notificación de mantenimiento**<br>Dado que la fecha de mantenimiento del vehículo se acerca, cuando el sistema detecta que faltan X días para la fecha de mantenimiento, entonces se envía una notificación al transportista y se devuelve un `response` con `status 200` confirmando el envío exitoso.<br><br>**Scenario 02: Error en el envío de notificación de mantenimiento**<br>Dado que el sistema falla en enviar la notificación de mantenimiento, cuando el sistema intenta enviar la notificación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP04**                   |
| **TS-03** | Implementación de Verificación de Permisos de Transportistas | Como desarrollador, quiero implementar la funcionalidad para verificar los permisos y certificaciones de los transportistas, para que las empresas puedan tomar decisiones informadas al contratarlos. | **Background:** Crear un endpoint `GET /api/transporters/{transporterId}/certifications` que devuelva los permisos y certificaciones de un transportista específico.<br><br>**Scenario 01: Obtener permisos y certificaciones del transportista**<br>Dado que la empresa necesita verificar los permisos de un transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, y el transportista tiene permisos registrados, entonces el sistema devuelve un `response` con `status 200` y los detalles de las certificaciones en el `Response Body`.<br><br>**Scenario 02: Error al obtener permisos y certificaciones**<br>Dado que el sistema falla en obtener los permisos del transportista, cuando el cliente realiza una solicitud `GET` a `/api/transporters/{transporterId}/certifications`, entonces el sistema devuelve un `response` con `status 500` o `404` y un mensaje de error adecuado en el `Response Body`. | **EP02**                   |
| **TS-04** | Implementación de Monitoreo en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad de monitoreo en tiempo real utilizando la Edge API, para que los dispositivos IoT puedan enviar datos de ubicación, velocidad, estado y horas de conducción directamente desde el transporte. | **Background:** Configurar un endpoint en la Edge API `POST /edge/vehicle-monitoring` que reciba datos en tiempo real desde dispositivos IoT instalados en los vehículos.<br><br>**Scenario 01: Recepción de datos en tiempo real**<br>Dado que el vehículo está en movimiento, cuando el dispositivo IoT envía datos de ubicación, velocidad, estado y horas de conducción al endpoint `/edge/vehicle-monitoring`, entonces la Edge API procesa y almacena los datos en la base de datos central, devolviendo un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de datos**<br>Dado que el sistema IoT falla en enviar los datos al Edge API, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/vehicle-monitoring` y ocurre un error de conexión o datos corruptos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP03**                   |
| **TS-05** | Implementación de Notificaciones de Incidentes en Tiempo Real a través de Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT envíen notificaciones de incidentes en tiempo real a través de la Edge API, para que la empresa pueda reaccionar rápidamente a situaciones críticas. | **Background:** Configurar un endpoint en la Edge API `POST /edge/incident-notifications` que reciba alertas de incidentes desde los sensores IoT del vehículo.<br><br>**Scenario 01: Recepción de notificación de incidente**<br>Dado que ocurre un incidente durante el transporte, cuando el dispositivo IoT detecta un evento crítico (accidente, desviación, etc.) y envía datos al endpoint `/edge/incident-notifications`, entonces la Edge API procesa la alerta, notifica a la empresa, y devuelve un `response` con `status 200` para confirmar la recepción exitosa.<br><br>**Scenario 02: Error en la recepción de notificación de incidente**<br>Dado que el sistema IoT falla en enviar la notificación de incidente, cuando el dispositivo IoT intenta enviar datos al endpoint `/edge/incident-notifications` y ocurre un error de comunicación, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP04**                   |
| **TS-06** | Implementación de Actualización de Estado del Vehículo desde Edge API | Como desarrollador, quiero implementar la funcionalidad para que los dispositivos IoT en el vehículo actualicen el estado del transporte en tiempo real a través de la Edge API, para que la empresa siempre tenga información precisa sobre el progreso del viaje. | **Background:** Configurar un endpoint en la Edge API `PUT /edge/vehicle-status/{vehicleId}` que permita a los dispositivos IoT actualizar el estado del vehículo (en camino, retraso, entregado, etc.).<br><br>**Scenario 01: Actualización de estado exitosa**<br>Dado que el vehículo cambia su estado (por ejemplo, llega al destino), cuando el dispositivo IoT envía una actualización de estado al endpoint `/edge/vehicle-status/{vehicleId}`, entonces la Edge API actualiza la información en el sistema central y devuelve un `response` con `status 200` para confirmar la actualización exitosa.<br><br>**Scenario 02: Error en la actualización del estado del vehículo**<br>Dado que el sistema IoT falla en actualizar el estado del vehículo, cuando el dispositivo IoT intenta enviar una actualización al endpoint `/edge/vehicle-status/{vehicleId}` y ocurre un error de transmisión o de datos, entonces el sistema devuelve un `response` con `status 500` y un mensaje de error adecuado. | **EP02**                   |


## 3.3. Impact Mapping

**Transportistas de combustibles peligrosos**

![Impact map Transportista](https://i.imgur.com/isPyVui.png)

**Empresas de transporte de productos peligrosos**

![Impact map Empresa de tansportes](https://i.imgur.com/5o4y4SJ.png)



## 3.4. Product Backlog

A continuación, se mostrará la herramienta Product Backlog, lista de trabajo ordenado por la prioridad para el equipo de desarrollo de GreatMinds.

|**#Orden**|**User Story Id**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8)**|
| :-: | :-: | :-: | :-: | :-: |
|01|US17|Visualización de características de la aplicación web o móvil web en Landing Page|Como visitante deseo ver las principales características de la aplicación web o móvil para decidir si usar el producto en mi trabajo|5|
|02|US16|Landing Page responsive| Como visitante deseo visitar la landing page desde cualquier dispositivo.|5|
|03|US18|Botón Call to Action|Como visitante deseo ir a la aplicación web o móvil web desde un solo botón desde la landing page |5|
|04|US11|Publicación de Solicitudes de Transporte de Productos Peligrosos|Como empresa de transporte de productos peligrosos, quiero publicar solicitudes de transporte detallando el tipo de producto, cantidad, origen, destino, y requisitos especiales.|5|
|05|US09|Notificación de Nuevas Solicitudes de Transporte|Como transportista de combustibles peligrosos, quiero recibir notificaciones de nuevas solicitudes.|8|
|06|US01|Monitoreo del Vehículo|Como transportista, quiero realizar un monitoreo completo del vehículo antes de iniciar un viaje, para asegurarme de que está en condiciones óptimas.|8|
|07|US03|Verificación de Rutas Seguras|Como transportista, quiero verificar rutas seguras antes de iniciar un viaje, para minimizar riesgos.|5|
|08|US12|Visualización de Transportistas Disponibles|Como empresa de transporte de productos peligrosos, quiero ver una lista de transportistas disponibles que cumplan con los requisitos para transportar ciertos tipos de productos peligrosos.|5|
|09|US10|Actualización de Estado del Transporte|Como transportista de combustibles peligrosos, quiero actualizar el estado del transporte en tiempo real (en camino, entregado, retraso).|8|
|10|US08|Registro de Transportista de Combustibles Peligrosos|Como transportista de combustibles peligrosos, quiero registrarme en la plataforma proporcionando mis datos, certificaciones y permisos, para poder ser considerado en futuros trabajos de transporte.|8|
|11|US06|Verificación de Permisos de Transportistas|Como empresa de transporte de productos peligrosos, quiero verificar los permisos y certificaciones de los transportistas antes de contratarlos.|3|
|12|US07|Recibir Notificaciones de Incidentes en Tiempo Real|Como empresa de transporte de productos peligrosos, quiero recibir notificaciones en tiempo real sobre cualquier incidente durante el transporte (accidente, retraso, desviación de ruta).|5|
|13|US15|Notificación de tiempo de conducción de transporte en exceso|Como transportista de combustibles peligrosos, quiero recibir una notificación en caso de excederme el total de horas seguidas recomendadas de conducción por día para evitar posibles accidentes al manejar en estado de cansancio.|5|
|14|US05|Seguimiento en Tiempo Real de los Transportes Activos|Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento en tiempo real de todos los transportes activos para garantizar la seguridad y la entrega puntual de los productos.|2|
|15|US13|Control de tiempos de conducción de transporte|Como empresa de transporte de productos peligrosos, quiero realizar un seguimiento de las horas de conducción por los transportistas activos para evitar manejen en estado de cansancio.|2|
|16|US14|Reporte de Estado del Vehículo|Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.|2|
|17|US04|Reporte de Estado del Vehículo|Como transportista, quiero generar y enviar un reporte sobre el estado del vehículo, para mantener un registro actualizado.|3|
|18|US02|Notificaciones de Mantenimiento Preventivo|Como transportista, quiero recibir notificaciones para realizar el mantenimiento preventivo del vehículo, para evitar problemas inesperados.|3|

# Capítulo IV: Solution Software Design

## 4.1 Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
Durante la fase de *Event Storming*, el equipo de desarrollo llevó a cabo una sesión colaborativa en la que se compartieron ideas sobre funcionalidades y características que se deseaban incorporar en el proyecto. 

Para realizar esta dinámica se hizo uso de la plataforma *MIRO* como soporte visual y de organización. *Ver ANEXO A*

**Step 1: Unstructured exploration**

En esta fase, se lograron definir los eventos más relevantes que reflejan las acciones clave dentro de la solución tecnológica logrando así los primeros borarradores de los *bounded context*.

![image](https://github.com/user-attachments/assets/20a8a668-6e4e-4d80-90fe-b87d6e609bff)

**Step 2: Timelines**

En esta etapa, los eventos detectados se organizaron en conjuntos más pequeños, considerando tanto las rutas ideales o exitosas *(happy paths)* como aquellas que representan fallos o situaciones no deseadas *(unhappy paths)*. Esta clasificación permitió estructurar mejor la información y entender las distintas secuencias dentro del sistema de forma más clara.

![image](https://github.com/user-attachments/assets/3873cf40-8ccf-4aa3-a3a8-dd4e10f9014a)

**Step 3: Paint Points**

En este proceso se detectaron *paint points*, es decir, áreas problemáticas donde los usuarios podrían enfrentar dificultades al interactuar con nuestro sistema. Identificarlos es clave para mejorar la experiencia de uso y optimizar el diseño de la aplicación.

![step3](https://github.com/user-attachments/assets/f84f6a50-bde3-46fe-8577-3a862380ec8c)


**Step 4: Pivotal Points**

Durante esta fase se identificaron *pivotal points*, es decir, eventos clave que representan momentos cruciales en el flujo de la plataforma, con un fuerte impacto en el comportamiento del sistema o la experiencia de usuario.

![image](https://github.com/user-attachments/assets/7d6160ab-2489-4c5e-9206-7b69ddd0b90b)

**Step 5: Commands**

En este proceso, a cada evento se le asignó un comando específico que lo activa y un actor responsable de ejecutarlo, lo que le permitió comprender mejor la interacción de los usuarios con el sistema.

![step5](https://github.com/user-attachments/assets/511ac749-892d-4f8e-9ab5-c175d36c27bc)

**Step 6: Policies**

En esta etapa se definieron las políticas relevantes para cada contexto del sistema, incluyendo reglas de negocio, validaciones y restricciones específicas. 

![step6](https://github.com/user-attachments/assets/cd03c448-e0cf-42f4-b22b-d49c73f8ec9a)

**Step 7: Read Models**

En esta fase se diseñaron y desarrollaron los modelos de lectura correspondientes a cada contexto del sistema, grantizando que ofrecieran la información necesaria de forma clara, eficiente y alineada con las necesidades de usuario.

![step7](https://github.com/user-attachments/assets/c3698437-46d0-42c1-98f2-0a2feefa6a73)

**Step 8: External Systems**

Durante el transcurso de este proceso se identificaron los sistemas externos con los que la plataforma debe interactura y dse dfinieron las interfaces necesarias para lograr una integracion efectiva.

![step8](https://github.com/user-attachments/assets/43c6e6a4-103b-4425-94e1-60daccd9f8b6)


**Step 9: Aggregates**

En el transcurso de esta etapa se definieron los *aggregates* para cada contexto del sistema, con el objetivo de representar adecuadamente las transacciones y operaciones que deben mantenerse coherentes.

![step9](https://github.com/user-attachments/assets/4129de72-61c2-4287-8e04-6e7a03dd6f7c)

**Step 10: Bounded Contexts**

Por último, gracias a la identificación y definición de cada uno de los elementos se pudo lograr la resolución de los *bounded contexts*, espacios centrales de funcionamiento diferentes, pero necesarios.

![bcts](https://github.com/user-attachments/assets/33a1784f-b1aa-4c31-b0b2-3d7891c702b8)

**[Enlace del MIRO para mayor visualización del Event Storming](https://miro.com/welcomeonboard/ZDUyWkh5OTlpSVF4RGdTNG9tdkI0N0FnS1F5VUtRczM0dXJkS2dSZHRDeW1yWm54RW02c3EybHBKYzdIaGkxRjZUb2lwNHB2a0RKelJzRmJNUDd3NEoyNVE3Wk1Uc2U5MUFySzEyZFNBZ0pSa011QkVnQy93aVprVXUyVGFsQ2pNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=980476835383)**

#### 4.1.1.1 Candidate Context Discovery

Para priorizar el desarrollo del núcleo funcional del sistema aplicamos la técnica *start-with value*, con el objetivo de tener una visión más clara y enfocada del producto desde sus bases.

- **Identificación de valores del negocio:** Se realizó un análisis de los principales valores que aporta la aplicación. Tales como mejorar la experiencia de nuestros usuarios durante la monitorización de cargas, el registro eficiente de incidentes sucedidos durante el transporte, la calificación a nuestros usuarios transportistas luego de cada viaje relaixado y la optimización en la gestión de usuarios en Chemtrack.
- **Identidicación de funcionalidades clave:** Se definieron las funcionalidades fundamentales que sostienen el objetivo de nuestro sistema. Incluyendo la autenticación y registro de usuarios *(IAM)*, el monitoreo y notificación de incidentes *(MANAGEMENT)* y las operaciones de registro y reporte de incidentes *(RECORDS)*. Todas ellas alineadas directamente con el valor agregado del negocio.

**Candidate para Bounded Context: *IAM***

![iamBC](https://github.com/user-attachments/assets/60d88854-4c28-49c2-ab1c-b5df1bef1907)

**Candidate para Bounded Context: *MANAGEMENT***

![managementBC](https://github.com/user-attachments/assets/4f17b55d-9a8e-4d5e-8c82-2915430d7488)

**Candidate para Bounded Context: *RECORDS***

![recordsBC](https://github.com/user-attachments/assets/673b12d5-0db6-4d8a-8ef5-f9edd020ff22)

**Vista Completa**

![bcs](https://github.com/user-attachments/assets/9b91cbb8-8664-49b3-92bb-9342524bc4fb)

#### 4.1.1.2 Domain Message Flows Modeling

**Iniciar sesión:** El flujo de autenticación comienza con la entrada de las credenciales del usuario, las cuales son validadas por el sistema; si son correctas, el flujo continúa hacia el panel principal del usuario; en caso contrario, el flujo se detiene y se muestra un mensaje de error.
<img src="https://i.imgur.com/xMhtNnf.png" style="width:80%">

**Visualización de historial de transportes:** El flujo permite al usuario acceder a una vista que carga dinámicamente los registros de transporte desde la base de datos, con la opción de aplicar filtros para refinar los resultados; cada elemento del historial es interactuable para obtener detalles adicionales del transporte.
<img src="https://i.imgur.com/MdgpWkT.png" style="width:80%">

**Monitoreo real de transporte:** El flujo de monitoreo en tiempo real utiliza un mapa interactivo que actualiza constantemente la ubicación de los vehículos, integrando datos en vivo mediante APIs de geolocalización, y ofreciendo notificaciones en caso de eventos relevantes como desvíos o retrasos.
<img src="https://i.imgur.com/ZrJcw9H.png" style="width:80%">

#### 4.1.1.3 Bounded Context Canvases 

**Iniciar sesión:** El usuario accede al sistema ingresando sus credenciales en una interfaz simple que valida la autenticidad antes de redirigirlo al panel principal.
<img src="https://i.imgur.com/iagavZb.png" style="width:80%">


**Visualización de historial de transportes:** El usuario puede consultar una lista detallada de transportes previos, con opciones de filtrado y visualización de información específica de cada registro.
<img src="https://i.imgur.com/kiryIY9.png" style="width:80%">

**Monitoreo real de transporte:** El sistema muestra en tiempo real la ubicación y estado de los vehículos en un mapa interactivo, permitiendo supervisión y respuesta inmediata ante eventualidades.
<img src="https://i.imgur.com/vXip4Oq.png" style="width:80%">

### 4.1.2. Context Mapping

Este diagrama muestra la interacción entre los contextos delimitados IAM, Records y Management en Chemtrack. IAM y Management se conectan mediante un Shared Kernel, compartiendo lógica para autenticación y gestión de transporte. Records usa un ACL con Management e IAM para preservar la integridad de los datos y evitar contaminación. IAM actúa como Supplier para Records, proporcionando servicios de autenticación, mientras Records los consume para gestionar incidentes. Esto fomenta una arquitectura modular y cohesiva en el sistema.

<a href="https://ibb.co/wZts5VFt"><img src="https://i.ibb.co/sp7H8nd7/contextmapping.png" alt="contextmapping" border="0"></a>

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

En el diagrama se identifican dos usuarios principales: el Driver (Conductor) y el Manager (Gerente), quienes interactúan directamente con el sistema Chemtrack para gestionar el transporte y responder ante posibles riesgos. A su vez, el sistema Chemtrack utiliza un Alert System, un servicio de notificaciones, para enviar alertas y mantener informados a los usuarios ante cualquier evento relevante durante el proceso de transporte.

<a href="https://ibb.co/4Rz65xL1"><img src="https://i.ibb.co/DfhxSnFr/landscapecontext.png" alt="landscapecontext" border="0"></a>

#### 4.1.3.2. Software Architecture Context Level Diagrams

Este diagrama contextualiza cómo el sistema Chemtrack se integra en su entorno y qué actores externos (personas o sistemas) interactúan con él, resaltando el flujo de información crítica como el monitoreo, las alertas y la gestión de incidentes en situaciones de riesgo.

![image](https://github.com/user-attachments/assets/c2df48b0-dada-401d-aed2-dac8f42f14e2)


#### 4.1.3.2. Software Architecture Container Level 

El diagrama representa la arquitectura de software a nivel de contenedores del sistema de mitigación de riesgos de productos químicos reactivos. Incluye actores como Driver y Manager, que interactúan con componentes como Mobile App, Landing Page, Web Application, Edge Application, IoT Embedded App, Alert System, Web API, Edge Database y Web Database. Las conexiones muestran flujos de datos y notificaciones, como monitoreo, alertas de incidentes y consultas, integrando aplicaciones móviles, web y de borde con bases de datos para gestionar datos en tiempo real. Los bounded context están incluidos y son los de IAM, Management y Records.

![image](https://github.com/user-attachments/assets/a37540be-ea8e-4bc4-b4e4-a07c649fcce0)


#### 4.1.3.3. Software Architecture Deployment Diagrams

El diagrama de despliegue muestra la arquitectura de software del sistema Chemtrack para la mitigación de riesgos de productos químicos reactivos. Detalla los contenedores y nodos de despliegue: Landing Page (HTML/CSS, Github Pages), Web Application (Angular/Springboot, Netlify), Web API y Edge API Application (Springboot, Azure), Mobile App (Flutter, dispositivos móviles), IoT Embedded App (Python, dispositivos IoT), Web Database (MySQL, Azure) y Edge Database (MySQL, Azure). Las conexiones indican flujos de datos, como monitoreo, transferencia de datos IoT y lecturas/escrituras en bases de datos.

<a href="https://ibb.co/G4zcw7sy"><img src="https://i.ibb.co/8L163Mzq/deployment.png" alt="deployment" border="0"></a>

## 4.2. Tactical-Level Domain-Driven Design

Este apartado describe el diseño orientado a dominios a nivel táctico, un enfoque que estructura el software basado en los dominios del negocio. Se centra en modelos, entidades, objetos de valor y servicios que reflejan las necesidades y reglas del dominio, facilitando una implementación más alineada con los requisitos del sistema Chemtrack para la mitigación de riesgos de productos químicos reactivos.

### 4.2.1. Bounded Context: IAM

**Descripción:** Este contexto se encarga de controlar la autenticación, autorización y gestión de los roles asignados a los usuarios del sistema. Permite una administración centralizada de usuarios, abarcando su creación, actualización y eliminación, además de definir y aplicar las políticas de acceso a los distintos servicios y datos que ofrece la plataforma.

#### 4.2.1.1. Domain Layer

## Aggregate 1: Usuario
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Usuario</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Modela un usuario del sistema Chemtrack, gestionando su información de acceso, roles y certificaciones para garantizar una autenticación y autorización seguras.</td>
    </tr>
</table>

### Atributos de Usuario

<table>
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
        <td>Identificador único del usuario</td>
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
        <td>Correo electrónico del usuario</td>
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
        <td>Rol del usuario</td>
    </tr>
    <tr>
        <td>createdAt</td>
        <td>DateTime</td>
        <td>Private</td>
        <td>Fecha de creación de cuenta del usuario</td>
    </tr>
</table>

### Métodos de Usuario

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Construye una entidad User con los datos proporcionados</td>
    </tr>
    <tr>
        <td>authenticate</td>
        <td>Boolean</td>
        <td>Public</td>
        <td>Autentica al usuario basándose en su email y contraseña</td>
    </tr>
    <tr>
        <td>updateProfile</td>
        <td>Void</td>
        <td>Public</td>
        <td>Actualiza la dirección de correo electrónico del usuario</td>
    </tr>
     <tr>
        <td>assignRole</td>
        <td>Void</td>
        <td>Public</td>
        <td>Asigna un rol al usuario</td>
    </tr>
</table>

## Aggregate 2: Rol
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Rol</td>
        <td>Value Object</td>
        <td colspan="2">Especifica el rol de un usuario (DRIVER o MANAGER) dentro de Chemtrack, permitiendo la asignación de permisos y responsabilidades según su función.</td>
    </tr>
</table>

### Atributos de Rol

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>value</td>
        <td>String</td>
        <td>Private</td>
        <td>Enum value ("DRIVER" o "MANAGER")</td>
    </tr>
</table>

### Métodos de Rol

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Construye una entidad Rol con los datos proporcionados</td>
    </tr>
    <tr>
        <td>equals</td>
        <td>Boolean</td>
        <td>Public</td>
        <td>Compara con otro: Rol para igualar</td>
    </tr>
</table>

## Aggregate 3: Certificación
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Certificación</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Registra y gestiona las certificaciones asociadas a un usuario en Chemtrack, asegurando que cumplan con los requisitos de validez para operar en el sistema.</td>
    </tr>
</table>

### Atributos de Certificación

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>UUID</td>
        <td>Private</td>
        <td>Identificador único de la certificación</td>
    </tr>
    <tr>
        <td>certName</td>
        <td>String</td>
        <td>Private</td>
        <td>Nombre de la certificación</td>
    </tr>
     <tr>
        <td>issueDate</td>
        <td>Date</td>
        <td>Private</td>
        <td>Fecha de expedición de la certificación</td>
    </tr>
     <tr>
        <td>expirationDate</td>
        <td>Date</td>
        <td>Private</td>
        <td>Fecha de caducidad de la certificación</td>
    </tr>
</table>

### Métodos de Certificación

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Constructor de una certificación con información proveída</td>
    </tr>
</table>

## Aggregate 4: Permiso
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>Permiso</td>
        <td>Entity/Aggregate</td>
        <td colspan="2">Establece los permisos específicos de un usuario en Chemtrack, controlando su acceso a funcionalidades y datos según su rol.</td>
    </tr>
</table>

### Atributos de Permiso

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>id</td>
        <td>UUID</td>
        <td>Private</td>
        <td>Identificador único del permiso</td>
    </tr>
    <tr>
        <td>name</td>
        <td>String</td>
        <td>Private</td>
        <td>Nombre del permiso</td>
    </tr>
</table>

### Métodos de Certificación

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>Constructor</td>
        <td>Void</td>
        <td>Public</td>
        <td>Constructor de un permiso con información proveída</td>
    </tr>
    <tr>
        <td>definePermission</td>
        <td>Void</td>
        <td>Public</td>
        <td>Define el nombre del permiso</td>
    </tr>
</table>

#### 4.2.1.2. Interface Layer

## Controller 1: AuthController
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>AuthController</td>
        <td>Controller</td>
        <td colspan="2">Maneja las solicitudes HTTP para autenticar usuarios y gestionar sus cuentas en Chemtrack, incluyendo inicio de sesión, registro y actualizaciones.</td>
    </tr>
</table>

### Atributos de AuthController

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>userService</td>
        <td>UserService</td>
        <td>Private</td>
        <td>Servicio para aplicar reglas de negocio y lógica de autenticación</td>
    </tr>
    <tr>
        <td>userMapper</td>
        <td>UserMapper</td>
        <td>Private</td>
        <td>Mapeador para transformar entidades de usuario en DTO y viceversa</td>
    </tr>
</table>

### Métodos de AuthController

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>authenticateUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Autentica un usuario usando credenciales y JWT</td>
    </tr>
    <tr>
        <td>registerUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Registra un nuevo usuario en el sistema</td>
    </tr>
    <tr>
        <td>getAllUsers</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Devuelve la lista de usuarios registrados</td>
    </tr>
     <tr>
        <td>updateUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Actualiza la información de un usuario existente</td>
    </tr>
    <tr>
        <td>deleteUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Elimina un usuario por ID</td>
    </tr>
</table>

#### Controller 2: PermissionController

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| PermissionController | Controller | Gestiona solicitudes HTTP para asignar y remover permisos de usuarios en Chemtrack, asegurando un control de acceso granular. |

**Atributos de PermissionController:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| permissionService | PermissionService | Private | Servicio para aplicar las reglas de negocio |

**Métodos de PermissionController:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| getAllPermissions | ResponseEntity | Public | Retorna la lista de todos los permisos |
| assignPermissionToUser | ResponseEntity | Public | Asigna el permiso para cada user |
| removePermissionFromUser | ResponseEntity | Public | Quita el permiso para cada user |

#### 4.2.1.3. Application Layer

## Service 1: UserService
<table>
    <tr>
        <td>Nombre</td>
        <td>Categoria</td>
        <td colspan="2">Propósito</td>
    </tr>
    <tr>
        <td>UserService</td>
        <td>Service</td>
        <td colspan="2">Implementa la lógica de negocio para la gestión de usuarios en Chemtrack, incluyendo autenticación, registro y manejo de perfiles.</td>
    </tr>
</table>

### Atributos de UserService

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de dato</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>userRepository</td>
        <td>UserRepository</td>
        <td>Private</td>
        <td>Repositorio para las operaciones CRUD de los usuarios</td>
    </tr>
    <tr>
        <td>passwordEncoder</td>
        <td>passwordEncoder</td>
        <td>Private</td>
        <td>Se utiliza para codificar las contraseñas de los usuarios</td>
    </tr>
    <tr>
        <td>jwtHandler</td>
        <td>JwtHandler</td>
        <td>Private</td>
        <td>Manejador para autenticación y autorización JWT</td>
    </tr>
</table>

### Métodos de UserService

<table>
    <tr>
        <td>Nombre</td>
        <td>Tipo de retorno</td>
        <td>Visibilidad</td>
        <td>Descripción</td>
    </tr>
    <tr>
        <td>authenticateUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Autentica un usuario usando credenciales y JWT</td>
    </tr>
    <tr>
        <td>registerUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Registra un nuevo usuario en el sistema y cifra la contraseña</td>
    </tr>
    <tr>
        <td>getAllUsers</td>
        <td>List</td>
        <td>Public</td>
        <td>Devuelve la lista de usuarios registrados</td>
    </tr>
     <tr>
        <td>updateUser</td>
        <td>User</td>
        <td>Public</td>
        <td>Actualiza la información de un usuario existente</td>
    </tr>
    <tr>
        <td>deleteUser</td>
        <td>ResponseEntity</td>
        <td>Public</td>
        <td>Elimina un usuario por ID</td>
    </tr>
    <tr>
        <td>loadUserByUsername</td>
        <td>UserDetails</td>
        <td>Public</td>
        <td>Carga un usuario por nombre de usuario para la autenticación</td>
    </tr>
</table>

#### Service 2: PermissionService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| PermissionService | Service | Aplica la lógica de negocio para la gestión de permisos en Chemtrack, permitiendo asignar y revocar accesos a usuarios. |

**Atributos de PermissionService:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| permissionRepository | PermissionRepository | Private | Repositorio para operaciones CRUD de permisos|

**Métodos de PermissionService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| getAllPermissions | List<Permission> | Public | Devuelve la lista de todos los permisos |
| assignPermissionToUser | ResponseEntity | Public | Asigna un permiso al usuario |
| removePermissionFromUser | ResponseEntity | Public | Elimina el permiso de un usuario |

#### 4.2.1.4. Infrastructure Layer

#### Repository 1: UserRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| UserRepositoryImpl | Repository | Facilita las operaciones de persistencia de usuarios en Chemtrack, interactuando con la base de datos para operaciones CRUD. |

**Métodos de UserRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findById | User | Public | Recupera usuario de la base de datos por id |
| findByEmail | User | Public | Recupera el usuario de la base de datos por correo electrónico |
| save | Void | Public | Guarda usuario |
| existsByEmail | Boolean | Public | Verifica si el usuario existe por email |

#### Repository 2: PermissionRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| PermissionRepositoryImpl | Repository | Administra la persistencia de permisos en Chemtrack, permitiendo operaciones CRUD en la base de datos. |

**Métodos de PermissionRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findByName | Optional<Permission> | Public | Recupera el permiso de la base de datos por nombre |
| save | Permission | Public | Guarda el permiso en la base de datos |
| deleteById | Void | Public | Elimina el permiso en la base de datos por id|

### External Service

#### Service 1: EmailService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| EmailService | Service | Gestiona el envío de notificaciones y correos electrónicos a usuarios de Chemtrack a través de un servidor SMTP externo. |

**Métodos de EmailService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| sendEmail | Void | Public | Envía un correo electrónico al destinatario |

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

El IAM Bounded Context administra identidad y acceso para Drivers y Managers en Chemtrack. Componentes como AuthController, UserService y PermissionService manejan autenticación y permisos. EmailService, Certification y UserRepositoryImpl gestionan notificaciones y persistencia de usuarios. Se integra con un External Email System y una base de datos relacional para almacenamiento.

![image](https://github.com/user-attachments/assets/3178abf8-7494-4cde-8c7a-14583a51c3ef)


#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

A continuación se incluirán las secciones internas Bounded Context Domain Layer Class Diagrams y Bounded Context Database Diagram para el Bounded Context de IAM.

#### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de la capa de dominio muestra el contexto delimitado de gestión de usuarios en Chemtrack. Incluye clases como UserAggregate, que contiene User y Certification, con métodos para agregar certificaciones y validar usuarios. AuthenticationService genera tokens y hashes de contraseñas, mientras UserRepository gestiona operaciones CRUD. La relación "has" con Role define roles como DRIVER y MANAGER, integrando permisos y autenticación.

![image](https://github.com/user-attachments/assets/7870fb53-32b9-449f-944c-dad16c11f427)


#### 4.2.1.6.2. Bounded Context Database Design Diagram

El diagrama de diseño de base de datos representa la estructura relacional del contexto delimitado IAM. La tabla User almacena id, role_id y password_hash, con una relación "tiene" hacia Certification. Role contiene name y se asocia con User_Role_Permission mediante asignado_a y tiene relaciones. Permission define name único, conectando con User_Role_Permission para gestionar accesos.

![image](https://github.com/user-attachments/assets/5be6bc52-8caf-4531-b0da-45991ff25087)


### 4.2.2. Bounded Context: Management

**Descripción:** Este módulo se ocupa de organizar y manejar todo lo relacionado con la generación, envío y monitoreo de notificaciones sobre incidentes o eventos importantes. Su objetivo es mantener informados en tiempo real a transportistas, operadores y supervisores, facilitando la transmisión oportuna de alertas y actualizaciones sobre el estado de dichos sucesos.

#### 4.2.2.1. Domain Layer

#### Entity 1: Transporte

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| Transporte | Entity | Modela y gestiona una operación de transporte químico en Chemtrack, incluyendo su estado, conductor asignado y datos de inicio. |

**Atributos de Transporte:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único del transporte |
| driverId | UUID | Private | ID del Conductor asignado |
| status | TransportStatus | Private | Estado del transporte (PENDIENTE, EN_PROCESO) |
| startTime | DateTime | Private |  Hora de inicio del transporte |

**Métodos de Transporte:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un Transporte con id|
| updateStatus | Void | Public | Actualiza el estado del transporte |
| assignDriver | Void | Public | Asigna un driverId |

#### Entity 2: SensorReading

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| SensorReading | Entity | Registra y gestiona las lecturas de sensores durante un transporte en Chemtrack, capturando datos como niveles de gas y temperatura. |

**Atributos de SensorReading:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único de la lectura |
| type | String | Private | Tipo de lectura del sensor |
| gasLevel | Float | Private | Medida del nivel de gas |
| temperature | Float | Private | Medida de temperatura |
| timestamp | DateTime | Private | Tiempo de la lectura |

**Métodos de SensorReading:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un SensorReading con ID |

#### Value Object 1: TransportStatus

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportStatus | Value Object | Define y categoriza los estados posibles de un transporte en Chemtrack, como PENDIENTE o EN_PROCESO, para seguimiento operativo. |

**Atributos de TransportStatus:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| value | String | Private | Valor Enum |

**Métodos de TransportStatus:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un TransportStatus con valor |
| equals | Boolean | Public | Compara con otros: TransportStatus para la igualdad |

#### 4.2.2.2. Interface Layer

#### Controller 1: TransportController

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportController | Controller | Procesa solicitudes HTTP para gestionar operaciones de transporte en Chemtrack, como inicio, actualización y consulta de estados. |

**Atributos de TransportController:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| transportService | TransportService | Private | Servicio para aplicar reglas de negocio de transporte |

**Métodos de TransportController:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| startTransport | ResponseEntity | Public | Inicializa transporte con transportId |
| updateStatus | ResponseEntity | Public | Actualiza el estado del transporte con transportId |
| getAllTransports | ResponseEntity | Public | Devuelve la lista de todos los transportes |

#### 4.2.2.3. Application Layer

#### Service 1: TransportService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportService | Service | Implementa la lógica de negocio para la gestión de operaciones de transporte en Chemtrack, coordinando inicios, actualizaciones y consultas. |

**Atributos de TransportService:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| transportRepository | TransportRepository | Private | Repositorio para operaciones CRUD de transporte |

**Métodos de TransportService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| startTransport | ResponseEntity | Public | Inicia el transporte con transportId |
| updateTransportStatus | ResponseEntity | Public | Actualiza el transporte con transportId |
| getAllTransports | List<Transport> | Public | Devuelve la lista de todos los transportes |

#### 4.2.2.4. Infrastructure Layer

#### Repository 1: TransportRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| TransportRepositoryImpl | Repository | Administra la persistencia de datos de transporte en Chemtrack, permitiendo operaciones CRUD en la base de datos. |

**Métodos de TransportRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findById | Transport | Public | Recupera el transporte de la base de datos por id |
| save | Void | Public | Guarda el transporte a la base de datos |

### External Service

#### Service 1: IoTDeviceService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IoTDeviceService | Service | Obtiene y procesa datos de sensores de dispositivos IoT en Chemtrack para monitoreo en tiempo real durante el transporte. |

**Métodos de IoTDeviceService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| fetchSensorData | SensorData | Public | Recupera datos del dispositivo con deviceId |

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

El diagrama del Management Bounded Context muestra la gestión de transporte y monitoreo en Chemtrack. Incluye TransportController, TransportService e IoTDeviceService para procesar datos de sensores IoT. Transport y SensorReading envían notificaciones vía SMTP, mientras TransportRepositoryImpl persiste datos. Se integra con una base de datos y un IoT System para monitoreo en tiempo real.

![image](https://github.com/user-attachments/assets/8b6ee048-e773-49e0-9fb4-092c47885f70)


#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

A continuación se incluirán las secciones internas Bounded Context Domain Layer Class Diagrams y Bounded Context Database Diagram para el Bounded Context de Management.

#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Management Bounded Context modela transporte en Chemtrack. TransportAggregate contiene Transport y SensorReading, con métodos como addSensorReading y validateTransport.MonitoringService procesa datos de sensores y genera alertas, mientras TransportRepository gestiona persistencia.TransportStatus define estados como PENDING, IN_PROGRESS y COMPLETED, asignados a Transport.

![image](https://github.com/user-attachments/assets/7458ce29-30be-407f-a661-d9983f5c246d)


#### 4.2.2.6.2. Bounded Context Database Design Diagram

El esquema de base de datos del Management Bounded Context organiza datos de transporte. La tabla Transport almacena driver_id y status_id, vinculada a SensorReading por transport_id. TransportStatus define estados únicos, mientras SensorReading registra value y timestamp. Las claves primarias y foráneas aseguran relaciones entre transporte, sensores y estados.

![image](https://github.com/user-attachments/assets/5c8a4a18-9b40-46af-99be-d76661ef4c6f)


### 4.2.3. Bounded Context: Records

**Descripción:** Este contexto tiene como propósito coordinar y controlar los servicios vinculados al transporte y la carga. Incluye funciones como el monitoreo de recursos, la planificación de rutas y la actualización de información relacionada con los servicios activos. Asimismo, respalda la toma de decisiones operativas con base en el estado actual de las operaciones logísticas.

#### 4.2.3.1. Domain Layer

#### Entity 1: Incident

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| Incident | Entity | Representa y gestiona un incidente relacionado con un transporte en Chemtrack, capturando su tipo, tiempo y estado para seguimiento y resolución. |

**Atributos de Incident:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único de un incidente |
| transportId | UUID | Private | ID del transporte relacionado |
| type | IncidentType | Private | Tipo de incidente |
| timestamp | DateTime | Private | Timestamp del incidente |

**Métodos de Incident:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructs de un incidente con id |
| updateDetails | Void | Public | Actualiza los detalles de un incidente |
| resolve | Void | Public | Marca el incidente como resuelto |

#### Entity 2: CorrectiveAction

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| CorrectiveAction | Entity | Define y registra una acción correctiva asociada a un incidente en Chemtrack, incluyendo su descripción y estado de resolución. |

**Atributos de CorrectiveAction:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| id | UUID | Private | Identificador único de la acción |
| actionDescription | String | Private | Descripción de la acción. |
| timestamp | DateTime | Private | Timestamp de la acción |

**Métodos de CorrectiveAction:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Contructor de CorrectiveAction con id |

### Value Objects

#### Value Object 1: IncidentType

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentType | Value Object | Clasifica los tipos de incidentes en Chemtrack, como fugas de gas o anomalías de temperatura, para categorización y análisis. |

**Atributos de IncidentType:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| value | String | Private | Valor enum |

**Métodos de IncidentType:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| Constructor | Void | Public | Constructor de un IncidentType |
| equals | Boolean | Public | Compara con otro: IncidentType para igualdad |

#### 4.2.3.2. Interface Layer

#### Controller 1: IncidentController

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentController | Procesa solicitudes HTTP para gestionar incidentes en Chemtrack, incluyendo reportes, resoluciones y consultas de incidentes. |

**Atributos de IncidentController:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| incidentService | IncidentService | Private | Servicio de aplicación de reglas de negocio de incidencias |

**Métodos de IncidentController:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| reportIncident | ResponseEntity | Public | Informa de un nuevo incidente con incidentData |
| resolveIncident | ResponseEntity | Public | Resuelve el incidente con incidentId |
| getAllIncidents | ResponseEntity | Public | Devuelve la lista de todos los incidentes |

#### 4.2.3.3. Application Layer

#### Service 1: IncidentService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentService | Service | Aplica la lógica de negocio para la gestión de incidentes en Chemtrack, incluyendo reportes, resoluciones y recuperación de datos históricos. |

**Atributos de IncidentService:**

| Nombre | Tipo de dato | Visibilidad | Descripción |
| --- | --- | --- | --- |
| incidentRepository | IncidentRepository | Private | Repositorio para operaciones CRUD de incidentes |

**Métodos de IncidentService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| reportIncident | ResponseEntity | Public | Informa de un nuevo incidente con incidentData |
| resolveIncident | ResponseEntity | Public | Resuelve el incidente con incidentId |
| getAllIncidents | List<Incident> | Public | Devuelve la lista de todos los incidentes |

#### 4.2.3.4. Infrastructure Layer

#### Repository 1: IncidentRepositoryImpl

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| IncidentRepositoryImpl | Repository | Gestiona la persistencia de incidentes en Chemtrack, permitiendo operaciones CRUD en la base de datos para datos históricos. |

**Métodos de IncidentRepositoryImpl:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| findById | Incident | Public | Recupera el incidente de la base de datos por id |
| save | Void | Public | Guarda el incidente: Incidente en la base de datos |

### External Service

#### Service 1: NotificationService

| Nombre | Categoría | Propósito |
| --- | --- | --- |
| NotificationService | Service | Gestiona el envío de notificaciones de incidentes en Chemtrack a sistemas externos, asegurando alertas en tiempo real. |

**Métodos de NotificationService:**

| Nombre | Tipo de retorno | Visibilidad | Descripción |
| --- | --- | --- | --- |
| sendNotification | Void | Public | Envía notificación al destinatario |

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

El Records Bounded Context gestiona incidentes y reportes históricos en Chemtrack. Incluye IncidentController, IncidentService y NotificationService para manejar reportes y alertas. Corrective Action envía acciones correctivas vía SMTP, mientras IncidentRepositoryImpl persiste datos. Se integra con un Alert System y una base de datos relacional para almacenamiento.

![image](https://github.com/user-attachments/assets/11cc8bdf-878c-432a-ac20-36c2bfb03060)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

A continuación se incluirán las secciones internas Bounded Context Domain Layer Class Diagrams y Bounded Context Database Diagram para el Bounded Context de Records.

#### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama de clases del Records Bounded Context modela incidentes en Chemtrack. IncidentAggregate contiene Incident y CorrectiveAction, con métodos como addAction y validateIncident. ReportingService genera reportes, mientras IncidentRepository gestiona persistencia de incidentes. IncidentType define tipos como GAS_LEAK y TEMPERATURE_ANOMALY, asociados a Incident.

![image](https://github.com/user-attachments/assets/db74f044-9b00-48a5-87dc-6095170426bb)


#### 4.2.3.6.2. Bounded Context Database Design Diagram

El esquema de base de datos del Records Bounded Context organiza datos de incidentes. La tabla Incident almacena transport_id y type_id, vinculada a CorrectiveAction por incident_id. IncidentType define tipos únicos, mientras CorrectiveAction registra action_description y completed_date. Las claves primarias y foráneas aseguran relaciones entre incidentes, tipos y acciones.

![image](https://github.com/user-attachments/assets/db160ad5-988c-49e9-aa79-d3a18edcde06)



# Bibliografía

Aguilar-Velázquez, J. A., & Salazar-González, M. (2018). Evaluación del riesgo en el transporte terrestre de sustancias peligrosas mediante sistemas de información geográfica. Revista Internacional de Contaminación Ambiental, 34(1), 131-141.

García, C. H., & Martínez, J. D. (2022). Aplicación de sensores IoT para detección temprana de fugas en unidades móviles de transporte de gas. Revista Electrónica de Ciencia y Tecnología, 19(1), 47-55.

López-Atamoros, L. G., Fernández-Villagómez, G., Cruz-Gómez, M. J., & Durán-de-Bazúa, C. (2010). Integración de una Base Nacional de Datos de Accidentes durante el Transporte de Gas LP (BNDAT@ GLP) 1998-2009: Sustento para un estudio de evaluación de riesgo. Tecnología, Ciencia, Educación, 25(2), 99-112.

Rivas-Tovar, L. A., & Vázquez-González, R. (2017). Desarrollo de un sistema de monitoreo para transporte de materiales peligrosos utilizando sensores y redes inalámbricas. Revista Iberoamericana de Automática e Informática Industrial RIAI, 14(3), 315-324.

Soto, J. A. S., González, D. L. E., Sánchez, J. F. I., Reyes, J. A., & Layva, J. M. E. (2023). DISEÑO DE DISPOSITIVO PARA PREVENIR ACCIDENTES CAUSADOS POR FUGAS DE GAS. Revista IPSUMTEC, 6(4), 11-14.


# Anexos

**Anexo A.** Event Storming desarrollado en la plataforma MIRO.

![eventStorming](https://github.com/user-attachments/assets/fe7db010-856e-4eee-8ef3-90a84ecb3327)

*[Enlace del MIRO para mayor visualización del Event Storming](https://miro.com/welcomeonboard/ZDUyWkh5OTlpSVF4RGdTNG9tdkI0N0FnS1F5VUtRczM0dXJkS2dSZHRDeW1yWm54RW02c3EybHBKYzdIaGkxRjZUb2lwNHB2a0RKelJzRmJNUDd3NEoyNVE3Wk1Uc2U5MUFySzEyZFNBZ0pSa011QkVnQy93aVprVXUyVGFsQ2pNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=980476835383)*

**Anexo B.** Diagrama de Clases de Chemtrack.

![image](https://github.com/user-attachments/assets/0ba27eb9-5cc4-468f-b3a3-f3ab755b4e94)


**Anexo C.** Diagrama de Base de Datos de Chemtrack.

![image](https://github.com/user-attachments/assets/8891c6d6-734c-46f2-9289-fd25f42f66af)


**Videos de exposición**

[Video de exposición TB1](https://youtu.be/n4_SKmnvCeU)

[Video de exposición TP1](https://youtu.be/Y9wkGYbHHYE)

[Video de exposición TB2](https://youtu.be/Yd74MizvXWY)

[Video de exposición TF1](https://youtu.be/F0Hp7YIlBoA)




