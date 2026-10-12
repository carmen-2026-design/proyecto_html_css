# **Proyecto con HTML & CSS**

Una plantilla y prototipo web desarrollado con HTML5 y CSS3 para eventos y conciertos.

# **Instalación y Visualización Local**

Dado que el proyecto se ha desarrollado localmente y no se encuentra publicado en un servidor en producción, puedes probarlo fácilmente tanto en versión móvil como de escritorio:

1. Clona el repositorio o descarga los archivos en tu equipo:  
   `git clone https://github.com/tu-usuario/tu-repositorio.git`  
2. Abre la carpeta del proyecto en **Visual Studio Code**.  
3. Utiliza la extensión **Live Server** (haciendo clic en el botón "Go Live" situado en la barra inferior del editor) para activar el servidor local y abrir automáticamente la página en tu navegador web.

# **Descripción**

Este proyecto consiste en una página web demostrativa creada por los coordinadores de eventos de conciertos. Su objetivo principal es servir como maqueta y guía visual para mostrar los diferentes apartados, bloques y componentes esenciales que debería estructurar un sitio web profesional enfocado en la promoción de conciertos y festivales.

Dado que aproximadamente el 90% de los usuarios accede a este tipo de plataformas a través de sus teléfonos móviles tanto para adquirir tickets como para comprar productos de merchandising, este proyecto ha sido concebido bajo una filosofía Mobile First, para luego adaptarse a pantallas más grandes como portátiles y de escritorio.

# **Estructura y Apartados de la Web**

## **Cabecera y Navegación (Header)**

* **Versión Móvil (Mobile First):** Icono de menú hamburguesa situado en la parte izquierda con menú desplegable interactivo que muestra las opciones de navegación al ser pulsado.  
* **Versión Escritorio (Portátil):** Título del evento situado en toda la parte superior con el menú de navegación alineado a la mano derecha para acceso rápido a las distintas opciones del sitio.

## **Página de Inicio (Home)**

Estructura clara e informativa para presentar el evento:

* **Imagen Principal:** Muestra una fotografía representativa de un concierto en vivo.  
* **Información General:** Breve resumen de la propuesta de eventos y el concepto del festival/concierto.  
* **Llamadas a la Acción (CTA) en Primera Pantalla:**  
  * **Venta de Tickets:** Botón/sección directa para la compra de entradas.  
  * **Programación del Día:** Acceso rápido al horario y las actuaciones destacadas de la jornada.

## **Pantalla de Merchandising**

Sección dedicada a la venta de productos oficiales del evento (camisetas, sudaderas, accesorios, etc.):

* **Catálogo Adaptativo (Responsive Gallery):** Muestra la lista de productos disponibles organizados de forma fluida.  
* **Disposición Flexible (`flex-wrap` / `grid`):** Los artículos ocupan todo el ancho disponible de la pantalla; si la pantalla se estrecha (como en dispositivos móviles), los productos adicionales pasan automáticamente a la siguiente fila para mantener la legibilidad y un diseño impecable.

## **Pantalla de Quiénes Somos**

Presentación del equipo humano detrás de la organización del evento:

* **Fotografía de Equipo:** Fotografía principal que muestra a los coordinadores y organizadores.  
* **Definición e Identidad:** Explicación del proyecto y quiénes forman parte de él.  
* **¿De dónde venimos?:** Historia, trayectoria y orígenes de la promotora/coordinación de conciertos.  
* **¿Hacia dónde vamos?:** Visión de futuro, metas y próximos eventos o retos de la organización.

## **Flujo de Compra y Autenticación de Usuarios**

Al hacer clic en el botón de compra de tickets, el usuario entra al proceso de acceso y registro:

* **Pantalla de Inicio de Sesión (Login):** Formulario de acceso mediante correo electrónico y contraseña.  
* **Pantalla de Registro de Usuario (Sign Up):** Formulario de captura de datos para nuevos usuarios con campos de tipo requerido (`required`) para asegurar la validación nativa en HTML5 antes de enviar el formulario.

## **Pie de Página (Footer)**

El footer consolida la información corporativa, apoyos y puntos de contacto del evento:

* **Sección de Partners y Patrocinadores (Izquierda/Centro):** Muestra de logos e imágenes representativas de las marcas y partners colaboradores en la organización del concierto.  
* **Opciones de Contacto y Ubicación (Mano Derecha):**  
  * **Solicitud de Información:** Enlace de contacto directo (`mailto:`) que abre el cliente de correo preconfigurado con la dirección de soporte/información.  
  * **Ubicación del Evento:** Integración de mapa interactivo mediante Google Maps para mostrar el recinto y la ubicación exacta donde se celebrará el concierto.

# **Características**

| Categoría | Descripción y Funcionalidades |
| :---- | :---- |
| **Enfoque Mobile First** | Optimizado para la experiencia de compra y navegación en dispositivos móviles, adaptándose fluidamente a pantallas de escritorio. |
| **Layout Flexible** | Catálogo de productos adaptable que reorganiza los elementos en filas según el tamaño de la pantalla. |
| **Estructura Modular** | Muestra los apartados clave de una web de conciertos (Inicio, Tienda, Nosotros, Autenticación y Contacto). |
| **Validación de Formularios** | Uso de atributos nativos de HTML5 (`required`, tipos de input específicos) para una correcta recolección de datos. |
| **Integración de Servicios** | Enlace a cliente de correo electrónico y mapas incrustados con Google Maps. |
| **Estilo Personalizado** | Maquetación moderna utilizando CSS3 (Flexbox/Grid y Media Queries). |

# **Tecnologías y Herramientas**

* **HTML5:** Estructuración del contenido, formularios, mapa (`iframe`/Google Maps) e hipervínculos de contacto (`mailto:`).  
* **CSS3:** Diseños, colores, tipografías, media queries y maquetación flexible para catálogos y galerías.  
* **Visual Studio Code:** Entorno de desarrollo integrado utilizado para la maquetación y escritura del código.


