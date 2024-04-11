# Capítulo IV: Product Design
## 4.1. Style Guidelines.


### 4.1.1. General Style Guidelines

*Branding:*
- Esta imagen simboliza nuestra dedicación a la agricultura y a los animales. Al unirse a nosotros, los usuarios experimentarán una conexión sólida y colaborativa, reflejada en nuestra comunidad.

<div align=center>
   <img src="/assets/logo-farm.jpeg" alt="Logo-farm"></img>
</div>

*Typography:*
- La tipografía de nuestro logotipo adoptará el elegante estilo Semi-bold, reconocido por su modernidad y su atractivo visual para nuestros usuarios. Este estilo no solo refleja la innovación y la creatividad que caracterizarán a nuestra aplicación, sino que también resalta la vanguardia que buscamos transmitir.

<div align=center>
   <img src="/assets/Font-typo.jpeg" alt="Font-typo"></img>
</div>
<br>

*Colors:*
- 
Nuestra paleta de colores se ha seleccionado para que al visitar nuestro sitio web, los usuarios sientan la atmósfera de una granja. El verde oscuro (#44604D) nos conecta con la naturaleza y la tierra, mientras que el verde claro (#25C95C) aporta frescura y vitalidad. El amarillo pálido (#FAFFDD) evoca la luz del sol sobre los cultivos. En conjunto, estos colores ofrecen una experiencia visual que refleja el ambiente y la energía de una granja.

<div align=center>
   <img src="/assets/palet-colors.jpeg" alt="palet-colors"></img>
</div>
<br>

### 4.1.2. Web Style Guidelines

*Icons:*

- Cuando se trata de diseñar una página web, los íconos juegan un papel crucial en la creación de una interfaz de usuario intuitiva y fácil de usar. Estos elementos visuales pequeños tienen el poder de mejorar la comprensión de los usuarios sobre la funcionalidad de diferentes partes de tu página. Los íconos permiten a los usuarios entender rápidamente la función de cada elemento y su simplicidad y claridad los hacen fácilmente comprensibles. Mantener una consistencia en el uso de íconos en toda la página ayuda a evitar confusiones entre los usuarios.
- Los que usaremos en el proyecto son los siguientes:

<br>

*Breackpoints*
- Los breakpoints más conocidos son los siguientes:

<br>

- Y los que usaremos en el proyecto principalmente son los de 768px y 1024px, ya que son los más comunes en los dispositivos móviles y de escritorio.

## 4.2. Information Architecture
### 4.2.1. Organization Systems

Al entrar a nuestro Website, el usuario podrá visualizar 3 secciones: El inicio, las tarifas, Login (Administradores) .

### 4.2.2. Labeling Systems


En el proyecto manejaremos un sistema de *etiquetado por facetas*, el cual consiste en la clasificación de los contenidos por categorías, las cuales se pueden combinar entre sí para encontrar un contenido específico.

Dichas categorías son:

- HomePage (Página de inicio)
- Login (Inicio de sesión)
- Register (Registro)
- Profile (Perfil)
- List of farms(Lista de granjas)
- Employee tasks(Tarea de empleados)
- Farm search (Búsqueda de granjas según el producto y la localización)

### 4.2.3. SEO Tags and Meta Tags

*Landing Page:* La página de inicio de nuestra aplicación contará con los siguientes tags:


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChambeaPe - Tu plataforma para encontrar empleo</title>
    <meta name="description" content="Encuentra empleo en Perú con ChambeaPe. Conectamos a empleadores y trabajadores de manera eficiente. ¡Regístrate y encuentra tu próximo trabajo!">
    <meta name="keywords" content="empleo, trabajo, Perú, búsqueda de empleo, ofertas de trabajo, empleos en Perú">
    <link rel="stylesheet" href="./assets/css/home.css">
    <link rel="shortcut icon" href="./assets/icons/Logo.svg" type="image/x-icon">

</head>



### 4.2.4. Searching Systems

En nuestro proyecto, facilitaremos a los usuarios la oferta de granjas que cumplan con sus requisitos específicos. Los usuarios podrán listar sus granjas según el tipo de producto que ofrecen, ya sea cultivos o animales, así como también podrán especificar la ubicación geográfica de sus granjas. Esto garantizará que los usuarios puedan mostrar fácilmente las características de sus granjas, mejorando así su visibilidad y accesibilidad en nuestra plataforma.

### 4.2.5. Navigation Systems

Para facilitar al usuario navegar por nuestro contenido, se utilizarán los siguientes sistemas de navegación:

- *Navegación principal o global:* Es el sistema de navegación más común, presente en todos los apartados de la página y usualmente representado por la barra de navegación y el footer.

<div align=center>
</div>

El patrón de lectura a utilizar para la visualización de nuestro website para las secciones que muestran contenido ligero será el patrón Z.
<div align=center>
<br>

</div>

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

<div align=center>
   <img src="/assets/Landing-Wireframe.png" alt="Landing-Wireframe"></img>
</div>


### 4.3.2. Landing Page Mock-up

<div align=center>
   <img src="/assets/Landing-Mock-up.png" alt="Landing-Mock-up"></img>
</div>

# 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes

<div align=center>
    <p>En la siguiente imagen, podemos observar los wireframes que se utilizan para poder publicar una granja.</p>
   <img src="/assets/Wireframe-Publicar-Anuncio-Sin-Conexion.jpg" alt="Wireframe-Publicar-Anuncio-Sin-Conexion"></img>
</div>

<div align=center>
    <p>En la siguiente imagen, se visualiza los wireframes que se utilizan para editar perfil.</p>
   <img src="/assets/Wireframe-Editar-Perfil-Sin-Conexion.jpg" alt="Wireframe-Editar-Perfil-Sin-Conexion"></img>
</div>

<div align=center>
<p>En la siguiente imagen, se visualiza los wireframes que usaran los trabajadores de las granjas al utilizar FarmLogitech para ver sus tareas asignadas</p>
   <img src="/assets/Wireframe-Monitoreo-Tasks-Sin-Conexion.jpg" alt="Wireframe-Monitoreo-Tasks-Sin-Conexion"></img>
</div>

<div align=center>
    <p>En la siguiente imagen se observa los wireframes que usará el administrador para poder ver ingresos y agresos a través de gráficos</p>
   <img src="/assets/Wireframe-Estadistica-Sin-Conexion.jpg" alt="Wireframe-Estadistica-Sin-Conexion"></img>
</div>

<div align=center>
   <p>En la siguiente imagen se observa los wireframes que usará el administrador o trabajador para poder mandar mensajes de emergencia a su jefe o compañeros</p>
   <img src="/assets/Wireframe-Mandar-Alerta-Sin-Conexion.jpg" alt="Wireframe-Mandar-Alerta-Sin-Conexion"></img>
</div>

### 4.4.2. Web Applications Wireflow Diagrams.

<div align=center>
    <p>Iniciar Sesion</p>
   <img src="/assets/Wireframe-Publicar-tu-anuncio.jpg" alt="Wireframe-Publicar-Anuncio"></img>
</div>

<div align=center>
    <p>Editar perfil</p>
   <img src="/assets/Wireframe-Editar-Perfil.jpg" alt="Wireframe-Editar-perfil"></img>
</div>

<div align=center>
    <p>Consultar tareas</p>
   <img src="/assets/Wireframe-Consultar-tareas.jpg" alt="Wireframe-Consultar-tareas"></img>
</div>

<div align=center>
    <p>Consulta de estadisticas</p>
   <img src="/assets/Wireframe-Consultar-estadisticas.jpg" alt="Wireframe-Consultar-estadisticas"></img>
</div>

<div align=center>
    <p>Consulta de inventario</p>
   <img src="/assets/Wireframe-Consultar-inventario.jpg" alt="Wireframe-Consultar-inventario"></img>
</div>

<div align=center>
    <p>Mandar Alerta de emergencia</p>
   <img src="/assets/Wireframe-Mandar-alterta-emergencia.jpg" alt="Wireframe-Alerta-emergencia"></img>
</div>

<div align=center>
    <p>Registrar Detalles</p>
   <img src="/assets/Wireframe-Registrar-detalles.jpg" alt="Wireframe-Registrar-detalles"></img>
</div>


### 4.4.3. Web Applications Mock-ups

<div align=center>
    <p>Publicar tu anuncio</p>
    <p>En la siguiente imagen, podemos observar los mockups que se utilizan para poder publicar una granja.</p>
   <img src="/assets/Mockup-Sin-Conexion-Publicar-anuncio.jpg" alt="Mockup-Sin-Conexion-Publicar-anuncio"></img>
</div>

<div align=center>
    <p>Editar perfil</p>
    <p>En la siguiente imagen, se visualiza los mockups que se utilizan para editar perfil.</p>
   <img src="/assets/Mockup-Sin-Conexion-Editar-perfil.jpg" alt="Editar-Perfil-Mockup"></img>
</div>
<div align=center>
    <p>Realizar task</p>
    <p>En la siguiente imagen, se visualiza los mockups que usaran los trabajadores de las granjas al utilizar FarmLogitech para ver sus tareas asignadas</p>
   <img src="/assets/Mockup-Sin-Conexion-Consultar-tareas.jpg" alt="Wireframe-Consultar-tareas"></img>
</div>
<div align=center>
    <p>Gestión y estadistica en FarmLogitech</p>
   <p>En la siguiente imagen observamos los mockups de los administradores de la granja en cual podrán acceder a las tareas asiganadas, estadísticas de ingresos y egresos, control de inventario.</p>
   <img src="/assets/Mockup-Sin-Conexion-Estadistica.jpg" alt="Mockup-Sin-Conexion-Estadistica"></img>
</div>

<div align=center>
    <p>Mandar alerta</p>
<p>En la siguiente imagen se observa los mockups que usará el administrador o trabajador para poder mandar mensajes de emergencia a su jefe o compañeros</p>
   <img src="/assets/Mockup-Sin-Conexion-Mensaje-alerta.jpg" alt="Mockup-Sin-Conexion-Mensaje-alerta"></img>
</div>

<div align=center>
    <p>Registrar detalles</p>
<p>En la siguiente imagen se observa el registro que llevará dependiendo a los pedidos o el estado de como lo ve para su granja</p>
   <img src="/assets/Mockup-Sin-Conexion-Registro-Detallado.jpg" alt="Mockup-Sin-Conexion-Registro-Detallado"></img>
</div>

### 4.4.4. Web Applications User Flow Diagrams.

<div align=center>
    <p>Publicar anuncio</p>
   <img src="/assets/Mockup-Publicar-anuncio.jpg" alt="Mockup-Publicar-anuncio"></img>
</div>

<div align=center>
    <p>Editar perfil</p>
   <img src="/assets/Mockup-Editar-perfil.jpg" alt="Editar-Perfil-Mockup"></img>
</div>
<div align=center>
    <p>Realizar task</p>
   <img src="/assets/Mockup-Consultar-tareas.jpg" alt="Wireframe-Consultar-tareas"></img>
</div>
<div align=center>
    <p>Gestión y estadistica en FarmLogitech</p>
   <img src="/assets/Mockup-Estadisticas.jpg" alt="Mockup-Estadistica"></img>
</div>

<div align=center>
    <p>Mandar alerta</p>
   <img src="/assets/Mockup-Alerta-emergencia.jpg" alt="Mockup-Mensaje-alerta"></img>
</div>

# 4.5. Web Applications Prototyping.
Para poder elaborar los prototipos de la interfaz de usuario destinados a Desktop se siguieron una serie
de criterios fundamentales, entre ellos:

1. Claridad y Facilidad: El enfoque fue lograr que la navegación en la aplicación sea intuitiva y comprensible, con el objetivo
   de que los usuarios puedan comprender plenamente las funciones de la aplicación.
   visualización de reportes estadísticos.
2. Diseño Responsive: Se ha tenido en cuenta la importancia del diseño "responsive" para garantizar que la aplicación web
   sea compatible con una variedad tamaños de pantalla, de tal manera que los usuarios no se vean limitados por el dispositivo que utilicen.
3. Priorización de Información Relevante: El diseño de la aplicación se enfoca en mostrar únicamente la información más importante para los usuarios pertenecientes al segmento objetivo.

# 4.6. Domain-Driven Software Architecture
El Domain Driven Design (DDD) tiene como objetivo llegar a un entendimiento compartido del dominio que abarca el espacio del problema. En el caso de “FarmLogitech”, este dominio es la gestión de granjas y la colaboración entre agricultores y empresas. Gracias a la perspectiva brindada por este enfoque, es posible mejorar la colaboración entre los desarrolladores y los expertos del dominio.


## 4.6.1. Software Architecture Context Diagram
El diagrama de contexto muestra una vista de alto nivel de las relaciones entre el sistema de software “FarmLogitech”, los usuarios y, si es el caso, de otros sistemas externos.

<img src="/assets/System-diagram.jpeg" alt="System diagram"></img>


## 4.6.2. Software Architecture Container Diagram
El diagrama de contenedores muestra una vista de alto nivel de las relaciones entre las aplicaciones y fuentes de datos que son parte de la ejecución del sistema de software “FarmLogitech”.

<img src="/assets/Conatiner-diagram.jpeg" alt="Container diagram"></img>

## 4.6.3. Software Architecture Components Diagrams
Los diagramas de componentes muestran una vista de las relaciones de los componentes principales del sistema de software “FarmLogitech”. Estos componentes detallan la implementación de los respectivos módulos en el programa.

- Log-In Bounded Context

  <img src="/assets/Login-Bounded-Context.jpeg" alt="Login Bounded Context"></img>

- Company Management Bounded Context

  <img src="/assets/Company-Management-Bounded-Context.jpeg" alt="Company Management Bounded Context"></img>

- Farm Management Bounded Context

  <img src="/assets/Farm-Management-Bounded-Context.jpeg" alt="Farm Management Bounded Context"></img>

- Notification Bounded Context

  <img src="/assets/Notification-Bounded-Context.jpeg" alt="Notification Bounded Context"></img>

- Payment Bounded Context

  <img src="/assets/Payment-Bounded-Context.jpeg" alt="Payment Bounded Context"></img>

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
<div align=center>
   <img src="/assets/Diagrama.jpg" alt="Diagrama"></img>
</div>

### 4.7.2. Class Dictionary
Class User
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a user
|  first_name  | String  | Name of a user
| last_name  | String | Last Name of a user
| phone_number  | int | Phone Number of the user
| email  | String | Email of the user |
| account  | Account  | Account of the User

Class Account
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for an account
| name  | String  | Name of the account
| owner  | User | The owner of the Account

Class Membership
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a Membership
|  name  | String  | Name of a Membership
| price  | int | Price of a Membership
| description  | int | Description of a Membership

Class MembershipPayment
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a MembershipPayment
| amount  | int  | Amount to be paid
| paid_date  | int | The date the Membership was paid

Class Farm_Owner
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a Farm_Owner
| first_name  | String  | Name of a Farm_Owner
| last_name  | String | Last Name of a Farm_Owner
| phone_number  | int | Phone Number of the Farm_Owner
| email  | String | Email of the Farm_Owner |
| account  | Account  | Account of the Farm_Owner
| password  | String | Password of a Farm_Owner

Class Client
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id  | int | Unique code for a Client
| first_name  | String  | Name of a Client
| last_name  | String | Last Name of a Client
| phone_number  | int | Phone Number of the Client
| email  | String | Email of the Client |
| account  | Account  | Account of the Client

Class Collaborator
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a Collaborator
| first_name  | String  | Name of a Collaborator
| last_name  | String | Last Name of a Collaborator
| phone number  | int | Phone Number of a Collaborator
| Email  | String | Email of a Collaborator
| password  | String | Password of a Collaborator
| working_hours  | int | hours that the collaborator works per week
| salary  | int | the salary of the collaborator

Class Farm
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a Collaborator
| name  | String  | Name of a Collaborator
| location  | String | The location of the farm
| infrastructure  | String | Infrastructure of the farm
| service  | String | Services of the farm
| certificates  | String | Certificates that the farm have
| status  | String | Status of the farm

Class Animal
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for an animal
| age  | int  | The age of the animal
| sex  | String | Sex of an animal
| health_condition  | int | The health condition of the animal
| addition_date  | String | The date the animal was brought to the farm

Class Task
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a task
| description  | String  | Description for a task
| estimated_time_to_make  | int | The estimated hours that will take doing this task to the collaborator
| end_date  | int |  The deadline for the task

Class Valoration
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a valoration
| rating  | String  | Rating made by the user for the farm

Class Message
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a message
| text  | String  | Text of the message
| date  | int | The date the message was sent
| isEmergency  | bool | The urgency of the Message

Class Crop
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a crop
| age  | int  | Age of a crop
| location  | String | The location of the crop
| health_status  | int |  The health status of the crop

Class Shed
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a shed
| type  | String  | Type of the shed
| location  | int | The location of the shed

Class Sells
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a task
| quantity  | int  | Quantity of the sells
| date  | String | Day of the sell
| percentage  | int | Percentage of the sell

Class Notification
| Atribute  | Type  | Description |
| ------------ | ------------ |------------ |
| id | int | Unique code for a notification
| description  | String  | Description for a task


## 4.8 Database Design
Para el proyecto, nos hemos decidido por utilizar el motor de base de datos de MySQL, debido a que es una herramientas con la que todos los integrantes del equipo nos sentimos comodos y familiarizados, ademas que posee una interfaz sencilla e intuitiva. Este motor nos permite desarrollar una base de datos para nuestro proyecto, el cual requerira de muchas tablas y conexiones entre ellas.

### 4.8.1 Database Diagram

<div align=center>
   <img src="/assets/diagrama-database.png.jpg" alt="Diagrama-database"></img>
</div>



