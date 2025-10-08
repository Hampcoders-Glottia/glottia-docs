<h2 align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="logo-upc" width="200px" height="200px" align="center">
</h2>

<h1 align="center">Universidad Peruana de Ciencias Aplicadas</h1>

<h3 align="center">
  Ingeniería de Software
  <br><br>
  Curso: Aplicaciones para Dispositivos Móviles
  <br><br>
  Sección: 1818
  <br><br>
  Profesor: Eduardo Martin Reyes Rodriguez
  <br><br>
  Semestre: 2025-20
  <br><br>
  Informe del Trabajo Final
  <br><br>
  Startup: Hampcoders
  <br><br>
  Producto: Glottia
</h3>

<div align="center">

| <div style="width:300px">Alumno</div>       | <div style="width:125px">Código</div>       |
|:-------------------------------------------:|:-------------------------------------------:|
|       Ethan Matias Aliaga Aguirre           |            u202318323                       |
|       Leandro Saul Contreras López          |            u20231E215                       |
|       Italo Ludwing Sanchez Manrique        |            u202316967                       |
|       Ivo Marcelo Machado Bracamonte        |            u20231C368                       |
|       Rodrigo Jesus Miraval Pomalaya        |            u202311082                       |
|       Arnold Gabriel Morales Sosa           |            u201822516                       |

</div>

<div align="center"> Septiembre 2025 </div>

<hr>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe  
---

<div align="center">

| Versión | Fecha       | Autor(es)                                    | Descripción de modificación |
|---------|-------------|-----------------------------------------------|------------------------------|
|   TB1   | 16/09/2025  | **Ethan Matías Aliaga Aguirre**               | Redacción del Capítulo I a V. Diseño de arquitectura usando *Domain-Driven Design*. Implementación inicial de la landing page. Documentación técnica de componentes. Diseño de historias de usuario. Coordinación general del enfoque técnico del proyecto. |
|   TB1   | 16/09/2025  | **Leandro Saúl Contreras López**              | Elaboración de análisis competitivo y estrategias frente a competidores. Definición de *Lean UX Problem Statements* y *Assumptions*. Colaboración en entrevistas y registro de hallazgos. |
|   TB1   | 16/09/2025  | **Ítalo Ludwing Sánchez Manrique**            | Configuración del entorno de desarrollo. Gestión inicial del *Product Backlog*. Aportes en la estructura general del documento y lineamientos de SEO. |
|   TB1   | 16/09/2025  | **Ivo Marcelo Machado Bracamonte**            | Diseño de *User Personas*, *User Task Matrix* y flujos de usuario. Desarrollo de prototipos móviles y guía de estilos visuales. Apoyo en estructura narrativa del documento. |
|   TB1   | 16/09/2025  | **Rodrigo Jesús Miraval Pomalaya**            | Investigación de bases de datos relacionales y no relacionales. Propuesta de modelo de datos inicial. Redacción de *Requirements Specification* y contribución en *EventStorming*. |
|   TB1   | 16/09/2025  | **Piero Francesco Tenorio Medina**            | Apoyo en la definición de *User Journey Mapping* y *Empathy Mapping*. Contribución en la documentación de *Bounded Context Canvases*. Revisión de consistencia en *Context Mapping*. |
|   TB1   | 16/09/2025  | **Arnold Gabriel Morales Sosa**               | Configuración del repositorio en GitHub. Propuesta de flujo de control de versiones (*branching strategy*). Documentación del uso de herramientas colaborativas. Apoyo en la integración de *Software Architecture Diagrams*. |


---

</div>

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights

El informe del proyecto se ha gestionado de forma colaborativa mediante el siguiente repositorio en la organización de GitHub del equipo:

[Repositorio del Informe - GitHub](https://github.com/Hampcoders-Glottia/glottia-docs)

Este repositorio ha servido como espacio central para la redacción estructurada del informe final, el control de versiones, y la coordinación de contribuciones técnicas por parte de todos los integrantes del equipo.

A continuación, se presentan las evidencias de colaboración durante las distintas entregas, destacando el aporte activo de todos los miembros, en coherencia con el Registro de Versiones del Informe.

---

### TB1 – Inicio de Redacción y Estructura General del Informe

Durante la primera entrega se definió la estructura base del informe, incluyendo introducción, objetivos, justificación y marco metodológico. Se asignaron secciones de forma equitativa y se establecieron ramas para cada sección.

- Se registraron contribuciones constantes por parte de **WiDDsito**, **MatFragg**, **ItaloSanche**, **ivommb11** y **Arnold-ST**.
- La colaboración fue paralela y coordinada, sin conflictos de fusión.
- Se gestionaron ramas específicas por integrante para mantener un flujo limpio.

Captura de commits semanales por integrante:

<img src="https://i.postimg.cc/jjNBmwPP/commitsss.png"/>


---

# Contenido
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
  
- [Capítulo I: Introducción](#capítulo-i-introducción)
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
    
- [Capítulo II: Requirements Development \& Software Solution Design](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)
  - [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](#243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-drive-design)
    - [2.5.1. EventStorming](#251-event-storming)
        - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
        - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
        - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
        - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
        - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level)
        - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.x. Bounded Context: <Bounded Context Name>]()
        - [2.6.x.1. Domain Layer]()
        - [2.6.x.2. Interface Layer]()
        - [2.6.x.3. Application Layer]()
        - [2.6.x.4 Infrastructure Layer]()
        - [2.6.x.5. Bounded Context Software Architecture Component Level Diagrams]()
        - [2.6.x.6. Bounded Context Software Architecture Code Level Diagrams]()
            - [2.6.x.6.1. Bounded Context Domain Layer Class Diagrams]()
            - [2.6.x.6.2. Bounded Context Database Design Diagram]()

- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-ui-ux-design)
  - [3.1. Product Design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
        - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
        - [3.1.2.1. Organization Systems](#3121-organization-systems)
        - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
        - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
        - [3.1.2.4. Searching Systems](#3124-searching-systems)
        - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
  - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
        - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
        - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
  - [3.1.4. Mobile Applications UX/UI Design](#32-information-architecture)
        - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applicaction-wireframes)
        - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-application-wireflow-diagrams)
        - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
        - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
        - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
    
- [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation-and-validation)
  - [4.1. Software Configuration Management](#41-style-guidelines)
    - [4.1.1. Software Development Environment Configuration](#411-general-style-guidelines)
    - [4.1.2. Source Code Management](#412-web-style-guidelines)
    - [4.1.2. Source Code Style Guide & Conventions](#412-web-style-guidelines)
    - [4.1.2. Software Deployment Configuration](#412-web-style-guidelines)
  - [4.2. Landing Page & Mobile Application Implementation](#42-information-architecture)
    - [4.2.1. Sprint n](#421-organization-systems)
        - [4.2.1.1. Sprint Planning n](#422-labeling-systems)
        - [4.2.1.2. Sprint Backlog n](#422-labeling-systems)
        - [4.2.1.3. Development Evidence for Sprint Review](#422-labeling-systems)
        - [4.2.1.4. Testing Suite Evidence for Sprint Review](#422-labeling-systems)
        - [4.2.1.5. Execution Evidence for Sprint Review](#422-labeling-systems)
        - [4.2.1.6. Services Documentation Evidence for Sprint Review](#422-labeling-systems)
        - [4.2.1.7. Software Deployment Evidence for Sprint Review](#422-labeling-systems)
        - [4.2.1.8. Team Collaboration Insights during Sprint](#422-labeling-systems)
  - [4.3. Validation Interviews](#43-landing-page-ui-design)
    - [4.3.1. Diseño de Entrevistas](#442-web-applications-wireflow-diagrams)
    - [4.3.2. Registro de Entrevistas](#442-web-applications-mock-ups)
    - [4.3.3. Evaluaciones según heurísticas](#443-web-applications-user-flow-diagrams)
- [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  
<div style="page-break-after: always;"></div>

## Student Outcome 7 – Aprendizaje Autónomo y Continuo

En esta sección se evidencia cómo las actividades realizadas en el **Trabajo Final** han contribuido al desarrollo del **Outcome 7 de ABET – EAC**, referido a la *capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas*. Cada integrante del equipo ha asumido responsabilidades que implicaron la búsqueda, asimilación y aplicación de nuevos conceptos, metodologías y herramientas propias de la Ingeniería de Software. Estas acciones fortalecieron la autonomía del aprendizaje y la habilidad de adaptarse a desafíos técnicos y metodológicos reales.  

> *Adquiere y aplica nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.*

| **Criterio específico** | **Acciones realizadas (TB1)** | **Conclusiones (TB1)** |
|-------------------------|-------------------------------|-------------------------|
| **Demuestra capacidad de adquirir y aplicar nuevos conocimientos según sea necesario.** | **Aliaga Aguirre, Ethan Matías**<br>- Investigó y redactó la **Descripción de la Startup** y **Perfiles de Integrantes del Equipo**, aplicando metodologías de documentación empresarial.<br>- Contribuyó en la **Especificación de Requerimientos (User Stories, Impact Mapping, Product Backlog)**, investigando buenas prácticas en gestión de requisitos.<br><br>**Contreras López, Leandro Saúl**<br>- Elaboró la sección de **Antecedentes y Problemática**, contextualizando la solución en el marco de la industria EdTech.<br>- Participó en el **Diseño de Entrevistas y Registro**, aplicando técnicas de levantamiento de información para identificar necesidades reales de los usuarios.<br><br>**Machado Bracamonte, Ivo Marcelo**<br>- Desarrolló los entregables de **Lean UX Process** (Problem Statements, Assumptions, Hypothesis, Canvas), aprendiendo a aplicar esta metodología centrada en el usuario.<br>- Contribuyó en la construcción de **User Personas** y **User Task Matrix**, profundizando en técnicas de experiencia de usuario.<br><br>**Miraval Pomalaya, Rodrigo Jesús**<br>- Se encargó del **Análisis Competitivo** y de proponer **Estrategias frente a Competidores**, explorando marcos de referencia estratégicos en el desarrollo de software.<br>- Colaboró en la elaboración de **Context Mapping** y **EventStorming**, asimilando conceptos de Domain-Driven Design.<br><br>**Morales Sosa, Arnold Gabriel**<br>- Documentó y diagramó los apartados de **Arquitectura de Software** (Context Level, Container Level, Deployment), aprendiendo notación C4 y su aplicación en ingeniería de software.<br>- Participó en la redacción de **Ubiquitous Language**, vinculando conceptos técnicos con el dominio del negocio.<br><br>**Sánchez Manrique, Italo Ludwing**<br>- Lideró el diseño de **User Journey Mapping y Empathy Mapping**, investigando métodos de análisis de experiencia de usuario.<br>- Contribuyó en la construcción de los **Bounded Context Canvases** y en el modelado de capas de DDD (Domain, Interface, Application, Infrastructure). | **TB1:** El equipo demostró su capacidad de **aprender de manera autónoma** para abordar nuevas metodologías (Lean UX, Domain-Driven Design, C4, Needfinding) y herramientas de modelado. La investigación y aplicación práctica de estos enfoques redujo la incertidumbre en el diseño de la solución, permitió consolidar una base conceptual sólida y garantizó que cada entregable esté alineado con buenas prácticas de Ingeniería de Software. |

---

<div style="page-break-after: always;"></div>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
HampCoders es una startup innovadora que se enfoca en el desarrollo de soluciones empleando una arquitectura orientada a servicios, haciendo uso de tecnologías open-source. Mediante esta startup, buscamos conectar personas que desean practicar la comunicación en distintos idiomas, en grupo de manera presencial, en locales públicos que ofrezcan sus espacios como puntos de reunión. Es por eso que presentamos el proyecto “Glottia”.

### Misión:
Facilitar la práctica oral de idiomas a través de experiencias conversacionales reales, seguras y entretenidas, tanto en espacios públicos como virtuales, impulsando la confianza, la fluidez y la conexión entre personas con intereses lingüísticos comunes.

### Visión:
Convertirse en la comunidad global de referencia para la práctica de idiomas a través de conversaciones naturales, generando encuentros significativos entre personas que buscan mantener vivo un idioma a través del habla cotidiana y el intercambio cultural.


### 1.1.2. Perfiles de integrantes del equipo

| Miembros del equipo                             | Codigo Estudiante | Descripcion            |
| ----------------------------------------------- | ----------------- | ---------------------- |
| Italo Ludwing Sanchez Manrique	![Imagen del compañero](https://i.imgur.com/R1iMW0N.png)   | U202316967            | Mi nombre es Italo Ludwing Sanchez Manrique, soy estudiante de Ingeniería de Software en la UPC, tengo 19 años y actualmente curso el sexto ciclo académico. Destaco por mi perseverancia, tolerancia y compromiso con mis metas. En este proyecto, mi objetivo es buscar soluciones que beneficien al grupo, ya que tengo experiencia en trabajar de forma proactiva y colaborativa. Además, poseo sólidos conocimientos en lenguajes de programación como Java y C++. | 
| Ethan Matias Aliaga Aguirre	[![image.png](https://i.postimg.cc/sXYKCY1B/image.png)](https://postimg.cc/jwjyzJHK)   | U202318323            | Soy Ethan Matias Aliaga Aguirre, estudiante de 5to ciclo de Ingeniería de Software en la UPC, sede San Miguel. Me caracterizo por mi compromiso, responsabilidad, habilidad para trabajar en equipo y comunicación. Mis conocimientos Incluyen arquitectura de Software , desarrollo de APIs y Experiencias Web Full Stack. Además, tengo experiencia en el uso de herramientas como Photoshop, Filmadora y Vegas Studio, lo que me permite aportar con soluciones creativas y técnicas en mis proyectos. Estoy comprometido con mi crecimiento personal y profesional, siempre buscando aprender y mejorar en cada oportunidad que se presente. | 
| Leandro Saúl Contreras Lopez	![Imagen del compañero](https://i.postimg.cc/FF86sBWr/Screenshot-2025-07-08-at-5-48-58-PM.png)   | U20231E215            | Mucho gusto, soy Leandro Contreras, estudiante de la carrera de Ingeniería de Software en la UPC, sede San Miguel, tengo 19 años y estoy cursando el sexto ciclo académico. Me considero una persona adaptativa, perseverante y comprometida con lo que me propongo. En este proyecto tengo como objetivo buscar múltiples soluciones que beneficien a todo el grupo, por experiencia propia suelo trabajar de manera colaborativa y eficaz. Terminando la carrera de ingeniería, me gustaría estudiar una segunda carrera: Gastronomía y Gestión culinaria | 
| Ivo Marcelo Machado Bracamonte	![Imagen del compañero](https://i.imgur.com/n8LhONl.png)   | U20231C368            | Mi nombre es Ivo Machado, tengo 19 años, soy estudiante y actualmente estudio en el sexto ciclo de ingeniería de software en la UPC. Mis fuertes son la mentalidad, no me rindo con facilidad y no le tengo miedo al error, tengo empatía con los demás, me gusta resolver problemas y siempre intento mejorar en lo que hago y seguir aprendiendo. Tengo conocimientos del lenguaje de programación C++, Java y un poco de Python, HTML, CSS y JavaScript, también domino el Inglés y sé Portugués. | 
|       Rodrigo Jesus Miraval Pomalaya        |            u202311082                       | |
| Arnold Gabriel Morales Sosa   ![Image](https://github.com/user-attachments/assets/20e7f70a-36b2-46e3-8bd8-eb15f2c5c655)        | U201822516           | Estudiante de la carrera de Ingeniería de Software en la UPC, con estudios intermedios en Ensamblaje, Mantenimiento, Conectividad de equipos, desarrollo de software, programación y diseño. Innovador con deseos de aprender y apoyar en este proyecto donde pueda desarrollar mis conocimientos, apoyar a la mejora y logros de los objetivos estratégicos. Soy una persona con facilidad para trabajar en equipo, bajo presión, responsable, honesto, proactivo, creativo, ordenado, y dinámico. Tengo conocimientos en C++, Python, Javascript, agile scrum, SQL, NOSQL, vue.js, jerkins.  | 

  
## 1.2. Solution Profile

Glottia es una solución que busca conectar a personas interesadas en practicar distintos idiomas con espacios públicos que ofrezcan sus locales como puntos de reunión. Nuestra plataforma busca facilitar encuentros conversacionales presenciales y virtuales, resolviendo la falta de espacios seguros y accesibles para la práctica oral.

De esta manera, Glottia impulsa la confianza, la fluidez y la conexión cultural entre los usuarios, al mismo tiempo que brinda a los establecimientos aliados una oportunidad de atraer nuevos clientes y posicionarse como centros de intercambio cultural.

### 1.2.1. Antecedentes y problemática

Con el propósito de obtener una comprensión más profunda de las necesidades de nuestros usuarios, hemos investigado sus antecedentes históricos y los desafíos que enfrentan mediante la metodología de las `5W'S y 2H'S`. Este enfoque nos asegura que la información recopilada sea pertinente y nos permita desarrollar soluciones precisas y eficaces que satisfagan sus necesidades.

#### What: 
La problemática que como equipo buscamos solucionar,  es que cada vez más los jóvenes adultos se interesan en aprender nuevos idiomas y establecer conexiones con personas de diferente cultura, ya sea para mejorar sus oportunidades laborales o ampliar sus horizontes personales. Sin embargo, encontrar espacios adecuados para practicar idiomas de manera regular social puede ser un reto. Las academias tradicionales suelen ser costosas o tener horarios poco flexibles, mientras que muchas plataformas en línea carecen de la interacción. Además tras la pandemia muchos jóvenes se han visto afectadas sus habilidades sociales o anhelan espacios ideales donde puedan relacionarse con personas que compartan su interés por contextos urbanos con acceso limitado a comunidades multiculturales. Esto es de suma importancia porque nos abre una oportunidad para mejorar nuestro aprendizaje de idiomas a través de entornos sociales que sean accesibles, inclusivos, seguros y dinámicos. Para eso debe ser en un lugar donde la gente pueda sentir satisfacción y comodidad para poder interactuar en este entorno. Según Cáceres (2022) implica que para poder aprender otros idiomas es adecuado poder encontrar un entorno donde la gente se encuentre cómoda y esté motivada a aprender,  de acuerdo con su investigación a la gente a la que ha estudiado un total de 374 personas el 28,10% suelen participar de forma voluntaria. Otro tema que se tiene en cuenta es la interacción con las personas ya que el 20,9% son quienes pueden interactuar mejor con las personas y aprender inglés en conjunto y aprender más acerca de las demás personas internacionalmente hablando dando a entender si se pone en práctica su conclusión se podrá enfrentar a esta situación. 

#### When:
El problema ocurre cuando una persona desea practicar un nuevo idioma de forma real y no encuentra un entorno adecuado para hacerlo. Según investigaciones pueden ser los siguientes casos: cuando se buscan alternativas a los institutos y academias tradicionales, requiere mejorar su fluidez oral así mismo  cuando experimentan frustración por la falta de un ambiente convencional para el aprendizaje. Segun Soncco (2022), afirma que los estudiantes encuentran una mejor forma de poder aprender su inglés mediante las tecnologías móviles así como también empleando muchas estrategias de evaluación para medir el nivel de 325 estudiantes de los cuales un 51,8% tiene un nivel medio asimismo se demostró que un 53,4% demostró tener mejoras en el inglés mediante estos aplicativos móviles en base a esta investigación demostraría que se puede aplicar landing page en especializada para potenciar las habilidades con respecto a otros idiomas. 

#### Where:
En cualquier lugar donde no existan espacios accesibles que se ajusten a las necesidades de los usuarios por lo que la landing page que estamos desarrollado permitirá que los usuarios no tengan problemas en elegir sus lugares de estudio con sus respectivos compañeros de aprendizaje y digamos la experiencia sea agradable y le brinde al estudiante las herramientas para poder mejorar. Estos entonces pueden ser desde cafeterías, departamentos, lugares públicos, salones etc. Además contamos con un entorno virtual en el que el usuario puede organizar su clase a distancia al horario que le sea más flexible al estudiante. Según Soto (2018) señaló que el involucrarse con personas de otros países, ciudades y culturas es sumamente fundamental para el desarrollo del inglés independientemente del nivel que la persona tenga. Asimismo Idiomas PUCP (2028) señaló que la virtualidad puede ayudar a los estudiar inglés a los demás garantizando resultados positivos, pero qué hay del lugar nosotros planteamos que el usuario siempre esté satisfecho por el lugar y tiempo que invierte por ello también enfocamos en que el alumno pueda administrar de manera efectiva su horario.    

#### Who:
Nuestros usuarios son por lo general jóvenes adultos entre 18 y 35 años con interés en mejorar su fluidez oral al hablar en otros idiomas, asimismo también buscamos ayudar a los jóvenes universitarios o recién egresados que desean mejorar su empleabilidad, así como a profesionales que necesitan practicar otros idiomas en su entorno laboral, por último tenemos a las personas de otras culturas que buscan ampliar sus horizontes conociendo y enseñando sus costumbres e idiomas. 

#### Why:
Las causas de este problema que como startup buscamos solucionar son  : Las academias de idioma suelen ser costosas, Las plataformas online carecen de lucidez y espontaneidad y los espacios informales para prácticas suelen ser escasos o desorganizados. Por ello nuestro proyecto nace como una respuesta directa a esa necesidad insatisfecha, promoviendo un entorno dinámico, inclusivo y eficaz para practicar idiomas mediante la conversación constante. 

#### How:
A través de una plataforma digital donde los usuarios pueden registrarse, seleccionar el idioma que desean practicar, emparejarse con otras personas según nivel y disponibilidad, y asistir a encuentros organizados o espontáneos, presenciales o virtuales. 
Registro de creación de perfil con intereses, nivel de idioma y disponibilidad. 
Selección del idioma a practicar y emparejamiento inteligente.
Reserva de encuentros temáticos o asistencia a sesiones abiertas.
Participación en retos lingüísticos, eventos  y dinámicas gamificadas.
Acumulación de puntos, logros y beneficios por participación.
Organización de eventos con embajadores locales y moderadores certificados. 

#### How Much:
En una investigación por parte de Segovia (2021), en el Perú se selecciponó una muestra de 37 estudiantes de un instituto de educación superior.  Esto con el fin de hacer una evaluación para medir las causas que pueden generar el problema con el aprendizaje de una nueva lengua por esta razón según la investigación que de los estudiantes seleccionados por lo que se puede tomar en cuenta el 75,7% quienes conforman a los hombres y el 24,3% quienes conforman a las mujeres cuyas edades son entre los 18 y 25 años. Dieron como resultado que el temor a la evaluación negativa de compañeros y la ansiedad son los principales factores así mismo según el gráfico estadístico para medir el problema principal de la ansiedad nos revela que el 89,20% de la muestra, revela una aprehensión comunicativa grande y un 59,5% a la evaluación negativa. asimismo otra investigación realizada por Muñoz (2020) quien tomó un total de 210 estudiantes demostró que al tener buen hábito de estudio y gente que complementa dichas habilidades, como hábitos de organización, estudio y controles para exámenes etc. Estos estudios demuestran que sí podemos tomar en cuenta el problema y aplicar soluciones podremos lograr un producto que satisfaga correctamente la necesidad del usuario. Se revela que un 43, 4% no tiene muchos hábitos de estudio y solo el 27,2% cuenta con buenas maneras de poner en práctica otros idiomas, siendo únicamente el 15% los más destacables dentro de los 210 estudiantes destacando que en esta manera hay aun más casos de personas con problemas de aprendizaje de idiomas que no logran encontrar la metodología perfecta para poder desarrollarse social y académicamente. 


### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Nuestra plataforma tiene como propósito brindar oportunidades de práctica conversacional en distintos idiomas, eliminando barreras económicas y geográficas. Buscamos que cualquier persona, sin importar su ubicación o condición económica, pueda mejorar su fluidez y confianza al comunicarse en otra lengua.

Hemos observado que los jóvenes adultos enfrentan cada vez mayores obstáculos para acceder a prácticas lingüísticas constantes, principalmente debido al alto costo de las academias tradicionales o la ausencia de espacios organizados cerca de sus zonas de residencia o estudio.

Ante este desafío, surge la pregunta: ¿Cómo podemos proporcionar opciones accesibles (económicamente y geográficamente) para practicar idiomas sin depender de instituciones costosas o ubicaciones limitadas?

#### 1.2.2.2. Lean UX Assumptions

#### Business Assumptions:
Creemos que las personas que ya han aprendido un idioma (como inglés) necesitan practicarlo de forma conversacional para dominarlo completamente.
Nuestra idea servirá para que las personas que necesiten practicar su idioma verbalmente, lo hagan con mucha más facilidad y comodidad.
Creemos que un formato de reunión con temas específicos y actividades lúdicas (juegos, dinámicas) es más atractivo que una conversación libre sin estructura.
La segmentación por intereses, edad, cercanía geográfica y nivel de idioma (datos proporcionados por el cliente), mejorará la calidad de la experiencia y la satisfacción del usuario.
Si los usuarios que no pueden asistir presencialmente encontrarán igual valor en sesiones virtuales bien estructuradas y moderadas.

#### Business Outcome:
Seremos una plataforma confiable para practicar idiomas.
Conseguiremos una mayor cantidad de usuarios utilizando nuestra plataforma progresivamente.
Estableceremos alianzas estratégicas con locales comerciales (cafeterías, coworkings, restaurantes), generando acuerdos de patrocinio o comisiones por consumo.
Lograremos que nuestros clientes pasen una agradable experiencia usando nuestra plataforma, garantizando su seguridad y nivel de satisfacción.
Podremos ganar popularidad y expandirnos a mayor nivel con el tiempo.

#### Users Assumptions:
**¿Quiénes son nuestros usuarios?** <br>
Nuestros usuarios son personas que buscan practicar su idioma de forma conversacional, especialmente en un entorno social. Suelen ser jóvenes y adultos interesados en mejorar su fluidez, hacer networking o conocer nuevas personas con intereses similares.

**¿Dónde encaja nuestro producto?** <br>
Nuestro producto encaja en su vida como una actividad social y de desarrollo personal, ocupando un espacio similar al de ir a clases de conversación, asistir a meetups o realizar actividades recreativas con propósito.

**¿Qué problema tiene nuestro producto a resolver?** <br>
Nuestro producto busca resolver el problema de que muchas personas no tienen con quién practicar un idioma que ya han aprendido, lo que les impide ganar fluidez, confianza y mantener lo aprendido.

**¿Cuándo y cómo es usado nuestro producto?** <br>
Nuestro producto se usa principalmente en horarios libres de los clientes, cuando los usuarios buscan actividades recreativas o de crecimiento personal. Se accede a través de una app, donde el usuario se registra, completa su perfil y se une a reuniones temáticas, ya sean presenciales en lugares públicos o virtuales por videollamada.

**¿Qué características son importantes?** <br>
Emparejamiento inteligente por intereses, edad, ubicación y nivel de idioma, reuniones temáticas estructuradas con dinámicas para guiar la conversación, opciones presenciales y virtuales.

**¿Cómo debería verse y comportarse nuestro producto?** <br>
Nuestro producto debería verse moderno, amigable y social, con una interfaz intuitiva, clara y cálida que invite a participar. Colores suaves, ilustraciones o íconos relacionados al idioma y la cultura pueden reforzar la experiencia.

#### User Outcome:
Mejora en la fluidez y confianza al hablar el idioma, gracias a la práctica regular con personas reales en contextos reales.
Conexión social significativa, al conocer personas con intereses similares y compartir experiencias en un ambiente relajado.
Aumento de la motivación para seguir practicando.
Flexibilidad para practicar de forma presencial o virtual.
Acceso a experiencias prácticas y entretenidas.

#### 1.2.2.3. Lean UX Hypothesis Statements
**Creemos que** al emparejar a los usuarios por nivel de idioma, intereses y cercanía, mejoraremos la calidad de las interacciones en las reuniones. <br>
**Sabremos que** conseguimos excelentes resultados. <br> 
**Cuando** el 60% de los usuarios participen en más de una reunión dentro del primer mes. <br>

**Creemos que** ofreciendo reuniones temáticas con dinámicas y juegos relacionados al idioma, los usuarios estarán más comprometidos y motivados. <br>
**Sabremos que** conseguimos excelentes resultados. <br>
**Cuando** el 60% de los usuarios participen en más de una reunión dentro del primer mes. <br>

**Creemos que** brindando la opción de participar tanto de forma presencial como virtual, ampliaremos la accesibilidad y comodidad para los usuarios. <br>
**Sabremos que** conseguimos excelentes resultados. <br>

**Creemos que** al emparejar a los usuarios por nivel de idioma, intereses y cercanía, mejoraremos la calidad de las interacciones en las reuniones.
**Sabremos que** conseguimos excelentes resultados.
**Cuando** el 60% de los usuarios participen en más de una reunión dentro del primer mes.

**Creemos que** ofreciendo reuniones temáticas con dinámicas y juegos relacionados al idioma, los usuarios estarán más comprometidos y motivados.
**Sabremos que** conseguimos excelentes resultados.
**Cuando** el 60% de los usuarios participen en más de una reunión dentro del primer mes.

**Creemos que** brindando la opción de participar tanto de forma presencial como virtual, ampliaremos la accesibilidad y comodidad para los usuarios.
**Sabremos que** conseguimos excelentes resultados.
**Cuando** al menos el 40% de los usuarios utilicen ambas modalidades durante su primer trimestre en la app.

#### 1.2.2.4. Lean UX Canvas

| 1. Problema de negocio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                    5. Idea de soluciones                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      2. Bussiness Outcome |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Nuestra plataforma tiene como propósito brindar oportunidades de práctica conversacional en distintos idiomas, eliminando barreras económicas y geográficas. Buscamos que cualquier persona, sin importar su ubicación o condición económica, pueda mejorar su fluidez y confianza al comunicarse en otra lengua.<br><br>Hemos observado que los jóvenes adultos enfrentan cada vez mayores obstáculos para acceder a prácticas lingüísticas constantes, principalmente debido al alto costo de las academias tradicionales o la ausencia de espacios organizados cerca de sus zonas de residencia o estudio.<br><br>Ante este desafío, surge la pregunta: ¿Cómo podemos proporcionar opciones accesibles (económicamente y geográficamente) para practicar idiomas sin depender de instituciones costosas o ubicaciones limitadas?                                                      | Interfaz fácil de usar, intuitiva y que les permita a los usuarios sentirse cómodos con la app.<br><br>Para facilitar que los usuarios se sientan cómodos al reunirse con desconocidos, podemos incluir una fase de introducción guiada, donde los usuarios se presenten brevemente y se alineen con los objetivos comunes antes de comenzar la práctica.<br><br>Una solución podría ser recompensar la consistencia a través de un sistema de puntos o logros.<br><br>Para evitar que las reuniones se vuelvan monótonas o difíciles de seguir, podemos integrar temas variados y dinámicas que cambian regularmente.<br><br>Implementar retos o metas grupales podría ser una excelente forma de involucrar a los usuarios en una experiencia compartida. |                                                                                                                       Lograr que los usuarios regresen a participar en reuniones regularmente indica que el producto cumple con sus expectativas y se vuelve parte de su rutina de práctica, lo que aumenta el valor del ciclo de vida del cliente.<br><br>Al trabajar con cafeterías, restaurantes o coworkings para realizar reuniones presenciales, se abren nuevas fuentes de ingresos y visibilidad, además de enriquecer la experiencia del usuario.<br><br>Disminuir la cantidad de usuarios que abandonan la plataforma refleja una experiencia sólida, útil y disfrutable, lo cual permite construir una comunidad estable y confiable.<br><br>Cuando los usuarios recomiendan activamente la app a amigos o colegas, se demuestra que hay un alto nivel de confianza en el producto y se habilita un canal de crecimiento natural y sostenible. |
| 3. Usuarios y clientes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 4. Beneficios del Usuario |
| Personas que ya tienen conocimientos básicos o intermedios de un idioma y buscan mejorar su fluidez a través de la práctica, no del estudio. Son jóvenes o adultos con intereses diversos, que valoran la interacción social, la flexibilidad y una experiencia de aprendizaje práctica y entretenida.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Mejora real de fluidez oral: Al participar regularmente en conversaciones guiadas y naturales, los usuarios mejoran notablemente su fluidez y pronunciación en el idioma, ganando seguridad al expresarse.<br><br>Ambiente relajado y sin presión: Las sesiones están diseñadas para ser sociales y entretenidas, lo que elimina la ansiedad que muchos sienten al practicar en entornos académicos. <br><br>Conexiones con personas: Los usuarios no solo practican un idioma, sino que también conocen personas con intereses, edades y estilos de vida similares, lo cual puede derivar en amistades, oportunidades profesionales o simplemente una red de apoyo para seguir aprendiendo.<br><br>Flexibilidad en la práctica: La posibilidad de elegir entre encuentros virtuales o presenciales, y horarios ajustados al ritmo de vida del usuario, permite que la práctica se adapte a sus tiempos sin interferir con sus responsabilidades diarias. |
| 6. Hipotesis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 7. ¿Qué es lo más importante que necesitamos aprender primero?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          8. ¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver las dudas y para hacer lo siguiente más importante? |
| Creemos que al emparejar a los usuarios por nivel de idioma, intereses y cercanía, mejoraremos la calidad de las interacciones en las reuniones. Sabremos que conseguimos excelentes resultados cuando el 60% de los usuarios participen en más de una reunión dentro del primer mes.<br>Creemos que ofreciendo reuniones temáticas con dinámicas y juegos relacionados al idioma, los usuarios estarán más comprometidos y motivados. Sabremos que conseguimos excelentes resultados cuando el 60% de los usuarios participen en más de una reunión dentro del primer mes.<br>Creemos que brindando la opción de participar tanto de forma presencial como virtual, ampliaremos la accesibilidad y comodidad para los usuarios. Sabremos que conseguimos excelentes resultados cuando al menos el 40% de los usuarios utilicen ambas modalidades durante su primer trimestre en la app. | ¿Los usuarios están dispuestos a reunirse con desconocidos para practicar un idioma?<br><br>¿Qué motiva más a los usuarios: mejorar su fluidez, conocer gente o ambos?<br><br>¿Qué barreras existen para que los usuarios participen en su primera reunión?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                Hacer un prototipo de interfaz minimalista con un grupo reducido de usuarios para recopilar información sobre las preguntas o problemas más frecuentes.<br><br>Reducir la dificultad en el proceso de registro ofreciendo la opción de unirse a una reunión con un solo clic, para evitar pasos innecesarios y largos.<br><br>Ofrecer una funcionalidad sencilla para que los usuarios puedan reprogramar sus reuniones si no pueden asistir, sin perder demasiado tiempo. |

## 1.3. Segmentos objetivo
### Segmento objetivo #1: Usuarios aprendices de idiomas

#### Aspectos demográficos:
- Sexo: Masculino, femenino y no binario.
- Edad: Entre 16 y 40 años (desde estudiantes de secundaria superior hasta jóvenes/adultos profesionales).
- Nivel socioeconómico: Medio a medio-alto.

#### Aspectos geográficos:
- Residen en áreas urbanas o metropolitanas con buena conectividad y vida cultural activa.
- Se concentran en ciudades con alta población estudiantil, diversidad cultural o presencia de comunidades extranjeras.
- Frecuentan espacios como universidades, bibliotecas, coworkings, cafeterías, bares, centros culturales y parques urbanos.

#### Aspectos psicográficos:
- Tienen motivación tanto académica/profesional (certificaciones, prácticas, empleabilidad) como social/personal (viajar, conocer culturas, socializar).
- Buscan fluidez, vocabulario conversacional y confianza al hablar en un entorno real.
- Valoran experiencias auténticas, accesibles y presenciales fuera de un aula tradicional.
- Son curiosos, abiertos, sociables y dispuestos a salir de su zona de confort.


## Segmento objetivo #2: Administradores que ofrecen su establecimiento como punto de reunión

#### Aspectos demográficos:
- Perfil: Administradores, dueños o encargados de cafeterías, bares, restaurantes, coworkings y centros culturales.
- Tipo de negocio: Establecimientos con espacios adecuados para grupos pequeños o medianos.
- Ubicación: Zonas céntricas, estudiantiles o con alto tránsito de jóvenes/adultos interesados en socializar y aprender idiomas.

#### Aspectos geográficos:
- Se encuentran en áreas urbanas y metropolitanas con vida cultural activa.
- Están ubicados en distritos o barrios con alta concentración de estudiantes, profesionales jóvenes y comunidades extranjeras.
- Sus locales suelen estar cerca de universidades, residencias estudiantiles, coworkings o zonas de ocio.

#### Aspectos psicográficos:
- Buscan atraer nuevos clientes mediante experiencias innovadoras.
- Están interesados en diferenciar su local con propuestas culturales y sociales.
- Valoran el posicionamiento digital y la visibilidad que les brinda la app.
- Quieren generar mayor consumo en su establecimiento a través de las reuniones organizadas.
- Desean fidelizar clientes al vincular su espacio con un ambiente inclusivo, cultural e internacional.


---

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Development & Software Solution Design
## 2.1. Competidores
Glottia se ubica en un punto intermedio entre las apps para aprender idiomas y las plataformas de eventos sociales. Por eso no solo compite con apps similares, sino también con redes para hacer networking y métodos más tradicionales.
### 2.1.1. Análisis competitivo
## Competidores directos: Son aquellas plataformas que, al igual que Glottia, conectan a personas para practicar idiomas en encuentros presenciales.
### Meetup
Es una de las plataformas más grandes para crear grupos y eventos con intereses específicos. Hay muchos grupos de “language exchange” que se reúnen en bares, cafés o parques. No es exclusiva de idiomas, pero su tamaño, popularidad y facilidad para organizar eventos la hacen el rival más fuerte.
### Tandem y HelloTalk
Aunque se enfocan sobre todo en el intercambio virtual (chat o videollamadas), ya integran geolocalización y “eventos” para encontrar gente cercana. Son una amenaza porque tienen una base de usuarios muy grande y reconocida en el aprendizaje de idiomas.
## Competidores indirectos: Son servicios que no ofrecen exactamente lo mismo, pero cubren la misma necesidad que es practicar idiomas en un entorno social o encontrar eventos para ello.
### Escuelas y academias de idiomas
Aunque su modelo es formal y educativo, suelen organizar cafés de idiomas, clubes de conversación u otros eventos sociales para estudiantes. Estos espacios compiten con las reuniones de Glottia porque ofrecen práctica guiada y en un ambiente conocido.
### Apps de citas o redes sociales con geolocalización
Plataformas como Bumble o grupos de Facebook específicos para aprender idiomas se usan mucho para conocer gente con intereses parecidos. Los usuarios pueden crear eventos informales o buscar amigos para practicar, reduciendo la necesidad de una app especializada como Glottia.
### 2.1.2. Estrategias y tácticas frente a competidores
Para sobresalir, Glottia necesita aprovechar su propuesta de valor: la conexión directa con locales físicos y la experiencia del evento.
## Frente a competidores directos:
### Alianzas con locales asociados
A diferencia de Meetup, que es genérica, Glottia puede firmar acuerdos con bares, cafés u otros espacios. Así ofrece lugares seguros, organizados y con beneficios (por ejemplo, descuentos). Para los locales, la app significa visibilidad y más clientes, algo que Meetup no garantiza.
### Cuidar la experiencia del evento
Mientras otras apps solo conectan, Glottia puede garantizar la experiencia: temas preestablecidos, voluntarios que faciliten la conversación, para que cada encuentro sea más divertido y productivo que una reunión informal.
## Frente a competidores indirectos:
### Ser complemento, no sustituto
Glottia puede mostrarse como el complemento perfecto a la educación formal. Puede asociarse con escuelas y universidades para que recomienden la app como espacio de práctica fuera del aula.
### Construir comunidad y marca
A diferencia de un grupo suelto en Facebook, Glottia puede crear una comunidad sólida y confiable, cuidando la seguridad, la calidad de los encuentros y la cultura alrededor de la app. Eso genera confianza y preferencia.

## 2.2. Entrevistas
De acuerdo con Easwaramoorthy y Zarinpoush (2006), las entrevistas son un método de investigación, en el que se lleva a cabo “una conversación para recolectar información”. En esta, se realizan una serie de preguntas sobre el agente que queremos llegar a conocer mejor y profundizar en su sentir y punto de vista. Para HampCoders, la información recogida a través de las entrevistas es esencial para identificar cómo ElectroLink aportaría a solucionar el problema relacionado a la instalación y mantenimiento preventivo sobre el consumo de energía, en qué medida y en qué aspectos específicos. Por ello, realizamos un total de 3 entrevistas por segmento. Todas las entrevistas se realizaron a larga distancia (Google Meet, Zoom y Discord), y de manera presencial, en un espacio cómodo y silencioso y dentro del ámbito informal. 

### 2.2.1. Diseño de entrevistas

## Segmento objetivo #1: Usuarios aprendices de idiomas

### Preguntas principales:
- ¿Qué métodos usas actualmente para practicar un idioma (apps, clases, grupos, amigos)?
- ¿Qué limitaciones encuentras al practicar un idioma en tu día a día?
- ¿Qué tan cómodo te resulta hablar en otro idioma en público o con desconocidos?
- ¿En qué tipo de entornos prefieres practicar un idioma (formal, informal, académico, social)?
- ¿Qué valor tendría para ti contar con un espacio físico donde practicar idiomas con otras personas?
- ¿Qué te motivaría más: mejorar tu fluidez para fines académicos/profesionales o para socializar/viajar?
- ¿Con qué frecuencia estarías dispuesto a asistir a reuniones presenciales de práctica de idiomas?
- ¿Qué tipo de locales te parecerían más adecuados para reunirte (cafeterías, bares, coworkings, parques, etc.)?
- ¿Qué esperas de una aplicación que organice encuentros presenciales para practicar idiomas?
- ¿Qué factores te harían confiar en una app de este tipo (seguridad, calidad de participantes, facilidad de uso, precio)?

### Preguntas complementarias:

- ¿Qué experiencias negativas has tenido al intentar practicar idiomas antes?
- ¿Te motiva más practicar con nativos o con personas en tu mismo nivel?
- ¿Qué rol sueles tomar en una conversación en otro idioma: hablar mucho, escuchar más, participar poco?

## Segmento objetivo #2: Administradores que ofrecen su establecimiento como punto de reunión

### Preguntas principales:

- ¿Cómo atraes actualmente nuevos clientes a tu establecimiento?
- ¿Qué opinas de ofrecer tu local como punto de reunión para actividades sociales o culturales?
- ¿Qué beneficios crees que podría tener para tu negocio recibir grupos que se reúnan a practicar idiomas?
- ¿Qué preocupaciones tendrías al permitir que tu establecimiento sea usado para reuniones de este tipo?
- ¿Qué tipo de consumo esperarías que hagan los asistentes durante estas reuniones?
- ¿Qué días y horarios consideras más convenientes para albergar encuentros de práctica de idiomas?
- ¿Qué valor tendría para ti que tu local aparezca en una app como espacio recomendado para estas actividades?
- ¿Qué condiciones pondrías para aceptar que tu local sea un punto de reunión?
- ¿Qué otros eventos o actividades culturales sueles organizar en tu establecimiento?
- ¿Qué expectativas tendrías de la plataforma respecto a la promoción de tu local?

### Preguntas complementarias:

- ¿Qué tipo de clientes quieres atraer más a tu local (jóvenes, profesionales, extranjeros)?
- ¿Estarías dispuesto a ofrecer descuentos o promociones a los grupos que asistan?
- ¿Qué te haría confiar en una asociación con una app de este estilo?

### 2.2.2. Registro de entrevistas

En esta sección, el equipo realiza el registro de las entrevistas realizadas
### Segmento #1: Usuarios aprendices de idiomas

**Entrevista: Pablo Pedro Medina**  
- **Sexo:** Masculino  
- **Edad:** 17
- **Link:** [Ver entrevista](https://www.youtube.com/watch?v=up8_ieASldk&lc=Ugze5itcZxsrASv5_P54AaABAg)  
- **Inicia en:** 0:05  
- **Duración:** 7:15
  
<img src="https://i.postimg.cc/9FVrzZJg/4234234.png"/>


### Resumen de entrevista

**Datos objetivos y perfil general**

Pablo Pedro Medina, 17 años, estudiante de la carrera de Comunicación en la Universidad César Vallejo. Es sociable, le gusta el fútbol y compartir tiempo con amigos en actividades recreativas como pichangas, cine y salidas al parque. Declara un nivel C1 en ruso, aprendido en gran medida por convivencia con personas hablantes nativas, aunque no por completo formal. También muestra interés por interactuar en inglés.

**Características subjetivas – Personalidad y comportamiento**

Pablo se muestra extrovertido, curioso y motivado por experiencias sociales. Considera que practicar idiomas es esencial para evitar situaciones incómodas o burlas, lo cual relaciona directamente con su confianza personal. Aunque le gusta relacionarse, indica que salir de su zona de confort para practicar con desconocidos le resulta un reto (5/10 en disposición), en parte por las limitaciones de su entorno. Sin embargo, la motivación de aprender y mejorar lo impulsa a aceptar desafíos.

**Relación con la propuesta de Glottia**

Encuentra valor en espacios organizados para practicar idiomas, tanto virtuales como presenciales, siempre que se brinden condiciones de seguridad, confianza y paciencia. Destaca que le gustaría que los encuentros sean en lugares públicos y accesibles, con un ambiente cómodo y con posibilidades de socializar. Reconoce que no ha participado antes en intercambios de idiomas, lo que evidencia una necesidad no cubierta que Glottia podría resolver.

**Canales de búsqueda y decisión**

Actualmente practica mediante internet, redes sociales y academias. Utiliza la tecnología de forma intensiva para conectar con personas (relaciones, amistades, incluso entretenimiento), lo que muestra que un canal digital como Glottia sería percibido como natural y atractivo para él.

**Dispositivos y tecnología utilizada**

Declara sentirse totalmente cómodo (10/10) con el uso de herramientas digitales para conocer nuevas personas. Considera que los avances tecnológicos han sido clave para su socialización y aprendizaje.

**Criterios de participación y expectativas**

- Ambientes públicos con sensación de seguridad.

- Lugares cómodos, con aire acondicionado y posibilidad de consumir bebidas (incluso alcohólicas).

- Paciencia y comprensión por parte de los interlocutores.

- Menor ruido ambiental para favorecer la escucha y la práctica.

- Actitud frente a plataformas de intermediación

Pablo estaría dispuesto a participar en Glottia tanto en encuentros virtuales como presenciales. Su expectativa es que la plataforma facilite un entorno seguro, accesible y diverso, donde pueda conocer nuevas personas, practicar idiomas y vivir experiencias culturales enriquecedoras.

---
### Segmento #2: Administradores que ofrecen su establecimiento como punto de reunión

**Entrevista: Ariana Calderón**  
- **Sexo:** Femenino  
- **Edad:** 24  
- **Link:** [Ver entrevista](https://www.youtube.com/watch?v=mSrdbDVvqAQ)  
- **Inicia en:** 0:01  
- **Duración:** 4:46
  
<img src="https://i.postimg.cc/MTQ8m3K0/sdadas.png"/>


### Resumen de entrevista

**Datos objetivos y perfil general** 

Ariana Calderón es administradora de un café ubicado en una zona urbana. Su rol principal consiste en la gestión operativa y administrativa del establecimiento, así como en la atracción de nuevos clientes mediante redes sociales, recomendaciones y colaboraciones locales. Organiza también actividades culturales y promociones para mantener la afluencia del público.

**Características subjetivas – Personalidad y comportamiento** 

Ariana se muestra receptiva e interesada en iniciativas que fortalezcan la comunidad y generen experiencias enriquecedoras para sus clientes. Su visión es estratégica, pues reconoce el potencial de abrir su espacio a actividades culturales y sociales como una forma de atraer público diverso y fidelizar clientes. Al mismo tiempo, evidencia una personalidad práctica y previsora, manifestando preocupaciones claras sobre aspectos de organización, consumo mínimo y control del ruido.

**Relación con la propuesta de Glottia** 

La entrevistada ve de forma positiva que su local sea un punto de encuentro para prácticas de idiomas, ya que esto incrementaría la afluencia en horarios menos concurridos y aportaría un público nuevo, como jóvenes, profesionales y extranjeros. Sin embargo, plantea condiciones: que los grupos reserven previamente, que cada asistente consuma al menos una bebida (preferiblemente con un snack), que el tiempo de permanencia sea razonable y que el número de participantes se ajuste a la capacidad del café.

**Canales de búsqueda y decisión** 

Ariana utiliza principalmente redes sociales y colaboraciones locales para dar visibilidad a su negocio. Considera que aparecer en una aplicación que promueva su establecimiento como espacio recomendado tendría un valor alto, ya que le daría exposición gratuita o de bajo costo y la conectaría con un público que todavía no la conoce.

**Dispositivos y tecnología utilizada** 

Aunque no se profundizó en los dispositivos que usa, se deduce que depende de herramientas digitales y redes sociales para la promoción de su local. Está abierta a integrarse a nuevas plataformas que difundan de manera clara horarios, condiciones de consumo y ubicación de su establecimiento.

**Criterios de colaboración y expectativas** 

Ariana espera que los asistentes tengan un consumo mínimo y respeten las normas del local. Valora que la plataforma garantice transparencia en las condiciones, canales de comunicación claros y promociones constantes. También estaría dispuesta a ofrecer descuentos o combos para grupos, siempre que se cumpla el consumo mínimo.

**Actitud frente a plataformas de intermediación** 

La entrevistada expresó interés en asociarse con una aplicación como Glottia, siempre que esta ofrezca confianza, organización y proyección de su local como un espacio cultural y acogedor. Destaca que el éxito de la colaboración dependerá de la claridad en las reglas, la comunicación fluida y la capacidad de atraer a su público objetivo: jóvenes, profesionales y extranjeros interesados en experiencias multiculturales.

---

### Segmento #2: Administradores que ofrecen su establecimiento como punto de reunión

**Entrevista: Leonardo Donarie**  
- **Sexo:** Masculino  
- **Edad:** 28  
- **Link:** [Ver entrevista](https://www.youtube.com/watch?v=DZAXVHlCj70)  
- **Inicia en:** 0:05  
- **Duración:** 9:20
  
<img src="https://i.postimg.cc/gJ8222RP/4534rfr.png"/>


### Resumen de entrevista

**Datos objetivos y perfil general**

Leonardo Don es dueño y administrador de un restaurante–café que ofrece platillos sencillos, postres, snacks y café en un ambiente acogedor con espacio interior adecuado para reuniones pequeñas o medianas. Su negocio se encuentra en un área urbana y actualmente atrae clientes principalmente mediante redes sociales y el boca a boca, lo que le ha permitido crecer progresivamente.

**Características subjetivas – Personalidad y comportamiento**

Leonardo se muestra abierto a innovar y valora iniciativas que le generen un valor añadido a su negocio. Considera positivo que su local se use como punto de encuentro para prácticas de idiomas, ya que percibe que esto puede fidelizar a clientes y darle mayor visibilidad. Al mismo tiempo, es precavido respecto a aspectos prácticos como el consumo mínimo, el orden y el nivel de ruido dentro de su establecimiento.

**Relación con la propuesta de Glottia**

El entrevistado identifica beneficios directos en participar con Glottia: atraer un público más diverso (jóvenes, estudiantes y extranjeros), aumentar la afluencia en horarios de menor demanda y reforzar la difusión de su local. Entre sus preocupaciones, menciona la posibilidad de que algunos asistentes usen el espacio sin consumir, el exceso de ruido y la falta de organización del grupo. Establece como condiciones para aceptar los encuentros la obligatoriedad de consumo, respeto de horarios específicos y un ambiente ordenado.

**Canales de búsqueda y decisión**

Actualmente, Leonardo utiliza redes sociales y recomendaciones de clientes para atraer público. Reconoce que no es muy activo en plataformas digitales, por lo que considera de gran valor que su local aparezca en una aplicación como Glottia, al darle mayor visibilidad y exposición virtual que complementa sus esfuerzos actuales de promoción.

**Dispositivos y tecnología utilizada**

No se detallaron dispositivos específicos, pero se desprende que utiliza redes sociales de forma básica para promocionar el restaurante–café. Ve en Glottia una oportunidad de profesionalizar y reforzar su presencia digital con bajo esfuerzo de su parte.

**Criterios de colaboración y expectativas**

Leonardo espera que cada participante consuma al menos una bebida o un snack, que los encuentros se realicen en horarios menos concurridos (tardes o noches) y que se mantenga el orden dentro del local. Está dispuesto a considerar el espacio para estos grupos si se cumplen esas condiciones básicas. Valora también que la plataforma difunda su local de manera clara y atractiva para captar nuevos clientes.

**Actitud frente a plataformas de intermediación**

El entrevistado ve con buenos ojos colaborar con Glottia, ya que le otorgaría mayor visibilidad y le permitiría atraer un público interesado en idiomas y experiencias culturales. Destaca la importancia de la comunicación transparente y constante con la plataforma, así como de establecer reglas claras que aseguren una convivencia armónica entre los asistentes y el resto de clientes del local.

---

### Segmento #2: Administradores que ofrecen su establecimiento como punto de reunión

**Entrevista: Alessandro Bravo**  
- **Sexo:** Masculino  
- **Edad:** 29  
- **Link:** [Ver entrevista](https://youtu.be/r9YsPmAdfwI)  
- **Inicia en:** 0:05  
- **Duración:** 6:55
  
<img src="https://i.postimg.cc/gJ8222RP/4534rfr.png"/>


### Resumen de entrevista

**Datos objetivos y perfil general**

Alessandro Bravo es dueño de una cafetería que ofrece café, postres y snacks en un ambiente cálido, con espacio interior adecuado para reuniones de grupos pequeños o medianos. Su negocio se ubica en una zona de San Martin de Porres y actualmente atrae clientes principalmente a través de redes sociales, el boca a boca y colaboraciones con pequeños emprendimientos locales, lo que le ha permitido mantener un crecimiento constante.

**Características subjetivas – Personalidad y comportamiento**

Alessandro se muestra abierto a innovar y busca que su cafetería sea también un punto de encuentro social y cultural. Considera positivo recibir grupos para prácticas de idiomas porque percibe que eso fideliza a los clientes y da mayor visibilidad al local. A la vez, es cuidadoso respecto a aspectos prácticos como mantener un consumo mínimo, evitar exceso de ruido y organizar bien los horarios para no afectar a otros clientes.

**Relación con la propuesta de Glottia**

El entrevistado identifica beneficios claros en colaborar con Glottia: atraer un público más variado, aumentar la afluencia en horarios de baja demanda y reforzar la difusión de su cafetería como espacio cultural. Entre sus preocupaciones menciona nque se generen molestias por ruido o que falte coordinación en la organización de los encuentros. Como condiciones básicas establece que debe existir un consumo por persona, respeto de horarios previamente definidos y mantener un ambiente ordenado.

**Canales de búsqueda y decisión**

Actualmente, Alessandro recurre a redes sociales y recomendaciones de clientes satisfechos para atraer nuevo público. Reconoce que sus esfuerzos digitales son limitados, por lo que valora mucho la posibilidad de que su cafetería aparezca en una aplicación como Glottia, al otorgarle visibilidad directa frente a un público específico interesado en actividades sociales y culturales.

**Dispositivos y tecnología utilizada**

No se detallaron dispositivos concretos, pero se infiere que utiliza de manera sencilla redes sociales para promocionar el negocio. Percibe en Glottia una oportunidad para reforzar y profesionalizar su presencia digital, con bajo esfuerzo adicional de su parte.

**Criterios de colaboración y expectativas**

Alessandro espera que cada asistente consuma al menos una bebida y, de ser posible, algún snack. Considera más conveniente que los encuentros se realicen en horarios menos concurridos, especialmente por las tardes de lunes a viernes entre las 4 a 7. También espera que la plataforma promocione el local y podría ayudar proporcionando ofertas exclusivas.

**Actitud frente a plataformas de intermediación**

El entrevistado muestra disposición a colaborar con Glottia, al verla como una forma de aumentar la visibilidad y atraer público interesado en idiomas y experiencias culturales. Señala la importancia de establecer reglas claras para asegurar un ambiente respetuoso y de mantener una comunicación transparente con la plataforma, lo que generaría confianza y permitiría una relación beneficiosa para ambas partes.

---

### 2.2.3. Análisis de entrevistas
En esta sección, el equipo realiza el análisis respectivo de las entrevistas, consolidándolo en un resumen de acuerdo a los segmentos entrevistados.

### Segmento 1: Usuarios aprendices de idiomas

**Total entrevistados:** 2
**Edad promedio:** 20 años
**Sexo:** Masculino
**Ocupación:** Estudiante universitario

#### Características objetivas:

- **100%** practica idiomas principalmente mediante internet y academias.

- **100%** se siente totalmente cómodo usando tecnología para conocer nuevas personas (10/10).

- **100%** está interesado en encuentros presenciales y virtuales para practicar idiomas.

- **100%** manifiesta interés en conocer nuevas personas y culturas a través de la práctica lingüística.

- **0%** ha participado previamente en intercambios de idiomas organizados.

#### Características subjetivas:

- La motivación principal es mejorar fluidez y confianza social, evitando burlas o juicios.

- Alta valoración del idioma como herramienta de integración social y cultural.

- Percibe limitaciones en el entorno (ruido, falta de espacios adecuados, lejanía).

- Muestra disposición media a salir de su zona de confort (5/10), aunque la motivación lo impulsa a hacerlo.

- Busca entornos públicos, seguros y cómodos, con ambiente social agradable.

---

### Segmento 2: Administradores de establecimientos (cafeterías, bares, coworkings)

**Total entrevistados:** 2
**Edad promedio:** 26-37 años (aprox.)
**Sexo:** Masculino y Femenino
**Ocupación:** Dueño de restaurante-café

### Características objetivas:

- **100%** gestiona su clientela mediante redes sociales y boca a boca.

- **100%** cuenta con un local físico con áreas internas adecuadas para grupos pequeños/medianos.

- **100%** considera viable recibir grupos para prácticas de idiomas en horarios de baja afluencia (tardes/noches).

- **100%** valora la visibilidad que una app puede brindar a su establecimiento.

- **100%** condiciona la participación a que los asistentes consuman algo en el local.

### Características subjetivas:

- Interés en atraer nuevo público a través de experiencias culturales y sociales.

- Percibe la propuesta como un valor agregado que diferencia su local de la competencia.

- Preocupación por posibles problemas de ocupación de espacio sin consumo y exceso de ruido.

- Considera importante mantener el orden y el respeto de normas para asegurar la convivencia en el local.

- Ve en la app una oportunidad de posicionamiento digital y fidelización de clientes.

## Síntesis de Hallazgos y Validación Cuantitativa

A partir de los gráficos obtenidos del formulario post-entrevista, se destacan las siguientes tendencias cuantitativas que validan los hallazgos cualitativos anteriores:

### 1. Usuarios aprendices – Espacios seguros

<img src="https://i.postimg.cc/g0JP7k4K/hallazgo1.png"/>

### Hallazgo para el gráfico:

La mayoría de usuarios indica que no encuentra espacios seguros ni accesibles para practicar idiomas, lo que evidencia una necesidad que Glottia puede cubrir.

### 2. Usuarios aprendices – Uso de tecnología

<img src="https://i.postimg.cc/3NQV3KjV/hallazgo2.png"/>

### Hallazgo para el gráfico:
La mayoría de entrevistados no utiliza actualmente aplicaciones digitales para practicar idiomas, lo que muestra una oportunidad clara de posicionar a Glottia como primera opción.

### 3. Administradores de locales – Valor de aparecer en app

<img src="https://i.postimg.cc/qqrb914d/hallazgo3.png"/>

### Hallazgo para el gráfico:

La mayoría de administradores valora positivamente aparecer en una app, ya que reconocen que esto les daría visibilidad y llegada a nuevos públicos.

### 4. Administradores de locales – Consumo mínimo

<img src="https://i.postimg.cc/9QkxWmCb/hallazgo4.png"/>

### Hallazgo para el gráfico:

La mayoría de administradores indica que no aceptarían reuniones sin consumo mínimo, lo que confirma la necesidad de establecer reglas claras en la plataforma.


## 2.3. Needfinding
En esta sección, el equipo presenta los elementos del needfinding

### 2.3.1. User Personas
En esta sección, el equipo presenta a los user personas de acuerdo a los segmenots objetivos

**Segmento #1**
<img src="https://i.postimg.cc/kMQV14BS/Sofia-Ram-rez-1.png"/>

**Segmento #2**
<img src="https://i.postimg.cc/bwQFd1JJ/Carlos-M-ndez-1.png"/>


### 2.3.2. User Task Matrix

En esta sección se detallan las tareas que realizan los diferentes segmentos de usuarios representados por los User Personas de Glottia, con el objetivo de cumplir sus metas relacionadas con el mantenimiento preventivo de sistemas eléctricos en hogares, oficinas o como parte de su actividad profesional.

---

### Sofia Ramirez – Usuarios aprendices de idiomas

| Actividades                                               | Frecuencia        | Importancia |
|-----------------------------------------------------------|-------------------|-------------|
| Buscar espacios de práctica de idiomas                    | Frecuentemente    | Alta        |
| Participar en encuentros presenciales o virtuales         | Frecuentemente    | Alta        |
| Agendar y coordinar sesiones de conversación con otros    | Frecuentemente    | Alta        |
| Buscar eventos temáticos relacionados con idiomas         | Ocasionalmente    | Media       |
| Participar en juegos o dinámicas de gamificación          | Ocasionalmente    | Media       |
| Reservar encuentros por idioma o nivel de fluidez         | Frecuentemente    | Alta        |
| Investigar sobre nuevas plataformas de intercambio lingüístico | Ocasionalmente | Media       |
| Pedir recomendaciones sobre buenas prácticas lingüísticas | Rara vez          | Media       |
| Evaluar su progreso en el aprendizaje del idioma          | Frecuentemente    | Alta        |


---

### Carlos Mendoza – Administradores que ofrecen su establecimiento como punto de reunión

| Actividades                                                | Frecuencia        | Importancia |
|------------------------------------------------------------|-------------------|-------------|
| Promover el establecimiento en la plataforma Glottia       | Frecuentemente    | Alta        |
| Coordinar y gestionar reservas de reuniones de idiomas     | Frecuentemente    | Alta        |
| Organizar y preparar el espacio para las reuniones        | Frecuentemente    | Alta        |
| Ofrecer descuentos o promociones para usuarios recurrentes | Ocasionalmente    | Media       |
| Evaluar el rendimiento de las reuniones y el feedback de los participantes | Ocasionalmente | Alta       |
| Actualizar el perfil del establecimiento en la plataforma  | Ocasionalmente    | Media       |
| Participar en eventos de gamificación o colaboraciones     | Rara vez          | Media       |
| Crear promociones o paquetes especiales para grupos       | Ocasionalmente    | Media       |
| Establecer alianzas con otras instituciones (universidades, centros culturales) | Rara vez | Media       |



### 2.3.3. User Journey Mapping
En esta sección, el equipo muestra el journey map por cada segmento realizado 


<img src="https://i.postimg.cc/XY0dKz84/Customer-journey.png"/>
<img src="https://i.postimg.cc/85qbrBPY/Customer-journey-1.png"/>


### 2.3.4. Empathy Mapping


En esta sección, el equipo presenta el empathy mapping para cada user persona

<img src="https://i.postimg.cc/brLbzQMW/Empathy-map.png"/>

---

<img src="https://i.postimg.cc/9QkdRYMj/Carlos-Mendez.png"/>

### 2.3.5. Ubiquitous Language

# Glosario del Dominio del Negocio - Glottia

Este glosario contiene términos clave relacionados al dominio del proyecto **Glottia**. Cada término está en inglés, seguido de su equivalente en español entre paréntesis.  
Las definiciones están redactadas en español de forma clara y sin ambigüedades, para facilitar la comunicación entre todos los miembros del equipo y stakeholders.

---

## 1. Stakeholders & Roles

**Language Learner (Aprendiz de idiomas)**  
Persona que busca mejorar fluidez mediante *Encounter* presenciales.  

**Conversation Partner (Compañero de conversación)**  
Usuario emparejado por *Language Matchmaking* dentro del *Encounter*.  

**Platform Administrator (Administrador de plataforma)**  
Valida *Venue*, asigna *Role* y gestiona *Community Guidelines*.  

---

## 2. Servicios y Experiencias

**Language Meetup (Encuentro de idiomas)**  
*Encounter* presencial en *Venue*; práctica conversacional sin clases.  

**Language Matchmaking (Emparejamiento lingüístico)**  
Algoritmo que empareja *Language Learners* según *IdiomaMeta*, *NivelCEFR* y *Disponibilidad*.  

**Cultural Exchange (Intercambio cultural)**  
Resultado del emparejamiento entre *Language Learners* de distintos orígenes.  

---

## 3. Funcionalidades de la Plataforma

**Booking (Reserva)**  
*JoinEncounter* – confirma un *Attendance* dentro del *Encounter* (máximo *capacity*).  

**Verified Space (Espacio verificado)**  
*Venue* validado; aparece en *ActiveVenues*.  

**Progress Tracking (Seguimiento de progreso)**  
*PartnerDashboard / AdminDashboard* – métricas de *PointsAwarded*, *MonthlyReport*.  

**Rating & Review (Calificación y reseña)**  
*SubmitFeedback* – deja *rating* tras *EncounterCompleted*; actualiza *ReputationUpdated*.  

**Loyalty Benefits (Beneficios de fidelización)**  
*BadgeUnlocked* – desbloquea *Badge* cuando *LoyaltyAccount* alcanza umbral.  

**Wait-List Promotion (Promoción desde lista de espera)**  
*WaitingListPromotionTriggered* – ofrece cupo libre al primer *WaitListEntry*.  

**No-Show Penalty (Penalización por no-show)**  
*NoShowPenaltyApplied* – descuenta puntos si *Attendance.status* ≠ *ATTENDED*.  

---

## 4. Seguridad y Confianza

**Safe Environment (Entorno seguro)**  
*ValidateQR + Time/Proximity* – garantiza *check-in* correcto.  

**Community Guidelines (Normas de la comunidad)**  
Incumplimiento puede generar *NoShowPenaltyApplied* o suspensión.  

**Identity Verification (Verificación de identidad)**  
Valida email único y *Role* asignado por *Platform Administrator*.  

**Trust Badge (Insignia de confianza)**  
Visible en perfil de *User* o *Venue* que cumple estándares.  

---

## 5. Otros conceptos del dominio

**Language Flow (Fluidez lingüística)**  
Mejora continua medida por *FeedbackSubmitted* y *Level* dentro del *Profile*.  

**Hybrid Practice (Práctica híbrida)**  
*Encounter* presencial + *Virtual Session* (post-MVP).  

**Digital Presence (Presencia digital)**  
Visibilidad de *User*, *Partner*, *Encounter* dentro de la app y canales asociados.  

---



## 2.4. Requirements Specification

En este apartado se formalizan los requerimientos del sistema en formato estructurado y verificable. Se presenta el catálogo de requisitos, modelos de casos de uso, restricciones técnicas y condiciones de aceptación. Esta especificación servirá como base contractual entre el equipo de desarrollo y los interesados.

### 2.4.1. User Stories

# User Stories - Plataforma de Intercambio de Idiomas

## Tabla de User Stories de Landing Page

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-01 | Visitante de la página | 3 | Landing Page |
| **Título** | **Visualización de la Propuesta de Valor** |  |  |
| **Descripción** | **Como** visitante de la página **Quiero** ver una sección principal atractiva que resuma la idea del producto **Para** entender rápidamente de qué se trata el servicio. **Escenario \#1: Presentación del propósito de Glottia** \- Dado que un visitante accede a la landing page, Cuando la carga inicial se completa, Entonces se muestra un título claro que comunica el propósito: "Practica idiomas cara a cara", un subtítulo que resume el valor principal, y una llamada a la acción para registrarse. |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-02 | Visitante interesado en practicar idiomas | 2 | Landing Page |
| **Título** | **Ver Beneficios para Aprendices** |  |  |
| **Descripción** | **Como** visitante interesado en practicar idiomas **Quiero** ver claramente los beneficios específicos para aprendices **Para** entender cómo Glottia me puede ayudar a mejorar. **Escenario \#1: Visualización de beneficios para aprendices** \- Dado que un visitante explora la landing page, Cuando se desplaza a la sección de "Para Aprendices", Entonces identifica claramente beneficios como "Gana fluidez en conversaciones reales", "Conoce gente nueva" y "Acceso accesible sin academias", cada uno con una descripción breve. |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-03 | Dueño de un local | 2 | Landing Page |
| **Título** | **Ver Beneficios para Locales** |  |  |
| **Descripción** | **Como** dueño de un local **Quiero** ver claramente los beneficios que la plataforma ofrece a mi negocio **Para** comprender cómo puede aumentar mis clientes y visibilidad. **Escenario \#1: Visualización de beneficios para locales** \- Dado que un dueño de un local visita la landing page, Cuando navega a la sección de "Para Locales", Entonces ve beneficios destacados como "Atrae nuevos clientes", "Aumenta el consumo en horas valle" y "Publicidad gratuita para tu negocio". |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-04 | Visitante | 3 | Landing Page |
| **Título** | **Explicación de Cómo Funciona** |  |  |
| **Descripción** | **Como** visitante **Quiero** ver una explicación sencilla y visual de cómo funciona la plataforma **Para** entender los pasos necesarios para participar. **Escenario \#1: Pasos para el aprendiz** \- Dado que un visitante está en la sección "Cómo Funciona", Cuando revisa el flujo para aprendices, Entonces ve una secuencia de 3 o 4 pasos sencillos, como "1. Regístrate y completa tu perfil", "2. Busca un encuentro" y "3. ¡Asiste y practica\!". **Escenario \#2: Pasos para el local** \- Dado que un visitante está en la sección "Cómo Funciona", Cuando revisa el flujo para locales, Entonces ve los pasos correspondientes: "1. Registra tu local", "2. Ofrece tu espacio" y "3. Recibe a los practicantes". |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-05 | Visitante indeciso | 3 | Landing Page |
| **Título** | **Visualización de Testimonios** |  |  |
| **Descripción** | **Como** visitante indeciso **Quiero** ver testimonios de aprendices y dueños de locales reales **Para** aumentar mi confianza en el servicio. **Escenario \#1: Visualización de testimonios diversos** \- Dado que el visitante explora la landing page, Cuando accede a la sección de testimonios, Entonces debe ver al menos un testimonio de un aprendiz y uno de un dueño de local, mostrando su nombre, una foto, su rol y su comentario. |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-06 | Visitante | 2 | Landing Page |
| **Título** | **Llamadas a la Acción (CTA) Diferenciadas** |  |  |
| **Descripción** | **Como** visitante **Quiero** ver botones de llamada a la acción claros y separados, uno para aprendices y otro para locales **Para** poder registrarme fácilmente según mi interés. **Escenario \#1: Registro como aprendiz** \- Dado que un visitante está interesado en practicar idiomas, Cuando hace clic en el botón "Únete como Aprendiz", Entonces es redirigido a la página de registro para usuarios aprendices. **Escenario \#2: Registro como local** \- Dado que un visitante es dueño de un local, Cuando hace clic en el botón "Registra tu Local", Entonces es redirigido a la página de registro para partners. |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-07 | Visitante que accede desde diferentes dispositivos | 5 | Landing Page |
| **Título** | **Adaptabilidad a Diferentes Dispositivos (Responsive)** |  |  |
| **Descripción** | **Como** visitante que accede desde diferentes dispositivos **Quiero** que la landing page se adapte correctamente a mi pantalla **Para** tener una experiencia óptima independientemente del dispositivo que use. **Escenario \#1: Experiencia en dispositivo móvil** \- Dado que un visitante accede a la landing page desde un smartphone, Cuando la página se carga, Entonces todos los elementos se reorganizan en una sola columna, el texto es legible y los botones son fáciles de presionar, sin necesidad de hacer zoom o scroll horizontal. |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-08 | Visitante | 3 | Landing Page |
| **Título** | **Navegación mediante Encabezado Fijo** |  |  |
| **Descripción** | **Como** visitante **Quiero** un menú de navegación claro en el encabezado que permanezca visible mientras me desplazo **Para** acceder fácilmente a las diferentes secciones de la página. **Escenario \#1: Acceso a secciones desde el encabezado** \- Dado que un visitante explora la landing page, Cuando hace clic en una opción del menú de navegación (ej. "Beneficios"), Entonces la página se desplaza suavemente hasta esa sección, y el encabezado permanece fijo en la parte superior de la pantalla. |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-09 | Visitante con dudas | 2 | Landing Page |
| **Título** | **Visualización de una Sección de Preguntas Frecuentes (FAQ)** |  |  |
| **Descripción** | **Como** visitante con dudas **Quiero** encontrar una sección de preguntas frecuentes **Para** resolver rápidamente mis inquietudes más comunes. **Escenario \#1: Resolver una duda común** \- Dado que un visitante se pregunta si tiene que pagar para asistir, Cuando accede a la sección de FAQ y hace clic en la pregunta "¿Tiene algún costo?", Entonces se despliega una respuesta clara y concisa. |  |  |

| Story ID | User | Story Points | Epic |
| :---- | :---- | :---- | :---- |
| US-LP-10 | Visitante | 1 | Landing Page |
| **Título** | **Visualización del Pie de Página (Footer)** |  |  |
| **Descripción** | **Como** visitante **Quiero** ver un pie de página organizado con enlaces de interés **Para** encontrar información adicional o contactar con la empresa. **Escenario \#1: Contenido completo del pie de página** \- Dado que un visitante se desplaza hasta el final de la landing page, Cuando llega al pie de página, Entonces debe ver enlaces a "Términos y Condiciones", "Política de Privacidad", y enlaces a las redes sociales del proyecto. |  |  |

## Tabla de User Stories por Epic

| Story ID | User | Story Points | Epic |
|----------|------|----------|------|
| US01 | Persona interesada en practicar idiomas | 3 | Gestión de Identidad y Acceso (IAM) |
| **Title** | **Registro de nuevo aprendiz** |
| **Description** | **Como** una persona interesada en practicar idiomas **Quiero** registrarme en la plataforma con mi correo y contraseña **Para** poder acceder a la comunidad y a los encuentros. **Escenario #1: Registro exitoso** - Dado que un nuevo usuario desea unirse a la plataforma, Cuando proporciona los datos requeridos para el registro y acepta los términos, Entonces el sistema crea su cuenta, le envía una bienvenida y lo guía para completar su perfil. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US02 | Dueño de un local | 5 | Gestión de Identidad y Acceso (IAM) |
| **Title** | **Registro de nuevo local** |
| **Description** | **Como** dueño de un local **Quiero** registrar mi negocio en la plataforma **Para** ofrecer mi espacio para los encuentros y ganar visibilidad. **Escenario #1: Registro de local exitoso** - Dado que el dueño de un local desea unirse a la plataforma, Cuando proporciona la información de su cuenta y los datos de su negocio, Entonces el sistema crea una cuenta de tipo "Partner", la asocia al local y le concede acceso al panel de gestión. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US03 | Usuario registrado (aprendiz o dueño de local) | 3 | Gestión de Identidad y Acceso (IAM) |
| **Title** | **Inicio de sesión general** |
| **Description** | **Como** usuario registrado (aprendiz o dueño de local) **Quiero** iniciar sesión con mi correo y contraseña **Para** acceder a mis funcionalidades personalizadas. **Escenario #1: Inicio de sesión exitoso** - Dado que un usuario registrado desea acceder a su cuenta, Cuando proporciona sus credenciales de acceso correctas, Entonces el sistema lo autentica y le presenta su panel principal correspondiente. **Escenario #2: Credenciales incorrectas** - Dado que un usuario registrado desea acceder a su cuenta, Cuando proporciona credenciales incorrectas, Entonces el sistema le informa que el acceso ha sido denegado por credenciales inválidas. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US04 | Usuario autenticado | 1 | Gestión de Identidad y Acceso (IAM) |
| **Title** | **Cierre de sesión** |
| **Description** | **Como** usuario autenticado **Quiero** poder cerrar mi sesión **Para** proteger la privacidad de mi cuenta en dispositivos compartidos. **Escenario #1: Cierre de sesión exitoso** - Dado que un usuario ha iniciado sesión en la plataforma, Cuando solicita finalizar su sesión, Entonces el sistema termina la sesión activa y lo devuelve a la página de inicio pública. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US05 | Usuario registrado | 2 | Gestión de Identidad y Acceso (IAM) |
| **Title** | **Recuperación de contraseña** |
| **Description** | **Como** usuario registrado **Quiero** solicitar un enlace para restablecer mi contraseña si la he olvidado **Para** poder recuperar el acceso a mi cuenta. **Escenario #1: Solicitud de recuperación exitosa** - Dado que un usuario olvidó su contraseña, Cuando proporciona el correo electrónico de su cuenta para la recuperación, Entonces el sistema le envía un correo con las instrucciones para crear una nueva contraseña. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US06 | Nuevo aprendiz | 3 | Perfiles de Usuario (Profiles) |
| **Title** | **Completar perfil de aprendiz** |
| **Description** | **Como** nuevo aprendiz **Quiero** completar mi perfil con mi idioma nativo, los idiomas que quiero practicar y mi nivel **Para** que otros usuarios me conozcan y el sistema me recomiende encuentros relevantes. **Escenario #1: Primer llenado de perfil** - Dado que un aprendiz se ha registrado, Cuando especifica sus idiomas, su nivel de fluidez y guarda la información, Entonces su perfil se actualiza y el sistema utiliza estas preferencias para recomendarle encuentros. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US07 | Aprendiz | 2 | Perfiles de Usuario (Profiles) |
| **Title** | **Editar perfil de aprendiz** |
| **Description** | **Como** aprendiz **Quiero** poder editar la información de mi perfil en cualquier momento **Para** mantenerla actualizada. **Escenario #1: Actualización de idiomas** - Dado que un aprendiz ha mejorado su nivel de inglés, Cuando actualiza su nivel de fluidez en su perfil, Entonces el sistema guarda los cambios y su perfil público refleja la nueva información. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US08 | Aprendiz | 2 | Perfiles de Usuario (Profiles) |
| **Title** | **Ver perfil de otro usuario** |
| **Description** | **Como** aprendiz **Quiero** ver el perfil de otros asistentes a un encuentro **Para** conocer sus idiomas de interés y conectar con ellos. **Escenario #1: Visualización de perfil público** - Dado que estoy viendo los detalles de un encuentro, Cuando solicito ver el perfil de otro asistente, Entonces se me muestra su información pública relevante (foto, nombre, idiomas). |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US09 | Usuario | 2 | Perfiles de Usuario (Profiles) |
| **Title** | **Subir foto de perfil** |
| **Description** | **Como** usuario **Quiero** subir una foto de perfil **Para** personalizar mi cuenta y que otros me reconozcan más fácilmente. **Escenario #1: Carga de imagen exitosa** - Dado que estoy gestionando mi perfil, Cuando proporciono una nueva imagen para mi perfil, Entonces la imagen se actualiza y se muestra en toda la plataforma. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US10 | Dueño de negocio (Partner) | 5 | Gestión de Locales (Partner) |
| **Title** | **Dar de alta un nuevo local** |
| **Description** | **Como** dueño de negocio (Partner) **Quiero** añadir los detalles de mi local, incluyendo nombre, dirección, aforo y horario **Para** que aparezca en la plataforma como un lugar disponible para encuentros. **Escenario #1: Registro de información del local** - Dado que un Partner desea añadir un nuevo local, Cuando proporciona toda la información requerida del establecimiento y la guarda, Entonces el local se añade a su perfil y se vuelve visible en la plataforma. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US11 | Partner | 3 | Gestión de Locales (Partner) |
| **Title** | **Editar información de un local** |
| **Description** | **Como** Partner **Quiero** poder editar los detalles de mi local registrado **Para** mantener la información actualizada (ej. cambio de horario). **Escenario #1: Actualizar horario del local** - Dado que un Partner necesita cambiar el horario de su cafetería, Cuando modifica la información del horario en los detalles del local, Entonces la nueva información se refleja inmediatamente en la plataforma. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US12 | Partner | 3 | Gestión de Locales (Partner) |
| **Title** | **Añadir fotos del local** |
| **Description** | **Como** Partner **Quiero** subir varias fotos de mi local **Para** hacerlo más atractivo y mostrar el ambiente a los aprendices. **Escenario #1: Cargar galería de fotos** - Dado que un Partner está gestionando el perfil de su local, Cuando proporciona un conjunto de imágenes del establecimiento, Entonces las fotos se asocian al perfil del local y se muestran en una galería. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US13 | Partner | 2 | Gestión de Locales (Partner) |
| **Title** | **Definir consumo mínimo (Opcional)** |
| **Description** | **Como** Partner **Quiero** tener la opción de definir un consumo mínimo sugerido para los asistentes a encuentros en mi local **Para** asegurar un retorno económico. **Escenario #1: Establecer consumo mínimo** - Dado que un Partner desea incentivar el consumo, Cuando establece un consumo mínimo sugerido para los encuentros en su local, Entonces esta información es visible en los detalles de dichos encuentros. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US14 | Partner | 5 | Gestión de Locales (Partner) |
| **Title** | **Ver dashboard de mi local** |
| **Description** | **Como** Partner **Quiero** ver un dashboard con un resumen de la actividad en mi local **Para** entender rápidamente cuántos encuentros se han realizado y cuántas personas han asistido. **Escenario #1: Visualización de métricas clave** - Dado que un Partner accede a su panel, Cuando solicita ver el resumen de actividad, Entonces se le presentan las métricas clave de sus locales (encuentros, asistentes, calificación). |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US15 | Aprendiz | 3 | Gestión de Encuentros (Event) |
| **Title** | **Buscar encuentros disponibles** |
| **Description** | **Como** aprendiz **Quiero** buscar encuentros usando filtros por idioma, ciudad y fecha **Para** encontrar fácilmente una sesión de práctica que me interese. **Escenario #1: Búsqueda con filtros** - Dado que un aprendiz quiere encontrar un encuentro, Cuando aplica filtros de búsqueda por idioma, ciudad y fecha, Entonces el sistema le muestra una lista de resultados que coinciden con sus criterios. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US16 | Aprendiz | 2 | Gestión de Encuentros (Event) |
| **Title** | **Ver detalles de un encuentro** |
| **Description** | **Como** aprendiz **Quiero** ver los detalles completos de un encuentro **Para** saber el idioma, el tema, el lugar, la hora y quiénes más asistirán. **Escenario #1: Acceder a la información del encuentro** - Dado que un aprendiz ha encontrado un encuentro de su interés, Cuando selecciona ese encuentro de la lista, Entonces se le presenta toda la información detallada del evento. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US17 | Aprendiz | 5 | Gestión de Encuentros (Event) |
| **Title** | **Reservar un cupo en un encuentro** |
| **Description** | **Como** aprendiz **Quiero** reservar mi cupo en un encuentro que tenga plazas disponibles **Para** asegurar mi asistencia. **Escenario #1: Reserva exitosa** - Dado que un aprendiz está viendo un encuentro con cupos disponibles, Cuando confirma su deseo de reservar un cupo, Entonces el sistema procesa su reserva, actualiza los cupos y le envía una notificación. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US18 | Aprendiz | 5 | Gestión de Encuentros (Event) |
| **Title** | **Recibir confirmación con código QR** |
| **Description** | **Como** aprendiz **Quiero** recibir una confirmación de mi reserva que incluya un código QR **Para** poder hacer check-in fácilmente al llegar al local. **Escenario #1: Generación de QR tras reserva** - Dado que un aprendiz ha completado una reserva, Cuando consulta los detalles de su reserva, Entonces el sistema le proporciona un código QR único para el check-in. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US19 | Aprendiz | 8 | Gestión de Encuentros (Event) |
| **Title** | **Crear un encuentro (iniciativa del aprendiz)** |
| **Description** | **Como** aprendiz **Quiero** proponer la creación de un nuevo encuentro en un local registrado **Para** organizar una sesión si no hay ninguna que se ajuste a mis necesidades. **Escenario #1: Proponer nuevo encuentro** - Dado que un aprendiz desea organizar un encuentro, Cuando proporciona los detalles del nuevo evento (local, fecha, idioma), Entonces el sistema crea el encuentro, lo registra como el primer asistente y lo hace visible para otros usuarios. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US20 | Aprendiz | 8 | Gestión de Encuentros (Event) |
| **Title** | **Check-in en un encuentro** |
| **Description** | **Como** aprendiz **Quiero** hacer check-in al llegar al encuentro mostrando mi código QR **Para** confirmar mi asistencia y ganar puntos de lealtad. **Escenario #1: Check-in exitoso por parte del local** - Dado que un aprendiz llega al local del encuentro, Cuando su código QR es validado por el organizador, Entonces el sistema registra su asistencia y le asigna los puntos correspondientes. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US21 | Partner | 3 | Gestión de Encuentros (Event) |
| **Title** | **Ver lista de asistentes (vista de Partner)** |
| **Description** | **Como** Partner **Quiero** ver la lista de personas que han reservado para un encuentro en mi local **Para** tener una idea del aforo esperado. **Escenario #1: Consultar asistentes** - Dado que un Partner tiene un encuentro programado, Cuando consulta los detalles de dicho evento, Entonces el sistema le muestra la lista de los aprendices que han confirmado su asistencia. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US22 | Aprendiz con una reserva | 2 | Gestión de Encuentros (Event) |
| **Title** | **Recibir recordatorio de encuentro** |
| **Description** | **Como** aprendiz con una reserva **Quiero** recibir una notificación de recordatorio 24 horas antes del encuentro **Para** no olvidarme de asistir. **Escenario #1: Notificación automática** - Dado que un aprendiz tiene una reserva para mañana, Cuando faltan 24 horas para el evento, Entonces el sistema le envía automáticamente un recordatorio. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US23 | Aprendiz | 3 | Gestión de Encuentros (Event) |
| **Title** | **Unirse a la lista de espera** |
| **Description** | **Como** aprendiz **Quiero** unirme a una lista de espera si un encuentro está lleno **Para** tener la oportunidad de asistir si alguien cancela. **Escenario #1: Encuentro lleno** - Dado que un aprendiz desea asistir a un encuentro sin cupos, Cuando opta por unirse a la lista de espera, Entonces el sistema lo añade a la cola y le notifica su posición. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US24 | Aprendiz en una lista de espera | 5 | Gestión de Encuentros (Event) |
| **Title** | **Recibir notificación de cupo liberado** |
| **Description** | **Como** aprendiz en una lista de espera **Quiero** recibir una notificación inmediata si un cupo se libera **Para** poder reservarlo rápidamente. **Escenario #1: Alguien cancela** - Dado que un aprendiz está en una lista de espera y se libera un cupo, Cuando le llega su turno, Entonces el sistema le envía una notificación para que pueda confirmar su asistencia en un tiempo limitado. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US25 | Aprendiz que asistió a un encuentro | 3 | Gestión de Encuentros (Event) |
| **Title** | **Dejar feedback de un encuentro** |
| **Description** | **Como** aprendiz que asistió a un encuentro **Quiero** dejar una calificación y un comentario sobre mi experiencia **Para** ayudar a otros usuarios y a los locales. **Escenario #1: Calificar la experiencia** - Dado que un aprendiz ha asistido a un encuentro, Cuando proporciona una calificación y un comentario sobre el evento, Entonces el sistema guarda su feedback y lo asocia al encuentro y al local. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US26 | Aprendiz | 3 | Gestión de Encuentros (Event) |
| **Title** | **Cancelar mi reserva** |
| **Description** | **Como** aprendiz **Quiero** poder cancelar mi reserva a un encuentro con antelación **Para** liberar mi cupo si no puedo asistir. **Escenario #1: Cancelación a tiempo** - Dado que un aprendiz tiene una reserva y no puede asistir, Cuando solicita la cancelación de su reserva antes del tiempo límite, Entonces su cupo se libera para otros usuarios. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US27 | Aprendiz | 2 | Gestión de Encuentros (Event) |
| **Title** | **Ver encuentros pasados** |
| **Description** | **Como** aprendiz **Quiero** tener un historial de los encuentros a los que he asistido **Para** recordar los lugares y las fechas. **Escenario #1: Consultar historial** - Dado que un aprendiz quiere revisar su actividad pasada, Cuando consulta su historial de encuentros, Entonces el sistema le muestra una lista de todos los eventos en los que participó. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US28 | Aprendiz | 5 | Gestión de Encuentros (Event) |
| **Title** | **Ver el mapa de locales** |
| **Description** | **Como** aprendiz **Quiero** ver un mapa con la ubicación de todos los locales registrados **Para** descubrir lugares cercanos donde se organizan encuentros. **Escenario #1: Exploración geográfica** - Dado que un aprendiz quiere descubrir nuevos locales, Cuando explora la vista de mapa, Entonces el sistema le muestra la ubicación de todos los locales aliados. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US29 | Aprendiz | 5 | Lealtad y Gamificación (Loyalty) |
| **Title** | **Ganar puntos por asistencia** |
| **Description** | **Como** aprendiz **Quiero** ganar puntos de lealtad cada vez que hago check-in en un encuentro **Para** ser recompensado por mi participación activa. **Escenario #1: Acumulación de puntos** - Dado que un aprendiz ha hecho check-in exitosamente en un evento, Cuando el sistema procesa su asistencia, Entonces automáticamente se suman los puntos correspondientes a su cuenta. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US30 | Aprendiz | 1 | Lealtad y Gamificación (Loyalty) |
| **Title** | **Ver mi total de puntos y nivel** |
| **Description** | **Como** aprendiz **Quiero** poder ver mi saldo total de puntos y mi nivel actual en mi perfil **Para** seguir mi progreso. **Escenario #1: Consultar progreso** - Dado que un aprendiz accede a su perfil, Cuando consulta su progreso de lealtad, Entonces el sistema le muestra sus puntos totales y su nivel actual. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US31 | Aprendiz | 5 | Lealtad y Gamificación (Loyalty) |
| **Title** | **Desbloquear una insignia (badge)** |
| **Description** | **Como** aprendiz **Quiero** desbloquear insignias al alcanzar ciertos hitos (ej. "Asistir a 5 encuentros de francés") **Para** sentir que logro algo. **Escenario #1: Desbloqueo de insignia por asistencia** - Dado que un aprendiz ha cumplido los requisitos para una insignia, Cuando el sistema verifica el hito, Entonces le otorga la insignia correspondiente y le muestra una notificación. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US32 | Aprendiz | 3 | Lealtad y Gamificación (Loyalty) |
| **Title** | **Ver mis insignias desbloqueadas** |
| **Description** | **Como** aprendiz **Quiero** tener una sección en mi perfil donde pueda ver todas las insignias que he ganado **Para** mostrarlas a la comunidad. **Escenario #1: Galería de logros** - Dado que un aprendiz ha desbloqueado insignias, Cuando visita un perfil (suyo o de otro usuario), Entonces puede ver la colección de insignias ganadas. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US33 | Aprendiz | 3 | Lealtad y Gamificación (Loyalty) |
| **Title** | **Ver un ranking de usuarios** |
| **Description** | **Como** aprendiz **Quiero** ver una tabla de clasificación (leaderboard) semanal o mensual **Para** competir de forma amistosa con otros miembros de la comunidad. **Escenario #1: Consultar el leaderboard** - Dado que un aprendiz quiere ver su posición en la comunidad, Cuando accede a la tabla de clasificación, Entonces el sistema le muestra el ranking de usuarios basado en puntos. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US34 | Aprendiz leal | 5 | Lealtad y Gamificación (Loyalty) |
| **Title** | **Recibir ofertas de locales por lealtad** |
| **Description** | **Como** aprendiz leal **Quiero** recibir ofertas especiales o descuentos de los locales asociados **Como** recompensa por mi participación. **Escenario #1: Recompensa de un Partner** - Dado que un aprendiz ha alcanzado un nivel de lealtad alto, Cuando un local ofrece una recompensa para ese nivel, Entonces el aprendiz recibe una notificación con la oferta especial. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US35 | Aprendiz | 3 | Lealtad y Gamificación (Loyalty) |
| **Title** | **Mantener una racha de asistencia** |
| **Description** | **Como** aprendiz **Quiero** que el sistema registre mi racha de asistencia semanal **Para** motivarme a participar de forma consistente. **Escenario #1: Incrementar la racha** - Dado que un aprendiz asistió a un encuentro la semana pasada, Cuando asiste a otro encuentro esta semana, Entonces el sistema incrementa su racha de asistencia y se lo notifica. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US36 | Partner | 5 | Analíticas (Analytics) |
| **Title** | **Ver número de asistentes por mes** |
| **Description** | **Como** Partner **Quiero** ver un gráfico con el número total de asistentes a encuentros en mi local cada mes **Para** medir el impacto de la plataforma. **Escenario #1: Reporte mensual de asistencia** - Dado que un Partner está en su panel de analíticas, Cuando consulta el reporte de asistencia mensual, Entonces el sistema le presenta un gráfico con los datos de asistencia por mes. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US37 | Partner | 3 | Analíticas (Analytics) |
| **Title** | **Ver calificación promedio de mi local** |
| **Description** | **Como** Partner **Quiero** ver la calificación promedio que los aprendices le han dado a los encuentros realizados en mi local **Para** evaluar la satisfacción del cliente. **Escenario #1: Métrica de satisfacción** - Dado que un Partner está en su dashboard, Cuando consulta el rendimiento de su local, Entonces el sistema le muestra la calificación promedio basada en el feedback de los usuarios. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US38 | Partner | 8 | Analíticas (Analytics) |
| **Title** | **Identificar horas y días pico** |
| **Description** | **Como** Partner **Quiero** ver un reporte que me muestre qué días de la semana y a qué horas se realizan más encuentros en mi local **Para** optimizar mi personal. **Escenario #1: Mapa de calor de actividad** - Dado que un Partner quiere conocer sus horas más populares, Cuando consulta el reporte de horas pico, Entonces el sistema le presenta una visualización de los días y horas con mayor actividad. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US39 | Partner | 8 | Analíticas (Analytics) |
| **Title** | **Rastrear asistentes nuevos vs. recurrentes** |
| **Description** | **Como** Partner **Quiero** saber qué porcentaje de los asistentes son nuevos clientes versus personas que ya han venido antes **Para** medir la captación de nuevo público. **Escenario #1: Reporte de retención** - Dado que un Partner está analizando sus métricas, Cuando consulta el reporte de clientes, Entonces el sistema le muestra la proporción de asistentes nuevos vs. recurrentes. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US40 | Partner | 5 | Analíticas (Analytics) |
| **Title** | **Descargar reporte básico** |
| **Description** | **Como** Partner **Quiero** poder descargar un resumen de mis analíticas en formato PDF o CSV **Para** mis registros internos. **Escenario #1: Exportar datos** - Dado que un Partner necesita un informe de su actividad, Cuando solicita la descarga del reporte de analíticas, Entonces el sistema genera un archivo con los datos del período seleccionado. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US41 | Aprendiz | 3 | Comunidad y Social |
| **Title** | **Enviar solicitud de contacto** |
| **Description** | **Como** aprendiz **Quiero** poder enviar una solicitud de contacto a otra persona con la que interactué en un encuentro **Para** mantener la comunicación. **Escenario #1: Conectar después de un evento** - Dado que he interactuado con otro aprendiz en un encuentro, Cuando envío una solicitud de contacto a través de su perfil, Entonces el sistema notifica al otro usuario de mi solicitud. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US42 | Aprendiz | 3 | Comunidad y Social |
| **Title** | **Aceptar solicitud de contacto** |
| **Description** | **Como** aprendiz **Quiero** recibir notificaciones de nuevas solicitudes de contacto **Para** poder aceptarlas o rechazarlas. **Escenario #1: Gestión de solicitudes** - Dado que he recibido una solicitud de contacto, Cuando acepto la solicitud, Entonces ambos pasamos a formar parte de nuestras respectivas listas de contactos. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US43 | Aprendiz | 2 | Comunidad y Social |
| **Title** | **Ver mi lista de contactos** |
| **Description** | **Como** aprendiz **Quiero** tener una lista de todos los usuarios con los que he conectado **Para** poder iniciar una conversación. **Escenario #1: Acceder a mis conexiones** - Dado que he establecido contactos en la plataforma, Cuando consulto mi lista de contactos, Entonces el sistema me muestra todos los usuarios con los que he conectado. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US44 | Aprendiz | 5 | Mensajería |
| **Title** | **Enviar mensaje a un contacto** |
| **Description** | **Como** aprendiz **Quiero** poder enviar un mensaje directo a uno de mis contactos **Para** organizar una futura práctica de idiomas. **Escenario #1: Iniciar una conversación** - Dado que deseo comunicarme con un contacto, Cuando le envío un mensaje privado, Entonces el sistema entrega el mensaje y le notifica al destinatario. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US45 | Usuario | 5 | Notificaciones |
| **Title** | **Recibir notificaciones de mensajes nuevos** |
| **Description** | **Como** usuario **Quiero** recibir una notificación cuando uno de mis contactos me envía un mensaje **Para** poder responder a tiempo. **Escenario #1: Alerta de mensaje** - Dado que estoy usando la aplicación, Cuando recibo un nuevo mensaje de un contacto, Entonces el sistema me alerta de la notificación. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US46 | Usuario | 5 | Moderación |
| **Title** | **Reportar un usuario** |
| **Description** | **Como** usuario **Quiero** tener la opción de reportar a otro usuario por comportamiento inapropiado **Para** mantener un ambiente seguro y respetuoso en la comunidad. **Escenario #1: Denunciar comportamiento** - Dado que he presenciado un comportamiento inapropiado, Cuando envío un reporte sobre un usuario especificando el motivo, Entonces el sistema envía el reporte a los administradores para su revisión. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US47 | Administrador | 8 | Administración |
| **Title** | **Ver dashboard de administrador** |
| **Description** | **Como** administrador de la plataforma **Quiero** acceder a un dashboard con métricas generales de uso **Para** monitorear la salud del servicio. **Escenario #1: Vista general del sistema** - Dado que un administrador ha iniciado sesión, Cuando accede al panel de administración, Entonces el sistema le presenta las métricas clave de la plataforma. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US48 | Administrador | 5 | Administración |
| **Title** | **Gestionar usuarios** |
| **Description** | **Como** administrador **Quiero** poder ver la lista de todos los usuarios y poder desactivar una cuenta en caso de abuso **Para** mantener la calidad de la comunidad. **Escenario #1: Desactivar una cuenta** - Dado que se ha verificado un reporte de abuso, Cuando el administrador ejecuta la acción de desactivar la cuenta del infractor, Entonces el usuario ya no puede acceder a la plataforma. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US49 | Administrador | 5 | Administración |
| **Title** | **Validar nuevos locales** |
| **Description** | **Como** administrador **Quiero** tener un proceso para validar y aprobar los nuevos locales que se registran **Para** asegurar que son lugares apropiados y reales. **Escenario #1: Aprobación de local** - Dado que un nuevo local está pendiente de aprobación, Cuando el administrador verifica y aprueba la solicitud, Entonces el local se activa y se hace visible públicamente en la plataforma. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US50 | Administrador | 8 | Administración |
| **Title** | **Gestionar reportes de usuarios** |
| **Description** | **Como** administrador **Quiero** ver una lista de todos los reportes enviados por los usuarios **Para** poder investigarlos y tomar acciones. **Escenario #1: Revisar una denuncia** - Dado que un usuario ha sido reportado, Cuando el administrador consulta los reportes pendientes, Entonces puede ver todos los detalles de la denuncia para su investigación. |

| Story ID | User | Priority | Epic |
|----------|------|----------|------|
| US51 | Administrador | 8 | Administración |
| **Title** | **Enviar comunicaciones globales** |
| **Description** | **Como** administrador **Quiero** poder enviar notificaciones o correos electrónicos a todos los usuarios **Para** comunicar novedades o mantenimientos de la plataforma. **Escenario #1: Anuncio de nueva funcionalidad** - Dado que se necesita comunicar una novedad a todos los usuarios, Cuando el administrador envía una comunicación global, Entonces todos los usuarios registrados reciben la notificación. |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-01** | API Endpoint para Registro de Usuarios | IAM |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/auth/register **Para** que los nuevos usuarios (aprendices o partners) puedan crear una cuenta en el sistema. **Criterios de Aceptación** **Escenario \#1: Registro exitoso de un aprendiz** **Dado que** un usuario no registrado desea unirse como aprendiz, **Cuando** se envía una petición POST a /api/auth/register con un body JSON válido que incluye email, password y role: "aprendiz", **Entonces** el sistema responde con un código de estado 201 Created, crea el nuevo user y su user\_profile asociado, y devuelve un token JWT en el cuerpo de la respuesta. **Escenario \#2: Correo electrónico ya existe** **Dado que** un correo electrónico "user@example.com" ya existe en la base de datos, **Cuando** se envía una petición POST a /api/auth/register con el mismo correo, **Entonces** el sistema responde con un código de estado 409 Conflict y un mensaje de error indicando que el email ya está en uso. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-02** | API Endpoint para Autenticación de Usuarios | IAM |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/auth/login **Para** que los usuarios registrados puedan autenticarse y obtener un token de acceso. **Criterios de Aceptación** **Escenario \#1: Autenticación exitosa** **Dado que** un usuario existe con credenciales válidas, **Cuando** se envía una petición POST a /api/auth/login con su email y password correctos, **Entonces** el sistema responde con un código de estado 200 OK y un cuerpo de respuesta JSON que contiene un accessToken JWT válido. **Escenario \#2: Credenciales incorrectas** **Dado que** un usuario intenta iniciar sesión, **Cuando** se envía una petición POST a /api/auth/login con una contraseña incorrecta, **Entonces** el sistema responde con un código de estado 401 Unauthorized y un mensaje de error. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-03** | API Endpoint para Obtener Datos del Usuario Autenticado | IAM |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/users/me **Para** que el frontend pueda obtener los datos del perfil del usuario actualmente autenticado. **Criterios de Aceptación** **Escenario \#1: Obtener perfil de usuario exitosamente** **Dado que** un usuario está autenticado con un JWT válido, **Cuando** envía una petición GET a /api/users/me, **Entonces** el sistema responde con 200 OK y el objeto JSON completo de su perfil (sea user\_profile o partner\_profile). |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-04** | API Endpoint para Actualizar el Perfil de un Aprendiz | Profiles |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint PUT /api/profiles/user **Para** que un aprendiz autenticado pueda actualizar su información personal y preferencias de idioma. **Criterios de Aceptación** **Escenario \#1: Actualización exitosa** **Dado que** un aprendiz está autenticado, **Cuando** envía una petición PUT a /api/profiles/user con un body JSON que contiene los campos a actualizar (ej: full\_name, languages), **Entonces** el sistema responde con 200 OK, actualiza la información en la base de datos y devuelve el perfil actualizado. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-05** | API Endpoint para Obtener un Perfil Público de Aprendiz | Profiles |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/profiles/user/{profileId} **Para** que los usuarios puedan ver la información pública de otros aprendices. **Criterios de Aceptación** **Escenario \#1: Perfil encontrado** **Dado que** un aprendiz con profileId=456 existe, **Cuando** un usuario autenticado envía una petición GET a /api/profiles/user/456, **Entonces** el sistema responde con 200 OK y un objeto JSON con los datos públicos del perfil (nombre, foto, idiomas, insignias). |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-06** | API Endpoint para que un Partner añada un Local | Partner |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/venues **Para** que un usuario autenticado con rol "Partner" pueda registrar un nuevo local. **Criterios de Aceptación** **Escenario \#1: Partner registra un local exitosamente** **Dado que** un usuario está autenticado con un JWT válido y tiene el rol "Partner", **Cuando** envía una petición POST a /api/venues con los datos del local (nombre, dirección, aforo) en el body, **Entonces** el sistema responde con 201 Created, crea el nuevo registro en la tabla venues asociándolo al partner (con estado pending\_approval), y devuelve el objeto del local creado. **Escenario \#2: Usuario no autorizado intenta registrar un local** **Dado que** un usuario está autenticado pero tiene el rol "aprendiz", **Cuando** intenta enviar una petición POST a /api/venues, **Entonces** el sistema responde con un código de estado 403 Forbidden. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-07** | API Endpoint para que un Partner obtenga sus Locales | Partner |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/partners/me/venues **Para** que un Partner pueda ver la lista de todos los locales que ha registrado. **Criterios de Aceptación** **Escenario \#1: Obtener lista de locales** **Dado que** un Partner autenticado ha registrado 3 locales, **Cuando** envía una petición GET a /api/partners/me/venues, **Entonces** el sistema responde con 200 OK y un array JSON que contiene los 3 objetos de sus locales. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-08** | API Endpoint para que un Partner actualice un Local | Partner |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint PUT /api/venues/{venueId} **Para** que un Partner pueda actualizar la información de un local que le pertenece. **Criterios de Aceptación** **Escenario \#1: Actualización exitosa** **Dado que** un Partner es dueño del local con venueId=789, **Cuando** envía una petición PUT a /api/venues/789 con los nuevos datos, **Entonces** el sistema responde con 200 OK y devuelve el objeto del local actualizado. **Escenario \#2: Intento de actualizar un local ajeno** **Dado que** un Partner NO es dueño del local con venueId=789, **Cuando** intenta enviar una petición PUT a /api/venues/789, **Entonces** el sistema responde con 403 Forbidden. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-09** | API Endpoint para Obtener Catálogos | Catalogs |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/catalogs **Para** que el frontend pueda obtener las listas de idiomas, niveles e intereses disponibles. **Criterios de Aceptación** **Escenario \#1: Obtener todos los catálogos** **Cuando** se envía una petición GET a /api/catalogs, **Entonces** el sistema responde con 200 OK y un objeto JSON que contiene tres arrays: languages, levels, e interests. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-10** | API Endpoint para Buscar Encuentros | Event |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/encounters que soporte filtros **Para** que los usuarios puedan buscar encuentros según sus preferencias. **Criterios de Aceptación** **Escenario \#1: Búsqueda con filtros** **Dado que** existen varios encuentros programados en la base de datos, **Cuando** se envía una petición GET a /api/encounters?languageId=1\&city=Lima, **Entonces** el sistema responde con un 200 OK y una lista de los encuentros que coinciden con los filtros. **Escenario \#2: Búsqueda sin resultados** **Cuando** se envía una petición GET a /api/encounters con filtros que no coinciden con ningún encuentro, **Entonces** el sistema responde con un 200 OK y una lista vacía \[\]. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-11** | API Endpoint para Crear un Encuentro | Event |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/encounters **Para** que un aprendiz autenticado pueda crear un nuevo encuentro. **Criterios de Aceptación** **Escenario \#1: Creación exitosa** **Dado que** un aprendiz está autenticado, **Cuando** envía una petición POST a /api/encounters con los detalles del evento (venue\_id, language\_id, start\_time, etc.), **Entonces** el sistema responde con 201 Created, crea el encuentro y la primera attendance para el creador, y devuelve el objeto del encuentro creado. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-12** | API Endpoint para Obtener Detalles de un Encuentro | Event |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/encounters/{encounterId} **Para** que los usuarios puedan ver la información completa de un evento específico. **Criterios de Aceptación** **Escenario \#1: Encuentro encontrado** **Dado que** un encuentro con id=123 existe, **Cuando** se envía una petición GET a /api/encounters/123, **Entonces** el sistema responde con 200 OK y el objeto JSON del encuentro, incluyendo detalles del local y una lista de los perfiles de los asistentes. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-13** | API Endpoint para Reservar un Cupo en un Encuentro | Event |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/encounters/{encounterId}/attendances **Para** que un aprendiz pueda reservar su asistencia a un encuentro. **Criterios de Aceptación** **Escenario \#1: Reserva exitosa** **Dado que** un aprendiz está autenticado y un encuentro con id=123 tiene cupos disponibles, **Cuando** envía una petición POST a /api/encounters/123/attendances, **Entonces** el sistema responde con 201 Created, crea un registro en la tabla attendances con estado "confirmed", y devuelve el objeto de la reserva incluyendo un código QR. **Escenario \#2: Encuentro sin cupos disponibles** **Dado que** el encuentro con id=123 no tiene cupos disponibles, **Cuando** un aprendiz envía una petición POST a /api/encounters/123/attendances, **Entonces** el sistema responde con un 409 Conflict y un mensaje indicando que el encuentro está lleno. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-14** | API Endpoint para Cancelar una Reserva | Event |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint DELETE /api/attendances/{attendanceId} **Para** que un aprendiz pueda cancelar su asistencia a un encuentro. **Criterios de Aceptación** **Escenario \#1: Cancelación exitosa** **Dado que** un aprendiz es el dueño de la reserva con attendanceId=999, **Cuando** envía una petición DELETE a /api/attendances/999, **Entonces** el sistema responde con 204 No Content y elimina el registro de la asistencia. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-15** | API Endpoint para realizar el Check-in | Event |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/attendances/check-in **Para** validar la asistencia de un aprendiz a un encuentro a través de su código QR. **Criterios de Aceptación** **Escenario \#1: Check-in exitoso** **Dado que** un Partner está autenticado y un aprendiz tiene una reserva confirmada con un qr\_code válido, **Cuando** el Partner envía una petición POST a /api/attendances/check-in con el qr\_code del aprendiz, **Entonces** el sistema responde con 200 OK, actualiza el estado de la attendance a "attended", y dispara un evento interno UserCheckedInEvent. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-16** | API Endpoint para Enviar Feedback | Feedback |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/attendances/{attendanceId}/feedback **Para** que un aprendiz pueda calificar un encuentro al que asistió. **Criterios de Aceptación** **Escenario \#1: Feedback enviado exitosamente** **Dado que** un aprendiz asistió a un encuentro (su attendance tiene estado "attended"), **Cuando** envía una petición POST a /api/attendances/{attendanceId}/feedback con rating y comment, **Entonces** el sistema responde con 201 Created y guarda el feedback en la base de datos. **Escenario \#2: Intento de dar feedback sin haber asistido** **Dado que** la attendance de un aprendiz no tiene el estado "attended", **Cuando** intenta enviar feedback, **Entonces** el sistema responde con 403 Forbidden. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-17** | Listener de Eventos para Asignar Puntos de Lealtad | Loyalty |
| **Descripción** | **Como** Developer, **Quiero** implementar un listener de eventos que reaccione al UserCheckedInEvent **Para** asignar puntos de lealtad al usuario de forma automática y desacoplada del flujo de check-in. **Criterios de Aceptación** **Escenario \#1: Usuario gana puntos por asistencia** **Dado que** el sistema de Lealtad está escuchando eventos de la aplicación, **Cuando** se dispara un evento UserCheckedInEvent con el profile\_id de un aprendiz, **Entonces** el listener de Lealtad captura el evento y crea un nuevo registro en la tabla loyalty\_points para ese profile\_id con la cantidad de puntos correspondiente por asistencia. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-18** | Listener de Eventos para Desbloquear Insignias | Loyalty |
| **Descripción** | **Como** Developer, **Quiero** implementar una lógica de negocio que se ejecute después de asignar puntos **Para** verificar si un usuario ha cumplido los criterios para desbloquear una nueva insignia. **Criterios de Aceptación** **Escenario \#1: Usuario desbloquea insignia de "Primer Encuentro"** **Dado que** un usuario no tiene asistencias previas, **Cuando** el sistema de lealtad procesa su primer UserCheckedInEvent, **Entonces** después de asignar los puntos, el sistema verifica sus logros, le asigna la insignia "Primer Encuentro" creando un registro en user\_badges y le envía una notificación. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-19** | API Endpoint para Obtener Puntos e Insignias de un Perfil | Loyalty |
| **Descripción** | **Como** Developer, **Quiero** que el endpoint de perfil GET /api/profiles/user/{profileId} incluya la información de lealtad **Para** que pueda ser mostrada en la vista del perfil. **Criterios de Aceptación** **Escenario \#1: Perfil incluye datos de lealtad** **Dado que** un usuario ha ganado 50 puntos y 2 insignias, **Cuando** se solicita su perfil a través de la API, **Entonces** la respuesta JSON del perfil contiene un objeto loyalty con el total de puntos y un array de las insignias ganadas. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-20** | API Endpoint para Enviar Solicitud de Contacto | Community |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/contacts/requests **Para** que un aprendiz pueda enviar una solicitud de contacto a otro. **Criterios de Aceptación** **Escenario \#1: Solicitud enviada exitosamente** **Dado que** el usuario A (id=1) y el usuario B (id=2) no son contactos, **Cuando** el usuario A envía una petición POST a /api/contacts/requests con { "receiver\_profile\_id": 2 }, **Entonces** el sistema responde con 201 Created y crea un registro en la tabla contacts con estado "pending". |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-21** | API Endpoint para Responder Solicitud de Contacto | Community |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint PUT /api/contacts/requests/{requestId} **Para** que un usuario pueda aceptar o rechazar una solicitud de contacto. **Criterios de Aceptación** **Escenario \#1: Aceptar una solicitud** **Dado que** el usuario B ha recibido una solicitud de contacto del usuario A (requestId=5), **Cuando** el usuario B envía una petición PUT a /api/contacts/requests/5 con { "status": "accepted" }, **Entonces** el sistema responde con 200 OK y actualiza el estado del registro en la tabla contacts. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-22** | API Endpoint para Listar Contactos | Community |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/contacts **Para** que un usuario pueda ver su lista de contactos aceptados. **Criterios de Aceptación** **Escenario \#1: Obtener lista de contactos** **Dado que** un usuario autenticado tiene 5 contactos aceptados, **Cuando** envía una petición GET a /api/contacts, **Entonces** el sistema responde con 200 OK y un array con los 5 perfiles de sus contactos. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-23** | API Endpoint para Enviar un Mensaje | Messaging |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint POST /api/messages **Para** que un usuario pueda enviar un mensaje privado a uno de sus contactos. **Criterios de Aceptación** **Escenario \#1: Mensaje enviado exitosamente** **Dado que** el usuario A y el usuario B son contactos, **Cuando** el usuario A envía una petición POST a /api/messages con { "receiver\_profile\_id": B, "content": "Hola\!" }, **Entonces** el sistema responde con 201 Created, guarda el mensaje y envía una notificación al usuario B. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-24** | API Endpoint para Obtener Historial de una Conversación | Messaging |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/messages/{contactId} **Para** que un usuario pueda ver todos los mensajes intercambiados con un contacto. **Criterios de Aceptación** **Escenario \#1: Cargar historial de chat** **Dado que** el usuario A y el contacto B (contactId=25) han intercambiado mensajes, **Cuando** el usuario A envía una petición GET a /api/messages/25, **Entonces** el sistema responde con 200 OK y un array de todos los mensajes entre ellos, ordenados por fecha. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-25** | API Endpoint para que un Admin vea Locales Pendientes | Admin |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/admin/venues/pending **Para** que un administrador pueda ver todos los locales que necesitan ser validados. **Criterios de Aceptación** **Escenario \#1: Hay locales pendientes** **Dado que** un usuario con rol "Admin" está autenticado, **Cuando** envía una petición GET a /api/admin/venues/pending, **Entonces** el sistema responde con 200 OK y una lista de los locales con estado "pending\_approval". |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-26** | API Endpoint para que un Admin Apruebe o Rechace un Local | Admin |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint PUT /api/admin/venues/{venueId}/status **Para** que un administrador pueda cambiar el estado de un local. **Criterios de Aceptación** **Escenario \#1: Aprobar un local** **Dado que** un local está pendiente de aprobación, **Cuando** un Admin envía una petición PUT a /api/admin/venues/{venueId}/status con { "status": "active" }, **Entonces** el sistema responde con 200 OK y actualiza el estado del local en la base de datos. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-27** | API Endpoint para que un Admin Gestione Reportes | Admin |
| **Descripción** | **Como** Developer, **Quiero** implementar endpoints GET /api/admin/reports y PUT /api/admin/reports/{reportId} **Para** que un admin pueda ver y gestionar los reportes de usuarios. **Criterios de Aceptación** **Escenario \#1: Marcar un reporte como resuelto** **Dado que** un reporte con reportId=33 está abierto, **Cuando** un Admin envía una petición PUT a /api/admin/reports/33 con { "status": "resolved" }, **Entonces** el sistema responde con 200 OK y actualiza el estado del reporte. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-28** | API Endpoint para que un Partner vea sus Analíticas | Analytics |
| **Descripción** | **Como** Developer, **Quiero** implementar un endpoint GET /api/partners/me/analytics **Para** que un Partner pueda ver las métricas de sus locales. **Criterios de Aceptación** **Escenario \#1: Obtener métricas** **Dado que** un Partner está autenticado, **Cuando** envía una petición GET a /api/partners/me/analytics?period=monthly, **Entonces** el sistema responde con 200 OK y un objeto JSON con las métricas relevantes (total de asistentes, calificación promedio, etc.). |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-29** | Servicio de Notificaciones Push/Email | Notifications |
| **Descripción** | **Como** Developer, **Quiero** implementar un servicio de notificaciones desacoplado **Para** que diferentes partes del sistema puedan enviar notificaciones a los usuarios (recordatorios de eventos, mensajes nuevos, etc.). **Criterios de Aceptación** **Escenario \#1: Enviar recordatorio de encuentro** **Dado que** un encuentro está programado para ocurrir en 24 horas, **Cuando** un job programado (cron job) se ejecuta, **Entonces** el job identifica a todos los asistentes confirmados y delega al servicio de notificaciones el envío de un recordatorio a cada uno. |  |

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **TS-30** | Job Programado para Limpiar Tokens Expirados | System |
| **Descripción** | **Como** Developer, **Quiero** implementar un job programado que se ejecute diariamente **Para** eliminar tokens de refresco o de reseteo de contraseña que hayan expirado. **Criterios de Aceptación** **Escenario \#1: Ejecución diaria del job** **Dado que** existen tokens expirados en la base de datos, **Cuando** el job programado se ejecuta a la hora definida, **Entonces** los tokens que han superado su tiempo de vida son eliminados de la base de datos para mantener la higiene del sistema. |  |

# **Spike Stories**

### **Spike: Investigación de Generación y Validación de Códigos QR**

**Contexto**

La plataforma Glottia consta de un backend monolito modular construido con **Java 23 y Spring Boot 3.5.x**, una **aplicación móvil nativa para Android (Kotlin/Java)** para aprendices en su primera versión (y posteriormente Flutter), y un dashboard para partners en **React (orientado a uso móvil)**. El proceso de check-in (US20) es una funcionalidad central del MVP que requiere que un aprendiz presente un código QR desde su app nativa de Android, y que un partner lo valide a través del dashboard accedido desde un dispositivo móvil. Este flujo debe ser rápido, seguro y fiable.

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **SP-01** | **Investigación de Generación y Validación de Códigos QR** | Event |
| **Descripción** | **Como** Developer, **Quiero** investigar y crear un prototipo del flujo de generación y escaneo de códigos QR **Para** validar la viabilidad técnica del proceso de check-in y elegir las librerías adecuadas para nuestro stack tecnológico. **Objetivo de Investigación:** Definir el flujo técnico completo desde que el backend genera un QR para una reserva, hasta que el cliente (React) lo valida, identificando las mejores herramientas (librerías Java para backend, librerías JS para frontend) y los posibles puntos de fallo (ej. condiciones de baja luz, cámaras de baja resolución). **Criterios de Aceptación:** 1\. Un documento que compare al menos dos librerías Java (ej. ZXing, QRGen) para la generación de QR en el servidor. 2\. Un prototipo funcional (Proof of Concept) que consista en: \- Un endpoint de API Spring Boot que genere un QR para una reserva ficticia. \- Una vista **móvil** simple en React que pueda usar la cámara de un dispositivo para escanear el QR y enviar su contenido a otro endpoint de validación. 3\. Documentación con la recomendación técnica final y un diagrama de secuencia del flujo de datos. |  |

### **Spike: Análisis de Estrategias para Notificaciones en Tiempo Real**

**Contexto**

El backend de Glottia (Java 23, Spring Boot 3.5.x) necesita comunicar eventos urgentes a los clientes (la **app nativa de Android** y el dashboard React). Los casos de uso críticos son notificar a un aprendiz en lista de espera cuando un cupo se libera (US24) y alertar sobre nuevos mensajes en el chat (US45). La solución debe ser eficiente y compatible tanto con la **aplicación móvil nativa para Android** como con el dashboard para partners (React), considerando una futura migración a Flutter.

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **SP-02** | **Análisis de Estrategias para Notificaciones en Tiempo Real** | Notifications / Community |
| **Descripción** | **Como** Developer, **Quiero** analizar diferentes tecnologías para notificaciones en tiempo real (WebSockets vs. Servicios de Push Notifications como Firebase Cloud Messaging) **Para** decidir la arquitectura más eficiente y escalable para el stack de Glottia. **Objetivo de Investigación:** Comprender la complejidad de implementación, costos de infraestructura y beneficios de cada enfoque. Evaluar cómo se integra cada solución con Spring Boot en el backend y con Android Nativo/React en los clientes. **Criterios de Aceptación:** 1\. Un documento comparativo detallando pros y contras de WebSockets (ej. con Spring WebSocket) y FCM para nuestro caso de uso. 2\. Una conclusión técnica documentada que recomiende una estrategia para el MVP. 3\. Un prototipo simple que demuestre la recepción de una notificación en un cliente **móvil nativo de Android** y en el dashboard de React al ocurrir un evento en el servidor. |  |

### **Spike: Prueba de Viabilidad de Búsquedas Geoespaciales en PostgreSQL**

**Contexto**

La funcionalidad de búsqueda de encuentros (US15) y el mapa de locales (US28) requieren filtrar por ubicación. El backend utiliza **Spring Boot 3.5.x con Spring Data JPA** y una base de datos **PostgreSQL 16**. Para que la experiencia de usuario sea fluida, las consultas que busquen locales "en una ciudad" o "cerca de mi ubicación" deben tener un rendimiento óptimo, incluso cuando la base de datos crezca a miles de locales.

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **SP-03** | **Prueba de Viabilidad de Búsquedas Geoespaciales** | Event / Partner |
| **Descripción** | **Como** Developer, **Quiero** investigar y probar el rendimiento de las consultas geoespaciales en PostgreSQL **Para** asegurar que la búsqueda de locales y encuentros por cercanía sea rápida y eficiente. **Objetivo de Investigación:** Determinar si es necesaria la extensión **PostGIS** para PostgreSQL. Definir la forma óptima de almacenar coordenadas (latitud/longitud) y estructurar las consultas y los índices de la base de datos. **Criterios de Aceptación:** 1\. Una base de datos de prueba poblada con miles de locales ficticios en diferentes ubicaciones. 2\. Un conjunto de consultas de ejemplo (SQL nativo y/o JPQL) para buscar locales "a X km de un punto" y "dentro de un polígono de ciudad". 3\. Un reporte con los benchmarks de rendimiento de dichas consultas, con y sin índices espaciales (ej. GiST). 4\. Una recomendación final sobre si usar PostGIS en el MVP y la estrategia de indexación a seguir. |  |

### **Spike: Validación del Patrón de Eventos Internos en un Monolito Modular**

**Contexto**

La arquitectura de Glottia es un **monolito modular con Java 23 y Spring Boot 3.5.x**. Para mantener un bajo acoplamiento entre los diferentes módulos (Bounded Contexts), se planea usar **Spring ApplicationEvents** para la comunicación asíncrona. Un ejemplo clave es el flujo de Check-in (módulo Event), que debe notificar al módulo de Loyalty para asignar puntos (US29), sin que el proceso de lealtad retrase la respuesta de la API de check-in.

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **SP-04** | **Validación del Patrón de Eventos Internos (Spring Events)** | System / Loyalty |
| **Descripción** | **Como** Developer, **Quiero** crear un prototipo de la comunicación entre módulos usando Spring ApplicationEvents **Para** validar que el desacoplamiento entre funcionalidades funciona de manera asíncrona y no afecta el rendimiento del request principal. **Objetivo de Investigación:** Asegurar que la comunicación por eventos se beneficie del manejo de transacciones de Spring y que los errores en un "listener" (ej. en el módulo de lealtad) no reviertan la transacción principal (el check-in). **Criterios de Aceptación:** 1\. Un mini-proyecto en Spring Boot con dos servicios (EventService y LoyaltyService) en paquetes separados para simular los módulos. 2\. El EventService publica un evento personalizado (UserCheckedInEvent) al ser llamado. 3\. El LoyaltyService contiene un @EventListener que escucha dicho evento (en modo asíncrono @Async) y simula una operación. 4\. Conclusiones documentadas que expliquen cómo manejar las transacciones (@TransactionalEventListener) y los errores en este flujo asíncrono para garantizar la consistencia de los datos. |  |

### **Spike: Investigación de Optimización de Consultas para el Dashboard de Analíticas**

**Contexto**

El dashboard de partners (desarrollado en **React**) debe presentar varias métricas de negocio, como el número de asistentes por mes (US36) y la proporción de clientes nuevos vs. recurrentes (US39). Estas métricas requieren consultas de agregación complejas sobre las tablas de encounters y attendances en nuestra base de datos **PostgreSQL 16**. El backend **Spring Boot** debe servir estos datos rápidamente sin impactar el rendimiento de las operaciones transaccionales de la aplicación.

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **SP-05** | **Investigación de Optimización de Consultas para Analíticas** | Analytics |
| **Descripción** | **Como** Developer, **Quiero** analizar las mejores estrategias para generar las métricas del dashboard del Partner **Para** garantizar que las consultas de analíticas no sobrecarguen la base de datos y respondan en un tiempo aceptable. **Objetivo de Investigación:** Evaluar y comparar diferentes enfoques: consultas SQL nativas optimizadas con JPQL, el uso de Vistas Materializadas en PostgreSQL para prec-alcular resultados, o una capa de caché (ej. Caffeine) en Spring Boot para los datos agregados. **Criterios de Aceptación:** 1\. Un script SQL que genere datos de prueba masivos (miles de encuentros y asistencias durante un año). 2\. Versiones alternativas de las consultas necesarias para los reportes. 3\. Un documento que compare el rendimiento (tiempo de ejecución), la complejidad de implementación y la "frescura" de los datos de cada enfoque. 4\. Una recomendación final sobre la estrategia a seguir para el MVP. |  |

### **Spike: Análisis de Integración con Pasarela de Pagos Stripe**

**Contexto**

Aunque la monetización es post-MVP, es un riesgo técnico significativo. La plataforma Glottia (**backend Spring Boot 3.5.x, Java 23**) necesitará integrar un sistema de pagos para gestionar suscripciones de partners y, potencialmente, funcionalidades premium para aprendices. Se considera **Stripe** como la principal opción por su robusta API y documentación. La integración debe ser segura, cumplir con los estándares PCI y ser manejada enteramente en el backend.

| Story ID | Título | Epic |
| :---- | :---- | :---- |
| **SP-06** | **Análisis de Integración con Pasarela de Pagos (Stripe)** | Monetization |
| **Descripción** | **Como** Developer, **Quiero** investigar la API de Stripe y crear un prototipo básico de su integración con nuestro backend Spring Boot **Para** entender el esfuerzo, la complejidad y los requerimientos técnicos para implementar las suscripciones. **Objetivo de Investigación:** Mapear el flujo de datos necesario para crear suscripciones, manejar webhooks de pago (para confirmaciones, renovaciones y fallos), y asociar un plan de Stripe a un partner\_profile en nuestra base de datos. **Criterios de Aceptación:** 1\. Un documento que resuma los pasos clave para integrar Stripe Subscriptions, utilizando la librería stripe-java. 2\. Un prototipo funcional que logre: \- Crear un "Customer" en Stripe cuando un Partner se registra. \- Iniciar una sesión de "Stripe Checkout" para un plan de suscripción predefinido. \- Un endpoint en nuestro backend que reciba y valide un webhook de Stripe cuando el pago es exitoso. 3\. Una estimación de esfuerzo más precisa (en Story Points) para las User Stories de monetización del backlog. |  |
---

## Resumen del Proyecto

### Módulos del Sistema
1. **Gestión de Identidad y Acceso (IAM)** - 5 user stories
2. **Perfiles de Usuario (Profiles)** - 4 user stories  
3. **Gestión de Locales (Partner)** - 5 user stories
4. **Gestión de Encuentros (Event)** - 14 user stories
5. **Lealtad y Gamificación (Loyalty)** - 7 user stories
6. **Analíticas (Analytics)** - 5 user stories
7. **Comunidad y Social** - 6 user stories
8. **Administración (Admin)** - 5 user stories

**Total: 51 User Stories**

### Roles del Sistema
- **Aprendiz**: Usuarios que buscan practicar idiomas
- **Partner**: Dueños de locales que ofrecen su espacio
- **Administrador**: Gestores de la plataforma

### Funcionalidades Clave
- Sistema de registro y autenticación diferenciado por roles
- Gestión completa de perfiles de usuario con idiomas y niveles
- Registro y administración de locales para encuentros
- Sistema completo de gestión de eventos con reservas, QR y check-in
- Programa de lealtad con puntos, insignias y rankings
- Analíticas detalladas para partners
- Sistema de mensajería y networking social
- Panel de administración completo
  

### 2.4.2. Impact Mapping
En este sección , el equipo presenta los mapas de impacto realizados

<img src="https://i.postimg.cc/xCn5wTz8/Impact-map-1.png"/>
<img src="https://i.postimg.cc/FztLMTqZ/Impact-map-Carlos-1.png"/>

### 2.4.3. Product Backlog

En esta sección, el equipo organiza el Product Backlog incluyendo Historias de Usuario e Historias Técnicas en base a su valor para el negocio y su peso en Story Points.

| StoryID | Titulo | Descripción | Story Points |
| :---- | :---- | :---- | :---- |
| **US04** | Cierre de sesión | **Como** usuario autenticado **Quiero** poder cerrar mi sesión **Para** proteger la privacidad de mi cuenta en dispositivos compartidos. **Escenario \#1: Cierre de sesión exitoso** **Dado que** un usuario ha iniciado sesión en la plataforma, **Cuando** solicita finalizar su sesión, **Entonces** el sistema termina la sesión activa y lo devuelve a la página de inicio pública. | 1 |
| **US30** | Ver mi total de puntos y nivel | **Como** aprendiz **Quiero** poder ver mi saldo total de puntos y mi nivel actual en mi perfil **Para** seguir mi progreso. **Escenario \#1: Consultar progreso** **Dado que** un aprendiz accede a su perfil, **Cuando** consulta su progreso de lealtad, **Entonces** el sistema le muestra sus puntos totales y su nivel actual. | 1 |
| **US05** | Recuperación de contraseña | **Como** usuario registrado **Quiero** solicitar un enlace para restablecer mi contraseña si la he olvidado **Para** poder recuperar el acceso a mi cuenta. **Escenario \#1: Solicitud de recuperación exitosa** **Dado que** un usuario olvidó su contraseña, **Cuando** proporciona el correo electrónico de su cuenta para la recuperación, **Entonces** el sistema le envía un correo con las instrucciones para crear una nueva contraseña. | 2 |
| **US07** | Editar perfil de aprendiz | **Como** aprendiz **Quiero** poder editar la información de mi perfil en cualquier momento **Para** mantenerla actualizada. **Escenario \#1: Actualización de idiomas** **Dado que** un aprendiz ha mejorado su nivel de inglés, **Cuando** actualiza su nivel de fluidez en su perfil, **Entonces** el sistema guarda los cambios y su perfil público refleja la nueva información. | 2 |
| **US08** | Ver perfil de otro usuario | **Como** aprendiz **Quiero** ver el perfil de otros asistentes a un encuentro **Para** conocer sus idiomas de interés y conectar con ellos. **Escenario \#1: Visualización de perfil público** **Dado que** estoy viendo los detalles de un encuentro, **Cuando** solicito ver el perfil de otro asistente, **Entonces** se me muestra su información pública relevante (foto, nombre, idiomas). | 2 |
| **US09** | Subir foto de perfil | **Como** usuario **Quiero** subir una foto de perfil **Para** personalizar mi cuenta y que otros me reconozcan más fácilmente. **Escenario \#1: Carga de imagen exitosa** **Dado que** estoy gestionando mi perfil, **Cuando** proporciono una nueva imagen para mi perfil, **Entonces** la imagen se actualiza y se muestra en toda la plataforma. | 2 |
| **US13** | Definir consumo mínimo (Opcional) | **Como** Partner **Quiero** tener la opción de definir un consumo mínimo sugerido para los asistentes a encuentros en mi local **Para** asegurar un retorno económico. **Escenario \#1: Establecer consumo mínimo** **Dado que** un Partner desea incentivar el consumo, **Cuando** establece un consumo mínimo sugerido para los encuentros en su local, **Entonces** esta información es visible en los detalles de dichos encuentros. | 2 |
| **US16** | Ver detalles de un encuentro | **Como** aprendiz **Quiero** ver los detalles completos de un encuentro **Para** saber el idioma, el tema, el lugar, la hora y quiénes más asistirán. **Escenario \#1: Acceder a la información del encuentro** **Dado que** un aprendiz ha encontrado un encuentro de su interés, **Cuando** selecciona ese encuentro de la lista, **Entonces** se le presenta toda la información detallada del evento. | 2 |
| **US22** | Recibir recordatorio de encuentro | **Como** aprendiz con una reserva **Quiero** recibir una notificación de recordatorio 24 horas antes del encuentro **Para** no olvidarme de asistir. **Escenario \#1: Notificación automática** **Dado que** un aprendiz tiene una reserva para mañana, **Cuando** faltan 24 horas para el evento, **Entonces** el sistema le envía automáticamente un recordatorio. | 2 |
| **US27** | Ver encuentros pasados | **Como** aprendiz **Quiero** tener un historial de los encuentros a los que he asistido **Para** recordar los lugares y las fechas. **Escenario \#1: Consultar historial** **Dado que** un aprendiz quiere revisar su actividad pasada, **Cuando** consulta su historial de encuentros, **Entonces** el sistema le muestra una lista de todos los eventos en los que participó. | 2 |
| **US43** | Ver mi lista de contactos | **Como** aprendiz **Quiero** tener una lista de todos los usuarios con los que he conectado **Para** poder iniciar una conversación. **Escenario \#1: Acceder a mis conexiones** **Dado que** he establecido contactos en la plataforma, **Cuando** consulto mi lista de contactos, **Entonces** el sistema me muestra todos los usuarios con los que he conectado. | 2 |
| **US01** | Registro de nuevo aprendiz | **Como** una persona interesada en practicar idiomas **Quiero** registrarme en la plataforma con mi correo y contraseña **Para** poder acceder a la comunidad y a los encuentros. **Escenario \#1: Registro exitoso** **Dado que** un nuevo usuario desea unirse a la plataforma, **Cuando** proporciona los datos requeridos para el registro y acepta los términos, **Entonces** el sistema crea su cuenta, le envía una bienvenida y lo guía para completar su perfil. | 3 |
| **US03** | Inicio de sesión general | **Como** usuario registrado (aprendiz o dueño de local) **Quiero** iniciar sesión con mi correo y contraseña **Para** acceder a mis funcionalidades personalizadas. **Escenario \#1: Inicio de sesión exitoso** **Dado que** un usuario registrado desea acceder a su cuenta, **Cuando** proporciona sus credenciales de acceso correctas, **Entonces** el sistema lo autentica y le presenta su panel principal correspondiente. **Escenario \#2: Credenciales incorrectas** **Dado que** un usuario registrado desea acceder a su cuenta, **Cuando** proporciona credenciales incorrectas, **Entonces** el sistema le informa que el acceso ha sido denegado por credenciales inválidas. | 3 |
| **US06** | Completar perfil de aprendiz | **Como** nuevo aprendiz **Quiero** completar mi perfil con mi idioma nativo, los idiomas que quiero practicar y mi nivel **Para** que otros usuarios me conozcan y el sistema me recomiende encuentros relevantes. **Escenario \#1: Primer llenado de perfil** **Dado que** un aprendiz se ha registrado, **Cuando** especifica sus idiomas, su nivel de fluidez y guarda la información, **Entonces** su perfil se actualiza y el sistema utiliza estas preferencias para recomendarle encuentros. | 3 |
| **US11** | Editar información de un local | **Como** Partner **Quiero** poder editar los detalles de mi local registrado **Para** mantener la información actualizada (ej. cambio de horario). **Escenario \#1: Actualizar horario del local** **Dado que** un Partner necesita cambiar el horario de su cafetería, **Cuando** modifica la información del horario en los detalles del local, **Entonces** la nueva información se refleja inmediatamente en la plataforma. | 3 |
| **US12** | Añadir fotos del local | **Como** Partner **Quiero** subir varias fotos de mi local **Para** hacerlo más atractivo y mostrar el ambiente a los aprendices. **Escenario \#1: Cargar galería de fotos** **Dado que** un Partner está gestionando el perfil de su local, **Cuando** proporciona un conjunto de imágenes del establecimiento, **Entonces** las fotos se asocian al perfil del local y se muestran en una galería. | 3 |
| **US15** | Buscar encuentros disponibles | **Como** aprendiz **Quiero** buscar encuentros usando filtros por idioma, ciudad y fecha **Para** encontrar fácilmente una sesión de práctica que me interese. **Escenario \#1: Búsqueda con filtros** **Dado que** un aprendiz quiere encontrar un encuentro, **Cuando** aplica filtros de búsqueda por idioma, ciudad y fecha, **Entonces** el sistema le muestra una lista de resultados que coinciden con sus criterios. | 3 |
| **US21** | Ver lista de asistentes (vista de Partner) | **Como** Partner **Quiero** ver la lista de personas que han reservado para un encuentro en mi local **Para** tener una idea del aforo esperado. **Escenario \#1: Consultar asistentes** **Dado que** un Partner tiene un encuentro programado, **Cuando** consulta los detalles de dicho evento, **Entonces** el sistema le muestra la lista de los aprendices que han confirmado su asistencia. | 3 |
| **US23** | Unirse a la lista de espera | **Como** aprendiz **Quiero** unirme a una lista de espera si un encuentro está lleno **Para** tener la oportunidad de asistir si alguien cancela. **Escenario \#1: Encuentro lleno** **Dado que** un aprendiz desea asistir a un encuentro sin cupos, **Cuando** opta por unirse a la lista de espera, **Entonces** el sistema lo añade a la cola y le notifica su posición. | 3 |
| **US25** | Dejar feedback de un encuentro | **Como** aprendiz que asistió a un encuentro **Quiero** dejar una calificación y un comentario sobre mi experiencia **Para** ayudar a otros usuarios y a los locales. **Escenario \#1: Calificar la experiencia** **Dado que** un aprendiz ha asistido a un encuentro, **Cuando** proporciona una calificación y un comentario sobre el evento, **Entonces** el sistema guarda su feedback y lo asocia al encuentro y al local. | 3 |
| **US26** | Cancelar mi reserva | **Como** aprendiz **Quiero** poder cancelar mi reserva a un encuentro con antelación **Para** liberar mi cupo si no puedo asistir. **Escenario \#1: Cancelación a tiempo** **Dado que** un aprendiz tiene una reserva y no puede asistir, **Cuando** solicita la cancelación de su reserva antes del tiempo límite, **Entonces** su cupo se libera para otros usuarios. | 3 |
| **US32** | Ver mis insignias desbloqueadas | **Como** aprendiz **Quiero** tener una sección en mi perfil donde pueda ver todas las insignias que he ganado **Para** mostrarlas a la comunidad. **Escenario \#1: Galería de logros** **Dado que** un aprendiz ha desbloqueado insignias, **Cuando** visita un perfil (suyo o de otro usuario), **Entonces** puede ver la colección de insignias ganadas. | 3 |
| **US33** | Ver un ranking de usuarios | **Como** aprendiz **Quiero** ver una tabla de clasificación (leaderboard) semanal o mensual **Para** competir de forma amistosa con otros miembros de la comunidad. **Escenario \#1: Consultar el leaderboard** **Dado que** un aprendiz quiere ver su posición en la comunidad, **Cuando** accede a la tabla de clasificación, **Entonces** el sistema le muestra el ranking de usuarios basado en puntos. | 3 |
| **US35** | Mantener una racha de asistencia | **Como** aprendiz **Quiero** que el sistema registre mi racha de asistencia semanal **Para** motivarme a participar de forma consistente. **Escenario \#1: Incrementar la racha** **Dado que** un aprendiz asistió a un encuentro la semana pasada, **Cuando** asiste a otro encuentro esta semana, **Entonces** el sistema incrementa su racha de asistencia y se lo notifica. | 3 |
| **US37** | Ver calificación promedio de mi local | **Como** Partner **Quiero** ver la calificación promedio que los aprendices le han dado a los encuentros realizados en mi local **Para** evaluar la satisfacción del cliente. **Escenario \#1: Métrica de satisfacción** **Dado que** un Partner está en su dashboard, **Cuando** consulta el rendimiento de su local, **Entonces** el sistema le muestra la calificación promedio basada en el feedback de los usuarios. | 3 |
| **US41** | Enviar solicitud de contacto | **Como** aprendiz **Quiero** poder enviar una solicitud de contacto a otra persona con la que interactué en un encuentro **Para** mantener la comunicación. **Escenario \#1: Conectar después de un evento** **Dado que** he interactuado con otro aprendiz en un encuentro, **Cuando** envío una solicitud de contacto a través de su perfil, **Entonces** el sistema notifica al otro usuario de mi solicitud. | 3 |
| **US42** | Aceptar solicitud de contacto | **Como** aprendiz **Quiero** recibir notificaciones de nuevas solicitudes de contacto **Para** poder aceptarlas o rechazarlas. **Escenario \#1: Gestión de solicitudes** **Dado que** he recibido una solicitud de contacto, **Cuando** acepto la solicitud, **Entonces** ambos pasamos a formar parte de nuestras respectivas listas de contactos. | 3 |
| **US02** | Registro de nuevo local | **Como** dueño de un local **Quiero** registrar mi negocio en la plataforma **Para** ofrecer mi espacio para los encuentros y ganar visibilidad. **Escenario \#1: Registro de local exitoso** **Dado que** el dueño de un local desea unirse a la plataforma, **Cuando** proporciona la información de su cuenta y los datos de su negocio, **Entonces** el sistema crea una cuenta de tipo "Partner", la asocia al local y le concede acceso al panel de gestión. | 5 |
| **US10** | Dar de alta un nuevo local | **Como** dueño de negocio (Partner) **Quiero** añadir los detalles de mi local, incluyendo nombre, dirección, aforo y horario **Para** que aparezca en la plataforma como un lugar disponible para encuentros. **Escenario \#1: Registro de información del local** **Dado que** un Partner desea añadir un nuevo local, **Cuando** proporciona toda la información requerida del establecimiento y la guarda, **Entonces** el local se añade a su perfil y se vuelve visible en la plataforma. | 5 |
| **US14** | Ver dashboard de mi local | **Como** Partner **Quiero** ver un dashboard con un resumen de la actividad en mi local **Para** entender rápidamente cuántos encuentros se han realizado y cuántas personas han asistido. **Escenario \#1: Visualización de métricas clave** **Dado que** un Partner accede a su panel, **Cuando** solicita ver el resumen de actividad, **Entonces** se le presentan las métricas clave de sus locales (encuentros, asistentes, calificación). | 5 |
| **US17** | Reservar un cupo en un encuentro | **Como** aprendiz **Quiero** reservar mi cupo en un encuentro que tenga plazas disponibles **Para** asegurar mi asistencia. **Escenario \#1: Reserva exitosa** **Dado que** un aprendiz está viendo un encuentro con cupos disponibles, **Cuando** confirma su deseo de reservar un cupo, **Entonces** el sistema procesa su reserva, actualiza los cupos y le envía una notificación. | 5 |
| **US18** | Recibir confirmación con código QR | **Como** aprendiz **Quiero** recibir una confirmación de mi reserva que incluya un código QR **Para** poder hacer check-in fácilmente al llegar al local. **Escenario \#1: Generación de QR tras reserva** **Dado que** un aprendiz ha completado una reserva, **Cuando** consulta los detalles de su reserva, **Entonces** el sistema le proporciona un código QR único para el check-in. | 5 |
| **US24** | Recibir notificación de cupo liberado | **Como** aprendiz en una lista de espera **Quiero** recibir una notificación inmediata si un cupo se libera **Para** poder reservarlo rápidamente. **Escenario \#1: Alguien cancela** **Dado que** un aprendiz está en una lista de espera y se libera un cupo, **Cuando** le llega su turno, **Entonces** el sistema le envía una notificación para que pueda confirmar su asistencia en un tiempo limitado. | 5 |
| **US28** | Ver el mapa de locales | **Como** aprendiz **Quiero** ver un mapa con la ubicación de todos los locales registrados **Para** descubrir lugares cercanos donde se organizan encuentros. **Escenario \#1: Exploración geográfica** **Dado que** un aprendiz quiere descubrir nuevos locales, **Cuando** explora la vista de mapa, **Entonces** el sistema le muestra la ubicación de todos los locales aliados. | 5 |
| **US29** | Ganar puntos por asistencia | **Como** aprendiz **Quiero** ganar puntos de lealtad cada vez que hago check-in en un encuentro **Para** ser recompensado por mi participación activa. **Escenario \#1: Acumulación de puntos** **Dado que** un aprendiz ha hecho check-in exitosamente en un evento, **Cuando** el sistema procesa su asistencia, **Entonces** automáticamente se suman los puntos correspondientes a su cuenta. | 5 |
| **US31** | Desbloquear una insignia (badge) | **Como** aprendiz **Quiero** desbloquear insignias al alcanzar ciertos hitos (ej. "Asistir a 5 encuentros de francés") **Para** sentir que logro algo. **Escenario \#1: Desbloqueo de insignia por asistencia** **Dado que** un aprendiz ha cumplido los requisitos para una insignia, **Cuando** el sistema verifica el hito, **Entonces** le otorga la insignia correspondiente y le muestra una notificación. | 5 |
| **US34** | Recibir ofertas de locales por lealtad | **Como** aprendiz leal **Quiero** recibir ofertas especiales o descuentos de los locales asociados **Como** recompensa por mi participación. **Escenario \#1: Recompensa de un Partner** **Dado que** un aprendiz ha alcanzado un nivel de lealtad alto, **Cuando** un local ofrece una recompensa para ese nivel, **Entonces** el aprendiz recibe una notificación con la oferta especial. | 5 |
| **US36** | Ver número de asistentes por mes | **Como** Partner **Quiero** ver un gráfico con el número total de asistentes a encuentros en mi local cada mes **Para** medir el impacto de la plataforma. **Escenario \#1: Reporte mensual de asistencia** **Dado que** un Partner está en su panel de analíticas, **Cuando** consulta el reporte de asistencia mensual, **Entonces** el sistema le presenta un gráfico con los datos de asistencia por mes. | 5 |
| **US40** | Descargar reporte básico | **Como** Partner **Quiero** poder descargar un resumen de mis analíticas en formato PDF o CSV **Para** mis registros internos. **Escenario \#1: Exportar datos** **Dado que** un Partner necesita un informe de su actividad, **Cuando** solicita la descarga del reporte de analíticas, **Entonces** el sistema genera un archivo con los datos del período seleccionado. | 5 |
| **US44** | Enviar mensaje a un contacto | **Como** aprendiz **Quiero** poder enviar un mensaje directo a uno de mis contactos **Para** organizar una futura práctica de idiomas. **Escenario \#1: Iniciar una conversación** **Dado que** deseo comunicarme con un contacto, **Cuando** le envío un mensaje privado, **Entonces** el sistema entrega el mensaje y le notifica al destinatario. | 5 |
| **US45** | Recibir notificaciones de mensajes nuevos | **Como** usuario **Quiero** recibir una notificación cuando uno de mis contactos me envía un mensaje **Para** poder responder a tiempo. **Escenario \#1: Alerta de mensaje** **Dado que** estoy usando la aplicación, **Cuando** recibo un nuevo mensaje de un contacto, **Entonces** el sistema me alerta de la notificación. | 5 |
| **US46** | Reportar un usuario | **Como** usuario **Quiero** tener la opción de reportar a otro usuario por comportamiento inapropiado **Para** mantener un ambiente seguro y respetuoso en la comunidad. **Escenario \#1: Denunciar comportamiento** **Dado que** he presenciado un comportamiento inapropiado, **Cuando** envío un reporte sobre un usuario especificando el motivo, **Entonces** el sistema envía el reporte a los administradores para su revisión. | 5 |
| **US48** | Gestionar usuarios | **Como** administrador **Quiero** poder ver la lista de todos los usuarios y poder desactivar una cuenta en caso de abuso **Para** mantener la calidad de la comunidad. **Escenario \#1: Desactivar una cuenta** **Dado que** se ha verificado un reporte de abuso, **Cuando** el administrador ejecuta la acción de desactivar la cuenta del infractor, **Entonces** el usuario ya no puede acceder a la plataforma. | 5 |
| **US49** | Validar nuevos locales | **Como** administrador **Quiero** tener un proceso para validar y aprobar los nuevos locales que se registran **Para** asegurar que son lugares apropiados y reales. **Escenario \#1: Aprobación de local** **Dado que** un nuevo local está pendiente de aprobación, **Cuando** el administrador verifica y aprueba la solicitud, **Entonces** el local se activa y se hace visible públicamente en la plataforma. | 5 |
| **US19** | Crear un encuentro (iniciativa del aprendiz) | **Como** aprendiz **Quiero** proponer la creación de un nuevo encuentro en un local registrado **Para** organizar una sesión si no hay ninguna que se ajuste a mis necesidades. **Escenario \#1: Proponer nuevo encuentro** **Dado que** un aprendiz desea organizar un encuentro, **Cuando** proporciona los detalles del nuevo evento (local, fecha, idioma), **Entonces** el sistema crea el encuentro, lo registra como el primer asistente y lo hace visible para otros usuarios. | 8 |
| **US20** | Check-in en un encuentro | **Como** aprendiz **Quiero** hacer check-in al llegar al encuentro mostrando mi código QR **Para** confirmar mi asistencia y ganar puntos de lealtad. **Escenario \#1: Check-in exitoso por parte del local** **Dado que** un aprendiz llega al local del encuentro, **Cuando** su código QR es validado por el organizador, **Entonces** el sistema registra su asistencia y le asigna los puntos correspondientes. | 8 |
| **US38** | Identificar horas y días pico | **Como** Partner **Quiero** ver un reporte que me muestre qué días de la semana y a qué horas se realizan más encuentros en mi local **Para** optimizar mi personal. **Escenario \#1: Mapa de calor de actividad** **Dado que** un Partner quiere conocer sus horas más populares, **Cuando** consulta el reporte de horas pico, **Entonces** el sistema le presenta una visualización de los días y horas con mayor actividad. | 8 |
| **US39** | Rastrear asistentes nuevos vs. recurrentes | **Como** Partner **Quiero** saber qué porcentaje de los asistentes son nuevos clientes versus personas que ya han venido antes **Para** medir la captación de nuevo público. **Escenario \#1: Reporte de retención** **Dado que** un Partner está analizando sus métricas, **Cuando** consulta el reporte de clientes, **Entonces** el sistema le muestra la proporción de asistentes nuevos vs. recurrentes. | 8 |
| **US47** | Ver dashboard de administrador | **Como** administrador de la plataforma **Quiero** acceder a un dashboard con métricas generales de uso **Para** monitorear la salud del servicio. **Escenario \#1: Vista general del sistema** **Dado que** un administrador ha iniciado sesión, **Cuando** accede al panel de administración, **Entonces** el sistema le presenta las métricas clave de la plataforma. | 8 |
| **US50** | Gestionar reportes de usuarios | **Como** administrador **Quiero** ver una lista de todos los reportes enviados por los usuarios **Para** poder investigarlos y tomar acciones. **Escenario \#1: Revisar una denuncia** **Dado que** un usuario ha sido reportado, **Cuando** el administrador consulta los reportes pendientes, **Entonces** puede ver todos los detalles de la denuncia para su investigación. | 8 |
| **US51** | Enviar comunicaciones globales | **Como** administrador **Quiero** poder enviar notificaciones o correos electrónicos a todos los usuarios **Para** comunicar novedades o mantenimientos de la plataforma. **Escenario \#1: Anuncio de nueva funcionalidad** **Dado que** se necesita comunicar una novedad a todos los usuarios, **Cuando** el administrador envía una comunicación global, **Entonces** todos los usuarios registrados reciben la notificación. | 8 |


## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming

El EventStorming es una técnica de brainstorming colaborativa y visual que se utiliza en el desarrollo de software, especialmente en el contexto de Domain-Driven Design (DDD). Su objetivo principal es ayudar a un equipo a entender y modelar un dominio de negocio complejo, identificando los eventos de dominio que ocurren en él. A continuación el equipo presenta el diseño del EventStorming.

![EventStorming](https://github.com/user-attachments/assets/7b4f333f-54bf-4ed7-abc0-a3d2c33a3238)

#### 2.5.1.1. Candidate Context Discovery
|     <b>Contexto Candidato</b>        |                         <b>Eventos Principales</b>                          |            <b>Responsable(s)</b>               |                  <b>Riesgos Asociados</b>                               |
|:------------------------------------:|:---------------------------------------------------------------------------:|:----------------------------------------:|:---------------------------------------------------------------:|
|     User Identity & Trust            |Usuario se registra, valida identidad, obtiene insignias de confianza        |Usuario aprendiz, sistema de verificación |Suplantación de identidad, baja confianza en la comunidad          |
|     Language Exchange Session        |Creación de sesión, emparejamiento de aprendices, confirmación de asistencia |Usuario aprendiz, app Glottia |Cancelaciones frecuentes, baja asistencia                          |
|     Venue Partnership                |Registro de local asociado, disponibilidad de espacios, reseñas de usuarios  |Administradores de locales, sistema      |Baja atracción de clientes, incumplimiento de condiciones del local|
|     Learning Progress & Gamification |Registro de participación, asignación de puntos, logros desbloqueados        |Usuario aprendiz, sistema                |Desmotivación si no hay recompensas claras                         |
|     Community & Cultural Exchange    |Publicación de normas, moderación de interacciones, actividades culturales   |Comunidad Glottia, moderadores           |Conductas inapropiadas, ambiente inseguro                          |

#### 2.5.1.2. Domain Message Flows Modeling
| Flujo              | Contexto Origen                 | Mensaje/Event / Comando         | Contexto Destino                  | Resultado                                                                 |
|--------------------|---------------------------------|---------------------------------|-----------------------------------|---------------------------------------------------------------------------|
| Registro y Confianza | User Identity & Trust           | Evento: Usuario verificado       | Community & Cultural Exchange      | El usuario obtiene acceso completo a la comunidad y puede participar en eventos. |
| Reserva de Sesión  | Language Exchange Session        | Evento: Sesión creada            | Venue Partnership                  | Se notifica al local asociado que habrá un encuentro y se bloquea el espacio. |
| Matchmaking        | Language Exchange Session        | Comando: Emparejar aprendiz      | User Identity & Trust              | El sistema consulta idioma, nivel y disponibilidad antes de asignar compañero. |
| Gamificación       | Learning Progress & Gamification | Evento: Logro desbloqueado       | Community & Cultural Exchange      | El sistema muestra insignias y motiva la participación en próximos eventos. |
| Calificación       | Community & Cultural Exchange    | Evento: Reseña creada            | Venue Partnership + User Identity & Trust | Se actualiza la reputación tanto del local como del usuario anfitrión. |

#### 2.5.1.3. Bounded Context Canvases
![The Bounded Context Canvas - User Identity & Trust](https://github.com/user-attachments/assets/e09a500e-4a55-4de6-96b1-dfc7caa8d66b)
![The Bounded Context Canvas - Language Exchange Session](https://github.com/user-attachments/assets/85ad1409-3898-49e8-84a9-66997d43f9cf)
![The Bounded Context Canvas - Venue Partnership](https://github.com/user-attachments/assets/0cf487fe-5c39-44fb-a258-67e4ead8b580)
![The Bounded Context Canvas - Learning Progress & Gamification](https://github.com/user-attachments/assets/1acfc8b3-5f61-42a7-b6ab-c547db50bcba)
![The Bounded Context Canvas -Community & Cultural Exchange](https://github.com/user-attachments/assets/2331ded6-8caa-4cad-ad35-6986b841b618)
### 2.5.2. Context Mapping
## Relaciones entre Contextos

| Contexto Origen                 | Relación (DDD)      | Contexto Destino                | Descripción                                                                 |
|---------------------------------|----------------------|----------------------------------|-----------------------------------------------------------------------------|
| User Identity & Trust            | Supplier             | Community & Cultural Exchange    | La verificación de usuario habilita acceso y confianza en la comunidad.     |
| User Identity & Trust            | Supplier             | Language Exchange Session        | Los datos de idioma y nivel alimentan el proceso de matchmaking.            |
| User Identity & Trust            | Shared Kernel        | Venue Partnership                | Se comparten datos básicos de reputación y verificación de usuarios.        |
| Language Exchange Session        | Partnership          | Venue Partnership                | Una sesión programada bloquea espacio en un local asociado.                 |
| Language Exchange Session        | Customer             | User Identity & Trust            | Consulta disponibilidad y nivel de idioma de los usuarios.                  |
| Learning Progress & Gamification | Supplier             | Community & Cultural Exchange    | Los logros desbloqueados se publican en la comunidad para motivar.          |
| Community & Cultural Exchange    | Supplier             | Venue Partnership                | Las reseñas de usuarios impactan en la reputación de los locales.           |
| Community & Cultural Exchange    | Supplier             | User Identity & Trust            | Actualiza la reputación del usuario anfitrión con base en reseñas.          |

## Notas
- **User Identity & Trust** es el **núcleo**, provee información confiable a los demás contextos.  
- **Language Exchange Session** y **Venue Partnership** funcionan en **partnership**, porque ambos dependen mutuamente para habilitar encuentros.  
- **Community & Cultural Exchange** es un **hub**, recibe y redistribuye información (reseñas, logros).  
- **Learning Progress & Gamification** es un **supplier secundario**, motiva con logros que alimentan a la comunidad.
- 
### 2.5.3. Software Architecture

La arquitectura de Glottia se ha modelado siguiendo el modelo C4, que permite visualizar el sistema en diferentes niveles de abstracción. Esto facilita la comprensión de la estructura, las responsabilidades y las interacciones tanto para perfiles técnicos como no técnicos. Los niveles que se detallan a continuación son: Contexto (Nivel 1), Contenedores (Nivel 2) y Componentes (Nivel 3).

- Nivel 1 (Contexto): Muestra el sistema como una caja negra, enfocándose en sus interacciones con los usuarios y otros sistemas externos.

- Nivel 2 (Contenedores): Descompone el sistema en sus elementos desplegables de alto nivel, como aplicaciones cliente, APIs y bases de datos.

- Nivel 3 (Componentes): Detalla los componentes internos de un contenedor específico, en este caso, los Bounded Contexts que conforman el API Backend.

#### 2.5.3.1. Software Architecture Context Level Diagrams

Este diagrama ofrece una visión general del ecosistema de Glottia. Muestra a los actores principales (usuarios) y los sistemas externos con los que Glottia debe interactuar para cumplir sus objetivos.

> [!IMPORTANT]
> Descripción de Interacciones:
> 
> - **Aprendiz**: Utiliza Glottia para buscar, reservar y participar en encuentros de idiomas, así como para gestionar su perfil y progreso.
> - **Local Aliado**: Usa la plataforma para registrar sus establecimientos, gestionar la disponibilidad, crear eventos y consultar analíticas de rendimiento.
> - **Administrador**: Supervisa y gestiona el sistema, los usuarios y los locales aliados para asegurar el correcto funcionamiento de la plataforma.
> - **Sistema de Email**: Es utilizado por Glottia para enviar notificaciones transaccionales, como confirmaciones de registro, recordatorios de eventos y recuperación de contraseñas.
> - **Stripe**: Se integra con Glottia (post-MVP) para procesar los pagos de las suscripciones de los locales y las funcionalidades premium para los aprendices.

<img src = "https://i.postimg.cc/J4NmY9xS/structurizr-System-Context-1.png"/>

#### 2.5.3.2. Software Architecture Container Level Diagrams

Este diagrama desglosa el sistema Glottia en sus contenedores principales. Un contenedor representa una unidad desplegable o ejecutable, como una aplicación móvil, landing page, API web o base de datos. Muestra cómo se distribuyen las responsabilidades del sistema entre estos contenedores.

> [!IMPORTANT]
> Descripción de Contenedores:
> 
> - **Aplicación Móvil**: Construida en Flutter y Android Native, es la interfaz principal para los Aprendices. Permite buscar eventos, reservar, hacer check-in y gestionar el perfil. Se comunica con el API Backend.
> - **Aplicación de Página Única (SPA)**: Un dashboard desarrollado en React para los Locales Aliados y Administradores. Ofrece herramientas para gestionar locales, eventos y visualizar analíticas.  También consume el API Backend.
> - **API Backend**: El núcleo del sistema. Un monolito modular desarrollado en Java/Spring Boot que contiene toda la lógica de negocio, gestiona los datos y se comunica con sistemas externos.
> - **Base de Datos**: Un servidor PostgreSQL que persiste toda la información del sistema, organizada en esquemas lógicos, uno por cada Bounded Context.

<img src = "https://i.postimg.cc/BnmrdsK7/structurizr-Containers.png" />

#### 2.5.3.3. Software Architecture Deployment Diagrams

Este diagrama detalla la arquitectura interna del contenedor API Backend. Cada componente corresponde a uno de los Bounded Contexts definidos en tu documentación. Muestra cómo estos componentes colaboran para implementar la lógica de negocio, comunicándose a través de eventos internos de Spring (`ApplicationEvents`) como especificaste.

> [!IMPORTANT]
> Descripción de Componentes (Bounded Contexts):
> 
> - **Identity & Access Management (IAM)**: Gestiona el registro, login (JWT) y roles. Es el punto de entrada para la autenticación.
> - **Profiles & Preferences Management**: Administra los perfiles de usuario, sus idiomas y disponibilidad.
> - **Partner - Venues Management**: Responsable del ciclo de vida de los locales aliados y sus espacios.
> - **Meeting Management**: Componente central que gestiona la creación, reserva y check-in de los encuentros. Orquesta interacciones con otros componentes.
> - **Loyalty & Engagement**: Gestiona la lógica de gamificación, como puntos y badges, reaccionando a eventos de check-in.
> - **Analytics - Dashboard & KPI's**: Recopila y procesa métricas de negocio para los dashboards de los locales.

<img src="https://i.postimg.cc/jjCpT96x/structurizr-Components.png" />

<br>

## 2.6. Tactical-Level Domain-Driven Design
## 2.6. Tactical-Level Domain-Driven Design
Esta sección describe el diseño táctico basado en DDD, detallando cómo se estructuran los diferentes Bounded Contexts de la plataforma. Incluye la organización de las capas de dominio, aplicación, infraestructura e interfaz, así como los diagramas que facilitan la comprensión técnica y funcional del sistema.

### 2.6.1. Bounded Context: Identity & Access Management
Esta sección describe la arquitectura y los componentes clave del contexto de gestión de identidad y acceso. Se detallan las entidades, servicios y repositorios necesarios para el registro, autenticación y administración de roles de usuario, asegurando la seguridad y el control de acceso en la plataforma.
#### 2.6.1.1. Domain Layer
| Class / Interface | Type      | Responsability                                       |
| ----------------- | --------- | ---------------------------------------------------- |
| User              | Entity    | Root aggregate: unique email, role, password hash    |
| Role              | Enum      | USER, PARTNER, ADMIN                                 |
| Credential        | VO        | Wraps email + hashed password; enforces format rules |
| UserRepository    | Interface | Persistence port (load/save/exists)                  |

Business rules
- Email debe de ser único (repository enforces).
- Password ≥ 8 chars, 1 uppercase, 1 digit (Credential VO).
- Solo un ADMIN puede crear otro adming (domain service).

#### 2.6.1.2. Interface Layer
| Component                | Technology  | Responsibility                     |
| ------------------------ | ----------- | ---------------------------------- |
| AuthenticationController | Spring REST | POST /auth/register & /auth/login  |
| UserController           | Spring REST | GET /users/{id}, PATCH /users/{id} |
| RoleController           | Spring REST | GET /roles, PUT /users/{id}/role   |


#### 2.6.1.3. Application Layer

| Component                    | Type     | Responsibility                                |
| ---------------------------- | -------- | --------------------------------------------- |
| AuthenticationCommandService | @Service | Handles RegisterCommand, emits UserRegistered |
| AuthenticationQueryService   | @Service | Login flow, token generation                  |
| UserCommandService           | @Service | Change email, deactivate, assign role         |
| UserQueryService             | @Service | Read models for users & roles                 |



#### 2.6.1.4. Infrastructure Layer
| Component           | Type        | Responsibility            |
| ------------------- | ----------- | ------------------------- |
| UserRepository      | Interface   | Port outward              |
| RoleRepository      | Interface   | Port outward              |
| BCryptHasherAdapter | @Component  | Password hashing (BCrypt) |
| UserJpaRepository   | Spring-Data | Implements UserRepository |
| RoleJpaRepository   | Spring-Data | Implements RoleRepository |


#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams
Esta sección presenta diagramas a nivel de componentes que ilustran la arquitectura interna de cada Bounded Context. Los diagramas muestran cómo se organizan y relacionan los principales módulos y servicios dentro del contexto, facilitando la comprensión de la estructura y las interacciones técnicas clave.

[![IAMCD.png](https://i.postimg.cc/8P8k01D7/IAMCD.png)](https://postimg.cc/6T0N7x8K)
<br>

#### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

##### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams
Aquí se incluyen los diagramas de clases de la capa de dominio para cada Bounded Context. Estos diagramas detallan las entidades, objetos de valor y agregados principales, así como sus relaciones, proporcionando una visión clara del modelo de dominio y su lógica central.

<img src="https://i.postimg.cc/8P8k01D7/IAMCD.png">

##### 2.6.1.6.2. Bounded Context Database Design Diagram
En esta sección se muestran los diagramas de diseño de base de datos correspondientes a cada Bounded Context. Los diagramas reflejan la estructura de las tablas, claves y relaciones, sirviendo como referencia para la implementación y el mantenimiento de la persistencia de datos.

<br>

[![iam.jpg](https://i.postimg.cc/PqfGPqsF/iam.jpg)](https://postimg.cc/WdyYyT4M)


### 2.6.2. Bounded Context: Profiles & Preferences Management
Aquí se presenta el diseño del contexto encargado de la administración de perfiles de usuario, incluyendo idiomas y disponibilidad. Se explican las reglas de negocio, los servicios de aplicación y los componentes de infraestructura que permiten a los usuarios personalizar su experiencia y gestionar su información personal.

#### 2.6.2.1. Domain Layer
| Artefact          | Type      | Responsibility                      |
| ----------------- | --------- | ----------------------------------- |
| Profile           | Aggregate | Root; owns languages & availability |
| Language          | VO        | ISO-639-1 code + name               |
| AvailabilitySlot  | VO        | day-of-week + start/end time        |
| ProfileRepository | Interface | Port outward                        |

Rules
- One profile per user (userId unique).
- Slots must not overlap (validated in Profile).

#### 2.6.2.2. Interface Layer
| Component         | Responsibility                                                     |
| ----------------- | ------------------------------------------------------------------ |
| ProfileController | GET /profiles, PUT /profiles, PATCH /profiles/{id}/languages, etc. |

#### 2.6.2.3. Application Layer
| Component             | Responsibility                                   |
| --------------------- | ------------------------------------------------ |
| ProfileCommandService | Create / update profile, languages, availability |
| ProfileQueryService   | Read profile, list profiles by language, etc.    |


#### 2.6.2.4. Infrastructure Layer
| Component            | Responsibility             |
| -------------------- | -------------------------- |
| ProfileRepository    | Port                       |
| ProfileJpaRepository | Spring-Data implementation |
| ProfileMapper        | Map Entity ↔ JPA           |


#### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams
Esta sección presenta diagramas a nivel de componentes que ilustran la arquitectura interna de cada Bounded Context. Los diagramas muestran cómo se organizan y relacionan los principales módulos y servicios dentro del contexto, facilitando la comprensión de la estructura y las interacciones técnicas clave.
<img src="https://i.postimg.cc/C1rjCRfr/Profiles.png">
<br>

#### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams
Aquí se incluyen los diagramas de clases de la capa de dominio para cada Bounded Context. Estos diagramas detallan las entidades, objetos de valor y agregados principales, así como sus relaciones, proporcionando una visión clara del modelo de dominio y su lógica central.

<img src="https://i.postimg.cc/j5mqKT7k/Profiles-CD.png">

##### 2.6.2.6.2. Bounded Context Database Design Diagram
En esta sección se muestran los diagramas de diseño de base de datos correspondientes a cada Bounded Context. Los diagramas reflejan la estructura de las tablas, claves y relaciones, sirviendo como referencia para la implementación y el mantenimiento de la persistencia de datos.

[![profiles.jpg](https://i.postimg.cc/bNbf5M9L/profiles.jpg)](https://postimg.cc/ykVGgL5S)

### 2.6.3. Bounded Context: Partner & Venue Management 
Esta sección aborda la estructura y los procesos para la gestión de partners (locales aliados) y sus espacios. Se describen los artefactos principales, los controladores y los servicios que permiten registrar, activar y administrar locales, así como gestionar la relación entre partners y sus venues.

#### 2.6.3.1. Domain Layer
| Artefact         | Responsibility                                                                     |
| ---------------- | ---------------------------------------------------------------------------------- |
| Partner          | Aggregate root; owns venues, manages activation                                    |
| Venue            | Entity; belongs to one partner; has capacity, min. consumption, availability slots |
| MembershipStatus | Enum: PENDING / ACTIVE / SUSPENDED                                                 |


#### 2.6.3.2. Interface Layer
| Component         | Responsibility                                |
| ----------------- | --------------------------------------------- |
| PartnerController | POST /partners, PATCH /partners/{id}/activate |
| VenueController   | POST /venues, PUT /venues/{id}                |


#### 2.6.3.3. Application Layer
| Component             | Responsibility                      |
| --------------------- | ----------------------------------- |
| PartnerCommandService | Register partner, activate, suspend |
| PartnerQueryService   | Get partner, list venues            |
| VenueCommandService   | Add venue, update details           |
| VenueQueryService     | Get venue, list by partner          |

#### 2.6.3.4. Infrastructure Layer
| Component            | Responsibility   |
| -------------------- | ---------------- |
| PartnerRepository    | Port             |
| VenueRepository      | Port             |
| PartnerJpaRepository | Spring-Data impl |
| VenueJpaRepository   | Spring-Data impl |

#### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams
Esta sección presenta diagramas a nivel de componentes que ilustran la arquitectura interna de cada Bounded Context. Los diagramas muestran cómo se organizan y relacionan los principales módulos y servicios dentro del contexto, facilitando la comprensión de la estructura y las interacciones técnicas clave.

<img src="https://i.postimg.cc/4dx6h6nh/Partner.png">

#### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams
Aquí se incluyen los diagramas de clases de la capa de dominio para cada Bounded Context. Estos diagramas detallan las entidades, objetos de valor y agregados principales, así como sus relaciones, proporcionando una visión clara del modelo de dominio y su lógica central.

<img src="https://i.postimg.cc/V6ds3vdC/Partner-CD.png">

##### 2.6.3.6.2. Bounded Context Database Design Diagram
En esta sección se muestran los diagramas de diseño de base de datos correspondientes a cada Bounded Context. Los diagramas reflejan la estructura de las tablas, claves y relaciones, sirviendo como referencia para la implementación y el mantenimiento de la persistencia de datos.

[![venue.jpg](https://i.postimg.cc/RC2zX9KN/venue.jpg)](https://postimg.cc/dDRXVbWY)

### 2.6.4. Bounded Context: Encounter Management
En esta sección se detalla el contexto responsable de la creación, reserva y control de asistencia a los encuentros. Se incluyen los modelos de dominio, los flujos de reserva y check-in, la gestión de listas de espera y los componentes técnicos que soportan estas funcionalidades.

#### 2.6.4.1. Domain Layer
| Artefact      | Responsibility                                           |
| ------------- | -------------------------------------------------------- |
| Encounter     | Aggregate root; manages seats, wait-list, check-in rules |
| Attendance    | Entity; seat reservation state machine                   |
| WaitListEntry | Entity; position inside wait-list                        |
| QRCode        | Value-Object; encodes encounterId + userId               |

#### 2.6.4.2. Interface Layer
| Component            | Technology  | Responsibility                                                                                                                    |
| -------------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------- |
| EncounterController  | Spring REST | `POST /encounters` crear, `GET /encounters` búsqueda con filtros, `PATCH /encounters/{id}/join`, `POST /encounters/{id}/check-in` |
| AttendanceController | Spring REST | `GET /attendances/{encounterId}` lista de asistentes, `PATCH /attendances/{id}/cancel` cancelar reserva                           |
| WaitListController   | Spring REST | `POST /wait-lists` unirse a lista de espera, `PATCH /wait-lists/{id}/accept` aceptar promoción                                    |

#### 2.6.4.3. Application Layer
| Component                | Type     | Responsibility                                                          |
| ------------------------ | -------- | ----------------------------------------------------------------------- |
| EncounterCommandService  | @Service | Orquesta JoinEncounterCommand, CancelReservationCommand, CheckInCommand |
| EncounterQueryService    | @Service | Orquesta SearchEncountersQuery, GetEncounterQuery                       |
| AttendanceCommandService | @Service | CancelAttendanceCommand, MarkAttendedCommand                            |
| AttendanceQueryService   | @Service | ListAttendancesQuery, GetAttendanceQuery                                |
| WaitListCommandService   | @Service | JoinWaitListCommand, AcceptPromotionCommand, DeclinePromotionCommand    |
| WaitListQueryService     | @Service | GetWaitListQuery, GetPositionQuery                                      |


#### 2.6.4.4. Infrastructure Layer
| Component               | Type        | Responsibility                               |
| ----------------------- | ----------- | -------------------------------------------- |
| EncounterRepository     | Interface   | Port outward – load/save Encounter aggregate |
| AttendanceRepository    | Interface   | Port outward – load/save Attendance          |
| WaitListRepository      | Interface   | Port outward – load/save WaitListEntry       |
| EncounterJpaRepository  | Spring-Data | Implements EncounterRepository               |
| AttendanceJpaRepository | Spring-Data | Implements AttendanceRepository              |
| WaitListJpaRepository   | Spring-Data | Implements WaitListRepository                |
| QRGeneratorAdapter      | @Component  | Generates QR code bytes for check-in         |


#### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams
Esta sección presenta diagramas a nivel de componentes que ilustran la arquitectura interna de cada Bounded Context. Los diagramas muestran cómo se organizan y relacionan los principales módulos y servicios dentro del contexto, facilitando la comprensión de la estructura y las interacciones técnicas clave.

<img src="https://i.postimg.cc/fy6mF1Cx/Encounter.png">

#### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams
Aquí se incluyen los diagramas de clases de la capa de dominio para cada Bounded Context. Estos diagramas detallan las entidades, objetos de valor y agregados principales, así como sus relaciones, proporcionando una visión clara del modelo de dominio y su lógica central.
<img src="https://i.postimg.cc/65d6sD5Y/Encounter-CD.png">

##### 2.6.4.6.2. Bounded Context Database Design Diagram
En esta sección se muestran los diagramas de diseño de base de datos correspondientes a cada Bounded Context. Los diagramas reflejan la estructura de las tablas, claves y relaciones, sirviendo como referencia para la implementación y el mantenimiento de la persistencia de datos.

<img src="https://i.postimg.cc/sg4djh8h/encounters.jpg">


### 2.6.5. Bounded Context: Loyalty and Engagement 
Esta sección explica el sistema de lealtad y gamificación, que incentiva la participación de los usuarios mediante puntos e insignias. Se describen los artefactos de dominio, los servicios de aplicación y los mecanismos de integración con otros contextos para otorgar recompensas y reconocer logros.

#### 2.6.5.1. Domain Layer
| Artefact             | Responsibility                            |
| -------------------- | ----------------------------------------- |
| LoyaltyAccount       | Aggregate root; points & badge collection |
| Badge                | Entity; achievement definition            |
| CheckInEventListener | Event handler (in application layer)      |


#### 2.6.5.2. Interface Layer
| Component                | Responsibility                                                              |
| ------------------------ | --------------------------------------------------------------------------- |
| LoyaltyAccountController | `GET /loyalty-accounts/{userId}`, `PATCH /loyalty-accounts/{userId}/points` |
| BadgeController          | `GET /badges`, `GET /badges/{id}`, `POST /badges` (admin)                   |

#### 2.6.5.3. Application Layer
| Component                    | Responsibility                                                                                            |
| ---------------------------- | --------------------------------------------------------------------------------------------------------- |
| CheckInEventListener         | @EventListener – listens to PractitionerCheckedInEvent and calls LoyaltyAccountCommandService.addPoints() |
| LoyaltyAccountCommandService | AwardPointsCommand, UnlockBadgeCommand                                                                    |
| LoyaltyAccountQueryService   | GetAccountQuery, GetPointsQuery                                                                           |
| BadgeCommandService          | CreateBadgeCommand (admin)                                                                                |
| BadgeQueryService            | ListBadgesQuery, GetBadgeQuery                                                                            |


#### 2.6.5.4. Infrastructure Layer
| Component                   | Responsibility                            |
| --------------------------- | ----------------------------------------- |
| LoyaltyAccountRepository    | Port – load/save LoyaltyAccount aggregate |
| BadgeRepository             | Port – load/save Badge definitions        |
| LoyaltyAccountJpaRepository | Spring-Data impl                          |
| BadgeJpaRepository          | Spring-Data impl                          |

#### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams
Esta sección presenta diagramas a nivel de componentes que ilustran la arquitectura interna de cada Bounded Context. Los diagramas muestran cómo se organizan y relacionan los principales módulos y servicios dentro del contexto, facilitando la comprensión de la estructura y las interacciones técnicas clave.
<img src="https://i.postimg.cc/fy3Y8Mcz/Loyalty.png">

#### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams
Aquí se incluyen los diagramas de clases de la capa de dominio para cada Bounded Context. Estos diagramas detallan las entidades, objetos de valor y agregados principales, así como sus relaciones, proporcionando una visión clara del modelo de dominio y su lógica central.
<img src="https://i.postimg.cc/gjhz27yc/Loyality-CD.png">

##### 2.6.5.6.2. Bounded Context Database Design Diagram
En esta sección se muestran los diagramas de diseño de base de datos correspondientes a cada Bounded Context. Los diagramas reflejan la estructura de las tablas, claves y relaciones, sirviendo como referencia para la implementación y el mantenimiento de la persistencia de datos.

[![loyalty.jpg](https://i.postimg.cc/2SDNNwHY/loyalty.jpg)](https://postimg.cc/LnNbzzKQ)

### 2.6.6. Bounded Context: Analytics & Dashboard
Aquí se expone el diseño del contexto de analíticas, encargado de recopilar, procesar y presentar métricas clave del sistema. Se detallan los modelos de datos, los servicios de generación de reportes y los componentes que permiten a los partners y administradores visualizar el desempeño y la actividad en la plataforma.

#### 2.6.6.1. Domain Layer
| Artefact        | Responsibility                                 |
| --------------- | ---------------------------------------------- |
| MonthlyReport   | Read-Model; pre-computed KPI line              |
| AnalyticsEngine | Domain-service; aggregates events into metrics |


#### 2.6.6.2. Interface Layer
| Component            | Responsibility                                                        |
| -------------------- | --------------------------------------------------------------------- |
| ReportController     | `GET /reports/monthly`, `GET /reports/partner/{id}`, export endpoints |
| ReportTypeController | `GET /report-types`, `POST /report-types` (admin CRUD)                |


#### 2.6.6.3. Application Layer
| Component                  | Responsibility                                                |
| -------------------------- | ------------------------------------------------------------- |
| ReportCommandService       | GenerateReportCommand, RefreshReportCommand                   |
| ReportQueryService         | GetMonthlyReportQuery, DownloadReportQuery                    |
| ReportTypeCommandService   | CreateReportTypeCommand, UpdateReportTypeCommand              |
| ReportTypeQueryService     | ListReportTypesQuery, GetReportTypeQuery                      |
| EncounterCompletedListener | @EventListener → calls ReportCommandService.generateMonthly() |
| FeedbackSubmittedListener  | @EventListener → updates avg-rating                           |


#### 2.6.6.4. Infrastructure Layer
| Component               | Responsibility                            |
| ----------------------- | ----------------------------------------- |
| ReportRepository        | Port – load/save MonthlyReport read-model |
| ReportTypeRepository    | Port – load/save ReportType definition    |
| ReportJpaRepository     | Spring-Data impl                          |
| ReportTypeJpaRepository | Spring-Data impl                          |

#### 2.6.6.5. Bounded Context Software Architecture Component Level Diagrams
Esta sección presenta diagramas a nivel de componentes que ilustran la arquitectura interna de cada Bounded Context. Los diagramas muestran cómo se organizan y relacionan los principales módulos y servicios dentro del contexto, facilitando la comprensión de la estructura y las interacciones técnicas clave.

<img src="https://i.postimg.cc/Bvg56YZ0/Analytics.png">

#### 2.6.6.6. Bounded Context Software Architecture Code Level Diagrams

##### 2.6.6.6.1. Bounded Context Domain Layer Class Diagrams
Aquí se incluyen los diagramas de clases de la capa de dominio para cada Bounded Context. Estos diagramas detallan las entidades, objetos de valor y agregados principales, así como sus relaciones, proporcionando una visión clara del modelo de dominio y su lógica central.
<img src="https://i.postimg.cc/pV5XC9NN/Analytics.png">

##### 2.6.6.6.2. Bounded Context Database Design Diagram
En esta sección se muestran los diagramas de diseño de base de datos correspondientes a cada Bounded Context. Los diagramas reflejan la estructura de las tablas, claves y relaciones, sirviendo como referencia para la implementación y el mantenimiento de la persistencia de datos.

[![loyalty.jpg](https://i.postimg.cc/2SDNNwHY/loyalty.jpg)](https://postimg.cc/LnNbzzKQ)

<img src="https://i.postimg.cc/MHgQr6LN/diagrama-glottia.png"/>


# Capítulo III: Solution UI/UX Design

## 3.1. Product Design

En esta capitulo, el equipo de Hampcoders presenta los artefactos de Diseño pertinentes para el diseño y prototipado de nuestros producto

### 3.1.1. Style Guidelines
En esa sección el equipo pressenta la Guía de Estilos para Glottia


#### 3.1.1.1. General Style Guidelines

#### Branding:

El logo de Glottia refleja la misión de la plataforma: ser un espacio de encuentro seguro, moderno y accesible para practicar idiomas de forma conversacional. Los dos globos de diálogo representan la interacción y el intercambio cultural, simbolizando tanto los encuentros presenciales como los virtuales. El azul vibrante transmite confianza, frescura y apertura, mientras que el negro aporta seriedad y profesionalismo. La composición minimalista asegura claridad y versatilidad en distintos formatos digitales e impresos. La tipografía en mayúsculas refuerza solidez y visibilidad, alineándose con la identidad de Glottia como un puente entre personas, culturas y lenguas.

**Variantes de Logo:**

*Logo Original*
Con globos de diálogo y la palabra "GLOTTIA".

*Logo OG*
Versión simplificada para uso en fondos claros y digitales.

*Logo sin Letras (Logo NL)*
Solo con los globos de diálogo, ideal para favicons, app icons o avatares sociales.

*Colores Invertidos (CI)*
Fondo azul con globos y tipografía en blanco, para aplicaciones en superficies oscuras.

**Typography:**

La tipografía de Glottia es moderna, clara y amigable, alineada con su propósito de generar confianza y comodidad entre los usuarios. El lenguaje de marca será cercano, sencillo y motivador, para que los participantes sientan la plataforma como un espacio inclusivo y accesible.

- Fuente primaria: Montserrat (Sans-serif)

- Títulos y subtítulos: Montserrat Bold / Semibold, en tamaños mayores para jerarquía.

- Cuerpo de texto: Montserrat Regular, fácil de leer en dispositivos móviles y de escritorio.

- La consistencia tipográfica en toda la plataforma busca transmitir profesionalismo, pero con un tono humano y cálido.

**Colors:**

La paleta de colores de Glottia refuerza los valores de confianza, accesibilidad y dinamismo. El azul principal es el color guía, evocando comunicación y apertura cultural. Los tonos neutros (blanco y gris) equilibran la interfaz y garantizan legibilidad, mientras que acentos vibrantes pueden utilizarse para destacar interacciones clave (ej. botones de acción o estados positivos).

### Paleta de Colores - Glottia

### Paleta de Colores - Glottia

| Color                  | Uso principal                                   | Código Hex          |
|------------------------|------------------------------------------------|---------------------|
| Azul principal         | Globos de diálogo, botones primarios            | `#1E90FF`           |
| Negro profundo         | Texto principal, logotipo                      | `#1C1C1C`           |
| Gris suave             | Fondos secundarios, bordes, texto auxiliar     | `#D9D9D9`           |
| Blanco                 | Fondo principal, contraste universal            | `#FFFFFF`           |
| Verde                  | Confirmaciones, mensajes de éxito               | `#0D7229`           |
| Degradado azul-violeta | Títulos y frases destacadas (ej. “Practica idiomas”) | `#1E90FF → #6683F3` |
| Naranja                | Títulos y frases secundarias (ej. “Sobre nosotros”) | `#FF9E` |

### 3.1.2. Information Architecture

La arquitectura de información que se implementará en Glottia está orientada a facilitar una experiencia clara, accesible y motivadora para dos tipos de usuarios principales: aprendices de idiomas y propietarios de locales aliados. El diseño busca que los aprendices encuentren encuentros conversacionales relevantes con el menor esfuerzo posible, y que los Partners gestionen sus espacios de forma sencilla y atractiva.

Desde el Landing Page, los visitantes podrán acceder de manera inmediata a secciones clave como:

- Descubre encuentros: listado de próximos eventos filtrados por idioma, ubicación y fecha.

- Explora locales: directorio de cafeterías, bares, coworkings y espacios aliados, con mapa interactivo.

- Cómo funciona: explicación breve y visual del modelo de Glottia (registro, reserva, práctica, recompensas).

- Únete a la comunidad: llamadas a la acción diferenciadas para aprendices y partners.

- Testimonios y cultura: experiencias de usuarios y beneficios para los establecimientos.

En la Aplicación Móvil , la navegación se organiza en un menú principal con accesos a:

- Inicio: resumen personalizado con próximos encuentros, notificaciones y recordatorios.

- Encuentros: búsqueda avanzada con filtros por idioma, ciudad, fecha, disponibilidad y nivel.

- Mapa: visualización geográfica de locales aliados.

- Mi perfil: gestión de datos personales, idiomas, logros, puntos de lealtad e insignias.

- Mensajes y contactos: chat directo y lista de conexiones.

- Locales (vista Partner): gestión de establecimientos, creación/edición de fichas, carga de fotos, métricas y reportes.


#### 3.1.2.1. Organization Systems

La organización de la información en Glottia se ha diseñado para atender de manera clara y efectiva a sus dos audiencias principales: aprendices de idiomas y administradores de locales aliados. Se aplican distintos sistemas de organización visual y esquemas de categorización para garantizar que los usuarios encuentren lo que necesitan con rapidez y sin fricciones.

#### 1. Organización visual del contenido:

**Jerárquica (Visual Hierarchy):**

- Se utiliza en la Landing Page y en la pantalla principal de la App, destacando primero las opciones más relevantes para el usuario: próximos encuentros, eventos recomendados y botones de acción (“Reservar”, “Explorar locales”, “Unirme”).

- Los perfiles de usuarios y locales se presentan con una jerarquía visual clara: foto, nombre, idiomas, horarios, reseñas.

**Secuencial (Step-by-step):**

- En los procesos de registro, creación de eventos y reserva de encuentros, donde el usuario debe seguir pasos guiados (ejemplo: registro → selección de idioma → elección de local → confirmación).

- Esto reduce la complejidad y ayuda a usuarios principiantes a completar acciones sin confundirse.

**Matricial:**

- Aplicado en la sección de búsqueda de encuentros y en el mapa de locales, donde se combinan filtros múltiples (idioma, fecha, nivel, ubicación, disponibilidad).

- Este sistema permite comparar diferentes opciones en paralelo, ofreciendo flexibilidad para tomar decisiones.

<img src="https://i.postimg.cc/PqdpLNcj/organizacion.png"/>

#### 3.1.2.2. Labelling Systems

### 3.1.2.2. Labelling Systems  

| **Sección** | **Etiqueta** | **Descripción** |
|-------------|--------------|-----------------|
| **Landing** | Inicio | Pantalla principal que muestra la visión general de la plataforma y accesos rápidos a las funcionalidades clave (encuentros, mapa, perfil). |
| | Cómo funciona | Explicación breve y visual del funcionamiento de Glottia: registro, búsqueda de encuentros y práctica de idiomas. |
| | Contacto / Ayuda | Formulario y canales de soporte (FAQ, chat de ayuda, correo). |
| **Botones de ingreso y salida de la plataforma** | Iniciar Sesión | Botón para acceder con cuenta registrada. |
| | Iniciar con Google | Acceso rápido usando la cuenta de Google. |
| | Iniciar con Facebook | Acceso rápido usando la cuenta de Facebook. |
| | Registrarse | Botón para crear una nueva cuenta de aprendiz o Partner. |
| | Cerrar Sesión | Botón para finalizar sesión de forma segura. |
| **Menú del aprendiz (usuario)** | Encuentros | Lista de encuentros disponibles con filtros por idioma, ubicación, fecha y nivel. |
| | Mapa de locales | Visualización de los locales registrados en un mapa interactivo. |
| | Mi Perfil | Edición de datos personales, idiomas, foto y progreso de gamificación (puntos, insignias). |
| | Mis reservas | Sección con los encuentros reservados y confirmaciones QR. |
| | Historial | Registro de encuentros pasados y reseñas dadas. |
| | Contactos | Lista de conexiones establecidas en la plataforma. |
| | Mensajes | Chat con contactos y notificaciones de nuevas conversaciones. |
| **Menú del Partner (dueño de local)** | Mi Local | Panel para gestionar la información del local (dirección, fotos, aforo, horarios). |
| | Crear Encuentro | Opción para proponer o programar un encuentro en el local. |
| | Dashboard | Visualización de métricas clave: asistentes, reseñas, fidelidad de usuarios. |
| | Reseñas | Acceso a valoraciones y comentarios recibidos. |
| | Ofertas y recompensas | Gestión de promociones especiales para usuarios frecuentes. |
| **Menú de administración (interno)** | Dashboard Admin | Panel con métricas generales del sistema (usuarios activos, eventos, locales). |
| | Gestionar usuarios | Opción para ver, aprobar o desactivar cuentas de usuarios y locales. |
| | Reportes | Listado de reportes enviados por usuarios y acciones tomadas. |
| | Comunicaciones globales | Envío de notificaciones o correos masivos a la comunidad. |

#### 3.1.2.3. SEO Tags and Meta Tags
### 3.1.2.3. SEO Tags and Meta Tags  

#### Landing Page 
- **Title**: Glottia | Practica idiomas con experiencias reales  
- **Meta Description**: Glottia conecta a personas que desean mejorar sus idiomas mediante encuentros reales en espacios públicos y locales aliados. Vive experiencias auténticas, seguras y divertidas mientras practicas con hablantes de todo el mundo.  
- **Keywords**: idiomas, práctica de idiomas, intercambio lingüístico, inglés, español, francés, conversación, encuentros, Glottia  
- **Author**: Equipo Glottia  

#### Mobile Application 
- **Title**: Glottia Web App | Encuentros y práctica de idiomas  
- **Meta Description**: Reserva encuentros, conecta con locales aliados y mejora tu fluidez en idiomas con Glottia. Una experiencia interactiva de aprendizaje y conexión.  
- **Keywords**: Glottia app, practicar inglés, practicar español, intercambios, locales aliados, conversación en vivo  
- **Author**: Equipo Glottia  

#### App Store Optimization (ASO) – Aplicaciones móviles  
- **App Title**: Glottia – Practica idiomas con experiencias reales  
- **App Subtitle**: Conecta, conversa y aprende en encuentros reales  
- **App Keywords**: idiomas, aprender idiomas, intercambio, conversación, inglés, español, práctica oral  
- **App Description**:  
  Glottia es la aplicación que te ayuda a ganar fluidez en idiomas a través de experiencias conversacionales reales.  
  - Encuentra locales aliados y participa en encuentros de idiomas.  
  - Conoce personas con tus mismos intereses.  
  - Gana confianza, fluidez y motivación con cada experiencia.  
  ¡Glottia convierte la práctica de idiomas en algo divertido y auténtico!  

---

#### 3.1.2.4. Searching Systems

| **Filtro**                  | **Descripción** |
|------------------------------|-----------------|
| Idioma                       | Permite al usuario buscar encuentros o personas según el idioma que desea practicar (inglés, español, francés, etc.). |
| Nivel de Fluidez             | Filtra por nivel de conversación (básico, intermedio, avanzado) para emparejar usuarios con mayor afinidad. |
| Ubicación / Zona             | Filtro geográfico para encontrar encuentros o locales aliados cercanos a la ubicación del usuario. |
| Fecha y Horario              | Permite seleccionar encuentros disponibles según día y hora que mejor se ajusten al usuario. |
| Tipo de Encuentro            | Diferencia entre encuentros individuales, grupales o actividades especiales en locales aliados. |
| Locales Aliados              | Muestra los espacios aliados disponibles, con información de ubicación, servicios y reseñas. |
| Reseñas y Calificaciones     | Filtra encuentros y usuarios según la valoración de otros participantes, destacando los mejor evaluados. |
| Intereses en Común           | Permite buscar usuarios o encuentros en función de intereses personales (música, viajes, negocios, cultura, etc.). |
| Costo del Encuentro          | Filtra opciones gratuitas, con costo reducido o premium según el presupuesto del usuario. |
| Historial de Participación   | Muestra y filtra encuentros previos en los que el usuario participó, para facilitar repetición o recomendaciones. |

#### 3.1.2.5. Navigation Systems

Los sistemas de navegación de Glottia han sido diseñados para guiar de forma intuitiva a los usuarios a través del Landing Page y la aplicación, facilitando la exploración del contenido y el acceso a las funcionalidades clave. La estructura sigue una lógica clara que permite a cada tipo de usuario (aprendices de idiomas y administradores de locales ) encontrar rápidamente lo que necesita mediante menús jerárquicos, enlaces destacados y botones de acción visibles.

<img src="https://i.postimg.cc/4xF817Cd/Captura.png"/>

### 3.1.3. Landing Page UI Design
En esta sección, el equipo de Hampcoders presenta el Diseño de Interfaz de Usuario de la Landing Page del negocio


#### 3.1.3.1. Landing Page Wireframe

### Sección "Vista Principal y ¿Cómo funciona?" 
<hr>

<img src="https://i.postimg.cc/2yHqtXpR/principal.png"/>


### Sección "Nuestra Solución: Glottia y Ve Glottia en Acción" 
<hr>

<img src="https://i.postimg.cc/FHvRZ4kT/nuestra-solucion.png"/>


### Sección "Beneficios y Sobre Nosotros" 
<hr>

<img src="https://i.postimg.cc/k4RqC1tg/beneficios.png"/>

### Sección "Nuestros Valores y Nuestro Equipo" 
<hr>

<img src="https://i.postimg.cc/9FJSxPrZ/valores.png"/>


### Sección "Lo que dicen de nosotros y Preguntas Frecuentes" 
<hr>

<img src="https://i.postimg.cc/dQn4vsvb/lo-que-dicen-de-nosotros.png"/>


#### 3.1.3.2. Landing Page Mock-up


### Sección "Vista Principal y ¿Cómo funciona?" 
<hr>

<img src="https://i.postimg.cc/4y0TSj5b/principal2.png"/>


### Sección "Nuestra Solución: Glottia y Ve Glottia en Acción" 
<hr>

<img src="https://i.postimg.cc/xjZDnDv0/solucion2.png"/>


### Sección "Beneficios y Sobre Nosotros" 
<hr>

<img src="https://i.postimg.cc/DZjVSRRB/beneficios2.png"/>

### Sección "Nuestros Valores y Nuestro Equipo" 
<hr>

<img src="https://i.postimg.cc/htTq2y74/valores2.png"/>


### Sección "Lo que dicen de nosotros y Preguntas Frecuentes" 
<hr>

<img src="https://i.postimg.cc/44Y4z1w7/nosotros.png"/>

--- 

[https://glottia-landing-page-master.vercel.app/](https://glottia-landing-page-master.vercel.app/)

### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes
#### 3.1.4.2. Mobile Applications Wireflow Diagrams
#### 3.1.4.3. Mobile Applications Mock-ups
#### 3.1.4.4. Mobile Applications User Flow Diagrams

<img src = "https://i.postimg.cc/SK3mvyP5/Captura.png" />

<img src = "https://i.postimg.cc/y825qkVJ/flow2.png" />

<img src = "https://i.postimg.cc/pLjCFkHr/flow3.png" />

<img src = "https://i.postimg.cc/xd0m1PT8/flow4.png" />

#### 3.1.4.5. Mobile Applications Prototyping

---

# Capítulo IV: Product Implementation & Validation
## 4.1. Software Configuration Management
A continuación, se va a realizar el proceso por el cual organizamos y gestionamos  los cambios desarrolados en el proyecto de Glottia

### 4.1.1. Software Development Environment Configuration
Este este apartado vamos a describir la configuración del entorno de desarrollo de software establecida para el proyecto, con el propósito de garantizar la correcta integración, colaboración y trazabilidad de las actividades realizadas por los miembros del equipo.
Se definen las herramientas, plataformas y productos de software utilizados a lo largo del ciclo de vida del desarrollo, desde la gestión del proyecto hasta el despliegue y documentación.


| **Plataforma / Herramienta** | **Descripción** | **Enlace** |
|------------------------------|-----------------|-------------|
| **Trello** | Plataforma de gestión de proyectos que permite organizar tareas mediante tableros, listas y tarjetas. Facilita la asignación de responsables, seguimiento del progreso y comunicación entre los miembros del equipo. | [https://trello.com](https://trello.com) |
| **UXPressia** | Herramienta en línea enfocada en el diseño de experiencias de usuario. Permite crear **User Personas**, **Customer Journey Maps**, **Empathy Maps** e **Impact Maps**, ofreciendo plantillas ágiles y colaborativas para el análisis del usuario. | [https://uxpressia.com](https://uxpressia.com) |
| **Mural** | Plataforma visual colaborativa ideal para **brainstorming**, **scenario mapping** y desarrollo de **estrategias UX**. Permite trabajar en equipo de forma remota con plantillas interactivas y herramientas de diseño intuitivas. | [https://www.mural.co](https://www.mural.co) |
| **Figma** | Herramienta de diseño colaborativo utilizada para la creación de **wireframes**, **mockups**, **prototipos interactivos** y **diseños de interfaces móviles/web**. Favorece la colaboración en tiempo real y la integración con flujos de trabajo ágiles. | [https://www.figma.com](https://www.figma.com) |
| **Canva** | Aplicación web de diseño gráfico que permite crear materiales visuales (presentaciones, posters, publicaciones, etc.) con plantillas predefinidas y funciones colaborativas. Útil para diseño visual complementario. | [https://www.canva.com](https://www.canva.com) |
| **Vertabelo** | Plataforma para el **diseño, documentación y gestión de bases de datos relacionales**. Permite modelar esquemas de datos, generar scripts SQL y trabajar colaborativamente en la estructura del sistema. | [https://vertabelo.com](https://vertabelo.com) |
| **Lucidchart** | Herramienta de diagramación que facilita la creación de **diagramas de flujo**, **diagramas de clases**, **user flows** y **wireflows**. Ideal para la documentación visual y el análisis de procesos. | [https://lucidchart.com](https://lucidchart.com) |
| **Structurizr** | Herramienta especializada para modelar **diagramas C4** de arquitectura de software. Permite representar de manera jerárquica los componentes del sistema y su relación con el entorno tecnológico. | [https://structurizr.com](https://structurizr.com) |
| **C4 Model** | Modelo conceptual para documentar arquitecturas de software en diferentes niveles de abstracción (contexto, contenedor, componente y código), ayudando a comunicar decisiones de diseño de forma estructurada. | [https://c4model.com](https://c4model.com) |
| **HTML5 / CSS3 / JavaScript** | Conjunto de tecnologías empleadas para el desarrollo de la **Landing Page** del proyecto. Permiten construir interfaces web responsivas y visualmente atractivas, integrando elementos interactivos y multimedia. | — |
| **GitHub** | Plataforma de control de versiones basada en Git que permite la colaboración en el desarrollo del código fuente, manejo de ramas, control de cambios y despliegue continuo. | [https://github.com](https://github.com) |
| **Postman** | Herramienta para **pruebas y validación de APIs REST**. Permite enviar solicitudes HTTP, automatizar test cases y analizar respuestas del servidor durante la etapa de integración del sistema. | [https://www.postman.com](https://www.postman.com) |
| **Firebase / AWS IoT Core (opcional)** | Plataformas en la nube para el **despliegue y gestión de soluciones IoT**, ofreciendo servicios de base de datos en tiempo real, autenticación, almacenamiento y comunicación entre dispositivos conectados. | [https://firebase.google.com](https://firebase.google.com) / [https://aws.amazon.com/iot-core](https://aws.amazon.com/iot-core) |

---


### 4.1.2. Source Code Management

En esta sección se define el esquema de gestión del código fuente del proyecto **Glottia**, estableciendo los medios, convenciones y flujos de trabajo que el equipo empleará para garantizar la trazabilidad, integridad y control de versiones en todas las etapas del desarrollo.  

El sistema de control de versiones seleccionado es **Git**, con **GitHub** como plataforma principal de alojamiento y colaboración.  
GitHub permite la administración de ramas, el seguimiento de cambios, la revisión de código mediante *pull requests*, la integración continua y el control de versiones en cada uno de los módulos del sistema.

El ecosistema Glottia está estructurado en tres repositorios principales, cada uno con un propósito definido dentro del desarrollo:

| **Componente / Producto** | **Descripción** | **Repositorio (GitHub URL)** |
|----------------------------|-----------------|-------------------------------|
| **Landing Page** | Contiene el código fuente de la página principal del proyecto, desarrollada con HTML, CSS y JavaScript. Su objetivo es brindar información general sobre Glottia, sus funcionalidades y acceso a la plataforma. | [https://github.com/Hampcoders-Glottia/glottia-landing-page](https://github.com/Hampcoders-Glottia/glottia-landing-page) |
| **Web Services (Back-End)** | Incluye la lógica del servidor, controladores de API REST, base de datos, autenticación y servicios IoT. Contiene también los archivos de **pruebas unitarias e integración**, asegurando la correcta funcionalidad del sistema. | [https://github.com/Hampcoders-Glottia/glottia-back-end](https://github.com/Hampcoders-Glottia/glottia-back-end) |
| **Documentación Técnica (Docs)** | Contiene la documentación técnica, manuales de uso, diagramas, reportes y archivos Markdown relacionados con la planificación y desarrollo del proyecto. | [https://github.com/Hampcoders-Glottia/glottia-docs](https://github.com/Hampcoders-Glottia/glottia-docs) |

#### **Modelo de Ramas — GitFlow Workflow**

El equipo adoptará la metodología **GitFlow**, propuesta por Vincent Driessen, como modelo de ramificación (*branching model*) para organizar el ciclo de vida del código fuente.  
Este flujo de trabajo permite mantener un desarrollo ordenado y paralelo entre funcionalidades nuevas, versiones estables y correcciones urgentes.

**Estructura principal de ramas:**

| **Rama** | **Propósito** |
|-----------|---------------|
| **main** | Contiene el código fuente estable y listo para producción. Cada versión publicada se etiqueta con una versión semántica. |
| **develop** | Rama de integración principal para las funcionalidades en desarrollo. Aquí se fusionan los *feature branches* antes de ser liberados. |
| **feature/** | Ramas creadas a partir de `develop` para implementar nuevas funcionalidades o mejoras específicas. |
| **release/** | Ramas creadas desde `develop` cuando se prepara una nueva versión de producción. Se usan para pruebas y ajustes menores antes del despliegue. |
| **hotfix/** | Ramas derivadas de `main` para corregir errores críticos detectados en producción. Una vez corregido, se fusionan tanto en `main` como en `develop`. |

### 4.1.3. Source Code Style Guide & Conventions
Esta sección establece las convenciones de estilo y guías de codificación adoptadas por el equipo de desarrollo del proyecto **Glottia**, con el fin de asegurar la coherencia, mantenibilidad y legibilidad del código fuente en todos los módulos del sistema.

Se adopta el principio de **Clean Code** y se exige el uso consistente del **idioma inglés** para nombres de variables, clases, métodos, funciones, comentarios y archivos, independientemente del lenguaje o tecnología empleada.

#### **Lenguajes y Estándares Aplicados**

El ecosistema Glottia utiliza múltiples lenguajes de programación y tecnologías para diferentes componentes del sistema. Cada uno adopta convenciones reconocidas y guías oficiales:

| **Lenguaje / Tecnología** | **Guía de Estilo Adoptada** | **Referencia Oficial** |
|----------------------------|------------------------------|-------------------------|
| **HTML5 / CSS3** | Se siguen las convenciones de indentación, nombramiento semántico y estructura modular sugeridas por **Google HTML/CSS Style Guide**. | [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) |
| **JavaScript (Frontend)** | Uso del estándar **Airbnb JavaScript Style Guide**, promoviendo consistencia en variables, funciones y estructuras. | [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) |
| **TypeScript (Frontend WebApp)** | Se adopta la **Google TypeScript Style Guide**, que enfatiza tipado estricto, uso de `interface` y separación clara de responsabilidades. | [Google TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html) |
| **Java (Backend - Spring Boot)** | Basado en las convenciones de **Google Java Style Guide** y las **Spring Boot Best Practices**, priorizando modularidad, claridad y consistencia. | [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html) |
| **SQL / Modelado de Datos (Vertabelo)** | Uso de nombres descriptivos en inglés, en singular, con prefijos claros según entidad. Palabras clave en mayúsculas. | [SQL Style Guide](https://www.sqlstyle.guide/) |
| **Gherkin (.feature files - QA / BDD)** | Se siguen las convenciones de **Gherkin Conventions for Readable Specifications**, priorizando la claridad en los escenarios de prueba. | [Gherkin Syntax](https://cucumber.io/docs/gherkin/reference/) |
| **HTML + CSS (Landing Page)** | Estructura jerárquica, uso de **BEM (Block-Element-Modifier)** para clases CSS y componentes reutilizables. | [BEM Naming Convention](http://getbem.com/naming/) |

#### **Indentación y Estructura**

- **Indentación:** 2 espacios para HTML, CSS, JavaScript y TypeScript; **4 espacios para Java**.  
- **Longitud máxima de línea:** 120 caracteres.  
- **Comillas:** Simples (`'`) por defecto en JavaScript/TypeScript; dobles (`"`) en Java y HTML.  
- **Llaves:** En Java, se abren **en la misma línea** del bloque (`K&R style`).  
- **Comentarios:**
  - `//` para comentarios breves.
  - `/** ... */` para documentación de métodos o clases.
- **Bloques de código:** No más de 30 líneas por función o método. Se prioriza la modularidad y reutilización.

---

### 4.1.4. Software Deployment Configuration

**Consideraciones Preliminares al Despliegue:**

* **Implementación de Archivos Web:** Se requiere la implementación completa de la página web utilizando archivos HTML, CSS y JS para garantizar su correcta operatividad. Se autoriza el uso de diversos formatos para los archivos de imagen (jpg, png, webp, etc.).
* **Mecanismo de Publicación en Github:** En virtud del servicio Github Pages, todos los archivos necesarios para la funcionalidad de la aplicación se cargarán al repositorio compartido de Github, facilitando la colaboración simultánea entre los miembros del equipo.
* **Protocolo de Pruebas de Funcionamiento:** Tras cada actualización e integración al repositorio, se ejecutarán pruebas internas para asegurar la correcta operación de la página. Asimismo, se someterá la página a pruebas por parte de usuarios externos al grupo de trabajo para obtener una evaluación imparcial.

## 4.2. Landing Page & Mobile Application Implementation
### 4.2.1. Sprint 1

Esta sección presenta los detalles de la primera reunión de planificación de Sprint del equipo **Hampcoders**, correspondiente al desarrollo de **Glottia**.  
Durante esta sesión se definieron los objetivos principales del sprint, la capacidad del equipo y las historias de usuario priorizadas para esta iteración.  
Al ser el primer Sprint del proyecto, no se incluyen resúmenes de revisión ni retrospectiva previos.  

El enfoque principal fue **implementar la Landing Page y los primeros módulos funcionales del backend**, con el objetivo de validar la propuesta de valor del proyecto y preparar la infraestructura base para la interacción de usuarios (aprendices y locales).  

#### 4.2.1.1. Sprint Planning 1 

| **Sprint #** | Sprint 1 |
|--------------|-----------|
| **Date** | 2025-04-22 |
| **Time** | 3:00 PM |
| **Location** | Virtual – Google Meet |
| **Prepared By** | Matías Aliaga |
| **Attendees (Planning Meeting)** |  Matías Aliaga, Ivo Machado, Leandro Contreras, Ítalo Sánchez |
| **Sprint n - 1 Review Summary** | Durante esta fase inicial del proyecto **Glottia**, se establecieron las primeras historias de usuario centradas en el desarrollo de la **Landing Page** y en la implementación de la arquitectura base del **backend** utilizando **Java Spring Boot**. Se logró con éxito el despliegue inicial de la Landing Page dentro del plazo acordado, junto con la configuración del entorno de desarrollo y los primeros endpoints funcionales para registro y autenticación. Además, la documentación se enriqueció con la definición de la visión de negocio y la incorporación de artefactos técnicos y de diseño que consolidan la base del proyecto. |
| **Sprint n - 1 Retrospective Summary** | En general, el equipo mantuvo una excelente organización y comunicación gracias al uso de herramientas colaborativas como **Slack** y **GitHub Projects**. No obstante, se identificó la necesidad de mejorar la estimación del tiempo de desarrollo para tareas relacionadas con la integración del backend y los wireframes del frontend, con el fin de optimizar la planificación en futuros sprints. También se acordó reforzar el uso del formato **Markdown** para la documentación técnica y la consistencia en los mensajes de commit, garantizando así una comunicación más clara y una trazabilidad efectiva del código. |
| **Sprint 1 Goal** | **Our focus is on** establishing the technical and visual foundation of Glottia by developing the Landing Page and core backend modules for user registration and authentication. **We believe it delivers** credibility, accessibility, and a first interactive experience to early users and stakeholders. **This will be confirmed when** the Landing Page is deployed online and users can successfully register and log in using the backend system developed in Java Spring Boot.<br><br>**Outcome:** Desplegar la primera versión funcional del sistema.<br>**Impact:** Generar visibilidad y validar el interés inicial de los usuarios.<br>**Customer(s):** Visitantes interesados en practicar idiomas mediante Glottia.<br>**Event:** Los usuarios pueden registrarse, iniciar sesión y acceder al contenido inicial del sitio. |
| **Sprint 1 Velocity** | El equipo puede atender hasta **28 Story Points**. |
| **Sum of Story Points** | La suma de Story Points planificados para este sprint es de **28 Story Points**. |


#### 4.2.1.2. Sprint Backlog 1 

El objetivo principal del Sprint 1 fue implementar la Landing Page de Glottia y establecer la arquitectura base del backend utilizando Java Spring Boot, incluyendo los primeros endpoints para autenticación, registro y gestión básica de usuarios. Este sprint se centró en construir la experiencia visual inicial del producto y sentar las bases técnicas para la integración entre el frontend y el backend.

El equipo trabajó de manera colaborativa mediante Trello como herramienta de gestión ágil, dividiendo las historias de usuario en tareas específicas con sus responsables, estimaciones y estado de avance.



| **Sprint #** | Sprint 1 |  |  |  |  |  |  |
|---------|---------|---------|---------|---------|---------|---------|---------|
| **User Story** | | **Work-Item / Task** | | | | | |
| **ID** | **Title** | **Id** | **Title** | **Description** | **Estimation (hrs)** | **Assigned To** | **Status** |
| US-LP-01 | Visualización de la Propuesta de Valor | T01-1 | Diseñar hero section | Crear diseño visual de la sección principal con título, subtítulo y CTA. | 2 | Matías Aliaga | Done |
| US-LP-01 | Visualización de la Propuesta de Valor | T01-2 | Implementar estructura HTML/CSS | Construir la sección principal en HTML y CSS. | 2 | Matías Aliaga | Done |
| US-LP-01 | Visualización de la Propuesta de Valor | T01-3 | Integrar endpoint de registro | Conectar botón CTA con endpoint de registro del backend (Spring Boot). | 3 | Leandro Contreras | Done |
| US-LP-02 | Ver Beneficios para Aprendices | T02-1 | Diseñar sección beneficios | Diseñar visualmente la sección “Para Aprendices”. | 1 | Matías Aliaga | Done |
| US-LP-02 | Ver Beneficios para Aprendices | T02-2 | Implementar HTML/CSS | Implementar estructura y estilos de la sección. | 1 | Matías Aliaga | Done |
| US-LP-02 | Ver Beneficios para Aprendices | T02-3 | Redactar contenido | Redactar textos claros sobre los beneficios de Glottia para aprendices. | 0.5 | Ivo Machado | Done |
| US-LP-03 | Ver Beneficios para Locales | T03-1 | Diseñar sección “Para Locales” | Crear layout visual para locales asociados. | 1 | Matías Aliaga | Done |
| US-LP-03 | Ver Beneficios para Locales | T03-2 | Implementar HTML/CSS | Implementar diseño en código. | 1 | Matías Aliaga | Done |
| US-LP-03 | Ver Beneficios para Locales | T03-3 | Redactar contenido | Escribir beneficios claros para los dueños de locales. | 0.5 | Ivo Machado | Done |
| US-LP-04 | Explicación de Cómo Funciona | T04-1 | Diseñar flujo visual | Crear diseño de pasos para aprendices y locales. | 2 | Matías Aliaga | Done |
| US-LP-04 | Explicación de Cómo Funciona | T04-2 | Implementar HTML/CSS/JS | Implementar sección interactiva que muestre los pasos. | 3 | Matías Aliaga | Done |
| US-LP-04 | Explicación de Cómo Funciona | T04-3 | Integrar datos dinámicos | Preparar estructura para cargar pasos desde el backend (mock API). | 2 | Leandro Contreras | In Progress |
| US-LP-05 | Visualización de Testimonios | T05-1 | Diseñar sección de testimonios | Crear layout con fotos, nombres y comentarios. | 1 | Matías Aliaga | Done |
| US-LP-05 | Visualización de Testimonios | T05-2 | Implementar carrusel dinámico | Implementar carrusel con JavaScript. | 2 | Ítalo Sánchez | Done |
| US-LP-05 | Visualización de Testimonios | T05-3 | Endpoint de testimonios | Crear endpoint REST en Java Spring Boot para cargar testimonios desde base de datos. | 4 | Leandro Contreras | In Progress |
| US-LP-06 | Llamadas a la Acción (CTA) Diferenciadas | T06-1 | Crear botones diferenciados | Implementar botones para “Aprendiz” y “Local”. | 1 | Matías Aliaga | Done |
| US-LP-06 | Llamadas a la Acción (CTA) Diferenciadas | T06-2 | Conectar backend | Asociar los botones con rutas de registro del backend. | 2 | Leandro Contreras | Done |
| US-LP-07 | Adaptabilidad a Diferentes Dispositivos | T07-1 | Implementar responsive design | Adaptar landing page a pantallas móviles. | 4 | Matías Aliaga | Done |
| US-LP-07 | Adaptabilidad a Diferentes Dispositivos | T07-2 | Test de compatibilidad | Probar en distintos navegadores y dispositivos. | 2 | Ítalo Sánchez | Done |
| US-LP-08 | Navegación mediante Encabezado Fijo | T08-1 | Diseñar header fijo | Diseñar barra de navegación con scroll sticky. | 1 | Matías Aliaga | Done |
| US-LP-08 | Navegación mediante Encabezado Fijo | T08-2 | Implementar comportamiento JS | Programar desplazamiento suave y resaltado de secciones. | 2 | Ítalo Sánchez | Done |
| US-LP-09 | Sección de Preguntas Frecuentes (FAQ) | T09-1 | Diseñar sección FAQ | Crear estructura de preguntas desplegables. | 1 | Matías Aliaga | Done |
| US-LP-09 | Sección de Preguntas Frecuentes (FAQ) | T09-2 | Programar comportamiento | Implementar acordeón con JavaScript. | 1 | Ítalo Sánchez | Done |
| US-LP-09 | Sección de Preguntas Frecuentes (FAQ) | T09-3 | Redactar contenido | Redactar preguntas y respuestas principales. | 1 | Ivo Machado | Done |
| US-LP-10 | Visualización del Pie de Página | T10-1 | Diseñar footer | Diseñar estructura del pie de página. | 1 | Matías Aliaga | Done |
| US-LP-10 | Visualización del Pie de Página | T10-2 | Implementar HTML/CSS | Crear pie de página con enlaces y redes. | 1 | Matías Aliaga | Done |
| US-LP-10 | Visualización del Pie de Página | T10-3 | Agregar enlaces legales | Añadir enlaces a políticas de privacidad y condiciones. | 0.5 | Ítalo Sánchez | Done |
| US-LP-10 | Visualización del Pie de Página | T10-4 | Verificar integración | Validar que el pie de página cargue correctamente en todas las vistas. | 0.5 | Ítalo Sánchez | Done |

#### 4.2.1.3. Development Evidence for Sprint Review

En esta sección presentamos el flujo de trabajo para la creación y actuallización de la landing page

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|---------------------|--------------------|
| glottia-landing-page | main | 01 | Landing Page | - | 29/09/2025 |


[Repositorio Glottia – Landing Page](https://github.com/Hampcoders-Glottia/glottia-landing-page)


#### 4.2.1.4. Testing Suite Evidence for Sprint Review

En esta sección se presenta la evidencia de pruebas de aceptación realizadas durante el **Sprint 1** del proyecto **Glottia**, enfocadas en validar la correcta implementación de la **Landing Page** y los **endpoints iniciales del backend** desarrollados con **Java Spring Boot**.

| Epic / Story ID | Título | Criterios de Aceptación | Resultado |
|----------------|--------|--------------------------|-----------|
| US-01 | Visualización de la Landing Page | **Escenario #1: Carga y estructura general**<br>Given que un usuario accede a la URL principal de Glottia<br>When la página termina de cargar<br>Then debe visualizar correctamente el hero banner, las secciones informativas y el pie de página<br>And no deben presentarse errores en consola ni fallos visuales. |  Pasado |
| US-01 | Visualización de la Landing Page | **Escenario #2: Contenido visible y coherente**<br>Given que el usuario explora la landing page<br>When se desplaza por las secciones principales<br>Then debe visualizar mensajes claros sobre la misión y objetivos del proyecto Glottia<br>And los botones de acción deben dirigir correctamente a las secciones correspondientes. |  Pasado |
| US-02 | Autenticación de Usuario (Backend) | **Escenario #1: Registro exitoso**<br>Given que un nuevo usuario envía sus datos válidos al endpoint `/api/auth/register`<br>When la solicitud es procesada por el backend Java Spring Boot<br>Then debe crearse un nuevo registro en la base de datos<br>And el sistema debe devolver una respuesta con código 201 y un mensaje de confirmación. |  Pasado |
| US-02 | Autenticación de Usuario (Backend) | **Escenario #2: Inicio de sesión correcto**<br>Given que un usuario registrado envía sus credenciales al endpoint `/api/auth/login`<br>When las credenciales son válidas<br>Then el sistema debe generar y devolver un token JWT<br>And el código de respuesta debe ser 200. |  Pasado |
| US-02 | Autenticación de Usuario (Backend) | **Escenario #3: Validación de credenciales erróneas**<br>Given que un usuario intenta iniciar sesión con datos incorrectos<br>When envía la solicitud al endpoint `/api/auth/login`<br>Then el backend debe responder con un código 401<br>And un mensaje de error indicando “Credenciales inválidas”. |  Pasado |
| US-03 | Responsividad del Sitio | **Escenario #1: Visualización en móviles**<br>Given que el usuario accede desde un smartphone<br>When se carga la landing page<br>Then todos los elementos deben ajustarse correctamente al ancho del dispositivo<br>And no debe existir desplazamiento horizontal<br>And los botones deben ser accesibles táctilmente. |  Pasado |
| US-03 | Responsividad del Sitio | **Escenario #2: Visualización en pantallas medianas (tablets)**<br>Given que el usuario accede desde una tablet<br>When se carga la landing page<br>Then el diseño debe reorganizar los elementos de manera proporcional<br>And mantener la legibilidad del contenido y la jerarquía visual. |  Pasado |
| US-04 | Comunicación Frontend–Backend | **Escenario #1: Consumo de endpoints**<br>Given que el frontend intenta conectarse con los endpoints del backend desplegado<br>When se realiza una solicitud desde la interfaz (por ejemplo, registro o login)<br>Then la API debe responder correctamente según los parámetros enviados<br>And no deben presentarse errores CORS ni fallos de conexión. | Pasado |
| US-05 | Seguridad del Sistema | **Escenario #1: Validación de token JWT**<br>Given que un usuario intenta acceder a un endpoint protegido<br>When no incluye el token de autenticación<br>Then el backend debe devolver un código 403<br>And cuando el token es válido, el acceso debe concederse correctamente. | Pasado |
| US-06 | Sección “Sobre Glottia” | **Escenario #1: Visualización de información corporativa**<br>Given que un visitante se desplaza hasta la sección “Sobre Glottia”<br>When se muestra el contenido<br>Then debe visualizarse la misión, visión y objetivo del proyecto<br>And el diseño debe mantener coherencia con la identidad visual general. |  Pasado |
| US-07 | Pie de Página | **Escenario #1: Verificación de enlaces funcionales**<br>Given que el usuario llega al pie de página<br>When hace clic en cualquiera de los enlaces o redes sociales<br>Then debe redirigir correctamente a la página o red externa<br>And no deben existir enlaces rotos. |  Pasado |

---

#### 4.2.1.5. Execution Evidence for Sprint Review

En esta entrega, nuestro equipo ha desplegado con éxito la landing page.
Enlace de la Landing Page: https://glottia-landing-page-master.vercel.app/

<img src="https://i.postimg.cc/fT2VnLTz/landing1.png" />

<img src="https://i.postimg.cc/j5txJ0dv/landing2.png" />

<img src="https://i.postimg.cc/Mp1J0P4X/landing3.png" />

<img src="https://i.postimg.cc/RC3S6RMq/landing-4.png" />

<img src="https://i.postimg.cc/zfLtSV3G/lading5.png" />

<img src="https://i.postimg.cc/Gm6JRzhd/landing6.png" />


#### 4.2.1.6. Services Documentation Evidence for Sprint Review

Backend API

#### 4.2.1.7. Software Deployment Evidence for Sprint Review

Para este primer Sprint , como equipo logramos implementar satisfactoriamente la primera versión de la landing page.

## Design

Para realizar el diseño de los wireframes y mockups de la **Landing Page** para este Sprint, se hizo uso de la plataforma **Figma**.
Para utilizar la plataforma:

1. Se accede a través de la página oficial de Figma: https://www.figma.com/login
    <img  src="https://i.postimg.cc/g2yX0rpY/65765.png"/>
2. Luego, se crea un **Draft** que nos servirá como base para el proyecto colaborativo.
   <img  src="https://i.postimg.cc/dQzjk7bd/76867.png"/>
---

## Deployment

Para la landing page, se utilizará Netlify para el despliegue de la página.
<img  src="https://i.postimg.cc/W3d0tjSX/9789789.png"/>
<img  src="https://i.postimg.cc/6qd2GQZL/567567.png"/>
<img  src="https://i.postimg.cc/3Jtrfp30/876876.png"/>
<img  src="https://i.postimg.cc/FRTnX9zp/87876.png"/>

<img  src="https://i.postimg.cc/tg2zYBbC/5456.png"/>

<img  src="https://i.postimg.cc/KvPpmr14/45345.png"/>

<img  src="https://i.postimg.cc/prNkHpxD/32143.png"/>


Tras definir el repositorio , conectamos este mismo con el servicio de netlify para realizar el despliegue.

<img  src="https://i.postimg.cc/kMxvSMqp/645.png"/>

<img  src="https://i.postimg.cc/YqdgNhVb/44.png"/>


Para nuestro proyecto se crearon **2 repositorios**, el cuál fue:

- **Glottia** | https://github.com/Hampcoders-Glottia/glottia-landing-page: Este repositorio se usa para realizar el informe del proyecto de manera continua y subir la landing page. :
- **Documentación** | https://github.com/Hampcoders-Glottia/glottia-docs : Este repositorio contiene el informe de nuestro proyecto.
#### 4.2.1.8. Team Collaboration Insights during Sprint
A continuación, se muestran las capturas de los insights del repositorio.


## 4.3. Validation Interviews
En esta sección, el equipo presenta la entrevistas de validación

### 4.3.1. Diseño de Entrevistas
###  Segmento Objetivo #1: Usuarios Aprendices de Idiomas  


**Objetivo de la entrevista:**  
Evaluar la claridad de la propuesta de valor, la facilidad de uso de la landing page y la app, la motivación para participar en prácticas presenciales y la percepción de confianza y autenticidad de la experiencia Glottia.

**Preguntas:**

1. ¿Cómo llegaste a conocer Glottia (redes, recomendación, anuncio, evento, etc.)?
2. ¿Qué impresión te dio Glottia al visitar la landing page por primera vez?
3. ¿Pudiste entender de inmediato qué ofrece la plataforma y cómo funciona?
4. ¿Qué tan fácil te resultó registrarte y navegar por la aplicación?
5. ¿Qué fue lo que más te llamó la atención de la idea de practicar con otras personas en espacios reales?
6. ¿Qué te motiva más a usar Glottia: mejorar tu fluidez, conocer gente nueva o ambas?
7. ¿Te sentiste cómodo explorando los puntos de encuentro o prácticas disponibles?
8. ¿Qué tan clara te pareció la información sobre los lugares de práctica y sus anfitriones?
9. ¿Qué emociones sentiste antes y después de tu primera sesión (confianza, nervios, entusiasmo, curiosidad)?
10. ¿Consideras que Glottia ofrece una experiencia distinta frente a clases o apps tradicionales?
11. ¿Qué mejorarías en la app para sentirte más motivado o seguro al participar?
12. ¿Recomendarías Glottia a otros que estén aprendiendo un idioma? ¿Por qué?

---

###  Segmento Objetivo #2: Administradores de Establecimientos Asociados  

**Objetivo de la entrevista:**  
Comprender el nivel de interés, las expectativas y las percepciones sobre la colaboración con Glottia como punto de encuentro para prácticas presenciales.

**Preguntas:**

1. ¿Cómo te enteraste de la propuesta de Glottia?
2. ¿Qué opinas sobre la idea de que tu local sea un punto de encuentro para prácticas de idiomas?
3. ¿Crees que este tipo de actividades puede atraer nuevos clientes o aumentar el consumo?
4. ¿Qué tan alineada te parece la iniciativa de Glottia con la identidad y el ambiente de tu local?
5. ¿Qué condiciones considerarías importantes para que estas reuniones sean cómodas y seguras?
6. ¿Qué tipo de beneficios te motivarían a colaborar con Glottia (visibilidad, tráfico, reputación, fidelización)?
7. ¿Te interesaría que tu local aparezca dentro del mapa interactivo de la app?
8. ¿Qué tan importante consideras el posicionamiento digital o redes sociales para tu negocio?
9. ¿Cómo te gustaría que Glottia comunique tu establecimiento dentro de la plataforma (estilo, fotos, descripciones)?
10. ¿Has participado antes en iniciativas culturales o colaboraciones similares?
11. ¿Qué preocupaciones o dudas tendrías al recibir grupos de práctica en tu local?
12. ¿Qué expectativas tendrías sobre la organización y el comportamiento de los usuarios de Glottia?
13. ¿Qué sugerencias aportarías para que esta alianza sea beneficiosa tanto para el local como para la comunidad de usuarios?

---

### 4.3.2. Registro de Entrevistas
### 4.3.3. Evaluaciones según heurísticas

---

# Conclusiones

El análisis de entrevistas y hallazgos evidencia que existe una necesidad real y no cubierta en torno a la práctica de idiomas en contextos sociales. Los usuarios aprendices de idiomas expresan entusiasmo por mejorar su fluidez y confianza, pero enfrentan limitaciones en el acceso a espacios seguros, accesibles y organizados donde practicar. Asimismo, aunque utilizan tecnología en su vida diaria, la mayoría no cuenta con plataformas específicas para encuentros lingüísticos, lo que posiciona a Glottia como una oportunidad innovadora para liderar este nicho.

Por otro lado, los administradores de locales (cafeterías, restaurantes, coworkings y espacios culturales) perciben un valor positivo en ofrecer sus establecimientos como puntos de encuentro, ya que les permite atraer un público diverso, aumentar la afluencia en horarios valle y reforzar el posicionamiento cultural de sus marcas. Sin embargo, muestran preocupaciones claras respecto al consumo mínimo, control del tiempo y manejo del ruido, aspectos que deben ser regulados mediante las políticas de la plataforma para generar confianza y sostenibilidad en las alianzas.

En conjunto, los hallazgos indican que Glottia puede convertirse en un ecosistema de confianza y beneficio mutuo, donde los usuarios encuentren oportunidades inclusivas y accesibles para practicar idiomas, mientras los establecimientos ganan visibilidad y fidelización de clientes. La propuesta se fortalece al estar orientada a la construcción de comunidad, la seguridad de los espacios y la experiencia cultural compartida, factores que la diferencian de academias tradicionales y de aplicaciones exclusivamente virtuales.

---
#  Recomendaciones

- Fomentar una distribución más equitativa de tareas técnicas y documentales para asegurar un esfuerzo balanceado entre todos los miembros.
- Continuar con la validación frecuente de los avances con usuarios reales, especialmente antes de cada iteración, para mantener la alineación entre desarrollo y necesidades reales.
- Aprovechar las fortalezas individuales del equipo para asignar responsabilidades específicas que optimicen los tiempos de desarrollo.
- Documentar de manera más sistemática los aprendizajes y desafíos encontrados en cada sprint, para mejorar continuamente el proceso.
  
# Bibliografía

Carrillo-García, M. E., Cascales-Martínez, A., & Valero, A. L. (2018). Apps para el aprendizaje de idiomas en la Universidad de Murcia. Revista de Educación a Distancia (RED), (58). 
[https://revistas.um.es/red/article/view/351511/](https://revistas.um.es/red/article/view/351511/)

Palma, D. G. D., & Vázquez, M. E. M. (2023). Uso de aplicaciones móviles como herramienta de apoyo en el aprendizaje del idioma inglés. Ciencia Latina Revista Científica Multidisciplinar, 7(4), 2773-2788.
[https://ciencialatina.org/index.php/cienciala/article/view/7139/](https://ciencialatina.org/index.php/cienciala/article/view/7139/)

Cobos Guillén, C. G. (2023). Azuay Café: propuesta de una escuela cafetería en base de la metodología del aprender haciendo para las prácticas preprofesionales de los estudiantes de una carrera de turismo (Master's thesis, Universidad del Azuay).[https://dspace.uazuay.edu.ec/handle/datos/13362/](https://dspace.uazuay.edu.ec/handle/datos/13362/)

Dueñas-Mendoza, A. S., & Zaldumbide-Peralvo, D. A. Estrategias de marketing digital para cafeterías-restaurantes en Esmeraldas, Ecuador. Obtenido de, 593.
[https://www.academia.edu/download/117711219/2011.pdf/](https://www.academia.edu/download/117711219/2011.pdf/)
# Anexos
