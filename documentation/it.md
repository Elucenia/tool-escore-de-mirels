<!-- ELUCENIA technical documentation · escore-de-mirels · it · no clinical/professional/rights approval -->

# Punteggio di Mirels

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escore-de-mirels)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Sede della lesione

`local`

- `1` — Arto superiore
- `2` — Arto inferiore
- `3` — Peritrocanterica

### Dolore

`dor`

- `1` — Lieve
- `2` — Moderata
- `3` — Funzionale (al carico)

### Aspetto radiografico

`lesao`

- `1` — Blastica
- `2` — Mista
- `3` — Litica

### Dimensione (frazione del diametro osseo)

`tamanho`

- `1` — Meno di 1/3
- `2` — 1/3 a 2/3
- `3` — Più di 2/3

## Edizione del metodo

Mirels 1989: sede/dolore/lesione/dimensione 1–3, totale 4–12

## Formula documentata

Quattro item, 1 a 3: sede (arto superiore 1, inferiore 2, peritrocanterica 3), dolore (lieve 1, moderato 2, funzionale 3), lesione (blastica 1, mista 2, litica 3), dimensione sul diametro osseo (\<1/3: 1; 1/3 a 2/3: 2; \>2/3: 3). Totale 4 a 12.

## Limiti e popolazione

Il Mirels del 1989 è stato sviluppato in lesioni metastatiche delle ossa lunghe irradiate senza fissazione profilattica, con valutazione delle fratture a sei mesi. L’abstract originale e le versioni interpretative successive non usano necessariamente la stessa soglia decisionale; l’edizione e la gestione corrispondente devono essere esplicite. Il totale da solo non stabilisce la scelta tra radioterapia e chirurgia.

## Riferimenti

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
