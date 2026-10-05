<!-- ELUCENIA technical documentation · escore-de-mirels · en · no clinical/professional/rights approval -->

# Mirels score

[conditions, sources and permissions](https://elucenia.org/en/tools/escore-de-mirels)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Lesion site

`local`

- `1` — Upper limb
- `2` — Lower limb
- `3` — Peritrochanteric

### Pain

`dor`

- `1` — Mild
- `2` — Moderate
- `3` — Functional (with weight bearing)

### Radiographic appearance

`lesao`

- `1` — Blastic
- `2` — Mixed
- `3` — Lytic

### Size (fraction of bone diameter)

`tamanho`

- `1` — Less than 1/3
- `2` — 1/3 to 2/3
- `3` — More than 2/3

## Method edition

Mirels 1989: site/pain/lesion/size 1–3, total 4–12

## Documented formula

Four items, 1 to 3 each: site (upper limb 1, lower 2, peritrochanteric 3), pain (mild 1, moderate 2, functional 3), lesion (blastic 1, mixed 2, lytic 3), size relative to bone diameter (\<1/3: 1; 1/3 to 2/3: 2; \>2/3: 3). Total 4 to 12.

## Limits and population

The 1989 Mirels was developed in metastatic long-bone lesions irradiated without prophylactic fixation, with fractures assessed over six months. The original abstract and later interpretive versions do not necessarily use the same decision cutoff; the edition and corresponding management must be explicit. The total alone does not establish the choice between radiotherapy and surgery.

## References

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
