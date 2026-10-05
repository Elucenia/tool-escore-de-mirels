<!-- ELUCENIA technical documentation · escore-de-mirels · pt-BR · no clinical/professional/rights approval -->

# Escore de Mirels

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escore-de-mirels)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Local da lesão

`local`

- `1` — Membro superior
- `2` — Membro inferior
- `3` — Peritrocantérica

### Dor

`dor`

- `1` — Leve
- `2` — Moderada
- `3` — Funcional (ao carregar peso)

### Aspecto radiográfico

`lesao`

- `1` — Blástica
- `2` — Mista
- `3` — Lítica

### Tamanho (fração do diâmetro do osso)

`tamanho`

- `1` — Menos de 1/3
- `2` — 1/3 a 2/3
- `3` — Mais de 2/3

## Edição do método

Mirels 1989:local/dor/lesão/tamanho 1–3, total 4–12

## Fórmula documentada

Quatro itens de 1 a 3 pontos: local (membro superior 1, inferior 2, peritrocantérico 3), dor (leve 1, moderada 2, funcional 3), lesão (blástica 1, mista 2, lítica 3) e tamanho em relação ao diâmetro do osso (\< 1/3: 1; 1/3 a 2/3: 2; \> 2/3: 3). Total de 4 a 12.

## Limites e população

O Mirels de 1989 foi desenvolvido em lesões metastáticas de ossos longos, irradiadas sem fixação profilática, com fraturas avaliadas em seis meses. O resumo original e versões interpretativas posteriores não usam necessariamente o mesmo corte de decisão; a edição e a conduta correspondente devem estar explícitas. O total não estabelece sozinho escolha entre radioterapia e cirurgia.

## Referências

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
