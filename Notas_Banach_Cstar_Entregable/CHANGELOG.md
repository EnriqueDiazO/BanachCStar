# Cambios de la segunda revisión

## Matemática y fuentes

- Se corrigió la atribución de proyecciones ortogonales a los operadores P± del problema de Haseman sobre una estrella abierta. BFK 2006 sí proporciona proyecciones ortogonales para el modelo L²(R/T); Karlovich 2017, teorema 5.3, da un caso de estrella abierta con SΓ²≠I.
- Se corrigió la observación de T1.pdf, p. 3, sobre el álgebra del disco: la conjugación puntual no preserva funciones holomorfas. La comparación de espectros sigue siendo válida como inclusión de álgebras de Banach unitales.
- Se precisaron el espacio real subyacente de la álgebra con conjugación de Karlovich 2025, la diferencia entre Calkin Banach y Calkin C*, y las hipótesis de los criterios de símbolo.
- Se separó el teorema 6.2 de Karlovich 2025 (subálgebra compleja) del teorema 7.2 (álgebra real con conjugación), enlazados por la representación matricial compleja del teorema 7.1.
- Se señaló como antecedente estándar adicional la positividad de a*a para construir |a|; el PDF cap2.pdf no la demuestra.
- Se auditaron los seis corolarios del curso contra sus fuentes: hipótesis, variables, unidad, título, especialización del resultado padre, prueba y diagrama.
- Se corrigieron los localizadores de C_b(Γ)/SO(Γ) a Karlovich 2017, p. 464, y de las rotaciones U_z a BFK 2006, §1, p. 20.

## Aprendizaje y estructura

- Se añadieron los puentes Neumann → resolvente → espectro y ideal K(X) → Calkin → invertibilidad de clase → Fredholm, con ejemplos calculables.
- La deducción Sokhotski–Plemelj → T muestra explícitamente Φ−=−P−φ y conserva el signo correcto.
- Se redibujaron mapas de dependencias para que las flechas representen pasos de prueba; las analogías con investigación se etiquetan aparte.
- Cada inciso resuelto de Tarea 1 y Tarea 2 declara sus dependencias y lo que prepara.
- Se añadieron notas sobre el uso de hipótesis, un ejemplo de función lentamente oscilante sin límite ordinario y distinciones entre homomorfismos, transformada de Gelfand y mapas de símbolo.
- Se preservaron las demostraciones desarrolladas y los ambientes del estilo LaTeX existente.
- Las pruebas y sus diagramas se ordenaron como enunciado → demostración → diagrama → ejemplo; los 38 incisos de las dos tareas colocan después Dependencias y Qué prepara.
- Se completaron pasos abreviados de Neumann, radio espectral, espectro real, permanencia, cálculo funcional, tareas y corolarios. La función de oscilación lenta incluye ahora la cota de oscilación y sucesiones que prueban la ausencia de límite.
- Se revisaron los ejemplos para que declaren objeto y objetivo antes del cálculo, desarrollen los pasos necesarios e interpreten el resultado; los dos mapas hacia Haseman incluyen una comprobación concreta cada uno.
- El mapa de la Sección 2 separa la igualdad norma–radio para normales de la conmutatividad de C*(a,1), pues tienen dependencias distintas.
- Se inventariaron y revisaron las 95 cajas de ejemplo: propósito, cálculo, interpretación y enlace con el resultado previo. La revisión puntual del ejemplo de oscilación lenta añadió una cota explícita y dos sucesiones que prueban la falta de límite.
- Se inspeccionaron los 86 diagramas TikZ y las cajas del PDF página por página. Se redistribuyeron el mapa global, dos puentes y la paginación de las proyecciones de Cauchy, los shifts, el ejemplo de oscilación lenta y la ruta de lectura.

## Entregables

- Fuentes: main.tex y sections/00–07.
- Evidencia: FUENTES_Y_TRAZABILIDAD.md y REVISION_HASeman_EXAMPLES.md.
- Lectura estructural: MAPA_DEPENDENCIAS.md y AUDITORIA_ENUNCIADOS.md.
- Registros de revisión: AUDITORIA_EJEMPLOS.md y AUDITORIA_VISUAL.md.
- PDF: main.pdf, compilado y revisado tras la integración final.
- La skill `consistencia-notas-cocid` recibió una regla, checklist y caso de regresión para detectar ejemplos telegráficos.
