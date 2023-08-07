# Documentation du Tuto GitHub avec Git

## Initialisation du dépot

'''bash
git init
git remote add origin SSh_REPO
'''

## Reediger un commit
'''
Titre du commit

Description de notre commit avec des informations sur l'évolution du projet
'''
## Envoyer un commit à distance

"""bash
git add .
git commit -m "Titre du commit"
git push origin main
"""

## Creation d'une branche
"""bash
git checkout -b NOM_BRANCHE

"""

Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt distant, puis créer une pull request pour demander une revue de code.