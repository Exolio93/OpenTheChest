
## Guide d'Installation Rapide

### 1. Création de l'environnement Conda
```bash
# Créer l'environnement avec Python 3.10
conda create -n openthechest python=3.10 -y

# Activer l'environnement
conda activate openthechest
```
### 2. Installation des dépendances
```bash
# Installer PyBullet via Conda (Recommandé pour Mac/Windows)
conda install -c conda-forge pybullet -y

# Installer toutes les autres bibliothèques via le fichier requirements
pip install -r requirements.txt

# Enregistrer l'environnement pour Jupyter
python -m ipykernel install --user --name openthechest --display-name "Python (OpenTheChest)"
```

## Structure de répertoire

Le projet est organise autour des elements suivants :

- `Open_The_Chests_Project.ipynb` : 
Notebook principal pour travailler et faire le code : c'est ici où il y a toutes les consignes etc. Il y a 3 parties (3 taches).
- `report.ipynb` : 
Rapport de notre travail.
- `colored_chest_kuka_env.py` : 
- `register_envs.py` : 
Fichiers d'utils
- `requirements.txt` :
Liste des dependances Python.
- `logs/` :
logs d'entrainements pour plot la learning curve.
- `assets_task_1/` : 
Les fichiers (images / vidéo) correspondants à la partie 1.
- `assets_task_3/` : 
Les fichiers (images / vidéo) correspondants à la partie 3.
- `*.zip` : 
Modèles entrainé qui peuvent être chargé depuis le code si nécessaire.
