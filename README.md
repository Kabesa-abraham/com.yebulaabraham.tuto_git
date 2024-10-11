# Documentation de mon formation git github

## initialiser un dépôt

```bash
git init
git remote add origin SSH_DU_REPO
git add 'nom du fichier' pour que git suis le fichier
```

## rediger un commit (bonne pratique)

```
Titre du commit

Description de notre commit avec des informations sur l'évolution du projec
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "titre du commentaire"
git push origin main
```

##creation d'une branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes pratique, on va integrer la notion de revue de code. Pour cela, on va créer une branche, faire des modification,
les envoyer sur le dépôt distant, puis créer un pull request pour démander une revue de code.