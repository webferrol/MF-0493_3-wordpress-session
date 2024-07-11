# Sesiones

## Sesión 1
- Proporcionar una visión general de WordPress y sus componentes.
- Asignar equipos y roles para el proyecto.

### Teoría:

1. **Introducción al Proyecto:**
   - Explicar el propósito del proyecto: Desarrollo de un portal de noticias utilizando WordPress.
   - Resaltar los objetivos de aprendizaje, incluyendo la instalación, configuración, desarrollo, pruebas y documentación de una aplicación web.

2. **Visión General de WordPress:**
   - **Qué es WordPress:**
     - [Historia y evolución de WordPress.](https://es.wikipedia.org/wiki/WordPress)
     - Usos comunes de WordPress: blogs, sitios de noticias, tiendas en línea, etc.
        - Verificar que CMS utilizan los siguientes usos web
            - edu.xunta.gal (www.wappalyzer.com/)
            - www.santiagodecompostela.gal (www.wappalyzer.com/)
            - visitferrol.com (www.wappalyzer.com)
        - Qué tecnologías conocidas incluyen: frameworks, BBDD, lenguajes ...
3. **Wordpress.com vs Wordpress.org**

| Característica       | WordPress.com                                         | WordPress.org                                        |
|----------------------|-------------------------------------------------------|------------------------------------------------------|
| **Alojamiento**      | Gestionado por WordPress.com                          | Debes gestionar tu propio hosting                    |
| **Costo**            | Planes gratuitos y de pago                            | Software gratuito; debes pagar por hosting y dominio |
| **Dominio**          | Subdominio gratuito; dominio personalizado en planes de pago | Dominio personalizado                                |
| **Personalización**  | Limitada (más opciones en planes de pago altos)       | Totalmente personalizable                            |
| **Monetización**     | Limitada en planes gratuitos y de pago bajos          | Total libertad                                       |
| **Mantenimiento**    | Gestionado por WordPress.com                          | Gestionado por ti mismo                              |
| **Seguridad**        | Gestionada por WordPress.com                          | Gestionada por ti mismo                              |

`¿Cuál elegir?`

- **WordPress.com** es ideal para aquellos que buscan una solución simple y gestionada, sin preocuparse por aspectos técnicos de mantenimiento y seguridad. Es una buena opción para bloggers, pequeños negocios y usuarios no técnicos.
- **WordPress.org** es la mejor opción para aquellos que desean un control total sobre su sitio web, incluyendo la capacidad de personalizar completamente la apariencia y funcionalidad. Es ideal para desarrolladores, empresas, y cualquier persona que necesite una solución altamente flexible y escalable.

4. **Arquitectura de WordPress:**
     - Estructura de archivos de WordPress.
     - Temas y plugins.
   - **Componentes Principales:**
     - **Core**: El núcleo de WordPress.
     - **Temas**: Plantillas para la apariencia y el diseño.
     - **Plugins**: Extensiones que añaden funcionalidad.
     - **Widgets**: Componentes pequeños y reutilizables.
### Sesión Práctica de WordPress

#### Objetivo
Al finalizar esta sesión, deberás ser capaz de instalar WordPress, configurar los ajustes básicos, elegir y personalizar un tema, y añadir contenido básico a tu sitio web.

#### Materiales Necesarios
- Acceso a Internet
- Un servidor web con PHP y MySQL (puedes usar servicios como Local by Flywheel, XAMPP, o un hosting web)
- Un navegador web

#### Instalación de WordPress

1. **Descargar WordPress**
   - Visita [wordpress.org](https://wordpress.org) y descarga la última versión de WordPress.

2. **Preparar el Entorno**
   - Si usas un servidor local como XAMPP o Local by Flywheel, asegúrate de tener el servidor web y la base de datos MySQL activos.
   - Si usas un hosting, accede al cPanel o al panel de control de tu hosting.

3. **Crear una Base de Datos**
   - En el servidor local, abre phpMyAdmin y crea una nueva base de datos.
   - En el hosting, utiliza la herramienta de gestión de bases de datos para crear una nueva base de datos.

4. **Subir y Configurar WordPress**
   - Extrae el archivo ZIP de WordPress descargado y sube los archivos al servidor (directorio `htdocs` en XAMPP o la carpeta adecuada en el hosting).
   - Navega a `http://localhost/nombredetuproyecto` o la URL correspondiente en tu hosting.
   - Sigue las instrucciones del instalador: selecciona el idioma, ingresa los detalles de la base de datos, crea una cuenta de administrador y configura el sitio.
