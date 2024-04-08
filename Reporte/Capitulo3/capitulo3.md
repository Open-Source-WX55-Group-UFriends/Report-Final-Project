# CAPITULO III: Requirements Specifications

## 3.1 To-Be Scenario Mapping
![Imagen de Granjero To-Be Scenario Mapping](https://i.postimg.cc/52VS1CqV/To-Be-Scenario-Mapping-Granjero.jpg)
![Imagen de Trabajador To-Be Scenario Mapping](https://i.postimg.cc/wT0JLmcg/To-Be-Scenario-Mapping-Trabajadores.jpg)
![Imagen de Empresario To-Be Scenario Mapping](https://i.postimg.cc/zfYSzRCN/To-Be-Scenario-Mapping-Empresario.jpg)

## 3.2 User Stories
<table>
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
<tr>
    <td>US-01</td> 
    <td>Ver descripción clara y concisa de los servicios en la landing page</td>
    <td>Como usuario potencial, quiero ver una descripción clara y concisa de los servicios ofrecidos en la landing page, para comprender rápidamente cómo pueden beneficiar a mi operación agrícola y ganadera.</td>
    <td>
        <b>Scenario 01:</b> Acceso exitoso a la descripción de servicios en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> observa la sección de servicios ofrecidos<br>
        <b>Entonces</b> el usuario puede leer fácilmente una descripción clara y concisa de los servicios agrícolas y ganaderos, resaltando cómo pueden beneficiar su operación.<br><br>
        <b>Scenario 02:</b> Error al acceder a la descripción de servicios en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> intenta acceder a la sección de servicios ofrecidos<br>
        <b>Entonces</b> el usuario se confunde al no encontrar una descripción clara y concisa de los servicios, lo que podría hacerle perder interés en la plataforma.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-02</td> 
    <td>Encontrar fácilmente los precios y planes de suscripción en la landing page</td>
    <td>Como usuario potencial, quiero encontrar fácilmente los precios y planes de suscripción disponibles en la landing page, para evaluar la viabilidad económica de utilizar la plataforma en mi granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso exitoso a los precios y planes de suscripción en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre precios y planes de suscripción<br>
        <b>Entonces</b> el usuario puede encontrar rápidamente una sección dedicada que describe los diferentes precios y planes de suscripción disponibles, con claridad sobre lo que incluye cada uno y sus costos asociados.<br><br>
        <b>Scenario 02:</b> Dificultad para encontrar precios y planes de suscripción en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre precios y planes de suscripción<br>
        <b>Entonces</b> el usuario se frustra al no encontrar fácilmente la información que busca, lo que puede generar dudas sobre la transparencia de la plataforma y su viabilidad económica para su granja.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-03</td> 
    <td>Adaptación de la landing page a diferentes dispositivos</td>
    <td>Como usuario potencial, quiero que la landing page se adapte correctamente a la pantalla de mi dispositivo, para poder verla y usarla de forma cómoda, independientemente de si estoy usando un ordenador, una tablet o un teléfono móvil.</td>
    <td>
        <b>Scenario 01:</b> Adaptación exitosa en diferentes dispositivos<br>
        <b>Dado</b> que un usuario potencial visita la landing page desde diferentes dispositivos (ordenador, tablet, teléfono móvil)<br>
        <b>Cuando</b> accede a la landing page desde cada dispositivo<br>
        <b>Entonces</b> la página se adapta correctamente a la pantalla de cada dispositivo, manteniendo una experiencia de usuario cómoda y funcional en todas las resoluciones y tamaños de pantalla.<br><br>
        <b>Scenario 02:</b> Problemas de adaptación en algunos dispositivos<br>
        <b>Dado</b> que un usuario potencial visita la landing page desde diferentes dispositivos (ordenador, tablet, teléfono móvil)<br>
        <b>Cuando</b> accede a la landing page desde ciertos dispositivos<br>
        <b>Entonces</b> la página presenta problemas de visualización o funcionalidad en algunos dispositivos, lo que dificulta la experiencia del usuario y puede llevar a una percepción negativa de la plataforma.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-04</td> 
    <td>Identificar fácilmente las características de la aplicación en la landing page</td>
    <td>Como usuario potencial, quiero identificar fácilmente en la landing page las características que me ayudarán a encontrar una granja ideal, para evaluar la efectividad de la aplicación.</td>
    <td>
        <b>Scenario 01:</b> Acceso fácil a las características en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca características para encontrar una granja ideal<br>
        <b>Entonces</b> el usuario puede encontrar rápidamente una sección dedicada que describe las características principales, como ubicación, tamaño, tipo de suelo, instalaciones, etc., de manera clara y organizada.<br><br>
        <b>Scenario 02:</b> Dificultad para identificar características en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca características para encontrar una granja ideal<br>
        <b>Entonces</b> el usuario se siente frustrado al no poder identificar fácilmente las características necesarias, lo que puede afectar su percepción de la efectividad de la aplicación y su interés en utilizarla.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-05</td> 
    <td>Encontrar información sobre los colaboradores en la landing page</td>
    <td>Como usuario potencial, quiero encontrar información sobre los colaboradores del proyecto en la landing page, para saber quiénes están detrás de la aplicación y qué experiencia tienen.</td>
    <td>
        <b>Scenario 01:</b> Acceso fácil a la información de los colaboradores en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre los colaboradores del proyecto<br>
        <b>Entonces</b> el usuario puede encontrar rápidamente una sección dedicada que describe quiénes son los colaboradores del proyecto, incluyendo sus nombres, roles y experiencia relevante de manera clara y organizada.<br><br>
        <b>Scenario 02:</b> Dificultad para encontrar información de los colaboradores en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre los colaboradores del proyecto<br>
        <b>Entonces</b> el usuario se siente frustrado al no poder encontrar fácilmente la información deseada, lo que puede generar dudas sobre la transparencia y credibilidad del proyecto.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-06</td> 
    <td>Interactuar con las imágenes en la landing page</td>
    <td>Como usuario potencial, quiero interactuar con las imágenes de la landing page, para obtener más información o realizar acciones, como ampliarlas, verlas en una galería o acceder a una descripción.</td>
    <td>
        <b>Scenario 01:</b> Interacción exitosa con las imágenes en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> interactúa con las imágenes presentes en la página<br>
        <b>Entonces</b> el usuario puede realizar acciones como ampliar las imágenes, verlas en una galería o acceder a una descripción detallada, lo que mejora su experiencia de navegación y le proporciona información adicional.<br><br>
        <b>Scenario 02:</b> Problemas de interacción con las imágenes en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> intenta interactuar con las imágenes presentes en la página<br>
        <b>Entonces</b> el usuario encuentra dificultades para ampliar las imágenes, acceder a una galería o encontrar una descripción detallada, lo que puede generar frustración y afectar negativamente su experiencia de usuario.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-07</td> 
    <td>Demostración de efectividad de funciones en la landing page</td>
    <td>Como usuario potencial, quiero encontrar fácilmente información en la landing page sobre cómo puedo mejorar la eficiencia y rentabilidad de mi granja utilizando la plataforma, para evaluar la efectividad de la aplicación.</td>
    <td>
        <b>Scenario 01:</b> Acceso fácil a información sobre mejora de eficiencia en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre cómo mejorar la eficiencia y rentabilidad de su granja<br>
        <b>Entonces</b> el usuario puede encontrar rápidamente una sección dedicada que describe cómo la plataforma puede ayudar a mejorar la eficiencia y rentabilidad de su granja, proporcionando detalles sobre características, herramientas y consejos útiles de manera clara y organizada.<br><br>
        <b>Scenario 02:</b> Dificultad para encontrar información sobre mejora de eficiencia en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre cómo mejorar la eficiencia y rentabilidad de su granja<br>
        <b>Entonces</b> el usuario se siente frustrado al no poder encontrar fácilmente la información deseada, lo que puede generar dudas sobre la efectividad y utilidad de la aplicación.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-08</td> 
    <td>Entender cómo la plataforma puede ayudar a controlar costos y maximizar ingresos en la landing page</td>
    <td>Como usuario potencial, quiero entender en la landing page cómo la plataforma puede ayudarme a controlar los costos y maximizar los ingresos de mi granja, para evaluar la efectividad de la aplicación.</td>
    <td>
        <b>Scenario 01:</b> Acceso fácil a información sobre control de costos y maximización de ingresos en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre cómo la plataforma puede ayudar a controlar costos y maximizar ingresos<br>
        <b>Entonces</b> el usuario puede encontrar rápidamente una sección dedicada que describe cómo la plataforma ofrece herramientas y funcionalidades para controlar costos, optimizar recursos y maximizar ingresos en la operación de su granja, de manera clara y organizada.<br><br>
        <b>Scenario 02:</b> Dificultad para entender cómo la plataforma puede ayudar en control de costos y maximización de ingresos en la landing page<br>
        <b>Dado</b> que un usuario potencial visita la landing page por primera vez<br>
        <b>Cuando</b> busca información sobre cómo la plataforma puede ayudar a controlar costos y maximizar ingresos<br>
        <b>Entonces</b> el usuario se siente frustrado al no poder entender fácilmente cómo la plataforma puede ser útil para su situación específica, lo que puede generar dudas sobre la efectividad y utilidad de la aplicación en este aspecto.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-09</td> 
    <td>Elegir método de pago para suscripción</td>
    <td>Como dueño de granja, quiero elegir entre diferentes métodos de pago, para pagar mi suscripción de la forma más cómoda y segura para mí.</td>
    <td>
        <b>Scenario 01:</b> Acceso exitoso a los métodos de pago<br>
        <b>Dado</b> que soy un dueño de granja registrado<br>
        <b>Cuando</b> navego a la sección de pagos de la suscripción<br>
        <b>Entonces</b> el sistema muestra una lista de métodos de pago disponibles, incluyendo tarjetas de crédito, débito y otros servicios de pago electrónico, con la opción de seleccionar uno.<br><br>
        <b>Scenario 02:</b> Error al cargar métodos de pago<br>
        <b>Dado</b> que soy un dueño de granja registrado<br>
        <b>Cuando</b> intento acceder a la sección de pagos de la suscripción<br>
        <b>Entonces</b> el sistema muestra un mensaje indicando que los métodos de pago no están disponibles en este momento o hay un problema técnico.<br><br>
        <b>Scenario 03:</b> Selección y confirmación de método de pago<br>
        <b>Dado</b> que he seleccionado un método de pago<br>
        <b>Cuando</b> confirmo mi elección y procedo al pago<br>
        <b>Entonces</b> el sistema muestra un resumen de la suscripción y del método de pago elegido, permitiéndome confirmar la transacción.<br><br>
        <b>Scenario 04:</b> Confirmación exitosa de pago<br>
        <b>Dado</b> que he confirmado mi transacción de pago<br>
        <b>Cuando</b> se procesa la transacción con éxito<br>
        <b>Entonces</b> el sistema muestra un mensaje de confirmación y actualiza mi suscripción automáticamente.<br><br>
        <b>Scenario 05:</b> Error en la confirmación de pago<br>
        <b>Dado</b> que he confirmado mi transacción de pago<br>
        <b>Cuando</b> hay un error durante el procesamiento de la transacción<br>
        <b>Entonces</b> el sistema muestra un mensaje de error indicando que la transacción no se pudo completar y proporciona instrucciones sobre qué hacer a continuación.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-10</td> 
    <td>Crear y asignar tareas a los trabajadores</td>
    <td>Como dueño de granja, quiero crear y asignar tareas a los trabajadores, para mejorar la gestión de la mano de obra en mi finca.</td>
    <td>
        <b>Scenario 01:</b> Creación de nueva tarea exitosa<br>
        <b>Dado</b> que soy el dueño de la granja y estoy autenticado en el sistema<br>
        <b>Cuando</b> accedo a la sección de gestión de tareas<br>
        <b>Entonces</b> el sistema me permite crear una nueva tarea especificando detalles como nombre, descripción, fecha límite, y asignarla a uno o varios trabajadores.<br><br>
        <b>Scenario 02:</b> Falla en la creación de nueva tarea<br>
        <b>Dado</b> que soy el dueño de la granja y estoy autenticado en el sistema<br>
        <b>Cuando</b> estoy creando una tarea y completo algún detalle con un valor inválido<br>
        <b>Entonces</b> el sistema muestra un mensaje de error e indica cuál es el problema.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-11</td> 
    <td>Recibir notificaciones sobre tareas asignadas</td>
    <td>Como trabajador, quiero recibir notificaciones sobre las tareas asignadas, para mantenerme informado sobre las indicaciones del superior.</td>
    <td>
        <b>Scenario 01:</b> Recepción de notificación al asignar una tarea<br>
        <b>Dado</b> que soy un trabajador registrado en el sistema<br>
        <b>Cuando</b> el superior asigna una nueva tarea a mí<br>
        <b>Entonces</b> el sistema me envía una notificación instantánea con los detalles de la tarea asignada.<br><br>
        <b>Scenario 02:</b> Notificación de recordatorio de tarea pendiente<br>
        <b>Dado</b> que soy un trabajador con una tarea pendiente<br>
        <b>Cuando</b> la fecha límite de la tarea se acerca o ha pasado<br>
        <b>Entonces</b> el sistema me envía una notificación recordándome la tarea pendiente y la fecha límite.<br><br>
        <b>Scenario 03:</b> Acceso a notificaciones en la aplicación<br>
        <b>Dado</b> que soy un trabajador que ha recibido notificaciones<br>
        <b>Cuando</b> accedo a la aplicación móvil o al sitio web<br>
        <b>Entonces</b> el sistema me muestra una lista de todas las notificaciones recibidas, permitiéndome revisarlas en cualquier momento.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-12</td> 
    <td>Registrar progreso de tareas</td>
    <td>Como trabajador, quiero registrar el progreso de mis tareas, para mantenerme organizado y productivo.</td>
    <td>
        <b>Scenario 01:</b> Actualizar estado de tarea a "En progreso"<br>
        <b>Dado</b> que soy un trabajador y tengo una tarea asignada<br>
        <b>Cuando</b> comienzo a trabajar en la tarea<br>
        <b>Entonces</b> el sistema me permite actualizar el estado de la tarea a "En progreso", indicando que estoy trabajando en ella.<br><br>
        <b>Scenario 02:</b> Registrar avance de tarea<br>
        <b>Dado</b> que soy un trabajador y estoy trabajando en una tarea<br>
        <b>Cuando</b> avanzo en la tarea y alcanzo un hito significativo<br>
        <b>Entonces</b> el sistema me permite registrar mi avance, como porcentaje completado o hitos alcanzados, y actualiza el estado de la tarea en consecuencia.<br><br>
        <b>Scenario 03:</b> Marcar tarea como completada<br>
        <b>Dado</b> que soy un trabajador y he finalizado una tarea<br>
        <b>Cuando</b> completo todos los requerimientos de la tarea<br>
        <b>Entonces</b> el sistema me permite marcar la tarea como completada, actualizando su estado y notificando al superior.<br><br>
        <b>Scenario 04:</b> Registro de tiempo dedicado a la tarea<br>
        <b>Dado</b> que soy un trabajador y quiero registrar el tiempo dedicado a una tarea<br>
        <b>Cuando</b> completo la tarea o necesito reportar el tiempo dedicado<br>
        <b>Entonces</b> el sistema me permite ingresar el tiempo dedicado y lo registra en la tarea correspondiente.<br><br>
        <b>Scenario 05:</b> Acceso al historial de progreso de tareas<br>
        <b>Dado</b> que soy un trabajador<br>
        <b>Cuando</b> accedo a mi panel de tareas asignadas<br>
        <b>Entonces</b> el sistema me muestra un historial detallado de progreso de cada tarea, incluyendo las actualizaciones de estado y los tiempos dedicados.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-13</td> 
    <td>Buscar y contactar a dueños de granjas potenciales</td>
    <td>Como empresario, quiero buscar y contactar a dueños de granjas potenciales, para establecer asociaciones comerciales y mejorar nuestra cadena de suministro.</td>
    <td>
        <b>Scenario 01:</b> Búsqueda de dueños de granjas potenciales<br>
        <b>Dado</b> que soy un empresario autenticado en el sistema<br>
        <b>Cuando</b> accedo a la función de búsqueda<br>
        <b>Entonces</b> el sistema me permite buscar dueños de granjas potenciales utilizando criterios como ubicación, tipo de cultivo, tamaño de la granja, etc.<br><br>
        <b>Scenario 02:</b> Visualización de resultados de búsqueda<br>
        <b>Dado</b> que he realizado una búsqueda de dueños de granjas potenciales<br>
        <b>Cuando</b> el sistema encuentra coincidencias<br>
        <b>Entonces</b> el sistema me muestra una lista de resultados de búsqueda que coinciden con mis criterios, incluyendo detalles de contacto como correo electrónico, número de teléfono, etc.<br><br>
        <b>Scenario 03:</b> Contacto con dueños de granjas potenciales<br>
        <b>Dado</b> que he encontrado un dueño de granja potencial con el que deseo establecer una asociación comercial<br>
        <b>Cuando</b> selecciono el perfil del dueño de la granja<br>
        <b>Entonces</b> el sistema me muestra opciones para contactarlo, como enviar un correo electrónico directamente desde la plataforma o acceder a su información de contacto para hacer una llamada.<br><br>
        <b>Scenario 04:</b> Registro de interacciones<br>
        <b>Dado</b> que he contactado a un dueño de granja potencial<br>
        <b>Cuando</b> realizo una interacción, como enviar un correo electrónico o hacer una llamada<br>
        <b>Entonces</b> el sistema registra la interacción y la asocia con el perfil del dueño de la granja, permitiéndome hacer un seguimiento de las comunicaciones realizadas.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-14</td> 
    <td>Ver información detallada de las granjas</td>
    <td>Como empresario, quiero ver información detallada de las granjas, para poder elegir una adecuada para mi idea de negocio.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la lista de granjas<br>
        <b>Dado</b> que soy un empresario autenticado en el sistema<br>
        <b>Cuando</b> accedo a la sección de granjas disponibles<br>
        <b>Entonces</b> el sistema me muestra una lista de granjas disponibles para explorar.<br><br>
        <b>Scenario 02:</b> Visualización de detalles de granja<br>
        <b>Dado</b> que estoy viendo la lista de granjas<br>
        <b>Cuando</b> selecciono una granja específica<br>
        <b>Entonces</b> el sistema me muestra información detallada de la granja, incluyendo ubicación, tamaño, tipo de cultivos, infraestructura, historial de producción, etc.<br><br>
        <b>Scenario 03:</b> Exploración de fotos y videos de la granja<br>
        <b>Dado</b> que estoy viendo los detalles de una granja<br>
        <b>Cuando</b> accedo a la galería de medios<br>
        <b>Entonces</b> el sistema me muestra fotos y videos de la granja, permitiéndome explorar visualmente las instalaciones y condiciones.<br><br>
        <b>Scenario 05:</b> Guardar granjas como favoritas<br>
        <b>Dado</b> que soy un empresario interesado en varias granjas<br>
        <b>Cuando</b> encuentro una granja que me interesa<br>
        <b>Entonces</b> el sistema me permite guardar la granja como favorita para poder acceder fácilmente a ella más tarde.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-15</td> 
    <td>Buscar granjas con filtros específicos</td>
    <td>Como empresario, quiero buscar granjas con filtros en específico, para encontrar fácilmente una granja que se adapte a mis necesidades.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la función de búsqueda avanzada<br>
        <b>Dado</b> que soy un empresario autenticado en el sistema<br>
        <b>Cuando</b> accedo a la función de búsqueda avanzada<br>
        <b>Entonces</b> el sistema me permite utilizar filtros específicos para refinar mi búsqueda de granjas.<br><br>
        <b>Scenario 02:</b> Filtro por ubicación<br>
        <b>Dado</b> que estoy utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciono un filtro de ubicación, como ciudad o región<br>
        <b>Entonces</b> el sistema muestra solo las granjas ubicadas en la ubicación especificada.<br><br>
        <b>Scenario 03:</b> Filtro por tipo de cultivo<br>
        <b>Dado</b> que estoy utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciono un filtro de tipo de cultivo, como frutas, verduras, cereales, etc.<br>
        <b>Entonces</b> el sistema muestra solo las granjas que cultivan el tipo de cultivo especificado.<br><br>
        <b>Scenario 04:</b> Filtro por tamaño de la granja<br>
        <b>Dado</b> que estoy utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciono un filtro de tamaño de la granja, como pequeña, mediana o grande<br>
        <b>Entonces</b> el sistema muestra solo las granjas que se ajustan al tamaño especificado.<br><br>
        <b>Scenario 05:</b> Filtro por infraestructura<br>
        <b>Dado</b> que estoy utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciono un filtro de infraestructura, como invernaderos, sistemas de riego, almacenes, etc.<br>
        <b>Entonces</b> el sistema muestra solo las granjas que cuentan con la infraestructura especificada.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-16</td> 
    <td>Acceder a valoraciones y comentarios de otras empresas sobre las granjas</td>
    <td>Como empresario, quiero acceder a las valoraciones y comentarios de otros empresarios sobre las granjas, para tomar decisiones informadas y sentirme seguro al realizar negocios con ellas.</td>
    <td>
        <b>Scenario 01:</b> Acceso a valoraciones y comentarios<br>
        <b>Dado</b> que soy un empresario autenticado en el sistema<br>
        <b>Cuando</b> accedo a la página de detalles de una granja<br>
        <b>Entonces</b> el sistema me muestra las valoraciones y comentarios dejados por otros empresarios sobre esa granja.<br><br>
        <b>Scenario 02:</b> Visualización de valoraciones<br>
        <b>Dado</b> que estoy viendo las valoraciones de una granja<br>
        <b>Cuando</b> accedo a las valoraciones<br>
        <b>Entonces</b> el sistema me muestra una calificación numérica o de estrellas y comentarios detallados dejados por otros empresarios.<br><br>
        <b>Scenario 03:</b> Filtro de valoraciones<br>
        <b>Dado</b> que estoy viendo las valoraciones de una granja<br>
        <b>Cuando</b> accedo a los filtros de valoraciones<br>
        <b>Entonces</b> el sistema me permite filtrar las valoraciones por diferentes criterios, como puntuación, fecha, etc.<br><br>
        <b>Scenario 04:</b> Dejar valoración y comentario<br>
        <b>Dado</b> que soy un empresario y he interactuado con una granja<br>
        <b>Cuando</b> deseo dejar una valoración y comentario sobre mi experiencia<br>
        <b>Entonces</b> el sistema me permite dejar una valoración y escribir un comentario detallado sobre mi experiencia con la granja.<br><br>
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-17</td> 
    <td>Recibir alertas automáticas sobre cambios climáticos significativos</td>
    <td>Como trabajador, quiero recibir alertas automáticas sobre cambios climáticos significativos que puedan afectar mis cultivos, para poder tomar medidas preventivas y proteger mis cosechas.</td>
    <td>
        <b>Scenario 01:</b> Recepción de alertas automáticas<br>
        <b>Dado</b> que hay un cambio climático significativo que puede afectar mis cultivos<br>
        <b>Cuando</b> se activa una alerta automática<br>
        <b>Entonces</b> el sistema me envía una notificación instantánea con detalles sobre el cambio climático y recomendaciones sobre las medidas preventivas que debo tomar.<br><br>
        <b>Scenario 02:</b> Acceso a información detallada<br>
        <b>Dado</b> que recibo una alerta automática<br>
        <b>Cuando</b> accedo a la sección de alertas en la aplicación<br>
        <b>Entonces</b> el sistema me muestra información detallada sobre el cambio climático, incluyendo pronósticos, impacto esperado en los cultivos y consejos para proteger las cosechas.<br><br>
        <b>Scenario 03:</b> Historial de alertas recibidas<br>
        <b>Dado</b> que soy un trabajador<br>
        <b>Cuando</b> accedo a la sección de alertas en la aplicación<br>
        <b>Entonces</b> el sistema me muestra un historial de todas las alertas recibidas, permitiéndome revisarlas en cualquier momento y hacer un seguimiento de los eventos climáticos pasados.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-18</td> 
    <td>Verificar niveles de inventario y recibir notificaciones de reposición</td>
    <td>Como dueño de la granja, quiero verificar fácilmente los niveles de inventario de productos agrícolas y ganaderos, y recibir notificaciones cuando sea necesario reponerlos, para garantizar un flujo de trabajo ininterrumpido.</td>
    <td>
        <b>Scenario 01:</b> Acceso a los niveles de inventario<br>
        <b>Dado</b> que soy el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accedo al panel de control de inventario<br>
        <b>Entonces</b> el sistema me muestra una lista de productos agrícolas y ganaderos con sus respectivos niveles de inventario.<br><br>
        <b>Scenario 02:</b> Visualización detallada de inventario<br>
        <b>Dado</b> que estoy viendo los niveles de inventario<br>
        <b>Cuando</b> selecciono un producto específico<br>
        <b>Entonces</b> el sistema me muestra detalles adicionales del producto, como fecha de caducidad, ubicación de almacenamiento, etc.<br><br>
        <b>Scenario 03:</b> Configuración de notificaciones de reposición<br>
        <b>Dado</b> que soy el dueño de la granja<br>
        <b>Cuando</b> accedo a la configuración de notificaciones<br>
        <b>Entonces</b> el sistema me permite configurar umbrales de inventario bajo para recibir notificaciones cuando los niveles de un producto caigan por debajo de un cierto punto.<br><br>
        <b>Scenario 04:</b> Recepción de notificaciones de reposición<br>
        <b>Dado</b> que los niveles de inventario de un producto caen por debajo del umbral configurado<br>
        <b>Cuando</b> se activa una notificación de reposición<br>
        <b>Entonces</b> el sistema me envía una notificación instantánea indicando qué producto necesita ser reabastecido y en qué cantidad.<br><br>
        <b>Scenario 05:</b> Registro de reposición de inventario<br>
        <b>Dado</b> que he recibido una notificación de reposición<br>
        <b>Cuando</b> realizo el pedido o reabastecimiento del producto<br>
        <b>Entonces</b> el sistema registra la reposición de inventario y actualiza los niveles correspondientes en la base de datos.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-19</td> 
    <td>Ver información detallada sobre el estado de cultivos y ganado</td>
    <td>Como dueño de la granja, quiero saber información detallada sobre el estado de mis cultivos y ganado, para poder administrarla de manera rápida e informada.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la información detallada<br>
        <b>Dado</b> que soy el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accedo al panel de control de cultivos y ganado<br>
        <b>Entonces</b> el sistema me muestra una lista de todos mis cultivos y ganado con su información detallada.<br><br>
        <b>Scenario 02:</b> Visualización de detalles de cultivos<br>
        <b>Dado</b> que estoy viendo la información detallada<br>
        <b>Cuando</b> selecciono un cultivo específico<br>
        <b>Entonces</b> el sistema me muestra información detallada sobre el cultivo, como fecha de siembra, variedades, estado de crecimiento, necesidades de riego y fertilización, etc.<br><br>
        <b>Scenario 03:</b> Visualización de detalles de ganado<br>
        <b>Dado</b> que estoy viendo la información detallada<br>
        <b>Cuando</b> selecciono un animal o grupo de animales específico<br>
        <b>Entonces</b> el sistema me muestra información detallada sobre el ganado, como edad, raza, historial de salud, dieta, y cualquier otro detalle relevante.<br><br>
        <b>Scenario 04:</b> Seguimiento de cambios en el estado<br>
        <b>Dado</b> que estoy viendo la información detallada<br>
        <b>Cuando</b> los cultivos o el ganado experimentan cambios en su estado, como crecimiento, enfermedad, o reproducción<br>
        <b>Entonces</b> el sistema actualiza automáticamente la información mostrada para reflejar los cambios recientes.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-20</td> 
    <td>Ver estadísticas financieras</td>
    <td>Como dueño de la granja, quiero saber estadísticas financieras, para poder administrar correctamente la economía de mi granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso a las estadísticas financieras<br>
        <b>Dado</b> que soy el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accedo al panel de control financiero<br>
        <b>Entonces</b> el sistema me muestra una variedad de estadísticas financieras relevantes para mi granja.<br><br>
        <b>Scenario 02:</b> Visualización de ingresos y gastos<br>
        <b>Dado</b> que estoy viendo las estadísticas financieras<br>
        <b>Cuando</b> reviso la sección de ingresos y gastos<br>
        <b>Entonces</b> el sistema me muestra un desglose detallado de los ingresos y gastos de mi granja, clasificados por categoría y período de tiempo.<br><br>
        <b>Scenario 03:</b> Análisis de rentabilidad<br>
        <b>Dado</b> que estoy viendo las estadísticas financieras<br>
        <b>Cuando</b> reviso la sección de análisis de rentabilidad<br>
        <b>Entonces</b> el sistema me muestra métricas y gráficos que me ayudan a evaluar la rentabilidad de mi granja, como margen de beneficio, retorno sobre la inversión, etc.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-21</td> 
    <td>Registrar el cumplimiento de tareas con detalles de producción</td>
    <td>Como trabajador en la granja, quiero registrar el cumplimiento de mis tareas con detalles como la cantidad, calidad y fecha de cosecha, para mantener un registro preciso de la producción de la granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso al registro de cumplimiento de tareas<br>
        <b>Dado</b> que soy un trabajador autenticado en el sistema<br>
        <b>Cuando</b> accedo a mi panel de control de tareas<br>
        <b>Entonces</b> el sistema me muestra una lista de tareas asignadas y un formulario para registrar el cumplimiento de las mismas.<br><br>
        <b>Scenario 02:</b> Registro de detalles de producción<br>
        <b>Dado</b> que estoy registrando el cumplimiento de una tarea<br>
        <b>Cuando</b> ingreso los detalles de producción, como cantidad cosechada, calidad del producto, fecha de cosecha, etc.<br>
        <b>Entonces</b> el sistema registra estos detalles junto con la tarea cumplida.<br><br>
        <b>Scenario 03:</b> Registro de calidad del producto<br>
        <b>Dado</b> que estoy registrando el cumplimiento de una tarea relacionada con la producción<br>
        <b>Cuando</b> ingreso la calidad del producto, como grado de madurez, tamaño, estado de frescura, etc.<br>
        <b>Entonces</b> el sistema registra esta información para proporcionar un registro detallado de la calidad de la producción.<br><br>
        <b>Scenario 04:</b> Seguimiento de fechas de cosecha<br>
        <b>Dado</b> que estoy registrando el cumplimiento de una tarea de cosecha<br>
        <b>Cuando</b> ingreso la fecha de cosecha<br>
        <b>Entonces</b> el sistema registra la fecha de cosecha junto con los demás detalles de producción.<br><br>
        <b>Scenario 05:</b> Revisión y edición de registros<br>
        <b>Dado</b> que soy un trabajador y deseo revisar o editar registros de cumplimiento de tareas anteriores<br>
        <b>Cuando</b> accedo al historial de registros de cumplimiento de tareas<br>
        <b>Entonces</b> el sistema me permite ver y editar los detalles registrados previamente, manteniendo un registro preciso y actualizado de la producción de la granja.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-22</td> 
    <td>Emitir alertas de emergencia de manera eficaz</td>
    <td>Como trabajador en la granja, quiero emitir alertas sobre cualquier emergencia a mis colegas y supervisores de manera eficaz e inmediata.</td>
    <td>
        <b>Scenario 01:</b> Acceso rápido a la función de alerta de emergencia<br>
        <b>Dado</b> que soy un trabajador en la granja<br>
        <b>Cuando</b> me encuentro en una situación de emergencia<br>
        <b>Entonces</b> quiero acceder rápidamente a la función de alerta de emergencia en la aplicación o dispositivo proporcionado.<br><br>
        <b>Scenario 02:</b> Selección del tipo de emergencia<br>
        <b>Dado</b> que estoy emitiendo una alerta de emergencia<br>
        <b>Cuando</b> selecciono el tipo de emergencia que estoy enfrentando, como incendio, accidente, lesión, etc.<br>
        <b>Entonces</b> el sistema registra el tipo de emergencia para una respuesta adecuada.<br><br>
        <b>Scenario 03:</b> Notificación a colegas y supervisores<br>
        <b>Dado</b> que emito una alerta de emergencia<br>
        <b>Cuando</b> envío la alerta<br>
        <b>Entonces</b> el sistema notifica automáticamente a mis colegas y supervisores designados sobre la emergencia, utilizando métodos como notificaciones push, mensajes de texto o llamadas de voz.<br><br>
        <b>Scenario 04:</b> Inclusión de detalles adicionales<br>
        <b>Dado</b> que estoy emitiendo una alerta de emergencia<br>
        <b>Cuando</b> necesito proporcionar detalles adicionales, como ubicación exacta, número de personas involucradas, gravedad de la situación, etc.<br>
        <b>Entonces</b> el sistema me permite incluir esta información para una mejor comprensión de la emergencia.<br><br>
        <b>Scenario 05:</b> Confirmación de recepción de alerta<br>
        <b>Dado</b> que emito una alerta de emergencia<br>
        <b>Cuando</b> mis colegas y supervisores reciben la alerta<br>
        <b>Entonces</b> el sistema muestra una confirmación de recepción para garantizar que la alerta haya sido recibida y comprendida.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-23</td> 
    <td>Registrar horas de trabajo para cálculo de salario</td>
    <td>Como trabajador, quiero registrar mis horas de trabajo, para saber mi salario en función a ello.</td>
    <td>
        <b>Scenario 01:</b> Acceso al registro de horas de trabajo<br>
        <b>Dado</b> que soy un trabajador autenticado en el sistema<br>
        <b>Cuando</b> accedo a la función de registro de horas de trabajo<br>
        <b>Entonces</b> el sistema me muestra un formulario o interfaz para ingresar mis horas de trabajo.<br><br>
        <b>Scenario 02:</b> Registro de horas trabajadas<br>
        <b>Dado</b> que estoy registrando mis horas de trabajo<br>
        <b>Cuando</b> ingreso la hora de inicio y la hora de fin de mi jornada laboral<br>
        <b>Entonces</b> el sistema calcula automáticamente la duración de mi jornada y registra estas horas en mi historial de trabajo.<br><br>
        <b>Scenario 03:</b> Registro de horas extras<br>
        <b>Dado</b> que trabajo horas extras<br>
        <b>Cuando</b> ingreso las horas extras trabajadas<br>
        <b>Entonces</b> el sistema registra estas horas extras en mi historial de trabajo, con una indicación clara de que son horas adicionales.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-24</td> 
    <td>Registrar cantidad de ganado enfermo</td>
    <td>Como trabajador, quiero registrar la cantidad de ganado enfermo, para tener información vital de la situación de cada animal.</td>
    <td>
        <b>Scenario 01:</b> Acceso al registro de ganado enfermo<br>
        <b>Dado</b> que soy un trabajador autenticado en el sistema<br>
        <b>Cuando</b> accedo a la función de registro de ganado enfermo<br>
        <b>Entonces</b> el sistema me muestra un formulario o interfaz para ingresar la cantidad de ganado enfermo.<br><br>
        <b>Scenario 02:</b> Registro de cantidad de ganado enfermo<br>
        <b>Dado</b> que estoy registrando la cantidad de ganado enfermo<br>
        <b>Cuando</b> ingreso el número de animales enfermos<br>
        <b>Entonces</b> el sistema registra esta información en el historial de salud del ganado, asociándola a la fecha y al tipo de enfermedad si es posible.<br><br>
        <b>Scenario 03:</b> Seguimiento de historial de salud<br>
        <b>Dado</b> que soy un trabajador<br>
        <b>Cuando</b> accedo al registro de salud del ganado<br>
        <b>Entonces</b> el sistema me muestra un historial de las cantidades de ganado enfermo registradas, permitiéndome realizar un seguimiento de la situación de salud del ganado a lo largo del tiempo.<br><br>
        <b>Scenario 04:</b> Alertas de emergencia por cantidad de ganado enfermo<br>
        <b>Dado</b> que el número de ganado enfermo excede un umbral crítico<br>
        <b>Cuando</b> se supera este umbral<br>
        <b>Entonces</b> el sistema emite una alerta de emergencia para notificar a los supervisores y tomar medidas correctivas inmediatas.<br><br>
        <b>Scenario 05:</b> Análisis de tendencias de salud del ganado<br>
        <b>Dado</b> que soy un trabajador o supervisor<br>
        <b>Cuando</b> accedo al análisis de salud del ganado<br>
        <b>Entonces</b> el sistema me muestra gráficos y estadísticas que resumen la salud del ganado a lo largo del tiempo, lo que me permite identificar patrones y tomar decisiones informadas para mejorar el bienestar del ganado.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-25</td> 
    <td>Acceso móvil desde cualquier área de la granja</td>
    <td>Como trabajador, quiero acceder a la aplicación desde cualquier área de la granja, para tener acceso rápido y conveniente a la información y funcionalidades necesarias para mi trabajo.</td>
    <td>
        <b>Scenario 01:</b> Acceso desde dispositivos móviles<br>
        <b>Dado</b> que soy un trabajador en la granja<br>
        <b>Cuando</b> necesito acceder a la aplicación<br>
        <b>Entonces</b> la aplicación debe ser accesible desde dispositivos móviles, como smartphones o tablets, permitiéndome llevarla conmigo mientras trabajo en diferentes áreas de la granja.<br><br>
        <b>Scenario 02:</b> Funcionalidades offline<br>
        <b>Dado</b> que trabajo en áreas con conexión limitada o nula<br>
        <b>Cuando</b> no tengo acceso a internet<br>
        <b>Entonces</b> la aplicación debe proporcionar funcionalidades offline que me permitan acceder a la información previamente cargada y registrar datos localmente, sincronizándolos automáticamente una vez que recupere la conexión.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-26</td> 
    <td>Verificar estado de actividades diarias y tiempo dedicado por los trabajadores</td>
    <td>Como dueño de la granja, quiero verificar el estado de las actividades diarias de los trabajadores y el tiempo dedicado a cada tarea, para gestionar eficazmente la asignación de tareas y el horario de trabajo.</td>
    <td>
        <b>Scenario 01:</b> Acceso al registro de actividades diarias<br>
        <b>Dado</b> que soy el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accedo al panel de control de actividades diarias de los trabajadores<br>
        <b>Entonces</b> el sistema me muestra un resumen de las actividades realizadas por los trabajadores durante el día.<br><br>
        <b>Scenario 02:</b> Visualización del tiempo dedicado a cada tarea<br>
        <b>Dado</b> que estoy revisando las actividades diarias de los trabajadores<br>
        <b>Cuando</b> selecciono una actividad específica<br>
        <b>Entonces</b> el sistema me muestra el tiempo dedicado por cada trabajador a esa tarea, detallando el inicio y finalización de la misma.<br><br>
        <b>Scenario 03:</b> Generación de informes de actividades diarias<br>
        <b>Dado</b> que soy el dueño de la granja<br>
        <b>Cuando</b> deseo generar un informe detallado de las actividades diarias de los trabajadores<br>
        <b>Entonces</b> el sistema me permite generar un informe completo que incluya información sobre todas las actividades realizadas, el tiempo dedicado y otros detalles relevantes para la gestión de recursos humanos.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-27</td> 
    <td>Generar informe detallado de producción y gestión de la granja</td>
    <td>Como dueño de la granja, quiero un informe detallado sobre la producción y la gestión de la granja, para garantizar el cumplimiento de los estándares de calidad y rentabilidad.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la generación de informes<br>
        <b>Dado</b> que soy el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accedo a la sección de informes de la aplicación<br>
        <b>Entonces</b> el sistema me muestra opciones para generar informes sobre la producción y gestión de la granja.<br><br>
        <b>Scenario 02:</b> Selección de parámetros del informe<br>
        <b>Dado</b> que estoy generando un informe<br>
        <b>Cuando</b> selecciono los parámetros del informe, como período de tiempo, tipo de producción, áreas específicas de la granja, etc.<br>
        <b>Entonces</b> el sistema utiliza estos parámetros para personalizar el informe de acuerdo a mis necesidades.<br><br>
        <b>Scenario 03:</b> Inclusión de datos de producción<br>
        <b>Dado</b> que estoy generando un informe<br>
        <b>Cuando</b> selecciono la opción de incluir datos de producción<br>
        <b>Entonces</b> el sistema agrega información detallada sobre la producción de cultivos, ganado, productos agrícolas, etc., incluyendo cantidades producidas, calidad, y otros datos relevantes.<br><br>
        <b>Scenario 04:</b> Análisis de gestión<br>
        <b>Dado</b> que estoy generando un informe<br>
        <b>Cuando</b> selecciono la opción de incluir datos de gestión<br>
        <b>Entonces</b> el sistema agrega información sobre la gestión de recursos humanos, finanzas, inventario, mantenimiento de equipos, y cualquier otra área relevante de la operación de la granja.<br><br>
        <b>Scenario 05:</b> Formato y presentación del informe<br>
        <b>Dado</b> que he seleccionado los parámetros del informe y la información a incluir<br>
        <b>Cuando</b> genero el informe<br>
        <b>Entonces</b> el sistema presenta el informe en un formato claro y fácil de entender, utilizando gráficos, tablas y texto descriptivo para resaltar los puntos clave sobre la producción y gestión de la granja.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-28</td> 
    <td>Establecer y seguir metas de producción a lo largo del tiempo</td>
    <td>Como dueño de la granja, quiero establecer metas de producción y seguirlas a lo largo del tiempo, para mantenerme enfocado en mejorar el rendimiento de mi granja.</td>
    <td>
        <b>Scenario 01:</b> Establecimiento de metas de producción<br>
        <b>Dado</b> que soy el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accedo a la sección de configuración de metas de producción<br>
        <b>Entonces</b> el sistema me permite establecer metas específicas de producción para diferentes aspectos de la granja, como cantidad de cultivos producidos, rendimiento del ganado, eficiencia del uso del agua, etc.<br><br>
        <b>Scenario 02:</b> Seguimiento de metas a lo largo del tiempo<br>
        <b>Dado</b> que he establecido metas de producción<br>
        <b>Cuando</b> accedo al panel de control de metas de producción<br>
        <b>Entonces</b> el sistema me muestra un seguimiento continuo del progreso hacia mis metas a lo largo del tiempo, utilizando gráficos y tablas que comparan los resultados reales con las metas establecidas.<br><br>
        <b>Scenario 03:</b> Alertas de desviación de metas<br>
        <b>Dado</b> que estoy siguiendo las metas de producción<br>
        <b>Cuando</b> los resultados reales se desvían significativamente de las metas establecidas<br>
        <b>Entonces</b> el sistema me envía alertas automáticas para notificarme sobre estas desviaciones, permitiéndome tomar medidas correctivas de manera oportuna.<br><br>
        <b>Scenario 04:</b> Flexibilidad para ajustar metas<br>
        <b>Dado</b> que estoy revisando el progreso hacia mis metas de producción<br>
        <b>Cuando</b> decido ajustar las metas debido a cambios en las condiciones del mercado, condiciones climáticas u otros factores<br>
        <b>Entonces</b> el sistema me permite modificar las metas de producción de manera flexible, manteniendo siempre el enfoque en mejorar el rendimiento de la granja.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-29</td> 
    <td>Acceso a la plataforma FarmLogiTech desde dispositivos móviles</td>
    <td>Como dueño de la granja, quiero acceder a la plataforma FarmLogiTech desde mi dispositivo móvil, para poder gestionar mi granja desde cualquier lugar.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la plataforma desde dispositivos móviles<br>
        <b>Dado</b> que soy el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accedo al sitio web o la aplicación móvil de FarmLogiTech<br>
        <b>Entonces</b> la plataforma debe ser completamente funcional y fácil de usar en dispositivos móviles, permitiéndome gestionar mi granja desde cualquier lugar con conexión a internet.<br><br>
        <b>Scenario 02:</b> Interfaz adaptada para dispositivos móviles<br>
        <b>Dado</b> que accedo a la plataforma desde un dispositivo móvil<br>
        <b>Cuando</b> utilizo la plataforma en una pantalla más pequeña<br>
        <b>Entonces</b> la plataforma debe tener una interfaz adaptada que sea fácil de usar y navegar en dispositivos móviles, con elementos y menús optimizados para pantallas táctiles.<br><br>
        <b>Scenario 03:</b> Funcionalidades completas en dispositivos móviles<br>
        <b>Dado</b> que accedo a la plataforma desde mi dispositivo móvil<br>
        <b>Cuando</b> realizo tareas de gestión de la granja, como revisar informes, asignar tareas, controlar inventario, etc.<br>
        <b>Entonces</b> la plataforma debe proporcionar todas las funcionalidades necesarias para realizar estas tareas de manera efectiva, sin limitaciones en la versión móvil.<br><br>
        <b>Scenario 04:</b> Seguridad de acceso<br>
        <b>Dado</b> que accedo a la plataforma desde mi dispositivo móvil<br>
        <b>Cuando</b> inicio sesión en la plataforma<br>
        <b>Entonces</b> la plataforma debe garantizar la seguridad de mi acceso mediante autenticación adecuada, como nombre de usuario y contraseña, o métodos biométricos si es compatible con el dispositivo móvil.<br><br>
        <b>Scenario 05:</b> Actualizaciones automáticas<br>
        <b>Dado</b> que utilizo la plataforma desde dispositivos móviles<br>
        <b>Cuando</b> la plataforma recibe actualizaciones o mejoras<br>
        <b>Entonces</b> estas actualizaciones deben aplicarse automáticamente en la versión móvil, garantizando que siempre tenga acceso a las últimas características y mejoras de seguridad.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-30</td> 
    <td>Crear API RESTful para acceder a datos agrícolas y ganaderos</td>
    <td>Como desarrollador, necesito crear una API RESTful para permitir que la plataforma web se comunique con el backend y acceda a los datos agrícolas y ganaderos de los usuarios.</td>
    <td>
        <b>Scenario 01:</b> Creación exitosa de la API RESTful<br>
        <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
        <b>Cuando</b> desarrollo la API RESTful<br>
        <b>Entonces</b> puedo acceder a los datos agrícolas y ganaderos de los usuarios a través de la plataforma .<br><br>
        <b>Scenario 02:</b> Error al crear la API RESTful<br>
         <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
         <b>Cuando</b> intento crear la API RESTful<br>
       <b>Entonces</b> se genera un mensaje de error indicando el problema específico, como la falta de permisos, problemas de configuración o errores de sintaxis en el código.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-31</td> 
    <td>Implementar medidas de seguridad robustas</td>
    <td>Como desarrollador, necesito implementar medidas de seguridad robustas, como autenticación de usuarios, para proteger la información confidencial de los agricultores en la plataforma.</td>
    <td>
        <b>Scenario 01:</b> Implementación exitosa de medidas de seguridad<br>
        <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
        <b>Cuando</b> implemento medidas de seguridad, incluida la autenticación de usuarios<br>
        <b>Entonces</b> la información confidencial de los agricultores está protegida contra accesos no autorizados.<br><br>
        <b>Scenario 02:</b> Error al implementar medidas de seguridad<br>
         <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
         <b>Cuando</b> intento implementar medidas de seguridad<br>
       <b>Entonces</b> se generan mensajes de error indicando problemas específicos, como fallas en la configuración de autenticación, vulnerabilidades de seguridad o errores en el código de protección de datos.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-32</td> 
    <td>Integrar funcionalidades de pronóstico meteorológico</td>
    <td>Como desarrollador, necesito integrar funcionalidades de pronóstico meteorológico en la plataforma, para proporcionar a los agricultores información actualizada sobre las condiciones climáticas en sus áreas.</td>
    <td>
        <b>Scenario 01:</b> Integración exitosa de pronóstico meteorológico<br>
        <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
        <b>Cuando</b> integro funcionalidades de pronóstico meteorológico mediante un API<br>
        <b>Entonces</b> los agricultores pueden acceder a información actualizada sobre las condiciones climáticas en sus áreas a través de la plataforma.<br><br>
        <b>Scenario 02:</b> Error al integrar pronóstico meteorológico<br>
         <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
         <b>Cuando</b> intento integrar funcionalidades de pronóstico meteorológico<br>
       <b>Entonces</b> se generan mensajes de error indicando problemas específicos, como falta de acceso a la API de pronóstico meteorológico, errores en la recopilación o procesamiento de datos meteorológicos, o problemas de visualización de la información en la plataforma.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-33</td> 
    <td>Crear una interfaz intuitiva y fácil de usar</td>
    <td>Como desarrollador, necesito crear una interfaz intuitiva y fácil de usar en la plataforma, para garantizar una experiencia de usuario positiva y aumentar la satisfacción del cliente.</td>
    <td>
        <b>Scenario 01:</b> Creación exitosa de interfaz intuitiva<br>
        <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
        <b>Cuando</b> diseño la interfaz de usuario<br>
        <b>Entonces</b> los usuarios pueden navegar fácilmente por la plataforma y acceder a las funcionalidades sin dificultad, lo que aumenta su satisfacción y la probabilidad de retención.<br><br>
        <b>Scenario 02:</b> Error al crear la interfaz intuitiva<br>
         <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
         <b>Cuando</b> intento diseñar la interfaz de usuario<br>
       <b>Entonces</b> se generan mensajes de error indicando problemas específicos, como diseño poco claro, navegación complicada, falta de consistencia en la interfaz o problemas de accesibilidad, lo que puede afectar negativamente la experiencia del usuario y la satisfacción del cliente.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-34</td> 
    <td>Garantizar la escalabilidad del sistema</td>
    <td>Como desarrollador, necesito garantizar la escalabilidad del sistema, para manejar un creciente número de usuarios y datos agrícolas sin comprometer el rendimiento.</td>
    <td>
        <b>Scenario 01:</b> Garantizar la escalabilidad exitosa del sistema<br>
        <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
        <b>Cuando</b> implemento medidas de escalabilidad, como la optimización de consultas a la base de datos, el uso de servidores escalables o la implementación de sistemas de almacenamiento distribuido<br>
        <b>Entonces</b> el sistema puede manejar un creciente número de usuarios y datos agrícolas sin comprometer el rendimiento.<br><br>
        <b>Scenario 02:</b> Error al garantizar la escalabilidad del sistema<br>
         <b>Dado</b> que soy un desarrollador trabajando en la plataforma <br>
         <b>Cuando</b> intento implementar medidas de escalabilidad<br>
       <b>Entonces</b> se generan mensajes de error indicando problemas específicos, como falta de recursos para escalar, problemas de configuración en los servidores, o falta de optimización en la gestión de datos, lo que puede resultar en una degradación del rendimiento del sistema ante un aumento de la carga.
    </td>
    <td>###</td> 
</tr>
<tr>
    <td>US-35</td> 
    <td>Establecer un sistema de soporte técnico y atención al cliente</td>
    <td>Como desarrollador, necesito establecer un sistema de soporte técnico y atención al cliente, para ayudar a los granjeros y empresarios con cualquier problema o pregunta relacionada con la plataforma.</td>
    <td>
        <b>Scenario 01:</b> Implementación exitosa del sistema de soporte técnico<br>
        <b>Dado</b> que soy un desarrollador trabajando en la plataforma web<br>
        <b>Cuando</b> establezco un sistema de soporte técnico, que incluya canales de comunicación como correo electrónico, chat en vivo o tickets de soporte<br>
        <b>Entonces</b> los granjeros y empresarios pueden obtener ayuda rápida y eficaz para resolver problemas o responder preguntas relacionadas con la plataforma.<br><br>
        <b>Scenario 02:</b> Error al establecer el sistema de soporte técnico<br>
         <b>Dado</b> que soy un desarrollador trabajando en la plataforma web<br>
         <b>Cuando</b> intento establecer el sistema de soporte técnico<br>
       <b>Entonces</b> se generan mensajes de error indicando problemas específicos, como falta de recursos para mantener el soporte, problemas de integración con herramientas de gestión de tickets o dificultades en la configuración de canales de comunicación, lo que puede afectar la experiencia del usuario y la satisfacción del cliente.
    </td>
    <td>###</td> 
</tr>
</table>



## 3.3 Impact Mapping

## 3.4 Product Backlog

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <th>
            # Orden
        </th>
        <th>
            User Story ID
        </th>
        <th>
            Título
        </th>
        <th>
            Descripción
        </th>
        <th>
            Story Points </br> (1 / 3 / 5 / 8)
        </th>
    </tr>
    <tr>
        <td>
            01
        </td>
        <td>
            US-10
        </td>
        <td>
            Crear y asignar tareas
        </td>
        <td>
            Como dueño de granja, quiero crear y asignar tareas a los trabajadores para mejorar la gestión de la mano de obra en mi finca.
        </td>
        <td>
            8
        </td>
    </tr>
    <tr>
        <td>
            02
        </td>
        <td>
            US-01
        </td>
        <td>
            Descripción clara de servicios en la landing page
        </td>
        <td>
            Como usuario potencial, quiero ver una descripción clara y concisa de los servicios ofrecidos en la landing page, para comprender rápidamente cómo pueden beneficiar a mi operación agrícola y ganadera.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            03
        </td>
        <td>
            US-04
        </td>
        <td>
            Identificación de características en la landing page
        </td>
        <td>
            Como usuario potencial, quiero identificar fácilmente en la landing page las características que me ayudarán a encontrar una granja ideal, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            04
        </td>
        <td>
            US-05
        </td>
        <td>
            Información de colaboradores en la landing page
        </td>
        <td>
            Como usuario potencial, quiero encontrar información sobre los colaboradores del proyecto en la landing page, para saber quiénes están detrás de la aplicación y qué experiencia tienen.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            05
        </td>
        <td>
            US-06
        </td>
        <td>
            Interacción con imágenes en la landing page
        </td>
        <td>
            Como usuario potencial, quiero interactuar con las imágenes de la landing page, para obtener más información o realizar acciones, como ampliarlas, verlas en una galería o acceder a una descripción.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            06
        </td>
        <td>
            US-13
        </td>
        <td>
            Búsqueda y contacto de granjas
        </td>
        <td>
            Como empresario, quiero buscar y contactar a dueños de granjas potenciales, para establecer asociaciones comerciales y mejorar nuestra cadena de suministro.
        </td>
        <td>
            8
        </td>
    </tr>
    <tr>
        <td>
            07
        </td>
        <td>
            US-18
        </td>
        <td>
            Verificación de inventario
        </td>
        <td>
            Como dueño de la granja, quiero verificar fácilmente los niveles de inventario de productos agrícolas y ganaderos, y recibir notificaciones cuando sea necesario reponerlos, para garantizar un flujo de trabajo ininterrumpido.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            08
        </td>
        <td>
            US-11
        </td>
        <td>
            Notificaciones de tareas asignadas
        </td>
        <td>
            Como trabajador, quiero recibir notificaciones sobre las tareas asignadas, para mantenerme informado sobre las indicaciones del superior.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            09
        </td>
        <td>
            US-09
        </td>
        <td>
            Elegir método de pago
        </td>
        <td>
            Como dueño de granja, quiero elegir entre diferentes métodos de pago, para pagar mi suscripción de la forma más cómoda y segura para mí.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            10
        </td>
        <td>
            US-03
        </td>
        <td>
            Adaptación de landing page a dispositivos
        </td>
        <td>
            Como usuario potencial, quiero que la landing page se adapte correctamente a la pantalla de mi dispositivo, para poder verla y usarla de forma cómoda, independientemente de si estoy usando un ordenador, una tablet o un teléfono móvil.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            11
        </td>
        <td>
            US-26
        </td>
        <td>
            Estado de actividades diarias de trabajadores
        </td>
        <td>
            Como dueño de la granja, quiero verificar el estado de las actividades diarias de los trabajadores y el tiempo dedicado a cada tarea, para gestionar eficazmente la asignación de tareas y el horario de trabajo.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            12
        </td>
        <td>
            US-24
        </td>
        <td>
            Registro de ganado enfermo
        </td>
        <td>
            Como trabajador, quiero registrar la cantidad de ganado enfermo, para tener información vital de la situación de cada animal.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            13
        </td>
        <td>
            US-07
        </td>
        <td>
            Apartado demostrativo de mejora de la eficiencia y rentabilidad de las granjas en la landing page
        </td>
        <td>
            Como usuario potencial, quiero encontrar fácilmente información en la landing page sobre cómo puedo mejorar la eficiencia y rentabilidad de mi granja utilizando la plataforma, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            14
        </td>
        <td>
            US-20
        </td>
        <td>
            Estadísticas financieras
        </td>
        <td>
            Como dueño de la granja, quiero saber estadísticas financieras, para poder administrar correctamente la economía de mi granja.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            15
        </td>
        <td>
            US-17
        </td>
        <td>
            Alertas automáticas de cambios climáticos
        </td>
        <td>
            Como trabajador, quiero recibir alertas automáticas sobre cambios climáticos significativos que puedan afectar mis cultivos, para poder tomar medidas preventivas y proteger mis cosechas.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            16
        </td>
        <td>
            US-08
        </td>
        <td>
            Apartado explicativo de control de costos y maximización de ingresos en la landing page
        </td>
        <td>
            Como usuario potencial, quiero entender en la landing page cómo la plataforma puede ayudarme a controlar los costos y maximizar los ingresos de mi granja, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            18
        </td>
        <td>
            US-12
        </td>
        <td>
            Registro de progreso de tareas
        </td>
        <td>
            Como trabajador, quiero registrar el progreso de mis tareas, para mantenerme organizado y productivo.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            19
        </td>
        <td>
            US-23
        </td>
        <td>
            Registro de horas de trabajo
        </td>
        <td>
            Como trabajador, quiero registrar mis horas de trabajo, para saber mi salario en función a ello.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            20
        </td>
        <td>
            US-22
        </td>
        <td>
            Alertas de emergencia
        </td>
        <td>
            Como trabajador en la granja, quiero emitir alertas sobre cualquier emergencia a mis colegas y supervisores de manera eficaz e inmediata.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            21
        </td>
        <td>
            US-29
        </td>
        <td>
            Acceso móvil a la plataforma
        </td>
        <td>
            Como dueño de la granja, quiero acceder a la plataforma FarmLogiTech desde mi dispositivo móvil, para poder gestionar mi granja desde cualquier lugar.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            22
        </td>
        <td>
            US-30
        </td>
        <td>
            API RESTful
        </td>
        <td>
            Como desarrollador, necesito crear una API RESTful, para permitir que la plataforma web se comunique con el backend y acceda a los datos agrícolas y ganaderos de los usuarios.
        </td>
        <td>
            8
        </td>
    </tr>
    <tr>
        <td>
            23
        </td>
        <td>
            US-31
        </td>
        <td>
            Seguridad robusta
        </td>
        <td>
            Como desarrollador, necesito implementar medidas de seguridad robustas, como autenticación de usuarios, para proteger la información confidencial de los agricultores en la plataforma.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            24
        </td>
        <td>
            US-32
        </td>
        <td>
            Integración de pronóstico meteorológico
        </td>
        <td>
            Como desarrollador, necesito integrar funcionalidades de pronóstico meteorológico en la plataforma, para proporcionar a los agricultores información actualizada sobre las condiciones climáticas en sus áreas.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            25
        </td>
        <td>
            US-33
        </td>
        <td>
            Interfaz intuitiva y fácil de usar
        </td>
        <td>
            Como desarrollador, necesito crear una interfaz intuitiva y fácil de usar en la plataforma, para garantizar una experiencia de usuario positiva y aumentar la satisfacción del cliente.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            26
        </td>
        <td>
            US-34
        </td>
        <td>
            Escalabilidad del sistema
        </td>
        <td>
            Como desarrollador, necesito garantizar la escalabilidad del sistema, para manejar un creciente número de usuarios y datos agrícolas sin comprometer el rendimiento.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            27
        </td>
        <td>
            US-27
        </td>
        <td>
            Informe detallado sobre la producción
        </td>
        <td>
            Como dueño de la granja, quiero un informe detallado sobre la producción y la gestión de la granja, para garantizar el cumplimiento de los estándares de calidad y rentabilidad.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            28
        </td>
        <td>
            US-28
        </td>
        <td>
            Establecimiento de metas de producción
        </td>
        <td>
            Como dueño de la granja, quiero establecer metas de producción y seguirlas a lo largo del tiempo, para mantenerme enfocado en mejorar el rendimiento de mi granja.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            29
        </td>
        <td>
            US-35
        </td>
        <td>
            Soporte técnico y atención al cliente
        </td>
        <td>
            Como desarrollador, necesito establecer un sistema de soporte técnico y atención al cliente, para ayudar a los granjeros y empresarios con cualquier problema o pregunta relacionada con la plataforma.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            30
        </td>
        <td>
            US-21
        </td>
        <td>
            Registro de cumplimiento de tareas
        </td>
        <td>
            Como trabajador en la granja, quiero registrar el cumplimiento de mis tareas con detalles como la cantidad, calidad y fecha de cosecha, para mantener un registro preciso de la producción de la granja.
        </td>
        <td>
            3
        </td>
    </tr>
     <tr>
        <td>
            31
        </td>
        <td>
            US-19
        </td>
        <td>
            Estado de cultivos y ganado
        </td>
        <td>
            Como dueño de la granja, quiero saber información detallada sobre el estado de mis cultivos y ganado, para poder administrarla de manera rápida e informada.
        </td>
        <td>
            3
        </td>
    </tr>
     <tr>
        <td>
            32
        </td>
        <td>
            US-15
        </td>
        <td>
            Filtros de busqueda de granjas
        </td>
        <td>
             Como empresario, quiero buscar granjas con filtros en específico, para encontrar fácilmente una granja que se adapte a mis necesidades.
        </td>
        <td>
            3
        </td>
    </tr>
     <tr>
        <td>
            33
        </td>
        <td>
            US-16
        </td>
        <td>
            Valoraciones y comentarios de granjas
        </td>
        <td>
            Como empresario, quiero acceder a las valoraciones y comentarios de otros empresarios sobre las granjas, para tomar decisiones informadas y sentirme seguro al realizar negocios con ellas.
        </td>
        <td>
            1
        </td>
    </tr>
     <tr>
        <td>
            34
        </td>
        <td>
            US-14
        </td>
        <td>
            Información detallada de las granjas
        </td>
        <td>
           Como empresario, quiero ver información detallada de las granjas, para poder elegir una adecuada para mi idea de negocio.
        </td>
        <td>
            1
        </td>
    </tr>
     <tr>
        <td>
            35
        </td>
        <td>
            US-02
        </td>
        <td>
            Planes de suscripción en la landing page
        </td>
        <td>
           Como usuario potencial, quiero encontrar fácilmente los precios y planes de suscripción disponibles en la landing page, para evaluar la viabilidad económica de utilizar la plataforma en mi granja.
        </td>
        <td>
            1
        </td>
    </tr>
</table>

