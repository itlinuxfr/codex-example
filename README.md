# Exemple de programme de musculation

Ce dépôt contient une simple page HTML permettant de créer et sauvegarder un programme de musculation pour chaque jour de la semaine.

## Utilisation

Ouvrez `index.html` dans votre navigateur. Les exercices peuvent se déplacer par glisser–déposer, et le programme se sauvegarde automatiquement dans le `localStorage` du navigateur. Il est possible d'exporter le programme du jour courant en PDF.

Pour vérifier la validité du code HTML, vous pouvez utiliser l'outil `tidy` :

```bash
tidy -e index.html
```

## Fonctionnalités
- Sélection du jour via un tableau interactif
- Ajout, modification ou suppression d'exercices avec numérotation et suivi de réussite
- Stockage automatique dans le navigateur pour chaque jour
- Calcul des besoins caloriques via le BMR en fonction de l'âge, de la taille, du sexe, du poids et de l'activité
