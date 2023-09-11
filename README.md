# Projet Pédagogique: Analyse et Nettoyage de Base de Données

Ce projet a été réalisé dans un but pédagogique. L'objectif principal est de nettoyer une base de données et d'effectuer des analyses préliminaires.

## Quick Start sur VSCode

### Prérequis

1. **Installer VSCode**  
   Téléchargez et installez depuis [VSCode Official Website](https://code.visualstudio.com/download).

2. **Installer Python**  
   Téléchargez et installez depuis [Python Official Website](https://www.python.org/downloads/).

### Installation des outils et extensions

1. **Installer Jupyter Notebook**
    ```bash
    pip install notebook
    ```

2. **Installer les Extensions Requises depuis VSCode**  
   - Extension Python  
   - Extension Jupyter

### Configuration de l'environnement virtuel

1. **Créer un environnement virtuel pour le projet**
    ```bash
    python -m venv venv
    ```

2. **Activer l'environnement virtuel**

    - Sur Windows avec PowerShell:
        ```powershell
        .\venv\Scripts\Activate.ps1
        ```
    - Sur macOS et Linux:
        ```bash
        source venv/bin/activate
        ```

3. **Installer les dépendances**
    ```bash
    pip install -r requirements.txt
    ```

4. **Ajouter l'environnement à Jupyter**
    ```bash
    python -m ipykernel install --user --name=venv
    ```

### Utilisation du Notebook

Ouvrez le fichier `Nicolas_Deleu_Projet05 (3).ipynb` dans VSCode. Ensuite, choisissez le noyau correspondant à votre environnement virtuel Python. Vous êtes maintenant prêt à explorer le notebook !
