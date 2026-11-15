# Groupe 10 – Projet Data Mining 2026-2027

**Membres :**
Abbas Yasmina, 
BAH Mamadou Sotho, 
BATTAL Mohammed Othmane, 
VALLOT Tanguy, 
VILLAUME Evan, 
YAGBASAN Aleyna 


## Organisation du dépôt

Chaque dossier de données est analysé dans son propre notebook.
Les notebooks se lancent depuis la racine du dépôt (ils lisent les fichiers de `data/`).

| Dossier | Notebook(s) | Remarque |
|---|---|---|
| `public_records` | `public_records.ipynb` | |
| `ecology` | `ecology.ipynb` | |
| `logistics` | `01_nettoyage_logistics.ipynb`, `02_analyse_logistics.ipynb` | lancer le nettoyage d'abord : il crée `data/logistics/clean/` |
| `health` | `01_nettoyage_health.ipynb`, `02_analyse_health.ipynb`, `03_rapport_health.ipynb` | `03` est le rapport court ; fonctions communes dans `health_utils.py` |
| synthèse | `00_synthese.ipynb` | relie les quatre dossiers et reconstitue l'histoire complète |

## Données

- `data/` : données fournies, non modifiées ;
- `data/logistics/clean/` et `data/health_clean/` : données nettoyées produites par les notebooks.

## Usage de l'IA générative

Chaque notebook précise comment l'IA générative a été utilisée pour sa partie.