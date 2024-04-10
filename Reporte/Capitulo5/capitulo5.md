# Capítulo V: Product Implementation, Validation & Deployment
## 5.1 Software Configuration Management
A continuación, presentaremos el proceso por el cual organizamos, gestionamos y controlamos los cambios en el desarrollo de este proyecto.
### 5.1.1. Software Development Environment Configuration.
**Requirements Management**
1. Trello: Es una herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente basados en marcos de
   trabajos ágiles. Será empleado para visualizar y actualizar el estado actual de las tareas e historias de usuario
   pertenecientes al sprint a desarrollar. Ruta de referencia https://trello.com/es
  

**Product UX/UI Design**

1. Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizado para el diseño digital. En el
   caso del proyecto, será utilizado para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.
   Ruta de referencia https://www.figma.com/login
2. Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama de
   clases asociado a la aplicación. Ruta de referencia https://www.lucidchart.com/
     
 **Software Testing**
1. Gherkin: Es un sistema de etiquetado utilizado para describir los criterios de aceptación de estructura de una user story.
   Ruta de referencia https://cucumber.io/docs/gherkin/  

**Software Development**
1. Visual Studio Code: Entorno de desarrollo integrado elegido para la elaboración y compilación del código por motivos de
   dominio por parte de los integrantes del equipo de trabajo. Utilizar este IDE supone de valor para el desarrollo del
   proyecto puesto que incluye la posibilidad de agregar extensiones de utilidad, soporte de edición de texto en múltiples
   lenguajes de programación, disponibilidade en múltiples sistemas operativos, entre otros beneficios. Ruta de referencia
   https://code.visualstudio.com/  
   <br>
2. HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Será
   empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación. Ruta de referencia
   https://www.w3schools.com/html/html5_syntax.asp   
   <br>
3. CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la mano
   con HTML. Ruta de referencia https://google.github.io/styleguide/htmlcssguide.html
   <br>
   <br>
 4. Tailwind CSS: Es un conjunto de herramientas de utilidad de CSS altamente personalizable y orientado a clases. Se utilizará para diseñar y estilizar la interfaz de usuario dentro de la aplicación. Puedes encontrar información detallada en la documentación
oficial de Tailwind CSS: https://tailwindcss.com/docs
<br>
<br>
5. JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz de
   usuario dentro de la aplicación. Ruta de referencia https://developer.mozilla.org/es/docs/Web/JavaScript

 <br>

**Software Deployment**
1. Git: Una herramienta de control de versiones que facilita el registro y la gestión de las distintas versiones del programa. Su propósito es mantener un historial de cambios y simplificar la corrección de errores. Los integrantes del equipo 
   accederán a través de la línea de comandos en sus sistemas locales https://git-scm.com/
   <br>
   <br>
**Software Documentation and Project Management**
2. Github: Una plataforma en la nube que hospedará los repositorios de código del proyecto. Permitirá la colaboración en 
   tiempo real y la revisión de contribuciones de cada miembro del equipo. Los integrantes del equipo podrán acceder a través de sus navegadores web. https://github.com/


### 5.1.2. Source Code Management.
El proyecto seguirá las convenciones del flujo de trabajo establecido por el modelo GitFlow para el control de versiones, empleando GitHub como plataforma y sistema de control de versiones. A continuación, se describirá la implementación de GitFlow como un flujo de trabajo para el control de versiones, junto con el enlace del Landing Page.
  
**Repositorio de GitHub:** 
- Enlace para acceder a la [organización en GitHub](https://github.com/Open-Source-WX55-Group-UFriends)   
- Enlace para acceder al repositorio de la [landing Page](https://github.com/Open-Source-WX55-Group-UFriends/landing-page)
- Enlace para acceder al repositorio del [reporte final](https://github.com/Open-Source-WX55-Group-UFriends/Report-Final-Project)

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


**Gherkin:** Es un DSL (Lenguaje de Dominio Específico) diseñado para abordar la comunicación entre los equipos de negocios y técnicos al adoptar Behavior Driven Development (BDD). Se han empleado saltos de línea para organizar y distinguir los diversos tipos de escenarios de manera efectiva, buscando una práctica óptima. Además, se han utilizado palabras clave como "Given", "When", "Then" y 
"And" para estructurar los escenarios de manera clara y concisa.


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

--PARTE DE MATHI
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



<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 1</b></td>
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
       <td>US01</td>
       <td>Descripcion clara de los servicios</td>
       <td>T01</td>
       <td>Agregar divs para los servicios  en la landing page</td>
       <td>Diseñar los servicios que ofrecemos usando divs</td>
       <td>2</td>
       <td>Mathias Kunimoto</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US06</td>
       <td>Interacción de imágenes en la landing page</td>
       <td>T02</td>
       <td>Agregar un carrusel en la landing page</td>
       <td>Diseñar un carrusel para la interacción con el usuario</td>
       <td>2</td>
       <td>Rodrigo Aguilar </td>
       <td>Done</td>
    </tr>
<tr>
       <td>US02</td>
       <td> Planes de suscripción en la landing page</td>
       <td>T02</td>
       <td>Agregar divs para las suscripciones en la landing page</td>
       <td>Diseñar los planes que ofrecemos usando divs</td>
       <td>2</td>
       <td>Janiel Escalante</td>
       <td>Done</td>
    </tr>
<tr>
<tr>
       <td>US02</td>
       <td> Planes de suscripción en la landing page</td>
       <td>T02</td>
       <td>Agregar interacción con los planes</td>
       <td> Añadir la función hover para planes interactivos</td>
       <td>2</td>
       <td>Luciano Ruiz</td>
       <td>Done</td>
    </tr>
<tr>
       <td>US03</td>
       <td>Adaptación de landing page a dispositivos</td>
       <td>T02</td>
       <td>Agregar responsive </td>
       <td>Añadir responsive al landing page para que se pueda acoplar a cualquier dispositivo</td>
       <td>1</td>
       <td>Augusto Pin</td>
       <td>Done</td>
    </tr>

   </table>




#### 5.2.1.3. Development Evidence for Sprint Review.
| Repository  | Branch | Commit id | Commit Message|Commit Message Body | Commited on (Date)|
|-------------|--------|-----------|------------------------------------|--------------------|-------- 
|  https://github.com/Open-Source-WX55-Group-UFriends/landing-page|        | 09:00  AM | Reunión virtual mediante Google meet | Elaborar y diseñar una landing page atractiva e informativa para la aplicación  | PRODUCT BACKLOG   | PRODUCT BACKLOG  |

#### 5.2.1.5. Execution Evidence for Sprint Review.




























5.2.
Landing Page, Services & Applications Implementation.
5.2.1. Sprint 1
5.2.1.1.
5.2.1.2.
5.2.1.3.
5.2.1.4.
5.2.1.5.
5.2.1.6.
5.2.1.7.
5.2.1.8.
Sprint Planning 1.
Sprint Backlog 1.
Development Evidence for Sprint Review.
Testing Suite Evidence for Sprint Review.
Execution Evidence for Sprint Review.
Services Documentation Evidence for Sprint Review.
Software Deployment Evidence for Sprint Review.
Team Collaboration Insights during Sprint. 