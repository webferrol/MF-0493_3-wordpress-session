# Proyecto: Desarrollo de un Portal de Noticias en WordPress

**Objetivo:** Crear un portal de noticias utilizando WordPress, cubriendo todas las fases de instalación, configuración, documentación y pruebas.

# Fases del Proyecto

## Fase 1: Instalación y Configuración
1. **CA1.1** - Determinar las fases y tecnologías:
   - **Fases**: Planificación, Instalación, Configuración, Desarrollo, Pruebas, Despliegue, Mantenimiento.
   - **Tecnologías**: Servidor web (Apache/Nginx), PHP, MySQL, WordPress, FTP/SFTP, SSL.

2. **CA1.2** - Supuesto práctico:
   - **Requisitos de instalación y distribución**: Dominio, servidor (local/hosting), versión de PHP y MySQL, espacio en disco.
   - **Estructura de directorios**: Crear directorios para `public_html`, `wp-content`, `themes`, `plugins`.
   - **Recursos afectados**: Base de datos, archivos de configuración, plugins y temas.
   - **Servicios necesarios**: Servidor web, base de datos, servidor FTP, servicios SSL.
   - **Parámetros de configuración**: Archivo `wp-config.php`, ajustes de PHP (memory_limit, max_execution_time).
   - **Seguridad**: Configuración de SSL, permisos de archivos, seguridad de base de datos, plugins de seguridad.
   - **Paquetes de instalación**: Descarga y configuración de WordPress, instalación de temas y plugins.
   - **Verificación**: Pruebas de acceso al sitio, funcionamiento de plugins y temas.

## Fase 2: Documentación y Control de Versiones
1. **CA2.1** - Identificación de herramientas:
   - **Herramientas**: Git para control de versiones, Markdown para documentación, plugins de documentación en WordPress.

2. **CA2.2** - Supuesto práctico:
   - **Documentación y calidad**: Crear una guía de instalación, configuración y uso del portal.
   - **Control de versiones**: Utilizar Git para mantener versiones del código y la documentación.
   - **Uso de herramientas**: Integrar plugins de documentación como WP Documentation para mantener actualizada la información.

## Fase 3: Verificación y Pruebas
1. **CA3.1** - Clasificación de métodos:
   - **Métodos**: Pruebas unitarias, pruebas de integración, pruebas funcionales, pruebas de rendimiento, pruebas de usabilidad.

2. **CA3.2** - Supuesto práctico:
   - **Verificación de documentos**: Asegurar que HTML, CSS y JavaScript funcionen correctamente.
   - **Componentes en el cliente**: Verificar scripts y su correcta ejecución.
   - **Usabilidad y accesibilidad**: Utilizar herramientas como WAVE y Lighthouse para evaluar accesibilidad.
   - **Integración de componentes**: Pruebas de compatibilidad de plugins y temas.
   - **Componentes en el servidor**: Pruebas con PHP y consultas a la base de datos.
   - **Acceso a bases de datos**: Verificación de operaciones CRUD.
   - **Servicios web**: Pruebas de API REST de WordPress.
   - **Rendimiento del servidor**: Utilizar herramientas como Apache JMeter para evaluar el rendimiento bajo carga.
   - **Optimización**: Ajustar configuración según resultados de las pruebas, implementar caché y optimización de bases de datos.

# Plan de Trabajo

1. **Sesión 1**: [Introducción y planificación del proyecto. Revisión de requisitos y tecnologías.](./docs/sesion-1.md)
2. **Sesión 2**: Instalación y configuración de WordPress en entornos locales y servidores de prueba.
3. **Sesión 3**: Desarrollo del portal de noticias: configuración de temas, plugins y estructura de contenido.
4. **Sesión 4**: Documentación del proceso de instalación y configuración. Introducción al control de versiones con Git.
5. **Sesión 5**: Pruebas de funcionalidad, rendimiento y seguridad. Optimización del portal.
6. **Sesión 6**: Revisión final, despliegue y presentación del proyecto.

# Resultados Esperados

- **Portal de noticias funcional** con WordPress.
- **Documentación completa** del proceso de instalación, configuración y uso.
- **Repositorio de control de versiones** con todo el código y documentación.
- **Informe de pruebas y optimización** del portal.

# Recursos Necesarios

- **Acceso a un servidor web** (puede ser un hosting compartido o un servidor local con XAMPP, WAMP, o MAMP).
- **Dominio** (puede ser uno gratuito para pruebas).
- **Herramientas de desarrollo**: Un editor de texto (VS Code, Sublime Text), navegador web, Git.

Este proyecto no solo permitirá a los alumnos familiarizarse con el desarrollo y despliegue de aplicaciones web en WordPress, sino que también les proporcionará una experiencia práctica completa que abarca desde la instalación inicial hasta la documentación y optimización final.