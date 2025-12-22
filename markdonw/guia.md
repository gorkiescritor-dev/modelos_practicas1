# Requisitos para Aprender WordPress

Para aprender WordPress, los requisitos varían dependiendo de si tu objetivo es ser un usuario que gestiona contenido o un desarrollador que crea temas y plugins. Basado en las fuentes, que incluyen una guía completa de WordPress y manuales técnicos de PHP y MySQL, aquí están los requisitos clasificados:

### 1. Requisitos Técnicos (Infraestructura)

Para que WordPress funcione, necesitas un entorno que soporte sus tecnologías base:

* **Alojamiento Web (Hosting):** WordPress funciona en un servidor que debe ser capaz de ejecutar PHP y bases de datos.
* **Lenguaje y Base de Datos:**
  * **PHP:** Es el lenguaje de programación en el que está basado WordPress. El servidor ejecuta los comandos PHP y devuelve los resultados al navegador.
  * **MySQL o MariaDB:** Son los gestores de bases de datos necesarios para almacenar la información (usuarios, configuraciones, contenido).
* **Instalación Local (Opcional):** Para aprender sin un hosting remoto, puedes usar paquetes como **MAMP** (Mac), **WAMP** (Windows) o **LAMP** (Linux) para crear un servidor local en tu ordenador,.

### 2. Herramientas Necesarias

Para gestionar la instalación y los archivos, las fuentes destacan:

* **Cliente FTP:** Una aplicación necesaria para conectar con el servidor y subir o bajar archivos (por ejemplo, al instalar manualmente temas o plugins).
* **Editor de Código:** Para modificar archivos de configuración o programar, **no se deben emplear procesadores de texto estándar** (como Word), sino editores especializados en código de programación.

### 3. Conocimientos para el Usuario (Nivel Básico/Intermedio)

Si tu objetivo es gestionar sitios, debes entender la lógica de la plataforma:

* **Gestión de Archivos:** Saber descomprimir archivos ZIP y subirlos vía FTP a carpetas específicas (como `/wp-content/themes/`) es necesario para instalaciones manuales,.
* **Conceptos de la Interfaz:**
  * Diferencia entre **Entradas** (contenido dinámico/cronológico) y **Páginas** (contenido estático),.
  * Gestión de **Categorías** (jerárquicas) y **Etiquetas** (no jerárquicas) para organizar el contenido,.
  * Uso de **Temas** para el diseño y **Plugins** para extender funcionalidades,.

### 4. Conocimientos para el Desarrollador (Nivel Avanzado)

Si deseas personalizar profundamente o crear tus propios temas y plugins, necesitas comprender la ingeniería subyacente:

* **PHP:** Es vital entender este lenguaje para crear funciones personalizadas o modificar archivos del núcleo del tema como `functions.php`,.
  * Se requiere entender la sintaxis básica, variables y cómo incrustar PHP en HTML (`<?php ... ?>`).
* **HTML y CSS:**
  * **HTML/XHTML:** Necesario para la estructura semántica de la web. WordPress corrige código mal anidado, pero es fundamental escribirlo bien para cumplir estándares.
  * **CSS (Hojas de estilo):** Es el lenguaje usado para definir el aspecto visual. En WordPress, el archivo `style.css` es fundamental para los temas,.
* **Bases de Datos (SQL):** Aunque WordPress maneja muchas consultas automáticamente, entender cómo funcionan las tablas y consultas SQL es útil para gestiones avanzadas o migraciones,.
