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
            Acceso a valoraciones y comentarios sobre las granjas para empresarios
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            7
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
            Acceder a valoraciones y comentarios sobre granjas
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
            <b>Scenario 01:</b> Acceso exitoso a valoraciones y comentarios sobre granjas<br>
            <b>Dado</b> que el empresario está autenticado en la plataforma<br>
            <b>Cuando</b> accede a la sección de valoraciones y comentarios sobre granjas<br>
            <b>Entonces</b> el sistema muestra de manera clara y organizada las valoraciones y comentarios de otros empresarios sobre las granjas.<br><br>
            <b>Scenario 02:</b> Error al acceder a valoraciones y comentarios sobre granjas por falta de datos<br>
            <b>Dado</b> que el empresario intenta acceder a la información pero no hay datos disponibles<br>
            <b>Cuando</b> intenta acceder a la sección de valoraciones y comentarios sobre granjas<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que no hay valoraciones o comentarios disponibles en ese momento.
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
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
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
            <b>Scenario 01:</b> Acceso exitoso a información detallada sobre cultivos y ganado<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> accede a la sección de información detallada sobre cultivos y ganado<br>
            <b>Entonces</b> el sistema muestra de manera rápida y clara el estado actualizado de los cultivos y ganado de la granja.<br><br>
            <b>Scenario 02:</b> Error al acceder a información detallada sobre cultivos y ganado por falta de autorización<br>
            <b>Dado</b> que el dueño de la granja intenta acceder a la información sin tener los permisos necesarios<br>
            <b>Cuando</b> intenta acceder a la sección de información detallada sobre cultivos y ganado<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que el usuario no está autorizado para ver la información.<br><br>
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            11
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
            Obtener estadísticas financieras
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> dueño de la granja, <b>quiero</b> saber estadísticas financieras, <b>para</b> poder administrar correctamente la economía de mi granja.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Acceso exitoso a estadísticas financieras<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> accede a la sección de estadísticas financieras<br>
            <b>Entonces</b> el sistema muestra las estadísticas financieras de la granja de manera clara y comprensible.<br><br>
            <b>Scenario 02:</b> Error al acceder a estadísticas financieras<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> intenta acceder a las estadísticas financieras pero hay un problema técnico o de conectividad<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que no se pueden mostrar las estadísticas financieras en ese momento.<br><br>
            <b>Scenario 03:</b> Restricción de acceso a estadísticas financieras<br>
            <b>Dado</b> que un usuario intenta acceder a las estadísticas financieras sin tener los permisos necesarios<br>
            <b>Entonces</b> el sistema rechaza el acceso y muestra un mensaje indicando que el usuario no está autorizado para ver las estadísticas financieras.
        </td>
    </tr>
</table>


<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            12
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
            Registrar el cumplimiento de tareas con detalles precisos
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador en la granja, <b>quiero</b> registrar el cumplimiento de mis tareas con detalles como la cantidad, calidad y fecha de cosecha, <b>para</b> mantener un registro preciso de la producción de la granja.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Registro exitoso del cumplimiento de tareas<br>
            <b>Dado</b> que el trabajador ha completado una tarea asignada correctamente<br>
            <b>Cuando</b> registra los detalles pertinentes como cantidad, calidad y fecha de cosecha<br>
            <b>Entonces</b> el sistema registra la información correctamente en el registro de producción de la granja.<br><br>
            <b>Scenario 02:</b> Error al registrar cumplimiento de tareas por falta de información<br>
            <b>Dado</b> que el trabajador intenta registrar el cumplimiento de una tarea sin proporcionar toda la información requerida<br>
            <b>Cuando</b> intenta guardar el registro<br>
            <b>Entonces</b> el sistema rechaza el registro y muestra un mensaje indicando que se deben proporcionar todos los detalles necesarios.<br><br>
            <b>Scenario 03:</b> Error al registrar cumplimiento de tareas por información incorrecta<br>
            <b>Dado</b> que el trabajador proporciona información incorrecta al registrar el cumplimiento de una tarea<br>
            <b>Cuando</b> intenta guardar el registro<br>
            <b>Entonces</b> el sistema rechaza el registro y muestra un mensaje indicando que la información proporcionada es inválida o inconsistente.
        </td>
    </tr>
</table>


<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            13
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
            Emitir alertas sobre emergencias a colegas y supervisores
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador en la granja, <b>quiero</b> emitir alertas sobre cualquier emergencia a mis colegas y supervisores de manera eficaz e inmediata.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Emisión exitosa de alerta de emergencia<br>
            <b>Dado</b> que el trabajador identifica una emergencia en la granja<br>
            <b>Cuando</b> emite una alerta utilizando la plataforma designada<br>
            <b>Entonces</b> la alerta se envía de manera inmediata y eficaz a todos los colegas y supervisores designados.<br><br>
            <b>Scenario 02:</b> Fallo por error del usuario al emitir alerta de emergencia<br>
            <b>Dado</b> que el trabajador intenta emitir una alerta de emergencia sin proporcionar información suficiente o precisa sobre la emergencia<br>
            <b>Entonces</b> la plataforma rechaza la solicitud y muestra un mensaje indicando que se deben proporcionar detalles adecuados sobre la emergencia.<br><br>
            <b>Scenario 03:</b> Restricción de acceso para emitir alertas de emergencia<br>
            <b>Dado</b> que un trabajador intenta emitir una alerta de emergencia sin tener los permisos necesarios<br>
            <b>Entonces</b> el sistema rechaza la solicitud y muestra un mensaje indicando que el usuario no está autorizado para emitir alertas de emergencia.
        </td>
    </tr>
</table>


<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            14
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
            Registrar horas de trabajo para cálculo de salario
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador, <b>quiero</b> registrar mis horas de trabajo, <b>para</b> saber mi salario en función a ello.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Registro exitoso de horas de trabajo<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> registra sus horas de trabajo al finalizar su jornada laboral<br>
            <b>Entonces</b> el sistema registra las horas de trabajo de manera correcta.<br><br>
            <b>Scenario 02:</b> Intento de registro de horas de trabajo incorrecto<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> intenta registrar sus horas de trabajo antes de iniciar o alargando su jornada sin justificación<br>
            <b>Entonces</b> el sistema rechaza el registro y muestra un mensaje indicando que el tiempo registrado es inválido o incoherente.<br><br>
            <b>Scenario 03:</b> Registro de horas de trabajo incompleto<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> intenta registrar sus horas de trabajo sin completar todos los campos requeridos<br>
            <b>Entonces</b> el sistema no acepta el registro y muestra un mensaje indicando que todos los campos deben ser completados.<br><br>
            <b>Scenario 04:</b> Intento de registro duplicado<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> intenta registrar las mismas horas de trabajo nuevamente<br>
            <b>Entonces</b> el sistema rechaza el registro y muestra un mensaje indicando que ya se han registrado las horas para ese período de tiempo.<br>
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            15
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
            Registrar cantidad de ganado enfermo
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador, <b>quiero</b> registrar la cantidad de ganado enfermo, <b>para</b> tener información vital de la situación de cada animal.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Registro exitoso de cantidad de ganado enfermo<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> registra la cantidad de ganado enfermo en la base de datos<br>
            <b>Entonces</b> el sistema registra la información correctamente.<br><br>
            <b>Scenario 02:</b> Registro de cantidad de ganado enfermo incorrecto<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> intenta registrar una cantidad de ganado enfermo negativa o no numérica<br>
            <b>Entonces</b> el sistema rechaza el registro y muestra un mensaje indicando que la cantidad debe ser un número positivo.<br><br>
            <b>Scenario 03:</b> Registro de cantidad de ganado enfermo fuera de rango<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> intenta registrar una cantidad de ganado enfermo mayor que el total de ganado en la granja<br>
            <b>Entonces</b> el sistema rechaza el registro y muestra un mensaje indicando que la cantidad no puede ser mayor que el total de ganado en la granja.<br><br>
            <b>Scenario 04:</b> Registro de cantidad de ganado enfermo incompleto<br>
            <b>Dado</b> que el trabajador está autenticado en la plataforma<br>
            <b>Cuando</b> intenta registrar la cantidad de ganado enfermo sin completar todos los campos requeridos<br>
            <b>Entonces</b> el sistema no acepta el registro y muestra un mensaje indicando que todos los campos deben ser completados.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Acceso a la aplicación desde cualquier área de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            16
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
            Acceso a la aplicación desde cualquier área de la granja
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> trabajador, <b>quiero</b> acceder a la aplicación desde cualquier área de la granja, <b>para</b> tener acceso rápido y conveniente a la información y funcionalidades necesarias para mi trabajo.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Acceso exitoso desde cualquier área de la granja<br>
            <b>Dado</b> que el trabajador está en la granja<br>
            <b>Cuando</b> intenta acceder a la aplicación desde cualquier dispositivo con conexión a internet<br>
            <b>Entonces</b> el sistema le permite acceder sin problemas y utilizar todas las funcionalidades.<br><br>
            <b>Scenario 02:</b> Problema de acceso desde ciertas áreas de la granja<br>
            <b>Dado</b> que el trabajador está en la granja<br>
            <b>Cuando</b> intenta acceder a la aplicación desde ciertas áreas con mala cobertura de internet o interferencias<br>
            <b>Entonces</b> el sistema puede tener dificultades para cargar o responder lentamente.<br><br>
            <b>Scenario 03:</b> Restricción de acceso por error del usuario<br>
            <b>Dado</b> que el trabajador está en la granja<br>
            <b>Cuando</b> intenta acceder a la aplicación ingresando credenciales incorrectas o no autorizadas<br>
            <b>Entonces</b> el sistema rechaza el acceso y muestra un mensaje indicando que las credenciales son inválidas o que el usuario no está autorizado.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            17
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
            Verificar el estado de actividades diarias de los trabajadores
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> dueño de la granja, <b>quiero</b> verificar el estado de las actividades diarias de los trabajadores y el tiempo dedicado a cada tarea, <b>para</b> gestionar eficazmente la asignación de tareas y el horario de trabajo.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Verificación exitosa de actividades diarias de los trabajadores<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> accede al registro de actividades diarias de los trabajadores<br>
            <b>Entonces</b> puede ver el estado de las actividades y el tiempo dedicado a cada tarea de manera clara y precisa.<br><br>
            <b>Scenario 02:</b> Error al verificar actividades diarias<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> intenta verificar las actividades diarias de los trabajadores<br>
            <b>Y</b> ocurre un error al cargar los datos o el sistema no responde correctamente<br>
            <b>Entonces</b> el sistema muestra un mensaje indicando que ha habido un error en el proceso de verificación.<br><br>
            <b>Scenario 03:</b> Restricción de acceso sin autorización<br>
            <b>Dado</b> que el dueño de la granja intenta acceder sin estar autorizado<br>
            <b>Entonces</b> el sistema rechaza el acceso y muestra un mensaje indicando que el usuario no tiene permisos para ver estas actividades.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            18
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
            Informes detallados sobre producción y gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> dueño de la granja, <b>quiero</b> un informe detallado sobre la producción y la gestión de la granja, <b>para</b> garantizar el cumplimiento de los estándares de calidad y rentabilidad.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Generación exitosa de informe detallado<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> solicita la generación de un informe detallado sobre la producción y la gestión de la granja<br>
            <b>Entonces</b> el sistema genera el informe de manera completa y precisa, incluyendo datos relevantes sobre la producción, gastos, ingresos y otros aspectos importantes.<br><br>
            <b>Scenario 02:</b> Error en la generación del informe<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> intenta generar el informe detallado<br>
            <b>Y</b> hay problemas técnicos o de conectividad<br>
            <b>Entonces</b> el sistema no puede completar la generación del informe y muestra un mensaje indicando que ha habido un error.<br><br>
            <b>Scenario 03:</b> Acceso restringido al informe<br>
            <b>Dado</b> que un usuario intenta acceder al informe sin tener los permisos necesarios<br>
            <b>Entonces</b> el sistema rechaza el acceso y muestra un mensaje indicando que el usuario no tiene autorización para ver el informe.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Gestión de la granja
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            19
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
            Establecer y seguir metas de producción
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> dueño de la granja, <b>quiero</b> establecer metas de producción y seguirlas a lo largo del tiempo, <b>para</b> mantenerme enfocado en mejorar el rendimiento de mi granja.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Establecimiento exitoso de metas de producción<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> establece metas de producción específicas y alcanzables para su granja<br>
            <b>Entonces</b> el sistema registra las metas de manera adecuada y las muestra para su seguimiento.<br><br>
            <b>Scenario 02:</b> Seguimiento de metas a lo largo del tiempo<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> consulta el progreso hacia las metas establecidas en períodos posteriores<br>
            <b>Entonces</b> el sistema muestra el progreso de manera clara y permite al dueño de la granja evaluar el rendimiento de su granja en relación con las metas establecidas.<br><br>
            <b>Scenario 03:</b> Error en el establecimiento de metas de producción<br>
            <b>Dado</b> que el dueño de la granja está autenticado en la plataforma<br>
            <b>Cuando</b> intenta establecer metas de producción de manera incorrecta o incompleta<br>
            <b>Entonces</b> el sistema no registra las metas y muestra un mensaje indicando que la información proporcionada es inválida o insuficiente.<br><br>
            <b>Scenario 04:</b> Restricción de acceso a establecimiento de metas<br>
            <b>Dado</b> que un usuario intenta establecer metas de producción sin tener los permisos necesarios<br>
            <b>Entonces</b> el sistema rechaza el acceso y muestra un mensaje indicando que el usuario no tiene autorización para establecer metas.
        </td>
    </tr>
</table>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Acceso móvil a la plataforma FarmLogiTech
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            20
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
            Acceder a la plataforma FarmLogiTech desde dispositivo móvil
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br>
            <b>Como</b> dueño de la granja, <b>quiero</b> acceder a la plataforma FarmLogiTech desde mi dispositivo móvil, <b>para</b> poder gestionar mi granja desde cualquier lugar.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br>
            <b>Scenario 01:</b> Acceso exitoso desde dispositivo móvil<br>
            <b>Dado</b> que el dueño de la granja tiene un dispositivo móvil con conexión a internet<br>
            <b>Cuando</b> accede a la plataforma FarmLogiTech a través del navegador web de su dispositivo móvil<br>
            <b>Entonces</b> el sistema le permite acceder y utilizar todas las funcionalidades de la plataforma de manera adecuada.<br><br>
            <b>Scenario 02:</b> Problemas de rendimiento en dispositivo móvil<br>
            <b>Dado</b> que el dueño de la granja está accediendo desde su dispositivo móvil<br>
            <b>Cuando</b> utiliza la plataforma FarmLogiTech y experimenta lentitud o errores en la carga de páginas<br>
            <b>Entonces</b> el sistema puede tener problemas de rendimiento en dispositivos móviles y necesita ser optimizado para mejorar la experiencia del usuario.<br><br>
            <b>Scenario 03:</b> Restricción de acceso desde dispositivo móvil<br>
            <b>Dado</b> que el dueño de la granja intenta acceder desde un dispositivo móvil sin estar autorizado<br>
            <b>Entonces</b> el sistema rechaza el acceso y muestra un mensaje indicando que el acceso desde ese dispositivo no está permitido.
        </td>
    </tr>
</table>



## 3.3 Impact Mapping

## 3.4 Product Backlog