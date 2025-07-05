
Now Playing PC

Una aplicación de escritorio para Windows que muestra en tiempo real la canción que está sonando en tu sistema, con carátula, barra de progreso y letras sincronizadas o normales. Inspirada en widgets de Spotify o AppleMusic.

Características

- Detección automática de la canción actual usando el sistema de medios de Windows 10/11 (Spotify, Navegador, Groove, etc.).
- Muestra la carátula del álbum y genera un fondo difuminado a partir de ella.
- Barra de progreso y tiempos de reproducción.
- Letras sincronizadas (si están disponibles) o letras normales usando Genius y SyncedLyrics.
- Interfaz: moderna con esquinas redondeadas y colores adaptativos.
- Ventana flotante y movible siempre encima de otras ventanas.
- Soporte para desplazamiento de texto en títulos/artistas largos.

Requisitos

- Windows 10 u 11
- Python 3.8+
- Las siguientes librerías de Python:
  - PyQt6
  - winsdk
  - lyricsgenius
  - syncedlyrics
  - colorgram.py
  - Pillow

Puedes instalar las dependencias con:

py -m pip install PyQt6 winsdk lyricsgenius syncedlyrics colorgram.py Pillow


Uso

1. Clona o descarga este repositorio.
2. Ejecuta el archivo principal:


py now_playing.py


La ventana aparecerá automáticamente cuando detecte una canción sonando.

Notas

- Necesitas un token de Genius válido para obtener letras. El token actual está en el código, pero puedes reemplazarlo por el tuyo propio.
- Las letras sincronizadas dependen de la disponibilidad en SyncedLyrics.
- Si tienes problemas con la librería `winsdk`, asegúrate de estar en Windows 10/11 y tener Python de 64 bits.

Créditos

- Basado en PyQt6 y APIs públicas de Windows.
- Letras proporcionadas por Genius y SyncedLyrics.
- Extracción de color por [colorgram.py](https://github.com/obskyr/colorgram.py).

Autor: Cristobal Palma
© 2025. Todos los derechos reservados.
