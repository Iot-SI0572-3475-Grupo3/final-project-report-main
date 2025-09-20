# <center>Informe del Trabajo Final</center>

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>1ASI0572 - Desarrollo de Soluciones IoT - 3475</strong><br>
    <strong>Profesor: Marco Antonio Leon Baca </strong><br>
    <br>INFORME
</p>

<center>

#### Startup: **SmartPark**

#### Product: **SmartPark**

</center>

## Team  Members:

<div align="center">

|               Member                |    Code    |
| :---------------------------------: | :--------: |
| Salgado Luna, Fernando Brian  | u202212023 |
| Ruiz Blas, Luciano Stefano  | U20211F978 |
| Linares Tejada, Leonardo Félix Jesús  | u202211168 |
| Chávez Rojas, Carlos Raúl Guillermo  | u201910317 |
| Aquije Quiroga, Luis Enrique  | u202114936 |

</div>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="6">V1</td>
      <td>08/09/2025</td>
      <td>Luciano Ruiz</td>
      <td>
        <ul>
          <li>Creación de plantilla en readme</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>18/09/2025</td>
      <td>Luciano Ruiz</td>
      <td>
        <ul>
          <li>Implementación del context mapping</li>
          <li>Implementacion student outcome</li>
          <li>Implementación de diagramas c4</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>18/09/2025</td>
      <td>Leonardo Linares</td>
      <td>
        <ul>
          <li>Analisis Competitivo, Impact y Journey Mappings</li>
          <li>Base de datos, Diagrama de clases and Component C4 para Time Tracking y Penalty Management BC</li>
          <li>Domain, Interface, Application e Infrastructure Layers</li>
          <li>Implementacion student outcome</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>xx</td>
      <td>xx</td>
      <td>
        <ul>
          <li>xx</li>
          <li>xx</li>
          <li>xx</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>xx</td>
      <td>xx</td>
      <td>
        <ul>
          <li>xx</li>
          <li>xx</li>
          <li>xx</li>
          <li>xx</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>xx</td>
      <td>xx</td>
      <td>
        <ul>
          <li>xx</li>
          <li>xx</li>
          <li>xx</li>
          <li>xx</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
  </tbody>
</table>


---

# Project Report Collaboration Insights

En esta sección, regirstraremos los cambios y logros que se completaron en cada entrega del reporte.

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
   * [1.1. Startup Profile](#11-startup-profile)
      + [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      + [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
   * [1.2. Solution Profile](#12-solution-profile)
      + [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      + [1.2.2. Lean UX Process](#122-lean-ux-process)
         - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
         - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
         - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
         - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
   * [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation-analysis)
   * [2.1. Competidores](#21-competidores)
      + [2.1.1. Análisis competitivo](#211-análisis-competitivo)
      + [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
   * [2.2. Entrevistas](#22-entrevistas)
      + [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
      + [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
      + [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
   * [2.3. Needfinding](#23-needfinding)
      + [2.3.1. User Personas](#231-user-personas)
      + [2.3.2. User Task Matrix](#232-user-task-matrix)
      + [2.3.3. User Journey Mapping](#233-user-journey-mapping)
      + [2.3.4. Empathy Mapping](#234-empathy-mapping)
   * [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
   * [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
   * [3.1. User Stories](#31-user-stories)
   * [3.2. Impact Mapping](#32-impact-mapping)
   * [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
   * [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
      + [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
         - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
         - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
         - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
      + [4.1.2. Context Mapping](#412-context-mapping)
      + [4.1.3. Software Architecture](#413-software-architecture)
         - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
         - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
         - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
         - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
   * [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
      + [4.2.1. Bounded Context: Identity and Access Management (IAM)](#421-bounded-context-identity-and-access-management-iam)
         - [4.2.1.1. Domain Layer](#4211-domain-layer)
         - [4.2.1.2. Interface Layer](#4212-interface-layer)
         - [4.2.1.3. Application Layer](#4213-application-layer)
         - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
         - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
            * [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
      + [4.2.2. Bounded Context: Reservation Management](#421-bounded-context-reservation-management)
         - [4.2.2.1. Domain Layer](#4221-domain-layer)
         - [4.2.2.2. Interface Layer](#4222-interface-layer)
         - [4.2.2.3. Application Layer](#4223-application-layer)
         - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
         - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
            * [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
      + [4.2.3. Bounded Context: Space & IoT Management](#423-bounded-context-space-&-iot-management)
         - [4.2.3.1. Domain Layer](#4231-domain-layer)
         - [4.2.3.2. Interface Layer](#4232-interface-layer)
         - [4.2.3.3. Application Layer](#4233-application-layer)
         - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
         - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
            * [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
      + [4.2.4. Bounded Context: Time Tracking](#424-bounded-context-time-tracking)
         - [4.2.4.1. Domain Layer](#4241-domain-layer)
         - [4.2.4.2. Interface Layer](#4242-interface-layer)
         - [4.2.4.3. Application Layer](#4243-application-layer)
         - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
         - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
            * [4.2.4.6.2. Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)
      + [4.2.5. Bounded Context: Penalty Management](#425-bounded-context-penalty-management)
         - [4.2.5.1. Domain Layer](#4251-domain-layer)
         - [4.2.5.2. Interface Layer](#4252-interface-layer)
         - [4.2.5.3. Application Layer](#4253-application-layer)
         - [4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)
         - [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4256-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams)
            * [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram)
      + [4.2.6. Bounded Context: Analytics & Reporting](#426-bounded-context-analytics-&-reporting)
         - [4.2.6.1. Domain Layer](#4261-domain-layer)
         - [4.2.6.2. Interface Layer](#4262-interface-layer)
         - [4.2.6.3. Application Layer](#4263-application-layer)
         - [4.2.6.4. Infrastructure Layer](#4264-infrastructure-layer)
         - [4.2.6.5. Bounded Context Software Architecture Component Level Diagrams](#4265-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.6.6. Bounded Context Software Architecture Code Level Diagrams](#4266-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.6.6.1. Bounded Context Domain Layer Class Diagrams](#42661-bounded-context-domain-layer-class-diagrams)
            * [4.2.6.6.2. Bounded Context Database Design Diagram](#42662-bounded-context-database-design-diagram)
      + [4.2.7. Bounded Context: Notification](#427-bounded-context-notification)
         - [4.2.7.1. Domain Layer](#4271-domain-layer)
         - [4.2.7.2. Interface Layer](#4272-interface-layer)
         - [4.2.7.3. Application Layer](#4273-application-layer)
         - [4.2.7.4. Infrastructure Layer](#4274-infrastructure-layer)
         - [4.2.7.5. Bounded Context Software Architecture Component Level Diagrams](#4275-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.7.6. Bounded Context Software Architecture Code Level Diagrams](#4276-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.7.6.1. Bounded Context Domain Layer Class Diagrams](#42761-bounded-context-domain-layer-class-diagrams)
            * [4.2.7.6.2. Bounded Context Database Design Diagram](#42762-bounded-context-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-ui/ux-design)
   * [5.1. Style Guidelines](#51-style-guidelines)
     + [5.1.1. General Style Guidelines](#511-general-style-guidelines)
     + [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
   * [5.2. Information Architecture](#52-information-architecture)
     + [5.2.1. Organization Systems](#521-organization-systems)
     + [5.2.2. Labeling Systems](#522-labeling-systems)
     + [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
     + [5.2.4. Searching Systems](#524-searching-systems)
     + [5.2.5. Navigation Systems](#525-navigation-systems)
   * [5.3. Landing Page UI Design](#53-landing-page-ui-design)
     + [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
     + [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
   * [5.4. Applications UX/UI Design](#54-applications-uxui-design)
     + [5.4.1. Applications Wireframes](#541-applications-wireframes)
     + [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
     + [5.4.2. Applications Mock-ups](#542-applications-mock-ups)
     + [5.4.3. Applications User Flow Diagrams](#543-applications-user-flow-diagrams)
   * [5.5. Applications Prototyping](#55-applications-prototyping)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
   * [6.1. Software Configuration Management](#61-software-configuration-management)
      + [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration) 
      + [6.1.2. Source Code Management](#612-source-code-management)
      + [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
      + [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
   * [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
      + [6.2.X. Sprint n](#62x-sprint-n)
         - [6.2.X.1. Sprint Planning n](#62x1-sprint-planning-n)
         - [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
         - [6.2.X.3. Sprint Backlog n](#62x3-sprint-backlog-n)
         - [6.2.X.4. Development Evidence for Sprint Review](#62x4-development-evidence-for-sprint-review)
         - [6.2.X.5. Testing Suite Evidence for Sprint Review](#62x5-testing-suite-evidence-for-sprint-review)
         - [6.2.X.6. Execution Evidence for Sprint Review](#62x6-execution-evidence-for-sprint-review)
         - [6.2.X.7. Services Documentation Evidence for Sprint Review](#62x7-services-documentation-evidence-for-sprint-review)
         - [6.2.X.8. Software Deployment Evidence for Sprint Review](#62x8-software-deployment-evidence-for-sprint-review)
         - [6.2.X.9. Team Collaboration Insights during Sprint](#62x9-team-collaboration-insights-during-sprint)
   * [6.3. Validation Interviews](#63-validation-interviews)
      + [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
      + [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
      + [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
   * [6.4. Video About-the-Product](#64-video-about-the-product)
- [Conclusiones](#conclusiones)
   * [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
   * [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome
En Ingeniería de Software, el logro de curso contribuye a alcanzar el:

ABET – EAC - Student Outcome 5: La capacidad de funcionar efectivamente en un
equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de
colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

<table>
  <tr>
    <th>Criterio Especifico</th>
    <th>Acciones Realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>
    <td>
        <p>
        TB1:
        <p/>
        Luciano Ruiz: Distribui tareas equitativas y por fortalezas de cada miembro del equipo. Además, proporcione apoyo a mis companeros de equipo en sus tareas para un mejor desenvolvimiento.
        <p/>
        Fernando: Colaboré en el desarrollo de los Bounded Contexts de Identity & Access Management y Parking Management, además de participar activamente en la planificación y coordinación del equipo para asegurar el cumplimiento de los objetivos del proyecto.
        <p/>
        Leonardo: A partir de la reunion de equipo, logre hacer mis partes del los capitulos I-III, además de explayar a fondo los Bounded Contexts de Time Tracking y Penalty Management.
        <p/>
        Carlos: Contribuí en el desarrollo de los Bounded Contexts de Analytics & Reporting y Notification, además de participar en la elaboración de los diagramas C4 y la arquitectura del sistema para garantizar una solución robusta y escalable.
        <p/>
        Luis Aquije: Participé en el desarrollo de los Bounded Contexts de Reservation Management y Parking Management, además de colaborar en la definición de la arquitectura del sistema y la integración de los componentes IoT.
    </td>
    <td>
        TB1: En esta entrega logramos trabajar en equipo, apoyándonos mutuamente y colaborando en la redacción del informe. Cada uno de los integrantes participó activamente en el desarrollo de las secciones asignadas, lo que permitió un avance significativo en el proyecto. La comunicación constante y la disposición para ayudar a los demás fueron clave para el éxito de esta entrega.</p>
     </td>
  </tr>
  <tr>
    <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
    <td>
      <p>
        TB1:
        <p/>
        Luciano Ruiz: Estableci los sprints, participe en el capitulo IV apoyando en la planificación de nuestra solución.
        <p/>
        Fernando: Establecí las bases para el desarrollo de la interfaz de usuario y la experiencia móvil, además de coordinar las tareas de frontend y backend para asegurar una integración fluida entre los componentes del sistema.
        <p/>
        Leonardo: Ayude en la elaboración del capitulo IV con los Bounded Contexts de Time Tracking y Penalty Management, y delimite el analisis competitivo, los journey e impact mappings y analisis de entrevistas
        <p/>
        Carlos: Planifiqué y estructuré la arquitectura de datos y los sistemas de reportes, además de establecer las métricas y KPIs necesarios para el monitoreo y análisis del rendimiento del sistema.
        <p/>
        Luis Aquije: Coordiné la integración de los sensores IoT con la plataforma, además de establecer los protocolos de comunicación y las interfaces necesarias para el funcionamiento del sistema de estacionamiento inteligente.
    <td>
    TB1: En esta entrega, logramos establecer un entorno colaborativo e inclusivo, donde cada miembro del equipo pudo expresar sus ideas y contribuir al desarrollo del proyecto. La planificación de tareas y el cumplimiento de objetivos fueron fundamentales para avanzar en la redacción del informe y en la elaboración de los diagramas y documentos requeridos. La comunicación constante y el uso del tablero Kanban facilitaron la organización y el seguimiento de las tareas asignadas.
    </p>
  </td>
  </tr>
</table>

# Capítulo I: Introducción

## 1.1. Startup Profile

En esta sección se ofrece una descripción del startup y se detallan los perfiles de los integrantes del equipo.

### 1.1.1. Descripción de la Startup

SmartParking Solutions es una startup enfocada en el desarrollo de soluciones de Internet de las Cosas (IoT) aplicadas al ámbito universitario. Su producto principal, SafePark, es un sistema automatizado de reserva gratuita de estacionamientos universitarios, diseñado para optimizar el uso de espacios en campus mediante sensores IoT, una aplicación móvil y un dashboard administrativo web.

El objetivo de la startup es ofrecer una solución tecnológica que simplifique la experiencia de los conductores y, al mismo tiempo, optimice la gestión de los administradores de estacionamientos. SafePark busca reducir el tiempo perdido en la búsqueda de espacios, incrementar la seguridad en la operación y generar un modelo de negocio escalable que aporte valor a usuarios, empresas y ciudades.

Nuestra visión es consolidarnos como un referente en el ámbito de la movilidad inteligente en Latinoamérica, contribuyendo al desarrollo de ciudades más sostenibles, organizadas y seguras, donde el estacionamiento deje de ser un problema cotidiano y se convierta en un proceso ágil y confiable.

Nuestra misión es brindar un sistema de estacionamiento automatizado que integre sensores IoT, plataformas móviles y paneles de control web, para ofrecer a los usuarios una experiencia rápida, transparente y segura. Entre sus funcionalidades destaca la posibilidad de reservar previamente un espacio con un tiempo límite de llegada, mientras que los administradores cuentan con herramientas en tiempo real para supervisar, controlar y maximizar el uso de los espacios, garantizando eficiencia operativa y rentabilidad.

### 1.1.2. Perfiles de integrantes del equipo

| Miembros del Equipo                  | Código Estudiante | Carrera                | Descripción | Imagen |
|-------------------------------------|------------------|-----------------------|-------------|--------|
| Aquije Quiroga, Luis Enrique         | U202114936       | Ingeniería de Software |             | <img src="assets/img/Chapter-I/.png" width="80">    |
| Chávez Rojas, Carlos Raúl Guillermo  | U201910317       | Ingeniería de Software |Tengo 23 años y estudio la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me apasiona el mundo digital y la capacidad de la tecnología para solucionar problemas y crear nuevas experiencias. Soy una persona proactiva, responsable y con gran capacidad de aprendizaje. Tengo un fuerte interés por la investigación y la innovación, y estoy siempre buscando nuevas formas de mejorar mis habilidades y conocimientos.| <img src="assets/img/Chapter-I/.png" width="80">       |
| Linares Tejada, Leonardo Félix Jesús | U202211168       | Ingeniería de Software | Mi nombre es Leonardo Linares, tengo 20 años y estoy en el 8vo ciclo de la UPC, estudiando para ser un Ingeniero de Software. Actualmente, tengo conocimientos sobre lenguajes y tecnologias como Python, C++, C#, HTML, JavaScript, MySQL, etc. |  <img src="assets/img/Chapter-I/yo.png" width="80">      |
| Ruiz Blas, Luciano Stefano           | U20211F978       | Ingeniería de Software |             |   <img src="assets/img/Chapter-I/.png" width="80">     |
| Salgado Luna, Fernando Brian         | U202212023       | Ingeniería de Software | Soy Fernando Salgado, tengo 20 años y me apasiona la tecnología. Tengo experiencia en desarrollo frontend y backend, trabajando con lenguajes y tecnologías como Python, C++, C#, Java, HTML, CSS, JavaScript, MySQL, así como frameworks de frontend como Vue.js y Angular. Disfruto resolviendo problemas y buscando soluciones prácticas que contribuyan a los proyectos en los que participo. | <img src="assets/img/Chapter-I/.png" width="80"> |

<br>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### Uso de la técnica The 5'W's w Y 2'H's

| LAS 5W y 2H | Pregunta                                   | Descripción                                                                                                                                                                                                                                                                                                                                                                      |
|-------------|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| What?       | ¿Cuál es el problema?                      | La falta de disponibilidad y control en los estacionamientos universitarios genera que los conductores pierdan tiempo dando vueltas en busca de espacios libres. Esto ocasiona estrés, congestión vehicular dentro del campus y dificulta el trabajo de los administradores, quienes no cuentan con herramientas para gestionar de forma eficiente. |
| When?       | ¿Cuándo surge el problema?                 | Se presenta principalmente en las horas punta de ingreso y salida de clases, cuando la demanda de estacionamiento supera la capacidad. También ocurre en situaciones inesperadas, como ocupación irregular de espacios o ausencia de información actualizada sobre la disponibilidad. |
| Where?      | ¿Dónde ocurren los problemas?              | En los estacionamientos de campus universitarios, especialmente en zonas de mayor afluencia. El problema se manifiesta en la búsqueda de espacios, la falta de señalización clara y la ausencia de datos en tiempo real. |
| Who?        | ¿A quién le afecta el problema?            | A los conductores universitarios (estudiantes, docentes y personal administrativo), que pierden tiempo y llegan tarde a sus actividades. También a los administradores de los estacionamientos, que enfrentan desorden operativo, quejas constantes y poca capacidad de control. |
| Why?        | ¿Por qué sucede el problema?               | Porque los procesos son manuales y no hay automatización en la detección de espacios libres. No existe control preciso de los tiempos de uso ni mecanismos de reserva anticipada, lo que genera errores, saturación y dependencia exclusiva de la disponibilidad inmediata. |
| How?        | ¿Cómo se diferencia del estado óptimo?     | En un estado ideal, los usuarios encontrarían un espacio de forma rápida y ordenada, podrían planificar su estacionamiento sin incertidumbre y los administradores contarían con visibilidad en tiempo real. Actualmente, predominan las demoras, la desorganización y la falta de control operativo. |
| How Much?   | ¿Cuál es la magnitud del problema?         | Los inconvenientes ocurren varias veces en un mismo día, especialmente en semanas de alta carga académica. A nivel mensual, se acumulan pérdidas significativas de tiempo para los usuarios e ineficiencias operativas para la universidad, convirtiéndose en un problema constante. |

<br>

### 1.2.2. Lean UX Process

A través de la metodología Lean UX podemos desarrollar y comprobar propuestas de solución que priorizan al usuario, concentrándonos en generar valor mediante procesos ágiles y optimizados. En este apartado se identifican los desafíos fundamentales que experimentan los usuarios, las premisas comerciales y de experiencia de usuario, junto con las hipótesis que orientarán la construcción del sistema SafePark. Esta aproximación garantiza que todas las decisiones de diseño se fundamenten en datos concretos y en la verificación temprana con los usuarios objetivo.

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement:**  
Actualmente, los estacionamientos universitarios continúan funcionando bajo modelos tradicionales donde los procesos son manuales y poco prácticos. Los conductores universitarios suelen perder tiempo buscando un espacio disponible, y los administradores carecen de herramientas tecnológicas que les permitan tener control en tiempo real de la operación.  
La mayoría de las soluciones disponibles se limitan a ofrecer sistemas básicos de acceso, sin integrar una experiencia completa que automatice la asignación de espacios, el guiado al conductor, la reserva previa gratuita de un lugar con un tiempo límite de llegada.  

**SafePark**, desarrollado por *SmartParking Solutions*, busca cubrir esta necesidad a través de un sistema que combina **sensores IoT**, una **aplicación móvil para usuarios** y un **panel de control web para administradores**. Con esta propuesta, se pretende optimizar la experiencia del conductor, reducir los tiempos de búsqueda y facilitar la gestión de los espacios en un solo ecosistema digital gratuito para la comunidad universitaria.  

El punto de partida se orientará a **estacionamientos de campus universitarios**, donde la rapidez y la conveniencia son factores críticos tanto para usuarios como para operadores.  
El éxito se reflejará en indicadores como una reducción del tiempo promedio de búsqueda de estacionamiento, un mayor aprovechamiento de los espacios disponibles y la satisfacción de los administradores al contar con reportes claros sobre ocupación.  

---

**Dominio:**  
SafePark se ubica dentro del dominio de la **gestión inteligente de estacionamientos universitarios**, un área donde convergen la movilidad en campus, la experiencia del usuario y las tecnologías emergentes como el **Internet de las Cosas (IoT)**.  
Su enfoque está en digitalizar la operación diaria de estacionamientos universitarios, ofreciendo **automatización, control remoto, opciones de reserva previa gratuita con tiempos límite de llegada y escalabilidad en la administración**.  

---

**Segmentos de Clientes:**  
- **Conductores universitarios:** buscan estacionar rápido, con un proceso sencillo, la posibilidad de asegurar un espacio gratuito antes de llegar.  
- **Administradores:** necesitan herramientas de monitoreo en tiempo real, control centralizado y gestión de reservas que se liberen automáticamente si no se cumplen los tiempos establecidos.  

---

**Puntos de Dolor:**  
- **Conductores universitarios:** pérdida de tiempo en la búsqueda de espacios, procesos engorrosos y la incertidumbre de no saber si encontrarán un lugar disponible al llegar al campus.  
- **Administradores:** operaciones manuales que generan errores, falta de métricas y poca eficiencia en la rotación de vehículos, especialmente cuando no se controla adecuadamente la ocupación de espacios reservados.  

---

**Visión / Estrategia:**  
La visión de **SafePark** es ofrecer una **solución integral de estacionamiento universitario** que logre simplificar la vida de los conductores universitarios y al mismo tiempo brinde un control más inteligente a los administradores.  
La estrategia se centra en combinar **sensores IoT** con **interfaces intuitivas** que hagan posible una experiencia fluida, confiable y escalable. Entre sus diferenciadores está la **gestión eficiente de reservas gratuitas**, que garantiza disponibilidad ordenada en contextos universitarios de alta demanda.  

---

**Segmento Inicial:**  
El lanzamiento inicial se enfocará en **estacionamientos de campus universitarios**. Este segmento permitirá validar rápidamente la propuesta, mostrar beneficios tangibles en la operación, como reducción de la búsqueda de espacios y cumplimiento de tiempos de reserva y, a partir de allí, **escalar la solución hacia otros campus universitarios**.  

<br>

#### 1.2.2.2. Lean UX Assumptions

## **Features**

### Para los Conductores universitarios (estudiantes, docentes y personal administrativo):
- Registro e inicio de sesión con correo institucional UPC para garantizar acceso seguro.  
- Creación de reservas gratuitas y anticipadas (máx. 24h antes), sin definir hora de salida.  
- Confirmación automática de llegada y salida gracias a sensores IoT en cada espacio.  
- Visualización en tiempo real del estado de los estacionamientos disponibles.  
- Consulta del tiempo de uso en vivo y del historial de sesiones pasadas.  
- Recepción de notificaciones sobre reservas activas, ventanas de llegada, finalización y penalizaciones.  
- Configuración personalizada de notificaciones y recordatorios.  

### Para los Administradores de estacionamiento:
- Panel de control en tiempo real con la ocupación de los espacios y el estado de las reservas.  
- Gestión de usuarios: visualización de perfiles, aplicación de suspensiones o reactivaciones automáticas y manuales.  
- Configuración de reglas operativas (ventana de llegada, límite de reservas, penalizaciones, anticipación máxima).  
- Generación de reportes automáticos (diarios, semanales y mensuales), exportables a PDF/Excel.  
- Monitoreo de alertas sobre usuarios suspendidos, incidencias técnicas o espacios en mantenimiento.  
- Estadísticas de eficiencia para optimizar el uso de espacios y reducir costos operativos.  

---

## **Business Outcomes**
- **Incremento de la rotación de espacios:** Se espera al menos un 25% más de disponibilidad efectiva gracias a la liberación automática de reservas no utilizadas en 30 minutos.  
- **Optimización del uso de espacios:** Los administradores proyectan un mejor aprovechamiento de espacios al reducir espacios ociosos.  
- **Reducción de costos operativos:** Con la automatización, se estima un 30% menos de incidencias manuales en asignación de espacios.  
- **Reputación y competitividad:** Los campus universitarios que implementen **SafePark** serán percibidos como modernos, confiables y organizados, mejorando la experiencia estudiantil.  

---

## **User Assumptions**

**¿Quién es el usuario?**  
- Conductores universitarios (estudiantes, docentes y personal administrativo) que buscan estacionar rápido y sin incertidumbre en el campus.  
- Administradores de estacionamientos universitarios que requieren control en tiempo real.  

**¿Dónde entra nuestro producto en su vida o trabajo?**  
- Para los conductores universitarios: como una **aplicación móvil** que permite ver disponibilidad en tiempo real y reservar sin costo.  
- Para los administradores: como un **panel web de control** con métricas de ocupación, gestión de reservas y liberación automática.  

**¿Cuál es el problema que nuestro producto soluciona?**  
- Pérdida de tiempo en la búsqueda de estacionamiento en campus.  
- Espacios reservados pero no ocupados que quedan bloqueados.  
- Procesos manuales de control, que generan errores y pérdidas de eficiencia.  

**¿Cómo y cuándo nuestro producto es usado?**  
- Durante la llegada al campus universitario en horarios académicos.  
- Antes de salir de casa, mediante la reserva anticipada gratuita en la app.  
- Al finalizar el uso del estacionamiento, con liberación manual del espacio.  

**¿Qué características son importantes?**  
- Precisión en la detección de espacios libres con **sensores IoT**.  
- Notificaciones claras sobre el tiempo límite de reserva y cancelación automática.  
- Proceso completamente gratuito para usuarios universitarios.  
- Reportes en tiempo real para administradores.  

---

## **User Outcomes & Benefits**

**Para los conductores:**  
- Ahorro de tiempo y reducción del estrés al tener un espacio asegurado gratuitamente.  
- Proceso transparente sin costos ocultos.  
- Se espera que al menos el 70% de los usuarios frecuentes valoren la función de reserva como la característica principal.  

**Para los administradores:**  
- Gestión centralizada y menos errores manuales.  
- Liberación automática de espacios no ocupados tras 30 minutos.  
- Se proyecta que el 60% de los administradores reduzcan incidencias operativas en el primer trimestre.  

---

## **Business Assumptions**
- Los usuarios universitarios aceptarán la política de cancelación automática si se comunica con claridad en la app.  
- Los administradores universitarios percibirán valor en la reducción de espacios ociosos y mayor control en tiempo real.  
- El modelo de negocio enfocado en el valor agregado para la universidad será percibido como una inversión rentable.  
- La integración de IoT y software será percibida como una mejora significativa en la experiencia del campus.

  <br>

#### 1.2.2.3. Lean UX Hypothesis Statements.

Usando la información recolectada en los Business Outcomes, Usuarios, Beneficios y Features. Podemos formular nuestras hipótesis, cada una centrada en un Feature a desarrollar.

---

**Hipótesis 1**  
Creemos que si la aplicación permite reservar un espacio gratuito con límite de llegada de 30 minutos,  
esto logrará aumentar la confianza de los conductores universitarios y reducir la incertidumbre de disponibilidad,  
y lo sabremos cuando al menos el **70% de los usuarios frecuentes** realice reservas anticipadas en lugar de depender únicamente de la disponibilidad inmediata.  

---

**Hipótesis 2**  
Creemos que si el sistema cancela automáticamente las reservas no utilizadas y libera el espacio,  
esto logrará mejorar la rotación de vehículos y el aprovechamiento de la capacidad,  
y lo sabremos cuando la **tasa de ocupación efectiva aumente en un 25%** respecto al modelo tradicional.  

---

**Hipótesis 3**  
Creemos que si los administradores tienen acceso a un panel web con reportes de ocupación y reservas activas,  
esto logrará mejorar la toma de decisiones y la eficiencia operativa,  
y lo sabremos cuando al menos el **60% de los administradores** use los reportes semanalmente para gestionar sus estacionamientos.  

---

**Hipótesis 4**  
Creemos que si el servicio se ofrece de forma completamente gratuita para la comunidad universitaria,  
esto logrará mayor adopción y satisfacción de los usuarios,  
y lo sabremos cuando el **80% de los conductores universitarios** prefiera usar **SafePark** frente a buscar espacios manualmente.  

---

**Hipótesis 5**  
Creemos que si la aplicación envía notificaciones claras y anticipadas sobre el vencimiento del tiempo límite de reserva,  
esto logrará reducir la frustración de los usuarios y mejorar la aceptación de la política,  
y lo sabremos cuando el **90% de los usuarios** confirme haber entendido las alertas y se reduzcan quejas por cancelaciones inesperadas.  

<br>

#### 1.2.2.4. Lean UX Canvas

Se ha utilizado el Lean UX Canvas como una herramienta estratégica clave para estructurar y validar ágilmente el concepto del producto. Este enfoque permite al equipo identificar con claridad el problema de negocio, definir a los usuarios objetivo, formular hipótesis comprobables y diseñar los experimentos mínimos necesarios para aprender e iterar rápidamente sobre la solución. De esta manera, se reduce significativamente el riesgo de desarrollar funcionalidades que no generen un valor real para el usuario final.

<img src="./assets/img/Chapter-I/lean-ux-canvas.png">

<br>

## 1.3. Segmentos objetivo

El sistema **SafePark** está enfocado en los principales actores que enfrentan directamente la problemática de disponibilidad y gestión eficiente de estacionamientos en campus universitarios:  

### 1. Conductores (estudiantes, docentes y personal administrativo)  
Estudiantes, docentes y personal administrativo de **18 a 65 años** que usan vehículo propio para llegar al campus.  
Enfrentan incertidumbre al buscar estacionamiento, especialmente en horarios pico, lo que genera **pérdida de tiempo y estrés**.  
Necesitan un sistema que les permita **reservar espacios gratuitamente con anticipación** y garantizar disponibilidad al llegar.  

### 2. Administradores de estacionamientos  
Personal de **30 a 55 años** encargado de supervisar y gestionar los estacionamientos del campus.  
Su trabajo se ve afectado por **procesos manuales, errores y falta de visibilidad en tiempo real**.  
Necesitan un sistema que **automatice el control, genere reportes y libere automáticamente los espacios no utilizados**, para mejorar la eficiencia y el aprovechamiento de los estacionamientos.  

<br>


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table border="1" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr>
            <th colspan="6" style="text-align: center;">Competitive Analysis Landscape</th>
        </tr>
        <tr>
            <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
            <td colspan="4">
                Para dar a conocer a los competidores que se presentan en nuestra Startup.
            </td>
        </tr>
    </thead>
    <tbody>
        <tr style="text-align: center;">
            <td colspan="2">Empresas</td>
            <td><strong>SafePark</strong><br><img src="./assets/img/Chapter-II/safepark-logo.png"></td>
            <td><strong>ParkSmart</strong><br><img src="./assets/img/Chapter-II/parksmart-logo.png"></td>
            <td><strong>ParkingDoor</strong><br><img src="./assets/img/Chapter-II/parkingdoor-logo.png"></td>
            <td><strong>Parkealo</strong><br><img src="./assets/img/Chapter-II/parkealo-logo.png"></td>
        </tr>
        <!-- Perfil -->
        <tr>
            <td rowspan="2" style="writing-mode: vertical-lr; text-align: center;">Perfil</td>
            <td>Overview</td>
            <td>Sistema IoT para reservas y gestión gratuita de estacionamientos universitarios.</td>
            <td>Solución global de smart parking con sensores, cámaras y software para ciudades.</td>
            <td>Control de accesos a estacionamientos mediante app y dispositivos IoT.</td>
            <td>Plataforma local peruana de gestión integral de estacionamientos con app móvil y reportes.</td>
        </tr>
        <tr>
            <td>¿Qué valor ofrece a los clientes?</td>
            <td>Reserva gratuita, optimización académica y sostenibilidad en campus universitarios.</td>
            <td>Amplia experiencia internacional en proyectos de smart cities.</td>
            <td>Simplicidad en accesos inteligentes y gestión de permisos.</td>
            <td>Conocimiento del contexto local y soporte en Perú.</td>
        </tr>
        <!-- Perfil de Marketing -->
        <tr>
            <td rowspan="2" style="writing-mode: vertical-lr; text-align: center;">Perfil de Marketing</td>
            <td>Mercado objetivo</td>
            <td>Universidades en Latinoamérica.</td>
            <td>Gobiernos municipales, centros comerciales, aeropuertos.</td>
            <td>Empresas, residencias y oficinas privadas.</td>
            <td>Estacionamientos privados y públicos en Perú.</td>
        </tr>
        <tr>
            <td>Estrategias de marketing</td>
            <td>Convenios con universidades y asociaciones estudiantiles (B2B2C).</td>
            <td>Alianzas con gobiernos y concesionarias.</td>
            <td>Promoción a través de inmobiliarias y comunidades.</td>
            <td>Marketing digital local y convenios con estacionamientos.</td>
        </tr>
        <!-- Perfil de Producto -->
        <tr>
            <td rowspan="3" style="writing-mode: vertical-lr; text-align: center;">Perfil de Producto</td>
            <td>Productos & Servicios</td>
            <td>Sensores IoT, reservas anticipadas, notificaciones, panel web.</td>
            <td>Sensores, cámaras, software de control de ocupación y pagos.</td>
            <td>App, controladores IoT de acceso, llaves digitales.</td>
            <td>App con mapa de estacionamientos, reservas y pagos.</td>
        </tr>
        <tr>
            <td>Precios & Costos</td>
            <td>Modelo de suscripción mensual a universidades.</td>
            <td>Costos elevados, modelo SaaS con hardware.</td>
            <td>Pago por dispositivo y suscripción mensual.</td>
            <td>Comisiones por transacción a usuarios y estacionamientos.</td>
        </tr>
        <tr>
            <td>Canales de distribución (Web o móvil)</td>
            <td>App móvil y web, alianzas con universidades.</td>
            <td>App, web, integraciones con ciudades inteligentes.</td>
            <td>App móvil, hardware instalado.</td>
            <td>Web, app móvil, soporte técnico local.</td>
        </tr>
        <!-- SWOT -->
        <tr>
            <td rowspan="4" style="writing-mode: vertical-lr; text-align: center;">Análisis SWOT</td>
            <td>Fortalezas</td>
            <td>Especialización en campus universitarios, bajo costo para usuarios.</td>
            <td>Experiencia internacional y soporte tecnológico.</td>
            <td>Seguridad y simplicidad en accesos.</td>
            <td>Conocimiento del mercado local.</td>
        </tr>
        <tr>
            <td>Debilidades</td>
            <td>Mercado inicial limitado a universidades.</td>
            <td>Costos altos, difícil de implementar en entornos pequeños.</td>
            <td>No orientado a espacios públicos.</td>
            <td>Cobertura geográfica reducida.</td>
        </tr>
        <tr>
            <td>Oportunidades</td>
            <td>Escalar a otras ciudades y campus corporativos.</td>
            <td>Creciente interés en ciudades inteligentes.</td>
            <td>Incremento de condominios y oficinas privadas.</td>
            <td>Expansión nacional.</td>
        </tr>
        <tr>
            <td>Amenazas</td>
            <td>Entrada de competidores globales al segmento educativo.</td>
            <td>Competencia de startups más ágiles.</td>
            <td>Limitada escalabilidad en espacios públicos.</td>
            <td>Competencia de soluciones globales más avanzadas.</td>
        </tr>
    </tbody>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

**A) Diferenciación de Servicios**  
SafePark se posicionará como la solución más especializada para el ámbito universitario, ofreciendo reservas gratuitas anticipadas, notificaciones inteligentes y liberación automática de espacios no utilizados. A diferencia de competidores como **ParkSmart** o **ParkingDoor**, SafePark no requiere grandes inversiones en hardware ni se limita únicamente al acceso, sino que integra la experiencia completa de gestión y uso en campus.

**B) Calidad Constante**  
La confiabilidad del sistema será un diferenciador frente a alternativas locales como **Parkealo**. SafePark implementará pilotos en universidades peruanas para validar métricas de ahorro de tiempo y mejora en la rotación de espacios. A partir de los resultados y del feedback de los usuarios, se aplicarán actualizaciones periódicas que garanticen un sistema robusto y en evolución continua.

**C) Servicio al Cliente de Calidad**  
El soporte será un punto clave frente a soluciones internacionales. SafePark ofrecerá atención personalizada en español, capacitación a administradores universitarios y un canal directo de soporte 24/7. Esto garantizará que tanto los estudiantes como los gestores del campus puedan utilizar el sistema desde el primer día sin fricciones, aumentando la satisfacción y la adopción.

**D) Alianzas Estratégicas**  
SafePark buscará convenios con universidades, asociaciones estudiantiles y entidades educativas para acelerar la implementación en campus. Asimismo, establecerá acuerdos con empresas locales de tecnología IoT para reducir costos de hardware y asegurar la escalabilidad. Estas alianzas permitirán a SafePark diferenciarse de competidores como **Parkealo**, que se enfocan en un mercado más comercial, al consolidarse como el referente en soluciones de movilidad universitaria.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se presentarán las preguntas empleadas en las entrevistas, incluyendo tanto las de carácter general aplicables a todos los segmentos objetivo, como aquellas diseñadas específicamente para cada grupo en particular.

**Preguntas generales**

- ¿Qué dispositivo tecnológico usas con más frecuencia en tu día a día (celular, laptop, tablet)?
- ¿Qué navegador web usas con mayor frecuencia?
- ¿Cuáles son los canales de interacción que más utilizas (WhatsApp, correo, llamadas, apps móviles, etc.)?
- ¿Cómo describes tu personalidad en pocas palabras?
- ¿Presentas alguna frustración en tu trabajo/rutina universitaria relacionada con la movilidad o el tiempo?
- ¿Cómo se llama el distrito donde resides actualmente?

**Preguntas Segmento 1: Conductores universitarios**

- ¿Con qué frecuencia utilizas los estacionamientos de la universidad?
- En promedio, ¿cuánto tiempo tardas en encontrar un espacio disponible para estacionar?
- ¿Cuál es el mayor inconveniente que enfrentas al buscar estacionamiento en horas punta?
- ¿Qué tan útil te resultaría poder reservar un espacio antes de llegar al campus?
- ¿Qué opinas de que las reservas tengan un límite de 30 minutos para llegar antes de liberarse?
- ¿Aceptarías recibir notificaciones en tu celular sobre disponibilidad, vencimiento de reservas o recordatorios?
- ¿Qué características te parecen más valiosas en una aplicación de estacionamiento (ejemplo: rapidez, gratuidad, facilidad de uso, confiabilidad)?
- ¿Qué mejoras propondrías para que un sistema de estacionamiento inteligente se adapte mejor a tus necesidades?

**Preguntas Segmento 2: Administradores**

- ¿Cómo gestionas actualmente la ocupación de los estacionamientos en el campus?
- ¿Qué problemas principales enfrentas en la administración de los espacios (errores manuales, quejas, falta de control, etc.)?
- ¿Qué tan difícil es controlar la rotación de vehículos en horarios de mayor demanda?
- ¿Qué beneficios esperas de un sistema automatizado de control de estacionamientos?
- ¿Qué opinas de implementar un sistema que libere automáticamente los espacios reservados no utilizados?
- ¿Qué tan útil sería contar con un panel web que muestre en tiempo real la ocupación y genere reportes automáticos?
- ¿Qué barreras crees que podrían surgir al implementar un sistema inteligente de reservas (resistencia de usuarios, falta de infraestructura, costos)?
- ¿Qué indicadores te ayudarían a evaluar si un sistema como SafePark realmente mejora la eficiencia operativa del estacionamiento?

### 2.2.2. Registro de entrevistas
A continuación, se registraron todas las entrevistas realizadas para nuestra solución, categorizadas según su segmento objetivo, y con un resumen que destaca las características y críticas realizadas sobre nuestro proyecto.

URL de video: 

**Entrevista 01 (Conductores Universitarios)**

Nombres: Manuel  
Apellidos: Chavez  
Edad: 23  
Sexo: Masculino  
Carrera: Ingeniería de Sistemas  
Universidad: UPC – Campus San Isidro  
Lugar de residencia: San Borja, Lima  
Duración de la entrevista: 00:00 – 6:29

Personalidad: Responsable, puntual y sociable.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/conductor-manuel.png" alt="Conductor Universitario Manuel Chavez" width="100%" />
</div><br>

En resumen, Manuel Chavez es estudiante de Ingeniería de Sistemas en la UPC de San Isidro y vive en San Borja, desde donde se traslada en auto al campus con una duración de viaje que varía entre 25 y 40 minutos según el tráfico. Utiliza principalmente el **celular** para revisar mensajes en WhatsApp, correos y escuchar música, mientras que la **laptop** la reserva para trabajos y proyectos académicos. Su **navegador habitual** es **Google Chrome**, sincronizado con su cuenta de Gmail para guardar contraseñas, marcadores y acceder a Drive. Se comunica sobre todo por **WhatsApp** y **correo institucional**, y solo realiza llamadas en casos urgentes. Usa el **estacionamiento de la universidad casi todos los días**, encontrando espacio en menos de 5 minutos si llega antes de las 7:30 a. m., pero demorando entre 15 y 20 minutos si llega después de las 8:00 a. m. Señala como principales problemas la alta demanda de espacios, la congestión en las entradas y el tráfico interno generado por vehículos que esperan una salida. Considera que un sistema que permita **reservar un espacio antes de llegar** sería **muy útil**, y ve razonable un límite de 30 minutos antes de liberar la reserva para que otros puedan ocupar el espacio. Le gustaría recibir **notificaciones en el celular** sobre la disponibilidad de espacios o el vencimiento de su reserva. Para una aplicación de estacionamiento, prioriza que sea **rápida, confiable y de uso sencillo**, con información actualizada en tiempo real, preferiblemente gratuita, que muestre un **mapa del campus** con los espacios disponibles, permita **reservar en uno o dos clics** y se integre con el **carné universitario** para validar rápidamente la entrada.
<br><br>

**Entrevista 02 (Conductores Universitarios)**  

Nombres: Diego  
Apellidos: Sanchez  
Edad: 22  
Sexo: Masculino  
Carrera: Ingeniería Industrial  
Universidad: UPC – Campus Monterrico  
Lugar de residencia: Surco, Lima  
Duración de la entrevista: 06:30 – 16:22

Personalidad: Organizado, responsable y puntual.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/conductor-2.png" alt="Conductor Universitario Diego Sanchez" width="100%" />
</div><br>

En resumen, Diego Sanchez es estudiante de Ingeniería Industrial en la UPC Monterrico y vive en Surco, a unos 15 minutos del campus. Usa principalmente el **celular** para clases, correos y coordinación de trabajos, mientras que la **laptop** la emplea solo en casa. Su **navegador habitual** es **Google Chrome** y se comunica sobre todo por **WhatsApp**, **correo institucional** y **Microsoft Teams**. Conduce al campus **4–5 veces por semana** y en hora punta puede tardar **15–20 minutos** en encontrar estacionamiento, lo que le genera estrés por la **falta de información en tiempo real** y el **desorden interno**. Considera muy útil un sistema de **reserva previa**, acepta un **límite de 30 minutos** para mantener la reserva y valora recibir **notificaciones en el celular**. Para una aplicación de estacionamiento, prioriza que sea **sencilla, rápida, confiable y gratuita**, idealmente integrada con el **carné universitario** para validar el ingreso.
<br><br>

**Entrevista 03 (Conductores Universitarios)**  

Nombres: Álvaro  
Apellidos: Rivas  
Edad: 21  
Sexo: Masculino  
Carrera: Administración y Negocios Internacionales  
Universidad: UPC – Campus San Isidro  
Lugar de residencia: Miraflores, Lima  
Duración de la entrevista: 16:23 – 22:07

Personalidad: Disciplinado, organizado y puntual.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/conductor-3.png" alt="Conductor Universitario Álvaro Rivas" width="100%" />
</div><br>

En resumen, Álvaro Rivas es estudiante de Administración y Negocios Internacionales en la UPC San Isidro y vive en Miraflores. Usa principalmente el **celular** para clases, coordinación y finanzas personales, mientras que la **laptop** la utiliza en casa para trabajos. Su **navegador habitual** es **Google Chrome**, con uso ocasional de Safari. Se comunica sobre todo por **WhatsApp**, **correo institucional** y **Microsoft Teams**. Conduce al campus **casi todos los días**, demorando **5 minutos si llega temprano** y **15–20 minutos en hora punta**, lo que le genera tensión por la **incertidumbre y el tráfico interno**. Considera muy útil un sistema de **reserva previa de estacionamiento**, ve adecuado un **límite de 30 minutos** y valora recibir **notificaciones en el celular**. Para una aplicación de estacionamiento, prioriza que sea **rápida, confiable, de uso sencillo y gratuita**, con integración al **carné universitario** y un **historial de uso** para planificar mejor sus horarios.
<br><br>


**Entrevista 01 (Administradores)**

Nombres: Maricarmen  
Apellidos: Tejada  
Edad: 60  
Sexo: Femenino  
Ocupación: Administradora de Servicios Generales – Gestión de Estacionamientos  
Lugar donde vive: San Miguel, Lima  
Duración de la entrevista: 22:12 – 29:46

Personalidad: Responsable, organizada y práctica.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/admin-maricarmen.png" alt="Administradora Maricarmen Tejada" width="100%" />
</div><br>

En resumen, Maricarmen Tejada es administradora de servicios generales en el campus de San Miguel con más de 12 años de experiencia gestionando estacionamientos y coordinando personal. Usa principalmente **laptop** para correos, reportes y hojas de cálculo, y **celular** para coordinar por WhatsApp; su navegador habitual es **Google Chrome**. Sus principales canales de comunicación son **correo institucional**, **WhatsApp** y **Microsoft Teams**.  
Experimenta gran **frustración por la congestión en horas pico**, pues la gestión de ocupación es **manual** y su equipo depende de conteos y reportes, lo que provoca **errores humanos**, **quejas de usuarios** y **falta de información en tiempo real**. Considera que un **sistema automatizado** aportaría **visibilidad inmediata**, menos carga de trabajo y mejor experiencia para los usuarios. Respalda la liberación automática de reservas no usadas y la existencia de un **panel web con reportes en tiempo real**, aunque advierte barreras como **resistencia de usuarios**, **costos de implementación** y necesidad de **soporte técnico constante**. Mide el éxito en base a **tiempo de búsqueda de estacionamiento**, **rotación de espacios**, **nivel de ocupación** y **reducción de quejas**.
<br><br>

**Entrevista 02 (Administradores)**  

Nombres: Carlos  
Apellidos: Méndez  
Edad: 42  
Sexo: Masculino  
Cargo: Jefe de Operaciones  
Universidad: UPC – Campus Monterrico  
Lugar de residencia: Surco, Lima  
Duración de la entrevista: 29:47 – 37:18

Personalidad: Práctico, ordenado y exigente; busca soluciones rápidas y claras en la operación diaria.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/admin-2.png" alt="Administrador Carlos Méndez" width="100%" />
</div><br>

En resumen, Carlos Méndez es jefe de operaciones en la UPC Monterrico y vive en Surco. Usa principalmente el **celular** para coordinar con su equipo de seguridad y logística, y la **computadora** para reportes. Su **navegador habitual** es **Google Chrome**. Se comunica por **correo institucional**, **WhatsApp**, llamadas y reuniones en **Microsoft Teams**. Gestiona los estacionamientos **de forma manual**, recibiendo reportes por radio y registrando datos en Excel. Identifica como principales problemas los **errores humanos**, las **quejas de usuarios** y la **falta de datos en tiempo real**. Considera **difícil controlar la rotación** en horas pico y valora un sistema que permita **monitoreo en vivo**, **liberación automática de espacios** y **reportes automáticos**. Reconoce posibles barreras como **resistencia de usuarios**, **costos de implementación** y la necesidad de **soporte técnico constante**.
<br><br>

**Entrevista 03 (Administradores)**  

Nombres: Javier  
Apellidos: Salazar  
Edad: 38  
Sexo: Masculino  
Cargo: Coordinador Administrativo  
Universidad: UPC – Campus Villa  
Lugar de residencia: (No especificado)  
Duración de la entrevista: 37:19 – 45:56 

Personalidad: Resolutivo, paciente y comunicativo; escucha antes de actuar y toma decisiones rápidas cuando es necesario.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/admin-3.png" alt="Administrador Javier Salazar" width="100%" />
</div><br>

En resumen, Javier Salazar es coordinador administrativo en la UPC Villa con 7 años de experiencia. Usa principalmente el **celular** para coordinar con su equipo y la **laptop** para reportes. Su **navegador principal** es **Google Chrome**, con uso ocasional de Edge. Se comunica por **correo institucional**, **WhatsApp** y reuniones en **Microsoft Teams**. Administra el estacionamiento **manualmente**, recibiendo reportes por radio o mensajes y, a veces, en Excel. Enfrenta **errores humanos**, **falta de datos en tiempo real** y **quejas frecuentes de usuarios**. Destaca la necesidad de un sistema que brinde **información en vivo**, **libere reservas no utilizadas** y genere **reportes automáticos**. Considera como retos la **resistencia de algunos usuarios**, el **costo inicial** y la importancia de un **buen soporte técnico** para evitar fallas en horas críticas.
<br><br>


### 2.2.3. Análisis de entrevistas

Con el fin de analizar las entrevistas realizadas a **conductores universitarios** y **administradores de estacionamientos**, se recopilaron las respuestas en un formulario de Google. A continuación, se presenta un resumen de los resultados más relevantes acompañados de los gráficos obtenidos.

<h4>Preguntas generales</h4>

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis1.png" alt="Navegador y dispositivo preferido" width="70%" />
</div>

En cuanto a dispositivos, predominan el **celular** y la **laptop**, confirmando que los usuarios acceden a herramientas digitales principalmente desde entornos móviles.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis2.png" alt="Navegador y dispositivo preferido" width="70%" />
</div>

La mayoría de los entrevistados utiliza **Google Chrome** como navegador principal, aunque se hace mención a **Safari**.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis3.png" alt="Navegador y dispositivo preferido" width="70%" />
</div>
Los canales de interacción más comunes son **WhatsApp**, **correo electrónico** y **llamadas**, con pequeña valoración de **apps móviles**.  

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis4.png" alt="Navegador y dispositivo preferido" width="70%" />
</div>
En la escala de frustración por problemas de movilidad o tiempo, la mayoría de los conductores reportan un nivel **4**, mientras que otros tienen un nivel **3 y 5**, evidenciando molestias constantes en su rutina universitaria.


<h4>Análisis segmento Conductores Universitarios</h4>

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-uni1.png" alt="Frecuencia de uso del estacionamiento" width="70%" />
</div>

La mayoría utiliza el estacionamiento **todos los dias**, seguido de quienes lo usan **3–4 veces por semana**.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-uni2.png" alt="Tiempo promedio para encontrar estacionamiento" width="70%" />
</div>

El **tiempo de búsqueda de un espacio** se concentra entre **10 y 20 minutos**, con casos que superan los 20 minutos en horas pico.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-uni3.png" alt="Principales inconvenientes" width="70%" />
</div>

Los principales inconvenientes son la **falta de espacios disponibles**, la **demora en encontrar lugar** y el **estrés** asociado.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-uni4.png" alt="Utilidad de reservar espacios" width="70%" />
</div>

La idea de **reservar un espacio antes de llegar al campus** se valora con puntajes de **4 y 5**, considerándola muy útil.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-uni5.png" alt="Opinión sobre límite de 30 min" width="70%" />
</div>

Respecto al **límite de 30 minutos para liberar reservas**, la mayoría lo considera **adecuado** (3–5).

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-uni6.png" alt="Características más valoradas en la app" width="70%" />
</div>

Las características más valoradas en una app de estacionamiento son **rapidez**, **facilidad de uso** y **confiabilidad**, con la **gratuidad** como valor agregado.


<h4>Análisis segmento Administradores</h4>

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-admin1.png" alt="Método de gestión de ocupación" width="70%" />
</div>

Casi todos los administradores, gestionan la ocupación de forma **manual**, mediante observación y reportes del personal de seguridad. Mientras que solo uno maneja la gestión con un software básico.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-admin2.png" alt="Problemas principales" width="70%" />
</div>

Los problemas más frecuentes son **errores manuales**, **quejas de usuarios** y **falta de control**.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-admin3.png" alt="Dificultad de controlar la rotación" width="70%" />
</div>

Controlar la **rotación de vehículos en horas pico** se califica entre **3, 4 y 5**, reflejando la alta dificultad.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-admin4.png" alt="Beneficios esperados de un sistema automatizado" width="70%" />
</div>

De los beneficios esperados del sistema, el que más se espera es el de **Mayor Control**, seguido de la optimización de tiempos, la reducción de erroes y una mejor experiencia de usuario.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-admin5.png" alt="Opinión sobre liberación automática" width="70%" />
</div>

La idea de **liberar automáticamente los espacios reservados no utilizados** obtiene una valoración **muy alta (5/5)**.

<div style="text-align: center;">
  <img src="./assets/img/Chapter-II/interview-analysis-admin6.png" alt="Utilidad de un panel web en tiempo real" width="70%" />
</div>

Contar con un **panel web en tiempo real** para monitoreo y reportes automáticos es considerado **fundamental**, con puntajes de **5/5**.

### Hallazgos clave

- **Conductores**  
  - Alta frustración (4–5) por la demora en encontrar estacionamiento.  
  - Ven muy útil la opción de **reservar espacios con antelación**.  
  - Valoran rapidez, facilidad y confiabilidad en una app de estacionamiento.

- **Administradores**  
  - Gestión actual **100 % manual**, dependiente de reportes del personal.  
  - Necesitan visibilidad **en tiempo real** y reducción de errores humanos.  
  - Alta disposición a sistemas que **liberen espacios automáticamente** y generen reportes automáticos.

- **Conclusión General**  
  Conductores y administradores coinciden en la necesidad de una **plataforma centralizada y automatizada** que reduzca la congestión, optimice la rotación de vehículos y ofrezca una experiencia eficiente para todos los usuarios.



## 2.3. Needfinding

Para comprender mejor cómo los usuarios interactuarán con nuestro producto, emplearemos herramientas como User Persona, User Task Matrix, User Journey Mapping y Empathy Mapping. Esto nos permitirá visualizar su experiencia de manera más clara y detallada. 

### 2.3.1. User Personas

## Conductor Universitario

<img src="./assets/img/Chapter-II/user-persona-conductores.png">

El segmento de Conductor Universitario representa a estudiantes, docentes y personal administrativo que buscan optimizar su tiempo y reducir la incertidumbre al estacionar dentro del campus. Este perfil se caracteriza por su enfoque en la eficiencia, la planificación y el uso de soluciones tecnológicas confiables que faciliten la movilidad y organización diaria. Buscan una solución integral que permita consultar disponibilidad en tiempo real, reservar espacios con anticipación y recibir notificaciones claras sobre sus reservas. Este segmento tiene un perfil demográfico de 18 a 35 años, usuarios frecuentes de smartphones y laptops, que valoran interfaces intuitivas y rápidas, así como herramientas de coordinación digital como WhatsApp y correo institucional.

<br>

## Administrador de Estacionamiento

<img src="./assets/img/Chapter-II/user-persona-administradores.png">

El segmento de Administrador de Estacionamiento representa a profesionales responsables de supervisar y gestionar los estacionamientos universitarios, buscando eficiencia operativa, control centralizado y reducción de errores manuales. Este perfil valora tecnologías confiables que faciliten la automatización de reservas, liberación de espacios, generación de reportes y métricas en tiempo real, mejorando la gestión de su equipo y la experiencia de los usuarios. El rango demográfico es de 30 a 60 años, con formación en administración o gestión de operaciones, y usuarios frecuentes de laptops y smartphones, que requieren interfaces web intuitivas y paneles de control claros para una operación eficiente.

<br>

### 2.3.2. User Task Matrix
En esta sección se muestra la User Task Matrix, que permite identificar las tareas más importantes y frecuentes de los usuarios de SafePark: conductores universitarios y administradores de estacionamientos. La matriz ayuda a comparar sus actividades, destacando similitudes y diferencias en frecuencia e importancia. Este análisis, basado en los User Personas, permite comprender mejor sus necesidades y desafíos, enfocando el diseño de SafePark en funciones que optimicen la experiencia de los conductores y faciliten la gestión eficiente de los administradores.

| Task | Conductores universitarios (Frecuencia / Importancia) | Administradores (Frecuencia / Importancia) |
|------|-------------------------------------------------------|-------------------------------------------|
| Buscar un espacio disponible al llegar al campus | Alta / Alta | Media / Alta |
| Reservar un espacio con anticipación mediante la app | Alta / Alta | Media / Media |
| Recibir notificaciones sobre disponibilidad o reservas | Media / Alta | Media / Media |
| Liberar espacios no utilizados o reservas vencidas | Baja / Media | Alta / Alta |
| Consultar el panel de ocupación en tiempo real | Baja / Media | Alta / Alta |
| Gestionar incidencias por ocupación irregular | Baja / Media | Alta / Alta |
| Optimizar la rotación de vehículos en horarios pico | Media / Media | Alta / Alta |
| Evaluar eficiencia y generar reportes de ocupación | Baja / Baja | Alta / Alta |
| Planificar tiempos de llegada y rutas al campus | Alta / Media | Baja / Baja |

<br>

### 2.3.3. User Journey Mapping  

En esta sección se presentan los **User Journey Mapping** de los dos perfiles de usuario principales, resaltando las etapas clave de interacción con **SafePark**, los puntos de contacto, así como las emociones y experiencias que viven en cada fase. El objetivo es identificar oportunidades de mejora para optimizar su experiencia.  

__User Journey Map – Manuel Rojas – Conductor Universitario (As-Is)__  

__Inicio de la mañana:__ Manuel se alista para sus clases y piensa en el tiempo que le tomará encontrar estacionamiento en el campus. Siente **ansiedad** porque en días de alta demanda suele dar varias vueltas antes de hallar un espacio.  

__Camino a la universidad:__ Durante el trayecto revisa, sin éxito, si hay información en tiempo real sobre espacios libres. La **frustración** aumenta porque no cuenta con una app que le avise.  

__Búsqueda de estacionamiento:__ Llega al campus y recorre el estacionamiento esperando encontrar un lugar. Experimenta **estrés** y **apuro** por no llegar tarde a su primera clase.  

__Estacionamiento y asistencia a clases:__ Finalmente encuentra un espacio tras varios minutos. Se siente **aliviado**, aunque sabe que el proceso fue poco eficiente.  

__Salida del campus:__ Al retirarse, piensa en lo útil que sería una aplicación que permita **reservar** o recibir **alertas en tiempo real**. Termina el día con **expectativa** de una futura solución tecnológica.  

<div style="text-align: center;">
  <img src="assets/img/Chapter-II/journey-conductor.png" alt="Journey Map Conductor" width="70%" />
</div><br>

__User Journey Map – Maricarmen Tejada – Administradora de Estacionamiento (As-Is)__  

__Inicio de la jornada:__ Maricarmen comienza su día revisando manualmente el registro de espacios disponibles. Siente **presión** porque debe garantizar un flujo adecuado de vehículos sin errores.  

__Control de ocupación:__ Atiende llamadas y mensajes de personal de seguridad para conocer la disponibilidad en tiempo real. La falta de un panel centralizado le genera **estrés** y posibles **confusiones**.  

__Atención a incidencias:__ Se comunica con guardias y estudiantes cuando surgen reclamos o problemas de estacionamiento. Vive momentos de **tensión** por la dificultad de coordinar rápidamente.  

__Elaboración de reportes:__ Al final del turno, recopila datos en hojas de cálculo para entregar un informe de ocupación. Esta tarea es **tediosa** y consume demasiado tiempo.  

__Cierre del día:__ Revisa que todo quede en orden para el siguiente turno, pero se siente **agotada** y con la expectativa de contar con una herramienta que permita automatizar reservas, alertas y reportes.  

<div style="text-align: center;">
  <img src="assets/img/Chapter-II/journey-admin.png" alt="Journey Map Admin" width="70%" />
</div> 

### 2.3.4. Empathy Mapping

El Empathy Mapping permite comprender a fondo las necesidades, emociones y comportamientos de los usuarios, identificando oportunidades para mejorar su experiencia. A continuación, se presentan los mapas de empatía de los dos segmentos objetivo de SafePark: Conductores Universitarios y Administradores de Estacionamientos.

## Empathy Map del Conductor Universitario

En este mapa de empatía, se ha representado al conductor universitario como el principal usuario de la aplicación SafePark. Este segmento busca reducir el tiempo y el estrés que genera la búsqueda de estacionamiento dentro del campus, asegurando un espacio disponible al llegar.  
Durante el análisis, se observa que los conductores sienten frustración por la congestión y la desorganización en los estacionamientos, y ansiedad por la posibilidad de llegar tarde a clases o reuniones. Normalmente intentan salir con mucha anticipación o dar vueltas alrededor del campus para encontrar un lugar, lo que afecta su productividad y estado de ánimo.  
Sus necesidades principales son contar con un sistema que permita reservar espacios con anticipación, recibir información confiable en tiempo real y reducir la incertidumbre en su rutina diaria. Buscan una herramienta tecnológica rápida, confiable y gratuita que les brinde tranquilidad, control y eficiencia en su movilidad.

<img src="./assets/img/Chapter-II/empathy-mapping-conductor.png">

<br>

## Empathy Map del Administrador de Estacionamientos

En este mapa de empatía, se ha representado al administrador como el principal responsable de gestionar los estacionamientos universitarios. Este segmento busca optimizar la eficiencia operativa, mantener el orden y reducir la carga manual de su equipo, especialmente durante las horas pico.  
Durante el análisis, se observa que los administradores enfrentan problemas diarios por la desorganización, quejas de usuarios y limitaciones de procesos manuales. Normalmente intentan resolver estos problemas con métodos tradicionales o herramientas digitales limitadas, que no siempre cumplen con sus expectativas.  
Sus necesidades principales son contar con un sistema automatizado que gestione reservas, libere espacios no utilizados, genere métricas en tiempo real y permita tomar decisiones basadas en datos. Buscan tecnología confiable que mejore la eficiencia operativa y garantice una experiencia positiva para los usuarios del campus.

<img src="./assets/img/Chapter-II/empathy-mapping-administradores.png">

<br>

## 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language  

Esta sección presenta un glosario de términos y conceptos clave del dominio, definidos de manera precisa para evitar ambigüedades. Su objetivo es asegurar una comunicación clara y uniforme entre los miembros del equipo y los stakeholders.  

| Término (Inglés)    | Término (Español)        | Definición |
|---------------------|--------------------------|------------|
| **Parking Spot**    | Espacio de estacionamiento | Lugar físico destinado al estacionamiento de un vehículo dentro del campus universitario. |
| **Reservation**     | Reserva                  | Acción mediante la cual un conductor asegura un espacio de estacionamiento de forma anticipada a través de la app SafePark. |
| **Reservation Status** | Estado de la reserva   | Condición actual de una reserva, por ejemplo: confirmada, pendiente, cancelada o expirada. |
| **Arrival Time**    | Hora de llegada          | Momento en el que el conductor debe llegar al espacio reservado antes de que se libere automáticamente. |
| **No-show**         | No presentación          | Situación en la que un conductor no ocupa el espacio reservado dentro del tiempo límite establecido. |
| **Occupancy**       | Ocupación                | Cantidad de espacios de estacionamiento actualmente ocupados en un área o lote específico. |
| **IoT Sensor**      | Sensor IoT               | Dispositivo que detecta la presencia de un vehículo en un espacio de estacionamiento y envía información en tiempo real al sistema. |
| **Dashboard**       | Panel de administración  | Interfaz web utilizada por los administradores para monitorear la ocupación, gestionar reservas y generar reportes. |
| **User App**        | Aplicación móvil         | Plataforma usada por conductores para consultar disponibilidad, reservar espacios y recibir notificaciones. |
| **Auto-release**    | Liberación automática    | Función que libera un espacio reservado si no es ocupado por el conductor dentro del tiempo límite de llegada. |
| **Peak Hours**      | Horas punta             | Intervalos de tiempo con mayor demanda de estacionamiento en el campus, generalmente al inicio y final de clases. |

Esta sección presenta un glosario de términos y conceptos clave del dominio, definidos de manera precisa para evitar ambigüedades. Su objetivo es asegurar una comunicación clara y uniforme entre los miembros del equipo y los stakeholders.

| Término (Inglés) | Término (Español)      | Definición                                                                                       |
|------------------|-----------------------|-------------------------------------------------------------------------------------------------|
| Parking Spot      | Espacio de estacionamiento | Lugar físico destinado al estacionamiento de un vehículo dentro del campus universitario.       |
| Reservation       | Reserva               | Acción mediante la cual un conductor asegura un espacio de estacionamiento de forma anticipada a través de la app SafePark. |
| Reservation Status | Estado de la reserva  | Condición actual de una reserva, por ejemplo: confirmada, pendiente, cancelada o expirada.     |
| Arrival Time      | Hora de llegada       | Momento en el que el conductor debe llegar al espacio reservado antes de que se libere automáticamente. |
| No-show           | No presentación       | Situación en la que un conductor no ocupa el espacio reservado dentro del tiempo límite establecido. |
| Occupancy         | Ocupación             | Cantidad de espacios de estacionamiento actualmente ocupados en un área o lote específico.     |
| IoT Sensor        | Sensor IoT            | Dispositivo que detecta la presencia de un vehículo en un espacio de estacionamiento y envía información en tiempo real al sistema. |
| Dashboard         | Panel de administración | Interfaz web utilizada por los administradores para monitorear la ocupación, gestionar reservas y generar reportes. |
| User App          | Aplicación móvil      | Plataforma usada por conductores para consultar disponibilidad, reservar espacios y recibir notificaciones. |
| Auto-release      | Liberación automática | Función que libera un espacio reservado si no es ocupado por el conductor dentro del tiempo límite de llegada. |
| Peak Hours        | Horas punta           | Intervalos de tiempo con mayor demanda de estacionamiento en el campus, generalmente al inicio y final de clases. |

<br>

# Capítulo III: Requirements Specification

## 3.1. User Stories


Redactamos las historias de usuario para el sistema de gestión de estacionamientos SafePark basándonos en las necesidades y problemas identificados en los segmentos de conductores universitarios y administradores del campus. Las historias de usuario describen las funcionalidades y características que los usuarios finales esperan del sistema, y se utilizan como guía para diseñar y desarrollar una experiencia eficiente, confiable y tecnológica para la gestión de reservas, ocupación y control de espacios de estacionamiento.

<br>

| Epic/Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---------------|--------|------------|-------------------------|---------------------------|
| EP01 | Gestión de Identidad y Acceso | Como miembro UPC quiero registrarme, autenticarme y gestionar mi perfil para acceder al sistema de estacionamiento. | – | – |
| US01 | Registro de Usuario UPC | Como estudiante/docente/personal de UPC quiero registrarme con mi email institucional (@upc.edu.pe) para acceder a SafePark. | Given que soy miembro de UPC con email válido When completo el formulario de registro Then el sistema valida mi email y crea mi cuenta And recibo un correo de confirmación And mi perfil se clasifica como “Estudiante”, “Docente” o “Personal Administrativo”. | EP01 |
| US02 | Autenticación de Usuario | Como miembro registrado quiero iniciar sesión en SafePark para acceder a mis funcionalidades. | Given que tengo una cuenta activa When ingreso mi email y contraseña válidos Then el sistema me autentica y me redirige al dashboard And mi sesión permanece activa And veo mi estado actual (reservas, ausencias, etc.). | EP01 |
| US03 | Gestión de Perfil Personal | Como usuario autenticado quiero actualizar mi información personal para mantener mis datos al día. | Given que estoy autenticado When accedo a “Mi Perfil” Then puedo editar nombre, teléfono y preferencias de notificación And los cambios se guardan And no puedo cambiar mi email institucional ni tipo de usuario. | EP01 |
| EP02 | Gestión de Reservas Flexibles | Como miembro UPC quiero crear, consultar y cancelar reservas con detección automática, sin necesidad de definir hora de salida. | – | – |
| US04 | Crear Nueva Reserva | Como miembro UPC quiero crear una reserva de estacionamiento para asegurar mi espacio. | Given que no tengo una reserva activa y hay espacios disponibles When selecciono fecha y hora de inicio (máx. 24h anticipación) Then el sistema asigna un espacio disponible And recibo confirmación con detalles And tengo ventana de 30 min para llegar And no necesito definir hora de fin. | EP02 |
| US05 | Ver Estado de Reservas | Como usuario con reserva quiero ver el estado actual de mis reservas para saber dónde y cuándo debo llegar. | Given que tengo una reserva activa When accedo al dashboard Then veo mi espacio asignado con fecha y hora And veo tiempo restante para llegar (cuenta regresiva) And veo el estado general de espacios. | EP02 |
| US06 | Cancelar Reserva | Como usuario con reserva quiero cancelarla para liberar el espacio si ya no lo necesito. | Given que tengo una reserva activa no confirmada When selecciono “Cancelar Reserva” Then el sistema libera el espacio And recibo confirmación And puedo crear otra reserva. | EP02 |
| US07 | Confirmación Automática de Llegada | Como usuario quiero que SafePark detecte mi llegada automáticamente al estacionar. | Given que tengo una reserva activa y llego a mi espacio When estaciono mi vehículo Then el sensor detecta ocupación And el LED cambia a rojo (ocupado) And el cronómetro inicia And recibo confirmación de inicio. | EP02 |
| US08 | Finalización Automática de Sesión | Como usuario quiero que SafePark detecte mi salida para cerrar la sesión. | Given que tengo una sesión activa When retiro mi vehículo Then el sensor detecta espacio libre And el cronómetro se detiene And recibo resumen de sesión And el LED cambia a verde (libre). | EP02 |
| EP03 | Control de Espacios IoT | Como sistema quiero gestionar espacios físicos e integrar dispositivos ESP32 para monitoreo en tiempo real. | – | – |
| US09 | Monitoreo de Estado de Espacios | Como usuario quiero ver el estado actual de todos los espacios para conocer disponibilidad en tiempo real. | Given que estoy en el dashboard When consulto el estado de espacios Then veo los 3 espacios (A, B, C) con estado: Libre, Reservado, Ocupado o Mantenimiento And se actualiza cada 15s And veo LED correspondiente. | EP03 |
| US10 | Indicación Visual de Espacio Asignado | Como usuario quiero identificar fácilmente mi espacio asignado para estacionar correctamente. | Given que tengo una reserva confirmada When llego al estacionamiento Then el LED de mi espacio parpadea en azul And el display muestra “Espacio [X] reservado para [Usuario]”. | EP03 |
| EP04 | Seguimiento de Tiempo Real | Como usuario quiero que SafePark registre y muestre el tiempo de uso en vivo sin límites temporales. | – | – |
| US11 | Cronometraje Automático | Como usuario quiero que el sistema registre automáticamente mi tiempo de uso. | Given que confirmé mi llegada When el sensor detecta ocupación Then el cronómetro inicia And puedo ver tiempo transcurrido en la app And se registra hasta mi salida. | EP04 |
| US12 | Visualización de Tiempo en Vivo | Como usuario quiero ver mi tiempo de uso actual en la app. | Given que tengo sesión activa When consulto el dashboard Then veo tiempo transcurrido actualizado en vivo And hora de inicio And datos sincronizados con IoT. | EP04 |
| US13 | Historial de Tiempos de Uso | Como usuario quiero ver mi historial de sesiones para conocer mis patrones de uso. | Given que tengo sesiones anteriores When accedo a “Mi Historial” Then veo lista de últimas 20 sesiones con fecha, duración y espacio And estadísticas personales And puedo filtrar por rango de fechas. | EP04 |
| EP05 | Sistema de Penalizaciones | Como sistema quiero registrar ausencias y suspender usuarios automáticamente para mantener justicia. | – | – |
| US14 | Registro Automático de Ausencias | Como sistema quiero detectar ausencias automáticamente. | Given que un usuario tiene reserva confirmada When pasan 30 min sin detectar ocupación Then registro ausencia And libero el espacio And envío notificación. | EP05 |
| US15 | Sistema de Advertencias Progresivas | Como usuario quiero recibir advertencias sobre mis ausencias. | Given que tengo 1 ausencia When accedo al sistema Then veo “Ausencias: 1/3” y notificación. Given que tengo 2 ausencias Then veo “Ausencias: 2/3 – Advertencia final” y notificación. | EP05 |
| US16 | Suspensión Automática de Usuario | Como sistema quiero suspender usuarios con 3 ausencias para evitar abuso. | Given que un usuario alcanza 3 ausencias When se registra la tercera Then se suspende por 7 días And no puede reservar And recibe notificación. | EP05 |
| US17 | Reactivación Automática Post-Suspensión | Como usuario quiero ser reactivado automáticamente después de la suspensión. | Given que fui suspendido por 7 días When se cumple el período Then mi cuenta se reactiva And contador reseteado 0/3 And recibo notificación. | EP05 |
| EP06 | Panel Administrativo | Como administrador quiero monitorear, configurar y generar reportes para gestionar el sistema. | – | – |
| US18 | Dashboard Administrativo | Como administrador quiero ver estado completo del sistema. | Given que soy administrador autenticado When accedo al panel Then veo estado en tiempo real And métricas del día And alertas de usuarios suspendidos o problemas técnicos. | EP06 |
| US19 | Gestión de Usuarios | Como administrador quiero gestionar usuarios del sistema. | Given que soy administrador When busco un usuario Then veo su perfil completo And puedo resetear ausencias, suspender o reactivar manualmente And ver historial. | EP06 |
| US20 | Configuración del Sistema | Como administrador quiero configurar parámetros del sistema. | Given que soy administrador When accedo a “Configuración” Then ajusto ventana de llegada, anticipación máxima, límite de reservas y penalizaciones And cambios aplicados inmediatamente. | EP06 |
| US21 | Reportes y Métricas | Como administrador quiero generar reportes y métricas. | Given que soy administrador When solicito reportes Then puedo generarlos diarios, semanales o mensuales And exportar a Excel/PDF And ver gráficos de tendencias. | EP06 |
| EP07 | Notificaciones Inteligentes | Como usuario quiero recibir notificaciones claras sobre mis reservas, sesiones y penalizaciones. | – | – |
| US22 | Notificaciones de Reserva | Como usuario quiero recibir notificaciones de mis reservas. | Given que creo una nueva reserva When el sistema la confirma Then recibo confirmación And recordatorio 15 min antes And alerta de ventana de llegada. | EP07 |
| US23 | Notificaciones de Sesión | Como usuario quiero recibir notificaciones sobre mi sesión. | Given que inicio una sesión When sensor confirma mi llegada Then recibo notificación de inicio Given que finalizo sesión When sensor detecta mi salida Then recibo resumen. | EP07 |
| US24 | Notificaciones de Penalizaciones | Como usuario quiero recibir notificaciones claras sobre ausencias y suspensiones. | Given que se registra una ausencia Then recibo notificación con contador actualizado. Given que soy suspendido When alcanzo 3 ausencias Then recibo notificación con fecha de reactivación. | EP07 |
| US25 | Configuración de Preferencias de Notificación | Como usuario quiero configurar mis preferencias de notificación. | Given que accedo a mi perfil When entro a “Preferencias de Notificación” Then puedo activar/desactivar push And configurar recordatorios automáticos. | EP07 |
| EP08 | Landing Page Institucional | Como visitante quiero conocer el sistema y acceder fácilmente a las apps. | – | – |
| US26 | Página Principal Informativa | Como visitante quiero conocer características principales del sistema. | Given que visito la landing page When navego Then veo información sobre automatización, tiempo ilimitado y facilidad de uso And demo visual con imágenes/video And testimonios. | EP08 |
| US27 | Descarga de Aplicaciones | Como miembro UPC quiero acceder fácilmente a las apps. | Given que decido usar el sistema When busco cómo acceder Then encuentro botones claros para App Web y App Móvil And enlaces me llevan correctamente. | EP08 |
| US28 | Información Técnica | Como visitante técnico quiero conocer detalles de la implementación. | Given que busco información técnica When accedo a “Tecnología” Then veo detalles de IoT (ESP32, sensores, LEDs) And stack tecnológico And estadísticas de eficiencia. | EP08 |
| TS01 | API de Autenticación | Como desarrollador quiero implementar endpoints JWT para autenticar usuarios. | Given que recibo credenciales válidas en POST /api/auth/login When proceso autenticación Then retorno JWT válido And expira en 24h. | EP01 |
| TS02 | API de Gestión de Reservas | Como desarrollador quiero implementar endpoints RESTful para reservas. | Given que recibo petición POST /api/reservations When valido disponibilidad y reglas Then creo reserva y retorno confirmación And actualizo estado en tiempo real. | EP02 |
| TS03 | Integración IoT con ESP32 | Como desarrollador quiero comunicación bidireccional con ESP32. | Given que ESP32 envía datos When recibo evento en /api/iot/sensor-data Then actualizo estado de espacio And notifico via WebSocket. | EP03 |
| TS04 | Sistema de Notificaciones | Como desarrollador quiero implementar servicio de notificaciones push. | Given que se dispara un evento When proceso solicitud con template Then envío notificación And registro estado de entrega. | EP07 |

<br>

## 3.2. Impact Mapping  

En el desarrollo de nuestro proyecto, aplicamos la metodología **Impact Mapping** como herramienta estratégica para asegurar que cada funcionalidad de **SafePark** se alinee con los objetivos de negocio y con las verdaderas necesidades de nuestros usuarios. Esta técnica permitió identificar con claridad qué queremos lograr, quiénes son los actores clave, cómo pueden influir en el resultado y qué acciones priorizar, evitando invertir recursos en características que no aporten valor directo.  

__Business goal:__  
Reducir en 30% el tiempo de búsqueda de estacionamiento en 3 meses
<div style="text-align: center;">
  <img src="assets/img/Chapter-III/impact-map-conductor.png" alt="Impact Map – Manuel (Conductor Universitario)" width="90%" />
</div>  

__Business goal:__  
Incrementar en 25% la rotación de espacios en 6 meses mediante liberación automática de reservas no utilizadas.
<div style="text-align: center;">
  <img src="assets/img/Chapter-III/impact-map-admin.png" alt="Impact Map – Maricarmen (Administradora de Estacionamiento)" width="90%" />
</div>  


## 3.3. Product Backlog

| Orden | User Story ID | Título | Descripción | Story Points |
|-------|---------------|--------|-------------|--------------|
| 1     | US01          | Registro Usuario UPC | Como miembro UPC quiero registrarme con email @upc.edu.pe para acceder al sistema | 3 |
| 2     | US02          | Autenticación Usuario | Como usuario registrado quiero iniciar sesión para acceder a funcionalidades | 3 |
| 3     | TS01          | API Autenticación JWT | Como desarrollador quiero endpoints de autenticación JWT para que las apps puedan autenticar usuarios | 5 |
| 4     | US26          | Landing Page Principal | Como visitante quiero conocer características del sistema para entender sus beneficios | 2 |
| 5     | US09          | Monitoreo Estado Espacios | Como usuario quiero ver el estado actual de los 3 espacios en tiempo real para saber si están disponibles | 5 |
| 6     | US04          | Crear Nueva Reserva | Como miembro UPC quiero crear reservas hasta 24h antes para garantizar un espacio | 5 |
| 7     | TS02          | API Gestión Reservas | Como desarrollador quiero endpoints RESTful para crear, consultar y cancelar reservas | 5 |
| 8     | US05          | Ver Estado Reservas | Como usuario con reserva quiero ver detalles y tiempo restante para gestionar mi llegada | 3 |
| 9     | US06          | Cancelar Reserva | Como usuario quiero cancelar una reserva para liberar el espacio si no lo necesito | 2 |
| 10    | US27          | Descarga Aplicaciones | Como miembro UPC quiero acceder fácilmente a apps móvil y web para instalar el sistema rápidamente | 2 |
| 11    | TS03          | Integración IoT ESP32 | Como desarrollador quiero comunicación bidireccional con ESP32 para sincronizar el estado de los espacios | 8 |
| 12    | US07          | Confirmación Automática Llegada | Como usuario quiero que el sistema detecte automáticamente mi llegada para validar mi reserva sin acciones manuales | 8 |
| 13    | US11          | Cronometraje Automático | Como usuario quiero que el sistema registre automáticamente el tiempo para llevar un control sin intervención manual | 5 |
| 14    | US08          | Finalización Automática Sesión | Como usuario quiero que el sistema detecte automáticamente mi salida para liberar el espacio sin necesidad de confirmación manual | 8 |
| 15    | US10          | Indicación Visual Espacio | Como usuario con reserva quiero identificar fácilmente mi espacio asignado para ubicarlo sin confusión | 3 |
| 16    | US12          | Visualización Tiempo en Vivo | Como usuario activo quiero ver el tiempo transcurrido actualizado en vivo para monitorear mi sesión en curso | 3 |
| 17    | US22          | Notificaciones Reserva | Como usuario quiero recibir notificaciones sobre mis reservas para estar informado de su estado | 3 |
| 18    | TS04          | Sistema Notificaciones | Como desarrollador quiero un servicio de notificación tipo push para enviar alertas a los usuarios | 5 |
| 19    | US14          | Registro Automático Ausencias | Como sistema quiero detectar ausencias automáticamente para gestionar penalizaciones sin intervención manual | 5 |
| 20    | US15          | Advertencias Progresivas | Como usuario con ausencias quiero recibir advertencias claras para conocer mi estado antes de una suspensión | 3 |
| 21    | US16          | Suspensión Automática | Como sistema quiero suspender automáticamente usuarios con 3 ausencias para asegurar cumplimiento de reglas | 5 |
| 22    | US23          | Notificaciones Sesión | Como usuario quiero recibir notificaciones de inicio y fin de sesión para estar al tanto de mis horarios | 2 |
| 23    | US24          | Notificaciones Penalizaciones | Como usuario quiero recibir notificaciones claras sobre mis ausencias y suspensiones para entender mis penalizaciones | 2 |
| 24    | US18          | Dashboard Administrativo | Como admin quiero ver el estado completo del sistema para monitorear y tomar decisiones | 8 |
| 25    | US03          | Gestión Perfil Personal | Como usuario quiero actualizar mi información personal para mantener mis datos correctos y actualizados | 3 |
| 26    | US13          | Historial Tiempos Uso | Como usuario quiero ver mi historial de sesiones y estadísticas personales para analizar mis hábitos de uso | 3 |
| 27    | US17          | Reactivación Automática | Como usuario suspendido quiero reactivación automática después del periodo para recuperar acceso al sistema | 3 |
| 28    | US19          | Gestión Usuarios | Como admin quiero gestionar usuarios para resolver problemas y administrar penalizaciones | 8 |
| 29    | US20          | Configuración Sistema | Como admin quiero configurar parámetros del sistema para adaptar su funcionamiento a las necesidades de la UPC | 5 |
| 30    | US25          | Configuración Preferencias | Como usuario quiero configurar mis preferencias de notificación para recibir alertas según mis necesidades | 2 |
| 31    | US21          | Reportes y Métricas | Como admin quiero generar reportes del sistema para analizar el uso y optimizar el servicio | 5 |
| 32    | US28          | Información Técnica | Como visitante técnico quiero conocer detalles de implementación y arquitectura para evaluar la solución en profundidad | 1 |

<br>


# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

Imagen del Event Storming general en su fase final: 
![image](./assets/img/Chapter-IV/eventstorming.jpg)

Imagen con resultado del Event Storming en relación a Identity and Access Management (IAM) Bounded Context:
![image](./assets/img/Chapter-IV/iam-eventstorming.png)

Imagen con resultado del Event Storming en relación a Reservation Management Bounded Context:
![image](./assets/img/Chapter-IV/reservation-eventstorming.png)

Imagen con resultado del Event Storming en relación a Space & IoT Management Bounded Context:
![image](./assets/img/Chapter-IV/iot-eventstorming.png)

Imagen con resultado del Event Storming en relación a Time Tracking Bounded Context:
![image](./assets/img/Chapter-IV/timeTracking-eventstorming.png)

Imagen con resultado del Event Storming en relación a Penalty Management Bounded Context:
![image](./assets/img/Chapter-IV/penalty-eventstorming.png)

Imagen con resultado del Event Storming en relación a Analytics & Reporting Bounded Context:
![image](./assets/img/Chapter-IV/analytics-eventstorming.png)

Imagen con resultado del Event Storming en relación a Notification Bounded Context:
![image](./assets/img/Chapter-IV/notification-eventstorming.png)

#### 4.1.1.1. Candidate Context Discovery

**Paso 1: Unstructured Exploration:** Comenzamos identificando todos los eventos de dominio que ocurren en el sistema SmartParking UPC. Durante esta fase, el equipo se enfocó en capturar eventos como "Usuario registrado en el sistema", "Espacio de estacionamiento detectado como ocupado", "Reserva confirmada exitosamente", "Sesión de estacionamiento iniciada", "Penalización aplicada por ausencia", entre otros. Cada evento fue documentado en post-its en Miro, considerando el flujo completo desde la perspectiva del usuario universitario hasta la gestión administrativa.  
**Imagen de la Reunión:**  
![Captura de pantalla de la reunión - Paso 1](./assets/img/Chapter-IV/meeting-step1.jpg)  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%201_%20Unstructured%20Exploration.jpg)

**Paso 2: Timelines:** Organizamos los eventos identificados en secuencias temporales que representan los diferentes flujos de usuario en SmartParking. Desarrollamos el flujo principal donde un estudiante busca un espacio disponible, realiza una reserva, llega al campus, confirma su llegada, estaciona su vehículo, y finalmente libera el espacio. También consideramos flujos alternativos como cancelaciones de reserva, penalizaciones por no presentarse, y escenarios de espacios ocupados inesperadamente.  
**Imagen de la Reunión:**  
![Captura de pantalla de la reunión - Paso 2](./assets/img/Chapter-IV/meeting-step2.jpg)  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%202_%20Timelines.jpg)

**Paso 3: Pain Points:** Identificamos los principales problemas que enfrentan los usuarios en el sistema actual de estacionamientos de la UPC. Entre estos se encuentran la falta de información en tiempo real sobre disponibilidad, la dificultad para encontrar espacios libres, la ausencia de un sistema de reservas, la falta de notificaciones sobre el estado de los espacios, y la inexistencia de un sistema de penalizaciones para usuarios que no cumplen con sus reservas.

**Paso 4: Pivotal Points:** Definimos los eventos críticos que marcan cambios significativos en el estado del sistema. Estos incluyen momentos como cuando un sensor IoT detecta la presencia de un vehículo, cuando un usuario confirma su llegada al espacio reservado, cuando se inicia el cronometraje de una sesión de estacionamiento, y cuando se aplica una penalización por ausencia.  
**Imagen de la Reunión:**  
![Captura de pantalla de la reunión - Paso 4](./assets/img/Chapter-IV/meeting-step4.jpg)  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%204_%20Pivotal%20Points.jpg)

**Paso 5: Commands:** Especificamos las acciones que los usuarios y el sistema pueden ejecutar para generar los eventos identificados. Los comandos incluyen "Registrar usuario", "Buscar espacios disponibles", "Crear reserva", "Confirmar llegada", "Iniciar sesión de estacionamiento", "Finalizar sesión", "Aplicar penalización", "Generar reporte de uso", entre otros. Cada comando fue asociado con los actores correspondientes: estudiantes, docentes, personal administrativo y administradores del sistema.  
**Imagen de la Reunión:**  
![Captura de pantalla de la reunión - Paso 5](./assets/img/Chapter-IV/meeting-step5.jpg)  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%205_%20Commands.jpg)

**Paso 6: Policies:** Establecimos reglas de negocio automatizadas que se ejecutan sin intervención directa del usuario. Estas políticas incluyen la detección automática de vehículos mediante sensores ultrasónicos ESP32, la aplicación automática de penalizaciones cuando un usuario no se presenta a su reserva, la generación automática de alertas cuando un espacio permanece ocupado más tiempo del reservado, y la actualización automática de métricas de uso del sistema.  
**Imagen de la reunión:**  
![Captura de pantalla de la reunión - Paso 6](./assets/img/Chapter-IV/meeting-step6.jpg)  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%206_%20Policies.jpg)

**Paso 7: Read Models:** Definimos las vistas de datos necesarias para soportar las consultas de los usuarios y administradores. Estos modelos incluyen la vista de disponibilidad de espacios en tiempo real, el historial personal de reservas del usuario, el dashboard administrativo con métricas de ocupación, los reportes de eficiencia por espacio, y las consultas de patrones de uso del estacionamiento.  
**Imagen de la Reunión:**  
![Captura de pantalla de la reunión - Paso 7](./assets/img/Chapter-IV/meeting-step7.jpg)  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%207_%20Read%20Models.jpg)

**Paso 8: External Systems:** Identificamos los sistemas externos que interactúan con SmartParking pero no forman parte de su dominio core. Estos incluyen los sensores IoT ESP32 con sensores ultrasónicos, el sistema de notificaciones push para móviles, la base de datos de usuarios de la UPC, el sistema de correo electrónico institucional, y potenciales integraciones futuras con sistemas de pago o Active Directory de la universidad.  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%208_%20External%20Systems.jpg)

**Paso 9: Aggregates:** Agrupamos las entidades relacionadas en agregados que mantienen la consistencia de datos. Los agregados principales incluyen UserAccount (usuario y perfil), Reservation (reserva y sus estados), ParkingSpace (espacio físico y sensores asociados), TimeTrackingSession (sesión de estacionamiento y cronometraje), PenaltyRecord (registro de penalizaciones), y AnalyticsData (métricas y reportes).  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%209_%20Agreggates.jpg)

**Paso 10: Bounded Context:** Agrupamos los agregados relacionados en contextos delimitados que representan áreas de responsabilidad específicas. Esto resultó en siete bounded contexts: Identity and Access Management (gestión de usuarios y autenticación), Reservation Management (gestión de reservas), Space & IoT Management (gestión de espacios y sensores), Time Tracking (cronometraje de sesiones), Penalty Management (gestión de penalizaciones), Analytics & Reporting (métricas y reportes), y Notification (sistema de notificaciones).  
**Imagen ejemplo:**  
![image](./assets/img/Chapter-IV/Step%2010_%20Bounded%20Context.jpg)

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

#### Proceso para Crear el Context Mapping y Análisis de Alternativas

##### 1. Pasos para Crear el Context Mapping

###### 1.1. Identificación de los Bounded Contexts
- **Identity and Access Management (IAM)**
- **Reservation Management**
- **Space & IoT Management**
- **Time Tracking**
- **Penalty Management**
- **Analytics & Reporting**
- **Notification**

###### 1.2. Identificación de Relaciones entre Bounded Contexts

1. **Reservation Management** → **Space & IoT Management**: Relación de **Customer/Supplier con ACL**.
   - *Reservation Management* necesita asignar espacios físicos cuando se confirman reservas.
   - *Space & IoT Management* provee control de espacios y dispositivos IoT.
   - Anti-Corruption Layer protege la lógica de reservas de cambios en hardware.

2. **Space & IoT Management** → **Time Tracking**: Relación de **Customer/Supplier**.
   - *Space & IoT Management* inicia y detiene cronómetros basado en detección de sensores.
   - *Time Tracking* provee servicios de cronometraje para sesiones de estacionamiento.

3. **Time Tracking** → **Analytics & Reporting**: Relación de **Customer/Supplier**.
   - *Time Tracking* provee datos de duración y patrones de uso.
   - *Analytics & Reporting* consume estos datos para generar métricas y reportes.

4. **Reservation Management** → **Penalty Management**: Relación de **Customer/Supplier**.
   - *Reservation Management* reporta eventos de ausencias (no-shows).
   - *Penalty Management* provee servicios de registro y gestión de penalizaciones.

5. **Reservation Management** → **Notification**: Relación de **Open/Host Service**.
   - *Reservation Management* utiliza servicios de notificación para confirmaciones.
   - *Notification* proporciona un servicio público de mensajería.

6. **Penalty Management** → **Notification**: Relación de **Open/Host Service**.
   - *Penalty Management* utiliza servicios de notificación para alertas de ausencias.
   - *Notification* proporciona servicios centralizados de comunicación.

###### 1.3. Gestión de Identidad mediante Middleware

**Identity and Access Management (IAM)** opera como middleware de infraestructura, proporcionando autenticación transparente sin crear dependencias directas en los bounded contexts de negocio. Este patrón:

- **Separación de responsabilidades**: La autenticación es una preocupación transversal, no de dominio.
- **Middleware transparente**: Validación automática de tokens JWT antes de llegar a los bounded contexts.
- **Bounded contexts limpios**: Reciben información de usuario ya validada sin conocer detalles de autenticación.

##### 2. Análisis de Alternativas y Preguntas Clave

###### 2.1. ¿Qué pasaría si movemos este capability a otro bounded context?
- **Caso Considerado:** Mover la capacidad de gestión de cronómetros desde *Time Tracking* hacia *Space & IoT Management*.
- **Impacto:**
  - *Space & IoT Management* tendría la responsabilidad de gestionar tanto sensores como cronómetros.
  - Incrementaría el acoplamiento de *Space & IoT Management*.
- **Discusión:**
  - Es recomendable mantener la separación, ya que aunque ambos están relacionados con el uso físico del espacio, *Time Tracking* maneja lógica de negocio específica (métricas, históricos) mientras que *Space & IoT* se enfoca en hardware. Pueden interactuar mediante eventos bien definidos.

###### 2.2. ¿Qué pasaría si descomponemos este capability y movemos uno de los sub-capabilities a otro bounded context?
- **Caso Considerado:** Descomponer *Penalty Management* en sub-capabilities como *AbsenceDetection* y *SuspensionManagement* y mover *AbsenceDetection* a *Reservation Management*.
- **Impacto:**
  - Implicaría que *Reservation Management* pueda detectar ausencias directamente, liberando responsabilidades de *Penalty Management*.
  - *SuspensionManagement* seguirá gestionando el sistema de "3 strikes".
- **Discusión:**
  - Esta descomposición podría ser beneficiosa ya que las ausencias están directamente relacionadas con las reservas. Sin embargo, mantener toda la lógica de penalizaciones unificada facilita la gestión del sistema de "3 strikes" y evita dispersar reglas de negocio relacionadas.

###### 2.3. ¿Qué pasaría si partimos el bounded context en múltiples bounded contexts?
- **Caso Considerado:** Partir *Space & IoT Management* en *Physical Spaces* y *IoT Device Management*.
- **Impacto:**
  - Separar la gestión física de espacios de la gestión de dispositivos IoT.
  - Organizaría mejor las responsabilidades entre infraestructura física y tecnológica.
- **Discusión:**
  - Aunque son conceptos diferentes, están fuertemente acoplados en el dominio de SmartParking. Los sensores están físicamente asociados a espacios específicos y la lógica de detección requiere coordinar ambos aspectos. Dividirlos podría crear complejidad innecesaria en la comunicación.

###### 2.4. ¿Qué pasaría si tomamos este capability de estos 3 contexts y lo usamos para formar un nuevo context?
- **Caso Considerado:** Crear un nuevo Bounded Context llamado *Session Management* que combine capacidades de *Reservation Management*, *Time Tracking* y *Space & IoT Management* relacionadas con sesiones activas de estacionamiento.
- **Impacto:**
  - Unificaría toda la lógica de gestión de sesiones activas en un solo contexto.
  - Reduciría la comunicación entre contextos durante el flujo principal de uso.
- **Discusión:**
  - Aunque la gestión de sesiones es central al negocio, combinar estos contextos violaría el principio de separación de responsabilidades. Cada contexto actual tiene un propósito claro y bien definido. Un contexto unificado sería demasiado grande y difícil de mantener.

###### 2.5. ¿Qué pasaría si duplicamos una funcionalidad para romper la dependencia?
- **Caso Considerado:** Duplicar la funcionalidad de notificaciones en funcionalidades específicas para cada tipo, tales como *ReservationNotification*, *PenaltyNotification*, *AlertNotification*, etc.
- **Impacto:**
  - Las funcionalidades estarían mejor desacopladas, pero se repetiría mucho código.
  - Podría generar inconsistencias en el formato y entrega de notificaciones.
- **Discusión:**
  - No se recomienda, pues aumentaría la complejidad y la dificultad de mantenimiento. Es mejor utilizar el patrón Open/Host Service con un contexto de *Notification* centralizado que maneje todas las comunicaciones de manera consistente.

###### 2.6. ¿Qué pasaría si creamos un shared service para reducir la duplicación entre múltiples bounded contexts?
- **Caso Considerado:** Crear un servicio compartido de validación de reglas de negocio al que puedan acceder *Reservation Management* y *Penalty Management*.
- **Impacto:**
  - Reduciría la duplicación de validaciones comunes (ej: verificar estado del usuario).
  - Permitiría centralizar reglas transversales del sistema.
- **Discusión:**
  - Esto podría ser beneficioso para reglas muy específicas y compartidas, pero debe hacerse con cuidado para no crear un "god service". Es preferible mantener las validaciones específicas dentro de cada contexto y solo compartir utilidades muy genéricas.

###### 2.7. ¿Qué pasaría si aislamos los core capabilities y movemos los otros a un context aparte?
- **Caso Considerado:** Aislar las capacidades core de gestión de espacios en *Space & IoT Management* y mover las funcionalidades de IoT a un contexto separado llamado *Device Management*.
- **Impacto:**
  - Se reduciría la complejidad de *Space & IoT Management*.
  - Se especializarían mejor las responsabilidades.
- **Discusión:**
  - En el dominio de SmartParking, los espacios físicos y los dispositivos IoT están intrínsecamente relacionados. Separar estas capacidades requeriría mucha coordinación y comunicación entre contextos, añadiendo complejidad sin beneficios claros.

##### 3. Alternativa Recomendada de Context Mapping

1. **Mantener la estructura actual de 7 contextos** - cada uno tiene responsabilidades bien definidas.
2. **Implementar Anti-Corruption Layer (ACL)** entre *Reservation Management* y *Space & IoT Management* para proteger de cambios en el hardware.
3. **Usar Open/Host Service** para *Notification Context* - servicio público para todas las comunicaciones.
4. **Establecer Customer/Supplier** entre contextos según el flujo de control del negocio.
5. **Implementar middleware para IAM** - separación de concerns transversales de la lógica de dominio.

##### 4. Patrones de Relaciones Aplicados

- **Anti-corruption Layer (ACL)**: Para proteger *Reservation Management* de cambios en hardware IoT.
- **Open/Host Service**: *Notification* como servicio público para múltiples contextos.
- **Customer/Supplier**: Relaciones direccionales claras para flujo de datos según modelo de negocio.
- **Middleware Pattern**: IAM como concern transversal implementado en la capa de infraestructura.

##### 5. Implementación Técnica

###### 5.1. Middleware de Autenticación

El sistema implementa autenticación mediante middleware Express que:

- Intercepta todas las requests a endpoints protegidos
- Valida tokens JWT con IAM
- Inyecta información de usuario validada en el request
- Permite que bounded contexts operen con datos ya autenticados

###### 5.2. Arquitectura Monolítica Modular

Aunque implementa una arquitectura monolítica, los Bounded Contexts identificados sirven como módulos organizacionales que:

- Definen la estructura interna del código
- Establecen la división de responsabilidades del equipo  
- Determinan las interfaces entre componentes
- Facilitan la evolución futura hacia microservicios si fuera necesario

![Context Mapping](./assets/img/Chapter-IV/context-mapping-map.png)

### 4.1.3. Software Architecture

URL Structurizr para apreciar mejor los diagramas C4: <a href="https://structurizr.com/share/106335">https://structurizr.com/share/106335</a>
<br><br>

#### 4.1.3.1. Software Architecture System Landscape Diagram
El System Landscape Diagram ilustra la arquitectura general del sistema SmartParking, mostrando los diferentes actores y componentes que lo componen en el contexto universitario. Este diagrama proporciona una visión general de cómo se organizan los distintos usuarios y servicios en el ecosistema del sistema, así como las relaciones entre ellos. Los miembros universitarios (estudiantes, docentes y personal administrativo) no se consideran actores internos del sistema, sino como actores externos que interactúan y se benefician del sistema de gestión inteligente de estacionamientos. En este caso, el sistema SmartParking se despliega como una solución integral que puede ser implementada en cualquier campus universitario, manteniendo la flexibilidad para futuras integraciones con sistemas institucionales como Active Directory. El diagrama incluye dos grupos principales de usuarios: Miembros Universitarios (que utilizan el sistema para encontrar y reservar espacios) y Administradores (que gestionan y supervisan el funcionamiento del sistema). La arquitectura está diseñada para ser escalable y adaptable a diferentes entornos universitarios, proporcionando un servicio gratuito de estacionamiento inteligente mediante tecnología IoT.<br>
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/systemLandscape-c4.png" alt="System Landscape Diagram" width="90%" />
</div><br><br>

#### 4.1.3.2. Software Architecture Context Level Diagrams
El diagrama de contexto del sistema ilustra la interacción entre el sistema SmartParking y los actores externos que interactúan con él. Este diagrama proporciona una visión general de cómo el sistema se integra como una solución autónoma para la gestión de estacionamientos universitarios. En este caso, el sistema SmartParking opera de manera independiente sin dependencias críticas de sistemas externos, manteniendo toda la funcionalidad core internamente. Los Miembros Universitarios interactúan con el sistema para realizar reservas de espacios de estacionamiento, consultar disponibilidad en tiempo real, recibir notificaciones automáticas de confirmación de llegada/salida y gestionar sus reservas activas. Los Administradores utilizan el sistema para configurar espacios de estacionamiento, supervisar la ocupación en tiempo real, gestionar usuarios del sistema y generar reportes operacionales. El sistema mantiene un diseño limpio sin integraciones complejas, enfocándose en proporcionar una experiencia de usuario fluida y una gestión eficiente de recursos de estacionamiento mediante tecnología IoT avanzada.<br>
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/systemcontext-c4.png" alt="Context Diagram" width="90%" />
</div><br><br>

#### 4.1.3.3. Software Architecture Container Level Diagrams
A continuación, se presenta el diagrama de contenedores del sistema SmartParking, que ilustra los diferentes componentes y su interacción dentro de la arquitectura del software. Este diagrama proporciona una visión detallada de cómo se organizan los distintos servicios y aplicaciones en el sistema, así como las relaciones entre ellos. El sistema SmartParking se basa en una arquitectura híbrida RESTful API + Edge Computing que se divide en varios contenedores especializados, cada uno con funcionalidades y responsabilidades específicas. Los usuarios podrán utilizar la Landing Page estática para conocer las características del sistema y acceder a las aplicaciones. Una vez registrados, tendrán acceso a una aplicación web (Angular) y aplicación móvil (Flutter), las cuales consumirán datos desde la RESTful API principal desarrollada en Spring Boot + Java con base de datos MySQL.
En el contexto de IoT, existen dispositivos ESP32 físicos con sensores ultrasónicos que funcionan como sistemas externos hardware. Los datos de estos dispositivos son procesados a través de una Embedded Application (C++ + ESP32 Framework) que actúa como intermediario, enviando información procesada hacia el Edge API (Flask + Python) con base de datos SQLite local para procesamiento en tiempo real con latencia mínima. El Edge API sincroniza los datos relevantes con la RESTful API principal, creando un flujo de datos eficiente: Hardware IoT → Embedded App → Edge API → RESTful API → Frontend Applications. Esta arquitectura garantiza escalabilidad distribuida, procesamiento local de sensores, y una experiencia de usuario fluida tanto para reservas como para detección automática de vehículos.<br>
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/containers-c4.png" alt="Container Diagram" width="90%" />
</div><br><br>

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: Identity & Access Management Context

## Introducción

El Bounded Context **Identity & Access Management** es responsable de gestionar la identidad, autenticación y autorización de usuarios en el sistema SmartParking UPC. Este contexto opera como un contexto de soporte que proporciona capacidades transversales de seguridad a todos los demás bounded contexts del sistema.

Como se identificó en el Context Mapping, IAM actúa como middleware de infraestructura, proporcionando autenticación transparente sin crear dependencias directas en los bounded contexts de negocio. Esto permite una separación clara de responsabilidades donde la autenticación es tratada como una preocupación transversal.

#### 4.2.1.1. Domain Layer

La capa de dominio contiene las reglas de negocio fundamentales y las entidades core relacionadas con la identidad y acceso en el contexto universitario UPC.

##### Entidades (Entities)

###### **User**
Representa un usuario del sistema SmartParking UPC (datos de autenticación).

**Atributos:**
- `userId`: Identificador único del usuario
- `email`: Email institucional (@upc.edu.pe)
- `passwordHash`: Hash de la contraseña del usuario
- `role`: Rol del usuario (UNIVERSITY_MEMBER, ADMINISTRATOR)
- `status`: Estado del usuario (ACTIVE, INACTIVE, SUSPENDED)
- `createdAt`: Fecha de creación de la cuenta
- `lastLoginAt`: Fecha del último acceso
- `failedLoginAttempts`: Contador de intentos fallidos de login

**Métodos:**
- `authenticate(password: string): boolean`
- `suspend(): void`
- `reactivate(): void`
- `updateLastLogin(): void`
- `incrementFailedAttempts(): void`
- `resetFailedAttempts(): void`
- `hasRole(role: UserRole): boolean`

**Invariantes de Negocio:**
- El email debe ser válido y del dominio @upc.edu.pe
- El usuario solo puede ser suspendido si está activo
- Los intentos fallidos se reinician tras un login exitoso

###### **UserProfile**
Representa el perfil e información personal del usuario.

**Atributos:**
- `profileId`: Identificador único del perfil
- `userId`: Referencia al usuario propietario
- `firstName`: Nombre del usuario
- `lastName`: Apellido del usuario
- `createdAt`: Fecha de creación del perfil
- `updatedAt`: Fecha de última actualización

**Métodos:**
- `updatePersonalInfo(firstName: string, lastName: string): void`
- `getFullName(): string`

**Invariantes de Negocio:**
- Debe existir exactamente un perfil por usuario
- Los nombres no pueden estar vacíos

###### **Session**
Representa una sesión activa de usuario en el sistema.

**Atributos:**
- `sessionId`: Identificador único de sesión
- `userId`: Referencia al usuario propietario
- `token`: Token JWT de la sesión
- `createdAt`: Fecha de creación de la sesión
- `expiresAt`: Fecha de expiración del token
- `isActive`: Estado de la sesión

**Métodos:**
- `isExpired(): boolean`
- `invalidate(): void`
- `refreshToken(): string`

**Invariantes de Negocio:**
- Una sesión no puede estar activa si ha expirado
- Solo pueden existir tokens válidos para usuarios activos

##### Value Objects

###### **Email**
Value Object que encapsula y valida emails institucionales.

**Atributos:**
- `value`: El valor del email

**Métodos:**
- `isValid(): boolean`
- `getDomain(): string`
- `getLocalPart(): string`

**Invariantes:**
- Debe ser un email válido con formato correcto
- Debe pertenecer al dominio @upc.edu.pe
- No requiere verificación adicional

###### **UserRole**
Value Object que representa los roles del sistema.

**Atributos:**
- `value`: UNIVERSITY_MEMBER | ADMINISTRATOR

**Métodos:**
- `hasPermission(permission: string): boolean`
- `isAdministrator(): boolean`

###### **PasswordHash**
Value Object que maneja el hash seguro de contraseñas.

**Atributos:**
- `hashedValue`: Hash de la contraseña
- `algorithm`: Algoritmo usado para el hash
- `salt`: Salt utilizado

**Métodos:**
- `verify(plainPassword: string): boolean`
- `needsRehash(): boolean`

##### Aggregates

###### **UserAccount**
Aggregate Root que encapsula la lógica completa de cuenta de usuario.

**Entidades contenidas:**
- User (Root)
- UserProfile
- Conjunto de Sessions

**Métodos del Aggregate:**
- `register(email: Email, password: string, firstName: string, lastName: string): UserAccount`
- `login(email: Email, password: string): Session`
- `logout(sessionId: string): void`
- `updateProfile(firstName: string, lastName: string): void`
- `changePassword(oldPassword: string, newPassword: string): void`
- `assignRole(role: UserRole): void`

##### Domain Services

###### **AuthenticationService**
Servicio de dominio que maneja la lógica compleja de autenticación.

**Métodos:**
- `authenticateUser(email: Email, password: string): AuthenticationResult`
- `generateToken(user: User): string`
- `validateToken(token: string): TokenValidationResult`
- `handleFailedLogin(user: User): void`

###### **PasswordPolicyService**
Servicio que valida políticas de contraseñas institucionales.

**Métodos:**
- `validatePassword(password: string): ValidationResult`
- `generateSecureHash(password: string): PasswordHash`

##### Repository Interfaces

###### **IUserRepository**
Interface para persistencia de usuarios.

**Métodos:**
- `findByEmail(email: Email): User | null`
- `findById(userId: string): User | null`
- `save(user: User): void`
- `delete(userId: string): void`

###### **IUserProfileRepository**
Interface para persistencia de perfiles de usuario.

**Métodos:**
- `findByUserId(userId: string): UserProfile | null`
- `save(userProfile: UserProfile): void`
- `update(userProfile: UserProfile): void`

###### **ISessionRepository**
Interface para persistencia de sesiones.

**Métodos:**
- `findByToken(token: string): Session | null`
- `findActiveByUserId(userId: string): Session[]`
- `save(session: Session): void`
- `invalidateAllForUser(userId: string): void`

#### 4.2.1.2. Interface Layer

La capa de interfaz expone las capacidades del bounded context mediante controllers REST y maneja la comunicación HTTP.

##### Controllers

###### **AuthenticationController**
Controlador REST que maneja endpoints de autenticación.

**Endpoints:**
- `POST /api/auth/login`: Autenticar usuario
- `POST /api/auth/logout`: Cerrar sesión
- `POST /api/auth/refresh-token`: Renovar token
- `GET /api/auth/validate`: Validar token actual

**Métodos:**
- `login(loginRequest: LoginRequest): LoginResponse`
- `logout(logoutRequest: LogoutRequest): void`
- `refreshToken(refreshRequest: RefreshTokenRequest): TokenResponse`
- `validateToken(request: HttpRequest): ValidationResponse`

###### **UserRegistrationController**
Controlador para registro de nuevos usuarios UPC.

**Endpoints:**
- `POST /api/users/register`: Registrar nuevo usuario

**Métodos:**
- `register(registrationRequest: UserRegistrationRequest): RegistrationResponse`

###### **UserProfileController**
Controlador para gestión de perfiles de usuario.

**Endpoints:**
- `GET /api/users/profile`: Obtener perfil actual
- `PUT /api/users/profile`: Actualizar perfil
- `PUT /api/users/change-password`: Cambiar contraseña

**Métodos:**
- `getProfile(userId: string): UserProfileResponse`
- `updateProfile(profileRequest: UpdateProfileRequest): void`
- `changePassword(passwordRequest: ChangePasswordRequest): void`

##### DTOs (Data Transfer Objects)

###### **LoginRequest**
```typescript
{
  email: string,
  password: string,
  rememberMe: boolean
}
```

###### **LoginResponse**
```typescript
{
  accessToken: string,
  refreshToken: string,
  expiresIn: number,
  user: UserProfileResponse
}
```

###### **UserRegistrationRequest**
```typescript
{
  email: string,
  password: string,
  firstName: string,
  lastName: string
}
```

##### Middleware

###### **JWTAuthenticationMiddleware**
Middleware que intercepta requests para validar autenticación.

**Funcionalidades:**
- Extrae token JWT del header Authorization
- Valida firma y expiración del token
- Inyecta información de usuario en el contexto de request
- Maneja errores de autenticación

#### 4.2.1.3. Application Layer

La capa de aplicación orchestla los casos de uso y coordina entre la capa de dominio e infraestructura.

##### Command Handlers

###### **RegisterUserCommandHandler**
Maneja el proceso completo de registro de usuario.

**Command:** `RegisterUserCommand`
**Responsabilidades:**
- Validar unicidad del email
- Aplicar políticas de contraseña
- Crear cuenta de usuario activa
- Publicar evento de registro

**Método:**
```typescript
handle(command: RegisterUserCommand): Promise<RegisterUserResult>
```

###### **LoginUserCommandHandler**
Maneja el proceso de autenticación de usuario.

**Command:** `LoginUserCommand`
**Responsabilidades:**
- Validar credenciales
- Generar sesión y token
- Registrar evento de login
- Manejar intentos fallidos

###### **LogoutUserCommandHandler**
Maneja el proceso de cierre de sesión.

**Command:** `LogoutUserCommand`
**Responsabilidades:**
- Invalidar sesión actual
- Limpiar tokens
- Registrar evento de logout

##### Query Handlers

###### **GetUserProfileQueryHandler**
Obtiene información del perfil de usuario.

**Query:** `GetUserProfileQuery`
**Método:**
```typescript
handle(query: GetUserProfileQuery): Promise<UserProfileResult>
```

###### **ValidateTokenQueryHandler**
Valida tokens de autenticación.

**Query:** `ValidateTokenQuery`
**Responsabilidades:**
- Verificar firma del token
- Validar expiración
- Comprobar estado del usuario
- Retornar información de usuario

##### Event Handlers

###### **UserRegisteredEventHandler**
Maneja evento cuando un usuario se registra.

**Event:** `UserRegisteredEvent`
**Responsabilidades:**
- Inicializar configuraciones por defecto
- Registrar métricas de registro

###### **UserLoginEventHandler**
Maneja evento de login exitoso.

**Event:** `UserLoggedInEvent`
**Responsabilidades:**
- Actualizar último acceso
- Registrar métricas de uso
- Verificar ubicación de acceso

##### Application Services

###### **UserRegistrationService**
Orchestla el proceso completo de registro.

**Métodos:**
- `registerUniversityMember(request: RegisterUserRequest): Promise<void>`
- `validateInstitutionalEmail(email: string): Promise<boolean>`

###### **TokenService**
Maneja generación y validación de tokens JWT.

**Métodos:**
- `generateAccessToken(user: User): string`
- `generateRefreshToken(user: User): string`
- `validateToken(token: string): TokenValidationResult`
- `extractUserFromToken(token: string): User`

#### 4.2.1.4. Infrastructure Layer

La capa de infraestructura implementa las interfaces definidas en el dominio y maneja persistencia, servicios externos y configuración.

##### Repository Implementations

###### **MySQLUserRepository**
Implementación concreta del repositorio de usuarios para MySQL.

**Dependencias:**
- JPA/Hibernate para ORM
- MySQL Database Connection

**Métodos implementados:**
- `findByEmail(email: Email): User | null`
- `save(user: User): void`
- `findById(userId: string): User | null`

**Mapeo de Entidades:**
- Mapea entidades de dominio User a tabla users de MySQL
- Convierte Value Objects a tipos de columna apropiados

###### **MySQLUserProfileRepository**
Implementación del repositorio de perfiles de usuario.

**Funcionalidades:**
- Persistencia de información personal del usuario
- Manejo de relación 1:1 con User
- Actualizaciones de perfil

###### **MySQLSessionRepository**
Implementación del repositorio de sesiones.

**Funcionalidades:**
- Persistencia de tokens JWT
- Gestión de expiración automática
- Cleanup de sesiones inactivas

##### External Service Integrations

###### **JWTTokenProvider**
Implementación concreta para manejo de tokens JWT.

**Configuración:**
- Algoritmo HS256
- Secret key configurable
- Tiempo de expiración: 24 horas
- Refresh token: 30 días

**Métodos:**
- `generateToken(user: User, expirationTime: Duration): string`
- `validateTokenSignature(token: string): boolean`
- `extractClaims(token: string): Claims`

##### Configuration

###### **SecurityConfiguration**
Configuración de seguridad y políticas.

**Configuraciones:**
- Password policy (mínimo 8 caracteres, mayúsculas, números)
- Failed login attempts limit (5 intentos)
- Account lockout duration (30 minutos)
- Session timeout (24 horas)

###### **DatabaseConfiguration**
Configuración de conexión a base de datos.

**Configuraciones:**
- Connection pool settings
- Transaction management
- Entity mappings
- Migration scripts

##### Infrastructure Services

###### **PasswordHashingService**
Servicio que implementa hash seguro de contraseñas.

**Algoritmo:** BCrypt con salt
**Métodos:**
- `hashPassword(plainPassword: string): string`
- `verifyPassword(plainPassword: string, hash: string): boolean`

###### **AuditLoggingService**
Servicio para logging de eventos de seguridad.

**Funcionalidades:**
- Log de intentos de login
- Registro de cambios en cuentas
- Tracking de sesiones
- Alertas de seguridad

##### Database Schema (Resumen para la capa)

**Tabla: users**
- user_id (VARCHAR(36), PK)
- email (VARCHAR(255), UNIQUE)
- password_hash (VARCHAR(255))
- role (ENUM: UNIVERSITY_MEMBER, ADMINISTRATOR)
- status (ENUM: ACTIVE, INACTIVE, SUSPENDED)
- created_at (TIMESTAMP)
- last_login_at (TIMESTAMP)
- failed_login_attempts (INT)

**Tabla: user_profiles**
- profile_id (VARCHAR(36), PK)
- user_id (VARCHAR(36), FK)
- first_name (VARCHAR(100))
- last_name (VARCHAR(100))
- created_at (TIMESTAMP)
- updated_at (TIMESTAMP)

**Tabla: user_sessions**
- session_id (VARCHAR(36), PK)
- user_id (VARCHAR(36), FK)
- token_hash (VARCHAR(255))
- created_at (TIMESTAMP)
- expires_at (TIMESTAMP)
- is_active (BOOLEAN)

---

##### Conclusión

El Bounded Context Identity & Access Management implementa una arquitectura limpia siguiendo principios DDD, proporcionando capacidades robustas de autenticación y autorización específicamente diseñadas para el entorno universitario UPC. 

**Características clave:**
- **Seguridad institucional:** Validación estricta de emails @upc.edu.pe
- **Gestión de sesiones:** Manejo seguro de tokens JWT con expiración
- **Arquitectura desacoplada:** Interfaces claras entre capas
- **Middleware transparente:** Autenticación como concern transversal
- **Escalabilidad:** Diseño preparado para crecimiento del sistema

Este diseño asegura que la autenticación opere como un servicio de infraestructura confiable, permitiendo que otros bounded contexts se enfoquen en su lógica de dominio específica sin preocuparse por los detalles de seguridad.

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

URL Structurizr para apreciar mejor los diagramas de componentes IAM: <a href="https://structurizr.com/share/106368/diagrams#IAM-MobileComponents">https://structurizr.com/share/106368/diagrams#IAM-MobileComponents</a>
<br><br>

**IAM Web Services Component Diagram**
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/iam-webservice-component-c4.png" alt="IAM Web Service Component Diagram" width="90%" />
</div><br><br>

**IAM Mobile Application Component Diagram**
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/iam-mobile-component-c4.png" alt="IAM Mobile Component Diagram" width="90%" />
</div><br><br>

**IAM Web Application Component Diagram**
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/iam-webapplication-component-c4.png" alt="IAM Web Application Component Diagram" width="90%" />
</div><br><br>

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

URL para apreciar mejor el diagrama de clases del dominio IAM: <a href="#">[Enlace pendiente]</a>
<br><br>

**IAM Domain Layer Class Diagram**
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/iam-diagramclass.png" alt="IAM Domain Layer Class Diagram" width="90%" />
</div><br><br>

##### 4.2.1.6.2. Bounded Context Database Design Diagram

URL Vertabelo para apreciar mejor el diagrama de base de datos IAM: <a href="https://my.vertabelo.com/doc/G39D0hVaSi9Fl9cHFAsuUyP4761M1Nit">https://my.vertabelo.com/doc/G39D0hVaSi9Fl9cHFAsuUyP4761M1Nit</a>
<br><br>

**IAM Database Design Diagram**
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/iam-database-diagram.png" alt="IAM Database Design Diagram" width="90%" />
</div><br><br>

### 4.2.2. Bounded Context: Reservation Management
#### 4.2.2.1. Domain Layer
#### 4.2.2.2. Interface Layer
#### 4.2.2.3. Application Layer
#### 4.2.2.4. Infrastructure Layer
#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.2.6.2. Bounded Context Database Design Diagram

### 4.2.3. Bounded Context: Space & IoT Management
#### 4.2.3.1. Domain Layer

**Agregados y Entidades del Dominio Space & IoT Management en nuestro Web/Mobile Application**

En nuestras aplicaciones web y móvil, la carpeta `domain` dentro del Bounded Context **Space & IoT Management** contiene las entidades y agregados del dominio, representadas como clases con sus atributos y constructores. Cada clase encapsula la lógica de negocio principal asociada a espacios de estacionamiento y dispositivos IoT.

---

## ParkingSpace
Representa un espacio de estacionamiento.

**Atributos principales:**

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| Id | int | Identificador único del espacio |
| Code | string | Código identificador del espacio (A, B, C) |
| Status | string | Estado actual del espacio (AVAILABLE, RESERVED, OCCUPIED, MAINTENANCE) |
| CurrentReservationId | int? | ID de la reserva activa asociada |
| LastUpdated | DateTime | Última fecha y hora de actualización del estado |

**Constructores:** Por parámetros individuales.  
**Comandos relacionados:** `AssignSpaceCommand`, `UpdateSpaceStatusCommand`.

---

## IoTDevice
Representa un dispositivo IoT ESP32 que controla los espacios.

**Atributos principales:**

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| Id | int | Identificador único del dispositivo |
| Name | string | Nombre descriptivo del dispositivo (ESP32-Central) |
| IPAddress | string | Dirección IP del dispositivo |
| MacAddress | string | Dirección MAC del dispositivo |
| IsConnected | bool | Indica si está conectado al sistema |
| LastSync | DateTime | Última sincronización exitosa con la base de datos |

**Constructores:** Por parámetros individuales.  
**Comandos relacionados:** `ConnectIoTDeviceCommand`, `DisconnectIoTDeviceCommand`.

---

## Sensor
Representa un sensor ultrasónico HC-SR04 asociado a un espacio.

**Atributos principales:**

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| Id | int | Identificador único del sensor |
| ParkingSpaceId | int | ID del espacio al que pertenece |
| LastDistance | double | Última medición de distancia del sensor |
| State | string | Estado actual del sensor (ACTIVE, INACTIVE, ERROR) |
| LastDetected | DateTime? | Fecha y hora del último vehículo detectado |

**Constructores:** Por parámetros individuales.  
**Comandos relacionados:** `UpdateSensorStateCommand`, `UpdateSensorDistanceCommand`.

---

## ArrivalEvent

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| Id | int | Identificador único del evento |
| ReservationId | int | ID de la reserva correspondiente |
| ParkingSpaceId | int | Espacio donde se detectó el vehículo |
| Timestamp | DateTime | Fecha y hora de detección |

**Constructores:** Desde evento de sensor `VehicleDetectedEvent`.

---

## DepartureEvent

| Atributo | Tipo | Descripción |
|----------|------|-------------|
| Id | int | Identificador único del evento |
| ReservationId | int | ID de la reserva correspondiente |
| ParkingSpaceId | int | Espacio del que se retiró el vehículo |
| Timestamp | DateTime | Fecha y hora de salida |

**Constructores:** Desde evento de sensor `VehicleLeftEvent`.

---

## Comandos

### ParkingSpace

| Comando | Descripción |
|---------|------------|
| AssignSpaceCommand.cs | Asigna un espacio de estacionamiento a una reserva específica |
| UpdateSpaceStatusCommand.cs | Actualiza el estado del espacio (AVAILABLE, RESERVED, OCCUPIED, MAINTENANCE) |

### Sensor

| Comando | Descripción |
|---------|------------|
| UpdateSensorStateCommand.cs | Actualiza el estado del sensor (ACTIVE, INACTIVE, ERROR) |
| UpdateSensorDistanceCommand.cs | Actualiza la última distancia detectada por el sensor |

### IoTDevice

| Comando | Descripción |
|---------|------------|
| ConnectIoTDeviceCommand.cs | Registra la conexión de un ESP32 al sistema |
| DisconnectIoTDeviceCommand.cs | Marca la desconexión del dispositivo |

---

## Queries

| Archivo | Descripción breve |
|---------|-----------------|
| GetAllParkingSpacesQuery.cs | Lista todos los espacios y su estado actual |
| GetParkingSpaceByIdQuery.cs | Obtiene un espacio específico por ID |
| GetSensorByParkingSpaceIdQuery.cs | Obtiene sensor asociado a un espacio |
| GetIoTDeviceStatusQuery.cs | Retorna estado actual del ESP32 central |

---

## Repositories (Interfaces)

| Archivo | Descripción breve |
|---------|-----------------|
| IParkingSpaceRepository.cs | Define operaciones sobre espacios: FindById, FindAll, UpdateStatus |
| ISensorRepository.cs | Operaciones sobre sensores: FindById, FindByParkingSpaceId, UpdateState |
| IIoTDeviceRepository.cs | Operaciones sobre ESP32: FindById, UpdateConnectionStatus |

---

## ParkingSpace Services

| Archivo | Descripción breve |
|---------|-----------------|
| IParkingSpaceCommandService.cs | Comandos de espacios: asignación y actualización de estado |
| IParkingSpaceQueryService.cs | Consultas de espacios y estados actuales |

---

## Sensor Services

| Archivo | Descripción breve |
|---------|-----------------|
| ISensorCommandService.cs | Comandos de sensores: actualización de estado y distancia |
| ISensorQueryService.cs | Consultas de sensores por espacio o ID |

---

## IoTDevice Services

| Archivo | Descripción breve |
|---------|-----------------|
| IIoTDeviceCommandService.cs | Comandos de ESP32: conexión y desconexión |
| IIoTDeviceQueryService.cs | Consultas de estado del dispositivo |

<br>

#### 4.2.3.2. Interface Layer

**Interface Layer – Presentación de la Aplicación**  

La carpeta `Interfaces/REST` representa la capa de presentación de la arquitectura, encargada de recibir solicitudes HTTP, transformarlas en comandos o queries, y devolver respuestas adecuadas al cliente.

---

### Resources
Las clases Resource funcionan como objetos de transferencia entre el mundo externo (API REST) y la capa de aplicación.

| Archivo | Función |
|---------|---------|
| CreateParkingSpaceResource.cs | Recibe datos para crear un nuevo espacio de estacionamiento desde el cliente. |
| UpdateSpaceStatusResource.cs | Permite actualizar el estado de un espacio (AVAILABLE, RESERVED, OCCUPIED, MAINTENANCE). |
| ParkingSpaceResource.cs | Devuelve información de un espacio de estacionamiento. |
| CreateIoTDeviceResource.cs | Recibe datos para registrar un nuevo dispositivo IoT (ESP32). |
| IoTDeviceResource.cs | Devuelve información de un dispositivo IoT. |
| UpdateSensorStateResource.cs | Permite cambiar el estado de un sensor (activo/inactivo). |
| SensorResource.cs | Devuelve información de un sensor HC-SR04. |
| UpdateLEDStatusResource.cs | Permite actualizar el color o estado de un LED de un espacio. |
| LEDResource.cs | Devuelve información del LED asociado a un espacio. |

---

### Transform / Assemblers
Las clases de la carpeta `Transform` (también llamadas Assemblers) son responsables de:

- Convertir Resources en Command Objects para que los maneje la capa de aplicación.
- Convertir entidades del dominio en Resources para que sean devueltos en la respuesta de la API.

| Archivo | Función |
|---------|---------|
| CreateParkingSpaceCommandFromResourceAssembler.cs | Transforma `CreateParkingSpaceResource` en `CreateParkingSpaceCommand`. |
| UpdateSpaceStatusCommandFromResourceAssembler.cs | Transforma `UpdateSpaceStatusResource` en `UpdateSpaceStatusCommand`. |
| ParkingSpaceResourceFromEntityAssembler.cs | Convierte una entidad `ParkingSpace` en `ParkingSpaceResource`. |
| CreateIoTDeviceCommandFromResourceAssembler.cs | Transforma `CreateIoTDeviceResource` en `CreateIoTDeviceCommand`. |
| IoTDeviceResourceFromEntityAssembler.cs | Convierte una entidad `IoTDevice` en `IoTDeviceResource`. |
| UpdateSensorStateCommandFromResourceAssembler.cs | Transforma `UpdateSensorStateResource` en `UpdateSensorStateCommand`. |
| SensorResourceFromEntityAssembler.cs | Convierte una entidad `Sensor` en `SensorResource`. |
| UpdateLEDStatusCommandFromResourceAssembler.cs | Transforma `UpdateLEDStatusResource` en `UpdateLEDStatusCommand`. |
| LEDResourceFromEntityAssembler.cs | Convierte una entidad `LED` en `LEDResource`. |

---

### Controllers
Cada entidad clave en el Bounded Context `Space & IoT Management` cuenta con un REST Controller.  
Estos controladores definen los endpoints públicos de la aplicación y orquestan los flujos de ejecución:

| Controlador | Ruta base típica | Responsabilidad principal |
|-------------|-----------------|--------------------------|
| ParkingSpaceController.cs | /api/parkingspace | Gestiona la creación, actualización y consulta de espacios de estacionamiento. |
| IoTDeviceController.cs | /api/iotdevice | Maneja el registro y consulta de dispositivos IoT (ESP32). |
| SensorController.cs | /api/sensor | Expone endpoints para crear, actualizar y consultar sensores HC-SR04. |
| LEDController.cs | /api/led | Expone endpoints para actualizar y consultar el estado de los LEDs de los espacios. |

<br>

#### 4.2.3.3. Application Layer

**Servicios de Aplicación – Gestión de Flujos de Negocio**

---

### Command Services
| Clase | Descripción |
|-------|------------|
| ParkingSpaceCommandService.cs | Maneja comandos para crear un espacio de estacionamiento, actualizar su estado o configurar parámetros de ocupación. Utiliza el agregado ParkingSpace. |
| IoTDeviceCommandService.cs | Administra la creación, configuración y actualización de dispositivos IoT (ESP32). |
| SensorCommandService.cs | Administra la creación y actualización de sensores HC-SR04 asociados a los espacios de estacionamiento. |
| LEDCommandService.cs | Administra la actualización de LEDs RGB de los espacios (colores y estado). |

---

### Query Services
| Clase | Descripción |
|-------|------------|
| ParkingSpaceQueryService.cs | Devuelve información de espacios filtrada por ID, estado, disponibilidad o asignación. Utiliza ParkingSpaceResource para evitar ciclos. |
| IoTDeviceQueryService.cs | Lista dispositivos IoT por ID, estado, ubicación o conectividad. |
| SensorQueryService.cs | Devuelve información de sensores por ID, estado o espacio asociado. |
| LEDQueryService.cs | Lista el estado de LEDs por espacio, color actual y estado operativo. |

---

### Capabilities del Bounded Context Space & IoT Management
*Extraído del Bounded Context Canvas y el Event Storming elaborado:*

<br>

| Capability (Funcionalidad) | Tipo    | Handler Responsable                               | Descripción                                                                 |
|----------------------------|--------|--------------------------------------------------|----------------------------------------------------------------------------|
| ✅ Assign Space            | Command | SpaceCommandService.Handle(AssignSpaceCommand)  | Asigna un espacio disponible a un usuario tras la creación de la reserva. |
| ✅ Release Space           | Command | SpaceCommandService.Handle(ReleaseSpaceCommand) | Libera el espacio cuando el usuario decide retirarse, actualizando estado y tiempo. |
| ✅ Update Space Status     | Command | SpaceCommandService.Handle(UpdateSpaceStatusCommand) | Cambia el estado del espacio (AVAILABLE, RESERVED, OCCUPIED, MAINTENANCE). |
| ✅ Vehicle Detected        | Event   | SpaceEventHandler.Handle(VehicleDetectedEvent)  | Sensor detecta presencia de un vehículo y actualiza automáticamente el estado del espacio. |
| ✅ Vehicle Left            | Event   | SpaceEventHandler.Handle(VehicleLeftEvent)      | Sensor detecta que el vehículo se retiró y activa liberación de espacio y cálculo de tiempo. |
| ✅ LED Status Changed      | Event   | IoTCommandService.Handle(UpdateLEDStatusCommand) | Actualiza color de LED según estado del espacio (verde, azul, rojo). |
| ✅ Sensor Data Received    | Event   | IoTCommandService.Handle(ProcessSensorDataEvent) | Recibe y procesa datos de sensores HC-SR04 para detección de vehículos. |
| ✅ Timer Started           | Event   | TimeTrackingService.Handle(StartTimerEvent)     | Inicia cronómetro cuando se detecta que un vehículo ha ocupado un espacio. |
| ✅ Timer Stopped           | Event   | TimeTrackingService.Handle(StopTimerEvent)      | Detiene cronómetro cuando el usuario libera el espacio. |
| ✅ Duration Calculated     | Event   | TimeTrackingService.Handle(CalculateDurationEvent) | Calcula el tiempo total que el usuario ocupó el espacio y lo registra en el historial. |

<br>

#### 4.2.3.4. Infrastructure Layer

### Implementación de Repositories

| Clase                     | Interfaz implementada       | Función principal                                                                 |
|----------------------------|----------------------------|---------------------------------------------------------------------------------|
| SpaceRepository.cs         | ISpaceRepository           | Implementa operaciones de persistencia y consultas sobre los espacios de estacionamiento, incluyendo búsqueda por estado (AVAILABLE, RESERVED, OCCUPIED, MAINTENANCE) y asignación/liberación de espacios. |
| IoTDeviceRepository.cs     | IIoTDeviceRepository       | Gestiona la persistencia de los dispositivos IoT (ESP32), incluyendo conexión, desconexión y estado en tiempo real. |
| SensorRepository.cs        | ISensorRepository          | Maneja la persistencia de sensores HC-SR04, incluyendo recepción de datos, estado y calibración. |
| LEDRepository.cs           | ILEDRepository             | Persiste y gestiona los estados de los LEDs RGB de cada espacio (verde, azul, rojo). |
| TimeTrackingRepository.cs  | ITimeTrackingRepository    | Almacena registros históricos de tiempo de uso de cada espacio y estadísticas para análisis y reportes. |

<br>

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

En el diagrama de componentes en el contexto Space & IoT Management se puede observar la interacción del usuario al hacer consultas relacionadas a espacios de estacionamiento y el estado de sensores IoT. 

### Web Services

<img src="./assets/img/Chapter-IV/space-iot-web-services.png">

Se muestra el diagrama de componentes del Web Services, desde la solicitud del front end, comunicación con otros bounded contexts y consultas a la base de datos.

<br>

### Web Application

<img src="./assets/img/Chapter-IV/space-iot-web-app.png">

Se muestra el diagrama de componentes de Web Application, mostrando los componentes y páginas relacionados entre sí.

<br>

### Mobile Application

<img src="./assets/img/Chapter-IV/space-iot-mobile.png">

Se muestra el diagrama de componentes del Mobile Application, mostrando los Widgets relacionados entre sí.

<br>


#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

En el siguiente diagrama de clases se muestran las interfaces, clases e implementaciones de repositorios que conforman el bounded context actual. Este diagrama permite visualizar la estructura interna del dominio, así como las relaciones y dependencias entre los distintos componentes que lo integran.

<img src="./assets/img/Chapter-IV/space-iot-domain-layer-class-diagram.png">

<br>

**Bounded Context Domain Layer Class Diagrams Embedded Application**

<img src="./assets/img/Chapter-IV/space-iot-embedded-class-diagram.png">

<br>

##### 4.2.3.6.2. Bounded Context Database Design Diagram

<img src="./assets/img/Chapter-IV/space-iot-database-diagram.jpeg">

<br>

Las tablas principales y únicas del Bounded Context Space & IoT Management son:

## `parking_spaces`
**Atributos principales:**

| **Atributo** | **Tipo** | **Descripción** |
|---|---|---|
| `space_id` | varchar(36) | Identificador único del espacio |
| `code` | varchar(1) | Código del espacio (A, B, C) |
| `status` | enum | Estado actual (`AVAILABLE`, `RESERVED`, `OCCUPIED`, `MAINTENANCE`) |
| `current_reservation_id` | varchar(36)? | ID de la reserva activa asignada |
| `last_updated` | timestamp | Última actualización del estado |
| `created_at` | timestamp | Fecha de creación |

## `sensors`
**Atributos principales:**

| **Atributo** | **Tipo** | **Descripción** |
|---|---|---|
| `sensor_id` | varchar(36) | Identificador único del sensor |
| `space_id` | varchar(36) | Relación con el espacio de estacionamiento |
| `last_distance` | decimal(5,2)? | Última medición de distancia |
| `state` | enum | Estado del sensor (`ACTIVE`, `INACTIVE`, `ERROR`) |
| `last_detected` | timestamp? | Última detección de vehículo |
| `created_at` | timestamp | Fecha de creación |

## `space_led_status`
**Atributos principales:**

| **Atributo** | **Tipo** | **Descripción** |
|---|---|---|
| `led_id` | varchar(36) | Identificador único del LED |
| `space_id` | varchar(36) | Relación con el espacio (1:1) |
| `color` | enum | Color actual (`GREEN`, `BLUE`, `RED`, `YELLOW`) |
| `status` | enum | Estado operativo (`ON`, `OFF`, `BLINKING`, `ERROR`) |
| `last_updated` | timestamp | Última actualización |
| `created_at` | timestamp | Fecha de creación |

## `arrival_events`
**Atributos principales:**

| **Atributo** | **Tipo** | **Descripción** |
|---|---|---|
| `event_id` | varchar(36) | Identificador único del evento |
| `reservation_id` | varchar(36) | Relación con reserva (contexto externo) |
| `space_id` | varchar(36) | Espacio donde se detectó llegada |
| `timestamp` | timestamp | Momento de detección automática |
| `created_at` | timestamp | Fecha de registro |

## `departure_events`
**Atributos principales:**

| **Atributo** | **Tipo** | **Descripción** |
|---|---|---|
| `event_id` | varchar(36) | Identificador único del evento |
| `reservation_id` | varchar(36) | Relación con reserva (contexto externo) |
| `space_id` | varchar(36) | Espacio donde se detectó salida |
| `timestamp` | timestamp | Momento de detección automática |
| `created_at` | timestamp | Fecha de registro |

## `iot_devices`
**Atributos principales:**

| **Atributo** | **Tipo** | **Descripción** |
|---|---|---|
| `device_id` | varchar(36) | Identificador único del dispositivo |
| `name` | varchar(50) | Nombre descriptivo (ESP32-Central) |
| `ip_address` | varchar(15) | Dirección IP del dispositivo |
| `mac_address` | varchar(17) | Dirección MAC única |
| `is_connected` | boolean | Estado de conectividad |
| `last_sync` | timestamp? | Última sincronización exitosa |
| `created_at` | timestamp | Fecha de registro |

## `sensor_readings`
**Atributos principales:**

| **Atributo** | **Tipo** | **Descripción** |
|---|---|---|
| `reading_id` | varchar(36) | Identificador único de lectura |
| `sensor_id` | varchar(36) | Relación con el sensor |
| `distance_cm` | decimal(5,2) | Distancia medida por HC-SR04 |
| `vehicle_detected` | boolean | Indicador de detección |
| `timestamp` | timestamp | Momento de la medición |
| `created_at` | timestamp | Fecha de registro |

<br>


### 4.2.4. Bounded Context: Time Tracking

El **Bounded Context Time Tracking** registra y gestiona el tiempo de uso de los espacios de estacionamiento sin límites temporales.  
Su objetivo es iniciar, detener y calcular la duración de cada sesión de estacionamiento a partir de los eventos de llegada y salida enviados por el **Space & IoT Management**.  
Los datos generados se utilizan para métricas, reportes y, eventualmente, procesos de facturación o penalización.

#### 4.2.4.1. Domain Layer.

Agregados y Entidades del Dominio **Time Tracking** en nuestra Web/Mobile Application.

En la carpeta `domain` dentro de este Bounded Context se definen las entidades, agregados y servicios de dominio que encapsulan la lógica de negocio principal.

##### TimeSession
Representa una sesión de tiempo de uso de un espacio de estacionamiento.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| Id | int | Identificador único de la sesión |
| UserId | int | ID del usuario que ocupa el espacio |
| ParkingSpaceId | int | ID del espacio de estacionamiento utilizado |
| StartTime | DateTime | Fecha y hora de inicio |
| EndTime | DateTime? | Fecha y hora de finalización (puede ser nulo mientras la sesión está activa) |
| Duration | TimeSpan? | Duración total calculada cuando la sesión termina |
| Status | string | Estado de la sesión (ACTIVE, COMPLETED, CANCELLED) |

**Constructores**  
- Por parámetros individuales  
- A partir de `StartTimerCommand` y `StopTimerCommand`

##### Timer
Entidad que representa el cronómetro interno de la sesión.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| Id | int | Identificador único del cronómetro |
| TimeSessionId | int | Relación con la sesión de tiempo |
| StartTick | DateTime | Momento exacto en que se inició |
| StopTick | DateTime? | Momento exacto en que se detuvo |
| Elapsed | TimeSpan? | Tiempo transcurrido |

**Constructores**  
- Por parámetros individuales  
- Desde evento `TimerStartedEvent` y `TimerStoppedEvent`

##### TimeRecord
Registro histórico de uso de un espacio, derivado de una sesión completada.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| Id | int | Identificador único |
| UserId | int | ID del usuario |
| ParkingSpaceId | int | ID del espacio |
| Duration | TimeSpan | Duración final |
| DateRecorded | DateTime | Fecha de registro del historial |

##### DurationCalculator (Domain Service)
Servicio de dominio que encapsula la lógica para calcular la duración de una sesión.

**Métodos**  
- `Calculate(TimeSession session): TimeSpan`

**Comandos**

| Comando | Descripción |
|---------|------------|
| StartTimerCommand.cs | Inicia una nueva sesión de tiempo al recibir evento de llegada |
| StopTimerCommand.cs | Detiene la sesión al recibir evento de salida |
| CalculateDurationCommand.cs | Calcula la duración total de la sesión y actualiza el registro |

**Queries**

| Archivo | Descripción |
|---------|------------|
| GetActiveSessionByUserQuery.cs | Obtiene la sesión activa de un usuario |
| GetTimeHistoryByUserQuery.cs | Lista histórico de tiempos de un usuario |
| GetSpaceUsageQuery.cs | Devuelve uso de tiempo por espacio |

**Repositories (Interfaces)**

| Archivo | Descripción |
|---------|------------|
| ITimeSessionRepository.cs | Operaciones CRUD y búsqueda por usuario o espacio |
| ITimeRecordRepository.cs | Persistencia de registros históricos |
| ITimerRepository.cs | Persistencia de cronómetros activos |

**Domain Services**

| Archivo | Descripción |
|---------|------------|
| ITimeTrackingCommandService.cs | Comandos: iniciar, detener, calcular duración |
| ITimeTrackingQueryService.cs | Consultas: historial, sesiones activas |

#### 4.2.4.2. Interface Layer.

Interface Layer – Presentación de la Aplicación.

Esta capa expone los endpoints REST y transforma las solicitudes HTTP en comandos/queries para la capa de aplicación.

**Resources**

| Archivo | Función |
|---------|--------|
| StartTimerResource.cs | Recibe datos para iniciar cronómetro (UserId, ParkingSpaceId) |
| StopTimerResource.cs | Recibe datos para detener cronómetro |
| TimeSessionResource.cs | Devuelve información de una sesión (inicio, fin, duración) |
| TimeRecordResource.cs | Devuelve información histórica de uso |

**Transform/Assemblers**

| Archivo | Función |
|---------|--------|
| StartTimerCommandFromResourceAssembler.cs | Convierte StartTimerResource en StartTimerCommand |
| StopTimerCommandFromResourceAssembler.cs | Convierte StopTimerResource en StopTimerCommand |
| TimeSessionResourceFromEntityAssembler.cs | Convierte entidad TimeSession en TimeSessionResource |
| TimeRecordResourceFromEntityAssembler.cs | Convierte entidad TimeRecord en TimeRecordResource |

**Controllers**

| Controlador | Ruta base típica | Responsabilidad principal |
|-------------|------------------|--------------------------|
| TimeTrackingController.cs | /api/timetracking | Gestiona el inicio/detención de cronómetros y consulta de sesiones activas |
| TimeHistoryController.cs | /api/timetracking/history | Expone el historial de uso de tiempo por usuario o espacio |

#### 4.2.4.3. Application Layer.

Servicios de Aplicación – Gestión de Flujos de Negocio.

**Command Services**

| Clase | Descripción |
|-------|------------|
| TimeTrackingCommandService.cs | Maneja inicio, detención y cálculo de duración de una sesión; utiliza `TimeSession` y `Timer`. |

**Query Services**

| Clase | Descripción |
|-------|------------|
| TimeTrackingQueryService.cs | Devuelve información de sesiones activas, histórico de tiempo por usuario o por espacio. |

**Eventos clave**

- ✅ **Timer Started Event**: Se dispara cuando el Space & IoT Management detecta llegada.  
- ✅ **Timer Stopped Event**: Se dispara cuando se detecta salida.  
- ✅ **Duration Calculated Event**: Calcula y persiste la duración final en `TimeRecord`.  
- ✅ **Session Expired Event** (opcional): Maneja sesiones que no fueron cerradas correctamente.

#### 4.2.4.4. Infrastructure Layer.

Implementación de Repositories y adaptadores externos.

| Clase | Interfaz Implementada | Función Principal |
|-------|----------------------|------------------|
| TimeSessionRepository.cs | ITimeSessionRepository | Persiste y consulta sesiones de tiempo en la base de datos relacional (PostgreSQL/MySQL). |
| TimeRecordRepository.cs | ITimeRecordRepository | Persiste registros históricos para análisis posteriores. |
| TimerRepository.cs | ITimerRepository | Gestiona datos de cronómetros en curso. |
| TimeTrackingEventPublisher.cs | — | Publica eventos de inicio/detención a otros contextos (por ejemplo, Analytics & Reporting). |
| RealTimeDisplayAdapter.cs | — | Actualiza pantallas o notificaciones en vivo para el usuario. |


#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams  

En el diagrama de componentes del contexto **Time Tracking** se observa la interacción del usuario con el servicio para iniciar y finalizar sesiones de tiempo, además de las dependencias entre controladores, servicios de aplicación, agregados de dominio y repositorios.  

<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/time-component-c4.png" alt="Time Tracking Component C4" width="90%" />
</div><br>

URL Structurizr: https://structurizr.com/share/102034

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams  
##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams  

El siguiente diagrama de clases muestra las entidades, servicios de dominio, interfaces de repositorio y sus relaciones que conforman el **bounded context Time Tracking**. Incluye las clases **TimeSession**, **Timer**, **TimeRecord**, el servicio de dominio **DurationCalculator** y las interfaces de repositorios que garantizan la persistencia.  

<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/time-diagramclass.png" alt="Time Tracking Domain Layer Class Diagram" width="90%" />
</div><br>

Link: https://lucid.app/lucidchart/12a7e0a9-9b1c-48d8-a6dd-ab1b1fdc7d9c/edit?viewport_loc=-456%2C-116%2C2232%2C1049%2CHWEp-vi-RSFO&invitationId=inv_c243830e-22c1-42ae-a345-cae63204a020

##### 4.2.4.6.2. Bounded Context Database Design Diagram  

El diagrama entidad-relación (ERD) de la base de datos para **Time Tracking** presenta las tablas **TimeSessions**, **Timers** y **TimeRecords**, junto con sus llaves primarias, foráneas y restricciones, reflejando la persistencia de sesiones, cronómetros y registros históricos.  

<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/time-database.png" alt="Time Tracking Database Design Diagram" width="90%" />
</div><br>

### 4.2.5. Bounded Context: Penalty Management

El **Bounded Context Penalty Management** administra el sistema de penalizaciones “3 Strikes” configurable basado en **ausencias automáticas**, sin intervención manual.  
Su objetivo es detectar usuarios que no se presenten en el estacionamiento dentro de la ventana configurada, acumular “strikes” y aplicar suspensiones temporales, enviando advertencias y reactivaciones según las reglas de negocio.

#### 4.2.5.1. Domain Layer.

Agregados y Entidades del Dominio **Penalty Management** en nuestra Web/Mobile Application.

En la carpeta `domain` de este Bounded Context se encuentran las clases principales que encapsulan la lógica de negocio para la detección de ausencias, emisión de advertencias y suspensión de usuarios.

##### Absence
Representa una ausencia registrada cuando un usuario no llega en el tiempo establecido.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| Id | int | Identificador único de la ausencia |
| UserId | int | ID del usuario ausente |
| ReservationId | int | ID de la reserva no utilizada |
| DetectedAt | DateTime | Fecha y hora en que se detectó la ausencia |

**Constructores**  
- Por parámetros individuales  
- Desde `RegisterAbsenceCommand`

##### AbsenceCounter
Contador de ausencias acumuladas por usuario.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| Id | int | Identificador del contador |
| UserId | int | ID del usuario |
| StrikeCount | int | Número de ausencias registradas |
| MaxStrikes | int | Límite de strikes configurable (2–5) |
| LastUpdated | DateTime | Última fecha de actualización |

**Métodos de dominio**  
- `IncrementStrike()` – Incrementa el número de ausencias.  
- `ResetCounter()` – Reinicia el contador tras suspensión.

##### Suspension
Entidad que representa la suspensión de un usuario por alcanzar el máximo de strikes.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| Id | int | Identificador único |
| UserId | int | ID del usuario suspendido |
| StartDate | DateTime | Fecha de inicio de la suspensión |
| EndDate | DateTime | Fecha de reactivación automática |
| Status | string | Estado (ACTIVE, COMPLETED) |

**Métodos de dominio**  
- `Activate()` – Activa suspensión.  
- `Complete()` – Marca la suspensión como finalizada.

##### Warning
Advertencia emitida antes de la suspensión.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| Id | int | Identificador único |
| UserId | int | ID del usuario |
| Message | string | Mensaje de advertencia |
| CreatedAt | DateTime | Fecha de emisión |

##### PenaltyRules (Value Object)
Objeto de valor que define las reglas de penalización configurables.

| Atributo | Tipo | Descripción |
|----------|------|------------|
| MaxStrikes | int | Límite de ausencias antes de suspensión |
| SuspensionDays | int | Días de suspensión automática |
| WindowMinutes | int | Minutos de ventana de llegada antes de marcar ausencia |

**Comandos**

| Comando | Descripción |
|---------|------------|
| RegisterAbsenceCommand.cs | Registra una nueva ausencia al no detectar llegada |
| IssueWarningCommand.cs | Emite una advertencia por ausencia |
| SuspendUserCommand.cs | Suspende usuario tras alcanzar máximo de strikes |
| ReactivateUserCommand.cs | Reactiva usuario al finalizar período de suspensión |
| ResetAbsenceCounterCommand.cs | Reinicia el contador de ausencias |
| ConfigurePenaltyRulesCommand.cs | Actualiza las reglas de penalización |

**Queries**

| Archivo | Descripción |
|---------|------------|
| GetAbsenceHistoryByUserQuery.cs | Lista las ausencias de un usuario |
| GetCurrentSuspensionQuery.cs | Obtiene información de la suspensión actual |
| GetPenaltyRulesQuery.cs | Consulta las reglas de penalización vigentes |
| GetAbsenceCounterQuery.cs | Devuelve el contador de ausencias actual de un usuario |

**Repositories (Interfaces)**

| Archivo | Descripción |
|---------|------------|
| IAbsenceRepository.cs | CRUD de ausencias |
| IAbsenceCounterRepository.cs | Maneja contador de ausencias por usuario |
| ISuspensionRepository.cs | Persiste y consulta suspensiones activas o completadas |
| IWarningRepository.cs | Registra advertencias enviadas |
| IPenaltyRulesRepository.cs | Gestiona las reglas de penalización configurables |

**Domain Services**

| Archivo | Descripción |
|---------|------------|
| IPenaltyCommandService.cs | Orquesta la lógica para registrar ausencias, emitir advertencias y suspender usuarios |
| IPenaltyQueryService.cs | Consulta histórico de ausencias, suspensiones y reglas |

#### 4.2.5.2. Interface Layer.

Interface Layer – Presentación de la Aplicación.

La carpeta `interfaces/REST` expone endpoints que permiten al sistema y a los administradores consultar o actualizar las penalizaciones y reglas.

**Resources**

| Archivo | Función |
|---------|--------|
| RegisterAbsenceResource.cs | Datos para registrar una ausencia automática |
| WarningResource.cs | Devuelve datos de advertencias emitidas |
| SuspensionResource.cs | Devuelve información de suspensiones activas |
| PenaltyRulesResource.cs | Muestra las reglas actuales de penalización |
| UpdatePenaltyRulesResource.cs | Permite a un administrador actualizar las reglas (strikes, días de suspensión, ventana de llegada) |

**Transform/Assemblers**

| Archivo | Función |
|---------|--------|
| RegisterAbsenceCommandFromResourceAssembler.cs | Convierte RegisterAbsenceResource en RegisterAbsenceCommand |
| UpdatePenaltyRulesCommandFromResourceAssembler.cs | Convierte UpdatePenaltyRulesResource en ConfigurePenaltyRulesCommand |
| SuspensionResourceFromEntityAssembler.cs | Convierte entidad Suspension en SuspensionResource |
| WarningResourceFromEntityAssembler.cs | Convierte entidad Warning en WarningResource |

**Controllers**

| Controlador | Ruta base típica | Responsabilidad principal |
|-------------|------------------|--------------------------|
| PenaltyController.cs | /api/penalty | Expone endpoints para registro de ausencias y emisión de advertencias |
| SuspensionController.cs | /api/penalty/suspension | Consulta y gestión de suspensiones de usuarios |
| PenaltyRulesController.cs | /api/penalty/rules | Consulta y actualización de reglas de penalización |

#### 4.2.5.3. Application Layer.

Servicios de Aplicación – Gestión de Flujos de Negocio.

**Command Services**

| Clase | Descripción |
|-------|------------|
| PenaltyCommandService.cs | Orquesta la lógica para registrar ausencias, emitir advertencias, suspender usuarios y reactivar automáticamente. |

**Query Services**

| Clase | Descripción |
|-------|------------|
| PenaltyQueryService.cs | Permite consultas de ausencias, suspensiones y reglas de penalización. |

**Eventos clave**

- ✅ **Absence Detected Event**: Disparado por Reservation Management cuando no hay llegada dentro de la ventana configurada.  
- ✅ **Warning Issued Event**: Notifica al Notification Context sobre la advertencia al usuario.  
- ✅ **User Suspended Event**: Marca y comunica la suspensión.  
- ✅ **User Reactivated Event**: Reactiva el acceso del usuario tras el período configurado.  

#### 4.2.5.4. Infrastructure Layer.

Implementación de Repositories y adaptadores externos.

| Clase | Interfaz Implementada | Función Principal |
|-------|----------------------|------------------|
| AbsenceRepository.cs | IAbsenceRepository | Persiste ausencias registradas y permite filtrado por usuario o fecha |
| AbsenceCounterRepository.cs | IAbsenceCounterRepository | Gestiona el conteo de ausencias de cada usuario |
| SuspensionRepository.cs | ISuspensionRepository | Persiste suspensiones activas, fechas y reactivaciones automáticas |
| WarningRepository.cs | IWarningRepository | Almacena advertencias emitidas |
| PenaltyRulesRepository.cs | IPenaltyRulesRepository | Mantiene la configuración de reglas de penalización |
| PenaltyEventPublisher.cs | — | Publica eventos hacia Notification Context para envío de alertas |
| SchedulerAdapter.cs | — | Programa tareas automáticas para reactivación de usuarios después del período de suspensión |

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams  

En el diagrama de componentes del contexto **Penalty Management** se evidencia la orquestación de ausencias, advertencias y suspensiones. Se detallan los controladores REST, servicios de aplicación, agregados de dominio y repositorios encargados de administrar reglas de penalización, contadores de ausencias y suspensiones.  

<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/penalty-component-c4.png" alt="Penalty Management Component C4" width="90%" />
</div><br>

URL Structurizr: https://structurizr.com/share/84646

#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams  
##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams  

En este diagrama se aprecian las entidades **Absence**, **AbsenceCounter**, **Suspension**, **Warning** y el value object **PenaltyRules**, además de las interfaces de repositorio y servicios de dominio que encapsulan la lógica de negocio del **bounded context Penalty Management**.  

<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/penalty-diagramclass.png" alt="Penalty Management Domain Layer Class Diagram" width="90%" />
</div><br>

Link: https://lucid.app/lucidchart/4d516fa9-fed5-4131-8a22-16207e3b05a0/edit?viewport_loc=-3820%2C-575%2C6132%2C2883%2CHWEp-vi-RSFO&invitationId=inv_709a7505-bf02-440a-87b9-406019cc1dca

##### 4.2.5.6.2. Bounded Context Database Design Diagram  

El diagrama entidad-relación (ERD) de **Penalty Management** representa las tablas **Absences**, **AbsenceCounters**, **Suspensions** y **Warnings**, incluyendo sus claves primarias, relaciones de usuario y constraints necesarias para gestionar las penalizaciones.  

<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/penalty-database.png" alt="Penalty Management Database Design Diagram" width="90%" />
</div><br>

### 4.2.6. Bounded Context: Analytics & Reporting

#### Introduccion
Este bounded context es responsable de generar, almacenar y proveer métricas, reportes y análisis relacionados al uso del sistema de estacionamientos inteligentes. Sus objetivos son optimizar la gestión de los espacios, identificar patrones de comportamiento de los usuarios, medir la eficiencia de los espacios y ofrecer a los administradores un panel de control con indicadores clave de rendimiento (KPIs).
#### 4.2.6.1. Domain Layer
En esta capa definimos las entidades y objetos de valor que representan el núcleo del negocio de Analytics & Reporting.

#### Entities

##### **UsageMetric**

Representa una métrica puntual del uso de un espacio de estacionamiento.

#### Atributos

- `metricId`: Identificador único de métrica
- `spaceId`: Identificador del espacio asociado
- `vehicleId`: Identificador del vehículo (opcional, anonimizado)
- `startTime`: Inicio de ocupación
- `endTime`: Fin de ocupación
- `duration`: Tiempo total de uso

#### Métodos:

- `calculateDuration()`: number
- `isValid()`: boolean

#### Invariantes de Negocio:

- La duración debe ser mayor a 0
- Los tiempos deben ser consistentes (startTime < endTime)


##### **SpaceEfficiencyReport**

Reporte de eficiencia por espacio en un rango de tiempo.

#### Atributos:

- `reportId`: Identificador único
- `spaceId`: Identificador del espacio
- `totalTimeOccupied`: Total de tiempo ocupado
- `totalTimeAvailable`: Total de tiempo disponible
- `efficiencyRate`: Porcentaje de eficiencia calculado

#### Métodos:

- `calculateEfficiency()`: number

#### Invariantes de Negocio:

- `efficiencyRate = totalTimeOccupied / totalTimeAvailable`
- La eficiencia debe estar en rango 0–100%


##### **UserBehaviorPattern**

Describe patrones de comportamiento detectados en usuarios.

#### Atributos:

- `patternId`: Identificador único
- `userId`: Usuario asociado (anonimizado en reportes agregados)
- `frequentSpaces`: Lista de espacios más usados
- `peakHours`: Horas de mayor uso
- `averageDuration`: Tiempo promedio de ocupación

#### Métodos:

- `detectPeakHours()`: void
- `calculateAverageDuration()`: number



##### **AdminDashboard**

Representa el dashboard administrativo configurable.

#### Atributos:

- `dashboardId`: Identificador único
- `widgets`: Lista de KPIs y visualizaciones
- `lastUpdatedAt`: Fecha de última actualización

#### Métodos:

- `addWidget(widget: KPIWidget)`: void
- `removeWidget(widgetId: string)`: void
- `refreshData()`: void

##### Value Objects

##### **KPIWidget**
Value Object que encapsula un KPI configurable.

#### Atributos:

- `name`: Nombre del indicador
- `value`: Valor actual
- `target`: Meta establecida
- `unit`: Unidad de medida (%) / min / horas

#### Métodos:

- `isTargetMet()`: boolean


##### **ReportFormat**
Define el formato de exportación de un reporte.

#### Atributos:

- `type`: PDF | CSV | XLSX

#### Métodos:

 - `validateFormat()`: boolean

##### Aggregates
##### **AnalyticsAggregate**
Aggregate Root que orquesta la lógica de métricas, reportes y dashboards.

#### Entidades contenidas:

- UsageMetric
- SpaceEfficiencyReport
- UserBehaviorPattern
- AdminDashboard

#### Métodos del Aggregate:

- `generateUsageMetrics(data: RawIoTData): UsageMetric[]`
- `calculateEfficiencyReport(spaceId: string, period: DateRange): SpaceEfficiencyReport`
- `analyzeUserPatterns(userId: string): UserBehaviorPattern`
- `createDashboard(config: DashboardConfig): AdminDashboard`
- `exportReport(reportId: string, format: ReportFormat): File`


#### Domain Services

##### **AnalyticsService**
Servicio de dominio que maneja la lógica de análisis.

#### Métodos:

- `aggregateMetrics(period: DateRange): UsageMetric[]`
- `generateSpaceReports(period: DateRange): SpaceEfficiencyReport[]`
- `detectUserPatterns(users: User[]): UserBehaviorPattern[]`

##### Repository Interfaces
##### **IUsageMetricsRepository**

Persistencia de métricas de uso.

##### **IReportsRepository**

Persistencia de reportes de eficiencia.

##### **IDashboardRepository**

Persistencia de configuraciones de dashboard.


#### 4.2.6.2. Interface Layer
La capa de interfaz expone las capacidades del bounded context mediante APIs REST y endpoints de consulta.

##### Controllers
##### **AnalyticsController**
Controlador REST para generación de métricas.

#### Endpoints:

- `GET /api/analytics/usage: Obtener métricas de uso`
- `GET /api/analytics/efficiency: Obtener reportes de eficiencia`
- `GET /api/analytics/patterns: Analizar patrones de usuario`

##### **DashboardController**
Controlador para administración de dashboards.

#### Endpoints:

- `POST /api/dashboard: Crear dashboard`
- `PUT /api/dashboard/{id}: Actualizar configuración`
- `GET /api/dashboard/{id}: Ver dashboard`

##### **ReportExportController**

Controlador para exportación de reportes.

#### Endpoints:

- `GET /api/reports/{id}/export?format=pdf: Exportar reporte en formato`

##### DTOs

##### **UsageMetricResponse**
```
{
  spaceId: string,
  duration: number,
  startTime: string,
  endTime: string
}
```
##### **EfficiencyReportResponse**
```
{
  spaceId: string,
  efficiencyRate: number,
  totalTimeOccupied: number,
  totalTimeAvailable: number
}
```
##### **DashboardResponse**
```
{
  dashboardId: string,
  widgets: KPIWidget[]
}
```
#### 4.2.6.3. Application Layer
Coordina casos de uso entre dominio e infraestructura.

##### Command Handlers

##### **GenerateUsageMetricsCommandHandler**
##### **CalculateSpaceEfficiencyCommandHandler**
##### **AnalyzeUserPatternsCommandHandler**
##### **CreateAdminDashboardCommandHandler**

##### Query Handlers

##### **GetUsageMetricsQueryHandler**
##### **GetEfficiencyReportQueryHandler**
##### **GetUserPatternsQueryHandler**
##### **GetDashboardQueryHandler**

##### Event Handlers

##### **SpaceOccupiedEventHandler**
Actualiza métricas en tiempo real
##### **ReservationCreatedEventHandler** 
Impacta estadísticas de uso

#### 4.2.6.4. Infrastructure Layer
Implementa persistencia, integración y servicios externos.

##### Repository Implementations

##### **PostgresUsageMetricsRepository**
##### **PostgresReportsRepository**
##### **RedisDashboardRepository** (para dashboards en caché)

##### External Integrations

##### **IoTDataIngestionService** 
Procesa datos crudos de sensores
##### **ReportingExportService**
Genera archivos PDF/CSV/XLSX

##### Database Schema (Resumen)

#### Tabla: usage_metrics

- metric_id (UUID, PK)
- space_id (UUID, FK)
- start_time (TIMESTAMP)
- end_time (TIMESTAMP)
- duration (INT)

#### Tabla: efficiency_reports

- report_id (UUID, PK)
- space_id (UUID, FK)
- total_time_occupied (INT)
- total_time_available (INT)
- efficiency_rate (DECIMAL)

#### Tabla: dashboards

- dashboard_id (UUID, PK)
- widgets (JSONB)
- last_updated (TIMESTAMP)

##### Conclusión

El Bounded Context Analytics & Reporting proporciona una arquitectura robusta para la recolección, análisis y presentación de métricas.

#### Características clave:

- Visibilidad administrativa: KPIs y dashboards configurables
- Optimización operativa: Reportes de eficiencia por espacio
- Inteligencia de uso: Patrones de comportamiento de usuarios
- Exportabilidad: Reportes en múltiples formatos

Esto asegura que la gestión del sistema de estacionamientos no solo sea operativa, sino también estratégica, permitiendo decisiones basadas en datos.

#### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams

  <img src="./assets/img/Chapter-IV/Analytics_Reporting_c4.png" alt="Context Diagram" width="90%" />

#### 4.2.6.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.6.6.1. Bounded Context Domain Layer Class Diagrams

  <img src="./assets/img/Chapter-IV/analysis_class_diagram.png" alt="Context Diagram"/>

##### 4.2.6.6.2. Bounded Context Database Design Diagram

URL Vertabelo para apreciar mejor el diagrama de base de datos Analytics & Reporting: <a href="https://my.vertabelo.com/doc/yV4QquKh1vFJgVa60d7UfUDGHXiNYsSE">https://my.vertabelo.com/doc/yV4QquKh1vFJgVa60d7UfUDGHXiNYsSE</a>
<br><br>

**Analytics & Reporting Database Design Diagram**
<div style="text-align: center;">
  <img src="./assets/img/Chapter-IV/analytics-datatbase-diagram.png" alt="Analytics & Reporting Database Design Diagram" width="90%" />
</div><br><br>

### 4.2.7. Bounded Context: Notification
#### 4.2.7.1. Domain Layer
#### 4.2.7.2. Interface Layer
#### 4.2.7.3. Application Layer
#### 4.2.7.4. Infrastructure Layer
#### 4.2.7.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.7.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.7.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.7.6.2. Bounded Context Database Design Diagram



# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Landing Page Wireframe

### 5.3.2. Landing Page Mock-up

## 5.4. Applications UX/UI Design

### 5.4.1. Applications Wireframes

### 5.4.2. Applications Wireflow Diagrams

### 5.4.2. Applications Mock-ups

### 5.4.3. Applications User Flow Diagrams

## 5.5. Applications Prototyping


# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Source Code Style Guide & Conventions

### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.X. Sprint n

#### 6.2.X.1. Sprint Planning n

#### 6.2.X.2. Aspect Leaders and Collaborators

#### 6.2.X.3. Sprint Backlog n

#### 6.2.X.4. Development Evidence for Sprint Review

#### 6.2.X.5. Testing Suite Evidence for Sprint Review

#### 6.2.X.6. Execution Evidence for Sprint Review

#### 6.2.X.7. Services Documentation Evidence for Sprint Review

#### 6.2.X.8. Software Deployment Evidence for Sprint Review

#### 6.2.X.9. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews

### 6.3.1. Diseño de Entrevistas

### 6.3.2. Registro de Entrevistas

### 6.3.3. Evaluaciones según heurísticas

## 6.4. Video About-the-Product


# Conclusiones

## Conclusiones y recomendaciones

## Video About-the-Team

# Bibliografía

# Anexos
