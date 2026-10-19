# Mapa de dependencias verificadas

Una **dependencia** es una hipótesis, construcción o resultado usado en una prueba. Una **aplicación** usa un resultado en otro contexto después de verificar sus hipótesis. Una **analogía** sólo orienta la lectura. Las flechas continuas del [mapa LaTeX](sections/06_mapa_tareas.tex) representan dependencias dentro de cada construcción; su flecha discontinua entre los dos contextos de Cauchy compara la forma de las fórmulas, sin transportar propiedades de un contorno al otro.

Las correspondencias se refieren a [Parte 1](sections/01_banach.tex), [Sección 2](sections/02_cstar.tex), [Tarea 1](sections/03_tarea1.tex) y [Tarea 2](sections/04_tarea2.tex). Karlovich (2025), p. 2, respalda la formulación de Fredholm por la clase en Calkin; Karlovich (2017) respalda la reducción de frontera al operador indicado más abajo. Esas afirmaciones de investigación no se deducen de las notas abstractas por sí solas.

## R1. Inversión local y resolvente

- **RESULTADO:** La serie de Neumann invierte `1-h` cuando `‖h‖<1`; `GL(A)` es abierto y la inversión es continua. El espectro se define por la falta de invertibilidad de `λ1-a`.
- **DEPENDENCIAS:** Completitud, submultiplicatividad y unidad del álgebra de Banach (Parte 1, Def. 1.1 y Prop. 1.8); T1.1(b) demuestra la continuidad de la inversión.
- **RESULTADOS QUE DEPENDEN DE ÉL:** Espectro cerrado y acotado, holomorfía del resolvente y paso al límite de inversos en la permanencia espectral (Prop. 2.17).
- **TAREAS RELACIONADAS:** T1.1(a,b), T1.6, T1.8; T2.10 usa la cota espectral que se obtiene de Neumann.
- **CONEXIÓN SECCIÓN2:** En la Prop. 2.17, `(b+i/n)⁻¹→b⁻¹` en el álgebra ambiente y la subálgebra cerrada conserva el límite.
- **CONEXIÓN INVESTIGACIÓN:** La invertibilidad de un operador Haseman se puede formular como `0∉σ(T)` cuando `T` pertenece al álgebra de operadores considerada. La estabilidad local de invertibles es una herramienta general; no proporciona por sí sola un criterio de Fredholm.

## R2. Caracteres, radio espectral y transformada de Gelfand

- **RESULTADO:** En un álgebra de Banach conmutativa unital, los caracteres describen el espectro y `â(φ)=φ(a)` define la transformada de Gelfand. La fórmula del radio espectral es `r(a)=lim ‖aⁿ‖^(1/n)`.
- **DEPENDENCIAS:** Espectro no vacío, ideales maximales y Gelfand–Mazur (Parte 1, Teos. 1.15, 1.16 y 1.22); fórmula del radio espectral (Teo. 1.26).
- **RESULTADOS QUE DEPENDEN DE ÉL:** `‖a‖=r(a)` para normales (Teo. 2.6, con la identidad `C*`), realidad del espectro autoadjunto (Prop. 2.13, tras reducción conmutativa) y Gelfand–Naimark conmutativo (Teo. 2.20).
- **TAREAS RELACIONADAS:** T1.8, T1.9, T1.10; T2.2(b), T2.5.
- **CONEXIÓN SECCIÓN2:** El Teo. 2.20 usa que la transformada es isométrica para una `C*` conmutativa y Stone–Weierstrass para la sobreyectividad.
- **CONEXIÓN INVESTIGACIÓN:** Los espacios maximales de álgebras conmutativas de coeficientes lentamente oscilantes parametrizan evaluaciones y fibras. La interpretación concreta de cada fibra exige las hipótesis de la fuente de investigación; no sigue sólo del teorema abstracto de Gelfand.

## R3. Álgebra generada y reducción conmutativa

- **RESULTADO:** T1.3 construye la subálgebra cerrada generada por un conjunto. T1.9 escoge una subálgebra conmutativa inversamente cerrada que preserva el espectro de los elementos de partida.
- **DEPENDENCIAS:** Continuidad del producto (T1.1(a)); conmutación con inversos (T1.2); conmutación de palabras (T1.3); lema de Zorn en T1.9.
- **RESULTADOS QUE DEPENDEN DE ÉL:** Realidad del espectro de un autoadjunto en la Prop. 2.13. Para `a` normal, la conmutatividad de `C*(a,1)` participa en la Prop. 2.18 y el Teo. 2.22.
- **TAREAS RELACIONADAS:** T1.1–T1.3, T1.9; T2.4 y T2.6 usan el cálculo funcional construido después.
- **CONEXIÓN SECCIÓN2:** La reducción de T1.9 aporta preservación del espectro para aplicar caracteres; la identidad `C*` y el resultado sobre funcionales completan la prueba de realidad.
- **CONEXIÓN INVESTIGACIÓN:** Karlovich (2025), ec. (1.4), p. 3, trabaja con una álgebra **real** en `B(ℝLᵖ(Γ,w))`, generada por multiplicadores `M_a` con `a∈SO^◇(Γ)`, el operador singular `S_Γ` y la conjugación `C` real-lineal. «Generada por» conserva el mecanismo de T1.3 (sumas, productos, clausura en norma), pero no autoriza aplicar sin más el cálculo funcional de `C*`-álgebras complejas.

## R4. Permanencia espectral en `C*`-subálgebras

- **RESULTADO:** Si `B⊂A` es una `C*`-subálgebra unital con la misma unidad, `σ_B(b)=σ_A(b)` para `b∈B` (Prop. 2.17).
- **DEPENDENCIAS:** Espectro real de autoadjuntos (Prop. 2.13), criterio por `b*b` y `bb*` (Prop. 2.16), continuidad de la inversión (T1.1(b)) y cierre de `B`.
- **RESULTADOS QUE DEPENDEN DE ÉL:** Identificación `Ω(C*(a,1))≅σ(a)` (Prop. 2.18); construcción del cálculo funcional (Teo. 2.22); prueba de mapeo espectral T2.4.
- **TAREAS RELACIONADAS:** T1.1(b), T1.9, T1.12; T2.4.
- **CONEXIÓN SECCIÓN2:** La prueba reduce a un autoadjunto y usa los inversos de `b+i/n` dentro de `B`, que convergen al inverso calculado en `A`.
- **CONEXIÓN INVESTIGACIÓN:** T1.12 muestra el límite de la analogía: el álgebra del disco, vista dentro de `C(T)`, es una subálgebra de Banach cerrada y unital que cambia el espectro, pero no es una `C*`-subálgebra. No se puede transportar un criterio espectral entre álgebras de operadores sin revisar la inclusión.

## R5. Representación de Gelfand–Naimark y cálculo funcional

- **RESULTADO:** Una `C*`-álgebra conmutativa unital es `*-isomorfa` isométricamente a `C(Ω(A))` (Teo. 2.20). Para `a` normal, `f↦f(a)` identifica `C(σ(a))` con `C*(a,1)` (Teo. 2.22).
- **DEPENDENCIAS:** Teo. 2.6 (`‖a‖=r(a)` para normales), caracteres que preservan `*`, Stone–Weierstrass, Prop. 2.18 y permanencia espectral. T1.3(d) proporciona conmutatividad de `C*(a,1)`.
- **RESULTADOS QUE DEPENDEN DE ÉL:** Mapeo espectral T2.4; clasificación de normales T2.6; raíz positiva y T2.7; continuidad T2.8.
- **TAREAS RELACIONADAS:** T1.3(d), T1.7, T1.10; T2.4–T2.8.
- **CONEXIÓN SECCIÓN2:** `a↔(z↦z)` y `a*↔(z↦conj(z))` convierten igualdades de funciones sobre el espectro en igualdades de elementos.
- **CONEXIÓN INVESTIGACIÓN:** En una `C*`-álgebra conmutativa de coeficientes, Gelfand convierte elementos en funciones sobre su espacio maximal. Para símbolos matriciales o cocientes no conmutativos se requieren resultados adicionales de la literatura; el cálculo funcional escalar no los sustituye.

## R6. `C₀(X)` y construcciones no unitales

- **RESULTADO:** T1.5 demuestra que `C₀(X)` es un ideal cerrado de `C_b(X)`; T2.3 construye productos acotados de `C*`-álgebras y el ideal de familias que tienden a cero.
- **DEPENDENCIAS:** Definición de desvanecimiento al infinito, norma uniforme y cerradura bajo límites; para T2.3, completitud coordenada e identidad `C*`.
- **RESULTADOS QUE DEPENDEN DE ÉL:** T1.4 permite formar cocientes como álgebras de Banach; concluir que el cociente es una `C*`-álgebra requiere el teorema correspondiente sobre cocientes `C*`.
- **TAREAS RELACIONADAS:** T1.4, T1.5; T2.3(a,b).
- **CONEXIÓN SECCIÓN2:** La Sección 2 demuestra Gelfand–Naimark para álgebras **unitales**. Si `X` no es compacto, `C₀(X)` es no unital y su clasificación pertenece a la versión no unital; si `X` es compacto, `C₀(X)=C(X)`.
- **CONEXIÓN INVESTIGACIÓN:** Son modelos de ideales y cocientes de funciones. Ningún criterio de Fredholm específico de Haseman se deduce aquí sin identificar el álgebra y el ideal usados en esa fuente.

## R7. Clasificación espectral, raíz positiva y polar

- **RESULTADO:** Para `x` normal, su espectro real, en `T` o en `{0,1}` caracteriza respectivamente autoadjunción, unitariedad o proyección (Prop. 2.28/T2.6). Si `a` es invertible, `u=a(a*a)^(-1/2)` es unitario (T2.7).
- **DEPENDENCIAS:** Cálculo funcional (Teo. 2.22), T2.2(a,c), normalidad en las recíprocas, raíz positiva (Prop. 2.30) e invertibilidad de `a*a` para la parte polar.
- **RESULTADOS QUE DEPENDEN DE ÉL:** T2.7 usa la raíz; T2.8 prueba estabilidad de `f(x_n)` por aproximación polinómica. La clasificación permite reconocer proyecciones ortogonales sólo cuando se verifica autoadjunción.
- **TAREAS RELACIONADAS:** T2.2, T2.4, T2.6–T2.8.
- **CONEXIÓN SECCIÓN2:** Los bloques de Jordan de T2.6(d) muestran que el espectro solo no determina estas identidades fuera de la clase normal.
- **CONEXIÓN INVESTIGACIÓN:** Los shifts unitarios de rotación en el modelo Hilbertiano de Bastos–Fernandes–Karlovich (2006) obedecen la restricción espectral a `T`. Para operadores de composición generales `Vα` no se debe afirmar unitariedad sin verificar preservación de norma y adjunto.

## R8. Cociente de Calkin y Fredholm

- **RESULTADO:** Para un espacio de Banach `X` de dimensión infinita, `K(X)` es un ideal bilateral cerrado de `B(X)` y `Q(X)=B(X)/K(X)` es un álgebra de Banach. Atkinson: `A` es Fredholm si y sólo si `A+K(X)` es invertible en `Q(X)`.
- **DEPENDENCIAS:** T1.4 prueba la estructura del cociente. El teorema de Atkinson es externo a T1.4; exige la definición de Fredholm (rango cerrado, núcleo y conúcleo finito dimensionales).
- **RESULTADOS QUE DEPENDEN DE ÉL:** Permite formular problemas de Fredholm como problemas de invertibilidad módulo compactos. Un criterio por símbolos necesita un homomorfismo o principio local adicional.
- **TAREAS RELACIONADAS:** T1.4; T2.3 ofrece otra construcción de ideal cerrado, sin implicar por sí sola Atkinson.
- **CONEXIÓN SECCIÓN2:** Si `X=H` es Hilbert, `B(H)` es una `C*`-álgebra. Que su cociente por `K(H)` también sea `C*` requiere el teorema de cocientes de `C*`-álgebras, adicional a T1.4.
- **CONEXIÓN INVESTIGACIÓN:** Karlovich (2025), p. 2, usa la caracterización de Fredholm por invertibilidad en Calkin. El paso posterior a símbolos/localización pertenece a resultados específicos de esa literatura.

## R9. Dos contextos para los operadores de Cauchy

- **RESULTADO:** En el modelo Hilbertiano de Bastos–Fernandes–Karlovich (2006), `Γ₀=ℝ` o `𝕋`, `S_{Γ₀}²=I` y `S_{Γ₀}*=S_{Γ₀}` en `L²(Γ₀)`. Por ello `P_{Γ₀}±=(I±S_{Γ₀})/2` son proyecciones ortogonales. En la estrella abierta de Karlovich (2017), Sokhotski–Plemelj da `P±=(I±S_Γ)/2` como componentes de trazas y la ecuación `T=V_αP+ + M_GP−`; no se afirma allí idempotencia general de esos `P±`.
- **DEPENDENCIAS:** En el modelo de 2006, `S_{Γ₀}²=I` da idempotencia y `S_{Γ₀}*=S_{Γ₀}` da autoadjunción. En el de 2017, la reducción a `T` usa las hipótesis analíticas de la fuente sobre estrella abierta, `Lᵖ(Γ)`, coeficientes y shift; la fórmula de Plemelj no exige `S_Γ²=I`.
- **RESULTADOS QUE DEPENDEN DE ÉL:** En 2006 se deducen `P_{Γ₀}±²=P_{Γ₀}±`, `P_{Γ₀}±*=P_{Γ₀}±` y `σ(P_{Γ₀}±)⊂{0,1}`; T2.2(a) y T2.6(c) explican los pasos abstractos. En 2017, `T` combina componentes de trazas a las que se aplican `V_α` y `M_G`; estudiar invertibilidad o Fredholm exige verificar acotación y pertenencia al álgebra considerada, sin usar idempotencia no establecida.
- **TAREAS RELACIONADAS:** T2.2(a) distingue idempotencia algebraica; T2.6(c) caracteriza proyecciones normales; T1.4 aporta el lenguaje del cociente para Fredholm. Ninguna de esas tareas demuestra la fórmula de frontera de 2017.
- **CONEXIÓN SECCIÓN2:** El resultado de proyecciones de la Sección 2 se aplica directamente a `P_{Γ₀}±` del modelo `L²(Γ₀)` de 2006. No se aplica automáticamente a los `P±` de la estrella abierta, pues allí no se ha verificado `S_Γ²=I` ni autoadjunción.
- **CONEXIÓN INVESTIGACIÓN:** Bastos–Fernandes–Karlovich (2006), §2, p. 22, respalda el modelo ortogonal para `Γ₀=ℝ` o `𝕋`. Karlovich (2017), pp. 463–464, ecs. (1.1)–(1.2), respalda Plemelj y `T` en la estrella abierta; su teorema 5.3, p. 476, impide trasladar `S_{Γ₀}²=I` como identidad general a ese contorno. La flecha entre ambos modelos es sólo una comparación de fórmulas.

## R10. Representación concreta y shift unilateral

- **RESULTADO:** `B(H)` es una `C*`-álgebra (T1.11(a)); `f↦M_f` representa `C_b(X)` isométricamente sobre `ℓ²(X)` (T2.1). El shift unilateral no es normal y tiene por espectro el disco cerrado `\overline{\mathbb D}` (T2.10).
- **DEPENDENCIAS:** Norma operatorial y adjunto para T1.11(a)/T2.1; T1.11(d) da falta de sobreyectividad del shift; en T2.10 los vectores propios de su adjunto llenan el disco abierto y la clausura del espectro añade la frontera.
- **RESULTADOS QUE DEPENDEN DE ÉL:** T2.1 es modelo concreto de `*-monomorfismo` isométrico; T2.10 sirve de contraejemplo a extrapolaciones de la clasificación de normales.
- **TAREAS RELACIONADAS:** T1.11(a–d), T2.1, T2.10.
- **CONEXIÓN SECCIÓN2:** El Teo. 2.27 garantiza isometría de un `*-monomorfismo` unital; T2.1 verifica directamente esa propiedad. El Teo. 2.28 no se aplica al shift unilateral por falta de normalidad.
- **CONEXIÓN INVESTIGACIÓN:** El shift unilateral desplaza coordenadas y el `V_α` de Karlovich (2017) compone funciones sobre una estrella abierta. Ambos son operadores de desplazamiento en sentido amplio; el cálculo `σ(S)=\overline{\mathbb D}` de T2.10 no determina el espectro de `V_α` ni propiedades de los `P±` que aparecen junto a él.

## R11. Convergencia de operadores

- **RESULTADO:** T2.8: si `x_n→x` en norma, son normales y sus espectros están en un mismo compacto `K`, entonces `f(x_n)→f(x)` en norma para `f∈C(K)`. T2.9: una red creciente, acotada y autoadjunta converge fuertemente a un autoadjunto.
- **DEPENDENCIAS:** T2.8 usa T1.7, Stone–Weierstrass y cálculo funcional. T2.9 usa orden positivo, polarización, Riesz y `0≤A²≤‖A‖A` para positivos.
- **RESULTADOS QUE DEPENDEN DE ÉL:** Continuidad de raíces positivas bajo T2.8; convergencia vector por vector bajo T2.9. Ninguno de esos resultados da automáticamente convergencia en norma para la red de T2.9.
- **TAREAS RELACIONADAS:** T1.1(a), T1.7; T2.8, T2.9.
- **CONEXIÓN SECCIÓN2:** La normalidad es condición de aplicación del cálculo funcional; el orden positivo se define por espectro no negativo o formas cuadráticas en `B(H)`.
- **CONEXIÓN INVESTIGACIÓN:** Son herramientas potenciales para familias de operadores, pero aquí no se ha identificado una familia concreta de Haseman que satisfaga sus hipótesis.

## Cobertura individual de tareas

| Tarea | Resultado e inciso crítico | Nodo anterior → nodo posterior |
|---|---|---|
| T1.1 | Continuidad conjunta e inversión | Neumann/submultiplicatividad → T1.3, T1.7, Prop. 2.17, T2.8. |
| T1.2 | Conmutación con inversos y adjuntos | Asociatividad/involución → T1.9. |
| T1.3 | Generación y propagación de conmutación | T1.1(a) → `C*(a,1)` conmutativa cuando `a` es normal. |
| T1.4 | Álgebra cociente | Ideal cerrado → Calkin; Atkinson es externo. |
| T1.5 | Ideal `C₀(X)` | Norma uniforme → modelo no unital cuando `X` no es compacto; la Sección 2 actual trata el caso unital. |
| T1.6 | Espectro del adjunto | Inversión y `*` → simetría; la realidad requiere más. |
| T1.7 | Normales cerrados | T1.1(a) e involución continua → T2.8. |
| T1.8 | Inclusión espectral | Homomorfismo unital/inversos → Teo. 2.8. |
| T1.9 | Reducción conmutativa | T1.2, T1.3 y Zorn → Prop. 2.13. |
| T1.10 | Espectro como imagen de función | Invertibilidad puntual y compacidad → T2.4. |
| T1.11 | `B(H)` y shift | Adjunto/rango/valores aproximados → T2.1 y T2.10. |
| T1.12 | Espectros del álgebra del disco | Principio del máximo e inversión ambiente → contraste con Prop. 2.17. |
| T2.1 | Representación de `C_b(X)` | `B(H)` y adjunto → modelo del Teo. 2.27. |
| T2.2 | Idempotentes, producto y unitarios | Radio/inversión → direcciones directas de T2.6(b,c); (b) tiene uso propio. |
| T2.3 | Producto acotado e ideal `c₀` | Identidad `C*` coordenada → cociente posible por T1.4. |
| T2.4 | Mapeo espectral | Cálculo funcional, permanencia, T1.10 → `σ(f(x))=f(σ(x))`. |
| T2.5 | Espacio maximal de `C(X)` | Caracteres/compacidad → unicidad en Cor. 2.21. |
| T2.6 | Clasificación de normales | T2.2 y cálculo funcional → Prop. 2.28 y límites de la normalidad. |
| T2.7 | Parte unitaria polar | Raíz positiva e invertibilidad → `a=u|a|`. |
| T2.8 | Continuidad de `f(x_n)` | T1.7, Stone–Weierstrass, cálculo funcional → convergencia en norma. |
| T2.9 | Red monótona autoadjunta | Orden, Riesz y desigualdad positiva → convergencia fuerte. |
| T2.10 | Shift unilateral | T1.11(d), adjunto y cierre espectral → disco cerrado. |
