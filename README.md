# Actividad-0

API - Plataforma de Blog

Descripción general
Esta API corresponde a una plataforma de blog o red social básica de publicación de contenidos y comentarios. Permite que los usuarios publiquen artículos o entradas de blog, que otros usuarios puedan leerlas y agregar comentarios, gestionando también categorías o etiquetas para organizar el contenido. En resumen, expone endpoints para manejar usuarios, posts (entradas de blog), comentarios y categorías. El propósito de esta API es servir de backend a un sitio de blogging donde múltiples usuarios pueden contribuir con contenido e interactuar.

Elementos de la API

Ublicar artículos (entradas de blog).

Leer artículos publicados por otros.

Comentar en esos artículos.

Organizar los artículos por categorías.

¿Qué partes tendrá la API?
Entradas de Blog (Posts)
Cada entrada tendrá: título, contenido, autor, fecha y categoría.
Las personas registradas podrán crear, editar o eliminar sus propias publicaciones.
Cualquier visitante podrá leer los artículos.

Comentarios
Los usuarios registrados podrán comentar en los artículos.
Solo se podrán editar o eliminar los comentarios que uno mismo haya hecho.

Los autores de los artículos también podrán eliminar comentarios en sus publicaciones.

Categorías
Servirán para agrupar los artículos por tema.
Las categorías pueden ser creadas por un administrador (persona encargada del sistema).

Usuarios
Las personas podrán registrarse y luego iniciar sesión.
Habrá dos tipos de usuarios: normales (quienes pueden publicar y comentar) y administradores (quienes pueden además gestionar todo el contenido).

Requerimientos Funcionales
Permitir a los usuarios registrarse e iniciar sesión.
Publicar nuevos artículos.
Leer artículos existentes.
Comentar en los artículos.
Eliminar o editar los artículos o comentarios que uno mismo hizo.
Ver los artículos por categoría.
Controlar quién puede hacer qué (por ejemplo, solo los autores pueden editar lo que escribieron).

Requerimientos No funcionales
Guardar todo en una base de datos MongoDB.
Proteger el acceso para que solo usuarios registrados puedan publicar o comentar.
Asegurar que el sistema sea fácil de mantener y se pueda ampliar en el futuro.
