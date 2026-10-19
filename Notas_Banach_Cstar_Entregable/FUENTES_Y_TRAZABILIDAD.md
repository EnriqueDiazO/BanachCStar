# Fuentes y trazabilidad matemática

## Jerarquía y estado de las fuentes

La teoría y la numeración original del curso se contrastaron con los cuatro PDF docentes. La literatura de investigación aporta objetos y aplicaciones; no reemplaza los resultados del curso.

| Nivel | Documento local | Uso |
|---|---|---|
| A | /home/enriquedo/Descargas/C star/Parte1.pdf (SHA-256 89b500da…390a99) | Definiciones y resultados de álgebra de Banach y espectro. |
| A | /home/enriquedo/Descargas/C star/cap2.pdf (30a9d7d4…8197fa4) | Sección 2 de C*-álgebras. |
| A | /home/enriquedo/Descargas/C star/T1.pdf (13c9c061…f75c7) | Enunciados de Tarea 1; el nombre real del archivo es T1.pdf. |
| A | /home/enriquedo/Descargas/C star/Tarea2.pdf (59a2cd82…48587ca) | Enunciados de Tarea 2. |
| B | haseman-literature-index/links/by_key/Karlovich2017HasemanSO.pdf (9f92e375…15e9091) | Frontera, Plemelj, shifts, funciones SO, criterio de Fredholm. |
| B | haseman-literature-index/links/by_key/Karlovich2025Cusps.pdf (301f8435…846be23) | Calkin, álgebra con conjugación y cálculo de símbolos en cúspides. |
| B | haseman-literature-index/links/by_key/BastosFernandesKarlovich2006.pdf (ad310374…8033ef487) | Modelo Hilbertiano con proyecciones ortogonales y shifts unitarios. |
| B | haseman-literature-index/links/by_key/RSS11.pdf (9a328ff6…26f) | Exposición complementaria del cociente de Calkin; §1.4.1, pp. 45–46 impresas. |

Las páginas de Karlovich 2017 y BFK 2006 citadas abajo son páginas impresas. En Karlovich 2025 se indican páginas del artículo (la cabecera del PDF las identifica). Los identificadores EX son puntos de trazabilidad de estas notas, no identificadores del índice de literatura.

## Registro de ejemplos y puentes

| ID y lugar | Concepto de las notas | Fuente verificada: autor, año, lugar | Objeto tomado de la fuente | Explicación pedagógica propia |
|---|---|---|---|---|
| EX-HAS-FRONTERA; §§1 y 5 | Álgebra de operadores e invertibilidad | Yu. I. Karlovich, 2017, pp. 463–464, ecs. (1.1)–(1.2) | En la estrella abierta, P±=(I±SΓ)/2, Vαf=f∘α y T=VαP+ + GP− sobre Lp(Γ). | Identificar T como elemento de B(Lp(Γ)) y leer su invertibilidad con el lenguaje del curso. El símbolo M_G en las notas hace explícita la multiplicación. |
| EX-CSTAR-COEF; §2 e índice | C*-álgebra concreta | Karlovich, 2017, introducción, p. 464 | C_b(Γ) es la C*-álgebra de funciones continuas acotadas y SO(Γ) la C*-álgebra de las que oscilan lentamente en los extremos. | Recuperar un ejemplo de coeficientes después de la definición abstracta; dejar fibras y Haseman para más adelante. |
| EX-HAS-SIGNO; §5 | Reducción a ecuación de operadores | Karlovich, 2017, pp. 463–464, Sokhotski–Plemelj | Φ+=P+φ y Φ−=−P−φ antes de obtener Tφ=g. | Escribir la sustitución con el signo de la traza negativa y comprobar α=id, G=1, T=I. |
| EX-CALKIN; §§1 y 5 | Ideal cerrado, cociente, invertibilidad y Fredholm | Karlovich, 2025, p. 2; Roch–Santos–Silbermann, 2011, §1.4.1, pp. 45–46 | K(X) ideal cerrado de B(X); A Fredholm si y sólo si A+K(X) invertible en B(X)/K(X). | Construir tres niveles: clases elementales, A/J y Calkin. Distinguir inversa exacta e inversa módulo compactos. |
| EX-CALKIN-RANGO1; §§1 y 5 | Diferencia entre espectro ordinario y esencial | Derivado del criterio anterior; no figura como ese ejemplo en los artículos | Sólo se toma el criterio general de Calkin. | En ℓ², A=I−P con P de rango uno no es invertible, aunque su clase es la unidad del cociente. |
| EX-PROJ-MODELO; §§2 y 5 | Proyección algebraica y ortogonal | M. A. Bastos, C. A. Fernandes, Yu. I. Karlovich, 2006, §2, p. 22 | Para Γ=R o T en L²(Γ), SΓ²=I y PΓ±=(I±SΓ)/2 son proyecciones ortogonales. | Separar la identidad S²=I, que da idempotencia, de S*=S, que da autoadjunción. |
| EX-PROJ-LIMITE; §§1, 2 y 5 | Hipótesis de idempotencia | Karlovich, 2017, teorema 5.3 y ec. (5.5), p. 476 | En una rama con p=2 y δ=0, el símbolo de SΓ es ε₁ tanh(πx), con ε₁=±1 según orientación; su cuadrado no es 1. | Calcular P±²−P±=(SΓ²−I)/4 y explicar por qué los P± de esa geometría no son proyecciones. |
| EX-SHIFT; §§2 y 5 | Unitario frente a composición acotada | BFK, 2006, §1, p. 20; Karlovich, 2017, p. 467, ecs. (2.8)–(2.12) | Rotaciones U_z en L²(T) y shift Vα bajo condiciones de regularidad en la estrella. | Comparar invariancia de medida y adjunto con mera acotación; no llamar unitario a Vα. |
| EX-SO; §§1, 2 y 5 | C*-álgebra conmutativa, caracteres y Gelfand | Karlovich, 2017, §2, pp. 465–466, ecs. (2.1)–(2.4), props. 2.1–2.2 | SO(R+) y fibras de caracteres M₀ y M∞. | Mostrar por qué los caracteres de frontera no se reducen a evaluar a(0) o a(∞). La función sin límites ordinarios es elaboración propia de la definición. |
| EX-ALG-REAL; §5 y Tarea 1.3 | Álgebra generada por operadores | Karlovich, 2025, ec. (1.4), p. 3 | Álgebra generada por multiplicadores aI, SΓ y conjugación C en B(RLp(Γ,w)). | Tipar los generadores y explicar que C es real-lineal, no complejo-lineal; no trasladar automáticamente la teoría C* compleja. |
| EX-SIMBOLO; §5 | Homomorfismos y cálculo de símbolos | Karlovich, 2025, teoremas 4.2–4.4, pp. 15–17; teorema 6.2, p. 25; teoremas 7.1–7.2, pp. 25–26 | El teorema 6.2 da símbolos para la subálgebra compleja A; el teorema 7.1 representa matricialmente el operador real-lineal y el 7.2 da el criterio para N en la álgebra real B de (1.4). | Distinguir dominio de cada símbolo, homomorfismo abstracto, *-homomorfismo y Gelfand. |
| EX-CRITERIO-HAS; §5 | Destino de la cadena de dependencias | Karlovich, 2017, teorema 7.1 y prueba, pp. 487–489 | Criterio Fredholm para T bajo hipótesis del artículo, mediante representación Mellin módulo compactos y determinantes de símbolos. | Mostrar la ruta desde cociente hasta criterio como motivación; no aplicar el teorema a un operador de cúspide con shift sin verificar pertenencia. |

## Distinciones y verificaciones negativas

- La igualdad SΓ²=I y la ortogonalidad de P± de BFK 2006 pertenecen al modelo L²(R/T). El teorema 5.3 de Karlovich 2017 impide trasladarlas a la estrella abierta general. La reducción de frontera a T sigue siendo válida allí porque usa Plemelj, no idempotencia.
- SO(R+) de Karlovich 2017 y SO^diamond(Γ) de Karlovich 2025 son objetos distintos; los espacios maximales y símbolos se citan con sus dominios.
- El criterio de Karlovich 2025, teorema 6.2, exige pertenencia a la subálgebra compleja A; para la álgebra real B de (1.4) corresponde el teorema 7.2. El índice registra los enunciados de fuente como verificados, pero la auditoría de clase simbólica del manuscrito de investigación está BLOCKED; las notas sólo usan ese criterio como motivación.
- El PDF docente T1.pdf, p. 3, llama involutiva al álgebra del disco con conjugación puntual. Esa operación no conserva holomorfía. Las notas corrigen la observación y usan el álgebra del disco como subálgebra de Banach unital no autoadjunta de C(T).
- El hecho estándar a*a≥0, empleado para la raíz positiva y el módulo, no queda demostrado en cap2.pdf; la Sección 2 lo identifica como antecedente adicional.

## Tipo y nivel de cada conexión

| ID | Tipo de conexión | Nivel | Qué se debe reconocer |
|---|---|---|---|
| EX-HAS-FRONTERA, EX-HAS-SIGNO | Ejemplo directo y aplicación | Avanzado | T es una suma de composiciones y multiplicaciones en B(Lp(Γ)); Plemelj proporciona la ecuación, no el curso elemental. |
| EX-CSTAR-COEF, EX-SO | Ejemplo directo y uso de propiedad | Básico/intermedio | Las C*-álgebras de coeficientes y sus caracteres son objetos concretos para leer datos límite. |
| EX-CALKIN, EX-CALKIN-RANGO1 | Uso de propiedad y puente conceptual | Intermedio | El ideal J de A/J se especializa en K(X), y la inversa de la clase puede existir sin inversa de A. |
| EX-PROJ-MODELO, EX-PROJ-LIMITE | Ejemplo bajo hipótesis y contraejemplo | Intermedio | La fórmula (I±S)/2 sólo da proyecciones cuando S²=I; ortogonalidad requiere además S*=S. |
| EX-SHIFT | Comparación | Intermedio | Un shift de composición puede ser acotado sin ser unitario. |
| EX-ALG-REAL | Ejemplo directo | Avanzado | Una conjugación compleja obliga a tipar la álgebra de operadores sobre escalares reales. |
| EX-SIMBOLO, EX-CRITERIO-HAS | Construcción relacionada y para leer más | Avanzado | El cálculo de símbolos es un paso adicional, con teoremas y pertenencias propios. |
