# Auditoría de ejemplos

## Criterio

Se inspeccionaron los 95 entornos `cthejemplo` del TeX y su posición en el PDF. Cada uno tiene título descriptivo, objeto y objetivo antes del cálculo, desarrollo proporcional e interpretación posterior. Cuando aplica un resultado previo, el ejemplo o su contexto inmediato lo identifica. Las demostraciones generales permanecen fuera de estos entornos y los contraejemplos dicen qué hipótesis o conclusión ponen a prueba.

La tabla da la ubicación y el resultado o sección que organiza cada ejemplo. **✓** significa que se revisaron contexto, objetivo, desarrollo, interpretación y uso de antecedentes, y que el bloque se comprobó en el PDF. La longitud por sí sola no se usó como criterio: un cálculo matricial breve puede ser suficiente si todos sus pasos decisivos son visibles.

## Parte 1 (27)

| ID | Ubicación TeX | Título | Ancla curricular | Estado |
|---|---|---|---|---|
| B-01 | `sections/01_banach.tex:20` | Funciones acotadas como álgebra de Banach | Definición 1.1 | ✓ |
| B-02 | `sections/01_banach.tex:36` | Composición de operadores acotados | Definición 1.1 | ✓ |
| B-03 | `sections/01_banach.tex:81` | Conjugación puntual como involución | Definición 1.4 | ✓ |
| B-04 | `sections/01_banach.tex:145` | Serie de Neumann para una matriz perturbada | Proposición 1.8 | ✓ |
| B-05 | `sections/01_banach.tex:160` | Invertibilidad estable alrededor de un operador | Proposición 1.8 | ✓ |
| B-06 | `sections/01_banach.tex:214` | Radio de estabilidad alrededor de $2I_n$ | Observación 1.9 | ✓ |
| B-07 | `sections/01_banach.tex:252` | Invertibilidad de $2I_2-A$ fuera del disco normado | Corolario 1.10 | ✓ |
| B-08 | `sections/01_banach.tex:283` | Espectro como imagen de una función continua | Definición 1.11 | ✓ |
| B-09 | `sections/01_banach.tex:324` | Espectro de una matriz triangular | Proposición 1.12 | ✓ |
| B-10 | `sections/01_banach.tex:351` | Resolvente de una matriz diagonal | Definición 1.13 | ✓ |
| B-11 | `sections/01_banach.tex:364` | Resolvente visto en el álgebra de operadores | Definición 1.13 | ✓ |
| B-12 | `sections/01_banach.tex:424` | Derivada del resolvente escalar | Lema 1.14 | ✓ |
| B-13 | `sections/01_banach.tex:473` | Espectro sin recurrir a un determinante | Teorema 1.15 | ✓ |
| B-14 | `sections/01_banach.tex:516` | Los escalares como álgebra de división | Teorema 1.16 | ✓ |
| B-15 | `sections/01_banach.tex:537` | La evaluación puntual es un carácter | Definición 1.17 | ✓ |
| B-16 | `sections/01_banach.tex:582` | Norma del funcional de evaluación en $C(X)$ | Proposición 1.18 | ✓ |
| B-17 | `sections/01_banach.tex:637` | Clases y norma en un cociente sencillo | Definición 1.19 | ✓ |
| B-18 | `sections/01_banach.tex:694` | Un ideal maximal definido por evaluación | Proposición 1.20 | ✓ |
| B-19 | `sections/01_banach.tex:785` | Recuperar dos puntos a partir de ideales | Proposición 1.21 | ✓ |
| B-20 | `sections/01_banach.tex:837` | Espectro de la función cuadrado en $[0,1]$ | Teorema 1.22 | ✓ |
| B-21 | `sections/01_banach.tex:892` | La identidad de Jacobson en matrices que no conmutan | Proposición 1.23 | ✓ |
| B-22 | `sections/01_banach.tex:948` | Cambio de orden entre dimensiones diferentes | Corolario 1.24 | ✓ |
| B-23 | `sections/01_banach.tex:975` | Radio espectral y norma de matrices | Definición 1.25 | ✓ |
| B-24 | `sections/01_banach.tex:1080` | El operador de Volterra es cuasinilpotente | Teorema 1.26 | ✓ |
| B-25 | `sections/01_banach.tex:1117` | La transformada recupera una función de $C(X)$ | Definición 1.27 | ✓ |
| B-26 | `sections/01_banach.tex:1196` | Unidad local para un ideal de evaluación | Definición 1.29 | ✓ |
| B-27 | `sections/01_banach.tex:1238` | Un cociente unital de $C_0(\mathbb R)$ | Proposición 1.31 | ✓ |

## Sección 2 (27)

| ID | Ubicación TeX | Título | Ancla curricular | Estado |
|---|---|---|---|---|
| C-01 | `sections/02_cstar.tex:14` | Operadores en Hilbert y la identidad $C^*$ | Definición 2.1 | ✓ |
| C-02 | `sections/02_cstar.tex:42` | Unidad autoadjunta de norma uno en matrices | Observación 2.2 | ✓ |
| C-03 | `sections/02_cstar.tex:71` | Funciones como operadores de multiplicación | Definición 2.4 | ✓ |
| C-04 | `sections/02_cstar.tex:98` | Normalidad, autoadjunción, unitariedad y proyección en $M_2$ | Definición 2.5 | ✓ |
| C-05 | `sections/02_cstar.tex:180` | Norma y radio de una matriz normal | Teorema 2.6 | ✓ |
| C-06 | `sections/02_cstar.tex:224` | La norma uniforme está forzada en $C(X)$ | Corolario 2.7 | ✓ |
| C-07 | `sections/02_cstar.tex:269` | Restricción como $*$-homomorfismo contractivo | Teorema 2.8 | ✓ |
| C-08 | `sections/02_cstar.tex:299` | Partes autoadjuntas de una matriz no hermitiana | Observación 2.9 | ✓ |
| C-09 | `sections/02_cstar.tex:340` | La cota vertical es exacta para escalares reales | Lema 2.10 | ✓ |
| C-10 | `sections/02_cstar.tex:371` | Una cota que falla para $1+i$ | Proposición 2.11 | ✓ |
| C-11 | `sections/02_cstar.tex:412` | Una evaluación cumple la hipótesis de realidad | Proposición 2.12 | ✓ |
| C-12 | `sections/02_cstar.tex:452` | Valores propios reales de una matriz hermitiana | Proposición 2.13 | ✓ |
| C-13 | `sections/02_cstar.tex:516` | Una evaluación preserva la conjugación | Corolario 2.14 | ✓ |
| C-14 | `sections/02_cstar.tex:561` | Conjugación bajo la transformada de Gelfand | Corolario 2.15 | ✓ |
| C-15 | `sections/02_cstar.tex:603` | Inversos de una matriz detectados por sus productos | Proposición 2.16 | ✓ |
| C-16 | `sections/02_cstar.tex:653` | Contraejemplo: el álgebra del disco no preserva espectros | Proposición 2.17 | ✓ |
| C-17 | `sections/02_cstar.tex:708` | Interpolación en el espectro de una matriz diagonal | Proposición 2.18 | ✓ |
| C-18 | `sections/02_cstar.tex:728` | Polinomios de coordenada y conjugada en un compacto | Teorema 2.19. Se usa como herramienta externa; no se reproduce aquí su demostración completa. | ✓ |
| C-19 | `sections/02_cstar.tex:770` | Matrices diagonales como funciones en dos puntos | Teorema 2.20 | ✓ |
| C-20 | `sections/02_cstar.tex:818` | Reconstruir el intervalo a partir de su álgebra | Corolario 2.21 | ✓ |
| C-21 | `sections/02_cstar.tex:892` | Raíz espectral de una matriz diagonal | Teorema 2.22 | ✓ |
| C-22 | `sections/02_cstar.tex:954` | La raíz de $t^2$ es $\lvert t\rvert$ | Observación 2.25 | ✓ |
| C-23 | `sections/02_cstar.tex:998` | Una raíz transportada a operadores de multiplicación | Lema 2.26 | ✓ |
| C-24 | `sections/02_cstar.tex:1046` | La representación diagonal de $C(\{1,2\})$ | Teorema 2.27 | ✓ |
| C-25 | `sections/02_cstar.tex:1095` | Contraejemplos: espectro pequeño sin normalidad | Proposición 2.28; corresponde directamente a la Tarea 2.6 | ✓ |
| C-26 | `sections/02_cstar.tex:1135` | Un autoadjunto como media de dos unitarios | Proposición 2.29 | ✓ |
| C-27 | `sections/02_cstar.tex:1178` | Módulo de una matriz nilpotente | Proposición 2.30 | ✓ |

## Tarea 1 (22)

| ID | Ubicación TeX | Título | Ancla curricular | Estado |
|---|---|---|---|---|
| T1-01 | `sections/03_tarea1.tex:34` | Producto de operadores que convergen | T1.1(a) | ✓ |
| T1-02 | `sections/03_tarea1.tex:74` | Inversión de una perturbación pequeña | T1.1(b) | ✓ |
| T1-03 | `sections/03_tarea1.tex:119` | Conmutación de matrices diagonales e inversos | T1.2(a) | ✓ |
| T1-04 | `sections/03_tarea1.tex:152` | El inverso de una matriz normal | T1.2(b) | ✓ |
| T1-05 | `sections/03_tarea1.tex:198` | Añadir la unidad cambia el álgebra generada | T1.3(a) | ✓ |
| T1-06 | `sections/03_tarea1.tex:245` | Un conmutante de matrices diagonales | T1.3(b) | ✓ |
| T1-07 | `sections/03_tarea1.tex:275` | Álgebra de un nilpotente | T1.3(c) | ✓ |
| T1-08 | `sections/03_tarea1.tex:304` | Un normal genera una álgebra involutiva conmutativa | T1.3(d) | ✓ |
| T1-09 | `sections/03_tarea1.tex:349` | Una clase en el álgebra de Calkin | T1.4 | ✓ |
| T1-10 | `sections/03_tarea1.tex:409` | Una función que se desvanece en la recta | T1.5 | ✓ |
| T1-11 | `sections/03_tarea1.tex:451` | Espectro del adjunto no normal | T1.6 | ✓ |
| T1-12 | `sections/03_tarea1.tex:485` | Límite de matrices normales | T1.7 | ✓ |
| T1-13 | `sections/03_tarea1.tex:520` | Inclusión espectral estricta en un cociente | T1.8 | ✓ |
| T1-14 | `sections/03_tarea1.tex:574` | Una subálgebra espectralmente fiel de matrices | T1.9 | ✓ |
| T1-15 | `sections/03_tarea1.tex:622` | Un espectro con forma de circunferencia | T1.10 | ✓ |
| T1-16 | `sections/03_tarea1.tex:670` | La identidad $C^*$ en una matriz diagonal | T1.11(a) | ✓ |
| T1-17 | `sections/03_tarea1.tex:698` | Valores propios de una matriz triangular | T1.11(b) | ✓ |
| T1-18 | `sections/03_tarea1.tex:731` | Espectro aproximado sin vector propio | T1.11(c) | ✓ |
| T1-19 | `sections/03_tarea1.tex:765` | Una isometría que no es sobreyectiva | T1.11(d) | ✓ |
| T1-20 | `sections/03_tarea1.tex:813` | Aproximación polinómica en el álgebra del disco | T1.12(a) | ✓ |
| T1-21 | `sections/03_tarea1.tex:850` | La norma del disco se alcanza en la frontera | T1.12(b) | ✓ |
| T1-22 | `sections/03_tarea1.tex:888` | El inverso depende del álgebra ambiente | T1.12(c) | ✓ |

## Tarea 2 (16)

| ID | Ubicación TeX | Título | Ancla curricular | Estado |
|---|---|---|---|---|
| T2-01 | `sections/04_tarea2.tex:64` | Un operador diagonal en el espacio de sucesiones | T2.1 | ✓ |
| T2-02 | `sections/04_tarea2.tex:111` | Espectro de una proyección matricial | T2.2(a) | ✓ |
| T2-03 | `sections/04_tarea2.tex:144` | La desigualdad del radio puede ser estricta | T2.2(b) | ✓ |
| T2-04 | `sections/04_tarea2.tex:185` | Espectro de una matriz unitaria diagonal | T2.2(c) | ✓ |
| T2-05 | `sections/04_tarea2.tex:254` | Un producto acotado de matrices | T2.3(a) | ✓ |
| T2-06 | `sections/04_tarea2.tex:302` | El ideal clásico de sucesiones nulas | T2.3(b) | ✓ |
| T2-07 | `sections/04_tarea2.tex:339` | Cuadrar un autoadjunto mediante el espectro | T2.4 | ✓ |
| T2-08 | `sections/04_tarea2.tex:393` | Un carácter dado por un punto del círculo | T2.5 | ✓ |
| T2-09 | `sections/04_tarea2.tex:429` | Espectro real sin autoadjunción | T2.6(a) | ✓ |
| T2-10 | `sections/04_tarea2.tex:461` | Espectro unitario sin unitariedad | T2.6(b) | ✓ |
| T2-11 | `sections/04_tarea2.tex:496` | Idempotente con espectro correcto que no es proyección | T2.6(c) | ✓ |
| T2-12 | `sections/04_tarea2.tex:544` | Dos operadores con el mismo espectro | T2.6(d) | ✓ |
| T2-13 | `sections/04_tarea2.tex:597` | Descomposición polar de una matriz diagonal | T2.7 | ✓ |
| T2-14 | `sections/04_tarea2.tex:649` | Continuidad de la raíz positiva | T2.8 | ✓ |
| T2-15 | `sections/04_tarea2.tex:722` | Convergencia fuerte de matrices crecientes | T2.9 | ✓ |
| T2-16 | `sections/04_tarea2.tex:775` | Un disco espectral sin valores propios | T2.10 | ✓ |

## Investigación (3)

| ID | Ubicación TeX | Título | Ancla curricular | Estado |
|---|---|---|---|---|
| I-01 | `sections/05_investigacion.tex:29` | La identidad como caso de la ecuación de Haseman | De la condición de frontera al operador | ✓ |
| I-02 | `sections/05_investigacion.tex:66` | Invertible módulo compactos sin inversa exacta | Del ideal compacto a la propiedad de Fredholm | ✓ |
| I-03 | `sections/05_investigacion.tex:226` | Oscilación lenta sin límite ordinario | Funciones lentamente oscilantes y fibras de caracteres | ✓ |

## Comprobaciones trabajadas fuera de cajas de ejemplo

| ID | Ubicación | Cálculo y lectura |
|---|---|---|
| M-01 | `sections/06_mapa_tareas.tex`, §7.4 | En $X=\ell^2$, $A=I-P$ tiene núcleo no trivial y $A+\mathcal K(X)$ es la unidad de Calkin: distingue inversa exacta de inversa módulo compactos. |
| M-02 | `sections/06_mapa_tareas.tex`, §7.4 | Con $\alpha=\mathrm{id}$ y $G=1$, $T=P_++P_-=I$ por cancelación: la reducción de Plemelj no exige $S_\Gamma^2=I$. |
| I-04 | `sections/05_investigacion.tex`, §6.4 | La sustitución de Haar verifica que $U_z$ es unitario en $L^2(\mathbb T)$; el texto distingue el shift $V_\alpha$ en $L^p(\Gamma)$. |
| I-05 | `sections/05_investigacion.tex`, §6.6 | $C(if)=-iCf$ y $C(rf)=rCf$ muestran exactamente por qué la conjugación es real lineal. |

## Correcciones representativas

- La evaluación en $C(X)$ ahora prueba las dos cotas de su norma y explica qué mide el cálculo.
- Los ejemplos de las dos tareas conectan cada cálculo con el inciso resuelto y con «Qué prepara este ejercicio».
- Los ejemplos de Calkin, Plemelj y oscilación lenta declaran el espacio de acción y distinguen el resultado del curso de la aplicación bibliográfica.
- Se evitó que tres ejemplos de la Parte 1 y una caja bibliográfica quedaran partidos de forma poco natural.
