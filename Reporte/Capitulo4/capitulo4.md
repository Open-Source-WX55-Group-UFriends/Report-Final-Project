# Capítulo IV: Product Design
## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines

### Branding:
- Esta imagen simboliza nuestra dedicación a la agricultura y a los animales. Al unirse a nosotros, los usuarios experimentarán una conexión sólida y colaborativa, reflejada en nuestra comunidad.

<div align=center>

colocar imagen del logo
</div>

### Typography:
- La tipografía de nuestro logotipo adoptará el elegante estilo Semibold, reconocido por su modernidad y su atractivo visual para nuestros usuarios. Este estilo no solo refleja la innovación y la creatividad que caracterizarán a nuestra aplicación, sino que también resalta la vanguardia que buscamos transmitir.

<div align=center>
 colocar imagen tipografia
</div>
<br>

### Colors:

- Nuestra paleta de colores se ha seleccionado para que al visitar nuestro sitio web, los usuarios sientan la atmósfera de una granja. El verde  (#25C95C) aporta frescura y vitalidad. El amarillo pálido (#E9F3AE) evoca la luz del sol sobre los cultivos. En conjunto, estos colores ofrecen una experiencia visual que refleja el ambiente y la energía de una granja.

<div align=center>
    colocar imagen 
</div>
<br>

### 4.1.2. Web Style Guidelines

*Icons:*

- Cuando se trata de diseñar una página web, los íconos juegan un papel crucial en la creación de una interfaz de usuario intuitiva y fácil de usar. Estos elementos visuales pequeños tienen el poder de mejorar la comprensión de los usuarios sobre la funcionalidad de diferentes partes de tu página. Los íconos permiten a los usuarios entender rápidamente la función de cada elemento y su simplicidad y claridad los hacen fácilmente comprensibles. Mantener una consistencia en el uso de íconos en toda la página ayuda a evitar confusiones entre los usuarios.
- Los que usaremos en el proyecto son los siguientes:

<div align=center>
    colocar imagen 
</div>
<br>

*Breackpoints*
- Los breakpoints más conocidos son los siguientes:

<div align=center>
    colocar imagen 
</div>
<br>

- Y los que usaremos en el proyecto principalmente son los de 768px y 1024px, ya que son los más comunes en los dispositivos móviles y de escritorio.

## 4.2. Information Architecture
### 4.2.1. Organization Systems

Al entrar a nuestro Website, el usuario podrá visualizar 5 secciones: El inicio, las tarifas, Login (Administradores) y publica tu anuncio .

<div align=center>
colocar imagen
</div>

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

Las etiquetas meta en HTML son esenciales para proporcionar información y metadatos no visibles a los usuarios, pero útiles para los navegadores y rastreadores web. Facilitan el análisis y mantenimiento del contenido, además de contribuir al posicionamiento en los motores de búsqueda. Utilizaremos estas etiquetas para optimizar nuestra página web.
  
- Título: Esta etiqueta es fundamental y suele colocarse antes que cualquier otra metaetiqueta. Todos los motores de búsqueda la utilizan como encabezado en las páginas de resultados de búsqueda (SERP).  
```<title>Register your processes with FarmLogiTech</title> ```
- Autor y Derechos de Autor:
  Esta etiqueta se emplea para registrar la información del autor y los derechos de propiedad de la página web.  
``` 
<meta name="author" content="FarmLogitech"/>
<meta name="copyright" content="Copyright FarmLogiTech team" /
- ```




### 4.2.4. Searching Systems



Es esencial que los usuarios administradores puedan distinguir y filtrar la información de los registros almacenados en la aplicación web de gestión de granjas. Uno de los objetivos clave del sistema es presentar de manera efectiva, sencilla y rápida la gran cantidad de datos que serán ingresados por las empresas agrícolas. Los usuarios tendrán la capacidad de buscar los registros de cultivos según su fecha de ingreso y la fase en la que se encuentran. Además, podrán filtrar la información según la fecha, fase y autor del registro de cultivos en el histórico general de cultivos realizados. También se incluirá funcionalidad de búsqueda en la visualización de los empleados de la empresa.

### 4.2.5. Navigation Systems


Los principales sistemas de navegación en la Landing Page son los menús ubicados en la parte superior e inferior. El etiquetado direcciona a los usuarios a las secciones específicas de la página. Si no se utilizan estos enlaces, la página se desplazará hacia abajo automáticamente. En la aplicación, los usuarios seguirán un proceso de cultivo, con secciones numeradas y visibles encima de los registros de cada fase. Los usuarios tienen la opción de saltar entre fases o seguir un orden secuencial. Los botones, por su parte, representan acciones como abrir, confirmar o completar un registro, facilitando el seguimiento del proceso en una nueva pantalla.

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe



### 4.3.2. Landing Page Mock-up

### 4.4. Web Applications UX/UI Design.
#### 4.4.1. Web Applications Wireframes.
#### 4.4.2. Web Applications Wireflow Diagrams.
####  4.4.3. Web Applications Mock-ups.
#### 4.4.4. Web Applications User Flow Diagrams.
#### 4.5. Web Applications Prototyping.



# 4.6. Domain-Driven Software Architecture
El Domain Driven Design (DDD) tiene como objetivo llegar a un entendimiento compartido del dominio que abarca el espacio del problema. En el caso de “FarmLogitech”, este dominio es la gestión de granjas y la colaboración entre agricultores y empresas. Gracias a la perspectiva brindada por este enfoque, es posible mejorar la colaboración entre los desarrolladores y los expertos del dominio.


## 4.6.1. Software Architecture Context Diagram
El diagrama de contexto muestra una vista de alto nivel de las relaciones entre el sistema de software “FarmLogitech”, los usuarios y, si es el caso, de otros sistemas externos.

<img src="/assets/img-diagram-system.png" alt="System diagram"></img>

## 4.6.2. Software Architecture Container Diagram
El diagrama de contenedores muestra una vista de alto nivel de las relaciones entre las aplicaciones y fuentes de datos que son parte de la ejecución del sistema de software “FarmLogitech”.

<img src="/assets/img-diagram-container.png" alt="Container diagram"></img>

## 4.6.3. Software Architecture Components Diagrams
Los diagramas de componentes muestran una vista de las relaciones de los componentes principales del sistema de software “FarmLogitech”. Estos componentes detallan la implementación de los respectivos módulos en el programa.

- Log-In Bounded Context

  <img src="/assets/img-LoginBC.png" alt="Login Bounded Context"></img>

- Company Management Bounded Context

  <img src="/assets/img-companyManagementBC.png" alt="Company Management Bounded Context"></img>

- Farm Management Bounded Context

  <img src="/assets/img-farmManagementBC.png" alt="Farm Management Bounded Context"></img>

- Notification Bounded Context

  <img src="/assets/img-notificationBC.png" alt="Notification Bounded Context"></img>

- Payment Bounded Context

  <img src="/assets/img-paymentBC.png" alt="Payment Bounded Context"></img>

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

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

## Database Design
Para el proyecto, nos hemos decidido por utilizar el motor de base de datos de MySQL, debido a que es una herramientas con la que todos los integrantes del equipo nos sentimos comodos y familiarizados, ademas que posee una interfaz sencilla e intuitiva. Este motor nos permite desarrollar una base de datos para nuestro proyecto, el cual requerira de muchas tablas y conexiones entre ellas.
### Database Diagram



