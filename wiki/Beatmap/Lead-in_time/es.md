---
tags:
  - leadin
  - lead in
  - AudioLeadIn
---

# Tiempo de entrada

*Vea también: [Compensación](/wiki/Offset)*

La **entrada** es la cantidad de tiempo que da el juego para que los jugadores reaccionen antes del primer [objeto](/wiki/Gameplay/Hit_object) de un [mapa](/wiki/Beatmap). Este puede ser personalizado por los [mapeadores](/wiki/Beatmapping) editando el campo `AudioLeadIn` en el [archivo `.osu`](/wiki/Client/File_formats/Osu_(file_format)) en una [dificultad del mapa](/wiki/Beatmap/Difficulty), que contiene la duración de la entrada en milisegundos.

## Comportamiento

El tiempo de entrada mínimo utilizado automáticamente por osu! es de 1.8 segundos. Con la [velocidad de aproximación](/wiki/Beatmap/Approach_rate) más baja de 0, esta es la cantidad de tiempo que un objeto es visible antes de que necesite ser golpeado. Cualquier [storyboard](/wiki/Storyboard) o vídeo que se reproduzca antes del primer objeto puede extender el tiempo de entrada.

El uso de una entrada personalizada es requerida para los [criterios de clasificación](/wiki/Ranking_criteria#general) en caso de que el mapa contenga un aviso de epilepsia que cubra los primeros objetos.
