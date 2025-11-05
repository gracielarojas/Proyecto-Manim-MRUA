# Proyecto de Física: MRUA con Manim

Video-ensayo sobre el Movimiento Rectilíneo Uniformemente Acelerado (MRUA), creado con Manim para la asignatura TICS.

**Estudiante:** Graciela Rojas Silva
**Universidad:** Universidad de Talca, 2025

---

## Estructura del Proyecto

Este repositorio está organizado de la siguiente manera:

* `/codigo/trabajo_tics_mrua.py`: Es el **único** script de Python que contiene todas las escenas (Clases) de Manim para el video completo.
* `/assets/audio/`: Contiene todos los archivos de narración (`.m4a`, `.mp3`) y música de fondo.
* `/assets/imagenes/`: Contiene los archivos de imagen (`.png`) usados en las escenas (como la portada y el icono).

---

## Como Ejecutar este Proyecto

### 1. Prerrequisitos

Para ejecutar este proyecto, necesitas tener Python y Manim Community instalados.
```bash

### 2. Renderizar una Escena Individual

Todas las escenas están en el archivo `trabajo_tics_mrua.py`. Para renderizar una escena específica, debes indicar el archivo y luego el **nombre de la Clase** de la escena.

El comando para renderizar en alta calidad (1080p, 60fps) es:
`manim -pqh [ruta_del_archivo] [NombreDeLaClase]`

**Ejemplo para renderizar S1 (Apertura):**
```bash
manim -pqh codigo/trabajo_tics_mrua.py S1_Apertura

### 3. Unir el Video Final

Después de renderizar todas las escenas (S1, S2, S3a, S3b, S4, S5a, S5b, S6, S7), los archivos `.mp4` finales se encontrarán en la carpeta:
`media/videos/codigo/1080p60/`

Para crear el video final, puedes importar estos 9 archivos `.mp4` en cualquier software de edición de video (como DaVinci Resolve, Kdenlive, Adobe Premiere, etc.) y colocarlos en la línea de tiempo, uno después del otro, en el orden correcto.
