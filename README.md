<h3 align="center"> Universidad Peruana de Ciencias Aplicadas </h3>

<h3 align="center"> Ingeniería de Software </h3>
<h3 align="center"> Ciclo 2025 - 1</h3>

<br>

<div align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
</div>

<br>

<h1 align="center"> TP1 Report </h1>

<h3 align="center"> Aplicaciones para Dispositivos Móviles - 346 </h3>

<h3 align="center"> Docente: Jorge Luis Mayta Guillermo </h3>

<h3> Startup: HealTeam</h3>

<h3> Product: NutriPlan</h3>

<h3> Team Members: </h3>

| Member                         |    Code    |
| :----------------------------- | :--------: |
|                                |            |
|                                |            |
| Oshiro Yamashita, Daiki Oscar  | U20201F846 |
| Pardo Zapata, Gustavo Adolfo   | U202120347 |
| Alejandro Espino Flores        | U202122129 |
| Dueñas Canales Leonardo Manuel | U202117475 |

<h3 align="center">Abril, 2025</h3>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

| Versión | Fecha | Autor |  Descripción de modificación   |
| :-----: | :---: | :---: | :----------------------------: |
|   TB1   |       |   -   | Se añadió los capítulos 1 al 4 |

# Project Report Collaboration Insights

<div style="page-break-after: always;"></div>

# Contenido

## Tabla de Contenidos

[Registro de versiones del informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Contenido](#contenido)

[Student Outcome](#student-outcome-1)

[Capítulo I: Introducción](#capitulo-i-introduccion)

- [1.1. Startup Profile](#11-startup-profile)

  - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)

  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-1)

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

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design-1)

- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modelings](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
    - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
    - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)

  - [4.2.1. Bounded Context: <Bounded-Context-Name>](#421-bounded-context-bounded-context-name)
    - [4.2.1.1. Domain Layer](#4211-domain-layer)
    - [4.2.1.2. Interface Layer](#4212-interface-layer)
    - [4.2.1.3. Application Layer](#4213-aplication-layer)
    - [4.2.1.4. Infrastructure Layer](#4214-infrasructure-layer)
    - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
    - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
      - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)

  [Conclusiones](#conclusiones-1)

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

[Bibliografía](#bibliografc3ada-1)

[Anexos](#anexos-1)

<div style="page-break-after: always;"></div>

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
| :------------------ | :------------------ | :----------- |
| 1                   | 2                   | 3            |

<div style="page-break-after: always;"></div>

# Capitulo I: Introduccion

## 1.1. StartUp Profile

En un contexto donde la salud y el bienestar han cobrado una importancia central, y donde la tecnología redefine nuestros hábitos cotidianos, nace NutriPlan. Con una propuesta enfocada en la planificación nutricional inteligente, esta app busca empoderar a las personas y profesionales de la salud a través de una herramienta digital accesible, educativa y personalizada.

### 1.1.1. Description de la StartUp

NutriPlan es una app móvil que facilita la planificación de comidas saludables mediante recetas balanceadas, listas de compras inteligentes y seguimiento nutricional.
Está diseñada tanto para usuarios que desean mejorar su alimentación como para nutricionistas que buscan una herramienta práctica para personalizar y monitorear planes alimenticios.

- Misión: Promover una alimentación saludable y accesible, utilizando la tecnología para mejorar los hábitos nutricionales de las personas y apoyar el trabajo de los profesionales de la salud.

- Visión: Ser la plataforma líder en planificación nutricional personalizada en Latinoamérica, transformando la forma en que las personas se alimentan y cuidan su salud.

### 1.1.2. Perfiles de integrantes del equipo

| Integrantes                                                                                              | Descripción                                                                                                                                                                                                                                                                                                                                                                      | Conocimientos                                                                   |
| :------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------ |
| Nombre                                                                                                   | Descripción                                                                                                                                                                                                                                                                                                                                                                      | Conocimientos                                                                   |
| Daiki Oscar Oshiro Yamashita u20201f846                                                                  | Soy estudiante de la carrera de Ingeniería de Software. Tengo interés en obtener nuevos conocimientos relacionados con mi carrera que me sean de utilidad para el futuro.                                                                                                                                                                                                        | Cuento con el conocimiento de diversos lenguajes HTML, Python, C++, C# y MySQL. |
| <img src="img/PerfilGustavo.jpg" alt="" width="100" height="120">Pardo Zapata Gustavo Adolfo u2020120347 | Estudiante de la carrera de Ingeniería de Software. Soy proactivo, colaborativo, organizado,responsable y con habilidades de resolución de problemas.Tengo una excelente capacidad para comunicarme de manera efectiva y clara con los demás miembros de mi equipo y deseo colaborar en todo lo posible con mis demás compañeros en este trabajo.                                | Cuento con conocimiento en JavaScript, Java, Python, C# y SQL.                  |
| <img src="" alt="" width="100" height="120">Espino Flores, Alejandro                                     | Soy estudiante de la carrera de Ingeniería de Software. Me considero una persona proactiva, responsable y con gran capacidad para trabajar en equipo. Valoro el compañerismo y la colaboración, ya que creo que son fundamentales para alcanzar los objetivos comunes. Estoy comprometido con el aprendizaje continuo y me esfuerzo por aportar lo mejor de mí en cada proyecto. | Cuento con conocimientos en Python, Java, SQL y desarrollo web.                 |
| Dueñas Canales Leonardo Manuel                                                                           | Soy estudiante de la carrera Ingeniría de Software. Me considero una persona asertiva, logíca con gran capacidad de trabajar en equipo.                                                                                                                                                                                                                                          | Cuento el conocimiento de Java, javascript, Python, C#, HTML.                   |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### Antecedentes y problemática

En la actualidad, muchas personas desean mejorar su alimentación, pero se enfrentan a barreras como la falta de conocimientos nutricionales, el poco tiempo para planificar comidas o la dificultad para mantener hábitos saludables. Paralelamente, nutricionistas buscan herramientas modernas que les permitan brindar un mejor seguimiento a sus pacientes y generar planes personalizados de forma eficiente.

En este contexto, surge la necesidad de una solución tecnológica que integre educación nutricional, planificación inteligente y asesoría profesional, de manera accesible y personalizada.

#### What? (¿Qué es?)

NutriPlan es una aplicación móvil que permite planificar comidas saludables, visualizar el valor nutricional de cada plato, generar listas de compras y acceder a recetas con instrucciones paso a paso. Además, brinda a los nutricionistas herramientas para crear y gestionar planes personalizados para sus pacientes.

#### Why? (¿Por qué lo hacemos?)

Porque muchas personas quieren alimentarse mejor, pero no saben cómo empezar o cómo mantener una rutina saludable. Al mismo tiempo, los nutricionistas necesitan soluciones digitales que faciliten su trabajo. NutriPlan responde a ambas necesidades, promoviendo una mejor salud a través de la tecnología.

#### Where? (¿Dónde se utilizará?)

En cualquier lugar, gracias a su formato de app móvil. Ya sea en casa, en el supermercado o en la consulta con el nutricionista, NutriPlan está disponible para acompañar al usuario en todo momento.

#### When? (¿Cuándo se utilizará?)

NutriPlan está pensada para su uso diario, especialmente durante la planificación de comidas, compras semanales o al momento de preparar alimentos. También es útil durante las consultas nutricionales o el seguimiento de planes alimenticios.

#### Who? (¿A quién está dirigido?)

Usuarios generales que buscan mejorar su alimentación diaria, cocinar de manera saludable y optimizar sus compras.

Nutricionistas que requieren una herramienta digital para personalizar dietas, monitorear pacientes y compartir recomendaciones profesionales.

#### How? (¿Cómo funciona?)

Los usuarios descargan la app, configuran sus objetivos y preferencias, y acceden a un plan nutricional adaptado. Pueden consultar recetas, ver el valor nutricional de cada plato, organizar sus compras y recibir recordatorios. Los nutricionistas, por su parte, pueden crear planes, hacer seguimiento y comunicarse con sus pacientes desde la plataforma.

#### How much? (¿Cuánto cuesta?)

NutriPlan utilizará un modelo de negocio freemium con las siguientes modalidades:

Versión gratuita: Acceso a funciones básicas como recetas saludables, planificación semanal simple y generación automática de listas de compras.

Suscripción Premium para usuarios: Incluye planes nutricionales personalizados, seguimiento de objetivos, historial nutricional y acceso a contenido exclusivo.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

La idea central de NutriPlan surge a partir de la creciente necesidad de las personas de adoptar hábitos alimenticios saludables, pero sin contar con el conocimiento, el tiempo o las herramientas necesarias para lograrlo. Además, los profesionales de la nutrición enfrentan dificultades para hacer seguimiento personalizado y digital a sus pacientes de forma práctica y eficiente.

Pese a que existen aplicaciones centradas en dietas o recetas, muchas de ellas no ofrecen una visión integral que combine educación, seguimiento personalizado y planificación automatizada de comidas.

NutriPlan supera estas limitaciones al ofrecer una solución digital que permite a los usuarios planificar sus comidas, conocer su valor nutricional, mejorar sus hábitos y recibir orientación profesional. Al mismo tiempo, brinda a los nutricionistas una herramienta moderna para gestionar a sus pacientes y crear planes alimenticios basados en evidencia.

Sentiremos que estamos logrando nuestro propósito cuando veamos un número creciente de personas usando NutriPlan como parte de su rutina alimentaria diaria, y a nutricionistas recomendándola como una extensión de sus consultas.

#### 1.2.2.2. Lean UX Assumptions

¿Quién es el usuario?

Personas que desean mejorar su alimentación y aprender a comer de manera más saludable.

Nutricionistas que buscan herramientas digitales para gestionar mejor sus planes y pacientes.

¿Dónde encaja nuestro servicio? ¿En su trabajo o vida?
NutriPlan se integra en el día a día de quienes quieren mejorar su salud a través de la comida, facilitando la planificación y la educación alimentaria. En el caso de los nutricionistas, es un apoyo digital para su trabajo profesional.

¿Cuándo y cómo es usado nuestro servicio?

Los usuarios utilizarán NutriPlan al organizar sus menús semanales, al momento de cocinar, hacer compras o seguir un plan nutricional.

Los nutricionistas lo usarán para crear planes, revisar el progreso de sus pacientes y brindar recomendaciones a través de la app.

¿Qué problemas puede enfrentar nuestro servicio?

Dificultad para lograr la adherencia al uso continuo por parte del usuario.

Garantizar que los planes y recetas sean realmente personalizados y basados en datos confiables.

Conseguir que los nutricionistas adopten la plataforma como parte de su rutina profesional.

##### Business Outcomes

Creemos que los usuarios valorarán una plataforma que les ayude a mejorar su alimentación de forma práctica, educativa y personalizable.

Creemos que los nutricionistas adoptarán una herramienta que les permita ampliar su alcance, profesionalizar su seguimiento y mejorar la atención a sus pacientes.

Sabemos que existen apps similares, pero creemos que podemos diferenciarnos al integrar funcionalidades como planificación inteligente, análisis nutricional por receta y conexión con profesionales de la salud.

Reconocemos que existen otras aplicaciones relacionadas con nutrición, pero creemos que NutriPlan se diferenciará al integrar funciones de planificación automática, educación alimentaria, conexión con profesionales y análisis nutricional en una sola plataforma, ofreciendo una experiencia más completa y personalizada.

#### 1.2.2.3. Lean UX Hypothesis Statements

Creemos que los usuarios interesados en mejorar su alimentación usarán NutriPlan como una herramienta práctica y confiable para planificar sus comidas y adquirir mejores hábitos.

Creemos que los nutricionistas utilizarán nuestra plataforma para crear planes personalizados y monitorear el progreso de sus pacientes, fortaleciendo así su práctica profesional.

Creemos que ofrecer una experiencia integral (planificación, recetas, valor nutricional y seguimiento profesional) nos permitirá destacar frente a la competencia y generar un crecimiento sostenido en ambas audiencias.

Creemos que si incluimos funciones adaptables y contenido educativo accesible, lograremos una alta retención de usuarios y recomendaciones boca a boca.

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos Objetivo

#### 1. Usuarios generales

Jóvenes y adultos que desean mejorar sus hábitos alimenticios de forma sencilla y sostenible.

Personas con objetivos específicos como pérdida de peso, ganancia muscular o control de enfermedades crónicas (como diabetes o hipertensión).

Usuarios con poco tiempo para planificar sus comidas que buscan recetas saludables y fáciles de preparar.

Familias que quieren organizar mejor sus compras y comidas semanales, reduciendo desperdicio y mejorando su nutrición.

#### 2. Nutricionistas

Nutricionistas que desean ofrecer planes personalizados a sus pacientes de forma digital, optimizando su tiempo y aumentando su alcance.

Profesionales de la salud que buscan una plataforma que les permita monitorear progresos, enviar recomendaciones y mantener una comunicación constante con sus pacientes.

Especialistas que ya ofrecen asesoría nutricional presencial y desean digitalizar y escalar sus servicios.

Expertos en nutrición interesados en generar ingresos extra compartiendo su conocimiento a través de contenidos, recetas y asesorías online.

# Capítulo II: Requirements Elicitation & Analysis

En este capítulo se realizará el proceso de Análisis competitivo y Needfinding necesario para la identificación de las necesidades de nuestro segmento objetivo.

## 2.1. Competidores

### 2.1.1. Análisis Competitivo

A continuación se presenta un análisis competitivo de las empresas que ofrecen servicios similares a NutriPlan.

<table>
  <tr>
    <th colspan="6"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">
      Este análisis fue realizado con el propósito de estudiar el valor ofrecido por las empresas que compiten con nuestra solución NutriPlan. La información obtenida nos proporcionará la perspectiva necesaria para la realización de un servicio innovador y diferenciador.
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td><b>NutriPlan</b></td>
    <td><b>Yazio</b></td>
    <td><b>Noom</b></td>
    <td><b>Lifesum</b></td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td>
      Plataforma de planificación de comidas y recetas saludables, con enfoque personalizado y educación nutricional accesible.
    </td>
    <td>
      App de planificación nutricional que ofrece seguimiento de comidas y macronutrientes con recetas saludables.
    </td>
    <td>
      App de salud que combina coaching nutricional y psicológico para mejorar hábitos alimenticios.
    </td>
    <td>
      Plataforma de nutrición personalizada basada en metas de salud y estilo de vida con interfaz atractiva.
    </td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td>
      Planificación de menús adaptada a gustos y objetivos, interfaz amigable, enfoque educativo y accesible para todos.
    </td>
    <td>
      Recetas visuales, fácil seguimiento de objetivos, buena interfaz y enfoque saludable europeo.
    </td>
    <td>
      Enfoque psicológico y conductual, coaching personalizado, más allá de contar calorías.
    </td>
    <td>
      Recomendaciones visuales y personalizadas según metas, buena experiencia de usuario.
    </td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>
      Familias, jóvenes y adultos que buscan comer mejor sin complicaciones, interesados en salud preventiva y recetas prácticas.
    </td>
    <td>
      Usuarios que desean una alimentación balanceada, basada en recetas y control de macronutrientes.
    </td>
    <td>
      Personas que buscan cambiar hábitos a largo plazo con apoyo conductual y motivacional.
    </td>
    <td>
      Usuarios modernos interesados en bienestar integral y nutrición con diseño atractivo.
    </td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>
      Contenido educativo en redes sociales, colaboraciones con nutricionistas, modelo freemium con opción premium accesible.
    </td>
    <td>
      Promociones freemium, marketing de influencers, campañas en Instagram y TikTok.
    </td>
    <td>
      Publicidad en plataformas de salud, storytelling en redes, testimonios de usuarios.
    </td>
    <td>
      Estrategias visuales, campañas pagadas en redes, segmentación según metas de salud.
    </td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos y Servicios</b></td>
    <td>
      Recetas interactivas, planes semanales de comida, escáner de ingredientes, historial nutricional y consejos saludables.
    </td>
    <td>
      Seguimiento de comidas, planes de dieta, recetas saludables, estadísticas de macronutrientes.
    </td>
    <td>
      Coaching conductual, planes de alimentación y ejercicios, comunidad de apoyo.
    </td>
    <td>
      Dietas personalizadas, seguimiento visual del progreso, recomendaciones saludables.
    </td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td>
      Freemium con funciones básicas gratis y planes mensuales o anuales económicos.
    </td>
    <td>
      Modelo freemium con suscripción premium para acceso completo.
    </td>
    <td>
      Prueba gratuita, suscripción mensual con acceso a coach y planes personalizados.
    </td>
    <td>
      Modelo por suscripción, con precios según funciones y metas elegidas.
    </td>
  </tr>
  <tr>
    <td><b>Canales de distribución (Web y/o móvil)</b></td>
    <td>
      Web y app móvil (iOS/Android), versión web responsive y posibilidad de integración futura con dispositivos.
    </td>
    <td>
      App móvil con presencia fuerte en redes sociales y comunidad de usuarios.
    </td>
    <td>
      App móvil, acompañamiento vía notificaciones y correo electrónico.
    </td>
    <td>
      Web y app móvil con interfaz visual atractiva y recomendaciones personalizadas.
    </td>
  </tr>
  <tr>
    <td rowspan="5"><b>Análisis SWOT</b></td>
    <td colspan="5">
    </td>
  </tr>
  <tr>
    <td><b>Fortalezas</b></td>
    <td>
      Enfoque inclusivo, recetas regionales adaptadas, facilidad de uso, personalización inteligente.
    </td>
    <td>
      Diseño intuitivo, enfoque en recetas, análisis nutricional completo.
    </td>
    <td>
      Acompañamiento emocional, diferencial psicológico y enfoque en el hábito.
    </td>
    <td>
      Personalización visual, buena experiencia de usuario, adaptación a estilo de vida.
    </td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>
      Escasa notoriedad de marca al inicio. Marca en etapa inicial con baja visibilidad
    </td>
    <td>
      Limitado para usuarios que buscan coaching más avanzado o control conductual.
    </td>
    <td>
      Costo elevado frente a apps más simples, requiere mayor compromiso del usuario.
    </td>
    <td>
      Menor base de datos comparado con gigantes del mercado.
    </td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>
      Alianzas con supermercados, integración con nutricionistas, entrada a programas educativos y corporativos.
    </td>
    <td>
      Expansión a planes familiares y mercado corporativo wellness.
    </td>
    <td>
      Aumento de interés por la salud mental y nutrición consciente.
    </td>
    <td>
      Creciente mercado joven que valora estética y bienestar integral.
    </td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>
      Alta competencia de apps posicionadas, dependencia del marketing digital para crecer.
    </td>
    <td>
      Saturación del mercado de apps nutricionales, dificultad para destacar sin diferenciación clara.
    </td>
    <td>
      Pérdida de usuarios por falta de resultados rápidos o motivación.
    </td>
    <td>
      Alta competencia, especialmente en diseño visual y experiencia de usuario.
    </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

En primer lugar, frente a la amplia base de usuarios que poseen competidores como Fitia y Yazio, NutriPlan deberá enfocarse en la diferenciación a través de la cercanía cultural y la personalización local. Esto implica adaptar los planes nutricionales al contexto latinoamericano, incorporando ingredientes típicos de la región y recomendaciones acordes con los hábitos y preferencias culturales.

En cuanto a la integración con dispositivos y aplicaciones de salud, una de las fortalezas clave de apps como Fitia, Yazio y Lifesum, NutriPlan deberá desarrollar alianzas estratégicas con fabricantes de tecnología y plataformas como Google Fit y Apple Health, permitiendo a los usuarios sincronizar su información de manera fluida y mejorar la experiencia de seguimiento.

Respecto a la interfaz visual y la gamificación, donde destacan especialmente Yazio y Lifesum, NutriPlan puede apostar por un diseño centrado en el usuario que incluya incentivos saludables, como desafíos semanales, logros por metas alcanzadas y una navegación simple e intuitiva que motive al usuario a mantenerse constante en su progreso nutricional.

Por último, para contrarrestar el respaldo científico y profesional que exhiben otras plataformas, NutriPlan trabajará con nutricionistas certificados de habla hispana, ofreciendo contenido validado y accesible para usuarios que buscan confianza y claridad en sus planes alimenticios.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas Generales**

- ¿Cuál es su nombre?
- ¿Cuántos años tiene usted?
- ¿En que ciudad y distrito reside?
- ¿A qué se dedica o cual es su ocupación?

**Preguntas Específicas**

#### Segmento 1: Usuarios generales

¿Qué le motiva a querer mejorar su alimentación o estilo de vida?

¿Cuál es su mayor desafío cuando intenta seguir una dieta saludable?

¿Ha utilizado alguna vez aplicaciones o plataformas para gestionar su nutrición? ¿Cuáles?

¿Qué tipo de información espera recibir de una aplicación de nutrición (por ejemplo, menús personalizados, seguimiento de calorías, consejos de salud)?

¿Qué funcionalidades considera imprescindibles en una app que lo ayuden a mantenerse motivado y organizado en su plan nutricional?

#### Segmento 2: Nutricionistas

¿Cuáles son los principales retos que enfrenta al gestionar los planes nutricionales de sus pacientes?

¿Qué funcionalidades le gustaría que tuviera una aplicación para facilitar la creación de planes de dieta personalizados para sus pacientes?

¿Utiliza alguna herramienta digital en su práctica profesional para gestionar las dietas o el progreso de sus pacientes? Si es así, ¿qué le gustaría mejorar de esa herramienta?

¿Qué tan importante es para usted que una app de nutrición ofrezca un sistema de seguimiento del progreso de los pacientes en tiempo real?

¿Le gustaría poder acceder a recursos educativos dentro de la app para poder compartirlos con sus pacientes o actualizarlos según nuevos descubrimientos o tendencias?

### 2.2.2. Registro de entrevistas

#### Segmento #1: Usuarios generales

**Entrevista #1:**

Nombre: Ernesto Ruiz

Edad: 20

Distrito: Pueblo Libre

Link:

En la entrevista, el usuario expresó que su motivación principal para mejorar su alimentación es llevar una vida más saludable, tener más energía y prevenir enfermedades. El mayor desafío que enfrenta es la falta de tiempo para planificar y preparar comidas saludables. Ha probado aplicaciones como Yazio y FatSecret, pero las encuentra complicadas y poco personalizadas. Busca una aplicación que ofrezca recomendaciones personalizadas, menús adaptados, seguimiento de calorías y hábitos saludables, además de contar con funcionalidades como recordatorios y monitoreo de metas para mantenerse motivado.

#### Segmento #2: Nutricionistas

### 2.2.3. Análisis de entrevistas

| Entrevistado | Análisis de la entrevista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ernesto Ruiz | Según el entrevistado del segmento de usuarios generales, la motivación principal para mejorar su alimentación está en alcanzar una vida más saludable, tener más energía y prevenir enfermedades a futuro, junto con un interés estético por controlar el peso. Su mayor desafío radica en la falta de tiempo para planificar comidas y la confusión ante tanta información sobre nutrición. Ha utilizado aplicaciones como Yazio y FatSecret, pero las considera poco personalizadas y difíciles de mantener a largo plazo. Espera que una app de nutrición ofrezca menús adaptados, recomendaciones claras y herramientas visuales para seguir su progreso. Destaca como funciones imprescindibles una interfaz sencilla, metas personalizables, recordatorios y recetas rápidas que se alineen con sus objetivos. |

## 2.3. Needfinding

En esta sección se muestra el proceso de análisis de la información recolectada en las entrevistas. Se incluyen los User Personas, User Task Matrix, User Journey Maps, Empathy Mapping y As-Is Scenario Mapping.

### 2.3.1. User Personas

A continuación brindamos las fichas de User Persona elaboradas a partir del análisis de las entrevistas realizadas.

**Segmento #1: Usuarios generales**

<img src="./img/user1.png" width="900" height="900">

**Segmento #2: Nutricionistas**

<img src="./img/user2.png" width="900" height="900">

### 2.3.2. User Task Matrix

A continuación se muestra el proceso para la realizacion del User Task Matrix para comprender las tareas que realizan los User Persona para cumplir sus objetivos.

**Segmento #1: Usuarios generales**

| **Tarea**                                                         | **Frecuencia** | **Importancia** |
| ----------------------------------------------------------------- | -------------- | --------------- |
| Ingresar alimentos y hacer seguimiento de calorías                | Diaria         | Alta            |
| Seguir plan nutricional personalizado                             | Diaria         | Alta            |
| Consultar recetas rápidas y fáciles                               | Semanal        | Media           |
| Realizar ajustes a la dieta (como cambiar recetas o ingredientes) | Semanal        | Media           |
| Consultar el progreso del peso o salud                            | Semanal        | Alta            |
| Recibir recordatorios de comidas o ejercicios                     | Diario         | Alta            |
| Acceder a recomendaciones sobre hábitos saludables                | Semanal        | Baja            |

---

**Segmento #2: Nutricionistas**

| **Tarea**                                                        | **Frecuencia** | **Importancia** |
| ---------------------------------------------------------------- | -------------- | --------------- |
| Crear y personalizar planes nutricionales para pacientes         | Diario         | Alta            |
| Realizar seguimiento del progreso de los pacientes               | Semanal        | Alta            |
| Proveer consultas y asesoramiento a pacientes                    | Semanal        | Alta            |
| Ajustar planes nutricionales basados en el progreso del paciente | Semanal        | Alta            |
| Gestionar el historial de pacientes                              | Semanal        | Alta            |
| Acceder a recursos educativos sobre nutrición                    | Mensual        | Media           |
| Mantener comunicación con los pacientes                          | Semanal        | Alta            |

### 2.3.3. User Journey Mapping

A continuación se muestra el proceso para la realización del User Journey Mapping para los User Persona con el fin de entender las experiencias del usuario sin nuestra solución.

**Segmento #1: Usuarios generales**

**Segmento #2: Nutricionistas**

### 2.3.4. Empathy Mapping

A continuación se muestra el proceso para la realización del Empathy Mapping para los User Persona con el fin de entender lo que piensa, siente, oye, hace y observa.

**Segmento #1: Usuarios generales**

<img src="./img/empathy1.png" width="900" height="900">

**Segmento #2: Nutricionistas**

<img src="./img/empathy2.png" width="900" height="900">

### 2.3.5. As-is Scenario Mapping

A continuación se muestra el proceso para la realización del As-Is Scenario Mapping para los User Persona.

**Segmento #1: Usuarios generales**

<img src="./img/asis1.png" width="1400" height="600">

**Segmento #2: Nutricionistas**

<img src="./img/asis2.png" width="1400" height="600">

## 2.4. Ubiquitous Language

A continuación, se presentan los términos clave utilizados en el dominio de negocio de **NutriPlan**, con el objetivo de unificar el lenguaje entre el equipo de desarrollo, los usuarios y los profesionales involucrados.

- **User (usuario general):** Persona que utiliza la aplicación con el objetivo de mejorar su alimentación mediante planes personalizados y seguimiento de hábitos.

- **Nutritionist (nutricionista):** Profesional de la salud que diseña, adapta y supervisa los planes alimenticios de los usuarios a través de la plataforma.

- **Meal plan (plan nutricional):** Conjunto de recomendaciones alimenticias diarias personalizadas según las metas, preferencias y estado de salud del usuario.

- **Progress tracking (seguimiento de progreso):** Funcionalidad que permite al usuario y al nutricionista visualizar avances relacionados al peso, hábitos y cumplimiento del plan.

- **Reminder (recordatorio):** Notificaciones automáticas que motivan al usuario a mantener la constancia en sus comidas, hidratación o consultas.

- **Healthy recipes (recetas saludables):** Preparaciones sugeridas por la app, sencillas y alineadas con el objetivo nutricional del usuario.

- **Food log (historial alimenticio):** Registro diario de alimentos consumidos por el usuario, utilizado para evaluación y ajustes del plan.

- **Professional dashboard (panel del profesional):** Interfaz exclusiva para nutricionistas, donde gestionan usuarios, visualizan métricas y dan seguimiento a planes.

- **Initial assessment (evaluación inicial):** Formulario al inicio del uso de la app donde el usuario detalla su estilo de vida, hábitos y metas.

- **Nutritional goal (objetivo nutricional):** Meta definida por el usuario, como perder peso, ganar masa muscular o mantener una dieta equilibrada.

- **Feedback (comentario):** Opiniones o sugerencias que el usuario deja en la plataforma sobre su experiencia, planes o funcionalidades.

- **Onboarding (proceso de incorporación):** Etapas iniciales para guiar al nuevo usuario en el uso de NutriPlan, como crear su perfil y recibir su primer plan.

- **Metrics (métricas):** Datos cuantificables como peso, IMC, calorías diarias y nivel de adherencia al plan, que se usan para evaluar el progreso del usuario.

- **Customization (personalización):** Adaptación del contenido de la app a las necesidades individuales de cada usuario.

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

En esta sección se introduce y explica el proceso realizado para las decisiones de nivel estratégico aplicando Domain-Driven Design. El equipo explica y evidencia el proceso para descomponer el sistema en subconjuntos con límites naturales o Bounded Contexts. Para ello debe aplicar las herramientas de EvenStorming y Bounded Context Canvas.

### 4.1.1. EventStorming

Durante esta sesión de EventStorming, el equipo de NutriPlan se reunió conel objetivo de mapear de manera colaborativa yvisual el flujo principal de eventos de dominio que ocurren en la interacción entre usuarios y la apliación.La actividad tuvo una duración aprocimada de 2 horas, y fue facilitada utilizando herramientas digitales, siendo en este caso la herramienta Miro.

La técnica e aplico enfocándonos en la experienciadel usuario general y del nutricionista,identificando los eventos significativos del negocio, los comandos del sistema,los agregados y las vistas,conforme a la metodología propuesta por Alberto Brandolini.

**Actividades realizadas**

- Se identificaron eventos clave de negocio.
- Se agregaron comando que desencadenan estos eventos.
- Se agruparon eventos por áreas funcionales, lo que permitió visualizar puntos de transición y dependencia.

#### 4.1.1.1. Candidate Context Discovery

A partir del EventStorming realizado,se llevó a cabo una sesión de Candidate Context Discovery con el objetivo de identificar los posibles bounded contexts del sistema, Para esta sesión, se utilizaron las siguientes técnicas:

- Start-with-value: Se priorizaron los componentes con mayor impacto en la propuesta de valor, como la personalización de planes y el monitoreo del progreso.
- Look-for-pivotal-events: Se analizaron los eventos que marcaban unatransición de responabilidad o un cambio de estado claro.

**Bounded Contexts identificados**

1. Planificación Nutricional Context : Gestiona la creación, personalización y actualizazión de planes alimenticios
2. Seguimiento y Progreso Context : Encargado de registrar alimentos, métricas y generar reportes de progreso.
3. Onboarding Context : Maneja la incorporación de usuarios y su evaluacion incial.
4. Recetario y compras Context : Relacionado con la sugerencia de recetas saludables y generación de listas de compra.
5. Getion del Nutricionista Context : Espacio exclusivo del nutricionista para gestionar pacientes,metricas y recomendaciones.

#### 4.1.1.2. Domain Message Flows Modelings

En esta etapa se aplicó la tecnica de Domain Storytelling para representar como los distintos bounded contexts colaboran para satisfacer escenarios del negocio.Se seleccionaron flujos representativos como:

- Creacion de plan nutricional personalizado
- Monitoreo del progreso del usuario
- Comunicación entre usuario y nutricionista

Cada historia se representa mediantes actores, acciones y los contextos responsable,permitiendo visualizar la orquestación y los contratos entre servicios

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture Context Level Diagrams

#### 4.1.3.2. Software Architecture Container Level Diagrams

#### 4.1.3.3. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: <Bounded-Context-Name>

#### Bounded Context: NutritionPlanning

En este contexto se gestiona toda la lógica relacionada con la **creación, asignación y seguimiento de planes nutricionales**, así como su desglose diario y por momento de comida. Este módulo es central en el sistema y depende de perfiles y recetas.

---

##### Clase: `NutritionalPlan`

###### Propósito:

Representa un plan nutricional creado por un nutricionista para un paciente. Contiene la información general del plan y los planes diarios asociados.

###### Atributos:

- `id: Long` – Identificador único del plan.
- `userId: Long` – ID del paciente al que está asignado el plan.
- `startDate: Date` – Fecha de inicio del plan.
- `name: String` – Nombre del plan (ej: "Plan Keto Semana 1").
- `description: String` – Descripción general del plan.
- `active: boolean` – Indicador de si el plan está activo.
- `dailyPlans: List<DailyPlan>` – Lista de planes diarios asociados al plan.

###### Métodos:

- `activatePlan(): void` – Activa el plan.
- `deactivatePlan(): void` – Desactiva el plan.
- `getDayPlan(weekDay:WeekDay):DailyPlan` – Devuelve el Plan del día de comida.
- `scheduleMeal(weekDay:WeekDay, meal:ScheduledMeal):void` – Agregar una comida programada a un día.
- `addFoodToMeal(weekDay:WeekDay,timeDay:TimeDay,food:PlannedFood)` – Agrega un alimento a la comida programada.
- `removeFoodFromMeal(weekDay:WeekDay,timeDay:TimeDay,foodId:Food)` – Elimina un alimento a la comida programada.
- `getPlanSummary(): PlanSummaryDTO` – Devuelve un resumen del plan.

---

#### Clase: `DailyPlan`

###### Propósito:

Representa un plan diario dentro de un plan nutricional. Define qué comidas están programadas para un día específico.

###### Atributos:

- `id: Long` – Identificador único del día.
- `nutritionalPlanId: Long` – Referencia al plan nutricional padre.
- `weekDay: WeekDay (enum)` – Día de la semana (ej: MONDAY).
- `scheduledMeals: List<ScheduledMeal>` – Comidas planificadas para ese día.

###### Métodos:

- `addScheduledMeal(meal: ScheduledMeal): void` – Agrega una comida al día.
- `removeScheduledMeal(moment: MomentOfDay): void` – Elimina una comida específica.
- `getMeals(): List<ScheduledMeal>` – Devuelve las comidas del día.
- `totalCalories(): Int` – Suma total de calorías del día.

---

#### Clase: `ScheduledMeal`

###### Propósito:

Representa una comida planificada en un momento específico del día (ej: desayuno).

###### Atributos:

- `momentOfDay: MomentOfDay (enum)` – Momento del día (ej: BREAKFAST, DINNER).
- `recipeId: Long` – Referencia a una receta (opcional).
- `plannedFoods: List<PlannedFood>` – Lista de alimentos específicos.

###### Métodos:

- `addFoodItem(foodItem: PlannedFood): void` – Agrega alimento a la comida.
- `removeFoodItem(foodId: Long): void` – Elimina un alimento.
- `getRecipe(): Recipe` – Devuelve la receta asociada (si la hay).
- `totalCalories(): Int` – Suma de calorías de esta comida.

---

#### Clase: `PlannedFood`

###### Propósito:

Alimento específico que se planifica consumir en una comida, con cantidad incluida.

###### Atributos:

- `foodId: Long` – Referencia al alimento.
- `quantity: Int` – Cantidad en gramos o unidad base.

###### Métodos:

- `calculateCalories(): Int` – Retorna las calorías de este alimento según su cantidad.

---

##### Relaciones

- `NutritionalPlan` → contiene muchos `DailyPlan`
- `DailyPlan` → contiene muchos `ScheduledMeal`
- `ScheduledMeal` → puede tener un `Recipe` o muchos `PlannedFood`
- `PlannedFood` → referencia a `Food` en el contexto de `FoodCatalog`

#### Bounded Context: FoodCatalog

Este contexto gestiona el catálogo de alimentos y recetas disponibles en el sistema. Permite a los nutricionistas y administradores registrar, consultar y estructurar alimentos y recetas, los cuales serán utilizados en la planificación de comidas.

---

##### Clase: `Food`

###### Propósito:

Representa un alimento individual que puede ser consumido por sí mismo o como parte de una receta. Contiene información nutricional relevante.

###### Atributos:

- `id: Long` – Identificador único del alimento.
- `name: String` – Nombre del alimento.
- `description: String` – Descripción general del alimento.
- `caloriesPerUnit: Int` – Calorías por unidad.
- `proteinPerUnit: Float` – Proteína por unidad.
- `fatPerUnit: Float` – Grasa por unidad.
- `carbsPerUnit: Float` – Carbohidratos por unidad.
- `unit: UnitOfMeasure (enum)` – Unidad de medida base.

###### Métodos:

- `calculateCalories(quantity: Float): Int` – Calcula las calorías según una cantidad dada.
- `isValid(): Boolean` – Valida si el alimento tiene datos completos.

---

##### Clase: `Recipe`

###### Propósito:

Representa una receta compuesta por varios ingredientes. Cada receta puede ser utilizada en la planificación de comidas.

###### Atributos:

- `id: Long` – Identificador único de la receta.
- `name: String` – Nombre de la receta.
- `description: String` – Descripción de preparación.
- `ingredients: List<Ingredient>` – Lista de ingredientes que componen la receta.
- `instructions: String` – Pasos para preparar la receta.

###### Métodos:

- `addIngredient(ingredient: Ingredient): void` – Agrega un ingrediente.
- `removeIngredient(foodId: Long): void` – Elimina un ingrediente de la receta.
- `getTotalCalories(): Int` – Calcula la suma total de calorías de la receta.

---

##### Clase: `Ingredient`

###### Propósito:

Representa un alimento y su cantidad utilizada dentro de una receta.

###### Atributos:

- `foodId: Long` – Referencia al alimento.
- `quantity: Float` – Cantidad utilizada.
- `unit: UnitOfMeasure (enum)` – Unidad de medida (gramos, unidades, etc.).

###### Métodos:

- `calculateCalories(): Int` – Calcula las calorías del ingrediente.
- `toFood(): Food` – Devuelve el objeto `Food` referenciado.

---

##### Enum: `UnitOfMeasure`

###### Propósito:

Enumera las unidades de medida disponibles para alimentos e ingredientes.

###### Valores:

- `GRAMS`
- `MILLILITERS`
- `UNITS`
- `CUPS`
- `TABLESPOONS`
- `TEASPOONS`

---

###### Relaciones

- `Recipe` → contiene muchos `Ingredient`
- `Ingredient` → referencia a `Food`
- `Food` → puede estar presente en múltiples `Recipe` a través de `Ingredient`

#### Bounded Context: UserProfiles

Este contexto gestiona la información de perfil tanto de los pacientes como de los nutricionistas. Incluye detalles personales, profesionales y el estado de verificación de los perfiles.

---

##### Clase: `UserProfile`

###### Propósito:

Representa el perfil básico de un usuario, ya sea paciente o nutricionista. Es la base para extender con roles específicos.

###### Atributos:

- `id: Long` – Identificador único del perfil.
- `userId: Long` – Referencia al usuario del sistema.
- `fullName: String` – Nombre completo del usuario.
- `birthDate: Date` – Fecha de nacimiento.
- `gender: Gender` – Género del usuario.
- `height: Float` – Altura en centímetros.
- `weight: Float` – Peso actual en kilogramos.
- `activityLevel: ActivityLevel` –Nivel de actividad del usuario.
- `profilePictureUrl: String` – URL de la imagen de perfil.

###### Métodos:

- `updateProfile(data: ProfileDTO): void` – Actualiza los datos del perfil.
- `getAge(): Int` – Calcula la edad actual.
- `isComplete(): Boolean` – Verifica si el perfil está completo.

---

##### Clase: `NutritionistProfile`

###### Propósito:

Extiende `UserProfile` con atributos y comportamientos específicos de los nutricionistas, permitiendo gestionar su perfil profesional, pacientes asignados y planes creados.

###### Atributos:

- `id:Long` – Referencia a la clase padre.
- `userId: Long` – Referencia al usuario.
- `patientId: List<PatientId>` – Referencia al paciente usuario.
- `licenseNumber: String` – Número de licencia profesional.
- `specialization: String` – Especialidad médica o nutricional.
- `yearsOfExperience: Int` – Años de experiencia.
- `description: String` – Descripción del perfil profesional.
- `isVerified: Boolean` – Estado de verificación por la plataforma.
- `createdAt: DateTime` – Fecha de creación del perfil.

###### Métodos:

- `updateProfile(specialization: String, description: String): void` – Actualiza la especialidad y descripción.
- `verifyLicense(): void` – Marca la licencia como verificada.
- `getAssignedPatients(): List<PatientProfile>` – Devuelve la lista de pacientes asignados.
- `getActivePlans(): List<NutritionalPlan>` – Devuelve los planes nutricionales activos que ha creado.
- `assignPatient(patientId: Long): void` – Asigna un paciente al nutricionista.
- `unassignPatient(patientId: Long): void` – Desasigna un paciente del nutricionista.
- `listPatients(): List<PatientProfile>` – Lista todos los pacientes asignados.
- `createNutritionalPlan(patientId: Long, planData: NutritionalPlanDTO): NutritionalPlan` – Crea un nuevo plan nutricional para un paciente.
- `reviewWeeklyReport(patientId: Long): WeeklyReport` – Permite revisar el reporte semanal de un paciente.

---

###### Relaciones

- `NutritionistProfile` extiende a `UserProfile`
- `UserProfile` está asociado a `User` (del contexto IAM)

#### Bounded Context: ProgressTracking

Este contexto se encarga de registrar y monitorear el progreso del paciente durante la duración de un plan nutricional. Incluye métricas como peso, calorías consumidas, adherencia al plan, y otros indicadores semanales.

---

##### Clase: `WeeklyReport`

###### Propósito:

Representa el reporte de progreso semanal de un paciente respecto a un plan nutricional asignado.

###### Atributos:

- `id: Long` – Identificador único del reporte.
- `userId: Long` – ID del paciente.
- `planId: Long` – Referencia al plan nutricional.
- `weekStart: Date` – Fecha de inicio de la semana.
- `weekEnd: Date` – Fecha de fin de la semana.
- `mealsPlanned: Int` – Cantidad total de comidas esperadas esa semana.
- `mealsLogged: Int` – Número de comidas registradas por el paciente.
- `adherence: Float` – Porcentaje de adherencia al plan (0.0 a 1.0).
- `caloriesPlanned: Int` – Calorías totales planificadas para la semana.
- `caloriesConsumed: Int` – Calorías realmente consumidas.
- `startingWeight: Float` – Peso al inicio de la semana.
- `endingWeight: Float` – Peso al final de la semana.
- `generatedAt: DateTime` – Fecha de generación del reporte.

###### Métodos:

- `calculateAdherence(): Float` – Calcula el nivel de adherencia del paciente.
- `calculateCaloricBalance(): Int` – Diferencia entre calorías planificadas y consumidas.
- `hasProgress(): Boolean` – Indica si hubo progreso en el peso.
- `generateSummary(): WeeklySummaryDTO` – Devuelve un resumen general del progreso.

---

###### Relaciones

- `WeeklyReport` → referencia a `NutritionalPlan` (en NutritionPlanning)
- `WeeklyReport` → se asocia a un `User` por `usuarioId`

#### Bounded Context: IAM

Este contexto gestiona la **identidad y acceso de los usuarios**, incluyendo la autenticación, autorización mediante roles y la asociación de estos con los usuarios. Es fundamental para garantizar el control de acceso dentro del sistema.

---

##### Clase: `User`

###### Propósito:

Representa a un usuario del sistema, ya sea paciente, nutricionista o administrador. Se encarga de manejar su identidad, credenciales y roles asignados.

###### Atributos:

- `id: Long` – Identificador único del usuario.
- `email: String` – Correo electrónico del usuario.
- `password: String` – Contraseña encriptada.
- `role: Set<Role>` – Conjunto de roles asignados.
- `createdAt: Date` – Fecha de creación del usuario.
- `updatedAt: Date` – Fecha de última actualización.

###### Métodos:

- `User()` – Constructor vacío.
- `User(email: String, password: String)` – Constructor con credenciales básicas.
- `User(email: String, password: String, roles: List<Role>)` – Constructor con roles iniciales.
- `addRole(role: Role): User` – Asigna un nuevo rol al usuario.
- `addRoles(roles: List<Role>): User` – Asigna múltiples roles al usuario.
- `getSerializedRoles(): List<String>` – Devuelve los roles como lista de strings.
- `getEmail(): String` – Devuelve el email del usuario.
- `getPassword(): String` – Devuelve la contraseña del usuario.
- `getRoles(): Set<Role>` – Devuelve el conjunto de roles asignados.

---

##### Clase: `Role`

###### Propósito:

Define un rol dentro del sistema, utilizado para controlar los permisos y acceso a funcionalidades específicas.

###### Atributos:

- `id: Long` – Identificador del rol.
- `name: Roles (enum)` – Nombre del rol, como `ROLE_ADMIN`, `ROLE_USER`, etc.

###### Métodos:

- `Role()` – Constructor vacío.
- `Role(name: Roles)` – Constructor con nombre de rol.
- `getStringName(): String` – Devuelve el nombre del rol como string.
- `getDefaultRole(): Role` – Devuelve el rol por defecto.
- `toRoleFromName(name: String): Role` – Convierte un string al rol correspondiente.
- `validateRoleSet(roles: List<Role>): List<Role>` – Valida y filtra un conjunto de roles.
- `getId(): Long` – Devuelve el ID del rol.
- `getName(): Roles` – Devuelve el nombre del rol.
- `setId(id: Long): void` – Asigna el ID del rol.
- `setName(name: Roles): void` – Asigna el nombre del rol.

---

##### Enumeración: `Roles`

###### Propósito:

Define los posibles valores de roles utilizados en el sistema.

###### Valores:

- `ROLE_ADMIN`
- `ROLE_NUTRITIONIST`
- `ROLE_USER`

---

## Relaciones

- `User` → puede tener muchos `Role`.
- `Role` → pertenece a uno o más `User`.
- `Roles` (enum) → define las constantes de los nombres de rol utilizados por `Role`.

#### Bounded Context: Subscription

Este contexto gestiona la **suscripción de usuarios al sistema**, incluyendo el tipo de plan contratado, su duración, estado y renovación. Se relaciona directamente con el contexto de `Payment` para validar los pagos asociados.

---

##### Clase: `Subscription`

###### Propósito:

Representa una suscripción activa o pasada de un usuario a un plan del sistema. Permite modificar el tipo de plan o renovarlo.

###### Atributos:

- `id: Long` – Identificador único de la suscripción.
- `planType: PlanTypes (enum)` – Tipo de plan contratado.
- `userId: UserId` – Identificador del usuario.
- `startDate: LocalDate` – Fecha de inicio de la suscripción.
- `renewDate: LocalDate` – Fecha de renovación automática.
- `status: String` – Estado de la suscripción (ej: ACTIVA, CANCELADA).
- `cost: double` – Costo del plan.
- `createdAt: Date` – Fecha de creación del registro.
- `updatedAt: Date` – Fecha de última modificación.

###### Métodos:

- `Subscription(command: CreateSubscriptionCommand)` – Constructor de suscripción.
- `updatePlanType(command: UpdatePlanTypeCommand): void` – Cambia el tipo de plan.
- `renewPlan(command: RenewSubscriptionCommand): void` – Renueva la suscripción.
- `getUserId(): Long` – Devuelve el ID del usuario.
- `getPlanType(): PlanTypes` – Devuelve el tipo de plan.
- `getStartDate(): LocalDate` – Devuelve la fecha de inicio.
- `getRenewDate(): LocalDate` – Devuelve la fecha de renovación.
- `getStatus(): String` – Devuelve el estado.
- `getCost(): double` – Devuelve el costo.

---

##### Enumeración: `PlanTypes`

###### Propósito:

Define los tipos de suscripciones disponibles en el sistema.

###### Valores:

- `BASIC`
- `PREMIUM`
- `STANDARD`

---

##### Relaciones

- `Subscription` → pertenece a un `User` (desde IAM).
- `Subscription` → tiene uno o más `Payment`.

---

#### Bounded Context: Payment

Este contexto gestiona la **información de pagos asociados a suscripciones**, incluyendo datos de tarjeta, fecha de vencimiento, CVV, estado de pago, y más.

---

##### Clase: `Payment`

###### Propósito:

Representa un pago realizado por un usuario para una suscripción, guardando detalles sensibles como método de pago, fecha y estado.

###### Atributos:

- `id: Long` – Identificador del pago.
- `subscriptionId: Long` – Referencia a la suscripción asociada.
- `date: LocalDate` – Fecha en la que se realizó el pago.
- `state: String` – Estado del pago (ej: APROBADO, RECHAZADO).
- `cardHolderName: String` – Nombre en la tarjeta.
- `cardNumber: String` – Número de la tarjeta (enmascarado).
- `expireDate: Date` – Fecha de expiración de la tarjeta.
- `cvv: String` – Código de seguridad.
- `createdAt: Date` – Fecha de creación del registro.
- `updatedAt: Date` – Fecha de última modificación.

###### Métodos:

- `Payment(command: CreatePaymentCommand)` – Constructor de pago.
- `getSubscriptionId(): Long` – Devuelve el ID de la suscripción.
- `getDate(): LocalDate` – Devuelve la fecha del pago.
- `getState(): String` – Devuelve el estado del pago.
- `getCardHolderName(): String` – Devuelve el nombre del titular.
- `getCardNumber(): String` – Devuelve el número de tarjeta.
- `getExpireDate(): String` – Devuelve la fecha de vencimiento.
- `getCvv(): String` – Devuelve el código de seguridad.

---

###### Relaciones

- `Payment` → pertenece a una `Subscription`.

#### 4.2.1.1. Domain Layer

#### Domain Layer - NutritionPlanning

La capa de dominio representa el núcleo de la lógica de negocio de la aplicación. Define los conceptos fundamentales del dominio, sus reglas y relaciones, utilizando elementos como Aggregates, Entities, Value Objects, Domain Services y comandos/consultas.

#### Aggregates

#### NutritionalPlan

Es la raíz del agregado que encapsula toda la lógica del plan nutricional de un usuario durante una semana. Garantiza la integridad y coherencia de los elementos que lo componen: los DailyPlans y sus ScheduledMeals.

**Métodos:**

- `activatePlan()`
- `deactivatePlan()`
- `getPlanSummary(): PlanSummaryDTO`
- `getDailyPlan(weekDay: WeekDay): DailyPlan`
- `scheduleMeal(weekDay: WeekDay, timeDay: TimeDay, meal: ScheduledMeal): void`
- `addFoodToMeal(weekDay: WeekDay, timeDay: TimeDay, food: PlannedFood): void`
- `removeFoodFromMeal(weekDay: WeekDay, timeDay: TimeDay, foodId: Long): void`

#### Entities

#### DailyPlan

Representa el conjunto de comidas planificadas para un día específico de la semana.

**Propiedades:**

- `weekDay: WeekDay`
- `scheduledMeals: List<ScheduledMeal>`

**Métodos:**

- `addScheduledMeal(meal: ScheduledMeal): void`
- `removeScheduledMeal(timeDay: TimeDay): void`
- `getMeals(): List<ScheduledMeal>`
- `totalCalories(): Int`

#### ScheduledMeal

Representa una comida específica (por ejemplo, desayuno o almuerzo) dentro de un día del plan.

**Propiedades:**

- `timeDay: TimeDay`
- `plannedFoods: List<PlannedFood>`
- `recipeId: Long?`

**Métodos:**

- `addFoodItem(foodItem: PlannedFood): void`
- `removeFoodItem(foodId: Long): void`
- `getRecipe(): Recipe`
- `totalCalories(): Int`

#### PlannedFood

Representa un alimento específico que será consumido dentro de una comida.

**Propiedades:**

- `foodId: Long`
- `amount: Int`
- `unit: Unit`

**Método:**

- `calculateCalories(): Int`

#### Value Objects

##### WeekDay (Enum)

Días de la semana:

- `MONDAY`, `TUESDAY`, `WEDNESDAY`, `THURSDAY`, `FRIDAY`, `SATURDAY`, `SUNDAY`

##### TimeDay (Enum)

Momentos del día para planificar comidas:

- `BREAKFAST`, `MIDMORNING`, `LUNCH`, `DINNER`

##### Unit (Enum)

Unidades válidas para los alimentos:

- `GRAM`, `KILOGRAM`, `MILLILITER`, `LITER`, `UNIT`, `SLICE`, `TABLESPOON`, `TEASPOON`, `CUP`, `PIECE`

### Commands

Acciones que modifican el estado del dominio:

- `CreateNutritionalPlanCommand(userId, startDate, name, description)`
- `DeleteNutritionalPlanCommand(planId)`
- `ActivatePlanCommand(planId)`
- `DeactivatePlanCommand(planId)`
- `ScheduleMealCommand(planId, weekDay, momentDay, recipeId?, List<PlannedFoodDTO>)`
- `AddFoodToMealCommand(planId, weekDay, momentDay, foodId, quantity)`
- `RemoveFoodFromMealCommand(planId, weekDay, momentDay, foodId)`
- `ReplaceMealRecipeCommand(planId, weekDay, momentDay, recipeId)`

### Queries

Consultas que permiten leer el estado del dominio:

- `GetNutritionalPlanQuery(planId)`
- `GetDailyPlanQuery(planId, weekDay)`
- `GetScheduledMealQuery(planId, weekDay, momentDay)`
- `GetWeeklySummaryQuery(planId)`
- `ListAllPlansForUserQuery(userId)`

### Domain Services

Servicios de dominio encargados de manejar lógica de negocio que no corresponde exclusivamente a una entidad:

- `NutritionalPlanCommandService`
- `DailyPlanCommandService`
- `ScheduledMealCommandService`
- `NutritionalPlanQueryService`
- `DailyPlanQueryService`
- `ScheduledMealQueryService`

---

#### Domain Layer - WeeklyReport

La capa de dominio representa el núcleo de la lógica del módulo de reportes semanales. Define los conceptos clave del dominio, sus atributos, comportamientos y relaciones, centrándose en representar el progreso del paciente con respecto a un plan nutricional.

#### Aggregates

#### WeeklyReport

Agregado raíz que representa el reporte semanal generado para un paciente. Centraliza la información sobre cumplimiento, consumo calórico y evolución del peso.

**Atributos:**

- `id: Long`
- `userId: Long`
- `planId: Long`
- `weekStart: Date`
- `weekEnd: Date`
- `mealsPlanned: Int`
- `mealsLogged: Int`
- `adherence: Float`
- `caloriesPlanned: Int`
- `caloriesConsumed: Int`
- `startingWeight: Float`
- `endingWeight: Float`
- `generatedAt: DateTime`

**Métodos:**

- `calculateAdherence(): Float`
- `calculateCaloricBalance(): Int`
- `hasProgress(): Boolean`
- `generateSummary(): WeeklySummaryDTO`

#### Value Objects

Actualmente no se definen Value Objects independientes, ya que los datos están encapsulados directamente en el agregado `WeeklyReport`.

---

### Commands

Acciones que modifican o generan nuevos elementos en el dominio:

- `GenerateWeeklyReportCommand(userId, planId, weekStart, weekEnd, mealsPlanned, mealsLogged, caloriesPlanned, caloriesConsumed, startingWeight, endingWeight)`

---

### Queries

Consultas para obtener información del dominio:

- `GetWeeklyReportQuery(reportId)`
- `ListWeeklyReportsForUserQuery(userId)`
- `GetReportByWeekQuery(userId, weekStart)`

---

### Domain Services

Servicios de dominio que encapsulan reglas de negocio complejas que no pertenecen a una sola entidad:

- `WeeklyReportCommandService`
- `WeeklyReportQueryService`

---

#### Domain Layer - RecipesAndFood

La capa de dominio representa el núcleo de la lógica relacionada con la gestión de alimentos y recetas. Define los conceptos fundamentales, sus atributos, comportamientos y relaciones dentro de este bounded context.

#### Aggregates

#### Recipe

Es la raíz del agregado que encapsula la lógica de una receta alimentaria. Gestiona su identidad, descripción, instrucciones y la lista de ingredientes que la componen.

**Propiedades:**

- `id: Long`
- `name: String`
- `description: String`
- `instructions: String`
- `createdBy: Long`
- `ingredients: List<MealIngredient>`

**Métodos:**

- `addIngredient(foodId: Long, quantity: Int): void`
- `removeIngredient(foodId: Long): void`
- `getTotalCalories(): Int`

#### Entities

#### Food

Representa un alimento individual con su información nutricional asociada.

**Propiedades:**

- `id: Long`
- `name: String`
- `unit: Unit`
- `caloriesPerUnit: Float`
- `proteinPerUnit: Float`
- `carbsPerUnit: Float`
- `fatPerUnit: Float`

**Método:**

- `getNutritionalInfo(): NutritionDTO`

#### Value Objects

##### Unit (Enum)

Unidades válidas para los alimentos:

- `GRAM`
- `KILOGRAM`
- `MILLILITER`
- `LITER`
- `UNIT`
- `SLICE`
- `TABLESPOON`
- `TEASPOON`
- `CUP`
- `PIECE`

#### Commands

Acciones que modifican el estado del dominio:

- `CreateRecipeCommand(name, description, instructions, createdBy)`
- `AddIngredientToRecipeCommand(recipeId, foodId, quantity)`
- `RemoveIngredientFromRecipeCommand(recipeId, foodId)`
- `DeleteRecipeCommand(recipeId)`
- `UpdateFoodNutritionalInfoCommand(foodId, updatedValues)`
- `CreateFoodCommand(name, unit, calories, proteins, carbs, fats)`

#### Queries

Consultas que permiten obtener información del dominio:

- `GetRecipeQuery(recipeId)`
- `ListAllRecipesByUserQuery(userId)`
- `GetFoodQuery(foodId)`
- `ListAllFoodsQuery()`

#### Domain Services

Servicios de dominio encargados de manejar lógica de negocio transversal:

- `RecipeCommandService`
- `FoodCommandService`
- `RecipeQueryService`
- `FoodQueryService`

---

#### Domain Layer - Profiles

La capa de dominio representa el núcleo de la lógica de negocio relacionada con los profesionales de la nutrición y los pacientes. Define las entidades principales, sus relaciones, comportamientos y validaciones, a través de Entities, Value Objects y Domain Services.

#### Entities

#### Nutritionist

Representa a un profesional de la salud encargado de gestionar planes nutricionales y hacer seguimiento del progreso de los pacientes.

**Propiedades:**

- `id: Long`
- `userId: Long`
- `patientIds: List<Long>`
- `licenseNumber: String`
- `specialization: String`
- `yearsOfExperience: Int`
- `description: String`
- `isVerified: Boolean`
- `createdAt: DateTime`

**Métodos:**

- `updateProfile(specialization: String, description: String): void`
- `verifyLicense(): void`
- `getAssignedPatients(): List<PatientProfile>`
- `getActivePlans(): List<NutritionalPlan>`
- `assignPatient(patientId: Long): void`
- `unassignPatient(patientId: Long): void`
- `listPatients(): List<PatientProfile>`
- `createNutritionalPlan(patientId: Long, planData: NutritionalPlanDTO): NutritionalPlan`
- `reviewWeeklyReport(patientId: Long): WeeklyReport`

#### PatientProfile (PerfilUsuario)

Contiene la información personal, biométrica y de estilo de vida del usuario paciente.

**Propiedades:**

- `id: Long`
- `userId: Long`
- `name: String`
- `birthdate: Date`
- `gender: Gender`
- `height: Float`
- `weight: Float`
- `activityLevel: ActivityLevel`

**Métodos:**

- `updateProfile(data: ProfileDTO): void`
- `getAge(): Int`
- `isComplete(): Boolean`

#### Value Objects

##### Gender (Enum)

Categoriza el género del paciente:

- `MALE`
- `FEMALE`
- `OTHER`

##### ActivityLevel (Enum)

Clasifica el nivel de actividad física del paciente:

- `SEDENTARY`
- `MODERATE`
- `ACTIVE`

#### Domain Services

Servicios de dominio que gestionan operaciones entre perfiles de usuario y nutricionistas, validaciones cruzadas o lógicas que no pertenecen exclusivamente a una entidad.

- `ProfileManagementService`
- `PatientAssignmentService`
- `NutritionistVerificationService`

---

#### 4.2.1.2. Interface Layer

#### Interface Layer - NutritionPlanning

Esta capa define los puntos de entrada de la aplicación desde el exterior, como controladores HTTP (REST API). Se encarga de recibir las solicitudes del cliente, transformarlas en comandos o queries, y delegarlas a la capa de aplicación. También transforma las respuestas del dominio en formatos comprensibles por el cliente.

#### Resources

Clases que representan las estructuras de datos que viajan entre el cliente y la aplicación.

- `NutritionalPlanResource.java`  
  Representa un plan nutricional completo con todos sus días y comidas asociadas.

- `DailyPlanResource.java`  
  Representa un día específico de un plan nutricional.

- `ScheduledMealResource.java`  
  Representa una comida planificada en un momento del día.

- `PlannedFoodResource.java`  
  Representa un alimento planificado con su cantidad y unidad.

#### Controllers

Clases encargadas de exponer endpoints REST para las funcionalidades del dominio.

- `NutritionalPlansController.java`

  - POST `/plans` → Crear un nuevo plan nutricional
  - DELETE `/plans/{id}` → Eliminar un plan
  - PUT `/plans/{id}/activate` → Activar un plan
  - PUT `/plans/{id}/deactivate` → Desactivar un plan
  - GET `/plans/{id}` → Obtener un plan específico
  - GET `/plans/user/{userId}` → Listar todos los planes de un usuario

- `DailyPlansController.java`

  - GET `/plans/{id}/days/{weekDay}` → Obtener plan diario
  - POST `/plans/{id}/days/{weekDay}/meals` → Agendar comida

- `ScheduledMealsController.java`
  - GET `/plans/{id}/days/{weekDay}/meals/{momentDay}` → Obtener comida específica
  - PUT `/plans/{id}/days/{weekDay}/meals/{momentDay}/foods` → Agregar alimento
  - DELETE `/plans/{id}/days/{weekDay}/meals/{momentDay}/foods/{foodId}` → Quitar alimento
  - PUT `/plans/{id}/days/{weekDay}/meals/{momentDay}/recipe` → Reemplazar receta

#### Transformers / Assemblers

Clases responsables de transformar entre recursos (DTOs) y comandos o entidades del dominio.

- `NutritionalPlanResourceFromEntityAssembler.java`
- `DailyPlanResourceFromEntityAssembler.java`
- `ScheduledMealResourceFromEntityAssembler.java`
- `PlannedFoodResourceFromEntityAssembler.java`

- `CreateNutritionalPlanCommandFromResourceAssembler.java`
- `ScheduleMealCommandFromResourceAssembler.java`
- `AddFoodToMealCommandFromResourceAssembler.java`
- `ReplaceMealRecipeCommandFromResourceAssembler.java`

---

#### Interface Layer - WeeklyReport

Esta capa expone los endpoints y recursos necesarios para interactuar con los reportes semanales a través de HTTP (REST API).

#### Controllers

##### WeeklyReportController

Responsable de manejar las solicitudes HTTP relacionadas con reportes semanales.

**Endpoints:**

- `GET /weekly-reports/{reportId}`  
  Obtiene un reporte semanal por su ID.

- `GET /users/{userId}/weekly-reports`  
  Lista todos los reportes semanales de un usuario.

- `GET /users/{userId}/weekly-reports/week?startDate=yyyy-MM-dd`  
  Obtiene el reporte semanal correspondiente a una semana específica.

- `POST /weekly-reports`  
  Genera un nuevo reporte semanal con los datos del progreso del paciente.

---

### Interface Layer - RecipesAndFood

La capa de interfaz o presentación expone los endpoints necesarios para la interacción de usuarios o sistemas externos con el bounded context de gestión de recetas y alimentos. Aquí se definen controladores REST y clases de ensamblaje (transformers).

#### Resources

Clases que representan los datos que se reciben y se envían desde/hacia la capa de presentación.

- `RecipeResource.java`  
  Representa la estructura de datos para mostrar una receta.

- `FoodResource.java`  
  Estructura que encapsula los datos nutricionales y de identificación de un alimento.

- `CreateRecipeResource.java`  
  Payload para la creación de una receta.

- `AddIngredientResource.java`  
  Payload para agregar un ingrediente a una receta.

- `CreateFoodResource.java`  
  Estructura de datos utilizada para registrar un nuevo alimento.

#### Controllers

Encargados de recibir las peticiones HTTP, validar datos, delegar en la capa de aplicación y devolver la respuesta.

- `RecipesController.java`  
  Expone endpoints como:

  - `POST /recipes`
  - `GET /recipes/{id}`
  - `POST /recipes/{id}/ingredients`
  - `DELETE /recipes/{id}/ingredients/{foodId}`

- `FoodsController.java`  
  Expone endpoints como:
  - `GET /foods`
  - `GET /foods/{id}`
  - `POST /foods`
  - `PUT /foods/{id}`

#### Transformers / Assemblers

Clases utilitarias para convertir entre recursos y entidades del dominio.

- `RecipeResourceFromEntityAssembler.java`  
  Convierte una entidad `Recipe` en un `RecipeResource`.

- `RecipeFromResourceCommandAssembler.java`  
  Ensambla un `CreateRecipeCommand` a partir de un `CreateRecipeResource`.

- `FoodResourceFromEntityAssembler.java`  
  Ensambla un `FoodResource` desde una entidad `Food`.

- `FoodFromResourceCommandAssembler.java`  
  Ensambla comandos de creación o actualización de alimento a partir de recursos.

---

### Interface Layer - Profiles

La capa de interfaz expone la funcionalidad del sistema al exterior (por ejemplo, a través de una API REST), delegando la lógica de negocio a los servicios de aplicación. Define los controladores, recursos y transformadores necesarios para la interacción con los perfiles de usuarios y nutricionistas.

#### Resources

- `/api/nutritionists`
- `/api/nutritionists/{id}`
- `/api/nutritionists/{id}/patients`
- `/api/nutritionists/{id}/plans`
- `/api/nutritionists/{id}/reports`
- `/api/patients/{id}`
- `/api/patients/{id}/profile`

#### Controllers

##### `NutritionistController`

Gestiona operaciones relacionadas con el perfil del nutricionista y la asignación de pacientes.

- `GET /nutritionists/{id}`  
  Retorna el perfil del nutricionista.

- `PUT /nutritionists/{id}`  
  Actualiza la especialización y descripción.

- `POST /nutritionists/{id}/verify-license`  
  Verifica la licencia profesional del nutricionista.

- `POST /nutritionists/{id}/patients`  
  Asigna un nuevo paciente.

- `DELETE /nutritionists/{id}/patients/{patientId}`  
  Desasigna un paciente del nutricionista.

- `GET /nutritionists/{id}/patients`  
  Lista los pacientes asignados.

- `GET /nutritionists/{id}/plans`  
  Lista los planes activos de los pacientes del nutricionista.

- `POST /nutritionists/{id}/patients/{patientId}/plans`  
  Crea un plan nutricional para un paciente.

- `GET /nutritionists/{id}/patients/{patientId}/weekly-report`  
  Revisa el reporte semanal del paciente.

##### `PatientProfileController`

Gestiona las operaciones relacionadas con el perfil del paciente.

- `GET /patients/{id}/profile`  
  Obtiene el perfil del paciente.

- `PUT /patients/{id}/profile`  
  Actualiza los datos del perfil.

- `GET /patients/{id}/profile/age`  
  Calcula la edad del paciente.

- `GET /patients/{id}/profile/completeness`  
  Verifica si el perfil está completo.

#### Transformers / Assemblers

Encargados de convertir entre DTOs y objetos de dominio o respuestas HTTP.

- `NutritionistAssembler`

  - `toDTO(Nutritionist): NutritionistDTO`
  - `fromDTO(NutritionistDTO): Nutritionist`

- `PatientProfileAssembler`

  - `toDTO(PatientProfile): ProfileDTO`
  - `fromDTO(ProfileDTO): PatientProfile`

- `WeeklyReportAssembler`
  - `toDTO(WeeklyReport): WeeklyReportDTO`

---

#### 4.2.1.3. Application Layer

#### Application Layer - NutritionPlanning

La capa de aplicación coordina los flujos de procesos del negocio, orquestando la ejecución de comandos y consultas definidos en el dominio. Se encarga de manejar los casos de uso del sistema, delegando la lógica de negocio a la Domain Layer y gestionando la persistencia a través de interfaces como los repositorios. Esta capa expone las **capacidades** (capabilities) del sistema, y está compuesta por **Command Handlers**, **Query Handlers** y, eventualmente, **Event Handlers**.

#### Command Handlers

Encargados de ejecutar operaciones que modifican el estado del dominio. Cada handler implementa un caso de uso del negocio.

- `CreateNutritionalPlanCommandHandler.java`  
  Crea un nuevo plan nutricional para un usuario.

- `DeleteNutritionalPlanCommandHandler.java`  
  Elimina un plan nutricional existente.

- `ActivatePlanCommandHandler.java`  
  Activa un plan nutricional, asegurando que otros planes queden desactivados.

- `DeactivatePlanCommandHandler.java`  
  Desactiva un plan nutricional.

- `ScheduleMealCommandHandler.java`  
  Agrega una nueva comida a un día del plan.

- `AddFoodToMealCommandHandler.java`  
  Agrega un alimento específico a una comida planificada.

- `RemoveFoodFromMealCommandHandler.java`  
  Elimina un alimento específico de una comida.

- `ReplaceMealRecipeCommandHandler.java`  
  Reemplaza la receta asociada a una comida planificada.

#### Query Handlers

Se encargan de ejecutar consultas de solo lectura sobre el modelo de dominio.

- `GetNutritionalPlanQueryHandler.java`  
  Obtiene los datos completos de un plan nutricional.

- `GetDailyPlanQueryHandler.java`  
  Devuelve las comidas planificadas para un día específico.

- `GetScheduledMealQueryHandler.java`  
  Obtiene una comida específica del plan.

- `GetWeeklySummaryQueryHandler.java`  
  Calcula y devuelve un resumen semanal del plan (calorías por día, por ejemplo).

- `ListAllPlansForUserQueryHandler.java`  
  Devuelve todos los planes nutricionales asociados a un usuario.

#### Event Handlers

(Actualmente no definidos)

---

#### Application Layer - WeeklyReport

Esta capa coordina los flujos de negocio a través de command handlers y query handlers. Aquí se define cómo se ejecutan las operaciones que responden a los requerimientos de la aplicación.

#### Command Handlers

- `GenerateWeeklyReportCommandHandler`  
  Se encarga de crear y persistir un nuevo reporte semanal a partir de los datos del usuario y su progreso.

#### Query Handlers

- `GetWeeklyReportQueryHandler`
- `ListWeeklyReportsForUserQueryHandler`
- `GetReportByWeekQueryHandler`

---

### Application Layer - RecipesAndFood

La capa de aplicación orquesta los flujos de procesos del negocio mediante el uso de comandos, eventos y servicios. Define los _capabilities_ de la aplicación y conecta la capa de presentación con la lógica de dominio.

#### Command Handlers

Clases responsables de manejar los comandos enviados por los controladores y ejecutar las acciones sobre el dominio.

- `CreateRecipeCommandHandler`  
  Maneja la creación de una nueva receta a partir de los datos enviados por el usuario.

- `AddIngredientCommandHandler`  
  Agrega un nuevo ingrediente (referencia a un alimento) a una receta existente.

- `RemoveIngredientCommandHandler`  
  Elimina un ingrediente específico de una receta.

- `CreateFoodCommandHandler`  
  Registra un nuevo alimento con sus propiedades nutricionales.

- `UpdateFoodCommandHandler`  
  Actualiza los datos de un alimento existente.

#### Event Handlers

_No se han definido Event Handlers en este bounded context por el momento._

#### Services (Application Services)

Servicios que coordinan la ejecución de comandos complejos y componen lógica orquestada de aplicación.

- `RecipeApplicationService`  
  Servicio de aplicación para gestión de recetas. Coordina comandos como creación, adición o remoción de ingredientes.

- `FoodApplicationService`  
  Servicio de aplicación para registro, consulta y modificación de alimentos.

#### Comandos

- `CreateRecipeCommand(name, description, instructions, createdBy)`
- `AddIngredientCommand(recipeId, foodId, quantity)`
- `RemoveIngredientCommand(recipeId, foodId)`
- `CreateFoodCommand(name, unit, caloriesPerUnit, proteinPerUnit, carbsPerUnit, fatPerUnit)`
- `UpdateFoodCommand(foodId, updatedValues...)`

---

### Application Layer - Profiles

La capa de aplicación orquesta la lógica de negocio definida en la capa de dominio, coordinando la ejecución de comandos y consultas relacionados con los perfiles de usuario y nutricionistas. Sirve como puente entre la Interface Layer y el Domain Layer.

#### Commands

Acciones que modifican el estado del dominio:

- `UpdateNutritionistProfileCommand(nutritionistId, specialization, description)`
- `VerifyNutritionistLicenseCommand(nutritionistId)`
- `AssignPatientCommand(nutritionistId, patientId)`
- `UnassignPatientCommand(nutritionistId, patientId)`
- `CreateNutritionalPlanForPatientCommand(nutritionistId, patientId, planData)`
- `ReviewWeeklyReportCommand(nutritionistId, patientId)`
- `UpdatePatientProfileCommand(patientId, profileDTO)`

#### Queries

Consultas que permiten leer el estado del dominio:

- `GetNutritionistProfileQuery(nutritionistId)`
- `ListAssignedPatientsQuery(nutritionistId)`
- `ListActivePlansQuery(nutritionistId)`
- `GetPatientProfileQuery(patientId)`
- `GetPatientAgeQuery(patientId)`
- `CheckPatientProfileCompletenessQuery(patientId)`

#### Application Services

Servicios de aplicación que encapsulan la coordinación de casos de uso del negocio:

- `NutritionistCommandService`
- `NutritionistQueryService`
- `PatientProfileCommandService`
- `PatientProfileQueryService`

---

#### 4.2.1.4. Infrastructure Layer

#### Infrastructure Layer - NutritionPlanning

La capa de infraestructura contiene las implementaciones concretas que permiten a la aplicación interactuar con sistemas externos, como bases de datos, servicios de mensajería o APIs de terceros. En esta capa se implementan las interfaces definidas en la Domain Layer, especialmente los **Repositories** y potencialmente los **Message Brokers**.

#### Repositories

Implementaciones concretas de las interfaces de persistencia del dominio. Estas clases utilizan frameworks de persistencia como JPA, Hibernate o tecnologías similares para acceder a la base de datos.

- `JpaNutritionalPlanRepository.java`  
  Implementa el repositorio de planes nutricionales, permitiendo almacenar, recuperar y eliminar planes.

- `JpaDailyPlanRepository.java`  
  Proporciona acceso a los planes diarios asociados a un plan nutricional.

- `JpaScheduledMealRepository.java`  
  Permite la persistencia de comidas planificadas (ScheduledMeal) dentro de los planes diarios.

- `JpaPlannedFoodRepository.java`  
  Administra el acceso a los alimentos planificados que componen una comida.

---

#### Infrastructure Layer - WeeklyReport

Esta capa contiene las implementaciones técnicas que interactúan con servicios externos como bases de datos o mensajería.

#### Repositories

##### WeeklyReportRepository (Interface)

Define las operaciones de acceso a datos para los reportes semanales.

##### JpaWeeklyReportRepository (Implementación)

Implementación de la interfaz `WeeklyReportRepository` utilizando JPA/Hibernate para persistencia en base de datos relacional.

**Métodos comunes:**

- `findById(reportId): WeeklyReport`
- `findByUserId(userId): List<WeeklyReport>`
- `findByUserIdAndWeekStart(userId, weekStart): WeeklyReport`
- `save(report: WeeklyReport): void`

### Infrastructure Layer - RecipesAndFood

La capa de infraestructura se encarga de interactuar con servicios externos, como bases de datos o sistemas de mensajería. Contiene implementaciones concretas de interfaces definidas en el dominio, como los repositorios y adaptadores para otros servicios.

#### Repositories

Implementaciones que permiten el acceso y persistencia de entidades del dominio.

- `JpaRecipeRepository implements RecipeRepository`  
  Implementación del repositorio de recetas utilizando JPA/Hibernate. Permite crear, buscar y actualizar recetas.

- `JpaFoodRepository implements FoodRepository`  
  Implementación del repositorio de alimentos. Se encarga de almacenar y consultar objetos `Food`.

  ***

  ### Infrastructure Layer - Profiles

La capa de infraestructura proporciona implementaciones técnicas necesarias para interactuar con recursos externos, como bases de datos, servicios externos o sistemas de mensajería. Su propósito es soportar las operaciones definidas en la capa de aplicación.

#### Repositories

##### `NutritionistRepository`

Interfaz que define las operaciones de persistencia para nutricionistas.

**Métodos:**

- `findById(id: Long): Nutritionist`
- `save(nutritionist: Nutritionist): void`
- `deleteById(id: Long): void`
- `findPatientsByNutritionistId(nutritionistId: Long): List<PatientProfile>`
- `findActivePlans(nutritionistId: Long): List<NutritionalPlan>`

##### `PatientProfileRepository`

Interfaz para acceder a los perfiles de los pacientes.

**Métodos:**

- `findById(id: Long): PatientProfile`
- `save(profile: PatientProfile): void`
- `deleteById(id: Long): void`

---

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

##### 4.2.1.6.2. Bounded Context Database Design Diagram
