<!-- ELUCENIA technical documentation · escore-de-mirels · es · no clinical/professional/rights approval -->

# Puntuación de Mirels

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escore-de-mirels)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Localización de la lesión

`local`

- `1` — Miembro superior
- `2` — Miembro inferior
- `3` — Peritrocantérica

### Dolor

`dor`

- `1` — Leve
- `2` — Moderada
- `3` — Funcional (al soportar peso)

### Aspecto radiográfico

`lesao`

- `1` — Blástica
- `2` — Mixta
- `3` — Lítica

### Tamaño (fracción del diámetro del hueso)

`tamanho`

- `1` — Menos de 1/3
- `2` — 1/3 a 2/3
- `3` — Más de 2/3

## Edición del método

Mirels 1989: sitio/dolor/lesión/tamaño 1–3, total 4–12

## Fórmula documentada

Cuatro ítems, 1 a 3: sitio (superior 1, inferior 2, peritrocantérico 3), dolor (leve 1, moderado 2, funcional 3), lesión (blástica 1, mixta 2, lítica 3), tamaño por diámetro óseo (\<1/3: 1; 1/3 a 2/3: 2; \>2/3: 3). Total 4 a 12.

## Límites y población

El Mirels de 1989 se desarrolló en lesiones metastásicas de huesos largos, irradiadas sin fijación profiláctica, con evaluación de fracturas a seis meses. El resumen original y las versiones interpretativas posteriores no utilizan necesariamente el mismo punto de corte de decisión; la edición y la conducta correspondiente deben ser explícitas. El total no establece por sí solo la elección entre radioterapia y cirugía.

## Referencias

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
