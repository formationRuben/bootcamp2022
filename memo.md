# Logiciels Pratiques

## Git

### Configuration

    git config user.name "monNom"
    git config user.email "monadresse@email.com"

### Trois états de fichiers
- Modifié (modified)
- Indexé (staged)
- Validé (committed)

### Gestion des fichiers et dossiers (bash)

- Se placer dans un dossier
    cd monDossier

- Voir le contenu d'un dossier
    ls

- Créer un dossier
    mkdir nomDuDossier

- Créer un fichier
    touch fichier.extension

- Effacer un dossier
    rmdir nomDuDossier

- Effacer un fichier
    rm nomDuFichier

Création - Suppression de plusieurs fichiers / dossiers
    commande nomDuFichier1 nomDuFichier2

e.g 
    mkdir css js

### Commandes de Git

- Initialiser un repo Git
    git init

- Statut du repo
    git status

- Indexer les fichiers
    git add .

- Valider les modifications
    git commit
(en annulant le dernier commit --amend)

- Renommer les fichiers
    git mv nomDuFichier nouveauNomDuFichier
(Sans arguments, ouverture d'un fichier à modifier)

- Créer une nouvelle branche
    git branch nomDeLaBranche

- Se placer dans une branche
    git checkout nomDeLaBranche

- Fusionner la branche avec le main
    git merge nomDeLaBrancheAFusionner

- Supprimer une branche
    git branch -d nomDeLaBranche

