# CAPITULO III: Requirements Specifications

## 3.1 To-Be Scenario Mapping
![Imagen de Granjero To-Be Scenario Mapping](https://i.postimg.cc/RhwZqJDK/To-Be-Scenary-Mapping-Due-o-de-la-granja.jpg)
![Imagen de Trabajador To-Be Scenario Mapping](https://i.postimg.cc/wTdBZF1V/To-Be-Scenary-Mapping-Trabajador.jpg)
![Imagen de Empresario To-Be Scenario Mapping](https://i.postimg.cc/tR6TB84J/To-Be-Scenary-Mapping-Empresario.jpg)

## 3.2 User Stories

| Epic / Story ID 	    | Título 	                                                 | Descripción 	                                                                                                                                                                                                    | Criterios de Aceptación 	 | Relacionado con Epic ID 	|
|----------------------|----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|-----------------------	|
| EP01               	 | Información de la aplicación      	                      | **Como** visitante del landing page **Quiero** obtener información relacionada a la aplicación **Para** conocer los beneficios que obtendré al usarlo                                                            | No Corresponde | No Corresponde|
| EP02               	 | Vinculo entre el landing page y la aplicación web      	 | **Como** visitante del landing page **Quiero** poder ingresar a la aplicación web **Para** probar la aplicación de FarmLogitech                                                                                  | No Corresponde  |No Corresponde|
| EP03               	 | Crear tareas       	                                     | **Como** dueño de una granja **Quiero** poder crear y asignar tareas a mis trabajadores **Para** que estos tengan conocimiento de lo que deben realizar en tiempo real                                           | No Corresponde  | No Corresponde|
| EP04               	 | Gestionar empleados       	                              | **Como** dueño de una granja **Quiero** poder crear y visualizar a mis trabajadores **Para** que tener conocimiento de con cuantos trabajadores cuento y se debo añadir alguno                                   | No Corresponde | No Corresponde|
| EP05               	 | Visualizar datos estadísticos       	                    | **Como** dueño de una granja **Quiero** poder  visualizar mis datos estadísticos **Para** tener conocimiento de mis ganancias anules o mensuales, animales enfermos y cumplimiento de tareas                     | No Corresponde |No Corresponde|
| EP06               	 | Gestionar emergencias       	                            | **Como** dueño de una granja **Quiero** poder crear emergencias **Para** que mis trabajadores sepan cuando hay una tarea que debe ser realizada en ese mismo momento                                             | No Corresponde| No Corresponde|
| EP07               	 | Gestionar el inventario                                  | **Como** dueño de una granja **Quiero** poder agregar semillas, cultivos y animales a mi inventario **Para** poder revisar si faltan semillas, cultivos o animales y de esa manera buscar mejorar la productividad |No Corresponde| No Corresponde|
| EP08               	 | Publicar anuncio de la granja       	                    | **Como** dueño de una granja **Quiero** publicar un anuncio de mi granja **Para** que empresarios interesados en establecer un alianza estrátegica se contacten conmigo                                          | No Corresponde| No Corresponde	|
| EP09               	 | Visualizar anuncios de granja                            | **Como** dueño de una empresa **Quiero** visualizar anuncios de granjas **Para** poder establecer una alianza estrátegica con una granja que se ajuste a la visión de mi empresa                                 | No Corresponde| No Corresponde|
| EP10               	 | Contactar granja       	                                 | **Como** dueño de una granja **Quiero** contactar a la granja en la que estoy interesado **Para** llegar a un acuerdo y establecer una alianza                                                                   | No Corresponde|No Corresponde|
| EP11               	 | Calificar granja    	                                    | **Como** dueño de una granja **Quiero** poner una calificación a la granja con la que trabajé **Para** que otros empresarios tengan una referencia del trabajo de la granja                                      | No Corresponde | No Corresponde|
| EP12               	 | Visualizar tareas                                        | **Como** trabajador de una granja **Quiero** visualizar las tareas que me asigno el dueño de la granja **Para** poder realizar las tareas del día                                                                | No Corresponde| No Corresponde|
| EP13               	 | Visualizar el pronostico climático                       | **Como** trabajador de una granja **Quiero** visualizar el pronostico meteorologico **Para** preparar a los animales o cultivos de acuerdo al posible estado del clima                                           | No Corresponde| No Corresponde|
| EP14               	 | Visualizar emergencias                                   | **Como** trabajador de una granja **Quiero** visualizar las emergencias **Para** poder solucionar las emergencias problemas rapidamente          	                                                               | No Corresponde| No Corresponde|
| EP15               	 | Modificar el inventario                                  | **Como** trabajador de una granja **Quiero** modificar el inventario **Para** que mis compañeros y el dueño de la granja esten al tanto del inventario        	                                                  | No Corresponde| No Corresponde|
| EP16               	 | Gestionar cuentas                                        | **Como** trabajador de una granja **Quiero** tener la capacidad de crear una cuenta **Para** comenzar a gestionar los procesos de mi granjas y concretar futuras alianzas estrategicas        	                  | No Corresponde| No Corresponde|

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
    <td>Como visitante, quiero ver una descripción clara y concisa de los servicios ofrecidos en la landing page, para comprender rápidamente cómo pueden beneficiar a mi operación agrícola o ganadera.</td>
    <td>
        <b>Scenario 01:</b> Contactar a los desarrolladores<br>
        <b>Dado</b> que el visitante tiene una consulta <br>
        <b>Cuando</b> redacte un mensaje y su correo electronico para contactar a los desarrolladores<br>
        <b>Entonces</b> el mensaje le llegara a los desarrolladores.<br><br>
    </td>
    <td>EP01</td> 
</tr>
<tr>
    <td>US-02</td> 
    <td>Vinculo entre el Landing Page y la Aplicación Web</td>
    <td>Como visitante interesado en la aplicación, quiero probar la aplicación web desde la Landing Page.</td>
    <td>
        <b>Scenario 01:</b> El visitante ingresa a la aplicación<br>
        <b>Dado</b> que el visitante desea usar la aplicación<br>
        <b>Cuando</b> ingrese a la landing page y encuentre el botón para acceder a la aplicación. <br>
        <b>Entonces</b> el visitante será redirigido a la aplicación web y podrá convertirse en nuestro usuario.<br><br>
   </td>
    <td>EP02</td> 
</tr>



<tr>
    <td>US-10</td> 
    <td>Crear y asignar tareas a los trabajadores</td>
    <td>Como dueño de granja, quiere crear y asignar tareas a los trabajadores, para mejorar la gestión de la mano de obra en su finca.</td>
    <td>
        <b>Scenario 01:</b> Creación de nueva tarea exitosa<br>
        <b>Dado</b> que es el dueño de la granja y está autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de gestión de tareas<br>
        <b>Entonces</b> el sistema le permite crear una nueva tarea especificando detalles como nombre, descripción, fecha límite, y asignarla a uno o varios trabajadores.<br><br>
        <b>Scenario 02:</b> Falla en la creación de nueva tarea<br>
        <b>Dado</b> que es el dueño de la granja y está autenticado en el sistema<br>
        <b>Cuando</b> está creando una tarea y completa algún detalle con un valor inválido<br>
        <b>Entonces</b> el sistema muestra un mensaje de error e indica cuál es el problema.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-11</td> 
    <td>Recibir notificaciones sobre tareas asignadas</td>
    <td>Como trabajador, quiere recibir notificaciones sobre las tareas asignadas, para mantenerse informado sobre las indicaciones del superior.</td>
    <td>
        <b>Scenario 01:</b> Recepción de notificación al asignar una tarea<br>
        <b>Dado</b> que es un trabajador registrado en el sistema<br>
        <b>Cuando</b> el superior asigna una nueva tarea a él<br>
        <b>Entonces</b> el sistema le envía una notificación instantánea con los detalles de la tarea asignada.<br><br>
        <b>Scenario 02:</b> Notificación de recordatorio de tarea pendiente<br>
        <b>Dado</b> que es un trabajador con una tarea pendiente<br>
        <b>Cuando</b> la fecha límite de la tarea se acerca o ha pasado<br>
        <b>Entonces</b> el sistema le envía una notificación recordándole la tarea pendiente y la fecha límite.<br><br>
        <b>Scenario 03:</b> Acceso a notificaciones en la aplicación<br>
        <b>Dado</b> que es un trabajador que ha recibido notificaciones<br>
        <b>Cuando</b> accede a la aplicación móvil o al sitio web<br>
        <b>Entonces</b> el sistema le muestra una lista de todas las notificaciones recibidas, permitiéndole revisarlas en cualquier momento.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-12</td> 
    <td>Registrar progreso de tareas</td>
    <td>Como trabajador, quiere registrar el progreso de sus tareas, para mantenerse organizado y productivo.</td>
    <td>
        <b>Scenario 01:</b> Actualizar estado de tarea a "En progreso"<br>
        <b>Dado</b> que es un trabajador y tiene una tarea asignada<br>
        <b>Cuando</b> comienza a trabajar en la tarea<br>
        <b>Entonces</b> el sistema le permite actualizar el estado de la tarea a "En progreso", indicando que está trabajando en ella.<br><br>
        <b>Scenario 02:</b> Registrar avance de tarea<br>
        <b>Dado</b> que es un trabajador y está trabajando en una tarea<br>
        <b>Cuando</b> avanza en la tarea y alcanza un hito significativo<br>
        <b>Entonces</b> el sistema le permite registrar su avance, como porcentaje completado o hitos alcanzados, y actualiza el estado de la tarea en consecuencia.<br><br>
        <b>Scenario 03:</b> Marcar tarea como completada<br>
        <b>Dado</b> que es un trabajador y ha finalizado una tarea<br>
        <b>Cuando</b> completa todos los requerimientos de la tarea<br>
        <b>Entonces</b> el sistema le permite marcar la tarea como completada, actualizando su estado y notificando al superior.<br><br>
        <b>Scenario 04:</b> Registro de tiempo dedicado a la tarea<br>
        <b>Dado</b> que es un trabajador y quiere registrar el tiempo dedicado a una tarea<br>
        <b>Cuando</b> completa la tarea o necesita reportar el tiempo dedicado<br>
        <b>Entonces</b> el sistema le permite ingresar el tiempo dedicado y lo registra en la tarea correspondiente.<br><br>
        <b>Scenario 05:</b> Acceso al historial de progreso de tareas<br>
        <b>Dado</b> que es un trabajador<br>
        <b>Cuando</b> accede a su panel de tareas asignadas<br>
        <b>Entonces</b> el sistema le muestra un historial detallado de progreso de cada tarea, incluyendo las actualizaciones de estado y los tiempos dedicados.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-13</td> 
    <td>Buscar y contactar a dueños de granjas potenciales</td>
    <td>Como empresario, quiere buscar y contactar a dueños de granjas potenciales, para establecer asociaciones comerciales y mejorar su cadena de suministro.</td>
    <td>
        <b>Scenario 01:</b> Búsqueda de dueños de granjas potenciales<br>
        <b>Dado</b> que es un empresario autenticado en el sistema<br>
        <b>Cuando</b> accede a la función de búsqueda<br>
        <b>Entonces</b> el sistema le permite buscar dueños de granjas potenciales utilizando criterios como ubicación, tipo de cultivo, tamaño de la granja, etc.<br><br>
        <b>Scenario 02:</b> Visualización de resultados de búsqueda<br>
        <b>Dado</b> que ha realizado una búsqueda de dueños de granjas potenciales<br>
        <b>Cuando</b> el sistema encuentra coincidencias<br>
        <b>Entonces</b> el sistema le muestra una lista de resultados de búsqueda que coinciden con sus criterios, incluyendo detalles de contacto como correo electrónico, número de teléfono, etc.<br><br>
        <b>Scenario 03:</b> Contacto con dueños de granjas potenciales<br>
        <b>Dado</b> que ha encontrado un dueño de granja potencial con el que desea establecer una asociación comercial<br>
        <b>Cuando</b> selecciona el perfil del dueño de la granja<br>
        <b>Entonces</b> el sistema le muestra opciones para contactarlo, como enviar un correo electrónico directamente desde la plataforma o acceder a su información de contacto para hacer una llamada.<br><br>
        <b>Scenario 04:</b> Registro de interacciones<br>
        <b>Dado</b> que ha contactado a un dueño de granja potencial<br>
        <b>Cuando</b> realiza una interacción, como enviar un correo electrónico o hacer una llamada<br>
        <b>Entonces</b> el sistema registra la interacción y la asocia con el perfil del dueño de la granja, permitiéndole hacer un seguimiento de las comunicaciones realizadas.
    </td> 
    <td>###</td> 
</tr>
<tr>
    <td>US-14</td> 
    <td>Ver información detallada de las granjas</td>
    <td>Como empresario, quiere ver información detallada de las granjas, para poder elegir una adecuada para su idea de negocio.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la lista de granjas<br>
        <b>Dado</b> que es un empresario autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de granjas disponibles<br>
        <b>Entonces</b> el sistema le muestra una lista de granjas disponibles para explorar.<br><br>
        <b>Scenario 02:</b> Visualización de detalles de granja<br>
        <b>Dado</b> que está viendo la lista de granjas<br>
        <b>Cuando</b> selecciona una granja específica<br>
        <b>Entonces</b> el sistema le muestra información detallada de la granja, incluyendo ubicación, tamaño, tipo de cultivos, infraestructura, historial de producción, etc.<br><br>
        <b>Scenario 03:</b> Exploración de fotos y videos de la granja<br>
        <b>Dado</b> que está viendo los detalles de una granja<br>
        <b>Cuando</b> accede a la galería de medios<br>
        <b>Entonces</b> el sistema le muestra fotos y videos de la granja, permitiéndole explorar visualmente las instalaciones y condiciones.<br><br>
        <b>Scenario 04:</b> Guardar granjas como favoritas<br>
        <b>Dado</b> que es un empresario interesado en varias granjas<br>
        <b>Cuando</b> encuentra una granja que le interesa<br>
        <b>Entonces</b> el sistema le permite guardar la granja como favorita para poder acceder a ella fácilmente en el futuro.<br><br>
    </td>
    <td>###</td>
<tr>
    <td>US-15</td> 
    <td>Buscar granjas con filtros específicos</td>
    <td>Como empresario, quiere buscar granjas con filtros específicos, para encontrar fácilmente una granja que se adapte a sus necesidades.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la función de búsqueda avanzada<br>
        <b>Dado</b> que es un empresario autenticado en el sistema<br>
        <b>Cuando</b> accede a la función de búsqueda avanzada<br>
        <b>Entonces</b> el sistema le permite utilizar filtros específicos para refinar su búsqueda de granjas.<br><br>
        <b>Scenario 02:</b> Filtro por ubicación<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de ubicación, como ciudad o región<br>
        <b>Entonces</b> el sistema muestra solo las granjas ubicadas en la ubicación especificada.<br><br>
        <b>Scenario 03:</b> Filtro por tipo de cultivo<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de tipo de cultivo, como frutas, verduras, cereales, etc.<br>
        <b>Entonces</b> el sistema muestra solo las granjas que cultivan el tipo de cultivo especificado.<br><br>
        <b>Scenario 04:</b> Filtro por tamaño de la granja<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de tamaño de la granja, como pequeña, mediana o grande<br>
        <b>Entonces</b> el sistema muestra solo las granjas que se ajustan al tamaño especificado.<br><br>
        <b>Scenario 05:</b> Filtro por infraestructura<br>
        <b>Dado</b> que está utilizando la búsqueda avanzada<br>
        <b>Cuando</b> selecciona un filtro de infraestructura, como invernaderos, sistemas de riego, almacenes, etc.<br>
        <b>Entonces</b> el sistema muestra solo las granjas que cuentan con la infraestructura especificada.
    </td> 
    <td>###</td> 
</tr>

POR ARREGLAR
<tr>
    <td>US-17</td> 
    <td>Ver cambios climáticos de la semana</td>
    <td>Como trabajador, quiere ver los cambios climáticos de la semana, para poder planificar las actividades agrícolas y tomar medidas preventivas si es necesario.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la sección de cambios climáticos<br>
        <b>Dado</b> que un trabajador está autenticado en el sistema<br>
        <b>Cuando</b> accede a la sección de cambios climáticos<br>
        <b>Entonces</b> el sistema le muestra el pronóstico climático detallado para la semana, incluyendo temperatura, precipitación, humedad y otras variables relevantes.<br><br>
        <b>Scenario 02:</b> Información detallada de cambios climáticos<br>
        <b>Dado</b> que un trabajador está viendo el pronóstico climático semanal<br>
        <b>Cuando</b> selecciona un día específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre los cambios climáticos previstos para ese día, incluyendo alertas sobre condiciones extremas si las hay.<br><br>
        <b>Scenario 03:</b> Notificaciones de cambios climáticos<br>
        <b>Dado</b> que un trabajador<br>
        <b>Cuando</b> hay un cambio climático significativo que puede afectar sus actividades agrícolas<br>
        <b>Entonces</b> el sistema le envía una notificación instantánea con detalles sobre el cambio climático y recomendaciones sobre las medidas preventivas que debe tomar.<br><br>
        <b>Scenario 04:</b> Historial de cambios climáticos<br>
        <b>Dado</b> que un trabajador<br>
        <b>Cuando</b> accede a la sección de cambios climáticos<br>
        <b>Entonces</b> el sistema le muestra un historial de los cambios climáticos de semanas anteriores, permitiéndole analizar patrones y tendencias climáticas.
    </td> 
    <td>###</td> 
</tr>

<tr>
    <td>US-18</td> 
    <td>Verificar niveles de inventario</td>
    <td>Como dueño de la granja, quiere verificar fácilmente los niveles de inventario de productos agrícolas y ganaderos.</td>
    <td>
        <b>Scenario 01:</b> Acceso a los niveles de inventario<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control de inventario<br>
        <b>Entonces</b> el sistema le muestra una lista de productos agrícolas y ganaderos con sus respectivos niveles de inventario.<br><br>
        <b>Scenario 02:</b> Visualización detallada de inventario<br>
        <b>Dado</b> que está viendo los niveles de inventario<br>
        <b>Cuando</b> selecciona un producto específico<br>
        <b>Entonces</b> el sistema le muestra detalles adicionales del producto, como fecha de caducidad, ubicación de almacenamiento, etc.<br><br>
        <b>Scenario 03:</b> Registro de reposición de inventario<br>
        <b>Dado</b> que necesita reabastecer un producto<br>
        <b>Cuando</b> realiza el pedido o reabastecimiento del producto<br>
        <b>Entonces</b> el sistema registra la reposición de inventario y actualiza los niveles correspondientes en la base de datos.
    </td> 
    <td>###</td> 
</tr>

<tr>
    <td>US-19</td> 
    <td>Ver información detallada sobre el estado de cultivos y ganado</td>
    <td>Como dueño de la granja, quiere saber información detallada sobre el estado de sus cultivos y ganado, para poder administrarlos de manera rápida e informada.</td>
    <td>
        <b>Scenario 01:</b> Acceso a la información detallada<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control de cultivos y ganado<br>
        <b>Entonces</b> el sistema le muestra una lista de todos sus cultivos y ganado con su información detallada.<br><br>
        <b>Scenario 02:</b> Visualización de detalles de cultivos<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> selecciona un cultivo específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre el cultivo, como fecha de siembra, variedades, estado de crecimiento, necesidades de riego y fertilización, etc.<br><br>
        <b>Scenario 03:</b> Visualización de detalles de ganado<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> selecciona un animal o grupo de animales específico<br>
        <b>Entonces</b> el sistema le muestra información detallada sobre el ganado, como edad, raza, historial de salud, dieta, y cualquier otro detalle relevante.<br><br>
        <b>Scenario 04:</b> Seguimiento de cambios en el estado<br>
        <b>Dado</b> que está viendo la información detallada<br>
        <b>Cuando</b> los cultivos o el ganado experimentan cambios en su estado, como crecimiento, enfermedad, o reproducción<br>
        <b>Entonces</b> el sistema actualiza automáticamente la información mostrada para reflejar los cambios recientes.
    </td> 
    <td>###</td> 
</tr>

<tr>
    <td>US-20</td> 
    <td>Ver estadísticas financieras</td>
    <td>Como dueño de la granja, quiere saber estadísticas financieras, para poder administrar correctamente la economía de su granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso a las estadísticas financieras<br>
        <b>Dado</b> que es el dueño de la granja autenticado en el sistema<br>
        <b>Cuando</b> accede al panel de control financiero<br>
        <b>Entonces</b> el sistema le muestra una variedad de estadísticas financieras relevantes para su granja.<br><br>
        <b>Scenario 02:</b> Visualización de ingresos y gastos<br>
        <b>Dado</b> que está viendo las estadísticas financieras<br>
        <b>Cuando</b> revisa la sección de ingresos y gastos<br>
        <b>Entonces</b> el sistema le muestra un desglose detallado de los ingresos y gastos de su granja, clasificados por categoría y período de tiempo.<br><br>
        <b>Scenario 03:</b> Análisis de rentabilidad<br>
        <b>Dado</b> que está viendo las estadísticas financieras<br>
        <b>Cuando</b> revisa la sección de análisis de rentabilidad<br>
        <b>Entonces</b> el sistema le muestra métricas y gráficos que le ayudan a evaluar la rentabilidad de su granja, como margen de beneficio, retorno sobre la inversión, etc.
    </td> 
    <td>###</td> 
</tr>

<tr>
    <td>US-21</td> 
    <td>Registrar el cumplimiento de tareas con detalles de producción</td>
    <td>Como trabajador en la granja, quiere registrar el cumplimiento de sus tareas con detalles como la cantidad, calidad y fecha de cosecha, para mantener un registro preciso de la producción de la granja.</td>
    <td>
        <b>Scenario 01:</b> Acceso al registro de cumplimiento de tareas<br>
        <b>Dado</b> que es un trabajador autenticado en el sistema<br>
        <b>Cuando</b> accede a su panel de control de tareas<br>
        <b>Entonces</b> el sistema le muestra una lista de tareas asignadas y un formulario para registrar el cumplimiento de las mismas.<br><br>
        <b>Scenario 02:</b> Registro de detalles de producción<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea<br>
        <b>Cuando</b> ingresa los detalles de producción, como cantidad cosechada, calidad del producto, fecha de cosecha, etc.<br>
        <b>Entonces</b> el sistema registra estos detalles junto con la tarea cumplida.<br><br>
        <b>Scenario 03:</b> Registro de calidad del producto<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea relacionada con la producción<br>
        <b>Cuando</b> ingresa la calidad del producto, como grado de madurez, tamaño, estado de frescura, etc.<br>
        <b>Entonces</b> el sistema registra esta información para proporcionar un registro detallado de la calidad de la producción.<br><br>
        <b>Scenario 04:</b> Seguimiento de fechas de cosecha<br>
        <b>Dado</b> que está registrando el cumplimiento de una tarea de cosecha<br>
        <b>Cuando</b> ingresa la fecha de cosecha<br>
        <b>Entonces</b> el sistema registra la fecha de cosecha junto con los demás detalles de producción.<br><br>
        <b>Scenario 05:</b> Revisión y edición de registros<br>
        <b>Dado</b> que es un trabajador y desea revisar o editar registros de cumplimiento de tareas anteriores<br>
        <b>Cuando</b> accede al historial de registros de cumplimiento de tareas<br>
        <b>Entonces</b> el sistema le permite ver y editar los detalles registrados previamente, manteniendo un registro preciso y actualizado de la producción de la granja.
    </td> 
    <td>###</td> 
</tr>

<tr>
    <td>US-22</td> 
    <td>Emitir alertas de emergencia de manera eficaz</td>
    <td>Como trabajador en la granja, quiere emitir alertas sobre cualquier emergencia a sus colegas y supervisores de manera eficaz e inmediata.</td>
    <td>
        <b>Scenario 01:</b> Acceso rápido a la función de alerta de emergencia<br>
        <b>Dado</b> que es un trabajador en la granja<br>
        <b>Cuando</b> se encuentra en una situación de emergencia<br>
        <b>Entonces</b> quiere acceder rápidamente a la función de alerta de emergencia en la aplicación o dispositivo proporcionado.<br><br>
        <b>Scenario 02:</b> Selección del tipo de emergencia<br>
        <b>Dado</b> que está emitiendo una alerta de emergencia<br>
        <b>Cuando</b> selecciona el tipo de emergencia que está enfrentando, como incendio, accidente, lesión, etc.<br>
        <b>Entonces</b> el sistema registra el tipo de emergencia para una respuesta adecuada.<br><br>
        <b>Scenario 03:</b> Notificación a colegas y supervisores<br>
        <b>Dado</b> que emite una alerta de emergencia<br>
        <b>Cuando</b> envía la alerta<br>
        <b>Entonces</b> el sistema notifica automáticamente a sus colegas y supervisores designados sobre la emergencia, utilizando métodos como notificaciones push, mensajes de texto o llamadas de voz.<br><br>
        <b>Scenario 04:</b> Inclusión de detalles adicionales<br>
        <b>Dado</b> que está emitiendo una alerta de emergencia<br>
        <b>Cuando</b> necesita proporcionar detalles adicionales, como ubicación exacta, número de personas involucradas, gravedad de la situación, etc.<br>
        <b>Entonces</b> el sistema le permite incluir esta información para una mejor comprensión de la emergencia.<br><br>
        <b>Scenario 05:</b> Confirmación de recepción de alerta<br>
        <b>Dado</b> que emite una alerta de emergencia<br>
        <b>Cuando</b> sus colegas y supervisores reciben la alerta<br>
        <b>Entonces</b> el sistema muestra una confirmación de recepción para garantizar que la alerta haya sido recibida y comprendida.
    </td> 
    <td>###</td> 
</tr>






## 3.3 Impact Mapping
Impact Mapping (Dueño de granja y Empresario):
![Imagen de Impact Mapping - Dueño de granja y Empresario](https://i.postimg.cc/T1NTHjFV/Impact-Mapping-Due-o-de-granja-y-Empresario.jpg)

Impact Mapping (Trabajador):
![Imagen de Impact Mapping - Trabajador](https://i.postimg.cc/NFjg4CJG/Impact-Mapping-Trabajador.jpg)


## 3.4 Product Backlog

Product Backlog en Pivotal Tracker: 
https://www.pivotaltracker.com/n/projects/2700504

Presentación de nuestras 5 Epics y 35 User Stories en la herramienta.
![Imagen de Epics y Users en Pivotal Tracker](https://i.postimg.cc/mZ03K3w2/Users-y-epics-1.png)

Visualización de las User Stories seleccionadas para nuestro sprint 1 y ya implementadas por los miembros del equipo.
![Imagen de Users Stories seleccionadas para el sprint 1](https://i.postimg.cc/Y0Wm3VLK/Current-Backlog-Sprint1.png)
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
            3
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
            Como visitante, quiero ver una descripción clara y concisa de los servicios ofrecidos en la landing page, para comprender rápidamente cómo pueden beneficiar a mi operación agrícola y ganadera.
        </td>
        <td>
            1
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
            Como visitante del segmento empresarial, quiero identificar fácilmente en la landing page las características que me ayudarán a encontrar una granja ideal, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            1
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
            Como visitante, quiero encontrar información sobre los colaboradores del proyecto en la landing page, para saber quiénes están detrás de la aplicación y qué experiencia tienen.
        </td>
        <td>
            1
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
            Como visitante, quiero interactuar con las imágenes de la landing page, para obtener más información o realizar acciones, como ampliarlas, verlas en una galería o acceder a una descripción.
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
            3
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
            Como dueño de la granja, quiero verificar fácilmente los niveles de inventario de productos agrícolas y ganaderos.
        </td>
        <td>
            3
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
            5
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
            Como visitante, quiero que la landing page se adapte correctamente a la pantalla de mi dispositivo, para poder verla y usarla de forma cómoda, independientemente de si estoy usando un ordenador, una tablet o un teléfono móvil.
        </td>
        <td>
            1
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
            Como visitante del segmento agropecuario, quiero encontrar fácilmente información en la landing page sobre cómo puedo mejorar la eficiencia y rentabilidad de mi granja utilizando la plataforma, para evaluar la efectividad de la aplicación.
        </td>
        <td>
            5
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
            5
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
            5
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
            Como visitante del segmento agropecuario, quiero entender en la landing page cómo la plataforma puede ayudarme a controlar los costos y maximizar los ingresos de mi granja, para evaluar la efectividad de la aplicación.
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
            3
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
            3
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
            5
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
            5
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
            5
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
            1
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
            5
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

