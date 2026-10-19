# Notas de teoría espectral, álgebras de Banach y C*-álgebras

Autor: Enrique Díaz Ocampo

Estas notas parten de los PDF docentes Parte1.pdf, cap2.pdf, T1.pdf y Tarea2.pdf. Los ejemplos de investigación se contrastaron con los artículos primarios disponibles en haseman-literature-index.

## Archivos

| Archivo | Contenido |
|---|---|
| main.tex, sections/00_mapa_global.tex | Documento principal y mapa de Parte 1 y Sección 2. |
| sections/01_banach.tex | Invertibilidad, espectro, resolvente, ideales, Gelfand y radio espectral. |
| sections/02_cstar.tex | Identidad C*, normalidad, permanencia y cálculo funcional. |
| sections/03_tarea1.tex, sections/04_tarea2.tex | Soluciones desarrolladas, dependencias y continuidad curricular. |
| sections/05_investigacion.tex | Puentes verificados hacia Calkin, Plemelj, Haseman y símbolos. |
| sections/06_mapa_tareas.tex | Correspondencias entre las tareas, el curso y la investigación. |
| sections/07_indice_literatura.tex | Índice final de conexiones con artículos concretos. |
| FUENTES_Y_TRAZABILIDAD.md | Fuentes primarias, localizadores y alcance de cada ejemplo. |
| REVISION_HASeman_EXAMPLES.md | Ejemplos nuevos, modificados y descartados. |
| MAPA_DEPENDENCIAS.md | Grafo textual de resultados y cobertura de ejercicios. |
| AUDITORIA_ENUNCIADOS.md | Revisión de hipótesis, símbolos, corolarios y correcciones frente a los PDF base. |
| AUDITORIA_EJEMPLOS.md | Inventario y revisión pedagógica de todos los ejemplos. |
| AUDITORIA_VISUAL.md | Inspección de diagramas, cajas y continuidad de página. |
| CHANGELOG.md | Cambios matemáticos y pedagógicos de esta revisión. |
| main.pdf | Documento compilado. |
| main_en.tex, main_en.pdf, sections_en/ | Edición íntegra en inglés del documento. |
| README_EN.md | Guía de lectura y compilación de la edición inglesa. |

Los estilos notes.cls, notes.sty, miestilo.sty, coloredtheorem.sty y mathmongo-macros.sty son parte de la infraestructura del proyecto.

## Compilación

Desde esta carpeta:

    pdflatex -interaction=nonstopmode -halt-on-error main.tex
    pdflatex -interaction=nonstopmode -halt-on-error main.tex

La segunda pasada estabiliza índice y referencias.

Para compilar también la edición inglesa:

    pdflatex -interaction=nonstopmode -halt-on-error main_en.tex
    pdflatex -interaction=nonstopmode -halt-on-error main_en.tex

## Clave de lectura

Cada resultado del curso se lee como enunciado, demostración, diagrama de la prueba y ejemplo. Las conexiones con la literatura aparecen después de ese recorrido. En particular, las proyecciones ortogonales del modelo Hilbertiano en la recta o el círculo se distinguen de los operadores P± del problema de Haseman sobre una estrella abierta. Pasar de una clase invertible en Calkin a un criterio de símbolo requiere las hipótesis del artículo correspondiente.
