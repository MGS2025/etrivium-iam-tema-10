# Tema 10 — Changelog

> **Título oficial**: LO 3/2007 (igualdad efectiva de mujeres y hombres) · Ley 4/2023 (personas trans y LGTBI) · III Plan de Igualdad del Ayuntamiento de Madrid y sus OO.AA. (2024-2027).

---

## v1.0 — 2026-06-25 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM).

> **QA post-generación (mismo día, pre-validación)**: barrido getBBox sobre los 12 SVG renderizados con Chrome headless. Se detectó y corrigió texto que desbordaba/rozaba el borde de su caja en **D1** (Formal/Material art. 14/9.2), **D2** (pregunta clásica ámbito universal), **D5** (presencia equilibrada 40-60 %) y **D8** (misma tutela LOIEMH): se ensancharon las cajas y se redujo la fuente de esas líneas a 9,5 px. Resultado final: **todos los textos con margen ≥ 6 px respecto a su caja**. No afecta al contenido, solo a la maquetación de los diagramas. Criterio de QA reforzado: exigir margen mínimo de 6 px, no solo "no desborda".

### Alcance y decisiones

- **Fuentes nucleares**: **LOIEMH (LO 3/2007)**, **Ley 4/2023** y **III Plan de Igualdad 2024-2027** del Ayuntamiento de Madrid.
- **Material del cliente**: `TEMA_10.docx` (índice oficial del tema, incluyendo datos del diagnóstico del III Plan).
- **Verificación previa**: los datos del III Plan se han **contrastado con el documento oficial** publicado en el Portal de Transparencia del Ayuntamiento de Madrid (BOAM nº 9547/70, de 11-ene-2024) antes de redactar.

### Datos del III Plan verificados contra fuente oficial

1. **Aprobación y vigencia**: JGCM 28-dic-2023; BOAM 9547/70 (11-ene-2024); vigencia 1-ene-2024 a 31-dic-2027.
2. **Base legal**: art. 64 LOIEMH + DA 7.ª TREBEP (modificada por la Ley 31/2022 de PGE); sustituyó al II Plan (2022-2024) antes de su vencimiento.
3. **Estructura**: 3 líneas de intervención (Institución, Comunicación, Personas) y 13 objetivos específicos (3 + 2 + 8).
4. **Comisión de Igualdad**: paritaria, presidida por la DG de Función Pública; sindicatos CSIF, UGT, CCOO, CITAM, CSIT, CPPM y UPM (reglamento de 30-mar-2021).
5. **Seguimiento**: semestral (Comisión); informe anual (DG Función Pública); diagnóstico bienal; evaluación final.
6. **Diagnóstico**: 27.893 efectivos (46,1 % mujeres / 53,9 % hombres); IAM único OO.AA. con mayoría masculina (533 efectivos: 43,2 % / 56,8 %).

### Ajuste sobre el índice del cliente (referencia jurídica)

- La **presencia/composición equilibrada (40-60 %)** se ha referenciado en la **Disposición adicional primera de la LOIEMH**, aplicada por el **art. 53** (equivalente al **art. 60.1 TREBEP**). El índice del cliente la situaba en el "art. 54"; se ha **ajustado** la cita por rigor jurídico. Anotado para confirmación con Jesús/María.

### Entregables generados

| Fichero | Contenido |
|---|---|
| `tema-10-indice.md` | Índice de 11 secciones + tablas de datos clave |
| `tema-10-fuentes.md` | Registro Tier 1/2/3 + auditoría de datos del III Plan |
| `tema-10-contenido.md` | Contenido teórico (11 secciones, callouts) |
| `tema-10-diagramas.md` | 12 diagramas SVG accesibles |
| `tema-10-test.md` | 150 preguntas tipo examen |
| `tema-10-caso-practico.md` | 6 casos prácticos (igualdad / IAM), 10 pts c/u |
| `tema-10-validacion.md` | Checklist de validación |
| `index.html` | Web autosuficiente, pestañas, motor test 1/3 |

### QA aplicado

- Datos del III Plan contrastados con el documento oficial (transparencia.madrid.es) antes de la redacción.
- Referencias jurídicas de la LOIEMH y la Ley 4/2023 verificadas (carácter mixto, arts. 6-13, DA 1.ª/art. 53, arts. 43 y ss. Ley 4/2023).
- Diagramas con CSS **scoped** por SVG (evita el bug sistémico de colisión de estilos entre los 12 SVG) y verificados por render del `index.html` real.
- Balanceo automático A/B/C de las respuestas del test.
- Refs cruzadas verificadas vs BOAM 10.032 (T1, T5, T9).

### Pendiente

- Validación de contenido por María / Ana (IAM).
- Confirmar el ajuste de la cita de presencia equilibrada (art. 53 + DA 1.ª en lugar de "art. 54").
- Reverificar los datos del diagnóstico del III Plan antes de cada convocatoria (actualización bienal).
