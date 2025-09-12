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
> Contexto del problema que se quiere resolver.

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
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

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

### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. Ubiquitous Language

## 2.4. Requirements Specification
### 2.4.1. User Stories
### 2.4.2. Impact Mapping
### 2.4.3. Product Backlog

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams

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
