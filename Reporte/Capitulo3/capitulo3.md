# CAPITULO III: Requirements Specifications

## 3.1 To-Be Scenario Mapping
![Imagen de Granjero To-Be Scenario Mapping](https://i.postimg.cc/52VS1CqV/To-Be-Scenario-Mapping-Granjero.jpg)
![Imagen de Trabajador To-Be Scenario Mapping](https://i.postimg.cc/wT0JLmcg/To-Be-Scenario-Mapping-Trabajadores.jpg)
![Imagen de Empresario To-Be Scenario Mapping](https://i.postimg.cc/zfYSzRCN/To-Be-Scenario-Mapping-Empresario.jpg)

## 3.2 User Stories
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            01
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Crear y Asignar tareas
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> dueño de granja, <b>quiero</b> crear y asignar tareas a los trabajadores <b>para</b> mejorar la gestión de la mano de obra en mi finca.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Creación y asignación exitosa de una nueva tarea</br>
            <b>Dado</b> que el granjero ya está autenticado en la plataforma </br>
            <b>Cuando</b> completa los campos obligatorios (título, descripción, fecha de inicio, fecha de vencimiento, trabajador)</br>
            <b>Entonces</b> la tarea se crea con éxito en el sistema y está disponible su visualización. </br> </br>
            <b>Scenario 02:</b> Fallo en la creación o asignación de tarea </br>
            <b>Dado</b> que el granjero ya se encuentra autenticado en la plataforma</br>
            <b>Cuando</b> intente guardar la tarea con información incompleta o inválida</br>
            <b>Entonces</b> el sistema mostrará un mensaje de error indicando que la acción no pudo completarse y proporcionará orientación sobre cómo corregir los errores</br>
            <b>Y</b> se mostrará un mensaje de error indicando que las credenciales son incorrectas.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            02
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Recibir notificaciones sobre tareas asignadas
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador, <b>quiero</b> recibir notificaciones sobre las tareas asignadas <b>para</b> mantenerme informado sobre las indicaciones del superior.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Recepción exitosa de notificación sobre tarea asignada<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> se le asigne una nueva tarea por parte del superior<br>
            <b>Entonces</b> el sistema enviará una notificación al trabajador sobre la tarea asignada.<br><br>
            <b>Scenario 02:</b> Fallo en la recepción de notificación sobre tarea asignada<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> se le asigne una nueva tarea por parte del superior<br>
            <b>Y</b> haya un error en el envío de la notificación<br>
            <b>Entonces</b> el sistema registrará el error y lo mostrará en los registros del sistema para su posterior revisión.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            03
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Registrar el progreso de las tareas
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador, <b>quiero</b> registrar el progreso de mis tareas <b>para</b> mantenerme organizado y productivo.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Registro exitoso del progreso de la tarea<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> actualiza el estado de una tarea asignada (por ejemplo, en progreso, completada)<br>
            <b>Entonces</b> el sistema registra el progreso de la tarea y lo muestra correctamente en la interfaz del usuario.<br><br>
            <b>Scenario 02:</b> Fallo en el registro del progreso de la tarea debido a información incorrecta<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> intenta actualizar el estado de una tarea asignada con una opción no válida o incompleta<br>
            <b>Entonces</b> el sistema muestra un mensaje de error indicando que la acción no puede ser completada debido a información incorrecta o incompleta<br>
            <b>Y</b> proporciona orientación sobre cómo corregir la información y proceder con el registro del progreso.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Mejora de la cadena de suministro
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            04
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Buscar y contactar a dueños de granjas potenciales
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> empresario, <b>quiero</b> buscar y contactar a dueños de granjas potenciales <b>para</b> establecer asociaciones comerciales y mejorar nuestra cadena de suministro.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Búsqueda exitosa de dueños de granjas potenciales<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> realiza una búsqueda de dueños de granjas utilizando criterios específicos (ubicación, tipo de cultivo, tamaño de la finca, etc.)<br>
            <b>Entonces</b> el sistema muestra una lista de resultados relevantes.<br><br>
            <b>Scenario 02:</b> Contacto exitoso con un dueño de granja potencial<br>
            <b>Dado</b> que el empresario ha encontrado un dueño de granja potencial en la plataforma<br>
            <b>Cuando</b> selecciona al dueño de la lista de resultados y envía un mensaje de contacto<br>
            <b>Entonces</b> el sistema registra el contacto y envía una notificación al dueño de la granja.<br><br>
            <b>Scenario 03:</b> Falla en la búsqueda o contacto<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> intenta realizar una búsqueda o enviar un mensaje de contacto<br>
            <b>Y</b> hay un error en el proceso<br>
            <b>Entonces</b> el sistema muestra un mensaje de error indicando que la acción no puede ser completada y ofrece la opción de intentarlo nuevamente.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Mejora de la cadena de suministro
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            05
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Ver información detallada de las granjas
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> empresario, <b>quiero</b> ver información detallada de las granjas, <b>para</b> poder elegir una adecuada para mi idea de negocio.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Visualización exitosa de información detallada de la granja<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> selecciona una granja de la lista de resultados<br>
            <b>Entonces</b> el sistema muestra información detallada sobre la granja, incluyendo ubicación, tipo de cultivo, tamaño, infraestructura, y cualquier otra información relevante.<br><br>
            <b>Scenario 02:</b> Fallo en la visualización de información detallada de la granja<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> intenta ver información detallada de una granja<br>
            <b>Y</b> hay un error en el proceso<br>
            <b>Entonces</b> el sistema muestra un mensaje de error indicando que la información detallada de la granja no puede ser mostrada en este momento y ofrece la opción de intentarlo nuevamente más tarde.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Mejora de la cadena de suministro
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            06
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Buscar granjas con filtros específicos
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> empresario, <b>quiero</b> buscar granjas con filtros en específico, <b>para</b> encontrar fácilmente una granja que se adapte a mis necesidades.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Búsqueda exitosa de granjas con filtros específicos<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> utiliza filtros específicos como ubicación, tipo de cultivo, tamaño de la finca, infraestructura, etc.<br>
            <b>Entonces</b> el sistema muestra una lista de granjas que cumplen con los criterios de búsqueda.<br><br>
            <b>Scenario 02:</b> No se encuentran resultados con los filtros especificados<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> realiza una búsqueda utilizando filtros específicos<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que no se encontraron resultados con los filtros especificados. El empresario puede ajustar los criterios de búsqueda y volver a intentarlo.<br><br>
            <b>Scenario 03:</b> Error en la selección de filtros<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> intenta seleccionar filtros para la búsqueda de granjas<br>
            <b>Y</b> selecciona criterios que no son válidos o incompatibles<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que los filtros seleccionados no son válidos o compatibles, y sugiere al empresario seleccionar opciones válidas.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Mejora de la cadena de suministro
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            07
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Acceder a valoraciones y comentarios de otras granjas
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> empresario, <b>quiero</b> acceder a las valoraciones y comentarios de otros empresarios sobre las granjas, <b>para</b> tomar decisiones informadas y sentirme seguro al realizar negocios con ellas.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Acceso exitoso a las valoraciones y comentarios<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> selecciona una granja y accede a su perfil<br>
            <b>Entonces</b> el sistema muestra las valoraciones y comentarios de otros empresarios sobre esa granja.<br><br>
            <b>Scenario 02:</b> No hay valoraciones o comentarios disponibles<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> intenta acceder a las valoraciones y comentarios de una granja<br>
            <b>Y</b> no hay información disponible<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que no hay valoraciones ni comentarios disponibles en este momento.<br><br>
            <b>Scenario 03:</b> Error al acceder a las valoraciones y comentarios<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> intenta acceder a las valoraciones y comentarios de una granja<br>
            <b>Y</b> hay un problema técnico o de conectividad<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que no es posible acceder a la información en este momento y sugiere intentarlo nuevamente más tarde.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            08
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Recibir alertas automáticas sobre cambios climáticos significativos
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador, <b>quiero</b> recibir alertas automáticas sobre cambios climáticos significativos que puedan afectar mis cultivos, <b>para</b> poder tomar medidas preventivas y proteger mis cosechas.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Recepción exitosa de alertas automáticas<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> se detecta un cambio climático significativo que puede afectar los cultivos del trabajador<br>
            <b>Entonces</b> el sistema envía automáticamente una alerta al trabajador sobre el cambio climático detectado.<br><br>
            <b>Scenario 02:</b> No hay alertas disponibles<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> se verifica si hay cambios climáticos significativos<br>
            <b>Y</b> no se detecta ningún cambio significativo<br>
            <b>Entonces</b> el sistema no envía ninguna alerta al trabajador.<br><br>
            <b>Scenario 03:</b> Error en la recepción de alertas automáticas<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> se detecta un cambio climático significativo que puede afectar los cultivos del trabajador<br>
            <b>Y</b> hay un problema técnico o de conectividad<br>
            <b>Entonces</b> el sistema no puede enviar la alerta y muestra un mensaje indicando que ha habido un error en el proceso.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            09
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Verificar niveles de inventario y recibir notificaciones de reposición
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> dueño de la granja, <b>quiero</b> verificar fácilmente los niveles de inventario de productos agrícolas y ganaderos, y recibir notificaciones cuando sea necesario reponerlos, <b>para</b> garantizar un flujo de trabajo ininterrumpido.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Verificación exitosa de niveles de inventario<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> accede al sistema de gestión de inventario<br>
            <b>Entonces</b> puede ver fácilmente los niveles de inventario de productos agrícolas y ganaderos.<br><br>
            <b>Scenario 02:</b> Recepción exitosa de notificaciones de reposición<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> los niveles de inventario de algún producto alcanzan un umbral mínimo predefinido<br>
            <b>Entonces</b> el sistema envía automáticamente una notificación al dueño de la granja para informarle sobre la necesidad de reponer dicho producto.<br><br>
            <b>Scenario 03:</b> Error al verificar los niveles de inventario<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> intenta verificar los niveles de inventario<br>
            <b>Y</b> hay un problema técnico o de conectividad<br>
            <b>Entonces</b> el sistema no puede mostrar los niveles de inventario y muestra un mensaje indicando que ha habido un error en el proceso.<br><br>
            <b>Scenario 04:</b> Error en la recepción de notificaciones de reposición<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> los niveles de inventario de algún producto alcanzan un umbral mínimo predefinido<br>
            <b>Y</b> hay un problema técnico o de conectividad<br>
            <b>Entonces</b> el sistema no puede enviar la notificación de reposición y muestra un mensaje indicando que ha habido un error en el proceso.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            10
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Luciano Ruiz
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Obtener información detallada sobre el estado de cultivos y ganado
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> dueño de la granja, <b>quiero</b> saber información detallada sobre el estado de mis cultivos y ganado, <b>para</b> poder administrarla de manera rápida e informada.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Obtención exitosa de información detallada<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> accede al sistema de gestión de cultivos y ganado<br>
            <b>Entonces</b> puede ver información detallada sobre el estado actual de sus cultivos y ganado, incluyendo salud, crecimiento, producción, y cualquier otra métrica relevante.<br><br>
            <b>Scenario 02:</b> No hay información disponible<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> intenta obtener información detallada sobre el estado de sus cultivos y ganado<br>
            <b>Y</b> no hay datos disponibles en el sistema<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que no hay información disponible en este momento.<br><br>
            <b>Scenario 03:</b> Error al obtener información detallada<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> intenta obtener información detallada sobre el estado de sus cultivos y ganado<br>
            <b>Y</b> hay un problema técnico o de conectividad<br>
            <b>Entonces</b> el sistema no puede mostrar la información detallada y muestra un mensaje indicando que ha habido un error en el proceso.
        </td>
    </tr>
</table>



## 3.3 Impact Mapping

## 3.4 Product Backlog