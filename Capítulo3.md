
<h1>CAPÍTULO III: REQUIREMENTS SPECIFICATION</h1>
<h2>3.1 To-Be Scenario Mapping</h2>
<img src="/imagenes/tobe.png"/>
<h2>3.2 User Stories</h2>
<table>
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP01</td>
      <td>Autenticación de usuario</td>
      <td>Como usuario Quiero registrarme e iniciar sesión Para acceder a la aplicación MyEvent</td>
      <td>El usuario puede registrar una cuenta nueva con su información personal.
          El usuario puede iniciar sesión con su nombre de usuario y contraseña.
          El usuario recibirá un mensaje de error si el inicio de sesión falla.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>EP02</td>
      <td>Creación de eventos</td>
      <td>Como organizador de eventos Quiero poder crear y publicar eventos en la plataforma Para promover mi evento y vender entradas</td>
      <td>El organizador puede completar un formulario con detalles del evento.
          El organizador puede enviar el evento para su revisión y aprobación.
          El evento se muestra en la plataforma una vez aprobado por el administrador.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>EP03</td>
      <td>Exploración de eventos</td>
      <td>Como usuario interesado en eventos Quiero poder buscar y filtrar eventos disponibles Para encontrar eventos que me interesen</td>
      <td>El usuario puede navegar por una lista de eventos.
          El usuario puede aplicar filtros por categorías como género musical, ubicación y fecha.
          El usuario puede ver detalles de eventos individuales haciendo clic en ellos.</td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>EP04</td>
      <td>Compra de entradas</td>
      <td>Como comprador de entradas Quiero poder seleccionar y comprar entradas Para asegurar mi participación en eventos</td>
      <td>El usuario puede seleccionar las entradas deseadas y agregarlas al carrito.
          El usuario puede completar el proceso de pago utilizando diferentes métodos de pago.
          El usuario recibe confirmación de la compra por correo electrónico.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>EP05</td>
      <td>Opción Premium para Revendedores</td>
      <td>Como revendedor Quiero tener una opción premium Para obtener ventajas sobre otros compradores</td>
      <td>El revendedor puede comprar una membresía premium con acceso anticipado y límites de compra más altos.
          El revendedor puede acceder a la opción premium desde su cuenta.
          El revendedor recibe beneficios adicionales al adquirir la membresía premium.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>EP06</td>
      <td>Transferencia de Entradas</td>
      <td>Como usuario que ya ha comprado entradas Quiero poder transferirlas a otros usuarios Para permitir que otros disfruten del evento</td>
      <td>El usuario puede seleccionar las entradas que desea transferir.
          El usuario puede proporcionar la información de contacto del destinatario.
          El usuario recibe confirmación de la transferencia exitosa.</td>
      <td>EP06</td>
    </tr>
    <tr>
      <td>EP07</td>
      <td>Membresía de Descuentos Periódicos</td>
      <td>Como usuario fiel a la plataforma Quiero recibir descuentos especiales periódicamente Para incentivar mi participación continua</td>
      <td>El usuario puede adquirir una membresía que le otorgue descuentos periódicos en eventos seleccionados.
          El usuario recibe notificaciones sobre los descuentos disponibles.
          El usuario puede aplicar los descuentos durante el proceso de compra.</td>
      <td>EP07</td>
    </tr>
        <tr>
      <td>EP08</td>
      <td>Membresía de Concursos y Sorteos Exclusivos</td>
      <td>Como miembro de la plataforma, quiero participar en concursos y sorteos exclusivos para ganar entradas gratuitas y experiencias VIP, para disfrutar de beneficios adicionales y experiencias únicas.</td>
      <td>El usuario puede acceder a concursos y sorteos exclusivos desde su cuenta.
          El usuario puede participar en los concursos y sorteos siguiendo las instrucciones proporcionadas.
          El usuario recibe notificaciones sobre los resultados de los concursos y sorteos.</td>
      <td>EP08</td>
    </tr>
    <tr>
      <td>EP09</td>
      <td>Membresía de Contenido Exclusivo</td>
      <td>Como suscriptor premium, quiero tener acceso a contenido exclusivo relacionado con eventos, como transmisiones en vivo y entrevistas detrás de escena, para disfrutar de una experiencia más completa y enriquecedora.</td>
      <td>El usuario puede acceder a contenido exclusivo desde su cuenta premium.
          El usuario puede ver transmisiones en vivo y contenido especial disponible solo para suscriptores premium.
          El usuario puede comentar y compartir el contenido exclusivo con otros usuarios.</td>
      <td>EP09</td>
    </tr>
    <tr>
      <td>EP10</td>
      <td>Membresía de Prioridad en Servicio al Cliente</td>
      <td>Como usuario premium, quiero recibir atención prioritaria en el servicio al cliente, con tiempos de respuesta más rápidos y asistencia personalizada, para sentirme valorado y apoyado como cliente leal.  </td>
      <td>El usuario premium puede acceder a un servicio al cliente dedicado desde su cuenta.
          El usuario premium recibe respuestas más rápidas a sus consultas y solicitudes de soporte.
          El usuario premium puede comunicarse con el servicio al cliente a través de canales exclusivos, como líneas telefónicas o correos electrónicos dedicados.</td>
      <td>EP10</td>
<tr>
  <td>EP11</td>
  <td>Membresía de Descuentos en Futuras Compras</td>
  <td>Como usuario habitual de la plataforma, quiero recibir descuentos para futuras compras de entradas Para incentivar mi lealtad y continuar utilizando el servicio</td>
  <td>El usuario acumula descuentos después de comprar un número determinado de entradas.
      El usuario recibe un cupón de descuento para su próxima compra después de alcanzar el umbral establecido.
      El usuario puede aplicar el cupón durante el proceso de compra.</td>
  <td>EP11</td>
</tr>
<tr>
  <td>EP12</td>
  <td>Entradas Gratis para Eventos Seleccionados</td>
  <td>Como usuario frecuente de la plataforma, quiero tener la oportunidad de obtener entradas gratuitas Para disfrutar de eventos sin costo adicional y fomentar mi fidelidad</td>
  <td>El usuario acumula entradas gratuitas después de comprar un cierto número de entradas.
      El usuario puede canjear una entrada gratuita para un evento específico de su elección.
      El usuario puede seleccionar la entrada gratuita durante el proceso de compra.</td>
  <td>EP12</td>
</tr>
<tr>
  <td>EP13</td>
  <td>Acceso a Preventas Exclusivas</td>
  <td>Como usuario frecuente de la plataforma, quiero tener acceso exclusivo a preventas de eventos populares Para asegurar mi participación en eventos de alto demanda</td>
  <td>El usuario acumula acceso a preventas exclusivas después de comprar un número determinado de entradas.
      El usuario puede comprar entradas antes de que estén disponibles para el público en general.
      El usuario puede asegurar su participación en eventos populares durante la preventa.</td>
  <td>EP13</td>
</tr>
<tr>
  <td>EP14</td>
  <td>Puntos de Fidelidad o Programa de Recompensas</td>
  <td>Como usuario frecuente de la plataforma, quiero acumular puntos de fidelidad por cada compra de entradas Para canjearlos por descuentos, entradas gratuitas u otros beneficios</td>
  <td>El usuario acumula puntos de fidelidad por cada compra de entradas.
      El usuario puede canjear los puntos por recompensas como descuentos, entradas gratis o productos exclusivos.
      El usuario puede verificar su saldo de puntos y las opciones de canje desde su cuenta.</td>
  <td>EP14</td>
</tr>
<tr>
  <td>EP15</td>
  <td>Niveles de Entrada con Descuento</td>
  <td>Como usuario frecuente de la plataforma, quiero acceder a precios especiales de entrada después de realizar cierto número de compras Para disfrutar de beneficios adicionales y promociones exclusivas</td>
  <td>El usuario alcanza niveles de entrada con descuento después de comprar un número determinado de entradas.
      El usuario puede acceder a precios especiales para ciertos niveles de entrada.
      El usuario puede seleccionar el nivel de entrada con descuento durante el proceso de compra.</td>
  <td>EP15</td>
</tr>
<tr>
  <td>EP16</td>
  <td>Notificaciones de Eventos y Ofertas</td>
  <td>Como usuario de la plataforma, quiero recibir notificaciones sobre eventos nuevos y ofertas especiales Para estar al tanto de las últimas novedades y oportunidades</td>
  <td>El usuario puede optar por recibir notificaciones por correo electrónico o mensajes push en la aplicación.
      El usuario puede configurar sus preferencias de notificación desde la cuenta.
      El usuario recibe información actualizada sobre eventos nuevos, descuentos y promociones.</td>
  <td>EP16</td>
</tr>
<tr>
  <td>EP17</td>
  <td>Integración con Redes Sociales</td>
  <td>Como usuario de la plataforma, quiero poder compartir eventos y experiencias en mis redes sociales Para ampliar el alcance de la plataforma y compartir intereses con amigos</td>
  <td>El usuario puede conectar su cuenta de la plataforma con redes sociales como Facebook, Twitter o Instagram.
      El usuario puede compartir detalles de eventos, compras de entradas y experiencias directamente desde la plataforma.
      Los amigos y seguidores del usuario pueden ver y participar en eventos compartidos.</td>
  <td>EP17</td>
</tr>
<tr>
  <td>EP18</td>
  <td>Soporte Multilingüe</td>
  <td>Como usuario de la plataforma, quiero poder acceder a la aplicación en varios idiomas Para facilitar la navegación y comprensión del contenido</td>
  <td>El usuario puede seleccionar su idioma preferido desde la configuración de la cuenta.
      La aplicación se traduce automáticamente al idioma seleccionado por el usuario.
      Todos los textos, botones y mensajes de la aplicación están disponibles en el idioma elegido.</td>
  <td>EP18</td>
</tr>
<tr>
  <td>EP19</td>
  <td>Integración con Mapas y Direcciones</td>
  <td>Como usuario de la plataforma, quiero tener acceso a información de ubicación y direcciones de eventos Para facilitar la planificación y asistencia a los mismos</td>
  <td>El usuario puede ver la ubicación del evento en un mapa interactivo.
      El usuario puede obtener direcciones y rutas recomendadas hacia el lugar del evento.
      La aplicación muestra información detallada sobre la ubicación, incluyendo transporte público cercano y estacionamientos.</td>
  <td>EP19</td>
</tr>
<tr>
  <td>EP20</td>
  <td>Calificación y Reseñas de Eventos</td>
  <td>Como usuario de la plataforma, quiero poder calificar y dejar reseñas sobre eventos a los que asistí Para compartir experiencias y ayudar a otros usuarios en su decisión de compra</td>
  <td>El usuario puede calificar eventos utilizando una escala de estrellas.
      El usuario puede escribir reseñas detalladas sobre su experiencia en el evento.
      Las calificaciones y reseñas están visibles para otros usuarios interesados en el evento.</td>
  <td>EP20</td>
</tr>
<tr>
  <td>EP21</td>
  <td>Asistencia en Vivo y Chat en Línea</td>
  <td>Como usuario de la plataforma, quiero tener acceso a asistencia en vivo y chat en línea Para resolver consultas rápidamente y recibir ayuda durante la navegación</td>
  <td>El usuario puede acceder a un servicio de chat en vivo desde la aplicación.
      El usuario puede recibir respuestas rápidas a preguntas sobre eventos, compras de entradas y problemas técnicos.
      La asistencia en vivo está disponible durante horas específicas y es accesible desde cualquier página de la aplicación.</td>
  <td>EP21</td>
</tr>
<tr>
  <td>EP22</td>
  <td>Estadísticas y Análisis de Participación</td>
  <td>Como organizador de eventos, quiero acceder a estadísticas y análisis detallados sobre la participación en mis eventos Para evaluar su éxito y mejorar la planificación futura</td>
  <td>El organizador puede ver datos de participación, incluyendo número de entradas vendidas y perfiles de compradores.
      El organizador puede acceder a informes analíticos sobre la satisfacción de los asistentes y la efectividad de las estrategias de marketing.
      Las estadísticas están disponibles en tiempo real y se presentan de manera clara y comprensible.</td>
  <td>EP22</td>
</tr>
<tr>
  <td>EP23</td>
  <td>Integración con Plataformas de Streaming</td>
  <td>Como usuario de la plataforma, quiero tener acceso a transmisiones en vivo y contenido exclusivo de eventos Para disfrutar de experiencias virtuales y ampliar mi participación en eventos</td>
  <td>El usuario puede acceder a transmisiones en vivo de eventos a través de la plataforma.
      El usuario puede ver contenido exclusivo relacionado con eventos como entrevistas, sesiones acústicas y contenido detrás de escena.
      La plataforma integra servicios de streaming populares para ofrecer una experiencia inmersiva a los usuarios.</td>
  <td>EP23</td>
</tr>
<tr>
  <td>EP24</td>
  <td>Verificación de Identidad para Revendedores</td>
  <td>Como revendedor de entradas, quiero completar un proceso de verificación de identidad Para garantizar la legitimidad de mis transacciones y proteger la integridad de la plataforma</td>
  <td>El revendedor proporciona información de identificación oficial, como documento de identidad o pasaporte.
      La plataforma verifica la identidad del revendedor antes de habilitar funciones avanzadas como la compra anticipada y límites de compra más altos.
      La verificación de identidad se realiza de manera segura y confidencial, cumpliendo con las regulaciones de protección de datos.</td>
  <td>EP24</td>
</tr>
<tr>
  <td>EP25</td>
  <td>Integración con Plataformas de Pago Internacionales</td>
  <td>Como usuario internacional de la plataforma, quiero poder utilizar diferentes métodos de pago Para facilitar la compra de entradas desde cualquier parte del mundo</td>
  <td>El usuario puede seleccionar su método de pago preferido entre una variedad de opciones internacionales.
      La plataforma integra pasarelas de pago seguras y confiables que admiten tarjetas de crédito, transferencias bancarias y monederos electrónicos.
      Los pagos se procesan en la moneda local del usuario, simplificando las transacciones internacionales.</td>
  <td>EP25</td>
</tr>
<tr>
  <td>EP26</td>
  <td>Reserva de Entradas</td>
  <td>Como usuario de la plataforma, quiero tener la opción de reservar entradas para eventos populares Para garantizar mi participación antes de la venta general</td>
  <td>El usuario puede realizar una reserva para asegurar entradas antes de que estén disponibles para la venta general.
      La reserva se confirma mediante un pago inicial que se deduce del precio total de las entradas.
      El usuario recibe instrucciones claras sobre el proceso de reserva y los plazos de pago.</td>
  <td>EP26</td>
</tr>
<tr>
  <td>EP27</td>
  <td>Reembolso y Política de Devoluciones</td>
  <td>Como usuario de la plataforma, quiero conocer la política de reembolso y devoluciones Para tomar decisiones informadas sobre mis compras de entradas</td>
  <td>La plataforma proporciona información clara sobre las condiciones de reembolso y devoluciones.
      El usuario puede solicitar un reembolso dentro de ciertos plazos y bajo ciertas condiciones especificadas.
      La política de reembolso y devoluciones se comunica de manera transparente para garantizar la satisfacción del cliente.</td>
  <td>EP27</td>
</tr>

</tr>
  </tbody>
</table>


<h2>3.3 Impact Mapping</h2>
  <img src="./imagenes/impactMapping/Impact Mapping.jpg"/>


<h2>3.4 Product Backlog</h2>
<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>EP01</td>
      <td>Autenticación de usuario</td>
      <td>Como usuario quiero registrarme e iniciar sesión Para acceder a MyEvent</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>EP02</td>
      <td>Creación de eventos</td>
      <td>Como organizador de eventos Quiero poder crear y publicar eventos en la plataforma Para promover mi evento y vender entradas</td>
      <td>5</td>
    </tr>
    <tr>
      <td>3</td>
      <td>EP03</td>
      <td>Exploración de eventos</td>
      <td>Como usuario interesado en eventos Quiero poder buscar y filtrar eventos disponibles Para encontrar eventos que me interesen</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>EP04</td>
      <td>Compra de entradas</td>
      <td>Como comprador de entradas Quiero poder seleccionar y comprar entradas Para asegurar mi participación en eventos</td>
      <td>8</td>
    </tr>
    <tr>
      <td>5</td>
      <td>EP05</td>
      <td>Opción Premium para Revendedores</td>
      <td>Como revendedor Quiero tener una opción premium Para obtener ventajas sobre otros compradores</td>
      <td>5</td>
    </tr>
    <tr>
      <td>6</td>
      <td>EP06</td>
      <td>Transferencia de Entradas</td>
      <td>Como usuario que ya ha comprado entradas Quiero poder transferirlas a otros usuarios Para permitir que otros disfruten del evento</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>EP07</td>
      <td>Membresía de Descuentos Periódicos</td>
      <td>Como usuario fiel a la plataforma Quiero recibir descuentos especiales periódicamente Para incentivar mi participación continua</td>
      <td>2</td>
    </tr>
    <tr>
      <td>8</td>
      <td>EP08</td>
      <td>Membresía de Concursos y Sorteos Exclusivos</td>
      <td>Como miembro de la plataforma, quiero participar en concursos y sorteos exclusivos para ganar entradas gratuitas y experiencias VIP, para disfrutar de beneficios adicionales y experiencias únicas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>EP09</td>
      <td>Membresía de Contenido Exclusivo</td>
      <td>Como suscriptor premium, quiero tener acceso a contenido exclusivo relacionado con eventos, como transmisiones en vivo y entrevistas detrás de escena, para disfrutar de una experiencia más completa y enriquecedora.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>10</td>
      <td>EP10</td>
      <td>Membresía de Prioridad en Servicio al Cliente</td>
      <td>Como usuario premium, quiero recibir atención prioritaria en el servicio al cliente, con tiempos de respuesta más rápidos y asistencia personalizada, para sentirme valorado y apoyado como cliente leal.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

    
<h1>CAPÍTULO IV: PRODUCT UX/UI DESIGN</h1>
<h2>4.1 Style Guidelines</h2>
<h3>4.1.1 General Style Guidelines</h3>
<h3>4.1.2 Web Style Guidelines</h3>

<h2>4.2 Information Architecture</h2>
<h3>4.2.1 Organization Systems</h3>
<p class="justificado">En este apartado, nuestro equipo ha optado por implementar un enfoque basado en la jerarquía visual. Creemos firmemente que esta estructura organizativa proporcionará una experiencia más intuitiva y eficiente para nuestros usuarios, al tiempo que les permitirá interactuar de manera más fluida con nuestra aplicación.</p>
<img src="./imagenes/organizationSystems/Organization Systems.jpg"/>

<h3>4.2.2 Labeling Systems</h3>
<p class="justificado">Para el diseño de nuestra página web, hemos implementado un sistema de etiquetado uniforme con el objetivo de facilitar la navegación de los usuarios por nuestra plataforma. Este sistema se compone de etiquetas específicas que tienen funciones definidas para mejorar la experiencia del usuario. A continuación, se detallan las etiquetas utilizadas:</p>
<img src="./imagenes/labelingSystems/1.png"/>
<ul>
  <li><strong>Inicio:</strong> Dirige a la página de inicio.</li>
  <li><strong>MyEvent:</strong> Acceso al área de eventos disponibles.</li>
  <li><strong>Nosotros:</strong> Información sobre nuestra empresa.</li>
  <li><strong>Contáctanos:</strong> Canal para comunicarse con nuestro equipo de soporte.</li>
</ul>
<img src="./imagenes/labelingSystems/2.png"/>
<ul>
  <li><strong>Discotecas:</strong> Eventos relacionados con establecimientos sociales y clubes.</li>
  <li><strong>Conciertos:</strong> Eventos musicales en vivo.</li>
  <li><strong>Eventos:</strong> Otras actividades y espectáculos disponibles.</li>
</ul>

<h3>4.2.3 SEO Tags and Meta Tags</h3>
<h3>4.2.4 Searching Systems</h3>
<p class="justificado">Los sistemas de búsqueda son esenciales para permitir a los usuarios encontrar y descubrir características y funcionalidades relevantes en nuestro sitio web. Para una experiencia de usuario eficiente, hemos implementado un sistema de búsqueda simple pero efectivo:</p>
<img src="./imagenes/labelingSystems/3.png"/>
<ul>
  <li><strong>Lupa de Búsqueda:</strong> Permite a los usuarios buscar rápidamente cualquier tema de su interés.</li>
  <li><strong>Perfil de Usuario:</strong> Representado por el icono del usuario, proporciona acceso al perfil del usuario para editar información o iniciar sesión.</li>
  <li><strong>Membresías:</strong> Representado por el icono de membresías, muestra los planes disponibles y sus precios para suscripciones mensuales o anuales.</li>
</ul>

<h3>4.2.5 Navigation Systems</h3>
<p class="justificado">Nuestra aplicación cuenta con un sistema de navegación claro y definido para garantizar una experiencia fluida para los usuarios.</p>
<img src="./imagenes/labelingSystems/5.png"/>
<p class="justificado">El sistema de navegación de nuestra aplicación móvil está diseñado para ofrecer a los usuarios una experiencia intuitiva y fluida. Con iconos claramente identificados en la parte superior, los usuarios pueden acceder fácilmente a las funciones principales de la aplicación.</p>

<h2>4.3 Landing Page UI Design</h2>
<h3>4.3.1 Landing Page Wireframe</h3>
<td>Desktop Landing Page Wireframe:</td>
<br>
<td>Pantalla de inicio, contiene el apartado mas llamativo del landing page.</td>
<img src="./imagenes/wireframe.png"/>
<br>
<td>Pantalla de "Proximos eventos", este apartado contiene los diversos eventos a los que pueden asistir los usuarios.</td>
<img src="./imagenes/wireframe1.png"/>
<br>
<td>Pantalla de "Nosotros", este apartado contiene la mision de la startup, junto con el proposito de la plataforma web.</td>
<img src="./imagenes/wireframe3.png"/>
<br>
<td>Pantalla de "Contactanos", en este apartado encuentran la informacion de contacto del startup.</td>
<img src="./imagenes/wireframe4.png"/>
<br>
<p>Link de la entrevista: https://www.figma.com/file/dDsv9BCQHxxzDUz3hqTTyp/Landing-Page-Wireframe--Desarrollo-Open-Source?type=design&mode=design&t=baNvdMOlwkRcVvBE-1</p>
<h3>4.3.2 Landing Page Mock-up</h3>
<br>
<td>Pantalla de inicio, contiene el apartado mas llamativo del landing page con los colores asignados en el Style Guidelines, detalla brevemente las multiples opciones que puede tener el usuario, acompañado con imagenes referentes.</td>
<img src="./imagenes/mockup 1.JPG"/>
<br>
<td>Pantalla de "Proximos eventos", este apartado contiene los diversos eventos a los que el usuario puede asistir, incluye la foto del artista o artistas, el lugar y la fecha de preentación.</td>
<img src="./imagenes/mockup 2.JPG"/>
<br>
<td>Pantalla de "Nosotros", este apartado contiene la mision de la startup y muestra el lineamiento que sigue la paltaforma web para cunmplir su proposito.</td>
<img src="./imagenes/mockup 3.JPG"/>
<br>
<td>Pantalla de "Contactanos", en este apartado encuentran la informacion de contacto del startup. Insertamos un QR Code para facilitar el medio de comunicacion entre el usuario y nosotros. </td>
<img src="./imagenes/mockup 4.JPG"/>
<br>
<h2>4.4 Web Applications UX/UI Design</h2>
<h3>4.4.1 Web Applications Wireframes</h3>
<h3>4.4.2 Web Applications Wireflow Diagrams</h3>
<h3>4.4.2 Web Applications Mock-ups</h3>
<h3>4.4.3 Web Applications User Flow Diagrams</h3>

<h2>4.5 Web Applications Prototyping</h2>

<h2>4.6 Domain-Driven Software Architecture</h2>
<h3>4.6.1 Software Architecture Context Diagram</h3>
<img src="./imagenes/MyEventDDC.png"/>
<h3>4.6.2 Software Architecture Container Diagrams</h3>
<img src="./imagenes/MyEventDDCTX.png"/>
<h3>4.6.3 Software Architecture Components Diagrams</h3>
<h4>Landing Page</h4>
<img src="./imagenes/MyEventDDCLand.png"/>
<h4>Web Application</h4>
<img src="./imagenes/MyEventDDCWeb.png"/>
<h4>Mobile Application</h4>
<img src="./imagenes/MyEventDDCMB.png"/>
<h4>API</h4>
<img src="./imagenes/MyEventDDCAPI.png"/>

<h2>4.7 Software Object-Oriented Design</h2>
<h3>4.7.1 Class Diagrams</h3>
<img src="./imagenes/DiagramaClases.png"/>
<h3>4.7.2 Class Dictionary</h3>

<td><strong>Usuario</strong></td>
<p>Representa a las personas que interactuan con la aplicacion.</p>
<p>Los usuarios poseen:</p>
<ul>
    <li>Nombre</li>
    <li>Apellido</li>
    <li>Dirección</li>
    <li>Correo electronico</li>
    <li>Telefono</li>
    <li>Contraseña</li>
    <li>Fecha de creacion</li>
    <li>Fecha de suspension</li>
</ul>

<td><strong>Cliente</strong></td>
<p>Usuario que solo puede comprar y ver los eventos disponibles en el aplicativo, tiene un metodo de pago para pagar sus boletos/entradas</p>

<td><strong>Revenvedor</strong></td>
<p>Un cliente puede volverse un revendedor, para eso necesita registrar donde sera almacenado su dinero.</p>

<td><strong>Organizador</strong></td>
<p>Usuario que solo puede ofertar y administrar eventos en el aplicativo, esta ligado a una empresa.</p>

<td><strong>Boleto</strong></td>
<p>Posee toda la informacion de compra como el precio y datos del evento, usuario y categoria de boleto.</p>

<td><strong>Categoria</strong></td>
<p>Se usa para clasificar los boletos de un evento, ya se por ubicacion, calidad u otro factor. La categoria afecta el precio del boleto.</p>

<td><strong>Evento</strong></td>
<p>Los eventos pueden ser conciertos, obras de teatro, etc.</p>
<p>Los eventos poseen:</p>
<ul>
    <li>Un nombre</li>
    <li>Descripcion que tiene la informacion del evento</li>
    <li>Periodo de tiempo de inicio y fin</li>
    <li>Una sede donde se da a cabo el evento</li>
    <li>Un organizador que es el encargado principal del evento</li>
    <li>Un total de boletos/entradas</li>
</ul>

<td><strong>Precio</strong></td>
<p>El precio cambia segun el evento y sus categorias, toda esta informacion es registrada por el organizador.</p>

<td><strong>Lugar</strong></td>
<p>Es una ubicación fisica donde reside un local.</p>

<td><strong>RUC</strong></td>
<p>Es el padrón que contiene los datos de identificación de las actividades económicas y demás información relevante de los sujetos inscritos.</p>

<td><strong>Sede</strong></td>
<p>Es el lugar donde se va a dar a cabo el evento, tiene un numero de asientos limitado.</p>

<td><strong>Empresa</strong></td>
<p>Es el ente que financia el evento y tiene un organizador que los representa en el evento./>

<h2>4.8 Database Design</h2>
<h3>4.8.1 Database Diagram</h3>
<img src="./imagenes/DiagramaBaseDatos.png"/>
    
<h1>CAPÍTULO V: PRODUCT IMPLEMENTATION</h1>
<h2>5.1 Software Configuration Management</h2>
<h3>5.1.1 Software Development Environment Configuration</h3>
<p class="justificado">En la siguiente sección se detalla la ruta de acceso de cada uno de los productos de software, facilitando a cualquier miembro del equipo el desarrollo de cada aspecto del trabajo:</p>
<p>Visual Studio Code: Entorno de desarrollo.</p>
<img src="./imagenes/logo-visual.png"/>
<p>HTML5: Lenguaje de marcado para la elaboración de páginas web.</p>
<img src="./imagenes/logo-html.png"/>
<p>CSS3: Tecnología para dar estilo a nuestras páginas web.</p>
<img src="./imagenes/logo-css.png"/>
<p>JavaScript: Lenguaje de programación orientado a objetos utilizado para implementar funcionalidades en nuestra Landing Page.</p>
<img src="./imagenes/logo-js.png"/>
<p>GitHub: Repositorio colaborativo en la nube.</p>
<img src="./imagenes/logo-github.png"/>
<p>GitHub Pages: Plataforma que facilita implementar despliegues sencillos para nuestras páginas web.</p>
<img src="./imagenes/logo-githubpages.png"/>
<p>LucidChart: Aplicación web dedicada a la elaboración de Wireflows, User Flows y diagramas de clases.</p>
<img src="./imagenes/logo-lucidchart.png"/>
<p>Vertabelo: Plataforma colaborativa para la creación de diagramas de base de datos.</p>
<img src="./imagenes/logo-vertabelo.png"/>
<p>Figma: Herramienta colaborativa que permite elaborar wireframes y mockups.</p>
<img src="./imagenes/logo-figma.png"/>
<h3>5.1.2 Source Code Management</h3>
<p>
Link del Landing Page: https://stxfxno.github.io/MyEvent/myevent.html
    
<p>Trabajamos con tres ramas principales:</p>  
<p>Main: Es nuestra rama principal donde presentaremos nuestras publicaciones oficiales.
<p>Dev: Esta rama es nuestro entorno de desarrollo, donde probamos e integramos las funcionalidades trabajadas antes de ser implementadas en la rama principal.</p>    
<p>Feat: Esta rama se descompone en ramas individuales por cada funcionalidad o feature trabajada, permitiendo un enfoque más específico y organizado en el desarrollo de cada aspecto del proyecto.</p>

<h3>5.1.3 Source Code Style Guide & Conventions</h3>
<p>HTML:</p>
<p>En HTML se aplicó la nomenclatura en inglés, por ello en cada DIV su class va estar declarado en este idioma, también podemos observar esto en los inputs y en la clase de span.</p>
<p>div class="search">/div</p>
<img src="./imagenes/html-img1.png"/>
<p>div class="destination__container">/div</p>
<img src="./imagenes/html-image2.png"/>
<p>CSS:</p>
<p>En CSS se mantuvo el mismo trabajo de como se realizó en el HTML.</p>  
<img src="./imagenes/css-img1.png"/>
<img src="./imagenes/css-img2.png"/>
<p>JS:</p>
<p>Con respecto al desarrollo del JS las variables usadas también se aplico la nomenclatura en inglés:</p>
<img src="./imagenes/js-img1.png"/>
<p>Con la primera función creada en JS de const showHideIcons se espera que cada vez que fuera a la izquierda o derecha se ocultara el icono de navegación:</p>
<p>Icono de la izquierda oculto:</p>
<img src="./imagenes/js-ejemplo1.png"/>
<p>Icono de la derecha oculto:</p>
<img src="./imagenes/js-ejemplo2.png"/>
<p>Con respecto a la segunda función, nos da la posibilidad de navegar en el carrusel de arrastrando las imágenes de manera horizontal, ya sea para la derecha o izquierda.</p>
<img src="./imagenes/js-ejemplo3.png"/>
<h3>5.1.4 Software Deployment Configuration</h3>
<p class="justificado">Primero: Subimos todos los archivos necesarios para que github.pages funcione correctamente, entre ellos podemos observar el index.html, styles.css y las demás carpetas que están en formato html.</p>
<img src="./imagenes/paso1.png"/>
<p>Segundo: Recordemos que para funcione la página correctamente la implementación de nuestro landing page debe de tener la siguiente nomenclatura:</p>  
<p>Nombre del proyecto.github.io en este caso se uso el nombre de stxfxno para el nombre del proyecto.</p>
<img src="./imagenes/paso2.png"/>
<p>Tercero: Verificamos que la pagina se haya subido de manera correcta a GitHub Pages , por ello entramos a settings y vamos al apartado de page. </p>
<img src="./imagenes/paso3-parte1.png"/>
<p>Una vez ya en Pages, asegurarnos que en Branch este seleccionado el de main y luego darle en save, esperamos unos minutos para que cargue la página.</p>
<img src="./imagenes/paso3-parte2.png"/>
<p>Luego de esperar cierto tiempo, esperamos a que nuestra página este subida a GitHub Pages, si sale para visitar nuestro sitio web es porque lo hicimos correctamente.</p>
<img src="./imagenes/paso3-parte3.png"/>
<h2>5.2 Product Implementation & Deployment</h2>
<h3>5.2.1.1 Sprint Planning 1</h3>
 <table>
            <thead>
                <tr>
                    <td>Sprint #</td>
                    <td>Sprint 1</td>
                </tr>
                <tr>
                    <td colspan="2">Sprint Planning Background</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Date</td>
                    <td>10/04/2024</td>
                </tr>
                <tr>
                    <td>Time</td>
                    <td>00:00 am</td>
                </tr>
                <tr>
                    <td>Location</td>
                    <td>Google Meet</td>
                </tr>
                <tr>
                    <td>Prepared By</td>
                    <td>Godofredo Quispe Tipo</td>
                </tr>
                <tr>
                    <td>Attendees (to planning meeting)</td>
                    <td>/ / Quispe Tipo, Godofredo /</td>
                </tr>
                <tr>
                    <td>Sprint n – 1 Review Summary</td>
                    <td>Debido a que es el primer sprint, no hay reviews de un sprint anterior.</td>
                </tr>
                <tr>
                    <td>Sprint n – 1 Retrospective Summary</td>
                    <td>Siendo el primer sprint, se mencionará la expectativa de los miembros del equipo: Terminar las actividades antes de la crítica. </td>
                </tr>
                <tr>
                    <td colspan="2">Sprint Goal & User Stories</td>
                </tr>
                <tr>
                    <td>Sprint 1 Goal</td>
                    <td>Diseñar e implementar una landing page, realizar el CRUD de adquisicion de boletos u entradas.</td>
                </tr>
                <tr>
                    <td>Sprint 1 Velocity</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>Sum of Story Points</td>
                    <td>13</td>
                </tr>
            </tbody>
        </table>

<h3>5.2.1.2 Sprint Backlog 1</h3>
<P>En este primer Sprint Backlog el grupo se enfoco en realizar la landing page y el diseño del Front de la aplicación web junto con el CRUD de la venta de boletas. Para el registro de cada tarea utilizamos Trello</P>
<img src="https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/cad12107-8da2-477f-854c-a4acc4d893c7">
<table>
            <thead>
                    <tr>
                    <td>Sprint #:</td>
                    <td colspan="7">Sprint 1</td>
                    </tr>
                    <tr>
                        <td colspan="2">User Story</td>
                        <td colspan="6">Work-Item / Task</td>
                    </tr>
                    <tr>
                        <td>ID</td>
                        <td>Title</td>
                        <td>ID</td>
                        <td>Title</td>
                        <td>Description</td>
                        <td>Estimation (Hours)</td>
                        <td>Assigned to</td>
                        <td>Status (To-Do/In-Process/To-Review/Done)</td>
                    </tr>
            </thead>
            <tbody>
                    <tr>
                        <td>..</td>
                        <td>..</td>
                        <td>..</td>
                        <td>..</td>
                        <td>..</td>
                        <td>..</td>
                        <td>..</td>
                        <td>..</td>
                    </tr>
            </tbody>
</table>
<h3>5.2.1.3 Development Evidence for Sprint Review.</h3>
<table>
    <thead>
      <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Committed on (date)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ponlo para poder mostraralo en GitHub(URL)</td>
        <td>nombre_de_la_rama</td>
        <td>ID_del_commit</td>
        <td>Mensaje_del_commit</td>
        <td>Cuerpo_del_mensaje_del_commit</td>
        <td>Fecha_de_commit</td>
      </tr>
      <!-- Aquí puedes agregar más filas si necesitas -->
    </tbody>
</table>
<h3>5.2.1.4 Testing Suite Evidence for Sprint Review.</h3>
<table>
    <thead>
      <tr>
        <th>Repository</th>
        <th>Branch</th>
        <th>Commit ID</th>
        <th>Commit Message</th>
        <th>Commit Message Body</th>
        <th>Committed on (date)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ponlo para poder mostraralo en GitHub(URL)</td>
        <td>nombre_de_la_rama</td>
        <td>ID_del_commit</td>
        <td>Mensaje_del_commit</td>
        <td>Cuerpo_del_mensaje_del_commit</td>
        <td>Fecha_de_commit</td>
      </tr>
      <!-- Aquí puedes agregar más filas si necesitas -->
    </tbody>
</table>
<h3>5.2.1.5 Execution Evidence for Sprint Review.</h3>
Registro de usuario:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/9a4fbf95-c832-4e19-a6df-9a0c013722e8>
Ingreso de usuario:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/da88db46-8844-4c7c-b92b-4e7dcda6371e>
Ingreso de fecha de publicacion del evento:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/0ccf3c98-e90d-4dbc-9167-7f0ec1626e00>
Añadiendo evento:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/8185c700-0e34-43ec-9905-9f0765532e80>
Descripcion del Evento:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/ad5b917f-4805-4f87-a254-c9088fe44ee8>
Registro de Evento Confirmado:
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/b09fc6ee-54e3-4aa6-aae4-59b89f049ff1>

<h3>5.2.1.6 Services Documentation Evidence for Sprint Review.</h3>
<p>Para este primer sprint no fue contemplada la evidencia de documentacion de los servicios.</p>
<h3>5.2.1.7 Software Deployment Evidence for Sprint Review.</h3>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/1b3fa686-0854-43de-a750-e5e8c0b8171f>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/cfb530ba-637b-4770-9689-82b60e77ce3b>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/1ecb7c71-631f-4456-a070-ea9f0de0eba9>
<img src=https://github.com/AlejandroZarateGamarra/WS51_AppWeb_Grupo2/assets/112044940/a883a101-fe73-4215-9798-7e88ab721427>
<h3>5.2.1.8 Team Collaboration Insights during Sprint.</h3>
