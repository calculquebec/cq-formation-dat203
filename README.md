# DAT203

## Titres d'atelier

* (FR) **Visualisation de données en Python**
* (EN) **Data Visualization in Python**

## Dépendances

Python >= 3.11, `pip install ...`:

* `numpy pandas matplotlib`
* `altair vega-datasets vl-convert-python`

## À propos des notebooks

Le développement du matériel se fait dans le répertoire `src`.
Voir [les instructions ici](https://github.com/calculquebec/make-translated-notebooks/blob/main/README.md#fichiers-sources).

Les fichiers compilés et à utiliser pendant un atelier sont dans :

* `en` et `fr` pour les versions à remplir;
* `solution-en` et `solution-fr` pour les solutionnaires.

### Compilation

Pour cloner l'outil de compilation des traductions :

`git submodule update --init`

Ensuite :

* Compilation des dernières modifications : `python translation/make.py`
* Recompilation complète (rebuild) : `python translation/make.py -r`
