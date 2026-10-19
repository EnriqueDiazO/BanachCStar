# Auditoría transversal de enunciados, variables e hipótesis

Esta auditoría acompaña la edición de las notas. Se revisaron definiciones, teoremas, proposiciones, lemas, corolarios, observaciones matemáticas, ejemplos generales, pruebas y diagramas contra los cuatro PDF docentes. Las filas registran correcciones o una comprobación especial; las pruebas y cajas corregidas están en las fuentes LaTeX.

## Parte 1: álgebras de Banach

| ID | Tipo | Problema detectado | Corrección aplicada | Fuente |
|---|---|---|---|---|
| P1.4 | Definición | La denominación de álgebra de Banach involutiva no explicitaba completitud ni el alcance de la identidad de involución. | Se cuantificaron a,b,λ y se exigió que A sea Banach antes de usar la denominación. | Parte1.pdf, Def. 1.4. |
| P1.7 | Definición | La unidad y el inverso aparecían sólo mediante notación implícita. | Se fijó A unital, 1_A y el inverso bilateral único. | Parte1.pdf, Def. 1.7. |
| P1.8 | Proposición y diagrama | a no estaba declarado en la hipótesis de Neumann. | Se declaró A Banach unital y a∈A; diagrama y conclusión nombran a⁻¹. | Parte1.pdf, Prop. 1.8. |
| P1.9 | Proposición y diagrama | b aparecía en la perturbación sin b∈A. | Se declaró b∈A y se alineó el dato inicial del diagrama. | Parte1.pdf, Obs. 1.9. |
| P1.10 | Corolario, prueba y diagrama | a, λ y la unidad eran libres; λ⁻¹ se utilizaba antes de justificar λ≠0; el título decía resolvente antes de definir ρ. | Se declaró A, a∈A, λ∈C; se probó λ≠0; el título ahora expresa invertibilidad y, después de definir espectro, se da la lectura λ∈ρ_A(a). | Parte1.pdf, Cor. 1.10. |
| P1.11 | Definición | Faltaba declarar el álgebra ambiente en σ_A(a). | Se fijaron A Banach compleja unital, 1_A y a∈A. | Parte1.pdf, Def. 1.11. |
| P1.12 | Proposición y diagrama | La compacidad espectral no declaraba A y a aisladamente. | Se añadieron ambiente, variable y espectro relativo a A. | Parte1.pdf, Prop. 1.12. |
| P1.13–1.14 | Definición y lema | El resolvente y su dominio tenían a y A implícitos. | Se declararon A, a, ρ_A(a) y el codominio de R_a; diagrama tipado. | Parte1.pdf, Def. 1.13, Lema 1.14. |
| P1.15–1.16 | Teoremas | La no vacuidad y Gelfand–Mazur necesitaban explicitar cuerpo complejo en el diagrama o en el enunciado. | Se mantuvo el resultado del curso y se indicó dónde se usan Liouville, Hahn–Banach y la complejidad. | Parte1.pdf, Teoremas 1.15–1.16. |
| P1.17–1.19 | Definición y proposición | Ω(A) recibía topología débil-* antes de probar que sus caracteres pertenecen a A*. | Se separó la definición de carácter, la prueba de continuidad y la definición posterior de topología de Gelfand. | Parte1.pdf, Defs. 1.17/1.19 y Prop. 1.18. |
| P1.20–1.22 | Proposiciones y teorema | El ideal bilateral y la norma cociente no se habían definido antes de A/J; algunas afirmaciones sólo decían “A conmutativa”. | Se definieron ideal y cociente antes del teorema y se declararon Banach, complejidad y unidad donde intervienen. | Parte1.pdf, Props. 1.20–1.21 y Teo. 1.22; T1.pdf, problema 4. |
| P1.23 | Proposición y diagrama | El álgebra ambiente de 1−ab no figuraba en el enunciado aislado. | Se fijaron A unital, a,b∈A y 1_A en la conclusión. | Parte1.pdf, Prop. 1.23. |
| P1.24 | Corolario, prueba y diagrama | A,a,b no estaban declarados; la prueba debía restringirse a λ≠0 para aplicar Jacobson. | Se fijaron A, a,b∈A, y λ∈C\{0} en la prueba y el diagrama. El corolario sí se sigue del resultado padre. | Parte1.pdf, Cor. 1.24. |
| P1.25–1.26 | Definición y teorema | El radio espectral y la fórmula tenían A o a implícitos; la prueba no explicaba el caso r(a)=0 ni por qué un factor conmutante de un producto invertible es invertible. | Se declararon A,a, se adoptó 1/0=∞ y se hizo explícito el argumento de factores conmutantes. | Parte1.pdf, Def. 1.25, Teo. 1.26. |
| P1.27–1.28 | Definición y proposición | La transformada y la contractividad no declaraban A y a en enunciados aislados. | Se fijó A Banach compleja conmutativa unital, a∈A y el codominio C(Ω(A)). | Parte1.pdf, Def. 1.27, Obs. 1.28. |
| P1.29–1.31 | Definición y proposición | El criterio de modularidad dejaba I y A implícitos y el caso I=A dependía de una convención sobre el álgebra cero. | Se declaró I ideal bilateral propio en el criterio y se alineó el diagrama. | Parte1.pdf, Def. 1.29, Prop. 1.31. |
| P1.EX-CALKIN | Ejemplo general | La estructura C* del cociente podía atribuirse a un Banach general. | Se afirmó sólo estructura de Banach para X general y estructura C* cuando X es Hilbert; X se toma infinito-dimensional. | Karlovich 2025, p. 2; RSS11, §1.4.1. |
| P1.EX-RECT | Ejemplo | AB y BA rectangulares viven en matrices de tamaños distintos y no son caso literal del corolario en una misma álgebra. | Se escribió la fórmula rectangular del inverso con dominios y codominios correctos. | Elaboración de la identidad de Jacobson de Parte1.pdf, Prop. 1.23. |
| P1.EX-SO | Ejemplo general | La terminología C* aparecía antes de su definición formal. | Se señaló que aquí sólo se usa el álgebra Banach conmutativa; la identidad C* se retoma en Sección 2. | Karlovich 2017, §2, pp. 465–466. |
| P1.EX-VACÍO | Ejemplos generales | Con la convención de unidad de norma uno, C_b(∅), C(∅) y B({0}) son casos degenerados. | Los ejemplos unitarios declaran espacio topológico no vacío o Banach no nulo. | Parte1.pdf, Def. 1.1 y ejemplos. |

## Tarea 1 y Tarea 2

| ID | Tipo | Problema detectado | Corrección aplicada | Fuente |
|---|---|---|---|---|
| T1.1–T1.2 | Hipótesis | La completitud, unidad e involución aparecían implícitas en incisos distintos. | Se declararon A Banach en 1(a), A unital en 1(b)/2(a) e involución en 2(b), sin imponerlas donde sobran. | T1.pdf, p. 1. |
| T1.3 | Dominio y definición | El álgebra generada por involución requiere A involutiva y S⊂A. | Se declararon S, S* y las hipótesis del inciso correspondiente. | T1.pdf, p. 1. |
| T1.4 | Hipótesis y alcance | El cociente necesita J bilateral cerrado; el criterio de Fredholm no es parte de esa prueba. | Se separó la prueba de completitud del ejemplo Calkin y del teorema adicional de Fredholm. | T1.pdf, p. 1; Karlovich 2025, p. 2. |
| T1.5–T1.7 | Hipótesis | C₀(X) necesita X localmente compacto Hausdorff; espectro/involución y cierre de normales requieren sus álgebras respectivas. | Se declararon espacios, involución, convergencia y alcance no unital de C₀(X). | T1.pdf, p. 2. |
| T1.8–T1.10 | Homomorfismo y espectro | Faltaban dominios/codominios y condiciones de unidad, conmutación y compacidad en incisos diferentes. | Se declararon A,B, ψ, S, X y f según el ejercicio. | T1.pdf, p. 2. |
| T1.11 | Hipótesis y prueba | H, T∈B(H) y la completitud de B(H) estaban demasiado implícitos. | Se tiparon los objetos y se remitió a la construcción de Parte 1. | T1.pdf, p. 2. |
| T1.12 | Errata matemática de fuente | La conjugación puntual indicada en T1.pdf, p. 3, no preserva el álgebra del disco. | La inclusión en C(T) se presenta como subálgebra de Banach no autoadjunta; se exhibe h(z)=z como contraejemplo. | T1.pdf, p. 3. |
| T2.1–T2.3 | Dominios y casos límite | X, ℓ²(X), familias de álgebras e ideal c₀ necesitaban cuantificadores y tratamiento del conjunto vacío. | Se declararon índices, espacios y operaciones; se comprobó la estabilidad por adjunto. | Tarea2.pdf, p. 1. |
| T2.4–T2.6 | Hipótesis espectrales | Cálculo funcional y recíprocas espectrales requieren A unital, x normal y f∈C(σ(x)). | Se explicitaron esas hipótesis en los incisos y contraejemplos. | Tarea2.pdf, pp. 1–2. |
| T2.7–T2.8 | Cuantificadores | El módulo de a existe para todo a, pero u polar exige inversibilidad; continuidad funcional requiere un compacto común de espectros. | Se separaron los cuantificadores y se declaró el compacto K. | Tarea2.pdf, p. 2. |
| T2.9–T2.10 | Dominios y prueba | La red de operadores, el orden, la convergencia fuerte y el uso del adjunto necesitaban definición local. | Se añadieron las definiciones y se comprobó la polarización y el disco espectral del shift. | Tarea2.pdf, p. 2. |

## Segunda pasada de corolarios

Los dos corolarios de Parte 1 (P1.10 y P1.24) se contrastaron por separado con su resultado padre, sus variables, hipótesis, título, prueba y diagrama. P1.10 se deriva de Neumann y sólo afirma invertibilidad antes de introducir ρ; P1.24 se deriva de Jacobson para λ≠0. Los cuatro corolarios de Sección 2 (2.7, 2.14, 2.15 y 2.21) se comprobaron contra su resultado padre y cap2.pdf; las correcciones se detallan abajo.

## Sección 2

Se contrastaron los resultados numerados 2.1–2.30 con cap2.pdf, pp. 1–8, y la nota histórica con pp. 8–10. Las filas reúnen los hallazgos que exigieron una corrección; los demás enunciados conservan sus hipótesis y alcance del material base.

| ID | Tipo | Problema detectado | Corrección aplicada | Fuente |
|---|---|---|---|---|
| 2.2 | Observación y prueba | Faltaba justificar `1_A*=1_A` y `||1_A||=1`. | Se añadió la prueba explícita desde unidad e identidad C*. | cap2.pdf, p. 1. |
| 2.5 | Definición | La unidad se exigía también para normalidad, autoadjunción y proyección; faltaban `A_sa`, `U(A)` y `P(A)`. | Se exige unidad sólo para unitarios y se restituyen las notaciones. | cap2.pdf, p. 1. |
| 2.7 | Corolario | El álgebra ambiente y el elemento estaban implícitos en la unicidad de norma. | Se declaran A unital y a∈A; se prueba que el radio espectral algebraico de a*a determina la norma. | cap2.pdf, p. 2. |
| 2.11–2.12 | Proposiciones y diagrama | La constante se restringía a C>0; el funcional y el caso cero estaban incompletos. | Se permite C≥0, se tipa φ:A→C con `||φ||=φ(1_A)` y se trata φ=0. | cap2.pdf, pp. 2–3. |
| 2.13 | Proposición y prueba | La subálgebra usada en la prueba de realidad espectral necesitaba justificarse sin circularidad. | Se usa T1.9 y se verifica que la subálgebra es cerrada, unital, involutiva y C*. | cap2.pdf, p. 3 y nota al pie; Tarea 1.9. |
| 2.14 | Corolario y diagrama | El enunciado se había estrechado indebidamente a caracteres. | Se restituye todo funcional continuo con `||φ||=φ(1_A)` y la prueba descompone a=x+iy. | cap2.pdf, p. 3. |
| 2.15 | Corolario y prueba | La compatibilidad de Gelfand con la involución dejaba libre al carácter. | Se fija φ∈Ω(A) y se aplica 2.14 punto a punto. | cap2.pdf, pp. 3–4. |
| 2.17 | Proposición y prueba | Desajuste de variables en el argumento de permanencia e inversos. | Se prueba primero para h autoadjunto y después para b*b y bb*. | cap2.pdf, p. 4. |
| 2.21 | Corolario y prueba | La unicidad del compacto remitía circularmente a T2.5, posterior. | Se demuestra dentro del capítulo que Ω(C(Y)) es homeomorfo a Y. | cap2.pdf, p. 6; Tarea 2.5. |
| 2.23–2.24 | Definición y observación | Faltaba explicitar el mapa `C_b(E)→A`; la Observación 2.24 se había presentado como ejemplo. | Se escribe el *-homomorfismo unital por restricción y se restituye el tipo de observación. | cap2.pdf, pp. 6–7. |
| 2.27–2.29 | Teorema, proposiciones y diagramas | La función separadora, normalidad y escala de unitarios requerían hipótesis y pasos expresos; la prueba de 2.28 dependía de T2.2 posterior. | Se fija dominio y no anulación de la función, se usa cálculo funcional para 2.28 y se precisa la escala en 2.29. | cap2.pdf, pp. 7–8. |
| 2.30 | Proposición y prueba | Se afirmaba unicidad global de la raíz positiva sin demostrarla en la ruta del capítulo. | Se vuelve al enunciado de existencia de cap2.pdf y se prueba por cálculo funcional. | cap2.pdf, p. 8. |
| EX-CSTAR y EX-PROJ | Conexiones laterales | La fórmula P±=(I±SΓ)/2 podía hacer pensar que SΓ²=I en la estrella abierta de Haseman. | Se separa el modelo Hilbertiano de BFK2006 de la reducción por Plemelj de Karlovich2017; se añaden C_b(Γ), SO(Γ) y las fibras cuando el curso ya define esas nociones. | BFK2006, §2, p. 22; Karlovich2017, §1, p. 464 y §2, pp. 465–466. |
| Nota histórica | Sección | Faltaba la nota histórica del capítulo base. | Se restituyó de forma resumida al final de la Sección 2. | cap2.pdf, pp. 8–10. |

La raíz `|a|=(a*a)^{1/2}` usa además el hecho estándar `a*a≥0`; el capítulo lo identifica como antecedente adicional y no lo atribuye a la proposición 2.30.

## Pasada de demostraciones completas y orden editorial

En la Sección 2, los veinte diagramas de demostración se colocaron después de la prueba correspondiente. Se revisaron en particular la unicidad de la descomposición de la Observación 2.9, la prueba de la Observación 2.25, la invertibilidad en ambas direcciones de 2.16–2.17, la continuidad e inversa de 2.18, la clausura de la imagen isométrica de 2.20, la construcción del cálculo funcional de 2.22, los dos mapas del Lema 2.26 y la función separadora del Teorema 2.27. En los Corolarios 2.7, 2.14, 2.15 y 2.21 se escribió la especialización del resultado padre, se verificaron las hipótesis y se dejó explícita la conclusión.

Stone–Weierstrass (Teorema 2.19) se identifica como herramienta externa, tal como ocurre en cap2.pdf. La nota `a*a≥0` se marca como antecedente estándar adicional donde se usa el módulo; no se presenta como una consecuencia probada por la Prop. 2.30.

En las tareas se revisaron los 22 incisos de Tarea 1 y los 16 de Tarea 2. Una comprobación estructural encontró en los 38 bloques la secuencia enunciado, solución, diagrama, ejemplo, Dependencias y Qué prepara. Se completaron, entre otros, el caso de índice vacío en T2.1, la prueba bilateral de inversos de T1.8, la unidad en `C*(a,1)` de T1.3(d), los contraejemplos de T2.6(d), la invertibilidad de `|a|` en T2.7 y la desigualdad positiva usada en T2.9. Las conexiones bibliográficas se colocaron después de las soluciones.
