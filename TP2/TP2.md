# TP2 : Utilisation courante de Docker

## Partie commune : Stack Web

### Packaging de l'app Web

🌞 docker-compose.yml

Tu as juste à te rendre dans le dossier **Part I** et taper ***docker compose up*** et l'app se lance.

## Partie 2 : Dév  packaging et environnement de dév local

Pour lancer la calculatrice :
- Se rendre au dépôt git https://github.com/Solarfresh33/TP2-DEV
- le cloner
- se rendre dans le dossier
- exécuter la commande **docker compose -f docker-composer.yml up**
- Lancer un nouveau terminal, se rendre dans le dossier à nouveau
- lancer le client avec la commande **python3 ./bs_client.py**
- rentrer le port 13337
- et voilà ! Les logs apparaîtrons sur le terminal servant de serveur.

![C pas hyper dur en vrai](itsnothard.png)
