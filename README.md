# API-VIES

## Objet

Requêter l'API VIES avec un échantillon propre

## Prérequis

- Python 3.10 ou plus récent
- pip

## Installation

1. python -m venv .venv
2. source .venv/Scripts/activate
3. pip install -r requirements.txt

## Lancement

Execution des notebooks `2.Nettoyage.ipynb` et `3.Interroger.ipynb`

## Données

numeros_tva.csv, 
site VIES de la commission européenne

## Contenus du repo
- Ce README.md,
- Les installations requises `requirements.txt`
- Un dossier "notebook" qui comprend : 
  - 3 notebooks : `1.Exploration.ipynb`, `2.Nettoyage.ipynb`, `3.Interroger.ipynb`
  - un rapport à la direction financière `4.Rapport.md`
  - Un rapport de conciliation `rapport_de_conciliation.csv`
  - Un journal `requetes_api.log`
  - Un document de résultats `resultats_requetes.csv`
  - Un exemplaire de dataframe nettoyé `tva_propre.cvs`

