# GESTION DE AULA GRUPAL

## Ingeniería de Requisitos (ISR-401)

**Estudiantes:** Alvia Villegas Erick Adalberto , Chalacan Toala Yerai David
**Docente:** Ing. Guerrero Ulloa Gleiston Cicerón  
**Universidad:** Universidad Técnica Estatal de Quevedo  

---

## Descripción

Repositorio correspondiente al Trabajo Gestion de Aula correspondiente a la Unidad I de la asignatura Ingeniería de Requisitos (ISR-401).

El trabajo desarrolla el caso ** MEDICLAB ** mediante 5 actividades

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

ej: `cd "C:\Users\GAMEMAX\OneDrive\Documentos\00_Git\ISR401-AlviaErick\TrabajosGrupales\GA-SUM-01"`

luego colocar el siguiente comando: 

`pdflatex main.tex`

despues de completar la primera carga use el siguiente comando para la generacion de referencias bibliograficas:

`bibtex main`

vuelva a ejecutar `bibtex main` para corrección de errores de referencias y prosiga

Volver a ejecutar permite actualizar correctamente la numeración, referencias internas y demás elementos generados por LaTeX:

`pdflatex main.tex`

## Dependencias

El documento utiliza los siguientes paquetes de LaTeX:

* `inputenc`
* `fontenc`
* `lmodern`
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
* `cyte`

---

## Estructura del repositorio

```text
GA-SUM-01/
├── main.tex
├── Tarea_IR_ALVIAERICK.pdf
├── README.md
├── Evidencia_Interfacez/
├── Figuras/
    ├── DiagramaConceptual.jpeg
    ├── DiagramaContextual.jpeg
    ├── DiagramaConceptual.drawio
    └── Evidencia_mendeley.jpeg




