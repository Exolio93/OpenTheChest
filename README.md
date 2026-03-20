
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
Notebook principal pour travailler et faire le code : c'est ici où il y a toutes les consignes etc. Il y a 3 parties (3 taches), j'ai fait la première. Les consignes sont assez abstraites, c'est un projet assez ouvert visiblement.  
- `report.ipynb` : 
C'est le rapport à rendre.
- `colored_chest_kuka_env.py` : 
Fichier qui était fourni avec le TP, normalement on est pas sensé trop le toucher car tout ce passe sur le notebook (sauf exceptions)
- `register_envs.py` : 
Fichier qui était fourni avec le TP, normalement on est pas sensé trop le toucher car tout ce passe sur le notebook (sauf exceptions)
- `requirements.txt` :
Liste des dependances Python.
- `logs/` :
logs d'entrainements pour plot la learning curve (ils devraient plus servir mais ne supprimer pas au cas ou on sait jamais)
- `assets_task_1/` : 
Les fichiers (images / vidéo) que j'avais besoin d'enregisrer pour le rapport pour la partie 1. Vous pourrez créer assets_task_2 et _3 si il faut ajouter des images
- `*.zip` : 
Modèles entrainé qui peuvent être chargé depuis le code si nécessaire.
