# Temario-de-App-Web
##Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.
El desarrollo web es el proceso de crear sitios y aplicaciones accesibles a través de navegadores de Internet. Ha evolucionado desde páginas estáticas y simples hasta aplicaciones interactivas y avanzadas.


<img width="315" height="159" alt="image" src="https://github.com/user-attachments/assets/11085325-0958-4bff-b64e-24cd60b04756" />


## Historia y Evolución

- **Web 1.0:** Primeras páginas estáticas, solo texto e imágenes, sin interacción.
- **Web 2.0:** Incorporación de CSS, JavaScript y bases de datos. Surgen sitios dinámicos y redes sociales.
- **Web 3.0:** Aplicaciones web avanzadas, mayor interactividad, integración con tecnologías móviles y progresivas.

## Tipos de Aplicaciones Web

- **Estáticas:** Contenido fijo, no cambia sin intervención manual.
- **Dinámicas:** El contenido cambia según la interacción del usuario o la información de una base de datos.
- **SPA (Single Page Application):** Aplicaciones que cargan una sola página y actualizan el contenido dinámicamente sin recargar toda la página.
- **PWA (Progressive Web Application):** Aplicaciones web que ofrecen experiencia similar a una app nativa, funcionan offline y pueden instalarse en dispositivos.

  # Arquitectura de aplicaciones web

La arquitectura de aplicaciones web define cómo se organizan y comunican los componentes de una aplicación para ofrecer servicios eficientemente.

## Modelo Cliente-Servidor
- El **cliente** (navegador o app) solicita servicios o datos.
- El **servidor** procesa las solicitudes y responde con la información solicitada.
- Es la base de toda aplicación web.

## Arquitectura de Tres Capas
1. **Presentación:** Interfaz de usuario (HTML, CSS, JavaScript).
2. **Lógica de negocio:** Procesa reglas y operaciones (servidor/back-end).
3. **Datos:** Almacena y gestiona la información (base de datos).

Esta estructura separa responsabilidades y facilita el mantenimiento y escalabilidad.

## REST y API-first design
- **REST:** Estilo de arquitectura para crear APIs, usando métodos HTTP (GET, POST, etc.), recursos identificados por URLs y datos en formatos como JSON.
- **API-first design:** Estrategia donde la API se diseña antes de implementar la aplicación, facilitando la integración y el trabajo en paralelo entre equipos.
Lenguajes y tecnologías fundamentales

En el desarrollo web existen lenguajes y tecnologías esenciales que permiten crear sitios y aplicaciones funcionales:

- **HTML:** Define la estructura y el contenido de las páginas web.
- **CSS:** Da estilo, formato y presentación visual a los elementos HTML.
- **JavaScript:** Añade interactividad y dinamismo a las páginas web, ejecutándose en el navegador.
- **PHP:** Es un lenguaje de programación que se ejecuta en el servidor, permitiendo crear páginas dinámicas y gestionar la lógica del sitio.
- **MySQL:** Es un sistema de gestión de bases de datos que almacena, organiza y consulta información para las aplicaciones web.
#Control de versiones
##Lenguajes y tecnologías fundamentales
El control de versiones es esencial en el desarrollo web, ya que permite registrar y gestionar los cambios en el código de un proyecto, facilitando la colaboración y la recuperación de versiones anteriores.

- **Git:** Es el sistema de control de versiones más utilizado. Permite crear un historial de cambios, trabajar con ramas y fusionar diferentes versiones del proyecto.
- **GitHub:** Plataforma en la nube para alojar repositorios Git y facilitar el trabajo colaborativo mediante herramientas como pull requests y revisiones de código.

## Flujo de trabajo con ramas
- **Ramas (branching):** Permiten desarrollar nuevas características o corregir errores sin afectar la versión principal del proyecto.
- **Merge (fusión):** Consiste en integrar los cambios de una rama al proyecto principal.
- **Pull requests:** Son solicitudes para fusionar ramas, permitiendo la revisión y discusión del código antes de integrarlo.
# Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web



<img width="349" height="276" alt="image" src="https://github.com/user-attachments/assets/fe4b5686-7562-4164-bb0d-6469ce122902" />

## 1. Diseño e implementación del frontend

- **Maquetación / Wireframe / Mockup:**
  - El proceso comienza con bocetos (wireframes) y prototipos visuales (mockups) para definir el diseño y la estructura visual antes de codificar.
  - Herramientas comunes: Figma, Adobe XD, Sketch o lápiz y papel.

- **API:**
  - El frontend se comunica con el backend a través de APIs (Interfaz de Programación de Aplicaciones), normalmente usando HTTP y formatos como JSON.
  - Permiten obtener, enviar y manipular datos de manera dinámica y asíncrona.

## 2. Diseño e implementación del backend

- **Servidor:**
  - Es el programa que recibe las peticiones del frontend y responde con datos o realiza acciones solicitadas.
  - Tecnologías habituales: Node.js, Express, Django, Flask, PHP, etc.

- **Manejo de peticiones y respuestas HTTP:**
  - El backend gestiona las solicitudes (GET, POST, PUT, DELETE) y envía respuestas adecuadas.
  - Incluye la gestión de rutas, parámetros y códigos de estado HTTP.

- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB):**
  - El backend se conecta a bases de datos para almacenar y recuperar información necesaria para la aplicación.
  - Cada base de datos tiene su propia forma de organizar y manejar los datos (relacional o no relacional).

## 3. Bases de datos

- **Modelado de datos y relaciones:**
  - Consiste en definir las tablas o colecciones, los campos y cómo se relacionan entre sí (uno a uno, uno a muchos, muchos a muchos).
  - Esencial para garantizar integridad y eficiencia en el almacenamiento de datos.

- **ORM (Object Relational Mapping):**
  - Es una técnica que permite interactuar con la base de datos usando objetos y código en lugar de consultas SQL directas.
  - Ejemplos: Sequelize (Node.js), SQLAlchemy (Python), Eloquent (Laravel).

- **CRUD desde el backend:**
  - CRUD (Create, Read, Update, Delete) son las operaciones básicas para gestionar los datos desde el servidor.
## 4. Seguridad básica en aplicaciones web

- **Validación de formularios:**
  - Es fundamental validar la información que los usuarios envían desde el frontend, tanto en el cliente como en el servidor, para evitar datos incorrectos o maliciosos.

- **Autenticación y autorización:**
  - **Autenticación:** Proceso para verificar la identidad de un usuario (ej: login).
  - **Autorización:** Determina los permisos que tiene un usuario autenticado para acceder a ciertos recursos o acciones dentro de la aplicación.
# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional



<img width="450" height="286" alt="image" src="https://github.com/user-attachments/assets/802cfa0c-6fa7-41f7-b189-f296da7f7269" />

## 1. Integración de frontend y backend

- **Interfaz de usuario (Frontend):**
  - El frontend es la parte visual e interactiva de la aplicación, desarrollada con tecnologías como HTML, CSS y JavaScript (y frameworks como React, Angular o Vue).
  - Se encarga de mostrar la información y recoger datos del usuario.

- **Manejo de API:**
  - El frontend se comunica con el backend a través de APIs (generalmente REST o GraphQL), enviando y recibiendo datos en formatos como JSON.
  - Las APIs permiten que el frontend y backend trabajen de manera desacoplada y flexible.

- **Proceso de Solicitud y Respuesta de Backend:**
  - El backend recibe solicitudes del frontend, procesa la lógica de negocio, interactúa con la base de datos y responde con la información solicitada.
  - Este ciclo de solicitud-respuesta se realiza mediante protocolos como HTTP/HTTPS.
## 2. Almacenamiento en Servidor

- **Tipos de servidores:**
  - Servidores físicos (on-premise) y servidores en la nube (cloud).
  - Servidores dedicados, compartidos o VPS (Servidor Privado Virtual).

- **Servidores y servicios de hosting:**
  - Servicios que permiten publicar aplicaciones web en Internet.
  - Ejemplos: Netlify, Vercel, Heroku, AWS, Azure, DigitalOcean.

- **Proveedores de servicios de almacenamiento:**
  - Empresas que ofrecen infraestructura para almacenar archivos y bases de datos.
  - Ejemplos: Amazon S3, Google Cloud Storage, Firebase Storage.
## 3. Optimización y rendimiento

- **Optimización de recursos (imágenes, scripts):**
  - Comprimir imágenes y minificar archivos CSS/JS para mejorar la velocidad de carga.
  - Uso de técnicas como lazy loading y caché.

- **Despliegue de aplicaciones web:**
  - Proceso de poner la aplicación en producción, accesible para los usuarios finales.
  - Involucra configurar dominios, certificados SSL, y ajustar variables de entorno.

- **CI/CD básico (Integración y Despliegue Continuos):**
  - Automatización de pruebas, construcción y despliegue de la aplicación usando herramientas como GitHub Actions, GitLab CI o Jenkins.
  - Permite entregar actualizaciones frecuentes y confiables.

- **Documentación del proyecto:**
  - Escribir documentación clara para facilitar el mantenimiento y la colaboración.
  - Incluye instrucciones de instalación, uso, arquitectura y APIs.
