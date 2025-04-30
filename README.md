# Juego_Del_Quiz
# Juego de Quiz en PSeInt

Este es un programa sencillo de **quiz** o juego de preguntas y respuestas implementado en **PSeInt**. El objetivo del juego es hacerle al jugador una serie de preguntas y evaluar sus respuestas. Al final, se muestra la cantidad de respuestas correctas obtenidas.

## Descripción

En este juego de quiz, el programa presenta al jugador una serie de preguntas con opciones de respuesta. El jugador debe elegir la respuesta correcta, y el programa evalúa si la respuesta es correcta o no. El puntaje final se muestra al terminar todas las preguntas.

## Características

- El jugador responde a varias preguntas de opción múltiple.
- El programa verifica si las respuestas son correctas.
- Al final, muestra la cantidad de respuestas correctas obtenidas.
- Se incluye retroalimentación sobre el puntaje final del jugador.

## Instrucciones para Ejecutar

1. **Descargar e instalar PSeInt**:
   Si aún no tienes PSeInt, puedes descargarlo desde su [sitio web oficial](https://pseint.sourceforge.io/).

2. **Abrir el archivo en PSeInt**:
   Una vez descargado el archivo de este proyecto, abre PSeInt y carga el archivo con extensión `.pseint` para comenzar.

3. **Ejecutar el programa**:
   Presiona el botón de ejecutar en PSeInt para comenzar a jugar.

## Código Fuente

El código principal se encuentra en el archivo `quiz.pseint`, el cual sigue la siguiente estructura básica:

```pseudocode
Algoritmo Quiz
    Definir respuestaUsuario Como Cadena
    Escribir "¿Cuál es la capital de Francia?"
    Escribir "a) Londres"
    Escribir "b) París"
    Escribir "c) Madrid"
    Leer respuestaUsuario
	
    Si respuestaUsuario = "b" Entonces
        Escribir "¡Correcto! La capital de Francia es París."
    Sino
        Escribir "Incorrecto. La respuesta correcta es París."
    FinSi
FinAlgoritmo
## Tecnologías Utilizadas
PSeInt: Herramienta para la creación de algoritmos en pseudocódigo.

Algoritmo en pseudocódigo: Simulación de un juego de preguntas y respuestas.

## Contribuciones
Si tienes alguna sugerencia o mejora para este proyecto, no dudes en abrir un "issue" o enviar un "pull request". Todas las contribuciones son bienvenidas.

Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
