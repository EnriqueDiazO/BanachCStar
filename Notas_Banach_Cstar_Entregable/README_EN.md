# Study notes on spectral theory, Banach algebras, and C*-algebras

Author: Enrique Díaz Ocampo

This is the English edition of the study notes. The companion Spanish edition is
[main.tex](main.tex) and [main.pdf](main.pdf). Both editions use the same mathematical
structure, diagrams, citations, and document style.

The notes draw on the supplied course PDFs *Parte1.pdf*, *cap2.pdf*, *T1.pdf*, and
*Tarea2.pdf*. The research examples were checked against the primary papers listed
in the project's Haseman literature index. The titles of the Spanish source notes
remain in their original language in the bibliography.

## Files

| File | Contents |
|---|---|
| main_en.tex, main_en.pdf | Complete English document. |
| sections_en/00_mapa_global.tex | Logical map of Part 1 and Section 2. |
| sections_en/01_banach.tex | Invertibility, spectrum, resolvent, ideals, Gelfand theory, and spectral radius. |
| sections_en/02_cstar.tex | The C* identity, normal elements, spectral permanence, and functional calculus. |
| sections_en/03_tarea1.tex, sections_en/04_tarea2.tex | Fully developed solutions, dependencies, and curricular continuity. |
| sections_en/05_investigacion.tex | Carefully qualified bridges to Calkin algebras, Plemelj formulas, Haseman problems, and symbols. |
| sections_en/06_mapa_tareas.tex | Connections among assignments, course results, and research. |
| sections_en/07_indice_literatura.tex | Index of connections to specific papers. |

The files notes.cls, notes.sty, miestilo.sty, coloredtheorem.sty, and
mathmongo-macros.sty are shared document infrastructure.
The audit and traceability files remain in Spanish.

## Build

From this directory:

    pdflatex -interaction=nonstopmode -halt-on-error main_en.tex
    pdflatex -interaction=nonstopmode -halt-on-error main_en.tex

The second pass resolves the table of contents and cross-references.

## Reading guide

Each course result is presented as a statement, proof, proof diagram, and
example. Research connections follow the elementary development. In particular,
orthogonal projections in the Hilbert-space model on the line or circle are
distinguished from the operators $P_\pm$ in the Haseman problem on an open star.
Passing from an invertible class in the Calkin algebra to a symbol criterion
requires the assumptions of the relevant paper.
