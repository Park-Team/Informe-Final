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
|TB1      |      23/04/2025      |    ParkTeam   |    Se hizo la entrega del primer avance del Informe, desde la presentacion de la startup, hasta el capitulo 4 y las primeras conclusiones.                         |

# Project Report Collaboration Insights

![Project Report Collaboration Insights](./assets/collaboration-insights1.png)

![Project Report Collaboration Insights](./assets/collaboration-insights3.png)

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
- [4.2.1. Bounded Context: User Management](#421-bounded-context-user-management)
- [4.2.1.1. Domain Layer](#4211-domain-layer)
- [4.2.1.2. Interface Layer](#4212-interface-layer)
- [4.2.1.3. Application Layer](#4213-application-layer)
- [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
- [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
- [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
- [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
- [2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)
- [4.2.2. Bounded Context: Parking Management ](#422-bounded-context-parking-management)
- [4.2.2.1. Domain Layer](#4221-domain-layer)
- [4.2.2.2. Interface Layer](#4222-interface-layer)
- [4.2.2.3. Application Layer](#4223-application-layer)
- [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
- [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
- [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
- [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
- [2.6.2.6.2. Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)
- [4.2.3. Bounded Context: Reservation Management Context ](#423-bounded-context-reservation-management-context)
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

El curso contribuye al cumplimiento del Student Outcome ABET:<br>
**ABET - EAC - Student Outcome 7**<br>
- Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias deaprendizaje apropiadas.
En elsiguiente cuadro se describe las accionesrealizadas y enunciados de conclusiones
por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET –
EAC - Student Outcome 7.
<table>
        <tr>
            <th>Criterio específico</th>
            <th>Acciones realizadas </th>
            <th>Conclusiones</th>
        </tr>
        <tr>
            <td>Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.</td>
            <td>Alonso Garay, Diego Jesus<br>TB1<br>Desarrollé el capítulo 4 del proyecto EzPark. Aprendí a comprender los conceptos necesarios para desarrollar los diagramas presentes del capítulo correctamente.<br>
                Oliveira Paucar, Mauricio<br>TB1<br>En esta entrega realice el Capitulo 1 y algunos puntos del Capitulo 4. En estos puntos pude ver conceptos nuevos, pasados y mejorar aquellos puntos que creia necesarios con la ayuda de mi docente.<br>
                Rodriguez Zuluoeta, Andres Fernando<br>TB1<br>lDesarrollé los capítulos 2 y 3 del proyecto EzPark, incluyendo análisis de requerimientos, user stories, Impact Mapping y Domain Message Flow Modeling. Aprendí a aplicar conceptos como Bounded Context y flujos de dominio en un sistema real.<br>
            </td>
            <td>El proyecto permitió al equipo adquirir nuevos conocimientos sobre modelado de dominio y diseño de soluciones, herramientas fundamentales para el desarrollo profesional en ingeniería de software."<br>
                </td>
        </tr>
        <tr>
            <td>Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.</td>
            <td>Alonso Garay, Diego Jesus<br>TB1<br>Durante el desarrollo del trabajo aprendimos puntos importantes sobre la colaboración y sobre como se debe investigar para la elaboración de un buen proyecto.<br>
                Oliveira Paucar, Mauricio<br>TB1<br>En todo momento del trabajo se aprendimos nuevas cosas o mejoramos lo que ya creaiamos correcto, ya que con el tiempo algunas cosas se actulizan y tenemos que estar en constante aprendizaje para poder entregar lo mejor en nuestros trabajos.<br>
                Rodriguez Zuluoeta, Andres Fernando<br>TB1<br>Investigué por mi cuenta sobre Impact Mapping y Bounded Context, usando documentación y ejemplos externos, aplicando estrategias de autoaprendizaje para completar correctamente mi parte del proyecto.<br></td>
            <td>El equipo comprendió que el aprendizaje continuo es esencial para enfrentar desafíos reales en proyectos, y que es necesario mantenerse actualizado de manera constante para seguir creciendo profesionalmente.<br></td>
        </tr>
    </table>

# Objetivos SMART

**Oliveira Paucar, Mauricio**

**Objetivo 1**
- **Our focus is on** working as a backend developer using Python to build secure and efficient APIs for user management.  
- **We believe it delivers** faster onboarding and authentication experiences for end users in small-to-medium-sized digital platforms.  
- **This will be confirmed when** the APIs I develop are deployed and used in production with positive feedback from users or QA metrics.

**Objetivo 2** 
- **Our focus is on** completing three backend-focused bootcamps that cover authentication, RESTful design, and system architecture.  
- **We believe it delivers** a robust knowledge foundation to build scalable solutions for web and mobile platforms.  
- **This will be confirmed when** I complete the bootcamps and apply those concepts in a demo project validated by technical peers.

**Alonso Garay, Diego Jesús**

 **Objetivo 1**
- **Our focus is on** building and launching an MVP for an urban mobility app inspired by EzPark's value proposition.  
- **We believe it delivers** increased accessibility and convenience for drivers seeking short-term parking in busy districts.  
- **This will be confirmed when** the MVP is publicly released and used by at least 20 external users with feedback collected.

**Objetivo 2** 
- **Our focus is on** completing an advanced UX/UI design course and redesigning a legacy app interface.  
- **We believe it delivers** improved usability and user satisfaction for individuals using service-based applications.  
- **This will be confirmed when** users report higher task success rates or NPS (Net Promoter Score) in user testing sessions.

**Rodriguez Zuluoeta, Andrés Fernando**

 **Objetivo 1**  
- **Our focus is on** applying Domain-Driven Design in the development of a real-world software module.  
- **We believe it delivers** a scalable and maintainable architecture that improves collaboration between developers and stakeholders in small tech companies.  
- **This will be confirmed when** the module is deployed in a freelance or open-source project and reviewed positively by collaborators.

**Objetivo 2** 
- **Our focus is on** earning a Scrum Master certification (PSM I) and applying agile practices in a cross-functional team.  
- **We believe it delivers** continuous improvement and effective team coordination in early-stage product development.  
- **This will be confirmed when** I pass the certification and complete a full agile cycle in a real team setting with retrospectives and sprint reviews.

# Capítulo I: Presentación
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

EzPark nace como respuesta a la creciente problemática de la escasez de espacios de estacionamiento en entornos urbanos. La congestión vehicular, sumada a la ineficiencia en la búsqueda de lugares disponibles para aparcar, genera frustración y retrasos, afectando la experiencia de los conductores a nivel global. Al mismo tiempo, los propietarios de espacios de estacionamiento no utilizados enfrentan la dificultad de encontrar una forma efectiva de monetizar estos activos.

El objetivo principal de EzPark es transformar la manera en que los usuarios encuentran y aprovechan los espacios de estacionamiento. Para ello, desarrollaremos una aplicación móvil con una interfaz intuitiva y amigable, que permitirá a los usuarios buscar, reservar y pagar por estacionamientos de manera ágil y eficiente. Los conductores podrán localizar fácilmente espacios disponibles cercanos a su destino, lo que les permitirá ahorrar tiempo y evitar la frustración derivada de una búsqueda ineficaz.

Por otro lado, los propietarios de espacios de estacionamiento tendrán la posibilidad de registrarse en la plataforma para poner a disposición sus cocheras o garajes para alquiler. La aplicación proporcionará herramientas para que los propietarios gestionen sus espacios, ajusten precios, establezcan horarios de disponibilidad y reciban pagos de forma segura. Este modelo permitirá a los propietarios optimizar el uso de sus activos y generar ingresos adicionales, mientras colaboran en la reducción de la congestión del tráfico urbano.

### 1.1.2. Perfiles de integrantes del equipo

|                                                                                 | Oliveira Paucar, Mauricio                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img height="90" width="600" src="./assets/team/mauricio.PNG" alt="Mauricio" /> | <strong>Ingeniería de Software - U201719831</strong><br />Tengo 24 años, me gusta mucho aprender cosas nuevas sobre mi carrera, trabajar en equipo de manera proactiva y lograr los objetivos junto a mis compañeros. Me considero una persona ambiciosa, ya que mi meta es llegar a obtener un alto cargo en una empresa que me agrade o formar mi propia empresa relacionada al software. Gracias a ello siempre podré trabajar en algo que me guste. |

|                                                                                | Rodriguez Zuluoeta, Andres Fernando                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img height="90" width="400" src="assets/Andres.jpg"  alt="Andres" /> | <strong>Ingeniería de Software - U202124213</strong><br />Tengo 21 años, tengo conocimiento de lenguaje de programación como C ++ y Python. Me considero una persona centrada y responsable al momento de realizar trabajos en equipo. |

|                                                                                   | Alonso Garay, Diego Jesus                                                                                                                                                                                                                                                                                                                                                                                               |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img height="90" width="400" src="./assets/team/diego.jpg" alt="Diego" /> | <strong>Ingeniería de Software - U20221d014</strong><br /> Tengo 22 años, tengo conocimiento en el uso de programas de edición como Photoshop y también sobre el uso de algunos lenguajes de programación. Por lo general siempre busco dar lo necesario para realizar un buen trabajo y presentar correctamente algún proyecto. |

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática

Antecedentes

En la actualidad, las áreas urbanas experimentan un aumento constante en la congestión del tráfico debido al crecimiento de la población y al incremento del uso de vehículos motorizados.
Este problema de tráfico, agravado por la ineficiente búsqueda de espacios de estacionamiento, ha generado una experiencia frustrante para los conductores en todo el mundo. Además, esta situación también representa un desafío para quienes poseen espacios de estacionamiento no utilizados en áreas urbanas, ya que no cuentan con una plataforma efectiva para aprovechar estos activos.


Problemática

What?

La problemática percibida por nuestra startup es la escasez de espacios de estacionamiento en los entornos urbanos y la complejidad actual en la búsqueda de lugares para estacionar. Esto es debido a la alta demanda de vehículos motorizados para las actividades cotidianas.

When?

Esta preocupación ha estado aumentando a lo largo del tiempo, a medida que las ciudades han experimentado un crecimiento de la población y, por lo tanto, la cantidad de vehículos en circulación, la congestión de tráfico y la búsqueda ineficiente de estacionamiento se ha vuelto más apremiante en los últimos años.

Where?

El problema surge principalmente en áreas urbanas densamente pobladas de todo el mundo, donde el espacio es limitado y la demanda de vehículos es alta.

Who?

Los afectados por este problema son los conductores que enfrentan las dificultades para encontrar lugares de estacionamiento convenientes. Además, muchos propietarios de espacios de estacionamiento tienden a enfrentarse a empresas grandes dedicadas a este rubro, dificultando la promoción de sus servicios.

Why?

Esto ocurre debido a la insuficiencia de lugares de estacionamiento disponibles en áreas urbanas, lo que lleva a una congestión de tráfico más intensa y a la dificultad para los conductores de encontrar estacionamientos de manera oportuna.

How?

El problema sucede cuando la congestión del tráfico y la falta de espacios de estacionamiento disponibles conlleva a que la población tenga dificultades de encontrar estacionamientos de manera conveniente y eficiente.

How much?

El problema de la escasez de espacios de estacionamiento afecta de manera significativa a Lima, la capital, donde de acuerdo con un estudio realizado por la ONG Luz Ámbar en 2016 se ha demostrado que hay una insuficiencia de alrededor de 45,000 estacionamientos vehiculares en cinco distritos. Sin embargo, esta cifra resulta insuficiente en comparación con el tamaño del parque automotor de la ciudad, que consta de aproximadamente 1 millón 800,000 unidades. Esta disparidad entre la cantidad de vehículos y la disponibilidad de estacionamientos contribuye a la congestión del tráfico y al desafío constante para los conductores de encontrar lugares para estacionar de manera eficiente.


### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

En las zonas urbanas del Perú, la creciente demanda de espacios de estacionamiento ha generado una experiencia problemática tanto para los conductores como para los propietarios de garajes. Los conductores se enfrentan a una situación frustrante al buscar estacionamiento, perdiendo tiempo valioso y, en muchos casos, dejando sus vehículos en la vía pública, lo que genera riesgos innecesarios. Mientras tanto, los propietarios de cocheras tienen espacios vacíos que podrían ser alquilados para generar ingresos pasivos.

Actualmente, los conductores carecen de una forma eficiente y segura para encontrar estacionamientos disponibles cerca de su destino. Esto no solo aumenta el tiempo que invierten en la búsqueda de un lugar donde estacionar, sino que también contribuye a la congestión del tráfico. Por otro lado, los propietarios de cocheras tienen dificultades para aprovechar sus espacios debido a la inseguridad y desconfianza que sienten al permitir que personas desconocidas accedan a sus propiedades, que en muchos casos están integradas a sus viviendas.

Es necesario crear una solución que permita a los conductores encontrar de manera rápida y segura espacios de estacionamiento disponibles, mientras que, al mismo tiempo, ofrezca un entorno confiable y seguro para que los propietarios de cocheras puedan alquilar sus espacios sin temor a los riesgos asociados. La solución debe abordar las necesidades y preocupaciones de ambas partes sin comprometer la experiencia ni la seguridad de ninguna de ellas.

#### 1.2.2.2. Lean UX Assumptions

**<ins>Business Assumptions</ins>**

1. **Creo que mis usuarios necesitan** una mejor manera de encontrar lugares de estacionamientos y, de ser posible, reservarlos.
2. **Estas necesidades se pueden resolver** con una aplicación que les permite a los conductores reservar en los garajes de la ciudad, debido a que la mayoría del tiempo se encuentran desocupados o libres.
3. **Mis clientes iniciales son** los ciudadanos que cuenten con algún vehículo motorizado con dificultades para encontrar estacionamiento y/o deseen poner en alquiler sus garajes.
4. **El valor #1 que el cliente requiere de mi servicio** es encontrar y reservar espacios para estacionar en un corto periodo de tiempo. Además, los usuarios desean saber si esta metodología es totalmente segura para ambos tipos de usuario.
5. **Voy a adquirir a mis clientes a través de** estrategias de Marketing en diversas redes sociales, resaltando las principales características y beneficios de la aplicación.
6. **Mi competencia en el mercado** serán las empresas que se dedican a ofrecer sus servicios de estacionamiento.
7. **Los venceremos debido a que** ofrecemos a los usuarios poder generar ingresos de manera pasiva al rentar sus garajes como estacionamiento.
8. **Mis mayores riesgos del producto es** no encontrar una manera de brindar seguridad a los conductores como a los propietarios de los garajes.
9. **Resolveremos esto con** la incorporación de un sistema que se encargue de validar los parámetros de seguridad de los conductores y los garajes en alquiler para ofrecer una mayor seguridad al público.

**Sabremos que hemos tenido éxito cuando veamos los siguientes cambios en el comportamiento de nuestros clientes:**

- Reducción significativa en los tiempos de búsqueda de espacios disponibles para estacionar.
- Ingresos económicos en los propietarios con garajes registrados en la aplicación.

**¿Qué otras suposiciones tenemos que, de probarse falsas, pueden causar el fracaso del proyecto?**

- El permitir el acceso a cualquier usuario con propósitos malignos o perversos generará en todos los usuarios inseguridad. Por consiguiente, muchos de ellos dejarán la aplicación.

**<ins>User Assumptions</ins>**
**Clientes de parking**
¿Quién es el usuario?
Conductores que en su día a día necesitan encontrar estacionamiento para sus vehículos motorizados.

¿Dónde encaja nuestro servicio? ¿En su trabajo o en su vida?
Nuestro servicio encaja tanto para su trabajo como para sus actividades diarias. El usuario tiene la necesidad de encontrar un estacionamiento cercano a su puesto de trabajo. Asimismo, para otras actividades en algún punto específico de la ciudad desean tener su vehículo en un lugar cercano.

¿Qué problema tiene nuestro servicio y cómo se resuelve?
Problema será la posible inseguridad del usuario al alquilar en una cochera de cualquier persona desconocida.
Lo podemos resolver mediante un sistema de filtros que garanticen al usuario la seguridad de la cochera y contar con bases legales para la publicación del producto.

¿Cuándo y cómo es usado nuestro producto?
El producto es usado mayormente cuando el usuario necesita encontrar algún lugar de estacionamiento para cualquier actividad.
La aplicación se puede usar como un sistema de búsqueda y reserva de cocheras.

**Anfitriones de garajes**
¿Quién es el usuario?
Personas con garajes que desean poner en alquiler para generar ingresos pasivos.

¿Dónde encaja nuestro servicio? ¿En su trabajo o en su vida?
Nuestro servicio encaja en su vida porque pueden poner en alquiler sus garajes mientras realizan cualquier actividad.

¿Qué problema tiene nuestro servicio y cómo se resuelve?
El problema será el proceso para poder registrar sus cocheras, debido a que puede llegar a ser confuso o tedioso para el anfitrión.
Lo podemos resolver mediante capacitación sobre el proceso de filtros para facilitar al usuario el registro.

¿Cuándo y cómo es usado nuestro producto?
Nuestra aplicación es usada principalmente cuando el anfitrión dispone de cualquier garaje disponible que desee poner en alquiler para generar ingresos.
Nuestro producto es usado como un gestor de cocheras sobre reservas, estados, recibos, etc.

**<ins>Features</ins>**

¿Qué características son importantes?

- Hacer reservas de estacionamientos desde cualquier ubicación con conexión a internet, ya sea mediante un ordenador o un dispositivo móvil.
- Inscribir estacionamientos para alquilar y obtener ingresos adicionales según la tarifa establecida por el propietario.
- Verificar la disponibilidad de estacionamientos dentro de la zona o dirección especificada.

¿Cómo debe verse y comportarse nuestro producto?

- La interfaz de usuario contará con un diseño intuitivo, sencillo y atractivo, siguiendo las pautas de estilo específicas de nuestro sector.
- Se enfocará principalmente en la experiencia del usuario para garantizar una alta eficiencia en el funcionamiento de la aplicación.
- Estará disponible las 24 horas del día, los 7 días de la semana.
- Se respalda con una sólida arquitectura de software para abordar cualquier incidencia que pueda surgir.

#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que la función de reservar cocheras facilitará al usuario encontrar un espacio para estacionamiento.
Sabremos que tendremos éxito cuando la mayoría de los usuarios consigan un estacionamiento en un plazo máximo de 5 minutos.

- Creemos que la implementación de Google Maps en la aplicación permitirá al usuario localizar las cocheras de manera más eficiente.
Sabremos que estaremos en lo cierto cuando el 100% de los usuarios no tengan dificultades para encontrar estacionamientos en la plataforma.

- Creemos que permitir que los usuarios registren sus cocheras incrementará la cantidad de espacios disponibles para estacionamiento.
Sabremos que estaremos en lo cierto cuando el índice de escasez de estacionamientos se reduzca en al menos un 20%.

#### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas de ParkTeam](./assets/lean-ux-canvas.jpg)

## 1.3. Segmentos objetivo

Nuestro segmento objetivo está compuesto por dos tipos de usuarios:

**Guest:** Individuo que busca soluciones convenientes y accesibles para sus necesidades de buscar estacionamiento en entornos urbanos para su vehículo.

**Host:** Propietario de una vivienda que cuente con una cochera privada que busque sacar provecho de forma efectiva de estos mismos.

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

**Segmento objetivo: Guest y Host**

1. ¿Cuál es su nombre?
1. ¿Que edad tiene?
1. ¿En qué distrito reside?
1. ¿A que se dedica?
1. ¿Actualmente cuenta con algún tipo de vehículo?
1. ¿Cuántas veces a la semana usa su auto?
1. ¿Tiene dificultad para encontrar estacionamiento?
1. ¿En qué distritos suele buscar con mayor frecuencia un estacionamiento?
1. ¿Cuáles cree que son las horas más difíciles para encontrar estacionamiento?
1. ¿Estaría dispuesto a utilizar una cochera diferente a la tradicional?
1. ¿Con qué frecuencia usaría este servicio?
1. ¿Cree que sería de utilidad una aplicación que le ayude a buscar de manera más eficiente estos tipos 1. de estacionamientos?
1. ¿Qué requisitos mínimos cree que deberían cumplir los estacionamientos para que se sienta seguro de 1. dejar su vehículo en dichos lugares?
1. ¿Cuenta usted con algún espacio de estacionamiento disponible en su hogar?
1. ¿Usted estaría dispuesto a alquilarlo? ¿Por qué?
1. ¿Cada cuánto tiempo alquilaría su cochera?
1. ¿Cree que sería de utilidad una aplicación que le ayude a alquilar y publicitar su espacio de una manera eficiente?

### 2.2.2. Registro de entrevistas

**Segmento objetivo: Guest y Host**

Segmento objetivo: Guest y Host
Entrevista 1: Juan Carlos Bodoque Bolaños (26 años - San Miguel) - 4 de abril del 2023
URL del video: [Entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ESO5uEQLJUpJv5oRx-H9DbgBQ2BZ0bczJgFh8GRWHVF6wA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=duBHCs) (Comienzo 00:32:16 - Fin 00:37:06)
<img width =100% src="assets/entrevista1.PNG" alt="entrevista1" />

Resumen:
Después de entrevistar a Juan Carlos Bodoque Bolaños, un abogado de 26 años residente en el distrito de San Miguel, se han obtenido detalles significativos sobre sus necesidades y preferencias en relación con el estacionamiento. Juan Carlos mencionó tener dificultades para encontrar estacionamiento en su centro de labores en el distrito de San Isidro, así como en zonas turísticas como Miraflores. Destacó que los horarios laborales presentan mayores desafíos para encontrar estacionamiento. Expresó interés en utilizar una plataforma de alquiler de espacios de estacionamiento sí ofrece beneficios económicos y afirmó que la utilizaría diariamente durante los días laborales. En términos de seguridad, señaló la importancia de verificar la identidad de los ocupantes de los espacios y la presencia de agentes de seguridad.
Por otro lado, reveló que tiene dos espacios de estacionamiento disponibles en su hogar y estaría dispuesto a alquilar uno de ellos en todo momento, ya que rara vez lo utiliza. Sugirió que sería útil tener la función de alquiler de espacios de estacionamiento junto con la búsqueda de espacios disponibles en una misma plataforma para mayor eficiencia y para generar ganancias adicionales.

---

Segmento objetivo: Guest y Host
Entrevista 2: Liliana Fu Ye (22 años - Jesús María) - 4 de abril del 2023
URL del video: [Entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ESO5uEQLJUpJv5oRx-H9DbgBQ2BZ0bczJgFh8GRWHVF6wA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=duBHCs) (Comienzo 00:16:00 - Fin 00:22:02)
<img width=100% src="assets/entrevista2.PNG" alt="entrevista2" />
Resumen:
Después de entrevistar a Liliana Fu Ye, una estudiante de 22 años de Ingeniería de Software en la UPC y practicante en el banco Interbank, se han recopilado detalles importantes sobre sus hábitos de estacionamiento y sus preferencias en cuanto a la utilización de espacios de estacionamiento. Liliana mencionó que reside en el distrito de Jesús María y utiliza un vehículo prestado por su madre para desplazarse al trabajo y hacer compras los fines de semana en el distrito del Callao. Suele visitar los distritos de San Isidro y el Callao. Identificó las horas laborales y las ocasiones en las que almuerza con amigos en Miraflores como momentos difíciles para encontrar estacionamiento. Expresó su disposición para utilizar un estacionamiento privado y consideró útil una aplicación que muestre estos lugares, ya que actualmente se apoya en GPS que no son precisos para este propósito.
En cuanto a seguridad, sugirió que los estacionamientos deberían ubicarse en lugares privados o contar con personal vigilante en caso de ser públicos. Reveló que tiene dos espacios de estacionamiento en su hogar, pero solo utiliza uno y estaría dispuesta a alquilar el espacio no utilizado de manera indefinida, ya que su padre se ha mudado a otra ciudad con su vehículo. Propuso que la función de alquilar espacios propios esté integrada en la misma aplicación que ayuda a buscar espacios de otros usuarios para mayor comodidad. En cuanto a la tarifa de alquiler mensual, sugirió un precio aproximado de 300 soles, y consideraría cobrar por horas a partir de 5, aunque requiere una deliberación más detenida sobre esta opción.

---

Segmento objetivo: Guest y Host
Entrevista 3: Leonardo Jesús Vargas Navarro (26 años - Ate) - 5 de abril del 2024
URL del video: [Entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ESO5uEQLJUpJv5oRx-H9DbgBQ2BZ0bczJgFh8GRWHVF6wA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=duBHCs) (Comienzo 00:00:00 - Fin 00:09:09)
<img width=100% src="assets/entrevista3.PNG" alt="entrevista3" />
Resumen:
Después de entrevistar a Leonardo Jesús Vargas Navarro, un ingeniero civil de 26 años que trabaja actualmente en la empresa D'site Perú y que reside en el distrito de Ate Vitarte, pudimos informarnos sobre su rutina semanal que tiene para con su vehículo y algunas preferencias que tiene a la hora de usar espacios de estacionamiento. Más adelante, Leonardo nos comenta que es dueño de un Hyundai Sedán y cuenta con un garaje para el mismo en su hogar.
En cuanto a sus destinos frecuentes, él suele ir con su vehículo hasta el distrito de San Miguel por temas de trabajo, además de pasear de vez en cuando por distritos como San Isidro o La Molina. Luego, nos comentó que es un poco más complicado conseguir espacios de estacionamiento en las mañanas y al mediodía. Por otro lado, nos expresó que le parecía buena la idea de utilizar un estacionamiento privado, especialmente para los días que va a trabajar.
Sin embargo, identificó algunos aspectos de seguridad que podrían ser útiles para la aplicación, como el hecho de saber quién alquila el espacio privado o que estos espacios existan solo en distritos "no tan movidos". Sobre su disponibilidad para rentar alquilar su espacio de estacionamiento privado,

---

Segmento objetivo: Guest y Host
Entrevista 4: Jesus Pedro Casana (San Miguel) - 5 de Abril, 2024
URL del video: [Entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ESO5uEQLJUpJv5oRx-H9DbgBQ2BZ0bczJgFh8GRWHVF6wA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=duBHCs) (Comienzo 00:28:36 = Fin 00:32:15)
<img width=100% src="assets/entrevista4.PNG" alt="entrevista4" />
Terminada la entrevista a Jesus Pedro Casana, el nos comenta que es joven universitario que estudia y trabaja y cuenta con carro propio. Él es consciente que debido a su trabajo le demanda ir a varios distritos de Lima y casi la mayoría del tiempo no consigue un estacionamiento adecuado debido a la gran cantidad de vehículos estacionados que se encuentran por la zona. El también comenta que cuenta con una amplia cochera donde guarda su auto. El entrevistado manifestó su disposición a utilizar estacionamientos privados y reconoció el valor de una aplicación que facilite la visualización de estos lugares. Señaló que actualmente se apoya en sistemas de GPS que no son precisos para encontrar estacionamiento, por lo que considera útil una herramienta que le brinde información específica sobre los espacios disponibles en estacionamientos privados.

---

Segmento objetivo: Guest y Host
Entrevista 5: Edu Arturo Antayhua Ticona (San Miguel) - 6 de Abril, 2024
URL del video: [Entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ESO5uEQLJUpJv5oRx-H9DbgBQ2BZ0bczJgFh8GRWHVF6wA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=duBHCs) (Comienzo 00:22:03 - Fin 00:28:35)
<img width=100% src="assets/entrevista5.png" alt="entrevista5" />
Se ha entrevistado a Edu Arturo Antayhua Ticona que tiene 21 años y trabaja de bartender. El menciona que usa su vehículo todos los días para ir a trabajar, estudiar y salir con su familia a pasear. Del mismo modo también dice que se le dificulta mucho salir a pasear con su vehículo ya que no encuentra un estacionamiento seguro por las zonas donde él normalmente se moviliza. También menciona que el uso de una aplicación con los servicios que mencionamos le serían de gran ayuda para su día a día..

---

Segmento objetivo: Guest y Host
Entrevista 6. Rodrigo Tornero Loayza (Santiago de Surco) - 6 de Abril, 2024
URL del video: [Entrevistas](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c410_upc_edu_pe/ESO5uEQLJUpJv5oRx-H9DbgBQ2BZ0bczJgFh8GRWHVF6wA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=duBHCs) (Comienzo 00:09:10 - Fin 00:15:59)
<img width=100% src="assets/entrevista6.png" alt="entrevista6" />
Se le ha realizado una entrevista a Rodrigo Tornero Loayza que cuenta con 21 años. El menciona que usó su vehículo de Lunes a Sábado para ir a la universidad y comprar algunas cosas que necesita para su universidad. El menciona también que durante la tarde cuando necesite un estacionamiento no hay debido a la alta demanda. El cree que usar la app que brinda nuestro servicio podría solucionar esos problemas y le ayudará a ahorrar un poco de tiempo. Respecto a los servicios de nuestra app, Rodrigo menciona que él considera viable la opción de alquilar una cochera a una persona si los estacionamiento se encuentran ocupados. Del mismo modo el dice que también sería capaz de alquilar su cochera si en algún momento no llegará a usarlo.

### 2.2.3. Análisis de entrevistas

- Los entrevistados han comentado que sería de mucha utilidad el uso de una aplicación con los servicios que nosotros ofrecemos. Además, ellos son conscientes de la dificultad para conseguir un estacionamiento seguro fuera de su domicilio debido a las altas frecuencias de robo de vehículos.

- El 100% de los entrevistados destacan como aspecto positivo de la integración de herramientas de software para el proceso de búsqueda de estacionamientos que se optimiza significativamente el tiempo que se destina a desarrollar el proceso.

- El 100% de los entrevistados denotan interés y expresaron la utilidad de la plataforma que busca ofrecer Testigos de Vue con JobSync. Especialmente, expresaron que sería de gran utilidad que las pequeñas y medianas empresas que suelen tener presupuesto limitado para la adquisición de estos tipos de software

- Un porcentaje de los entrevistados comentaron que el proceso de búsqueda resultaba ser tedioso/laborioso por la gran cantidad de posibles estacionamientos a encontrar y que algunos no sean de su entera confianza.

## 2.3. Needfinding
### 2.3.1. User Personas

**User Persona: Guest**
 <img src="assets/UserPersonaGuest.png" alt="User Persona: Guest" />

**User Persona: Host**
<img src="assets/UserPersonaHost.png" alt="User Persona: Host" />

### 2.3.2. User Task Matrix

**User Persona: Guest(Luis Gonzales)**
|Actividad|Frecuencia de uso|Nivel de importancia|
|---------|-----------------|--------------------|
|Consultar en tiempo real los espacios de estacionamiento disponibles|Frecuente|Alta|
|Realizar la reserva de un lugar para estacionar|Frecuente|Alta|
|Revisar las condiciones de seguridad del estacionamiento antes de reservar|Ocasional|Alta|
|Cancelar una reserva previamente hecha|Poco frecuente|Media|
|Efectuar el pago del estacionamiento desde la misma plataforma|Frecuente|Alta|
|Dejar una calificación sobre la experiencia de estacionamiento|Ocasional|Media|
|Recibir notificaciones sobre espacios disponibles cercanos|Frecuente|Alta|

**User Persona: Host(Alejandro García)**
|Actividad|Frecuencia de uso|Nivel de importancia|
|---------|-----------------|--------------------|
|Publicar la disponibilidad de su cochera para alquiler en la app|Ocasional|Alta|
|Validar la identidad de los usuarios interesados en su cochera|Ocasional|Alta|
|Aceptar o rechazar solicitudes de reserva|Frecuente|Alta|
|Recibir pagos por los periodos de alquiler de su espacio|Frecuente|Alta|
|Atender solicitudes de cancelación de reservas|Poco frecuente|Media|
|Interactuar con los usuarios mediante el sistema de mensajería de la plataforma|Ocasional|Media|
|Actualizar datos e información sobre su cochera|Poco frecuente|Media|

### 2.3.3. User Journey Mapping

**User Persona: Guest**
<img src="assets/User JourneyMappingGuest.png" alt="User Persona: Guest" />

**User Persona: Host**
<img src="assets/User JourneyMappingHost.png" alt="User Persona: Host" />

### 2.3.4. Empathy Mapping
**User Persona: Guest**
<img src="assets/EmpathyMappingGuest.png" alt="User Persona: Guest" />

**User Persona: Host**
<img src="assets/EmpathyMappingHost.png" alt="User Persona: Host" />

### 2.3.5. As-is Scenario Mapping

**User Persona: Guest**
<img src="assets/As-Is Scenario Mapping - Guest.jpg" alt="User Persona: Guest" />

**User Persona: Host**
<img src="assets/As-Is Scenario Mapping - Host.jpg" alt="User Persona: Host" />

## 2.4. Ubiquitous Language

| **Término (EN)**     | **Término (ES)**           | **Definición**                                                                 |
|----------------------|----------------------------|--------------------------------------------------------------------------------|
| **Guest**            | Conductor                  | Usuario que busca estacionamiento en zonas urbanas a través de la app EzPark. |
| **Host**             | Anfitrión                  | Persona que posee cocheras y desea alquilarlas mediante EzPark.               |
| **Parking Space**    | Cochera / Espacio de estacionamiento | Área privada o semiprivada destinada al aparcamiento de un vehículo.   |
| **Reservation**      | Reserva                    | Acción mediante la cual un Guest asegura el uso temporal de una cochera.      |
| **Available Spot**   | Cochera disponible         | Espacio libre y apto para ser reservado, con ubicación, horario y tarifa.     |
| **Booking Request**  | Solicitud de reserva       | Pedido realizado por un Guest para utilizar una cochera en un horario dado.   |
| **Trusted Host**     | Anfitrión verificado       | Host que ha validado su identidad y confiabilidad en la plataforma.           |
| **Trusted Space**    | Cochera verificada         | Espacio que cumple requisitos de seguridad y ha sido validado por EzPark.     |
| **Time Slot**        | Franja horaria             | Intervalo de tiempo en el cual una cochera está habilitada para reservarse.   |
| **Parking Fee**      | Tarifa de estacionamiento  | Monto cobrado por el uso de una cochera según duración y horario.             |
| **Urban Congestion** | Congestión urbana          | Exceso de vehículos en zonas urbanas por falta de estacionamientos adecuados. |
| **Shared Parking**   | Estacionamiento compartido | Modelo donde los Hosts ofrecen sus cocheras temporalmente a otros usuarios.   |
| **Reservation History** | Historial de reservas   | Registro donde el usuario consulta sus reservas pasadas o activas.            |
| **Community Rating** | Calificación de la comunidad | Sistema de reseñas y puntuaciones tras completar una reserva.               |
| **Security Filter**  | Filtro de seguridad        | Mecanismo que verifica identidad de usuarios y condiciones de las cocheras.   |

# Capítulo III: Requirements specification
## 3.1. To-Be Scenario Mapping.

**User Persona: Guest**
<img src="assets/To-Be Scenario Mapping - Guest.jpg" alt="User Persona: Host" />

**User Persona: Host**
<img src="assets/To-Be Scenario Mapping - Host.jpg" alt="User Persona: Host" />


## 3.2. User Stories.

#### **Epics**  

| **Epic ID** | **Título**                          | **Descripción**                                                                 |
|-------------|-------------------------------------|---------------------------------------------------------------------------------|
| EP01        | Desplegar Landing Page          | Mostrar componentes informativos y visuales de la página principal del producto.|
| EP02        | Gestionar Cuenta de Usuario     | Permitir registro, autenticación y gestión del perfil de usuarios.              |
| EP03        | Buscar y Reservar Estacionamientos | Facilitar la búsqueda, filtrado, reserva y gestión de estacionamientos.       |
| EP04        | Administrar Cocheras (Hosts)    | Habilitar la publicación, edición y gestión de espacios de estacionamiento.     |
| EP05        | Procesar Pagos                  | Gestionar transacciones, facturación y métodos de pago.                         |
| EP06        | Configurar Perfil de Usuario    | Permitir visualización y edición de datos personales, vehículos y preferencias.|
| EP07        | Garantizar Seguridad y Notificaciones | Implementar funciones de seguridad y notificaciones relevantes.              |


**User Stories**

| **User Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con Epic ID** |
|-------------------|------------|-----------------|-----------------------------|---------------------|
| **US01** | **Acceder** a la Barra de Navegación | Como usuario, quiero usar una barra de navegación para ir a secciones clave. | **Escenario 1: Navegar a secciones**<br>- Dado que estoy en el landing page<br>- Cuando hago clic en "Cómo funciona" en la barra de navegación<br>- Entonces soy redirigido a la sección EP04<br><br>**Escenario 2: Menú desplegable**<br>- Dado que la barra de navegación tiene un menú hamburguesa (mobile)<br>- Cuando hago clic en el ícono<br>- Entonces se despliegan las opciones principales | EP01 |
| **US02** | **Acceder** a la Sección comenzar | Como usuario, quiero ver una introducción visual del servicio. | **Escenario 1: Visualización básica**<br>- Dado que cargo la página principal<br>- Cuando la sección comenzar se muestra<br>- Entonces veo un título llamativo y un botón "Comenzar"<br><br>**Escenario 2: Redirección al registro**<br>- Dado que estoy en la sección Hero<br>- Cuando hago clic en "Comenzar"<br>- Entonces soy redirigido al formulario de registro | EP01 |
| **US03** | **Acceder** a la Sección Ventajas ("Why Choose Us?") | Como usuario, quiero conocer las razones para usar EzPark. | **Escenario 1: Mostrar ventajas**<br>- Dado que estoy en la sección "Why Choose Us?"<br>- Cuando reviso el contenido<br>- Entonces veo 3 tarjetas con iconos y texto descriptivo<br><br>**Escenario 2: Responsividad**<br>- Dado que accedo desde móvil<br>- Cuando la sección se adapta<br>- Entonces las tarjetas se apilan verticalmente | EP01 |
| **US04** | **Acceder** a la Sección Funcionamiento ("How It Works") | Como usuario, quiero entender cómo usar la app. | **Escenario 1: Pasos claros**<br>- Dado que estoy en "How It Works"<br>- Cuando leo la información<br>- Entonces identifico 3 pasos numerados con ilustraciones<br><br>**Escenario 2: Llamado a acción**<br>- Dado que llego al final de la sección<br>- Cuando veo el botón "Descargar ahora"<br>- Entonces este me redirige a las app stores | EP01 |
| **US05** | **Acceder** a la Sección Testimonios | Como usuario, quiero ver opiniones de usuarios reales. | **Escenario 1: Testimonios auténticos**<br>- Dado que reviso la sección<br>- Cuando observo los testimonios<br>- Entonces cada uno muestra foto, nombre y cargo/ubicación<br><br>**Escenario 2: Carrusel interactivo**<br>- Dado que hay más de 3 testimonios<br>- Cuando hago clic en "Siguiente"<br>- Entonces se muestran nuevos testimonios con animación | EP01 |
| **US06** | **Acceder** a la Sección Precios | Como usuario, quiero conocer los costos de los servicios. | **Escenario 1: Planes comparativos**<br>- Dado que veo la sección de precios<br>- Cuando analizo las opciones<br>- Entonces identifico al menos 3 planes con características diferenciadas<br><br>**Escenario 2: Destacar recomendado**<br>- Dado que existe un plan recomendado<br>- Cuando la página carga<br>- Entonces este plan tiene un destacado visual (ej: borde colorido) | EP01 |
| **US07** | **Registrar** una Cuenta | Como usuario, quiero crear una cuenta para acceder a la app. | **Escenario 1: Registro exitoso**<br>- Dado que completo el formulario con datos válidos<br>- Cuando hago clic en "Registrarme"<br>- Entonces recibo un email de confirmación<br><br>**Escenario 2: Correo duplicado**<br>- Dado que ingreso un email ya registrado<br>- Cuando intento registrarme<br>- Entonces el sistema muestra "Este correo ya está en uso" | EP02 |
| **US08** | **Iniciar** Sesión | Como usuario, quiero autenticarme de forma segura. | **Escenario 1: Login válido**<br>- Dado que ingreso credenciales correctas<br>- Cuando hago clic en "Ingresar"<br>- Entonces accedo a mi dashboard<br><br>**Escenario 2: Credenciales inválidas**<br>- Dado que ingreso una contraseña incorrecta<br>- Cuando intento iniciar sesión<br>- Entonces el sistema muestra "Credenciales no válidas" | EP02 |
| **US09** | **Recuperar** Contraseña | Como usuario, quiero restablecer mi contraseña si la olvido. | **Escenario 1: Solicitud exitosa**<br>- Dado que ingreso mi email registrado<br>- Cuando hago clic en "Recuperar"<br>- Entonces recibo un enlace temporal al correo<br><br>**Escenario 2: Email no registrado**<br>- Dado que ingreso un email no existente<br>- Cuando solicito recuperación<br>- Entonces el sistema muestra "Email no encontrado" | EP02 |
| **US10** | **Buscar** Estacionamientos Cercanos | Como usuario, quiero encontrar espacios disponibles cerca de mí. | **Escenario 1: Búsqueda por ubicación**<br>- Dado que abro la app<br>- Cuando ingreso mi ubicación actual<br>- Entonces veo una lista de estacionamientos en un radio de 5 km<br><br>**Escenario 2: Sin resultados**<br>- Dado que busco en una zona rural<br>- Cuando no hay estacionamientos disponibles<br>- Entonces el sistema muestra "No encontramos espacios en esta área" | EP03 |
| **US11** | **Filtrar** por Precio | Como usuario, quiero ajustar la búsqueda a mi presupuesto. | **Escenario 1: Filtro aplicado**<br>- Dado que selecciono "Menos de S/10 por hora"<br>- Cuando aplico el filtro<br>- Entonces solo veo estacionamientos con precios ≤ S/10<br><br>**Escenario 2: Rango inválido**<br>- Dado que ingreso un rango negativo (ej: -S/5)<br>- Cuando intento filtrar<br>- Entonces el sistema muestra "Ingrese un valor válido" | EP03 |
| **US12** | **Visualizar** Mapa Interactivo | Como usuario, quiero ver estacionamientos en un mapa. | **Escenario 1: Marcadores en mapa**<br>- Dado que activo la vista de mapa<br>- Cuando cargo la pantalla<br>- Entonces los estacionamientos aparecen como marcadores azules<br><br>**Escenario 2: Marcador seleccionado**<br>- Dado que hago clic en un marcador<br>- Cuando se despliega el popup<br>- Entonces muestra precio, distancia y botón "Reservar" | EP03 |
| **US13** | **Reservar** un Estacionamiento | Como usuario, quiero asegurar un espacio para mi vehículo. | **Escenario 1: Reserva exitosa**<br>- Dado que selecciono un espacio disponible<br>- Cuando confirmo la reserva y pago<br>- Entonces recibo un código QR de acceso<br><br>**Escenario 2: Espacio ocupado**<br>- Dado que otro usuario reserva primero<br>- Cuando intento reservar<br>- Entonces el sistema muestra "Este espacio ya no está disponible" | EP03 |
| **US14** | **Cancelar** una Reserva | Como usuario, quiero anular una reserva si no la necesito. | **Escenario 1: Cancelación a tiempo**<br>- Dado que cancelo 1 hora antes<br>- Cuando confirmo la acción<br>- Entonces recibo un reembolso del 80%<br><br>**Escenario 2: Fuera de plazo**<br>- Dado que intento cancelar 10 minutos antes<br>- Cuando el plazo ya expiró<br>- Entonces el sistema muestra "No puedes cancelar esta reserva" | EP03 |
| **US15** | **Consultar** Historial de Reservas | Como usuario, quiero ver mis reservas anteriores. | **Escenario 1: Historial completo**<br>- Dado que accedo a "Mis reservas"<br>- Cuando selecciono "Historial"<br>- Entonces veo todas mis reservas pasadas ordenadas por fecha<br><br>**Escenario 2: Sin historial**<br>- Dado que soy un usuario nuevo<br>- Cuando reviso el historial<br>- Entonces el sistema muestra "Aún no tienes reservas" | EP03 |
| **US16** | **Calificar** Experiencias | Como usuario, quiero evaluar estacionamientos después de usarlos. | **Escenario 1: Reseña completa**<br>- Dado que finalizo una reserva<br>- Cuando dejo 5 estrellas y un comentario<br>- Entonces la reseña aparece en el perfil del estacionamiento<br><br>**Escenario 2: Reseña anónima**<br>- Dado que selecciono "Publicar anónimamente"<br>- Cuando envío la calificación<br>- Entonces solo se muestra "Usuario verificado" en lugar de mi nombre | EP03 |
| **US17** | **Ver** Próximas Reservas | Como usuario, quiero conocer mis reservas futuras. | **Escenario 1: Reservas activas**<br>- Dado que tengo 2 reservas pendientes<br>- Cuando abro la sección<br>- Entonces veo ambas con fechas y ubicaciones<br><br>**Escenario 2: Recordatorio automático**<br>- Dado que tengo una reserva en 1 hora<br>- Cuando el sistema detecta mi ubicación<br>- Entonces recibo una notificación push "Tu reserva inicia pronto" | EP03 |
| **US18** | **Actualizar** Perfil | Como usuario, quiero editar mi información personal. | **Escenario 1: Cambio de teléfono**<br>- Dado que modifico mi número<br>- Cuando guardo los cambios<br>- Entonces recibo un SMS de verificación<br><br>**Escenario 2: Foto de perfil**<br>- Dado que subo una nueva foto<br>- Cuando la imagen excede 5MB<br>- Entonces el sistema muestra "El archivo es demasiado grande" | EP02 |
| **US19** | **Eliminar** Cuenta | Como usuario, quiero borrar mi cuenta permanentemente. | **Escenario 1: Confirmación requerida**<br>- Dado que hago clic en "Eliminar cuenta"<br>- Cuando ingreso mi contraseña para confirmar<br>- Entonces todos mis datos se borran en 72 horas<br><br>**Escenario 2: Con reservas activas**<br>- Dado que tengo una reserva pendiente<br>- Cuando intento eliminar mi cuenta<br>- Entonces el sistema bloquea la acción hasta completar la reserva | EP02 |
| **US20** | **Vincular** Métodos de Login | Como usuario, quiero asociar cuentas (Google/Facebook). | **Escenario 1: Vinculación exitosa**<br>- Dado que selecciono "Google"<br>- Cuando ingreso credenciales válidas<br>- Entonces mi cuenta queda vinculada<br><br>**Escenario 2: Cuenta ya vinculada**<br>- Dado que intento vincular Facebook otra vez<br>- Cuando ya está asociado<br>- Entonces el sistema muestra "Esta cuenta ya está conectada" | EP02 |
| **US21** | **Revisar** Detalles de Estacionamiento | Como usuario, quiero información completa antes de reservar. | **Escenario 1: Detalles clave**<br>- Dado que selecciono un estacionamiento<br>- Cuando abro su ficha<br>- Entonces veo fotos, horarios, precio y reglas<br><br>**Escenario 2: Sin fotos**<br>- Dado que el Host no subió imágenes<br>- Cuando veo la ficha<br>- Entonces se muestra un ícono de "Imagen no disponible" | EP03 |
| **US22** | **Listar** Estacionamientos | Como usuario, quiero ver opciones en formato de lista. | **Escenario 1: Ordenar por precio**<br>- Dado que selecciono "Más barato primero"<br>- Cuando la lista se actualiza<br>- Entonces el primer resultado cuesta ≤ S/5<br><br>**Escenario 2: Sin conexión**<br>- Dado que pierdo internet<br>- Cuando intento cargar la lista<br>- Entonces el sistema muestra datos en caché con alerta "Modo offline" | EP03 |
| **US23** | **Previsualizar** Entorno (Street View) | Como usuario, quiero ver el área del estacionamiento. | **Escenario 1: Integración con Google**<br>- Dado que hago clic en "Ver ubicación"<br>- Cuando se carga Street View<br>- Entonces puedo navegar 360° alrededor del lugar<br><br>**Escenario 2: Zona no cubierta**<br>- Dado que el estacionamiento está en una calle privada<br>- Cuando intento abrir Street View<br>- Entonces el sistema muestra "Vista no disponible" | EP03 |
| **US24** | **Publicar** una Cochera | Como Host, quiero ofrecer mi espacio para alquilar. | **Escenario 1: Publicación exitosa**<br>- Dado que completo todos los campos obligatorios<br>- Cuando subo fotos y confirmo<br>- Entonces mi cochera aparece en búsquedas en 24h<br><br>**Escenario 2: Geolocalización fallida**<br>- Dado que el GPS no detecta mi dirección<br>- Cuando ingreso manualmente "Av. Perú 123"<br>- Entonces el sistema sugiere "¿Quiso decir Av. Perú 125?" | EP04 |
| **US25** | **Modificar** Información de Cochera | Como Host, quiero actualizar los datos de mi espacio. | **Escenario 1: Cambio de horario**<br>- Dado que edito "Horario de atención"<br>- Cuando guardo los cambios<br>- Entonces las reservas futuras se ajustan automáticamente<br><br>**Escenario 2: Precio inválido**<br>- Dado que ingreso "S/0" como precio<br>- Cuando intento guardar<br>- Entonces el sistema muestra "El precio debe ser mayor a S/3" | EP04 |
| **US26** | **Ver** Cocheras Publicadas | Como Host, quiero revisar mis espacios en la plataforma. | **Escenario 1: Estado actualizado**<br>- Dado que tengo 2 cocheras publicadas<br>- Cuando abro "Mis espacios"<br>- Entonces veo una como "Disponible" y otra como "Ocupado"<br><br>**Escenario 2: Filtro por estado**<br>- Dado que selecciono "Mostrar solo ocupadas"<br>- Cuando aplico el filtro<br>- Entonces solo veo la cochera con reservas activas | EP04 |
| **US27** | **Eliminar** una Cochera | Como Host, quiero retirar un espacio de la plataforma. | **Escenario 1: Eliminación estándar**<br>- Dado que no tengo reservas futuras<br>- Cuando elimino la cochera<br>- Entonces desaparece de los resultados de búsqueda<br><br>**Escenario 2: Con reservas pendientes**<br>- Dado que tengo una reserva para mañana<br>- Cuando intento eliminar<br>- Entonces el sistema requiere que cancele primero la reserva | EP04 |
| **US28** | **Pagar** por Reserva | Como usuario, quiero realizar transacciones seguras. | **Escenario 1: Pago con tarjeta**<br>- Dado que ingreso los datos de mi VISA<br>- Cuando confirmo el pago de S/15<br>- Entonces recibo un comprobante por email<br><br>**Escenario 2: Tarjeta rechazada**<br>- Dado que mi tarjeta tiene fondos insuficientes<br>- Cuando intento pagar<br>- Entonces el sistema muestra "Transacción rechazada" | EP05 |
| **US29** | **Descargar** Facturas | Como usuario, quiero obtener comprobantes de mis transacciones. | **Escenario 1: Factura en PDF**<br>- Dado que selecciono una reserva pasada<br>- Cuando hago clic en "Descargar factura"<br>- Entonces se genera un PDF con logo de EzPark<br><br>**Escenario 2: Sin facturas**<br>- Dado que soy un usuario nuevo<br>- Cuando reviso "Mis facturas"<br>- Entonces el sistema muestra "Aún no tienes transacciones" | EP05 |
| **US30** | **Guardar** Métodos de Pago | Como usuario, quiero almacenar tarjetas para futuros pagos. | **Escenario 1: Tarjeta guardada**<br>- Dado que ingreso los datos de mi Mastercard<br>- Cuando marco "Guardar para futuros pagos"<br>- Entonces aparece en mi perfil como "•••• 4567"<br><br>**Escenario 2: Tarjeta expirada**<br>- Dado que ingreso una tarjeta vencida<br>- Cuando intento guardarla<br>- Entonces el sistema muestra "Fecha de expiración inválida" | EP05 |
| **US31** | **Ver** Perfil | Como usuario, quiero acceder a mi información personal. | **Escenario 1: Datos básicos**<br>- Dado que abro "Mi perfil"<br>- Cuando la página carga<br>- Entonces veo mi nombre, foto y correo electrónico<br><br>**Escenario 2: Edición rápida**<br>- Dado que hago clic en "Editar" junto a mi nombre<br>- Cuando modifico el campo<br>- Entonces los cambios se guardan sin recargar la página | EP06 |
| **US32** | **Agregar** Vehículo | Como usuario, quiero registrar mi auto para reservas. | **Escenario 1: Auto registrado**<br>- Dado que ingreso placa "ABC-123" y modelo "Toyota Yaris"<br>- Cuando guardo<br>- Entonces aparece en "Mis vehículos"<br><br>**Escenario 2: Placa inválida**<br>- Dado que ingreso "XYZ-999" (placa no existente)<br>- Cuando intento guardar<br>- Entonces el sistema valida con la base de SUNARP | EP06 |
| **US33** | **Editar** Datos de Vehículo | Como usuario, quiero actualizar la información de mi vehículo. | **Escenario 1: Cambio de modelo**<br>- Dado que modifico "Toyota Yaris" a "Toyota Corolla"<br>- Cuando confirmo<br>- Entonces todas mis reservas futuras reflejan el cambio<br><br>**Escenario 2: Sin cambios**<br>- Dado que no modifico ningún campo<br>- Cuando hago clic en "Guardar"<br>- Entonces el sistema ignora la acción | EP06 |
| **US34** | **Eliminar** Vehículo | Como usuario, quiero borrar un vehículo registrado. | **Escenario 1: Eliminación confirmada**<br>- Dado que selecciono "Eliminar" en un vehículo<br>- Cuando confirmo la acción<br>- Entonces desaparece de mi lista<br><br>**Escenario 2: Con reservas activas**<br>- Dado que tengo una reserva pendiente para este auto<br>- Cuando intento eliminarlo<br>- Entonces el sistema muestra "No puedes eliminar un vehículo con reservas" | EP06 |
| **US35** | **Gestionar** Métodos de Pago | Como usuario, quiero ver y administrar mis tarjetas guardadas. | **Escenario 1: Lista de tarjetas**<br>- Dado que tengo 2 tarjetas guardadas<br>- Cuando abro "Métodos de pago"<br>- Entonces veo ambas con sus últimos 4 dígitos<br><br>**Escenario 2: Predeterminar una tarjeta**<br>- Dado que hago clic en "Establecer como predeterminada"<br>- Cuando selecciono una VISA<br>- Entonces aparece con un check verde en futuras compras | EP06 |
| **US36** | **Personalizar** Notificaciones | Como usuario, quiero elegir qué alertas recibir. | **Escenario 1: Desactivar notificaciones**<br>- Dado que desmarco "Promociones"<br>- Cuando guardo<br>- Entonces dejo de recibir emails promocionales<br><br>**Escenario 2: Notificaciones push**<br>- Dado que activo "Recordatorios de reserva"<br>- Cuando tengo una reserva en 2 horas<br>- Entonces recibo una alerta en mi móvil | EP06 |
| **US37** | **Recibir** Notificación de Reserva | Como usuario, quiero ser notificado al confirmar una reserva. | **Escenario 1: Notificación push**<br>- Dado que completo una reserva<br>- Cuando se confirma el pago<br>- Entonces mi móvil muestra "¡Reserva confirmada en Av. Perú 123!"<br><br>**Escenario 2: Sin permisos**<br>- Dado que tengo notificaciones desactivadas<br>- Cuando hago una reserva<br>- Entonces el sistema sugiere "Activa notificaciones para recibir alertas" | EP07 |
| **US38** | **Alertar** sobre Expiración | Como usuario, quiero un recordatorio antes de que venza mi reserva. | **Escenario 1: Alerta programada**<br>- Dado que mi reserva termina en 30 minutos<br>- Cuando el sistema detecta mi ubicación lejos del estacionamiento<br>- Entonces recibo "Tu tiempo está por terminar"<br><br>**Escenario 2: Renovación automática**<br>- Dado que activo "Renovar automáticamente"<br>- Cuando el tiempo se agota<br>- Entonces se cobra 1 hora adicional sin notificación | EP07 |
| **US39** | **Verificar** Identidad | Como usuario, quiero que la app valide la identidad de Hosts/conductores. | **Escenario 1: Verificación de Host**<br>- Dado que un Host sube su DNI y selfie<br>- Cuando el sistema valida los datos<br>- Entonces su perfil muestra un sello "Identidad verificada"<br><br>**Escenario 2: Documento rechazado**<br>- Dado que subo una foto borrosa de mi DNI<br>- Cuando el sistema no puede leerla<br>- Entonces recibo "Sube una imagen más clara" | EP07 |

## 3.3. Impact Mapping.

**User Persona: Guest**
<img src="assets/Impact map - Guest.png" alt="Impact map - Guest" />

**User Persona: Host**
<img src="assets/Impact map - Host.png" alt="Impact map - Host" />

## 3.4. Product Backlog.

| # Orden | User Story ID | Título | Story Points |
|---------|--------------|--------|--------------|
| 1 | US02 | Acceder a la Sección comenzar | 2 |
| 2 | US01 | Acceder a la Barra de Navegación | 1 |
| 3 | US03 | Acceder a la Sección Ventajas ("Why Choose Us?") | 2 |
| 4 | US04 | Acceder a la Sección Funcionamiento ("How It Works") | 3 |
| 5 | US05 | Acceder a la Sección Testimonios | 2 |
| 6 | US06 | Acceder a la Sección Precios | 3 |
| 7 | US10 | Buscar Estacionamientos Cercanos | 5 |
| 8 | US12 | Visualizar Mapa Interactivo | 8 |
| 9 | US13 | Reservar un Estacionamiento | 8 |
| 10 | US21 | Revisar Detalles de Estacionamiento | 3 |
| 11 | US22 | Listar Estacionamientos | 3 |
| 12 | US23 | Previsualizar Entorno (Street View) | 5 |
| 13 | US07 | Registrar una Cuenta | 5 |
| 14 | US08 | Iniciar Sesión | 3 |
| 15 | US28 | Pagar por Reserva | 5 |
| 16 | US30 | Guardar Métodos de Pago | 3 |
| 17 | US29 | Descargar Facturas | 2 |
| 18 | US24 | Publicar una Cochera | 5 |
| 19 | US25 | Modificar Información de Cochera | 3 |
| 20 | US26 | Ver Cocheras Publicadas | 2 |
| 21 | US27 | Eliminar una Cochera | 3 |
| 22 | US16 | Calificar Experiencias | 2 |
| 23 | US17 | Ver Próximas Reservas | 3 |
| 24 | US14 | Cancelar una Reserva | 3 |
| 25 | US15 | Consultar Historial de Reservas | 2 |
| 26 | US31 | Ver Perfil | 1 |
| 27 | US18 | Actualizar Perfil | 3 |
| 28 | US32 | Agregar Vehículo | 3 |
| 29 | US33 | Editar Datos de Vehículo | 2 |
| 30 | US34 | Eliminar Vehículo | 2 |
| 31 | US35 | Gestionar Métodos de Pago | 3 |
| 32 | US09 | Recuperar Contraseña | 3 |
| 33 | US20 | Vincular Métodos de Login | 3 |
| 34 | US19 | Eliminar Cuenta | 3 |
| 35 | US36 | Personalizar Notificaciones | 2 |
| 36 | US37 | Recibir Notificación de Reserva | 2 |
| 37 | US38 | Alertar sobre Expiración | 3 |
| 38 | US39 | Verificar Identidad | 5 |
| 39 | US11 |Filtrar por Precio | 3|


### **Herramienta de Gestión del Product Backlog**
Para visualizar el Product Backlog de manera interactiva, se ha utilizado **Trello**. A continuación, se incluye una captura y el enlace público al tablero:

#### **Captura del Product Backlog en Trello**:
<img src="assets/ProductBacklog.png" alt="ProductBacklog"/>

#### **Enlace al Tablero Público**:
[Product Backlog - EzPark en Trello](https://trello.com/invite/b/68088a638ddf51d42031db4d/ATTI4ac925397a9cda133d661ba7bb801c83AAE4F040/aplicaciones-para-dispositivos-moviles-ezpark)

# Capítulo IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
En esta fase, se adoptó un enfoque colaborativo y visual para facilitar el modelado del contexto del dominio. Esto se logró mediante la exploración de etapas como el Candidate Context Discovery, Domain Message Flows Modeling y la creación de Bounded Context Canvases.

**Unstructured Exploration**

Este método utiliza una representación gráfica donde todos los involucrados en un proyecto se juntan para analizar a fondo cómo funciona un sistema. Para esto, se emplean notas de colores variados que simbolizan diferentes componentes, lo que hace más sencilla la conversación y la identificación de lo que se necesita.

<img src="assets/eventstorming.png" alt="eventstorming"/>

**Pain Points**

Los pain points son esos obstáculos o complicaciones que experimentan tanto los usuarios como las personas interesadas en el sistema. Detectar estos problemas es crucial porque nos permite enfocarnos en crear funcionalidades y soluciones que de verdad resuelvan las necesidades de quienes van a usar el sistema.

<img src="assets/painpoints.png" alt="painpoints"/>

**Timelines**

La línea de tiempo del sistema describe el orden en que suceden las cosas dentro de él. Al definir esta secuencia de eventos, podemos entender mejor cómo se relacionan las acciones y cómo impactan el desarrollo del trabajo.
<img src="assets/timelines.png" alt="timelines"/>

**Pivotal Points**
Los puntos pivote son esos instantes cruciales dentro de la secuencia de eventos que tienen la capacidad de transformar la condición del sistema o de afectar de manera importante la vivencia del usuario. Reconocer estos momentos nos permite enfocar nuestras energías en las partes más trascendentales del proceso.

<img src="assets/pivotalpoints.png" alt="pivotalpoints"/>

**Commands**

Los comandos son las acciones o las órdenes que un usuario o el mismo sistema pueden llevar a cabo para generar una modificación en cómo se encuentra el sistema en un momento dado.

<img src="assets/commands.png" alt="commands"/>

**Policies**

Las políticas son los lineamientos o normas que definen la manera en que se deben tomar las decisiones dentro del sistema. Esto puede abarcar reglas de negocio que establecen el momento en que ciertos comandos deben ejecutarse o la forma en que ciertos eventos deben ser gestionados.

<img src="assets/policies1.png" alt="policies1"/>
<img src="assets/policies2.png" alt="policies2"/>
<img src="assets/policies3.png" alt="policies3"/>
<img src="assets/policies4.png" alt="policies4"/>
<img src="assets/policies5.png" alt="policies5"/>

**Read Model**

Estos modelos se crean específicamente para que la búsqueda de datos sea rápida, y a menudo se diseñan de forma diferente a cómo se guardan los datos inicialmente para que el sistema funcione mejor y pueda manejar más trabajo.

<img src="assets/readmodel.png" alt="readmodel"/>

**External Systems**

Los sistemas externos son aquellos otros sistemas o servicios con los que el sistema principal se comunica o trabaja en conjunto. Reconocer cuáles son estos sistemas nos ayuda a comprender qué conexiones y dependencias son necesarias para que todo funcione correctamente.

<img src="assets/externalsystem.png" alt="externalsystem"/>

#### 4.1.1.1. Candidate Context Discovery

**User Managment:**
<img src="assets/CandidateContextDiscoveryUserManagement.jpg" alt="CandidateContextDiscoveryUserManagement" />

**Parking Managment:**

![Parking Managment Bounded Context](./assets/parking-management-bounded-context.png)

**Reservation Managment:**

<img src="assets/reservationcandidate.png" alt="reservationcandidate" />


#### 4.1.1.2. Domain Message Flows Modeling

**Scenario: User management**

<img src="assets/DomainMessageFlowsModelingUserManagement.jpg" alt="DomainMessageFlowsModelingUserManagement" />

**Scenario: Create Parking**

![Parking Managment Message Flows Modeling](./assets/parking-management-message-flow.png)

**Scenario: Reservation Management**

<img src="assets/reservationdomain.png" alt="reservationdomain" />


#### 4.1.1.3. Bounded Context Canvases

**User management**

<img src="assets/BoundedContextCanvasesUserManagement.jpg" alt="BoundedContextCanvasesUserManagement" />

**Parking Management**

![Parking Managment Context Canvases](./assets/parking-management-context-canvases.png)

**Reservation Management**

<img src="assets/reservationbounded.png" alt="reservationbounded" />


### 4.1.2. Context Mapping


### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture Context Level Diagrams

Este diagrama de contexto ilustra cómo los Guests y los Hosts interactúan directamente con el sistema EzPark para solicitar y ofrecer espacios de estacionamiento, respectivamente. Además, muestra cómo EzPark utiliza Google Cloud Storage para la gestión de datos de los usuarios. Es una representación de alto nivel de los límites del sistema y sus principales interacciones con el mundo exterior.

<img src="assets/contextlevel.png" alt="contextlevel" />


#### 4.1.3.2. Software Architecture Container Level Diagrams

Este diagrama muestra cómo los usuarios interactúan con EzPark a través de interfaces web y móviles. Estas interfaces se comunican con la Aplicaciones API, que contiene la lógica del negocio. La API interactúa con una Base de Datos para la gestión de usuarios y con Google Cloud Storage para el almacenamiento de datos específicos. Es una vista de la arquitectura de software del sistema EzPark.

<img src="assets/containerlevel.png" alt="containerlevel" />

#### 4.1.3.3. Software Architecture Deployment Diagrams


## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: User Management
En este contexto, ParkTeam define los elementos fundamentales para la gestión de usuarios dentro de su producto EzPark. Este Bounded Context se enfoca en gestionar las entidades relacionadas con los usuarios, incluyendo su registro, autenticación, roles y perfiles.
#### 4.2.1.1. Domain Layer
En esta capa, se representan las reglas de negocio centrales del dominio de usuarios. Las clases identificadas son:
- User: Entidad que representa a un usuario del sistema, incluyendo atributos como identificador, correo electrónico, contraseña y rol.
- UserId: Objeto de valor que encapsula el identificador único del usuario.
- Email: Objeto de valor que asegura la validez del formato del correo electrónico.
- Password: Objeto de valor que maneja el hashing y la validación de contraseñas.
- Role: Enumeración que define los posibles roles de usuario, como DRIVER, OWNER y ADMIN.
- UserProfile: Entidad que contiene información adicional del usuario, como nombre, dirección y número de teléfono.
- UserAggregate: Agregado que agrupa a las entidades y objetos de valor relacionados con el usuario, asegurando la consistencia transaccional.
- UserFactory: Fábrica que se encarga de crear instancias válidas del agregado de usuario.
- IUserRepository: Interfaz que define el contrato para acceder a la persistencia de los usuarios.
- IUserDomainService: Servicio de dominio que encapsula lógica de negocio que no pertenece a una entidad específica, como la verificación de identidad.

#### 4.2.1.2. Interface Layer

Esta capa expone la funcionalidad del sistema al exterior, permitiendo la interacción con los usuarios:
- UserController: Controlador REST que maneja las solicitudes HTTP relacionadas con los usuarios, como registro, inicio de sesión y gestión de perfiles.
- AuthController: Controlador REST que gestiona la autenticación, incluyendo la generación y validación de tokens.

#### 4.2.1.3. Application Layer

Esta capa orquesta los casos de uso del dominio, coordinando las interacciones entre las entidades y servicios:
- RegisterUserCommand: Comando que contiene los datos necesarios para registrar un nuevo usuario.
- RegisterUserHandler: Manejador que procesa el comando de registro, utilizando los servicios y repositorios del dominio.
- LoginCommand: Comando que contiene los datos necesarios para autenticar a un usuario.
- LoginHandler: Manejador que procesa el comando de inicio de sesión, generando tokens de autenticación.
- UserEventHandler: Manejador de eventos que responde a eventos del dominio, como "UserRegistered" o "UserLoggedIn".

#### 4.2.1.4. Infrastructure Layer

Esta capa se encarga de la integración con tecnologías externas y la implementación de las interfaces definidas en el dominio:
- UserRepositoryPostgres: Implementación de IUserRepository que utiliza PostgreSQL para la persistencia de los usuarios.
- JwtTokenService: Servicio que genera y valida tokens JWT para la autenticación de usuarios.
- PasswordHasherBCrypt: Servicio que implementa el hashing seguro de contraseñas utilizando BCrypt.
- EmailSenderSMTP: Servicio que envía correos electrónicos de verificación a los usuarios.

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

Este apartado incluirá el diagrama de componentes del modelo C4 para el contenedor relacionado con la gestión de usuarios. El diagrama mostrará cómo se descompone el contenedor en componentes, sus responsabilidades y las interacciones entre ellos

<img src="assets/Bounded ContextSoftwareArchitectureComponentLevelDiagramsUserManagement.png" alt="Bounded ContextSoftwareArchitectureComponentLevelDiagramsUserManagement" />

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

Este apartado presentará el diagrama de clases UML para las clases del Domain Layer en el Bounded Context de gestión de usuarios. Incluirá clases, interfaces, enumeraciones, atributos, métodos, visibilidad y relaciones entre ellas.
<img src="assets/BoundedContextDomainLayerClassDiagramsUserManagement.png" alt="BoundedContextDomainLayerClassDiagramsUserManagement" />

##### 2.6.1.6.2. Bounded Context Database Design Diagram
Este apartado mostrará el diagrama de la base de datos que incluye las tablas, columnas, claves primarias y foráneas, y las relaciones entre las tablas necesarias para la persistencia de la información de los usuarios.
<img src="assets/BoundedContextDatabaseDesignDiagramUserManagement.png" alt="BoundedContextDatabaseDesignDiagramUserManagement" />

### 4.2.2. Bounded Context: Parking Management 
#### 4.2.2.1. Domain Layer

La capa de dominio representa el núcleo del sistema de gestión de estacionamientos. En ella se encapsulan las entidades, objetos de valor, agregados, repositorios y servicios que reflejan las reglas de negocio fundamentales.
 
Entidades y Objetos de Valor

Parking:

Entidad principal que representa un estacionamiento publicado por un usuario tipo Host. Contiene atributos como:

- parkingId (identificador único) Objeto de valor que encapsula el identificador único del estacionamiento, garantizando su integridad e inmutabilidad.
- ownerId (identificador del propietario) Objeto de valor que representa al usuario propietario del estacionamiento.
- location (dirección y coordenadas geográficas) Objeto de valor que agrupa la dirección del estacionamiento junto con su latitud y longitud.
- rate (tarifa por hora o día) Define el precio del estacionamiento junto con la unidad de tiempo.
- availability (rango de horarios) Representa los intervalos de tiempo disponibles en los que un estacionamiento puede ser reservado.

Agregado

- ParkingAggregate: Agregado raíz que garantiza la consistencia de las operaciones realizadas sobre un estacionamiento y sus componentes relacionados.

Repositorio (Interface)

- IParkingRepository: Interfaz que define el contrato para operaciones de almacenamiento, consulta, actualización y eliminación de datos persistentes de estacionamientos.

Servicios de Dominio

- IParkingDomainService: Encapsula lógica de negocio que no pertenece a una sola entidad, como la validación de disponibilidad o la detección de solapamientos de horarios.

#### 4.2.2.2. Interface Layer

La capa de interfaz permite exponer los servicios del sistema al exterior a través de endpoints HTTP, facilitando la comunicación entre los clientes (por ejemplo, la aplicación móvil) y el backend.
 
Controladores

ParkingController: Controlador REST encargado de las siguientes operaciones:

- POST /parkings: Registro de nuevos estacionamientos.
- PUT /parkings/{id}: Actualización de los datos del estacionamiento.
- GET /parkings/{id}: Obtención de los detalles de un estacionamiento específico.
- PATCH /parkings/{id}/availability: Actualización de la disponibilidad horaria.
 
DTOs (Data Transfer Objects)

- RegisterParkingRequest: Objeto que encapsula los datos requeridos para registrar un nuevo estacionamiento.
- UpdateParkingRequest: Contiene los datos que pueden modificarse en un estacionamiento existente.
- AvailabilityUpdateRequest: Define la estructura para modificar la disponibilidad del espacio.
- ParkingResponse: Estructura de respuesta con los datos completos de un estacionamiento, utilizada para devolver información al cliente.

#### 4.2.2.3. Application Layer

Esta capa coordina los casos de uso de negocio. Se encarga de procesar los comandos recibidos desde la capa de interfaz y delegar la lógica necesaria al dominio.
 
Comandos

- RegisterParkingCommand: Contiene los datos necesarios para crear un nuevo estacionamiento.
- UpdateParkingCommand: Encapsula los datos para actualizar información de un estacionamiento.
- ChangeAvailabilityCommand: Solicita modificar los horarios disponibles de un estacionamiento.

Manejadores

- RegisterParkingHandler: Procesa el comando de registro, construye el agregado y lo persiste utilizando IParkingRepository.
- UpdateParkingHandler: Recupera el agregado desde el repositorio, aplica cambios y guarda el nuevo estado.
- ChangeAvailabilityHandler: Gestiona la actualización del atributo availability y asegura que no se superpongan intervalos de tiempo.

Eventos del Dominio

- ParkingRegisteredEvent
- ParkingUpdatedEvent
- AvailabilityChangedEvent
 
Manejador de Eventos

- ParkingEventHandler: Responde ante eventos del dominio, como el registro exitoso de un estacionamiento, pudiendo ejecutar acciones como notificaciones.

#### 4.2.2.4. Infrastructure Layer

La capa de infraestructura implementa los mecanismos técnicos necesarios para soportar la lógica de negocio, incluyendo persistencia, servicios externos y utilitarios.
 
Repositorios

- ParkingRepositoryPostgres: Implementación de IParkingRepository basada en PostgreSQL. Incluye métodos para insertar, actualizar, eliminar y consultar estacionamientos en la base de datos.
 
Servicios

- NotificationService: Servicio encargado de enviar notificaciones al propietario del estacionamiento una vez que este ha sido registrado o modificado exitosamente.
- GeoLocationService: Servicio que transforma direcciones en coordenadas y viceversa, permitiendo almacenar ubicaciones geográficas precisas.
- AvailabilityScheduler: Componente encargado de validar y procesar rangos de disponibilidad, evitando conflictos de horario o solapamientos.

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

Este diagrama de componentes ilustra cómo se descompone el contenedor de Parking Management en componentes específicos, sus responsabilidades y las interacciones entre ellos. Cada componente tiene una función clave en el flujo de operaciones del sistema, desde la exposición de servicios REST hasta la interacción con el dominio y la persistencia de datos

![Parking Managment  Component Level Diagram](./assets/parking-management-component-diagram.png)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

Este diagrama de clases ilustra las principales entidades y sus relaciones dentro de la capa de dominio del Bounded Context: Parking Management.

![Parking Managment Class Diagram](./assets/parking-management-class-diagram.png)

##### 2.6.2.6.2. Bounded Context Database Design Diagram

Este diagrama de base de datos ilustra las principales tablas y sus relaciones dentro del contexto de Parking Management. En el diagrama se representan las entidades clave como Parking, Location, Rate, Availability, cada una con sus atributos respectivos.

![Parking Managment Database Design Diagram](./assets/parking-management-database-diagram.png)

### 4.2.3. Bounded Context: Reservation Management Context 
#### 4.2.3.1. Domain Layer

En esta capa, se representan las reglas de negocio centrales del dominio de reservas. Las clases identificadas son:

- Reservation: Entidad que representa una reserva específica, incluyendo atributos como identificador, identificador del usuario (reservante), identificador del espacio reservado, fecha y hora de inicio, fecha y hora de fin, estado de la reserva.
- ReservationId: Objeto de valor que encapsula el identificador único de la reserva.
- ReservationStatus: Enumeración que define los posibles estados de una reserva
- IReservationRepository: Interfaz que define el contrato para acceder a la persistencia de las reservas.
- IReservationDomainService: Servicio de dominio que encapsula lógica de negocio compleja que no pertenece directamente a una entidad, como la verificación de la disponibilidad de un espacio para un rango de tiempo dado o la aplicación de políticas de cancelación.


#### 4.2.3.2. Interface Layer

Esta capa expone la funcionalidad del sistema al exterior, permitiendo la interacción con los usuarios y otros sistemas:

- ReservationController: Controlador REST que maneja las solicitudes HTTP relacionadas con las reservas, como crear una nueva reserva, cancelar una reserva, obtener detalles de una reserva.


#### 4.2.3.3. Application Layer

Esta capa orquesta los casos de uso del dominio, coordinando las interacciones entre las entidades y servicios:

- CreateReservationCommand: Comando que contiene los datos necesarios para crear una nueva reserva (identificador del usuario, identificador del espacio, fecha y hora de inicio, fecha y hora de fin).
- GetReservationQuery: Consulta que contiene el identificador de una reserva para obtener sus detalles.


#### 4.2.3.4. Infrastructure Layer

Esta capa se encarga de la integración con tecnologías externas y la implementación de las interfaces definidas en el dominio:

- ReservationRepository: Implementación de IReservationRepository que utiliza PostgreSQL para la persistencia de las reservas.
- DateTimeServiceSystem: Implementación de un servicio para obtener la fecha y hora actual del sistema (podría ser una interfaz en la capa de aplicación si se necesita abstracción).


#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

Este diagrama ofrece una visión general de los componentes de software dentro del contexto de "Reservation Management", así como de sus responsabilidades e interacciones.

<img src="assets/reservationcomponentlevel.png" alt="reservationcomponentlevel" />


#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

Este diagrama de clases ilustra las principales entidades y sus relaciones dentro de la capa de dominio del bounded context de "Reservation Management".

<img src="assets/reservationlayerclass.png" alt="reservationlayerclass" />


##### 2.6.3.6.2. Bounded Context Database Design Diagram

Este diagrama representa el esquema de la base de datos para el bounded context de "Reservation Management". Cada recuadro representa una tabla, y dentro de cada tabla se listan las columnas con su nombre y, en algunos casos, su tipo y si es una clave primaria (PK) o clave foránea (FK).

<img src="assets/reservationdatabasedesign.png" alt="reservationdatabasedesign" />


# Conclusiones
## Conclusiones y recomendaciones.
- La aplicación EzPark tiene el potencial de abordar un problema real y común en entornos urbanos, que es la escasez de espacios de estacionamiento y la búsqueda ineficiente de lugares para estacionar. La propuesta de la aplicación para permitir a los usuarios buscar, reservar y pagar por espacios de estacionamiento de manera eficiente, así como permitir a los propietarios de espacios registrarse y alquilar a través de la plataforma, puede tener un impacto significativo en la experiencia de los conductores y en la congestión del tráfico en las áreas urbanas.

- La viabilidad de EzPark se sustenta en la creciente digitalización de los servicios y la adopción de soluciones tecnológicas para la vida cotidiana. La conveniencia de gestionar el estacionamiento a través de una aplicación móvil responde a las necesidades de un público cada vez más conectado y que valora la eficiencia y el ahorro de tiempo.

- Creemos que se han cumplido adecuadamente todos los criterios solicitados para esta primera entrega. Cabe mencionar que el trabajo colaborativo y bien planificado ha sido muy importante para completar las secciones de este informe, como recomendación, sería excelente tener fechas y horarios preestablecidos para cada reunión.
# Bibliografía

Carranza Casana, N. C., Céspedes Amanzo, E. B., & Salgado Bolaños, E. (2017). Propuesta de solución para el déficit de estacionamiento vehicular, caso de estudio la zona del nuevo centro empresarial del distrito de Magdalena del Mar, provincia y departamento de Lima. Recuperado de https://repositorioacademico.upc.edu.pe/handle/10757/622734

Mateo Quesada, E. N. (2022). Factores que inciden en el congestionamiento vehicular en Lima Metropolitana año 2019. Recuperado de https://repositorio.ucv.edu.pe/handle/20.500.12692/83477

Quispe Quispealaya, J., & Ramirez Gil, K. J. (2022). Evaluación de la infraestructura vial para reducir la congestión vehicular en la avenida Javier Prado Este-Lima 2020. Recuperado de https://repositorio.usil.edu.pe/entities/publication/8222137c-a234-4b1e-bd18-5b7bfc030853

Reghellin Palacios, A. F. (2018). La congestión vehicular en Lima Metropolitana entre los años 2012 y 2016 afecta económicamente a las empresas aseguradoras de vida y a sus trabajadores. Recuperado de https://repositorio.ulima.edu.pe/handle/20.500.12724/6170

# Anexos
