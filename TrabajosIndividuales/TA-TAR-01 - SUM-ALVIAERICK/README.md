# Prueba Práctica - Unidad IV

## Ingeniería de Requisitos (ISR-401)

**Estudiante:** Alvia Villegas Erick Adalberto  
**Docente:** Ing. Guerrero Ulloa Gleiston Cicerón  
**Universidad:** Universidad Técnica Estatal de Quevedo  

---

## Descripción

Repositorio correspondiente al Trabajo autónomo correspondiente a la Unidad I de la asignatura Ingeniería de Requisitos (ISR-401).

El trabajo desarrolla el caso ** Discord como plataforma de comunicacion** mediante 5 actividades
---
## Contenido del desarrollo

* **P1. Redactar un resumen analítico de 1,5 a 2 páginas, con sus palabras y citando la cláusula exacta. Debe explicar qué es un requisito bien formado, las características de un requisito individual y de un conjunto, y los términos ambiguos que la norma prohíbe.
* **P2. Elaborar un glosario de 10 términos de la cláusula 3, cada uno con un ejemplo propio.
* **P3. Formular 15 requisitos de al menos cinco tipos distintos. Al menos 5 deben ser de calidad, clasificados con ISO/IEC 25010:2023 y cuantificados con métrica y umbral.
* **P4. Presentar una tabla de clasificación con el criterio de aceptación de cada requisito.
* **P5. Autoevaluar cada requisito y escribir su versión corregida.
* **P6. Escribir una reflexión de media página.
---

## Compilación

El documento fue desarrollado en **LaTeX** y compilado mediante **pdfLaTeX** por medio de la terminal del computador con el uso de MikTex.

### Compilador
`pdfLaTeX`

### Archivo principal
`main.tex`

## Figuras y Evidencias

### Carpeta `Figuras/`
* `Canal_Texto_Discord_chat.png`: Canales de textos manejados en un servidor propio de Discord.
* `discord_permisos.png`: Imagen de Roles y Permisos correspondientes a los Miembros del Servidor de Discord.
* `discord_notificaciones.png`: Manejo de Notificaciones para los distintos canales de discord.


### Orden de compilación
Ejecutar en la terminal del computador (se recomienda tener instalado MikTex):
dentro del terminal colocar el siguiente comando cd "Ruta donde se encuentra su archivo en el explorador"; 

ej: `cd "C:\Users\GAMEMAX\OneDrive\Documentos\00_Git\ISR401-AlviaErick\TrabajosIndividuales\TA-TAR-01 - SUM-ALVIAERICK"`

luego colocar el siguiente comando: 

`pdflatex main.tex`

despues de completar la primera carga use el siguiente comando para la generacion de referencias bibliograficas:

`bibtex main`

Volver a ejecutar permite actualizar correctamente la numeración, referencias internas y demás elementos generados por LaTeX:

`pdflatex main.tex`

## Dependencias

El documento utiliza los siguientes paquetes de LaTeX:

* `inputenc`
* `babel`
* `geometry`
* `graphicx`
* `booktabs`
* `array`
* `tabularx`
* `enumitem`
* `xcolor`
* `titlesec`
* `fancyhdr`
* `hyperref`
* `float`

---

## Estructura del repositorio

```text
TA-TAR-01-SUM-ALVIAERICK/
├── main.tex
├── Tarea_IR_ALVIAERICK.pdf
├── README.md
├── Figuras/
    ├── Canal_Texto_Discord_chat.png
    ├── discord_permisos.png
    └── discord_notificaciones.png



