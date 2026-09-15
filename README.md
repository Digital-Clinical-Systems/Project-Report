<div align="center">
  <img src="logo_upc.png" alt="Logo UPC" width="300">
  <br>
  <h3>Universidad Peruana de Ciencias Aplicadas</h3>
  <h4>Facultad de Ingeniería</h4>
  <h4>Carrera de Ingeniería de Software</h4>
  <br>
  <h4>Ciclo 2026-20</h4>
  <br>
  <h4>1ASI0729 - Desarrollo de Aplicaciones Open Source</h4>
  <h4>NRC: [Ingresar NRC]</h4>
  <h4>Profesor: [Ingresar Nombre del Profesor]</h4>
  <br>
  <h2>Informe de Trabajo Final</h2>
  <br>
  <h3>Startup: [Nuevo Nombre de la Startup]</h3>
  <h3>Producto: [Nuevo Nombre del Producto]</h3>
  <br>
  <h4>Integrantes:</h4>
  <ul style="list-style-type: none; padding: 0;">
    <li>[Código 1] - [Apellidos, Nombres 1]</li>
    <li>[Código 2] - [Apellidos, Nombres 2]</li>
    <li>[Código 3] - [Apellidos, Nombres 3]</li>
    <li>[Código 4] - [Apellidos, Nombres 4]</li>
  </ul>
  <br>
  <h4>[Mes], [Año]</h4>
</div>

---

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| 1.0     | [Fecha] | [Autor] | Versión inicial del documento (Estructura base) |

---

## Project Report Collaboration Insights

URL del repositorio: `[URL del Repositorio de GitHub para el Informe]`

*(En esta sección se explicará cómo se han desarrollado las actividades de elaboración del informe y se presentarán capturas de los analíticos de colaboración y commits en GitHub).*

---

## Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
      - [Organización de la Landing Page](#organización-de-la-landing-page)
      - [Organización de la Web Application](#organización-de-la-web-application)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
      - [Convenciones de etiquetado](#convenciones-de-etiquetado)
      - [Correspondencia entre el dominio y la interfaz](#correspondencia-entre-el-dominio-y-la-interfaz)
      - [Etiquetado de estados](#etiquetado-de-estados)
      - [Etiquetado de la Landing Page](#etiquetado-de-la-landing-page)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
      - [Landing Page](#landing-page)
      - [Etiquetas Open Graph y Twitter Card](#etiquetas-open-graph-y-twitter-card)
      - [Reglas aplicadas](#reglas-aplicadas)
      - [Exclusión de la Web Application](#exclusión-de-la-web-application)
    - [4.2.4. Searching Systems](#424-searching-systems)
      - [Landing Page](#landing-page-1)
      - [Web Application](#web-application)
      - [Criterios de filtrado por vista](#criterios-de-filtrado-por-vista)
      - [Comportamiento de la búsqueda](#comportamiento-de-la-búsqueda)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
      - [Navegación de la Landing Page](#navegación-de-la-landing-page)
      - [Navegación de la Web Application](#navegación-de-la-web-application)
      - [Tipos de navegación empleados](#tipos-de-navegación-empleados)
      - [Ruta de migas](#ruta-de-migas)
      - [Verificación de la restricción de dos interacciones](#verificación-de-la-restricción-de-dos-interacciones)
      - [Consideraciones de accesibilidad en la navegación](#consideraciones-de-accesibilidad-en-la-navegación)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  - [Anexo A. Videos de Exposiciones](#anexo-a-videos-de-exposiciones)

---

## Student Outcome
**ABET - EAC - Student Outcome 3**
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

El curso contribuye al cumplimiento del Student Outcome ABET. En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | **[Apellidos, Nombres 1]**<br>AV1: [Acción 1]<br>AV2: [Acción 2] | *(Conclusión grupal sobre la mejora en comunicación oral y medios audiovisuales)* |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | **[Apellidos, Nombres 1]**<br>AV1: [Acción 1]<br>AV2: [Acción 2] | *(Conclusión grupal sobre redacción técnica, calidad de entregables e idioma)* |

---

## Capítulo I: Introducción
### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup
#### 1.1.2. Perfiles de integrantes del equipo
### 1.2. Solution Profile
#### 1.2.1 Antecedentes y problemática
#### 1.2.2 Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
##### 1.2.2.2. Lean UX Assumptions
##### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.4. Lean UX Canvas
### 1.3. Segmentos objetivo

---

## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores
#### 2.1.1. Análisis competitivo
#### 2.1.2. Estrategias y tácticas frente a competidores
### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas
#### 2.2.2. Registro de entrevistas
#### 2.2.3. Análisis de entrevistas
### 2.3. Needfinding
#### 2.3.1. User Personas
#### 2.3.2. User Task Matrix
#### 2.3.3. User Journey Mapping
#### 2.3.4. Empathy Mapping
### 2.4. Big Picture Event Storming
### 2.5. Ubiquitous Language

---

## Capítulo III: Requirements Specification
### 3.1. User Stories
### 3.2. Impact Mapping
### 3.3. Product Backlog

---

## Capítulo IV: Product Design
### 4.1. Style Guidelines
#### 4.1.1. General Style Guidelines

El diseño de estilo de ClinicalSync se fundamenta en transmitir seguridad, eficiencia y profesionalismo, valores indispensables para una solución digital orientada al sector salud. Este busca dar una identidad gráfica moderna, ordenada y amigable para el usuario con el propósito de mejorar la comunicación clínica y la comodidad de los pacientes.

* Colores: La paleta de colores emplea un azul noche (#172554) para transmitir autoridad clínica, un verde esmeralda (#10B981), siendo este un color con acento tecnológico para destacar acciones exitosas y confirmaciones de traspasos SBAR, un gris pálido (#64748B) para los textos secundarios y elementos inactivos, con esto estableciendo una jerarquía visual clara para el usuario. Por último, se emplea un blanco puro (#FFFFFF) para generar un mayor contraste y evitar la fatiga visual.

* Tipografia: Se utilizan fuentes de letras sans-serif debido a su simpleza, alta legibilidad, claridad y una apariencia profesional.

* Distribución y espaciado: La interfaz adopta una arquitectura de bloques bien definidos, con un espaciado consistente y una jerarquía visual estricta. La información se presenta de manera progresiva, permitiendo que el usuario identifique fácilmente el propósito de cada módulo.

* Iconografía: Se utilizan iconos minimalistas y universalmente reconocibles en el ámbito médico y de comunicación asistencial. Esto reduce la complejidad de interpretación y acelera el reconocimiento visual de los flujos de trabajo cardiovasculares.
  
#### 4.1.2. Web Style Guidelines

El diseño web de ClinicalSync se implementa como una solución digital orientada al sector salud, buscando que tanto la Landing Page como la Web App mantengan una experiencia uniforme, clara, responsiva y accesible. El objetivo es asegurar una interfaz confiable que facilite la interacción de visitantes, personal de enfermería cardiovascular y médicos especialistas.

* **Diseño adaptable:** La interfaz se ajusta a distintos dispositivos (Escritorio, Laptop o móvil), manteniendo consistencia visual entre la landing page y la web application. Esto permite que los usuarios puedan registrar información clínica y consultar traspasos SBAR desde cualquier entorno de trabajo hospitalario.
  
* **Componentes de interfaz:** Los botones principales utilizan los colores como verde esmeralda (#10B981) o azul noche (#172554) para resaltar acciones críticas como guardar un registro, mientras que los elementos secundarios mantienen un estilo neutral en gris pálido. Esto establece una jerarquía visual que permite identificar con rapidez las acciones prioritarias.
  
* **Notificaciones y estados:** Los mensajes del sistema utilizan convenciones visuales claras para comunicar el estado de una acción o proceso. Los estados positivos se muestran en verde para indicar un guardado exitoso, las advertencias en amarillo para señalar pendientes y los errores o alertas en rojo.
  
* **Tablas y dashboards:** Se prioriza una presentación clara y ordenada de la información dentro de tablas y paneles de control, facilitando la consulta rápida del historial clínico. La organización visual de los registros y signos vitales permite que el médico interprete la evolución del paciente de manera más eficiente y rápida.
  
* **Accesibilidad:** Se consideran contrastes adecuados entre la tipografía y los fondos, además de una disposición clara del contenido. Se busca mantener una navegación sencilla y legible que reduzca la fatiga visual del personal durante las guardias, fortaleciendo la usabilidad general de la web app.
  
### 4.2. Information Architecture

La arquitectura de información define cómo se organiza, se nombra, se busca y se recorre el contenido de ClinicalSync. Su propósito es que cada usuario encuentre lo que necesita en el menor número de pasos posible, criterio que no es estético sino operativo: en el Capítulo II quedó establecido que el personal de enfermería registra durante la atención y que el médico especialista pierde tiempo reconstruyendo el estado del paciente desde varias fuentes.

La solución comprende dos productos con audiencias y objetivos distintos, por lo que su arquitectura se define por separado.

| Producto | Audiencia | Objetivo de la arquitectura |
|---|---|---|
| **Landing Page** | Visitantes y decisores institucionales que aún no conocen el producto. | Conducir al visitante desde el problema hasta la solicitud de una demostración, en una lectura lineal y sin autenticación. |
| **Web Application** | Personal de enfermería cardiovascular y médicos especialistas, autenticados y con un rol asignado. | Minimizar los pasos de las tareas frecuentes del turno y permitir localizar información clínica en segundos. |

Las decisiones de esta sección se apoyan en tres insumos previos: el vocabulario fijado en el Ubiquitous Language (sección 2.5), que determina cómo se nombran los elementos de la interfaz; la User Task Matrix (sección 2.3.2), que indica qué tareas son más frecuentes y por lo tanto deben estar más accesibles; y las User Stories del Capítulo III, que delimitan qué contenido existe realmente en cada producto.

#### 4.2.1. Organization Systems

Los sistemas de organización determinan cómo se agrupa el contenido y bajo qué lógica se relaciona. ClinicalSync combina tres esquemas, cada uno aplicado donde resulta más natural para el usuario.

| Esquema de organización | Dónde se aplica | Justificación |
|---|---|---|
| **Secuencial (por pasos)** | Landing Page y formulario de traspaso SBAR. | El visitante necesita recorrer un argumento en orden: problema, solución, funcionamiento, beneficios y contacto. El traspaso SBAR es secuencial por definición del formato: situación, antecedentes, evaluación y recomendación. |
| **Jerárquico (de lo general a lo particular)** | Web Application. | El profesional parte de sus pacientes asignados, entra a un paciente y desde ahí accede a sus registros. Cada nivel acota el anterior. |
| **Cronológico** | Evolución clínica, eventos, bitácora de trazabilidad e historial de indicaciones. | En el dominio clínico el orden temporal es la relación más significativa entre registros: lo que importa es qué ocurrió antes y qué después. |
| **Matricial (por múltiples atributos)** | Listados filtrables de pacientes, eventos y bitácora. | Un mismo conjunto de registros debe poder recorrerse por paciente, por tipo de acción, por responsable o por rango de fechas, según lo que el profesional esté buscando. |

##### Organización de la Landing Page

El contenido se dispone en una sola página de desplazamiento vertical, con secciones autónomas y un orden argumental que va del problema a la acción:

1. Presentación y propuesta de valor.
2. El problema de la información clínica dispersa en unidades cardiovasculares.
3. Cómo funciona ClinicalSync, en pasos.
4. Características principales.
5. Beneficios, diferenciados por perfil.
6. Planes y modelo de servicio.
7. Preguntas frecuentes.
8. Equipo de desarrollo.
9. Formulario de contacto y solicitud de demostración.

La estructura es deliberadamente plana: no existen subpáginas, de modo que el visitante puede recorrer todo el argumento sin abandonar la página ni perder el contexto.

##### Organización de la Web Application

El contenido se organiza en cuatro niveles de profundidad. La restricción de diseño es que ninguna tarea de frecuencia muy alta según la User Task Matrix supere el segundo nivel.

| Nivel | Contenido | Ejemplo |
|---|---|---|
| **1. Turno** | Panel inicial con los pacientes asignados al profesional durante su turno. | Lista de pacientes con su estado y alertas activas. |
| **2. Paciente** | Ficha del paciente con su resumen clínico y accesos a cada tipo de registro. | Últimos signos vitales, indicaciones vigentes, eventos recientes. |
| **3. Tipo de registro** | Colección de un tipo específico dentro del paciente. | Historial de signos vitales, traspasos, medicación administrada. |
| **4. Registro individual** | Detalle de una entrada, con su responsable, su marca temporal y su historial de cambios. | Una toma de signos vitales puntual, un traspaso SBAR determinado. |

El agrupamiento responde al rol del usuario. El personal de enfermería accede a una organización centrada en la captura, donde las acciones de registro están disponibles desde el nivel del paciente sin navegación adicional. El médico especialista accede a una organización centrada en la consulta, donde el resumen clínico consolidado ocupa el nivel del paciente y los registros individuales quedan como profundización opcional.

#### 4.2.2. Labeling Systems

El sistema de etiquetado define cómo se nombran las secciones, las acciones y los datos en la interfaz. En ClinicalSync la regla de fondo es que **la interfaz usa el vocabulario del Ubiquitous Language definido en la sección 2.5**, no una traducción libre ni terminología técnica. Si el personal de enfermería dice "traspaso de turno", la aplicación no debe decir "transferencia de guardia" ni "handover".

##### Convenciones de etiquetado

| Convención | Regla | Ejemplo correcto | Ejemplo a evitar |
|---|---|---|---|
| **Idioma** | Toda la interfaz visible se rotula en español; el inglés queda reservado para el código y la documentación técnica. | Signos vitales | Vital Signs |
| **Consistencia con el dominio** | Cada etiqueta corresponde a un término del Ubiquitous Language. | Traspaso SBAR | Reporte de cambio |
| **Acciones en infinitivo** | Los botones nombran la acción que ejecutan. | Registrar signos vitales | Signos vitales |
| **Brevedad** | Las etiquetas de navegación no superan las tres palabras. | Mis pacientes | Listado de pacientes asignados al turno |
| **Sin abreviaturas ambiguas** | Solo se abrevia lo que es estándar del dominio clínico. | UCI, SBAR, FC | Trasp., Med. |
| **Estados explícitos** | Los estados se nombran con una palabra que el usuario pueda interpretar sin leyenda. | Pendiente, Confirmado, Vencido | Estado 1, Estado 2 |

##### Correspondencia entre el dominio y la interfaz

| Término del dominio (2.5) | Etiqueta en la interfaz | Dónde aparece |
|---|---|---|
| Assigned Patient | Mis pacientes | Navegación principal de la Web App |
| Patient Status | Estado del paciente | Ficha del paciente y listado del turno |
| Vital Signs | Signos vitales | Sección de registro y de historial |
| Clinical Event | Eventos clínicos | Sección de registro y de historial |
| Medication Administration | Medicación administrada | Sección de registro |
| Shift Handover | Traspaso de turno | Navegación principal |
| SBAR Report | Traspaso SBAR | Formulario y listado de traspasos |
| Situation / Background / Assessment / Recommendation | Situación / Antecedentes / Evaluación / Recomendación | Secciones del formulario SBAR |
| Medical Indication | Indicaciones médicas | Ficha del paciente |
| Indication Compliance | Cumplimiento | Acción y estado dentro de una indicación |
| Clinical Alert | Alertas | Distintivo en el listado del turno y en la ficha |
| Clinical Evolution | Evolución clínica | Vista de consulta del médico especialista |
| Audit Trail | Bitácora | Sección de auditoría del paciente |
| Responsible Staff | Registrado por | Pie de cada registro individual |
| Timestamp | Fecha y hora | Pie de cada registro individual |

##### Etiquetado de estados

Los estados se rotulan con una sola palabra y se refuerzan con el color definido por Johnny en las Web Style Guidelines (sección 4.1.2), nunca solo con color, para no depender de la percepción cromática del usuario.

| Estado | Etiqueta | Refuerzo visual | Dónde se usa |
|---|---|---|---|
| Registro guardado correctamente | Guardado | Verde esmeralda | Confirmación de cualquier registro |
| Traspaso emitido y aún no recibido | Pendiente | Amarillo | Listado de traspasos |
| Traspaso recibido por el turno entrante | Confirmado | Verde esmeralda | Listado de traspasos |
| Indicación emitida y no ejecutada | Pendiente | Amarillo | Indicaciones del paciente |
| Indicación fuera de su plazo previsto | Vencida | Rojo | Indicaciones del paciente |
| Paciente con alerta activa | Requiere atención | Rojo | Listado del turno |
| Documentación incompleta al cierre | Incompleto | Amarillo | Resumen de cierre de turno |

##### Etiquetado de la Landing Page

Las secciones del sitio promocional se rotulan con lenguaje orientado al visitante, que no conoce el producto ni su vocabulario interno. Se emplean los rótulos Inicio, El problema, Cómo funciona, Características, Beneficios, Planes, Preguntas frecuentes, Equipo y Contacto. Se evita nombrar módulos internos del sistema en esta capa, ya que para el visitante son conceptos sin referente.

#### 4.2.3. SEO Tags and Meta Tags

La estrategia de posicionamiento aplica únicamente a la Landing Page. La Web Application opera detrás de autenticación y maneja información clínica, por lo que **debe quedar explícitamente excluida de la indexación**: no existe beneficio en que un buscador alcance sus rutas y sí un riesgo de exposición.

##### Landing Page

| Etiqueta | Contenido propuesto |
|---|---|
| `<title>` | ClinicalSync — Traspaso de turno y trazabilidad clínica cardiovascular |
| `<meta name="description">` | Plataforma web que estandariza el traspaso de turno con SBAR, agiliza el registro de signos vitales y garantiza la trazabilidad de cada acción clínica en unidades cardiovasculares. |
| `<meta name="keywords">` | traspaso de turno, SBAR, registro clínico, signos vitales, trazabilidad clínica, unidad cardiovascular, UCI cardiovascular, software clínico |
| `<meta name="author">` | Digital Clinical System |
| `<meta name="robots">` | index, follow |
| `<meta http-equiv="Content-Language">` | es-PE |
| `<link rel="canonical">` | URL pública de la landing page |
| `<html lang>` | es, alternando a en cuando el visitante cambia el idioma |

##### Etiquetas Open Graph y Twitter Card

Se incorporan para que el enlace se previsualice correctamente cuando se comparta por mensajería o correo, que es la vía habitual por la que un contacto institucional recibe la referencia.

| Etiqueta | Contenido propuesto |
|---|---|
| `og:title` | ClinicalSync — Continuidad clínica en unidades cardiovasculares |
| `og:description` | Estandariza el traspaso SBAR, registra signos vitales en segundos y deja constancia de quién hizo qué y cuándo. |
| `og:type` | website |
| `og:url` | URL pública de la landing page |
| `og:image` | Imagen de previsualización de 1200 × 630 px |
| `og:locale` | es_PE, con `og:locale:alternate` en en_US |
| `twitter:card` | summary_large_image |

##### Reglas aplicadas

- El `title` se mantiene por debajo de 60 caracteres y la `description` entre 140 y 160, para que no se trunquen en los resultados de búsqueda.
- Cada sección de la landing usa un único `<h1>` y jerarquiza el resto con `<h2>` y `<h3>`, sin saltar niveles.
- Toda imagen lleva `alt` descriptivo, lo que sirve simultáneamente al posicionamiento y a la accesibilidad comprometida en la sección 4.1.2.
- Las dos versiones de idioma se declaran con `hreflang`, en coherencia con la historia US-11 del backlog.
- Se publica un `sitemap.xml` con las secciones de la landing y un `robots.txt` que permite el rastreo del sitio promocional.

##### Exclusión de la Web Application

```
User-agent: *
Allow: /
Disallow: /app/
Disallow: /api/
Sitemap: https://<dominio>/sitemap.xml
```

Adicionalmente, las vistas de la aplicación incluyen `<meta name="robots" content="noindex, nofollow">`, de modo que la exclusión no dependa únicamente del `robots.txt`, que es una convención que los rastreadores pueden ignorar.

#### 4.2.4. Searching Systems

Las necesidades de búsqueda son distintas en cada producto y deben resolverse con mecanismos proporcionales a su complejidad real.

##### Landing Page

No incorpora un buscador. El contenido cabe en una sola página y un motor de búsqueda añadiría un elemento que el visitante no espera. La localización de contenido se resuelve con la navegación ancla descrita en 4.2.5 y con la sección de preguntas frecuentes, que agrupa las dudas más habituales.

##### Web Application

La búsqueda es una necesidad operativa concreta: durante el turno el profesional necesita llegar a un paciente o a un registro sin recorrer listados. Los mecanismos previstos son tres, en orden de inmediatez.

| Mecanismo | Qué resuelve | Dónde opera | Historia relacionada |
|---|---|---|---|
| **Búsqueda por paciente** | Localizar a un paciente por nombre o número de historia clínica. | Barra superior, disponible desde cualquier vista. | US-17 |
| **Filtros sobre listados** | Acotar un conjunto de registros por uno o más atributos. | Listado del turno, traspasos, indicaciones, eventos y bitácora. | US-14, US-23, US-27, US-30 |
| **Ordenamiento** | Reorganizar un listado ya acotado. | Todos los listados. | US-29 |

##### Criterios de filtrado por vista

| Vista | Filtros disponibles |
|---|---|
| Pacientes del turno | Estado del paciente, presencia de alertas activas, indicaciones pendientes |
| Traspasos de turno | Paciente, turno, estado (pendiente o confirmado), rango de fechas |
| Signos vitales | Paciente, rango de fechas, parámetro |
| Eventos clínicos | Paciente, criticidad, responsable, rango de fechas |
| Indicaciones médicas | Paciente, estado (vigente, pendiente, cumplida, vencida), médico emisor |
| Bitácora de auditoría | Paciente, tipo de acción, responsable, rango de fechas |

##### Comportamiento de la búsqueda

- Los resultados se muestran mientras el usuario escribe, a partir del tercer carácter, para reducir el número de interacciones.
- La búsqueda ignora mayúsculas y tildes, de modo que "Muñoz" y "munoz" devuelvan el mismo resultado.
- El alcance respeta el rol y el turno: un profesional no obtiene resultados de pacientes que no tiene asignados.
- Cuando no hay coincidencias, el sistema indica el criterio aplicado y ofrece limpiar los filtros, en lugar de mostrar un listado vacío sin explicación.
- Los filtros activos permanecen visibles, para que el usuario no interprete un listado filtrado como el conjunto completo. Esta regla es deliberada: en un contexto clínico, creer que se está viendo la totalidad de los registros cuando en realidad hay un filtro aplicado constituye un riesgo, no solo una molestia.

#### 4.2.5. Navigation Systems

El sistema de navegación define cómo el usuario se desplaza entre los contenidos organizados en 4.2.1. ClinicalSync emplea navegación global, local y contextual, y su diseño responde a una restricción tomada de la User Task Matrix: **las tareas de frecuencia muy alta deben alcanzarse en un máximo de dos interacciones desde el punto de entrada.**

##### Navegación de la Landing Page

Al tratarse de una página única, la navegación es de tipo ancla: cada elemento del menú desplaza a la sección correspondiente sin recargar.

```
Landing Page
├── Barra superior (fija al desplazar)
│   ├── Inicio
│   ├── El problema
│   ├── Cómo funciona
│   ├── Características
│   ├── Beneficios
│   ├── Planes
│   ├── Preguntas frecuentes
│   ├── Selector de idioma (ES / EN)
│   └── [Solicitar demostración]  ← acción principal, destacada
└── Pie de página
    ├── Equipo
    ├── Contacto
    ├── Repositorio del proyecto
    └── Aviso de privacidad
```

La barra permanece fija durante el desplazamiento para que la acción principal esté siempre disponible, sin obligar al visitante a volver al inicio. En pantallas reducidas el menú colapsa en un icono desplegable, conforme a la historia US-12.

##### Navegación de la Web Application

La navegación global se presenta en una barra lateral persistente cuyo contenido **depende del rol del usuario**. Esto responde directamente a la conclusión de la sección 2.3.1: el personal de enfermería produce información y el médico especialista la consume, de modo que una navegación idéntica para ambos obligaría a uno de los dos perfiles a atravesar opciones que no utiliza.

```
Web Application
├── Barra superior (persistente)
│   ├── Buscar paciente
│   ├── Alertas activas
│   └── Perfil y cierre de sesión
│
├── Barra lateral — perfil Enfermería
│   ├── Mis pacientes          ← vista de inicio
│   ├── Traspaso de turno
│   │   ├── Recibir traspaso
│   │   └── Entregar traspaso
│   ├── Indicaciones pendientes
│   └── Cierre de turno
│
├── Barra lateral — perfil Médico especialista
│   ├── Mis pacientes          ← vista de inicio
│   ├── Evolución clínica
│   ├── Indicaciones
│   └── Bitácora
│
└── Dentro de un paciente (navegación local por pestañas)
    ├── Resumen
    ├── Signos vitales
    ├── Medicación
    ├── Eventos clínicos
    ├── Indicaciones
    ├── Traspasos
    └── Bitácora
```

##### Tipos de navegación empleados

| Tipo | Implementación | Función |
|---|---|---|
| **Global** | Barra lateral persistente, adaptada al rol. | Acceso a las áreas principales desde cualquier punto. |
| **Local** | Pestañas dentro de la ficha del paciente. | Desplazamiento entre los tipos de registro sin abandonar el paciente. |
| **Contextual** | Acciones de registro ubicadas dentro de la vista donde el dato se consulta. | Permite registrar en el momento y en el lugar donde surge la necesidad, sin navegar a otro módulo. |
| **Suplementaria** | Ruta de migas y botón de retorno. | Indica dónde está el usuario dentro de la jerarquía y cómo volver. |

##### Ruta de migas

Presente en todas las vistas de la Web Application a partir del segundo nivel, refleja la jerarquía definida en 4.2.1:

```
Mis pacientes  ›  Rosa Medina (Cama 4)  ›  Signos vitales  ›  Registro del 12/09 14:30
```

##### Verificación de la restricción de dos interacciones

| Tarea (frecuencia muy alta según 2.3.2) | Recorrido | Interacciones |
|---|---|---|
| Consultar los pacientes asignados | Es la vista de inicio tras iniciar sesión | 0 |
| Registrar signos vitales | Paciente → Registrar signos vitales | 2 |
| Registrar administración de medicamento | Paciente → Registrar medicación | 2 |
| Consultar el traspaso del turno anterior | Traspaso de turno → Recibir traspaso | 2 |
| Consultar el resumen clínico del paciente | Paciente → Resumen (pestaña activa por defecto) | 1 |
| Revisar indicaciones vigentes | Paciente → Indicaciones | 2 |

Ninguna de las tareas críticas supera las dos interacciones, lo que cumple el criterio establecido al inicio de esta sección y responde a la exigencia recogida en las entrevistas: que la herramienta sea al menos tan rápida como la anotación en papel a la que busca reemplazar.

##### Consideraciones de accesibilidad en la navegación

En coherencia con lo comprometido en la sección 4.1.2, la navegación es operable por teclado en su totalidad, con un orden de tabulación que sigue el orden visual. El elemento activo se identifica con un indicador de foco visible y no únicamente por color. Se incluye un enlace para saltar al contenido principal, de modo que quien navegue con lector de pantalla no deba recorrer la barra lateral en cada vista.

### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe

<p align="center">
  <img src="assets/chapter-4/Wireframe1.png" alt="WireFrame1" width="800">
</p>


<p align="center">
  <img src="assets/chapter-4/Wireframe 2.png" alt="Wireframe2" width="800">
</p>


<p align="center">
  <img src="assets/chapter-4/Wireframe 3.png" alt="Wireframe3" width="800">
</p>


<p align="center">
  <img src="assets/chapter-4/Wireframe 4.png" alt="Wireframe4" width="800">
</p>


#### 4.3.2. Landing Page Mock-up

<p align="center">
  <img src="assets/chapter-4/Mock-up 1.png" alt="MockUp1" width="800">
</p>


<p align="center">
  <img src="assets/chapter-4/Mock-up 2.png" alt="MockUp2" width="800">
</p>


<p align="center">
  <img src="assets/chapter-4/Mock-up 3.png" alt="MockUp3" width="800">
</p>


<p align="center">
  <img src="assets/chapter-4/Mock-up 4.png" alt="MockUp4" width="800">
</p>

### 4.4. Web Applications UX/UI Design

La Web Application de ClinicalSync fue diseñada para centralizar y apoyar los flujos clínicos relacionados con el registro, consulta y trazabilidad de la información en áreas cardiovasculares. La experiencia de usuario prioriza la claridad visual, la reducción de la carga operativa y el acceso ágil a las acciones principales, respondiendo a la necesidad del personal de enfermería y de los médicos especialistas de interactuar en entornos de alta presión donde el tiempo y la precisión son críticos.

Los wireframes, wireflows, mock-ups y diagramas de flujo de usuario se organizan alrededor de los módulos principales de la plataforma, adaptados a los distintos roles: el dashboard clínico (Mis pacientes), el monitoreo de signos vitales, los traspasos de turno estructurados mediante la metodología SBAR, el registro de eventos clínicos, la bitácora y la elección de planes de suscripción. Estos artefactos permiten evidenciar la relación entre las User Stories, los flujos de interacción y la implementación final de la Web Application.

#### 4.4.1. Web Applications Wireframes
<p align="center">
  <img src="assets/chapter-4/WireframeWeb1.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb2.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb3.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb4.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb5.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb6.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb7.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb8.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb9.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb10.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/WireframeWeb11.jpg" alt="WireframeWeb1" width="800">
</p>

#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb1.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb2.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb3.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb4.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb5.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb6.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb7.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb8.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb9.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb10.jpg" alt="WireframeWeb1" width="800">
</p>

<p align="center">
  <img src="assets/chapter-4/Mock-upWeb11.jpg" alt="WireframeWeb1" width="800">
</p>

#### 4.4.4. Web Applications User Flow Diagrams
### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
A partir de lo que trabajamos en el Big Picture Event Storming, en esta sección detallamos el diseño de nuestra arquitectura usando Domain-Driven Design (DDD). Aquí definimos los Bounded Contexts, los agregados, eventos y comandos, y finalmente mostramos la estructura del sistema aplicando el Modelo C4.
#### 4.6.1. Design-Level Event Storming
Para bajar al detalle técnico, armamos una sesión de Design-Level Event Storming. Esto nos sirvió para pasar del flujo general del negocio a los componentes reales de software, identificando qué comandos disparan qué eventos y en qué contextos viven.

**Objetivo de la sesión**
Nos enfocamos en desglosar el flujo clínico de la UCI Cardiovascular en eventos concretos, agrupar las responsabilidades en Bounded Contexts y definir las reglas (políticas) que el sistema ClinicalSync debe respetar de manera interna.

**Paso 1: Recolección de Domain Events**
Primero identificamos los eventos de dominio clave para el negocio, redactándolos siempre en pasado. Los eventos detectados para ClinicalSync fueron:

- Información clínica entregada al nuevo turno
- Turno anterior finalizado
- Pacientes asignados revisados
- Estado inicial del paciente verificado
- Signos vitales registrados
- Signos vitales monitoreados
- Medicamento administrado
- Indicación médica revisada
- Evolución reciente del paciente revisada
- Evolución posterior monitoreada
- Evento clínico relevante detectado
- Cambio crítico identificado
- Médico informado sobre cambio clínico
- Cumplimiento de indicación registrado
- Medicación e indicaciones validadas
- Información clínica consultada por el médico
- Nueva indicación médica registrada
- Indicación ejecutada por enfermería

**Paso 2: Identificación de Bounded Contexts**
Luego agrupamos estos eventos para separar correctamente las responsabilidades de la plataforma:

*   **BC-01: Security & Shared Kernel (IAM) Context — Subdominio Genérico**
    Se encarga de la seguridad y de que solo el personal autorizado acceda al sistema.
    *Domain Events clave:* Usuario autenticado, Rol asignado, Sesión iniciada.

*   **BC-02: Patients Context — Subdominio de Soporte**
    Maneja los datos básicos y la admisión de los pacientes. Actúa como el directorio maestro.
    *Domain Events clave:* Paciente admitido, Datos demográficos registrados, Estado actualizado.

*   **BC-03: Vital Signs Context — Core Domain**
    Es el núcleo de ClinicalSync. Aquí se registran y evalúan los signos vitales en tiempo real.
    *Domain Events clave:* Signos vitales registrados, Nivel de riesgo clínico evaluado.

*   **BC-04: Critical Events & Alerts Context — Core Domain**
    Controla el ciclo de vida de las alertas médicas cuando hay anomalías.
    *Domain Events clave:* Alerta crítica generada, Alerta atendida, Alerta resuelta.

*   **BC-05: Handover (SBAR) Context — Trazabilidad Clínica**
    Se encarga de estructurar y guardar los traspasos de turno usando el modelo SBAR.
    *Domain Events clave:* Entrega SBAR registrada, Turno finalizado, Acuse de recibo confirmado.

*   **BC-06: Audit Logs Context — Subdominio de Soporte**
    Guarda un registro inmutable de todo lo que hacen los usuarios para mantener la trazabilidad.
    *Domain Events clave:* Log de auditoría creado, Operación clínica registrada.

*   **BC-07: Physicians & Treatments Context — Subdominio de Soporte**
    Administra el catálogo de médicos y el historial cronológico de los tratamientos.
    *Domain Events clave:* Médico asignado, Tratamiento prescrito, Historial actualizado.

**Paso 3: Identificación de Comandos y Políticas**
- **Comandos identificados:** Registrar signos vitales, Iniciar entrega de turno SBAR, Reportar evento clínico crítico, Prescribir tratamiento.
- **Políticas de dominio:** 
  - Cuando un signo vital supera un umbral de riesgo → generar alerta crítica de inmediato.
  - Cuando se inicia el cambio de turno → generar un resumen estructurado del SBAR.

**Paso 4: Modelos de Lectura**
Para que los usuarios puedan interactuar con esta data, identificamos estas vistas:
- Dashboard de monitoreo de constantes vitales.
- Vista de entrega de turno (SBAR).
- Historial de eventos y auditoría.

#### 4.6.2. Software Architecture Context Diagram
Este diagrama muestra una vista de alto nivel de ClinicalSync. Aquí identificamos a los actores principales (enfermeros, médicos y auditores) y cómo interactúan con el sistema sin entrar en detalles técnicos.

<p align="center">
  <img src="assets/chapter-4/context-diagram.png" alt="Diagrama de Contexto ClinicalSync" width="800">
</p>

*Muestra la interacción directa de los roles clínicos con la plataforma.*


#### 4.6.3. Software Architecture Container Diagrams
Haciendo un poco de zoom, en este diagrama separamos las unidades de despliegue. Tenemos nuestra Single Page Application (SPA) para el frontend, el backend que expone el RESTful API y nuestra base de datos relacional.

<p align="center">
  <img src="assets/chapter-4/container-diagram.png" alt="Diagrama de Contenedores ClinicalSync" width="800">
</p>

*Detalla la comunicación JSON/HTTPS entre la Web App y el API, y la persistencia hacia MySQL 8.x.*

#### 4.6.4. Software Architecture Components Diagrams

Aquí mostramos cómo está estructurado el Backend API por dentro. Separamos la lógica en componentes basados en nuestros Bounded Contexts, cada uno con sus propios servicios y controladores REST.

<p align="center">
  <img src="assets/chapter-4/components-diagram.png" alt="Diagrama de Componentes ClinicalSync" width="800">
</p>

*Muestra las interacciones internas (mediante interfaces de Java y Domain Events) entre los componentes del sistema.*

### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
Basándonos en los Bounded Contexts, armamos el diagrama de clases del dominio. El objetivo es mantener una alta cohesión y aislar la lógica de negocio clínica de la infraestructura.

Para implementar DDD correctamente, utilizamos herencia desde un `AbstractDomainAggregateRoot` del *Shared Kernel* para poder lanzar eventos de dominio. También definimos Value Objects (como `BloodPressure` para encapsular la presión sistólica y diastólica) y las enumeraciones para estandarizar estados (`RiskLevel`, `HandoverStatus`, etc.). 

El modelo de traspasos SBAR mantiene la trazabilidad exigiendo el ID del enfermero que recibe el turno (`incomingNurseId`), y el sistema de auditoría es robusto mediante el uso de la clase inmutable `AuditLog`.

<p align="center">
  <img src="assets/chapter-4/class-diagram.png" alt="UML Class Diagram - ClinicalSync" width="100%">
</p>

*Detalla los paquetes de dominio de cada contexto y las relaciones estructurales entre las entidades.*

### 4.8. Database Design
#### 4.8.1. Database Diagrams
Para la persistencia relacional usamos MySQL con Spring Data JPA. El esquema refleja nuestros contextos y mantiene una integridad referencial estricta:

*   **patients:** Tabla central con los datos y ubicación del paciente.
*   **vital_sign_records:** Guarda el monitoreo continuo de biomarcadores y calcula el nivel de riesgo.
*   **alerts:** Maneja el ciclo de vida de los eventos críticos y los responsables de su atención.
*   **handovers:** Guarda la estructura del SBAR entre los profesionales.
*   **audit_logs:** Implementamos esta tabla como *append-only* (solo inserciones) para guardar la metadata en JSON y cumplir con las normativas de trazabilidad hospitalaria.
*   **physicians y patient_treatments:** Soportan el historial de atenciones y prescripciones médicas.

<p align="center">
  <img src="assets/chapter-4/database-diagram.png" alt="Database Diagram - ClinicalSync" width="100%">
</p>

*Muestra las tablas físicas, tipos de datos y relaciones de llave foránea de la base de datos.*

---

## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
#### 5.1.2. Source Code Management
#### 5.1.3. Source Code Style Guide & Conventions
#### 5.1.4. Software Deployment Configuration
### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint 1
##### 5.2.1.1. Sprint Planning 1
##### 5.2.1.2. Aspect Leaders and Collaborators
##### 5.2.1.3. Sprint Backlog 1
##### 5.2.1.4. Development Evidence for Sprint Review
##### 5.2.1.5. Execution Evidence for Sprint Review
##### 5.2.1.6. Services Documentation Evidence for Sprint Review
##### 5.2.1.7. Software Deployment Evidence for Sprint Review
##### 5.2.1.8. Team Collaboration Insights during Sprint
*(Nota: Repetir esta estructura para Sprint 2, 3, y 4 según corresponda cada hito de evaluación)*
### 5.3. Validation Interviews
#### 5.3.1. Diseño de Entrevistas
#### 5.3.2. Registro de Entrevistas
#### 5.3.3. Evaluaciones según heurísticas
### 5.4. Video About-the-Product

---

## Conclusiones
### Conclusiones y recomendaciones
### Video About-the-Team

---

## Bibliografía

---

## Anexos
### Anexo A. Videos de Exposiciones
*(Incluir de forma progresiva el título e hipervínculo al video de Exposición en Microsoft Stream para cada entrega AV1, TB1, AV2, TB2).*
