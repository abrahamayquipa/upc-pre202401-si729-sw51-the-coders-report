﻿# 3. Capítulo III: Requirements Specification 
# 3.1. To-Be Scenario Mapping.
En esta sección se presentan los To-Be Scenario Mapping para el segmento objetivo donde se reflejarán a partir de los As-Is Scenario Mapping. la experiencia de usuario ideal si se resuelven los puntos de dolor y necesidades. La herramienta usada fue Miro:

**To-be scenario mapping: Cliente que quiere customizar su auto**

<https://miro.com/welcomeonboard/NDFUcUtZQU9SWkZ4SDhKUnNoR0RFVjhWTWZnTFNGd245YVBzZU1UQkxsR3E2WjFaMURtZXY3QjRDeG1DYW53cXwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=418419123921> 


` `**Brainstorm individually:**

![](Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.001.png)


**identify phases:**

![](Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.002.png)

**To-be scenario mapping: staff mecanico**

<https://miro.com/welcomeonboard/NDFUcUtZQU9SWkZ4SDhKUnNoR0RFVjhWTWZnTFNGd245YVBzZU1UQkxsR3E2WjFaMURtZXY3QjRDeG1DYW53cXwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=418419123921> 

**Brainstorm individually:**

![](Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.003.png)

**identify phases:**

![](Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.004.png)




**identify phases:**

![](Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.002.png)

# 3.2. User Stories

|**Epic/StoryID**|**Título**|**Descripción**|**Criterios de aceptación**|**Epic ID**|
| :-: | :-: | :-: | :-: | :-: |
|<p>**Epic 1: Landing page**</p><p>**Como** cliente</p><p>**Quiero** visualizar una página</p><p>**Para** saber acerca de la aplicación e ingresar a la aplicación</p>|||||
|**E1-US01**|**Barra de navegación en la landing page**|<p>**Como** cliente o staff mecanico</p><p>**Quiero** una barra de navegación en la landing page</p><p>**Para** tener acceso directo a la aplicación</p>|<p>**Escenario 1: El cliente o staff mecánico se encuentra en el navbar de navegación**</p><p>**Dado** que el usuario se encuentra en la landing page</p><p>**Cuando** se encuentre en la sección del navbar</p><p>**Entonces** visualiza enlaces de las secciones, botón de idiomas y el botón para redirigir a la aplicación</p><p></p>|**1**|
|**E1-US02**|**Dirigirse a la aplicación mediante el landing page**|<p>**Como** cliente o staff mecanico</p><p>**Quiero** dirigirme a la aplicación mediante el botón “Open App”</p><p>**Para** poder usarla.</p><p></p>|<p>**Escenario 1: Enlace directo a la aplicación a través de un botón**</p><p>**Dado que** el cliente o staff mecánico se encuentra en la landing page</p><p>**Y** este se dirige al navbar,</p><p>**Cuando** presione el botón “Open app”</p><p>**Entonces** es dirigido a la aplicación donde se podrá loguearse.</p>|**1**|
|**E1-US03**|**Sección hero del landing page**|<p>**Como** cliente o staff mecanico</p><p>**Quiero** observar la sección hero de la landing</p><p>**Para** poder tener información de lo que es y ofrece la aplicación.</p><p></p>|<p>**Escenario 1: El cliente o staff mecánico se encuentra en la sección de hero**</p><p>**Dado que** el cliente o staff mecánico se encuentra en la landing page</p><p>**Cuando** se encuentra en la sección hero </p><p>**Entonces** observa una presentación de la aplicación.</p><p>**Escenario 2: El cliente o staff mecánico accede a la aplicación por el botón de Sign Up**</p><p>**Dado que** el cliente o staff mecánico se encuentra en la landing page</p><p>**Cuando** se encuentra en la sección hero </p><p>**Y** presiona el botón “Sign up”</p><p>**Entonces** es redirigido al formulario de registro de cuentas.</p>|**1**|
|**E1-US04**|**Versión en español de landing page**|<p>**Como** cliente y staff mecanico</p><p>**Quiero** tener al alcance una versión en español del landing page</p><p>**Para** tener accesibilidad en cuanto a opciones de idioma</p><p></p>|<p>**Escenario 1: El cliente entra a la landing page**</p><p>**Dado que** el usuario se encuentra en el landing page</p><p>**Cuando** sea su primera vez</p><p>**Entonces** el idioma predeterminado de la landing page será inglés</p><p></p><p>**Escenario 2: El cliente quiere cambiar de idioma**</p><p>**Dado que** el usuario se encuentra en la landing page</p><p>**Y** desea cambiar de idioma a español,</p><p>**Cuando** presiona el botón para cambiar de ingles a español</p><p>**Entonces** la landing page se muestra en el idioma de preferencia seleccionado.</p>|**1**|
|<p>**Epic 2: Autentificación y perfil de usuario**</p><p></p><p>**Como  cliente o miembro del staff**</p><p>**Quiero autentificar y configurar mi perfil de usuario**</p><p>**Para ingresar a la aplicación**</p>|||||
|**E2-US01**|**Registro de cuentas**|<p>**Como cliente o miembro del staff**</p><p>**Quiero poder registrar una cuenta**</p><p>**Para acceder a los servicios que ofrece**</p>|<p>**Escenario 1: El cliente quiere crear una cuenta**</p><p>**Dado que el usuario se encuentra en la pantalla de inicio**</p><p>**Cuando elige el tipo de usuario entre cliente o personal del staff mecánico**</p><p>**Y proporciona los datos correctos**</p><p>**Entonces se crea la cuenta satisfactoriamente.**</p><p></p><p>**Escenario 2: El cliente recibe un mensaje de confirmación**</p><p>**Dado que todos los datos se han completado correctamente**</p><p>**Cuando selecciona la opción de "Confirmar registro"**</p><p>**Entonces aparece un mensaje de confirmación de cuenta creada satisfactoriamente en la pantalla.**</p><p></p><p>**Escenario 3: Registro incorrecto**</p><p>**Dado que el usuario ha completado el formulario de registro**</p><p>**Cuando intenta registrarse con información incorrecta o incompleta**</p><p>**Entonces recibe un mensaje de error que indica los campos que deben corregirse o completarse.**</p>|**1**|
|**E2-US02**|**Inicio de sesión**|<p>**Como cliente o integrante del staff mecánico**</p><p>**Quiero iniciar sesión en mi cuenta**</p><p>**Para acceder a las funciones de la aplicación**</p>|<p>**Escenario 1: Inicio de sesión satisfactorio**</p><p>**Dado que el usuario se encuentra en el inicio de sesión**</p><p>**Cuando ingresa sus credenciales correctas**</p><p>**Entonces inicia sesión en su cuenta.**</p><p></p><p>**Escenario 2: Inicio de sesión sin registrar**</p><p>**Dado que el usuario se encuentra en la pantalla de inicio de sesión**</p><p>**Cuando intenta iniciar sesión sin tener una cuenta previamente registrada**</p><p>**Entonces recibe un mensaje de error indicando que no tiene una cuenta registrada**</p><p>**Y se le proporciona la opción de redirigirse a la pantalla de registro para crear una cuenta nueva.**</p>|**1**|
|**E2-US03**|**Recuperación de contraseña**|<p>**Como cliente o integrante del staff mecánico**</p><p>**Quiero recuperar la contraseña de mi cuenta**</p><p>**Para poder iniciar sesión**</p>|<p>**Escenario 1: Solicitud de cambio de contraseña**</p><p>**Dado que el usuario accede a la aplicación y se encuentra en la sección de recuperación de contraseña,** </p><p>**Cuando ingresa el correo asociado a su cuenta para recuperar la contraseña y dicho correo existe en la base de datos, Entonces se envía un mensaje de recuperación de contraseña a su dirección de correo electrónico.**</p><p></p><p>**Escenario 2: Cuenta de correo no existe**</p><p>**Dado que el usuario ingresa a la aplicación y accede a la sección de recuperación de contraseña,** </p><p>**Cuando introduce el correo asociado a su cuenta para recuperar la contraseña y dicho correo no existe en la base de datos,** </p><p>**Entonces no se envía un correo de recuperación de contraseña.**</p>|**1**|
|**E2-US04**|**Cerrar sesión**|<p>**Como cliente o integrante del staff mecánico**</p><p>**Quiero cerrar mi sesión**</p><p>**Para no dejar mi sesión abierta en un dispositivo**</p>|<p>**Escenario 1: Cerrar sesión**</p><p>**Dado que el usuario se encuentra dentro de la aplicación y selecciona el menú de la barra de navegación,** </p><p>**Cuando presiona la opción "Sign out" y confirma la acción,** </p><p>**Entonces es redirigido automáticamente al landing page.**</p><p></p>|**1**|
|<p>**Epic 3: Paneles de usuario**</p><p></p><p></p><p>**Como cliente** </p><p>**Quiero visualizar un panel**</p><p>**Para observar cada opción de navegación**</p>|||||
|**E3-US01**|**Barra de navegación**|<p>**Como cliente**</p><p>**Quiero visualizar un sidebar con links de navegación**</p><p>**Para navegar por la aplicación**</p>|<p>**Escenario 1: El cliente quiere navegar por la aplicación**</p><p>**Dado que el cliente ha observado las interfaces de la aplicación.**</p><p>**Cuando inicie sesión con su usuario y contraseña.**</p><p>**Y vea la barra de navegación**</p><p>**Entonces podrá interactuar con la aplicación con facilidad.**</p><p></p><p>**Escenario 2: El cliente quiere acceder a las secciones principales**</p><p>**Dado que el cliente ha iniciado sesión en la aplicación.**</p><p>**Cuando el cliente hace clic en el ícono de sidebar de navegación.**</p><p>**Entonces el cliente ve la lista desplegable con los links principales.**</p><p>**Y el cliente debe poder acceder rápidamente a las secciones principales al hacer clic en los links correspondientes**</p>|**1**|
|**E3-US02**|**Configuración de perfil**|<p>**Como cliente**</p><p>**Quiero poder configurar mi perfil**</p><p>**Para visualizar o modificar mis datos**</p>|<p>**Escenario 1:El cliente quiere acceder a la configuración de su perfil**</p><p>**Dado que el cliente ha iniciado sesión y se encuentra en la pantalla de inicio.**</p><p>**Cuando el cliente se dirija a la sección “Configuración de perfil”.**</p><p>**Entonces el cliente podrá observar sus datos personales actuales.**</p><p></p><p>**Escenario 2: El cliente quiere modificar sus datos personales**</p><p>**Dado que el cliente se encuentra en la pantalla de inicio.**</p><p>**Cuando el cliente accede a la sección de “Configuración de perfil”.**</p><p>**Y el cliente modifica sus datos personales.**</p><p>**Entonces el cliente debe poder editar sus datos y guardar los cambios realizados.**</p><p>**Y el cliente recibe una confirmación de que los cambios se han guardado correctamente.**</p>|**1**|
|**E3-US03**|**Ajustes de aplicación**|<p>**Como cliente**</p><p>**Quiero realizar ajustes y preferencias de aplicación**</p><p>**Para tener una experiencia personalizada en la aplicación**</p>|<p>**Escenario 1: El cliente quiere visualizar ajustes de la aplicación**</p><p>**Dado que el cliente quiere visualizar los ajustes de la aplicación.**</p><p>**Cuando el cliente accede a la sección de “Ajustes de la aplicación”.**</p><p>**Entonces el cliente debe poder ver una lista de ajustes disponibles.**</p><p>**Y cada ajuste debe tener una descripción**</p><p>**Escenario 2: El cliente quiere realizar ajustes en la aplicación**</p><p>**Dado que el cliente está en la pantalla de inicio.**</p><p>**Cuando el cliente accede a la sección de ajustes de la aplicación.**</p><p>**Y el cliente selecciona un ajuste para poder modificarlo.**</p><p>**Y el cliente debe poder guardar los cambios realizados en los ajustes.**</p><p>**Entonces el cliente debe poder guardar los cambios realizados.**</p>|**1**|
|**E3-US04**|**Recibir notificaciones**|<p>**Como cliente**</p><p>**Quiero recibir notificaciones relevantes**</p><p>**Para estar informado sobre las novedades en la aplicación**</p>|<p>**Escenario 1: Activar notificaciones en la aplicación**</p><p>**Dado que el cliente está en la pantalla de inicio.**</p><p>**Cuando el cliente accede a la sección de “Ajustes de la aplicación”.**</p><p>**Y el cliente busca la opción para activar las notificaciones.**</p><p>**Entonces el cliente podrá activar la opción “Recibir notificaciones”**</p><p></p><p>**Escenario 2: El cliente quiere desactivar las notificaciones en la aplicación**</p><p>**Dado se encuentra en la pantalla de inicio.**</p><p>**Cuando el cliente accede a la sección “Ajustes de la aplicación”.**</p><p>**Y el cliente busca la opción para desactivar las notificaciones**</p><p>**Entonces el cliente podrá desactivar la opción “Recibir notificaciones”.**</p>|**2**|
|**E3-U05**|**Pasarela de pagos**|<p>**Como cliente Quiero observar una lista de los productos que  seleccioné con el total a pagar**</p><p>**Para poder realizar el pago total de mi pedido**</p>|<p>**Escenario 1: Visualización de productos y total a pagar**</p><p></p><p>**Dado que el cliente ha seleccionado los productos que desea comprar,**</p><p>**Cuando accede a la página de pago,**</p><p>**Entonces se le muestra una lista detallada de los productos seleccionados junto con su precio unitario y la cantidad elegida, así como el total a pagar por todos los productos.<br>Escenario 2: Proceso de Pago Exitoso**</p><p></p><p>**Dado que el cliente ha revisado la lista de productos y el total a pagar,**</p><p>**Cuando procede a ingresar los detalles de su tarjeta de crédito y otra información requerida,**</p><p>**Entonces el sistema valida la información ingresada y procesa el pago de manera exitosa,**</p><p>**Y el cliente recibe una confirmación de que el pago se ha realizado correctamente, junto con un recibo electrónico que incluye los detalles de la transacción.**</p><p>**Escenario 3: Pago Fallido por Tarjeta Rechazada**</p><p></p><p>**Dado que el cliente ha ingresado los detalles de su tarjeta de crédito y otra información requerida,**</p><p>**Cuando procede a realizar el pago,**</p><p>**Pero la transacción es rechazada debido a que la tarjeta de crédito está vencida o los fondos son insuficientes,**</p><p>**Entonces el sistema muestra un mensaje de error indicando la causa del rechazo,**</p><p>**Y ofrece al cliente la opción de intentar nuevamente con otra tarjeta u otro método de pago.**</p>||
|**E3-U06**|**Visualización de Productos** |<p>**Como cliente interesado en explorar nuevas opciones de compra**</p><p>**Quiero para poder ver los productos más recientes disponibles en la plataforma, Para aumentar mis posibilidades de personalización y elección**</p>|<p>**Escenario 1: Visualización de Todos los Productos**</p><p>**Dado que un cliente está navegando por la página principal,**</p><p>**Cuando ve la sección de "Productos Más Recientes",**</p><p>**Entonces puede hacer clic en el botón "Ordenar" para acceder a opciones de filtrado y ordenación de los productos.**</p><p></p><p>**Escenario 2: Agregar Producto a Favoritos**</p><p>**Dado que un cliente está explorando los productos más recientes,**</p><p>**Cuando encuentra un producto que le interesa,**</p><p>**Entonces puede hacer clic en el botón "Agregar a Favoritos" para guardar el producto en su lista de favoritos.**</p><p></p><p>**Escenario 3: Detalles del Producto y Proceso de Compra**</p><p>**Dado que un cliente ha encontrado un producto deseado en la sección de "Productos Más Recientes",**</p><p>**Cuando hace clic en el producto para ver más detalles,**</p><p>**Entonces es redirigido a una sección de la plataforma donde puede iniciar el proceso de compra y realizar el pago.**</p><p></p>||
|<p>**Epic 4: Control de usuario**</p><p></p><p></p><p>**Como** cliente</p><p>**Quiero** crear, configurar o editar</p><p>**Para** realizar mejores procesos en la aplicación</p>|||||
|**E4-US01**|**Afiliar tarjeta para pagos**|<p>**Como cliente**</p><p></p><p>**Quiero afiliar una tarjeta en la aplicación**</p><p></p><p>**Para poder pagar la personalización del auto**</p>|<p>**Escenario 1: El usuario afilia una tarjeta válida a su cuenta**</p><p></p><p>**Dado que el cliente cuenta con una cuenta en la aplicación Y está en la sección de afiliar una tarjeta,**</p><p>**Y rellene los formularios con sus datos**</p><p>**Cuando haga clic en el botón de afiliar,**</p><p>**Entonces el sistema le mostrará un mensaje “afiliación exitosa”.**</p><p></p><p>**Escenario 2: El cliente trata de afiliar una tarjeta no válida**</p><p></p><p>**Dado que el cliente se encuentra en la sección de afiliar tarjeta**</p><p>**Y llena todos los datos, pero con una tarjeta inválida,**</p><p>**Cuando presione el botón de afiliar,**</p><p>**Entonces el sistema le mostrará un mensaje indicando que “los datos de la tarjeta son erróneos”.**</p><p></p><p>**Escenario 3: El cliente no rellena de forma adecuada o deja en blanco algunos datos requeridos**</p><p>**Dado que el cliente se encuentre en la sección de afiliar tarjeta**</p><p>**Y no rellena de forma adecuada o deja casilleros en blanco, Cuando oprima el botón de afiliar,**</p><p>**Entonces el sistema le devolverá el mensaje “debe rellenar los datos adecuadamente**</p><p>**Y no dejar casilleros en blanco”.**</p>|**1**|
|**E4-US02**|**Eliminar datos de la cuenta**|<p>**Como cliente**</p><p></p><p>**Quiero eliminar mis datos de la cuenta**</p><p></p><p>**Para cuando decida retirarme permanentemente de la aplicación**</p>|<p>**Escenario 1: Usuario quiere eliminar datos de su cuenta**</p><p></p><p>**Dado que el cliente se encuentra dentro de la aplicación**</p><p>**Y esté seleccione el menú de la barra de navegación,**</p><p>**Cuando presione la opción “Settings”**</p><p>**Y se dirige a dicho apartado**</p><p>**a la vez que se presiona la opción de eliminar datos**</p><p>**Entonces le pedirá “confirmar” para eliminar permanentemente sus datos de la aplicación**</p>|**1**|
|<p>**Epic 5: Preferencias en la aplicación**</p><p></p><p>**Como cliente** </p><p>` `**Quiero visualizar una página**</p><p>**Para saber acerca de las preferencias del cliente**</p>|||||
|**E5-US01**|**Preferencia de idioma**|<p>**Como cliente**</p><p>**Quiero configurar preferencias de idioma**</p><p>**Para utilizar la aplicación según mi preferencia de idioma**</p><p></p>|<p>**Escenario 1: Modo predeterminado de idioma    Dado que el usuario no haya realizado cambios en la preferencia de idioma,       Cuando ingrese a la aplicación, Entonces el idioma predeterminado es inglés**</p><p>**Escenario 2: Cambio de idioma en la aplicación**</p><p>**Dado que el usuario se encuentre en sección de configuración de idioma,                                Cuando seleccione un idioma, Entonces el idioma de la aplicación se cambiará al idioma seleccionado**</p>|**1**|
|**E5-US02**|**Preferencia de tema oscuro**|<p>**Como cliente**</p><p></p><p>**Quiero cambiar el tipo de tema claro a oscuro**</p><p></p><p>**Para utilizar la aplicación de acuerdo con mi preferencia**</p><p></p>|<p>**Escenario 1: Modo predeterminado del tema de la aplicación**</p><p>**Dado que el usuario no haya realizado cambios en la preferencia de temas,**</p><p>**Cuando ingrese a la aplicación,**</p><p>**Entonces el tema predeterminado es el modo claro.**</p><p></p><p>**Escenario 2: Cambio de tema en la aplicación**</p><p>**Dado que el usuario se encuentre en sección de configuración de tema,**</p><p>**Cuando seleccione un tema,**</p><p>**Entonces el tema de la aplicación se cambiará al modo seleccionado.**</p>|**1**|
|<p>**Epic 6: Backend API**</p><p></p><p>**Como** desarrollador</p><p>` `**Quiero** utilizar la API de un servicio backend</p><p>**Para** que el usuario pueda usar la aplicación</p>|||||
|**E6-US01**|Registro de usuario |<p>**Como** desarrollador </p><p>**Quiero** realizar el proceso de registro de los datos de los usuarios a  través del backend</p><p>**Para** que los clientes pueden autenticarse en la aplicación </p><p></p>|<p>**Escenario 1: Guardar data de un usuario**</p><p>**Dado que** el desarrollador  quiere guardar la data</p><p>**Cuando** utilice el método POST en el endpoint “/login” </p><p>**Entonces** la api responderá con un código 201 </p><p>**Y** se** guardará los datos del nuevo cliente en la base de datos</p><p></p><p>**Escenario 2: Guardar data de un usuario existente**</p><p>**Dado que** el desarrollador  quiere guardar la data de un usuario que ya existe</p><p>**Cuando** utilice el método POST en el endpoint “/login” </p><p>**Entonces** la api responderá con un código 400 </p><p>**Y** se **NO** guardará los datos del nuevo cliente en la base de datos</p><p></p><p>**Escenario 3: Actualizar data de un usuario por su id**</p><p>**Dado que** el desarrollador  quiere actualizar la data de un usuario en específico</p><p>**Cuando** utilice el método POST en el endpoint “/data/user:id” </p><p>**Entonces** la api responderá con un código 201 </p><p>**Y** se** actualizará los datos del nuevo cliente en la base de datos</p><p></p><p>**Escenario 4: Actualizar data de un usuario inexistente por su id**</p><p>**Dado que** el desarrollador  quiere actualizar la data de un usuario en específico inexistente</p><p>**Cuando** utilice el método POST en el endpoint “/data/user:id” </p><p>**Entonces** la api responderá con un código 400 </p><p>**Y** se **NO se** actualizará nada</p><p></p><p></p><p>**Escenario 4: Validar data de un usuario** </p><p>**Dado que** el desarrollador  quiere validar la data de un usuario para que pueda acceder a la aplicación</p><p>**Cuando** utilice el método GET en el endpoint “/user:id” </p><p>**Entonces** la api responderá con un código 201 </p><p>**Y** se** obtendrá todos los datos de todos los clientes para poder proceder con las validaciones necesarias</p>|**2**|
|**E6-US02**|Traer toda la data de las modificaciones que ofreceremos a los clientes|<p>**Como** desarrollador </p><p>**Quiero** obtener toda la data de las modificaciones que ofreceremos a los clientes a  través del backend</p><p>**Para** que los clientes puedan visualizarlas</p><p> </p><p></p><p></p>|<p>**Escenario 1: Obtener todas las modificaciones**</p><p></p><p>**Dado que** el desarrollador  quiere visualizar la lista de modificaciones disponibles</p><p>**Cuando** utilice el método GET en el endpoint “/modifications” </p><p>**Entonces** la api responderá con un código 201 </p><p>**Y** se** obtendrá todas las modificaciones disponibles</p><p></p><p>**Escenario 2: Obtener una modificación mediante su id**</p><p>**Dado que** el desarrollador  quiere visualizar una modificación disponible</p><p>**Cuando** utilice el método GET en el endpoint “/modification:id” </p><p>**Entonces** la api responderá con un código 201 </p><p>**Y** se** obtendrá la modificación en específico</p><p></p><p>**Escenario 3: Obtener una modificación inexistente mediante su id**</p><p>**Dado que** el desarrollador  quiere visualizar una modificación inexistente </p><p>**Cuando** utilice el método GET en el endpoint “/modification:id” </p><p>**Entonces** la api responderá con un código 400</p><p>Y **NO** se mostrará nada</p>|**2**|
|**E6-US03**|Traer toda la data de las órdenes para los miembros staff|<p>**Como** desarrollador </p><p>**Quiero** obtener toda la data de todas las órdenes a  través del backend</p><p>**Para** que los usuarios de tipo staff puedan visualizarlas</p>|<p>**Escenario 1: Obtener todas las órdenes**</p><p>**Dado que** el desarrollador  quiere visualizar la lista de órdenes disponibles</p><p>**Cuando** utilice el método GET en el endpoint “/orders” </p><p>**Entonces** la api responderá con un código 201 </p><p>**Y** se** obtendrá todas las órdenes disponibles</p><p></p><p>**Escenario 2: Obtener una orden mediante su id**</p><p>**Dado que** el desarrollador  quiere visualizar una orden disponible</p><p>**Cuando** utilice el método GET en el endpoint “/order:id” </p><p>**Entonces** la api responderá con un código 201 </p><p>**Y** se** obtendrá la orden en específico</p><p></p><p>**Escenario 3: Obtener una orden inexistente mediante su id**</p><p>**Dado que** el desarrollador  quiere visualizar una orden inexistente </p><p>**Cuando** utilice el método GET en el endpoint “/orden:id” </p><p>**Entonces** la api responderá con un código 400</p><p>Y **NO** se mostrará nada</p>|**2**|

# 3.3. Impact Mapping
En la presente sección se elaboró el impact mapping partiendo desde las metas de negocio para cada user persona, los impactos, entregables y unirlos a las historias de usuario adecuadas.

   **Segmento Objetivo: Cliente**

   <https://uxpressia.com/w/DeRZM/i/cXXoH> 

   ![ref1]







   ![ref2]

   **Segmento Objetivo: Staff de taller mecánico**

   <https://uxpressia.com/w/DeRZM/i/3kJuF> 

   ![ref3]

![ref4]

# 3.4. Product Backlog 

![](Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.009.png)

**Link del trello: [https://trello.com/invite/b/c7wBt54Y/ATTI10dc05b4716e2b5ca0de129e90564f0eCE69B89C/product-backlog**](https://trello.com/invite/b/c7wBt54Y/ATTI10dc05b4716e2b5ca0de129e90564f0eCE69B89C/product-backlog)**


|**#Orden**|**User Story Id**|**Título**|**Description**|**Story Points (1/2/3/5/8)** |
| :-: | :-: | :-: | :-: | :-: |
|**1**|**E1-US01**|**Barra de navegación en la landing page**|<p>**Como cliente o staff mecanico**</p><p>**Quiero una barra de navegación en la landing page**</p><p>**Para tener acceso directo a la aplicación**</p>|**1**|
|**2**|**E1-US02**|**Dirigirse a la aplicación mediante el landing page**|<p>**Como cliente o staff mecanico**</p><p>**Quiero dirigirme a la aplicación mediante el botón “Open app”**</p><p>**Para poder usarla.**</p>|**1**|
|**3**|**E1-US03**|**Sección hero del landing page**|<p>**Como cliente o staff mecanico**</p><p>**Quiero observar la sección hero de la landing**</p><p>**Para poder tener información de lo que es y ofrece la aplicación.**</p>|**1**|
|**4**|**E1-US04**|**Versión en español de landing page**|<p>**Como cliente y staff mecanico**</p><p>**Quiero tener al alcance una versión en español del landing page**</p><p>**Para tener accesibilidad en cuanto a opciones de idioma**</p><p></p>|**1**|
|**5**|**E2-US01**|**Registro de cuentas**|<p>**Como cliente o miembro del staff**</p><p>**Quiero poder registrar una cuenta**</p><p>**Para acceder a los servicios que ofrece**</p>|**1**|
|**6**|**E2-US02**|**Inicio de sesión**|<p>**Como cliente o integrante del staff mecánico**</p><p>**Quiero iniciar sesión en mi cuenta**</p><p>**Para acceder a las funciones de la aplicación**</p>|**1**|
|**7**|**E2-US03**|**Recuperación de contraseña**|<p>**Como cliente o integrante del staff mecánico**</p><p>**Quiero recuperar la contraseña de mi cuenta**</p><p>**Para poder iniciar sesión**</p>|**1**|
|**8**|**E2-US04**|**Cerrar sesión**|<p>**Como cliente o integrante del staff mecánico**</p><p>**Quiero cerrar mi sesión**</p><p>**Para no dejar mi sesión abierta en un dispositivo**</p>|**1**|
|**9**|**E3-US01**|**Barra de navegación**|<p>**Como cliente**</p><p>**Quiero visualizar un sidebar con links de navegación**</p><p>**Para navegar por la aplicación**</p>|**1**|
|**10**|**E3-US02**|**Configuración de perfil**|<p>**Como cliente**</p><p>**Quiero configurar mi perfil**</p><p>**Para visualizar o modificar mis datos**</p>|**1**|
|**11**|**E3-US03**|**Ajustes de aplicación**|<p>**Como cliente**</p><p>**Quiero realizar ajustes y preferencias de aplicación**</p><p>**Para tener una experiencia personalizada en la aplicación**</p>|**1**|
|**12**|**E3-US04**|**Recibir notificaciones**|<p>**Como cliente**</p><p>**Quiero recibir notificaciones relevantes**</p><p>**Para estar informado sobre las novedades en la aplicación**</p>|**2**|
|**13**|**E3-US05**||||
|**14**|**E3-US06**|**Visualización de productos**|<p>**Como cliente interesado en explorar nuevas opciones de compra**</p><p>**Quiero para poder ver los productos más recientes disponibles en la plataforma, Para aumentar mis posibilidades de personalización y elección**</p>|**2**|
|**15**|**E4-US01**|**Afiliar tarjeta para pagos**|<p>**Como cliente**</p><p>**Quiero afiliar una tarjeta en la aplicación**</p><p>**Para poder pagar la personalización del auto**</p>|**1**|
|**16**|**E4-US02**|**Eliminar datos de la cuenta**|<p>**Como cliente**</p><p></p><p>**Quiero eliminar mis datos de la cuenta**</p><p></p><p>**Para cuando decida retirarme permanentemente de la aplicación**</p>|**1**|
|**17**|**E5-US01**|**Preferencia de idioma**|<p>**Como cliente**</p><p>**Quiero configurar preferencias de idioma**</p><p>**Para utilizar la aplicación según mi preferencia de idioma**</p><p></p>|**1**|
|**18**|**E5-US02**|**Preferencia de tema oscuro**|<p>**Como cliente**</p><p></p><p>**Quiero cambiar el tipo de tema claro a oscuro**</p><p></p><p>**Para utilizar la aplicación de acuerdo con mi preferencia**</p><p></p>|**1**|
|**19**|**E6-US01**|**Registro de usuario** |<p>**Como desarrollador** </p><p>**Quiero realizar el proceso de registro de los datos de los usuarios a  través del backend**</p><p>**Para que los clientes pueden autenticarse en la aplicación** </p><p></p>|**2**|
|**20**|**E6-US02**|**Traer toda la data de las modificaciones que ofreceremos a los clientes**|<p>**Como desarrollador** </p><p>**Quiero obtener toda la data de las modificaciones que ofreceremos a los clientes a través del backend**</p><p>**Para que los clientes puedan visualizarlas**</p>|**2**|
|**21**|**E6-US03**|**Traer toda la data de las órdenes para los miembros staff**|<p>**Como desarrollador** </p><p>**Quiero obtener toda la data de todas las órdenes a través del backend**</p><p>**Para que los usuarios de tipo staff puedan visualizarlas**</p>|**2**|

[ref1]: Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.005.png
[ref2]: Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.006.png
[ref3]: Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.007.png
[ref4]: Aspose.Words.bab3cc99-ea87-4418-83f8-f9cdae5788a5.008.png