# <p align="center">Informe de Trabajo Final</p>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<div align="center">
  <img src="./assets/upc-logo.png" alt="Logo de UPC" />
</div>

<p align="center">Ingeniería de Software</p>
<p align="center">Aplicaciones para Dispositivos Móviles - 366</p>
<p align="center"><strong>Docente:</strong> David Gerardo Quevedo Velasco</p>
<p align="center"><strong>Startup:</strong> ParkTeam</p>
<p align="center"><strong>Producto:</strong> EzPark</p>

<p align="center"><strong>Team members:</strong></p>

| Nombre                            | Código     |
| --------------------------------- | ---------- |
| Alonso Garay, Diego Jesus        | U20201C410|
| Oliveira Paucar, Mauricio         | U201719831 |
| Rodriguez Zuluoeta, Andres Fernando  | U20201F140 |
 

<p align="center"><strong>Ciclo 2025-10</strong></p>

# Registro de Versiones del Informe

| Versión |   Fecha    | Autor | Descripción de modificación | 
|:-------:|:----------:|:-----:|:----------------------------| 
|TB1      |            |       |                             |

# Project Report Collaboration Insights
# Contenido
- [**Student Outcome**](#student-outcome)
- [**Objetivos SMART**](#objetivos-smart)
- [**Capítulo I: Presentación**](#capítulo-i-presentación)
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
- [**Capítulo II: Requirements Elicitation & Analysis**](#capítulo-ii-requirements-elicitation--analysis)
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
- [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [**Capítulo III: Requirements specification**](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping.](#31-to-be-scenario-mapping)
- [3.2. User Stories.](#32-user-stories)
- [3.3. Impact Mapping.](#33-impact-mapping)
- [3.4. Product Backlog.](#34-product-backlog)
- [**Capítulo IV: Solution Software Design**](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
- [4.1.1. EventStorming](#411-eventstorming)
- [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
- [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
- [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
- [4.1.2. Context Mapping](#412-context-mapping)
- [4.1.3. Software Architecture](#413-software-architecture)
- [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
- [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
- [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
- [4.2.1. Bounded Context:](#421-bounded-context)
- [4.2.1.1. Domain Layer](#4211-domain-layer)
- [4.2.1.2. Interface Layer](#4212-interface-layer)
- [4.2.1.3. Application Layer](#4213-application-layer)
- [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
- [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
- [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
- [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
- [2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)
- [4.2.2. Bounded Context: ](#422-bounded-context)
- [4.2.2.1. Domain Layer](#4221-domain-layer)
- [4.2.2.2. Interface Layer](#4222-interface-layer)
- [4.2.2.3. Application Layer](#4223-application-layer)
- [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
- [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
- [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
- [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
- [2.6.2.6.2. Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)
- [4.2.3. Bounded Context: ](#423-bounded-context)
- [4.2.3.1. Domain Layer](#4231-domain-layer)
- [4.2.3.2. Interface Layer](#4232-interface-layer)
- [4.2.3.3. Application Layer](#4233-application-layer)
- [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
- [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
- [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
- [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
- [2.6.3.6.2. Bounded Context Database Design Diagram](#26362-bounded-context-database-design-diagram)
- [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)
- [Video About-the-team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)


# Student Outcome
# Objetivos SMART
# Capítulo I: Presentación
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos objetivo
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
EzPark se enfrentará a una competencia formada por aplicaciones móviles que facilitan la búsqueda y gestión de espacios de estacionamiento. A continuación, se presentan algunas de las más representativas en este rubro:
**Apparka**
Esta app peruana ofrece una solución innovadora para el alquiler temporal de cocheras privadas. A través de Apparka, los propietarios pueden registrar sus espacios disponibles y los conductores pueden encontrarlos fácilmente, pagar directamente desde la aplicación y evitar el tiempo perdido dando vueltas. Apparka se enfoca principalmente en zonas urbanas, promoviendo el uso eficiente de cocheras subutilizadas, una propuesta muy alineada al concepto de EzPark, aunque con un enfoque más cerrado en espacios privados formales.
**Quadra**
Esta app permite a los usuarios encontrar, comparar y alquilar cocheras en función de ubicación, precio y tiempo disponible. Su principal valor está en ofrecer múltiples opciones de estacionamiento a corto o largo plazo, ideal para usuarios que buscan flexibilidad. Aunque aún se encuentra en crecimiento, Quadra está ganando terreno gracias a su interfaz práctica y sistema de reservas con confirmación rápida. EzPark puede diferenciarse incorporando una experiencia de usuario más personalizada y una red más diversa que incluya espacios no tradicionales.
**Parkopedia**
Es una de las más completas a nivel mundial sobre estacionamientos, incluyendo tanto espacios públicos como privados. Proporciona información sobre tarifas, horarios, disponibilidad estimada y está integrada a sistemas de navegación en vehículos. Aunque su fortaleza es su alcance global (más de 15,000 ciudades), su enfoque es más informativo que transaccional. EzPark puede posicionarse como una opción más local e interactiva, centrada en la reserva y pago en tiempo real, especialmente adaptada a las necesidades del conductor peruano.

<table border="1">
  <thead>
        <tr>
      <th colspan="2">¿Por qué llevar a cabo este análisis?</th>
      <td colspan="4">El análisis competitivo es fundamental para comprender el entorno en el que se insertará EzPark, identificar brechas en el mercado, entender qué hacen bien los competidores y cómo diferenciarnos. A partir de esta evaluación, se pueden diseñar mejores estrategias de producto, marketing y expansión, alineadas con las necesidades reales del usuario y las oportunidades del sector.</td>
    </tr>
    <tr>
      <th colspan="2">Competidores</th>
      <th>EzPark</th>
      <th>Apparka</th>
      <th>Quadra</th>
      <th>Parkopedia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="2">Perfil</th>
      <td>Overview</td>
      <td>Esta enfocada en resolver la escasez de estacionamientos urbanos mediante una app que permite a los usuarios buscar, reservar y pagar espacios de forma rápida y sencilla.</td>
      <td>Aplicación centrada en el alquiler temporal de cocheras privadas. Funciona como un marketplace entre propietarios y conductores.</td>
      <td>App móvil que permite buscar, comparar y alquilar cocheras en función de ubicación, precio y disponibilidad horaria.</td>
      <td>Plataforma global que brinda información sobre estacionamientos públicos y privados, operativa en más de 15,000 ciudades.</td>
    </tr>
    <tr>
      <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
      <td>Permitir a los usuarios encontrar y reservar cocheras privadas en tiempo real, reduciendo la congestión urbana y generando ingresos adicionales a los dueños de los espacios.</td>
      <td>Oferta formal y segura de espacios privados.<br>Facilita ingresos pasivos para dueños de cocheras.<br>Pago directo desde la app.
      </td>
      <td>Flexibilidad en tiempo de uso.<br>Sistema de reservas rápidas y comparación de precios.<br>Enfocada en eficiencia y experiencia de usuario.
      </td>
      <td>Amplia cobertura geográfica.<br>Integración con sistemas de navegación y autos.<br>Gran base de datos de tarifas, horarios y ubicación.
      </td>
    </tr>
    <tr>
      <th rowspan="2">Perfil de Marketing</th>
      <td>Mercado objetivo</td>
      <td>Conductores de vehículos particulares que deseen un estacionamiento.<br>
Propietarios de cocheras que desean generar ingresos pasivos alquilando sus espacios sin complicarse.
</td><td>Usuarios urbanos con auto y propietarios de cocheras formales</td><td>Conductores que buscan alternativas prácticas y flexibles</td><td>Conductores globales que requieren información rápida</td>
    </tr>
    <tr>
      <td>Estrategias de marketing</td>
      <td>Alianzas locales, redes sociales, promociones por uso, marketing boca a boca</td>
      <td>Enfoque B2C y B2B, convenios con edificios y condominios</td>
      <td>Publicidad en redes, UX optimizada, convenios con empresas</td>
      <td>SEO, integración en autos, posicionamiento por data útil</td>
    </tr>
    <tr>
      <th rowspan="3">Perfil de producto</th>
      <td>Productos & Servicios</td>
      <td>Plataforma móvil (App Android/iOS) para buscar y reservar cocheras.<br>
Sistema de pagos integrado y seguros.
</td>
      <td>Alquiler de cocheras privadas</td>
      <td>Alquiler por hora/día; comparación de espacios</td>
      <td>Búsqueda informativa (precios, horarios, disponibilidad)</td>
    </tr>
    <tr>
      <td>Precios & Costos</td>
      <td>Comisión por transacción; modelo freemium</td><td>Comisión al propietario / tarifa por uso</td><td>Tarifa por uso / comisión variable</td><td>Gratuito para usuarios; modelos B2B y licencias</td>
    </tr>
    <tr>
      <td>Canales de distribución (Web y/o Móvil)</td>
      <td>App móvil y Web</td><td>App móvil y Web</td><td>App móvil</td><td>Web y app móvil, integrada a navegadores</td>
    </tr>
    <tr>
      <th rowspan="4">Análisis SWOT</th>
      <td>Fortalezas</td>
      <td>Adaptado al mercado peruano.<br>
Oferta diversa (cocheras tradicionales y no tradicionales).<br>
Interfaz simple e intuitiva.
</td><td>Marca local reconocida.<br>
Oferta formal y legalizada.
Plataforma establecida.
</td><td>Comparación inteligente de precios y horarios.<br>
Experiencia de usuario moderna.
</td><td>Enorme base de datos global.<br>
Integración en navegadores y vehículos.
</td>
    </tr>
    <tr>
      <td>Debilidades</td>
      <td>En etapa inicial, falta de reputación/marca consolidada.<br>
Requiere masa crítica de usuarios y ofertantes.
</td><td>Limitada a espacios privados registrados.<br>
Poca flexibilidad para incluir otros tipos de espacios.<br>
No cubre zonas con menor desarrollo.
</td><td>Limitado a usuarios más tecnológicamente activos.<br>
Poca personalización local o cultural.
</td><td>No transaccional: no permite reservas ni pagos.<br>
Información a veces desactualizada.<br>
No adaptada a mercados específicos como Perú.
</td>
    </tr>
    <tr>
      <td>Oportunidades</td>
      <td>Crecimiento urbano y aumento del parque automotor.<br>

Espacios subutilizados disponibles en hogares y negocios.<br>
Falta de soluciones locales completas.
</td><td>Expansión a más ciudades.<br>

Integración con sistemas de movilidad urbana.
</td><td>Implementación de suscripciones o membresías.<br>

Expansión a flotas corporativas.
</td><td>Convertirse en marketplace.<br>

Asociaciones con startups locales para operar en nuevas regiones.
</td>
    </tr>
    <tr>
      <td>Amenazas</td>
      <td>Competencia de apps ya posicionadas.<br>Regulaciones sobre el uso comercial de espacios privados.<br>Desconfianza inicial de usuarios.
      </td><td>Nuevos competidores con propuestas más flexibles.Saturación de espacios en zonas céntricas
      </td><td>Competidores con enfoque local más profundo.<br>Problemas de confianza entre usuario y proveedor.
      </td><td>Apps locales más funcionales y enfocadas.<br>Cambios rápidos en el comportamiento de los usuarios urbanos.
      </td>
    </tr>
  </tbody>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Para posicionarse de manera sólida frente a la competencia, ParkTeam, con su producto EzPark, ha desarrollado una serie de estrategias y tácticas preliminares que buscan contrarrestar las fortalezas de sus competidores, capitalizar sus debilidades y responder de forma inteligente al entorno de oportunidades y amenazas. <br>
En relación con las fortalezas de competidores como Apparka, Quadra y Parkopedia, EzPark plantea diferenciarse mediante una propuesta más flexible e inclusiva. Mientras Apparka prioriza cocheras privadas formales, nuestra app permitirá registrar espacios no tradicionales como patios de casas, negocios o terrenos, siempre con validación visual y geolocalización para asegurar la confianza. Frente a la interfaz comparativa de Quadra, EzPark buscará ofrecer una experiencia de usuario mucho más fluida y enfocada en la rapidez de reserva, permitiendo concretar una transacción en solo tres pasos. Asimismo, frente al alcance global y enfoque informativo de Parkopedia, nuestra solución se centrará en la interacción local, con reservas y pagos en tiempo real, ajustados a las dinámicas y preferencias del conductor peruano. <br>
Aprovechando las debilidades de estas plataformas, EzPark implementará una estrategia de democratización del espacio urbano. A diferencia de Quadra, que aún está limitado a usuarios muy digitales, nuestra aplicación incorporará un diseño accesible, tutoriales interactivos y soporte por WhatsApp para captar una audiencia más amplia. Mientras tanto, al no contar Parkopedia con funciones transaccionales, nuestro producto ofrecerá la posibilidad de pagar directamente desde la app con métodos populares como Yape, Plin y tarjetas, generando mayor comodidad y fidelización del usuario. <br>
Respecto a las oportunidades que ofrece el entorno, EzPark busca aprovechar el crecimiento constante del parque automotor urbano para posicionarse primero en distritos emergentes con alta congestión y escasa oferta de estacionamientos, como San Juan de Lurigancho o Los Olivos. Además, estableceremos alianzas con negocios locales y comunidades vecinales para captar espacios subutilizados como cocheras temporales, promoviendo la economía compartida. En paralelo, exploraremos integraciones con aplicaciones de movilidad o delivery, generando sinergias que aumenten nuestra visibilidad y valor percibido. <br>
Frente a las amenazas, como la posible entrada de nuevos actores al mercado o las regulaciones sobre el uso de espacios privados, ParkTeam implementará tácticas de fidelización temprana mediante programas de recompensas por invitaciones, uso frecuente y reseñas positivas. Además, nuestra app incorporará términos de uso claros, funcionalidades de contacto directo con propietarios y sistemas de calificación y reputación que ayuden a construir una comunidad segura y confiable. De esta forma, buscamos transformar potenciales riesgos en oportunidades para fortalecer la confianza y el crecimiento sostenible de la plataforma. <br>


## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping
## 2.4. Ubiquitous Language
# Capítulo III: Requirements specification
## 3.1. To-Be Scenario Mapping.
## 3.2. User Stories.
## 3.3. Impact Mapping.
## 3.4. Product Backlog.
# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
#### 4.1.1.1. Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams
#### 4.1.3.3. Software Architecture Deployment Diagrams
## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context:
#### 4.2.1.1. Domain Layer
#### 4.2.1.2. Interface Layer
#### 4.2.1.3. Application Layer
#### 4.2.1.4. Infrastructure Layer
#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.1.6.2. Bounded Context Database Design Diagram
### 4.2.2. Bounded Context: 
#### 4.2.2.1. Domain Layer
#### 4.2.2.2. Interface Layer
#### 4.2.2.3. Application Layer
#### 4.2.2.4. Infrastructure Layer
#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.2.6.2. Bounded Context Database Design Diagram
### 4.2.3. Bounded Context: 
#### 4.2.3.1. Domain Layer
#### 4.2.3.2. Interface Layer
#### 4.2.3.3. Application Layer
#### 4.2.3.4. Infrastructure Layer
#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.3.6.2. Bounded Context Database Design Diagram
# Conclusiones
## Conclusiones y recomendaciones.
## Video About-the-team
# Bibliografía
# Anexos