1. **Capítulo V: Product Implementation**
   1. **Software Configuration Management.**
      1. **Software Development Environment Configuration**

         A continuación, describiremos los productos de software que hemos empleado durante el desarrollo del proyecto. 

**Project Management**




- Trello: <https://trello.com/>

  La plataforma de Trello se empleó para la gestión de las tareas y la organización del flujo del trabajo en el proyecto. Presentándose las tareas dentro de las tarjetas en listas con el integrante encargado de realizarla. Además, utilizamos las funcionalidades como agregar las etiquetas de colores y marcar el proceso de las tareas. De esta manera pudimos hacer seguimiento a nuestros avances en el proyecto.

- Notion: <https://www.notion.so/>  

  La plataforma de Notion fue utilizada para la colaboración de los integrantes con el proyecto. Se crearon calendarios y listas con las fechas de las reuniones del equipo. Además, se hizo uso de herramientas como comentarios y menciones para fomentar el trabajo y colaboración en equipo.

**Requirements Management**

- Trello: <https://trello.com/> 

  Empleamos Trello para organizar los requisitos de la aplicación. En el que tenemos al product backlog el cual ordenamos según la prioridad aplicando Fibonacci para enumerar las historias de usuario y en otra sección organizándolas según las épicas.

**Product UX/UI Design**

- Figma: <https://www.figma.com/> 

  La plataforma de Figma nos ayudó a desarrollar los wireframes, mockups y prototyping del mobile applications.

- Miro: <https://miro.com/es/> 

  Miro nos fue de utilidad para poder realizar los As-Is Scenario Mapping y  To-Be Scenraio Mapping para cada uno de los segmentos objetivos.

- UXPressia: <https://uxpressia.com/> 

  La plataforma UXPressia se empleó para la creación de los User Personas, Empathy Maps, Journey Maps e Impact Maps. Hemos hecho uso de las plantillas que UXPressia nos ofrece para elaborar cada una de ellas. Nos permitió exportar lo que se realizó para incluirlo en el trabajo.

**Software Development**




- Landing Page

  Para el desarrollo de la landing page se hará empleó de HTML5, CSS y JavaScript.

- Frontend Web Application

  Para desarrollar la aplicación web frontend, es esencial tener una comprensión sólida de los fundamentos de HTML, CSS y JavaScript. En nuestro caso, optamos por utilizar Angular como framework de JavaScript. Además, para facilitar la creación de componentes reutilizables y accesibles, decidimos emplear PrimeNG como biblioteca de componentes UI. Nuestro stack tecnológico incluye el uso del lenguaje Java con el framework Spring Boot, junto con HTML, Angular, JavaScript, CSS y una base de datos MySQL.

**Software Testing**

Para las pruebas funcionales del software, tanto como de la Landing page y de la aplicación web, hemos utilizado las herramientas de desarrollo de los navegadores web siguientes: Google Chrome (<https://www.google.com/chrome/>), Microsoft Edge (<https://www.microsoft.com/en-us/edge>) y Mozilla Firefox (<https://www.mozilla.org/en-US/firefox/browsers/>).

**Software Deployment**

- Netlify: <https://www.netlify.com/> 

  Para implementar el despliegue de la Landing Page, se llevó a cabo la conexión entre el repositorio de Github y Netlify. Esto permite que Netlify maneje automáticamente la implementación de la Landing Page cada vez que se realice una actualización en el repositorio.

**Software Documentation**

- Google Drive: <https://www.google.com/intl/es-419_pe/drive/> 

  Esta plataforma fue empleada para crear documentos mediante Google Docs, el cual nos permite trabajar de manera colaborativa los informes de las entregas.

- Structurizr: <https://structurizr.com/> 

  Herramienta utilizada para la creación de diagramas C4 (diagrama de contexto, diagrama de contenedor y diagrama de componentes). Para elaborar los diagramas fue necesario utilizar una sintaxis parecida a un lenguaje de programación.

- GitHub: <https://github.com/> 

  Plataforma empleada tanto como para la creación de la documentación y de la Landing page. Nuestro eligió esta plataforma debido a que nos permite trabajar de manera colaborativa. 

2. **Source Code Management**

La administración y estructuración de las múltiples modificaciones se realizaron mediante la creación de un repositorio en GitHub para el proyecto. Nuestra organización se estructuró de la siguiente manera:

Organización: <https://github.com/upc-pre-202401-si729-sw51-the-coders> 

Repositorio de la Landing page: <https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page> 

Además, con el objetivo de mejorar el control sobre la creación de ramas y la implementación de cambios en el código fuente, se procedió a utilizar Gitflow.

De esta forma, se establecieron 2 ramas principales: main y develop.

**Ramas principales:**

Rama “main”: En esta rama se almacenan las versiones oficiales de nuestro repositorio para pasarlas a producción.

Rama “develop”: Esta rama se utilizará como punto de integración para las ramas de “feature”. Una vez que el  “head” sea estable y el equipo lo considere listo para el lanzamiento, se fusionará con la rama “release”.

**Ramas auxiliares:**

Rama “release”: La rama “release” se emplea para la preparación del lanzamiento de una nueva versión en la rama “main” ayudando a controlar las versiones de código. Aquí se pueden solucionar errores menores y preparar los datos para la versión. Esta rama permitirá liberar a la rama “develop” de estas tareas preparatorias y evita demoras en el desarrollo mientras se prepara para el lanzamiento. 

Rama “feature”: En las ramas “feature” se desarrollan las características generales que se integrarán en la rama “develop”. Estas características son aquellas funcionalidades solicitadas por los usuarios tanto en la página de inicio como en la aplicación web. Por ejemplo, la rama feature/navbar.

Rama “hotfix”: Esta rama se utiliza para corregir urgentemente errores en la última versión de la rama “main” que no pueden esperar hasta el próximo lanzamiento para ser solucionados.





3. **Source Code Style Guide & Conventions**

`        `Utilizaremos el lenguaje de etiquetas HTML para el desarrollo principal de nuestra Landing page.

●        Utilizaremos el lenguaje CSS, que nos permitirá realizar los estilos de la estructura de nuestra Landing Page

●        Implementaremos el lenguaje de JavaScript para brindar las funcionalidades a nuestra Landing page. 

●        Utilizaremos el lenguaje Gherkin que se usará para realizar los diseños de prueba de cada historia de usuario, contando con su estructura básica. 

**Convenciones de Commits:**

Nuestro equipo de desarrollo sigue las Convenciones de Commits, adoptando el formato de los “Conventional Commits” en su versión 1.0.0 (disponible en <https://www.conventionalcommits.org/en/v1.0.0/>) para garantizar una fácil comprensión de nuestros registros. Por lo tanto, nos regimos por la siguiente estructura:

**Donde:**

**<type>[scope opcional]: <description>**




- type: Indica el tipo de modificación realizada, limitado a opciones como feat, fix, docs, etc.
- scope: Define el alcance del cambio realizado en nuestro código.
- descripción: Ofrece un resumen conciso de los cambios implementados.

**Convenciones de versionado de lanzamientos**

Para la gestión de versiones, seguimos el estándar “Semantic Versioning 2.0.0”. En este formato las versiones se presentan como (X.Y.Z), con las siguientes interpretaciones: 

- X: Indica una versión principal que incorpora cambios incompatibles con versiones anteriores. Iniciamos en 0 durante la etapa de desarrollo inicial y transicionamos a 1 cuando la versión esté lista para su lanzamiento público. Por convención, Y y Z se reinician a 0 cuando X aumenta.
- Y: Representa una versión secundaria, que abarca cambios compatibles con versiones anteriores. Además, esta incluye los commits provenientes de las “release branches” cada vez que se agregan nuevas funcionalidades. Convencionalmente, Z se reinicia a 0 cuando Y aumenta.
- Z: Refleja parches y correcciones de errores menores, integrando commits realizados en la “rama de corrección” y fusionados con la rama principal.
4. **Software Deployment Configuration.**

   Entrar a Netlify y presionar la opción de “Import an existing project”

![Interfaz de usuario gráfica, Texto, Aplicación, Chat o mensaje de texto

Descripción generada automáticamente]

Después seleccionar la opcion de “Deploy con github”

![ref1]

Tras haber hecho eso tenemos que seleccionar nuestra organización y dentro de ella buscar el repositorio del proyecto que deseamos subir a producción

Para finalmente agregar la data necesaria para el despliegue

![ref2]

Y final solo presionar el botón con el nombre de proyecto a desplegar

![Imagen que contiene Texto

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.004.png)

\-       Link de la Landing page:[ ](https://echero11.github.io/OpenSource_GasYa_LandingPage/)[**https://upc-pre-202401-si729-sw51-cartunn.netlify.app**](https://upc-pre-202401-si729-sw51-cartunn.netlify.app)

2. **Product Implementation & Deployment**
   1. **Sprint 1**
      1. **Sprint planning 1**

En este sprint planning 1 se presenta la evidencia de la planificación e implementación de la landing page. Además, se evidenciaron los avances del proyecto e insights de colaboración en el equipo a través de GitHub.

|**Sprint #**|Sprint 1|
| :- | :- |
|**Sprint Planning Background**||
|**Date**|7 de abril de 2024|
|**Time**|12:00 horas (GMT-5)|
|**Location**|Modalidad remota|
|**Prepared By**|TheCoders|
|**Attendees (to planning meeting)**|Todos los miembros de TheCoders|
|**Sprint n - 0 Review Summary**|Debido a que es el primer sprint, no hay review summary de un sprint anterior|
|**Sprint n - 1 Retrospective Summary**|En este Sprint se planea desarrollar el landing page con HTML y CSS3. Previamente, el landing page se diseñó en Figma. El grupo discutió cómo diseñar el landing, implementación de imágenes y todo lo referente a la interfaz. Al finalizar este sprint, el landing page estará desplegado en Netlify y entonces cualquier usuario podrá acceder al landing a través del link.|

|**Sprint Goal & User Stories**||
| :- | :- |
|**Sprint Velocity 1**|8|
|**Sum of Story Points**|8|




2. **Sprint Backlog 1**

En esta parte mostramos las tareas que se realizaron en este sprint.

Link del Trello: <https://trello.com/b/BaYjwdz9/sprint-backlog-1-cartunn> 

Vista del Sprint Backlog en Trello

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.005.png)

|**Sprint #**|**Sprint 1**|||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|**User Story**|**Work-item / Task**|||||||
|ID|Title|Id|Title|Description|Estimation(hours)|Assigned To|Status (To-do/in-Process/To-Review/Done)|
|E1-US01|Barra de navegación en la landing page|T1|Navbar section|<p>Implementar navbar</p><p>con botón (redirige a la aplicación) y responsive design, </p>|1h|David Soto|Done|
|E1-US02|Dirigirse a la aplicación mediante el landing page|T2|Button Call to Action|<p></p><p>Implementar el button Call to Action del navbar</p>|0\.1h|David Soto|Done|
|E1-US03|Sección hero del landing page|T3|Navbar section responsive|Aplicar diseño responsive a las opciones del navbar|1h|David Soto|Done|
|E1-US03|Sección hero del landing page|T4|hero section|Implementar un hero secion|1h|Abraham Ayquipa|Done|
|E1-US03|Sección hero del landing page|T5|<p>responsive</p><p>design</p><p>hero</p><p>section</p>|aplicar design responsive al hero section|x|Abraham Ayquipa|Done|
|E1-US03|Sección hero del landing page|T6|<p>Product section</p><p>and items</p>|Implementar Product section y los ítems característicos en orden grid|1h|Franky Mallma|Done|
|E1-US03|Sección hero del landing page|T7|<p>reponsive</p><p>dessign</p><p>Product section</p><p></p>|Implementar design responsive a Product section|1h|Franky Mallma|Done|
|E1-US03|Sección hero del landing page|T8|<p>Costumers section</p><p>and items</p>|Implementar Costumers section y los ítems característicos en orden grid y aplicar animaciones|1\.5h|David Soto|Done|
|E1-US03|Sección hero del landing page|T9|<p>reponsive</p><p>dessign</p><p>Costumers section</p><p></p>|Implementar diseño responsive a Costumers section|1h|David Soto|Done|
|E1-US03|Sección hero del landing page|T10|Princing section|Implementar Princing section y los ítems característicos en orden grid |1h|Belen Ramos|Done|
|E1-US03|Sección hero del landing page|T11|<p>reponsive</p><p>dessign</p><p>Princing section</p><p></p>|Implementar diseño responsive a Princing section|1h|Belen Ramos|Done|
|E1-US03|Sección hero del landing page|T12|Contact section|Implementar Contact section y los ítems característicos en orden grid |1h|Mariana Chambi|Done|
|E1-US03|Sección hero del landing page|T13|<p>reponsive</p><p>dessign</p><p>Contact section</p><p></p>|Implementar diseño responsive a Contact section|1h|Mariana Chambi|Done|
|E1-US03|Sección hero del landing page|T14|footer section|Implementar footer section|1h|Abraham Ayquipa|Done|
|E1-US03|Sección hero del landing page|T15|Social media section|implementar icons para las redes sociales y tambien links|0\.5h|Abraham Ayquipa|Done|
|E1-US03|Sección hero del landing page|T16|<p>Reponsive</p><p>dessign</p><p>footer section</p><p></p>|Aplicar diseño responsive|1h|Mariana Chambi|Done|
|E1-US04|Versión en español de landing page|T17|Switch que activa I18n|Button de tipo switch que permite cambiar de idioma  a la landing|0\.5h|Belen Ramos|Done|




3. **Development Evidence for Sprint Review**

<table><tr><th valign="top"><b>Repository</b></th><th valign="top"><b>Branch</b></th><th valign="top"><b>Commit Id</b></th><th valign="top"><b>Commit Message</b></th><th valign="top"><b>Commit Message Body</b></th><th valign="top"><b>Committed on (Date)</b></th></tr>
<tr><td rowspan="17" valign="top"><p>[<b>upc-pre202401-si729-sw51-the-coders-landing-page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-landing-page)</p><p></p></td><td rowspan="17" valign="top"><b>main</b></td><td valign="top"><b>53c0c9e0717da4c5a070fd8379b9c640ca3134e7</b></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/53c0c9e0717da4c5a070fd8379b9c640ca3134e7) <b>[#3](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/pull/3) [from upc-pre-202401-si729-sw51-the-coders/develop</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/53c0c9e0717da4c5a070fd8379b9c640ca3134e7)</b></td><td valign="top"><b>-</b></td><td valign="top"><p><b>Apr 11, 2024</b></p><p></p></td></tr>
<tr><td valign="top"><b>6ba407ecc0bfc5d9a274fbe073f28df2192fdd69</b></td><td valign="top">[<b>feat: add the footer</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/6ba407ecc0bfc5d9a274fbe073f28df2192fdd69)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><p><b>236a53a872fe7561ce46082c0ddcfda1a5f77a61</b></p><p></p><p></p></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/236a53a872fe7561ce46082c0ddcfda1a5f77a61) <b>[#2](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/pull/2) [from upc-pre-202401-si729-sw51-the-coders/feature/contact-section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/236a53a872fe7561ce46082c0ddcfda1a5f77a61)</b></td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>581556d90f615484076fa5f6231af17bbb5460e3</b></td><td valign="top">[<b>feat: add the contact styles</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/581556d90f615484076fa5f6231af17bbb5460e3)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>91590cb7349d480e1e356b48a30a920cde6ba50f</b></td><td valign="top">[<b>feat: add the contact section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/91590cb7349d480e1e356b48a30a920cde6ba50f)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>f9990aa0fa2b381d93152ea59c26431cbbee9a04</b></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/f9990aa0fa2b381d93152ea59c26431cbbee9a04) <b>[#1](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/pull/1) [from upc-pre-202401-si729-sw51-the-coders/feature/pricing-section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/f9990aa0fa2b381d93152ea59c26431cbbee9a04)</b></td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>60681f8ce06921a1bfb606f2956c3ab7d28418a1</b></td><td valign="top">[<b>feat: add the pricing styles</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/60681f8ce06921a1bfb606f2956c3ab7d28418a1)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>c1ca89a363f2b17d72d8d1613f67910df058251a</b></td><td valign="top">[<b>feat: add the pricing section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/c1ca89a363f2b17d72d8d1613f67910df058251a)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>48edcefbe42adf44f4966d61c9469fd5e0476e26</b></td><td valign="top">[<b>feat: add the costumers section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/48edcefbe42adf44f4966d61c9469fd5e0476e26)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>1dc460bd1c12d6693a9122065210e5b5d9af45ec</b></td><td valign="top">[<b>feat: add the costumer section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/1dc460bd1c12d6693a9122065210e5b5d9af45ec)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>27441fc50d9dc51d47658d5886ee5ae3326847b9</b></td><td valign="top">[<b>feat: add the product section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/27441fc50d9dc51d47658d5886ee5ae3326847b9)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>5bd87558ecb5d241fb2bf1afc434171ce36e32b6</b></td><td valign="top">[<b>feat: add the product styles</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/5bd87558ecb5d241fb2bf1afc434171ce36e32b6)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>0af349eb7982ae9510b99b869e079c2a983fe54c</b></td><td valign="top">[<b>feat: add the product section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/0af349eb7982ae9510b99b869e079c2a983fe54c)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>f574d140d5d2c710a5a76310413f74c0822d1d95</b></td><td valign="top">[<b>feat: add the navbar</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/f574d140d5d2c710a5a76310413f74c0822d1d95)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>cde689db4cde22597915df332f86e82e37ba582e</b></td><td valign="top">[<b>feat: add the hero section</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/cde689db4cde22597915df332f86e82e37ba582e)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>5d392ca46cbae26c6c1af0c7f0b3ee3b7d6733cf</b></td><td valign="top">[<b>feat: add the navbar</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/5d392ca46cbae26c6c1af0c7f0b3ee3b7d6733cf)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
<tr><td valign="top"><b>7107cede24f274f3c0de6ea437d92eb5c47a5c04</b></td><td valign="top">[<b>chore: initial commit</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre-202401-si729-sw51-the-coders-landing-page/commit/7107cede24f274f3c0de6ea437d92eb5c47a5c04)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
</table>





4. **Testing Suite Evidence for Sprint Review**

<table>   <tr><th valign="top"><b>Repository</b></th><th valign="top"><b>Branch</b></th><th valign="top"><b>Commit Id</b></th><th valign="top"><b>Commit Message</b></th><th valign="top"><b>Commit Message Body</b></th><th valign="top"><b>Commited on (Date)</b></th></tr>
   <tr><td rowspan="5" valign="top"><p>[<b>upc-pre202401-si729-sw51-the-coders-acceptance-tests</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-acceptance-tests)</p><p></p></td><td rowspan="5" valign="top"><b>main</b></td><td valign="top"><b>a571cd6c5c30a97bdf55086df2256f8e543ce0bd</b></td><td valign="top">[<b>chore: add AT01.feature file</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-acceptance-tests/commit/a571cd6c5c30a97bdf55086df2256f8e543ce0bd)</td><td valign="top"><b>-</b></td><td valign="top"><p><b>Apr 11, 2024</b></p><p></p></td></tr>
   <tr><td valign="top"><b>b38f24bb4f70ae31ffdfc21e47149af91c033fd8</b></td><td valign="top">[<b>chore: add AT02.feature file</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-acceptance-tests/commit/a571cd6c5c30a97bdf55086df2256f8e543ce0bd)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
   <tr><td valign="top"><b>2822407798d69e79059a55296cdd82b14257381e</b></td><td valign="top">[<b>chore: add AT03.feature file</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-acceptance-tests/commit/a571cd6c5c30a97bdf55086df2256f8e543ce0bd)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
   <tr><td valign="top"><b>e62e30e01e229f7dfda1939f96278bf7d1a6ec16</b></td><td valign="top">[<b>chore: add AT04..feature file</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-acceptance-tests/commit/a571cd6c5c30a97bdf55086df2256f8e543ce0bd)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
   <tr><td valign="top"><b>26897e7664a9f74ac2109178c74c8835f4081031</b></td><td valign="top">[<b>chore: add AT5..feature file</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-acceptance-tests/commit/a571cd6c5c30a97bdf55086df2256f8e543ce0bd)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 11, 2024</b></td></tr>
</table>




5. **Execution Evidence for Sprint Review**

En este sprint logramos como primera fase de nuestro producto final  desarrollar nuestra landing page usando HTML y CSS, teniendo en cuenta también el desarrollo responsive para dispositivos tanto android como IOS y su respectivo despliegue en el Netlify. ![](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.006.png)












video que ilustra y explica la visualización y navegación logrados en este Sprint![](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.007.png)

Link del video: 

<https://upcedupe-my.sharepoint.com/personal/u202218475_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202218475_upc_edu_pe%2FDocuments%2Fweb-applications-prototyping-video%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ed93e3ab8-9945-48ee-a498-fcb783c15a7e>




6. **Services Documentation Evidence for Sprint Review**

En el alcance del sprint 1 se logró desarrollar la landing page, por lo que no se evidencia el empleo de web services.




7. **Software Deployment Evidence for Sprint Review**

Durante el primer sprint, desarrollamos la landing page del proyecto. El despliegue de esta página lo llevó a cabo uno de nuestros integrantes(Abraham), ya que el proceso no tomaba más de 5 minutos. Utilizamos la plataforma de Netlify para el despliegue, lo cual implicó crear una cuenta e iniciar sesión en dicha plataforma. Antes de proceder con el despliegue, realizamos varias pruebas en la rama "develop" para asegurarnos de que no surgieran problemas al desplegar la rama "main".

`		`**Pasos para este sprint:**

1. Creación de cuenta en netlify

![Interfaz de usuario gráfica

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.008.png)

2. Selección de  la opción de “add new website” para elegir el proyecto que queremos deplegar

![](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.009.png)

3. Finalmente, elegimos nuestra rama a desplegar y hacemos click en “Desploy”

   ![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.010.png)

8. **Team Collaboration Insights during Sprint**

Durante este sprint para proteger la rama “main” creamos una rama “develop” de la que cada integrante de nuestro grupo creó su propia sub-rama “feature“ para subir un capítulo del reporte siguiendo las convenciones antes señaladas(conventional commit y git flow).

![Diagrama, Esquemático

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.011.png)

**Github analytics de nuestro primer sprint:** 

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente]

2. **Sprint 2**
   1. **Sprint Planning 2.**

|**Sprint #**|Sprint 2|
| :- | :- |
|**Sprint Planning Background**||
|**Date**|7 de abril de 2024|
|**Time**|12:00 horas (GMT-5)|
|**Location**|Modalidad remota|
|**Prepared By**|TheCoders|
|**Attendees (to planning meeting)**|Todos los miembros de TheCoders|
|**Sprint n - 1 Review Summary**|<p>Corregir: </p><p>- Problem Statement</p><p>- As-Is y To-be</p><p>- Product Backlog</p><p>- Sprint Backlog</p><p>- Class Diagram</p><p>- DataBase Diagram</p><p>- Landing Page (ids)</p>|
|**Sprint n - 2 Retrospective Summary**|En este Sprint se planea desarrollar la aplicación web con Angular y Angular Material. Previamente a su respectivo diseñó en Figma. El grupo discutió que mockups haría de la landing para crear su respectiva rama que después se uniría al main branch. Al finalizar este sprint, la aplicación web estará desplegada y entonces cualquier usuario podrá acceder a través de su dominio.|

|**Sprint Goal & User Stories**||
| :- | :- |
|**Sprint Velocity 1**|8|
|**Sum of Story Points**|8|




2. **Sprint Backlog 2.**

En esta parte mostramos las tareas que se realizaron en este sprint.

Link del Trello: <https://trello.com/b/AxO4wcPY/sprint-backlog-2-cartunn> 

Vista del Sprint Backlog en Trello

|**Sprint #**|**Sprint 2**|||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|**User Story**|**Work-item / Task**|||||||
|ID|Title|Id|Title|Description|Estimation(hours)|Assigned To|Status (To-do/in-Process/To-Review/Done)|
|**E2-US01**|<p></p><p>Registro de cuentas</p><p></p>|<p>T1</p><p></p>|Interfaz de usuario del inicio de registro de cuentas|Implementar interfaz de los formularios para el registro de cuentas para ambos segmentos como cliente y staff|4|David Soto|Done|
|**E2-US02**|Inicio de sesión|T2|Interfaz de usuario de inicio de sesión|Implementar interfaz de formularios para el inicio de sesión de las cuentas de ambos segmentos como cliente y staff|2|David Soto|Done|
|**E2-US03**|Recuperación de contraseña|T3|Interfaz de usuario de recuperación de contraseña|Implementar interfaz de formularios para la recuperación de contraseña de ambos segmentos objetivos|1|David Soto|Done|
|**E3-US01**|Barra de navegación|T4|Componente de usuario de barra de navegación|Implementar el componente de barra de navegación|2|Abraham Ayquipa|Done|
|**E3-US04**|Recibir notificaciones|T5|Interfaz de usuario para recibir notificaciones |Implementar interfaz de para que el segmento cliente pueda recibir notificaciones|1|Franky Mallma|Done|
|**E3-U05**|Pasarela de pagos|T6|Interfaz de usuario para observar lista de productos y total a pagar|Implementar interfaz para la visualización de productos, total a pagar, formularios que permitan llenar la información requerida para el pago y opciones de pago|3|Alexandra Ramos|Done|
|<p></p><p>**E3-U06**</p><p></p>|<p></p><p>Visualización de Productos </p><p></p>|T7|Interfaz del usuario principal para poder ver los productos|Implementar interfaz para la sección de home(pantalla principal) |4|Mariana Chambi|Done|





3. **Development Evidence for Sprint Review.**

<table>   <tr><th valign="top"><b>Repository</b></th><th valign="top"><b>Branch</b></th><th valign="top"><b>Commit Id</b></th><th valign="top"><b>Commit Message</b></th><th valign="top"><b>Commit Message Body</b></th><th valign="top"><b>Commited on (Date)</b></th></tr>
   <tr><td rowspan="5" valign="top"><p>[<b>cartunn-frontend</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend)</p><p></p></td><td rowspan="5" valign="top"><b>main</b></td><td valign="top"><b>5ef9da4ba657c108d7379ff0b4d8c80ed5113c00</b></td><td valign="top">[<b>chore: add the main structure</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/5ef9da4ba657c108d7379ff0b4d8c80ed5113c00)</td><td valign="top"><b>-</b></td><td valign="top"><p><b>Apr 20, 2024</b></p><p></p></td></tr>
   <tr><td valign="top"><b>9c08d45cf23d7e39d7d5755e098cbc9b7d61ccb1</b></td><td valign="top">[<b>feat: add the sidebar</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/9c08d45cf23d7e39d7d5755e098cbc9b7d61ccb1)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 21, 2024</b></td></tr>
   <tr><td valign="top"><b>a7d950b0dc5de805dd9ebaeff3baef23760a15da</b></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/a7d950b0dc5de805dd9ebaeff3baef23760a15da) <b>[#1](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/1) [from upc-pre-202401-si729-sw51-the-coders/develop</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/a7d950b0dc5de805dd9ebaeff3baef23760a15da)</b></td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 21, 2024</b></td></tr>
   <tr><td valign="top"><b>dfd3ac6f732f4743e4acf9124bd95912aeb4f4be</b></td><td valign="top">[<b>feat: add the pages folder</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/dfd3ac6f732f4743e4acf9124bd95912aeb4f4be)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 21, 2024</b></td></tr>
   <tr><td valign="top"><b>0b2057a5522f79ccad99c7e3de585aa3d99d55d5</b></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/0b2057a5522f79ccad99c7e3de585aa3d99d55d5) <b>[#2](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/2) [from upc-pre-202401-si729-sw51-the-coders/feature/routing</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/0b2057a5522f79ccad99c7e3de585aa3d99d55d5)</b></td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 21, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>ccd2dcf0e32241b8955cae3e6c1e460336393e60</b></td><td valign="top"><p>[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/ccd2dcf0e32241b8955cae3e6c1e460336393e60) <b>[#3](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/3) [from upc-pre-202401-si729-sw51-the-coders/develop</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/ccd2dcf0e32241b8955cae3e6c1e460336393e60)</b></p><p></p><p></p></td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 21, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>fb1970081041f00ad482138f66faf6ca52c51491</b></td><td valign="top">[<b>fix(app.module.ts): resolve the import bugs</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/fb1970081041f00ad482138f66faf6ca52c51491)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 25, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>4972fa11cee6bc04469599cc78292ff9266c767e</b></td><td valign="top">[<b>feat: add the base service</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/4972fa11cee6bc04469599cc78292ff9266c767e)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 26, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>7fecaa08437b03864bd693758e50b913a187fa14</b></td><td valign="top"><p>[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/7fecaa08437b03864bd693758e50b913a187fa14) <b>[#4](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/4) [from upc-pre-202401-si729-sw51-the-coders/feature/fake-api</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/7fecaa08437b03864bd693758e50b913a187fa14)</b></p><p></p></td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 26, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>71b0034770588c6e459758126d1041776df05536</b></td><td valign="top">[<b>fix: resolve the call of a component</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/71b0034770588c6e459758126d1041776df05536)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 28, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>466c0da7f57e5561b20b58a6a0a66da09445ac1b</b></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/466c0da7f57e5561b20b58a6a0a66da09445ac1b) <b>[#5](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/5) [from upc-pre-202401-si729-sw51-the-coders/develop</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/466c0da7f57e5561b20b58a6a0a66da09445ac1b)</b></td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 28, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>e9ac61ab3f2c8b37596f5e7d2b29d6f454017b4a</b></td><td valign="top">[<b>fix: resolve the call of the components</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/e9ac61ab3f2c8b37596f5e7d2b29d6f454017b4a)</td><td valign="top"><b>-</b></td><td valign="top"><p><b>Apr 28, 2024</b></p><p></p></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>ed0339b18e172d41ebd8f19c913292a5b49b9db5</b></td><td valign="top">[<b>fix: resolve the routing problems</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/ed0339b18e172d41ebd8f19c913292a5b49b9db5)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 30, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>555efad472dcb371ba86014277c86812fa87897b</b></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/555efad472dcb371ba86014277c86812fa87897b) <b>[#6](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/6) [from upc-pre-202401-si729-sw51-the-coders/develop</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/555efad472dcb371ba86014277c86812fa87897b)</b></td><td valign="top"><b>-</b></td><td valign="top"><p><b>Apr 30, 2024</b></p><p></p></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>ee0214358ffdc61a86f4adf536324d48e0be590a</b></td><td valign="top">[<b>feat: add the help and center page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/ee0214358ffdc61a86f4adf536324d48e0be590a)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 30, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>ea223078bb347f657e0d0bc8ad206f6c0cfc136f</b></td><td valign="top">[<b>feat: add the notifications page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/ea223078bb347f657e0d0bc8ad206f6c0cfc136f)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 30, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>e81fb79d43fdc78b57ceabe62e901ff8000b197c</b></td><td valign="top">[<b>feat: add the reports page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/e81fb79d43fdc78b57ceabe62e901ff8000b197c)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 30, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>feb308544c397440425eca03a66c2c41be06638b</b></td><td valign="top">[<b>feat: add the notifications pages</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/feb308544c397440425eca03a66c2c41be06638b)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 30, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>117ce7af3d2d4f940afe5db1e8dd0e5a2e77ab1e</b></td><td valign="top">[<b>feat: add the reports pages</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/117ce7af3d2d4f940afe5db1e8dd0e5a2e77ab1e)</td><td valign="top"><b>-</b></td><td valign="top"><b>Apr 30, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>132818c0df47ad8a46e77cbbf2f598348a1ada3b</b></td><td valign="top">[<b>feat: shopping-cart component</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/132818c0df47ad8a46e77cbbf2f598348a1ada3b)</td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>779c548907a8281e5809e2432514c00286aeb24c</b></td><td valign="top">[<b>feat: add secure image</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/779c548907a8281e5809e2432514c00286aeb24c)</td><td valign="top"><b>-</b></td><td valign="top"><p><b>May 1, 2024</b></p><p></p></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>a973e2e979b99581df944c2eeef020f0a28361e2</b></td><td valign="top">[<b>feat: add the settings page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/a973e2e979b99581df944c2eeef020f0a28361e2)</td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>2ad7c1813f77fc872555a7a5d53a67aa478ad62d</b></td><td valign="top">[<b>feat: add the login pages</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/2ad7c1813f77fc872555a7a5d53a67aa478ad62d)</td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>bc010a9c7cbb81a09b45b7012d872f12f0cd3b79</b></td><td valign="top">[<b>feat: add the shopping cart page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/bc010a9c7cbb81a09b45b7012d872f12f0cd3b79)</td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>02d56e2cd3e02acd54b2ef94df94c35fd321b2fc</b></td><td valign="top">[<b>feat: add the home page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/02d56e2cd3e02acd54b2ef94df94c35fd321b2fc)</td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>da76b4c9430fefdb615bc365ea333a8631ee0f19</b></td><td valign="top">[<b>feat: update the shopping cart page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/da76b4c9430fefdb615bc365ea333a8631ee0f19)</td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>c0852c4193ce243d484c923d5cd8d5c86715bf32</b></td><td valign="top">[<b>feat: add the favorites page</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/c0852c4193ce243d484c923d5cd8d5c86715bf32)</td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>174e69e4f90ac398593e9d4ccd87c872ce08e551</b></td><td valign="top">[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/174e69e4f90ac398593e9d4ccd87c872ce08e551) <b>[#10](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/10) [from upc-pre-202401-si729-sw51-the-coders/develop</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/174e69e4f90ac398593e9d4ccd87c872ce08e551)</b></td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>8d9f571f593a9a0fe991e73269fc08bc849b0849</b></td><td valign="top"><p>[<b>feat: add the environment variables</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/8d9f571f593a9a0fe991e73269fc08bc849b0849)</p><p></p></td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
   <tr><td valign="top"></td><td valign="top"></td><td valign="top"><b>a8293ffba3c2abff3df5f5e4679288c6011f3afa</b></td><td valign="top"><p>[<b>Merge pull request](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/a8293ffba3c2abff3df5f5e4679288c6011f3afa) <b>[#11](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/pull/11) [from upc-pre-202401-si729-sw51-the-coders/develop</b>](https://github.com/upc-pre-202401-si729-sw51-the-coders/cartunn-frontend/commit/a8293ffba3c2abff3df5f5e4679288c6011f3afa)</b></p><p></p></td><td valign="top"><b>-</b></td><td valign="top"><b>May 1, 2024</b></td></tr>
</table>




4. **Testing Suite Evidence for Sprint Review.**

En el alcance del sprint 2 se ha desarrollado el frontend de la aplicación web por lo que no se evidencia testing.

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commit Message Body**|**Commited on (Date)**|
| :- | :- | :- | :- | :- | :- |
|||||||





5. **Execution Evidence for Sprint Review.**

En este sprint logramos como primera fase de nuestro producto final, desarrollar nuestra aplicación web usando Angular y Angular Material, en conjunto con una API hecha con JSON server. 

Muestra de todas  vistas programadas en Angular para este sprint: 

- Pantalla de Login

![Interfaz de usuario gráfica, Aplicación, Teams

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.013.png)

- Pantalla de Sign up

![Interfaz de usuario gráfica, Aplicación, Teams

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.014.png)

- Pantalla de reset you password

![Interfaz de usuario gráfica, Aplicación, Teams

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.015.png)






- Dashboard

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.016.png)

- Pantalla de favoritos

![Interfaz de usuario gráfica

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.017.png)

- Pantalla de notificaciones

![](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.018.png)






- Pantalla de status report

![Interfaz de usuario gráfica

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.019.png)

- Pantalla de Carrito de compras

![Interfaz de usuario gráfica

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.020.png)

- Pantalla de configuraciones

![Interfaz de usuario gráfica, Aplicación, Teams

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.021.png)





- Pantalla de Help and center

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.022.png)

Muestra de la respuesta de nuestra API hecha con JSON server: 

![Texto

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.023.png)

video que ilustra y explica la visualización y navegación logrados en este Sprint

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.024.png)

video:<https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218475_upc_edu_pe/EYGlhhSe3SRMpcAYXnC-JjMB_sHeALjhl19QUBri7tNWkQ?e=Zolbor&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D> 




6. **Services Documentation Evidence for Sprint Review.**

Para este sprint utilizamos los servicios básicos Http en conjunto con Json server que facilitó la construcción de nuestra fake api.

Nuestras variable de entorno serverBasePath que apuntará al puerto 3000:

![Interfaz de usuario gráfica, Texto, Aplicación

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.025.png)

Nuestra clase BaseService

![Texto

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.026.png)

Un ejemplo usando un endpoint:

![Texto

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.027.png)

7. **Software Deployment Evidence for Sprint Review.**

   Entrar a Netlify y presionar la opción de “Import an existing project”

![Interfaz de usuario gráfica, Texto, Aplicación, Chat o mensaje de texto

Descripción generada automáticamente]

Después seleccionar la opcion de “Deploy con github”

![Captura de pantalla con la imagen de una pantalla

Descripción generada automáticamente][ref1]

Tras haber hecho eso tenemos que seleccionar nuestra organización y dentro de ella buscar el repositorio del proyecto que deseamos subir a producción

Para finalmente agregar la data necesaria para el despliegue

![ref2]

Y final solo presionar el botón con el nombre de proyecto a desplegar

\-       Link de la Landing page:[ ](https://echero11.github.io/OpenSource_GasYa_LandingPage/)[https://cartunn-frontend.netlify.app](https://cartunn-frontend.netlify.app/home)

Nota: Al hacer click sobre el link por alguna extraña razón la ruta adquiere la siguiente forma: <https://cartunn-frontend.netlify.app/home> pero es necesario borrar la palabra “home” para que se pueda visualizar toda la aplicación y la ruta seria: <https://cartunn-frontend.netlify.app>. Pendiente que pensamos arreglar para el siguiente sprint.

8. **Team Collaboration Insights for Sprint Review**

Durante este sprint, al igual que para el desarrollo de la landing page, para proteger la rama “main” creamos una rama “develop” de la que cada integrante de nuestro grupo creó su propia sub-rama “feature“ para subir un capítulo del reporte siguiendo las convenciones antes señaladas(conventional commit y git flow).

![Diagrama, Texto

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.029.png)

**Github analytics de nuestro segundo sprint:** 

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente]

![Gráfico, Gráfico de líneas

Descripción generada automáticamente](Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.031.png)

**Conclusiones**

Hasta la fecha,  "CarTunn" ha avanzado significativamente en las fases de conceptualización, diseño y planificación. Nosotros como  equipo hemos logrado establecer una base sólida a través de un extenso trabajo de investigación y análisis que ha incluido la identificación de necesidades específicas de los usuarios. Se ha definido con claridad los perfiles de los usuarios y se ha elaborado una propuesta de diseño UX/UI que promete mejorar  la experiencia de personalización de vehículos.

Aunque solo  hemos implementado la landing page con todo lo aprendido hasta el momento, la preparación en las etapas previas asegura que el equipo está bien equipado para abordar la implementación con un entendimiento profundo del problema y una solución bien definida. La aplicación no solo pretende satisfacer las necesidades identificadas, sino también superar las expectativas del usuario a través de una interfaz intuitiva y una experiencia de usuario optimizada.

El progreso hasta ahora muestra un compromiso firme con la excelencia técnica y la innovación, estableciendo un  futuro satisfactorio del proyecto. Estamos en una posición favorable para iniciar la próxima fase de desarrollo, anticipando desafíos pero confiados en nuestra preparación y estrategia.

**Anexos**

Link de Microsoft Steam : 

Landing Page Wireframe y Mock-up:  

<https://www.figma.com/file/3puKCQI9HpY36ICGlYihgc/CarTunn-vFinal?type=design&node-id=224%3A2416&mode=design&t=wOoV1LZs3RIcch1q-1> 

<https://www.figma.com/file/Ra8FhHb46JMhkNThyLmwbU/Mobile-wireframe?type=design&node-id=0%3A1&mode=design&t=4IPCw13uV4ZLjkE0-1> 

<https://www.figma.com/file/mTtYszxtJt7r9ctlNzccEK/Wireframe-Landingpage?type=design&node-id=0%3A1&mode=design&t=SDb42Y1oTtVkd5Go-1> 

Web Applications Wireframes y Mock-up: [**https://www.figma.com/file/Ra8FhHb46JMhkNThyLmwbU/Mobile-wireframe?type=design&node-id=10%3A2763&mode=design&t=uEXRlWCPVG53IytA-1](https://www.figma.com/file/Ra8FhHb46JMhkNThyLmwbU/Mobile-wireframe?type=design&node-id=10%3A2763&mode=design&t=uEXRlWCPVG53IytA-1)**  

User personas

segmento 1: <https://uxpressia.com/w/DeRZM/p/7vFyy> 

segmento 2: <https://uxpressia.com/w/DeRZM/p/h3zhF> 

As-Is scenario mapping y To-be scenario mapping: <https://miro.com/welcomeonboard/NDFUcUtZQU9SWkZ4SDhKUnNoR0RFVjhWTWZnTFNGd245YVBzZU1UQkxsR3E2WjFaMURtZXY3QjRDeG1DYW53cXwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=418419123921> 

<https://miro.com/welcomeonboard/NDFUcUtZQU9SWkZ4SDhKUnNoR0RFVjhWTWZnTFNGd245YVBzZU1UQkxsR3E2WjFaMURtZXY3QjRDeG1DYW53cXwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=418419123921> 

to be 

<https://miro.com/welcomeonboard/NDFUcUtZQU9SWkZ4SDhKUnNoR0RFVjhWTWZnTFNGd245YVBzZU1UQkxsR3E2WjFaMURtZXY3QjRDeG1DYW53cXwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=418419123921> 

<https://miro.com/welcomeonboard/NDFUcUtZQU9SWkZ4SDhKUnNoR0RFVjhWTWZnTFNGd245YVBzZU1UQkxsR3E2WjFaMURtZXY3QjRDeG1DYW53cXwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=418419123921> 

Repositorio Github: <https://github.com/upc-pre-202401-si729-sw51-the-coders/upc-pre202401-si729-sw51-the-coders-acceptance-tests> 

entrevistas:[ https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c607_upc_edu_pe/ETkXbFSbZatDpAEvHzTPTJMB-mXrG_XL1xe922soG6czhQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=fIFERB](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c607_upc_edu_pe/ETkXbFSbZatDpAEvHzTPTJMB-mXrG_XL1xe922soG6czhQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=fIFERB) 

exposición:[ https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c607_upc_edu_pe/ERHF5u8IUTxHne5kc_G-4MgBYx9g1BkBvoXTWiNv0B_E_A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=xC9b5p](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c607_upc_edu_pe/ERHF5u8IUTxHne5kc_G-4MgBYx9g1BkBvoXTWiNv0B_E_A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=xC9b5p)

**Bibliografía**

- *Peru, N. (2023, junio 24). Aumentan las estafas cibernéticas de repuestos y accesorios de autos. Peru21. <https://peru21.pe/lima/estafas-sector-automotriz-ventas-electronicas-renusa-aumentan-las-estafas-ciberneticas-de-repuestos-y-accesorios-de-autos-noticia/>* 

[Interfaz de usuario gráfica, Texto, Aplicación, Chat o mensaje de texto

Descripción generada automáticamente]: Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.001.png
[ref1]: Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.002.png
[ref2]: Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.003.png
[Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente]: Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.012.png
[Interfaz de usuario gráfica, Texto, Aplicación, Chat o mensaje de texto

Descripción generada automáticamente]: Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.028.png
[Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente]: Aspose.Words.debf479b-f8e0-4343-956c-c3241a452912.030.png
