# Lector de Noticias

## Crear una aplicación para ver Noticias

### Las noticias deben tener los siguientes campos:

1. Fecha de Publicación
2. Título
3. Contenido (todo la noticia en particular debe permitir texto enriquecido (HTML))
4. Imagen (URL de la imagen)

### La aplicación debe ser web y consiste de dos páginas

1. Inicio (Muestra las noticias “destacadas” un random de 3 noticias existentes en la BD)
2. Explorar (Permite al usuario especificar un texto para buscar por título y un rango de fecha de publicación, debe mostrar inicialmente las 5 noticias mas recientes)

**Nota**: No es necesario permitir al usuario que agregue noticias la aplicacion es meramente para lectura

### Tech Stack

#### Back End

1. HTTP API (ASP.NET) Puede ser full framework (4.5 en adelante) o .Net Core (2.0 en adelante)
2. Base de Datos puede ser en localDB, SQLLite o SQL Server Express
3. Usar Entity Framework bajo el model Code First para generar la BD, usar fluent API en ves de Data Annotations y crear un Seeding de al menos 10 noticias iniciales

#### Front End

1. Usar Angularjs 1.x para consumir el Web API y para renderizar las noticias
2. **Opcional** Usar Bootstrap 3 o 4 para estilos

### Entregable

Crear un repositorio publico en su github personal y enviar enlace a persona a cargo de su proceso de reclutacion.

### Puntos de interes

1. Completar funcionalidad segun requerimentos
2. Buenas practicas en el codigo, codigo entendible y limpio
3. Buena utilizacion de Git, commits claros y puntuales, git flow es opcional
4. Documentacion para Setup orientado a que otros desarrolladores puedan ejecutar su proyecto sin necesidad de preguntas adicionales

### Consejos

1. Hacer el codigo en ingles, evitar spanglish
2. Enforcarse en funcionalidad los estilos son segundarios en este caso.
3. Enviar enlace a repositorio desde que se inicie el trabajo no esperara terminar todo para subir y enviar
4. Agregue documentacion utilizando un README.md en la raiz del proyecto orientada a que la persona a cargo de revisar no tenga problemas en ejecutar y revisar su proyecto. (Pre requisitos (ASP.NET, SQL Server, Nodejs, etc...) para correrlo, comandos que se deban ejecutar etc...)
5. Considerando tiempos de entregua evite usar herramientas para compilar el front-end tales como grunt, gulp o webpack. Si las utiliza y documenta apropiadamente los pasos para ejecutar sera un plus pero no es requerido en este caso
6. Cualquier pregunta refierase con la persona acargo de su proceso de reclutamiento

## Buena Suerte!
