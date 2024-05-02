# Sistema de Microblogging

Este repositorio contiene el código fuente y la documentación para un Sistema de Microblogging diseñado para mejorar la comunicación dentro de una organización. Este sistema proporciona una plataforma para que los usuarios registrados compartan mensajes breves con sus colegas, fomentando la colaboración y el intercambio de información.

## Tabla de Contenidos

1. [Introducción](#introducción)
2. [Características](#características)
3. [Instalación](#instalación)
4. [Uso](#uso)
5. [Documentación de la API](#documentación-de-la-api)

## Introducción

En los lugares de trabajo modernos, la comunicación efectiva es crucial para la productividad y la colaboración. Para abordar esta necesidad, nuestro Sistema de Microblogging proporciona una plataforma para que los empleados compartan mensajes breves, enlaces y actualizaciones con sus colegas. Este repositorio contiene tanto los componentes frontend como backend del sistema, junto con una documentación completa para facilitar la comprensión y el uso.

## Características

### Gestión de Usuarios
- **Registro:** Los usuarios pueden registrarse con un nombre de usuario, correo electrónico, contraseña, nombre completo, foto y biografía.
- **Autenticación:** Sistema de autenticación seguro para el inicio de sesión de usuario.
- **Gestión de Perfiles:** Los usuarios pueden actualizar su información de perfil y foto.

### Funcionalidad de Microblogging
- **Publicación:** Los usuarios pueden crear publicaciones de hasta 140 caracteres, incluidos enlaces, menciones y hashtags.
- **Seguimiento:** Los usuarios pueden seguir a otros usuarios para ver sus publicaciones en su línea de tiempo.
- **Línea de Tiempo:** Los usuarios pueden ver publicaciones de usuarios a los que siguen y sus propias publicaciones.
- **Reposteo:** Los usuarios pueden compartir publicaciones de otros usuarios con sus seguidores.
- **Mensajería Privada:** Los usuarios pueden enviar mensajes privados a usuarios específicos.

### Gestión de Contenidos
- **Edición y Eliminación:** Los usuarios pueden editar y eliminar sus propias publicaciones.
- **Tendencias de Hashtags:** El sistema muestra hashtags populares basados en publicaciones recientes.
- **Digesto Semanal por Correo Electrónico:** Los usuarios reciben un correo electrónico semanal con temas populares y enlaces a publicaciones relacionadas.

### Integración
- **API RESTful:** Proporciona puntos finales para publicar y leer líneas de tiempo de usuario, facilitando la integración con otros sistemas.
- **Autenticación:** El acceso a los puntos finales de la API está restringido a aplicaciones registradas.


## Uso

Una vez que el sistema esté funcionando localmente, los usuarios pueden acceder a él a través de un navegador web. Pueden registrarse, crear publicaciones, seguir a otros usuarios e interactuar con las funciones de microblogging proporcionadas. El sistema proporciona una interfaz de usuario intuitiva para una interacción sin problemas.

## Documentación de la API

Para los desarrolladores interesados en integrarse con el Sistema de Microblogging, la documentación de la API proporciona información detallada sobre los puntos finales disponibles, los parámetros de solicitud y los formatos de respuesta. Consulte la [Documentación de la API](/api-docs) para obtener más información.
