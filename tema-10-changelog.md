# Tema 10 — Changelog

> **Título oficial**: LO 3/2007 (igualdad efectiva de mujeres y hombres) · Ley 4/2023 (personas trans y LGTBI) · III Plan de Igualdad del Ayuntamiento de Madrid y sus OO.AA. (2024-2027).

---

## v1.2 — 2026-10-01 — Revisión jurídica

**Motivo**: revisión jurídica de los temas 1-10 por la IAM.

### Cambios de la revisión (pestaña Fuentes)

1. Eliminada la tabla «Tier 2 — Material aportado por el cliente» (fila `[MAT-INDICE]`). La fila `[BOAM-10032]` (temario oficial) pasa a la tabla de fuentes primarias.
2. Eliminada la fila «El material aportado por el cliente (Tier 2)» de la trazabilidad fuente → contenido → pregunta.

### Correcciones comunes

- Títulos de las cajas: «Dato clave», «Cita normativa» (también para la Constitución), «Ejemplo de aplicación en el Ayto» y «Relación con otros temas». La leyenda ya no promete que un dato aparecerá en el test oficial.
- Fuera las promesas sobre el examen («pregunta clásica», «con valor de examen», «pieza clave examen») y las notas sobre el índice del cliente.
- Citas de artículos: «artículo» completo cuando forma parte de la oración; «art.» abreviado en los incisos entre paréntesis.
- Fuera las valoraciones fuera de las cajas («La distinción vertebra todo el tema», «Es una concreción del art. 6.1», «Es la garantía de indemnidad», «de especial relevancia para el empleo público», «mayor precariedad femenina», «por ser la que incide directamente en las condiciones laborales»…).

### Correcciones de contenido contra el BOE consolidado

- **Naturaleza de la LOIEMH**: según la DF 2.ª, solo las DA 1.ª, 2.ª y 3.ª tienen carácter orgánico; el texto decía que era orgánica «en lo relativo a derechos fundamentales» y ordinaria en el resto.
- **Art. 13 LOIEMH**: corresponde a la persona demandada probar la ausencia de discriminación en las medidas adoptadas y su proporcionalidad. Los «indicios fundados» no figuran en este artículo (sí en el art. 66.1 de la Ley 4/2023).
- **Art. 64 LOIEMH**: es el Plan de Igualdad de la AGE, que aprueba el Gobierno al inicio de cada legislatura y evalúa anualmente el Consejo de Ministros. «A desarrollar en el convenio colectivo o acuerdo» es de la DA 7.ª.2 TREBEP. La base del III Plan es la DA 7.ª TREBEP, no el art. 64.
- **Composición equilibrada**: DA 1.ª (definición), art. 51.d (todas las AAPP) y art. 53 (AGE). El art. 60.1 TREBEP dice «se tenderá a la paridad»; se quita «sustancialmente equivalente».
- **Arts. 6.2, 9, 10, 11, 12, 15, 19, 20, 45, 46 y 62 LOIEMH**: redacción ajustada al texto literal (justificación «necesarios y adecuados»; queja, reclamación, denuncia, demanda o recurso; sanciones del art. 10; art. 12.2-3; Consejo de Ministros en el art. 19; registro del art. 46.4-5; principios del protocolo del art. 62).
- **Ley 4/2023**: objeto (art. 1, que no menciona los arts. 9.2 y 14 CE), ámbito (art. 2, sin la mención a las CCAA, que no está en él), definiciones literales del art. 3 («identidad sexual», no «identidad de género»; «persona trans» sin la lista de colectivos), el art. 4 es el deber de protección (no una lista de principios), medidas en empresas en el art. 15 (no en una «DA 11.ª», que no existe), tutela de los arts. 64-66, rectificación registral de los arts. 43-44 (sin «autodeterminación» ni «simple declaración de voluntad», que no figuran en la ley). Fuera las «unidades de igualdad LGTBI en la AGE», que no están en la ley.
- **III Plan** (contrastado con el documento oficial): composición de la Comisión según el art. 5 de su Reglamento; ámbito personal literal; Auxiliar Administrativo 87 % de mujeres; Policía Municipal 86 % de hombres; flexibilidad horaria = 62 % de las medidas de conciliación.
- **Diagramas** D2, D3, D4, D5, D6, D7, D8, D9, D10 y D12 alineados con lo anterior (0 desbordes y 0 colisiones con `qa_svg.py`).
- **Casos prácticos** 1-6: soluciones ajustadas a los mismos preceptos; en el caso 5 la cuestión sobre la «autodeterminación» pasa a ser sobre el procedimiento del art. 44.

### Test (150 preguntas)

- Cada pregunta sale del texto literal del precepto citado, o es una variación leve de él. 76 reescritas (supuestos de aplicación, preguntas de interpretación o doctrina y preguntas que dependían de errores ya corregidos) y 74 mantenidas (con, como mucho, retoques literales y su orden de opciones).
- Respuestas correctas repartidas 50/50/50 entre a, b y c en el `.md`.

---

## v1.1 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~3.800 palabras · 12 diagramas · 150 preguntas de test
  - **Tiempo estimado de estudio**: 9-11 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

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
