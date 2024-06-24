# Capítulo V: Product Implementation, Validation & Deployment
## 5.1 Software Configuration Management
A continuación, presentaremos el proceso por el cual organizamos, gestionamos y controlamos los cambios en el desarrollo de este proyecto.
### 5.1.1. Software Development Environment Configuration.
**Requirements Management**
1. Trello: Es una herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente basados en marcos de
   trabajos ágiles. Será empleado para visualizar y actualizar el estado actual de las tareas e historias de usuario
   pertenecientes al sprint a desarrollar.  
   Ruta de referencia: https://trello.com/es


**Product UX/UI Design**

1. Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizado para el diseño digital. En el
   caso del proyecto, será utilizado para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.

   Ruta de referencia: https://www.figma.com/login
2. Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama de
   clases asociado a la aplicación.

   Ruta de referencia: https://www.lucidchart.com/


**Software Development**
1. Visual Studio Code: Entorno de desarrollo integrado elegido para la elaboración y compilación del código por motivos de
   dominio por parte de los integrantes del equipo de trabajo. Utilizar este IDE supone de valor para el desarrollo del
   proyecto puesto que incluye la posibilidad de agregar extensiones de utilidad, soporte de edición de texto en múltiples
   lenguajes de programación, disponibilidade en múltiples sistemas operativos, entre otros beneficios.

   Ruta de referencia: https://code.visualstudio.com/  
   <br>
2. HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Será
   empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación.

   Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp   
   <br>
3. CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la mano
   con HTML.

   Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html
   <br>
   <br>
4. Tailwind CSS: Es un conjunto de herramientas de utilidad de CSS altamente personalizable y orientado a clases. Se utilizará para diseñar y estilizar la interfaz de usuario dentro de la aplicación.

   Ruta de referencia: https://tailwindcss.com/docs
   <br>
   <br>
5. JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz de
   usuario dentro de la aplicación.

   Ruta de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript

 <br>

**Software Deployment**
1. Git: Una herramienta de control de versiones que facilita el registro y la gestión de las distintas versiones del programa. Su propósito es mantener un historial de cambios y simplificar la corrección de errores. Los integrantes del equipo
   accederán a través de la línea de comandos en sus sistemas locales.

   Ruta de referencia: https://git-scm.com/
   <br>
   <br>
   **Software Documentation and Project Management**
2. Github: Una plataforma en la nube que hospedará los repositorios de código del proyecto. Permitirá la colaboración en
   tiempo real y la revisión de contribuciones de cada miembro del equipo. Los integrantes del equipo podrán acceder a través de sus navegadores web.

   Ruta de referencia: https://github.com/


### 5.1.2. Source Code Management.
El proyecto seguirá las convenciones del flujo de trabajo establecido por el modelo GitFlow para el control de versiones, empleando GitHub como plataforma y sistema de control de versiones. A continuación, se describirá la implementación de GitFlow como un flujo de trabajo para el control de versiones, junto con el enlace del Landing Page.

**Repositorio de GitHub:**
- Enlace para acceder a la https://github.com/Open-Source-WX55-Group-UFriends
- Enlace para acceder al repositorio de la https://github.com/Open-Source-WX55-Group-UFriends/landing-page
- Enlace para acceder al repositorio del https://github.com/Open-Source-WX55-Group-UFriends/Report-Final-Project

**Flujo de trabajo GitFlow**

El flujo de trabajo a ser implementado para el desarrollo del proyecto se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

## <M Imagen de Realese branches

**Estructura de branches (Ramas):**
1. **Master branch (Rama principal):** Esta rama servirá como la principal para la aplicación, alojando versiones estables y finales del desarrollo. Únicamente se aceptarán cambios que hayan sido previamente probados y verificados en los features y de ahí en Developer.
2. **Develop branch (Rama de desarrollo):** El propósito de esta rama es facilitar los avances del proyecto en equipo y mantener los archivos centrales del desarrollo continuo.
3. **Feature branch(Ramas de funcionalidad):** Cada capitulo desarrollado por el equipo, o separada del enfoque actual del desarrollo, tendrá su propia rama. Una vez que una funcionalidad esté completamente trabajada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, "feature/chapter-#".
### 5.1.3. Source Code Style Guide & Conventions.
**HTML:** Algunas de las prácticas que deben de seguirse para alcanzar un código coherente, sostenible y ordenado son las
siguientes:
1. Cerrar todos los elementos HTML: Por ejemplo, ```<p>Esto es un párrafo.</p>```
2. Siempre declarar el tipo de documento en la primera línea del documento, para
   HTML es "<!DOCTYPE html>”.
3. Escribir en una línea los comentarios cortos.
4. Utilizar comillas en caso de que los atributos contengan espacios entre sí.
5. Procurar especificar el texto alt y las dimensiones width y height de las imágenes, ya que de esta manera se facilitará la
   disponibilidad del contenido. Por ejemplo:   ```<img src="abc.img" alt="image name"  
   style="width:128px;height:128px">```
6. Se nos recomienda no usar el espacio al momento de utilizar los signos porque
   es más fácil de leerlo de esta forma.  
   <br>
   HTML: (https://www.w3schools.com/html/html5_syntax.asp)

**CSS:** Entre las prácticas empleadas se menciona:

1. Se nos recomienda tener una sangría por 2 espacios a la vez, no debemos
   utilizar tabulaciones ni mezclarlas tabulaciones con espacios para la sangría.
2. Todo el código debe estar en minúscula.
3. Eliminar los espacios en blanco.
4. Usar comentarios para explicar el código.
5. Utilizar nombres de clase significativos o genéricos, nombres que reflejen el
   propósito de su elemento.  
   <br>

   CSS: (https://google.github.io/styleguide/htmlcssguide.html)

**Tailwind:** Entre las prácticas empleadas se menciona:

1. Utiliza clases utilitarias individuales en lugar de estilos personalizados.
2. Combina múltiples clases utilitarias para estilos complejos.
3. Usa prefijos contextuales para clasificar clases según el contexto o componente.  
   <br>

   Tailwind:(https://tailwindcss.com/docs/adding-custom-styles)




### 5.1.4. Software Deployment Configuration.
### Landing page deployment:
Para desplegar la landing page es necesario contar con una serie de requisitos, entre ellos, es necesario contar con
una cuenta personal, una organización y un repositorio al cual cargar los documentos. A partir de lo anterior, es posible
comenzar el despliegue de la landing page. A continuación se enuncian los pasos a seguir:

1. Crear una carpeta llamada "docs" para alojar el Landing Page.
2. Asegurarse de que los archivos sigan las nomenclaturas "index.html", para la landing page; "input.css" y "output.css" para poder utilizar Tailwind y
   una carpeta llamada "img" que contenga las imágenes.
3. Cargar los archivos al repositorio mediante un commit.
4. Dirigirse a Settings > Pages y seleccionar el branch correspondiente, en nuestro caso es el "main".
5. Especificar la carpeta "docs" como la fuente de la página.
6. Esperar a que GitHub realice las comprobaciones necesarias. Una vez culminado el proceso, se obtendrá un enlace que
   llevará al Landing Page desplegado

## < GithubPages

### 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1 Sprint 1.
#### 5.2.1.1 Sprint Planing 1.

En el marco de Scrum, un Sprint es un período de tiempo definido y breve en el que un equipo de desarrollo trabaja en
las tareas necesarias para lograr un objetivo específico del producto, conocido como "Product Goal". En el proyecto de
desarrollo de FarmLogiTech, se han planificado cuatro sprints, cada uno con una duración de dos semanas.


Durante el Sprint #1, que inicia el 06/04/2024, el objetivo principal es desarrollar una landing page
llamativa para FarmLogiTech. Esta página se diseñará para atraer a los visitantes y comunicar de manera efectiva los beneficios del producto. En resumen,
durante este sprint nos enfocaremos en el diseño y desarrollo de la landing page para cumplir con nuestros objetivos.

| Sprint | Prepared Date | Time      | Location                              | Prepared By     | Attendees                                                                      | Sprint 1 Goal                                                                               | Sprint 1 Velocity | Sum of Story Points |
|--------|---------------|-----------|---------------------------------------|-----------------|--------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|-------------------|---------------------|
|   1    | 06/04/2024    | 11:00  PM | Reunión virtual mediante Google meet  | Rodrigo Aguilar | Rodrigo Aguilar, Mathias Kunimoto, Janiel Escalante, Augusto Pin, Luciano Ruiz | Elaborar y diseñar una landing page atractiva e informativa para la aplicación FarmLogiTech | 22                | 22                  |

#### 5.2.1.2. Sprint Backlog 1.
En el primer sprint, el equipo tuvo como objetivo principal crear una landing page atractiva y funcional. Utilizamos la herramienta Trello para organizar y asignar tareas a los miembros del equipo según sus habilidades.

link del trello: https://trello.com/b/WJXt50JP/farmlogitech

<table>
  <tr>
    <th>Technical User Story</th>
    <th colspan="5">WorkItem / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status(Todo/InProcess/ToReview/Done)</th>
  </tr>
  <tr>
    <td rowspan="2">US09</td>
    <td rowspan="2">Elegir método de pago para suscripción</td>
    <td>TK01</td>
    <td>Crear endpoint para elegir método de pago</td>
    <td>Crear endpoint que permita la elección del método de pago para la suscripción.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK02</td>
    <td>Implementar validación de métodos de pago</td>
    <td>Validar los métodos de pago disponibles y su correcto funcionamiento.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US10</td>
    <td rowspan="2">Crear y asignar tareas a los trabajadores</td>
    <td>TK03</td>
    <td>Crear endpoint para asignar tareas</td>
    <td>Crear endpoint para asignar tareas a los trabajadores.</td>
    <td>5</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK04</td>
    <td>Crear lógica de asignación de tareas</td>
    <td>Implementar la lógica que permita asignar tareas según las capacidades y disponibilidad de los trabajadores.</td>
    <td>6</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US12</td>
    <td rowspan="2">Registrar progreso de tareas</td>
    <td>TK05</td>
    <td>Crear endpoint para registrar progreso de tareas</td>
    <td>Crear endpoint que permita registrar el progreso de las tareas asignadas.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK06</td>
    <td>Implementar validación de progreso</td>
    <td>Validar que el progreso de las tareas sea registrado correctamente en el sistema.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US13</td>
    <td rowspan="2">Buscar y contactar a dueños de granjas potenciales</td>
    <td>TK07</td>
    <td>Crear endpoint para buscar dueños de granjas</td>
    <td>Crear endpoint que permita buscar y contactar a dueños de granjas potenciales.</td>
    <td>5</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK08</td>
    <td>Implementar lógica de contacto</td>
    <td>Implementar la lógica que permita contactar a los dueños de granjas potenciales de manera efectiva.</td>
    <td>5</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US14</td>
    <td rowspan="2">Ver información detallada de granjas</td>
    <td>TK09</td>
    <td>Crear endpoint para obtener detalles de granjas</td>
    <td>Crear endpoint que permita obtener información detallada de las granjas.</td>
    <td>4</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK10</td>
    <td>Implementar validación de datos de granjas</td>
    <td>Validar que los datos obtenidos de las granjas sean precisos y completos.</td>
    <td>4</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US15</td>
    <td rowspan="2">Buscar granjas con filtros específicos</td>
    <td>TK11</td>
    <td>Crear endpoint para buscar granjas con filtros</td>
    <td>Crear endpoint que permita buscar granjas utilizando filtros específicos.</td>
    <td>5</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK12</td>
    <td>Implementar lógica de filtrado</td>
    <td>Implementar la lógica que permita aplicar filtros en la búsqueda de granjas.</td>
    <td>5</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US16</td>
    <td rowspan="2">Acceder a valoraciones y comentarios de otras empresas sobre las granjas</td>
    <td>TK13</td>
    <td>Crear endpoint para valoraciones y comentarios</td>
    <td>Crear endpoint que permita acceder a valoraciones y comentarios de otras empresas sobre las granjas.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK14</td>
    <td>Implementar validación de valoraciones</td>
    <td>Validar que las valoraciones y comentarios sean precisos y relevantes.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US18</td>
    <td rowspan="2">Verificar niveles de inventario</td>
    <td>TK15</td>
    <td>Crear endpoint para verificar inventario</td>
    <td>Crear endpoint que permita verificar los niveles de inventario.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK16</td>
    <td>Implementar lógica de verificación de inventario</td>
    <td>Implementar la lógica que permita verificar los niveles de inventario de manera precisa.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US19</td>
    <td rowspan="2">Ver información detallada sobre el estado de cultivos y ganado</td>
    <td>TK17</td>
    <td>Crear endpoint para obtener estado de cultivos</td>
    <td>Crear endpoint que permita obtener información detallada sobre el estado de cultivos y ganado.</td>
    <td>4</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK18</td>
    <td>Implementar validación de estado de cultivos</td>
    <td>Validar que la información sobre el estado de cultivos y ganado sea precisa.</td>
    <td>4</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US20</td>
    <td rowspan="2">Ver estadísticas financieras</td>
    <td>TK19</td>
    <td>Crear endpoint para obtener estadísticas financieras</td>
    <td>Crear endpoint que permita obtener estadísticas financieras detalladas.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK20</td>
    <td>Implementar lógica de estadísticas</td>
    <td>Implementar la lógica que permita calcular y mostrar estadísticas financieras.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US21</td>
    <td rowspan="2">Registrar el cumplimiento de tareas con detalles de producción</td>
    <td>TK21</td>
    <td>Crear endpoint para registrar cumplimiento de tareas</td>
    <td>Crear endpoint que permita registrar el cumplimiento de tareas con detalles de producción.</td>
    <td>5</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK22</td>
    <td>Implementar validación de cumplimiento</td>
    <td>Validar que el cumplimiento de tareas y los detalles de producción sean registrados correctamente.</td>
    <td>5</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US22</td>
    <td rowspan="2">Emitir alertas de emergencia de manera eficaz</td>
    <td>TK23</td>
    <td>Crear endpoint para emitir alertas de emergencia</td>
    <td>Crear endpoint que permita emitir alertas de emergencia de manera eficaz.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK24</td>
    <td>Implementar lógica de alertas de emergencia</td>
    <td>Implementar la lógica que permita emitir y gestionar alertas de emergencia.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US23</td>
    <td rowspan="2">Registrar horas de trabajo para cálculo de salario</td>
    <td>TK25</td>
    <td>Crear endpoint para registrar horas de trabajo</td>
    <td>Crear endpoint que permita registrar las horas de trabajo de los empleados para el cálculo de salario.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK26</td>
    <td>Implementar validación de horas de trabajo</td>
    <td>Validar que las horas de trabajo registradas sean precisas para el cálculo de salario.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US24</td>
    <td rowspan="2">Registrar cantidad de ganado enfermo</td>
    <td>TK27</td>
    <td>Crear endpoint para registrar ganado enfermo</td>
    <td>Crear endpoint que permita registrar la cantidad de ganado enfermo.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK28</td>
    <td>Implementar validación de registros de ganado enfermo</td>
    <td>Validar que los registros de ganado enfermo sean precisos y actualizados.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US26</td>
    <td rowspan="2">Verificar estado de actividades diarias y tiempo dedicado por los trabajadores</td>
    <td>TK29</td>
    <td>Crear endpoint para verificar estado de actividades diarias</td>
    <td>Crear endpoint que permita verificar el estado de actividades diarias y el tiempo dedicado por los trabajadores.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK30</td>
    <td>Implementar validación de actividades diarias</td>
    <td>Validar que los registros de actividades diarias y tiempo dedicado sean precisos.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US30</td>
    <td rowspan="2">Crear API RESTful para acceder a datos agrícolas y ganaderos</td>
    <td>TK31</td>
    <td>Diseñar y crear API RESTful</td>
    <td>Diseñar y crear una API RESTful que permita acceder a datos agrícolas y ganaderos.</td>
    <td>6</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK32</td>
    <td>Implementar endpoints de datos agrícolas y ganaderos</td>
    <td>Implementar los endpoints necesarios para acceder y gestionar datos agrícolas y ganaderos.</td>
    <td>6</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
</table>




#### 5.2.1.3. Development Evidence for Sprint Review.
| Repository                                                      | Branch             | Commit id | Commit Message                             | Commit Message Body                                                            | Commited on (Date) |
|-----------------------------------------------------------------|--------------------|--------|--------------------------------------------|--------------------------------------------------------------------------------|-------------------- 
| https://github.com/Open-Source-WX55-Group-UFriends/landing-page | interactive_images | 099a2cd | feat: update index(image carousel)         |  feat: update index(image carousel)                           | 07/04/2024         | 
|                                                                 | interactive_images | d5c926e | feat: added collaborators above the footer | feat: added collaborators above the footer| 9/04/2024          | 
|                                                                 | price_rates        | 8b7d124 | feat:  added price_rates section           | feat:  added price_rates section         | 10/04/2024         | 
|                                                                 | interactive_images | 1fec9bf | fix: update responsive                     | fix: update responsive | 07/04/2024         | 
|                                                                 | payment_method     | a28ada5 | chore: initial commit                       | chore: initial commit| 11/04/2024         | 

#### 5.2.1.4 Testing Suite Evidence for Sprint Review.

Para la entrega del Sprint 1, logramos completar el desarrollo, la implementación y el despliegue del Landing Page. Por esta razón, nos enfocamos en la sección de "acceptance-tests" en la implementación de los archivos feature que componen nuestro landing page. Estos features se basan en las Historias de Usuario especificadas en el sprint backlog, detallando cada uno de los escenarios que planeamos desarrollar.
<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>landing-page</td>
    <td>Features_testing</td>
    <td>07fa8d6</td>
    <td>Augusto Pin</td>
    <td>doc: add acceptance tests</td>
    <td>11/04/2024</td>
  </tr>
</table>



#### 5.2.1.5. Execution Evidence for Sprint Review.
Durante el Sprint 1, logramos la implementación y despliegue del Landing Page. Muestra diversas secciones donde los usuarios pueden encontrar información relevante sobre el producto. A continuación, se presentan algunas evidencias del progreso realizado.

1. Sección  carrusel de imágenes
   En esta sección, se puede visualizar e interactuar con las imágenes principales.
   <img src="/assets/carrousel.JPG" alt="Carrousel"/></img>

2. Sección de Características
   En esta sección, se puede observar lo que FarmLogitech ofrece.
   <img src="/assets/characteristics.JPG" alt="Characteristics"/></img>
3. Sección Planes
   En esta sección, se visualizan los planes que Farmlogitech, plan básico en el que solo
   podrás promocionar tu granja y el premium en la que no solo podrás promocionarla, sino también gestionarla.
   <img src="/assets/plans.JPG" alt="Plans"/></img>
4. Sección Método de Pago
   En esta sección, se visualizan diversos métodos de pago que Farmlogitech ofrece
   <img src="/assets/payment.JPG" alt="Payment"/></img>
5. Sección Colaboradores
   En esta sección, aparecerán los colaboradores encargados de desarrollar la landing page.
   <img src="/assets/collaborators.JPG" alt="Collaborators"/></img>

### 5.2.1.6. Services Documentation Evidence for Sprint Review.
Para este primer sprint no fue contemplada la evidencia de documentación de los servicios.


### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la entrega del Sprint número 2, se desplegó la landing.

<img src="/assets/img-landing.png" alt="Landing"/></img>


### 5.2.1.8. Team Collaboration Insights during Sprint.

| Alumno           | Actividad                                                   | 
|------------------|-------------------------------------------------------------|
| Rodrigo Aguilar  | Implementación de imágenes interactivas                     |
| Janiel Escalante | Implementación de sección métodos de pago                   |
| Mathias Kunimoto | Implementación del responsive y características del website |
| Augusto Pin      | Implementación de la sección colaboradores                  |
| Luciano Ruiz     | Implementación de la sección de planes                      |


<img src="/assets/stats1.JPG" alt="Statistics-01"/></img>  
<img src="/assets/stats2.JPG" alt="Statistics-02"/></img>  
<img src="/assets/stats3.JPG" alt="Statistics-03"/></img>



### 5.2.2 Sprint 2.
#### 5.2.2.1 Sprint Planing 2.

En el marco de Scrum, un Sprint es un período de tiempo definido y breve en el que un equipo de desarrollo trabaja en
las tareas necesarias para lograr un objetivo específico del producto, conocido como "Product Goal". En el proyecto de
desarrollo de FarmLogiTech, se han planificado cuatro sprints, cada uno con una duración de dos semanas.


Durante el Sprint #2, que inicia el 12/04/2024, el objetivo principal es implementar la website en Angular con todos los
conocimientos recibidos. Esta website se implementará para atraer a los visitantes y comunicar de manera efectiva los beneficios del producto. En resumen,
durante este sprint nos enfocaremos en mostrar la website y desarrollo para cumplir con nuestros objetivos.

| Sprint | Prepared Date | Time      | Location                              | Prepared By     | Attendees                                                                      | Sprint 1 Goal                                                                              | Sprint 1 Velocity | Sum of Story Points |
|--------|---------------|-----------|---------------------------------------|-----------------|--------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|-------------------|---------------------|
|   1    | 12/04/2024    | 11:00  PM | Reunión virtual mediante Google meet  | Rodrigo Aguilar | Rodrigo Aguilar, Mathias Kunimoto, Janiel Escalante, Augusto Pin, Luciano Ruiz | Implementar la website para la aplicación FarmLogiTech | 22                | 23                  |

#### 5.2.2.2. Sprint Backlog 2.
En el segundo sprint, el equipo tuvo como objetivo principal implementar la website y que tenga funcionamiento. Utilizamos la herramienta Trello para organizar y asignar tareas a los miembros del equipo según sus habilidades.

link del trello: https://trello.com/b/WJXt50JP/farmlogitech


<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 2</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
      <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
   <tr>
       <td>US15</td>
       <td>Buscar granjas con filtros específicos</td>
       <td>T01</td>
       <td>Agregar cards de las granjas</td>
       <td>Implementar las granjas y luego conectarlas para hacerle ruta y que se filtre a la hora de buscar</td>
       <td>6</td>
       <td>Mathias Kunimoto</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US06</td>
       <td>Elegir método de pago para suscripción</td>
       <td>T02</td>
       <td>Agregar métodos de pagos disponibles</td>
       <td>Implementar en una fila los métodos de pagos disponibles</td>
       <td>6</td>
       <td>Rodrigo Aguilar </td>
       <td>Done</td>
    </tr>
<tr>
       <td>US16</td>
       <td>Acceder a valoraciones y comentarios de otras empresas sobre las granjas</td>
       <td>T03</td>
       <td>Agregar sección de valoraciones y comentarios</td>
       <td>Implementar sección en donde podras ver las valoraciones y comentarios sobre la granja</td>
       <td>4</td>
       <td>Augusto Pin</td>
       <td>Done</td>
    </tr>
<tr>
<tr>
       <td>US10</td>
       <td>Crear y asignar tareas a los trabajadores</td>
       <td>T04</td>
       <td>Agregar tabla de asignar tareas</td>
       <td>Implementar tabla en donde puedas asignar tareas a los trabajadores </td>
       <td>5</td>
       <td>Janiel Escalante</td>
       <td>Done</td>
    </tr>
<tr>
<tr>
       <td>US20</td>
       <td> Estadísticas financieras</td>
       <td>T05</td>
       <td>Añadir gráficos</td>
       <td>Implementar gráficos estadísticos conforme a lo que el administrador seleccione</td>
       <td>5</td>
       <td>Luciano Ruiz</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>US14</td>
       <td>Informe detallada de las granjas</td>
       <td>T06</td>
       <td>Agregar información de las granjas</td>
       <td>Implementar funcion de darle click y que salga la información de la granja</td>
       <td>6</td>
       <td>Rodrigo Aguilar / Mathias Kunimoto </td>
       <td>Done</td>
    </tr>

   </table>




#### 5.2.2.3. Development Evidence for Sprint Review.
| Repository                                                      | Branch                      | Commit id | Commit Message                             | Commit Message Body                                                         | Commited on (Date) |
|-----------------------------------------------------------------|-----------------------------|--------|--------------------------------------------|-----------------------------------------------------------------------------|-------------------- 
| https://github.com/Open-Source-WX55-Group-UFriends/Frontend-App.git | feature/subscriptions       | 50ed12c | Merge branch 'develop' into feature/subscriptions         |  chore: initial commit                       | 28/04/2024         | 
|                                                                 | feature/search-and-match    | 49a4028 |feat: updated position and colors of toolbar. |chore: initial commit| 29/04/2024         | 
|                                                                 | feature/dashboard-analytics | e8d31e3 |fix: fix merged with develop.           |  chore: initial commit      | 29/04/2024         | 
|                                                                 | feature/social-interaction  | 0d1a4b8 |fix: conflicts resolved and routes connected                     |chore: initial commit | 29/04/2024         | 
|                                                                 | feature/task                | 62be550 |feature(task): implemented table add tasks.                      | chore: initial commit| 29/04/2024         | 

#### 5.2.2.4 Testing Suite Evidence for Sprint Review.

Para la entrega del Sprint 2, logramos completar la implementación del desarrollo de la website. Por esta razón, nos enfocamos en la sección de "acceptance-tests" en la implementación de los archivos feature que componen nuestro website. Estos features se basan en las Historias de Usuario especificadas en el sprint backlog, detallando cada uno de los escenarios que planeamos desarrollar.
<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>Frontend-App</td>
    <td>develop</td>
    <td>07fa8d6</td>
    <td>Augusto Pin</td>
    <td>doc: add acceptance tests</td>
    <td>29/04/2024</td>
  </tr>
</table>


<br>

#### 5.2.2.5. Execution Evidence for Sprint Review.
Durante el Sprint 2, logramos la implementación y despliegue de la website. Muestra diversas secciones donde los usuarios pueden encontrar información relevante sobre el producto. A continuación, se presentan algunas evidencias del progreso realizado.

1. Sección  Inicio:  
   En esta sección, se puede visualizar e interactuar con las publicaciones de dueños de granjas.    
   <img src="/assets/inicio.JPG" alt="Statistics-01"/></img>

2. Sección de Publicación:  
   En esta sección, se puede observar lo descripción de la publicación, ponerle una valoración y contactar al dueño de la publicación.    
   <img src="/assets/publication-1.JPG" alt="Publication-01"/></img>   
   <img src="/assets/publication-2.JPG" alt="Publication-02"/></img>
3. Sección Tarifas:
   En esta sección, se visualizan los planes que tiene Farmlogitech   
   <img src="/assets/rates.JPG" alt="Rates"/></img>

4. Sección Pagar Tarifa:     
   En esta sección, se visualiza un formulario de pago   
   <img src="/assets/payment-rate.JPG" alt="Payment-Rate"/></img>

5. Sección Tareas
   En esta sección, se puede ver una tabla con las tareas de cada trabajador de la granja y asignar una.   
   <img src="/assets/task-1.JPG" alt="Task-01"/></img>   
   <img src="/assets/task-2.JPG" alt="Task-02"/></img>

### 5.2.2.6. Services Documentation Evidence for Sprint Review.
Para este segundo sprint no fue contemplada la evidencia de documentación de los servicios.


### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Para la entrega del Sprint número 1, se desplegó la website.

<img src="/Assets/img-website.jpeg" alt="Website"/></img>

Enlace para acceder a la landing page: https://open-source-wx55-group-ufriends.github.io/landing-page/#

### 5.2.2.8. Team Collaboration Insights during Sprint.

| Alumno           | Actividad                                                       | 
|------------------|-----------------------------------------------------------------|
| Rodrigo Aguilar  | Implementación de metodos de suscripción                        |
| Janiel Escalante | Implementación de tablas para asignar tareas a los trabajadores |
| Mathias Kunimoto | Implementación de buscar y encontrar una granja                 |
| Augusto Pin      | Implementación de valoraciones asignadas a una granja           |
| Luciano Ruiz     | Implementación de mostrar los gráficos estadísticos             |

<img src="/assets/img-commits.png" alt="Statistics-01"/></img>

## 5.2.3. Sprint 3
### 5.2.3.1. Sprint Planning 3
El spring 3 tiene como inicio el dia 13/05/2024 y como objetivo plantea completar el frontend de nuestra aplicación web y realizar el backend.

<table>
<tr><td>Sprint #</td><td>Sprint 3</td></tr>
<tr><td colspan="2">Sprint Planning Background</td></tr>
<tr><td>Date</td><td>2024-05-13</td></tr>
<tr><td>Time</td><td>7:00 PM</td></tr>
<tr><td>Location</td><td>Meet virtual meeting</td></tr>
<tr><td>Prepared by</td><td>Rodrigo Aguilar</td></tr>
<tr><td>Atendees</td><td>Mathias Kunimoto, Franz Escalante, Augusto Pin, Franco Barrionuevo y Luciano Ruiz</td></tr>
<tr><td>Sprint 3 Review</td><td>En el Sprint 2 desarrollamos la mayoría de apartados de nuestra aplicación, declaramos los bounded context y features a utilizar para lograr un desarrollo uniforme y consistente. El product owner estuvo satisfecho con el manejo de desarrollo que tuvimos en el equipo.</td></tr>
<tr><td>Sprint 3 Retrospective</td><td>En el anterior sprint pudimos mejorar la comunicación y el empleo de herramientas de administración para obtener un progreso más rápido en el desarrollo del frontend. Se mejoraron detalles como la estructuración de los componentes y la consistencia del diseño en todos los features.</td></tr>
<tr><td colspan="2">Sprint Goal & User Stories</td></tr>
<tr><td>Sprint 3 Goal</td><td>Desarrollar el frontend completamente y avanzar en gran medida el backend, logrando satisfacer la mayoría de las user stories relacionadas con la lógica del negocio.</td></tr>
<tr><td>Sprint 3 Velocity</td><td>49</td></tr>
<tr><td>Sum of story points</td><td>49</td></tr>
</table>

### 5.2.3.2. Sprint Backlog 3

En este sprint backlog, desarrollamos completamente el frontend y en gran medida el backend, satisfaciendo la mayoría de las user stories. La herramienta utilizada para la organización del equipo fue Trello. Esta herramienta nos permitió tener en claro las tareas por desarrollar para asignarlas según las fortalezas de cada miembro del equipo.
<img src="/Assets/trello.png" alt="Repo 1"/></img>
Trello Link: [https://trello.com/b/7J9Z2J9A/sprint-3](https://trello.com/invite/b/WJXt50JP/ATTI255cf1b0d82284ff8d327dd3f64225d622C4A319/farmlogitech)

<table>
  <tr>
    <th>Technical User Story</th>
    <th colspan="5">WorkItem / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status(Todo/InProcess/ToReview/Done)</th>
  </tr>
  <tr>
    <td rowspan="2">US09</td>
    <td rowspan="2">Elegir método de pago para suscripción</td>
    <td>TK01</td>
    <td>Crear endpoint para elegir método de pago</td>
    <td>Crear endpoint que permita la elección del método de pago para la suscripción.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK02</td>
    <td>Implementar validación de métodos de pago</td>
    <td>Validar los métodos de pago disponibles y su correcto funcionamiento.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US10</td>
    <td rowspan="2">Crear y asignar tareas a los trabajadores</td>
    <td>TK03</td>
    <td>Crear endpoint para asignar tareas</td>
    <td>Crear endpoint para asignar tareas a los trabajadores.</td>
    <td>5</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK04</td>
    <td>Crear lógica de asignación de tareas</td>
    <td>Implementar la lógica que permita asignar tareas según las capacidades y disponibilidad de los trabajadores.</td>
    <td>6</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US12</td>
    <td rowspan="2">Registrar progreso de tareas</td>
    <td>TK05</td>
    <td>Crear endpoint para registrar progreso de tareas</td>
    <td>Crear endpoint que permita registrar el progreso de las tareas asignadas.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK06</td>
    <td>Implementar validación de progreso</td>
    <td>Validar que el progreso de las tareas sea registrado correctamente en el sistema.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US13</td>
    <td rowspan="2">Buscar y contactar a dueños de granjas potenciales</td>
    <td>TK07</td>
    <td>Crear endpoint para buscar dueños de granjas</td>
    <td>Crear endpoint que permita buscar y contactar a dueños de granjas potenciales.</td>
    <td>5</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK08</td>
    <td>Implementar lógica de contacto</td>
    <td>Implementar la lógica que permita contactar a los dueños de granjas potenciales de manera efectiva.</td>
    <td>5</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US14</td>
    <td rowspan="2">Ver información detallada de granjas</td>
    <td>TK09</td>
    <td>Crear endpoint para obtener detalles de granjas</td>
    <td>Crear endpoint que permita obtener información detallada de las granjas.</td>
    <td>4</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK10</td>
    <td>Implementar validación de datos de granjas</td>
    <td>Validar que los datos obtenidos de las granjas sean precisos y completos.</td>
    <td>4</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US15</td>
    <td rowspan="2">Buscar granjas con filtros específicos</td>
    <td>TK11</td>
    <td>Crear endpoint para buscar granjas con filtros</td>
    <td>Crear endpoint que permita buscar granjas utilizando filtros específicos.</td>
    <td>5</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK12</td>
    <td>Implementar lógica de filtrado</td>
    <td>Implementar la lógica que permita aplicar filtros en la búsqueda de granjas.</td>
    <td>5</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US16</td>
    <td rowspan="2">Acceder a valoraciones y comentarios de otras empresas sobre las granjas</td>
    <td>TK13</td>
    <td>Crear endpoint para valoraciones y comentarios</td>
    <td>Crear endpoint que permita acceder a valoraciones y comentarios de otras empresas sobre las granjas.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK14</td>
    <td>Implementar validación de valoraciones</td>
    <td>Validar que las valoraciones y comentarios sean precisos y relevantes.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US18</td>
    <td rowspan="2">Verificar niveles de inventario</td>
    <td>TK15</td>
    <td>Crear endpoint para verificar inventario</td>
    <td>Crear endpoint que permita verificar los niveles de inventario.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK16</td>
    <td>Implementar lógica de verificación de inventario</td>
    <td>Implementar la lógica que permita verificar los niveles de inventario de manera precisa.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US19</td>
    <td rowspan="2">Ver información detallada sobre el estado de cultivos y ganado</td>
    <td>TK17</td>
    <td>Crear endpoint para obtener estado de cultivos</td>
    <td>Crear endpoint que permita obtener información detallada sobre el estado de cultivos y ganado.</td>
    <td>4</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK18</td>
    <td>Implementar validación de estado de cultivos</td>
    <td>Validar que la información sobre el estado de cultivos y ganado sea precisa.</td>
    <td>4</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US20</td>
    <td rowspan="2">Ver estadísticas financieras</td>
    <td>TK19</td>
    <td>Crear endpoint para obtener estadísticas financieras</td>
    <td>Crear endpoint que permita obtener estadísticas financieras detalladas.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK20</td>
    <td>Implementar lógica de estadísticas</td>
    <td>Implementar la lógica que permita calcular y mostrar estadísticas financieras.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US21</td>
    <td rowspan="2">Registrar el cumplimiento de tareas con detalles de producción</td>
    <td>TK21</td>
    <td>Crear endpoint para registrar cumplimiento de tareas</td>
    <td>Crear endpoint que permita registrar el cumplimiento de tareas con detalles de producción.</td>
    <td>5</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK22</td>
    <td>Implementar validación de cumplimiento</td>
    <td>Validar que el cumplimiento de tareas y los detalles de producción sean registrados correctamente.</td>
    <td>5</td>
    <td>Franco Barrionuevo</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US22</td>
    <td rowspan="2">Emitir alertas de emergencia de manera eficaz</td>
    <td>TK23</td>
    <td>Crear endpoint para emitir alertas de emergencia</td>
    <td>Crear endpoint que permita emitir alertas de emergencia de manera eficaz.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK24</td>
    <td>Implementar lógica de alertas de emergencia</td>
    <td>Implementar la lógica que permita emitir y gestionar alertas de emergencia.</td>
    <td>4</td>
    <td>Luciano Ruiz</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US23</td>
    <td rowspan="2">Registrar horas de trabajo para cálculo de salario</td>
    <td>TK25</td>
    <td>Crear endpoint para registrar horas de trabajo</td>
    <td>Crear endpoint que permita registrar las horas de trabajo de los empleados para el cálculo de salario.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK26</td>
    <td>Implementar validación de horas de trabajo</td>
    <td>Validar que las horas de trabajo registradas sean precisas para el cálculo de salario.</td>
    <td>4</td>
    <td>Augusto Pin</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US24</td>
    <td rowspan="2">Registrar cantidad de ganado enfermo</td>
    <td>TK27</td>
    <td>Crear endpoint para registrar ganado enfermo</td>
    <td>Crear endpoint que permita registrar la cantidad de ganado enfermo.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK28</td>
    <td>Implementar validación de registros de ganado enfermo</td>
    <td>Validar que los registros de ganado enfermo sean precisos y actualizados.</td>
    <td>4</td>
    <td>Franz Escalante</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US26</td>
    <td rowspan="2">Verificar estado de actividades diarias y tiempo dedicado por los trabajadores</td>
    <td>TK29</td>
    <td>Crear endpoint para verificar estado de actividades diarias</td>
    <td>Crear endpoint que permita verificar el estado de actividades diarias y el tiempo dedicado por los trabajadores.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK30</td>
    <td>Implementar validación de actividades diarias</td>
    <td>Validar que los registros de actividades diarias y tiempo dedicado sean precisos.</td>
    <td>4</td>
    <td>Rodrigo Aguilar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US30</td>
    <td rowspan="2">Crear API RESTful para acceder a datos agrícolas y ganaderos</td>
    <td>TK31</td>
    <td>Diseñar y crear API RESTful</td>
    <td>Diseñar y crear una API RESTful que permita acceder a datos agrícolas y ganaderos.</td>
    <td>6</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TK32</td>
    <td>Implementar endpoints de datos agrícolas y ganaderos</td>
    <td>Implementar los endpoints necesarios para acceder y gestionar datos agrícolas y ganaderos.</td>
    <td>6</td>
    <td>Mathias Kunimoto</td>
    <td>Done</td>
  </tr>
</table>


### 5.2.3.3 Development Evidence for Sprint Review.

| Repository                                                      | Branch                     | Commit id | Commit Message                                                | Committed on (Date) |
|-----------------------------------------------------------------|----------------------------|--------|---------------------------------------------------------------|---------------------|
| https://farmlogitech-op.web.app/home)                           | feature/dashboard-analitycs|3e468c  | feature: Add method put                                       | 21/05/2024          |
|                                                                 | feature/dashboard-analitycs|d25e83  | feature: Added image filed to farm                             | 21/05/2024          |
|                                                                 | feature/dashboard-analitycs|c642ae  | feat(profiles-managment): Added profile and user.              | 21/05/2024          |
|                                                                 | feature/dashboard-analitycs|b37c18  | feat: add get subscription by id query to subscriptions        | 27/05/2024          |
|                                                                 | feature/dashboard-analitycs|294127  | feat: add social-interaction bounded context                   | 28/05/2024          |
|                                                                 | feature/dashboard-analitycs|bbf1a6  | feat: add all records                                          | 31/05/2024          |
|                                                                 | feature/dashboard-analitycs|2be2c3  | feat(task): repository created and the table are running :)    | 01/06/2024          |
|                                                                 | feature/dashboard-analitycs|c3eabf  | feat(task): Implemented task controller.                       | 01/06/2024          |
|                                                                 | feature/dashboard-analitycs|791547  | feat(feature/task): Added Queries get all task by collaborator with fa… | 01/06/2024          |
|                                                                 | feature/dashboard-analitycs|f0ece0  | feat(feature/dashboard-analitycs): Add aggregates Income and Expense.  | 02/06/2024          |
|                                                                 | feature/monitoring         |8677d1  | fix: update README                                            | 26/05/2024          |
|                                                                 | feature/monitoring         |b3bf62  | feat: add subscription bounded context                        | 26/05/2024          |
|                                                                 | feature/monitoring         |328889  | feat: add subscription command and query service impl          | 26/05/2024          |
|                                                                 | feature/monitoring         |e5e69b  | fix: subscription repository and command service impl fixed    | 26/05/2024          |
|                                                                 | feature/social-interaction |294127  | feat: add social-interaction bounded context                  | 28/05/2024          |
|                                                                 | feature/social-interaction |d7a80b  | feat: fix endpoint and add commands in readme                  | 28/05/2024          |
|                                                                 | feature/profiles-managment |c41ef5  | fix(social interaction): Added valueobject                   | 29/05/2024          |
|                                                                 | feature/profiles-managment |c59490  | feature(social interaction): Update subscription aggregate   | 30/05/2024          |
|                                                                 | feature/profiles-managment |e1fde1  | feature(social-interaction): Added update profile.           | 30/05/2024          |
|                                                                 | feature/profiles-managment |5a142a  | feature(profiles-managment): Update user aggregate           | 30/05/2024          |
|                                                                 | feature/profiles-managment |f7663f  | feature(profiles-managment): Add profileId in subscriptions  | 31/05/2024          |
|                                                                 | feature/profiles-managment |294158  | feature(profiles-managment): Updated get all socials interactions by … | 31/05/2024          |
|                                                                 | feature/subscription       |d72697  | feat: add update subscription command servioce and implementations | 30/05/2024          |
|                                                                 | feature/task               |623d8e  | feat(aggregate): task aggregate created  | 31/05/2024          |
|                                                                 | feature/task               |1d324f  | feat(task): create task command         | 31/05/2024          |
|                                                                 | feature/task               |f524de  | feat(task): add command to aggregate    | 31/05/2024          |
|                                                                 | feature/task               |a10634  | feat(task): create queries               | 31/05/2024          |
|                                                                 | feature/task               |2e4ad5  | feat(task): create services              | 31/05/2024          |


### 5.2.3.4 Testing Suite Evidence for Sprint Review.

Para la entrega del Sprint 3, logramos completar el desarrollo, la implementación y el despliegue del Landing Page, Frontend App y RESTFulAPI. Por esta razón, nos enfocamos en la sección de "acceptance-tests" en la implementación de los archivos feature que componen nuestro proyecto. Estos features se basan en las Historias de Usuario especificadas en el sprint backlog, detallando cada uno de los escenarios que planeamos desarrollar.
<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>landing-page</td>
    <td>Features_testing</td>
    <td>07fa8d6</td>
    <td>Augusto Pin</td>
    <td>doc: add acceptance tests</td>
    <td>11/05/2024</td>
  </tr>
</table>

### 5.2.3.5 Execution Evidence for Sprint Review.
En el sprint 3 se logró un desarrollo parcial tanto del frontend como del backend de la aplicación web.
Este avance incluye nuevas vistas relevantes sobre el producto y la startup, disponibles en inglés y español, así como una versión responsive.
A continuación, se presentan algunas evidencias:

- US09
  <img src="/Assets/img-website-page-9.png" alt="US09"/></img>

- US10
  <img src="/Assets/img-website-page-13.png" alt="US10"/></img>

- US12
  <img src="/Assets/img-website-page-14.png" alt="US12"/></img>

- US14
  <img src="/Assets/img-website-page-7.png" alt="US14"/></img>

- US15
  <img src="/Assets/img-website-page.png" alt="US15"/></img>

- US16
  <img src="/Assets/img-website-page-8.png" alt="US16"/></img>

- US18
  <img src="/Assets/img-website-page-15.png" alt="US18"/></img>

- US20
  <img src="/Assets/img-statics.png" alt="US20"/></img>

- US21
  <img src="/Assets/img-us-21.png" alt="US21"/></img>

- US22
  <img src="/Assets/img-website-page-16.png" alt="US22"/></img>

- US26
  <img src="/Assets/img-hours.png" alt="US24"/></img>


### 5.2.3.6 Services Documentation Evidence for Sprint Review.

Para el sprint 3, se planificó el front-end como el back-end. Inicialmente, se trabajó con el mismo github creando repositorios en donde
incluimos el db.json para luego enlazarlo llamandolo con la creación de rutas.

<img src="/Assets/img-repo1-json.png" alt="Repo 1"/></img>
<img src="/Assets/img-repo2-json.png" alt="Repo 2"/></img>
<img src="/Assets/img-repo3-json.png" alt="Repo 3"/></img>
<img src="/Assets/img-repo4-json.png" alt="Repo 4"/></img>
<img src="/Assets/img-repo5-json.png" alt="Repo 5"/></img>

| Endpoint           | Details                                                                                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /subscription-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /profile-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /farm-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /user-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /task-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /social-controller    | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /shed-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /income-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /expense-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /crop-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /animal-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /message-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |

### Web Service:

| Endpoint                | Operaciones | Parámetros       | URL                                                    |
|-------------------------|-------------|------------------|--------------------------------------------------------|
| subscription-controller | PUT         | {profileId}      | /api/v1/subscription/pay/subscription/{profileId}                                           |
|                         | POST        | No tiene         | /api/v1/subscription                          |
|                         | GET         | {id}             | api/v1/crops/{cropId}/tunnels                          |
|                         | GET         | No tiene         | /api/v1/subscription/all                |
| profile-controller      | GET         | {profileId}      | /api/v1/profile/{profileId}                           |
|                         | PUT         | {profileId}      | /api/v1/profile/{profileId}                                       |
|                         | POST        | No tiene         | /api/v1/profile                           |
|                         | GET         | No tiene         | /api/v1/profile/all                           |
| farm-controller         | GET         | {id}             | /api/v1/farm/{id}                          |
|                         | PUT         | {id}             | /api/v1/farm/{id}                                       |
|                         | POST        | No tiene         | /api/v1/farm                         |
|                         | GET         | {location}       | /api/v1/farm/location/{location}                           |
|                         | GET         | No tiene         | /api/v1/farm/all                         |
|                         | GET         | {profileId}        | /api/v1/farm/all/farms/profile/{profileId}                          |
| user-controller         | POST        | No tiene         | /api/v1/user                                       |
|                         | GET         | No tiene         | /api/v1/user/all                          |
| task-controller         | POST        | No tiene         | /api/v1/task                                      |
|                         | GET         | {farmerId}       | /api/v1/task/all/farmer/{farmerId}                          |
|                         | GET         | {collaboratorId} | /api/v1/task/all/collaborator/{collaboratorId}                          |
| social-controller       | POST        | No tiene         | /api/v1/socials                                      |
|                         | GET         | No tiene         | /api/v1/socials/all                         |
|                         | GET         | {id}             | /api/v1/socials/all/farm/{id}                         |
| shed-controller         | POST        | No tiene         | /api/v1/shed                                      |
|                         | GET         | {id}             | /api/v1/shed/{id}                         |
|                         | GET         | No tiene         | /api/v1/shed/all                        |
| income-controller       | POST        | No tiene         | /api/v1/income                                     |
| expense-controller      | POST        | No tiene         | /api/v1/expense                                     |
| crop-controller         | POST        | No tiene         | /api/v1/crop                                      |
|                         | GET         | {id}             | /api/v1/crop/{id}                         |
|                         | GET         | No tiene         | /api/v1/crop/all                       |
| animal-controller       | POST        | No tiene         | /api/v1/animal                                      |
|                         | GET         | {id}             | /api/v1/animal/{id}                         |
|                         | GET         | No tiene         | /api/v1/animal/all                       |
| message-controller      | POST        | {collaboratorId} | /api/v1/messages/collaborator/{collaboratorId}                                   |

### Web service images:
#### Subscriptions Controller:
<img src="/Assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>
<img src="/Assets/img-subscriptions-controller-2.png" alt="subscriptions-controller-2"/></img>

#### Profile Controller:
<img src="/Assets/profile-controller-1.png" alt="profile-controller-1"/></img>
<img src="/Assets/profile-controller-2.png" alt="profile-controller-2"/></img>

#### Farm Controller:
<img src="/Assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>
<img src="/Assets/img-farm-controller-2.png" alt="farm-controller-2"/></img>

#### User Controller:
<img src="/Assets/img-user-controller.png" alt="user-controller-1"/></img>
<img src="/Assets/img-user-controller-2.png" alt="user-controller-2"/></img>

#### Task Controller:
<img src="/Assets/img-task-controller-1.png" alt="task-controller-1"/></img>

#### Social Controller:
<img src="/Assets/img-social-controller-1.png" alt="social-controller-1"/></img>

#### Shed Controller:
<img src="/Assets/img-shed-controller.png" alt="shed-controller"/></img>


#### Income Controller:
<img src="/Assets/img-income-controller.png" alt="income-controller"/></img>

#### Expense Controller:
<img src="/Assets/img-expense-controller.png" alt="expense-controller"/></img>

#### Crop Controller:
<img src="/Assets/img-crop-controller-1.png" alt="crop-controller"/></img>
<img src="/Assets/img-crop-controller-2.png" alt="crop-controller-2"/></img>
<img src="/Assets/img-crop-controller-3.png" alt="crop-controller-3"/></img>

#### Animal Controller:
<img src="/Assets/img-animal-controller-1.png" alt="animal-controller"/></img>

#### Message Controller:
<img src="/Assets/img-message-controller.png" alt="message-controller"/></img>

#### Link del repositorio:
(https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op.git)

#### Web service commit details:

| Repository                                                      | Branch                     | Commit id | Commit Message                                                | Committed on (Date) |
|-----------------------------------------------------------------|----------------------------|--------|---------------------------------------------------------------|---------------------|
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                          | feature/dashboard-analitycs|3e468c  | feature: Add method put                                       | 21/05/2024          |
|   https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                              | feature/dashboard-analitycs|d25e83  | feature: Added image filed to farm                             | 21/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|c642ae  | feat(profiles-managment): Added profile and user.              | 21/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|b37c18  | feat: add get subscription by id query to subscriptions        | 27/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|294127  | feat: add social-interaction bounded context                   | 28/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|bbf1a6  | feat: add all records                                          | 31/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|2be2c3  | feat(task): repository created and the table are running :)    | 01/06/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|c3eabf  | feat(task): Implemented task controller.                       | 01/06/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|791547  | feat(feature/task): Added Queries get all task by collaborator with fa… | 01/06/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/dashboard-analitycs|f0ece0  | feat(feature/dashboard-analitycs): Add aggregates Income and Expense.  | 02/06/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/monitoring         |8677d1  | fix: update README                                            | 26/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/monitoring         |b3bf62  | feat: add subscription bounded context                        | 26/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/monitoring         |328889  | feat: add subscription command and query service impl          | 26/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/monitoring         |e5e69b  | fix: subscription repository and command service impl fixed    | 26/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/social-interaction |294127  | feat: add social-interaction bounded context                  | 28/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/social-interaction |d7a80b  | feat: fix endpoint and add commands in readme                  | 28/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/profiles-managment |c41ef5  | fix(social interaction): Added valueobject                   | 29/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/profiles-managment |c59490  | feature(social interaction): Update subscription aggregate   | 30/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/profiles-managment |e1fde1  | feature(social-interaction): Added update profile.           | 30/05/2024          |
|  https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                               | feature/profiles-managment |5a142a  | feature(profiles-managment): Update user aggregate           | 30/05/2024          |
|  https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                               | feature/profiles-managment |f7663f  | feature(profiles-managment): Add profileId in subscriptions  | 31/05/2024          |
|  https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                               | feature/profiles-managment |294158  | feature(profiles-managment): Updated get all socials interactions by … | 31/05/2024          |
|  https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                               | feature/subscription       |d72697  | feat: add update subscription command servioce and implementations | 30/05/2024          |
|  https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                               | feature/task               |623d8e  | feat(aggregate): task aggregate created  | 31/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/task               |1d324f  | feat(task): create task command         | 31/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/task               |f524de  | feat(task): add command to aggregate    | 31/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/task               |a10634  | feat(task): create queries               | 31/05/2024          |
| https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op                                                                | feature/task               |2e4ad5  | feat(task): create services              | 31/05/2024          |

### 5.2.3.7 Software Deployment Evidence for Sprint Review.

Para la entrega del tercer sprint, se implementó una landing page completamente funcional, cumpliendo
con los user stories correspondientes. También se desplegó y por otro lado se lanzó parcialmente el back-end, el cual aún no está finalizado.

Landin Page:

La actualización de la página de destino en GitHub Pages se realizó tras fusionar la rama "develop" con la rama principal ("main"). Este proceso permitió renovar la implementación de la página de destino.

- Capturas de pantalla landing page:
  <img src="/Assets/img-landing-page-1.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-2.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-3.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-4.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-5.png" alt="landing-page"/></img>

- Web Application Front-end:

Prueba de que esta enlazado con el Netlify

<img src="/Assets/img-deployment.png" alt="landing-page"/></img>

- Capturas de pantalla landing page:

  <img src="/Assets/img-website-page.png" alt="website"/></img>
  <img src="/Assets/img-website-page-4.png" alt="website"/></img>
  <img src="/Assets/img-website-page-6.png" alt="website"/></img>
  <img src="/Assets/img-website-page-7.png" alt="website"/></img>
  <img src="/Assets/img-website-page-9.png" alt="website"/></img>
  <img src="/Assets/img-website-page-12.png" alt="website"/></img>

- Web Application Back-end:

  <img src="/Assets/img-base-de-dato-workbrench-1.png" alt="Base de datos"/></img>
  <img src="/Assets/img-base-de-dato-workbrench-2.png" alt="Base de datos"/></img>


- Capturas de pantalla de Web Application:

<img src="/Assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>
<img src="/Assets/profile-controller-1.png" alt="profile-controller-1"/></img>
<img src="/Assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>


### 5.2.3.8 Insights de Colaboración del Equipo durante el Sprint

Durante este sprint (21 de abril de 2024 - 22 de junio de 2024), nuestro equipo logró avances significativos en los tres repositorios: Landing Page, Aplicación Web (Frontend) y Backend. A continuación, se presenta un desglose detallado de las contribuciones más representativas de cada miembro:

| Miembro del Equipo | Contribuciones Clave                                                                                                     |
|---------------------|--------------------------------------------------------------------------------------------------------------------------|
| Rodrigo Aguilar (Rodrag0lvr) | - Implementó funcionalidades de dashboard y análisis (Backend)<br>- Desarrolló servicios de gestión de tareas<br>        |
| Janiel Escalante | - Implementó el contexto acotado de interacción social (Backend)<br>- Desarrolló servicios de gestión de clima<br>       |
| Mathias Kunimoto (kuni2005) | - Implementó servicios de suscripción y monitoreo (Backend)<br>- Desarrolló funcionalidades de gestión de inventario<br> |
| Augusto Pin (GutoPin) | - Implementó servicios de interacción social (Backend)<br>- Desarrolló funcionalidades de gestión de suscripciones<br>   ||
| Luciano Ruiz | - Implementó funcionalidades de dashboard y análisis (Backend)<br>- Desarrolló servicios de gestión de tareas<br>        |

#### Insights de los Repositorios

1. Repositorio Landing Page:
   (https://github.com/Open-Source-WX55-Group-UFriends/landing-page.git)

   <img src="/Assets/img-repo-landing.png" alt="message-controller"/>
   <img src="/Assets/img-contributors-tb2.png" alt="message-controller"/>
   <img src="/Assets/participacion_landing_luciano.png" alt="message-controller"/>
   <img src="/Assets/participacion_landing_franz.png" alt="message-controller"/>
   
   Observaciones:
   - La participación de Luciano Ruiz y Franz en el repositorio de la landing page no se vio reflejada en los insights debido a problemas con la sincronización de github.
   Logros clave:
   - Completado el diseño responsivo para todos los tamaños de pantalla
   - Implementada la carga dinámica de contenido para mejorar el rendimiento

2. Repositorio de la Aplicación Web (Frontend):
   (https://github.com/Open-Source-WX55-Group-UFriends/Frontend-App.git)

   <img src="/Assets/img-repo-front.png" alt="message-controller"/>
   <img src="/Assets/img-contributors-tb2-frontend.png" alt="message-controller"/>

   Patrones de colaboración:
   - Se observaron dos grandes impulsos de desarrollo: a principios de mayo y a principios de junio
   - Contribuciones constantes durante todo el sprint

3. Repositorio Backend:
   (https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op.git)

   <img src="/Assets/img-repo-backend.png" alt="message-controller"/>
   <img src="/Assets/img-contributors-tb2-backend.png" alt="message-controller"/>

   Métricas notables:
   - Un total de 50 commits entre todo el equipo
   - Más de 21,000 líneas de código añadidas, indicando un desarrollo significativo de características

Los gráficos de contribución muestran un esfuerzo bien distribuido entre el equipo, con un aumento de actividad hacia el final del sprint debido a las fases de integración y pruebas. El repositorio backend vio la mayor actividad, reflejando nuestro enfoque en construir una API robusta para soportar nuestra aplicación web.

De cara al futuro, nuestro objetivo es mantener este nivel de colaboración mientras nos enfocamos en una distribución más uniforme de commits entre todos los miembros del equipo.

### 5.3. Validation Interviews.
Dentro de la sección "Validation Interviews" de nuestro proyecto, nos enfocamos en perfeccionar la aplicación web destinada a
la gestión de granjas, y publicar anuncios para conectar granjas con empresarios. Tuvimos entrevistas interactivas con
nuestros usuarios primordiales: los duesños de granjas, trabajadores de estas y empresarios interesados en establecer alianzas estratégicas con granjas.
A través de entrevistas estructuradas, nos proponemos captar las impresiones y sugerencias del segmento objetivo.

#### 5.3.1 Diseño de Entrevistas.
En esta parte, se describen los objetivos específicos de los usuarios que guían nuestras entrevistas. Estos objetivos de usuario son fundamentales para
asegurar que la plataforma web satisfaga las necesidades reales de los usuarios en la industria avícola y ganadera. A continuación, se presentan los
objetivos de usuario mencionados:

- **User Goal: Iniciar Sesion**  
  User persona: Dueños de granja, trabajadores de granja y empresarios.  
  El usuario debe ingresar a la aplicación web y visualizará el botón sign in. Si tiene una cuenta el usuario inicia sesión, y en caso de no tener una se crea una cuenta. Después de esto el usuario podrá ver las características de acuerdo al tipo de usuario que es.



- **User Goal: Navegar por los anuncios de granjas**  
  User persona: Dueños de granja y empresarios.  
  El usuario ingresa a la aplicación visualiza la vista home y se muestra un listado en formato grilla en 4 columnas y filas ilimitadas, las cuales despliegan los datos de cada una de las granjas.


- **User Goal: Navegar por las diferentes opciones de monitoreo.**  
  User persona: Trabajadores de granja.
  El usuario debe ingresar a la aplicación web y loguearse respectivamente, luego en el navbar presionar la opción de monitoring y posteriormente podrá visualizar los apartados de monitoreo y navegar por las opciones.


- **User Goal: Crear una nueva emergencia**  
  User persona: Trabajadores de granja, Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción emergencia. Aquí podrán enviar mensajes de emergencia describiendolos de manera que puedan llevar a todos los encargados de la granja.


- **User Goal: Añadir cosas al inventario**  
  User persona: Trabajadores de granja, Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción inventory. Después de esto el usuario podrá visualizar todos los apartados del inventario, de manera que podrá añadir todos los items necesarios navegando por la sidebar y rellenando los datos para cada apartado.


- **User Goal: Crear una nueva tarea**  
  User persona: Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción task. Después de esto el usuario le da click a create task y rellena los datos que se requieren. Después de esto la tarea ya se habrá creado.

- **User Goal: Crear una nuevo empleado**  
  User persona: Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción Employee. Luego de esto el usuario entrará en el apartado de Employees y le hará click a Add employee. Finalmente el usuario le da click a add employee y rellena los datos que se requieren. Después de esto el empleado ya se habrá creado.

- **User Goal: Trabajar con datos estadisticos**  
  User persona: Dueños de granja.
  Una vez logueado en la aplicación web presiona la opción de monitoring en la navbar y posteriormente a la opción Statistics. Luego de esto el usuario se dirigirá al apartado de estadísticas donde podrá trabajar con datos estadísticos.

- **User Goal: Contactar con dueños de granjas y darles una reseña**  
  User persona: Empresario.
  Una vez logueado el usuario en la aplicación web podrá visualizar todas las granjas disponibles para un acuerdo comercial. El usuario deberá hacer click a su granja de interés, de manera que deslizando el slide podrá visualizar el apartado de contacto. Aqui le podrá dar click al botón chat on Whatsapp o simplemente rellenar sus datos de contacto para que el granjero se comunique con el usuario.





#### 5.3.2. Registro de Entrevistas.
**Primer segmento objetivo (Dueño de granja):**

Entrevista de validación usuario dueño de granja 01:

Inicio:00:00 <br>
Fin: 1:32:00

| Entrevistado  01             	                                                                  | Jorge Kunimoto 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/Assets/img-entrevista-3.png" alt="message-controller"/></img>                      	 | Jorge Kunimoto fue entrevistado por Mathias Kunimoto acerca del servicio para manejar una granja tanto en su ámbito interno como externo. Durante la conversación, Jorge destacó la utilidad del servicio, mencionando que le parece una herramienta interesante para la gestión agrícola. Sin embargo, también ofreció algunas recomendaciones para mejorarla. Sugerió agregar un sector en la parte de roles (trabajadores) para que los empleados puedan dar su feedback sobre las necesidades que tienen, así como incluir un apartado de emergencias donde se pueda registrar el descanso médico. Otra sugerencia fue interconectar los tres roles para crear un buzón de mensajes, ya que a veces no se entienden bien las tareas asignadas. Según Jorge, estas mejoras podrían incrementar la eficiencia y la comunicación dentro de la granja, haciendo el servicio aún más valioso.         	 |
| Timing: 42:59 / Fin: 56:46 / Duracion: 13:47	                                                   | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EXAcj83ERHtPoZgYPm_f4uQBELiIyG7Vh0XDwtcCOeFHag?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjoyNTc5LjAwNiwidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=DJkqjs 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |


| Entrevistado  02             	                                                                    | Mirian Watanabe	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/Assets/img-entrevista-4.png" alt="message-controller"/></img>                        	 | Mirian Watanabe fue entrevistada por Mathias Kunimoto acerca del servicio para manejar una granja tanto en su ámbito interno como externo. Durante la conversación, Mirian destacó la utilidad del servicio, considerándolo una herramienta interesante para la gestión agrícola. Sin embargo, también ofreció algunas recomendaciones para mejorarlo. Sugirió agregar en el sector de inventario una sección de almacén para guardar herramientas típicas de una granja, como palas y escaleras. A pesar de esto, mencionó que el proyecto está bien distribuido en general. Según Mirian, esta mejora podría optimizar la organización y el manejo de recursos dentro de la granja, aumentando la eficiencia del servicio.        	 |
| Timing: 31:03 / Fin: 42:59 / Duracion: 11:56	                                                     | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EXAcj83ERHtPoZgYPm_f4uQBELiIyG7Vh0XDwtcCOeFHag?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjoxODYzLjI0NywidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=kvLCkz 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |




**Segundo segmento objetivo (Trabajador de granja):**


| Entrevistado  01             	                                                                    | Lucero Barrionuevo	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/Assets/img-entrevista-2.png" alt="message-controller"/></img>                        	 | Lucero Barrionuevo fue entrevistada acerca del servicio para manejar una granja tanto en su ámbito interno como externo. Durante la conversación, Lucero destacó la utilidad del servicio, mencionando que le parece una herramienta interesante para la gestión agrícola. Sin embargo, también ofreció una recomendación para mejorarla. Sugirió agregar conexiones para mejorar la comunicación entre los usuarios, lo que podría contribuir a reducir la carga de trabajo y evitar que se sientan explotados. Según Lucero, esta mejora podría incrementar la eficiencia y el bienestar de los trabajadores, haciendo el servicio aún más efectivo y equilibrado.       	 |
| Timing: 56:47 / Fin: 1:15:02 / Duracion: 18:16                                                    | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EXAcj83ERHtPoZgYPm_f4uQBELiIyG7Vh0XDwtcCOeFHag?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjozNDA3Ljk2MywidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=kYL9Ly 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |



Entrevista de validación usuario trabajador de granja 02:

| Entrevistado  02             	                                                                 | Rodrigo Noreña  	                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/Assets/img-entrevista-5.png" alt="message-controller"/></img>                        	 | Rodrigo Noreña Nuñez, un joven trabajador en granjas, fue entrevistado para evaluar la usabilidad del sitio web de FarmLogitech. Durante la entrevista, se le presentó cómo agregar un empleador, loguearse, crear un perfil y crear "cards", que son representaciones de las granjas en la plataforma. Rodrigo comentó sobre su experiencia y facilidad de uso del sitio web, proporcionando retroalimentación valiosa para mejorar la funcionalidad y la interfaz del usuario.          	 |
| Timing: 1:15:03	/ Fin: 1:32:00 / Duracion: 16:58                                               | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EXAcj83ERHtPoZgYPm_f4uQBELiIyG7Vh0XDwtcCOeFHag?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjo0NTAzLjkxOSwidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=7izle5 	                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |    

**Tercer segmento objetivo (Empresario):**

Entrevista de validación administrado de una empresa 01:


 Entrevistado  01             	                                                                    | Soledad Quispe  	                                                                                                                                                                                                        |
|---------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/Assets/img-entrevista-6.png" alt="message-controller"/></img>                        	 | Durante la entrevista Soledad, reviso las características que nuestra aplicación le ofrece a su segmento objetivo. Su único descontento fue que la pagina pueda cambiar de idioma ya que ella no habla inglés.          	 |
| Timing: 0:00 / Fin: 9:34 / Duracion: 9:34 	                                                       | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EXAcj83ERHtPoZgYPm_f4uQBELiIyG7Vh0XDwtcCOeFHag?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjowLjQ5MiwidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=IVWAWA 	                                                                                                                                                                                                        |

Entrevista de validación administrado de una empresa 02:

| Entrevistado  02             	                                                                    | Jorge Nestor  	                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/Assets/img-entrevista-7.png" alt="message-controller"/></img>                        	 | Durante la entrevista Jorge, reviso las características que nuestra aplicación le ofrece a su segmento objetivo. Las recomendaciones de Jorge fueron que el idioma no concuerda, ya que hay botones en ingles y otros en español. Por otro lado, deberian verse las reseñas que hicieron otras personas para tenerlas en cuenta         	                                                                                                                                                                                        |
| Timing: 9:35 / Fin: 18:11 / Duracion: 8:36  	                                                     | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EXAcj83ERHtPoZgYPm_f4uQBELiIyG7Vh0XDwtcCOeFHag?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjo1NzUuMDk2LCJ0aW1lc3RhbXBlZExpbmtSZWZlcnJlckluZm8iOnsic2NlbmFyaW8iOiJDaGFwdGVyU2hhcmUiLCJhZGRpdGlvbmFsSW5mbyI6eyJpc1NoYXJlZENoYXB0ZXJBdXRvIjpmYWxzZX19fSwicmVmZXJyYWxJbmZvIjp7InJlZmVycmFsQXBwIjoiU3RyZWFtV2ViQXBwIiwicmVmZXJyYWxWaWV3IjoiU2hhcmVDaGFwdGVyTGluayIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19&e=A0smD7 

Entrevista de validación administrado de una empresa 03:

| Entrevistado  03             	                                                                    | Cesar Pin 	                                                                                                                                                                                                              |
|---------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="/Assets/img-entrevista-1.png" alt="message-controller"/></img>                        	 | Augusto Pin entrevistó al Sr. César Pin, presentándole su página web, FarmLogiTech. Durante la conversación, César Pin elogió la utilidad y el diseño general del sitio, mencionando que le pareció una herramienta muy valiosa para su propósito. No obstante, también ofreció algunas sugerencias para mejorarla. César Pin señaló que la inclusión de animaciones más atractivas y detalladas podría enriquecer la experiencia del usuario, además de recomendar interfaces gráficas más elaboradas para hacer la navegación y el uso de la página más intuitivos y visualmente agradables. Estas mejoras, según él, podrían incrementar aún más la eficacia y el atractivo de FarmLogiTech.          	 |
| Timing: 18:11 / Fin: 31:02 / Duracion: 12:51	                                                     | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EXAcj83ERHtPoZgYPm_f4uQBELiIyG7Vh0XDwtcCOeFHag?nav=eyJwbGF5YmFja09wdGlvbnMiOnsic3RhcnRUaW1lSW5TZWNvbmRzIjoxMDkxLjA3NiwidGltZXN0YW1wZWRMaW5rUmVmZXJyZXJJbmZvIjp7InNjZW5hcmlvIjoiQ2hhcHRlclNoYXJlIiwiYWRkaXRpb25hbEluZm8iOnsiaXNTaGFyZWRDaGFwdGVyQXV0byI6ZmFsc2V9fX0sInJlZmVycmFsSW5mbyI6eyJyZWZlcnJhbEFwcCI6IlN0cmVhbVdlYkFwcCIsInJlZmVycmFsVmlldyI6IlNoYXJlQ2hhcHRlckxpbmsiLCJyZWZlcnJhbEFwcFBsYXRmb3JtIjoiV2ViIiwicmVmZXJyYWxNb2RlIjoidmlldyJ9fQ&e=cFrCPS	                                                                                                                                                                                                       |



#### 5.3.3. Evaluaciones según heurísticas.
**WEB APP A EVALUAR**  
*FarmLogiTech*  
Nuestro propósito es encontrar problemas existentes en nuestra aplicación web. Para ello, utilizaremos las heurísticas de Nielsen,
las cuales nos permitirán identificar problemas de usabilidad y experiencia de usuario. A continuación, se presentan las tareas a evaluar:

**TAREAS A EVALUAR**

- Web App
   1. El idioma de la aplicación debe poder cambiarse Escala de severidad: 4 Heuristica Relacionada: Usability: Consistencia y estándres
   2. Deberian haber mas animaciones y transciones a la hora de establecer farms y tasks
   3. Falta de Feedback de los Trabajadores
   4. Falta de Apartado en seccion de Emergencias
   5. Falta de Comunicación entre Roles
   6. Falta de Sección de Almacén en el Inventario
   7. Falta de Conexiones para Mejorar la Comunicación


**ESCALA DE SEVERIDAD:**  
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| Nivel 	| Descripción 	                                                                                                                                                                                              |
|-------	|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     	| Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.           	                   |
| 2     	| Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase           	 |
| 3     	| Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.           	                                |
| 4     	| Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.           	                              |

**TABLA RESUMEN:**

**Web Application**

| # 	 | Problema 	                                                                         | Escala de severidad 	 | Heurística/Principio violada(o) 	                                       |
|-----|------------------------------------------------------------------------------------|-----------------------|-------------------------------------------------------------------------|
| 1 	 | El idioma de la aplicación debe poder cambiarse      	                             | 4                   	 | Usability: Consistencia y estándres                               	     |
| 2 	 | Deberian haber mas animaciones y transciones a la hora de establecer farms y tasks | 1                     | Usability- Estética y diseño minimalista                              	 |
| 3 	 | Falta de Feedback de los Trabajadores      	                                       | 2                   	 | Usability - Coincidencia entre el sistema y el mundo real         |
| 4 	 | Falta de Apartado en seccion de Emergencias        	                               | 2                   	 | Usability - Coincidencia entre el sistema y el mundo real            |
| 5 	 | Falta de Comunicación entre Roles      	                                       | 3                   	 | Usability - Consistencia y estándares         |
| 6	  |  Falta de Sección de Almacén en el Inventario        	                               | 2                   	 | Usability - Coincidencia entre el sistema y el mundo real            |
| 7   |  Falta de Conexiones para Mejorar la Comunicación       	                               | 3                   	 | Usability - Flexibilidad y eficiencia de uso            |



### PROBLEMA #01: El idioma de la aplicación debe poder cambiarse:

**Escala de severidad:** 04

**Principio violado:** Usability: Consistencia y estándres

**Descripción del problema:** Nuestros usuarios actulamente hablan español y no todos entienden inglés, por lo tanto la aplicación debe permitir cambiar de idioma

**Recomendacion:** Para solucionar este problema debe agregarse I18n a la aplicación.

### PROBLEMA #02: El idioma de la aplicación debe poder cambiarse:

Deberian haber mas animaciones y transciones a la hora de establecer farms y tasks

**Escala de severidad:** 01

*Heuristica Relacionada:*

Usability- Estética y diseño
minimalista

*Descripción del problema:*

Nuestros usuarios podrian querer una interfaz mas animada o una interfaz grafica visualmente bonita y para saber que se esta constatando bien las acciones que estan haciendo

*Recomendacion:*

Para solucionar este problema debe implementar mas estilos en la parte del frontend, junto a transciones y componentes que solucionen el problema de la interfaz aburrida y sin dinamismo.


## Problema #03: Falta de Feedback de los Trabajadores

**Persona entrevistada:** Jorge Kunimoto

**Escala de severidad:** 02

**Principio violado:** Usability - Coincidencia entre el sistema y el mundo real

**Descripción del problema:** No existe un sector en la parte de roles (trabajadores) donde los empleados puedan dar su feedback sobre sus necesidades. Esto puede limitar la capacidad de la gestión para entender y atender las necesidades del personal, afectando su motivación y eficiencia.

**Recomendación:** Incluir un sector específico en la plataforma donde los trabajadores puedan dar su feedback y expresar sus necesidades.


## Problema #04: Falta de Apartado de Emergencias

**Persona entrevistada:** Jorge Kunimoto

**Escala de severidad:** 02

**Principio violado:** Usability - Coincidencia entre el sistema y el mundo real

**Descripción del problema:** No hay un apartado de emergencias donde se pueda registrar el descanso médico de los trabajadores. La ausencia de este apartado puede dificultar la gestión de situaciones de emergencia y la salud del personal, afectando la operación eficiente de la granja.

**Recomendación:** Agregar un apartado específico en la plataforma para registrar y gestionar descansos médicos y emergencias.

## Problema #05: Falta de Comunicación entre Roles

**Persona entrevistada:** Jorge Kunimoto

**Escala de severidad:** 03

**Principio violado:** Usability - Consistencia y estándares

**Descripción del problema:** Los tres roles no están interconectados para crear un buzón de mensajes, lo que dificulta la comprensión y asignación de tareas. Esta falta de comunicación clara puede llevar a malentendidos y errores en la ejecución de las tareas, afectando la productividad.

**Recomendación:** Implementar un sistema de mensajería interno que interconecte los tres roles para facilitar la comunicación y coordinación de tareas.


## Problema #06: Falta de Sección de Almacén en el Inventario

**Persona entrevistada:** Mirian Watanabe

**Escala de severidad:** 02

**Principio violado:** Usability - Coincidencia entre el sistema y el mundo real

**Descripción del problema:** No hay una sección de almacén en el sector de inventario para guardar herramientas típicas de una granja, como palas y escaleras. La ausencia de esta sección puede dificultar la organización y el acceso a las herramientas necesarias, afectando la eficiencia operativa.

**Recomendación:** Agregar una sección de almacén en el inventario para organizar y almacenar herramientas y equipos de la granja.


## Problema #07: Falta de Conexiones para Mejorar la Comunicación

**Persona entrevistada:** Lucero Barrionuevo

**Escala de severidad:** 03

**Principio violado:** Usability - Flexibilidad y eficiencia de uso

**Descripción del problema:** No hay conexiones adecuadas para mejorar la comunicación entre los usuarios, lo que puede llevar a una sobreexplotación del personal. La falta de comunicación efectiva puede resultar en una carga de trabajo desbalanceada y en la disminución del bienestar del personal, afectando la productividad y la moral.

**Recomendación:** Establecer conexiones y canales de comunicación efectivos entre los usuarios para asegurar una distribución equilibrada de las tareas y mejorar el bienestar del personal.

## 5.3.4. Sprint 4
### 5.3.4.1. Sprint Planning 4
El spring 4 tiene como inicio el dia 12/06/2024 y como objetivo plantea conectar el backend con el frontend y desplegar todos nuestros servicios

<table>
<tr><td>Sprint #</td><td>Sprint 4</td></tr>
<tr><td colspan="2">Sprint Planning Background</td></tr>
<tr><td>Date</td><td>2024-06-12</td></tr>
<tr><td>Time</td><td>7:00 PM</td></tr>
<tr><td>Location</td><td>Meet virtual meeting</td></tr>
<tr><td>Prepared by</td><td>Rodrigo Aguilar</td></tr>
<tr><td>Atendees</td><td>Mathias Kunimoto, Franz Escalante, Augusto Pin y Luciano Ruiz</td></tr>
<tr><td>Sprint 4 Review</td><td>En el Sprint 4 implementamos todos nuestros servicios y codigo en el frontend de manera que tengamos nuestra aplicacion funcional y lista para lanzarse, gracias a nuestros anteriores sprints dedicados a el desarrollo del frontend y backend.</td></tr>
<tr><td>Sprint 4 Retrospective</td><td>En el anterior sprint pudimos mejorar la organizacion de codigo y el como distribuirlo y aislarlo por secciones para que sea mas facil de trabajar, junto a definir la logica de negocio para una mejor experiencia del usuario.</td></tr>
<tr><td colspan="2">Sprint Goal & User Stories</td></tr>
<tr><td>Sprint 4 Goal</td><td>Implementar el backend y conectarlo al frontend para desplegar tanto nuestro servicio de API Rest como la aplicacion en si para que pueda ser distribuida.</td></tr>
<tr><td>Sprint 4 Velocity</td><td>15</td></tr>
<tr><td>Sum of story points</td><td>15</td></tr>
</table>

### 5.3.4.2. Sprint Backlog 4

En este sprint backlog, desarrollamos la implementacion de nuestros endpoint de nuestra API que ha estado siendo desarrollada desde el sprint 3, siendo utilizada en el frontend para recopilar y mostrar datos de nuestra base de datos desplegada en AWS.

<img src="/Assets/Trello-Sprint4.png" alt="message-controller"/></img>

Link del trello: https://trello.com/b/WJXt50JP/farmlogitech

| Technical User Story | WorkItem / Task                                   |      |                                                               |                                                                                                                                                              ||||
|----------------------|---------------------------------------------------|------|---------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|------|--------------|--------|
| Id                   | Title                                             | Id   | Title                                                         | Description                                                                                                                                                  | Estimation (Hours) | **Assigned To** | **Status** |
| US20                 | Crear un perfil de trabajador                     | TK33 | Conexión de backend con frontend del apartado de trabajadores | Conectar el API existente con el frontend de filtros y metodos relacionados con la administración de empleados en la empresa.                                | 4 | **Luciano Ruiz** | **Done** |
| US02                 | Vinculo entre el Landing Page y la Aplicación Web | TK34 | Configurar autenticación para acceso a la aplicación          | Implementar en el backend la lógica de autenticación necesaria para permitir el acceso seguro desde la landing page a la aplicación web.                     | 5 | **Mathias Kunimoto** | **Done** |
| US03                 | Crear y asignar tareas a los trabajadores         | TK35 | Mejora de la interfaz de gestión de tareas                    | Conectar la interfaz existente para permitir al dueño de la granja crear y asignar tareas a los trabajadores de manera más eficiente.                        | 6 | **Franz Escalante** | **Done** |
| US05                 | Registrar progreso de tareas                      | TK36 | Mejora de la API para registro de progreso de tareas          | Actualizar la API en el backend para mejorar la capacidad de los trabajadores de registrar y actualizar el progreso de sus tareas asignadas.                 | 5 | **Augusto Pin** | **Done** |
| US10                 | Verificar niveles de inventario                   | TK37 | Mejora del sistema de seguimiento de inventario               | Conectar el sistema existente con el frontend para rastrear y actualizar los niveles de inventario de productos agrícolas y ganaderos de manera más precisa. | 8 | **Rodrigo Aguilar** | **Done** |


### 5.3.4.3 Development Evidence for Sprint Review.

| Repository                                                      | Branch                     | Commit id | Commit Message                                                | Committed on (Date) |
|-----------------------------------------------------------------|----------------------------|---------|----------------------------------------------------------|---------------------|
| https://farmlogitech-op.web.app/home)                           | feature/develop            | 1925bb1 | fix: add autentication routes                               | 21/05/2024          |
|                                                                 | feature/develop            | 4f64216 | feat: Add create profile                                    | 21/05/2024          |
|                                                                 | feature/search-and-match   | 9a5be05 | fix: Add new farm                                           | 20/06/2024          |
|                                                                 | feature/monotoring         | 51c3163 | fix: Add role in profile card                               | 20/06/2024          |
|                                                                 | feature/monotoring         | 38d37fe | fix: look role                                              | 20/06/2024          |
|                                                                 | feature/monotoring         | 7baa711 | fix: Get role                                               | 20/06/2024          |
|                                                                 | feature/search-and-match   | d1008f1 | fix: Add create profile with toolbar                        | 20/06/2024          |
|                                                                 | feature/develop            | 538b6be | fix: get role                                               | 20/06/2024          |
|                                                                 | feature/develop            | 52bf5e3 | fix: get profile                                            | 20/06/2024          |
|                                                                 | feature/search-and-match   | a80d021 | fix: Add create profile                                     | 20/06/2024          |
|                                                                 | feature/monotoring         | 9c7cb77 | feat: add sheds                                             | 22/06/2024          |
|                                                                 | feature/monotoring         | 5b27cdd | feat: Update the user interface for employees               | 22/06/2024          |
|                                                                 | feature/monotoring         | a9d486a | feat: created profile to employees                          | 22/06/2024          |
|                                                                 | feature/search-and-match   | c3ada33 | feat: Add input search by location                          | 22/06/2024          |
|                                                                 | feature/search-and-match   | 0ead5da | feat: merge with search and match                           | 22/06/2024          |
|                                                                 | feature/develop            | 992645b | feat: Add farm description                                  | 22/06/2024          |
|                                                                 | feature/monotoring         | 9e1b5c3 | feat: add animal and add crops                              | 22/06/2024          |
|                                                                 | feature/monotoring         | 9a212c1 | feat: fix sheds ddl from inventory                          | 23/06/2024          |
|                                                                 | feature/develop            | 297b9b2 | Merge branch 'feature/monitoring' into develop              | 23/06/2024          |
|                                                                 | feature/search-and-match   | c87daaf | feat: Update inventory                                      | 23/06/2024          |
|                                                                 | feature/search-and-match   | ad62640 | feat: Update farm description                               | 23/06/2024          |
|                                                                 | feature/develop            | fef6c9c | fix: height of login card container                         | 24/06/2024          |
|                                                                 | feature/develop            | f223830 | feat: add role selector tu sign up                          | 24/06/2024          |
|                                                                 | feature/develop            | 3867e53 | feat: Update message with farmer                            | 24/06/2024          |
|                                                                 | feature/develop            | 833dc9a | feat: Add message in farmworker                             | 24/06/2024          |
|                                                                 | feature/monotoring         | 49c240a | feat: Update task view for employee                         | 24/06/2024          |
|                                                                 | feature/monotoring         | ffc8abb | feat: Add task for employees                                | 24/06/2024          |
|                                                                 | feature/develop            | 1d3194b | feat: Update authentication to farm edit                    | 24/06/2024          |
|                                                                 | feature/monotoring         | 1a1494e | feat: Update method put in farm                             | 24/06/2024          |

### 5.3.4.4 Testing Suite Evidence for Sprint Review

| Repository                            | Branch | Commit Id      | Commit Message   | Commit Message Body   | Commited on (Date) |
|---------------------------------------|--------|----------------|------------------|-----------------------|--------------------|
| Open-Source-WX55-Group-UFriends | "main" | feat(testing)  | testing evidence | test of farm-logitech | 23/06/2024         |

#### Subscription repository test 
<img src="/Assets/img-testing.png" alt="message-controller"/></img>

#### Aws test

<img src="/Assets/img-testo-aws.png" alt="message-controller"/></img>

### 5.3.4.5 Execution Evidence for Sprint Review.
En el sprint 4 se logró un desarrollo parcial tanto en la conexion del frontend como del backend de la aplicación web.
Este avance incluye nuevas vistas relevantes sobre el producto y la startup, disponibles en inglés y español, así como una versión responsive.
A continuación, se presentan algunas evidencias:

- US09
  <img src="/Assets/img-website-page-9.png" alt="US09"/></img>

- US14
  <img src="/Assets/img-website-page-7.png" alt="US14"/></img>

- US15
  <img src="/Assets/img-website-page.png" alt="US15"/></img>

- US16
  <img src="/Assets/img-website-page-8.png" alt="US16"/></img>

- US21
  <img src="/Assets/img-us-21.png" alt="US21"/></img>

- US22
  <img src="/Assets/img-website-page-16.png" alt="US22"/></img>


### 5.3.4.6 Services Documentation Evidence for Sprint Review.

Para el sprint 4, se planificó la conexión del  front-end con el back-end. Inicialmente, se trabajó con el mismo github creando repositorios en donde
incluimos el db.json para luego enlazarlo llamandolo con la creación de rutas.

| Endpoint           | Details                                                                                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /subscription-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /profile-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /farm-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /user-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /task-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /social-controller    | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /shed-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /income-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /expense-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /crop-controller   | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /animal-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |
| /message-controller | Se implementaron las operaciones CRUD en base.service.ts, logrando que las funcionalidades de creación local y obtención de todos los registros desde el db.json. |

Link del repositorio: https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op

### Web Service:

| Endpoint                | Operaciones | Parámetros       | URL                                                    |
|-------------------------|-------------|------------------|--------------------------------------------------------|
| subscription-controller | PUT         | {profileId}      | /api/v1/subscription/pay/subscription/{profileId}                                           |
|                         | POST        | No tiene         | /api/v1/subscription                          |
|                         | GET         | {id}             | api/v1/crops/{cropId}/tunnels                          |
|                         | GET         | No tiene         | /api/v1/subscription/all                |
| profile-controller      | GET         | {profileId}      | /api/v1/profile/{profileId}                           |
|                         | PUT         | {profileId}      | /api/v1/profile/{profileId}                                       |
|                         | POST        | No tiene         | /api/v1/profile                           |
|                         | GET         | No tiene         | /api/v1/profile/all                           |
| farm-controller         | GET         | {id}             | /api/v1/farm/{id}                          |
|                         | PUT         | {id}             | /api/v1/farm/{id}                                       |
|                         | POST        | No tiene         | /api/v1/farm                         |
|                         | GET         | {location}       | /api/v1/farm/location/{location}                           |
|                         | GET         | No tiene         | /api/v1/farm/all                         |
|                         | GET         | {profileId}        | /api/v1/farm/all/farms/profile/{profileId}                          |
| user-controller         | POST        | No tiene         | /api/v1/user                                       |
|                         | GET         | No tiene         | /api/v1/user/all                          |
| task-controller         | POST        | No tiene         | /api/v1/task                                      |
|                         | GET         | {farmerId}       | /api/v1/task/all/farmer/{farmerId}                          |
|                         | GET         | {collaboratorId} | /api/v1/task/all/collaborator/{collaboratorId}                          |
| social-controller       | POST        | No tiene         | /api/v1/socials                                      |
|                         | GET         | No tiene         | /api/v1/socials/all                         |
|                         | GET         | {id}             | /api/v1/socials/all/farm/{id}                         |
| shed-controller         | POST        | No tiene         | /api/v1/shed                                      |
|                         | GET         | {id}             | /api/v1/shed/{id}                         |
|                         | GET         | No tiene         | /api/v1/shed/all                        |
| income-controller       | POST        | No tiene         | /api/v1/income                                     |
| expense-controller      | POST        | No tiene         | /api/v1/expense                                     |
| crop-controller         | POST        | No tiene         | /api/v1/crop                                      |
|                         | GET         | {id}             | /api/v1/crop/{id}                         |
|                         | GET         | No tiene         | /api/v1/crop/all                       |
| animal-controller       | POST        | No tiene         | /api/v1/animal                                      |
|                         | GET         | {id}             | /api/v1/animal/{id}                         |
|                         | GET         | No tiene         | /api/v1/animal/all                       |
| message-controller      | POST        | {collaboratorId} | /api/v1/messages/collaborator/{collaboratorId}                                   |

### Web service images:
#### Subscriptions Controller:
<img src="/Assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>

#### Profile Controller:
<img src="/Assets/profile-controller-1.png" alt="profile-controller-1"/></img>

#### Farm Controller:
<img src="/Assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>

#### User Controller:
<img src="/Assets/img-user-controller.png" alt="user-controller-1"/></img>



### 5.3.4.7 Software Deployment Evidence for Sprint Review.

Para la entrega del cuarto sprint, se implementó una landing page completamente funcional, cumpliendo
con los user stories correspondientes. También se desplegó y por otro lado se lanzó parcialmente el back-end terminado.

Landing Page:

La actualización de la página de destino en GitHub Pages se realizó tras fusionar la rama "develop" con la rama principal ("main"). Este proceso permitió renovar la implementación de la página de destino.

- Capturas de pantalla landing page:
  <img src="/Assets/img-landing-page-1.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-2.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-3.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-4.png" alt="landing-page"/></img>
  <img src="/Assets/img-landing-page-5.png" alt="landing-page"/></img>

- Web Application Front-end:

Prueba de que esta enlazado con el Github pages

<img src="/Assets/img-deployment-today.png" alt="landing-page"/></img>

- Capturas de pantalla landing page:

  <img src="/Assets/img-website-page.png" alt="website"/></img>
  <img src="/Assets/img-website-page-4.png" alt="website"/></img>
  <img src="/Assets/img-website-page-6.png" alt="website"/></img>
  <img src="/Assets/img-website-page-7.png" alt="website"/></img>
  <img src="/Assets/img-website-page-9.png" alt="website"/></img>
  <img src="/Assets/img-website-page-12.png" alt="website"/></img>

- Web Application Back-end:

  <img src="/Assets/img-base-de-dato-workbrench-1.png" alt="Base de datos"/></img>
  <img src="/Assets/img-base-de-dato-workbrench-2.png" alt="Base de datos"/></img>

Prueba de que esta enlazado con Aws

<img src="/Assets/img-testo-aws.png" alt="landing-page"/></img>

- Capturas de pantalla de Web Application:

<img src="/Assets/img-subscriptions-controller-1.png" alt="subscriptions-controller-1"/></img>
<img src="/Assets/profile-controller-1.png" alt="profile-controller-1"/></img>
<img src="/Assets/img-farm-controller-1.png" alt="farm-controller-1"/></img>


### 5.4. Video About-The-Product.
A continuación, se muestra el video "Acerca del producto", el cual ilustra el propósito, beneficios y características principales de la aplicación.
Enlace para visualizar el video About the product
Enlace del video subido a Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211f978_upc_edu_pe/Edq2VQ_tLzFCuAXx0OFjGtYB5vx7IIgmk30-tS2SMn8z3A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=12oa9I

### Video About-The-Team.

Link del about the team subido en youtube: https://youtu.be/a_Oygo-rW28

Link del about the team subido en Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/EbYt973d3sxCqDbrdSWNQW8B8ls31bD_P7GLliAS32oenQ?e=Qvr5gT&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

### Link de la exposicion

Link de la exposicion en Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210148_upc_edu_pe/ERfwdAQEr49FpzZ6UkObzmoBvTVkY3upyvJoQhoeU6ID3Q?e=hsz9Dj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


# VI. Conclusiones y recomendaciones.
## Conclusiones

1. **Problem Statements:**
   - El desarrollo de FarmLogiTech como proyecto de curso ha abordado teóricamente la falta de herramientas tecnológicas integradas en la industria agrícola y ganadera. Nuestro diseño propone una solución para el monitoreo en tiempo real del estado de los cultivos, el bienestar animal y las condiciones climáticas, lo cual podría facilitar la toma de decisiones informadas y la optimización de la producción.
   - El proyecto ha explorado formas de mejorar la colaboración entre empresas y dueños de granjas, proponiendo mecanismos para facilitar asociaciones beneficiosas que podrían impulsar el crecimiento y la rentabilidad en la cadena de suministro agrícola.

2. **Assumptions vs. Comportamiento real de los segmentos:**
   - La asunción de que los dueños de granjas y trabajadores utilizarían la plataforma durante toda su jornada laboral se mantiene como una hipótesis que requeriría validación en un escenario real.
   - La hipótesis sobre el interés de las empresas grandes en utilizar la plataforma para establecer una mejor comunicación con las granjas es prometedora, pero necesitaría ser probada en el mercado real.

3. **Hypothesis Statements:**
   - El diseño del sistema de seguimiento y análisis de datos agrícolas propuesto tiene el potencial de mejorar la toma de decisiones y la eficiencia en las operaciones agrícolas, pero esto necesitaría ser validado en la práctica.
   - La inclusión de funcionalidades de pronóstico meteorológico en nuestro diseño parece valiosa en teoría, pero su efectividad real requeriría pruebas de campo.
   - La interfaz intuitiva y fácil de usar que hemos diseñado apunta a una mayor satisfacción del usuario, pero esto necesitaría ser confirmado con pruebas de usabilidad reales.

4. **Criterios de Éxito vs. Expectativas del Proyecto:**
   - Los objetivos de crecimiento, adopción y eficiencia establecidos en nuestro proyecto son ambiciosos y están bien fundamentados en nuestra investigación, pero su viabilidad solo podría ser determinada mediante una implementación real.
   - Las mejoras en eficiencia operativa, reducción de tiempo en gestión de tareas y disminución de incidencias críticas que hemos proyectado son metas realistas basadas en nuestro análisis, pero requerirían validación en un entorno operativo real.

5. **Conclusiones técnicas:**
   - El uso de Lean UX, fue de gran ayuda gracias a su enfoque iterativo, que  permite adaptarse rápidamente a los cambios del la aplicación y las necesidades del usuario, promoviendo así la eficiencia al desarrollar el producto.
   - Conventional Commits establecio un estándar para mensajes de confirmación claros y estructurados, lo que facilitó la comprensión del historial de cambios.
   - Los diagramas de arquitectura de dominio facilitaron la comprensión de las relaciones entre el dominio y sus contextos delimitados
   - Como equipo buscamos priorizar la comprensión profunda del negocio y su contexto, mediante la colaboración entre expertos técnicos y de dominio.
   - El enfoque en la modularidad y la reutilización de código de Angular agilizó el proceso de desarrollo.
   - El uso de Springboot nos ayudo gracias a su capacidad para gestionar fácilmente la lógica de negocios, la persistencia de datos y la integración con tecnologías externas
   - As-Is mapping nos proporcionó una comprensión detallada de los procesos existentes, identificando puntos débiles y oportunidades de mejora. Por otro lado, en el To-Be mapping, mostramos la visión futura del proceso optimizado, destacando los cambios planificados y las mejoras esperadas, sirviendo como guía para la transformación y la innovación.
   - Nuestra aplicación puede ayudar a gobiernos regionales y locales a impulsar la modernización de la industria al  permitir mejorar y controlar los procesos productivos
## Recomendaciones

Basándonos en el desarrollo de FarmLogiTech como proyecto de curso y en nuestro análisis teórico, recomendamos los siguientes pasos para un potencial Roadmap de desarrollo futuro:

1. **Validación de Conceptos:**
   - Realizar pruebas de concepto con un prototipo funcional en un entorno controlado, como una granja piloto, para validar las funcionalidades clave.
   - Conducir entrevistas y encuestas detalladas con potenciales usuarios (dueños de granjas, trabajadores y empresas) para refinar los requisitos y características del producto.

2. **Desarrollo Iterativo:**
   - Implementar un enfoque de desarrollo ágil, comenzando con un Producto Mínimo Viable (MVP) que incluya las funcionalidades más críticas identificadas en nuestro proyecto.
   - Establecer ciclos de retroalimentación tempranos y frecuentes con usuarios beta para iterar y mejorar el producto.

3. **Expansión Gradual de Funcionalidades:**
   - Priorizar el desarrollo de módulos core como la gestión de tareas, monitoreo de cultivos y animales, y herramientas de comunicación.
   - Planificar la integración futura de tecnologías avanzadas como IA y IoT, basándose en la retroalimentación de los usuarios iniciales.

4. **Estrategia de Entrada al Mercado:**
   - Desarrollar un plan de lanzamiento por fases, comenzando con un grupo selecto de granjas para un período de prueba extensivo.
   - Diseñar una estrategia de marketing enfocada en demostrar el valor tangible de FarmLogiTech a través de casos de estudio y testimonios de usuarios piloto.

5. **Consideraciones de Escalabilidad y Sostenibilidad:**
   - Investigar y planificar la infraestructura tecnológica necesaria para soportar un crecimiento potencial del número de usuarios y volumen de datos.
   - Incorporar desde el inicio prácticas de desarrollo sostenible y considerar el impacto ambiental de la implementación tecnológica en el sector agrícola.

Estas recomendaciones buscan trazar un camino desde el proyecto académico actual hacia una potencial implementación real de FarmLogiTech, reconociendo la necesidad de validación y refinamiento continuos basados en retroalimentación del mundo real.



# VII. Bibliografía.
Ministerio de Desarrollo Agrario y Riego. (s.f.). Plan Nacional Ganadero.
https://www.midagri.gob.pe/portal/download/pdf/especiales/plan-nacional-ganadero.pdf

Actualidad Ganadera. (s.f.). INEI actualiza cifras oficiales sobre nuestro sector ganadero.
https://actualidadganadera.com/inei-actualiza-cifras-oficiales-sobre-sobre-nuestro-sector-ganadero/

Ministerio de Desarrollo Agrario y Riego. (2023). Informe mensual avícola, abril 2023.
https://siea.midagri.gob.pe/portal/phocadownload/datos_estadisticas/mensual/Avicola/2023/avicola_04_2023.pdf

Instituto Nacional de Estadística e Informática. (2022). Estadísticas del sector ganadero.
https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib1912/libro.pdf

Infobae. (2023, 22 de marzo). Crisis en el sector avícola: Precio del pollo se eleva, granjas quebradas y millones de aves sacrificadas por influenza. https://www.infobae.com/peru/2023/03/22/crisis-en-el-sector-avicola-precio-del-pollo-se-eleva-granjas-quebradas-y-millones-de-aves-sacrificadas-por-influenza/

AviNews. (2023, 14 de noviembre). Brote de influenza aviar en granja de postura comercial en Perú. https://avinews.com/peru-se-presenta-brote-de-influenza-aviar-en-granja-de-postura-comercial/

Gobierno Regional de Lima. (2021, 3 de mayo). Productores de Barranca apuestan por el cultivo de maracuyá. https://www.gob.pe/regionlima

Moran, K. (2016). The Four Dimensions of Tone of Voice. Nielsen Norman Group. https://www.nngroup.com/articles/tone-of-voice-dimensions/

Gothelf, J., & Seiden, J. (2021). Lean UX, 3rd Edition. https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/

Progressa Lean. (2014). 5W+2H Técnica de análisis de problemas - Progressa Lean. Progressa Lean. https://www.progressalean.com/5w2h-tecnica-de-analisis-de-problemas/

UX Planet. (2017). Information Architecture. Basics for Designers. - UX Planet. Medium; UX Planet. https://uxplanet.org/information-architecture-basics-for-designers-b5d43df62e20

Gothelf, J. (2024). Leanux Sampler. https://es.scribd.com/document/655516553/Leanux-Sampler

Infobae. (2023, 22 de marzo). Crisis en el sector avícola: Precio del pollo se eleva, granjas quebradas y millones de aves sacrificadas por influenza. https://www.infobae.com/peru/2023/03/22/crisis-en-el-sector-avicola-precio-del-pollo-se-eleva-granjas-quebradas-y-millones-de-aves-sacrificadas-por-influenza/

AviNews. (2023, 14 de noviembre). Brote de influenza aviar en granja de postura comercial en Perú. https://avinews.com/peru-se-presenta-brote-de-influenza-aviar-en-granja-de-postura-comercial/

Gobierno Regional de Lima. (2021, 3 de mayo). Productores de Barranca apuestan por el cultivo de maracuyá. https://www.gob.pe/regionlima

Ganadera, P. (2021, 22 octubre). Guía para montar una granja. Material Ganadero Para Granjas Proyectos Agrícolas. https://peigganadera.com/guia-montar-una-granja/

Sanchez, L. (2023, 30 junio). Cómo iniciar tu propia granja avícola: consejos y consideraciones clave. AmericaAgro. https://americaagro.com/como-iniciar-tu-propia-granja-avicola-consejos-y-consideraciones-clave/

Pardo, J. (2023, 8 noviembre). DDD y arquitectura Onion, todo lo que necesitas saber. Paradigma Digital. https://www.paradigmadigital.com/techbiz/domain-driven-design-y-arquitectura-onion/

Fernández, R. G. (2022). Microservicios y Domain Driven Design (DDD): un enfoque práctico a la arquitectura de software. Izertis. https://www.izertis.com/es/-/blog/microservicios-domain-driven-design

Domain driven design | Modyo Docs. (2023). https://docs.modyo.com/es/architecture/patterns/ddd.html

Ibáñez, Y. G. (2024, 29 febrero). Patrones de arquitectura: organización y estructura de microservicios. Paradigma Digital. https://www.paradigmadigital.com/dev/patrones-arquitectura-organizacion-estructura-microservicios/

Candelario, L. (2021, 18 octubre). Arquitecturas limpias y DDD, un recorrido práctico. Parte 2. Sixphere Technologies. https://sixphere.com/blog/arquitecturas-limpias-ddd-parte-2/

RobBagby. (2024). Patrón Backends for Frontends - Azure Architecture Center. Microsoft Learn. https://learn.microsoft.com/es-es/azure/architecture/patterns/backends-for-frontends

GeeksforGeeks. (2024, 20 febrero). JavaScript for Backend Development. GeeksforGeeks. https://www.geeksforgeeks.org/javascript-backend-basics/

Pragma. (2023). Academia Pragma | Ruta Backend Node JS. https://www.pragma.com.co/academia/universo/galaxia-ingenieria/backend-nodejs

S, R. A. (2023, 6 octubre). How to Use Node Js for Backend Web Development in 2024. Simplilearn.com. https://www.simplilearn.com/tutorials/nodejs-tutorial/nodejs-backend

# VIII. Anexos.

- Registro de entrevistas: https://upcedupe-my.sharepoint.com/personal/u201912668_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu201912668%5Fupc%5Fedu%5Fpe%2FDocuments%2FInterviews%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E9ce4d8dc%2D3266%2D48c0%2D9695%2D4ae0d1270660
- Trello: https://trello.com/invite/b/H1ovwIyt/ATTIa06b8aa26ddc1b1aa652cdb1647fd69f7C984655/aplicaciones-web
- Enlace de Miro: https://miro.com/app/board/uXjVKYvs29U=/?share_link_id=40902593860
- Prouct Backlog: https://www.pivotaltracker.com/n/projects/2700504
- Structurizr: https://structurizr.com/share/83579/bbb84c20-9e26-49cd-9773-c0e5e00ed182
- Organización Github: https://github.com/Open-Source-WX55-Group-UFriends
- Landing Page: https://github.com/Open-Source-WX55-Group-UFriends/landing-page
- Backend: https://github.com/Open-Source-WX55-Group-UFriends/farmLogitech-backend-op.git
- Reporte Final: https://github.com/Open-Source-WX55-Group-UFriends/Report-Final-Project









