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

## 3.3 Impact Mapping

## 3.4 Product Backlog