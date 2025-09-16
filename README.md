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

| Versión | Fecha       | Autor(es)                                                                 | Descripción de modificación |
|---------|-------------|---------------------------------------------------------------------------|------------------------------|
|   TB1   | XX/09/2025  | Ethan Matias Aliaga Aguirre                                               | Realicé ... |
|   TB1   | XX/09/2025  | Leandro Saul Contreras López                                              | Realicé ... |
|   TB1   | XX/09/2025  | Italo Ludwing Sanchez Manrique                                            | Realicé ... |
|   TB1   | XX/09/2025  | Ivo Marcelo Machado Bracamonte                                            | Realicé ... |
|   TB1   | XX/09/2025  | Rodrigo Jesus Miraval Pomalaya                                            | Realicé ... |
|   TB1   | XX/09/2025  | Piero Francesco Tenorio Medina                                            | Realicé ... |
|   TB1   | XX/09/2025  | Arnold Gabriel Morales Sosa                                               | Realicé ... |

</div>

# Project Report Collaboration Insights  

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
    - [2.5.1. EvebtStorming](#251-event-storming)
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

# Student Outcome
| Criterio específico                                                   | Acciones realizadas                                                                                     | Conclusiones |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------ |
| Comunica oralmente con efectividad a diferentes rangos de audiencia   | **Nombre Apellido**<br>TB1<br>Texto<br><br>... | TB1: Texto   |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | **Nombre Apellido**<br>TB1<br>Texto<br><br>... | TB1: Texto   |

---

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
HampCoders es una startup innovadora que se enfoca en el desarrollo de soluciones empleando una arquitectura orientada a servicios, haciendo uso de tecnologías open-source. Mediante esta startup, buscamos conectar personas que desean practicar la comunicación en distintos idiomas, en grupo de manera presencial, en locales públicos que ofrezcan sus espacios como puntos de reunión. Es por eso que presentamos el proyecto “Glottia”.

### Misión:
Facilitar la práctica oral de idiomas a través de experiencias conversacionales reales, seguras y entretenidas, tanto en espacios públicos como virtuales, impulsando la confianza, la fluidez y la conexión entre personas con intereses lingüísticos comunes.

### Visión:
Convertirse en la comunidad global de referencia para la práctica de idiomas a través de conversaciones naturales, generando encuentros significativos entre personas que buscan mantener vivo un idioma a través del habla cotidiana y el intercambio cultural.


### 1.1.2. Perfiles de integrantes del equipo
| Foto | Código | Descripción |
|------|--------|-------------|
| ![Foto] | U202318731 | Soy Piero Tenorio... |
| ![Foto] | U202123843 | Soy Gianmarco Jiménez... |
| ![Foto] | UXXXXXXX | Texto de descripción |
| ![Foto] | UXXXXXXX | Texto de descripción |
| ![Foto] | UXXXXXXX | Texto de descripción |

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

Con el propósito de obtener una comprensión más profunda de las necesidades de nuestros usuarios, hemos investigado sus antecedentes históricos y los desafíos que enfrentan mediante la metodología de las 5W`S y 2H`S. Este enfoque nos asegura que la información recopilada sea pertinente y nos permita desarrollar soluciones precisas y eficaces que satisfagan sus necesidades.

#### What: 
La problemática que como equipo buscamos solucionar,  es que cada vez más los jóvenes adultos se interesan en aprender nuevos idiomas y establecer conexiones con personas de diferente cultura, ya sea para mejorar sus oportunidades laborales o ampliar sus horizontes personales. Sin embargo, encontrar espacios adecuados para practicar idiomas de manera regular social puede ser un reto. Las academias tradicionales suelen ser costosas o tener horarios poco flexibles, mientras que muchas plataformas en línea carecen de la interacción. Además tras la pandemia muchos jóvenes se han visto afectadas sus habilidades sociales o anhelan espacios ideales donde puedan relacionarse con personas que compartan su interés por contextos urbanos con acceso limitado a comunidades multiculturales. Esto es de suma importancia porque nos abre una oportunidad para mejorar nuestro aprendizaje de idiomas a través de entornos sociales que sean accesibles, inclusivos, seguros y dinámicos. Para eso debe ser en un lugar donde la gente pueda sentir satisfacción y comodidad para poder interactuar en este entorno. Según Cáceres (2022) implica que para poder aprender otros idiomas es adecuado poder encontrar un entorno donde la gente se encuentre cómoda y esté motivada a aprender,  de acuerdo con su investigación a la gente a la que ha estudiado un total de 374 personas el 28,10% suelen participar de forma voluntaria. Otro tema que se tiene en cuenta es la interacción con las personas ya que el 20,9% son quienes pueden interactuar mejor con las personas y aprender inglés en conjunto y aprender más acerca de las demás personas internacionalmente hablando dando a entender si se pone en práctica su conclusión se podrá enfrentar a esta situación. 

#### When:
El problema ocurre cuando una persona desea practicar un nuevo idioma de forma real y no encuentra un entorno adecuado para hacerlo. Según investigaciones pueden ser los siguientes casos: cuando se buscan alternativas a los institutos y academias tradicionales, requiere mejorar su fluidez oral así mismo  cuando experimentan frustración por la falta de un ambiente convencional para el aprendizaje. Segun Soncco (2022), afirma que los estudiantes encuentran una mejor forma de poder aprender su inglés mediante las tecnologías móviles así como también empleando muchas estrategias de evaluación para medir el nivel de 325 estudiantes de los cuales un 51,8% tiene un nivel medio asimismo se demostró que un 53,4% demostró tener mejoras en el inglés mediante estos aplicativos web en base a esta investigación demostraría que se puede aplicar landing page en especializada para potenciar las habilidades con respecto a otros idiomas. 

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
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo
### Segmento objetivo #1: Usuarios aprendices de idiomas

#### Aspectos demográficos:
Sexo: Masculino, femenino y no binario.
Edad: Entre 16 y 40 años (desde estudiantes de secundaria superior hasta jóvenes/adultos profesionales).
Nivel socioeconómico: Medio a medio-alto.

#### Aspectos geográficos:
Residen en áreas urbanas o metropolitanas con buena conectividad y vida cultural activa.
Se concentran en ciudades con alta población estudiantil, diversidad cultural o presencia de comunidades extranjeras.
Frecuentan espacios como universidades, bibliotecas, coworkings, cafeterías, bares, centros culturales y parques urbanos.

#### Aspectos psicográficos:
Tienen motivación tanto académica/profesional (certificaciones, prácticas, empleabilidad) como social/personal (viajar, conocer culturas, socializar).
Buscan fluidez, vocabulario conversacional y confianza al hablar en un entorno real.
Valoran experiencias auténticas, accesibles y presenciales fuera de un aula tradicional.
Son curiosos, abiertos, sociables y dispuestos a salir de su zona de confort.


## Segmento objetivo #2: Administradores que ofrecen su establecimiento como punto de reunión

#### Aspectos demográficos:
Perfil: Administradores, dueños o encargados de cafeterías, bares, restaurantes, coworkings y centros culturales.
Tipo de negocio: Establecimientos con espacios adecuados para grupos pequeños o medianos.
Ubicación: Zonas céntricas, estudiantiles o con alto tránsito de jóvenes/adultos interesados en socializar y aprender idiomas.

#### Aspectos geográficos:
Se encuentran en áreas urbanas y metropolitanas con vida cultural activa.
Están ubicados en distritos o barrios con alta concentración de estudiantes, profesionales jóvenes y comunidades extranjeras.
Sus locales suelen estar cerca de universidades, residencias estudiantiles, coworkings o zonas de ocio.

#### Aspectos psicográficos:
Buscan atraer nuevos clientes mediante experiencias innovadoras.
Están interesados en diferenciar su local con propuestas culturales y sociales.
Valoran el posicionamiento digital y la visibilidad que les brinda la app.
Quieren generar mayor consumo en su establecimiento a través de las reuniones organizadas.
Desean fidelizar clientes al vincular su espacio con un ambiente inclusivo, cultural e internacional.


---

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
### 2.2.3. Análisis de entrevistas

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

Language Learner (Aprendiz de idiomas)  
Persona que busca mejorar su fluidez, vocabulario y confianza al hablar un idioma extranjero mediante la práctica conversacional.

Host Administrator (Administrador de establecimiento)  
Dueño o encargado de un espacio físico (cafetería, coworking, bar, centro cultural) que ofrece su local como punto de encuentro para sesiones de práctica de idiomas.

Conversation Partner (Compañero de conversación)  
Usuario con quien se interactúa durante una sesión, emparejado según idioma, nivel de fluidez e intereses.

Event Organizer (Organizador de eventos)  
Persona o equipo responsable de coordinar encuentros temáticos, actividades culturales o dinámicas grupales dentro de Glottia.

Platform Administrator (Administrador de plataforma)  
Miembro del equipo de Glottia que gestiona usuarios, supervisa el cumplimiento de normas, valida perfiles y asegura el correcto funcionamiento del sistema.

---

## 2. Servicios y Experiencias

Language Meetup (Encuentro de idiomas)  
Reunión presencial en espacios públicos o locales aliados para practicar un idioma de manera informal y social.

Virtual Session (Sesión virtual)  
Conversación en línea, en tiempo real, entre dos o más usuarios de la plataforma.

Language Matchmaking (Emparejamiento lingüístico)  
Proceso de conectar a un aprendiz con compañeros de conversación adecuados según idioma, nivel y disponibilidad.

Cultural Event (Evento cultural)  
Actividad organizada que integra dinámicas multiculturales, juegos o celebraciones temáticas para enriquecer la práctica de idiomas.

Gamification Activity (Actividad de gamificación)  
Dinámica lúdica integrada en la plataforma para motivar la participación y el progreso del usuario.

---

## 3. Funcionalidades de la Plataforma

Booking (Reserva)  
Acción de un usuario para apartar un lugar en una sesión de práctica (presencial o virtual).

Verified Space (Espacio verificado)  
Estado de un establecimiento que ha sido validado por la plataforma como un lugar seguro y adecuado para encuentros.

Progress Tracking (Seguimiento de progreso)  
Registro del avance del usuario en términos de participación, niveles de fluidez y logros obtenidos.

Rating & Review (Calificación y reseña)  
Sistema de puntuación y comentarios que permite evaluar tanto la experiencia del usuario como del establecimiento anfitrión.

Loyalty Benefits (Beneficios de fidelización)  
Recompensas o ventajas otorgadas a usuarios recurrentes, como descuentos, accesos preferentes o reconocimientos.

---

## 4. Seguridad y Confianza

Safe Environment (Entorno seguro)  
Condición de que los encuentros —presenciales o virtuales— se desarrollan en espacios supervisados, confiables y respetuosos.

Community Guidelines (Normas de la comunidad)  
Reglas que regulan la conducta de los usuarios y administradores dentro de Glottia, promoviendo respeto e inclusión.

Identity Verification (Verificación de identidad)  
Proceso mediante el cual la plataforma confirma que el usuario o administrador es auténtico, evitando perfiles falsos.

Trust Badge (Insignia de confianza)  
Distintivo otorgado a usuarios o establecimientos que cumplen con los estándares de seguridad y calidad de Glottia.

---

## 5. Otros conceptos del dominio

Language Flow (Fluidez lingüística)  
Capacidad progresiva de expresarse de manera natural y coherente en un idioma extranjero.

Cultural Exchange (Intercambio cultural)  
Interacción entre personas de diferentes contextos culturales que fomenta el entendimiento mutuo y el aprendizaje más allá del idioma.

Hybrid Practice (Práctica híbrida)  
Modelo que combina encuentros presenciales con sesiones virtuales para ofrecer mayor flexibilidad a los usuarios.

Digital Presence (Presencia digital)  
Visibilidad de usuarios, establecimientos y eventos dentro de la aplicación y en los canales asociados a Glottia.



## 2.4. Requirements Specification

En este apartado se formalizan los requerimientos del sistema en formato estructurado y verificable. Se presenta el catálogo de requisitos, modelos de casos de uso, restricciones técnicas y condiciones de aceptación. Esta especificación servirá como base contractual entre el equipo de desarrollo y los interesados.

### 2.4.1. User Stories

# User Stories - Plataforma de Intercambio de Idiomas

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
### 2.4.3. Product Backlog

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming

El EventStorming es una técnica de brainstorming colaborativa y visual que se utiliza en el desarrollo de software, especialmente en el contexto de Domain-Driven Design (DDD). Su objetivo principal es ayudar a un equipo a entender y modelar un dominio de negocio complejo, identificando los eventos de dominio que ocurren en él. A continuación el equipo presenta el diseño del EventStorming.

![EventStorming](https://github.com/user-attachments/assets/7b4f333f-54bf-4ed7-abc0-a3d2c33a3238)

#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
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

Este diagrama desglosa el sistema Glottia en sus contenedores principales. Un contenedor representa una unidad desplegable o ejecutable, como una aplicación móvil, una API web o una base de datos. Muestra cómo se distribuyen las responsabilidades del sistema entre estos contenedores.

> [!IMPORTANT]
> Descripción de Contenedores:
> 
> - **Aplicación Móvil**: Construida en Flutter, es la interfaz principal para los Aprendices. Permite buscar eventos, reservar, hacer check-in y gestionar el perfil. Se comunica con el API Backend.
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
### 2.6.x. Bounded Context: <Bounded Context Name>
#### 2.6.x.1. Domain Layer
#### 2.6.x.2. Interface Layer
#### 2.6.x.3. Application Layer
#### 2.6.x.4. Infrastructure Layer
#### 2.6.x.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.x.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.x.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.x.6.2. Bounded Context Database Design Diagram

---

# Capítulo III: Solution UI/UX Design
## 3.1. Product Design
### 3.1.1. Style Guidelines
#### 3.1.1.1. General Style Guidelines
### 3.1.2. Information Architecture
#### 3.1.2.1. Organization Systems
#### 3.1.2.2. Labelling Systems
#### 3.1.2.3. SEO Tags and Meta Tags
#### 3.1.2.4. Searching Systems
#### 3.1.2.5. Navigation Systems
### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe
#### 3.1.3.2. Landing Page Mock-up
### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes
#### 3.1.4.2. Mobile Applications Wireflow Diagrams
#### 3.1.4.3. Mobile Applications Mock-ups
#### 3.1.4.4. Mobile Applications User Flow Diagrams
#### 3.1.4.5. Mobile Applications Prototyping

---

# Capítulo IV: Product Implementation & Validation
## 4.1. Software Configuration Management
### 4.1.1. Software Development Environment Configuration
### 4.1.2. Source Code Management
### 4.1.3. Source Code Style Guide & Conventions
### 4.1.4. Software Deployment Configuration

## 4.2. Landing Page & Mobile Application Implementation
### 4.2.1. Sprint n
#### 4.2.1.1. Sprint Planning n
#### 4.2.1.2. Sprint Backlog n
#### 4.2.1.3. Development Evidence for Sprint Review
#### 4.2.1.4. Testing Suite Evidence for Sprint Review
#### 4.2.1.5. Execution Evidence for Sprint Review
#### 4.2.1.6. Services Documentation Evidence for Sprint Review
#### 4.2.1.7. Software Deployment Evidence for Sprint Review
#### 4.2.1.8. Team Collaboration Insights during Sprint

## 4.3. Validation Interviews
### 4.3.1. Diseño de Entrevistas
### 4.3.2. Registro de Entrevistas
### 4.3.3. Evaluaciones según heurísticas

---

# Conclusiones
# Conclusiones y recomendaciones
# Video About-the-Team
# Bibliografía
# Anexos
