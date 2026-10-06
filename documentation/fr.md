<!-- ELUCENIA technical documentation · escore-de-mirels · fr · no clinical/professional/rights approval -->

# Score de Mirels

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escore-de-mirels)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Site de la lésion

`local`

- `1` — Membre supérieur
- `2` — Membre inférieur
- `3` — Péritrochantérienne

### Douleur

`dor`

- `1` — Léger
- `2` — Modérée
- `3` — Fonctionnelle (à la mise en charge)

### Aspect radiographique

`lesao`

- `1` — Blastique
- `2` — Mixte
- `3` — Lytique

### Taille (fraction du diamètre osseux)

`tamanho`

- `1` — Moins de 1/3
- `2` — 1/3 à 2/3
- `3` — Plus de 2/3

## Édition de la méthode

Mirels 1989 : site/douleur/lésion/taille 1–3, total 4–12

## Formule documentée

Quatre items, 1 à 3 : site (membre supérieur 1, inférieur 2, péritrochantérien 3), douleur (légère 1, modérée 2, fonctionnelle 3), lésion (condensante 1, mixte 2, lytique 3), taille selon diamètre osseux (\<1/3 : 1 ; 1/3 à 2/3 : 2 ; \>2/3 : 3). Total 4 à 12.

## Limites et population

Le Mirels de 1989 a été développé dans des lésions métastatiques des os longs irradiées sans fixation prophylactique, avec évaluation des fractures à six mois. Le résumé original et les versions interprétatives ultérieures n’utilisent pas nécessairement le même seuil décisionnel ; l’édition et la conduite correspondante doivent être explicites. Le total ne détermine pas seul le choix entre radiothérapie et chirurgie.

## Références

- [Mirels H. Metastatic disease in long bones: a proposed scoring system for diagnosing impending pathologic fractures. Clin Orthop Relat Res, 1989.](https://doi.org/10.1097/00003086-198912000-00027)

- [Jawad MU, Scully SP. In brief: classifications in brief: Mirels classification: metastatic disease in long bones and impending pathologic fracture. Clin Orthop Relat Res, 2010.](https://doi.org/10.1007/s11999-010-1326-4)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Jusqu’à 7 points : faible risque de fracture (environ 4 %)

Radiothérapie et surveillance.


### 2

8 points : risque intermédiaire (environ 15 %)

Jugement clinique : envisager une fixation prophylactique.


### 3

9 points ou plus : risque élevé de fracture (33 % ou plus)

Fixation prophylactique avant la radiothérapie.


### 4

9 points ou plus : risque élevé de fracture (33 % ou plus)

Fixation prophylactique avant la radiothérapie.

