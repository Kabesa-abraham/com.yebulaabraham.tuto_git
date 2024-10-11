# Documentation de mon formation git github

## initialiser un dépôt

```bash
git init
git remote add origin SSH_DU_REPO
git add 'nom du fichier' pour que git suis le fichier
```

## rediger un commit

```
Titre du commit

Description de notre commit avec des informations sur l'évolution du projec
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "titre du commit"
git push origin main
```