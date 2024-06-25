

|| [prerequisites](#prerequisites) ||
[Deployment](#deployment) ||
[Authors](#authors) ||

# containerization-devenv-odoo

Ce projet utilise Docker Compose pour créer et gérer un environnement local constituer de deux conteneurs `eazy-odoo-15` et `eazy-db-15` génerer a base d'images `odoo:15` et `postgres:15 `puis fourni un script bash pour gérer l'aplication.
## Technologies

**Docker :** `Docker compose`


## Features


- Crée des conteneurs docker et les lie grace a un fonctionnalite docker appelé `docker compose` 
- Une sript bash qui permet de choisir l'action à faire sur l'application lancer par notre docker compose qui seront le `build`, le `lancement` ou la `supression` de l'application.
## prerequisites

- **Docker :** installer docker sur votre machine sur windows en suivant le lien https://docs.docker.com/desktop/install/windows-install/ et sur un syteme linux suivre https://docs.docker.com/desktop/install/linux-install/.

Une fois Docker installé, vous pouvez commencer à l'utiliser pour exécuter des images et des conteneurs Docker. Vous pouvez trouver plus d'informations sur l'utilisation de Docker sur le site Web de Docker : https://docs.docker.com/.
## Installation


\
In your command prompt download the repo with the commands:
```bash
  git clone https://github.com/AnselmeG300/containerization-devenv-odoo.git
  cd containerization-devenv-odoo
  code . 
```

    
## Deployment

\
Comme dit tous haut le script bash vous permetra de faire un ensemble d'action par lots notemment de :

1- `build_start `: Permet de mettre a jour notre code a partir de notre repository (pull) ensuite permet de lancer notre application (start)et en fin permet de visualiser les logs de notre application en cours d'exécution (tail).

2- `start `: permet de lancer notre application (start) puis permet de visualiser les logs de notre application en cours d'exécution (tail).

3- `stop `: Permet d'arrêter notre application(down)

4- `purge `: Permet d'arrêter notre application (down) ensuite permet de supprimer nos volumes (delete)

pour ce faire il vous faudra ecrire dans votre terminal :

- Rendre exécutable notre script avec 
```bash
    chmod 777 run.sh
```
- Lancer notre script avec 
```bash
    chmod 777 run.sh
```
## Authors

- [@AnselmeG300](https://github.com/AnselmeG300/terraform-cloud.git)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

