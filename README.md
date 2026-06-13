# Botsito-python

Bot Multifuncional de Consola en Python

Este es un bot interactivo basado en la terminal de comandos desarrollado en Python. El proyecto funciona como un panel de control centralizado que permite al usuario interactuar con diferentes herramientas, cuestionarios y mini-juegos de forma automatizada.

El bot utiliza el sistema de subprocesos de Python, lo que significa que el menú principal nunca se cierra; simplemente abre el juego o la herramienta que elijas y, cuando terminas de usarla, te regresa automáticamente al menú de forma fluida.

El programa está organizado en 5 opciones principales:

Música: Ejecuta de forma automática el script externo "mus.py" para gestionar tus canciones o listas de reproducción.

Pintar: Abre el lienzo o herramienta de dibujo ejecutando el archivo independiente "Pintar.py".

Quiz: Inicia un cuestionario interactivo de preguntas y respuestas mediante el script "quiz.py".

Jugar: Despliega un submenú especial donde puedes elegir entre tres juegos diferentes. Al seleccionar uno, el bot corre su respectivo archivo:

Snake (ejecuta snake.py)

Examen (ejecuta examen.py)

Fútbol (ejecuta fc.py)

Despedida: Muestra un mensaje de cierre y finaliza la ejecución del bot de manera segura.

Para que el proyecto funcione correctamente, todos los archivos individuales de los juegos y herramientas deben estar guardados en la misma carpeta que el script del bot principal.
