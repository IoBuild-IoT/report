# <center>COURSE PROJECT</center>

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Periodo: 2026-2</strong><br>
    <strong>Desarrollo de Soluciones IoT</strong><br>
    <strong>NRC: 16518</strong><br>
    <strong>Profesor: Jimmy Enrique Sanchez Portugal</strong><br>
    <br>INFORME TRABAJO FINAL
</p>

<center>

#### Startup: **CcaritaTech**
#### Product: **IoBuild**

</center>

### <center>Team Members:</center>
<center>

| Member                           | Code       |
|----------------------------------|------------|
|Ordoñez Ricaldi, Axel Randall|U202216827|
|Ccarita Cruz, Brayan Roberto|U20221c218|
|Panta Castro, Fabrizio Martin|U20231a810|
|Loechle Arias, Mateo Italo|U202215004|
|Guia Carrasco, Pedro Andre|U202212010|
|Alejo Jesus, Anyelo Bill|U20231d149|
|Escalante Baygorrea, Janiel Franz|U201912668|


<br> Octubre 2026
</center>  

<div style="page-break-before: always;"></div>

# Registro de Versiones del Informe
<center>

| Version | Fecha | Autor | Descripcion de Modificacion |
| :---: | :---: | :--- | :--- |
| 0.0 | 05/09/2026 | Ccarita Cruz, Brayan Roberto | Inicialización del repositorio y estructura base del informe del proyecto. |
| 0.1 | 06/09/2026 | Ordoñez Ricaldi, Axel Randall | Redacción del Capítulo 1: Startup Profile, descripción de la organización y perfiles profesionales de los integrantes. |
| 0.2 | 07/09/2026 | Panta Castro, Fabrizio Martin | Elaboración del Solution Profile, antecedentes, problemática, proceso Lean UX (Problem Statements, Assumptions, Hypothesis, Canvas) y segmentos objetivo. |
| 0.3 | 08/09/2026 | Loechle Arias, Mateo Italo | Desarrollo del Capítulo 2: Análisis competitivo, benchmarking de competidores directos e indirectos y estrategias frente a la competencia. |
| 0.4 | 09/09/2026 | Guia Carrasco, Pedro Andre | Elaboración de entrevistas: diseño de guía de preguntas, registro audiovisual, transcripción y análisis de respuestas de los segmentos objetivo. |
| 0.5 | 10/09/2026 | Alejo Jesus, Anyelo Bill | Desarrollo de Needfinding: creación de User Personas, User Task Matrix, User Journey Mapping y Empathy Mapping. |
| 0.6 | 11/09/2026 | Escalante Baygorrea, Janiel Franz | Modelado de Big Picture EventStorming y definición formal del Ubiquitous Language del dominio de la solución. |
| 0.7 | 12/09/2026 | Ccarita Cruz, Brayan Roberto | Desarrollo del Capítulo 3: Especificación de requisitos, definición de Épicas, User Stories con criterios de aceptación (Gherkin) y Technical Stories. |
| 0.8 | 13/09/2026 | Ordoñez Ricaldi, Axel Randall | Construcción del Impact Mapping y estructuración del Product Backlog general con estimación de puntos de historia y priorización por Sprints. |
| 0.9 | 15/09/2026 | Panta Castro, Fabrizio Martin | Elaboración del Capítulo 4: Strategic-Level DDD (Design-Level EventStorming, Candidate Contexts, Bounded Context Canvases y Context Mapping). |
| 1.0 | 16/09/2026 | Loechle Arias, Mateo Italo | Tactical-Level DDD para los 4 Bounded Contexts, diagramas de arquitectura de software C4, conclusiones, bibliografía, anexos y consolidación final de la entrega hasta el Capítulo 4. |  

</center>

<div style="page-break-before: always;"></div>

# Project Report Collaboration Insights

**Enlace del repositorio:** [https://github.com/IoBuild-IoT/report](https://github.com/IoBuild-IoT/report)

El desarrollo del presente informe fue producto de un trabajo colaborativo, riguroso y planificado mediante el flujo de trabajo GitFlow sobre la plataforma GitHub. Las responsabilidades se distribuyeron equitativamente entre los integrantes del equipo cubriendo desde la investigación de mercado y elicitación de requisitos, hasta el modelado conceptual, arquitectónico y diseño de software bajo el estándar Domain-Driven Design (DDD).

### Evidencias de Contribución y Control de Versiones

A continuación, se presentan las métricas de participación de los miembros del equipo y la red de integración de ramas correspondientes al desarrollo del informe de la plataforma **IoBuild**:

#### Contribuidores del Repositorio (Contributors)
<img src="assets/Contributors-IoT.png" alt="Contributors - IoBuild Report" style="max-width: 100%; height: auto; border-radius: 6px;" />

<br>

#### Red de Ramas y Commits (Network Graph)
<img src="assets/Network-IoT.png" alt="Network Graph - IoBuild Report" style="max-width: 100%; height: auto; border-radius: 6px;" />

<br>

### Detalle de Aportes por Integrante

- **Ordoñez Ricaldi, Axel Randall:**
  - Coordinó la redacción inicial del **Capítulo I**, participando en la definición del perfil de la startup y la consolidación de los perfiles de los integrantes del equipo.
  - Estructuró la sección de **Impact Mapping** (3.2), alineando las metas estratégicas de negocio con los actores, impactos deseados y entregables funcionales.
  - Lideró la priorización y estimación del **Product Backlog** (3.3), calibrando los Story Points bajo la serie Fibonacci y organizando las historias en sprints para la planificación ágil.

- **Ccarita Cruz, Brayan Roberto:**
  - Inicializó y configuró la estructura del repositorio en GitHub bajo la metodología GitFlow, estableciendo las ramas de desarrollo, estándares de commit y buenas prácticas de colaboración.
  - Desarrolló la especificación de requisitos en la sección de **User Stories** (3.1), redactando las historias de usuario con criterios de aceptación bajo la sintaxis formal Gherkin (Given-When-Then) y formulando las historias técnicas de integración.
  - Participó en la definición y revisión de la arquitectura de software, colaborando en el alineamiento estratégico entre los casos de uso y los Bounded Contexts.

- **Panta Castro, Fabrizio Martin:**
  - Lideró el desarrollo del proceso **Lean UX** en el Capítulo I, estructurando los Problem Statements, Assumptions, Hypothesis Statements y el Lean UX Canvas de la solución IoBuild.
  - Diseñó y documentó la etapa de **Strategic-Level Domain-Driven Design** en el Capítulo IV, ejecutando las sesiones de Design-Level EventStorming, Candidate Context Discovery, Bounded Context Canvases y el Context Mapping del ecosistema.
  - Administró y mantuvo el repositorio de recursos gráficos y diagramas de arquitectura de la plataforma.

- **Loechle Arias, Mateo Italo:**
  - Desarrolló el **análisis competitivo** y benchmarking de competidores directos e indirectos en la sección 2.1 del Capítulo II, definiendo las ventajas competitivas y la matriz FODA.
  - Lideró la especificación del **Tactical-Level Domain-Driven Design** en el Capítulo IV para los cuatro Bounded Contexts, detallando las capas Domain, Application, Interface e Infrastructure, así como los diagramas de clases y esquemas de base de datos relacional.
  - Consolidó la versión final de la entrega, redactando las conclusiones, recomendaciones, bibliografía formal bajo normas APA y anexos del informe.

- **Guia Carrasco, Pedro Andre:**
  - Planificó y ejecutó el diseño de las **entrevistas semiestructuradas** en la sección 2.2 del Capítulo II, formulando las guías de preguntas orientadas a los dos segmentos objetivo del proyecto.
  - Realizó y moderó las entrevistas a representantes de empresas constructoras y propietarios residenciales, gestionando el registro audiovisual y el análisis de hallazgos.
  - Documentó la síntesis de validación con usuarios para fundamentar la necesidad de una plataforma IoT unificada en la supervisión de confort ambiental y automatización de iluminación.

- **Alejo Jesus, Anyelo Bill:**
  - Lideró el desarrollo de la sección de **Needfinding** en el Capítulo II, construyendo las **User Personas** representativas para el segmento B2B (arquitectos e ingenieros) y B2C (propietarios y residentes).
  - Diseñó y documentó la **User Task Matrix**, los **User Journey Maps** y los **Empathy Maps** de ambos segmentos, identificando puntos de dolor, necesidades latentes y oportunidades de mejora para la plataforma.
  - Aseguró que los requisitos de usuario reflejaran fielmente la experiencia cotidiana y las expectativas prácticas de los clientes.

- **Escalante Baygorrea, Janiel Franz:**
  - Facilitó y moderó las dinámicas de **Big Picture EventStorming** en la sección 2.4 del Capítulo II, identificando eventos del dominio, comandos, agregados y políticas de negocio de extremo a extremo.
  - Formalizó el **Ubiquitous Language** en la sección 2.5, estableciendo un glosario unificado de términos de negocio e ingeniería IoT para todo el equipo.
  - Contribuyó en la definición de la arquitectura de software C4 (System Landscape, Context, Container y Deployment diagrams) y en la revisión de consistencia técnica del informe.

<div style="page-break-before: always;"></div>

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process.](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores.](#21-competidores)
    - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas.](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
    - [2.3.1. User Personas.](#231-user-personas)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
  - [2.4. Big Picture EventStorming.](#24-big-picture-eventstorming)
  - [2.5. Ubiquitous Language.](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories.](#31-user-stories)
  - [3.2. Impact Mapping.](#32-impact-mapping)
  - [3.3. Product Backlog.](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design.](#41-strategic-level-domain-driven-design)
    - [4.1.1. Design-Level EventStorming.](#411-design-level-eventstorming)
      - [4.1.1.1 Candidate Context Discovery.](#4111-candidate-context-discovery)
      - [4.1.1.2 Domain Message Flows Modeling.](#4112-domain-message-flows-modeling)
      - [4.1.1.3 Bounded Context Canvases.](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping.](#412-context-mapping)
    - [4.1.3. Software Architecture.](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram.](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams.](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Software Architecture Container Level Diagrams.](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4. Software Architecture Deployment Diagrams.](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1. Bounded Context: Smart Project Setup.](#421-bounded-context-smart-project-setup)
      - [4.2.1.1. Domain Layer.](#4211-domain-layer)
      - [4.2.1.2. Interface Layer.](#4212-interface-layer)
      - [4.2.1.3. Application Layer.](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer.](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams.](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams.](#4216-bounded-context-software-architecture-code-level-diagrams)
    - [4.2.2. Bounded Context: Service Execution and Monitoring.](#422-bounded-context-service-execution-and-monitoring)
      - [4.2.2.1. Domain Layer.](#4221-domain-layer)
      - [4.2.2.2. Interface Layer.](#4222-interface-layer)
      - [4.2.2.3. Application Layer.](#4223-application-layer)
      - [4.2.2.4. Infrastructure Layer.](#4224-infrastructure-layer)
      - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams.](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams.](#4226-bounded-context-software-architecture-code-level-diagrams)
    - [4.2.3. Bounded Context: Smart Assistant.](#423-bounded-context-smart-assistant)
      - [4.2.3.1. Domain Layer.](#4231-domain-layer)
      - [4.2.3.2. Interface Layer.](#4232-interface-layer)
      - [4.2.3.3. Application Layer.](#4233-application-layer)
      - [4.2.3.4. Infrastructure Layer.](#4234-infrastructure-layer)
      - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams.](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams.](#4236-bounded-context-software-architecture-code-level-diagrams)
    - [4.2.4. Bounded Context: Energy Management.](#424-bounded-context-energy-management)
      - [4.2.4.1. Domain Layer.](#4241-domain-layer)
      - [4.2.4.2. Interface Layer.](#4242-interface-layer)
      - [4.2.4.3. Application Layer.](#4243-application-layer)
      - [4.2.4.4. Infrastructure Layer.](#4244-infrastructure-layer)
      - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams.](#4245-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams.](#4246-bounded-context-software-architecture-code-level-diagrams)
- [Capítulo V: Solution UX/UI Design](#capítulo-v-solution-ux/ui-design)
  - [5.1. Style Guidelines.](#51-style-guidelines)
    - [5.1.1. General Style Guidelines.](#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guidelines.](#512-web-mobile-and-iot-style-guidelines)
  - [5.2. Information Architecture.](#52-information-architecture)
    - [5.2.1. Organization Systems.](#521-organization-systems)
    - [5.2.2. Labeling Systems.](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags.](#523-seo-tags-and-meta-tags)
    - [5.2.4. Searching Systems.](#524-searching-systems)
    - [5.2.5. Navigation Systems.](#525-navigation-systems)
  - [5.3. Landing Page UI Design.](#53-landing-page-ui-design)
    - [5.3.1. Landing Page Wireframe.](#531-landing-page-wireframe)
    - [5.3.2. Landing Page Mock-up.](#532-landing-page-mock-up)
  - [5.4. Applications UX/UI Design.](#54-applications-ux/ui-design)
    - [5.4.1. Applications Wireframes.](#541-applications-wireframes)
    - [5.4.2. Applications Wireflow Diagrams.](#542-applications-wireflow-diagrams)
    - [5.4.3. Applications Mock-ups.](#543-applications-mock-ups)
    - [5.4.4. Applications User Flow Diagrams.](#544-applications-user-flow-diagrams)
  - [5.5. Applications Prototyping.](#55-applications-prototyping)
  - [5.6. IoT Device Design.](#56-iot-device-design)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
  - [6.1. Software Configuration Management.](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration.](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management.](#612-source-code-management)
    - [6.1.3. Source Code Style Guide & Conventions.](#613-source-code-style-guide--conventions)
    - [6.1.4. Software Deployment Configuration.](#614-software-deployment-configuration)
  - [6.2. Landing Page, Services & Applications Implementation.](#62-landing-page-services--applications-implementation)
    - [6.2.1. Sprint 1](#621-sprint-1)
      - [6.2.1.1. Sprint Planning 1.](#6211-sprint-planning-1)
      - [6.2.1.2. Aspect Leaders and Collaborators.](#6212-aspect-leaders-and-collaborators)
      - [6.2.1.3. Sprint Backlog 1.](#6213-sprint-backlog-1)
      - [6.2.1.4. Development Evidence for Sprint Review.](#6214-development-evidence-for-sprint-review)
      - [6.2.1.5. Testing Suite Evidence for Sprint Review.](#6215-testing-suite-evidence-for-sprint-review)
      - [6.2.1.6. Execution Evidence for Sprint Review.](#6216-execution-evidence-for-sprint-review)
      - [6.2.1.7. Services Documentation Evidence for Sprint Review.](#6217-services-documentation-evidence-for-sprint-review)
      - [6.2.1.8. Software Deployment Evidence for Sprint Review.](#6218-software-deployment-evidence-for-sprint-review)
      - [6.2.1.9. Team Collaboration Insights during Sprint.](#6219-team-collaboration-insights-during-sprint)
- [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)  

<div style="page-break-before: always;"></div>

# Student Outcome

| Criterio Específico | Acciones Realizadas | Conclusiones |
|---|---|---|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | **Ordoñez Ricaldi, Axel Randall:**<br>*TB1:* Participé activamente en la coordinación del equipo para la elaboración del Capítulo I y en la estructuración y priorización del Product Backlog en el Capítulo III, facilitando sesiones de trabajo colaborativo y asegurando una división equitativa de responsabilidades en la definición de historias de usuario y estimación de puntos de historia con objetividad y eficacia.<br><br>**Ccarita Cruz, Brayan Roberto:**<br>*TB1:* Lideré la sincronización del equipo multidisciplinario en la inicialización y estructuración del repositorio en GitHub, promoviendo una comunicación técnica fluida y eficaz para la definición de la arquitectura de la solución, e integrando los aportes de todos los miembros en la especificación de requisitos y diseño de bounded contexts.<br><br>**Panta Castro, Fabrizio Martin:**<br>*TB1:* Contribuí con objetividad en las dinámicas colaborativas del enfoque Lean UX en el Capítulo I y en el modelado de Domain-Driven Design (DDD) estratégico en el Capítulo IV, coordinando con el equipo la definición de contextos acotados y asegurando que las decisiones de diseño arquitectónico respondieran fielmente a los objetivos acordados.<br><br>**Loechle Arias, Mateo Italo:**<br>*TB1:* Colaboré eficientemente con el equipo en la investigación y análisis competitivo del Capítulo II, así como en la consolidación del diseño táctico de los bounded contexts y la revisión general del informe, fomentando la retroalimentación constructiva y asegurando el cumplimiento puntual y ordenado de los entregables.<br><br>**Guia Carrasco, Pedro Andre:**<br>*TB1:* Participé de forma activa en la planificación y ejecución de las entrevistas a los segmentos objetivo en el Capítulo II, coordinando los roles del equipo para la moderación, registro audiovisual y análisis sistemático de respuestas, garantizando objetividad en la recolección de hallazgos para el diseño de IoBuild.<br><br>**Alejo Jesus, Anyelo Bill:**<br>*TB1:* Contribuí en las sesiones de ideación y needfinding del Capítulo II, colaborando en la construcción de los User Personas, Empathy Maps y User Journey Maps junto al equipo, manteniendo una comunicación constante y asegurando que los requisitos identificados reflejaran fielmente las necesidades del usuario de forma consensuada.<br><br>**Escalante Baygorrea, Janiel Franz:**<br>*TB1:* Aporté con eficacia en la moderación y registro de los talleres de Big Picture EventStorming y la consolidación del Ubiquitous Language en el Capítulo II, integrando las distintas visiones multidisciplinarias de los miembros del equipo y alineando la terminología técnica y de negocio del proyecto con rigor y claridad. | En TB1, el equipo demostró un alto nivel de eficacia, eficiencia y objetividad al organizarse de manera multidisciplinaria mediante metodologías ágiles y herramientas colaborativas como Git, GitHub y entornos de modelado. Se logró una distribución equitativa de responsabilidades desde la concepción de la startup hasta el diseño de la arquitectura DDD y C4, manteniendo una comunicación constante, resolviendo discrepancias mediante consensos técnicos y asegurando entregables integrados, robustos y alineados con las buenas prácticas de la ingeniería de software. |
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software. | **Ordoñez Ricaldi, Axel Randall:**<br>*TB1:* Profundicé en el dominio de la administración residencial y condominios al elaborar el perfil de la solución y estructurar el Impact Mapping y Backlog, identificando los dolores operativos en el control manual de áreas comunes y cómo una solución IoT aporta valor tangible y medible al sector inmobiliario.<br><br>**Ccarita Cruz, Brayan Roberto:**<br>*TB1:* Analicé a profundidad el ecosistema de la domótica residencial y la gestión de infraestructura de edificios para formular los requisitos y la arquitectura de IoBuild, comprendiendo cómo los dispositivos IoT de monitoreo ambiental y conmutación de luminarias se integran funcionalmente en los procesos operativos de un condominio moderno.<br><br>**Panta Castro, Fabrizio Martin:**<br>*TB1:* Estudié el contexto de la gestión residencial y el comportamiento de los residentes en condominios mediante el desarrollo del Lean UX Canvas y el Bounded Context de Energy Management, analizando los patrones de consumo energético y las necesidades de confort térmico y lumínico en entornos habitacionales.<br><br>**Loechle Arias, Mateo Italo:**<br>*TB1:* Adquirí un conocimiento sólido del sector proptech y del mercado de automatización para edificios residenciales al realizar el benchmarking competitivo frente a plataformas comerciales, identificando brechas de costo, complejidad y oportunidades de mercado para IoBuild en el entorno residencial local.<br><br>**Guia Carrasco, Pedro Andre:**<br>*TB1:* Obtuve un entendimiento directo del sector inmobiliario y de administración de condominios al liderar las entrevistas con residentes y administradores, reconociendo de primera mano las deficiencias en la comunicación de incidencias, la falta de automatización en espacios compartidos y los requisitos del sector.<br><br>**Alejo Jesus, Anyelo Bill:**<br>*TB1:* Interioricé las dinámicas cotidianas del sector residencial y las expectativas de los copropietarios y administradores durante la elaboración de los User Personas y mapas de empatía, comprendiendo cómo las soluciones de software IoT deben adaptarse al estilo de vida de los residentes y a las reglas de administración condominal.<br><br>**Escalante Baygorrea, Janiel Franz:**<br>*TB1:* Desarrollé una comprensión integral de los flujos operativos del sector residencial al modelar los eventos de negocio en el Big Picture EventStorming y definir el lenguaje ubicuo, contextualizando términos como telemetría ambiental, actuadores de relé y zonas comunes dentro del dominio inmobiliario. | En TB1, el equipo evidenció un conocimiento riguroso y fundamentado del sector empresarial inmobiliario y de administración residencial (PropTech y domótica IoT en condominios). A través del levantamiento de información con usuarios reales, análisis exhaustivo de competidores y el modelado de dominio con EventStorming y DDD, el equipo comprendió a fondo los desafíos de eficiencia energética, automatización de áreas comunes y confort habitacional, logrando diseñar una solución de software que responde con precisión a las necesidades reales del mercado. |

---

<div style="page-break-before: always;"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
**IoBuild** es una startup tecnológica que nace con el propósito de democratizar y simplificar la integración del Internet de las Cosas (IoT) en el sector residencial y de la construcción. Diseñamos una **plataforma integral web y móvil** para el control y la gestión unificada de dispositivos IoT en condominios, abordando de manera cohesionada tanto los espacios comunes como los departamentos individuales.

A diferencia de las complejas soluciones industriales o de domótica propietaria de alto costo, IoBuild se enfoca en una solución accesible, práctica y viable. En su alcance principal, nuestra plataforma centraliza el monitoreo de **condiciones ambientales (sensores de temperatura y humedad)** y el control automatizado de la **iluminación a través de actuadores (módulos de relé)**. Esto permite, por ejemplo, automatizar el encendido y apagado de luces en pasillos y zonas compartidas de un condominio según horarios o niveles ambientales, así como brindar a cada residente el control remoto y personalizado del confort lumínico y térmico de su propio departamento desde su smartphone o navegador web.

IoBuild se dirige a dos segmentos clave:

- **Empresas constructoras, arquitectos y administradores de condominios:** que buscan incorporar un valor agregado tecnológico real, estandarizado y de bajo costo en sus proyectos residenciales, facilitando la supervisión y automatización básica de las áreas comunes.
- **Propietarios e inquilinos residenciales:** que desean disfrutar de mayor confort, supervisión ambiental y autonomía en sus viviendas mediante una interfaz amigable y sin complicaciones técnicas.

Nuestra propuesta de valor se sustenta en la simplicidad, la accesibilidad económica y la cohesión: conectar hardware accesible (microcontroladores, sensores y actuadores) con una arquitectura digital moderna que elimina la dispersión de aplicaciones.

- **Misión:** Facilitar la modernización de espacios residenciales a través de soluciones IoT accesibles, brindando a constructoras, administradores y residentes herramientas prácticas para el monitoreo ambiental y el control eficiente de dispositivos.
- **Visión:** Convertirnos en la plataforma referente de integración IoT residencial en la región, promoviendo viviendas y condominios más conectados, confortables y energéticamente conscientes.

<div style="page-break-before: always;"></div>

### 1.1.2. Perfiles de integrantes del equipo

| Miembros del equipo | Código Estudiante | Carrera | Conocimientos / Habilidades |
| :---: | :---: | :---: | :--- |
| <img src="assets/Axel-photo.jpg" alt="Axel Randall Ordoñez Ricaldi" width="85" style="max-height: 95px; object-fit: cover; border-radius: 4px;" /><br>**Ordoñez Ricaldi, Axel Randall** | U202216827 | Ingeniería de Software | Estudiante de la carrera de Ingeniería de Software en la UPC. Con capacidad para el trabajo en equipo y resolución de problemas técnicos bajo presión. Posee conocimientos en lenguajes como C# y Python, frameworks web y móviles como React, Vue y Angular, además de diseño y gestión de bases de datos relacionales y no relacionales como SQL y MongoDB. |
| <img src="assets/Brayan-photo.jpg" alt="Brayan Roberto Ccarita Cruz" width="85" style="max-height: 95px; object-fit: cover; border-radius: 4px;" /><br>**Ccarita Cruz, Brayan Roberto** | U20221c218 | Ingeniería de Software | Estudiante de la carrera de Ingeniería de Software en la UPC. Caracterizado por la perseverancia, puntualidad y enfoque en el cumplimiento eficiente de objetivos. Cuenta con experiencia en desarrollo con tecnologías como Golang y TypeScript, herramientas de frontend como Astro.js y Svelte, y aplicación de metodologías ágiles de diseño como Design Sprint. |
| <img src="assets/Fabrizio-photo.jpg" alt="Fabrizio Martin Panta Castro" width="85" style="max-height: 95px; object-fit: cover; border-radius: 4px;" /><br>**Panta Castro, Fabrizio Martin** | U20231a810 | Ingeniería de Software | Estudiante de la carrera de Ingeniería de Software en la UPC. Destacado por su proactividad, compañerismo y compromiso con el avance continuo del equipo. Posee competencias técnicas en C++ y Python, frameworks para desarrollo web y móvil como Flutter y Vue, así como administración de bases de datos relacionales SQL. |
| <img src="assets/mateo.jpg" alt="Mateo Italo Loechle Arias" width="85" style="max-height: 95px; object-fit: cover; border-radius: 4px;" /><br>**Loechle Arias, Mateo Italo** | U202215004 | Ingeniería de Software | Estudiante de la carrera de Ingeniería de Software en la UPC. Enfocado en el desarrollo backend con arquitectura hexagonal, diseño de interfaces de programación (APIs) y automatización de procesos. Cuenta con sólidos conocimientos en bases de datos relacionales y no relacionales como SQL y MongoDB, aportando al trabajo colaborativo con enfoque estructurado. |

<div style="page-break-before: always;"></div>

### 1.1.2. Perfiles de integrantes del equipo (continuación)

| Miembros del equipo | Código Estudiante | Carrera | Conocimientos / Habilidades |
| :---: | :---: | :---: | :--- |
| <img src="assets/pedro.jpeg" alt="Pedro Andre Guia Carrasco" width="85" style="max-height: 95px; object-fit: cover; border-radius: 4px;" /><br>**Guia Carrasco, Pedro Andre** | U202212010 | Ingeniería de Software | Estudiante de la carrera de Ingeniería de Software en la UPC, de 22 años. De perfil autodidacta y con vocación de liderazgo en equipos de trabajo, enfocado en generar confianza y seguridad en la dirección de proyectos. Posee capacitación técnica en lenguajes de programación como Java, Python, C#, JavaScript y TypeScript. |
| <img src="assets/Anyelo.jpg" alt="Anyelo Bill Alejo Jesus" width="85" style="max-height: 95px; object-fit: cover; border-radius: 4px;" /><br>**Alejo Jesus, Anyelo Bill** | U20231d149 | Ingeniería de Software | Estudiante de octavo ciclo de la carrera de Ingeniería de Software en la UPC. Caracterizado por ser una persona responsable, comprometida y con iniciativa, orientada a aportar activamente al logro de los objetivos del equipo. Cuenta con sólidos conocimientos en lenguajes como C++ y Python para el desarrollo eficiente de soluciones. |
| <img src="assets/janiel.jpeg" alt="Janiel Franz Escalante Baygorrea" width="85" style="max-height: 95px; object-fit: cover; border-radius: 4px;" /><br>**Escalante Baygorrea, Janiel Franz** | U201912668 | Ingeniería de Software | Estudiante próximo a egresar de la carrera de Ingeniería de Software en la UPC, con perfil Full Stack & AI Specialist. Especializado en el diseño e implementación de aplicaciones escalables, integración de soluciones de Inteligencia Artificial y experiencia comprobada en desarrollo integral end-to-end. |

<div style="page-break-before: always;"></div>

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
En los últimos años, el sector inmobiliario y de la construcción ha experimentado una transformación impulsada por la creciente demanda de espacios inteligentes, sostenibles y personalizables. Las tendencias globales en domótica, IoT (Internet of Things) y eficiencia energética han comenzado a redefinir la forma en que las personas interactúan con sus viviendas y lugares de trabajo. Sin embargo, en gran parte de Latinoamérica y específicamente en el Perú, la adopción de estas tecnologías sigue siendo limitada debido a altos costos de implementación, falta de estandarización y ausencia de soluciones accesibles para el usuario final.

Actualmente, la mayoría de proyectos inmobiliarios no incorpora de manera nativa funcionalidades inteligentes como control automatizado de iluminación, climatización, seguridad o gestión energética en tiempo real. Cuando estas soluciones se incluyen, suelen estar restringidas a segmentos de alto poder adquisitivo, generando una brecha de accesibilidad entre quienes pueden disfrutar de la tecnología y quienes no.

Por otro lado, los propietarios e inquilinos enfrentan problemas al intentar personalizar sus espacios: las opciones suelen ser costosas, requieren conocimientos técnicos avanzados o dependen de la contratación de múltiples proveedores sin integración entre sistemas. Esto genera experiencias fragmentadas y reduce el valor percibido de la inversión.

En el caso de las constructoras, arquitectos e ingenieros, la problemática se centra en la necesidad de diferenciar sus proyectos en un mercado altamente competitivo. Si bien existe interés en ofrecer soluciones innovadoras, los equipos de construcción se enfrentan a falta de plataformas unificadas que simplifiquen la integración de tecnología inteligente en sus edificaciones, lo que dificulta la planificación y eleva los costos de implementación.

La problemática puede resumirse en los siguientes puntos:
- **Accesibilidad limitada:** la mayoría de soluciones de automatización están dirigidas a mercados premium, dejando de lado a gran parte de la población.

- **Falta de estandarización:** los sistemas actuales suelen ser propietarios y poco compatibles, lo que genera barreras técnicas.

- **Costos elevados:** implementar tecnologías inteligentes requiere inversiones iniciales altas, lo que desalienta a constructoras y propietarios.

- **Complejidad técnica:** los usuarios finales carecen de herramientas intuitivas para personalizar y gestionar sus espacios de manera autónoma.

- **Baja diferenciación en proyectos inmobiliarios:** las constructoras tienen dificultades para ofrecer un valor agregado innovador frente a la competencia.

En este contexto, IoBuild surge como respuesta a la necesidad de democratizar el acceso a los espacios inteligentes, ofreciendo una plataforma que facilita la integración tecnológica desde la etapa de construcción hasta la personalización por parte del usuario final.<br><br>

**1. What (¿Qué?)**

La mayoría de proyectos inmobiliarios no incorporan de manera integral soluciones inteligentes desde su diseño, lo que provoca que los espacios continúen siendo rígidos y poco adaptables a las necesidades de los usuarios. Las opciones que existen en el mercado suelen estar enfocadas en segmentos de alto costo, como consecuencia, los usuarios finales terminan recurriendo a dispositivos aislados, como focos inteligentes o asistentes de voz, que no siempre son compatibles entre sí.

**2. Why (¿Por qué?)**

Porque las tecnologías de domótica e IoT han sido diseñadas de forma fragmentada, con estándares poco unificados que dificultan la integración entre sistemas. Además, el costo de implementación es elevado, ya que no solo implica la adquisición de hardware, sino también licencias y soporte especializado. A ello se suma la complejidad tecnológica, pues la configuración y mantenimiento de estos sistemas requieren conocimientos avanzados que no todos los usuarios poseen.

**3. Who (¿Quién?)**

Impacta principalmente en empresas constructoras, arquitectos e ingenieros que buscan diferenciar sus proyectos, pero no encuentran soluciones accesibles que les permitan añadir valor con espacios inteligentes. También, afecta a los propietarios e inquilinos, quienes experimentan frustración al no poder personalizar fácilmente sus viviendas u oficinas y ven reducido su nivel de confort.

**4. Where (¿Dónde?)**

Se manifiesta tanto en proyectos de construcción urbana como en remodelaciones de viviendas y oficinas. En el primer caso, los edificios se levantan bajo modelos tradicionales, con muy poca o nula integración de sistemas inteligentes, lo que limita el atractivo de las propuestas inmobiliarias. En el segundo, los propietarios interesados en modernizar sus espacios encuentran barreras técnicas y económicas que dificultan la incorporación de funcionalidades de automatización.

**5. When (¿Cuándo?)**

Se presenta en la actualidad, en un momento en que la digitalización y la sostenibilidad se han convertido en factores clave de competitividad. La demanda de espacios inteligentes es cada vez más alta, especialmente entre nuevas generaciones que valoran la tecnología como parte de su estilo de vida.

**6. How (¿Cómo?)**

Se refleja en la dificultad de las constructoras y arquitectos para ofrecer proyectos innovadores sin depender de sistemas costosos y difíciles de implementar. Para los propietarios e inquilinos, se traduce en experiencias limitadas, ya que deben conformarse con dispositivos sueltos que no logran integrarse en un ecosistema coherente.

**7. How much (¿Cuánto?)**

El costo de implementar tecnologías inteligentes en espacios inmobiliarios tradicionales suele ser elevado, no solo por el precio de los dispositivos, sino también por la necesidad de contratar integradores especializados y adquirir licencias propietarias. Para una empresa constructora, la integración de soluciones de automatización puede representar entre un 10 % y un 20 % adicional sobre el presupuesto inicial de un proyecto, lo que limita su adopción en desarrollos de bajo o mediano costo. Para un propietario, la inversión inicial en sistemas fragmentados puede superar varios miles de dólares, sin garantizar una experiencia unificada ni la posibilidad de escalar a nuevas funcionalidades.


### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
IoBuild es una plataforma digital que permite a empresas constructoras, arquitectos, ingenieros y propietarios transformar edificios y espacios en entornos inteligentes, accesibles y personalizables, fomentando la innovación en el sector inmobiliario y mejorando la experiencia de habitar y gestionar espacios.

**Contexto:** IoBuild es una plataforma que busca transformar edificios y espacios inmobiliarios en entornos inteligentes, accesibles y altamente personalizables. Nuestro servicio permite a empresas constructoras, arquitectos e ingenieros integrar fácilmente funcionalidades inteligentes en sus proyectos, al mismo tiempo que ofrece a propietarios e inquilinos la posibilidad de gestionar y personalizar su experiencia dentro de los espacios que habitan, sin necesidad de conocimientos técnicos avanzados.

**Observación del problema:** Sin embargo, hemos identificado que muchas empresas constructoras aún enfrentan barreras para implementar soluciones de automatización y gestión inteligente debido a la complejidad tecnológica, los altos costos y la falta de integración de sistemas. Por otro lado, los propietarios suelen experimentar frustración al no encontrar una forma sencilla y centralizada para controlar sus espacios, lo que limita la adopción de estas tecnologías. Estas observaciones provienen de entrevistas con profesionales de la construcción, arquitectos y usuarios finales, quienes señalan dificultades para incorporar soluciones accesibles y confiables que se adapten a las necesidades reales de sus proyectos y hogares.

**Impacto:** Esta situación genera una baja adopción de tecnologías inteligentes en nuevos proyectos inmobiliarios, lo que limita la capacidad de las constructoras para diferenciarse en el mercado y reduce el valor agregado que los propietarios perciben en sus viviendas o espacios de trabajo. Además, la falta de accesibilidad tecnológica contribuye a una brecha entre la innovación disponible y la experiencia práctica de los usuarios, afectando tanto la competitividad del sector como la satisfacción de los clientes finales.

**Necesidad insatisfecha:** Actualmente, las empresas constructoras, arquitectos e ingenieros necesitan soluciones integradas y fáciles de implementar para modernizar sus proyectos con tecnologías inteligentes. Al mismo tiempo, los propietarios requieren herramientas intuitivas y accesibles que les permitan personalizar y gestionar sus espacios de manera práctica, confiable y sin barreras técnicas.

**Pregunta de mejora:** ¿Cómo podríamos simplificar la integración y gestión de tecnologías inteligentes en proyectos inmobiliarios para que tanto constructoras como propietarios adopten estas soluciones con mayor facilidad, incrementando así el valor, la eficiencia y la satisfacción en los espacios construidos?

#### 1.2.2.2. Lean UX Assumptions.

En la fase inicial de desarrollo de la plataforma IoBuild, hemos identificado y articulado una serie de supuestos fundamentales siguiendo los principios del marco de trabajo Lean UX. Estos supuestos son nuestras hipótesis iniciales sobre quiénes son nuestros usuarios, qué beneficios esperan, cómo operará el negocio, el impacto que anticipamos generar y las características clave que necesitamos para lograrlo. Formalizar estas creencias nos permite enfocar el desarrollo del producto en la validación temprana, la minimización de riesgos y la toma de decisiones estratégicas basada en datos.

Los supuestos se han clasificado en cinco categorías principales para una estructuración clara:

- **User Assumptions**: Nuestras creencias sobre las necesidades, comportamientos y motivaciones de las empresas constructoras, arquitectos y propietarios.
- **User Outcome Assumptions**: Los resultados positivos y las ganancias de eficiencia que esperamos que nuestros usuarios experimenten al interactuar con IoBuild.
- **Business Assumptions**: Hipótesis sobre la viabilidad de nuestro modelo de negocio y el contexto del mercado inmobiliario.
- **Business Outcome Assumptions**: Los impactos mensurables que esperamos que la plataforma genere en la empresa, como crecimiento de ingresos y reducción de costos.
- **Feature Assumptions**: Nuestras creencias sobre cómo funcionalidades específicas resolverán los problemas de los usuarios y validarán los supuestos de negocio.

Estos supuestos formarán la estructura de nuestra estrategia de diseño y proporcionarán un marco para la validación continua.

- **User Assumptions** 
   - **Creemos que el 65 % de las empresas constructoras y arquitectos buscan soluciones de automatización de edificios que no requieran una integración compleja y costosa**, ya que las barreras tecnológicas y económicas actuales limitan la adopción de la domótica en sus proyectos.

   - **Creemos que el 90 % de los propietarios y arrendatarios valoran una interfaz de control unificada para sus hogares inteligentes**, porque la fragmentación de aplicaciones y dispositivos genera una experiencia frustrante e ineficiente.

   - **Creemos que el 80 % de los propietarios desea personalizar su entorno doméstico (iluminación, temperatura, seguridad) sin necesidad de conocimientos técnicos**, debido a que la personalización es un factor clave en la satisfacción residencial moderna.

   - **Creemos que el 75 % de los ingenieros y técnicos de la construcción desean herramientas que les permitan configurar y desplegar sistemas inteligentes de forma remota y sin interrupciones**, porque la gestión de proyectos a gran escala demanda flexibilidad y control en tiempo real.

   - **Creemos que el 55 % de los promotores inmobiliarios priorizarán la integración de tecnologías inteligentes si estas les permiten ofrecer un valor distintivo en el mercado**, ya que la innovación tecnológica se está convirtiendo en un factor decisivo de compra y arrendamiento.
<br>

- **User Outcome Assumptions**
   - **Creemos que si las constructoras pueden integrar nuestra solución con un proceso simplificado y modular, entonces reducirán el tiempo de implementación de tecnologías inteligentes en al menos un 40 %**, lo que les permitirá finalizar proyectos más rápido y de manera más competitiva.

    - **Creemos que si los propietarios tienen una herramienta accesible para controlar sus espacios, entonces su calificación de satisfacción con la experiencia de habitar será un 25 % superior** en encuestas de salida o de satisfacción anual.

    - **Creemos que si nuestra plataforma permite la gestión centralizada de múltiples funciones (seguridad, energía, confort), entonces el 60 % de los usuarios reportará una reducción significativa de la frustración** asociada al uso de múltiples aplicaciones dispares.

    - **Creemos que si los arquitectos y diseñadores pueden visualizar y simular la integración de nuestros sistemas en sus modelos BIM, entonces acelerarán su fase de diseño conceptual en un 30 %,** mejorando la eficiencia de sus flujos de trabajo.
<br>

- **Business Assumptions**
   - **Creemos que el 70 % de nuestros ingresos provendrá de la venta de licencias de proyecto (B2B)** a constructoras y arquitectos, y el 30 % restante de suscripciones y servicios de gestión para propietarios finales (B2C), ya que el sector de la construcción se digitaliza a un ritmo acelerado.

    - **Creemos que el 15 % de los proyectos registrados en la plataforma en el primer año superará los 100 usuarios activos**, lo que nos permitirá generar ingresos adicionales por el escalado de licencias.

    - **Creemos que mantendremos un margen bruto del 60 %**, ya que nuestro modelo de negocio de software y la producción bajo demanda evitan los costos de inventario.

    - **Creemos que cerraremos al menos 10 alianzas estratégicas con fabricantes de hardware y domótica**, lo que solidificará nuestra propuesta de valor y atraerá a un 20 % de clientes que prefieren ecosistemas de productos definidos.

    - **Creemos que al ofrecer una prueba de concepto gratuita para proyectos pequeños, lograremos convertir al 25 % de esos usuarios en clientes de pago en los primeros seis meses**, validando así la efectividad de nuestro embudo de ventas.

    - **Creemos que el 50 % de nuestras nuevas adquisiciones de clientes provendrá de marketing de contenido y alianzas con influenciadores de la industria inmobiliaria**, porque la confianza y las referencias son cruciales en este sector.
<br>

- **Business Outcome Assumptions**
    - **Creemos que si los propietarios adoptan y utilizan la plataforma con regularidad, entonces lograremos una tasa de retención de licencias B2C del 75 % en el primer año**, lo que generará un flujo de ingresos recurrente.
    - **Creemos que si la plataforma ofrece una experiencia de usuario fluida y sin complicaciones, entonces reduciremos los costos de soporte y atención al cliente en un 30 %** durante los primeros seis meses, mejorando la rentabilidad operativa.
    - **Creemos que si los ingenieros pueden configurar los sistemas de forma remota, entonces se reducirá en un 40 %** el tiempo y los costos de implementación en sitio, permitiéndonos escalar nuestra operación a más proyectos simultáneamente.
    - **Creemos que si fortalecemos las alianzas estratégicas, entonces conseguiremos una reducción del 15 % en los costos de adquisición de clientes (CAC)**, ya que las recomendaciones de nuestros socios nos proporcionarán nuevos clientes de forma más eficiente.
    - **Creemos que si las empresas constructoras pueden integrar nuestra plataforma fácilmente, entonces incrementaremos la tasa de conversión de proyectos de prueba a clientes de pago en un 25 %** durante el primer semestre, aumentando los ingresos directos.
<br>

- **Feature Assumptions**
    - **Creemos que la funcionalidad de un constructor de espacios inteligentes permitirá a los arquitectos e ingenieros diseñar layouts arrastrando y soltando dispositivos IoT**, de modo que el 60 % de ellos lo utilice para planificar sus proyectos en la plataforma.
    - **Creemos que el simulador en tiempo real de flujos de automatización permitirá a las constructoras validar la lógica de sus sistemas antes de la instalación**, de forma que el 90 % lo utilice para probar sus configuraciones.
    - **Creemos que el panel de control unificado permitirá a los propietarios gestionar su espacio desde una sola interfaz**, consiguiendo que el 80 % lo use como su herramienta principal de control diario.
    - **Creemos que la integración con marcas de hardware permitirá a los usuarios conectar sus dispositivos existentes a la plataforma**, logrando que el 70 % de los clientes B2C lo use en su primera semana de activación.
    - **Creemos que las notificaciones y alertas personalizables permitirán a los usuarios estar al tanto de la seguridad y el consumo de energía en sus propiedades**, de forma que el 50 % de ellos configure al menos 3 alertas en los primeros 30 días.
    - **Creemos que la funcionalidad de acceso remoto permitirá a los ingenieros y propietarios gestionar sus espacios desde cualquier lugar**, alcanzando que el 75 % de las gestiones fuera de la oficina se realicen en dispositivos móviles.
    - **Creemos que el sistema de reportes de consumo de energía permitirá a los usuarios tomar decisiones para optimizar sus gastos**, logrando una disminución del 20 % en el consumo energético reportado en el primer año.
    - **Creemos que la funcionalidad de creación de escenas o perfiles ambientales personalizados (ej. "Modo descanso", "Modo concentración") simplificará la vida de los propietarios**, con el 60 % de ellos creando al menos una escena en el primer mes de uso.
    - **Creemos que la integración con asistentes de voz (ej. Alexa, Google Home) mejorará la experiencia del usuario**, consiguiendo que el 40 % de los usuarios de hogares inteligentes conecte su cuenta en los primeros tres meses.
    - **Creemos que un sistema de permisos y roles permitirá a los administradores de proyectos controlar quién puede acceder a qué funciones**, logrando una reducción del 95 % en los problemas de seguridad o acceso no autorizado reportados.
<br>

#### 1.2.2.3. Lean UX Hypothesis Statements.

- **Creemos que lograremos** una tasa de retención de licencias B2C del 75% en el primer año  
  **Si** propietarios y arrendatarios  
  **Obtienen** una calificación de satisfacción un 25% superior en la experiencia de habitar  
  **Con** el panel de control unificado de la plataforma.<br><br>

- **Creemos** que lograremos reducir los costos de soporte y atención al cliente en un 30% en seis meses  
  **Si** usuarios finales (propietarios)  
  **Obtienen** una reducción significativa de la frustración al gestionar múltiples funciones  
  **Con** la funcionalidad de gestión centralizada de seguridad, energía y confort.<br><br>

- **Creemos** que lograremos reducir en un 40% los costos de implementación en sitio  
  **Si** ingenieros y técnicos de la construcción  
  **Obtienen** la posibilidad de configurar y desplegar sistemas de forma remota y sin interrupciones  
  **Con** la funcionalidad de acceso remoto para proyectos inteligentes.<br><br>

- **Creemos** que lograremos una reducción del 15% en el CAC gracias a alianzas estratégicas  
  **Si** constructoras y arquitectos  
  **Obtienen** un 30% de aceleración en la fase de diseño conceptual  
  **Con** el constructor de espacios inteligentes y la simulación en modelos BIM.<br><br>

- **Creemos** que lograremos incrementar la tasa de conversión de proyectos de prueba a clientes de pago en un 25% durante el primer semestre  
  **Si** empresas constructoras  
  **Obtienen** una reducción del 40% en el tiempo de implementación de tecnologías inteligentes  
  **Con** el simulador en tiempo real de flujos de automatización.<br><br>

- **Creemos** que lograremos un flujo de ingresos recurrente gracias a una tasa de retención B2C del 75%  
  **Si** propietarios  
  **Obtienen** una gestión centralizada que reduce en un 60% la frustración de usar múltiples aplicaciones  
  **Con** la integración con asistentes de voz y el panel unificado de IoBuild.<br><br>

- **Creemos** que lograremos reducir los costos de soporte en un 30% en los primeros seis meses  
  **Si** propietarios de viviendas inteligentes  
  **Obtienen** un aumento del 25% en su satisfacción con la experiencia de habitar  
  **Con** la funcionalidad de personalización de escenas y perfiles ambientales para optimizar el confort y el consumo.<br><br>

- **Creemos** que lograremos escalar nuestra operación a más proyectos simultáneamente reduciendo en un 40% los costos de implementación  
  **Si** ingenieros y técnicos de construcción  
  **Obtienen** mayor flexibilidad y control remoto de los sistemas inteligentes  
  **Con** el sistema de gestión remota y reportes energéticos en la plataforma.<br><br>

- **Creemos** que lograremos incrementar los ingresos directos en un 25% al convertir proyectos de prueba en clientes de pago  
  **Si** constructoras y promotores inmobiliarios  
  **Obtienen** una reducción del 40% en el tiempo de integración de tecnologías inteligentes en sus proyectos  
  **Con** la prueba de concepto gratuita y el simulador en tiempo real de automatización.<br><br>

- **Creemos** que lograremos reducir en un 40% los costos y tiempos de implementación en sitio  
  **Si** ingenieros de proyectos  
  **Obtienen** una aceleración del 30% en la fase de diseño conceptual  
  **Con** el simulador en tiempo real y la integración con modelos BIM.<br><br>

- **Creemos** que lograremos una reducción del 15% en el CAC gracias a recomendaciones de socios estratégicos  
  **Si** promotores inmobiliarios  
  **Obtienen** una experiencia de integración simplificada y modular que disminuye el tiempo de implementación en un 40%  
  **Con** la integración directa con marcas de hardware compatibles.<br><br>

- **Creemos** que lograremos incrementar los ingresos directos en un 25% durante el primer semestre  
  **Si** constructoras  
  **Obtienen** una disminución del 60% en la frustración por la fragmentación de aplicaciones  
  **Con** la gestión centralizada de funciones en un solo panel de control.<br><br>

- **Creemos** que lograremos un flujo de ingresos recurrente mediante la retención del 75% de usuarios B2C  
  **Si** propietarios y arrendatarios  
  **Obtienen** un 20% de reducción en su consumo energético anual  
  **Con** el sistema de reportes y análisis de consumo de energía.<br><br>

- **Creemos** que lograremos reducir los costos de soporte en un 30% en seis meses  
  **Si** usuarios residenciales  
  **Obtienen** una experiencia personalizada sin necesidad de conocimientos técnicos  
  **Con** la funcionalidad de creación de escenas y automatizaciones adaptadas al usuario.<br><br>


#### 1.2.2.4. Lean UX Canvas.

<div align="center">
  <img src="assets/Lean_UX_Canvas.png" alt="Lean UX Canvas" width="650" />
</div>

## 1.3. Segmentos objetivo.

| Variables | Segmento 1: Arquitectos e Ingenieros Civiles (B2B) | Segmento 2: Dueños y Residentes de Apartamentos (B2C) |
|---|---|---|
| **Definición del segmento** | Profesionales de la construcción, diseño arquitectónico e ingeniería civil involucrados en la planificación, edificación o administración de proyectos inmobiliarios multifamiliares y condominios residenciales. | Propietarios e inquilinos que habitan departamentos en condominios residenciales y buscan modernizar su vivienda con soluciones prácticas de confort, supervisión ambiental y automatización. |
| **Geográfica** | Principalmente en áreas urbanas de alto crecimiento inmobiliario en Latinoamérica, con especial énfasis en ciudades capitales (como Lima Metropolitana, Bogotá o Ciudad de México), donde la demanda y densificación de proyectos de vivienda colectiva y torres de departamentos es intensiva. | Residentes en zonas urbanas consolidadas y distritos de media y alta densidad residencial (como distritos céntricos o suburbanos de Lima y principales urbes). Priorizan la conectividad, la accesibilidad a servicios y la modernidad de su entorno habitacional. |
| **Demográfica** | • **Edad:** 30 a 55 años.<br>• **Género:** Hombres y mujeres profesionales.<br>• **Educación:** Superior universitaria completa (Arquitectura, Ingeniería Civil, Edificaciones o afines).<br>• **Nivel de Ingresos:** Medio-alto a alto.<br>• **Ocupación:** Proyectistas independientes, contratistas o líderes técnicos en empresas constructoras e inmobiliarias. | • **Edad:** 25 a 45 años.<br>• **Género:** Mixto.<br>• **Educación:** Nivel universitario o técnico superior.<br>• **Nivel de Ingresos:** Medio a medio-alto.<br>• **Estado Civil / Hogar:** Solteros, parejas jóvenes o familias pequeñas que adquieren su primera o segunda vivienda.<br>• **Ocupación:** Profesionales urbanos, colaboradores en modalidad remota/híbrida o emprendedores. |
| **Psicológica (Psicográfica)** | Orientados a la innovación y sostenibilidad, valoran la diferenciación competitiva y la eficiencia de costos. Buscan integrar tecnología domótica e IoT sin complicaciones de instalación industrial ni sobrecostos que encarezcan el metro cuadrado. Son meticulosos, analíticos y pragmáticos, motivados por entregar edificaciones modernas y atractivas para la venta o arriendo. | Buscadores de confort térmico, lumínico y tranquilidad. Tienen una actitud práctica ante la tecnología: valoran la conveniencia del día a día, la privacidad y el ahorro energético. Su estilo de vida es dinámico y aprecian llegar a un hogar con ambientes acogedores, automatizados y fáciles de controlar sin requerir soporte técnico constante. |
| **Función de comportamiento** | Evalúan e incorporan soluciones tecnológicas desde la etapa de diseño de planos y memoria descriptiva. Valoran la estandarización y compatibilidad con hardware accesible (sensores ambientales y actuadores/relés para iluminación en pasillos o áreas comunes). Se frustran enormemente por sistemas propietarios cerrados, costosos o difíciles de configurar en obra. Su meta es entregar condominios con valor agregado inteligente garantizando viabilidad técnica y operativa. | Uso frecuente y diario de aplicaciones móviles y asistentes para el hogar. Su adopción de tecnología se basa estrictamente en la facilidad de uso y la inmediatez: desean verificar la temperatura/humedad de sus habitaciones y controlar las luces (o activar escenas como "Modo Noche" o "Modo Fuera de Casa") con un toque. Se frustran ante la multiplicidad de apps incompatibles o fallas de configuración. Su meta es maximizar el bienestar dentro de su vivienda de forma intuitiva. |

---

<div style="page-break-before: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.
### 2.1.1. Análisis competitivo.
|  | **Competitive Analysis** |
| :---: | :--- |
| ¿Por qué llevar acabo este análisis? | El objetivo es identificar oportunidades de mejora y diferenciación frente a nuestros principales competidores en el sector de automatización, control de acceso y domótica. |

|  | IoBuild | MWF Solutions | Orvibo Perú | Domotec Perú |
| :---: | :--- | :--- | :--- | :--- |
| *Logo* | <img src="assets/iobuild_logo.png" alt="IoBuild" width="115" style="max-height: 42px; object-fit: contain;" /> | <img src="assets/mwf_solutions_logo.jpeg" alt="MWF Solutions" width="55" height="55" style="object-fit: contain;" /> | <img src="assets/orvibo_logo.jpg" alt="Orvibo" width="55" height="55" style="object-fit: contain;" /> | <img src="assets/domotec_logo.png" alt="Domotec Perú" width="100" style="max-height: 42px; object-fit: contain;" /> |
| *Overview* | Startup que transforma edificios y espacios en entornos inteligentes, accesibles y personalizables. Ofrece una plataforma digital sencilla para constructoras, arquitectos y propietarios, facilitando la integración de soluciones smart. | Empresa líder en soluciones multitécnicas. Especialistas en diseño, ejecución y mantenimiento de proyectos de ingeniería. | Empresa dedicada a soluciones de domótica y automatización de hogares. | Especialistas en convertir hogares y edificios en Smart Home, ofreciendo control desde dispositivos móviles y asistentes de voz. |
| *Ventaja competitiva ¿Qué valor ofrece a los clientes?* | Enfoque low-barrier: integración simplificada, costos accesibles y experiencia de usuario unificada. Prioriza la personalización, escalabilidad y eficiencia energética. | Equipo de ingenieros altamente capacitados. Experiencia comprobada en proyectos exitosos. Alta calidad, eficiencia energética y estándares internacionales. Partner estratégico en todas las fases del proyecto (diseño, ejecución, mantenimiento). | Ofrecen soluciones completas de domótica personalizadas para hogares y empresas. Control y monitoreo fácil desde app, voz y diversos equipos smart. | Soluciones profesionales, completas y fáciles de usar. Integración con asistentes de voz (Apple, Alexa, Google). Garantizan la ciberseguridad y control centralizado de todos los dispositivos. |
| *Mercado Objetivo* | Constructoras que buscan diferenciarse con proyectos inteligentes sin complejidad tecnológica. Propietarios que desean personalizar y gestionar sus hogares de manera práctica y accesible. | Empresas constructoras de oficinas, edificaciones industriales, comerciales y residenciales que necesiten ingeniería multitécnica. | Oficinas y hogares interesados en automatización y domótica. | Hogares, edificios, hoteles y oficinas interesados en automatización y modernización smart. |
| *Estrategia de Marketing* | Redes sociales (Facebook, Instagram, Youtube, Linkedin). Marketing de contenidos (demos). | Activos en Facebook, Linkedin, Instagram y Youtube. Promoción de servicios, casos de éxito, y artículos de ingeniería. | Redes Sociales (Facebook, Instagram, Youtube). Promocionan productos y nuevas tecnologías en posts. | Redes Sociales (Facebook, Instagram, Linkedin); Enfocados en la experiencia de usuario y difusión de soluciones smart. |
| *Productos y servicios* | Control unificado de iluminación, clima, seguridad, riego y energía. Funcionalidades avanzadas: escenas personalizadas, reportes de consumo, permisos multiusuario, integración con Alexa/Google Home. | Aire acondicionado, ventilación, clima, seguridad electrónica, domótica, automatización, energía, instalación eléctrica, sistemas contra incendio, refrigeración, mantenimiento. | Smart Film, cortinas inteligentes, gestión y ahorro de energía, seguridad smart, equipos Sonoff, luces smart, audio, jardín smart. | Cerraduras inteligentes, cortinas inteligentes, iluminación inteligente, seguridad, redes unificadas, interfaces, soluciones de automatización personalizadas. |
| *Precios y costos* | B2B: licencias por proyecto + servicios de integración. Instalación inicial con costo fijo ajustado al proyecto. B2C: suscripción mensual/anual según tamaño del espacio. | Cotización personalizada, generalmente modelo proyecto a medida (no disponibles en línea). | Servicios personalizados. Contacto para cotización (no disponibles en línea) basado en la selección del cliente. | Servicios personalizados. Contacto para cotización. Ventas por proyecto, cada solución es a medida. |
| *Canales de distribución (Web y/o Móvil)* | Plataforma web y aplicación móvil. Contacto directo vía sitio web, WhatsApp, correo y redes sociales. | Web, contacto vía sitio, redes sociales, WhatsApp, email, móvil para atención y soporte. | Web, contacto por teléfono, correo, WhatsApp, y redes sociales. | Web, WhatsApp, contacto por teléfono, presencial. |
| *Fortalezas* | Modelo de negocio por suscripción (ingresos recurrentes). Alianza directa con constructoras. Servicio integral que incluye instalación, soporte de cableado y plataforma centralizada. Doble interfaz para administradores y residentes. | Especialistas en experiencia de cliente smart y conectividad centralizada. Trabajan múltiples verticales (hogares, hoteles, edificios). Alto nivel de integración. | Propuesta innovadora con soluciones “llave en mano” para hogares inteligentes. Fácil integración y foco en simplificar la tecnología al usuario doméstico. | Experiencia multisectorial, enfoque integral en proyectos. Soluciones personalizadas para empresas. Alta capacidad técnica y enfoque en eficiencia y cumplimiento normativo. |
| *Debilidades* | Alta dependencia del sector construcción e inmobiliario. Ciclo de ventas potencialmente largo con las constructoras. Requiere una inversión inicial fuerte en tecnología y personal técnico especializado. | Foco muy avanzado puede limitar llegada a usuarios menos familiarizados. Reto en escalar por requerir asesoría y soporte muy personalizado. | Menor penetración en segmento corporativo. Posible dependencia de productos de marcas externas/globales para domótica. Segmentación principalmente residencial. | Dependencia de proyectos grandes (segmento corporativo/industrial). Requiere relaciones comerciales de largo plazo. Adaptación tecnológica constante frente a nuevas tendencias globales. |
| *Oportunidades* | Auge de los "edificios inteligentes" como estándar en nuevos proyectos inmobiliarios. Potencial para ofrecer servicios de valor añadido (mantenimiento predictivo, analítica de datos). Expansión a otros mercados verticales. | Hoteles y edificios buscan modernización. Auge de viviendas premium smart. Oportunidad de crear plataformas propias de gestión y control. Potencial expansión internacional. | Tendencia de adopción masiva de IoT y hogares inteligentes en Latinoamérica. Posibilidad de alianzas con desarrolladoras inmobiliarias. Ampliación de servicios postventa y soporte. | Crecimiento del mercado en automatización industrial y sostenibilidad. Expansión a nuevos mercados verticales (hospitales, data centers, infraestructuras especiales). Alianzas con marcas globales. |
| *Amenazas* | Posible resistencia de las constructoras a adoptar un modelo de suscripción. Ciberseguridad como riesgo crítico al centralizar el control del edificio. Rápida evolución de estándares y protocolos IoT que exigen actualización constante. | Vulnerabilidad a cambios en protocolos de asistentes de voz o plataformas smart grandes. Volatilidad del mercado inmobiliario. Ciberseguridad como preocupación creciente. | Entradas de nuevas startups globales con soluciones más económicas o DIY. Cambio rápido de estándares (protocolos, compatibilidad). Piratería tecnológica. | Competencia de multinacionales o integradores globales. Cambios regulatorios en el sector técnico. Riesgo tecnológico por obsolescencia rápida de equipos o sistemas. |

### 2.1.2. Estrategias y tácticas frente a competidores.
A partir del análisis competitivo realizado, se propone la siguiente tabla de estrategias y tácticas. El objetivo es identificar oportunidades de mejora y diseñar acciones específicas que permitan a **IoBuild** superar las debilidades detectadas en los principales competidores, fortalecer su propuesta de valor y consolidar una ventaja competitiva sostenible en el mercado.

| Competidores | ¿Qué debemos hacer para destacar más frente a nuestros principales competidores? |
| :--- | :--- |
| **Domotec Perú** | La fortaleza de Domotec es la alta personalización. Debemos posicionar nuestro modelo de suscripción como una solución **más escalable y financieramente predecible** para las constructoras. Enfatizar que ofrecemos un ecosistema estandarizado y fácil de implementar en proyectos inmobiliarios completos, reduciendo la complejidad y el costo por unidad en comparación con sus soluciones a medida. |
| **Orvibo Perú** | Su enfoque es el cliente final (B2C) y la "llave en mano" en hogares ya construidos. Nuestra estrategia debe ser resaltar el valor de una **integración nativa desde la fase de construcción**. Debemos demostrar a las inmobiliarias cómo nuestra plataforma no solo beneficia al residente, sino que ofrece una herramienta de gestión y mantenimiento centralizada para el administrador del edificio, una ventaja competitiva que Orvibo no posee. |
| **MWF Solutions** | Este competidor se enfoca en proyectos industriales complejos y de gran escala. Debemos posicionarnos como los **especialistas en el sector residencial inteligente**. Nuestra plataforma es más ágil, está diseñada para la experiencia del usuario residencial y nuestro modelo de negocio (suscripción) es más adecuado para la gestión de propiedades que el modelo de proyecto único y de alto costo de MWF. |

## 2.2. Entrevistas.
Para comprender a fondo las necesidades, expectativas y frustraciones de nuestros segmentos clave —ingenieros y arquitectos de constructoras, y propietarios o residentes de viviendas e inmuebles— realizamos entrevistas estructuradas con formularios diseñados específicamente para cada grupo. Las preguntas abiertas permitieron explorar su experiencia en el uso de tecnologías inteligentes, sus prioridades al diseñar o habitar un espacio, y sus percepciones sobre personalización, accesibilidad y eficiencia.

Las entrevistas fueron registradas, resumidas y posteriormente analizadas para identificar patrones de comportamiento y criterios de decisión. Los resultados sirvieron de base para elaborar User Personas, Empathy Maps y User Task Matrices, herramientas que nos permitieron captar con mayor claridad los puntos clave de cada segmento.

Las entrevistas realizadas aportaron información clave para definir los requisitos y guiar el diseño de IoBuild, asegurando que la plataforma responda a las expectativas de constructores y propietarios en la gestión de espacios inteligentes.

### 2.2.1. Diseño de entrevistas.
En esta sección se define la información a recolectar de los segmentos objetivos. Los datos demográficos y de perfil básico de los entrevistados se registran previamente mediante el siguiente formulario: [Formulario de Registro de Entrevistas](https://docs.google.com/forms/d/e/1FAIpQLSd4m5vmdvWBw-Lr2Kmbf6e4agyUNKCXlsnA6-H6IMEBz90eTg/viewform?usp=dialog).

A fin de garantizar sesiones dinámicas con una duración máxima estimada de **5 minutos** por participante, las preguntas han sido sintetizadas y adaptadas al alcance específico de **IoBuild**: integración accesible de hardware IoT (sensores de temperatura y humedad, y control de iluminación mediante actuadores/relés) en proyectos multifamiliares y residenciales.

---

#### Segmento 1: Arquitectos e Ingenieros Civiles (B2B)
1. **Demanda y experiencia:** En los proyectos inmobiliarios multifamiliares que ha diseñado o liderado, ¿ha recibido solicitudes para incorporar automatización o domótica (como control eficiente de iluminación o monitoreo ambiental)? ¿Con qué frecuencia?
2. **Frustraciones y costos:** ¿Cuáles han sido los mayores obstáculos al intentar integrar tecnología inteligente en obra (ej. sobrecostos de soluciones industriales cerradas, complejidad de cableado o falta de estandarización)?
3. **Viabilidad técnica en planos:** Desde la etapa de planos, ¿qué tan viable considera preinstalar una infraestructura IoT accesible (sensores ambientales y relés/actuadores para iluminación en pasillos, áreas comunes o departamentos) sin encarecer significativamente el metro cuadrado?
4. **Valor comercial y diferenciación:** En una escala del 1 al 10, ¿cuánto valor o atractivo comercial cree que aporta a una torre de apartamentos incluir preinstalación IoT y una plataforma de control centralizada frente a la competencia?
5. **Mantenimiento y gestión post-construcción:** ¿De qué manera un panel web unificado que permita supervisar dispositivos y estados en tiempo real facilitaría el trabajo de entrega y mantenimiento entre constructora y administración del edificio?
6. **Modelo de suscripción:** ¿Qué disposición observa en promotores o juntas de administración hacia un modelo SaaS (suscripción mensual/anual accesible) que garantice soporte técnico continuo, actualizaciones y compatibilidad del ecosistema?

---

#### Segmento 2: Propietarios y Residentes de Apartamentos (B2C)
1. **Hábitos y uso actual:** En su día a día dentro del departamento, ¿utiliza o le interesaría utilizar dispositivos inteligentes para gestionar la iluminación o supervisar el confort térmico (temperatura y humedad)?
2. **Frustraciones tecnológicas:** ¿Ha enfrentado problemas con soluciones inteligentes previas (ej. configuraciones complejas, tener múltiples aplicaciones incompatibles entre sí o caídas de conexión)?
3. **Casos de uso prioritarios:** Si pudiera gestionar su departamento desde una app unificada, ¿en qué momentos le resultaría más valioso (ej. programar el apagado automático de luces al salir/dormir, o recibir alertas si la humedad o temperatura varían fuera de lo normal)?
4. **Influencia en la decisión de compra/alquiler:** En una escala del 1 al 10, ¿cuánto influiría en su decisión de compra o alquiler que el departamento ya cuente con automatización de luces y monitoreo ambiental integrado desde el primer día?
5. **Preocupaciones clave:** Al utilizar una aplicación para gestionar el confort y la energía de su hogar, ¿cuáles son sus mayores inquietudes (facilidad de uso para toda la familia, privacidad de datos o estabilidad del servicio)?
6. **Disposición al modelo de servicio:** Si el departamento ya viene con los sensores y actuadores instalados, ¿estaría dispuesto a mantener una suscripción mensual accesible por funciones avanzadas como reportes de eficiencia de energía, automatizaciones personalizadas y soporte garantizado?

### 2.2.2. Registro de entrevistas.
En esta sección se documenta detalladamente cada entrevista realizada a los distintos segmentos objetivo. Se incluye información relevante como el perfil del entrevistado, sus respuestas y los principales hallazgos obtenidos.

#### Segmento objetivo #1: Arquitectos e Ingenieros Civiles (B2B)

| Segmento objetivo #1: Arquitectos/Ingenieros | |
|---|---|
| **Entrevista 1:** Javier Maximo Ordoñez Cordova | |
| **Enlace de la entrevista:** | [https://youtu.be/l9eikn4YOmw](https://youtu.be/l9eikn4YOmw) |
| **Sexo:** Masculino | **Edad**: 59 |
| **Instante en el que inicia:** 0 minutos y 0 segundos | **Duración:** 5 minutos y 7 segundos |
| **Imagen del entrevistado:**<br><img src="assets/Entrevistdo1.png" alt="Entrevistado 1 - Javier Ordóñez" height="180" style="max-height: 180px; border-radius: 4px;" /> | |
| **Resumen de la entrevista:**<br>Javier Ordóñez Córdoba es arquitecto con 30 años de experiencia en el sector. A lo largo de su trayectoria ha ejercido como docente en construcción civil, perito judicial en obras públicas, funcionario en municipalidades en áreas de desarrollo urbano y obras, además de supervisor y residente de proyectos arquitectónicos. Su trabajo está centrado en el diseño de viviendas, departamentos y otras edificaciones, siempre buscando garantizar buenas condiciones de ventilación, iluminación natural y distribución de espacios que favorezcan el bienestar de los usuarios.<br>Considera esencial mantenerse actualizado en el uso de software y herramientas tecnológicas como Revit, que simplifican procesos constructivos y permiten una mejor colaboración. Está abierto a la integración de tecnologías inteligentes en viviendas, como sistemas de iluminación automatizada, accesos inteligentes y control inalámbrico de dispositivos, aunque reconoce que esto incrementa ligeramente los costos de construcción. En cuanto a sostenibilidad, enfatiza la necesidad de priorizar energías renovables, como la solar y la eólica, para reducir la dependencia de fuentes contaminantes y costosas.<br>Entre sus frustraciones destaca la falta de apoyo gubernamental al desarrollo de la arquitectura y los bajos sueldos en comparación con el aporte profesional que se brinda. Pese a ello, se mantiene enfocado en incorporar innovaciones que satisfagan a los usuarios y en fomentar edificaciones modernas, sostenibles y adaptadas a las tendencias actuales del mercado inmobiliario.<br><br>**Datos adicionales del entrevistado:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows<br>**Dispositivo usado con más frecuencia:** Computadora estacionaria, Laptop, Smartphone<br>**Dispositivo móvil preferido:** Android<br>**Principal medio de contacto:** Apps de colaboración<br>**Herramientas utilizadas:** Revit y software de diseño arquitectónico.<br>**Enfoque de diseño:** Distribución eficiente de espacios, ventilación e iluminación natural.<br>**Tecnologías inteligentes incorporadas:** Iluminación automatizada, accesos inteligentes, control inalámbrico de agua, desagüe y comunicación.<br>**Factores clave en diseño residencial:** Necesidades del usuario, satisfacción del cliente final y adaptación a tendencias tecnológicas.<br>**Motivaciones:** Crear edificaciones sostenibles y modernas, incorporar tecnologías inteligentes, mejorar procesos constructivos con software especializado.<br>**Frustraciones:** Falta de apoyo gubernamental, bajos sueldos en el sector, limitaciones presupuestarias de los clientes. | |
| | |
| **Entrevista 2:** Arturo Velazco | |
| **Enlace de la entrevista:** | [https://youtu.be/zBm7PVg4cjI](https://youtu.be/zBm7PVg4cjI) |
| **Sexo:** Masculino | **Edad:** 57 |
| **Instante en el que inicia:** 11 minutos y 6 segundos | **Duración:** 4 minutos y 59 segundos |
| **Imagen del entrevistado:**<br><img src="assets/Entrevistdo3.png" alt="Entrevistado 2 - Arturo Velazco" height="180" style="max-height: 180px; border-radius: 4px;" /> | |
| **Resumen de la entrevista:**<br>Arturo Velasco es ingeniero civil colegiado desde 1994, con más de 30 años de experiencia en el sector construcción, especialmente en proyectos inmobiliarios y multifamiliares. Ha participado en obras de gran envergadura, como la ciudad de Nueva Cuerabamba, una central termoeléctrica y diversos edificios residenciales. Actualmente se desempeña como jefe de producción en una empresa inmobiliaria, donde prioriza la eficiencia en la gestión de obra, la coordinación de planos y tableros eléctricos, así como la integración de sistemas de automatización. En su labor enfatiza la comodidad del cliente, la eficiencia en las instalaciones y la coordinación entre especialidades. Sus objetivos incluyen escalar a puestos de mayor responsabilidad, fundar su propia constructora y aplicar su experiencia en proyectos modernos y altamente competitivos.<br>Entre los principales retos que identifica se encuentran la incompatibilidad de planos, las limitaciones técnicas de contratistas y el incremento de costos al integrar nuevas tecnologías. Reconoce que la automatización de luminarias, audio, cortinas, tomas eléctricas y electrodomésticos aporta un valor agregado de 7 a 8 en el mercado, aunque su adopción en el Perú aún es limitada. Considera viable una implementación progresiva con factibilidad de 6 sobre 10, siempre que no incremente significativamente los costos, y resalta que la clave está en alinear a clientes, constructores y autoridades. Además, señala como factores clave en el diseño residencial la adaptación a las necesidades del cliente, la integración tecnológica, la sostenibilidad y la eficiencia energética, recomendando que toda innovación se implemente de forma práctica y enfocada en la confianza y la eficiencia para los usuarios finales.<br><br>**Datos adicionales del entrevistado:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows<br>**Dispositivo usado con más frecuencia:** Laptop<br>**Dispositivo móvil preferido:** iOS<br>**Principal medio de contacto:** LinkedIn<br>**Herramientas utilizadas:** Revit.<br>**Enfoque de diseño:** Optimiza procesos, unifica sistemas y prioriza la eficiencia y satisfacción del cliente.<br>**Tecnologías inteligentes incorporadas:** Uso de BIM (Revit) y automatización en puertas y semáforos, con visión de integración futura.<br>**Factores clave en diseño residencial:** Demanda del mercado, eficiencia energética, seguimiento postventa e innovación progresiva.<br>**Motivaciones:** Centralizar herramientas, mantener competitividad y modernizar la gestión con nuevas tecnologías.<br>**Frustraciones:** Resistencia tecnológica, burocracia estatal, tecnologías inestables y falta de apoyo institucional. | |
| | |
| **Entrevista 3:** Miguel Díaz | |
| **Enlace de la entrevista:** | [https://youtu.be/M1nDEEuHymI](https://youtu.be/M1nDEEuHymI) |
| **Sexo:** Masculino | **Edad:** 31 |
| **Instante en el que inicia:** 16 minutos y 5 segundos | **Duración:** 6 minutos y 18 segundos |
| **Imagen del entrevistado:**<br><img src="assets/Entrevistdo4.png" alt="Entrevistado 3 - Miguel Díaz" height="180" style="max-height: 180px; border-radius: 4px;" /> | |
| **Resumen de la entrevista:**<br>Miguel es ingeniero civil con aproximadamente 10 años de experiencia profesional, 3 de ellos en Venezuela y 7 en Perú. Actualmente se desempeña como ingeniero residente en Nexo Ingeniería, empresa enfocada en la construcción de edificios multifamiliares. A lo largo de su trayectoria ha participado en proyectos de remodelaciones residenciales, habilitaciones urbanas, viviendas unifamiliares y plantas industriales. Su labor está centrada en el control de obra, asegurando que los proyectos se ejecuten conforme a los planos aprobados y a los presupuestos establecidos.<br>Considera esencial regirse por el Reglamento Nacional de Edificaciones, que constituye la base normativa para cualquier proyecto, y trabajar en conjunto con arquitectos y desarrolladores inmobiliarios para alinear las tendencias del mercado con las necesidades de los usuarios. Está abierto a la integración de tecnologías inteligentes en departamentos, como sistemas de control de iluminación o seguridad, a los que asigna un alto valor en términos de atractivo comercial. Sin embargo, reconoce que su implementación incrementa inevitablemente los costos, por lo que estima su viabilidad en un nivel medio. Recomienda que los planos que integren estas tecnologías sigan la claridad de los planos eléctricos, de modo que sean comprensibles para diferentes especialistas en obra.<br>Entre las principales dificultades de su rol actual, destaca los procesos burocráticos que surgen cuando se presentan modificaciones en los proyectos, ya que implican nuevos trámites y aprobaciones municipales. A pesar de ello, sostiene que una buena planificación y programación de obra reduce los contratiempos y permite ejecutar proyectos con eficiencia.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows<br>**Dispositivo usado con más frecuencia:** Laptop<br>**Dispositivo móvil preferido:** Android<br>**Principal medio de contacto:** Email<br>**Herramientas utilizadas:** AutoCAD, Excel, Project, Mathcad.<br>**Ocupación actual:** Ingeniero residente en Nexo Ingeniería.<br>**Enfoque de diseño:** Cumplimiento del Reglamento Nacional de Edificaciones, alineación con tendencias del mercado y satisfacción del cliente final.<br>**Tecnologías inteligentes incorporadas:** Control de iluminación y seguridad.<br>**Motivaciones:** Garantizar calidad y rentabilidad en los proyectos, mantenerse abierto a la innovación tecnológica, mejorar procesos constructivos.<br>**Frustraciones:** Burocracia en modificaciones de obra y lentitud en aprobaciones municipales. | |
| | |
| **Entrevista 4:** Jorge Gomez | |
| **Enlace de la entrevista:** | [https://www.youtube.com/watch?v=3jIZBLw9X-8](https://www.youtube.com/watch?v=3jIZBLw9X-8) |
| **Sexo:** Masculino | **Edad:** 31 |
| **Instante en el que inicia:** 16 minutos y 5 segundos | **Duración:** 6 minutos y 18 segundos |
| **Imagen del entrevistado:**<br><img src="assets/Entrevistdo9.png" alt="Entrevistado 4 - Jorge Gómez" height="180" style="max-height: 180px; border-radius: 4px;" /> | |
| **Resumen de la entrevista:**<br>Jorge Gómez es arquitecto con 4 años de experiencia en proyectos residenciales. Actualmente apoya en el desarrollo, coordinación y revisión de diseños en una constructora. Su labor se centra en asegurar que los planos sean funcionales y ejecutables.<br>Considera vital el equilibrio entre estética, funcionalidad y presupuesto. Valora altamente la integración de domótica (iluminación, cerraduras, seguridad) por la modernidad que aportan, pero estima su viabilidad en un nivel medio (5/10) por altos costos y falta de especialistas. Recomienda dejar preparadas las bases de conectividad desde la fase inicial.<br>Entre sus principales frustraciones están los cambios de último momento y la información poco clara, además de la incompatibilidad entre sistemas domóticos. Afronta esto con orden y coordinación constante.<br><br>**Datos adicionales:**<br>**Navegador preferido:** No especificado<br>**Sistema operativo de preferencia:** No especificado<br>**Dispositivo usado con más frecuencia:** No especificado<br>**Dispositivo móvil preferido:** No especificado<br>**Principal medio de contacto:** No especificado<br>**Herramientas utilizadas:** AutoCAD, Revit, SketchUp.<br>**Ocupación actual:** Arquitecto de apoyo en constructora.<br>**Enfoque de diseño:** Funcionalidad, estética moderna y viabilidad presupuestaria.<br>**Tecnologías inteligentes incorporadas:** Cerraduras, iluminación y seguridad básicas.<br>**Motivaciones:** Ganar experiencia para liderar proyectos multifamiliares a futuro.<br>**Frustraciones:** Cambios de diseño tardíos e incompatibilidad técnica entre sistemas. | |
| | |
| **Entrevista 5:** Alex Moreno Yactayo | |
| **Enlace de la entrevista:** | [https://youtu.be/FRZoNssTUv0](https://youtu.be/FRZoNssTUv0) |
| **Sexo:** Masculino | **Edad:** 28 |
| **Instante en el que inicia:** 0 minutos y 0 segundos | **Duración:** 4 minutos y 17 segundos |
| **Imagen del entrevistado:**<br><img src="assets/EntrevistaAlex.png" alt="Entrevistado 5 - Alex Moreno Yactayo" height="180" style="max-height: 180px; border-radius: 4px;" /> | |
| **Resumen de la entrevista:**<br>Alex Moreno Yactayo tiene 28 años, es bachiller en Ingeniería Civil y trabaja como asistente de proyectos, participando principalmente en la coordinación de planos e instalaciones para edificios multifamiliares. Señala que la domótica todavía no se solicita en todos los proyectos, aunque ya existe interés por automatizar la iluminación de pasillos, estacionamientos y otras áreas comunes.<br>Para Alex, los principales obstáculos son el costo, la falta de planificación temprana y la incompatibilidad entre equipos de distintas marcas. Considera que la preinstalación de sensores y actuadores es viable si se contempla desde el inicio, dejando listas las conexiones, cajas y canalizaciones para evitar modificaciones costosas cuando la obra ya está terminada. También propone comenzar por las áreas comunes y permitir que cada departamento amplíe posteriormente una instalación básica.<br>Califica con 8 de 10 el valor comercial de incorporar IoT y una plataforma centralizada, especialmente para compradores jóvenes. Destaca que un panel web permitiría detectar fallas, ubicar dispositivos desconectados y facilitar el traspaso de la gestión a la administración del edificio. Asimismo, considera aceptable una suscripción si tiene un precio razonable, ofrece soporte y actualizaciones, y ayuda a reducir el consumo eléctrico y resolver problemas con rapidez.<br><br>**Datos adicionales inferidos (pendientes de validación con el entrevistado):**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows<br>**Dispositivo usado con más frecuencia:** Laptop<br>**Dispositivo móvil preferido:** Android<br>**Principal medio de contacto:** WhatsApp y correo electrónico<br>**Herramientas utilizadas:** AutoCAD, Revit, Microsoft Excel y Microsoft Project.<br>**Ocupación actual:** Asistente de proyectos.<br>**Enfoque de diseño:** Coordinación temprana de planos e instalaciones para evitar modificaciones y sobrecostos.<br>**Tecnologías inteligentes incorporadas:** Iluminación automática en pasillos, estacionamientos y áreas comunes; preinstalación de sensores y actuadores.<br>**Factores clave en diseño residencial:** Planificación desde el inicio, compatibilidad entre equipos, facilidad de uso y mantenimiento.<br>**Motivaciones:** Diferenciar los proyectos inmobiliarios, facilitar la supervisión de dispositivos y reducir el consumo eléctrico.<br>**Frustraciones:** Costos elevados, propuestas tardías, cambios en cableado y tableros, e incompatibilidad entre marcas. | |
| | |
| **Entrevista 6:** Mathias Rodríguez Salinas | |
| **Enlace de la entrevista:** | [https://lix.li/neaB](https://lix.li/neaB) |
| **Sexo:** Masculino | **Edad:** 42 |
| **Instante en el que inicia:** 0 minutos y 0 segundos | **Duración:** 5 minutos y 7 segundos |
| **Imagen del entrevistado:**<br><img src="assets/mathias-interview.png" alt="Entrevistado 6 - Mathias Rodríguez Salinas" height="180" style="max-height: 180px; border-radius: 4px;" /> | |
| **Resumen de la entrevista:**<br>Mathias Rodríguez Salinas es promotor inmobiliario y lidera proyectos multifamiliares, donde observa una demanda moderada (30% a 40%) de automatización: un estándar en áreas comunes para optimizar el consumo energético y un lujo solicitado en departamentos de nivel socioeconómico medio-alto y alto. Su principal obstáculo en obra son las marcas domóticas tradicionales, a las que considera cerradas, excesivamente costosas y difíciles de integrar, lo que suele generar "islas tecnológicas" (sistemas de accesos, ascensores e intercomunicadores que no se comunican entre sí) y errores por parte de la mano de obra eléctrica estándar.<br>Considera altamente viable (8/10) preinstalar infraestructura IoT desde la etapa de planos sin encarecer la obra más de un 2%, siempre y cuando se utilicen protocolos inalámbricos (como Zigbee o Wi-Fi) en lugar de cableados complejos. Ve la tecnología como un gran gancho comercial en la sala de ventas, aportando un atractivo de edificio "futurista". Además, un panel de control unificado le resultaría un alivio enorme al momento de entregar el edificio a la administración, ya que permite demostrar el funcionamiento de todo en tiempo real. Sin embargo, como promotor, su disposición a pagar una suscripción SaaS a largo plazo es nula, ya que su modelo de negocio es "construir, vender y salir". Considera que la Junta de Propietarios tendría una disposición moderada (5/10) a asumirlo, solo si la cuota es baja y demuestra ahorros reales en mantenimiento o luz.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows 11<br>**Dispositivo usado con más frecuencia:** Laptop y Tablet (para planos en obra)<br>**Dispositivo móvil preferido:** Android<br>**Principal medio de contacto:** Correo electrónico y llamadas telefónicas<br>**Personalidad tecnológica:** Visionario y pragmático; valora la tecnología como herramienta de ventas y eficiencia, pero huye de las complicaciones de instalación.<br>**Objetivos principales:** Aumentar el atractivo comercial de sus torres (ventas rápidas), facilitar la entrega de áreas comunes y evitar problemas de postventa.<br>**Tecnologías inteligentes de interés:** Plataformas centralizadas, automatización de bombas y luces en áreas comunes, protocolos inalámbricos (Zigbee/Wi-Fi) y paneles web de supervisión.<br>**Motivaciones:** Destacar frente a la competencia en la sala de ventas e implementar infraestructura inteligente con un impacto mínimo en el presupuesto (menor al 1% o 2%).<br>**Frustraciones:** Cotizaciones infladas de marcas tradicionales, dependencia de programadores especializados, falta de estandarización ("islas tecnológicas") y errores de cableado en obra.<br>**Preocupaciones:** Que los sistemas requieran manuales complejos para el usuario final y se conviertan en quejas o problemas de mantenimiento a futuro.<br>**Disposición de pago (SaaS):** Nula desde su rol de constructora (solo pagaría el primer año para traspasarlo); disposición moderada para las Juntas de Propietarios, condicionada a la demostración de ahorro económico real. | |

#### Segmento objetivo #2: Propietarios y Residentes de Apartamentos (B2C)

| Segmento objetivo #2: Dueños de apartamentos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| **Entrevista 1:** Angela Alvarado Ordóñez                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | |
| **Enlace de la entrevista:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [https://youtu.be/z5K2cowIBxg](https://youtu.be/z5K2cowIBxg) |
| **Sexo:** Femenino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | **Edad:** 35 |
| **Instante en el que inicia:** 27 minutos y 19 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | **Duración:** 5 minutos y 18 segundos |
| **Imagen del entrevistado:**<br><img src="assets/Entrevistdo6.png" alt="Entrevistado 1 - Ángela Alvarado" height="180" style="max-height: 180px; border-radius: 4px;" />                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | |
| **Resumen de la entrevista:**<br>Ángela Alvarado Ordóñez es abogada de 35 años y reside desde el 2022 en un departamento en Jesús María, adquirido en 2021 por su ubicación céntrica y el precio accesible. Sus principales objetivos al vivir en un departamento son la comodidad, la seguridad y el acceso a una vivienda que se ajuste a su presupuesto. Su rutina diaria transcurre principalmente fuera de casa debido a su trabajo, por lo que utiliza el departamento sobre todo para descansar, aunque dedica tiempo a actividades como correr por las mañanas. Entre sus frustraciones actuales menciona la falta de consideración de algunos vecinos en la limpieza y uso de áreas comunes, el olor a cigarro en pasillos, la saturación de ascensores en horas pico y la percepción de un control insuficiente por parte del personal de seguridad.<br>Aunque no utiliza dispositivos inteligentes en su hogar, muestra interés en soluciones de domótica orientadas a la seguridad, como cerraduras electrónicas y cámaras en pasillos, así como en el control remoto de luces y electrodomésticos para evitar olvidos. Considera que una aplicación que integre estas funciones sería de gran utilidad, especialmente en las noches y al salir de casa, y asegura que la disponibilidad de esta tecnología influiría significativamente en su decisión de compra de un nuevo departamento. No obstante, expresa preocupaciones en torno a la privacidad, el manejo de datos y los posibles sobrecostos en electricidad, aunque estaría dispuesta a pagar una suscripción mensual si incluye funciones avanzadas como reportes de energía y alertas personalizadas, siempre que su costo guarde relación con la utilidad percibida.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Brave<br>**Sistema operativo de preferencia:** Windows<br>**Dispositivo usado con más frecuencia:** Laptop<br>**Dispositivo móvil preferido:** Android<br>**Principal medio de contacto:** Email<br>**Personalidad tecnológica:** Cautelosa, interesada en tecnología práctica y segura.<br>**Objetivos principales:** Comodidad, seguridad y precio accesible.<br>**Tecnologías inteligentes de interés:** Cerraduras inteligentes, cámaras en pasillos, control remoto de luces y electrodomésticos.<br>**Motivaciones:** Garantizar seguridad, comodidad y evitar preocupaciones por olvidos o accesos no controlados.<br>**Frustraciones:** Vecinos poco considerados, olor a cigarro, saturación de ascensores, falta de control en seguridad y desorden en áreas comunes.<br>**Preocupaciones:** Privacidad de datos, control de imágenes y posibles sobrecostos de electricidad.<br>**Disposición de pago:** Sí, por suscripción mensual si aporta funciones útiles como reportes de energía y alertas. | |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | |
| **Entrevista 2:** Christy Karen Callata Alvarez                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | |
| **Enlace de la entrevista:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [https://youtu.be/aDa8HZ03PWQ](https://youtu.be/aDa8HZ03PWQ) |
| **Sexo:** Femenino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | **Edad:** 24 |
| **Instante en el que inicia:** 32 minutos y 37 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | **Duración:** 4 minutos y 56 segundos |
| **Imagen del entrevistado:**<br><img src="assets/Entrevistdo7.png" alt="Entrevistado 2 - Christy Callata" height="180" style="max-height: 180px; border-radius: 4px;" />                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | |
| **Resumen de la entrevista:**<br>Cristi Karen Callata Álvarez vive desde hace menos de un año en un departamento, elegido por el espacio y la cantidad de habitaciones necesarias para compartir. Valora principalmente la tranquilidad de la zona, lo que le permite descansar, aunque reconoce como principal frustración la distancia hacia su centro laboral, que le implica viajes de hasta una hora y veinte minutos. Su rutina diaria transcurre mayormente fuera de casa, por lo que busca que ciertas tareas domésticas se realicen de forma más automática y práctica, como el encendido y apagado de luces. Actualmente no cuenta con dispositivos inteligentes, pero muestra interés en incorporarlos para simplificar su día a día y mejorar la seguridad.<br>Callata considera útil una aplicación que permita controlar luces, cámaras y accesos de manera remota, ya que mejoraría su comodidad y seguridad dentro del hogar. Valora especialmente que la app sea fácil de usar, intuitiva y accesible. Puntúa con un 6 o 7 sobre 10 la influencia de estas funcionalidades en la decisión de adquirir un nuevo apartamento. Reconoce que la principal preocupación sería la seguridad de sus datos personales al usar una aplicación de este tipo. Además, estaría dispuesta a pagar una suscripción mensual por funciones avanzadas, siempre que estas ofrezcan mayores facilidades y control en su vivienda.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows<br>**Dispositivo usado con más frecuencia:** Laptop<br>**Dispositivo móvil preferido:** Android<br>**Principal medio de contacto:** Apps de colaboración<br>**Personalidad tecnológica:** Interesada, pero aún sin adopción.<br>**Objetivos principales:** Tranquilidad, comodidad y seguridad en el hogar.<br>**Tecnologías inteligentes de interés:** Automatización de luces, cámaras de seguridad conectadas al celular, control de accesos.<br>**Motivaciones:** Ahorrar tiempo, simplificar tareas y reforzar seguridad.<br>**Frustraciones:** Larga distancia al trabajo y tiempo de traslado.<br>**Preocupaciones:** Seguridad y privacidad de datos personales.<br>**Disposición de pago:** Sí, suscripción mensual por funciones avanzadas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | |
| **Entrevista 3:** Marco Antonio Peralta Gongora                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | |
| **Enlace de la entrevista:**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [https://youtu.be/aDa8HZ03PWQ](https://youtu.be/aDa8HZ03PWQ) |
| **Sexo:** Masculino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | **Edad:** 24 |
| **Instante en el que inicia:** 32 minutos y 37 segundos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | **Duración:** 4 minutos y 56 segundos |
| **Imagen del entrevistado:**<br><img src="assets/entrevista-marco.png" alt="Entrevistado 3 - Marco Peralta" height="180" style="max-height: 180px; border-radius: 4px;" />                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | |
| **Resumen de la entrevista:**<br>El entrevistado muestra una alta aceptación hacia una solución de automatización residencial integrada. Los principales beneficios percibidos son el control de iluminación, monitoreo de temperatura y humedad, automatizaciones y alertas. Sin embargo, existen preocupaciones relacionadas con la facilidad de uso, estabilidad de conexión y privacidad. Además, existe disposición a pagar una suscripción mensual, siempre que las funciones avanzadas representen un beneficio tangible.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Google Chrome<br>**Sistema operativo de preferencia:** Windows<br>**Dispositivo usado con más frecuencia:** Laptop<br>**Dispositivo móvil preferido:** Android<br>**Principal medio de contacto:** Aplicaciones de mensajería y colaboración.<br>**Personalidad tecnológica:** Interesado en la tecnología, pero todavía con poca adopción de dispositivos inteligentes.<br>**Objetivos principales:** Buscar mayor tranquilidad, comodidad y seguridad dentro del hogar.<br>**Tecnologías inteligentes de interés:** Automatización de luces, monitoreo de temperatura y humedad, cámaras de seguridad conectadas al celular y control de accesos.<br>**Motivaciones:** Ahorrar tiempo, simplificar tareas cotidianas, mejorar el confort y reforzar la seguridad del hogar.<br>**Frustraciones:** Configuraciones complicadas, necesidad de utilizar múltiples aplicaciones y problemas de conexión entre dispositivos.<br>**Preocupaciones:** Seguridad y privacidad de los datos personales, además de la estabilidad del servicio.<br>**Disposición de pago:** Sí. Estaría dispuesto a pagar una suscripción mensual por funciones avanzadas, siempre que el costo sea accesible y los beneficios sean claros.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | |
| **Entrevista 4:** Franco Bautista Salazar | |
| **Enlace de la entrevista:** | [https://lix.li/seV508](https://lix.li/seV508) |
| **Sexo:** Masculino | **Edad:** 29 |
| **Instante en el que inicia:** 0 minutos y 0 segundos | **Duración:** 4 minutos y 40 segundos |
| **Imagen del entrevistado:**<br><img src="assets/franco-interview.png" alt="Entrevistado 4 - Franco Bautista Salazar" height="180" style="max-height: 180px; border-radius: 4px;" /> | |
| **Resumen de la entrevista:**<br>Franco Bautista Salazar ya tiene experiencia integrando tecnología en su departamento, utilizando actualmente dispositivos como focos inteligentes, enchufes y cerraduras digitales. Valora principalmente la comodidad y el ahorro energético, mostrando un gran interés en la gestión del confort térmico para evitar la humedad y mantener el ambiente fresco sin esfuerzo. Su principal frustración actual radica en la fragmentación de su ecosistema: debe usar hasta tres aplicaciones distintas y sufre dolores de cabeza cuando los dispositivos se desconectan del Wi-Fi y deben ser reconfigurados.<br>Franco considera que una aplicación unificada sería sumamente valiosa, especialmente para configurar rutinas prácticas como "salir de casa" y para recibir alertas preventivas sobre fugas o humedad cuando no está. Califica con un 7 u 8 sobre 10 el atractivo de un departamento que ya incluya esta automatización, viéndolo como un indicador de modernidad y calidad que le ahorra gastos de instalación. Sus mayores preocupaciones son la estabilidad del servicio (no depender exclusivamente de internet para no quedarse a oscuras) y que la plataforma sea intuitiva para que toda su familia pueda usarla. Respecto a pagar una suscripción (SaaS), su disposición es baja; solo la aceptaría si el costo es simbólico y se demuestra un ahorro real en su recibo de luz.<br><br>**Datos adicionales:**<br>**Navegador preferido:** Safari<br>**Sistema operativo de preferencia:** iOS / macOS<br>**Dispositivo usado con más frecuencia:** Smartphone<br>**Dispositivo móvil preferido:** iPhone<br>**Principal medio de contacto:** WhatsApp<br>**Personalidad tecnológica:** Usuario proactivo y pragmático; adopta la tecnología pero le frustra la complejidad y la fragmentación.<br>**Objetivos principales:** Comodidad en el hogar, eficiencia energética y protección del departamento (prevención de moho y daños).<br>**Tecnologías inteligentes de interés:** Iluminación automatizada, cerraduras digitales, enchufes inteligentes y sensores de confort térmico/humedad.<br>**Motivaciones:** Ejecutar rutinas rápidas con un solo toque, ahorrar en la factura eléctrica y evitar instalaciones complejas post-mudanza.<br>**Frustraciones:** Lidiar con múltiples aplicaciones incompatibles, desconexiones de red repentinas y pérdida de configuraciones.<br>**Preocupaciones:** La dependencia total de la conexión a internet/servidores y la curva de aprendizaje de la app para el resto de su familia.<br>**Disposición de pago:** Muy condicionada; solo pagaría un monto mensual simbólico si la plataforma prueba generar ahorros tangibles de energía.                                          | |

### 2.2.3. Análisis de entrevistas.

| Segmento | Características | Objetivos comunes | Características subjetivas comunes |
|---|---|---|---|
| **Segmento #1: Ingenieros/Arquitectos** | **Sexo:** Masculino<br>**Edad:** 29-59 años<br>**Dispositivos:** Laptop/PC con software especializado<br>**Programas:** Revit, AutoCAD, software de diseño arquitectónico, coordinación de planos eléctricos<br>**Canales de información:** Actualización constante en tendencias tecnológicas, uso de correo de forma empresarial<br>**Canales de trabajo:** Colaboración con equipos multidisciplinarios, comunicación y liderazgo | • Garantizar eficiencia y calidad en el diseño y ejecución de proyectos residenciales.<br><br>• Incorporar tecnologías inteligentes y sostenibles en sus proyectos.<br><br>• Adaptarse a las tendencias del mercado y necesidades del usuario final.<br><br>• Mejorar procesos constructivos mediante software especializado.<br><br>• Escalar profesionalmente y/o fundar su propia empresa.<br><br>• Superar retos técnicos y de coordinación entre especialidades. | **Motivación:** Usar tecnología para optimizar proyectos, mostrarlos a más público, personalizar funciones y recibir retroalimentación.<br><br>**Frustración:** Falta de plataformas flexibles, baja exposición de diseños y trabas técnicas que dificultan la integración tecnológica. |
| **Segmento #2: Propietarios de apartamentos** | **Sexo:** Mixto<br>**Edad:** 24-63 años<br>**Dispositivos:** Laptop, smartphone, televisores, computadoras<br>**Programas:** Apps de noticias, organización y movilidad, no uso de software profesional<br>**Canales de información:** Redes sociales, aplicaciones móviles, medios digitales<br>**Marcas preferidas:** Samsung, HP, Lenovo, Android, Apple | • Priorizar comodidad y seguridad en el hogar.<br><br>• Optimizar el uso de tecnología para facilitar la vida diaria.<br><br>• Garantizar privacidad y control de datos personales.<br><br>• Disposición a pagar por suscripción si aporta valor.<br><br>• Mejorar la eficiencia y el control de dispositivos en el hogar. | **Motivación:** Mejorar la experiencia en el hogar con tecnología interactiva, gestionar dispositivos de forma personalizada, optimizar comodidad y seguridad, y recibir retroalimentación por el uso eficiente.<br><br>**Frustración:** Carencia de plataformas atractivas y flexibles, limitaciones en dispositivos inteligentes, dificultad de adaptación a cada hogar y barreras técnicas que complican su integración. |

## 2.3. Needfinding.
El Needfinding, como proceso de investigación, se enfocó en descubrir las necesidades y frustraciones subyacentes de dos segmentos de usuario clave: arquitectos e ingenieros civiles, representados por Miguel Veramendi; y dueños de apartamentos, representados por Carla Flores. A través de entrevistas cualitativas, se identificaron patrones comunes y específicos que revelaron la necesidad de herramientas tecnológicas para optimizar la colaboración y la gestión de proyectos en el sector de la construcción, así como la demanda de control intuitivo y centralizado en el hogar, priorizando la seguridad y la funcionalidad para el usuario final. Este entendimiento profundo de los deseos y expectativas de los usuarios fue fundamental para sentar las bases de una solución que responda genuinamente a sus necesidades y requisitos.

### 2.3.1. User Personas.
En esta sección se elaboraron perfiles representativos, denominados "User Personas", que compilan los rasgos esenciales de los usuarios a partir del estudio cualitativo de entrevistas. Este recurso permite transformar los datos de los individuos en arquetipos comprensibles que guían la estrategia de diseño, facilitando decisiones clave sobre funcionalidades y experiencia de usuario. Se crearon dos perfiles principales para el proyecto: uno correspondiente a arquitectos e ingenieros civiles, y otro vinculado a los dueños de apartamentos.

**Anexo Diagrama User Persona:** [https://goo.su/nQxos3](https://goo.su/nQxos3)

**Segmento 1: Arquitectos e Ingenieros Civiles**
<br>
<img src="assets/UserPersona_Segmento1.png" alt="User Persona 1 - Miguel Veramendi" width="650" style="max-width: 100%; height: auto; border-radius: 6px;" />

**Segmento 2: Dueños de apartamentos**
<br>
<img src="assets/UserPersona_Segmento2.png" alt="User Persona 2 - Carla Flores" width="650" style="max-width: 100%; height: auto; border-radius: 6px;" />

### 2.3.2. User Task Matrix.
A continuación se presenta el **User Task Matrix**, elaborado a partir del análisis cualitativo y empírico de las entrevistas realizadas a los dos segmentos clave para el proyecto. Este artefacto concentra las actividades que los usuarios realizan habitualmente para satisfacer sus metas y necesidades, independientemente de la existencia de una solución de software específica.

Para este estudio se consideran los dos segmentos objetivo del proyecto:
- **Segmento #1: Arquitectos e Ingenieros Civiles (B2B)**, representado por el User Persona **Miguel Veramendi**, enfocado en la viabilidad técnica, habitabilidad, coordinación de especialidades y eficiencia constructiva.
- **Segmento #2: Propietarios y Residentes de Apartamentos (B2C)**, representado por la User Persona **Carla Flores**, centrada en el confort térmico, la seguridad, la conveniencia doméstica y el ahorro familiar.

El cuadro presenta como columnas a cada User Persona, desglosando como subcolumnas la **Frecuencia** (*Frequency*) y la **Importancia** (*Importance*) que le otorgan a cada tarea. En las filas se ubican las tareas identificadas en el dominio de gestión energética, confort ambiental, automatización e instalaciones residenciales.

| N° | Tarea (Task) | Miguel Veramendi (Arquitectos / Ingenieros) | | Carla Flores (Dueños de apartamentos) | |
| :---: | :--- | :---: | :---: | :---: | :---: |
| | | **Frecuencia** | **Importancia** | **Frecuencia** | **Importancia** |
| 1 | Revisar el consumo eléctrico en recibos mensuales | Mensual | Alta | Mensual | Alta |
| 2 | Estimar el gasto energético de dispositivos y equipos instalados | Semanal | Alta | Ocasional | Media |
| 3 | Supervisar el encendido/apagado y uso responsable de luminarias y equipos | Diaria | Alta | Diaria | Alta |
| 4 | Monitorear el confort ambiental interior (temperatura, humedad y ventilación) | Semanal | Alta | Diaria | Alta |
| 5 | Verificar la seguridad física y el control de accesos a las instalaciones | Diaria | Alta | Diaria | Alta |
| 6 | Identificar picos de consumo y momentos de sobrecarga o mayor gasto | Semanal | Alta | Semanal | Alta |
| 7 | Coordinar con proveedores, especialistas o servicios de mantenimiento | Semanal | Alta | Ocasional | Media |
| 8 | Buscar alternativas de sostenibilidad, automatización y eficiencia energética | Semanal | Alta | Ocasional | Alta |
| 9 | Establecer metas de ahorro y presupuestos de consumo | Mensual | Alta | Continua / Siempre | Alta |
| 10 | Comparar el consumo y comportamiento entre diferentes periodos | Mensual | Alta | Ocasional | Media |
| 11 | Revisar gastos generales y balances económicos (de obra o del hogar) | Mensual | Alta | Mensual | Alta |
| 12 | Asistir a capacitaciones o talleres de actualización técnica y normativa | Trimestral | Media | Ocasional | Baja |

#### Análisis y Hallazgos del User Task Matrix

A partir de la matriz de tareas, se identifican las prioridades funcionales que orientan el desarrollo de la solución digital de **IoBuild**:

1. **Tareas con mayor frecuencia e importancia (Tareas Críticas):**
   - **Para Miguel Veramendi (B2B):** Las tareas más críticas corresponden a la *supervisión diaria del estado de luminarias y equipos* (Tarea 3), *verificación de seguridad y accesos* (Tarea 5), y el *seguimiento semanal de consumos y condiciones ambientales de los proyectos* (Tareas 2, 4 y 6). Para el segmento profesional, desatender estos puntos genera sobrecostos operativos, riesgo de penalidades eléctricas en faena o entregas con deficiencias de confort para los futuros compradores.
   - **Para Carla Flores (B2C):** Sus tareas prioritarias y más frecuentes son de periodicidad diaria: *apagar y regular luminarias y aparatos para evitar consumos fantasma* (Tarea 3), *asegurar los accesos del departamento al salir o dormir* (Tarea 5) y *verificar el confort térmico interior* (Tarea 4). Estas actividades se articulan con la *revisión mensual del recibo eléctrico* (Tarea 1) y el esfuerzo continuo por *mantener metas de ahorro* (Tarea 9).

2. **Principales coincidencias entre User Personas:**
   - **Preocupación central por el ahorro energético y la prevención de sobrecostos:** Ambos perfiles asignan importancia **Alta** a la revisión de recibos (Tarea 1), detección de picos de gasto (Tarea 6) y balance general de gastos (Tarea 11), evidenciando que el costo de la energía es un factor de fricción transversal.
   - **Control de iluminación y accesos como rutina obligada:** Tanto en la gestión de un edificio/obra como dentro de la vivienda, asegurar que no queden luces encendidas innecesariamente y constatar el cierre seguro de puertas son hábitos diarios esenciales.
   - **Interés creciente en la sostenibilidad y automatización:** Ambos segmentos buscan soluciones que optimicen el uso de recursos y aporten sostenibilidad (Tarea 8), siempre que no impliquen complejidades técnicas o costos desproporcionados.

3. **Principales diferencias entre lo realizado por los User Personas:**
   - **Perspectiva macro y técnica vs. micro y doméstica:** Miguel ejecuta tareas con rigor normativo, cálculo de cargas eléctricas y proyección a escala de edificio multifamiliar (coordinación con ingenierías y subcontratistas), mientras que Carla se concentra en la practicidad inmediata, la sencillez de uso y el bienestar familiar directo.
   - **Frecuencia operativa en estimación y mantenimiento:** Para Miguel, la *estimación de consumos* (Tarea 2) y la *coordinación con especialistas y servicios técnicos* (Tarea 7) son actividades semanales indispensables para su labor constructiva, mientras que para Carla son esporádicas, suscitadas únicamente ante fallas puntuales o la compra de nuevos electrodomésticos.
   - **Enfoque de fijación de metas:** Miguel establece metas de ahorro enmarcadas en cierres contables mensuales de obra, en tanto que Carla mantiene una actitud de vigilancia continua y constante sobre los hábitos de consumo en su vivienda.

### 2.3.3. User Journey Mapping.
Con el propósito de obtener una comprensión integral de las necesidades, comportamientos, emociones y principales dificultades de nuestros segmentos de usuario, elaboramos un User Journey Map empleando la herramienta especializada UXPressia. Este ejercicio facilitó la representación clara y empática del recorrido que cada perfil de usuario experimenta, desde la detección de una necesidad inicial hasta la interacción final con el producto o servicio, permitiéndonos identificar oportunidades de mejora y optimización en su experiencia.

La actividad se centró en dos segmentos clave:

1. **Miguel Veramendi:** Arquitecto e ingeniero civil que busca garantizar la viabilidad técnica de los proyectos mediante la integración de tecnologías para lograr diseños más innovadores.
2. **Carla Flores:** Dueña de apartamento que busca soluciones que le permitan automatizar sus rutinas y tener un control sencillo y centralizado sobre sus dispositivos.

Para ambos perfiles se diseñó un mapa que incluye:

- Las fases del proceso.
- Los objetivos del usuario en cada etapa.
- El detalle de acciones realizadas, canales utilizados y emociones experimentadas.
- Los problemas identificados y las oportunidades de mejora a lo largo del recorrido.

Mediante el uso de UXPressia se obtuvo una representación visual clara y dinámica que favorece la toma de decisiones con un enfoque centrado en el usuario. Este proceso no solo profundiza en la comprensión de sus motivaciones y retos, sino que también orienta el diseño de soluciones más pertinentes, empáticas y funcionales para cada perfil identificado.

**Segmento Objetivo #1: Arquitectos e Ingenieros Civiles**
<br>
<img src="assets/UserJourneyMap_Segmento1.png" alt="Imagen User Journey Mapping 1 - Segmento 1" width="700" style="max-width: 100%; height: auto; border-radius: 6px;" />

**Segmento Objetivo #2: Dueños de apartamentos**
<br>
<img src="assets/UserJourneyMap_Segmento2.png" alt="Imagen User Journey Mapping 2 - Segmento 2" width="700" style="max-width: 100%; height: auto; border-radius: 6px;" />

### 2.3.4. Empathy Mapping.
Como parte del enfoque de diseño centrado en el usuario, se desarrollaron mapas de empatía (*Empathy Maps*) para los dos segmentos principales identificados: Propietarios y Constructoras. Esta técnica, introducida por Dave Gray, permite plasmar de manera visual lo que los usuarios piensan, sienten, expresan y hacen en relación con el producto o servicio, facilitando una comprensión más profunda de su experiencia tanto emocional como cognitiva.

#### Objetivo del Empathy Mapping
El mapa de empatía tiene como finalidad ampliar la visión sobre el usuario más allá de sus conductas observables, explorando sus motivaciones, temores, frustraciones y aspiraciones implícitas. Se trata de una herramienta clave para identificar oportunidades de mejora desde un enfoque cualitativo, complementando los hallazgos obtenidos a través de entrevistas, observaciones y análisis de comportamientos.

<div style="page-break-before: always;"></div>

#### Segmento 1: Arquitectos e Ingenieros Civiles (Miguel Veramendi)

<img src="assets/EmpathyMap_Segmento1.png" width="75%" alt="Imagen Empathy Map Segmento 1" style="max-width: 100%; height: auto; border-radius: 6px;">

##### Desglose del Empathy Map 1 (Miguel Veramendi)
- **¿Con quién estamos empatizando?** Miguel Veramendi, 40 años, arquitecto peruano enfocado en integrar tecnología innovadora y sostenible en edificaciones, pero que enfrenta barreras de costo, complejidad técnica y regulaciones.
- **¿Qué necesita hacer?** Integrar tecnologías inteligentes y sostenibles en sus proyectos arquitectónicos; garantizar la viabilidad técnica y estructural; optimizar costos sin comprometer la calidad; y posicionar a su empresa como referente en innovación.
- **¿Qué ve?** Soluciones tecnológicas innovadoras en el mercado pero costosas y complejas; tendencias crecientes hacia energías renovables y automatización; competencia que busca diferenciarse; y clientes exigentes que valoran eficiencia, seguridad y modernidad.
- **¿Qué escucha?** De colegas: *"Estas tecnologías aún no están maduras o son muy caras"*; de clientes: *"Queremos proyectos innovadores, eficientes y sostenibles"*; de autoridades: *"Existen muchas trabas para implementar nuevas soluciones"*; y del mercado: *"La competencia también busca diferenciarse con innovación"*.
- **¿Qué dice?** *“Quiero ofrecer espacios innovadores, sostenibles y seguros”*, *“Las soluciones inteligentes existen, pero son muy costosas y difíciles de integrar”*, *“Necesitamos tecnologías accesibles y compatibles para realmente transformar el sector”*, y *“Lo más importante es asegurar la calidad estructural de mis proyectos”*.
- **¿Qué hace?** Investiga constantemente nuevas tecnologías y tendencias del mercado; evalúa proveedores y soluciones con rigurosidad técnica; realiza pruebas piloto para medir la viabilidad de integración; y colabora con ingenieros y clientes para validar propuestas.
- **¿Qué piensa y siente?**
  - *Piensa:* *“Quiero que mis proyectos sean innovadores, pero muchas tecnologías son demasiado costosas”*, *“Necesito asegurarme de que cada propuesta sea viable técnica y económicamente”*, *“La innovación es clave para diferenciarme, pero siento que aún hay demasiados obstáculos”*, y *“Si logro integrar soluciones inteligentes accesibles, mi trabajo tendrá un impacto real en el sector”*.
  - *Siente:* *“Me frustra que las regulaciones retrasen la implementación de soluciones sostenibles”*.
- **Pains (Dolores y Frustraciones):** Frustración por los altos costos y complejidad de las soluciones inteligentes; estrés por la falta de compatibilidad tecnológica entre sistemas; preocupación por trabas regulatorias que frenan la innovación; y carga constante de garantizar viabilidad técnica y optimización de costos.
- **Gains (Aspiraciones y Beneficios):** Satisfacción al lograr proyectos modernos, eficientes y sostenibles; orgullo de posicionar a su empresa como líder en innovación arquitectónica; confianza al ofrecer edificaciones seguras y funcionales; y tranquilidad al verificar que la inversión tecnológica aporta valor agregado y reconocimiento.

<div style="page-break-before: always;"></div>

#### Segmento 2: Propietarios y Residentes de Apartamentos (Carla Flores)

<img src="assets/EmpathyMap_Segmento2.png" width="75%" alt="Imagen Empathy Map Segmento 2" style="max-width: 100%; height: auto; border-radius: 6px;">

##### Desglose del Empathy Map 2 (Carla Flores)
- **¿Con quién estamos empatizando?** Carla Flores, 32 años, abogada peruana. Es sociable, activa en redes sociales y suele salir de noche con sus amigos. Siente una constante preocupación por la inseguridad en su ciudad, especialmente al movilizarse en horarios nocturnos.
- **¿Qué necesita hacer?** Acceder de manera sencilla a una plataforma tecnológica que simplifique sus tareas diarias; contar con información clara y útil para tomar decisiones en el momento adecuado; tener un sistema confiable que le genere tranquilidad y reduzca preocupaciones; y lograr que la tecnología se integre de forma natural en su rutina.
- **¿Qué ve?** Opciones tecnológicas en el mercado que suelen ser complejas o poco adaptadas a sus necesidades reales; personas que recurren a soluciones digitales para organizarse; recomendaciones de familiares y amigos sobre aplicaciones que prometen mejorar la calidad de vida; y una brecha notable entre lo que ofrecen las herramientas digitales y lo que realmente necesita en su día a día.
- **¿Qué escucha?** De amigos: *"Yo uso esta aplicación, te podría servir"*; de la familia: *"Ten cuidado con lo que descargas, algunas cosas no son seguras"*; de publicidad: *"La mejor herramienta para cambiar tu rutina"*; y de su comunidad: historias de éxito y fracaso con soluciones tecnológicas similares.
- **¿Qué dice?** *“Necesito algo fácil de usar, que no me complique más de lo que ya estoy”*, *“Si me ayuda a organizarme y me ahorra tiempo, vale la pena”*, *“No quiero perderme entre mil funciones innecesarias”*, y *“Lo más importante es que sea confiable y que realmente me sirva”*.
- **¿Qué hace?** Prueba aplicaciones o servicios digitales para evaluar su utilidad; pide referencias a conocidos antes de comprometerse con una nueva herramienta; abandona plataformas confusas que no cumplen sus expectativas; e integra gradualmente en su rutina aquellas soluciones que percibe como beneficiosas.
- **¿Qué piensa y siente?**
  - *Piensa:* *“Si esta solución es confiable, podría integrarla sin problema en mi rutina diaria”*, *“Me preocupa que una herramienta nueva sea complicada y me haga perder tiempo en lugar de ayudarme”*, *“Quiero sentir que estoy en control de mis actividades y no depender de procesos confusos”*, y *“Sería un alivio encontrar algo que realmente me simplifique la vida y me haga sentir más organizada”*.
  - *Siente:* *“Me frustra cuando una aplicación promete mucho y no cumple con lo que necesito”*.
- **Pains (Dolores y Frustraciones):** Estrés al sentir que la tecnología puede complicar más que ayudar; inseguridad frente a plataformas poco claras o con baja confiabilidad; y frustración cuando una herramienta no cumple con lo prometido.
- **Gains (Aspiraciones y Beneficios):** Tranquilidad al encontrar una solución ajustada a sus necesidades; confianza al integrar una herramienta digital estable en su rutina diaria; satisfacción por ahorrar tiempo y sentir mayor control de sus actividades; y motivación para recomendar la herramienta con su círculo cercano.

<div style="page-break-before: always;"></div>

## 2.4. Big Picture EventStorming.

Para el desarrollo del Big Picture EventStorming, se utilizó la herramienta colaborativa Miro, la cual facilitó la exploración visual, dinámica y consensuada de los diferentes elementos y flujos del negocio de extremo a extremo. A continuación, se presentan los componentes identificados durante las sesiones de modelado del dominio:

Primero, se definieron las leyendas y códigos visuales para los diferentes artefactos utilizados en el modelado del EventStorming:

![Big-Picture-EventStorming-Leyenda](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-Leyenda.png)
<br>

- **Domain Events (Naranja):** Representa un hecho significativo del negocio que ya ocurrió en el pasado y es inmutable.<br>
- **Hotspot Question Improvement (Rojo/Púrpura):** Señala un punto de incertidumbre, duda o posible conflicto en el proceso para visibilizar preguntas que requieren análisis y mejora continua.<br>
- **Definition (Amarillo claro):** Aporta una explicación breve y precisa de un concepto clave dentro del dominio del negocio.<br>
- **Actor (Amarillo pequeño):** Representa a la persona, rol u organización que interactúa con el sistema o desencadena acciones directas.<br>
- **Command (Azul):** Expresa la intención o petición explícita de realizar una acción dentro del sistema promovida por un actor o política.<br>
- **Comment (Gris/Blanco):** Sirve para registrar notas, aclaraciones u observaciones de contexto que enriquecen la discusión del equipo sin alterar el flujo principal.<br>
- **Policy (Lila/Gris claro):** Define una regla o condición de negocio que conecta reactivamente un evento previo con un nuevo comando consecuente.<br>
- **External System (Rosa/Fucsia):** Representa plataformas, APIs o servicios externos con los que el sistema interactúa (ej. pasarelas de pago o brokers MQTT).<br>

El proceso colaborativo de EventStorming permitió mapear el flujo de valor integral del negocio, partiendo de la exploración temporal de los domain events, la identificación de los actores involucrados, la formulación de comandos disparadores y la definición de políticas operativas. A partir de ello, se estructuraron los 5 flujos clave del landscape de IoBuild:

<br>

**Big Picture EventStorming 1: Onboarding de Constructora y Asignación de Unidades**<br>
Modela la incorporación de las empresas inmobiliarias y constructoras en la plataforma. Se identifican domain events clave como la creación de la cuenta corporativa y la parametrización de edificios y departamentos. El actor principal (la constructora) inicia sesión, accede al módulo de gestión y registra la infraestructura. El sistema valida la disponibilidad física de las unidades habitacionales y emite notificaciones operativas en caso de duplicidad o conflicto.
<br>
![Big-Picture-EventStorming-1](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-1.png)
<br><br>

**Big Picture EventStorming 2: Suscripción y Contratación de Planes SaaS**<br>
Representa el ciclo comercial y financiero. Los domain events abarcan la selección de planes empresariales, la emisión de órdenes de pago, la confirmación o rechazo transaccional y la posterior activación del servicio. La constructora evalúa el catálogo de planes según el volumen de unidades gestionadas; el sistema se conecta con la pasarela de pagos externa para verificar la transacción y actualiza automáticamente los límites operativos del cliente.
<br>
![Big-Picture-EventStorming-2](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-2.png)
<br><br>

**Big Picture EventStorming 3: Planificación e Integración de Proyectos Inteligentes**<br>
Describe la configuración técnica de nuevas edificaciones residenciales. El actor principal (equipo técnico de la constructora) recibe los requisitos y especificaciones del proyecto, registra la obra en IoBuild y carga la distribución espacial junto a las especificaciones técnicas de zonificación. El sistema asiste en la asignación de módulos IoT (sensores ambientales y relés de control) y facilita la validación técnica previa a la entrega final y transferencia de control al residente o junta de propietarios.
<br>
![Big-Picture-EventStorming-3](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-3.png)
<br><br>

**Big Picture EventStorming 4: Telemetría, Monitoreo y Automatización en Operación**<br>
Modela la fase operativa del sistema en los departamentos y áreas comunes. Los domain events incluyen la recepción periódica de telemetría ambiental, el registro de métricas de consumo y el disparo de alertas por superación de umbrales. El residente o supervisor consulta el estado de las instalaciones, ajusta perfiles de confort y recibe notificaciones inmediatas ante anomalías o consumos atípicos de energía.
<br>
![Big-Picture-EventStorming-4](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-4.png)
<br><br>

**Big Picture EventStorming 5: Emparejamiento y Provisión de Dispositivos IoT**<br>
Detalla el aprovisionamiento e inicialización de hardware en las propiedades. Los domain events cubren la detección de hardware, la verificación de credenciales de red, la confirmación de enlace exitoso o la notificación de error en la sincronización. El residente o técnico instalador vincula nuevos sensores o actuadores guiado por la plataforma, que valida la compatibilidad e incorpora el dispositivo al registro activo.
<br>
![Big-Picture-EventStorming-5](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Big-Picture-EventStorming-5.png)

---

## 2.5. Ubiquitous Language.

Con el objetivo de garantizar una comunicación precisa, libre de ambigüedades y compartida entre el equipo de desarrollo, los especialistas del sector inmobiliario y los usuarios finales, se definió el siguiente lenguaje ubicuo correspondiente al dominio de edificaciones inteligentes y gestión IoT:

| Ubiquitous Term | Definición del Dominio Funcional |
| :--- | :--- |
| **Client** *(Cliente Inmobiliario)* | Empresa constructora, promotora o inmobiliaria que contrata la suscripción de IoBuild para equipar y gestionar proyectos residenciales con valor domótico. |
| **Property Manager** *(Administrador de Edificación)* | Rol responsable de supervisar la operatividad general, consumo energético de áreas comunes y mantenimiento de una o varias edificaciones. |
| **Resident** *(Residente / Propietario)* | Usuario que habita una unidad residencial y hace uso directo de las funciones de confort, visualización de consumo y automatización en su espacio. |
| **Platform Operator** *(Operador de Plataforma)* | Responsable interno del servicio SaaS que administra la disponibilidad global, planes comerciales y catálogo de dispositivos certificados. |
| **Property / Building** *(Propiedad / Edificio)* | Estructura inmobiliaria colectiva que agrupa un conjunto de unidades habitacionales y áreas compartidas bajo una misma gestión técnica. |
| **Unit** *(Unidad Habitacional / Departamento)* | Espacio habitacional individualizado dentro de un edificio al cual se asocian residentes y una red específica de dispositivos IoT. |
| **Device** *(Dispositivo IoT)* | Nodo físico compuesto por microcontrolador, sensores o actuadores que interactúa con el entorno físico y transmite datos hacia la plataforma. |
| **Environmental Sensor** *(Sensor Ambiental)* | Componente de hardware destinado a medir variables de habitabilidad física como temperatura ambiente, humedad relativa o presencia. |
| **Actuator** *(Actuador / Conmutador)* | Dispositivo electrónico (ej. relé, servomotor) capaz de alterar el estado de un circuito físico para encender iluminación o controlar accesos. |
| **Device Profile** *(Perfil de Dispositivo)* | Especificación y plantilla estandarizada de configuración que define los parámetros de telemetría y rangos operativos para un tipo de hardware. |
| **Provisioning** *(Aprovisionamiento / Emparejamiento)* | Secuencia técnica mediante la cual un nuevo nodo IoT es registrado, autenticado y vinculado de manera segura a una unidad específica. |
| **Telemetry** *(Telemetría)* | Flujo de lecturas continuas de variables físicas y métricas de consumo energético emitidas por los sensores hacia el sistema de procesamiento. |
| **Device State** *(Estado de Dispositivo)* | Condición operativa reportada por el nodo físico (ej. *En línea*, *Fuera de línea*, *Alerta*, *Batería crítica*). |
| **Control Action** *(Acción de Control)* | Instrucción emitida hacia un actuador para inducir un cambio físico inmediato (ej. corte preventivo, apertura o encendido). |
| **Environmental Profile / Scene** *(Perfil Ambiental / Escena)* | Conjunto de parámetros de confort y automatización predefinidos que ajustan simultáneamente el comportamiento de múltiples actuadores y sensores. |
| **Threshold Alert** *(Alerta de Umbral)* | Notificación automática desencadenada cuando una variable física o de consumo supera los rangos máximos o mínimos establecidos por la regla de negocio. |
| **Monitoring Console** *(Consola de Monitoreo)* | Espacio centralizado de supervisión donde se presenta la síntesis del estado operativo de los dispositivos y el histórico de métricas recopiladas. |
| **Subscription** *(Suscripción SaaS)* | Modalidad contractual que regula el nivel de servicio, cantidad de edificios admitidos y cupos de dispositivos soportados en la plataforma. |
| **Billing Cycle** *(Ciclo de Facturación)* | Periodo temporal recurrente bajo el cual se calculan los costos y cargos por el servicio de gestión y soporte contratado. |

---

<div style="page-break-before: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. User Stories.

En esta sección se detallan los requisitos del sistema especificados mediante un conjunto integrado de Epics, User Stories y Technical Stories. Cada historia de usuario sigue la estructura estándar («Como... deseo... para...») y cuenta con Criterios de Aceptación comprobables definidos bajo la sintaxis Gherkin (Dado... Cuando... Entonces...). Asimismo, se incorporan Technical Stories orientadas a la interacción técnica con los servicios y RESTful APIs de la plataforma IoBuild con el rol base *Developer*.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| EP01 | Landing page informativa | Como visitante del sitio, quiero tener acceso a una plataforma web, para conocer los servicios que brinda la aplicación. | | |
| EP02 | Gestión de cuentas y acceso | Como ingeniero quiero crear una cuenta para acceder a las funcionalidades de la aplicación | | |
| EP03 | Internacionalización de la plataforma | Como arquitecto, quiero que la aplicación esté disponible en más de un idioma para seleccionar el idioma de mi preferencia. | | |
| EP04 | Personalización de espacios inteligentes | Como propietario, quiero personalizar la configuración de mi vivienda y/o edificio, para adaptar el espacio a mis necesidades. | | |
| EP05 | Gestión de notificaciones | Como propietario, quiero recibir notificaciones relevantes sobre mis proyectos o configuraciones, para mantenerme informado en tiempo real. | | |
| EP06 | Gestión de perfil de usuario | Como usuario propietario, quiero actualizar la información de mi perfil, para personalizar mi experiencia en la plataforma. | | |
| EP07 | Dashboard de personalización del espacio | Como propietario, quiero acceder a un dashboard, para supervisar los dispositivos de mi departamento. | | |
| EP08 | Gestión de clientes y entregables | Como ingeniero, quiero gestionar la información de mis clientes, para mantener un control organizado de los proyectos. | | |
| EP09 | Gestión de proyectos inteligentes | Como arquitecto, quiero gestionar proyectos de construcción en la plataforma, para integrar funcionalidades inteligentes desde la planificación. | | |
| EP10 | Seguridad y Privacidad de Datos | Como desarrollador, quiero implementar protocolos de seguridad y privacidad de datos, para proteger la información de los usuarios. | | |
| EP11 | Gestión de dispositivos inteligentes | Como Desarrollador, quiero implementar un sistema de gestión de dispositivos inteligentes, para que permita registrar, modificar y asignar dispositivos disponibles dentro de un espacio. | | |
| EP12 | Gestión de energía en tiempo real | Como Desarrollador, quiero implementar un sistema de monitoreo energético, para que los usuarios puedan consultar el uso de energía en sus espacios. | | |
| EP13 | Gestión de usuarios | Como desarrollador, quiero gestionar a los usuarios de la plataforma, para asegurar un control adecuado de accesos, roles y permisos | | |
| US01 | Sección "Sobre Nosotros" | Como visitante del sitio, quiero conocer la historia y valores de la aplicación, para tener mayor conexión y confianza con la empresa. | **Escenario 1:**<br>Dado que el visitante está explorando la landing page,<br> Cuando llega a la sección “Sobre Nosotros”, <br>Entonces debe visualizar una descripción breve de la historia de IoBuild, su equipo y valores, acompañada de imágenes. | EP01 |
| US02 | Sección testimonios del cliente | Como visitante del sitio, quiero consultar testimonios de otros clientes, para generar confianza en la propuesta de valor de la startup | **Escenario 1:**<br>Dado que el visitante accede al sitio web<br>Cuando consulta la sección de testimonios<br>Entonces visualiza opiniones de clientes<br>Y percibe la experiencia de otros usuarios.<br><br>**Escenario 2:**<br>Dado que existen varios testimonios disponibles<br>Cuando el visitante desea revisar más testimonios<br>Entonces el sistema le muestra todos los testimonios | EP01 |
| US03 | Acceso a información de contacto | Como visitante del sitio, quiero acceder fácilmente a la información de contacto de IoBuild, para comunicarme en caso de dudas | **Escenario 1:**<br>Dado que el visitante accede a la landing page<br>Cuando consulta la sección de contacto<br>Entonces visualiza información clara como correo y teléfono <br>Y puede identificar rápidamente los medios de comunicación disponibles. | EP01 |
| US04 | Visualización de servicios principales | Como visitante del sitio, quiero conocer los servicios que ofrece IoBuild, para entender su propuesta de valor. | **Escenario 1:**<br>Dado que el visitante accede a la landing page<br>Cuando navega a la sección de servicios<br>Entonces visualiza una lista de los servicios principales<br><br>**Escenario 2:**<br>Dado que el visitante accede a la landing page <br>Cuando quiere conocer más sobre un servicio de su interés<br>Entonces selecciona la opción de “ver más”<br>Y se muestra un texto más completo sobre el servicio seleccionado | EP01 |
| US05 | Opción de registro | Como visitante del sitio, quiero registrarme en la aplicación, para tener acceso a las funcionalidades de la aplicación | **Escenario 1:**<br>Dado que el visitante accede a la landing page<br>Cuando se dirige a la parte superior de la página<br>Y selecciona la opción registrarse<br>Entonces la aplicación lo redirige al formulario de registro | EP02 |
| US06 | Preguntas frecuentes | Como visitante del sitio, quiero consultar una sección de preguntas frecuentes, para resolver dudas comunes sin necesidad de contactar a la startup | **Escenario 1:**<br>Dado que el visitante accede a la landing page<br>Cuando entra a la sección de preguntas frecuentes<br>Entonces puede desplegar las respuestas a cada pregunta común<br>Y encuentra información organizada y clara.<br><br>**Escenario 2:**<br>Dado que el visitante accede a la sección de preguntas frecuentes<br>Cuando revisa la lista de preguntas disponibles<br>Entonces el sistema debe mostrar múltiples preguntas frecuentes <br>Y cada pregunta debe poder expandirse para visualizar su respuesta correspondiente. | EP01 |
| US07 | Internacionalización de la landing page | Como visitante del sitio, quiero poder encontrar más de un idioma disponible, para poder elegir el idioma de mi preferencia. | **Escenario 1:**<br>Dado que el visitante accede a la landing page<br>Cuando selecciona un idioma distinto<br>Entonces todo el contenido de la landing page debe mostrarse automáticamente en el idioma seleccionado.<br><br>**Escenario 2:**<br>Dado que el visitante seleccionó un idioma previamente<br>Cuando vuelve a ingresar al sitio<br>Entonces la landing page debe mostrarse en el último idioma elegido, sin necesidad de volver a configurarlo. | EP03 |
| US08 | Dashboard Personalizado | Como usuario, quiero tener un dashboard personalizado, para visualizar la información relevante de manera rápida y eficiente. | **Escenario 1:**<br>Dado que el usuario accede al sistema,<br>Cuando el dashboard se carga,<br>Entonces verá una interfaz con widgets configurables (gráficos, estadísticas, alertas) según sus preferencias.<br><br>**Escenario 2:**<br>Dado que el usuario tiene acceso a múltiples secciones,<br>Cuando elige personalizar su dashboard,<br>Entonces podrá agregar, eliminar o reorganizar los widgets.<br><br>**Escenario 3:**<br>Dado que el usuario guarda los cambios en su dashboard,<br>Cuando vuelva a acceder,<br>Entonces verá el dashboard con las configuraciones guardadas. | EP07 |
| US09 | Acceso a Proyectos Activos | Como ingeniero, quiero tener acceso a los proyectos que se encuentran activos, para poder realizar un seguimiento de su progreso y gestionar los recursos necesarios. | **Escenario 1:**<br>Dado que el ingeniero accede al sistema,<br>Cuando consulta la lista de proyectos,<br>Entonces verá solo los proyectos con estado "activo".<br><br>**Escenario 2:**<br>Dado que el ingeniero tiene acceso a los proyectos activos,<br>Cuando selecciona un proyecto,<br>Entonces puede acceder a detalles como el progreso, recursos y métricas del proyecto.<br><br>**Escenario 3:**<br>Dado que el ingeniero está visualizando proyectos activos,<br>Cuando hay cambios en el estado de algún proyecto (e.g., transición a "completado"),<br>Entonces la lista se actualiza automáticamente. | EP09 |
| US10 | Acceso a Dispositivos Conectados | Como usuario, quiero tener acceso a los dispositivos conectados, para poder monitorear su estado y uso. | **Escenario 1:**<br>Dado que el usuario accede a la aplicación,<br>Cuando consulta los dispositivos conectados,<br>Entonces verá una lista de dispositivos con su estado actual (activo, inactivo, etc.).<br><br>**Escenario 2:**<br>Dado que el usuario tiene acceso a los dispositivos,<br>Cuando selecciona un dispositivo,<br>Entonces puede ver información detallada sobre su configuración, tipo y uso.<br><br>**Escenario 3:**<br>Dado que hay dispositivos conectados,<br>Cuando un dispositivo cambia su estado,<br>Entonces la interfaz se actualiza automáticamente. | EP04 |
| US11 | Acceso a la Capacidad de Ocupación de Cada Proyecto | Como ingeniero, quiero tener acceso a la capacidad de ocupación de cada proyecto, para poder analizar el uso de los recursos y planificar de manera eficiente. | **Escenario 1:**<br>Dado que el ingeniero accede al sistema,<br>Cuando consulta la información de ocupación,<br>Entonces verá la capacidad de ocupación de cada proyecto, expresada como porcentaje o número de espacios ocupados.<br><br>**Escenario 2:**<br>Dado que el ingeniero tiene acceso a los proyectos,<br>Cuando selecciona un proyecto,<br>Entonces puede ver su capacidad de ocupación histórica y proyectada.<br><br>**Escenario 3:**<br>Dado que un proyecto tiene capacidad de ocupación variable,<br>Cuando cambia su ocupación,<br>Entonces la información se actualiza en tiempo real. | EP09 |
| US12 | Gráfico de Consumo de Energía por Hora | Como ingeniero, quiero ver un gráfico sobre la energía que se consume por hora, para poder evaluar el rendimiento energético de los proyectos en tiempo real. | **Escenario 1:**<br>Dado que el ingeniero accede a la sección de consumo energético,<br>Cuando visualiza los datos,<br>Entonces verá un gráfico que muestra el consumo de energía de cada proyecto por hora.<br><br>**Escenario 2:**<br>Dado que el gráfico muestra el consumo energético,<br>Cuando se actualizan los datos de consumo,<br>Entonces el gráfico se refresca en tiempo real.<br><br>**Escenario 3:**<br>Dado que el ingeniero necesita analizar tendencias,<br>Cuando selecciona un rango de tiempo específico,<br>Entonces el gráfico ajusta el intervalo de horas. | EP12 |
| US13 | Gráfico de Registro de Ocupación | Como ingeniero, quiero ver un gráfico sobre el registro de ocupación, para poder analizar la evolución de la ocupación a lo largo del tiempo. | **Escenario 1:**<br>Dado que el ingeniero accede a la sección de ocupación,<br>Cuando consulta los datos históricos,<br>Entonces verá un gráfico que representa la evolución de la ocupación de los proyectos a lo largo del tiempo.<br><br>**Escenario 2:**<br>Dado que el gráfico de ocupación está disponible,<br>Cuando el ingeniero selecciona diferentes proyectos,<br>Entonces puede visualizar la ocupación de cada uno por separado.<br><br>**Escenario 3:**<br>Dado que los datos de ocupación se actualizan con frecuencia,<br>Cuando se produce un cambio en la ocupación,<br>Entonces el gráfico se actualiza automáticamente. | EP09 |
| US14 | Resumen de Proyecto | Como ingeniero, quiero ver un resumen sobre cada proyecto, para saber si está activo, su ubicación y cuántos departamentos están ocupados. | **Escenario 1:**<br>Dado que el ingeniero accede a los proyectos,<br>Cuando selecciona un proyecto,<br>Entonces verá un resumen con la información clave: estado (activo/inactivo), ubicación y número de departamentos ocupados.<br><br>**Escenario 2:**<br>Dado que el ingeniero puede ver el resumen,<br>Cuando se actualiza algún dato clave del proyecto (e.g., cambio de ubicación o estado),<br>Entonces el resumen se actualiza automáticamente.<br><br>**Escenario 3:**<br>Dado que el ingeniero tiene acceso a múltiples proyectos,<br>Cuando consulta la lista,<br>Entonces puede ver una visión general de todos los proyectos activos con esta información resumida. | EP09 |
| US15 | Visualización de Dispositivos y Distribución por Tipo | Como ingeniero, quiero ver cuáles son los dispositivos y cómo están distribuidos por tipo, para realizar un análisis más detallado de los recursos disponibles. | **Escenario 1:**<br>Dado que el ingeniero accede a la sección de dispositivos,<br>Cuando consulta los dispositivos,<br>Entonces verá una lista detallada de todos los dispositivos conectados, clasificados por tipo.<br><br>**Escenario 2:**<br>Dado que los dispositivos están clasificados por tipo,<br>Cuando selecciona un tipo específico,<br>Entonces verá solo los dispositivos de ese tipo.<br><br>**Escenario 3:**<br>Dado que el ingeniero puede ver la distribución de dispositivos,<br>Cuando se agrega o elimina un dispositivo,<br>Entonces la distribución se actualiza automáticamente. | EP11 |
| US16 | Acceso a Perfil del Usuario | Como usuario, quiero tener acceso a mi perfil, para ver datos como mi nombre, email, número de teléfono y mi dirección. | **Escenario 1:**<br>Dado que el usuario accede a la aplicación,<br>Cuando consulta su perfil,<br>Entonces verá una página o sección con la siguiente información: nombre, email, número de teléfono y dirección.<br><br>**Escenario 2:**<br>Dado que el usuario está visualizando su perfil,<br>Cuando la información de contacto está desactualizada,<br>Entonces puede identificar qué datos están desactualizados (si es el caso).<br><br>**Escenario 3:**<br>Dado que el usuario accede a su perfil,<br>Cuando realiza un cambio en la información personal,<br>Entonces la información se guarda correctamente y se actualiza en la base de datos. | EP06 |
| US17 | Edición de Información del Perfil | Como usuario, quiero poder editar alguna parte de mi información, como mi email, número de teléfono o dirección, para mantener mis datos actualizados. | **Escenario 1:**<br>Dado que el usuario accede a su perfil,<br>Cuando selecciona la opción para editar su información,<br>Entonces podrá modificar los siguientes campos: email, número de teléfono y dirección.<br><br>**Escenario 2:**<br>Dado que el usuario está editando su información,<br>Cuando hace un cambio en uno de estos campos,<br>Entonces la aplicación valida que el formato del email y número de teléfono sea correcto antes de guardar los cambios.<br><br>**Escenario 3:**<br>Dado que el usuario ha editado la información,<br>Cuando guarda los cambios,<br>Entonces recibirá una confirmación de que los datos fueron actualizados exitosamente.<br><br>**Escenario 4:**<br>Dado que el usuario intenta editar un campo,<br>Cuando el campo es obligatorio (por ejemplo, dirección),<br>Entonces se mostrará un mensaje de error si el campo está vacío. | EP06 |
| US18 | Ver Imagen que Representa al Usuario | Como usuario, quiero poder ver una imagen que me represente, para tener una experiencia más personalizada. | **Escenario 1:**<br>Dado que el usuario accede a su perfil,<br>Cuando visualiza la información personal,<br>Entonces verá una imagen o avatar asociado a su cuenta (si está disponible).<br><br>**Escenario 2:**<br>Dado que el usuario desea cambiar su imagen,<br>Cuando selecciona la opción para editar la foto de perfil,<br>Entonces podrá cargar una nueva imagen desde su dispositivo.<br><br>**Escenario 3:**<br>Dado que el usuario cambia su imagen de perfil,<br>Cuando la nueva imagen se guarda,<br>Entonces se actualiza correctamente en el perfil y se refleja en todas las pantallas donde se visualiza el avatar del usuario.<br><br>**Escenario 4:**<br>Dado que el usuario no ha subido una imagen de perfil,<br>Cuando no se encuentra una imagen,<br>Entonces se muestra una imagen predeterminada (por ejemplo, un avatar de usuario predeterminado). | EP06 |
| US19 | Ver el Rol de la Cuenta | Como usuario, quiero poder ver el rol de mi cuenta, para entender qué permisos tengo dentro de la aplicación. | **Escenario 1:**<br>Dado que el usuario accede a su perfil,<br>Cuando consulta los detalles de su cuenta,<br>Entonces verá un campo que indica su rol (por ejemplo: "Administrador", "Usuario", "Invitado").<br><br>**Escenario 2:**<br>Dado que el usuario tiene un rol específico,<br>Cuando el sistema identifica un cambio en el rol,<br>Entonces actualizará la información visible en el perfil en tiempo real.<br><br>**Escenario 3:**<br>Dado que el usuario ve su rol,<br>Cuando accede a secciones de la aplicación,<br>Entonces verá solo las opciones que correspondan a su nivel de acceso (por ejemplo, un "Administrador" verá opciones de configuración, mientras que un "Usuario" verá solo las opciones básicas).<br><br>**Escenario 4:**<br>Dado que el rol puede cambiar,<br>Cuando un administrador o un usuario con permisos lo actualiza,<br>Entonces la modificación se refleja inmediatamente en el perfil del usuario. | EP06 |
| US20 | Ver lista de proyectos | Como ingeniero, quiero ver una lista de todos mis proyectos para poder conocer el estado y detalles de cada uno. | **Escenario 1:**<br>Dado que existen proyectos registrados para el constructor,<br>Cuando el constructor accede a la vista de “Proyectos”,<br>Entonces el sistema muestra una lista con todos los proyectos incluyendo imagen, nombre, estado, tasa de ocupación y fecha de creación.<br><br>**Escenario 2:**<br>Dado que no existen proyectos registrados para el constructor,<br>Cuando el constructor accede a la vista de “Proyectos”,<br>Entonces el sistema muestra un mensaje indicando que no hay proyectos disponibles. | EP09 |
| US21 | Agregar un nuevo proyecto | Como arquitecto, quiero agregar un nuevo proyecto para poder registrar nuevos desarrollos inmobiliarios. | **Escenario 1:**<br>Dado que el constructor proporciona datos válidos (nombre, imagen, estado, unidades totales, fecha de creación, etc.),<br>Cuando el constructor envía la solicitud para agregar el proyecto,<br>Entonces el sistema crea el proyecto y lo muestra en la lista de proyectos.<br><br>**Escenario 2:**<br>Dado que el constructor proporciona datos inválidos (por ejemplo, nombre vacío o formato incorrecto),<br>Cuando el constructor envía la solicitud para agregar el proyecto,<br>Entonces el sistema rechaza la creación y muestra un mensaje de error. | EP09 |
| US22 | Ver detalles de un proyecto | Como arquitecto, quiero ver los detalles de un proyecto específico para poder revisar su información completa. | **Escenario 1:**<br>Dado que el proyecto existe en el sistema,<br>Cuando el constructor selecciona la opción “Ver Detalles” de ese proyecto,<br>Entonces el sistema muestra la información completa del proyecto seleccionado.<br><br>**Escenario 2:**<br>Dado que el proyecto no existe en el sistema,<br>Cuando el constructor intenta acceder a los detalles del proyecto,<br>Entonces el sistema muestra un mensaje de error indicando que el proyecto no se encuentra disponible. | EP09 |
| US23 | Ver Lista de Clientes | Como Arquitecto, quiero ver una lista de todos los clientes para poder gestionar sus proyectos asociados y el estado de su cuenta. | **Escenario 1:**<br>Dado que hay clientes registrados en el sistema,<br>Cuando el Arquitecto solicita la lista de clientes,<br>Entonces el sistema presenta el listado de clientes con su Nombre Completo, Proyecto Asociado, Estado de Cuenta y opciones de gestión disponibles.<br><br>**Escenario 2:**<br>Dado que no existen clientes registrados,<br>Cuando el Arquitecto solicita la lista de clientes,<br>Entonces el sistema notifica que no se encontraron clientes registrados.<br><br>**Escenario 3:**<br>Dado que la cantidad de clientes supera el límite por página,<br>Cuando el Arquitecto navega en la lista,<br>Entonces el sistema habilita controles de paginación para consultar los registros restantes. | EP08 |
| US24 | Buscar/Ordenar Clientes | Como Ingeniero, quiero ordenar la lista de clientes por columnas (Nombre Completo, Proyecto Asociado, Estado de Cuenta) para organizar clientes rápidamente según criterios específicos. | **Escenario 1:**<br>Dado que el usuario consulta la lista de clientes,<br>Cuando solicita ordenar por Nombre Completo,<br>Entonces el sistema organiza los registros alfabéticamente de forma ascendente o descendente.<br><br>**Escenario 2:**<br>Dado que el usuario consulta la lista de clientes,<br>Cuando solicita ordenar por Proyecto Asociado,<br>Entonces el sistema clasifica los registros según el nombre del proyecto correspondiente.<br><br>**Escenario 3:**<br>Dado que el usuario consulta la lista de clientes,<br>Cuando solicita ordenar por Estado de Cuenta,<br>Entonces el sistema agrupa los registros según su condición operativa (Activo, Stand by o Suspendido). | EP08 |
| US25 | Agregar un Nuevo Cliente | Como Arquitecto, quiero agregar un nuevo cliente para registrarlo en el sistema. | **Escenario 1:**<br>Dado que el Arquitecto suministra datos obligatorios y válidos de un nuevo cliente,<br>Cuando confirma la solicitud de registro,<br>Entonces el sistema persiste el registro y lo incorpora en la lista activa de clientes.<br><br>**Escenario 2:**<br>Dado que el formulario carece de información obligatoria o presenta formatos erróneos,<br>Cuando el Arquitecto confirma la solicitud de registro,<br>Entonces el sistema rechaza la operación y señala los campos con error. | EP08 |
| US26 | Ver Perfil del Cliente | Como Ingeniero, quiero ver el perfil detallado de un cliente para acceder a su información completa y opciones de gestión. | **Escenario 1:**<br>Dado que se consulta un cliente registrado en la lista,<br>Cuando el Ingeniero solicita visualizar su perfil detallado,<br>Entonces el sistema presenta la ficha completa con los proyectos asociados e historial del cliente. | EP08 |
| US27 | Acceder a la Configuración del Cliente | Como Arquitecto, quiero acceder a la configuración específica de un cliente para gestionar el estado de su cuenta y permisos. | **Escenario 1:**<br>Dado que se selecciona un cliente registrado,<br>Cuando el Arquitecto solicita gestionar su configuración,<br>Entonces el sistema presenta las opciones operativas para actualizar datos, suspender, activar o dar de baja la cuenta del cliente. | EP08 |
| US28 | Ver Plan de Suscripción Actual | Como ingeniero, quiero ver mi plan de suscripción actual y su estado para confirmar los beneficios que tengo y el costo mensual. | **Escenario 1:**<br>Dado que el ingeniero accede a la sección de suscripción,<br>Cuando el sistema carga la vista,<br>Entonces el sistema muestra el nombre del plan actual (Enterprise), su costo total, el estado de la suscripción (Active) y una lista detallada de todos los beneficios incluidos. | EP02 |
| US29 | Ver Planes de Suscripción Alternativos | Como ingeniero, quiero ver planes de suscripción alternativos (Professional y Starter) para poder comparar sus precios y beneficios con mi plan actual. | **Escenario 1:**<br>Dado que el ingeniero accede a la sección de suscripción,<br>Cuando el sistema carga la vista,<br>Entonces el sistema muestra, junto al plan actual, las tarjetas informativas de los planes Professional y Starter, incluyendo sus costos y sus listas de beneficios específicos. | EP02 |
| US30 | Iniciar Cambio de Plan | Como arquitecto, quiero solicitar un cambio de plan de suscripción para adaptar el nivel de servicio a las necesidades del proyecto. | **Escenario 1:**<br>Dado que el arquitecto consulta la suscripción de la empresa,<br>Cuando solicita cambiar de plan,<br>Entonces el sistema habilita el catálogo de planes disponibles y permite seleccionar el nuevo nivel tarifario. | EP02 |
| US31 | Renovar Plan Activo | Como arquitecto, quiero renovar el plan de suscripción activo para garantizar la continuidad del servicio en obra. | **Escenario 1:**<br>Dado que la cuenta posee una suscripción activa próxima a vencer,<br>Cuando el arquitecto confirma la orden de renovación,<br>Entonces el sistema procesa la transacción y actualiza la vigencia del servicio emitiendo el comprobante correspondiente. | EP02 |
| US32 | Cancelar Plan Actual | Como ingeniero, quiero solicitar la cancelación del plan de suscripción para suspender cobros al término del ciclo de facturación. | **Escenario 1:**<br>Dado que existe una suscripción activa,<br>Cuando el ingeniero solicita la cancelación del servicio,<br>Entonces el sistema registra la solicitud, programa el cese de cobros al fin del ciclo y notifica la confirmación respectiva. | EP02 |
| US33 | Ver Lista de Dispositivos | Como ingeniero, quiero ver una lista de todos los dispositivos registrados en el proyecto para monitorear su estado operativo y ubicación. | **Escenario 1:**<br>Dado que existen dispositivos aprovisionados en el sistema,<br>Cuando el ingeniero consulta el inventario de dispositivos,<br>Entonces el sistema presenta los registros con nombre, tipo, ubicación y estado en tiempo real, habilitando opciones de configuración y baja técnica.<br><br>**Escenario 2:**<br>Dado que existen dispositivos desconectados de la red,<br>Cuando el ingeniero consulta el inventario,<br>Entonces el sistema indica de forma clara y distintiva la condición fuera de línea (*Offline*).<br><br>**Escenario 3:**<br>Dado que se visualiza el inventario de dispositivos,<br>Cuando el ingeniero solicita ordenar por nombre, tipo o ubicación,<br>Entonces el sistema reordena los registros según el criterio establecido. | EP11 |
| US34 | Agregar un Nuevo Dispositivo | Como arquitecto, quiero registrar un nuevo dispositivo inteligente en la plataforma para expandir la cobertura de monitoreo y automatización. | **Escenario 1:**<br>Dado que el arquitecto solicita incorporar un nuevo equipo,<br>Cuando el sistema presenta el formulario de aprovisionamiento,<br>Entonces permite ingresar los identificadores técnicos, tipo de sensor o actuador y espacio asignado.<br><br>**Escenario 2:**<br>Dado que el arquitecto proporciona los datos válidos del dispositivo,<br>Cuando confirma el aprovisionamiento,<br>Entonces el sistema valida la compatibilidad, registra el nodo en la base de datos y lo incorpora a la red operativa. | EP11 |
| US35 | Editar/Configurar Ajustes de Dispositivo | Como ingeniero, quiero modificar los parámetros técnicos de un dispositivo para ajustar umbrales de medición y asegurar su funcionamiento. | **Escenario 1:**<br>Dado que se selecciona un dispositivo activo en la plataforma,<br>Cuando el ingeniero solicita editar su configuración,<br>Entonces el sistema permite modificar parámetros de lectura, frecuencia de telemetría y reglas de alerta asociadas. | EP11 |
| US36 | Eliminar un Dispositivo | Como arquitecto, quiero dar de baja un dispositivo que ya no está en uso o presenta fallas irreversibles para depurar el inventario. | **Escenario 1:**<br>Dado que un dispositivo es seleccionado para desincorporación,<br>Cuando el arquitecto confirma la orden de baja técnica,<br>Entonces el sistema desvincula el dispositivo de la unidad y actualiza su estado a inactivo.<br><br>**Escenario 2:**<br>Dado que un dispositivo tiene dependencias críticas en reglas de automatización activas,<br>Cuando el arquitecto solicita su baja,<br>Entonces el sistema previene la eliminación y señala las dependencias operativas vigentes. | EP11 |
| US37 | Gestionar Notificaciones | Como Usuario, quiero activar o desactivar diferentes tipos de alertas para controlar las notificaciones recibidas del sistema. | **Escenario 1:**<br>Dado que el usuario gestiona sus preferencias de notificación,<br>Cuando modifica la activación de las Alertas de Expiración,<br>Entonces el sistema actualiza inmediatamente la configuración guardada.<br><br>**Escenario 2:**<br>Dado que el usuario gestiona sus preferencias de notificación,<br>Cuando modifica la recepción de Actualizaciones del Sistema,<br>Entonces el sistema habilita o inhabilita dichos avisos periódicos.<br><br>**Escenario 3:**<br>Dado que el usuario gestiona sus preferencias de notificación,<br>Cuando modifica las Notificaciones Push,<br>Entonces el sistema actualiza la suscripción de eventos en tiempo real hacia su terminal. | EP05 |
| US38 | Cambiar Contraseña de la Cuenta | Como Usuario, quiero cambiar mi contraseña periódicamente para mantener la seguridad de mi cuenta. | **Escenario 1:**<br>Dado que el usuario se encuentra autenticado,<br>Cuando suministra la credencial actual y define una nueva clave con su respectiva confirmación,<br>Entonces el sistema valida los requisitos de seguridad y actualiza la contraseña de acceso. | EP10 |
| US39 | Gestionar Autenticación de Dos Factores | Como Usuario, quiero configurar la Autenticación de Dos Factores (2FA) para añadir un nivel adicional de seguridad a mi cuenta. | **Escenario 1:**<br>Dado que el usuario desea robustecer el acceso a su cuenta,<br>Cuando activa la opción de autenticación en dos factores,<br>Entonces el sistema genera los códigos de verificación necesarios y activa el segundo factor para inicios de sesión posteriores. | EP10 |
| US40 | Gestionar Sesiones Activas | Como Usuario, quiero monitorear y gestionar las sesiones activas de mi cuenta para revocar accesos en terminales no reconocidos. | **Escenario 1:**<br>Dado que el usuario consulta las conexiones activas asociadas a su cuenta,<br>Cuando solicita cerrar una o todas las sesiones abiertas,<br>Entonces el sistema invalida los tokens correspondientes impidiendo el acceso continuado desde dichos terminales. | EP10 |
| US41 | Añadir Correo Electrónico Alternativo | Como Usuario, quiero asociar una dirección de correo alternativa para facilitar la recuperación de la cuenta y avisos secundarios. | **Escenario 1:**<br>Dado que el usuario ingresa una dirección de correo complementaria,<br>Cuando confirma la solicitud de adición,<br>Entonces el sistema remite un código de verificación para validar la titularidad antes de registrarla como cuenta secundaria. | EP10 |
| US42 | Acceder a Ayuda y Soporte | Como Usuario, quiero consultar recursos de ayuda y contactar a soporte técnico para resolver incidencias operativas. | **Escenario 1:**<br>Dado que el usuario requiere asistencia técnica,<br>Cuando solicita consultar las preguntas frecuentes,<br>Entonces el sistema presenta el catálogo de soluciones a dudas comunes.<br><br>**Escenario 2:**<br>Dado que la consulta requiere atención personalizada,<br>Cuando el usuario envía una solicitud de soporte,<br>Entonces el sistema genera un ticket de atención y notifica al equipo técnico. | EP01 |
| US43 | Registrarse en la plataforma | Como Usuario, quiero crear una cuenta nueva con mis datos básicos y rol para acceder a las capacidades de IoBuild. | **Escenario 1:**<br>Dado que el visitante proporciona información válida de contacto y credenciales de acceso,<br>Cuando envía el formulario de registro,<br>Entonces el sistema crea la cuenta, autentica al usuario y lo canaliza a la vista de bienvenida.<br><br>**Escenario 2:**<br>Dado que el correo suministrado ya se encuentra asociado a una cuenta existente,<br>Cuando el visitante intenta registrarse,<br>Entonces el sistema previene la duplicidad y notifica que el correo ya está en uso. | EP02 |
| US44 | Iniciar Sesión (Login) | Como Usuario, quiero ingresar mis credenciales para acceder a mi cuenta y utilizar los servicios de IoBuild. | **Escenario 1:**<br>Dado que el usuario ingresa sus credenciales correctas de acceso,<br>Cuando confirma la autenticación,<br>Entonces el sistema valida la identidad, genera la sesión activa y presenta la consola principal correspondiente a su rol.<br><br>**Escenario 2:**<br>Dado que se ingresan credenciales erróneas o no registradas,<br>Cuando se solicita la autenticación,<br>Entonces el sistema deniega el acceso y presenta un mensaje seguro de advertencia. | EP02 |
| US45 | Cerrar Sesión (Logout) | Como Usuario, quiero cerrar mi sesión actual para proteger mi cuenta, especialmente si estoy en un dispositivo compartido. | **Escenario 1:**<br>Dado que el usuario tiene una sesión activa.<br>Cuando selecciona la opción "Cerrar Sesión".<br>Entonces el sistema invalida su acceso actual y lo redirige a la página de inicio o login pública. | EP02 |
| TS01 | Listar proyectos por Constructor | Como desarrollador, quiero solicitar a la API que liste todos los proyectos asociados a un constructor específico, para poder mostrar la vista principal de Proyectos. | **Escenario 1:**<br>Dado que se recibe una solicitud para listar proyectos filtrados por el identificador del constructor (ej. *builderId*),<br>Cuando la API encuentra uno o más recursos de proyecto que coinciden,<br>Entonces la API responde con **200 OK** y devuelve un arreglo no vacío de recursos de proyecto, cada uno incluyendo los campos: *id, imagen, nombre, estado, tasaDeOcupacion y fechaDeCreacion.*<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para listar proyectos de un constructor,<br>Cuando la API no encuentra recursos que coincidan,<br>Entonces la API responde con **200 OK** y devuelve un arreglo vacío. | EP09 |
| TS02 | Crear un Proyecto | Como desarrollador, quiero añadir un nuevo proyecto a través de la API para poder implementar la funcionalidad de registro de nuevos desarrollos. | **Escenario 1:**<br>Dado que se recibe una solicitud de creación que incluye todos los campos obligatorios y válidos (ej. *nombre, unidadesTotales, fechaDeCreacion*),<br>Cuando la API valida y persiste el nuevo recurso de proyecto exitosamente,<br>Entonces la API responde con **201 Created**, y devuelve la representación del recurso creado (incluyendo *id* y los datos proporcionados).<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud de creación con campos obligatorios faltantes o con valores inválidos (ej. un campo numérico incorrecto),<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload de error que describe los errores de validación específicos. | EP09 |
| TS03 | Recuperar un Proyecto por ID | Como desarrollador, quiero solicitar un proyecto por su *{id}* para poder mostrar la vista de detalles del proyecto. | **Escenario 1:**<br>Dado que se recibe una solicitud para un proyecto identificado por *{id}*,<br>Cuando la API encuentra el recurso,<br>Entonces la API responde con **200 OK** y devuelve el recurso de proyecto completo (con todos sus atributos detallados).<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para un proyecto identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error indicando que el proyecto no existe. | EP09 |
| TS04 | Actualizar la información de un cliente | Como desarrollador, quiero enviar a la API una solicitud para modificar los datos de un cliente existente, para poder implementar la edición de su perfil y la gestión de su estado de cuenta. | **Escenario 1:**<br>Dado que se recibe una solicitud **PUT** o **PATCH** para actualizar el cliente identificado por *{id}* con datos válidos (ej. un nuevo *accountStatement*),<br>Cuando la API valida y persiste los cambios exitosamente,<br>Entonces la API responde con **200 OK** y devuelve la representación del recurso de cliente actualizado.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud de actualización con campos obligatorios faltantes o que contienen valores inválidos,<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload de error que describe los errores de validación.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud para actualizar un cliente con un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error. | EP08 |
| TS05 | Eliminar un cliente | Como desarrollador, quiero solicitar a la API la eliminación de un cliente por su *{id}*, para poder implementar la funcionalidad de dar de baja clientes que ya no se utilizarán. | **Escenario 1:**<br>Dado que se recibe una solicitud **DELETE** para eliminar un cliente identificado por *{id}*,<br>Cuando la API elimina el recurso exitosamente,<br>Entonces la API responde con **204 No Content** (estándar para eliminación exitosa).<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para eliminar un cliente identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud para eliminar un cliente identificado por *{id}* que tiene proyectos activos o dependencias críticas,<br>Cuando la API detecta una restricción de dependencia,<br>Entonces la API responde con **409 Conflict** y un payload de error explicando que la acción fue rechazada debido a dependencias. | EP08 |
| TS06 | Soportar ordenación en la lista de clientes | Como desarrollador, quiero poder enviar parámetros de ordenación a la API (nombre de columna y dirección), para poder implementar las funcionalidades de Buscar/Ordenar Clientes. | **Escenario 1:**<br>Dado que se recibe una solicitud para listar clientes incluyendo parámetros de ordenación válidos (ej. *sort=fullName,desc* o *sort=accountStatement,asc*),<br>Cuando la API procesa los datos y aplica la ordenación,<br>Entonces la API responde con **200 OK** y los clientes son devueltos en el orden especificado.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para listar clientes incluyendo un parámetro de ordenación inválido o una columna no soportada,<br>Cuando la API valida los parámetros de entrada,<br>Entonces la API responde con **400 Bad Request** y un payload de error indicando que el parámetro de ordenación es incorrecto o no está permitido. | EP08 |
| TS07 | Listar clientes | Como desarrollador, quiero solicitar a la API que liste los clientes, opcionalmente filtrados por estado o nombre, para poder mostrar la vista de la lista de clientes. | **Escenario 1:**<br>Dado que se recibe una solicitud para listar clientes, potencialmente incluyendo parámetros de paginación (*límite*, *offset*) y ordenamiento,<br>Cuando la API encuentra uno o más clientes,<br>Entonces la API responde con **200 OK** y devuelve un arreglo de recursos de cliente, incluyendo *id*, *fullName*, *associatedProject* y *accountStatement*, junto con metadatos de paginación.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para listar clientes,<br>Cuando la API no encuentra recursos que coincidan,<br>Entonces la API responde con **200 OK** y devuelve un arreglo vacío. | EP08 |
| TS08 | Crear un cliente | Como desarrollador, quiero añadir un nuevo cliente a través de la API para poder implementar la funcionalidad de creación de clientes. | **Escenario 1:**<br>Dado que se recibe una solicitud de creación que incluye campos obligatorios (ej. *fullName*),<br>Cuando la API valida y persiste el nuevo cliente exitosamente,<br>Entonces la API responde con **201 Created** y devuelve la representación del recurso de cliente creado (incluyendo *id*).<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud de creación con campos obligatorios faltantes o que contienen valores inválidos,<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload de error que describe los errores de validación.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud de creación para un *fullName* que ya existe,<br>Cuando la API detecta la violación de la restricción de duplicado,<br>Entonces la API responde con **409 Conflict** y un payload de error explicativo. | EP08 |
| TS09 | Recuperar un cliente por id | Como desarrollador, quiero solicitar un recurso de cliente por su *{id}* para poder implementar la vista detallada del perfil. | **Escenario 1:**<br>Dado que se recibe una solicitud para un cliente identificado por *{id}*,<br>Cuando la API encuentra el recurso,<br>Entonces la API responde con **200 OK** y devuelve el recurso de cliente completo.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para un cliente identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error. | EP08 |
| TS10 | Listar dispositivos | Como desarrollador, quiero solicitar a la API que liste todos los dispositivos, filtrados por ubicación o estado, para poder mostrar la lista de Gestión de Dispositivos. | **Escenario 1:**<br>Dado que se recibe una solicitud para listar dispositivos,<br>Cuando la API encuentra uno o más recursos de dispositivo,<br>Entonces la API responde con **200 OK** y devuelve un arreglo no vacío de recursos de dispositivo, cada uno incluyendo *id*, *name*, *type*, *location* y *realTimeStatus*.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para listar dispositivos,<br>Cuando la API no encuentra recursos que coincidan,<br>Entonces la API responde con **200 OK** y devuelve un arreglo vacío.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud para listar dispositivos filtrados por un parámetro de *status* (ej. “Offline”),<br>Cuando la API filtra los recursos,<br>Entonces la API responde con **200 OK** y devuelve solo los dispositivos que coinciden con el estado solicitado. | EP11 |
| TS11 | Eliminar un dispositivo por id | Como desarrollador, quiero solicitar a la API que elimine un dispositivo por su *{id}* para poder retirar hardware que ya no se utiliza del sistema. | **Escenario 1:**<br>Dado que se recibe una solicitud para eliminar un dispositivo identificado por *{id}*,<br>Cuando la API elimina el recurso exitosamente,<br>Entonces la API responde con **204 No Content** (estándar para eliminación exitosa).<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud para eliminar un dispositivo identificado por un *{id}* no existente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un payload de error.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud para eliminar un dispositivo identificado por *{id}* que está actualmente en uso o vinculado a datos críticos,<br>Cuando la API detecta una restricción de dependencia,<br>Entonces la API responde con **409 Conflict** y un payload de error explicando la dependencia. | EP11 |
| TS12 | Actualizar información de un proyecto | Como desarrollador, quiero solicitar a la API que actualice la información de un proyecto (nombre, ubicación y descripción) para mantener los datos actualizados en la vista de gestión de proyectos. | **Escenario 1:**<br>Dado que se recibe una solicitud para actualizar un proyecto identificado por *{id}*, incluyendo campos válidos como *name*, *location* y *description*,<br>Cuando la API valida y persiste los cambios correctamente,<br>Entonces la API responde con **200 OK** y devuelve la representación actualizada del recurso de proyecto.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud de actualización con campos faltantes o valores inválidos,<br>Cuando la validación de la API falla,<br>Entonces la API responde con **400 Bad Request** y un payload que describe los errores de validación.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud para actualizar un proyecto identificado por un *{id}* inexistente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un mensaje de error apropiado. | EP09 |
| TS13 | Actualizar información de un dispositivo | Como desarrollador, quiero solicitar a la API que actualice la información de un dispositivo (nombre y ubicación) para reflejar los cambios en la gestión de dispositivos. | **Escenario 1:**<br>Dado que se recibe una solicitud para actualizar un dispositivo identificado por *{id}*, incluyendo campos válidos como *name* y *location*,<br>Cuando la API valida y persiste los cambios exitosamente,<br>Entonces la API responde con **200 OK** y devuelve el recurso de dispositivo actualizado.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud con campos inválidos o formatos incorrectos,<br>Cuando la API valida la información y detecta errores,<br>Entonces la API responde con **400 Bad Request** y un payload con los detalles del error.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud para actualizar un dispositivo con un *{id}* inexistente,<br>Cuando la API no encuentra el recurso,<br>Entonces la API responde con **404 Not Found** y un mensaje de error. | EP11 |
| TS14 | Crear un nuevo dispositivo | Como desarrollador, quiero solicitar a la API que cree un nuevo dispositivo especificando su nombre, tipo y ubicación, para registrar nuevos equipos en el sistema. | **Escenario 1:**<br>Dado que se recibe una solicitud de creación de un dispositivo con los campos obligatorios (*name*, *type*, *location*),<br>Cuando la API valida y persiste el nuevo recurso,<br>Entonces la API responde con **201 Created** y devuelve la representación del dispositivo creado, incluyendo su *id*.<br><br>**Escenario 2:**<br>Dado que se recibe una solicitud con campos faltantes o datos inválidos,<br>Cuando la API detecta errores de validación,<br>Entonces la API responde con **400 Bad Request** y un payload con los mensajes de error.<br><br>**Escenario 3:**<br>Dado que se recibe una solicitud para crear un dispositivo con un *name* duplicado,<br>Cuando la API detecta una violación de unicidad,<br>Entonces la API responde con **409 Conflict** y un mensaje explicativo. | EP11 |
| TS15 | Crear ruta protegida y restringir acceso a la consola de gestión | Como desarrollador, quiero implementar rutas protegidas con verificación de roles para asegurar que únicamente los ingenieros y constructores autorizados accedan a la consola de gestión técnica. | **Escenario 1:**<br>Dado que se configura una ruta protegida para el rol de constructor/ingeniero,<br>Cuando un usuario con dicho rol solicita acceder a la consola,<br>Entonces el sistema autoriza el acceso y suministra la información del proyecto.<br><br>**Escenario 2:**<br>Dado que un usuario sin privilegios de constructor intenta ingresar a la ruta protegida,<br>Cuando la API o router intercepta la solicitud,<br>Entonces el sistema restringe el acceso y responde con código de estado HTTP **403 Forbidden**. | EP10 |
| TS16 | Obtener suscripción actual | Como desarrollador, quiero solicitar la información de la suscripción activa del usuario actual, para mostrar el plan, costo y beneficios en la vista principal de suscripciones. | **Escenario 1:**<br>Dado que se recibe una solicitud GET para recuperar la suscripción del usuario autenticado<br>Cuando la API encuentra una suscripción activa asociada al usuario.<br>Entonces la API responde con **200 OK** y devuelve un objeto con los detalles del plan.<br><br>**Escenario 2:**<br>Dado que el usuario no cuenta con una suscripción vigente.<br>Cuando la API procesa la solicitud.<br>Entonces la API responde con **404 Not Found** indicando que no hay plan contratado. | EP02 |
| TS17 | Listar catálogo de planes | Como desarrollador, quiero solicitar la lista de todos los planes de suscripción disponibles en el sistema, para mostrarlos como alternativas en la interfaz de comparación. | **Escenario 1:**<br>Dado que se recibe una solicitud GET al endpoint de catálogo de planes.<br>Cuando la API recupera la configuración de planes disponibles en la base de datos.<br>Entonces la API responde con **200 OK** y devuelve un arreglo de objetos, donde cada uno contiene el nombre del plan, precio mensual y la lista de beneficios específicos. | EP02 |
| TS18 | Cambiar plan de suscripción | Como desarrollador, quiero enviar una solicitud para actualizar el plan de suscripción del usuario, para hacer efectivo el cambio de nivel de servicio seleccionado en la interfaz. | **Escenario 1:**<br>Dado que se recibe una solicitud PUT con el identificador del nuevo plan seleccionado.<br>Cuando la API valida que el plan existe y procesa la actualización de la suscripción.<br>Entonces la API responde con **200 OK** y devuelve los detalles de la suscripción actualizada con el nuevo plan.<br><br>**Escenario 2:**<br>Dado que se intenta cambiar a un plan inválido o no disponible.<br>Cuando la validación de la API falla.<br>Entonces la API responde con **400 Bad Request** indicando que el plan seleccionado no es válido para la transición. | EP02 |
| TS19 | Renovar suscripción | Como desarrollador, quiero solicitar la renovación de la suscripción actual, para extender la vigencia del servicio cuando el usuario confirma la acción. | **Escenario 1:**<br>Dado que se recibe una solicitud POST al endpoint de renovación para la suscripción actual.<br>Cuando la API procesa el pago o extiende la fecha de expiración exitosamente.<br>Entonces la API responde con **200 OK** y devuelve la suscripción con la nueva fecha de vencimiento actualizada.<br><br>**Escenario 2:**<br>Dado que hay un problema con el método de pago o el estado de la cuenta.<br>Cuando el proceso de renovación falla en el backend.<br>Entonces la API responde con **402 Payment Required** o **400 Bad Request** con el detalle del error. | EP02 |
| TS20 | Cancelar suscripción | Como desarrollador, quiero solicitar la cancelación de la suscripción activa, para detener la renovación automática y finalizar el servicio al terminar el ciclo. | **Escenario 1:**<br>Dado que se recibe una solicitud DELETE sobre la suscripción activa.<br>Cuando la API registra la solicitud de cancelación y actualiza el estado a "Cancelled" o "Pending Cancellation".<br>Entonces la API responde con **200 OK** confirmando que la suscripción no se renovará, pero manteniendo el acceso hasta el final del periodo actual si aplica. | EP02 |
| TS21 | Cambiar contraseña del usuario | Como desarrollador, quiero enviar la contraseña actual y la nueva contraseña del usuario a la API, para actualizar sus credenciales de acceso de forma segura. | **Escenario 1:**<br>Dado que se recibe una solicitud PUT al endpoint de cambio de contraseña que incluye currentPassword y newPassword.<br>Cuando la API verifica que la currentPassword coincide con la almacenada y la newPassword cumple con los requisitos de complejidad.<br>Entonces la API actualiza la contraseña (hashing), responde con **200 OK** y opcionalmente invalida otras sesiones activas o genera un nuevo token.<br><br>**Escenario 2:**<br>Dado que se intenta cambiar la contraseña proporcionando una currentPassword errónea.<br>Cuando la API detecta que la contraseña actual no coincide con la registrada.<br>Entonces la API responde con **400 Bad Request** con un mensaje indicando que la contraseña actual es inválida. | EP10 |
| TS22 | Solicitar adición de correo alternativo | Como desarrollador, quiero enviar una solicitud para agregar un correo electrónico secundario, para que el backend inicie el proceso de validación y verificación de dicha cuenta. | **Escenario 1:**<br>Dado que se recibe una solicitud POST con un email válido que no está registrado previamente.<br>Cuando la API registra el correo en estado "Pendiente" y dispara el servicio de envío de emails con el código o enlace de verificación.<br>Entonces la API responde con **200 OK** indicando que se ha enviado el correo de confirmación al usuario.<br><br>**Escenario 2:**<br>Dado que se intenta agregar un correo con formato incorrecto o que ya está en uso por otro usuario.<br>Cuando la API valida la unicidad y el formato del correo.<br>Entonces la API responde con **400 Bad Request**. | EP10 |
| TS23 | Registrar nuevo usuario | Como desarrollador, quiero enviar los datos de registro (nombre, email, password, rol) a la API, para crear una nueva identidad en el sistema y permitir el acceso futuro. | **Escenario 1:**<br>Dado que se recibe una solicitud POST con payload válido (email único, password cumple requisitos).<br>Cuando la API persiste el nuevo usuario y encripta la contraseña.<br>Entonces la API responde con **201 Created** y devuelve los datos del usuario creado o un token de acceso inicial.<br><br>**Escenario 2:**<br>Dado que se recibe un email que ya está registrado en la base de datos.<br>Cuando la API valida la unicidad del usuario.<br>Entonces la API responde con **409 Conflict** indicando que el recurso ya existe. | EP13 |
| TS24 | Validar token de sesión | Como desarrollador, quiero que la API valide que el token enviado en los headers es legítimo y no ha expirado, para proteger las rutas privadas. | **Escenario 1:**<br>Dado que se realiza una petición a un recurso protegido con un header Authorization: Bearer {token}.<br>Cuando la API verifica la firma y fecha del token.<br>Entonces la API permite el acceso y devuelve el recurso solicitado.<br><br>**Escenario 2:**<br>Dado que el token está caducado o malformado.<br>Cuando la API intenta decodificarlo.<br>Entonces la API responde con **401 Unauthorized** o **403 Forbidden**. | EP10 |

## 3.2. Impact Mapping.

El Impact Mapping es una técnica visual colaborativa que permite conectar los objetivos estratégicos del negocio con las acciones concretas de los usuarios y las funcionalidades del producto digital. Mediante un esquema jerárquico en forma de árbol, esta técnica muestra cómo las metas comerciales se traducen en cambios de comportamiento esperados en los actores clave y en entregables que hacen posible dichos cambios.

En el caso del presente proyecto, se utilizó esta herramienta para estructurar de manera clara la relación entre las metas SMART del modelo digital, los User Personas previamente definidos y las funcionalidades necesarias. El trabajo incluyó:

* **Business Goals SMART:** Plantean metas específicas, medibles, alcanzables, relevantes y con plazos definidos, orientadas tanto a la adquisición de usuarios como a la retención y recurrencia.
* **Actores principales:** Representados por Miguel Veramendi (Constructor / Arquitecto) y Carla Flores (Residente / Propietaria), definidos a partir de sus motivaciones y del rol que cumplen en el ecosistema domótico.
* **Impactos esperados:** Expresados como conductas observables que cada actor debe realizar para contribuir al cumplimiento de los objetivos (ejemplo: incorporar la solución en propuestas de diseño o personalizar perfiles de confort en el hogar).
* **Deliverables funcionales:** Características y componentes del producto digital diseñados para provocar esos impactos (plantillas de propuesta, consolas de telemetría o notificaciones guiadas).

El mapa fue diseñado siguiendo un enfoque centrado en el usuario y buenas prácticas colaborativas para asegurar la trazabilidad entre las metas de negocio y el desarrollo técnico de la solución.

**Anexo: Impact Mapping (Enlace interactivo):**  
[https://drive.google.com/file/d/1fFT-OfL06jICOptImqpWyogQl_eAtWj3/view?usp=sharing](https://drive.google.com/file/d/1fFT-OfL06jICOptImqpWyogQl_eAtWj3/view?usp=sharing)

<br>

**Business Goal 1: Alcanzar 600 suscripciones activas al plan inicial en un periodo de 8 meses.**

Este objetivo representa el primer paso estratégico para la consolidación del modelo de negocio digital de IoBuild. Se centra en la adquisición de usuarios iniciales, quienes validarán la propuesta de valor y permitirán generar un flujo de ingresos recurrente en la etapa temprana. La meta de 600 suscripciones en 8 meses no solo es medible y alcanzable según el análisis de mercado de edificaciones en Lima Metropolitana, sino que también responde a la necesidad de alcanzar un punto de equilibrio temprano, garantizando tracción sostenible.

Asimismo, este Business Goal está alineado con las actividades de los principales actores identificados (Miguel Veramendi y Carla Flores), quienes, a través de comportamientos clave (incorporar la solución en proyectos, usarla e interactuar activamente), impulsan la adopción de la plataforma.

<br>

![Impact-Mapping-1](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%203/Impact-Mapping-1.png)

<br><br>

**Business Goal 2: Automatizar el 70 % de los procesos de personalización en un periodo de 6 meses y aumentar la retención de clientes recurrentes en un 25 % en 9 meses.**

Este objetivo se enfoca en la optimización y sostenibilidad operativa del negocio en el mediano plazo. Una vez consolidada la primera base de clientes, el siguiente reto es reducir la fricción en el uso de la solución domótica a través de automatizaciones que hagan la experiencia de control ambiental más fluida e intuitiva. Lograr que al menos el 70 % de los procesos de personalización ambiental se realicen automáticamente en 6 meses permitirá que los usuarios perciban mayor comodidad y ahorro de tiempo.

De manera complementaria, la segunda parte de este objetivo busca incrementar la retención de clientes en un 25 % en 9 meses, consolidando relaciones duraderas y disminuyendo la tasa de abandono de la suscripción SaaS.

<br>

![Impact-Mapping-2](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%203/Impact-Mapping-2.png)

## 3.3. Product Backlog.

A continuación, se presenta el Product Backlog consolidado con las 45 historias de usuario y 24 tareas técnicas priorizadas para el desarrollo de la plataforma IoBuild. Cada ítem incluye su orden de priorización basado en el valor de negocio y dependencias arquitectónicas, identificador, título, descripción en formato ágil, su estimación en puntos de historia (Story Points bajo la secuencia Fibonacci 1, 2, 3, 5 y 8) y el Sprint planificado para su entrega.

Para el control, priorización y diseño del Product Backlog se utilizó la herramienta colaborativa Trello, la cual permitió organizar y visualizar el backlog en etapas de desarrollo, facilitando el seguimiento continuo del progreso y la gestión ágil del trabajo.

**Enlace del tablero colaborativo en Trello:** [https://goo.su/DYSGr6](https://goo.su/DYSGr6)

<br>

![Product-Backlog](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%203/Product-Backlog.png)

<br>

| #Orden | User Story / Task ID | Título | Descripción | Story Points (1/2/3/5/8) | Sprint |
|---|---|---|---|---|---|
| 1 | US01 | Seccion "Sobre Nosotros" | Como visitante del sitio, quiero conocer la historia y valores de la empresa, para tener mayor conexion y confianza con IoBuild. | 2 | Sprint 1 |
| 2 | US02 | Seccion testimonios del cliente | Como visitante del sitio, quiero consultar testimonios de otros clientes, para generar confianza en la propuesta de valor de la startup. | 2 | Sprint 1 |
| 3 | US03 | Acceso a informacion de contacto | Como visitante del sitio, quiero acceder facilmente a los canales de contacto de IoBuild, para comunicarme ante dudas comerciales. | 1 | Sprint 1 |
| 4 | US04 | Visualizacion de servicios principales | Como visitante del sitio, quiero conocer los servicios que ofrece IoBuild, para comprender su propuesta de valor en edificaciones inteligentes. | 2 | Sprint 1 |
| 5 | US05 | Opcion de registro en Landing | Como visitante del sitio, quiero acceder a la opcion de registro desde la pagina principal, para iniciar la creacion de mi cuenta. | 1 | Sprint 1 |
| 6 | US06 | Preguntas frecuentes (FAQ) | Como visitante del sitio, quiero consultar una seccion de preguntas frecuentes, para resolver inquietudes comunes de forma inmediata. | 2 | Sprint 1 |
| 7 | US07 | Internacionalizacion de la landing page | Como visitante del sitio, quiero disponer de mas de un idioma disponible (español e ingles), para navegar en mi idioma de preferencia. | 3 | Sprint 1 |
| 8 | US43 | Registrarse en la plataforma | Como Usuario, quiero crear una cuenta nueva con mis datos basicos y rol para acceder a las capacidades de IoBuild. | 5 | Sprint 1 |
| 9 | US44 | Iniciar Sesion (Login) | Como Usuario, quiero ingresar mis credenciales para acceder a mi cuenta y utilizar los servicios de IoBuild. | 3 | Sprint 1 |
| 10 | US45 | Cerrar Sesion (Logout) | Como Usuario, quiero cerrar mi sesion actual para proteger mi cuenta y revocar los tokens locales. | 1 | Sprint 1 |
| 11 | TS23 | Registrar nuevo usuario en API | Como desarrollador, quiero enviar los datos de registro (nombre, email, contraseña y rol) a la API, para crear una nueva identidad en el sistema. | 5 | Sprint 1 |
| 12 | TS24 | Validar token de sesion | Como desarrollador, quiero que la API valide que el token JWT enviado en los encabezados es legitimo y no ha expirado, protegiendo las rutas privadas. | 3 | Sprint 1 |
| 13 | US16 | Acceso a Perfil del Usuario | Como usuario, quiero acceder a mi perfil para visualizar mis datos registrados (nombre, email, telefono y direccion). | 2 | Sprint 1 |
| 14 | US17 | Edicion de Informacion del Perfil | Como usuario, quiero modificar datos de mi perfil (telefono o direccion) para mantener mi informacion actualizada. | 3 | Sprint 1 |
| 15 | US18 | Ver Imagen que Representa al Usuario | Como usuario, quiero visualizar mi fotografia o avatar de perfil, para contar con una experiencia personalizada. | 2 | Sprint 1 |
| 16 | US19 | Ver el Rol de la Cuenta | Como usuario, quiero visualizar el rol asignado a mi cuenta, para conocer los permisos operativos disponibles. | 1 | Sprint 1 |
| 17 | TS02 | Crear un Proyecto en API | Como desarrollador, quiero añadir un nuevo proyecto arquitectonico a traves de la API para implementar el registro de nuevos desarrollos. | 5 | Sprint 2 |
| 18 | TS01 | Listar proyectos por Constructor | Como desarrollador, quiero solicitar a la API que liste todos los proyectos asociados a un constructor, para abastecer la vista principal de Proyectos. | 3 | Sprint 2 |
| 19 | TS03 | Recuperar un Proyecto por ID | Como desarrollador, quiero solicitar un proyecto por su identificador unico para mostrar la vista de detalles y zonificacion. | 3 | Sprint 2 |
| 20 | TS12 | Actualizar informacion de un proyecto | Como desarrollador, quiero enviar a la API modificaciones de un proyecto (nombre, ubicacion y descripcion) para mantener la informacion al dia. | 3 | Sprint 2 |
| 21 | US20 | Ver lista de proyectos | Como ingeniero, quiero ver una lista de todos mis proyectos para conocer el estado y caracteristicas de cada obra. | 3 | Sprint 2 |
| 22 | US21 | Agregar un nuevo proyecto | Como arquitecto, quiero registrar un nuevo proyecto inteligente para parametrizar nuevos desarrollos inmobiliarios. | 5 | Sprint 2 |
| 23 | US22 | Ver detalles de un proyecto | Como arquitecto, quiero examinar los detalles tecnicos de un proyecto especifico para revisar su estructura fisica y configuracion. | 3 | Sprint 2 |
| 24 | TS14 | Crear un nuevo dispositivo en API | Como desarrollador, quiero solicitar a la API que registre un nuevo dispositivo con nombre, tipo y ubicacion, integrando nuevo hardware al sistema. | 5 | Sprint 2 |
| 25 | TS10 | Listar dispositivos en API | Como desarrollador, quiero solicitar a la API la lista de dispositivos filtrada por ubicacion o estado, para alimentar la vista de inventario. | 3 | Sprint 2 |
| 26 | TS13 | Actualizar informacion de un dispositivo | Como desarrollador, quiero enviar a la API cambios en el nombre o ubicacion de un dispositivo para reflejar su reasignacion fisica. | 3 | Sprint 2 |
| 27 | TS11 | Eliminar un dispositivo por ID | Como desarrollador, quiero solicitar a la API la baja de un dispositivo por su identificador para retirar hardware desincorporado. | 2 | Sprint 2 |
| 28 | US33 | Ver Lista de Dispositivos | Como ingeniero, quiero consultar la lista de dispositivos registrados en el proyecto para supervisar su operatividad y ubicacion fisica. | 3 | Sprint 2 |
| 29 | US34 | Agregar un Nuevo Dispositivo | Como arquitecto, quiero incorporar un nuevo sensor o actuador inteligente para ampliar la cobertura de monitoreo de la edificacion. | 5 | Sprint 2 |
| 30 | US35 | Editar/Configurar Ajustes de Dispositivo | Como ingeniero, quiero modificar los parametros tecnicos de un dispositivo para calibrar umbrales y asegurar su correcto funcionamiento. | 5 | Sprint 2 |
| 31 | US36 | Eliminar un Dispositivo | Como arquitecto, quiero desvincular un dispositivo en desuso o defectuoso para mantener depurado el inventario del proyecto. | 3 | Sprint 2 |
| 32 | TS15 | Crear ruta protegida y restringir acceso a la consola de gestion | Como desarrollador, quiero implementar rutas protegidas con verificacion de roles para asegurar que unicamente ingenieros y constructores autorizados gestionen hardware. | 5 | Sprint 2 |
| 33 | US08 | Dashboard Personalizado | Como usuario, quiero acceder a un panel principal con metricas clave, para monitorear el estado de las instalaciones de forma eficiente. | 5 | Sprint 3 |
| 34 | US09 | Acceso a Proyectos Activos en Dashboard | Como ingeniero, quiero consultar los proyectos activos desde el panel, para verificar su progreso y administrar recursos en obra. | 3 | Sprint 3 |
| 35 | US10 | Acceso a Dispositivos Conectados | Como usuario, quiero verificar el estado de conexion de los dispositivos, para identificar equipos activos o desconectados. | 3 | Sprint 3 |
| 36 | US11 | Acceso a la Capacidad de Ocupacion | Como ingeniero, quiero consultar la capacidad de ocupacion por proyecto, para optimizar el dimensionamiento de servicios e instalaciones. | 3 | Sprint 3 |
| 37 | US12 | Grafico de Consumo de Energia por Hora | Como ingeniero, quiero visualizar un grafico de consumo energetico horario, para evaluar el rendimiento electrico en tiempo real. | 8 | Sprint 3 |
| 38 | US13 | Grafico de Registro de Ocupacion | Como ingeniero, quiero observar un grafico historico de ocupacion, para correlacionar la afluencia de personas con el uso de recursos. | 5 | Sprint 3 |
| 39 | US14 | Resumen Ejecutivo de Proyecto | Como ingeniero, quiero visualizar un resumen de proyecto con su estado, ubicacion y aforo habitacional, obteniendo un balance rapido de obra. | 3 | Sprint 3 |
| 40 | US15 | Visualizacion de Dispositivos y Distribucion por Tipo | Como ingeniero, quiero analizar la distribucion de dispositivos por tipologia mediante graficos, planificando ampliaciones de red. | 5 | Sprint 3 |
| 41 | TS08 | Crear un cliente/residente en API | Como desarrollador, quiero añadir un nuevo perfil de residente a traves de la API para asociarlo a un departamento especifico. | 5 | Sprint 3 |
| 42 | TS07 | Listar clientes en API | Como desarrollador, quiero consultar a la API la lista de clientes con soporte a paginacion para la gestion de residentes. | 3 | Sprint 3 |
| 43 | TS09 | Recuperar un cliente por ID | Como desarrollador, quiero consultar los datos de un cliente especifico por su identificador para mostrar su ficha detallada. | 2 | Sprint 3 |
| 44 | TS04 | Actualizar la informacion de un cliente | Como desarrollador, quiero enviar a la API modificaciones en los datos del cliente para mantener actualizada su informacion de contacto. | 3 | Sprint 3 |
| 45 | TS06 | Soportar ordenacion en la lista de clientes | Como desarrollador, quiero enviar parametros de ordenacion (columna y sentido) a la API para agilizar la busqueda de residentes. | 5 | Sprint 3 |
| 46 | TS05 | Eliminar un cliente en API | Como desarrollador, quiero solicitar a la API la baja de un cliente para desvincular usuarios que ya no residen en el inmueble. | 3 | Sprint 3 |
| 47 | US23 | Ver Lista de Clientes | Como Arquitecto, quiero visualizar la lista de clientes para supervisar sus departamentos asignados y el estado de su cuenta. | 3 | Sprint 3 |
| 48 | US24 | Buscar/Ordenar Clientes | Como Ingeniero, quiero ordenar la lista de residentes por columnas para localizar cuentas con rapidez segun criterios operativos. | 3 | Sprint 3 |
| 49 | US25 | Agregar un Nuevo Cliente | Como Arquitecto, quiero dar de alta un nuevo cliente o propietario para otorgarle acceso a su unidad habitacional. | 3 | Sprint 3 |
| 50 | US26 | Ver Perfil del Cliente | Como Ingeniero, quiero consultar el perfil detallado de un residente para verificar sus unidades asignadas y dispositivos en uso. | 3 | Sprint 3 |
| 51 | US27 | Acceder a la Configuracion del Cliente | Como Arquitecto, quiero gestionar los permisos y estado de cuenta de un cliente para adecuar su nivel de acceso. | 3 | Sprint 3 |
| 52 | TS17 | Listar catalogo de planes en API | Como desarrollador, quiero solicitar a la API el catalogo de planes disponibles para poblar las opciones de suscripcion. | 3 | Sprint 4 |
| 53 | TS16 | Obtener suscripcion actual en API | Como desarrollador, quiero solicitar la informacion del plan activo del usuario para presentar su vigencia y costo en la interfaz. | 3 | Sprint 4 |
| 54 | TS18 | Cambiar plan de suscripcion en API | Como desarrollador, quiero enviar a la API la actualizacion de nivel de suscripcion para procesar el cambio de categoria de servicio. | 5 | Sprint 4 |
| 55 | TS19 | Renovar suscripcion en API | Como desarrollador, quiero enviar a la API la solicitud de renovacion de suscripcion para extender la vigencia del servicio. | 5 | Sprint 4 |
| 56 | TS20 | Cancelar suscripcion en API | Como desarrollador, quiero solicitar a la API la cancelacion de la renovacion automatica, finalizando el servicio al termino del ciclo. | 3 | Sprint 4 |
| 57 | US28 | Ver Plan de Suscripcion Actual | Como ingeniero, quiero consultar mi plan de suscripcion y vigencia para validar los beneficios contratados y costo mensual. | 3 | Sprint 4 |
| 58 | US29 | Ver Planes de Suscripcion Alternativos | Como ingeniero, quiero comparar los planes disponibles (Professional y Starter) para evaluar mejoras de cobertura tecnica. | 3 | Sprint 4 |
| 59 | US30 | Iniciar Cambio de Plan | Como arquitecto, quiero seleccionar un nuevo plan de suscripcion para adaptar la plataforma al crecimiento de mis proyectos. | 5 | Sprint 4 |
| 60 | US31 | Renovar Plan Activo | Como arquitecto, quiero tramitar la renovacion de mi suscripcion para asegurar la continuidad operativa de los sensores en obra. | 5 | Sprint 4 |
| 61 | US32 | Cancelar Plan Actual | Como ingeniero, quiero cancelar mi plan contratado al finalizar los proyectos para suspender cobros recurrentes. | 3 | Sprint 4 |
| 62 | TS21 | Cambiar contraseña en API | Como desarrollador, quiero enviar la contraseña actual y la nueva a la API para actualizar las credenciales de manera segura. | 3 | Sprint 4 |
| 63 | TS22 | Solicitar adicion de correo alternativo en API | Como desarrollador, quiero enviar una direccion de correo secundaria a la API para iniciar el proceso de verificacion. | 3 | Sprint 4 |
| 64 | US37 | Gestionar Notificaciones | Como Usuario, quiero configurar que alertas operativas y de consumo deseo recibir para evitar saturacion de mensajes. | 3 | Sprint 4 |
| 65 | US38 | Cambiar Contraseña de la Cuenta | Como Usuario, quiero renovar periodicamente mi contraseña para mantener protegidas mis credenciales de acceso. | 3 | Sprint 4 |
| 66 | US39 | Gestionar Autenticacion de Dos Factores | Como Usuario, quiero habilitar la Autenticacion de Dos Factores (2FA) para robustecer la seguridad en accesos criticos. | 5 | Sprint 4 |
| 67 | US40 | Gestionar Sesiones Activas | Como Usuario, quiero monitorear sesiones abiertas en diferentes navegadores y cerrarlas remotamente ante sospechas. | 5 | Sprint 4 |
| 68 | US41 | Añadir Correo Electronico Alternativo | Como Usuario, quiero registrar una cuenta de correo secundaria para facilitar la recuperacion de acceso. | 3 | Sprint 4 |
| 69 | US42 | Acceder a Ayuda y Soporte | Como Usuario, quiero consultar la base de conocimientos y contactar al equipo tecnico para resolver incidencias de plataforma. | 2 | Sprint 4 |

---

<div style="page-break-before: always;"></div>

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design.

El enfoque de **Strategic-Level Domain-Driven Design** sirve como pilar esencial en el desarrollo de la plataforma **IoBuild**. Mediante este marco de diseño estratégico, es posible identificar y delimitar los distintos contextos del dominio, definir cómo se relacionan entre sí y construir una arquitectura de software modular que responda a los objetivos del negocio en edificaciones inteligentes y telemetría IoT.

En esta etapa estratégica, se prioriza:

- Un entendimiento profundo del dominio, mediante la identificación de los procesos clave del negocio.
- La definición de *Bounded Contexts*, estableciendo límites claros entre las distintas áreas funcionales.
- El modelado de las relaciones y contratos de integración entre los diferentes contextos.
- El diseño de una arquitectura de software estructurada e integral basada en el modelo C4.

### 4.1.1. Design-Level EventStorming.

El Design-Level EventStorming es una técnica de modelado colaborativo que permite analizar y entender en profundidad el dominio de IoBuild. A través de sesiones de trabajo conjunto, esta práctica ayuda a identificar elementos clave como eventos de dominio, comandos, agregados y bounded contexts.

#### 4.1.1.1 Candidate Context Discovery.
El Candidate Context Discovery es el proceso mediante el cual identificamos los posibles bounded contexts dentro del dominio de IoBuild. Este proceso se basa en el análisis de los eventos, comandos y agregados identificados durante las sesiones de EventStorming.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%209.jpg?raw=true)<br>
Representa la frontera administrativa inicial de la plataforma. El flujo muestra a la **Constructora** ejecutando comandos para crear propietarios y asignar departamentos, estableciendo el evento crítico de **Apartamento Asignado**. Además, define la regla de negocio para adquirir unidades adicionales condicionada a la validación de **Fondos Suficientes**.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2010.jpg?raw=true)<br>
Define el límite de seguridad y autenticación. El diagrama expone el proceso donde un usuario inicia un intento de sesión, el sistema verifica las credenciales y, tras validarlas, genera un **Token Acceso**, marcando la sesión como iniciada de forma segura.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2011.jpg?raw=true)<br>
Agrupa todas las interacciones operativas directas con el hardware. El flujo refleja al **Propietario** vinculando nuevos equipos, y ejecutando comandos para encender, apagar o modificar parámetros, lo que genera los eventos de **Estado de Dispositivo Cambio** en el entorno físico.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2012.jpg?raw=true)<br>
Aísla el núcleo de cálculo analítico y procesamiento de telemetría. Se observa al **Sistema de Monitoreo** registrando lecturas de sensores y voltaje para calcular el gasto energético acumulado. El evento pivotal aquí es el **Limite de Energia Superado**, el cual actúa como detonante para emitir alertas automáticas.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2013.jpg?raw=true)<br>
Delimita el módulo encargado de las consultas (*Queries*) del sistema. Ilustra cómo el **Propietario** y la **Constructora** solicitan métricas y datos históricos, lo cual desencadena la generación de un **Reporte de Consumo** y culmina con el evento de **Dashboard Presentado**.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2014.jpg?raw=true)<br>
Muestra un módulo transversal dedicado a la comunicación saliente. El flujo detalla cómo el sistema formatea mensajes de alerta y utiliza canales externos como **Email Provider** y **Push Notification** para despachar la información hasta que la notificación es confirmada por el usuario.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2015.jpg?raw=true)<br>
Representa la capa de valor agregado y optimización autónoma. El diagrama muestra al **Motor IA** recibiendo consultas, analizando patrones de consumo y generando sugerencias de ahorro. Finaliza con un evento de alto impacto donde la IA ejecuta la **Sugerencia Aplicada al Dispositivo** de forma directa.

<br>

![Candidate Context Discovery](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2016.jpg?raw=true)<br>
Enmarca el modelo de negocio financiero de la plataforma. La imagen ilustra a la **Constructora** ingresando un método de pago para procesar la suscripción. El evento de **Suscripción Activada** es la frontera comercial que permite la renovación del acceso al servicio.

<br>

#### 4.1.1.2 Domain Message Flows Modeling.
El Domain Message Flows Modeling mapea cómo los mensajes (eventos, comandos) fluyen entre los diferentes bounded contexts identificados. Este modelado es crucial para entender las dependencias y patrones de comunicación del sistema.

<br>

![Domain Message Flows Modeling](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2017.jpg?raw=true)<br>
Este diagrama ilustra el flujo inicial de habilitación de un usuario en el sistema. Comienza con la **Constructora** ejecutando el comando síncrono para **Asignar Apartamento** dentro del contexto de **Smart Project Setup**. Esto detona un evento asíncrono **Apartamento Asignado** que viaja hacia **Service Execution**, dándole habilitación al **Propietario** para ejecutar el comando de **Vincular dispositivo**. El ciclo concluye cuando Service Execution emite el evento **Dispositivo Vinculado Integration** hacia Energy Management, preparándolo para recibir futuras métricas de ese nuevo hardware.

<br>

![Domain Message Flows Modeling](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2018.jpg?raw=true)<br>
Este diagrama representa el comportamiento reactivo y autónomo del sistema frente a un pico de consumo. Se inicia cuando un **Sensor IoT** envía continuamente el comando **Registrar Lectura** hacia **Energy Management**. Al detectarse una anomalía, este contexto publica el evento **Limite Energía Superado Integration** para despertar al **Smart Assistant**. La IA evalúa la situación y envía un comando de ejecución directa **Aplicar Optimización** hacia **Service Execution and Monitoring**, el cual apaga o regula el actuador y notifica de vuelta a **Energy Management** mediante un evento de cambio de estado.

<br>

![Domain Message Flows Modeling](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Frame%2019.jpg?raw=true)<br>
Esta imagen detalla cómo el usuario interactúa con el hardware utilizando la IA como intermediario contextual. El flujo muestra al **Propietario** utilizando la aplicación para enviar comandos de **Consultar Asistente** y posteriormente **Aceptar Sugerencia** hacia el **Smart Assistant**. Una vez autorizado, el asistente toma el control y manda el comando imperativo de **Modificar Parametros** hacia **Service Execution and Monitoring**. Finalmente, el hardware ejecuta el cambio y emite un evento de **Parametros Configurados Integration** hacia **Energy Management** para ajustar sus cálculos de consumo eléctrico.

<br>

#### 4.1.1.3 Bounded Context Canvases.
Los Bounded Context Canvases proporcionan una visión detallada de cada contexto delimitado, documentando sus responsabilidades, interfaces, eventos y relaciones con otros contextos.

<br>

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Smart%20Project%20Setup.jpg?raw=true)<br>
Esta imagen representa el contrato formal del módulo administrativo e inmobiliario. Se clasifica como un Supporting Domain cuyo rol es gestionar la infraestructura física. El diagrama central mapea su comunicación entrante (los comandos **Asignar Apartamento** de la Constructora y **Adquirir Apartamento** del Propietario) y su comunicación saliente (el evento **Apartamento Asignado Integration Event** dirigido hacia **Service Execution**). En la parte inferior, se documentan las reglas de negocio estrictas, como la validación de fondos y la restricción de que un usuario no puede operar dispositivos sin un departamento formalmente asignado.

<br>

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Service%20Execution%20and%20Monitoring.jpg?raw=true)<br>
Este lienzo expone la arquitectura del núcleo operativo en tiempo real de la plataforma IoT (un **Core Domain**). Define sus roles como **Orquestador de Hardware** y **Ejecutor de Órdenes**. El mapa de dependencias ilustra una alta interacción: recibe comandos físicos (**Vincular**, **Encender/Apagar**) tanto del Propietario como órdenes directas de la IA (**Aplicar Optimización**), y a su vez publica los eventos de **Estado Dispositivo Cambio** hacia los medidores. Sus decisiones de negocio garantizan que todo cambio físico se notifique inmediatamente para no perder precisión en el sistema.

<br>

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Energy%20Management.jpg?raw=true)<br>
Este diagrama delimita el motor analítico y cuantitativo del sistema (también un **Core Domain**). El lienzo muestra que su comunicación entrante se basa en telemetría (**Registrar Lectura Command**) proveniente de los sensores y en los cambios de estado del hardware. Visualmente, destaca que su salida más importante es la emisión del evento **Limite Energía Superado Integration Event** hacia el **asistente inteligente**. Entre sus políticas documentadas se subraya que el procesamiento debe ser asíncrono para evitar cuellos de botella en la red de los condominios.

<br>

![Bounded Context Canvases](https://github.com/F4brizio24/Imagenes-Proyecto/blob/main/Web%20App/Cap%C3%ADtulo%202/CcaritaTech%20-%20BIG%20Picture%20Eventstorming%20-%20Smart%20Assistant.jpg?raw=true)<br>
Este lienzo detalla el módulo de Inteligencia Artificial que aporta valor agregado a la plataforma (**Core Domain**). Establece sus roles como **Optimizador** y **Agente Autónomo**. El diagrama central mapea cómo la IA se alimenta de las alertas de **Energy Management** y de las consultas a demanda del usuario, para luego emitir el comando imperativo de **Aplicar Optimización** hacia Service Execution. En la base del lienzo, consolida decisiones críticas del negocio, como la capacidad del sistema para enviar órdenes de ajuste o apagado preventivo en **Modo Autónomo** sin tener que esperar la aprobación manual del usuario.

<br>

### 4.1.2. Context Mapping.

##### Resumen del Proceso
El Context Mapping es la fase donde definimos las relaciones estructurales y los contratos de comunicación entre nuestros Bounded Contexts. En IoBuild, este proceso se realizó mediante un análisis crítico de dependencias, buscando maximizar la autonomía de los microservicios y proteger el lenguaje ubicuo de cada contexto.

##### Análisis de Alternativas (Exploración de Diseño)

Para llegar a la arquitectura final, el equipo evaluó diversas configuraciones respondiendo a preguntas críticas de diseño:

###### 1. ¿Qué pasaría si movemos la capacidad de "Monitoreo de Umbrales" a Smart Assistant?
* **Análisis:** Si el motor de IA procesara directamente las lecturas de voltaje y sensores, se generaría un acoplamiento masivo de datos innecesarios hacia la IA.
* **Decisión:** Mantenerlo en **Energy Management**. Esto permite que la IA sea reactiva y solo actúe cuando ocurre un evento de negocio relevante (Límite Superado), siguiendo el principio de segregación de responsabilidades.

###### 2. ¿Qué pasaría si creamos un Shared Kernel para la entidad "Propietario"?
* **Análisis:** Aunque todos los contextos usan el concepto de "Propietario", su definición cambia: en *Smart Project Setup* es un titular legal del inmueble; en *Service Execution* es un operador de hardware.
* **Decisión:** Rechazado. Un Shared Kernel crearía un acoplamiento rígido en la base de datos. Se optó por duplicar el ID del propietario y usar una capa de traducción para mantener la autonomía de los modelos.

###### 3. ¿Qué pasaría si aislamos los Core Capabilities y movemos los otros a un contexto aparte?
* **Análisis:** Identificamos que *Smart Project Setup* es un dominio de soporte (SaaS B2B).
* **Decisión:** Se aisló completamente. Al ser Upstream, permite que el "Core IoT" (Execution, Energy, Assistant) evolucione técnicamente sin verse afectado por cambios en las reglas de negocio administrativas de la constructora.

##### Patrones de Relación y Mapa de Contextos

La arquitectura de IoBuild se define bajo una arquitectura orientada a eventos (EDA). A continuación se detallan las relaciones y patrones DDD establecidos:

###### A. Smart Project Setup (Upstream) -> Service Execution (Downstream)
* **Patrón:** **Customer-Supplier / Anti-Corruption Layer (ACL)**.
* **Motivo:** *Service Execution* depende de la información de departamentos asignados. Implementamos una ACL en *Service Execution* para evitar que cambios en el modelo de datos inmobiliario contaminen la lógica de control de dispositivos.

###### B. Service Execution (Upstream) -> Energy Management (Downstream)
* **Patrón:** **Published Language (PL)**.
* **Motivo:** La comunicación es asíncrona y continua. *Service Execution* publica eventos de telemetría en un formato estándar (JSON) que *Energy Management* consume para sus cálculos sin que ambos componentes se acoplen.

###### C. Energy Management (Upstream) -> Smart Assistant (Downstream)
* **Patrón:** **Published Language (PL)**.
* **Motivo:** El asistente se suscribe a eventos de alerta de consumo. La relación es de bajo acoplamiento, permitiendo que el motor de IA evolucione o se actualice sin afectar los medidores de energía.

###### D. Smart Assistant (Upstream) -> Service Execution (Downstream)
* **Patrón:** **Customer-Supplier**.
* **Motivo:** En este flujo de comando, el asistente actúa como el cliente que solicita una acción de ahorro. *Service Execution* actúa como el proveedor de la capacidad física de apagar o regular el actuador correspondiente.

##### Discusión de Alternativas y Conclusión
Tras evaluar modelos de *Conformist* (donde todos se adaptan al modelo de la constructora), el equipo decidió rechazarlo por el alto riesgo de deuda técnica. La aproximación elegida de **Customer-Supplier con ACL** y **Published Language** garantiza que IoBuild sea escalable, permitiendo manejar múltiples dispositivos simultáneamente sin que una falla en un módulo administrativo afecte la inteligencia operativa de la IA o el monitoreo de energía.

<br>

### 4.1.3. Software Architecture.
La arquitectura de software de IoBuild se ha diseñado utilizando el modelo C4, ya que este permite representar el sistema en diferentes niveles de abstracción como Contexto, Contenedores y Despliegue. Gracias a este enfoque, es más sencillo comprender cómo opera la plataforma de forma global, cómo interactúan los usuarios con ella y cómo se vincula con los servicios externos.

Para el diseño de la arquitectura, se han considerado principios clave de ingeniería de software:
- **Separación de responsabilidades:** Cada componente asume funciones delimitadas y cohesivas.
- **Bajo acoplamiento y alta cohesión:** Se minimizan dependencias directas entre módulos y se agrupan capacidades afines.
- **Escalabilidad y mantenibilidad:** Facilidad de evolución independiente entre las aplicaciones cliente y los servicios backend.

#### 4.1.3.1. Software Architecture System Landscape Diagram.
El diagrama de paisaje del sistema (*System Landscape*) dentro de la metodología C4 está concebido para modelar ecosistemas empresariales a gran escala, donde operan múltiples sistemas de software independientes dentro de una misma organización. 

En el caso de **IoBuild**, al tratarse de una plataforma tecnológica autónoma y autocontenida de producto (SaaS B2B/B2C para edificaciones inteligentes), la frontera tecnológica y las interacciones con todos los actores humanos (Ingenieros/Constructores y Propietarios/Residentes) y servicios externos (Cloudinary, OpenAI Chatbot Service y Stripe) se consolidan de manera exhaustiva y sin duplicidades conceptuales directamente en el **Diagrama de Contexto del Sistema (System Context Diagram)** presentado en la sección [4.1.3.2](#4132-software-architecture-context-level-diagrams).

<br>

#### 4.1.3.2. Software Architecture Context Level Diagrams.
El diagrama de contexto presenta el sistema IoBuild como una plataforma central, mostrando cómo interactúa con los usuarios y con distintos sistemas externos. Este nivel permite entender de manera general el alcance del sistema y cómo se integra con otros servicios.

**Enlace del Diagrama de Contexto:** [https://shorturl.at/EbWzU](https://shorturl.at/EbWzU)

<br>

![Context Level Diagrams](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Software%20Architecture%20Context%20Diagram.png)

<br>

**Explicación del Diagrama:**

**Sistema Central (IoBuild):**  
Es la plataforma principal encargada de gestionar proyectos de construcción inteligente. Permite a los usuarios configurar entornos, administrar dispositivos conectados y consultar información relevante como reportes y datos del sistema.

**Usuarios:**
- **Builder (Constructor / Ingeniero):** Usuario encargado de diseñar y parametrizar entornos inteligentes. Interactúa con IoBuild para registrar dispositivos y gestionar proyectos a través de la interfaz web.
- **Landlord / Resident (Propietario / Administrador):** Usuario que utiliza la plataforma para supervisar y administrar sus propiedades o departamentos. Consulta métricas y realiza seguimiento continuo.

**Sistemas Externos:**
- **Cloudinary:** Servicio utilizado para la gestión y almacenamiento seguro de archivos multimedia relacionados con los proyectos.
- **AI Chatbot Service:** Proporciona asistencia inteligente contextual a los usuarios, orientando decisiones de optimización.
- **Stripe:** Pasarela encargada de procesar pagos y gestionar las suscripciones de los clientes en IoBuild.

<br>

#### 4.1.3.3. Software Architecture Container Level Diagrams.
El diagrama de contenedores muestra la arquitectura de alto nivel del sistema IoBuild, permitiendo entender cómo se organizan sus principales componentes ejecutables, qué tecnologías se utilizan y cómo interactúan entre sí.

**Enlace del Diagrama de Contenedores:** [https://shorturl.at/FEOTa](https://shorturl.at/FEOTa)

<br>

![Container Level Diagrams](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Software%20Architecture%20Container%20Diagram.png)

<br>

**Descripción del Container Diagram:**

**Capa de Presentación:**
- **Landing Page:** Sitio público estático que brinda información general y canaliza el acceso hacia la aplicación web.
- **Web App (SPA):** Aplicación web interactiva donde los ingenieros y propietarios gestionan proyectos, dispositivos y telemetría.
- **Mobile Application:** Aplicación móvil que permite el control ágil y remoto de dispositivos y estados de alerta.

**Capa de Backend:**
- **Web Service API:** Backend central desarrollado en ASP.NET Core. Procesa la lógica del negocio, expone endpoints RESTful y gestiona la comunicación con la base de datos y pasarelas externas.

**Capa de Persistencia:**
- **Database (MySQL):** Motor relacional que garantiza persistencia transaccional y consistencia en los datos de usuarios, proyectos y configuraciones.

<br>

#### 4.1.3.4. Software Architecture Deployment Diagrams.
El diagrama de despliegue detalla la distribución de los componentes del sistema IoBuild en la infraestructura cliente y de nube (*Cloud Tier*).

**Enlace del Diagrama de Despliegue:** [https://shorturl.at/2DSHw](https://shorturl.at/2DSHw)

<br>

![Deployment Level Diagrams](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%202/Software%20Architecture%20Deployment%20Diagram.png)

<br>

**Descripción del Deployment Diagram:**

- **Client Tier:** Navegadores web de los usuarios (acceso a Landing Page y Web App) y dispositivos móviles con la aplicación cliente.
- **Cloud Tier (Frontend):** Despliegue en GitHub Pages (Landing Page) y Vercel (Web Application SPA).
- **Cloud Tier (Backend):** Contenedores Docker sobre servidores de aplicación que ejecutan el API en ASP.NET Core con comunicación segura HTTPS.
- **Data Tier:** Servidor de base de datos MySQL para la persistencia centralizada.

<div style="page-break-before: always;"></div>

## 4.2. Tactical-Level Domain-Driven Design.

### Introducción al Diseño Táctico
El Tactical-Level Domain-Driven Design de **IoBuild** representa la materialización concreta del diseño estratégico definido previamente. En esta sección se detalla cómo cada bounded context implementa sus capas Domain, Interface, Application e Infrastructure, así como sus componentes internos, contratos y mecanismos de persistencia. Este enfoque táctico asegura que las decisiones de negocio se traduzcan en una arquitectura modular, desacoplada, mantenible y lista para evolucionar conforme crezca la plataforma.

Para IoBuild se han identificado cuatro bounded contexts principales que cubren las capacidades nucleares de la solución:
1. **Smart Project Setup:** Configuración inicial de proyectos, zonas físicas, planos y perfiles IoT.
2. **Service Execution and Monitoring:** Orquestación operativa de servicios y supervisión de hardware en tiempo real.
3. **Smart Assistant:** Asistencia inteligente contextual y recomendaciones accionables para optimización del confort y habitabilidad.
4. **Energy Management:** Medición, telemetría, análisis de patrones y optimización del consumo energético en las edificaciones.

---

### 4.2.1. Bounded Context: Smart Project Setup.
#### 4.2.1.1. Domain Layer.
En **IoBuild**, este bounded context define cómo se prepara un proyecto inteligente antes de su ejecución operativa. El dominio cubre el modelado del sitio, la selección de perfiles IoT y la configuración de conectividad para dejar el proyecto listo para su despliegue en obra.

**Entities y Aggregates:**
- **SmartProjectSetup (Aggregate Root):** Representa la configuración principal del proyecto (*id, ownerId, projectName, buildingType, status, createdAt, updatedAt*).
- **SiteZone:** Representa un espacio físico del proyecto (piso, ambiente o sector) donde se desplegarán dispositivos.
- **DeviceProfile:** Representa la configuración funcional de un tipo de dispositivo IoT (sensor, intervalo de lectura, umbrales y protocolo).
- **ConnectivityProfile:** Representa la configuración de conectividad del proyecto (gateway, protocolo, credenciales y políticas de reconexión).

**Value Objects:**
- **SetupId, OwnerId, ZoneId, DeviceProfileId, ConnectivityProfileId:** Identificadores únicos del dominio.
- **SetupStatus:** Estado del setup (*DRAFT, VALIDATED, PROVISIONED, ARCHIVED*).
- **BuildingType:** Tipo de edificación (*RESIDENTIAL, COMMERCIAL, INDUSTRIAL, EDUCATIONAL*).
- **SensorType:** Tipo de sensor (*TEMPERATURE, HUMIDITY, OCCUPANCY, ENERGY_METER, AIR_QUALITY*).
- **ProtocolType:** Protocolo de comunicación (*MQTT, HTTP, MODBUS, BACNET*).

**Commands:**
- CreateSmartProjectSetupCommand
- UpdateSmartProjectSetupCommand
- DefineSiteZoneCommand
- UpdateSiteZoneCommand
- AssignDeviceProfileCommand
- ConfigureConnectivityProfileCommand
- ValidateSmartProjectSetupCommand
- ProvisionSmartProjectSetupCommand

**Queries:**
- GetSmartProjectSetupByIdQuery
- GetSmartProjectSetupsByOwnerIdQuery
- GetSetupChecklistByIdQuery
- GetZonesBySetupIdQuery
- GetAvailableDeviceProfilesQuery
- GetConnectivityProfileBySetupIdQuery

**Domain Services (Contratos):**
- SmartProjectSetupCommandService
- SmartProjectSetupQueryService
- ZoneConfigurationCommandService
- DeviceProfileConfigurationService
- SetupValidationService

#### 4.2.1.2. Interface Layer.
La capa de interfaz expone endpoints RESTful para crear y configurar proyectos en IoBuild, registrar zonas del sitio y asignar perfiles técnicos.

**Controllers:**
- **SmartProjectSetupsController:** Create, update, validate, provision y consultas principales del setup.
- **SetupZonesController:** Define y actualiza zonas físicas del proyecto.
- **SetupProfilesController:** Asigna perfiles de dispositivo y configura parámetros de conectividad.

**Resources (Request/Query DTOs):**
- **Setup:** CreateSmartProjectSetupResource, UpdateSmartProjectSetupResource, ValidateSmartProjectSetupResource, ProvisionSmartProjectSetupResource.
- **Zones:** DefineSiteZoneResource, UpdateSiteZoneResource.
- **Profiles:** AssignDeviceProfileResource, ConfigureConnectivityProfileResource.
- **Queries:** GetSmartProjectSetupByIdResource, GetSmartProjectSetupsByOwnerIdResource, GetSetupChecklistByIdResource, GetZonesBySetupIdResource.

**Smart Project Setup Interface Diagram:**  
![Smart Project Setup Interface Diagram](https://instasize.com/api/image/ac46962e9edde3cbfc8e372f387b207c489713181446b1a16f8ce49facd5b3b2.png)

#### 4.2.1.3. Application Layer.
La capa de aplicación orquesta comandos y consultas para preparar el proyecto IoBuild y validar que la configuración cumpla los requisitos mínimos antes del aprovisionamiento.

**Command Handlers:**
- **SmartProjectSetupCommandServiceImpl:** CreateSmartProjectSetupCommand, UpdateSmartProjectSetupCommand, ValidateSmartProjectSetupCommand, ProvisionSmartProjectSetupCommand.
- **ZoneConfigurationCommandServiceImpl:** DefineSiteZoneCommand, UpdateSiteZoneCommand.
- **DeviceProfileConfigurationServiceImpl:** AssignDeviceProfileCommand, ConfigureConnectivityProfileCommand.

**Query Handlers:**
- **SmartProjectSetupQueryServiceImpl:** GetSmartProjectSetupByIdQuery, GetSmartProjectSetupsByOwnerIdQuery, GetSetupChecklistByIdQuery, GetZonesBySetupIdQuery.
- **SetupCatalogQueryServiceImpl:** GetAvailableDeviceProfilesQuery, GetConnectivityProfileBySetupIdQuery.

**Smart Project Setup Application Diagram:**  
![Smart Project Setup Application Diagram](https://instasize.com/api/image/e9c9db4b1c8d1417d7243363b80201317c2b75e261099bf4500fee76ca9d9dea.png)

#### 4.2.1.4. Infrastructure Layer.
La capa de infraestructura implementa la persistencia del setup de IoBuild, incluyendo zonas, perfiles de dispositivos y configuración de conectividad.

**Repositories:**
- **SmartProjectSetupRepository:** Búsquedas por ownerId, status y validaciones por nombre del proyecto.
- **SiteZoneRepository:** Consultas de zonas por setup y validación de nombres repetidos por setup.
- **DeviceProfileRepository:** Catálogo de perfiles por sensor y tipo de edificio.
- **ConnectivityProfileRepository:** Obtención y reemplazo de configuración de conectividad por setup.

**Smart Project Setup Infrastructure Diagram:**  
![Smart Project Setup Infrastructure Diagram](https://instasize.com/api/image/7b5799c5a59f8baa058ce64b7ac8c866100f4a3f54a18da83b6da5bd5d9c55f4.png)

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams.

![Diagram C4 - Smart Project Setup](https://i.imgur.com/EZ0QtVR.png)

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams.
En esta sección se presentan los diagramas de nivel de código para **Smart Project Setup**, cubriendo el modelo del Domain Layer y su persistencia relacional.

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams.

![Diagrama de Clases - Smart Project Setup](https://i.imgur.com/aqFCKUf.png)

##### 4.2.1.6.2. Bounded Context Database Design Diagram.

![Diagrama de Base de Datos - Smart Project Setup](https://i.imgur.com/szDoLl0.png)

---

### 4.2.2. Bounded Context: Service Execution and Monitoring.
#### 4.2.2.1. Domain Layer.
En **IoBuild**, este bounded context gestiona la ejecución operativa de servicios y el monitoreo continuo de su comportamiento. El dominio cubre la orquestación de ejecuciones, el registro de métricas de observabilidad y la gestión de alertas operativas en los dispositivos.

**Entities y Aggregates:**
- **ServiceExecution (Aggregate Root):** Representa una ejecución de servicio (*id, projectId, serviceId, triggerType, status, startedAt, finishedAt, resultSummary*).
- **ExecutionTask:** Representa una tarea interna ejecutada dentro de un flujo de servicio (*id, executionId, taskOrder, command, status, durationMs*).
- **MonitoringMetric:** Representa una medición técnica asociada a una ejecución o servicio (*id, executionId, type, value, unit, timestamp*).
- **ServiceAlert:** Representa una alerta operativa generada por fallos, degradación o umbrales excedidos (*id, projectId, severity, message, resolved, createdAt*).

**Value Objects:**
- **ExecutionId, TaskId, ProjectId, ServiceId, MetricId, AlertId:** Identificadores únicos del dominio.
- **ExecutionStatus:** Estado de ejecución (*QUEUED, RUNNING, SUCCESS, FAILED, CANCELLED, TIMEOUT*).
- **TaskStatus:** Estado de tarea (*PENDING, RUNNING, COMPLETED, FAILED, SKIPPED*).
- **HealthStatus:** Salud del servicio (*HEALTHY, DEGRADED, OFFLINE*).
- **MetricType:** Tipo de métrica (*CPU_USAGE, MEMORY_USAGE, LATENCY, ERROR_RATE, THROUGHPUT*).
- **AlertSeverity:** Severidad de alerta (*INFO, WARNING, CRITICAL*).

##### Domain Behavior and Invariants:
- **ServiceExecution Behavior:** `startExecution()`, `stopExecution()`, `retryExecution()`, `completeExecution()`, `failExecution(reason)`, `registerMonitoringMetric(metric)`, `evaluateServiceHealth()`.
- **Domain Invariants:**
  - Una ejecución solo puede estar en estado *RUNNING* si posee *startTime*.
  - Una ejecución finalizada no puede reiniciarse sin crear una nueva instancia.
  - Las métricas solo pueden registrarse para ejecuciones activas.

##### Domain Events:
- ServiceExecutionStarted
- ServiceExecutionCompleted
- ServiceExecutionFailed
- MonitoringMetricRegistered
- ServiceHealthDegraded
- ServiceAlertRaised
- ServiceAlertResolved

**Commands:**
- StartServiceExecutionCommand
- StopServiceExecutionCommand
- RetryServiceExecutionCommand
- CancelServiceExecutionCommand
- RegisterMonitoringMetricCommand
- UpdateServiceHealthStatusCommand
- RaiseServiceAlertCommand
- ResolveServiceAlertCommand

**Queries:**
- GetExecutionByIdQuery
- GetExecutionsByProjectIdQuery
- GetActiveExecutionsQuery
- GetMetricsByExecutionIdQuery
- GetServiceHealthByProjectIdQuery
- GetOpenAlertsByProjectIdQuery

**Domain Services (Contratos):**
- ServiceExecutionCommandService
- ServiceExecutionQueryService
- MonitoringCommandService
- MonitoringQueryService
- AlertManagementService
- AlertQueryService

#### 4.2.2.2. Interface Layer.
La capa de interfaz expone endpoints RESTful para ejecutar servicios, consultar el estado operativo y administrar alertas del proyecto.

**Controllers:**
- **ServiceExecutionsController:** Start, stop, retry, cancel y consultas de ejecuciones.
- **ServiceMonitoringController:** Registro de métricas y consulta de salud operativa.
- **ServiceAlertsController:** Apertura, resolución y consulta de alertas activas.

**Resources (Request/Query DTOs):**
- **Execution:** StartServiceExecutionResource, StopServiceExecutionResource, RetryServiceExecutionResource, CancelServiceExecutionResource.
- **Monitoring:** RegisterMonitoringMetricResource, UpdateServiceHealthStatusResource.
- **Alerts:** RaiseServiceAlertResource, ResolveServiceAlertResource.
- **Queries:** GetExecutionByIdResource, GetExecutionsByProjectIdResource, GetMetricsByExecutionIdResource, GetServiceHealthByProjectIdResource, GetOpenAlertsByProjectIdResource.

**Service Execution and Monitoring Interface Diagram:**  
![Service Execution and Monitoring Interface Diagram](https://instasize.com/api/image/d237f139e3bd29eea6ef5698a4e4f57140679000ed1d00c23baaec4157afae78.png)

#### 4.2.2.3. Application Layer.
La capa de aplicación orquesta la ejecución de servicios y los procesos de observabilidad para garantizar trazabilidad y control operativo del sistema.

**Command Handlers:**
- **ServiceExecutionCommandServiceImpl:** StartServiceExecutionCommand, StopServiceExecutionCommand, RetryServiceExecutionCommand, CancelServiceExecutionCommand.
- **MonitoringCommandServiceImpl:** RegisterMonitoringMetricCommand, UpdateServiceHealthStatusCommand.
- **AlertManagementServiceImpl:** RaiseServiceAlertCommand, ResolveServiceAlertCommand.

**Query Handlers:**
- **ServiceExecutionQueryServiceImpl:** GetExecutionByIdQuery, GetExecutionsByProjectIdQuery, GetActiveExecutionsQuery.
- **MonitoringQueryServiceImpl:** GetMetricsByExecutionIdQuery, GetServiceHealthByProjectIdQuery.
- **AlertQueryServiceImpl:** GetOpenAlertsByProjectIdQuery.

**Service Execution and Monitoring Application Diagram:**  
![Service Execution and Monitoring Application Diagram](https://instasize.com/api/image/20b81bd5a2eecdf45ebe39b3305e475644b4581e030069c24911def098e3a3c8.png)

#### 4.2.2.4. Infrastructure Layer.
La capa de infraestructura implementa la persistencia de ejecuciones, métricas y alertas para soportar monitoreo histórico y operación en tiempo real.

**Repositories:**
- **ServiceExecutionRepository:** Búsquedas por projectId, estado de ejecución y ejecuciones activas.
- **ExecutionTaskRepository:** Tareas por executionId y estado de tarea.
- **MonitoringMetricRepository:** Métricas por executionId y por tipo de métrica.
- **ServiceAlertRepository:** Alertas por projectId, severidad y estado de resolución.

**Service Execution and Monitoring Infrastructure Diagram:**  
![Service Execution and Monitoring Infrastructure Diagram](https://instasize.com/api/image/6c9a8603ca4cac961870fdedc0c763647510ccd982a43e0e2128bb56cbe5cdd4.png)

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams.

![Diagram C4 - Service Execution and Monitoring](https://i.imgur.com/p8nHO38.png)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams.
En esta sección se presenta el detalle de implementación para **Service Execution and Monitoring**, incluyendo estructura de dominio y modelo de persistencia.

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams.

![Diagrama de Clases - Service Execution and Monitoring](https://i.imgur.com/Ngsgh4D.png)

##### 4.2.2.6.2. Bounded Context Database Design Diagram.

![Diagrama de Base de Datos - Service Execution and Monitoring](https://i.imgur.com/xtReovF.png)

---

### 4.2.3. Bounded Context: Smart Assistant.
#### 4.2.3.1. Domain Layer.
En **IoBuild**, este bounded context implementa la asistencia inteligente contextual para apoyar decisiones operativas. El dominio cubre conversaciones asistidas, generación de recomendaciones técnicas y construcción de planes de acción sobre eventos del proyecto.

**Entities y Aggregates:**
- **AssistantConversation (Aggregate Root):** Representa una sesión conversacional asociada a un proyecto (*id, projectId, userId, channel, status, startedAt, closedAt*).
- **AssistantMessage:** Representa cada mensaje de una conversación (*id, conversationId, role, content, metadataJson, sentAt*).
- **AssistantRecommendation:** Representa una recomendación accionable generada por el asistente para optimizar operación, mantenimiento o rendimiento.
- **AssistantActionPlan:** Representa el plan de acción derivado de una recomendación, con pasos, prioridad y estado de ejecución sugerido.

**Value Objects:**
- **ConversationId, MessageId, RecommendationId, ActionPlanId, ProjectId, UserId:** Identificadores únicos del dominio.
- **ConversationStatus:** Estado de conversación (*OPEN, WAITING_CONTEXT, RESOLVED, CLOSED*).
- **MessageRole:** Rol del mensaje (*USER, ASSISTANT, SYSTEM*).
- **AssistantChannel:** Canal de interacción (*WEB_CHAT, MOBILE_CHAT, API*).
- **RecommendationType:** Tipo de recomendación (*ALERT_TRIAGE, SERVICE_TUNING, ENERGY_OPTIMIZATION, MAINTENANCE*).
- **RecommendationPriority:** Prioridad (*LOW, MEDIUM, HIGH, CRITICAL*).

##### Domain Behavior and Invariants:
- **AssistantConversation Behavior:** `startConversation()`, `receiveUserMessage()`, `generateAssistantResponse()`, `closeConversation()`, `createRecommendation()`.
- **Domain Invariants:**
  - Una conversación en estado *CLOSED* no acepta nuevos mensajes.
  - Toda recomendación debe estar asociada a una conversación activa.
  - Los planes de acción solo pueden generarse a partir de recomendaciones existentes.

##### Domain Events:
- AssistantConversationStarted
- AssistantMessageReceived
- AssistantResponseGenerated
- AssistantRecommendationGenerated
- AssistantActionPlanCreated

**Commands:**
- StartAssistantConversationCommand
- SendUserMessageCommand
- GenerateAssistantResponseCommand
- CloseAssistantConversationCommand
- CreateAssistantRecommendationCommand
- AcceptAssistantRecommendationCommand
- DismissAssistantRecommendationCommand
- GenerateAssistantActionPlanCommand

**Queries:**
- GetConversationByIdQuery
- GetConversationsByProjectIdQuery
- GetConversationMessagesQuery
- GetRecommendationsByProjectIdQuery
- GetPendingRecommendationsQuery
- GetActionPlanByRecommendationIdQuery

**Domain Services (Contratos):**
- AssistantConversationCommandService
- AssistantConversationQueryService
- AssistantRecommendationCommandService
- AssistantRecommendationQueryService
- AssistantActionPlanCommandService
- AssistantActionPlanQueryService

#### 4.2.3.2. Interface Layer.
La capa de interfaz expone endpoints RESTful para interactuar con el asistente, administrar recomendaciones y consultar planes de acción.

**Controllers:**
- **AssistantConversationsController:** Inicio de conversación, envío de mensajes, cierre y consultas de historial.
- **AssistantRecommendationsController:** Creación, aceptación, descarte y consulta de recomendaciones.
- **AssistantActionPlansController:** Generación y consulta de planes de acción asociados a recomendaciones.

**Resources (Request/Query DTOs):**
- **Conversations:** StartAssistantConversationResource, SendUserMessageResource, GenerateAssistantResponseResource, CloseAssistantConversationResource.
- **Recommendations:** CreateAssistantRecommendationResource, AcceptAssistantRecommendationResource, DismissAssistantRecommendationResource.
- **Action Plans:** GenerateAssistantActionPlanResource.
- **Queries:** GetConversationByIdResource, GetConversationsByProjectIdResource, GetConversationMessagesResource, GetRecommendationsByProjectIdResource, GetPendingRecommendationsResource, GetActionPlanByRecommendationIdResource.

**Smart Assistant Interface Diagram:**  
![Smart Assistant Interface Diagram](https://instasize.com/api/image/f00d4edcae97cb8e384659f46342e12d43ad825eec9ea7cdeaf51d53e584f900.png)

#### 4.2.3.3. Application Layer.
La capa de aplicación orquesta la interacción del asistente con el contexto del proyecto para responder consultas, generar recomendaciones y proponer planes accionables.

**Command Handlers:**
- **AssistantConversationCommandServiceImpl:** StartAssistantConversationCommand, SendUserMessageCommand, GenerateAssistantResponseCommand, CloseAssistantConversationCommand.
- **AssistantRecommendationCommandServiceImpl:** CreateAssistantRecommendationCommand, AcceptAssistantRecommendationCommand, DismissAssistantRecommendationCommand.
- **AssistantActionPlanCommandServiceImpl:** GenerateAssistantActionPlanCommand.

**Query Handlers:**
- **AssistantConversationQueryServiceImpl:** GetConversationByIdQuery, GetConversationsByProjectIdQuery, GetConversationMessagesQuery.
- **AssistantRecommendationQueryServiceImpl:** GetRecommendationsByProjectIdQuery, GetPendingRecommendationsQuery.
- **AssistantActionPlanQueryServiceImpl:** GetActionPlanByRecommendationIdQuery.

**Smart Assistant Application Diagram:**  
![Smart Assistant Application Diagram](https://instasize.com/api/image/c1e93fdfadf169bc27b0c35f392c880a7e7cf8277875b5ca32146081bf2f4cae.png)

#### 4.2.3.4. Infrastructure Layer.
La capa de infraestructura implementa la persistencia de conversaciones, mensajes, recomendaciones y planes de acción para asegurar la trazabilidad de la asistencia inteligente.

**Repositories:**
- **AssistantConversationRepository:** Consultas por projectId, estado de conversación y usuario.
- **AssistantMessageRepository:** Historial de mensajes por conversationId y orden cronológico.
- **AssistantRecommendationRepository:** Recomendaciones por proyecto, prioridad y estado de aceptación.
- **AssistantActionPlanRepository:** Planes de acción por recommendationId.

**Smart Assistant Infrastructure Diagram:**  
![Smart Assistant Infrastructure Diagram](https://instasize.com/api/image/30c135e534c0d290f7f1eb2b52a4639e2d8ea4d833724136d9d91420f37e6c99.png)

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams.

![Diagram C4 - Smart Assistant](https://i.imgur.com/AQmKgPv.png)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams.
En esta sección se presenta el nivel de código del bounded context **Smart Assistant**, incluyendo su modelo de dominio y esquema de base de datos.

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams.

![Diagrama de Clases - Smart Assistant](https://i.imgur.com/nHDNIB3.png)

##### 4.2.3.6.2. Bounded Context Database Design Diagram.

![Diagrama de Base de Datos - Smart Assistant](https://i.imgur.com/2b7dggg.png)

---

### 4.2.4. Bounded Context: Energy Management.
#### 4.2.4.1. Domain Layer.
En **IoBuild**, este bounded context gestiona la medición, análisis y optimización del consumo energético de los edificios inteligentes. El dominio cubre planes de optimización, registro de consumo, detección de anomalías y eventos de respuesta a la demanda.

**Entities y Aggregates:**
- **EnergyOptimizationPlan (Aggregate Root):** Representa el plan de optimización energética de un proyecto (*id, projectId, baselineKwh, reductionTargetPercent, status, windowStart, windowEnd, createdAt*).
- **EnergyConsumptionRecord:** Representa una lectura de consumo energético por zona, medidor y período de tiempo (*id, energyPlanId, projectId, zoneId, meterId, value, unit, period, recordedAt*).
- **EnergyAnomaly:** Representa una desviación del patrón esperado de consumo como picos, sobrecargas o caídas (*id, energyPlanId, projectId, zoneId, severity, detectedPattern, acknowledged, detectedAt*).
- **DemandResponseEvent:** Representa un evento operativo para ajustar la carga eléctrica en períodos críticos (*id, energyPlanId, projectId, eventName, status, startsAt, endsAt*).

**Value Objects:**
- **EnergyPlanId, ConsumptionRecordId, AnomalyId, ResponseEventId, ProjectId, ZoneId, MeterId:** Identificadores únicos del dominio.
- **OptimizationStatus:** Estado del plan (*DRAFT, ACTIVE, PAUSED, COMPLETED, CANCELLED*).
- **ConsumptionPeriod:** Granularidad de lectura (*HOURLY, DAILY, WEEKLY, MONTHLY*).
- **EnergyUnit:** Unidad de energía (*WH, KWH, MWH*).
- **AnomalySeverity:** Severidad de anomalía (*LOW, MEDIUM, HIGH, CRITICAL*).
- **DemandResponseStatus:** Estado del evento de respuesta (*CREATED, IN_PROGRESS, EXECUTED, FAILED, CLOSED*).

##### Domain Behavior and Invariants:
- **EnergyOptimizationPlan Behavior:** `activate()`, `pause()`, `complete()`, `recordConsumption(record)`, `detectAnomaly(anomaly)`, `triggerDemandResponse(event)`.
- **Domain Invariants:**
  - El objetivo de reducción de energía (`reductionTargetPercent`) debe ser un valor porcentual positivo menor al 100%.
  - No se pueden registrar lecturas de consumo con marcas de tiempo futuras.
  - Una anomalía no puede ser marcada como reconocida (`acknowledged`) sin registrar la identidad del operador o regla responsable.

##### Domain Events:
- EnergyOptimizationPlanCreated
- EnergyOptimizationPlanActivated
- EnergyConsumptionRecorded
- EnergyAnomalyDetected
- DemandResponseEventTriggered
- EnergySavingsTargetAchieved

**Commands:**
- CreateEnergyOptimizationPlanCommand
- ActivateEnergyOptimizationPlanCommand
- PauseEnergyOptimizationPlanCommand
- RegisterEnergyConsumptionCommand
- DetectEnergyAnomalyCommand
- AcknowledgeEnergyAnomalyCommand
- CreateDemandResponseEventCommand
- CompleteDemandResponseEventCommand

**Queries:**
- GetOptimizationPlanByIdQuery
- GetOptimizationPlansByProjectIdQuery
- GetConsumptionByProjectIdQuery
- GetConsumptionByZoneIdQuery
- GetEnergyAnomaliesByProjectIdQuery
- GetActiveDemandResponseEventsQuery
- GetEnergySavingsSummaryByProjectIdQuery

**Domain Services (Contratos):**
- EnergyOptimizationCommandService
- EnergyOptimizationQueryService
- EnergyMonitoringCommandService
- EnergyMonitoringQueryService
- DemandResponseCommandService
- DemandResponseQueryService
- EnergySavingsAnalysisService

#### 4.2.4.2. Interface Layer.
La capa de interfaz expone endpoints RESTful para crear planes de optimización, registrar consumo, gestionar anomalías y ejecutar eventos de respuesta a la demanda.

**Controllers:**
- **EnergyOptimizationPlansController:** Creación, activación, pausa y consultas de planes de optimización.
- **EnergyMonitoringController:** Registro de consumo, detección/revisión de anomalías y consultas operativas.
- **DemandResponseController:** Apertura, cierre y consulta de eventos de respuesta a la demanda.

**Resources (Request/Query DTOs):**
- **Optimization:** CreateEnergyOptimizationPlanResource, ActivateEnergyOptimizationPlanResource, PauseEnergyOptimizationPlanResource.
- **Monitoring:** RegisterEnergyConsumptionResource, DetectEnergyAnomalyResource, AcknowledgeEnergyAnomalyResource.
- **Demand Response:** CreateDemandResponseEventResource, CompleteDemandResponseEventResource.
- **Queries:** GetOptimizationPlanByIdResource, GetOptimizationPlansByProjectIdResource, GetConsumptionByProjectIdResource, GetConsumptionByZoneIdResource, GetEnergyAnomaliesByProjectIdResource, GetActiveDemandResponseEventsResource, GetEnergySavingsSummaryByProjectIdResource.

**Energy Management Interface Diagram:**  
![Energy Management Interface Diagram](https://instasize.com/api/image/3be25a2e254b035f27c7ecdb7b05bb59883da84db0dbb2b70a1b26ef89bff79b.png)

#### 4.2.4.3. Application Layer.
La capa de aplicación orquesta comandos y consultas para convertir datos de consumo en decisiones operativas de eficiencia energética.

**Command Handlers:**
- **EnergyOptimizationCommandServiceImpl:** CreateEnergyOptimizationPlanCommand, ActivateEnergyOptimizationPlanCommand, PauseEnergyOptimizationPlanCommand.
- **EnergyMonitoringCommandServiceImpl:** RegisterEnergyConsumptionCommand, DetectEnergyAnomalyCommand, AcknowledgeEnergyAnomalyCommand.
- **DemandResponseCommandServiceImpl:** CreateDemandResponseEventCommand, CompleteDemandResponseEventCommand.

**Query Handlers:**
- **EnergyOptimizationQueryServiceImpl:** GetOptimizationPlanByIdQuery, GetOptimizationPlansByProjectIdQuery.
- **EnergyMonitoringQueryServiceImpl:** GetConsumptionByProjectIdQuery, GetConsumptionByZoneIdQuery, GetEnergyAnomaliesByProjectIdQuery, GetEnergySavingsSummaryByProjectIdQuery.
- **DemandResponseQueryServiceImpl:** GetActiveDemandResponseEventsQuery.

**Energy Management Application Diagram:**  
![Energy Management Application Diagram](https://instasize.com/api/image/5bb792141cfabc4249c13bd8e17c84a6a90107bd2fd33d9f018e89a5e9a35127.png)

#### 4.2.4.4. Infrastructure Layer.
La capa de infraestructura implementa persistencia de planes de optimización, lecturas de consumo, anomalías y eventos de respuesta para soportar analítica histórica y operación en tiempo real.

**Repositories:**
- **EnergyOptimizationPlanRepository:** Planes por projectId, estado de optimización y planes activos.
- **EnergyConsumptionRecordRepository:** Lecturas por projectId, zoneId, meterId y rango temporal.
- **EnergyAnomalyRepository:** Anomalías por proyecto, severidad y estado abierto/cerrado.
- **DemandResponseEventRepository:** Eventos por proyecto, estado y eventos activos.

**Energy Management Infrastructure Diagram:**  
![Energy Management Infrastructure Diagram](https://instasize.com/api/image/ebde2d543f68889ecb0ca0460f113851d31f2dafc5549e80d83402882b863d54.png)

##### AI Integration Anti-Corruption Layer (ACL):
Para evitar el acoplamiento directo con proveedores externos de inteligencia artificial, el sistema define la interfaz de dominio `AssistantAIService`. En la capa de infraestructura se implementan los adaptadores `OpenAIAssistantAdapter` y `ExternalLLMAdapter`, protegiendo el modelo de dominio ante evoluciones tecnológicas del proveedor.

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams.

![Diagram C4 - Energy Management](https://i.imgur.com/XKGyZ20.png)

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams.
En esta sección se presenta el detalle de implementación de **Energy Management** a nivel de clases de dominio y persistencia relacional.

##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams.

![Diagrama de Clases - Energy Management](https://i.imgur.com/VxFxqqC.png)

##### 4.2.4.6.2. Bounded Context Database Design Diagram.

![Diagrama de Base de Datos - Energy Management](https://i.imgur.com/bxwcuZp.png)

<div style="page-break-before: always;"></div>

# Capítulo V: Solution UX/UI Design
## 5.1. Style Guidelines.
### 5.1.1. General Style Guidelines.

En esta sección definimos los principios visuales y de interacción que rigen toda la experiencia **IoBuild**, asegurando coherencia entre la Landing Page y la Plataforma Web de gestión IoT. Establecemos una identidad visual clara mediante el uso coordinado de una paleta de colores moderna, tipografía de alta legibilidad, iconografía consistente (PrimeIcons), espaciado estructurado en múltiplos de 8px y un tono comunicacional unificado orientado al sector inmobiliario y a los residentes.

### 5.1.2. Web, Mobile and IoT Style Guidelines.

#### **Tipografía**
La tipografía seleccionada para los encabezados de nuestra marca es **Poppins**, debido a su estilo moderno, geométrico y limpio. Su diseño elegante permite destacar títulos y secciones importantes, generando un impacto claro y atractivo para los usuarios en la Landing Page.

Para la aplicación web de gestión (`iobuild-remix.arroz.dev`) y el cuerpo de texto general, se implementa **Inter** y **Roboto**, tipografías líderes en legibilidad en pantallas digitales, interfaces densas de datos (tablas, métricas, dashboards) y visualización de telemetría IoT. Su diseño asegura una experiencia de lectura cómoda y precisa tanto en tarjetas de métricas como en formularios complejos.

Los tamaños tipográficos definidos, desde los **12px (0.75rem)** para detalles secundarios y badges de estado hasta los **36px (2.25rem)** para títulos principales de sección, garantizan una jerarquía visual clara y ordenada.

#### **Colores**
La elección de la paleta de colores en nuestro proyecto obedece a una estrategia visual cuidadosamente planificada, orientada a reflejar tecnología, sostenibilidad, confianza y sofisticación, valores fundamentales en la propuesta de **IoBuild**.

- **Landing Page & Web App** <br>
  ![Imagen de la paleta de colores del landing page](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Paleta_Colores.png)

En la identidad visual, el color **verde menta/esmeralda primario (#10B981)** cumple el rol principal como color distintivo de la marca. Su tono fresco y vibrante transmite innovación, eficiencia energética y confianza, características que refuerzan la propuesta de valor de nuestro proyecto. Al mismo tiempo, este color genera una sensación positiva y cercana, lo que ayuda a establecer una conexión emocional con el usuario desde el primer contacto.

Para lograr versatilidad y equilibrio, se incorporan dos variaciones del color primario. El color **menta claro (#ECFDF5)** se utiliza en fondos, badges de estado activo y áreas de descanso visual, ofreciendo luminosidad y amplitud sin perder coherencia cromática. Por su parte, el color **menta oscuro (#059669)** se reserva para contrastes activos, botones principales en hover y llamadas a la acción críticas.

En cuanto a la gama neutra, el **gris muy claro / canvas (#F8FAFC / #F9FAFB)** funciona como base para pantallas y secciones de contenido del dashboard y módulos de administración. En contraste, el **slate oscuro (#0F172A / #111827)** se emplea en títulos, encabezados, barra superior y áreas que requieren solidez visual.

Para complementar la lectura, el sistema tipográfico integra dos niveles de color en los textos. El **texto primario (#0F172A / #111827)**, de alto contraste sobre fondos claros, asegura una comprensión inmediata y sin esfuerzo. En paralelo, el **texto secundario (#64748B / #6B7280)** se aplica en descripciones de proyectos, subtítulos de métricas y anotaciones secundarias.

En conjunto, esta paleta de verdes esmeralda combinados con slates neutros y acentos bien definidos construye una interfaz clara, fresca y profesional. La coherencia cromática no solo mejora la experiencia de usuario, sino que también refuerza los valores de accesibilidad, confianza y modernidad que IoBuild desea transmitir.

#### **Lenguaje**
En IoBuild, utilizaremos un lenguaje que refleje nuestra visión de transformar la construcción residencial mediante la integración inteligente de tecnología desde el diseño. Queremos conectar tanto con constructoras y desarrolladores como con los futuros propietarios, manteniendo siempre una comunicación clara, cercana y profesional. La combinación de tonos que emplearemos es la siguiente:

1. **Profesional pero accesible:** Nuestro objetivo es transmitir seriedad y conocimiento en la aplicación de soluciones tecnológicas a la construcción, sin dejar de ser comprensibles para todos los actores involucrados. Nuestro lenguaje estará planteado de manera clara y cercana, de modo que tanto expertos como clientes puedan comprender el valor de nuestra propuesta sin barreras.

2. **Formal pero cálido:** Si bien mantenemos un tono formal que exprese compromiso, seguridad y confiabilidad, también buscamos acercarnos a nuestros usuarios de una manera humana y auténtica. Queremos que desarrolladores y propietarios sientan que IoBuild no solo ofrece tecnología, sino también acompañamiento y confianza en cada etapa del proceso.

3. **Respetuoso y empático:** Reconocemos la diversidad de necesidades en el sector, desde constructoras que buscan eficiencia hasta propietarios que desean hogares adaptables y modernos. Nuestro lenguaje transmitirá respeto, promoviendo una relación colaborativa y de apoyo mutuo.

4. **Inspirador y optimista:** En IoBuild creemos que el futuro de la construcción es más sostenible, adaptable y tecnológico. Por ello, nos comunicaremos con entusiasmo y convicción, motivando a nuestros usuarios a visualizar y construir una nueva forma de habitar hogares inteligentes.

## 5.2. Information Architecture.

UX Heuristics & Principles Evaluation<br>
Usability – Inclusive Design – Information Architecture<br>
CARRERA: Ingeniería de Software<br>
CURSO: Desarrollo de Soluciones IOT<br>
NRC: 3687<br>
PROFESOR: Jimmy Enrique Sanchez Portugal<br>
CLIENTE(S): Javier Maximo Ordoñez Cordova, Christy Karen Callata Alvarez<br>
SITE o APP A EVALUAR: IoBuild (Landing Page & Plataforma Web IoT)

TAREAS A EVALUAR:<br>
El alcance de esta evaluación contempla el análisis de la usabilidad en la ejecución de las siguientes tareas:<br>

Segmento Objetivo #1: Arquitectos e Ingenieros Civiles
- **Configurar funcionalidades inteligentes:** Claridad y facilidad para integrar automatización (iluminación, climatización, seguridad, riego, etc.) dentro de la plataforma.
- **Gestionar proyectos y roles técnicos:** Facilidad para asignar permisos y colaborar con otros profesionales dentro del mismo entorno.
- **Acceder a documentación y guías técnicas:** Disponibilidad, organización y comprensión de recursos de soporte (manuales, tutoriales, BIM).

Segmento Objetivo #2: Dueños de Apartamentos (Usuarios Finales)
- **Controlar dispositivos desde un único panel:** Usabilidad de la interfaz centralizada para manejar iluminación, clima, seguridad y energía.
- **Recibir notificaciones y alertas personalizadas:** Facilidad para activar, modificar y entender las notificaciones sobre consumo energético o seguridad.
- **Acceder a reportes de consumo y eficiencia:** Claridad de la información mostrada y utilidad para la toma de decisiones sobre ahorro energético.

### 5.2.1. Organization Systems.

Dentro del diseño de interfaces digitales enfocadas en el usuario, el Organization System funciona como la base de la arquitectura de información, definiendo cómo se ordenan, agrupan y muestran los contenidos en la plataforma. Su propósito es facilitar la comprensión y la navegación, permitiendo que los usuarios encuentren de manera sencilla la propuesta de valor y los recursos más importantes. Este sistema ayuda a disminuir la carga mental, dirigir la atención hacia lo esencial y mejorar la experiencia general de interacción con el producto.

En el caso de IoBuild, la Landing Page implementa un sistema de organización jerárquico y temático, pensado para comunicar de forma clara el propósito de la aplicación y dirigir la acción del visitante. La estructura se organiza en bloques que siguen una lógica de prioridad: en primer lugar, se despliega un hero section con un mensaje directo sobre la propuesta de valor y un llamado a la acción destacado (“Explora IoBuild”), seguido de secciones que detallan los beneficios de la plataforma para arquitectos, ingenieros y propietarios de viviendas. Posteriormente, se integran apartados complementarios como la presentación del equipo, los objetivos del proyecto y los canales de contacto.

Tanto el header como el footer refuerzan esta organización al centralizar los accesos principales de navegación (inicio, características, contacto) y los secundarios (redes sociales y enlaces informativos). Esta disposición garantiza que los usuarios comprendan de manera inmediata qué es IoBuild, para quién está dirigido y cómo pueden empezar a interactuar con la solución. Además, la página aplica principios como la progressive disclosure y el diseño responsivo, asegurando una experiencia fluida y clara en dispositivos móviles y de escritorio.

### 5.2.2. Labeling Systems.

En el marco del diseño de la arquitectura de información, los Labeling Systems cumplen la función de comunicar de forma clara, coherente y predecible los elementos de interacción presentes en la interfaz. En IoBuild, cada etiqueta textual utilizada en botones, menús, enlaces y secciones está orientada a guiar al usuario en su recorrido por la Landing Page, facilitando la comprensión del propósito del proyecto y motivando la interacción con los elementos principales.

La siguiente tabla resume las etiquetas implementadas, su ubicación y su función en la experiencia de usuario:

| Etiqueta | Ubicación/Componente | Función |
|----------|----------------------|---------|
| Inicio | Header | Enlace a la página principal. Término estándar y familiar para usuarios. |
| Sobre Nosotros | Header | Presentación del propósito y misión del proyecto. Genera cercanía y confianza. |
| Equipo | Header | Sección dedicada al grupo desarrollador, destacando transparencia y credibilidad. |
| Contacto | Header | Canal directo para comunicación con el equipo. Claro y orientado a la acción. |
| Explora IoBuild | Hero Section (CTA principal) | Llamada a la acción inmediata para iniciar interacción con la plataforma. Imperativo motiva al usuario. |
| Objetivos | Sección informativa | Describe las metas del proyecto. Etiqueta concisa y orientada al valor. |
| Proyecto | Sección informativa | Explica en detalle la propuesta tecnológica. Término claro y descriptivo. |
| Contáctanos | Footer | Refuerzo del canal de comunicación, mantiene consistencia semántica. |
| Síguenos | Footer / Redes sociales | Agrupa accesos a redes sociales. Etiqueta convencional y reconocida globalmente. |
| IoBuild | Marca | Nombre distintivo en mayúsculas. Actúa como ancla visual e identitaria del sitio. |

El sistema de etiquetado en la Landing Page de IoBuild refleja una aplicación consistente de principios de usabilidad y arquitectura de información. Las etiquetas emplean un lenguaje simple, reconocible y orientado a la acción, lo que facilita tanto la navegación como la comprensión inmediata de los contenidos. Asimismo, existe una coherencia semántica entre el header, el cuerpo de la página y el footer, acompañada de un uso de imperativos y sustantivos comunes que refuerzan la accesibilidad cognitiva. Este Labeling System contribuye a la claridad, consistencia y escalabilidad de la experiencia web, garantizando que tanto profesionales técnicos como usuarios finales puedan interactuar sin fricciones con la plataforma.

### 5.2.3. SEO Tags and Meta Tags.

Los meta tags y etiquetas SEO son elementos esenciales dentro de la sección <head> de cualquier página web, ya que permiten definir cómo es interpretado, indexado y presentado el contenido de un sitio por parte de los motores de búsqueda (como Google) y las redes sociales (como Facebook, Twitter o LinkedIn). Aunque estos elementos no son visibles de forma directa para los usuarios, desempeñan un papel crucial en el posicionamiento orgánico, en la forma en que los enlaces se muestran al compartirse y en la claridad con la que se comunica la propuesta de valor del sitio.

En el caso de la Landing Page de IoBuild, se han incorporado meta etiquetas específicas con el objetivo de optimizar la indexación y visibilidad de la plataforma. La meta descripción resume de manera breve y clara la propuesta de IoBuild como una solución tecnológica orientada a la gestión y personalización de espacios inteligentes. Asimismo, se han definido meta keywords que incluyen términos relevantes como IoT, domótica, arquitectura inteligente, automatización de espacios y gestión de hogares inteligentes, lo que refuerza la capacidad del sitio para aparecer en búsquedas relacionadas.

#### 1. Index
La página principal de IoBuild incorpora un conjunto de etiquetas SEO que fortalecen su posicionamiento y presencia digital. Se incluyen una meta descripción clara sobre la propuesta de valor, palabras clave relacionadas con IoT y automatización residencial, así como etiquetas Open Graph y Twitter Card que aseguran una visualización atractiva y coherente al compartir el sitio en redes sociales. Estas configuraciones, junto con el ajuste de vista responsiva y la codificación adecuada, contribuyen a una experiencia accesible, profesional y optimizada para buscadores y usuarios.
![Imagen de Meta Tags Index](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Meta_Tags_Index.png)

#### 2. About Us
La página Sobre Nosotros de IoBuild incluye etiquetas SEO básicas que refuerzan su propósito informativo y de marca. Se define un título claro y directo, junto con una meta descripción que comunica la misión del proyecto y presenta al equipo como motor de la propuesta de innovación en la industria de la construcción mediante tecnología IoT. Además, se configuran los parámetros técnicos de codificación (UTF-8) y de vista responsiva, asegurando accesibilidad, correcta interpretación del contenido y una experiencia de navegación óptima en distintos dispositivos.
![Imagen de Meta Tags About-Us](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Meta_Tags_AboutUs.png)

#### 3. FAQ
La página FAQ - Preguntas Frecuentes de IoBuild incorpora etiquetas SEO orientadas a brindar claridad y accesibilidad al usuario. Se define un título descriptivo y directo que comunica de inmediato el propósito de la sección, acompañado de una meta descripción que resume su función como espacio de resolución de dudas sobre la plataforma SaaS y sus aplicaciones en proyectos de construcción con IoT. Asimismo, se incluyen configuraciones técnicas esenciales como la codificación UTF-8 y la vista responsiva, garantizando una correcta interpretación del contenido y una experiencia de navegación fluida en diversos dispositivos.
![Imagen de Meta Tags FAQ](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Meta_Tags_FAQ.png)

### 5.2.4. Searching Systems.

Al ingresar a la landing page de IoBuild, el usuario será recibido con una sección principal que introduce la propuesta de valor de la plataforma, acompañada de un botón destacado que invita a conocer más sobre sus funcionalidades. En la parte superior, la navegación se organiza mediante un menú claro y accesible que permite desplazarse hacia las secciones clave, como Sobre Nosotros, Preguntas Frecuentes y Contacto. Esta estructura busca brindar una experiencia fluida y ordenada, evitando confusiones y facilitando el acceso a la información más relevante.

La navegación está reforzada con etiquetas descriptivas, jerarquía visual y un diseño responsivo, de manera que el usuario siempre tenga claridad sobre en qué parte del sitio se encuentra y cómo puede avanzar o retroceder dentro del flujo. El enfoque de la interfaz prioriza la simplicidad y la claridad, asegurando que el visitante pueda comprender rápidamente la misión de IoBuild y decidir explorar más a fondo sus soluciones tecnológicas.

### 5.2.5. Navigation Systems.

La navegación es un elemento central en la landing page de IoBuild, ya que estructura el recorrido del usuario y facilita el acceso a la información clave sobre la plataforma. Bajo principios de simplicidad, accesibilidad y jerarquía visual, el sistema de navegación ha sido diseñado para garantizar una experiencia clara e intuitiva, tanto en dispositivos de escritorio como en móviles.

IoBuild implementa un sistema de navegación global, persistente y horizontal, ubicado en la parte superior de la página. Este está compuesto por siete elementos principales:
- **Home:** vinculado al logotipo de IoBuild, que permite regresar a la página de inicio desde cualquier sección.
- **Beneficios:** apartado que resalta las ventajas concretas para constructoras y propietarios.
- **Características:** detalle funcional de la plataforma.
- **Planes:** presenta las opciones comerciales y niveles de servicio adecuados para distintos tamaños de proyecto.
- **Sobre Nosotros:** ofrece información acerca de la misión, visión y equipo detrás del proyecto.
- **FAQ:** presenta un apartado de preguntas frecuentes que resuelve las dudas más comunes de los usuarios.
- **Empezar ahora (CTA):** botón destacado que impulsa la conversión (registro o contacto para proyecto), visualmente diferenciado del resto de enlaces.

El diseño del header utiliza un fondo uniforme y elementos textuales de alto contraste, siguiendo un estilo minimalista que evita distracciones y centra la atención en las decisiones de navegación. La organización de los enlaces sigue una estructura en tres zonas: el logotipo alineado a la izquierda, las secciones principales al centro y las acciones de contacto alineadas a la derecha.

En cuanto a adaptabilidad, la barra de navegación está construida bajo un enfoque mobile-first, ajustándose dinámicamente a distintas resoluciones. En pantallas pequeñas, el menú horizontal se convierte en un menú tipo hamburguesa, asegurando que todas las secciones permanezcan accesibles sin comprometer la usabilidad.

Finalmente, la navegación en IoBuild cumple con principios fundamentales de usabilidad:
- **Claridad:** los enlaces son directos y fácilmente identificables.
- **Consistencia:** la barra se mantiene visible y uniforme en todo momento.
- **Jerarquía:** las secciones más consultadas están ubicadas estratégicamente en el centro de la navegación.
- **Retroalimentación visual:** se incluyen estados hover y focus que refuerzan la interacción del usuario.

## 5.3. Landing Page UI Design.

La sección de Landing Page UI Design busca definir, estructurar y validar la interfaz visual de la página principal de IoBuild, garantizando una experiencia clara, accesible y centrada en los distintos perfiles de usuario interesados en soluciones IoT para la construcción. Para esta fase se diseñaron los primeros wireframes, los cuales permitieron organizar los contenidos clave como la propuesta de valor de la plataforma, los beneficios, características principales, planes de servicio, sección “Sobre Nosotros”, preguntas frecuentes y un footer con enlaces a contacto y redes sociales. Posteriormente, se elaboraron mockups de alta fidelidad aplicando un sistema de diseño minimalista y funcional, priorizando la jerarquía informativa, la coherencia visual y la consistencia entre dispositivos.


El sitio web de "lobuild" está construido como un viaje lógico y persuasivo, diseñado para guiar a un potencial cliente desde la primera impresión hasta la conversión final, construyendo valor y confianza en cada paso.

El recorrido comienza en la sección de inicio, que capta la atención de inmediato con un titular audaz: "Revoluciona Tus Proyectos Residenciales". Esta primera sección establece la propuesta de valor central, explicando que la plataforma beneficia tanto a los administradores (con gestión centralizada) como a los futuros propietarios (con control personalizado), posicionándose como una solución integral desde el principio.

A continuación, la sección "¿Por qué elegir ioBuild?" profundiza en esta promesa inicial, desglosándola en seis beneficios claros y tangibles. Aborda directamente las motivaciones del cliente, hablando de valor agregado para el proyecto, ahorro de energía, y una integración desde la construcción que evita costos futuros. Esta parte responde a la pregunta fundamental del cliente: "¿Qué gano yo con esto?".

Una vez que el cliente entiende los beneficios, el sitio pasa a demostrar su capacidad técnica en la sección de "Características Técnicas Avanzadas". Aquí se muestra cómo se cumplen las promesas, presentando el dashboard intuitivo, la compatibilidad con un amplio ecosistema de dispositivos y las herramientas especializadas para la gestión de áreas comunes. Esta sección es crucial para generar credibilidad y demostrar que la plataforma es robusta y bien diseñada.

Con el valor y la tecnología ya establecidos, el enfoque se desplaza hacia la construcción de confianza a un nivel más humano. La sección de "Testimonios de clientes" utiliza la prueba social, mostrando a líderes de otras empresas constructoras que validan el éxito, la fiabilidad y el retorno de inversión de la plataforma. Poco después, la página "Sobre Nosotros" complementa esto humanizando la marca, presentando la misión, los valores y, más importante, al equipo de expertos detrás del proyecto. Juntas, estas secciones le dicen al cliente: "Somos expertos en lo que hacemos y otras empresas como la tuya ya confían en nosotros".

Finalmente, el sitio se enfoca en eliminar las últimas barreras para la compra. La página de "Preguntas Frecuentes" se anticipa a cualquier duda restante sobre implementación, precios o soporte, ofreciendo respuestas claras y transparentes. Esto conduce de forma natural a la sección de "Planes de la aplicación", donde la decisión se vuelve tangible. Con una estructura de precios escalable y un plan "Más Popular" claramente destacado, se facilita al cliente la elección de la opción que mejor se adapte a su escala. Por último, el "Footer" o pie de página actúa como una red de seguridad: ofrece un último llamado a la acción y un mapa completo del sitio para quienes necesiten más información, asegurando que ninguna pregunta quede sin respuesta y que el camino para empezar sea siempre accesible.

### 5.3.1. Landing Page Wireframe.

[Link ded Figma]<https://shorturl.at/ZkQuE>

#### 1. Home
- La interfaz sigue una estructura en Z con un header fijo con logo y menú principal, un hero section con título, subtítulo y un llamado a la acción destacado (“Empezar ahora”). En las secciones intermedias se presentan los beneficios en formato de tarjetas, seguidos de testimonios y planes de precios. El footer reúne enlaces organizados por categorías, accesos a redes sociales y aviso de copyright. El diseño es claro, escaneable y enfocado en la conversión, guiando al usuario de manera natural desde el primer contacto hasta la acción final.<br>

<img src="https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_Home_Wireframe.png" style="page-break-inside: auto; break-inside: auto; display: block;">
<br>

#### 1. About Us
- El wireframe de About se organiza en un esquema de columnas, a la izquierda se ubican el título y los párrafos descriptivos, mientras que a la derecha se reserva un espacio para la imagen. La página integra secciones jerarquizadas que construyen una narrativa clara sobre la identidad de la marca. En la parte inferior se disponen tarjetas con íconos y descripciones, seguidas de la presentación del equipo con un miembro destacado y cuatro integrantes adicionales. La composición se enmarca con una navegación principal en la parte superior y un footer completo al final, manteniendo coherencia visual y un flujo narrativo fluido.<br>

![Landing page About-us Wireframe](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_About-us_Wireframe.png)
<br>

#### 1. FAQ
- La sección adopta un acordeón vertical, donde cada pregunta se despliega para mostrar respuestas detalladas. Los contenidos abarcan temas clave como precios, diseño, edición y alianzas. En la parte superior, filtros por categoría facilitan la exploración del material, mientras que en la parte inferior un CTA “Didn’t Find Your Answer?” dirige a la página de contacto. El diseño mantiene un estilo minimalista y ordenado, y una jerarquía visual clara, optimizada para la legibilidad y una experiencia sin distracciones.<br>

![Landing page FAQ 1 Wireframe](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ_Wireframe.png)

![Landing page FAQ 2 Wireframe](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ2_Wireframe.png)
<br>

### 5.3.2. Landing Page Mock-up.

[Link ded Figma]<https://shorturl.at/ZkQuE>

#### 1. Home
- El mockup de la página principal presenta una estética moderna y minimalista, enfocada en la claridad y la atracción visual. En la parte superior, el header integra el logo junto con enlaces a Benefits, Features, Plans, About Us y FAQ, además de un botón de llamado a la acción “Get Started”. El hero section concentra la atención con un título llamativo y un botón CTA (“I want it!”) sobre un fondo verde claro. Más abajo, el contenido se organiza en bloques visuales con imágenes y una tipografía legible, destacando secciones como “Advanced Technical Features” y “Plans Designed for Your Scale”. Finalmente, el footer reúne enlaces estructurados (Home Page, Community, Legal, Company), íconos de redes sociales y un mensaje de marca que refuerza la identidad visual del sitio.

![Landing page Home Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_Home_Mock-up.png)
<br>

#### 2. About Us
- Esta sección presenta una introducción sobre la misión de CcaritaTech, destacando su enfoque en la innovación y el impacto social. Le siguen las secciones “Our Values” y “Our Team”, que reflejan los principios de la organización y presentan a su equipo. Cada apartado combina textos con imágenes representativas, creando una composición equilibrada. Predomina un estilo limpio y luminoso, con fondos claros, amplio espaciado y jerarquía tipográfica definida, lo que refuerza la coherencia visual y facilita una experiencia clara y atractiva para el usuario.

![Landing page About-us Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_About-us_Mock-up.png)
<br>

#### 3. FAQ
- El mockup de la sección FAQ utiliza una estructura de acordeón que organiza las preguntas frecuentes de forma clara y accesible. Al desplegar cada entrada, se muestra una respuesta concisa y comprensible, manteniendo la coherencia con el branding visual de la plataforma. Además, se incorpora una sección complementaria con canales de contacto para ofrecer soporte adicional. La interfaz destaca por su simplicidad, legibilidad y enfoque en la eficiencia, facilitando que el usuario encuentre rápidamente la información que necesita.

![Landing page FAQ 1 Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ%201_Mock-up.png)

![Landing page FAQ 2 Mock-up](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Web%20App/Cap%C3%ADtulo%204/Landingpage_FAQ%202_Mock-up.png)
<br>

## 5.4. Applications UX/UI Design.

La sección de Diseño UX/UI de Desarrollo de Soluciones IoT se enfoca en la creación de interfaces intuitivas y la definición de experiencias de usuario optimizadas para la plataforma web de IoBuild (`https://iobuild-remix.arroz.dev/`). Este proceso comprende desde la conceptualización de pantallas funcionales hasta el diseño de flujos de interacción adaptados a entornos de escritorio y estaciones de trabajo, considerando las necesidades específicas de nuestros dos segmentos clave: Arquitectos/Ingenieros (Builders) y Propietarios de Departamentos (Owners/Residentes).

En esta etapa, se desarrollaron wireframes y mockups de alta fidelidad rigurosamente alineados con el sistema visual y la identidad de marca de IoBuild (#10B981, #ECFDF5, tipografía Inter y componentes Vue/PrimeVue), garantizando una experiencia coherente, moderna y accesible en cada módulo de la aplicación web. El diseño prioriza la claridad analítica, la visualización de telemetría IoT en tiempo real y la eficiencia operativa en la gestión de proyectos inmobiliarios y dispositivos conectados.

Los componentes de la interfaz fueron organizados cuidadosamente siguiendo patrones de progressive disclosure y flujos de usuario previamente validados, tomando como referencia los Empathy Maps y User Journey Maps definidos en fases anteriores. La arquitectura de navegación fue diseñada para ofrecer una experiencia fluida e inclusiva, incorporando principios de accesibilidad (WCAG 2.2 / a11y) y soporte multilenguaje (i18n con selector inglés/español). Asimismo, la aplicación web integra servicios RESTful para la comunicación con el backend desplegado en la nube.

### 5.4.1. Applications Wireframes.

- Web Applications Wireframes

#### Vista del segmento #1: Arquitectos e Ingenieros Civiles (Builders)

#### 1. Login / Sign In
- Estructura de acceso a la plataforma con campos para correo electrónico corporativo y contraseña, botón de envío principal y accesos directos diferenciados para el registro según el rol del usuario ("Register as Builder" y "Register as Owner").

<img src="assets/wireframes/wf_01_login.png" alt="Segmento #1 Wireframe Login" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 2. Register as Builder
- Flujo de incorporación guiado por pasos (Step 1: Account Information, Step 2: Company Information) con campos para correo, contraseña y confirmación de credenciales para empresas constructoras.

<img src="assets/wireframes/wf_02_register_builder.png" alt="Segmento #1 Wireframe Register Builder" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 3. Builder Dashboard / Telemetría IoT
- Panel central de supervisión de infraestructura inteligente. Incluye tarjetas de métricas de alto nivel: Active Projects, Connected Devices (con indicador de dispositivos online), Occupied Units, Total Units, Alerts Count y Energy Efficiency Average. En la zona inferior se integran visualizaciones esquemáticas de consumo energético por hora en las últimas 24 horas y tasa de ocupación mensual proyectada.

<img src="assets/wireframes/wf_04_builder_dashboard.png" alt="Segmento #1 Wireframe Dashboard" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 4. Projects Management
- Galería de proyectos inmobiliarios organizados en tarjetas modulares. Cada tarjeta expone el nombre del proyecto, ubicación/anexo, estado operativo (On going, Planned), Total Units, Occupied Units, barra de progreso de tasa de ocupación y botón de acción directa "View Details". En la cabecera destaca el botón "+ Add Project".

<img src="assets/wireframes/wf_05_builder_projects.png" alt="Segmento #1 Wireframe Projects" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 5. Create New Project
- Formulario de creación de proyectos residenciales con campos obligatorios para Project Name, Description, Location, enlace o carga de imagen del complejo inmobiliario y botón de confirmación "Save & Configure Structure".

<img src="assets/wireframes/wf_06_builder_new_project.png" alt="Segmento #1 Wireframe New Project" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 6. Clients Management
- Tabla analítica de administración de clientes y residentes asignados a los proyectos. Presenta columnas con ordenamiento dinámico: Full Name, Associated Project, Unit / Apartment, Account Statement (Active, Suspended) y columna de acciones (View Profile y engranaje de configuración).

<img src="assets/wireframes/wf_07_builder_clients.png" alt="Segmento #1 Wireframe Clients" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 7. Device Management
- Tabla de supervisión integral de hardware IoT instalado en los edificios. Desglosa los dispositivos por Name, Type (SmartMeter, SmartLight, SmokeDetector, WaterSensor, AirConditioner), Location (Torre y piso), Real-time Status (Online / Offline) y acciones de configuración y desvinculación.

<img src="assets/wireframes/wf_08_builder_devices.png" alt="Segmento #1 Wireframe Devices" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 8. Subscriptions & Plans
- Módulo de suscripciones SaaS de la constructora. Presenta la tarjeta de plan activo con tarifa mensual, cuotas de consumo de dispositivos IoT (IoT Devices Quotas), proyectos activos y fecha de renovación. En la parte inferior se exhiben los planes disponibles (Starter, Professional, Enterprise) con listas detalladas de características incluidas y botón de selección.

<img src="assets/wireframes/wf_09_builder_subscription.png" alt="Segmento #1 Wireframe Subscriptions" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 9. Profile & Account Settings
- Vista de configuración del perfil del usuario corporativo. Muestra la tarjeta del perfil con avatar, nombre, rol y botón "Edit Profile", acompañada del formulario de información de cuenta (Full Name, Email, Phone Number, Address, Alternate Email y Years in Business).

<img src="assets/wireframes/wf_10_builder_profile.png" alt="Segmento #1 Wireframe Profile" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br><br>

#### Vista del segmento #2: Propietarios de departamentos (Owners)

#### 1. Register as Owner
- Formulario de registro en dos pasos para propietarios y residentes de condominios, con campos de credenciales de acceso (Email, Password, Confirm Password) y posterior vinculación de información personal y número de departamento.

<img src="assets/wireframes/wf_03_register_owner.png" alt="Segmento #2 Wireframe Register Owner" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 2. My Unit Dashboard
- Panel de control doméstico inteligente para el residente. Expone indicadores de sus unidades asignadas (My Units), dispositivos instalados (My Devices), alertas activas y módulos de consumo energético de los últimos 30 días, confort térmico (temperatura) y consumo hídrico.

<img src="assets/wireframes/wf_11_owner_dashboard.png" alt="Segmento #2 Wireframe Owner Dashboard" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 3. Device Management
- Tabla de monitoreo y control en tiempo real de los dispositivos inteligentes instalados dentro del departamento privado del residente (iluminación inteligente, sensores de temperatura, detectores de humo y aire acondicionado), visualizando el estado de conexión Online/Offline y opciones de ajuste.

<img src="assets/wireframes/wf_08_builder_devices.png" alt="Segmento #2 Wireframe Devices" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 4. Profile & Preferences
- Vista de gestión de datos personales del propietario, información de contacto de emergencia, unidad asociada y personalización de preferencias.

<img src="assets/wireframes/wf_10_builder_profile.png" alt="Segmento #2 Wireframe Profile" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

### 5.4.2. Applications Wireflow Diagrams.

- Web Applocations Wireflow Diagrams

#### Segmento Objetivo #1: Arquitectos e Ingenieros Civiles
Los arquitectos e ingenieros civiles utilizan la plataforma IoBuild para gestionar sus proyectos residenciales, centralizar la información de clientes, monitorear dispositivos IoT implementados en los edificios y configurar opciones de administración de manera eficiente.

**Login / Create Account**

**1. Login:**
- El usuario de la constructora introduce su correo corporativo y contraseña.
-  Selecciona la opción “Login” para acceder a su cuenta empresarial.

**Create Account:**
- Si es un nuevo usuario, completa un formulario con datos de la empresa, representante y correo corporativo.
- Selecciona “Create” para registrar la cuenta en el sistema.

**Acción esperada:** Autenticarse exitosamente en la plataforma y acceder al Dashboard principal.<br><br>

**2. Dashboard**
-	Una vez autenticado, el usuario accede al panel principal, donde se visualiza un menú lateral con accesos a secciones clave:
     - Home
     - Profile
     - Projects
     - Client Management
     - Configuration
-	El Dashboard sirve como centro de navegación para todas las funciones de la plataforma.

**Acción esperada:** Orientarse rápidamente en la aplicación y seleccionar la sección que desea administrar.<br><br>

**3. Profile**
-	Visualiza y edita información del usuario administrador como el nombre, logo, contacto, etc.
-	Opciones para gestionar miembros del equipo y asignar roles.

**Acción esperada:** Actualizar datos corporativos, ver plan y administrar accesos del equipo.<br><br>

**4. Project Management**
-	El usuario accede a la sección Projects, donde puede ver un listado de proyectos residenciales activos.
-	Cada proyecto incluye nombre, estado, fecha y acceso a detalles.
-	Puede pulsar “+ Add Project” para registrar un nuevo proyecto en la plataforma.

**Acción esperada:** Visualizar, gestionar o crear proyectos residenciales vinculados a la constructora.<br><br>

**5. Client Management**
-	En la sección Client Management, se despliega una tabla con los clientes asociados a cada proyecto.
-	Se muestran datos como nombre completo, proyecto asociado, estado y opciones de acción.
-	El usuario puede añadir nuevos clientes con el botón “+ Add Client”.

**Acción esperada:** Gestionar información de clientes vinculados a los proyectos residenciales.<br><br>


**6. Configuration**
-	En el apartado Configuration, la constructora puede administrar aspectos como notificaciones, seguridad, idioma de la aplicación y soporte técnico.
-	Incluye secciones de seguridad y privacidad (cambio de contraseña, autenticación en dos pasos), así como alertas del sistema.

**Acción esperada:** Personalizar la configuración de la plataforma para ajustarla a las necesidades de la empresa.<br><br>

[Web Applications Wireflow Diagrams - Arquitectos e Ingenieros Civiles] <https://shorturl.at/ORylU>
![Web Aplication Wireflow Guest](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Wireflow_Segmento2.png)


#### Segmento Objetivo #2: Dueños de apartamentos


**Login / Create Account**

**1. Login:**
- El usuario introduce su correo electrónico y contraseña.
- Pulsa “Login” para acceder a su cuenta personal.

**Create Account:**
- Si es nuevo, completa un formulario con nombre completo, correo, dirección (unidad), y contraseña.
- Pulsa “Create” para registrar la cuenta.

**Acción esperada:** Autenticarse correctamente y acceder al Dashboard personal.<br><br>

**2. Dashboard**
-	Una vez autenticado, el usuario accede al panel principal, donde se visualiza un menú lateral con accesos a secciones clave::
     - Home
     - Profile
     - Device Management
     - Configuration
-	Al ingresar, el dueño visualiza un Dashboard con widgets clave: consumo energético mensual (gráfico), estado general de dispositivos (rueda/donut), resumen de ahorros por dispositivo (gráfica) y un Notifications feed con alertas recientes.

**Acción esperada:** Obtener un panorama rápido del estado del apartamento y acceder en un clic a control de dispositivos o a la configuración.<br><br>

**3. Profile**
-	Vista para ver/editar datos personales y de la unidad: nombre, contacto, dirección vinculada, Current Plan, zona horaria e idioma.
-	Secciones: Edit Profile, Favorite Scene Configuration (botones Use para escenas guardadas), opciones para invitar a familiares o delegar accesos.

**Acción esperada:** Actualizar información del propietario, gestionar quién tiene acceso y elegir escenas favoritas para uso rápido.<br><br>

**4. Device Management**
-	Acciones principales: + Add Device y + Create Scene.
-	Dentro de cada dispositivo: estado en tiempo real, historial básico y acceso a ajustes

**Acción esperada:** Añadir, identificar y controlar dispositivos individuales de forma ágil.<br><br>

**5. Configuration**
-	Panel con secciones: Notifications, Security and Privacy (cambio de contraseña, 2FA, gestión de sesiones), Support and Help y Advanced Device Management
-	Opciones para activar/desactivar notificaciones críticas, administrar permisos de invitados y configurar preferencias globales de la unidad.

**Acción esperada:** Personalizar la experiencia y garantizar seguridad y soporte.<br><br>

[Web Applications Wireflow Diagrams - Dueños de apartamentos] <https://shorturl.at/h1jhp>
![Web Aplication Wireflow Guest](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Wireflow_Segmento1.png)

### 5.4.3. Applications Mock-ups.

- Web Applications Mock-ups

Los mock-ups de alta fidelidad han sido implementados y validados directamente en el entorno de producción desplegado de la plataforma web IoBuild (`https://iobuild-remix.arroz.dev/`). Reflejan con exactitud los componentes PrimeVue, estilos Tailwind CSS, iconografía PrimeIcons y la arquitectura modular para los roles de empresa constructora (Builder) y propietario particular (Owner).

#### Vista del segmento #1: Arquitectos e Ingenieros Civiles (Builders)

#### 1. Login / Sign In
- Pantalla de inicio de sesión de la plataforma IoBuild. Presenta un formulario centrado sobre una imagen de fondo arquitectónico contemporáneo con superposición de cuadrícula técnica. Incluye los campos obligatorios para Email y Password, botón de acción "Sign In", y dos accesos destacados en tarjetas inferiores para el registro rápido según el rol: "Register as Builder" y "Register as Owner".

<img src="assets/webapp/01_login.png" alt="Segmento #1 Mock-up Login" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 2. Register as Builder
- Flujo interactivo de registro corporativo estructurado mediante un indicador de pasos (Step 1: Account Information, Step 2: Company Information). Permite registrar las credenciales del representante técnico de la constructora (Email, Password, Confirm Password) antes de pasar a la configuración de la empresa.

<img src="assets/webapp/02_register_builder.png" alt="Segmento #1 Mock-up Register Builder" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 3. Builder Dashboard & Telemetría IoT
- Panel principal de control y analítica para arquitectos e ingenieros. En la parte superior muestra tarjetas de indicadores clave de rendimiento (KPIs): "Active Projects" (2), "Connected Devices" (120 online), "Occupied Units" (6/50 con 12.0% de ocupación), "Total Units" (50), "Alerts" (0) y "Energy Efficiency" (1278.1 kWh de consumo promedio). En la sección inferior se despliegan gráficos interactivos de Chart.js: un gráfico de líneas continuo que muestra el "Hourly Energy Consumption (Last 24h)" y un gráfico de barras que detalla el "Monthly Occupancy Rate".

<img src="assets/webapp/04_builder_dashboard_full.png" alt="Segmento #1 Mock-up Dashboard" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 4. Projects Management
- Vista de administración de proyectos residenciales en ejecución. Presenta una cuadrícula de tarjetas donde se detallan proyectos como "ccarita house" (50 unidades totales, 6 ocupadas, 12% ocupación, estado "On going") y "proyecto 1" (estado "Planned"). Cada tarjeta cuenta con barra de progreso visual, fecha de actualización y botón interactivo "View Details". En la parte superior derecha se sitúa el botón "+ Add Project".

<img src="assets/webapp/05_builder_projects.png" alt="Segmento #1 Mock-up Projects" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 5. Create New Project
- Formulario de alta para nuevos desarrollos inmobiliarios y condominios inteligentes. Integra campos validados para "Project Name", "Description" y "Location", así como un componente de carga para imagen referencial del complejo habitacional y botón de guardado "Save & Configure Structure".

<img src="assets/webapp/06_builder_new_project.png" alt="Segmento #1 Mock-up New Project" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 6. Clients Management
- Tabla interactiva para la administración de propietarios y residentes asociados a los proyectos de la constructora. Muestra listados con paginación que incluyen: "Full Name", "Associated Project", "Unit / Apartment" (identificador de departamento), "Account Statement" (badges de estado "Active") y opciones de acción directa como "View Profile" y engranaje de configuración. En la cabecera cuenta con el botón "+ Add Client".

<img src="assets/webapp/07_builder_clients.png" alt="Segmento #1 Mock-up Clients" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 7. Device Management & Telemetry Status
- Centro de supervisión y gestión del inventario de dispositivos IoT instalados en las torres y áreas comunes. Presenta una tabla con ordenamiento por "Name" (ej. Sensor de Temperatura - Torre A, Monitor de Humedad - Torre B), "Type" (SmartMeter, SmartLight, SmokeDetector, WaterSensor, AirConditioner), "Location" (Torre y piso) y "Real-time Status" con etiquetas dinámicas en verde ("Online") y rojo ("Offline"), junto con acciones para editar y desvincular hardware.

<img src="assets/webapp/08_builder_devices.png" alt="Segmento #1 Mock-up Devices" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 8. Subscriptions & Billing Plans
- Panel de gestión de suscripciones SaaS integrado con Stripe. Expone el plan actual activo ("Professional" a $799/mes), métricas de cuota de dispositivos IoT asignados (0 / 200 cuotas utilizadas), proyectos activos permitidos y fecha del próximo ciclo de facturación. En la parte inferior permite explorar y cambiar a los planes "Starter" ($299/mes) o "Enterprise" ($1299/mes) con detalles pormenorizados de funcionalidades.

<img src="assets/webapp/09_builder_subscription.png" alt="Segmento #1 Mock-up Subscriptions" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 9. Profile & Account Settings
- Vista de configuración y administración del perfil del constructor. Incorpora tarjeta de cabecera con avatar personalizado, nombre de usuario corporativo ("ccaritatech"), rol asignado ("Builder") y botón "Edit Profile". En el bloque "Account Information" se visualizan los campos editables: Full Name, Email corporativo, Phone Number, Address, Alternate Email y Years in Business.

<img src="assets/webapp/10_builder_profile.png" alt="Segmento #1 Mock-up Profile" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br><br>

#### Vista del segmento #2: Propietarios de departamentos (Owners)

#### 1. Register as Owner
- Formulario de autoservicio para nuevos propietarios de unidades inteligentes. Permite crear la cuenta de residente mediante credenciales seguras (Email y contraseña con validación de seguridad y visor de caracteres) antes de asociar el departamento correspondiente.

<img src="assets/webapp/03_register_owner.png" alt="Segmento #2 Mock-up Register Owner" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 2. My Unit Dashboard
- Panel de control doméstico del propietario residencial ("My Unit Dashboard - Personal overview of your smart home"). Proporciona métricas rápidas de sus departamentos asociados ("My Units"), dispositivos activos ("My Devices") y "Alerts". En la zona central e inferior integra paneles de telemetría dedicados al consumo de energía de los últimos 30 días ("My Energy Consumption"), confort ambiental de temperatura ("Temperature Comfort (Last 7 Days)") y uso de agua semanal ("Water Usage (This Week)").

<img src="assets/webapp/13_owner_dashboard.png" alt="Segmento #2 Mock-up Owner Dashboard" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 3. Real-time Device Management
- Vista centralizada para la consulta del estado operativo de los dispositivos instalados en el departamento del propietario. Permite verificar en tiempo real si los sensores ambientales, medidores y actuadores de climatización se encuentran en línea y funcionando correctamente.

<img src="assets/webapp/14_devices_list.png" alt="Segmento #2 Mock-up Devices" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

#### 4. Profile & Preferences
- Vista de administración de datos personales del residente, información de contacto ante emergencias y preferencias de notificaciones sobre el estado de su unidad habitacional.

<img src="assets/webapp/10_builder_profile.png" alt="Segmento #2 Mock-up Owner Profile" width="850" style="max-width: 100%; height: auto; border-radius: 6px;" />
<br>

### 5.4.4. Applications User Flow Diagrams.

- Web Applications User Flow Diagrams

#### Segmento Objetivo #1: Arquitectos e Ingenieros Civiles

**1. Profile**
**User Goal:** Como ingeniero, quiero ver y editar mi infomación.
![Segmento #1 User Flow #1](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Segmento%231_User-Flow%231.png)

**2. Project Management**
**User Goal:** Como ingeniero, quiero ver, editar y añadir projects en los que estoy trabajando.
![Segmento #1 User Flow #2](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Segmento%231_User-Flow%232.png)

**3. Client Management**
**User Goal:** Como ingeniero, quiero monitorear los dispositivos de los projectos en los que estoy trabajando.
![Segmento #1 User Flow #3](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Segmento%231_User-Flow%233.png)

**4. Configuration**
**User Goal:** Como ingeniero, quiero personalizar la configuración de la plataforma.
![Segmento #1 User Flow #4](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Segmento%231_User-Flow%234.png)

#### Segmento Objetivo #2: Dueños de apartamentos

**1. Profile**
**User Goal:** Como propietario, quiero ver y editar mi infomación.
![Segmento #2 User Flow #1](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Segmento%232_User-Flow%231.png)

**2. Device Management**
**User Goal:** Como propietario, quiero monitorear y configurar mis dispositivos.
![Segmento #2 User Flow #2](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Segmento%232_User-Flow%232.png)

**3. Configuration**
**User Goal:** Como propietario, quiero personalizar la configuración de la plataforma.
![Segmento #2 User Flow #3](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%204/Segmento%232_User-Flow%233.png)

## 5.5. Applications Prototyping.

- Web Applications Prototyping

En esta etapa se presentan los prototipos funcionales y navegables de la aplicación web IoBuild, diseñados para entornos de escritorio y estaciones de trabajo de alta resolución. El enfoque está en validar los flujos principales de cada segmento objetivo, garantizando una experiencia clara, accesible y de alta usabilidad.

**Segmento constructoras (Arquitectos e Ingenieros Civiles)**  
Los ingenieros usan la plataforma web para gestionar proyectos residenciales, centralizar información de clientes, supervisar telemetría y dispositivos IoT en tiempo real y gestionar suscripciones y perfiles organizacionales:
- Desde el módulo principal, acceden al Dashboard con métricas de consumo energético (kWh) y ocupación mensual analítica en tiempo real.
- La barra lateral de navegación persistente incluye acceso directo a: Dashboard, Projects, Add Project, Clients, Device Management, Subscription y Profile.
- En la vista de Clientes y Proyectos, se administra la asignación de inquilinos, estados contractuales e inventario de hardware IoT por departamento.
- En Device Management se supervisa el estado operativo, telemetría y conectividad de cada actuador y sensor instalado.

**Segmento Dueños de Departamentos (Propietarios e Inquilinos)**  
Los residentes interactúan con el portal para monitorear el consumo de sus unidades departamentales y controlar sus dispositivos inteligentes:
- El recorrido inicia en el Dashboard de Propietario con tarjetas de resumen de consumo mensual y estado de los dispositivos vinculados.
- Menú simplificado y contextual con accesos a Dashboard, Dispositivos vinculados, Notificaciones de consumo y Perfil personal.
- Capacidad de encendido/apagado remoto, configuración de umbrales de alerta y visualización histórica de consumo energético y agua.

**Acceso al Prototipo Navegable y Entorno de Producción:**
- Prototipo interactivo navegable: [https://goo.su/Cor4Q](https://goo.su/Cor4Q)
- Aplicación Web en Producción: [https://iobuild-remix.arroz.dev/](https://iobuild-remix.arroz.dev/)

## 5.6. IoT Device Design.

El diseño físico y funcional de los nodos y dispositivos IoT de IoBuild contempla una arquitectura de hardware embebido optimizada para entornos residenciales y de construcción:
- **Unidad de Control y Procesamiento:** Módulos basados en microcontroladores ESP32 con conectividad Wi-Fi 802.11 b/g/n y Bluetooth Low Energy (BLE), garantizando bajo consumo de energía y procesamiento local de lecturas de sensores.
- **Sensores e Interfaces:** Módulos de medición de corriente y consumo eléctrico (sensores no invasivos SCT-013), sensores de flujo de agua y actuadores de relé para control de corte o activación remota.
- **Carcasa y Enclosure:** Gabinetes normalizados para riel DIN y cajas de empotrar con estándar de protección IP54, diseñados para su instalación en tableros eléctricos residenciales y cajas de pase de obra, garantizando seguridad eléctrica y disipación térmica adecuada.
- **Protocolo de Comunicación:** Transmisión ligera mediante MQTT/HTTPS hacia los gateways y la API RESTful de IoBuild, con cifrado TLS para asegurar la integridad de la telemetría enviada desde cada departamento.

# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management.

La gestion de configuracion de software del proyecto **IoBuild** define y controla el conjunto de herramientas, servicios y convenciones necesarios para asegurar un desarrollo movil consistente, trazable y reproducible.  
En esta seccion se documentan los componentes del entorno de desarrollo, su proposito dentro del proyecto y su aporte a la calidad del producto final.

### 6.1.1. Software Development Environment Configuration.

- Web Applications

| Producto                                                                                                                                                               | Propósito en el proyecto                                                      | Categoría | Ruta de descarga / acceso | Descripción |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|-----------|---------------------------|-------------|
| JetBrains WebStorm  ![Logo de WebStorm](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Web_Storm_logo.png)  | Desarrollo web moderno utilizando tecnologías actuales como Vue y TypeScript. | Software Development | https://www.jetbrains.com/webstorm/ | IDE de JetBrains para desarrollo web moderno con soporte para JavaScript, TypeScript y frameworks frontend como Vue.js. |
| Vue.js  ![Logo de Vue.js](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Vue_logo.png)                      | Administración del ciclo de vida en aplicaciones desarrolladas con Vue.js.    | Software Development | https://vuejs.org/guide/introduction.html | Framework progresivo de JavaScript para construir interfaces de usuario de forma declarativa y eficiente. |
| UXPressia  ![Logo de UXPressia](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Uxpressia_logo.png)          | Representación gráfica de la experiencia del usuario.                         | Product UX/UI Design | https://uxpressia.com/ | Plataforma orientada a la elaboración de journey maps y perfiles de usuario, que permite representar y analizar de forma visual la experiencia dentro del sistema. |
| Lucidchart  ![Logo de Lucidchart](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Lucidchart_logo.png)       | Planificación estructurada del software mediante representaciones gráficas.   | Product UX/UI Design | https://www.lucidchart.com/ | Herramienta diseñada para elaborar diagramas de procesos, flujos y arquitecturas de sistemas, que optimiza la planificación visual y la organización del software. |
| Structurizr  ![Logo de Structurizr](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Structurizr_logo.png)    | Diseño y documentación de arquitecturas de software basadas en el modelo C4.  | Product UX/UI Design | https://structurizr.com/ | Aplicación especializada en la creación de modelos de arquitectura de software con base en el modelo C4, ideal para documentar y comprender sistemas complejos. |
| GitHub  ![Logo de GitHub](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/GitHub_logo.png)                   | Plataforma para la gestión de código fuente y control de versiones.           | Collaboration & Version Control Tools | https://github.com/ | Plataforma de desarrollo colaborativo para alojar, revisar y gestionar proyectos de software. |
| MySQL Workbench  ![Logo de MySQL Workbench](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/MySQL_logo.jpg) | Desarrollo y depuración del backend basado en .NET.                           |Software Development |https://dev.mysql.com/downloads/workbench/ | Aplicación visual para diseñar esquemas, ejecutar consultas SQL, gestionar usuarios y administrar servidores MySQL de manera integrada.|
| Docker Desktop  ![Logo de Docker Desktop](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Docker_logo.jpg)   |Contenerización del backend y servicios asociados para facilitar despliegues.|DevOps / Containerization|https://www.docker.com/products/docker-desktop/|Herramienta que permite crear, ejecutar y gestionar contenedores Docker, asegurando entornos reproducibles para desarrollo y producción.   |
| Swagger UI  ![Logo de Swagger UI](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Logo.jpg)           |Documentación interactiva de la API.|API Documentation Tool|https://swagger.io/tools/swagger-ui/|Interfaz que genera documentación dinámica de APIs REST, permitiendo visualizar rutas, parámetros y probar los endpoints directamente desde el navegador.|
| Git CLI (Git)  ![Logo de Git CLI](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Git_logo.jpg)           |Manejo local de control de versiones.|Version Control|https://git-scm.com/|Sistema de control de versiones distribuido que permite gestionar cambios, trabajar con ramas y sincronizar código con repositorios remotos como GitHub.|


- Cloud & IoT Development Environment Configuration

Para complementar el desarrollo web y backend de la solución, se configuró el entorno de desarrollo y pruebas para los servicios en la nube y los dispositivos IoT:

| Producto/Herramienta | Categoría | Ruta de Descarga/Acceso | Propósito en el Proyecto |
|---|---|---|---|
| .NET 8 SDK | Desarrollo Backend | https://dotnet.microsoft.com/ | SDK y runtime para la compilación y ejecución de la Web API en ASP.NET Core |
| Visual Studio / VS Code | Desarrollo Backend | https://visualstudio.microsoft.com/ | Entornos de desarrollo integrados para C# y depuración de microservicios |
| Postman | Testing APIs | https://www.postman.com/ | Pruebas de endpoints RESTful y automatización de colecciones de prueba |
| Arduino IDE / ESP-IDF | Desarrollo IoT Embebido | https://www.arduino.cc/ | Programación y flasheo de microcontroladores ESP32 para nodos de telemetría |
| MQTT Explorer | Herramienta IoT | https://mqtt-explorer.com/ | Monitoreo y depuración de tópicos de telemetría MQTT transmitidos por los dispositivos |
| Stripe Dashboard (Sandbox) | Pasarela de Pagos | https://stripe.com/ | Entorno de pruebas para procesamiento de suscripciones y transacciones de clientes |
| GitHub Actions | CI/CD | https://github.com/features/actions | Automatización de flujos de integración y despliegue continuo |

### 6.1.2. Source Code Management.

- Web Applications

El proyecto IoBuild, una plataforma SaaS para la gestión y personalización de dispositivos IoT en entornos de construcción y apartamentos inteligentes, se desarrolla bajo un enfoque profesional que prioriza las buenas prácticas de arquitectura, la colaboración en equipo, la automatización de flujos y la estandarización del entorno de desarrollo. La configuración del entorno se ha diseñado con base en el modelo C4 (Context, Container, Component, Code) y en los principios de la Clean Architecture, lo que asegura una separación clara de responsabilidades, la reutilización de componentes y la escalabilidad del sistema a futuro.

Para el frontend, el equipo utiliza WebStorm como IDE principal, administrado a través de JetBrains Toolbox, lo que garantiza una configuración uniforme en todos los integrantes del equipo. Este entorno de trabajo ofrece integración nativa con Vue.js, framework elegido para el desarrollo de la interfaz, lo que facilita la generación de componentes, servicios y módulos directamente desde el IDE. Además, se aprovechan funciones avanzadas como la navegación semántica, la refactorización inteligente, la depuración integrada y la administración de dependencias, optimizando la productividad y reduciendo errores en el proceso de implementación.

Vue.js se seleccionó como la tecnología central para el frontend debido a su arquitectura reactiva y declarativa, basada en componentes reutilizables que permiten un diseño flexible y modular. Gracias a su Vue CLI, la integración de librerías externas y su compatibilidad con metodologías modernas de desarrollo, la plataforma puede estructurarse en torno a bounded contexts, separando de forma clara la vista, la lógica y los servicios. Esta organización permite que diferentes miembros del equipo trabajen en paralelo sin comprometer la coherencia del sistema, mejorando los tiempos de entrega y asegurando la calidad del producto final.

Finalmente, el equipo mantiene un repositorio paralelo denominado upc-pre-1ASI0730-7461-CcaritaTech (https://github.com/upc-pre-1ASI0730-7461-CcaritaTech), donde se gestionan versiones experimentales y entornos de prueba bajo un enfoque académico y exploratorio. Este repositorio funciona como un espacio seguro para validar prototipos, realizar pruebas funcionales y explorar nuevas características antes de ser integradas en el sistema principal. De esta manera, IoBuild asegura que las innovaciones sean evaluadas en un entorno controlado, evitando riesgos en la plataforma productiva y garantizando la estabilidad del proyecto central.

![Repositorios de IoBuild](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Repositorios_de_IoBuild.png)

- Mobile Applications

La gestion del codigo fuente de **IoBuild** se realiza con Git y GitHub, siguiendo practicas estandar para asegurar trazabilidad, colaboracion efectiva y control de cambios durante todo el ciclo de desarrollo.

**Gestion de Repositorios**

El proyecto utiliza GitHub como plataforma centralizada de control de versiones. La organizacion del codigo se separa por componente para facilitar mantenimiento independiente y evolucion controlada del sistema.

| Producto | URL del Repositorio | Descripcion |
|---|---|---|
| Landing Page | https://github.com/CcaritaTech/IoBuild-LandingPage | Sitio web de presentacion y marketing del producto |
| Web Application (Frontend) | https://github.com/CcaritaTech/IoBuild-Frontend | Aplicación web SPA desplegada en producción (https://iobuild-remix.arroz.dev/) |
| Backend Web Services | https://github.com/CcaritaTech/IoBuild-Backend | API RESTful en ASP.NET Core desplegada en la nube |
| Project Report | https://github.com/CcaritaTech/Report | Reporte tecnico y documentacion del proyecto |

**Implementacion de GitFlow**

Se adopta GitFlow como estrategia de branching para estructurar el trabajo del equipo. Este modelo define ramas principales para produccion e integracion, junto con ramas de soporte para nuevas funcionalidades, releases y hotfixes. Con ello se mantiene la estabilidad del codigo y se ordena el flujo de trabajo entre desarrollo, validacion y entrega.

**Convenciones de Nomenclatura**

Para mantener consistencia en el repositorio, se establecen convenciones de nombres para ramas:

- `feature/<modulo>-<descripcion-corta>`
- `release/v<major>.<minor>.<patch>`
- `hotfix/v<major>.<minor>.<patch>`
- `bugfix/<modulo>-<descripcion-corta>`

Estas convenciones permiten identificar rapidamente el proposito de cada rama y mejoran la coordinacion entre integrantes.

**Versionado Semantico**

El proyecto sigue Semantic Versioning (`MAJOR.MINOR.PATCH`):

- `MAJOR`: cambios incompatibles con versiones anteriores.
- `MINOR`: nuevas funcionalidades compatibles.
- `PATCH`: correcciones de errores sin romper compatibilidad.

Este esquema comunica claramente el impacto de cada version y facilita la planificacion de despliegues.

**Conventional Commits**

Se utiliza la especificacion Conventional Commits para estandarizar los mensajes de commit y mejorar la trazabilidad del historial. Formato base:

`<type>(<scope>): <description>`

Tipos de commit mas usados:

- `feat`: nueva funcionalidad.
- `fix`: correccion de error.
- `docs`: cambios en documentacion.
- `refactor`: mejora interna sin cambiar comportamiento funcional.
- `test`: incorporacion o ajuste de pruebas.
- `chore`: tareas de mantenimiento o configuracion.

Esta convencion facilita auditoria de cambios y futura generacion automatica de changelogs.

### 6.1.3. Source Code Style Guide & Conventions.

- Web Applications

El uso de un estilo de código unificado y una arquitectura bien definida es clave para asegurar la escalabilidad, la mantenibilidad y la colaboración efectiva en el desarrollo de IoBuild. Para ello, el proyecto incorpora prácticas de programación y convenciones estructurales que promueven la calidad técnica, la claridad y la consistencia en cada módulo de la plataforma, tomando como referencia estándares reconocidos de la industria y metodologías actuales.

**Arquitectura y organización del sistema**

IoBuild adopta el modelo C4 de Simon Brown, lo que permite visualizar el sistema en distintos niveles de abstracción (contexto, contenedor, componente y código). Este enfoque ofrece una representación clara y comprensible, facilitando la comunicación entre desarrolladores, diseñadores y testers. Además, la arquitectura se fundamenta en los principios de Domain-Driven Design (DDD) y Clean Architecture, lo que garantiza una separación rigurosa entre capas (presentación, aplicación, dominio e infraestructura). Gracias a ello, se reduce el acoplamiento, se incrementa la mantenibilidad y se fortalece la capacidad de realizar pruebas automatizadas de manera eficiente.

**Frontend: Vue.js**

En el frontend, se emplea Vue.js como framework principal, implementando una arquitectura centrada en componentes reutilizables, organizados en directorios específicos como components, views y store. La convención de nombres establece el uso de PascalCase para los componentes (por ejemplo, DeviceCard.vue) y kebab-case para los archivos (device-card.vue), en concordancia con las recomendaciones de la comunidad Vue. Asimismo, se aplican buenas prácticas de desarrollo, entre ellas:

- Separación de lógica y presentación mediante el patrón container/presentational components.
- Uso de props y emits para la comunicación clara entre componentes.
- Implementación de lazy loading y code splitting para optimizar el rendimiento.
- Internacionalización con vue-i18n, gestionando archivos JSON para cada idioma.

**Alineación con guías de estilo estándar**

La estructura y nomenclatura utilizadas en IoBuild siguen convenciones reconocidas como la Vue Style Guide y lineamientos generales de HTML/CSS. Además, el uso del inglés en identificadores, clases y funciones garantiza coherencia en el trabajo colaborativo, simplifica la integración con librerías externas y favorece la comprensión del código por parte de equipos internacionales.

- General Code Style Guide & Conventions

El proyecto **IoBuild** define una guía de estilo común para mantener consistencia, legibilidad y mantenibilidad en sus componentes de backend (.NET), frontend web (Vue.js/Remix), firmware IoT (ESP32) y landing page.

**1. Estándares Generales de Nomenclatura**

Se adopta nomenclatura en inglés para elementos de código (clases, métodos, variables, interfaces y ramas). Esta decisión reduce ambigüedades, facilita la colaboración técnica y mantiene alineación con la documentación de las tecnologías utilizadas.

Reglas generales:
- Nombres descriptivos y orientados a responsabilidad única (SRP).
- Una sola convención por tipo de elemento en todo el ecosistema.
- Evitar abreviaciones no estándar o crípticas.
- Mantener paridad semántica entre código, pruebas automatizadas y especificación técnica.

**2. Convenciones para Backend y Web API (.NET 8 / C#)**

Para el backend en ASP.NET Core se adoptan las convenciones oficiales de Microsoft C# Coding Conventions y principios de Clean Architecture:

- Clases, interfaces, métodos y propiedades públicas en `PascalCase` (ej. `DeviceController`, `IProjectRepository`).
- Parámetros de métodos y campos privados con prefijo de guión bajo en `camelCase` (ej. `_dbContext`, `projectId`).
- Prefijo `I` obligatorio para todas las interfaces (ej. `IUnitOfWork`).
- Controladores RESTful organizados bajo el patrón CQRS/DDD con rutas descriptivas en minúsculas y verbos HTTP estándar (`GET`, `POST`, `PUT`, `DELETE`).
- Métodos asíncronos sufijados con `Async` (ej. `GetProjectByIdAsync`).
- Recursos y DTOs específicos para evitar sobreexposición de entidades de dominio.

**3. Convenciones para Frontend Web (Vue.js / TypeScript)**

Para la aplicación web se siguen las recomendaciones oficiales de la Vue Style Guide (Priority A y B):

- Componentes Single File Components (SFC) con nombres multi-palabra en `PascalCase` (ej. `DeviceStatusCard.vue`, `ProjectList.vue`).
- Props declaradas con tipado estricto y valores por defecto (`camelCase` en script, `kebab-case` en template).
- Gestión de estado global con Pinia modularizado por contextos (`auth`, `analytics`, `devices`).
- Nomenclatura de clases CSS utility-first bajo estándares de Tailwind CSS.

**4. Convenciones para Pruebas y Especificaciones**

Las pruebas unitarias y de integracion usan nombres descriptivos que explican escenario y resultado esperado.

Convenciones aplicadas:

- Nombre de test orientado a comportamiento: `shouldExpectedResultWhenCondition`.
- Estructura `Arrange - Act - Assert`.
- Separacion de pruebas por capa o feature.
- En pruebas de aceptacion con Gherkin, uso de escenarios claros bajo `Given - When - Then`.

Con este enfoque, las pruebas funcionan como evidencia tecnica y documentacion viva de los requisitos.

**5. Guias para Frontend y Documentacion**

Para la landing page (HTML/CSS/JS) se aplican buenas practicas de estilo inspiradas en guias de Google y estandares web:

- HTML semantico y jerarquia clara de encabezados.
- Clases CSS con nombres descriptivos y consistentes.
- Separacion de estructura, estilos y comportamiento.
- Diseno responsive para desktop y mobile.

Para la documentacion (`README`, diagramas y evidencias), se mantiene formato uniforme:

- Titulos y secciones con numeracion consistente.
- Tablas para configuraciones, herramientas y trazabilidad.
- Lenguaje tecnico claro y directo.
- Actualizacion continua de evidencias por sprint.

Estas convenciones fortalecen la calidad del codigo y facilitan el trabajo colaborativo durante todo el ciclo de vida del producto.

### 6.1.4. Software Deployment Configuration.

- Web Applications

Para gestionar el desarrollo de IoBuild de manera colaborativa, el equipo utilizó la funcionalidad de forks en GitHub. Al crear un fork, cada integrante seleccionó la cuenta donde alojar su copia del repositorio principal de CcaritaTech/IoBuild, asignó un nombre identificador y, de ser necesario, añadió una breve descripción sobre el propósito del fork. También se podía optar por clonar únicamente la rama principal antes de confirmar la acción.

Una vez creado, el fork quedaba disponible en el perfil del desarrollador como una copia independiente del repositorio original, lista para experimentar, implementar nuevas funcionalidades o realizar pruebas sin afectar directamente al código base. Este flujo permitió mantener la seguridad del repositorio upstream, al mismo tiempo que fomentó la autonomía y la organización del trabajo en equipo.
![imagen deploy 1](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Imagen_deploy1.png)
![imagen deploy 2](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Imagen_deploy2.png)
![imagen deploy 3](https://raw.githubusercontent.com/F4brizio24/Imagenes-Proyecto/refs/heads/main/Imagenes/Cap%C3%ADtulo%205/Imagen_deploy3.png)

- Applications Deployment Architecture

El proyecto IoBuild implementa una estrategia de despliegue diferenciada por componente, utilizando servicios en la nube y canales de integración y entrega continua (CI/CD). Esta aproximación optimiza recursos y mantiene una entrega continua para la landing page, el backend de servicios RESTful y la aplicación web para usuarios.

**1. Landing Page**

- **Tipo de aplicación:** Sitio web responsivo (HTML5, CSS3, JavaScript)
- **Plataforma de despliegue:** GitHub Pages
- **URL de producción:** https://ccaritatech.github.io/IoBuild-LandingPage/
- **Fuente de despliegue:** Rama `main` del repositorio `IoBuild-LandingPage`
- **Estrategia:** Despliegue automático por cada push/merge a `main`
- **Objetivo:** Publicar una página comercial e informativa con soporte multi-idioma (EN/ES) para captación de clientes e inversionistas.

**2. Backend (Web Services RESTful)**

- **Tipo de servicio:** Web API RESTful
- **Plataforma:** Servidor Cloud con proxy inverso TLS/HTTPS
- **Runtime:** .NET 8 (ASP.NET Core Web API)
- **URL de producción:** https://io-build-back.arroz.dev/swagger/index.html
- **Fuente de despliegue:** Rama `main` del repositorio `IoBuild-Backend`
- **Base de datos:** Servicio relacional administrado en la nube
- **Variables de entorno:** `ConnectionStrings:DefaultConnection`, `Jwt:Secret`, `Stripe:ApiKey`
- **Health checks:** Endpoint de verificación de estado y documentación OpenAPI Swagger activa.
- **Objetivo:** Exponer la lógica de negocio en 11 bounded contexts para autenticación, gestión de proyectos, clientes, dispositivos IoT y telemetría analítica.

**3. Web Application (Frontend)**

- **Tipo de aplicación:** Single Page Application (Vue.js / Remix)
- **Plataforma:** Infraestructura Cloud de alta disponibilidad
- **URL de producción:** https://iobuild-remix.arroz.dev/
- **Fuente de despliegue:** Rama `main` del repositorio `IoBuild-Frontend`
- **Estrategia:** Integración y despliegue continuo (CI/CD) conectado a la API de backend
- **Objetivo:** Proveer la interfaz centralizada de administración para constructoras y el portal de control para propietarios de departamentos.

**4. Base de Datos Administrada**

- **Tipo de servicio:** Database as a Service (DaaS)
- **Motor:** Base de datos relacional con soporte transaccional y pooling de conexiones
- **Características:** Backups automatizados, conexiones encriptadas SSL/TLS y aislamiento de red
- **Objetivo:** Persistencia segura y consistente de las entidades del dominio de IoBuild.

**5. Consideraciones de Configuración y CI/CD**

- Control de versiones centralizado con GitHub
- Convenciones de ramas y commits bajo GitFlow y Conventional Commits
- Entornos de staging y producción reproducibles mediante contenedores Docker
- Monitoreo de disponibilidad mediante endpoints de telemetría y logs de auditoría

**Deploy Diagram**

El diagrama de despliegue representa la topología en producción:
- Repositorio GitHub (Landing Page) -> GitHub Pages CDN -> Navegador del usuario
- Repositorio Frontend Web -> Cloud Host -> Navegador del usuario (SPA interactiva)
- Repositorio Backend -> Cloud Host (.NET 8 Web API) -> Base de Datos Cloud Relacional

![Deploy Diagram](https://i.ibb.co/WYbfcRR/Deploy-Diagram.png) 

## 6.2. Landing Page, Services & Applications Implementation.
### 6.2.1. Sprint 1

El Sprint 1 se enfocó en establecer los cimientos de la plataforma IoBuild, desarrollando secciones clave de la landing page (sobre nosotros, testimonios, contacto y FAQ), la opción de registro e internacionalización, y el dashboard inicial con acceso básico a proyectos y dispositivos. El equipo trabajó de manera colaborativa distribuyéndose las tareas según sus especialidades, logrando completar todas las user stories planificadas dentro del timeline estimado.

#### 6.2.1.1. Sprint Planning 1.

| Sprint # | Sprint 1 |
|---|---|
| **Sprint Planning Background** | |
| Date | 05/05/2026 |
| Time | 17:00 PM |
| Location | Google Meet |
| Prepared By | Fabrizio Martin Panta Castro |
| Attendees | Fabrizio Martin Panta Castro, Iker Gabriel Barturen Panez, Axel Randall Ordonez Ricaldi, Brayan Roberto Ccarita Cruz, Mateo Italo Loechle Arias |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on establishing the foundational layer of the IoBuild platform, delivering a fully functional landing page with internationalization and a basic authenticated dashboard with access to projects and connected devices. We believe it delivers immediate value to potential clients exploring the platform and to engineers who need a starting point to manage their IoT resources. This will be confirmed when the landing page is publicly deployed with EN/ES support and registered users can access the dashboard, view active projects and monitor connected devices. |
| Sprint 1 Velocity | 36 |
| Sum of Story Points | 36 |

#### 6.2.1.2. Aspect Leaders and Collaborators.

En este apartado se describen los aspectos funcionales más relevantes trabajados durante el Sprint 1 en el desarrollo de la plataforma IoBuild. Cada uno de ellos representa un subconjunto significativo dentro del alcance funcional de la solución, incluyendo componentes de interfaz, características técnicas (I18n), elementos de diseño visual y estructural (UX - UI) y preguntas frecuentes (FAQ).

Para cada aspecto se asignó un responsable principal, denominado Líder (L), encargado de la dirección técnica o de la ejecución. De igual manera, se identificaron Colaboradores (C), miembros del equipo que participaron activamente en la implementación, validación o soporte.

La Matriz LACX (Leadership and Collaboration Matrix) ofrece una representación clara y organizada de la distribución de responsabilidades, favoreciendo la trazabilidad y visibilidad del trabajo colaborativo desarrollado a lo largo del Sprint.

| Team Member                   | GitHub Username | UX-UI | Home Page   | About Us | I18n | FAQ |
|-------------------------------|-----------------|-------|-------------|----------|------|-----|
| Arizabal Condori, Jean Niels  | JeanArizabal    | C     | C           | L        | C    | C   |
| Ccarita Cruz, Roberto Brayan  | hallzyx         | C     | C           | C        | L    | C   |
| Ordoñez Ricaldi, Axel Randall | nOOmzzzz        | C     | L           | C        | C    | C   |
| Panta Castro, Fabrizio Martin | F4brizio24      | C     | C           | C        | C    | L   |
| Olivos Huaman, Yeira Shari    | YeiShari        | L     | C           | C        | C    | C   |

#### 6.2.1.3. Sprint Backlog 1.

| Story ID | ID Task | Titulo | Descripción | Estimación (Horas) | Assigned To | Status |
|---|---|---|---|---|---|---|
| US01 | TK01 | Sección Sobre Nosotros | Como visitante del sitio, quiero conocer la historia y valores de la aplicación, para tener mayor conexión y confianza con la empresa. | 2 | Fabrizio Martin Panta Castro | Done |
| US02 | TK02 | Sección testimonios del cliente | Como visitante del sitio, quiero consultar testimonios de otros clientes, para generar confianza en la propuesta de valor de la start up. | 5 | Iker Gabriel Barturen Panez | Done |
| US03 | TK03 | Acceso a información de contacto | Como visitante del sitio, quiero acceder fácilmente a la información de contacto de IoBuild, para comunicarme en caso de dudas. | 5 | Axel Randall Ordonez Ricaldi | Done |
| US04 | TK04 | Visualización de servicios principales | Como visitante del sitio, quiero conocer los servicios que ofrece IoBuild, para entender su propuesta de valor. | 3 | Brayan Roberto Ccarita Cruz | Done |
| US05 | TK05 | Opción de registro | Como visitante del sitio, quiero registrarme en la aplicación, para tener acceso a las funcionalidades de la aplicación. | 3 | Axel Randall Ordonez Ricaldi | Done |
| US06 | TK06 | Preguntas frecuentes | Como visitante del sitio, quiero consultar una sección de preguntas frecuentes, para resolver dudas comunes sin necesidad de contactar a la start up. | 5 | Mateo Italo Loechle Arias | Done |
| US07 | TK07 | Internacionalización de la landing page | Como visitante del sitio, quiero poder encontrar más de un idioma disponible, para poder elegir el idioma de mi preferencia. | 3 | Axel Randall Ordonez Ricaldi | Done |
| US08 | TK08 | Dashboard personalizado | Como usuario, quiero tener un dashboard personalizado, para visualizar la información relevante de manera rápida y eficiente. | 5 | Fabrizio Martin Panta Castro | Done |
| US09 | TK09 | Acceso a proyectos activos | Como ingeniero, quiero tener acceso a los proyectos que se encuentran activos, para poder realizar un seguimiento de su progreso y gestionar los recursos necesarios. | 5 | Iker Gabriel Barturen Panez | Done |
| US10 | TK10 | Acceso a dispositivos conectados | Como usuario, quiero tener acceso a los dispositivos conectados, para poder monitorear su estado y uso. | 5 | Mateo Italo Loechle Arias | Done |
| US11     | TK11    | Capacidad de ocupación por proyecto     | Como ingeniero, quiero tener acceso a la capacidad de ocupación de cada proyecto, para poder analizar el uso de los recursos y planificar de manera eficiente.                                                   | 5                  | Brayan Roberto Ccarita Cruz  | Done   |
| US12     | TK12    | Gráfico de consumo de energía por hora  | Como ingeniero, quiero ver un gráfico sobre la energía que se consume por hora, para poder evaluar el rendimiento energético de los proyectos en tiempo real.                                                    | 8                  | Fabrizio Martin Panta Castro | Done   |
| US13     | TK13    | Gráfico de registro de ocupación        | Como ingeniero, quiero ver un gráfico sobre el registro de ocupación, para poder analizar la evolución de la ocupación a lo largo del tiempo.                                                                    | 5                  | Iker Gabriel Barturen Panez  | Done   |
| US14     | TK14    | Resumen del proyecto                    | Como ingeniero, quiero ver un resumen sobre cada proyecto, para saber si está activo, su ubicación y cuántos departamentos están ocupados.                                                                       | 5                  | Mateo Italo Loechle Arias    | Done   |
| US19     | TK15    | Visualización del rol de la cuenta      | Como usuario, quiero poder ver el rol de mi cuenta, para entender qué permisos tengo dentro de la aplicación.                                                                                                    | 5                  | Axel Randall Ordonez Ricaldi | Done   |
| US20     | TK16    | Lista de proyectos                      | Como ingeniero, quiero ver una lista de todos mis proyectos para poder conocer el estado y detalles de cada uno.                                                                                                 | 5                  | Fabrizio Martin Panta Castro | Done   |
| US21     | TK17    | Agregar nuevo proyecto                  | Como arquitecto, quiero agregar un nuevo proyecto para poder registrar nuevos desarrollos inmobiliarios.                                                                                                         | 8                  | Iker Gabriel Barturen Panez  | Done   |
| US22     | TK18    | Detalles de un proyecto                 | Como arquitecto, quiero ver los detalles de un proyecto específico para poder revisar su información completa.                                                                                                   | 5                  | Mateo Italo Loechle Arias    | Done   |
| US23     | TK19    | Lista de clientes                       | Como Arquitecto, quiero ver una lista de todos los clientes para poder gestionar sus proyectos asociados y el estado de su cuenta.                                                                               | 5                  | Brayan Roberto Ccarita Cruz  | Done   |
| US24     | TK20    | Buscar y ordenar clientes               | Como Ingeniero, quiero poder ordenar la lista de clientes por columnas (Nombre Completo, Proyecto Asociado, Estado de Cuenta) para poder encontrar u organizar clientes rápidamente según criterios específicos. | 5                  | Axel Randall Ordonez Ricaldi | Done   |
| US26     | TK21    | Perfil del cliente | Como Ingeniero, quiero ver el perfil detallado de un cliente para poder acceder a toda su información y opciones de gestión. | 8                  | Fabrizio Martin Panta Castro | Done   |
| US28     | TK21    | Plan de suscripción actual              | Como ingeniero, quiero ver mi plan de suscripción actual y su estado para confirmar los beneficios que tengo y el costo mensual.                                                                                 | 8                  | Fabrizio Martin Panta Castro | Done   |
| US29     | TK22    | Planes de suscripción alternativos      | Como ingeniero, quiero ver planes de suscripción alternativos (Professional y Starter) para poder comparar sus precios y beneficios con mi plan actual.                                                          | 5                  | Iker Gabriel Barturen Panez  | Done   |
| US30     | TK23    | Cambio de plan                          | Como arquitecto, quiero iniciar el proceso de cambio de plan para poder seleccionar un nivel de servicio diferente que se ajuste mejor a mis necesidades.                                                        | 2                  | Mateo Italo Loechle Arias    | Done   |
| US31     | TK24    | Renovar plan activo                     | Como arquitecto, quiero renovar mi plan actual para asegurar la continuidad del servicio si estoy cerca de la fecha de expiración o si mi plan no está configurado para renovación automática.                   | 5                  | Brayan Roberto Ccarita Cruz  | Done   |
| US32     | TK25    | Cancelar plan actual                    | Como ingeniero, quiero cancelar mi plan actual para finalizar mi suscripción al término del ciclo de facturación.                                                                                                | 8                  | Axel Randall Ordonez Ricaldi | Done   |
| TS01     | TK26    | Listar proyectos por constructor        | Como desarrollador, quiero solicitar a la API que liste todos los proyectos asociados a un constructor específico, para poder mostrar la vista principal de Proyectos.                                           | 5                  | Fabrizio Martin Panta Castro | Done   |
| TS02     | TK27    | Crear un proyecto                       | Como desarrollador, quiero añadir un nuevo proyecto a través de la API para poder implementar la funcionalidad de registro de nuevos desarrollos.                                                                | 2                  | Iker Gabriel Barturen Panez  | Done   |
| TS03     | TK28    | Recuperar proyecto por ID               | Como desarrollador, quiero solicitar un proyecto por su {id} para poder mostrar la vista de detalles del proyecto.                                                                                               | 5                  | Mateo Italo Loechle Arias    | Done   |
| TS04     | TK29    | Actualizar información de un cliente    | Como desarrollador, quiero enviar a la API una solicitud para modificar los datos de un cliente existente, para poder implementar la edición de su perfil y la gestión de su estado de cuenta.                   | 8                  | Brayan Roberto Ccarita Cruz  | Done   |
| TS05     | TK30    | Eliminar un cliente                     | Como desarrollador, quiero solicitar a la API la eliminación de un cliente por su {id}, para poder implementar la funcionalidad de dar de baja clientes que ya no se utilizarán.                                 | 5                  | Axel Randall Ordonez Ricaldi | Done   |
| TS06     | TK31    | Soportar ordenación de clientes         | Como desarrollador, quiero poder enviar parámetros de ordenación a la API (nombre de columna y dirección), para poder implementar las funcionalidades de Buscar/Ordenar Clientes.                                | 8                  | Fabrizio Martin Panta Castro | Done   |
| TS07     | TK32    | Listar clientes                         | Como desarrollador, quiero solicitar a la API que liste los clientes, opcionalmente filtrados por estado o nombre, para poder mostrar la vista de la lista de clientes.                                          | 5                  | Iker Gabriel Barturen Panez  | Done   |
| TS08     | TK33    | Crear un cliente                        | Como desarrollador, quiero añadir un nuevo cliente a través de la API para poder implementar la funcionalidad de creación de clientes.                                                                           | 8                  | Mateo Italo Loechle Arias    | Done   |
| TS09     | TK34    | Recuperar cliente por ID                | Como desarrollador, quiero solicitar un recurso de cliente por su {id} para poder implementar la vista detallada del perfil.                                                                                     | 5                  | Brayan Roberto Ccarita Cruz  | Done   |
| TS16     | TK35    | Obtener suscripción actual              | Como desarrollador, quiero solicitar la información de la suscripción activa del usuario actual, para mostrar el plan, costo y beneficios en la vista principal de suscripciones.                                | 3                  | Axel Randall Ordonez Ricaldi | Done   |
| TS17     | TK36    | Listar catálogo de planes               | Como desarrollador, quiero solicitar la lista de todos los planes de suscripción disponibles en el sistema, para mostrarlos como alternativas en la interfaz de comparación.                                     | 3                  | Fabrizio Martin Panta Castro | Done   |
| TS18     | TK37    | Cambiar plan de suscripción             | Como desarrollador, quiero enviar una solicitud para actualizar el plan de suscripción del usuario, para hacer efectivo el cambio de nivel de servicio seleccionado en la interfaz.                              | 5                  | Iker Gabriel Barturen Panez  | Done   |
| TS19     | TK38    | Renovar suscripción                     | Como desarrollador, quiero solicitar la renovación de la suscripción actual, para extender la vigencia del servicio cuando el usuario confirma la acción.                                                        | 3                  | Mateo Italo Loechle Arias    | Done   |
| TS20     | TK39    | Cancelar suscripción                    | Como desarrollador, quiero solicitar la cancelación de la suscripción activa, para detener la renovación automática y finalizar el servicio al terminar el ciclo.                                                | 3                  | Brayan Roberto Ccarita Cruz  | Done   |
| TS21     | TK40    | Cambiar contraseña del usuario          | Como desarrollador, quiero enviar la contraseña actual y la nueva contraseña del usuario a la API, para actualizar sus credenciales de acceso de forma segura.                                                   | 5                  | Axel Randall Ordonez Ricaldi | Done   |
| TS22     | TK41    | Solicitar adición de correo alternativo | Como desarrollador, quiero enviar una solicitud para agregar un correo electrónico secundario, para que el backend inicie el proceso de validación y verificación de dicha cuenta.                               | 5                  | Fabrizio Martin Panta Castro | Done   |
| TS23     | TK42    | Registrar nuevo usuario                 | Como desarrollador, quiero enviar los datos de registro (nombre, email, password, rol) a la API, para crear una nueva identidad en el sistema y permitir el acceso futuro.                                       | 5                  | Iker Gabriel Barturen Panez  | Done   |
| TS24     | TK43    | Validar token de sesión                 | Como desarrollador, quiero que la API valide que el token enviado en los headers es legítimo y no ha expirado, para proteger las rutas privadas.                                                                 | 3                  | Mateo Italo Loechle Arias    | Done   |

#### 6.2.1.4. Development Evidence for Sprint Review.

Durante el Sprint 1, el equipo logró implementar exitosamente los cimientos de la plataforma IoBuild, desarrollando de manera colaborativa las secciones principales de la landing page y los bounded contexts iniciales del backend. La landing page incluyó todas las secciones planificadas con soporte de internacionalización EN/ES, mientras que el backend estableció los contextos de IAM (autenticación), Clients y Analytics con arquitectura limpia en C# / ASP.NET Core.

### Repositorio: IoBuild-LandingPage

| Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|---|---|---|---|---|
| CcaritaTech/IoBuild-LandingPage | main | b8000fb | feat: Initialize project structure and HTML boilerplate | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 402602d | feat: Add SEO metadata and social sharing configuration | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 62df9db | feat: Create responsive header and navigation menu | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 7ae5c28 | feat: Implement hero section with primary call-to-action | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 9c38cc9 | feat: Add benefits section with feature cards | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 07427c0 | feat: Develop technical features showcase section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 3707a91 | feat: Add testimonials and social proof section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | c250122 | feat: Create pricing plans and subscription section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 6eb3579 | feat: Add final CTA section to homepage | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 829ec23 | feat: Implement footer with navigation links and social media | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 8bdbb20 | feat: Add comprehensive CSS variables for theming and typography | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | daddcf4 | feat: Remove default styles for lists, buttons, links and fields | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 7909c8a | feat: Add styles for hero section and benefits section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | ea5560e | feat: Add styles for benefits, features, social proof and CTA | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | e3bfc81 | feat: Add styles for pricing cards and final CTA section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 4c88c6b | feat: Add styles for footer and mission section | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 50b3168 | feat: Add styles for mission, values, team and contact sections | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | 3de3147 | feat: Add styles for FAQ section and implement button animations | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/styles | c3a0841 | feat: Enhance responsive design across all breakpoints | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | 5b44083 | feat: add faq basic structure, fonts and links to styles | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | de8cbe4 | feat: language switches y faq section for the landing | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | c4f8eb3 | feat: planes de precio para la aplicacion y items | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | 4eee754 | feat: seccion de faq con respuestas detalladas | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/faq | 40380bc | feat: contacto con empresa y footer | 09/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/about-us | 1201440 | chore: add about us | 10/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/add-photo | feb19ed | feat: Update team member details and add new images | 10/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/add-photo | 4425d52 | feat: Replace old team photos with updated assets | 10/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/scripts | b3eb4c5 | feat: add scripts for interactive components | 11/05/2026 |
| CcaritaTech/IoBuild-LandingPage | feature/assets | a9de205 | feat: add images and translation assets | 11/05/2026 |
| CcaritaTech/IoBuild-LandingPage | main | 4a3bee5 | Merge pull request #6 from CcaritaTech/feature/assets | 11/05/2026 |

### Repositorio: IoBuild-Backend

| Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|---|---|---|---|---|
| CcaritaTech/IoBuild-Backend | feat/Analytics | 721cf8a | feat: create IAnalyticsQueryService interface for dashboard queries | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | f11a40b | feat: create IDevicesContextFacade interface for device management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 771b8b8 | feat: create IProjectsContextFacade interface for project management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | b477723 | feat: implement AnalyticsController for dashboard metrics and insights | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | b478fdf | feat: add BuilderDashboardResource record for dashboard data representation | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | e6e1bbc | feat: add DeviceHealthStatusResource record for device health data | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 2a7669b | feat: add resources for historical data points and monthly occupancy | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | ae38294 | feat: add ProjectOverviewResource and UnitDetailResource records | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 13cdaf4 | feat: implement BuilderDashboardResourceFromEntityAssembler | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/Analytics | 1c0bfc1 | feat: add HistoricalDataPointResource for analytics tracking | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 7796b7e | feat: add Client aggregate with properties and methods for client management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | a09190b | feat: add Client command and query services for client management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | a80ef30 | feat: add ClientRepository with method to find clients by email | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 266c970 | feat: add query records for retrieving clients by various criteria | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 5596a2a | feat: add GetClientsByAccountStatementQuery for client retrieval | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 931ba5f | feat: add assemblers for converting client resources to commands | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | c93500a | feat: add resource models for client creation and updates | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 42fba34 | feat: implement ClientsController with CRUD operations for clients | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 6df24e7 | feat: add EAccountStatement enum for client account status management | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/clients | 6e0ff25 | feat: add ModelBuilderExtensions for client entity configuration | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | f40058d | feat: add User aggregate root for IAM bounded context | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | e5c7162 | feat: add sign-up, sign-in, and update-password commands | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | c7a718b | feat: add user and user-detail queries | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 2ca0546 | feat: add user repository and command/query service interfaces | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 0f510e4 | feat: add hashing and token outbound service interfaces | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 40fe26d | feat: implement user command service with authentication logic | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | aefd159 | feat: implement user query service | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | ce8fe21 | feat: add BCrypt hashing service | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 199893e | feat: add JWT token service and settings | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 2e3b850 | feat: add EF Core repository and model configuration for IAM | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | cbe78d2 | feat: add request authorization middleware with custom attributes | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 104f3f8 | feat: add REST resource DTOs for IAM | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | 99f68f5 | feat: add REST resources for resource-entity transformation | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | feat/IAM | cdac147 | feat: add authentication and users REST controllers | 10/05/2026 |
| CcaritaTech/IoBuild-Backend | develop | 33033fa | Merge pull request #4 from CcaritaTech/feat/clients | 11/05/2026 |

#### 6.2.1.5. Testing Suite Evidence for Sprint Review.

Para el Sprint 1, la estrategia de testing se centró en validar los flujos principales de la plataforma: autenticación de usuarios, gestión de perfiles y acceso al dashboard. Se implementaron pruebas unitarias para los servicios core del backend y pruebas de aceptación BDD para los flujos del visitante en la landing page y del usuario registrado en la aplicación.

### Unit Tests Implementados

**1. Bounded Context IAM (Autenticación)**

- `UserCommandServiceTest`: Valida el flujo de sign-up con email, password y rol; verifica el cifrado BCrypt de contraseñas y la generación de JWT (US05)
- `UserQueryServiceTest`: Prueba la recuperación de usuarios por ID y por email
- `AuthControllerTest`: Valida los endpoints `POST /api/v1/authentication/sign-up` y `POST /api/v1/authentication/sign-in`, incluyendo respuestas 201, 200 y manejo de errores

**2. Bounded Context Profiles**

- `ProfileCommandServiceTest`: Valida la creación de perfil con campos `name`, `username`, `address`, `age`, `phoneNumber` y `photoUrl` (US08)
- `ProfileQueryServiceTest`: Prueba la consulta de todos los perfiles y filtrado por `userId`

**3. Bounded Context Clients**

- `ClientCommandServiceTest`: Valida la creación, actualización y eliminación de clientes (US09)
- `ClientQueryServiceTest`: Prueba el filtrado de clientes por `EAccountStatement` y búsqueda por email

**4. Bounded Context Analytics**

- `AnalyticsQueryServiceTest`: Valida la generación del `BuilderDashboardResource` con datos de proyectos, dispositivos y puntos históricos (US08, US10)

### Acceptance Tests (BDD - Gherkin)

**landing_page.feature (US01, US02, US03, US04, US06, US07)**

```gherkin
# language: es
Característica: Exploración del Landing Page de IoBuild
  Como visitante del sitio
  Quiero navegar por las secciones informativas
  Para conocer la propuesta de valor antes de registrarme

  Escenario: Visualizar el hero section con propuesta de valor
    Dado que soy un visitante que accede a iobuild.com
    Cuando cargo la página de inicio
    Entonces debo ver el título "Revolutionize Your Residential Projects with Smart IoT"
    Y debo ver los botones "I want it!" y "See Benefits"

  Escenario: Visualizar los beneficios principales del servicio
    Dado que soy un visitante explorando la página
    Cuando hago scroll hacia la sección de beneficios
    Entonces debo ver las 6 tarjetas de beneficio
    Y debo identificar "Integration from Construction", "Personalized Control" y "Centralized Management"

  Escenario: Consultar testimonios de clientes
    Dado que soy un visitante evaluando la plataforma
    Cuando navego a la sección "Trusted by the Best Construction Companies"
    Entonces debo ver tres testimonios de clientes reales
    Y cada testimonio debe mostrar nombre y cargo del cliente

  Escenario: Acceder a la sección de preguntas frecuentes
    Dado que soy un visitante con dudas sobre el servicio
    Cuando navego a la sección FAQ
    Entonces debo ver las preguntas frecuentes organizadas
    Y debo poder expandir cada pregunta para ver su respuesta

  Escenario: Cambiar el idioma de la landing page a español
    Dado que soy un visitante que prefiere el idioma español
    Cuando hago clic en "ES" en el selector de idioma del header
    Entonces todo el contenido de la página debe mostrarse en español
    Y el selector debe mostrar "ES" como idioma activo

  Escenario: Cambiar el idioma de la landing page a inglés
    Dado que soy un visitante que prefiere el idioma inglés
    Cuando hago clic en "EN" en el selector de idioma del header
    Entonces todo el contenido de la página debe mostrarse en inglés
    Y el selector debe mostrar "EN" como idioma activo
```

**authentication.feature (US05)**

```gherkin
# language: es
Característica: Registro e inicio de sesión en IoBuild
  Como visitante del sitio
  Quiero crear una cuenta e iniciar sesión
  Para acceder a las funcionalidades de la plataforma

  Escenario: Registrar un nuevo usuario exitosamente
    Dado que soy un visitante que quiere crear una cuenta
    Cuando envío una solicitud POST a /api/v1/authentication/sign-up
    Con los campos email "test1@example.com", password "Password123!" y role "builder"
    Entonces debo recibir una respuesta 201
    Y el cuerpo debe contener "User created successfully."

  Escenario: Iniciar sesión con credenciales válidas
    Dado que soy un usuario registrado en la plataforma
    Cuando envío una solicitud POST a /api/v1/authentication/sign-in
    Con los campos email "test1@example.com" y password "Password123!"
    Entonces debo recibir una respuesta 200
    Y el cuerpo debe contener el campo "token" con un JWT válido
    Y el cuerpo debe contener "id", "email" y "role"

  Escenario: Intentar registrarse con email ya existente
    Dado que el email "test1@example.com" ya está registrado
    Cuando intento registrarme nuevamente con el mismo email
    Entonces debo recibir una respuesta de error
    Y mi cuenta no debe ser creada nuevamente

  Escenario: Intentar iniciar sesión con contraseña incorrecta
    Dado que soy un usuario registrado en la plataforma
    Cuando envío credenciales con una contraseña incorrecta
    Entonces debo recibir una respuesta de error de autenticación
    Y no debo recibir ningún token JWT
```

**profiles.feature (US08)**

```gherkin
# language: es
Característica: Gestión de perfiles de usuario
  Como usuario registrado en IoBuild
  Quiero crear y consultar mi perfil
  Para personalizar mi experiencia en la plataforma

  Escenario: Crear un perfil de usuario exitosamente
    Dado que soy un usuario autenticado con userId 1
    Cuando envío una solicitud POST a /api/v1/profiles
    Con los campos userId, name "Ana Perez", username "anap", address "Av. Demo 123", age 29 y phoneNumber "999999999"
    Entonces debo recibir una respuesta 201
    Y el perfil creado debe contener todos los campos enviados
    Y el campo "secondEmail" debe ser null por defecto

  Escenario: Obtener todos los perfiles del sistema
    Dado que existen perfiles registrados en la plataforma
    Cuando envío una solicitud GET a /api/v1/profiles
    Entonces debo recibir una respuesta 200
    Y el cuerpo debe ser un array con todos los perfiles disponibles
    Y cada perfil debe contener id, userId, name, username, address, age y phoneNumber
```

### Evidencia de Commits de Testing

| Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|---|---|---|---|---|
| CcaritaTech/IoBuild-Backend | testing | a1f3c2e | test(IAM): add unit tests for sign-up, sign-in and JWT generation | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | b2g4d5f | test(profiles): add unit tests for profile creation and query service | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | c3h5e6g | test(bdd): configure test framework and step definitions for auth flows | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | d4i6f7h | feat(landing): add BDD tests for landing page sections US01-US07 | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | e5j7g8i | feat(auth): add BDD tests for registration and login US05 | 11/05/2026 |
| CcaritaTech/IoBuild-Backend | testing | f6k8h9j | feat(profiles): add BDD tests for profile management US08 | 11/05/2026 |

#### 6.2.1.6. Execution Evidence for Sprint Review.

Durante el Sprint 1, el equipo completó exitosamente todos los entregables planificados, estableciendo los cimientos funcionales de la plataforma IoBuild. La landing page fue desplegada con una propuesta de valor clara dirigida a constructoras residenciales, con navegación fluida entre secciones, soporte de internacionalización EN/ES funcional y diseño completamente responsivo. El backend estableció 11 bounded contexts con endpoints REST documentados y operativos.

A continuación se describen las principales vistas implementadas y verificadas durante el sprint:

**Landing Page — Hero Section:** Título principal "Revolutionize Your Residential Projects with Smart IoT" con subtítulo descriptivo de la propuesta SaaS y botones de acción "I want it!" y "See Benefits". Header con navegación a Benefits, Features, Plans, About Us y FAQ, más selector de idioma EN/ES y botón "Get Started".

**Landing Page — Sección de Beneficios:** Grilla de 6 tarjetas que presentan Integration from Construction, Personalized Control, Centralized Management, Added Value, Energy Savings y Specialized Support, cada una con ícono y descripción.

**Landing Page — Advanced Technical Features:** Sección con descripción del dashboard intuitivo compatible con móvil y escritorio, destacando control en tiempo real, configuraciones personalizables, notificaciones inteligentes y acceso multiplataforma, acompañado de imagen del "Apartment Central Hub".

**Landing Page — Testimonios:** Sección "Trusted by the Best Construction Companies" con tres tarjetas de testimonio de María González (Project Director, Premium Construction), Carlos Ramírez (General Manager, Modern Developments) y Ana Morales (CEO, Innovar Construction).

**Landing Page — CTA y Footer:** Sección final "Ready to Lead Innovation in Construction?" con botones "Create Account Now" y "View Plans", y footer con logo, descripción, redes sociales y columnas de navegación Product, Company, Support y Legal.

**Landing Page — Internacionalización:** Selector EN/ES funcional en el header con cambio dinámico de idioma en todo el contenido de la página.

# FOTOS DE LA LANDING PAGE

![Landing Page 1](https://i.ibb.co/BHfmnGmV/1.jpg)

![Landing Page 2](https://i.ibb.co/wrpyLFyc/2.jpg)

![Landing Page 3](https://i.ibb.co/yBncdVxV/3.jpg)

![Landing Page 4](https://i.ibb.co/TxZzYQ27/4.jpg)

![Landing Page 5](https://i.ibb.co/F4KcdMYm/5.jpg)

![Landing Page 6](https://i.ibb.co/jvmZydVw/6.jpg)

![Landing Page 7](https://i.ibb.co/XQxj3ZG/7.jpg)

URL del repositorio landing page: *https://github.com/CcaritaTech/IoBuild-LandingPage*

URL de la landing page desplegada: *https://ccaritatech.github.io/IoBuild-LandingPage/*

# EVIDENCIA DE EJECUCIÓN: APLICACIÓN WEB EN PRODUCCIÓN (IOBUILD WEB APP)

A continuación se presenta la evidencia de ejecución de la aplicación web de IoBuild desplegada y conectada en producción en `https://iobuild-remix.arroz.dev/`, demostrando la operatividad de los flujos de autenticación, visualización analítica de telemetría IoT, administración de proyectos residenciales, clientes, inventario de dispositivos y planes de suscripción.

URL de la aplicación web desplegada: *https://iobuild-remix.arroz.dev/*  
Credenciales de acceso de demostración: `admin@iobuild.com` / `Admin01!`

##### 1. Autenticación y Registro Multi-Rol
- **Inicio de Sesión:** Validación con JWT contra el backend en producción, redirección contextual según el rol de usuario (`builder` o `owner`).
<img src="assets/webapp/01_login.png" width="900" alt="Inicio de Sesión en Producción" />

- **Registro de Empresa Constructora:** Alta de organizaciones y profesionales de ingeniería civil y arquitectura.
<img src="assets/webapp/02_register_builder.png" width="900" alt="Registro de Constructora" />

- **Registro de Propietario / Residente:** Registro de propietarios vinculados a unidades departamentales.
<img src="assets/webapp/03_register_owner.png" width="900" alt="Registro de Propietario" />

##### 2. Segmento Constructoras — Dashboard Analítico y Gestión de Proyectos
- **Dashboard Analítico en Tiempo Real:** Métricas de consumo energético en tiempo real (kWh), tasa de ocupación departamental mensual, proyectos activos y clientes gestionados.
<img src="assets/webapp/04_builder_dashboard_full.png" width="900" alt="Dashboard Analítico de Constructora" />

- **Catálogo de Proyectos Residenciales:** Visualización en grilla interactiva de proyectos residenciales (nombre, ubicación, fecha estimada de entrega y accesos rápidos).
<img src="assets/webapp/05_builder_projects.png" width="900" alt="Catálogo de Proyectos Residenciales" />

- **Formulario de Creación de Proyecto:** Interfaz para el registro de nuevos condominios y edificios inteligentes.
<img src="assets/webapp/06_builder_new_project.png" width="900" alt="Registro de Nuevo Proyecto" />

##### 3. Segmento Constructoras — Gestión de Clientes, Dispositivos y Suscripción
- **Directorio de Clientes / Residentes:** Lista de inquilinos y propietarios registrados con asignación de departamento y estado de cuenta.
<img src="assets/webapp/07_builder_clients.png" width="900" alt="Gestión de Clientes" />

- **Inventario y Monitoreo de Dispositivos IoT:** Supervisión de sensores y actuadores con telemetría en tiempo real y estado operativo.
<img src="assets/webapp/08_builder_devices.png" width="900" alt="Gestión de Dispositivos IoT" />

- **Planes de Suscripción SaaS:** Comparativa de planes (Basic, Pro, Enterprise) e integración con pasarela de pagos Stripe.
<img src="assets/webapp/09_builder_subscription.png" width="900" alt="Planes de Suscripción SaaS" />

- **Perfil Organizacional de la Constructora:** Configuración de perfil empresarial y datos de contacto.
<img src="assets/webapp/10_builder_profile.png" width="900" alt="Perfil Organizacional" />

##### 4. Segmento Residentes — Dashboard de Propietario y Control de Dispositivos
- **Dashboard de Propietario de Departamento:** Resumen de consumo energético mensual, estado general del hogar y alertas automáticas.
<img src="assets/webapp/13_owner_dashboard.png" width="900" alt="Dashboard de Propietario" />

- **Lista de Dispositivos Departamentales:** Control remoto y monitoreo del ecosistema IoT por unidad habitacional.
<img src="assets/webapp/14_devices_list.png" width="900" alt="Dispositivos del Departamento" />

#### 6.2.1.7. Services Documentation Evidence for Sprint Review.

En esta sección se presenta la evidencia de la documentación completa de los Web Services desarrollados durante el Sprint 1, generada utilizando la especificación OpenAPI/Swagger. Los endpoints implementados cubren **11 bounded contexts** principales que establecen la arquitectura base del sistema de la plataforma IoBuild: Authentication, Users, Profiles, Clients, Projects, Units, Devices, Subscriptions, Plans, Payments y Analytics. El backend fue desarrollado en C# con ASP.NET Core y Entity Framework Core.

URL del repositorio web service: `https://github.com/CcaritaTech/IoBuild-Backend`

URL de la documentación Swagger UI desplegada: `https://io-build-back.arroz.dev/swagger/index.html`

![Swagger UI 1](https://i.ibb.co/wN38k55W/Whats-App-Image-2026-05-12-at-11-10-05-PM.jpg)

![Swagger UI 2](https://i.ibb.co/60Sf8mDL/Whats-App-Image-2026-05-12-at-11-10-14-PM.jpg)

![Swagger UI 3](https://i.ibb.co/WWnCvgz7/Whats-App-Image-2026-05-12-at-11-10-34-PM.jpg)

![Swagger UI 4](https://i.ibb.co/5W3pdfn0/Whats-App-Image-2026-05-12-at-11-10-57-PM.jpg)

![Swagger UI 5](https://i.ibb.co/DH15p27L/Whats-App-Image-2026-05-12-at-11-11-12-PM.jpg)

**Base URL:** `api/v1`

### Endpoints Documentados por Contexto

#### **1. Authentication Context** (/authentication)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /authentication/sign-in | Autentica usuario | POST | [AllowAnonymous] | SignInResource (email, password) | AuthenticatedUserResource | 200 |
| /authentication/sign-up | Crea nuevo usuario | POST | [AllowAnonymous] | SignUpResource (email, password, role) | "User created successfully." | 201 |

#### **2. Users Context** (/users)

| Endpoint | Acción | Verbo HTTP | Auth | Parámetros | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /users/{userId} | Obtiene usuario por ID | GET | [Authorize] | Path: userId (int) | UserResource | 200, 404 |
| /users | Lista todos los usuarios | GET | [Authorize] | Ninguno | [ UserResource ] | 200 |
| /users/{userId}/profiles | Obtiene perfil del usuario | GET | [Authorize] | Path: userId (int) | ProfileResource | 200, 404 |
| /users/{userId}/password | Cambia contraseña del usuario | PUT | [Authorize] | Path: userId (int), Body: UpdatePasswordResource | Sin contenido | 204, 400, 404 |

#### **3. Profiles Context** (/profiles)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /profiles | Crea nuevo perfil | POST | [Authorize] | CreateProfileResource | ProfileResource | 201, 400 |
| /profiles/{profileId} | Obtiene perfil por ID | GET | [Authorize] | Path: profileId (int) | ProfileResource | 200, 404 |
| /profiles | Lista todos los perfiles | GET | [Authorize] | Ninguno | [ ProfileResource ] | 200 |
| /profiles/{profileId} | Actualiza perfil | PUT | [Authorize] | Path: profileId (int), Body: UpdateProfileResource | ProfileResource | 200, 400, 404 |
| /profiles/second-email | Establece segundo email | POST | [Authorize] | Query: userId (int), Body: SecondEmailResource | Sin contenido | 204, 404 |

#### **4. Clients Context** (/clients)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /clients/{clientId} | Obtiene cliente por ID | GET | [Authorize] | Path: clientId (int) | ClientResource | 200, 404 |
| /clients | Lista todos los clientes | GET | [Authorize] | Ninguno | [ ClientResource ] | 200 |
| /clients | Crea nuevo cliente | POST | [Authorize] | CreateClientResource | ClientResource | 201, 400 |
| /clients/{clientId} | Actualiza cliente | PUT | [Authorize] | Path: clientId (int), Body: UpdateClientResource | ClientResource | 200, 400, 404 |
| /clients/{clientId} | Elimina cliente | DELETE | [Authorize] | Path: clientId (int) | Sin contenido | 204, 400, 404 |

#### **5. Projects Context** (/projects)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /projects/{projectId} | Obtiene proyecto por ID | GET | [Authorize] | Path: projectId (int) | ProjectResource | 200, 404 |
| /projects | Lista todos los proyectos | GET | [Authorize] | Ninguno | [ ProjectResource ] | 200 |
| /projects | Crea nuevo proyecto | POST | [Authorize] | CreateProjectResource | ProjectResource | 201, 400 |
| /projects/{projectId} | Actualiza proyecto | PUT | [Authorize] | Path: projectId (int), Body: UpdateProjectResource | ProjectResource | 200, 400, 404 |
| /projects/{projectId} | Elimina proyecto | DELETE | [Authorize] | Path: projectId (int) | Sin contenido | 204, 400, 404 |

#### **6. Units Context** (/units)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /units | Lista todas las unidades | GET | [Authorize] | Ninguno | [ UnitResource ] | 200 |
| /units/{unitId} | Obtiene unidad por ID | GET | [Authorize] | Path: unitId (int) | UnitResource | 200, 404 |
| /units | Crea nueva unidad | POST | [Authorize] | CreateUnitResource | UnitResource | 201, 400 |

#### **7. Devices Context** (/devices)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /devices | Lista todos los dispositivos | GET | Público | Ninguno | [ DeviceResource ] | 200 |
| /devices/{deviceId} | Obtiene dispositivo por ID | GET | Público | Path: deviceId (int) | DeviceResource (null si no existe) | 200 |
| /devices | Crea nuevo dispositivo | POST | Público | CreateDeviceResource | { Id: int } | 201 |
| /devices/{deviceId} | Actualiza dispositivo | PUT | Público | Path: deviceId (int), Body: UpdateDeviceResource | DeviceResource | 200 |
| /devices/{deviceId} | Elimina dispositivo | DELETE | Público | Path: deviceId (int) | Sin contenido | 204 |

#### **8. Subscriptions Context** (/subscriptions)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /subscriptions | Lista todas las suscripciones | GET | Público | Ninguno | [ SubscriptionResource ] | 200 |
| /subscriptions/{id} | Obtiene suscripción por ID | GET | Público | Path: id (int) | SubscriptionResource | 200, 404 |
| /subscriptions | Crea nueva suscripción | POST | Público | CreateSubscriptionResource | { Id: int } | 201 |
| /subscriptions/{id} | Actualiza suscripción | PUT | Público | Path: id (int), Body: UpdateSubscriptionResource | SubscriptionResource | 200 |

#### **9. Plans Context** (/plans)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /plans | Lista todos los planes | GET | Público | Ninguno | [ PlanResource ] | 200 |

#### **10. Payments Context** (/subscriptions/payments)

| Endpoint | Acción | Verbo HTTP | Auth | Body | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /subscriptions/payments/create-session | Crea sesión de checkout en Stripe | POST | Público | CreatePaymentSessionResource | PaymentSessionResource | 200, 404, 500 |
| /subscriptions/payments/confirm | Confirma pago en Stripe | POST | Público | ConfirmPaymentResource | PaymentConfirmationResource | 200, 400, 500 |

#### **11. Analytics Context** (/analytics)

| Endpoint | Acción | Verbo HTTP | Auth | Parámetros | Respuesta | Códigos |
|---|---|---|---|---|---|---|
| /analytics/metrics/{userId} | Obtiene métricas del dashboard | GET | Público | Path: userId (int), Query: role (builder\|owner) | BuilderDashboardResource | 200, 400, 404 |
| /analytics/insights | Obtiene insights históricos por proyecto | GET | Público | Query: projectId (int), metric (string), startDate (datetime opt), endDate (datetime opt) | [ HistoricalDataPointResource ] | 200, 400 |

### Ejemplos Detallados de Interacción y Response

#### **Authentication Context**

**1. POST /authentication/sign-in**

```
POST /api/v1/authentication/sign-in
Content-Type: application/json

{
  "email": "user@demo.com",
  "password": "secret"
}
```

Response (200 OK):
```json
{
  "id": 1,
  "email": "user@demo.com",
  "role": "builder",
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..."
}
```

**2. POST /authentication/sign-up**

```
POST /api/v1/authentication/sign-up
Content-Type: application/json

{
  "email": "user@demo.com",
  "password": "secret",
  "role": "builder"
}
```

Response (201 Created):
```
"User created successfully."
```

#### **Users Context**

**3. GET /users/{userId}**

```
GET /api/v1/users/1
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 1,
  "email": "user@demo.com",
  "role": "builder"
}
```

**4. GET /users**

```
GET /api/v1/users
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "email": "user@demo.com",
    "role": "builder"
  }
]
```

**5. GET /users/{userId}/profiles**

```
GET /api/v1/users/1/profiles
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 10,
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999",
  "secondEmail": "ana.alt@demo.com"
}
```

**6. PUT /users/{userId}/password**

```
PUT /api/v1/users/1/password
Content-Type: application/json
Authorization: Bearer {token}

{
  "currentPassword": "old",
  "newPassword": "new",
  "confirmNewPassword": "new"
}
```

Response (204 No Content)

#### **Profiles Context**

**7. POST /profiles**

```
POST /api/v1/profiles
Content-Type: application/json
Authorization: Bearer {token}

{
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999"
}
```

Response (201 Created):
```json
{
  "id": 10,
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999",
  "secondEmail": null
}
```

**8. GET /profiles/{profileId}**

```
GET /api/v1/profiles/10
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 10,
  "userId": 1,
  "photoUrl": "https://img.demo/1.png",
  "name": "Ana Perez",
  "username": "anap",
  "address": "Av. Demo 123",
  "age": 29,
  "phoneNumber": "999999999",
  "secondEmail": null
}
```

**9. GET /profiles**

```
GET /api/v1/profiles
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 10,
    "userId": 1,
    "photoUrl": "https://img.demo/1.png",
    "name": "Ana Perez",
    "username": "anap",
    "address": "Av. Demo 123",
    "age": 29,
    "phoneNumber": "999999999",
    "secondEmail": null
  }
]
```

**10. POST /profiles/second-email**

```
POST /api/v1/profiles/second-email?userId=1
Content-Type: application/json
Authorization: Bearer {token}

{
  "secondEmail": "ana.alt@demo.com"
}
```

Response (204 No Content)

#### **Clients Context**

**11. POST /clients**

```
POST /api/v1/clients
Content-Type: application/json
Authorization: Bearer {token}

{
  "fullName": "Empresa Demo",
  "projectId": 1,
  "projectName": "Proyecto A",
  "accountStatement": "Al dia",
  "email": "contacto@demo.com",
  "phoneNumber": "999999999",
  "address": "Av. Demo 123"
}
```

Response (201 Created):
```json
{
  "id": 5,
  "fullName": "Empresa Demo",
  "projectId": 1,
  "projectName": "Proyecto A",
  "accountStatement": "Al dia",
  "email": "contacto@demo.com",
  "phoneNumber": "999999999",
  "address": "Av. Demo 123"
}
```

**12. GET /clients/{clientId}**

```
GET /api/v1/clients/5
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 5,
  "fullName": "Empresa Demo",
  "projectId": 1,
  "projectName": "Proyecto A",
  "accountStatement": "Al dia",
  "email": "contacto@demo.com",
  "phoneNumber": "999999999",
  "address": "Av. Demo 123"
}
```

**13. GET /clients**

```
GET /api/v1/clients
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 5,
    "fullName": "Empresa Demo",
    "projectId": 1,
    "projectName": "Proyecto A",
    "accountStatement": "Al dia",
    "email": "contacto@demo.com",
    "phoneNumber": "999999999",
    "address": "Av. Demo 123"
  }
]
```

#### **Projects Context**

**14. POST /projects**

```
POST /api/v1/projects
Content-Type: application/json
Authorization: Bearer {token}

{
  "name": "Proyecto A",
  "description": "Residencial",
  "location": "Lima",
  "totalUnits": 50,
  "builderId": 1,
  "imageUrl": "https://img.demo/p.png"
}
```

Response (201 Created):
```json
{
  "id": 1,
  "name": "Proyecto A",
  "description": "Residencial",
  "location": "Lima",
  "totalUnits": 50,
  "occupiedUnits": 0,
  "status": "Planned",
  "builderId": 1,
  "createdDate": "2026-05-11T10:30:00Z",
  "imageUrl": "https://img.demo/p.png"
}
```

**15. GET /projects/{projectId}**

```
GET /api/v1/projects/1
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 1,
  "name": "Proyecto A",
  "description": "Residencial",
  "location": "Lima",
  "totalUnits": 50,
  "occupiedUnits": 0,
  "status": "Planned",
  "builderId": 1,
  "createdDate": "2026-05-11T10:30:00Z",
  "imageUrl": "https://img.demo/p.png"
}
```

**16. GET /projects**

```
GET /api/v1/projects
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "name": "Proyecto A",
    "description": "Residencial",
    "location": "Lima",
    "totalUnits": 50,
    "occupiedUnits": 0,
    "status": "Planned",
    "builderId": 1,
    "createdDate": "2026-05-11T10:30:00Z",
    "imageUrl": "https://img.demo/p.png"
  }
]
```

#### **Units Context**

**17. POST /units**

```
POST /api/v1/units
Content-Type: application/json
Authorization: Bearer {token}

{
  "projectId": 1,
  "unitNumber": "A-101",
  "ownerId": 20
}
```

Response (201 Created):
```json
{
  "id": 1,
  "projectId": 1,
  "unitNumber": "A-101",
  "ownerId": 20
}
```

**18. GET /units/{unitId}**

```
GET /api/v1/units/1
Authorization: Bearer {token}
```

Response (200 OK):
```json
{
  "id": 1,
  "projectId": 1,
  "unitNumber": "A-101",
  "ownerId": 20
}
```

**19. GET /units**

```
GET /api/v1/units
Authorization: Bearer {token}
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "projectId": 1,
    "unitNumber": "A-101",
    "ownerId": 20
  }
]
```

#### **Devices Context**

**20. POST /devices**

```
POST /api/v1/devices
Content-Type: application/json

{
  "name": "Sensor Temp",
  "type": "sensor",
  "location": "Sala",
  "macAddress": "AA:BB:CC:DD:EE:FF",
  "projectId": 1,
  "status": "online"
}
```

Response (201 Created):
```json
{
  "Id": 123
}
```

**21. GET /devices**

```
GET /api/v1/devices
```

Response (200 OK):
```json
[
  {
    "id": 123,
    "name": "Sensor Temp",
    "type": "sensor",
    "location": "Sala",
    "macAddress": "AA:BB:CC:DD:EE:FF",
    "projectId": 1,
    "status": "online"
  }
]
```

**22. GET /devices/{deviceId}**

```
GET /api/v1/devices/123
```

Response (200 OK):
```json
{
  "id": 123,
  "name": "Sensor Temp",
  "type": "sensor",
  "location": "Sala",
  "macAddress": "AA:BB:CC:DD:EE:FF",
  "projectId": 1,
  "status": "online"
}
```

#### **Subscriptions Context**

**23. POST /subscriptions**

```
POST /api/v1/subscriptions
Content-Type: application/json

{
  "builderId": 1,
  "planId": 2,
  "status": "active",
  "startDate": "2026-05-01T00:00:00Z",
  "endDate": null
}
```

Response (201 Created):
```json
{
  "Id": 55
}
```

**24. GET /subscriptions**

```
GET /api/v1/subscriptions
```

Response (200 OK):
```json
[
  {
    "id": 55,
    "builderId": 1,
    "plan": {
      "id": 2,
      "name": "Professional",
      "price": 99.99,
      "description": "Plan profesional",
      "features": ["Soporte prioritario"],
      "maxDevices": 100,
      "maxAdministrators": 5,
      "supportLevel": "priority",
      "hasAPI": true,
      "hasAnalytics": true
    },
    "status": "active",
    "startDate": "2026-05-01T00:00:00Z",
    "endDate": null
  }
]
```

**25. GET /subscriptions/{id}**

```
GET /api/v1/subscriptions/55
```

Response (200 OK):
```json
{
  "id": 55,
  "builderId": 1,
  "plan": {
    "id": 2,
    "name": "Professional",
    "price": 99.99,
    "description": "Plan profesional",
    "features": ["Soporte prioritario"],
    "maxDevices": 100,
    "maxAdministrators": 5,
    "supportLevel": "priority",
    "hasAPI": true,
    "hasAnalytics": true
  },
  "status": "active",
  "startDate": "2026-05-01T00:00:00Z",
  "endDate": null
}
```

#### **Plans Context**

**26. GET /plans**

```
GET /api/v1/plans
```

Response (200 OK):
```json
[
  {
    "id": 1,
    "name": "Starter",
    "price": 29.99,
    "description": "Plan basico",
    "features": ["Soporte email"],
    "maxDevices": 10,
    "maxAdministrators": 2,
    "supportLevel": "basic",
    "hasAPI": false,
    "hasAnalytics": false
  },
  {
    "id": 2,
    "name": "Professional",
    "price": 99.99,
    "description": "Plan profesional",
    "features": ["Soporte prioritario", "Analytics basico"],
    "maxDevices": 100,
    "maxAdministrators": 5,
    "supportLevel": "priority",
    "hasAPI": true,
    "hasAnalytics": true
  }
]
```

#### **Payments Context**

**27. POST /subscriptions/payments/create-session**

```
POST /api/v1/subscriptions/payments/create-session
Content-Type: application/json

{
  "builderId": 1,
  "planId": 2,
  "successUrl": "https://demo/success",
  "cancelUrl": "https://demo/cancel"
}
```

Response (200 OK):
```json
{
  "sessionId": "cs_test_123",
  "checkoutUrl": "https://checkout.stripe.com/...",
  "amountInCents": 2999,
  "currency": "pen",
  "planId": 2,
  "planName": "Subscription Plan"
}
```

**28. POST /subscriptions/payments/confirm**

```
POST /api/v1/subscriptions/payments/confirm
Content-Type: application/json

{
  "builderId": 1,
  "sessionId": "cs_test_123"
}
```

Response (200 OK):
```json
{
  "status": "active",
  "subscriptionId": 55,
  "isNewSubscription": true
}
```

#### **Analytics Context**

**29. GET /analytics/metrics/{userId}**

```
GET /api/v1/analytics/metrics/10?role=builder
```

Response (200 OK):
```json
{
  "totalDevices": 120,
  "onlineDevices": 110,
  "offlineDevices": 10,
  "alertsCount": 2,
  "activeProjectsCount": 5,
  "totalUnits": 200,
  "occupiedUnits": 160,
  "occupancyRate": 0.8,
  "energyEfficiencyAvg": 0.92,
  "temperatureHistory": [
    { "timestamp": "2026-05-01T00:00:00Z", "value": 22.5, "type": "temperature" }
  ],
  "energyHistory": [
    { "timestamp": "2026-05-01T00:00:00Z", "value": 15.2, "type": "energy" }
  ],
  "hourlyEnergyData": [
    { "timestamp": "2026-05-01T01:00:00Z", "value": 1.2, "type": "energy" }
  ],
  "monthlyOccupancy": [
    { "month": "May", "occupancyRate": 0.8, "year": 2026 }
  ],
  "devicesByType": { "sensor": 80, "camera": 40 },
  "projectsOverview": [
    {
      "id": 1,
      "name": "Proyecto A",
      "location": "Lima",
      "status": "Active",
      "totalUnits": 50,
      "occupiedUnits": 40,
      "occupancyRate": 0.8,
      "deviceCount": 25
    }
  ]
}
```

**30. GET /analytics/insights**

```
GET /api/v1/analytics/insights?projectId=1&metric=energy&startDate=2026-05-01&endDate=2026-05-11
```

Response (200 OK):
```json
[
  { "timestamp": "2026-05-01T00:00:00Z", "value": 12.3, "type": "energy" },
  { "timestamp": "2026-05-02T00:00:00Z", "value": 11.8, "type": "energy" }
]
```

### Modelos de Datos (Resources / DTOs)

#### **Authentication & Users**

- **SignInResource**: email, password
- **SignUpResource**: email, password, role
- **AuthenticatedUserResource**: id, email, role, token
- **UserResource**: id, email, role
- **UpdatePasswordResource**: currentPassword, newPassword, confirmNewPassword

#### **Profiles**

- **CreateProfileResource**: userId, photoUrl, name, username, address, age, phoneNumber
- **UpdateProfileResource**: photoUrl, name, username, address, age, phoneNumber
- **ProfileResource**: id, userId, photoUrl, name, username, address, age, phoneNumber, secondEmail
- **SecondEmailResource**: secondEmail

#### **Clients**

- **CreateClientResource**: fullName, projectId, projectName, accountStatement, email, phoneNumber, address
- **UpdateClientResource**: mismo que CreateClientResource
- **ClientResource**: id, fullName, projectId, projectName, accountStatement, email, phoneNumber, address

#### **Projects**

- **CreateProjectResource**: name, description, location, totalUnits, builderId, imageUrl
- **UpdateProjectResource**: name, description, location, totalUnits, occupiedUnits, status, builderId, imageUrl
- **ProjectResource**: id, name, description, location, totalUnits, occupiedUnits, status, builderId, createdDate, imageUrl

#### **Units**

- **CreateUnitResource**: projectId, unitNumber, ownerId
- **UnitResource**: id, projectId, unitNumber, ownerId

#### **Devices**

- **CreateDeviceResource**: name, type, location, macAddress, projectId, status
- **UpdateDeviceResource**: name, type, location, projectId, status
- **DeviceResource**: id, name, type, location, macAddress, projectId, status

#### **Subscriptions**

- **CreateSubscriptionResource**: builderId, planId, status, startDate, endDate
- **UpdateSubscriptionResource**: planId, status, startDate, endDate
- **SubscriptionResource**: id, builderId, plan (PlanResource), status, startDate, endDate

#### **Plans**

- **PlanResource**: id, name, price, description, features, maxDevices, maxAdministrators, supportLevel, hasAPI, hasAnalytics

#### **Payments**

- **CreatePaymentSessionResource**: builderId, planId, successUrl, cancelUrl
- **PaymentSessionResource**: sessionId, checkoutUrl, amountInCents, currency, planId, planName
- **ConfirmPaymentResource**: builderId, sessionId
- **PaymentConfirmationResource**: status, subscriptionId, isNewSubscription

#### **Analytics**

- **HistoricalDataPointResource**: timestamp, value, type
- **MonthlyOccupancyDataResource**: month, occupancyRate, year
- **ProjectOverviewResource**: id, name, location, status, totalUnits, occupiedUnits, occupancyRate, deviceCount
- **DeviceHealthStatusResource**: deviceId, deviceName, type, status, healthPercentage
- **UnitDetailResource**: unitId, unitNumber, projectName, activeDevices, connectionStatus
- **BuilderDashboardResource**: totalDevices, onlineDevices, offlineDevices, alertsCount, activeProjectsCount, totalUnits, occupiedUnits, occupancyRate, energyEfficiencyAvg, temperatureHistory, energyHistory, hourlyEnergyData, monthlyOccupancy, devicesByType, projectsOverview

**Estadísticas del Sprint**

- Total de endpoints documentados: **30**
- Bounded contexts cubiertos: **11** (Authentication, Users, Profiles, Clients, Projects, Units, Devices, Subscriptions, Plans, Payments, Analytics)
- Operaciones implementadas: GET, POST, PUT, DELETE
- Autenticación: JWT con [Authorize] en contextos de Users, Profiles, Clients, Projects, Units; Público en Devices, Subscriptions, Plans, Payments, Analytics
- Integración externa: Stripe para pagos y suscripciones
- Modelos de datos: 25+ recursos/DTOs bien tipados
- Cobertura de API: Base URL `api/v1`, respuestas HTTP correctas con códigos 200, 201, 204, 400, 404, 500

*Nota. Elaboración propia.*

#### 6.2.1.8. Software Deployment Evidence for Sprint Review.

Durante el Sprint 1 se implementó el despliegue continuo de los componentes de la plataforma IoBuild en entornos productivos basados en la nube, garantizando disponibilidad y validación inmediata con stakeholders y usuarios reales.

**1. Landing Page (`IoBuild-LandingPage`)**  
Desplegada mediante un servicio de hosting estático con integración CI/CD directa al repositorio de GitHub, activando builds y despliegues automáticos ante cada merge a la rama `main`. Permite la captación y presentación comercial de la plataforma con soporte multi-idioma (EN/ES).
- URL de despliegue: `https://ccaritatech.github.io/IoBuild-LandingPage/`

**2. Backend Web Services (`IoBuild-Backend`)**  
Desplegado en un clúster en la nube optimizado para aplicaciones ASP.NET Core (.NET 8), integrando persistencia de datos relacional administrada, cifrado de credenciales con BCrypt y autenticación de tokens JWT. Expone la documentación OpenAPI interactiva para consumo de clientes y pruebas directas.
- URL de despliegue: `https://io-build-back.arroz.dev/swagger/index.html`

**3. Aplicación Web Frontend (`IoBuild Web Application`)**  
La aplicación web de administración y monitoreo IoT se encuentra totalmente desplegada y operativa en producción, sirviendo interfaces reactivas basadas en Vue.js / Remix conectadas en tiempo real a la API de backend y a los servicios analíticos de telemetría departamental.
- URL de despliegue en producción: `https://iobuild-remix.arroz.dev/`
- Credenciales demo: `admin@iobuild.com` / `Admin01!`

Evidencia consolidada del despliegue:
- **Landing Page:** Sitio público y accesible con las secciones Hero, Benefits, Features, Testimonials, Plans, About Us, FAQ y Footer completamente funcionales.
- **Web Services Backend:** API REST activa con URL pública segura HTTPS, 32 endpoints en 11 bounded contexts respondiendo con códigos de estado estandarizados (200, 201, 204, 400, 404).
- **Web Application Frontend:** Plataforma SPA interactiva con autenticación multi-rol, paneles analíticos con gráficos Chart.js en tiempo real, catálogo de proyectos residenciales, gestión de clientes y monitoreo de dispositivos IoT.

*Nota. Elaboración propia.*

#### 6.2.1.9. Team Collaboration Insights during Sprint.

Durante el Sprint 1, el equipo de IoBuild trabajó de manera coordinada distribuyendo las responsabilidades según las especialidades de cada integrante. Se utilizó GitHub como plataforma central de control de versiones, organizando el trabajo mediante ramas por feature y pull requests para integración a las ramas principales. A continuación se detalla la contribución individual de cada miembro del equipo.

---

**Fabrizio Martin Panta Castro**

Contribución Principal:

- Inicializó la estructura base del proyecto HTML y la configuración de metadatos SEO del repositorio `IoBuild-LandingPage`.
- Implementó el header con navegación responsiva y el hero section con la propuesta de valor principal de la plataforma.
- Desarrolló las secciones de Benefits, Advanced Technical Features, Testimonials, Pricing Plans, CTA final y Footer completo con columnas de navegación y redes sociales.
- Lideró la arquitectura de contenido de la landing page, estableciendo la estructura visual y el flujo de conversión del sitio.

---

**Iker Gabriel Barturen Panez** *(GitHub: krxxg04)*

Contribución Principal:

- Implementó el sistema completo de estilos CSS del repositorio `IoBuild-LandingPage`, definiendo las variables de diseño para theming, tipografía y paleta de colores.
- Desarrolló los estilos para todas las secciones: hero, benefits, features, testimonials, pricing, FAQ y footer.
- Implementó el sistema de diseño responsivo para todos los breakpoints (móvil, tablet y escritorio).
- Actualizó las fotografías y detalles del equipo en la sección About Us.
- En el backend (`IoBuild-Backend`), implementó el bounded context de Analytics: interfaces de fachada para proyectos y dispositivos, `AnalyticsController`, recursos del dashboard (`BuilderDashboardResource`, `DeviceHealthStatusResource`, `ProjectOverviewResource`) y el assembler correspondiente.

---

**Mateo Italo Loechle Arias** *(GitHub: LowMath)*

Contribución Principal:

- Desarrolló la sección FAQ completa en `IoBuild-LandingPage` con estructura de acordeón, respuestas detalladas y planes de precio.
- Implementó el selector de idioma y la internacionalización de la landing page con soporte para español e inglés.
- En el backend (`IoBuild-Backend`), implementó el bounded context de Clients completo: aggregate root `Client`, comandos de creación/actualización/eliminación, repositorio con búsqueda por email, query service, assemblers de recursos y `ClientsController` con operaciones CRUD.

---

**Brayan Roberto Ccarita Cruz**

Contribución Principal:

- Agregó los assets de imágenes y scripts de interactividad al repositorio `IoBuild-LandingPage`.
- En el backend (`IoBuild-Backend`), implementó el bounded context de IAM completo: aggregate root `User`, comandos de sign-up/sign-in/update-password, servicios de hashing con BCrypt, servicio y configuración de JWT, repositorio con EF Core, middleware de autorización con atributos personalizados, DTOs REST y los controllers de autenticación y usuarios.

---

**Axel Randall Ordonez Ricaldi** *(GitHub: nOOmz / nOOmzzzz)*

Contribución Principal:

- Contribuyó al desarrollo de la sección About Us en el repositorio `IoBuild-LandingPage`.
- En el backend (`IoBuild-Backend`), participó en el desarrollo de múltiples bounded contexts: Profiles, Projects, Units, Devices y Payments, implementando controllers, servicios y modelos de datos para la gestión integral de recursos IoT y suscripciones.

---

*Colaboración en GitHub — IoBuild-LandingPage.*

![Commits Landing Page](https://i.ibb.co/b5sHZjSQ/commitslanding.png)

![Contribuidores Landing Page](https://i.ibb.co/nqyk8HXr/contribuidoreslanding.png)

*Colaboración en GitHub — IoBuild-Backend.*

![Commits Backend](https://i.ibb.co/SD1psTZN/commitsbackend.png)

![Contribuidores Backend](https://i.ibb.co/1SPbRrD/contribuidoresbackend.png)

# Conclusiones y recomendaciones.

## Conclusiones
- **Alineación del Dominio y Propuesta de Valor:** A través de la fase inicial de empatía, entrevistas en profundidad y la construcción de User Personas y Journey Maps, se consolidó la orientación de IoBuild hacia dos segmentos clave: empresas constructoras / administradores de condominios y residentes particulares. La delimitación de la problemática permitió enfocar la plataforma en la automatización eficiente de iluminación y la supervisión del confort ambiental (temperatura y humedad), reduciendo costos e integrando espacios compartidos y privados de forma accesible.
- **Modelado Estratégico y Desacoplamiento Arquitectónico:** La aplicación de Strategic-Level Domain-Driven Design (DDD) y el EventStorming (Big Picture y Design-Level) permitió identificar y estructurar con claridad cuatro Bounded Contexts: *Smart Project Setup*, *Service Execution and Monitoring*, *Smart Assistant* y *Energy Management*. La definición explícita de mapas de contexto (Context Mapping) y diagramas C4 (System Landscape, Context, Container y Deployment) garantiza un diseño de arquitectura escalable, desacoplado y preparado para la coexistencia de microservicios con comunicación asíncrona y telemetría de dispositivos IoT.
- **Rigurosidad en el Diseño Táctico y Trazabilidad de Requisitos:** En el nivel táctico, la implementación de la Clean Architecture / Arquitectura Hexagonal en cuatro capas (Domain, Application, Interface e Infrastructure) asegura que las reglas de negocio permanezcan independientes de tecnologías o frameworks de infraestructura. Asimismo, la especificación de 69 historias de usuario con criterios de aceptación detallados en formato Gherkin (Given-When-Then) y un Product Backlog formalmente estimado en Story Points garantiza una trazabilidad directa entre las expectativas de los interesados y el diseño técnico.
- **Viabilidad Tecnológica y Sinergia IoT:** El diseño de software integra de manera coherente el hardware perimetral (sensores DHT22 y actuadores relé conectados a microcontroladores) con servicios en la nube a través de protocolos ligeros como MQTT y HTTP REST, demostrando que la solución es técnicamente viable, robusta y económicamente sostenible para el mercado inmobiliario local.

## Recomendaciones
- **Fidelidad al Modelo de Dominio:** Se recomienda preservar la integridad de los Bounded Contexts y el Lenguaje Ubicuo durante las etapas de codificación y construcción de servicios, evitando la filtración de lógica de negocio en las capas de controladores o persistencia.
- **Estrategia de Pruebas Tempranas en Firmware y Telemetría:** Es recomendable implementar bancos de pruebas automatizadas y simuladores de dispositivos IoT antes de la integración física final, validando la estabilidad en la reconexión de red Wi-Fi, la tolerancia a fallas de conexión y la gestión de la concurrencia en la ingesta de telemetría ambiental.
- **Monitoreo de Eficiencia y Latencia:** Para los servicios encargados de la ejecución de comandos y el procesamiento de reglas de automatización, se sugiere establecer métricas estrictas de latencia y consumo de memoria, asegurando tiempos de respuesta inmediatos ante eventos ambientales o solicitudes del usuario.
- **Consistencia en la Experiencia de Usuario (UI/UX):** Al abordar los siguientes hitos de implementación de las interfaces de usuario (web y móvil), se recomienda mantener una guía de estilos visuales unificada, con especial atención a la claridad en el reporte de estados de dispositivos y la simplicidad en la configuración de zonas comunes y privadas.

<div style="page-break-before: always;"></div>

# Bibliografía

- CEELA. (2024). *Perú – Proyecto CEELA – Eficiencia energética en edificios*. Recuperado de https://proyectoceela.com/
- Digi International. (2024). *IoT Applications for Smart Buildings: Use Cases and Key Benefits*. Recuperado de https://www.digi.com/
- Domotec Perú. (2024). *Soluciones de domótica e integración residencial*. Recuperado de https://www.domotecperu.com/
- Evans, E. (2003). *Domain-Driven Design: Tackling Complexity in the Heart of Software*. Addison-Wesley Professional.
- Fowler, M. (2013). *GivenWhenThen*. Recuperado de https://martinfowler.com/bliki/GivenWhenThen.html
- JLL. (2024). *Evolución sostenible: Edificios verdes en América Latina*. Jones Lang LaSalle IP, Inc. Recuperado de https://shorturl.at/QNYAH
- Lucid Software Inc. (2024). *Lucidchart: Diagramming and Visual Collaboration*. Recuperado de https://www.lucidchart.com/
- MWF Solutions. (2024). *Automatización y eficiencia de edificios inteligentes*. Recuperado de https://mwfsolutions.pe/
- Nexoinmobiliario. (2025). *¿Vale la pena comprar un departamento con certificación LEED Lima?*. Recuperado de https://shorturl.at/aRS1m
- Orvibo Perú. (2024). *Sistemas inteligentes para el hogar y la edificación*. Recuperado de https://orviboperu.com.pe/
- Structurizr Ltd. (2024). *The C4 model for visualising software architecture*. Recuperado de https://structurizr.com/
- Vernimmen, V. (2019). *Domain-Driven Design Reference: Definitions and Pattern Summaries*. Domain Language.

<div style="page-break-before: always;"></div>

# Anexos

#### ANEXO A: Investigación y Análisis de Usuarios
Este anexo recopila las evidencias de investigación, elicitación y validación con los usuarios finales que sustentan la solución IoBuild:
- **Repositorio de la organización:** [https://github.com/IoBuild-IoT](https://github.com/IoBuild-IoT)
- **Repositorio del informe de proyecto:** [https://github.com/IoBuild-IoT/report](https://github.com/IoBuild-IoT/report)
- **Registro de entrevistas en video:**
  - Entrevista 1 (Javier Ortiz - Constructor / Arquitecto): [https://youtu.be/l9eikn4YOmw](https://youtu.be/l9eikn4YOmw)
  - Entrevista 2 (Arturo Velásquez - Constructor / Arquitecto): [https://youtu.be/zBm7PVg4cjI](https://youtu.be/zBm7PVg4cjI)
  - Entrevista 3 (Mathias Gabriel Quispe Pariona - Propietario / Residente): [https://lix.li/neaB](https://lix.li/neaB)
  - Entrevista 4 (Franco Bautista Salazar - Propietario / Residente): [https://lix.li/seV508](https://lix.li/seV508)
  - Entrevista 5 (Alex Moreno - Constructor / Arquitecto): [https://youtu.be/M1nDEEuHymI](https://youtu.be/M1nDEEuHymI)

<div style="page-break-before: always;"></div>

#### ANEXO B: Documentación de Diseño, Requisitos y Arquitectura
Este anexo incluye los enlaces hacia los tableros de trabajo colaborativo, artefactos de diseño UX y diagramas arquitectónicos de soporte:
- **Lean UX Canvas:** [https://url-shortener.me/16XS](https://url-shortener.me/16XS)
- **Repositorio de imágenes y diagramas de arquitectura:** [https://github.com/F4brizio24/Imagenes-Proyecto](https://github.com/F4brizio24/Imagenes-Proyecto)
- **Impact Mapping:** [https://tinyurl.com/ytzz3rdn](https://tinyurl.com/ytzz3rdn)


