# Projet CV avec Next.js et Docker
## Phase de développement
1. Clonez le repository :
    git clone https://github.com/MaherZAR/maher_portfolio.git
    cd maher_portfolio
    ou unziper le dossier déposé

3. Construction de l'Image Docker : docker build -t maher_portfolio .
4. Lancement du Conteneur Docker : docker run -p 3000:3000 maher_portfolio

5. Développement dans le Conteneur :
   Ouvrir [http://localhost:3000](http://localhost:3000) avec votre navigateur pour voir le résultat.
  Vous pouvez éditer la page en modifiant `pages/index.js`. La page se met à jour automatiquement au fur et à mesure que vous modifiez le fichier.
7. Arrêt du Conteneur :
  Lorsque vous avez terminé, vous pouvez quitter le conteneur en tapant exit. Le conteneur sera automatiquement supprimé.
9. Autres Commandes Utiles:
   Pour lister tous les conteneurs en cours d'exécution : docker ps
   Pour lister tous les conteneurs (y compris ceux arrêtés) : docker ps -a
   Pour arrêter un conteneur en cours d'exécution : docker stop <ID_DU_CONTENEUR>
   Notes Supplémentaires:
   Assurez-vous que le port nécessaire pour le développement est exposé dans le Dockerfile.
   Les configurations spécifiques au développement peuvent être ajustées dans le Dockerfile selon les besoins.
