
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

