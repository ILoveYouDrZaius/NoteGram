
# 📝 Bot para tomar notas (note-taking) desde Telegram

## :bulb: Problema a resolver

Queremos poder tomar notas desde Telegram y poder recuperarlas más tarde.

Nuestra solución para tomar estas notas es un *bot* que atenderá nuestros mensajes y almacenará las notas para poder consultarlas cuando queramos.

## Tecnologías de nuestra solucións

- :hammer: Lenguaje de programación: GO
- :scroll: Servicio de logging : ** TBD **
- :floppy_disk: :minidisc: Almacenamiento: ** TBD **
- :wrench: Configuración: ** TBD ** 

## Gestión de proyecto

El proyecto se gestiona desde Github.

- [Épicas](docs/gestion_proyecto.md#epicas)
- [Historias de usuario](docs/gestion_proyecto.md#Historia_Usuario)
- [Hitos](docs/gestion_proyecto.md#Hitos)


### :lock: Protección de datos :lock:

Para cumplir con el reglamento de proyección de datos tendremos que incorporar un usuario *administrador* que de a los usuarios de baja del servicio si lo piden. Esta característica no se puede suplir un un modelo *self-service* porque el usuario puede hacer la petición por donde le de la gana, incluso si ha pedido el acceso a su cuenta de TG.

## Estructura del proyecto:

📁[docs](docs) Documentación

📁[docs/Diseño Funcional](docs/Diseño_Funcional.md) - Diseño funcional de la aplicación (alto nivel) 

📁[tests](tests) - test_de_funcionalidad/unitarios/etc.

📁[data](data) - Datos de la aplicación



# Ejecución + Instalación

Para utilizar el bot necesitamos un Token.

- Hay que hablar con el [@botfather](https://t.me/botfather) para crear un bot y que nos dé un token para usar con el bot.
- Ver: [Bots: An introduction for developers](https://core.telegram.org/bots) para más detalles.


# Equipo:

- @delightfulagony
- @igponce
- @ILoveYouDrZaius
- @murcian0
