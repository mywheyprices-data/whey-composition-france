---
license: odbl
language:
- fr
- en
pretty_name: Whey protein composition (France)
tags:
- nutrition
- food
- whey
- protein
- sports-nutrition
- france
size_categories:
- n<1K
---

# Composition des protéines whey vendues en France / Whey protein composition (France)

Relevé, étiquette par étiquette, de la composition nutritionnelle de **61 gammes de protéines en poudre** (dont 44 whey) de
30 marques vendues en France : protéines pour 100 g et par dose, glucides, sucres, lipides, lactose, édulcorants, forme
(isolat, concentrée, mélange), whey native, origine France revendiquée.

Nutrition facts of **61 protein powder product lines** (44 whey) from 30 brands sold in France, taken from the product
labels: protein per 100 g and per serving, carbohydrates, sugars, fat, lactose, sweeteners, form (isolate, concentrate,
blend), native whey, claimed French origin.

- Source et mise à jour / Source and updates: [mywheyprices.com/donnees/composition-whey/](https://mywheyprices.com/donnees/composition-whey/)
- Méthode / Methodology: [mywheyprices.com/notre-methode/](https://mywheyprices.com/notre-methode/)
- Également sur / Also on: [data.gouv.fr](https://www.data.gouv.fr/datasets/composition-nutritionnelle-des-proteines-whey-vendues-en-france), [Zenodo](https://doi.org/10.5281/zenodo.23815078), [GitHub](https://github.com/mywheyprices-data/whey-composition-france), [Hugging Face](https://huggingface.co/datasets/mywheyprices/whey-composition-france), [Kaggle](https://www.kaggle.com/datasets/mywheyprices/whey-protein-composition-in-france)
- Citation : MyWheyPrices (2026). Composition des protéines whey vendues en France. Zenodo. https://doi.org/10.5281/zenodo.23815078

## Fichiers / Files

| Fichier | Format |
|---|---|
| `whey-composition-france.csv` | virgule, point décimal, en-têtes anglais / comma-separated, dot decimals, English headers |
| `composition-whey-fr.csv` | point-virgule, virgule décimale, en-têtes français (identique au site) / semicolon, French headers |

## Quelques chiffres / Key figures

- Teneur médiane en protéines / median protein content: **83 g / 100 g** pour un isolat (isolate, 20 gammes, 79 à 90 g),
  **72 g** pour une concentrée (concentrate, 10 gammes), **75,5 g** pour un mélange concentrée + isolat (14 gammes).
- **47 gammes sur 61** contiennent du sucralose dans leur saveur de référence ; **9** n'ont aucun édulcorant.
  47 of 61 product lines contain sucralose in their reference flavour; 9 contain no sweetener.

## Colonnes / Columns (`whey-composition-france.csv`)

| Column | Description |
|---|---|
| `brand`, `product_line` | Marque et gamme / brand and product line |
| `category` | `whey` ou / or `other_protein` (mélanges multi-protéines, etc.) |
| `form` | `isolate`, `concentrate`, `concentrate_isolate_blend`, `multi_protein`, `hydrolysate` |
| `native` | Whey native (filtrée directement du lait) / native whey (filtered from milk) |
| `protein_per_100g` | Protéines pour 100 g de poudre, telles quelles / protein per 100 g of powder, as sold |
| `protein_per_100g_estimated` | `true` si calculée à partir des valeurs publiées (ex. par dose, ou sur matière sèche) / computed from published values |
| `protein_per_serving_g`, `serving_size_g` | Protéines par dose et taille de la dose / protein per serving and serving size |
| `carbs_per_100g`, `sugars_per_100g`, `fat_per_100g` | Glucides, sucres, lipides pour 100 g / per 100 g |
| `lactose` | `very_low`, `present`, `lactose_free_claimed` |
| `sweeteners` | Édulcorants de la saveur de référence / sweeteners in the reference flavour (`none` = aucun) |
| `made_in_france_claimed` | Origine France revendiquée par la marque / French origin claimed by the brand |
| `page_url` | Fiche détaillée sur MyWheyPrices / detailed page |
| `source_url` | Page d'où proviennent les valeurs / page the values were taken from |

Une case vide signifie « inconnu » : aucune valeur n'est devinée. / An empty cell means unknown: no value is guessed.

## Limites / Limitations

Valeurs indicatives pour une saveur de référence ; la composition varie selon la saveur et peut évoluer. Vérifier l'étiquette
avant achat. / Values are for one reference flavour and may change; check the label before buying.

## Licence / License

[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Réutilisation libre en citant la source :
« MyWheyPrices, https://mywheyprices.com/donnees/composition-whey/ ». / Free to reuse with attribution.
