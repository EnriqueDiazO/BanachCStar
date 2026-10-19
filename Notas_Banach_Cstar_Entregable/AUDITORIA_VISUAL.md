# Auditoría visual y continuidad de página

## Alcance

El documento contiene 86 diagramas TikZ: cuatro mapas globales, 74 diagramas de
demostraciones y tareas, seis esquemas de investigación y dos puentes finales.
La sección de dependencias añade cuatro esquemas matemáticos en cajas. La
inspección se hace sobre el PDF renderizado, no sólo sobre el código TeX.

## Criterios de revisión

- Las cajas conservan separación interior y exterior; ninguna se solapa con
  otra ni con el bloque siguiente.
- Las flechas no pasan sobre texto; las etiquetas matemáticas caben dentro de
  sus nodos y los diagramas permanecen dentro de los márgenes.
- Un título de capítulo o sección aparece con contenido útil en su página.
  Ejemplos y diagramas permanecen cerca del resultado que explican.
- Se revisan las páginas con más de 40–50 % de blanco aparente para distinguir
  final natural de capítulo de un salto artificial.

## Correcciones localizadas

| Fuente | Causa | Corrección |
|---|---|---|
| `sections/00_mapa_global.tex`, primer mapa | La ruta resolvente → no vacuidad atravesaba la caja de la cota y dos cajas casi se tocaban. | Se distribuyeron los nodos en tres filas, se aumentó la separación y se enrutó la flecha por debajo de la caja. |
| `sections/05_investigacion.tex`, ruta completa | En una compilación de control, el título y dos líneas introductorias quedaban al pie, con el mapa en la página siguiente. | `\Needspace` se aplica sólo antes de esa sección para mantener título, introducción y mapa juntos. |
| `sections/05_investigacion.tex`, §§6.3–6.4 | Los diagramas de las proyecciones de Cauchy y de los shifts empezaban en la página siguiente de sus cálculos. | Dos reservas de espacio antes de los encabezados mantienen cada explicación con su diagrama, conservando el tamaño legible de ambos. |
| `sections/05_investigacion.tex`, ejemplo de oscilación lenta | La caja dejaba sólo dos líneas en la página siguiente. | La nueva distribución sitúa completo el ejemplo con su título y cálculo en la página siguiente de la construcción de $SO(\mathbb R_+)$. |
| `sections/05_investigacion.tex`, §6.8 | El encabezado y la introducción quedaban separados de la lista de siete preguntas. | Una reserva de espacio reúne encabezado, introducción y lista. |
| `sections/06_mapa_tareas.tex`, dos puentes | La distancia entre nodos era ajustada. | Se amplió la separación horizontal y vertical sin reducir el tamaño del texto. |
| `sections/01_banach.tex` y `sections/02_cstar.tex`, resultados al pie | Varios enunciados completos cerraban una página y su demostración empezaba en la siguiente. | Tres saltos puntuales reordenan siete casos por flujo; dos ejemplos largos se marcan indivisibles para que no quede una tira aislada. |
| `sections/03_tarea1.tex` y `sections/04_tarea2.tex`, T1.2(b), T2.8 y T2.9 | Un diagrama quedaba separado de su ejemplo y dos enunciados de sus soluciones. | Cuatro reservas de espacio reúnen estos bloques sin añadir una página. |

Hay nueve `\pagebreak`: seis localizados en las dos tareas y tres antes de
resultados o sección de la parte teórica. En las tareas, dos mantienen el diagrama
de prueba junto al ejemplo correspondiente y cuatro preceden problemas nuevos
tras cerrar el anterior. Una compilación temporal por cada salto confirmó
que quitarlo separa diagrama y ejemplo o deja el enunciado al pie y la solución
en la página siguiente. En 01/02, tres saltos evitan enunciados al pie y los
casos relacionados se recompusieron por flujo. Ninguno crea más de media página
de blanco artificial en la versión actual. No hay diagramas en entornos flotantes. Los comienzos
de capítulo siguen la clase `report`.

T1.12 conserva dos cortes naturales: su título va con contexto y definiciones
al pie de una página llena, mientras el primer inciso empieza en la siguiente;
en T1.12(b), el diagrama llena el final de la página y su ejemplo inicia la
siguiente. Forzar ambos bloques juntos creó en la compilación de prueba una
página final con sólo doce líneas. Se preserva la lectura secuencial sin reducir
diagramas ni dejar una página casi vacía.

## Comprobación final

El PDF integral de 96 páginas se compiló en dos pasadas y se recorrió página por página en
contactos y a resolución individual en los puntos de riesgo. Se verificaron
los diagramas, las cajas, los títulos y los comienzos y finales de capítulo.
El capítulo 7 abre con explicación y primer mapa en la misma página. Los
espacios amplios que permanecen corresponden a finales naturales de capítulo
o a la portada; no quedan los cuatro cortes detectados en el capítulo 6.
